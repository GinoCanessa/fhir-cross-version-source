Comparison of 
Generated at Tuesday, April 1, 2025 1:39:14 PM

### DataElement

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | DataElement |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/DataElement` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for DataElement Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `503` |
| Database Snapshot Count | `32` |
| Database Differential Count | `21` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `DataElement` | `DataElement` | `DataElement` | DataElement | Resource data element | 0..* | DataElement |  |  |
| `DataElement.contact` | `DataElement.contact` | `contact` |  | Contact details for the publisher | 0..* | ContactDetail |  |  |
| `DataElement.contained` | `DataElement.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `DataElement.copyright` | `DataElement.copyright` | `copyright` |  | Use and/or publishing restrictions | 0..1 | markdown |  |  |
| `DataElement.date` | `DataElement.date` | `date` |  | Date this was last changed | 0..1 | dateTime |  |  |
| `DataElement.element` | `DataElement.element` | `element` |  | Definition of element | 1..* | ElementDefinition |  |  |
| `DataElement.experimental` | `DataElement.experimental` | `experimental` |  | For testing purposes, not real usage | 0..1 | boolean |  |  |
| `DataElement.extension` | `DataElement.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `DataElement.id` | `DataElement.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `DataElement.identifier` | `DataElement.identifier` | `identifier` |  | Additional identifier for the data element | 0..* | Identifier |  |  |
| `DataElement.implicitRules` | `DataElement.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `DataElement.jurisdiction` | `DataElement.jurisdiction` | `jurisdiction` |  | Intended jurisdiction for data element (if applicable) | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/jurisdiction` |
| `DataElement.language` | `DataElement.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `DataElement.mapping` | `DataElement.mapping` | `mapping` |  | External specification mapped to | 0..* | BackboneElement |  |  |
| `DataElement.mapping.comment` | `DataElement.mapping.comment` | `comment` |  | Versions, issues, scope limitations, etc. | 0..1 | string |  |  |
| `DataElement.mapping.extension` | `DataElement.mapping.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `DataElement.mapping.id` | `DataElement.mapping.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `DataElement.mapping.identity` | `DataElement.mapping.identity` | `identity` |  | Internal id when this mapping is used | 1..1 | id |  |  |
| `DataElement.mapping.modifierExtension` | `DataElement.mapping.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `DataElement.mapping.name` | `DataElement.mapping.name` | `name` |  | Names what this mapping refers to | 0..1 | string |  |  |
| `DataElement.mapping.uri` | `DataElement.mapping.uri` | `uri` |  | Identifies what this mapping refers to | 0..1 | uri |  |  |
| `DataElement.meta` | `DataElement.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `DataElement.modifierExtension` | `DataElement.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `DataElement.name` | `DataElement.name` | `name` |  | Name for this data element (computer friendly) | 0..1 | string |  |  |
| `DataElement.publisher` | `DataElement.publisher` | `publisher` |  | Name of the publisher (organization or individual) | 0..1 | string |  |  |
| `DataElement.status` | `DataElement.status` | `status` |  | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status` |
| `DataElement.stringency` | `DataElement.stringency` | `stringency` |  | comparable \| fully-specified \| equivalent \| convertable \| scaleable \| flexible | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/dataelement-stringency` |
| `DataElement.text` | `DataElement.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `DataElement.title` | `DataElement.title` | `title` |  | Name for this data element (human friendly) | 0..1 | string |  |  |
| `DataElement.url` | `DataElement.url` | `url` |  | Logical URI to reference this data element (globally unique) | 0..1 | uri |  |  |
| `DataElement.useContext` | `DataElement.useContext` | `useContext` |  | Context the content is intended to support | 0..* | UsageContext |  |  |
| `DataElement.version` | `DataElement.version` | `version` |  | Business version of the data element | 0..1 | string |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [DataElement](/docs/R2/Resources/DataElement.md)<br/> `http://hl7.org/fhir/StructureDefinition/DataElement\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `93`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `260`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DataElement](/docs/R3/Resources/DataElement.md)<br/> `http://hl7.org/fhir/StructureDefinition/DataElement\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `443`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `712`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [StructureDefinition](/docs/R4/Resources/StructureDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/StructureDefinition\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1621`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1622`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [StructureDefinition](/docs/R4B/Resources/StructureDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/StructureDefinition\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1044`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1273`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [StructureDefinition](/docs/R5/Resources/StructureDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/StructureDefinition\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition DataElement from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 DataElement](/docs/R2/Resources/DataElement.md)| Relationship | R3 DataElement| Relationship | [R4 StructureDefinition](/docs/R4/Resources/StructureDefinition.md)| Relationship | [R4B StructureDefinition](/docs/R4B/Resources/StructureDefinition.md)| Relationship | [R5 StructureDefinition](/docs/R5/Resources/StructureDefinition.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `DataElement`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4377)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(4378)| **`DataElement`**| | | | | | | 
| `DataElement.id`| _Equivalent_<br/>(4379/4380)| **`DataElement.id`**| | | | | | | 
| `DataElement.meta`| _Equivalent_<br/>(4381/4382)| **`DataElement.meta`**| | | | | | | 
| `DataElement.implicitRules`| _Equivalent_<br/>(4383/4384)| **`DataElement.implicitRules`**| | | | | | | 
| `DataElement.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4385)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(4386)| **`DataElement.language`**| | | | | | | 
| `DataElement.text`| _Equivalent_<br/>(4387/4388)| **`DataElement.text`**| | | | | | | 
| `DataElement.contained`| _Equivalent_<br/>(4389/4390)| **`DataElement.contained`**| | | | | | | 
| `DataElement.extension`| _Equivalent_<br/>(4391/4392)| **`DataElement.extension`**| | | | | | | 
| `DataElement.modifierExtension`| _Equivalent_<br/>(4393/4394)| **`DataElement.modifierExtension`**| | | | | | | 
| `DataElement.url`| _Equivalent_<br/>(4395/4396)| **`DataElement.url`**| | | | | | | 
| `DataElement.identifier`| _Equivalent_<br/>(4397/4398)| **`DataElement.identifier`**| | | | | | | 
| `DataElement.version`| _Equivalent_<br/>(4399/4400)| **`DataElement.version`**| | | | | | | 
| `DataElement.status`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4403)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4404)| **`DataElement.status`**| | | | | | | 
| `DataElement.experimental`| _Equivalent_<br/>(4405/4406)| **`DataElement.experimental`**| | | | | | | 
| `DataElement.date`| _Equivalent_<br/>(4416/4417)| **`DataElement.date`**| | | | | | | 
| `DataElement.publisher`| _Equivalent_<br/>(4407/4408)| **`DataElement.publisher`**| | | | | | | 
| `DataElement.name`| _Equivalent_<br/>(4401/4402)| **`DataElement.name`**| | | | | | | 
| | | **`DataElement.title`**| | | | | | | 
| `DataElement.contact`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4409)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4410)| **`DataElement.contact`**| | | | | | | 
| `DataElement.useContext`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4418)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4419)| **`DataElement.useContext`**| | | | | | | 
| | | **`DataElement.jurisdiction`**| | | | | | | 
| `DataElement.copyright`| _Equivalent_<br/>(4420/4421)| **`DataElement.copyright`**| | | | | | | 
| `DataElement.stringency`| _Equivalent_<br/>(4422/4423)| **`DataElement.stringency`**| | | | | | | 
| `DataElement.mapping`| _Equivalent_<br/>(4424/4425)| **`DataElement.mapping`**| | | | | | | 
| `DataElement.mapping.id`| _Equivalent_<br/>(4426/4427)| **`DataElement.mapping.id`**| | | | | | | 
| `DataElement.mapping.extension`| _Equivalent_<br/>(4428/4429)| **`DataElement.mapping.extension`**| | | | | | | 
| `DataElement.mapping.modifierExtension`| _Equivalent_<br/>(4430/4431)| **`DataElement.mapping.modifierExtension`**| | | | | | | 
| `DataElement.mapping.identity`| _Equivalent_<br/>(4432/4433)| **`DataElement.mapping.identity`**| | | | | | | 
| `DataElement.mapping.uri`| _Equivalent_<br/>(4434/4435)| **`DataElement.mapping.uri`**| | | | | | | 
| `DataElement.mapping.name`| _Equivalent_<br/>(4436/4437)| **`DataElement.mapping.name`**| | | | | | | 
| `DataElement.mapping.comments`| _Equivalent_<br/>(178/592)| **`DataElement.mapping.comment`**| | | | | | | 
| `DataElement.element`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4438)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4439)| **`DataElement.element`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(978)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1674)| `StructureDefinition.differential.element`| _Equivalent_<br/>(33540/33541)| `StructureDefinition.differential.element`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(47706)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47707)| `StructureDefinition.differential.element`
| *30 of 35 elements used* | | *32 of 32 elements used* | | *1 of 56 elements used* | | *1 of 56 elements used* | | *1 of 58 elements used* 

