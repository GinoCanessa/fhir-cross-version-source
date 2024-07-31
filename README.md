# Cross-Version Working Area

This repository is a working area for the Cross-Version Extensions project.  The goal of this repo is to serve as a location for temporary artifacts, documentation, and questions while working on Cross-Version Extensions.

Once the extensions are completed, relevant content will have new homes and this repo will be archived.

## Goals

This work is tied up with a few concerns that cannot be easily separated. The primary desired outputs are:
* `StructureDefinition` extensions for cross-version element use.
* `ValueSet` definitions based on differentials between versions to allow for binding in extensions.

The cross-version extensions are intended to **only** represent data that **cannot** be represented in a given FHIR version. For example, the cross-version extensions to use elements from R5 in R4 cannot be allowed to contain any data that is already present in R4.

In order to generate these extensions, we depend on some sources of truth which we are also iterating on:
* Core specifications
  * While these cannot be changed, we iterate on code to normalize and compare them.
* Artifacts in [fhir-cross-version](https://github.com/HL7/fhir-cross-version)
  * `ConceptMap` resources for mapping value sets used as codes (see [input/codes](https://github.com/HL7/fhir-cross-version/tree/main/input/codes))
    * The existing versions of these are based on element paths, which result in duplicates for elements that are bound to the same value sets.
    * As pre-processing we reconcile these based on the URL into a single version.  We do keep the original URLs so that we can reconstitute the original maps if desired.
  * `ConceptMap` resources for mapping types (see [input/types](https://github.com/HL7/fhir-cross-version/tree/main/input/types))
    * These are concerned with renaming types and adding/removing types between versions.
  * `ConceptMap` resources for mapping resources (see [input/resources](https://github.com/HL7/fhir-cross-version/tree/main/input/resources))
    * These are concerned with renaming resources and adding/removing types between versions.
  * `ConceptMap` resources for mapping renamed elements (see [input/elements](https://github.com/HL7/fhir-cross-version/tree/main/input/elements))
  * Per version `FML` files used to map structures (e.g., see [input/R5toR4](https://github.com/HL7/fhir-cross-version/tree/main/input/R5toR4))
    * These files are a mix of generated and hand-maintained content.  Brian Postlethwaite has been working on corrections based on this tooling.
* Manual primitive mappings
  * The primitive mapping decisions are quite varied across versions. It was simpler to hand-maintain a complete set for now, though we could push these back into the correct files of the `fhir-cross-version` repo.

## Process Overview

A high-level overview of the current process is as follows:
1. Execution begins with a `source` and `target` version for comparison (e.g., comparing R5 to R4).
    * Note that this is *directional* - having additional types is cause for an extension in one direction, but not the other.
2. Both the `source` and `target` versions are loaded into memory.
    * This is based on the `.core` and `.expansions` packages.
3. Existing `fhir-cross-version` content is loaded, if possible.
    * Content is based on the source-target version pairing, so content may or may not exist.
    * `ConceptMap` resources related to `codes` are loaded (elements with code bindings).
      * These are reconciled into a single `ConceptMap` per `ValueSet` instead of per element.
    * `ConceptMap` resources related to `types` are loaded (e.g., renamed types).
    * `ConceptMap` resources related to `resources` are loaded (e.g., renamed resources).
    * `ConceptMap` resources related to `elements` are loaded (e.g., renamed elements).
      * These are reconciled into a `ConceptMap` per resource instead of a single map for the version.
    * `FML` files related to mapping structures are loaded.
      * If `FML` files are loaded, they are reconciled with the per-resource `element` maps for use later in comparison.
4. `ValueSet` resources are compared between the two versions.
    * The list of value sets compared is based on the binding-strength as referenced in the specification.
      * Additional value sets may be added based on changed binding-strength in the `target` specification.
      * Value sets listed as untestable are excluded (e.g., UCUM, MIME, etc.)
    * The comparison takes into account existing `ConceptMap` resources and performs comparisons based on `system` and `code` values.
      * It also re-aligns mappings based on the *number* of mappings available (e.g., if a single code is mapped multiple times, the code relationship now reflects that).
    * The comparisons result in a ValueSet comparison structure that enumerates the set of all changes.
5. Primitive types (defined in `StructureDefinitions`) are compared.
    * This process makes use of the hand-maintained primitive mappings for allowed changes based on what happens in various versions.
    * The comparisons result in a Primitive type comparison structure that enumerates the set of all changes.
6. Data types (a.k.a. Complex Types - defined in `StructureDefinitions`) are compared.
    * This process makes use of the primitive comparison results in order to understand changes based on those (e.g., the relationship of moving an element from `integer` to `integer64`)
    * This process makes use of the value set comparison results to understand changes based on those (e.g., what is the difference for two elements bound to the same ValueSet across versions)
    * This process makes use of the internal `ConceptMap` resources to compare types that have been renamed (consolidated `types`, `elements`, and `FML`).
    * This process compares trees of elements and their types (see: [Comparing Elements](#comparing-elements))
    * The comparisons result in a Complex Type comparison structures that enumerates the set of all changes.
7. Resources (defined in `StructureDefinitions`) are compared.
    * This process makes use of the primitive comparison results in order to understand changes based on those (e.g., the relationship of moving an element from `integer` to `integer64`)
    * This process makes use of the complex type comparison results in order to understand changes based on those (e.g., what is the difference for two elements of type `Annotation` across versions)
    * This process makes use of the value set comparison results to understand changes based on those (e.g., what is the difference for two elements bound to the same ValueSet across versions)
    * This process makes use of the internal `ConceptMap` resources to compare resources that have been renamed (consolidated `resources`, `elements`, and `FML`).
    * This process compares trees of elements and their types (see: [Comparing Elements](#comparing-elements))
    * The comparisons result in a Resource comparison structures that enumerates the set of all changes.
8. The completed comparisons are used to generate the artifacts in this repo:
    * Overview markdown files (for information while making this - can decide if they live long-term or not)
    * `ConceptMap` resources for ValueSets
    * `ConceptMap` resources for types
    * `ConceptMap` resources for each complex type and resource for their elements
    * TODO: generate updated `StructureMap` or `FML` files.
    * Differential `ValueSet` resources for use in extensions (see: [Generating Differential ValueSets](#generating-differential-valuesets))
    * `StructureDefinition` resources for each desired extension (see: [Generating Extensions](#generating-extensions))

### Comparing Elements

1. Check for the source being optional and the target being mandatory (`min` changes from 0 to not 0)
2. Check for the source allowing fewer values than the target (`max` changes to a lower value)
3. Check for the source being a scalar and the target being an array (`max` changes from 1 to not 1)
4. Check for the source being an array and the garget being a scalar (`max` changes from not 1 to 1)
5. Check for the source allowing more values than the target (`max` changes to a higher value)
6. Check for binding changes
    * Increase in binding strength
    * Decrease in binding strength
    * Change in binding value set
    * Change in the contents of a bound value set
      * Comparison details depend on type of element being bound (e.g., a `code` only checks the value set codes while `coding` checks systems and codes).
7. Perform type comparisons for each matching type
    * Promote relationships based on known comparison results (e.g., primitives)
    * Check for differences in type `profile` (can be equal, additive, subtractive, or just different)
    * Check for differences in type `targetProfile` (can be equal, additive, subtractive, or just different)
8. Perform total-type comparison (e.g., types added, types removed, etc.) and promote changes from individual type comparisons.

### Generating Differential ValueSets

For a single version pair, this is fairly straightforward once the comparisons are complete - the differential is based off of the set of codes that do not have mapped or discovered equivalent values.

If we need to expand this to cover multiple version comparisons, we will need to build the individual differentials and then comparison-merge them.  Further discussion is below.

### Generating Extensions

1. Iterate over the structure comparisons based on presence in the `source` (same for data types and resources)
2. Check to see if the structure does not have a viable representation in the `target`
    * If so, generate an extension representing the entire structure and stop processing it.
3. Iterate over the elements in the structure
    1. If the element has a target, determine if it needs an extension (e.g., new type, changed binding, etc.)
    2. If the element has no target, generate an extension for the element.
    3. Track elements without targets so that we only generate extensions for the path 'closest' to the root for new structure trees.

When actually building the definition of an extension, extract the type differentials (based on types, profiles, target profiles, bindings, etc.) to only include information that cannot be stated in the `target`.

## Current Questions and Discussions

Note that discussion is generally on the [FHIR Cross-Version Issues](https://chat.fhir.org/#narrow/stream/426854-FHIR-cross-version-issues) Zulip stream.

### Extensions for `Resource`-type Elements

#### Question

[Zulip link](https://chat.fhir.org/#narrow/stream/426854-FHIR-cross-version-issues/topic/XVer.20Extension.20Generation.3A.20Resource.20elements)

This questions is about elements that are type Resource (e.g., [R5 Bundle.issues](https://hl7.org/fhir/bundle-definitions.html#Bundle.issues)).

If it is a resource type that does not exist in R4, we could directly launch into the extensions for the type. This feels like bad practice to me, since we also want to represent resources that do exist.

I am thinking about making the extension be a `Reference` type and documenting that the resource must be contained. Thoughts?

#### Current Status

+1 for this process


### ValueSet structure

#### Question

[Zulip link](https://chat.fhir.org/#narrow/stream/426854-FHIR-cross-version-issues/topic/XVer.20Extension.20Generation.3A.20ValueSet.20questions)

This question is about what artifacts we generate when we know we need a differential ValueSet (e.g., required binding that exists in both versions and has un-mappable values, etc.).  The existing pattern (and what I started with) was generating both a CodeSystem and a ValueSet in that situation.  When I was walking through content though, I realized that would break either: canonical resolution (i.e., defining another CodeSystem with the same URL), actual values in bindings (e.g., anything that needs a system+code), etc..  I am wondering if we can lean on the `version` elements within a ValueSet to bypass this.  An example can be found [here](https://github.com/GinoCanessa/fhir-cross-version-source/blob/main/R5_R4/xver/ValueSet-R5-R4-encounter-status.json), with the key being that it directly references the R5 version of the CodeSystem for the ValueSet.

```json
{
  "resourceType": "ValueSet",
  "id": "R5-R4-encounter-status",
  "url": "http://hl7.org/fhir/uv/xver/ValueSet/R5-R4-encounter-status",
  "version": "1.0.0",
  "name": "EncounterStatus",
  "title": "Encounter Status",
  "status": "draft",
  "experimental": true,
  "date": "2024-07-25T15:56:51.5309582-05:00",
  "description": "Cross-version difference of Current state of the encounter.",
  "purpose": "R5 http://hl7.org/fhir/ValueSet/encounter-status maps as RelatedTo to R4 http://hl7.org/fhir/ValueSet/encounter-status.",
  "compose": {
    "include": [
      {
        "system": "http://hl7.org/fhir/encounter-status",
        "version": "5.0.0",
        "concept": [
          {
            "code": "discontinued",
            "display": "Discontinued"
          }
        ]
      }
    ]
  },
  "expansion": {
    "contains": [
      {
        "extension": [
          {
            "url": "http://hl7.org/fhir/uv/xver/StructureDefinition/cross-version-message",
            "valueString": "R5 `discontinued` does not appear in the target and has no mapping for http://hl7.org/fhir/ValueSet/encounter-status."
          }
        ],
        "system": "http://hl7.org/fhir/encounter-status",
        "version": "5.0.0",
        "code": "discontinued",
        "display": "Discontinued"
      }
    ]
  }
}
```

Does that seem legal and like it would generally work?

#### Current Status

+1 for this process


### Backbone Element Depth

#### Question

[Zulip link](https://chat.fhir.org/#narrow/stream/426854-FHIR-cross-version-issues/topic/XVer.20Extension.20Generation.3A.20Backbone.20element.20depth)


This question is about "how deep do extension definitions go".  For example, assume we have a [FHIR R4 Account](https://hl7.org/fhir/R4/account.html) and want to use elements from the [FHIR R5 Account](https://hl7.org/fhir/account.html).

In R5, the `Account.balance` backbone element was added, with a few elements beneath it - for simplicity, I will be using `Account.balance.amount`.

For the extensions, do we generate:
1. A complex extension for [Account.balance](https://github.com/GinoCanessa/fhir-cross-version-source/blob/main/R5_R4/xver/StructureDefinition-Account.balance.json) that can be used on `R4:Account`,
2. A simple extension for [Account.balance.amount](https://github.com/GinoCanessa/fhir-cross-version-source/blob/main/R5_R4/xver/StructureDefinition-Account.balance.amount.json) that can be used on `R4:Account` or `extension:Account.balance`

In case 1), extensions would be generated based on the 'lowest' mapped element and the context would be very explicit.

In case 2), any element missing would be generated and the context would include both the 'lowest' mapped element and the parent in the tree.

As another example, consider a new resource (e.g., R5 `SubscriptionTopic`):
1. A complex extension for [SubscriptionTopic](https://github.com/GinoCanessa/fhir-cross-version-source/blob/main/R5_R4/xver/StructureDefinition-SubscriptionTopic.json) that can be used on `R4:Basic`,
2. Simple extensions for each element in `SubscriptionTopic` (e.g., [SubscriptionTopic.derivedFrom](https://github.com/GinoCanessa/fhir-cross-version-source/blob/main/R5_R4/xver/StructureDefinition-SubscriptionTopic.derivedFrom.json)).

#### Current Status

* Good discussion with Chris Moesel
* Current strategy feels like it should be 'closest to root' - have an exception discussion I will put in a new question set.

### BackboneElements, new types and arrays

#### Question

Based on the discussion about general `BackboneElement` process, I am currently trying to sort out a set of edge cases around moving from an array of a single type to/from a backbone and nested value.  For example, I will use:

| FHIR | Path | Type | Cardinality |
| --- | --- | --- | --- |
| R4 | `AdverseEvent.contributor` | `Reference(Practitioner, PractitionerRole, Device)` | `[0..*]` |
| R5 | `AdverseEvent.participant.actor` | `Reference(Practitioner, PractitionerRole, Device, Organization, CareTeam, Patient, RelatedPerson, ResearchSubject)` | `[0..*][1..1]` |

There exists some mapping information that we know the two are related and should contain the same content when possible.  Specifically, the R5 version includes more allowed types.

Now, the fun really starts because in R5 there is a new backbone element of `AdverseEvent.participant` which does not exist in R4.

So we have two sets of 'things' someone may want to express from R5 in R4:
1. A simple additional `AdverseEvent.contributor` that is a reference to an `Organization`.
2. An entire R5 `AdverseEvent.participant`.

The question is twofold:
* Do we _want_ to allow expression of 1), 2), or both in R4?
  * The simple element change (1) is listed in a map.
  * We do not know if there are requirements in any of the rest of the `AdverseEvent` structure that would be required to *use* one of the new reference types.
* Where do we want the extension context to live?
  * If we are using `AdverseEvent.participant.contributor`, do we want a null value in `AdverseEvent.contributor` with the extension, or do we move that up to `AdverseEvent`?
  * If we only allow the backbone-grouped `AdverseEvent.participant`, same question: since we know it maps from `contributor` in R4 do we put it there or `AdverseEvent`?

#### Current Status

New


## Resolved Questions and Discussions





------


# Older Content

Sorting out what to keep, what to reconcile, and what to discard...

### Issues to discuss
* When array elements move into a deeper level (e.g., an element converted to backbone and is now a property), I *think* the desired behavior is to not define the CVE for the element that got moved and then define the rest of the properties with CVEs based on that array.
    * `Practitioner.communication` in R4 moved to `Practitioner.communication.language` in R5
    * R5 *also* added a boolean for `preferred`
    * In R4, it is required that we use `Practitioner.communication`, which means that the additional elements attached to the Backbone in R5 (`preferred`) need to attach to repetitions of the R4 `Practitioner.communication`.
    * It will be complicated to generate, but if we just lump the R5 elements together, we have 'lost' data that an R4 client will not be able to access.


### Extension Definitions and FHIR Versions
* When defining, the extension URL is rooted in the *first* FHIR version with a compatible definition.  For example, using a DSTU2 instance, let us consider:
    * An element that was:
        * Added in STU3 (R3)
        * Unchanged in R4
        * Modified in R7
    * Unique extension definitions must exist for the version of the element in
        * R3 (added)
            * `http://hl7.org/fhir/3.0/StructureDefinition/extension-[resource]-[element-path]`
        * R5 (modified)
            * `http://hl7.org/fhir/5.0/StructureDefinition/extension-[resource]-[element-path]`
    * So I am working in R2 and want to:
        * Add the R3 element to my resource:
            * `http://hl7.org/fhir/3.0/StructureDefinition/extension-[resource]-[element-path]`
        * Add the R4 element to my resource:
            * `http://hl7.org/fhir/3.0/StructureDefinition/extension-[resource]-[element-path]`
        * Add the R5 element to my resource:
            * `http://hl7.org/fhir/5.0/StructureDefinition/extension-[resource]-[element-path]`

    * Bas Proposal is to change this to:
        * Add the R3 element to my resource:
            * `http://hl7.org/fhir/3.0/StructureDefinition/extension-[resource]-[element-path]`
        * Add the R4 element to my resource:
            * `http://hl7.org/fhir/4.0/StructureDefinition/extension-[resource]-[element-path]`
        * Add the R5 element to my resource:
            * `http://hl7.org/fhir/5.0/StructureDefinition/extension-[resource]-[element-path]`

    * Grahame Proposal is to change this to:
        * Backbone elements are un-versioned, only actual value elements are versioned
        * Add the R3 element to my resource:
            * `http://hl7.org/fhir/StructureDefinition/extension-[resource]-[element-path]`
        * Add the R4 element to my resource:
            * `http://hl7.org/fhir/4.0/StructureDefinition/extension-[resource]-[element-path]`
        * Add the R5 element to my resource:
            * `http://hl7.org/fhir/5.0/StructureDefinition/extension-[resource]-[element-path]`


## Notes and Questions from 2024 May WGM: 

* Question: Generate packages by target resource (e.g., R5 SubscriptionTopic)
* Currently working on reconciling the sources of truth:
    * Comparison of element definitions plus…
	* ValueSet concept maps
		* ConceptMaps in fhir-cross-version/input/codes, by binding element
		* Reconciling multiple instances into a single ValueSet mapping
		* (WIP) detecting manual mappings in FML from fhir-cross-version/input/R#toR#
	* Type mappings
		* ConceptMaps in fhir-cross-version/input/types, by version change
		* FML in fhir-cross-version/input/R#toR#/primitives.fml (manually extracted once since it doesn't change)
		* Manual serialization info from fhir/versions.html
	* Element changes
		* Renames from ConceptMaps in fhir-cross-version/input/elements, by version change
		* (WIP) FML files in fhir-cross-version/R#toR#, by resource/datatype
* Generating
	* Markdown comparisons (per version change: summary, per ValueSet, per type, per resource)
	* Concept Maps (per version change: per ValueSet, per type, per resource)
	* Structure Maps
* Working on UI (aspirational)
	* Process ValueSet
		* Set source and target (create maps from one VS to two, etc.)
		* Review concepts, set mapping info (target/s, relationship, etc.)
			* Relevant concept info (system, code, display)
			* Relevant concept map entries
			* Elements that use the value sets (where is this used)
			* Update element relationships based on changes
	* Process Structure (Complex Type, Resource)
		* Set source and target (map between changed structure names, split structures, etc.)
		* Review elements, set mapping info (target/s, relationship, etc.)
			* Relevant element info (cardinality, types, targets, descriptions)
			* Relevant concept map entries
			* Relevant FML lines
		* Nest into ValueSet comparison
		* Highlight Yes/No: Will this create an extension
			* Preview the extension information
	* Will NOT allow FML changes in first pass
	* Update definitions while changes are made (avoid re-running the entire comparison)
* Validate agreement on when and what the definitions have
	* When do we create a cross-version extension:
		* An element that has an *unrepresentable* change between two versions (either direction)
		* Not when
			* An element has the same type(s), target type(s), cardinality, and a compatible binding
			* Target is consistent but renamed
			* Multiple elements merge into a single target (e.g., CodeableConcept + Reference => CodeableReference)
			* Target is a narrower type definition (e.g., removed type, removed target, reduced cardinality)
			* Target has a wider set of concepts and is *not* a required binding
			    * Depends on where the code system comes from.  Using a code from a newer version would implicitly reference the newer code system, which may mean a different definition of the concept.
		* Specific causes for defining an extension
			* Target has higher cardinality (e.g., moving from scalar to array)
			* Target has one or more additional types (e.g., added to a choice type)
			* Target has one or more additional target profiles (e.g., added Reference(Device))
			* Target has a wider required binding (e.g., additional status codes)
			* Target has a wider binding strength (e.g., required -> extensible)
			* Target has the same binding with an expanded set of codes (e.g., new codes have been added)
	* What does the definition look like
		* TLDR: is each extension a representation of the target element or a differential between the current representation and the target?
		* Types
			* Does the extension include all types of the target, or only new types?
			* Does the extension include all target profiles, or only new targets?
		* Bindings
			* Do we use the target ValueSet or generate a differential ValueSet (would be per-version)
		* Allowed contexts
			* Do we try to determine the 'correct' contexts for the extensions, or just use Element?
		* Descriptions
			* What should the documentation template look like?  E.g., 'A cross-version extension to allow FHIR R4 Encounter resources to use the R5 Encounter.classStatus element…'
	* Can we generate them in packages per-target resource?  E.g., hl7.fhir.uv.cross-version.r5.encounter.r4 to contain the R4 extension definitions for the R5 Encounter resource.
	* What is our policy on extensions attached to the target?
		* Can we access extension definitions across versions (e.g., can an R4 instance use an R5 extension)
		* How do we define extensions (e.g., in the extensions pack) so that we have correct contexts when:
			* An element is renamed (context would not be a valid path in some versions)
			* An element is added (does context allow for Extension so that it can attach to cross-version extensions)
    * General questions about terminology access
        * Do we want to make core CodeSystems/ValueSets available in earlier versions too?  E.g., should cross-version extensions include those value sets (case: extension is defined with a binding to R5 and we want to use that extension in another version)

