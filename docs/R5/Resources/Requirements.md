Comparison of 
Generated at Monday, April 14, 2025 6:17:46 PM

### Requirements

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | Requirements |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Requirements` |
| Version | 5.0.0 |
| Description | The Requirements resource is used to describe an actor - a human or an application that plays a role in data exchange, and that may have obligations associated with the role the actor plays. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2374` |
| Database Snapshot Count | `43` |
| Database Differential Count | `32` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Requirements` | `Requirements` | `Requirements` | Requirements | A set of requirements - features of systems that are necessary | 0..* | Requirements |  |  |
| `Requirements.actor` | `Requirements.actor` | `actor` | Requirements.actor | Actor for these requirements | 0..* | canonical(http://hl7.org/fhir/StructureDefinition/ActorDefinition) |  |  |
| `Requirements.contact` | `Requirements.contact` | `contact` | Requirements.contact | Contact details for the publisher | 0..* | ContactDetail |  |  |
| `Requirements.contained` | `Requirements.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Requirements.copyright` | `Requirements.copyright` | `copyright` | Requirements.copyright | Use and/or publishing restrictions | 0..1 | markdown |  |  |
| `Requirements.copyrightLabel` | `Requirements.copyrightLabel` | `copyrightLabel` | Requirements.copyrightLabel | Copyright holder and year(s) | 0..1 | string |  |  |
| `Requirements.date` | `Requirements.date` | `date` | Requirements.date | Date last changed | 0..1 | dateTime |  |  |
| `Requirements.derivedFrom` | `Requirements.derivedFrom` | `derivedFrom` | Requirements.derivedFrom | Other set of Requirements this builds on | 0..* | canonical(http://hl7.org/fhir/StructureDefinition/Requirements) |  |  |
| `Requirements.description` | `Requirements.description` | `description` | Requirements.description | Natural language description of the requirements | 0..1 | markdown |  |  |
| `Requirements.experimental` | `Requirements.experimental` | `experimental` | Requirements.experimental | For testing purposes, not real usage | 0..1 | boolean |  |  |
| `Requirements.extension` | `Requirements.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Requirements.id` | `Requirements.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Requirements.identifier` | `Requirements.identifier` | `identifier` | Requirements.identifier | Additional identifier for the Requirements (business identifier) | 0..* | Identifier |  |  |
| `Requirements.implicitRules` | `Requirements.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Requirements.jurisdiction` | `Requirements.jurisdiction` | `jurisdiction` | Requirements.jurisdiction | Intended jurisdiction for Requirements (if applicable) | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/jurisdiction` |
| `Requirements.language` | `Requirements.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `Requirements.meta` | `Requirements.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Requirements.modifierExtension` | `Requirements.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Requirements.name` | `Requirements.name` | `name` | Requirements.name | Name for this Requirements (computer friendly) | 0..1 | string |  |  |
| `Requirements.publisher` | `Requirements.publisher` | `publisher` | Requirements.publisher | Name of the publisher/steward (organization or individual) | 0..1 | string |  |  |
| `Requirements.purpose` | `Requirements.purpose` | `purpose` | Requirements.purpose | Why this Requirements is defined | 0..1 | markdown |  |  |
| `Requirements.reference` | `Requirements.reference` | `reference` | Requirements.reference | External artifact (rule/document etc. that) created this set of requirements | 0..* | url |  |  |
| `Requirements.statement` | `Requirements.statement` | `statement` | Requirements.statement | Actual statement as markdown | 0..* | BackboneElement |  |  |
| `Requirements.statement.conditionality` | `Requirements.statement.conditionality` | `conditionality` | Requirements.statement.conditionality | Set to true if requirements statement is conditional | 0..1 | boolean |  |  |
| `Requirements.statement.conformance` | `Requirements.statement.conformance` | `conformance` | Requirements.statement.conformance | SHALL \| SHOULD \| MAY \| SHOULD-NOT | 0..* | code | `Required` | `http://hl7.org/fhir/ValueSet/conformance-expectation|5.0.0` |
| `Requirements.statement.derivedFrom` | `Requirements.statement.derivedFrom` | `derivedFrom` | Requirements.statement.derivedFrom | Another statement this clarifies/restricts ([url#]key) | 0..1 | string |  |  |
| `Requirements.statement.extension` | `Requirements.statement.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Requirements.statement.id` | `Requirements.statement.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Requirements.statement.key` | `Requirements.statement.key` | `key` | Requirements.statement.key | Key that identifies this statement | 1..1 | id |  |  |
| `Requirements.statement.label` | `Requirements.statement.label` | `label` | Requirements.statement.label | Short Human label for this statement | 0..1 | string |  |  |
| `Requirements.statement.modifierExtension` | `Requirements.statement.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Requirements.statement.parent` | `Requirements.statement.parent` | `parent` | Requirements.statement.parent | A larger requirement that this requirement helps to refine and enable | 0..1 | string |  |  |
| `Requirements.statement.reference` | `Requirements.statement.reference` | `reference` | Requirements.statement.reference | External artifact (rule/document etc. that) created this requirement | 0..* | url |  |  |
| `Requirements.statement.requirement` | `Requirements.statement.requirement` | `requirement` | Requirements.statement.requirement | The actual requirement | 1..1 | markdown |  |  |
| `Requirements.statement.satisfiedBy` | `Requirements.statement.satisfiedBy` | `satisfiedBy` | Requirements.statement.satisfiedBy | Design artifact that satisfies this requirement | 0..* | url |  |  |
| `Requirements.statement.source` | `Requirements.statement.source` | `source` | Requirements.statement.source | Who asked for this statement | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/CareTeam), Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/HealthcareService), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `Requirements.status` | `Requirements.status` | `status` | Requirements.status | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status|5.0.0` |
| `Requirements.text` | `Requirements.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `Requirements.title` | `Requirements.title` | `title` | Requirements.title | Name for this Requirements (human friendly) | 0..1 | string |  |  |
| `Requirements.url` | `Requirements.url` | `url` | Requirements.url | Canonical identifier for this Requirements, represented as a URI (globally unique) | 0..1 | uri |  |  |
| `Requirements.useContext` | `Requirements.useContext` | `useContext` | Requirements.useContext | The context that the content is intended to support | 0..* | UsageContext |  |  |
| `Requirements.version` | `Requirements.version` | `version` | Requirements.version | Business version of the Requirements | 0..1 | string |  |  |
| `Requirements.versionAlgorithm[x]` | `Requirements.versionAlgorithm[x]` | `versionAlgorithm[x]` | Requirements.versionAlgorithm[x] | How to compare versions | 0..1 | Coding, string | `Extensible` | `http://hl7.org/fhir/ValueSet/version-algorithm` |
### Empty Projection

This Structure (Resource) resulted in no projection (no mappings to other packages).

