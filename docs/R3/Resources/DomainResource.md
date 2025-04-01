Comparison of 
Generated at Tuesday, April 1, 2025 1:39:15 PM

### DomainResource

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | DomainResource |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/DomainResource` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for DomainResource Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `513` |
| Database Snapshot Count | `9` |
| Database Differential Count | `5` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `DomainResource` | `DomainResource` | `DomainResource` | DomainResource | A resource with narrative, extensions, and contained resources | 0..* | DomainResource |  |  |
| `DomainResource.contained` | `DomainResource.contained` | `contained` |  | Contained, inline Resources | 0..* | Resource |  |  |
| `DomainResource.extension` | `DomainResource.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `DomainResource.id` | `DomainResource.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `DomainResource.implicitRules` | `DomainResource.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `DomainResource.language` | `DomainResource.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `DomainResource.meta` | `DomainResource.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `DomainResource.modifierExtension` | `DomainResource.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `DomainResource.text` | `DomainResource.text` | `text` |  | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [DomainResource](/docs/R2/Resources/DomainResource.md)<br/> `http://hl7.org/fhir/StructureDefinition/DomainResource\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1295`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1296`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DomainResource](/docs/R3/Resources/DomainResource.md)<br/> `http://hl7.org/fhir/StructureDefinition/DomainResource\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1303`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1304`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DomainResource](/docs/R4/Resources/DomainResource.md)<br/> `http://hl7.org/fhir/StructureDefinition/DomainResource\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1471`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1472`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DomainResource](/docs/R4B/Resources/DomainResource.md)<br/> `http://hl7.org/fhir/StructureDefinition/DomainResource\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1655`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1656`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DomainResource](/docs/R5/Resources/DomainResource.md)<br/> `http://hl7.org/fhir/StructureDefinition/DomainResource\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition DomainResource from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 DomainResource](/docs/R2/Resources/DomainResource.md)| Relationship | R3 DomainResource| Relationship | [R4 DomainResource](/docs/R4/Resources/DomainResource.md)| Relationship | [R4B DomainResource](/docs/R4B/Resources/DomainResource.md)| Relationship | [R5 DomainResource](/docs/R5/Resources/DomainResource.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `DomainResource`| _Equivalent_<br/>(4926/4927)| **`DomainResource`**| _Equivalent_<br/>(13307/13308)| `DomainResource`| _Equivalent_<br/>(26129/26130)| `DomainResource`| _Equivalent_<br/>(40912/40913)| `DomainResource`
| `DomainResource.id`| _Equivalent_<br/>(4928/4929)| **`DomainResource.id`**| _Equivalent_<br/>(13309/13310)| `DomainResource.id`| _Equivalent_<br/>(26131/26132)| `DomainResource.id`| _Equivalent_<br/>(40914/40915)| `DomainResource.id`
| `DomainResource.meta`| _Equivalent_<br/>(4930/4931)| **`DomainResource.meta`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13311)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13312)| `DomainResource.meta`| _Equivalent_<br/>(26133/26134)| `DomainResource.meta`| _Equivalent_<br/>(40916/40917)| `DomainResource.meta`
| `DomainResource.implicitRules`| _Equivalent_<br/>(4932/4933)| **`DomainResource.implicitRules`**| _Equivalent_<br/>(13313/13314)| `DomainResource.implicitRules`| _Equivalent_<br/>(26135/26136)| `DomainResource.implicitRules`| _Equivalent_<br/>(40918/40919)| `DomainResource.implicitRules`
| `DomainResource.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4934)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(4935)| **`DomainResource.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13315)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(13316)| `DomainResource.language`| _Equivalent_<br/>(26137/26138)| `DomainResource.language`| _Equivalent_<br/>(40920/40921)| `DomainResource.language`
| `DomainResource.text`| _Equivalent_<br/>(4936/4937)| **`DomainResource.text`**| _Equivalent_<br/>(13317/13318)| `DomainResource.text`| _Equivalent_<br/>(26139/26140)| `DomainResource.text`| _Equivalent_<br/>(40922/40923)| `DomainResource.text`
| `DomainResource.contained`| _Equivalent_<br/>(4938/4939)| **`DomainResource.contained`**| _Equivalent_<br/>(13319/13320)| `DomainResource.contained`| _Equivalent_<br/>(26141/26142)| `DomainResource.contained`| _Equivalent_<br/>(40924/40925)| `DomainResource.contained`
| `DomainResource.extension`| _Equivalent_<br/>(4940/4941)| **`DomainResource.extension`**| _Equivalent_<br/>(13321/13322)| `DomainResource.extension`| _Equivalent_<br/>(26143/26144)| `DomainResource.extension`| _Equivalent_<br/>(40926/40927)| `DomainResource.extension`
| `DomainResource.modifierExtension`| _Equivalent_<br/>(4942/4943)| **`DomainResource.modifierExtension`**| _Equivalent_<br/>(13323/13324)| `DomainResource.modifierExtension`| _Equivalent_<br/>(26145/26146)| `DomainResource.modifierExtension`| _Equivalent_<br/>(40928/40929)| `DomainResource.modifierExtension`
| *9 of 9 elements used* | | *9 of 9 elements used* | | *9 of 9 elements used* | | *9 of 9 elements used* | | *9 of 9 elements used* 

