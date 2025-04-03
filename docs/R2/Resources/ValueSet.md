Comparison of 
Generated at Thursday, April 3, 2025 8:18:08 AM

### ValueSet

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | ValueSet |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ValueSet` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for ValueSet Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `135` |
| Database Snapshot Count | `103` |
| Database Differential Count | `62` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ValueSet` | `ValueSet` | `ValueSet` | ValueSet | A set of codes drawn from one or more code systems | 0..* | ValueSet |  |  |
| `ValueSet.codeSystem` | `ValueSet.codeSystem` | `codeSystem` |  | An inline code system, which is part of this value set | 0..1 | BackboneElement |  |  |
| `ValueSet.codeSystem.caseSensitive` | `ValueSet.codeSystem.caseSensitive` | `caseSensitive` |  | If code comparison is case sensitive | 0..1 | boolean |  |  |
| `ValueSet.codeSystem.concept` | `ValueSet.codeSystem.concept` | `concept` |  | Concepts in the code system | 1..* | BackboneElement |  |  |
| `ValueSet.codeSystem.concept.abstract` | `ValueSet.codeSystem.concept.abstract` | `abstract` |  | If this code is not for use as a real concept | 0..1 | boolean |  |  |
| `ValueSet.codeSystem.concept.code` | `ValueSet.codeSystem.concept.code` | `code` |  | Code that identifies concept | 1..1 | code |  |  |
| `ValueSet.codeSystem.concept.concept` | `ValueSet.codeSystem.concept.concept` | `concept` |  | Child Concepts (is-a/contains/categorizes) | 0..* | ValueSet.codeSystem.concept |  |  |
| `ValueSet.codeSystem.concept.definition` | `ValueSet.codeSystem.concept.definition` | `definition` |  | Formal definition | 0..1 | string |  |  |
| `ValueSet.codeSystem.concept.designation` | `ValueSet.codeSystem.concept.designation` | `designation` |  | Additional representations for the concept | 0..* | BackboneElement |  |  |
| `ValueSet.codeSystem.concept.designation.extension` | `ValueSet.codeSystem.concept.designation.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ValueSet.codeSystem.concept.designation.id` | `ValueSet.codeSystem.concept.designation.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `ValueSet.codeSystem.concept.designation.language` | `ValueSet.codeSystem.concept.designation.language` | `language` |  | Human language of the designation | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `ValueSet.codeSystem.concept.designation.modifierExtension` | `ValueSet.codeSystem.concept.designation.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ValueSet.codeSystem.concept.designation.use` | `ValueSet.codeSystem.concept.designation.use` | `use` |  | Details how this designation would be used | 0..1 | Coding | `Extensible` | `http://hl7.org/fhir/ValueSet/designation-use` |
| `ValueSet.codeSystem.concept.designation.value` | `ValueSet.codeSystem.concept.designation.value` | `value` |  | The text value for this designation | 1..1 | string |  |  |
| `ValueSet.codeSystem.concept.display` | `ValueSet.codeSystem.concept.display` | `display` |  | Text to display to the user | 0..1 | string |  |  |
| `ValueSet.codeSystem.concept.extension` | `ValueSet.codeSystem.concept.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ValueSet.codeSystem.concept.id` | `ValueSet.codeSystem.concept.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `ValueSet.codeSystem.concept.modifierExtension` | `ValueSet.codeSystem.concept.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ValueSet.codeSystem.extension` | `ValueSet.codeSystem.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ValueSet.codeSystem.id` | `ValueSet.codeSystem.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `ValueSet.codeSystem.modifierExtension` | `ValueSet.codeSystem.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ValueSet.codeSystem.system` | `ValueSet.codeSystem.system` | `system` |  | URI to identify the code system (e.g. in Coding.system) | 1..1 | uri |  |  |
| `ValueSet.codeSystem.version` | `ValueSet.codeSystem.version` | `version` |  | Version (for use in Coding.version) | 0..1 | string |  |  |
| `ValueSet.compose` | `ValueSet.compose` | `compose` |  | When value set includes codes from elsewhere | 0..1 | BackboneElement |  |  |
| `ValueSet.compose.exclude` | `ValueSet.compose.exclude` | `exclude` |  | Explicitly exclude codes | 0..* | ValueSet.compose.include |  |  |
| `ValueSet.compose.extension` | `ValueSet.compose.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ValueSet.compose.id` | `ValueSet.compose.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `ValueSet.compose.import` | `ValueSet.compose.import` | `import` |  | Import the contents of another value set | 0..* | uri |  |  |
| `ValueSet.compose.include` | `ValueSet.compose.include` | `include` |  | Include one or more codes from a code system | 0..* | BackboneElement |  |  |
| `ValueSet.compose.include.concept` | `ValueSet.compose.include.concept` | `concept` |  | A concept defined in the system | 0..* | BackboneElement |  |  |
| `ValueSet.compose.include.concept.code` | `ValueSet.compose.include.concept.code` | `code` |  | Code or expression from system | 1..1 | code |  |  |
| `ValueSet.compose.include.concept.designation` | `ValueSet.compose.include.concept.designation` | `designation` |  | Additional representations for this valueset | 0..* | ValueSet.codeSystem.concept.designation |  |  |
| `ValueSet.compose.include.concept.display` | `ValueSet.compose.include.concept.display` | `display` |  | Test to display for this code for this value set | 0..1 | string |  |  |
| `ValueSet.compose.include.concept.extension` | `ValueSet.compose.include.concept.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ValueSet.compose.include.concept.id` | `ValueSet.compose.include.concept.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `ValueSet.compose.include.concept.modifierExtension` | `ValueSet.compose.include.concept.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ValueSet.compose.include.extension` | `ValueSet.compose.include.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ValueSet.compose.include.filter` | `ValueSet.compose.include.filter` | `filter` |  | Select codes/concepts by their properties (including relationships) | 0..* | BackboneElement |  |  |
| `ValueSet.compose.include.filter.extension` | `ValueSet.compose.include.filter.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ValueSet.compose.include.filter.id` | `ValueSet.compose.include.filter.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `ValueSet.compose.include.filter.modifierExtension` | `ValueSet.compose.include.filter.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ValueSet.compose.include.filter.op` | `ValueSet.compose.include.filter.op` | `op` |  | = \| is-a \| is-not-a \| regex \| in \| not-in | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/filter-operator` |
| `ValueSet.compose.include.filter.property` | `ValueSet.compose.include.filter.property` | `property` |  | A property defined by the code system | 1..1 | code |  |  |
| `ValueSet.compose.include.filter.value` | `ValueSet.compose.include.filter.value` | `value` |  | Code from the system, or regex criteria | 1..1 | code |  |  |
| `ValueSet.compose.include.id` | `ValueSet.compose.include.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `ValueSet.compose.include.modifierExtension` | `ValueSet.compose.include.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ValueSet.compose.include.system` | `ValueSet.compose.include.system` | `system` |  | The system the codes come from | 1..1 | uri |  |  |
| `ValueSet.compose.include.version` | `ValueSet.compose.include.version` | `version` |  | Specific version of the code system referred to | 0..1 | string |  |  |
| `ValueSet.compose.modifierExtension` | `ValueSet.compose.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ValueSet.contact` | `ValueSet.contact` | `contact` |  | Contact details of the publisher | 0..* | BackboneElement |  |  |
| `ValueSet.contact.extension` | `ValueSet.contact.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ValueSet.contact.id` | `ValueSet.contact.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `ValueSet.contact.modifierExtension` | `ValueSet.contact.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ValueSet.contact.name` | `ValueSet.contact.name` | `name` |  | Name of an individual to contact | 0..1 | string |  |  |
| `ValueSet.contact.telecom` | `ValueSet.contact.telecom` | `telecom` |  | Contact details for individual or publisher | 0..* | ContactPoint |  |  |
| `ValueSet.contained` | `ValueSet.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `ValueSet.copyright` | `ValueSet.copyright` | `copyright` |  | Use and/or publishing restrictions | 0..1 | string |  |  |
| `ValueSet.date` | `ValueSet.date` | `date` |  | Date for given status | 0..1 | dateTime |  |  |
| `ValueSet.description` | `ValueSet.description` | `description` |  | Human language description of the value set | 0..1 | string |  |  |
| `ValueSet.expansion` | `ValueSet.expansion` | `expansion` |  | Used when the value set is "expanded" | 0..1 | BackboneElement |  |  |
| `ValueSet.expansion.contains` | `ValueSet.expansion.contains` | `contains` |  | Codes in the value set | 0..* | BackboneElement |  |  |
| `ValueSet.expansion.contains.abstract` | `ValueSet.expansion.contains.abstract` | `abstract` |  | If user cannot select this entry | 0..1 | boolean |  |  |
| `ValueSet.expansion.contains.code` | `ValueSet.expansion.contains.code` | `code` |  | Code - if blank, this is not a selectable code | 0..1 | code |  |  |
| `ValueSet.expansion.contains.contains` | `ValueSet.expansion.contains.contains` | `contains` |  | Codes contained under this entry | 0..* | ValueSet.expansion.contains |  |  |
| `ValueSet.expansion.contains.display` | `ValueSet.expansion.contains.display` | `display` |  | User display for the concept | 0..1 | string |  |  |
| `ValueSet.expansion.contains.extension` | `ValueSet.expansion.contains.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ValueSet.expansion.contains.id` | `ValueSet.expansion.contains.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `ValueSet.expansion.contains.modifierExtension` | `ValueSet.expansion.contains.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ValueSet.expansion.contains.system` | `ValueSet.expansion.contains.system` | `system` |  | System value for the code | 0..1 | uri |  |  |
| `ValueSet.expansion.contains.version` | `ValueSet.expansion.contains.version` | `version` |  | Version in which this code/display is defined | 0..1 | string |  |  |
| `ValueSet.expansion.extension` | `ValueSet.expansion.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ValueSet.expansion.id` | `ValueSet.expansion.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `ValueSet.expansion.identifier` | `ValueSet.expansion.identifier` | `identifier` |  | Uniquely identifies this expansion | 1..1 | uri |  |  |
| `ValueSet.expansion.modifierExtension` | `ValueSet.expansion.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ValueSet.expansion.offset` | `ValueSet.expansion.offset` | `offset` |  | Offset at which this resource starts | 0..1 | integer |  |  |
| `ValueSet.expansion.parameter` | `ValueSet.expansion.parameter` | `parameter` |  | Parameter that controlled the expansion process | 0..* | BackboneElement |  |  |
| `ValueSet.expansion.parameter.extension` | `ValueSet.expansion.parameter.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ValueSet.expansion.parameter.id` | `ValueSet.expansion.parameter.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `ValueSet.expansion.parameter.modifierExtension` | `ValueSet.expansion.parameter.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ValueSet.expansion.parameter.name` | `ValueSet.expansion.parameter.name` | `name` |  | Name as assigned by the server | 1..1 | string |  |  |
| `ValueSet.expansion.parameter.value[x]` | `ValueSet.expansion.parameter.value[x]` | `value[x]` |  | Value of the named parameter | 0..1 | boolean, code, decimal, integer, string, uri |  |  |
| `ValueSet.expansion.timestamp` | `ValueSet.expansion.timestamp` | `timestamp` |  | Time ValueSet expansion happened | 1..1 | dateTime |  |  |
| `ValueSet.expansion.total` | `ValueSet.expansion.total` | `total` |  | Total number of codes in the expansion | 0..1 | integer |  |  |
| `ValueSet.experimental` | `ValueSet.experimental` | `experimental` |  | If for testing purposes, not real usage | 0..1 | boolean |  |  |
| `ValueSet.extensible` | `ValueSet.extensible` | `extensible` |  | Whether this is intended to be used with an extensible binding | 0..1 | boolean |  |  |
| `ValueSet.extension` | `ValueSet.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ValueSet.id` | `ValueSet.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `ValueSet.identifier` | `ValueSet.identifier` | `identifier` |  | Additional identifier for the value set (e.g. HL7 v2 / CDA) | 0..1 | Identifier |  |  |
| `ValueSet.immutable` | `ValueSet.immutable` | `immutable` |  | Indicates whether or not any change to the content logical definition may occur | 0..1 | boolean |  |  |
| `ValueSet.implicitRules` | `ValueSet.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `ValueSet.language` | `ValueSet.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `ValueSet.lockedDate` | `ValueSet.lockedDate` | `lockedDate` |  | Fixed date for all referenced code systems and value sets | 0..1 | date |  |  |
| `ValueSet.meta` | `ValueSet.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `ValueSet.modifierExtension` | `ValueSet.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ValueSet.name` | `ValueSet.name` | `name` |  | Informal name for this value set | 0..1 | string |  |  |
| `ValueSet.publisher` | `ValueSet.publisher` | `publisher` |  | Name of the publisher (organization or individual) | 0..1 | string |  |  |
| `ValueSet.requirements` | `ValueSet.requirements` | `requirements` |  | Why needed | 0..1 | string |  |  |
| `ValueSet.status` | `ValueSet.status` | `status` |  | draft \| active \| retired | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/conformance-resource-status` |
| `ValueSet.text` | `ValueSet.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `ValueSet.url` | `ValueSet.url` | `url` |  | Globally unique logical identifier for  value set | 0..1 | uri |  |  |
| `ValueSet.useContext` | `ValueSet.useContext` | `useContext` |  | Content intends to support these contexts | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/use-context` |
| `ValueSet.version` | `ValueSet.version` | `version` |  | Logical identifier for this version of the value set | 0..1 | string |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ValueSet](/docs/R2/Resources/ValueSet.md)<br/> `http://hl7.org/fhir/StructureDefinition/ValueSet\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `164`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `331`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CodeSystem](/docs/R3/Resources/CodeSystem.md)<br/> `http://hl7.org/fhir/StructureDefinition/CodeSystem\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `433`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `629`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CodeSystem](/docs/R4/Resources/CodeSystem.md)<br/> `http://hl7.org/fhir/StructureDefinition/CodeSystem\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1429`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1430`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CodeSystem](/docs/R4B/Resources/CodeSystem.md)<br/> `http://hl7.org/fhir/StructureDefinition/CodeSystem\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `949`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1178`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CodeSystem](/docs/R5/Resources/CodeSystem.md)<br/> `http://hl7.org/fhir/StructureDefinition/CodeSystem\|5.0.0` 
| [ValueSet](/docs/R2/Resources/ValueSet.md)<br/> `http://hl7.org/fhir/StructureDefinition/ValueSet\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `164`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `331`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ValueSet](/docs/R3/Resources/ValueSet.md)<br/> `http://hl7.org/fhir/StructureDefinition/ValueSet\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `527`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `723`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ValueSet](/docs/R4/Resources/ValueSet.md)<br/> `http://hl7.org/fhir/StructureDefinition/ValueSet\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1641`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1642`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ValueSet](/docs/R4B/Resources/ValueSet.md)<br/> `http://hl7.org/fhir/StructureDefinition/ValueSet\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1057`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1286`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ValueSet](/docs/R5/Resources/ValueSet.md)<br/> `http://hl7.org/fhir/StructureDefinition/ValueSet\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition ValueSet from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 ValueSet| Relationship | [R3 CodeSystem](/docs/R3/Resources/CodeSystem.md)| Relationship | [R4 CodeSystem](/docs/R4/Resources/CodeSystem.md)| Relationship | [R4B CodeSystem](/docs/R4B/Resources/CodeSystem.md)| Relationship | [R5 CodeSystem](/docs/R5/Resources/CodeSystem.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`ValueSet`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(8506)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(8507)| `ValueSet`| | | | | | | 
| **`ValueSet.id`**| _Equivalent_<br/>(8508/8509)| `ValueSet.id`| | | | | | | 
| **`ValueSet.meta`**| _Equivalent_<br/>(8510/8511)| `ValueSet.meta`| | | | | | | 
| **`ValueSet.implicitRules`**| _Equivalent_<br/>(8512/8513)| `ValueSet.implicitRules`| | | | | | | 
| **`ValueSet.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(8514)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(8515)| `ValueSet.language`| | | | | | | 
| **`ValueSet.text`**| _Equivalent_<br/>(8516/8517)| `ValueSet.text`| | | | | | | 
| **`ValueSet.contained`**| _Equivalent_<br/>(8518/8519)| `ValueSet.contained`| | | | | | | 
| **`ValueSet.extension`**| _Equivalent_<br/>(8520/8521)| `ValueSet.extension`| | | | | | | 
| **`ValueSet.modifierExtension`**| →→→→ _Equivalent_ →→→→ <br/>(8522)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(8523)| `ValueSet.modifierExtension`| | | | | | | 
| **`ValueSet.url`**| _Equivalent_<br/>(8524/8525)| `ValueSet.url`| | | | | | | 
| **`ValueSet.identifier`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(8526)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(8527)| `ValueSet.identifier`| | | | | | | 
| **`ValueSet.version`**| _Equivalent_<br/>(8528/8529)| `ValueSet.version`| | | | | | | 
| **`ValueSet.name`**| _Equivalent_<br/>(8530/8531)| `ValueSet.name`| | | | | | | 
| **`ValueSet.status`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(8532)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(8533)| `ValueSet.status`| | | | | | | 
| **`ValueSet.experimental`**| _Equivalent_<br/>(8534/8535)| `ValueSet.experimental`| | | | | | | 
| **`ValueSet.publisher`**| _Equivalent_<br/>(8536/8537)| `ValueSet.publisher`| | | | | | | 
| **`ValueSet.contact`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(8538)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(8539)| `ValueSet.contact`| | | | | | | 
| **`ValueSet.contact.id`**| | | | | | | | | 
| **`ValueSet.contact.extension`**| | | | | | | | | 
| **`ValueSet.contact.modifierExtension`**| | | | | | | | | 
| **`ValueSet.contact.name`**| | | | | | | | | 
| **`ValueSet.contact.telecom`**| | | | | | | | | 
| **`ValueSet.date`**| _Equivalent_<br/>(8545/8546)| `ValueSet.date`| | | | | | | 
| **`ValueSet.lockedDate`**| _Equivalent_<br/>(452/784)| `ValueSet.compose.lockedDate`| | | | | | | 
| **`ValueSet.description`**| _Equivalent_<br/>(8547/8548)| `ValueSet.description`| | | | | | | 
| **`ValueSet.useContext`**| _Equivalent_<br/>(454/786)| `ValueSet.useContext`| | | | | | | 
| **`ValueSet.useContext`**| _Equivalent_<br/>(454/786)| `ValueSet.jurisdiction`| | | | | | | 
| **`ValueSet.immutable`**| _Equivalent_<br/>(8549/8550)| `ValueSet.immutable`| | | | | | | 
| **`ValueSet.requirements`**| _Equivalent_<br/>(453/785)| `ValueSet.purpose`| | | | | | | 
| **`ValueSet.copyright`**| _Equivalent_<br/>(8551/8552)| `ValueSet.copyright`| | | | | | | 
| **`ValueSet.extensible`**| _Equivalent_<br/>(8553/8554)| `ValueSet.extensible`| | | | | | | 
| **`ValueSet.codeSystem`**| | | | | | | | | 
| **`ValueSet.codeSystem.id`**| | | | | | | | | 
| **`ValueSet.codeSystem.extension`**| | | | | | | | | 
| **`ValueSet.codeSystem.modifierExtension`**| →→→→ _Equivalent_ →→→→ <br/>(455)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(8558)| `ValueSet.modifierExtension`| | | | | | | 
| **`ValueSet.codeSystem.system`**| | | | | | | | | 
| **`ValueSet.codeSystem.version`**| | | | | | | | | 
| **`ValueSet.codeSystem.caseSensitive`**| | | | | | | | | 
| **`ValueSet.codeSystem.concept`**| | | | | | | | | 
| **`ValueSet.codeSystem.concept.id`**| | | | | | | | | 
| **`ValueSet.codeSystem.concept.extension`**| | | | | | | | | 
| **`ValueSet.codeSystem.concept.modifierExtension`**| | | | | | | | | 
| **`ValueSet.codeSystem.concept.code`**| | | | | | | | | 
| **`ValueSet.codeSystem.concept.abstract`**| | | | | | | | | 
| **`ValueSet.codeSystem.concept.display`**| | | | | | | | | 
| **`ValueSet.codeSystem.concept.definition`**| | | | | | | | | 
| **`ValueSet.codeSystem.concept.designation`**| | | | | | | | | 
| **`ValueSet.codeSystem.concept.designation.id`**| | | | | | | | | 
| **`ValueSet.codeSystem.concept.designation.extension`**| | | | | | | | | 
| **`ValueSet.codeSystem.concept.designation.modifierExtension`**| | | | | | | | | 
| **`ValueSet.codeSystem.concept.designation.language`**| | | | | | | | | 
| **`ValueSet.codeSystem.concept.designation.use`**| | | | | | | | | 
| **`ValueSet.codeSystem.concept.designation.value`**| | | | | | | | | 
| **`ValueSet.codeSystem.concept.concept`**| | | | | | | | | 
| **`ValueSet.compose`**| _Equivalent_<br/>(8567/8568)| `ValueSet.compose`| | | | | | | 
| **`ValueSet.compose.id`**| _Equivalent_<br/>(8569/8570)| `ValueSet.compose.id`| | | | | | | 
| **`ValueSet.compose.extension`**| _Equivalent_<br/>(8571/8572)| `ValueSet.compose.extension`| | | | | | | 
| **`ValueSet.compose.modifierExtension`**| →→→→ _Equivalent_ →→→→ <br/>(19844)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(787)| `ValueSet.compose.modifierExtension`| | | | | | | 
| **`ValueSet.compose.modifierExtension`**| →→→→ _Equivalent_ →→→→ <br/>(19844)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(787)| `ValueSet.compose.include.modifierExtension`| | | | | | | 
| **`ValueSet.compose.import`**| | | | | | | | | 
| **`ValueSet.compose.include`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(8575)<hr/>←←←← _Equivalent_ ←←←← <br/>(8576)| `ValueSet.compose.include`| | | | | | | 
| **`ValueSet.compose.include.id`**| _Equivalent_<br/>(8577/8578)| `ValueSet.compose.include.id`| | | | | | | 
| **`ValueSet.compose.include.extension`**| _Equivalent_<br/>(8579/8580)| `ValueSet.compose.include.extension`| | | | | | | 
| **`ValueSet.compose.include.modifierExtension`**| →→→→ _Equivalent_ →→→→ <br/>(8581)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(8582)| `ValueSet.compose.include.modifierExtension`| | | | | | | 
| **`ValueSet.compose.include.system`**| →→→→ _Equivalent_ →→→→ <br/>(8583)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(8584)| `ValueSet.compose.include.system`| | | | | | | 
| **`ValueSet.compose.include.version`**| _Equivalent_<br/>(8585/8586)| `ValueSet.compose.include.version`| | | | | | | 
| **`ValueSet.compose.include.concept`**| _Equivalent_<br/>(8587/8588)| `ValueSet.compose.include.concept`| | | | | | | 
| **`ValueSet.compose.include.concept.id`**| _Equivalent_<br/>(8589/8590)| `ValueSet.compose.include.concept.id`| | | | | | | 
| **`ValueSet.compose.include.concept.extension`**| _Equivalent_<br/>(8591/8592)| `ValueSet.compose.include.concept.extension`| | | | | | | 
| **`ValueSet.compose.include.concept.modifierExtension`**| _Equivalent_<br/>(8593/8594)| `ValueSet.compose.include.concept.modifierExtension`| | | | | | | 
| **`ValueSet.compose.include.concept.code`**| _Equivalent_<br/>(8595/8596)| `ValueSet.compose.include.concept.code`| | | | | | | 
| **`ValueSet.compose.include.concept.display`**| _Equivalent_<br/>(8597/8598)| `ValueSet.compose.include.concept.display`| | | | | | | 
| **`ValueSet.compose.include.concept.designation`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(8599)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(8600)| `ValueSet.compose.include.concept.designation`| | | | | | | 
| **`ValueSet.compose.include.filter`**| _Equivalent_<br/>(8601/8602)| `ValueSet.compose.include.filter`| | | | | | | 
| **`ValueSet.compose.include.filter.id`**| _Equivalent_<br/>(8603/8604)| `ValueSet.compose.include.filter.id`| | | | | | | 
| **`ValueSet.compose.include.filter.extension`**| _Equivalent_<br/>(8605/8606)| `ValueSet.compose.include.filter.extension`| | | | | | | 
| **`ValueSet.compose.include.filter.modifierExtension`**| _Equivalent_<br/>(8607/8608)| `ValueSet.compose.include.filter.modifierExtension`| | | | | | | 
| **`ValueSet.compose.include.filter.property`**| _Equivalent_<br/>(8609/8610)| `ValueSet.compose.include.filter.property`| | | | | | | 
| **`ValueSet.compose.include.filter.op`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(8611)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(8612)| `ValueSet.compose.include.filter.op`| | | | | | | 
| **`ValueSet.compose.include.filter.value`**| _Equivalent_<br/>(8613/8614)| `ValueSet.compose.include.filter.value`| | | | | | | 
| **`ValueSet.compose.exclude`**| _Equivalent_<br/>(8615/8616)| `ValueSet.compose.exclude`| | | | | | | 
| **`ValueSet.expansion`**| _Equivalent_<br/>(8617/8618)| `ValueSet.expansion`| | | | | | | 
| **`ValueSet.expansion.id`**| _Equivalent_<br/>(8619/8620)| `ValueSet.expansion.id`| | | | | | | 
| **`ValueSet.expansion.extension`**| _Equivalent_<br/>(8621/8622)| `ValueSet.expansion.extension`| | | | | | | 
| **`ValueSet.expansion.modifierExtension`**| _Equivalent_<br/>(8623/8624)| `ValueSet.expansion.modifierExtension`| | | | | | | 
| **`ValueSet.expansion.identifier`**| _Equivalent_<br/>(8625/8626)| `ValueSet.expansion.identifier`| | | | | | | 
| **`ValueSet.expansion.timestamp`**| _Equivalent_<br/>(8627/8628)| `ValueSet.expansion.timestamp`| | | | | | | 
| **`ValueSet.expansion.total`**| _Equivalent_<br/>(8629/8630)| `ValueSet.expansion.total`| | | | | | | 
| **`ValueSet.expansion.offset`**| _Equivalent_<br/>(8631/8632)| `ValueSet.expansion.offset`| | | | | | | 
| **`ValueSet.expansion.parameter`**| _Equivalent_<br/>(8633/8634)| `ValueSet.expansion.parameter`| | | | | | | 
| **`ValueSet.expansion.parameter.id`**| _Equivalent_<br/>(8635/8636)| `ValueSet.expansion.parameter.id`| | | | | | | 
| **`ValueSet.expansion.parameter.extension`**| _Equivalent_<br/>(8637/8638)| `ValueSet.expansion.parameter.extension`| | | | | | | 
| **`ValueSet.expansion.parameter.modifierExtension`**| _Equivalent_<br/>(8639/8640)| `ValueSet.expansion.parameter.modifierExtension`| | | | | | | 
| **`ValueSet.expansion.parameter.name`**| _Equivalent_<br/>(8641/8642)| `ValueSet.expansion.parameter.name`| | | | | | | 
| **`ValueSet.expansion.parameter.value[x]`**| _Equivalent_<br/>(8643/8644)| `ValueSet.expansion.parameter.value[x]`| | | | | | | 
| **`ValueSet.expansion.contains`**| _Equivalent_<br/>(8645/8646)| `ValueSet.expansion.contains`| | | | | | | 
| **`ValueSet.expansion.contains.id`**| _Equivalent_<br/>(8647/8648)| `ValueSet.expansion.contains.id`| | | | | | | 
| **`ValueSet.expansion.contains.extension`**| _Equivalent_<br/>(8649/8650)| `ValueSet.expansion.contains.extension`| | | | | | | 
| **`ValueSet.expansion.contains.modifierExtension`**| _Equivalent_<br/>(8651/8652)| `ValueSet.expansion.contains.modifierExtension`| | | | | | | 
| **`ValueSet.expansion.contains.system`**| _Equivalent_<br/>(8653/8654)| `ValueSet.expansion.contains.system`| | | | | | | 
| **`ValueSet.expansion.contains.abstract`**| _Equivalent_<br/>(8655/8656)| `ValueSet.expansion.contains.abstract`| | | | | | | 
| **`ValueSet.expansion.contains.version`**| _Equivalent_<br/>(8657/8658)| `ValueSet.expansion.contains.version`| | | | | | | 
| **`ValueSet.expansion.contains.code`**| _Equivalent_<br/>(8659/8660)| `ValueSet.expansion.contains.code`| | | | | | | 
| **`ValueSet.expansion.contains.display`**| _Equivalent_<br/>(8661/8662)| `ValueSet.expansion.contains.display`| | | | | | | 
| **`ValueSet.expansion.contains.contains`**| _Equivalent_<br/>(8663/8664)| `ValueSet.expansion.contains.contains`| | | | | | | 
| *103 of 103 elements used* | | *75 of 68 elements used* | | *0 of 69 elements used* <br/>remaining elements:<br/>`CodeSystem`, `CodeSystem.caseSensitive`, `CodeSystem.compositional`, `CodeSystem.concept`, `CodeSystem.concept.code`, `CodeSystem.concept.concept`, `CodeSystem.concept.definition`, `CodeSystem.concept.designation`, `CodeSystem.concept.designation.extension`, `CodeSystem.concept.designation.id`, `CodeSystem.concept.designation.language`, `CodeSystem.concept.designation.modifierExtension`, `CodeSystem.concept.designation.use`, `CodeSystem.concept.designation.value`, `CodeSystem.concept.display`, `CodeSystem.concept.extension`, `CodeSystem.concept.id`, `CodeSystem.concept.modifierExtension`, `CodeSystem.concept.property`, `CodeSystem.concept.property.code`, `CodeSystem.concept.property.extension`, `CodeSystem.concept.property.id`, `CodeSystem.concept.property.modifierExtension`, `CodeSystem.concept.property.value[x]`, `CodeSystem.contact`, `CodeSystem.contained`, `CodeSystem.content`, `CodeSystem.copyright`, `CodeSystem.count`, `CodeSystem.date`, `CodeSystem.description`, `CodeSystem.experimental`, `CodeSystem.extension`, `CodeSystem.filter`, `CodeSystem.filter.code`, `CodeSystem.filter.description`, `CodeSystem.filter.extension`, `CodeSystem.filter.id`, `CodeSystem.filter.modifierExtension`, `CodeSystem.filter.operator`, `CodeSystem.filter.value`, `CodeSystem.hierarchyMeaning`, `CodeSystem.id`, `CodeSystem.identifier`, `CodeSystem.implicitRules`, `CodeSystem.jurisdiction`, `CodeSystem.language`, `CodeSystem.meta`, `CodeSystem.modifierExtension`, `CodeSystem.name`, `CodeSystem.property`, `CodeSystem.property.code`, `CodeSystem.property.description`, `CodeSystem.property.extension`, `CodeSystem.property.id`, `CodeSystem.property.modifierExtension`, `CodeSystem.property.type`, `CodeSystem.property.uri`, `CodeSystem.publisher`, `CodeSystem.purpose`, `CodeSystem.status`, `CodeSystem.supplements`, `CodeSystem.text`, `CodeSystem.title`, `CodeSystem.url`, `CodeSystem.useContext`, `CodeSystem.valueSet`, `CodeSystem.version`, `CodeSystem.versionNeeded`| | *0 of 69 elements used* <br/>remaining elements:<br/>`CodeSystem`, `CodeSystem.caseSensitive`, `CodeSystem.compositional`, `CodeSystem.concept`, `CodeSystem.concept.code`, `CodeSystem.concept.concept`, `CodeSystem.concept.definition`, `CodeSystem.concept.designation`, `CodeSystem.concept.designation.extension`, `CodeSystem.concept.designation.id`, `CodeSystem.concept.designation.language`, `CodeSystem.concept.designation.modifierExtension`, `CodeSystem.concept.designation.use`, `CodeSystem.concept.designation.value`, `CodeSystem.concept.display`, `CodeSystem.concept.extension`, `CodeSystem.concept.id`, `CodeSystem.concept.modifierExtension`, `CodeSystem.concept.property`, `CodeSystem.concept.property.code`, `CodeSystem.concept.property.extension`, `CodeSystem.concept.property.id`, `CodeSystem.concept.property.modifierExtension`, `CodeSystem.concept.property.value[x]`, `CodeSystem.contact`, `CodeSystem.contained`, `CodeSystem.content`, `CodeSystem.copyright`, `CodeSystem.count`, `CodeSystem.date`, `CodeSystem.description`, `CodeSystem.experimental`, `CodeSystem.extension`, `CodeSystem.filter`, `CodeSystem.filter.code`, `CodeSystem.filter.description`, `CodeSystem.filter.extension`, `CodeSystem.filter.id`, `CodeSystem.filter.modifierExtension`, `CodeSystem.filter.operator`, `CodeSystem.filter.value`, `CodeSystem.hierarchyMeaning`, `CodeSystem.id`, `CodeSystem.identifier`, `CodeSystem.implicitRules`, `CodeSystem.jurisdiction`, `CodeSystem.language`, `CodeSystem.meta`, `CodeSystem.modifierExtension`, `CodeSystem.name`, `CodeSystem.property`, `CodeSystem.property.code`, `CodeSystem.property.description`, `CodeSystem.property.extension`, `CodeSystem.property.id`, `CodeSystem.property.modifierExtension`, `CodeSystem.property.type`, `CodeSystem.property.uri`, `CodeSystem.publisher`, `CodeSystem.purpose`, `CodeSystem.status`, `CodeSystem.supplements`, `CodeSystem.text`, `CodeSystem.title`, `CodeSystem.url`, `CodeSystem.useContext`, `CodeSystem.valueSet`, `CodeSystem.version`, `CodeSystem.versionNeeded`| | *0 of 81 elements used* <br/>remaining elements:<br/>`CodeSystem`, `CodeSystem.approvalDate`, `CodeSystem.author`, `CodeSystem.caseSensitive`, `CodeSystem.compositional`, `CodeSystem.concept`, `CodeSystem.concept.code`, `CodeSystem.concept.concept`, `CodeSystem.concept.definition`, `CodeSystem.concept.designation`, `CodeSystem.concept.designation.additionalUse`, `CodeSystem.concept.designation.extension`, `CodeSystem.concept.designation.id`, `CodeSystem.concept.designation.language`, `CodeSystem.concept.designation.modifierExtension`, `CodeSystem.concept.designation.use`, `CodeSystem.concept.designation.value`, `CodeSystem.concept.display`, `CodeSystem.concept.extension`, `CodeSystem.concept.id`, `CodeSystem.concept.modifierExtension`, `CodeSystem.concept.property`, `CodeSystem.concept.property.code`, `CodeSystem.concept.property.extension`, `CodeSystem.concept.property.id`, `CodeSystem.concept.property.modifierExtension`, `CodeSystem.concept.property.value[x]`, `CodeSystem.contact`, `CodeSystem.contained`, `CodeSystem.content`, `CodeSystem.copyright`, `CodeSystem.copyrightLabel`, `CodeSystem.count`, `CodeSystem.date`, `CodeSystem.description`, `CodeSystem.editor`, `CodeSystem.effectivePeriod`, `CodeSystem.endorser`, `CodeSystem.experimental`, `CodeSystem.extension`, `CodeSystem.filter`, `CodeSystem.filter.code`, `CodeSystem.filter.description`, `CodeSystem.filter.extension`, `CodeSystem.filter.id`, `CodeSystem.filter.modifierExtension`, `CodeSystem.filter.operator`, `CodeSystem.filter.value`, `CodeSystem.hierarchyMeaning`, `CodeSystem.id`, `CodeSystem.identifier`, `CodeSystem.implicitRules`, `CodeSystem.jurisdiction`, `CodeSystem.language`, `CodeSystem.lastReviewDate`, `CodeSystem.meta`, `CodeSystem.modifierExtension`, `CodeSystem.name`, `CodeSystem.property`, `CodeSystem.property.code`, `CodeSystem.property.description`, `CodeSystem.property.extension`, `CodeSystem.property.id`, `CodeSystem.property.modifierExtension`, `CodeSystem.property.type`, `CodeSystem.property.uri`, `CodeSystem.publisher`, `CodeSystem.purpose`, `CodeSystem.relatedArtifact`, `CodeSystem.reviewer`, `CodeSystem.status`, `CodeSystem.supplements`, `CodeSystem.text`, `CodeSystem.title`, `CodeSystem.topic`, `CodeSystem.url`, `CodeSystem.useContext`, `CodeSystem.valueSet`, `CodeSystem.version`, `CodeSystem.versionAlgorithm[x]`, `CodeSystem.versionNeeded`


#### Map Group 1

This group is centered on the Structure Definition ValueSet from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 ValueSet| Relationship | [R3 ValueSet](/docs/R3/Resources/ValueSet.md)| Relationship | [R4 ValueSet](/docs/R4/Resources/ValueSet.md)| Relationship | [R4B ValueSet](/docs/R4B/Resources/ValueSet.md)| Relationship | [R5 ValueSet](/docs/R5/Resources/ValueSet.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`ValueSet`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(8506)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(8507)| `ValueSet`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(19854)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(19855)| `ValueSet`| _Equivalent_<br/>(34799/34800)| `ValueSet`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(49217)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(49218)| `ValueSet`
| **`ValueSet.id`**| _Equivalent_<br/>(8508/8509)| `ValueSet.id`| _Equivalent_<br/>(19856/19857)| `ValueSet.id`| _Equivalent_<br/>(34801/34802)| `ValueSet.id`| _Equivalent_<br/>(49219/49220)| `ValueSet.id`
| **`ValueSet.meta`**| _Equivalent_<br/>(8510/8511)| `ValueSet.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(19858)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(19859)| `ValueSet.meta`| _Equivalent_<br/>(34803/34804)| `ValueSet.meta`| _Equivalent_<br/>(49221/49222)| `ValueSet.meta`
| **`ValueSet.implicitRules`**| _Equivalent_<br/>(8512/8513)| `ValueSet.implicitRules`| _Equivalent_<br/>(19860/19861)| `ValueSet.implicitRules`| _Equivalent_<br/>(34805/34806)| `ValueSet.implicitRules`| _Equivalent_<br/>(49223/49224)| `ValueSet.implicitRules`
| **`ValueSet.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(8514)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(8515)| `ValueSet.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(19862)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(19863)| `ValueSet.language`| _Equivalent_<br/>(34807/34808)| `ValueSet.language`| _Equivalent_<br/>(49225/49226)| `ValueSet.language`
| **`ValueSet.text`**| _Equivalent_<br/>(8516/8517)| `ValueSet.text`| _Equivalent_<br/>(19864/19865)| `ValueSet.text`| _Equivalent_<br/>(34809/34810)| `ValueSet.text`| _Equivalent_<br/>(49227/49228)| `ValueSet.text`
| **`ValueSet.contained`**| _Equivalent_<br/>(8518/8519)| `ValueSet.contained`| _Equivalent_<br/>(19866/19867)| `ValueSet.contained`| _Equivalent_<br/>(34811/34812)| `ValueSet.contained`| _Equivalent_<br/>(49229/49230)| `ValueSet.contained`
| **`ValueSet.extension`**| _Equivalent_<br/>(8520/8521)| `ValueSet.extension`| _Equivalent_<br/>(19868/19869)| `ValueSet.extension`| _Equivalent_<br/>(34813/34814)| `ValueSet.extension`| _Equivalent_<br/>(49231/49232)| `ValueSet.extension`
| **`ValueSet.modifierExtension`**| →→→→ _Equivalent_ →→→→ <br/>(8522)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(8523)| `ValueSet.modifierExtension`| _Equivalent_<br/>(19870/19871)| `ValueSet.modifierExtension`| _Equivalent_<br/>(34815/34816)| `ValueSet.modifierExtension`| _Equivalent_<br/>(49233/49234)| `ValueSet.modifierExtension`
| **`ValueSet.url`**| _Equivalent_<br/>(8524/8525)| `ValueSet.url`| _Equivalent_<br/>(19872/19873)| `ValueSet.url`| _Equivalent_<br/>(34817/34818)| `ValueSet.url`| _Equivalent_<br/>(49235/49236)| `ValueSet.url`
| **`ValueSet.identifier`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(8526)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(8527)| `ValueSet.identifier`| _Equivalent_<br/>(19874/19875)| `ValueSet.identifier`| _Equivalent_<br/>(34819/34820)| `ValueSet.identifier`| _Equivalent_<br/>(49237/49238)| `ValueSet.identifier`
| **`ValueSet.version`**| _Equivalent_<br/>(8528/8529)| `ValueSet.version`| _Equivalent_<br/>(19876/19877)| `ValueSet.version`| _Equivalent_<br/>(34821/34822)| `ValueSet.version`| _Equivalent_<br/>(49239/49240)| `ValueSet.version`
| **`ValueSet.name`**| _Equivalent_<br/>(8530/8531)| `ValueSet.name`| _Equivalent_<br/>(19878/19879)| `ValueSet.name`| _Equivalent_<br/>(34823/34824)| `ValueSet.name`| _Equivalent_<br/>(49241/49242)| `ValueSet.name`
| **`ValueSet.status`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(8532)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(8533)| `ValueSet.status`| _Equivalent_<br/>(19882/19883)| `ValueSet.status`| _Equivalent_<br/>(34827/34828)| `ValueSet.status`| _Equivalent_<br/>(49245/49246)| `ValueSet.status`
| **`ValueSet.experimental`**| _Equivalent_<br/>(8534/8535)| `ValueSet.experimental`| _Equivalent_<br/>(19884/19885)| `ValueSet.experimental`| _Equivalent_<br/>(34829/34830)| `ValueSet.experimental`| _Equivalent_<br/>(49247/49248)| `ValueSet.experimental`
| **`ValueSet.publisher`**| _Equivalent_<br/>(8536/8537)| `ValueSet.publisher`| _Equivalent_<br/>(19888/19889)| `ValueSet.publisher`| _Equivalent_<br/>(34833/34834)| `ValueSet.publisher`| _Equivalent_<br/>(49251/49252)| `ValueSet.publisher`
| **`ValueSet.contact`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(8538)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(8539)| `ValueSet.contact`| _Equivalent_<br/>(19890/19891)| `ValueSet.contact`| _Equivalent_<br/>(34835/34836)| `ValueSet.contact`| _Equivalent_<br/>(49253/49254)| `ValueSet.contact`
| **`ValueSet.contact.id`**| | | | | | | | | 
| **`ValueSet.contact.extension`**| | | | | | | | | 
| **`ValueSet.contact.modifierExtension`**| | | | | | | | | 
| **`ValueSet.contact.name`**| | | | | | | | | 
| **`ValueSet.contact.telecom`**| | | | | | | | | 
| **`ValueSet.date`**| _Equivalent_<br/>(8545/8546)| `ValueSet.date`| _Equivalent_<br/>(19886/19887)| `ValueSet.date`| _Equivalent_<br/>(34831/34832)| `ValueSet.date`| _Equivalent_<br/>(49249/49250)| `ValueSet.date`
| **`ValueSet.lockedDate`**| _Equivalent_<br/>(452/784)| `ValueSet.compose.lockedDate`| _Equivalent_<br/>(19912/19913)| `ValueSet.compose.lockedDate`| _Equivalent_<br/>(34857/34858)| `ValueSet.compose.lockedDate`| _Equivalent_<br/>(49275/49276)| `ValueSet.compose.lockedDate`
| **`ValueSet.description`**| _Equivalent_<br/>(8547/8548)| `ValueSet.description`| _Equivalent_<br/>(19892/19893)| `ValueSet.description`| _Equivalent_<br/>(34837/34838)| `ValueSet.description`| _Equivalent_<br/>(49255/49256)| `ValueSet.description`
| **`ValueSet.useContext`**| _Equivalent_<br/>(454/786)| `ValueSet.useContext`| _Equivalent_<br/>(19894/19895)| `ValueSet.useContext`| _Equivalent_<br/>(34839/34840)| `ValueSet.useContext`| _Equivalent_<br/>(49257/49258)| `ValueSet.useContext`
| **`ValueSet.useContext`**| _Equivalent_<br/>(454/786)| `ValueSet.jurisdiction`| _Equivalent_<br/>(19896/19897)| `ValueSet.jurisdiction`| _Equivalent_<br/>(34841/34842)| `ValueSet.jurisdiction`| _Equivalent_<br/>(49259/49260)| `ValueSet.jurisdiction`
| **`ValueSet.immutable`**| _Equivalent_<br/>(8549/8550)| `ValueSet.immutable`| _Equivalent_<br/>(19898/19899)| `ValueSet.immutable`| _Equivalent_<br/>(34843/34844)| `ValueSet.immutable`| _Equivalent_<br/>(49261/49262)| `ValueSet.immutable`
| **`ValueSet.requirements`**| _Equivalent_<br/>(453/785)| `ValueSet.purpose`| _Equivalent_<br/>(19900/19901)| `ValueSet.purpose`| _Equivalent_<br/>(34845/34846)| `ValueSet.purpose`| _Equivalent_<br/>(49263/49264)| `ValueSet.purpose`
| **`ValueSet.copyright`**| _Equivalent_<br/>(8551/8552)| `ValueSet.copyright`| _Equivalent_<br/>(19902/19903)| `ValueSet.copyright`| _Equivalent_<br/>(34847/34848)| `ValueSet.copyright`| _Equivalent_<br/>(49265/49266)| `ValueSet.copyright`
| **`ValueSet.extensible`**| _Equivalent_<br/>(8553/8554)| `ValueSet.extensible`| | | | | | | 
| **`ValueSet.codeSystem`**| | | | | | | | | 
| **`ValueSet.codeSystem.id`**| | | | | | | | | 
| **`ValueSet.codeSystem.extension`**| | | | | | | | | 
| **`ValueSet.codeSystem.modifierExtension`**| →→→→ _Equivalent_ →→→→ <br/>(455)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(8558)| `ValueSet.modifierExtension`| _Equivalent_<br/>(19870/19871)| `ValueSet.modifierExtension`| _Equivalent_<br/>(34815/34816)| `ValueSet.modifierExtension`| _Equivalent_<br/>(49233/49234)| `ValueSet.modifierExtension`
| **`ValueSet.codeSystem.system`**| | | | | | | | | 
| **`ValueSet.codeSystem.version`**| | | | | | | | | 
| **`ValueSet.codeSystem.caseSensitive`**| | | | | | | | | 
| **`ValueSet.codeSystem.concept`**| | | | | | | | | 
| **`ValueSet.codeSystem.concept.id`**| | | | | | | | | 
| **`ValueSet.codeSystem.concept.extension`**| | | | | | | | | 
| **`ValueSet.codeSystem.concept.modifierExtension`**| | | | | | | | | 
| **`ValueSet.codeSystem.concept.code`**| | | | | | | | | 
| **`ValueSet.codeSystem.concept.abstract`**| | | | | | | | | 
| **`ValueSet.codeSystem.concept.display`**| | | | | | | | | 
| **`ValueSet.codeSystem.concept.definition`**| | | | | | | | | 
| **`ValueSet.codeSystem.concept.designation`**| | | | | | | | | 
| **`ValueSet.codeSystem.concept.designation.id`**| | | | | | | | | 
| **`ValueSet.codeSystem.concept.designation.extension`**| | | | | | | | | 
| **`ValueSet.codeSystem.concept.designation.modifierExtension`**| | | | | | | | | 
| **`ValueSet.codeSystem.concept.designation.language`**| | | | | | | | | 
| **`ValueSet.codeSystem.concept.designation.use`**| | | | | | | | | 
| **`ValueSet.codeSystem.concept.designation.value`**| | | | | | | | | 
| **`ValueSet.codeSystem.concept.concept`**| | | | | | | | | 
| **`ValueSet.compose`**| _Equivalent_<br/>(8567/8568)| `ValueSet.compose`| _Equivalent_<br/>(19904/19905)| `ValueSet.compose`| _Equivalent_<br/>(34849/34850)| `ValueSet.compose`| _Equivalent_<br/>(49267/49268)| `ValueSet.compose`
| **`ValueSet.compose.id`**| _Equivalent_<br/>(8569/8570)| `ValueSet.compose.id`| _Equivalent_<br/>(19906/19907)| `ValueSet.compose.id`| _Equivalent_<br/>(34851/34852)| `ValueSet.compose.id`| _Equivalent_<br/>(49269/49270)| `ValueSet.compose.id`
| **`ValueSet.compose.extension`**| _Equivalent_<br/>(8571/8572)| `ValueSet.compose.extension`| _Equivalent_<br/>(19908/19909)| `ValueSet.compose.extension`| _Equivalent_<br/>(34853/34854)| `ValueSet.compose.extension`| _Equivalent_<br/>(49271/49272)| `ValueSet.compose.extension`
| **`ValueSet.compose.modifierExtension`**| →→→→ _Equivalent_ →→→→ <br/>(19844)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(787)| `ValueSet.compose.modifierExtension`| _Equivalent_<br/>(19910/19911)| `ValueSet.compose.modifierExtension`| _Equivalent_<br/>(34855/34856)| `ValueSet.compose.modifierExtension`| _Equivalent_<br/>(49273/49274)| `ValueSet.compose.modifierExtension`
| **`ValueSet.compose.modifierExtension`**| →→→→ _Equivalent_ →→→→ <br/>(19844)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(787)| `ValueSet.compose.include.modifierExtension`| _Equivalent_<br/>(19922/19923)| `ValueSet.compose.include.modifierExtension`| _Equivalent_<br/>(34867/34868)| `ValueSet.compose.include.modifierExtension`| _Equivalent_<br/>(49285/49286)| `ValueSet.compose.include.modifierExtension`
| **`ValueSet.compose.import`**| | | | | | | | | 
| **`ValueSet.compose.include`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(8575)<hr/>←←←← _Equivalent_ ←←←← <br/>(8576)| `ValueSet.compose.include`| _Equivalent_<br/>(19916/19917)| `ValueSet.compose.include`| _Equivalent_<br/>(34861/34862)| `ValueSet.compose.include`| _Equivalent_<br/>(49279/49280)| `ValueSet.compose.include`
| **`ValueSet.compose.include.id`**| _Equivalent_<br/>(8577/8578)| `ValueSet.compose.include.id`| _Equivalent_<br/>(19918/19919)| `ValueSet.compose.include.id`| _Equivalent_<br/>(34863/34864)| `ValueSet.compose.include.id`| _Equivalent_<br/>(49281/49282)| `ValueSet.compose.include.id`
| **`ValueSet.compose.include.extension`**| _Equivalent_<br/>(8579/8580)| `ValueSet.compose.include.extension`| _Equivalent_<br/>(19920/19921)| `ValueSet.compose.include.extension`| _Equivalent_<br/>(34865/34866)| `ValueSet.compose.include.extension`| _Equivalent_<br/>(49283/49284)| `ValueSet.compose.include.extension`
| **`ValueSet.compose.include.modifierExtension`**| →→→→ _Equivalent_ →→→→ <br/>(8581)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(8582)| `ValueSet.compose.include.modifierExtension`| _Equivalent_<br/>(19922/19923)| `ValueSet.compose.include.modifierExtension`| _Equivalent_<br/>(34867/34868)| `ValueSet.compose.include.modifierExtension`| _Equivalent_<br/>(49285/49286)| `ValueSet.compose.include.modifierExtension`
| **`ValueSet.compose.include.system`**| →→→→ _Equivalent_ →→→→ <br/>(8583)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(8584)| `ValueSet.compose.include.system`| _Equivalent_<br/>(19924/19925)| `ValueSet.compose.include.system`| _Equivalent_<br/>(34869/34870)| `ValueSet.compose.include.system`| _Equivalent_<br/>(49287/49288)| `ValueSet.compose.include.system`
| **`ValueSet.compose.include.version`**| _Equivalent_<br/>(8585/8586)| `ValueSet.compose.include.version`| _Equivalent_<br/>(19926/19927)| `ValueSet.compose.include.version`| _Equivalent_<br/>(34871/34872)| `ValueSet.compose.include.version`| _Equivalent_<br/>(49289/49290)| `ValueSet.compose.include.version`
| **`ValueSet.compose.include.concept`**| _Equivalent_<br/>(8587/8588)| `ValueSet.compose.include.concept`| _Equivalent_<br/>(19928/19929)| `ValueSet.compose.include.concept`| _Equivalent_<br/>(34873/34874)| `ValueSet.compose.include.concept`| _Equivalent_<br/>(49291/49292)| `ValueSet.compose.include.concept`
| **`ValueSet.compose.include.concept.id`**| _Equivalent_<br/>(8589/8590)| `ValueSet.compose.include.concept.id`| _Equivalent_<br/>(19930/19931)| `ValueSet.compose.include.concept.id`| _Equivalent_<br/>(34875/34876)| `ValueSet.compose.include.concept.id`| _Equivalent_<br/>(49293/49294)| `ValueSet.compose.include.concept.id`
| **`ValueSet.compose.include.concept.extension`**| _Equivalent_<br/>(8591/8592)| `ValueSet.compose.include.concept.extension`| _Equivalent_<br/>(19932/19933)| `ValueSet.compose.include.concept.extension`| _Equivalent_<br/>(34877/34878)| `ValueSet.compose.include.concept.extension`| _Equivalent_<br/>(49295/49296)| `ValueSet.compose.include.concept.extension`
| **`ValueSet.compose.include.concept.modifierExtension`**| _Equivalent_<br/>(8593/8594)| `ValueSet.compose.include.concept.modifierExtension`| _Equivalent_<br/>(19934/19935)| `ValueSet.compose.include.concept.modifierExtension`| _Equivalent_<br/>(34879/34880)| `ValueSet.compose.include.concept.modifierExtension`| _Equivalent_<br/>(49297/49298)| `ValueSet.compose.include.concept.modifierExtension`
| **`ValueSet.compose.include.concept.code`**| _Equivalent_<br/>(8595/8596)| `ValueSet.compose.include.concept.code`| _Equivalent_<br/>(19936/19937)| `ValueSet.compose.include.concept.code`| _Equivalent_<br/>(34881/34882)| `ValueSet.compose.include.concept.code`| _Equivalent_<br/>(49299/49300)| `ValueSet.compose.include.concept.code`
| **`ValueSet.compose.include.concept.display`**| _Equivalent_<br/>(8597/8598)| `ValueSet.compose.include.concept.display`| _Equivalent_<br/>(19938/19939)| `ValueSet.compose.include.concept.display`| _Equivalent_<br/>(34883/34884)| `ValueSet.compose.include.concept.display`| _Equivalent_<br/>(49301/49302)| `ValueSet.compose.include.concept.display`
| **`ValueSet.compose.include.concept.designation`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(8599)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(8600)| `ValueSet.compose.include.concept.designation`| _Equivalent_<br/>(19940/19941)| `ValueSet.compose.include.concept.designation`| _Equivalent_<br/>(34885/34886)| `ValueSet.compose.include.concept.designation`| _Equivalent_<br/>(49303/49304)| `ValueSet.compose.include.concept.designation`
| **`ValueSet.compose.include.filter`**| _Equivalent_<br/>(8601/8602)| `ValueSet.compose.include.filter`| _Equivalent_<br/>(19954/19955)| `ValueSet.compose.include.filter`| _Equivalent_<br/>(34899/34900)| `ValueSet.compose.include.filter`| _Equivalent_<br/>(49317/49318)| `ValueSet.compose.include.filter`
| **`ValueSet.compose.include.filter.id`**| _Equivalent_<br/>(8603/8604)| `ValueSet.compose.include.filter.id`| _Equivalent_<br/>(19956/19957)| `ValueSet.compose.include.filter.id`| _Equivalent_<br/>(34901/34902)| `ValueSet.compose.include.filter.id`| _Equivalent_<br/>(49319/49320)| `ValueSet.compose.include.filter.id`
| **`ValueSet.compose.include.filter.extension`**| _Equivalent_<br/>(8605/8606)| `ValueSet.compose.include.filter.extension`| _Equivalent_<br/>(19958/19959)| `ValueSet.compose.include.filter.extension`| _Equivalent_<br/>(34903/34904)| `ValueSet.compose.include.filter.extension`| _Equivalent_<br/>(49321/49322)| `ValueSet.compose.include.filter.extension`
| **`ValueSet.compose.include.filter.modifierExtension`**| _Equivalent_<br/>(8607/8608)| `ValueSet.compose.include.filter.modifierExtension`| _Equivalent_<br/>(19960/19961)| `ValueSet.compose.include.filter.modifierExtension`| _Equivalent_<br/>(34905/34906)| `ValueSet.compose.include.filter.modifierExtension`| _Equivalent_<br/>(49323/49324)| `ValueSet.compose.include.filter.modifierExtension`
| **`ValueSet.compose.include.filter.property`**| _Equivalent_<br/>(8609/8610)| `ValueSet.compose.include.filter.property`| _Equivalent_<br/>(19962/19963)| `ValueSet.compose.include.filter.property`| _Equivalent_<br/>(34907/34908)| `ValueSet.compose.include.filter.property`| _Equivalent_<br/>(49325/49326)| `ValueSet.compose.include.filter.property`
| **`ValueSet.compose.include.filter.op`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(8611)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(8612)| `ValueSet.compose.include.filter.op`| _Equivalent_<br/>(19964/19965)| `ValueSet.compose.include.filter.op`| _Equivalent_<br/>(34909/34910)| `ValueSet.compose.include.filter.op`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(49327)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(49328)| `ValueSet.compose.include.filter.op`
| **`ValueSet.compose.include.filter.value`**| _Equivalent_<br/>(8613/8614)| `ValueSet.compose.include.filter.value`| _Equivalent_<br/>(19966/19967)| `ValueSet.compose.include.filter.value`| _Equivalent_<br/>(34911/34912)| `ValueSet.compose.include.filter.value`| _Equivalent_<br/>(49329/49330)| `ValueSet.compose.include.filter.value`
| **`ValueSet.compose.exclude`**| _Equivalent_<br/>(8615/8616)| `ValueSet.compose.exclude`| _Equivalent_<br/>(19970/19971)| `ValueSet.compose.exclude`| _Equivalent_<br/>(34915/34916)| `ValueSet.compose.exclude`| _Equivalent_<br/>(49333/49334)| `ValueSet.compose.exclude`
| **`ValueSet.expansion`**| _Equivalent_<br/>(8617/8618)| `ValueSet.expansion`| _Equivalent_<br/>(19972/19973)| `ValueSet.expansion`| _Equivalent_<br/>(34917/34918)| `ValueSet.expansion`| _Equivalent_<br/>(49335/49336)| `ValueSet.expansion`
| **`ValueSet.expansion.id`**| _Equivalent_<br/>(8619/8620)| `ValueSet.expansion.id`| _Equivalent_<br/>(19974/19975)| `ValueSet.expansion.id`| _Equivalent_<br/>(34919/34920)| `ValueSet.expansion.id`| _Equivalent_<br/>(49337/49338)| `ValueSet.expansion.id`
| **`ValueSet.expansion.extension`**| _Equivalent_<br/>(8621/8622)| `ValueSet.expansion.extension`| _Equivalent_<br/>(19976/19977)| `ValueSet.expansion.extension`| _Equivalent_<br/>(34921/34922)| `ValueSet.expansion.extension`| _Equivalent_<br/>(49339/49340)| `ValueSet.expansion.extension`
| **`ValueSet.expansion.modifierExtension`**| _Equivalent_<br/>(8623/8624)| `ValueSet.expansion.modifierExtension`| _Equivalent_<br/>(19978/19979)| `ValueSet.expansion.modifierExtension`| _Equivalent_<br/>(34923/34924)| `ValueSet.expansion.modifierExtension`| _Equivalent_<br/>(49341/49342)| `ValueSet.expansion.modifierExtension`
| **`ValueSet.expansion.identifier`**| _Equivalent_<br/>(8625/8626)| `ValueSet.expansion.identifier`| →→→→ _Equivalent_ →→→→ <br/>(19980)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(19981)| `ValueSet.expansion.identifier`| _Equivalent_<br/>(34925/34926)| `ValueSet.expansion.identifier`| _Equivalent_<br/>(49343/49344)| `ValueSet.expansion.identifier`
| **`ValueSet.expansion.timestamp`**| _Equivalent_<br/>(8627/8628)| `ValueSet.expansion.timestamp`| _Equivalent_<br/>(19982/19983)| `ValueSet.expansion.timestamp`| _Equivalent_<br/>(34927/34928)| `ValueSet.expansion.timestamp`| _Equivalent_<br/>(49345/49346)| `ValueSet.expansion.timestamp`
| **`ValueSet.expansion.total`**| _Equivalent_<br/>(8629/8630)| `ValueSet.expansion.total`| _Equivalent_<br/>(19984/19985)| `ValueSet.expansion.total`| _Equivalent_<br/>(34929/34930)| `ValueSet.expansion.total`| _Equivalent_<br/>(49347/49348)| `ValueSet.expansion.total`
| **`ValueSet.expansion.offset`**| _Equivalent_<br/>(8631/8632)| `ValueSet.expansion.offset`| _Equivalent_<br/>(19986/19987)| `ValueSet.expansion.offset`| _Equivalent_<br/>(34931/34932)| `ValueSet.expansion.offset`| _Equivalent_<br/>(49349/49350)| `ValueSet.expansion.offset`
| **`ValueSet.expansion.parameter`**| _Equivalent_<br/>(8633/8634)| `ValueSet.expansion.parameter`| _Equivalent_<br/>(19988/19989)| `ValueSet.expansion.parameter`| _Equivalent_<br/>(34933/34934)| `ValueSet.expansion.parameter`| _Equivalent_<br/>(49351/49352)| `ValueSet.expansion.parameter`
| **`ValueSet.expansion.parameter.id`**| _Equivalent_<br/>(8635/8636)| `ValueSet.expansion.parameter.id`| _Equivalent_<br/>(19990/19991)| `ValueSet.expansion.parameter.id`| _Equivalent_<br/>(34935/34936)| `ValueSet.expansion.parameter.id`| _Equivalent_<br/>(49353/49354)| `ValueSet.expansion.parameter.id`
| **`ValueSet.expansion.parameter.extension`**| _Equivalent_<br/>(8637/8638)| `ValueSet.expansion.parameter.extension`| _Equivalent_<br/>(19992/19993)| `ValueSet.expansion.parameter.extension`| _Equivalent_<br/>(34937/34938)| `ValueSet.expansion.parameter.extension`| _Equivalent_<br/>(49355/49356)| `ValueSet.expansion.parameter.extension`
| **`ValueSet.expansion.parameter.modifierExtension`**| _Equivalent_<br/>(8639/8640)| `ValueSet.expansion.parameter.modifierExtension`| _Equivalent_<br/>(19994/19995)| `ValueSet.expansion.parameter.modifierExtension`| _Equivalent_<br/>(34939/34940)| `ValueSet.expansion.parameter.modifierExtension`| _Equivalent_<br/>(49357/49358)| `ValueSet.expansion.parameter.modifierExtension`
| **`ValueSet.expansion.parameter.name`**| _Equivalent_<br/>(8641/8642)| `ValueSet.expansion.parameter.name`| _Equivalent_<br/>(19996/19997)| `ValueSet.expansion.parameter.name`| _Equivalent_<br/>(34941/34942)| `ValueSet.expansion.parameter.name`| _Equivalent_<br/>(49359/49360)| `ValueSet.expansion.parameter.name`
| **`ValueSet.expansion.parameter.value[x]`**| _Equivalent_<br/>(8643/8644)| `ValueSet.expansion.parameter.value[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(19998)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(19999)| `ValueSet.expansion.parameter.value[x]`| _Equivalent_<br/>(34943/34944)| `ValueSet.expansion.parameter.value[x]`| _Equivalent_<br/>(49361/49362)| `ValueSet.expansion.parameter.value[x]`
| **`ValueSet.expansion.contains`**| _Equivalent_<br/>(8645/8646)| `ValueSet.expansion.contains`| _Equivalent_<br/>(20000/20001)| `ValueSet.expansion.contains`| _Equivalent_<br/>(34945/34946)| `ValueSet.expansion.contains`| _Equivalent_<br/>(49363/49364)| `ValueSet.expansion.contains`
| **`ValueSet.expansion.contains.id`**| _Equivalent_<br/>(8647/8648)| `ValueSet.expansion.contains.id`| _Equivalent_<br/>(20002/20003)| `ValueSet.expansion.contains.id`| _Equivalent_<br/>(34947/34948)| `ValueSet.expansion.contains.id`| _Equivalent_<br/>(49365/49366)| `ValueSet.expansion.contains.id`
| **`ValueSet.expansion.contains.extension`**| _Equivalent_<br/>(8649/8650)| `ValueSet.expansion.contains.extension`| _Equivalent_<br/>(20004/20005)| `ValueSet.expansion.contains.extension`| _Equivalent_<br/>(34949/34950)| `ValueSet.expansion.contains.extension`| _Equivalent_<br/>(49367/49368)| `ValueSet.expansion.contains.extension`
| **`ValueSet.expansion.contains.modifierExtension`**| _Equivalent_<br/>(8651/8652)| `ValueSet.expansion.contains.modifierExtension`| _Equivalent_<br/>(20006/20007)| `ValueSet.expansion.contains.modifierExtension`| _Equivalent_<br/>(34951/34952)| `ValueSet.expansion.contains.modifierExtension`| _Equivalent_<br/>(49369/49370)| `ValueSet.expansion.contains.modifierExtension`
| **`ValueSet.expansion.contains.system`**| _Equivalent_<br/>(8653/8654)| `ValueSet.expansion.contains.system`| _Equivalent_<br/>(20008/20009)| `ValueSet.expansion.contains.system`| _Equivalent_<br/>(34953/34954)| `ValueSet.expansion.contains.system`| _Equivalent_<br/>(49371/49372)| `ValueSet.expansion.contains.system`
| **`ValueSet.expansion.contains.abstract`**| _Equivalent_<br/>(8655/8656)| `ValueSet.expansion.contains.abstract`| _Equivalent_<br/>(20010/20011)| `ValueSet.expansion.contains.abstract`| _Equivalent_<br/>(34955/34956)| `ValueSet.expansion.contains.abstract`| _Equivalent_<br/>(49373/49374)| `ValueSet.expansion.contains.abstract`
| **`ValueSet.expansion.contains.version`**| _Equivalent_<br/>(8657/8658)| `ValueSet.expansion.contains.version`| _Equivalent_<br/>(20014/20015)| `ValueSet.expansion.contains.version`| _Equivalent_<br/>(34959/34960)| `ValueSet.expansion.contains.version`| _Equivalent_<br/>(49377/49378)| `ValueSet.expansion.contains.version`
| **`ValueSet.expansion.contains.code`**| _Equivalent_<br/>(8659/8660)| `ValueSet.expansion.contains.code`| _Equivalent_<br/>(20016/20017)| `ValueSet.expansion.contains.code`| _Equivalent_<br/>(34961/34962)| `ValueSet.expansion.contains.code`| _Equivalent_<br/>(49379/49380)| `ValueSet.expansion.contains.code`
| **`ValueSet.expansion.contains.display`**| _Equivalent_<br/>(8661/8662)| `ValueSet.expansion.contains.display`| _Equivalent_<br/>(20018/20019)| `ValueSet.expansion.contains.display`| _Equivalent_<br/>(34963/34964)| `ValueSet.expansion.contains.display`| _Equivalent_<br/>(49381/49382)| `ValueSet.expansion.contains.display`
| **`ValueSet.expansion.contains.contains`**| _Equivalent_<br/>(8663/8664)| `ValueSet.expansion.contains.contains`| _Equivalent_<br/>(20022/20023)| `ValueSet.expansion.contains.contains`| _Equivalent_<br/>(34967/34968)| `ValueSet.expansion.contains.contains`| _Equivalent_<br/>(49385/49386)| `ValueSet.expansion.contains.contains`
| *103 of 103 elements used* | | *75 of 86 elements used* <br/>remaining elements:<br/>`ValueSet.compose.inactive`, `ValueSet.compose.include.concept.designation.extension`, `ValueSet.compose.include.concept.designation.id`, `ValueSet.compose.include.concept.designation.language`, `ValueSet.compose.include.concept.designation.modifierExtension`, `ValueSet.compose.include.concept.designation.use`, `ValueSet.compose.include.concept.designation.value`, `ValueSet.compose.include.valueSet`, `ValueSet.expansion.contains.designation`, `ValueSet.expansion.contains.inactive`, `ValueSet.title`| | *74 of 85 elements used* <br/>remaining elements:<br/>`ValueSet.compose.inactive`, `ValueSet.compose.include.concept.designation.extension`, `ValueSet.compose.include.concept.designation.id`, `ValueSet.compose.include.concept.designation.language`, `ValueSet.compose.include.concept.designation.modifierExtension`, `ValueSet.compose.include.concept.designation.use`, `ValueSet.compose.include.concept.designation.value`, `ValueSet.compose.include.valueSet`, `ValueSet.expansion.contains.designation`, `ValueSet.expansion.contains.inactive`, `ValueSet.title`| | *74 of 85 elements used* <br/>remaining elements:<br/>`ValueSet.compose.inactive`, `ValueSet.compose.include.concept.designation.extension`, `ValueSet.compose.include.concept.designation.id`, `ValueSet.compose.include.concept.designation.language`, `ValueSet.compose.include.concept.designation.modifierExtension`, `ValueSet.compose.include.concept.designation.use`, `ValueSet.compose.include.concept.designation.value`, `ValueSet.compose.include.valueSet`, `ValueSet.expansion.contains.designation`, `ValueSet.expansion.contains.inactive`, `ValueSet.title`| | *74 of 124 elements used* <br/>remaining elements:<br/>`ValueSet.approvalDate`, `ValueSet.author`, `ValueSet.compose.inactive`, `ValueSet.compose.include.concept.designation.additionalUse`, `ValueSet.compose.include.concept.designation.extension`, `ValueSet.compose.include.concept.designation.id`, `ValueSet.compose.include.concept.designation.language`, `ValueSet.compose.include.concept.designation.modifierExtension`, `ValueSet.compose.include.concept.designation.use`, `ValueSet.compose.include.concept.designation.value`, `ValueSet.compose.include.copyright`, `ValueSet.compose.include.valueSet`, `ValueSet.compose.property`, `ValueSet.copyrightLabel`, `ValueSet.editor`, `ValueSet.effectivePeriod`, `ValueSet.endorser`, `ValueSet.expansion.contains.designation`, `ValueSet.expansion.contains.inactive`, `ValueSet.expansion.contains.property`, `ValueSet.expansion.contains.property.code`, `ValueSet.expansion.contains.property.extension`, `ValueSet.expansion.contains.property.id`, `ValueSet.expansion.contains.property.modifierExtension`, `ValueSet.expansion.contains.property.subProperty`, `ValueSet.expansion.contains.property.subProperty.code`, `ValueSet.expansion.contains.property.subProperty.extension`, `ValueSet.expansion.contains.property.subProperty.id`, `ValueSet.expansion.contains.property.subProperty.modifierExtension`, `ValueSet.expansion.contains.property.subProperty.value[x]`, `ValueSet.expansion.contains.property.value[x]`, `ValueSet.expansion.next`, `ValueSet.expansion.property`, `ValueSet.expansion.property.code`, `ValueSet.expansion.property.extension`, `ValueSet.expansion.property.id`, `ValueSet.expansion.property.modifierExtension`, `ValueSet.expansion.property.uri`, `ValueSet.lastReviewDate`, `ValueSet.relatedArtifact`, `ValueSet.reviewer`, `ValueSet.scope`, `ValueSet.scope.exclusionCriteria`, `ValueSet.scope.extension`, `ValueSet.scope.id`, `ValueSet.scope.inclusionCriteria`, `ValueSet.scope.modifierExtension`, `ValueSet.title`, `ValueSet.topic`, `ValueSet.versionAlgorithm[x]`

