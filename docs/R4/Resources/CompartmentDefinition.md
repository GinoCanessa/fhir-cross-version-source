Comparison of 
Generated at Friday, April 4, 2025 2:58:45 PM

### CompartmentDefinition

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | CompartmentDefinition |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/CompartmentDefinition` |
| Version | 4.0.1 |
| Description | A compartment definition that defines how resources are accessed on a server. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1055` |
| Database Snapshot Count | `29` |
| Database Differential Count | `18` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `CompartmentDefinition` | `CompartmentDefinition` | `CompartmentDefinition` | CompartmentDefinition | Compartment Definition for a resource | 0..* | CompartmentDefinition |  |  |
| `CompartmentDefinition.code` | `CompartmentDefinition.code` | `code` | CompartmentDefinition.code | Patient \| Encounter \| RelatedPerson \| Practitioner \| Device | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/compartment-type|4.0.1` |
| `CompartmentDefinition.contact` | `CompartmentDefinition.contact` | `contact` | CompartmentDefinition.contact | Contact details for the publisher | 0..* | ContactDetail |  |  |
| `CompartmentDefinition.contained` | `CompartmentDefinition.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `CompartmentDefinition.date` | `CompartmentDefinition.date` | `date` | CompartmentDefinition.date | Date last changed | 0..1 | dateTime |  |  |
| `CompartmentDefinition.description` | `CompartmentDefinition.description` | `description` | CompartmentDefinition.description | Natural language description of the compartment definition | 0..1 | markdown |  |  |
| `CompartmentDefinition.experimental` | `CompartmentDefinition.experimental` | `experimental` | CompartmentDefinition.experimental | For testing purposes, not real usage | 0..1 | boolean |  |  |
| `CompartmentDefinition.extension` | `CompartmentDefinition.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `CompartmentDefinition.id` | `CompartmentDefinition.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `CompartmentDefinition.implicitRules` | `CompartmentDefinition.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `CompartmentDefinition.language` | `CompartmentDefinition.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `CompartmentDefinition.meta` | `CompartmentDefinition.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `CompartmentDefinition.modifierExtension` | `CompartmentDefinition.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `CompartmentDefinition.name` | `CompartmentDefinition.name` | `name` | CompartmentDefinition.name | Name for this compartment definition (computer friendly) | 1..1 | string |  |  |
| `CompartmentDefinition.publisher` | `CompartmentDefinition.publisher` | `publisher` | CompartmentDefinition.publisher | Name of the publisher (organization or individual) | 0..1 | string |  |  |
| `CompartmentDefinition.purpose` | `CompartmentDefinition.purpose` | `purpose` | CompartmentDefinition.purpose | Why this compartment definition is defined | 0..1 | markdown |  |  |
| `CompartmentDefinition.resource` | `CompartmentDefinition.resource` | `resource` | CompartmentDefinition.resource | How a resource is related to the compartment | 0..* | BackboneElement |  |  |
| `CompartmentDefinition.resource.code` | `CompartmentDefinition.resource.code` | `code` | CompartmentDefinition.resource.code | Name of resource type | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/resource-types|4.0.1` |
| `CompartmentDefinition.resource.documentation` | `CompartmentDefinition.resource.documentation` | `documentation` | CompartmentDefinition.resource.documentation | Additional documentation about the resource and compartment | 0..1 | string |  |  |
| `CompartmentDefinition.resource.extension` | `CompartmentDefinition.resource.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `CompartmentDefinition.resource.id` | `CompartmentDefinition.resource.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `CompartmentDefinition.resource.modifierExtension` | `CompartmentDefinition.resource.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `CompartmentDefinition.resource.param` | `CompartmentDefinition.resource.param` | `param` | CompartmentDefinition.resource.param | Search Parameter Name, or chained parameters | 0..* | string |  |  |
| `CompartmentDefinition.search` | `CompartmentDefinition.search` | `search` | CompartmentDefinition.search | Whether the search syntax is supported | 1..1 | boolean |  |  |
| `CompartmentDefinition.status` | `CompartmentDefinition.status` | `status` | CompartmentDefinition.status | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status|4.0.1` |
| `CompartmentDefinition.text` | `CompartmentDefinition.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `CompartmentDefinition.url` | `CompartmentDefinition.url` | `url` | CompartmentDefinition.url | Canonical identifier for this compartment definition, represented as a URI (globally unique) | 1..1 | uri |  |  |
| `CompartmentDefinition.useContext` | `CompartmentDefinition.useContext` | `useContext` | CompartmentDefinition.useContext | The context that the content is intended to support | 0..* | UsageContext |  |  |
| `CompartmentDefinition.version` | `CompartmentDefinition.version` | `version` | CompartmentDefinition.version | Business version of the compartment definition | 0..1 | string |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [CompartmentDefinition](/docs/R3/Resources/CompartmentDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/CompartmentDefinition\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `436`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `632`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CompartmentDefinition](/docs/R4/Resources/CompartmentDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/CompartmentDefinition\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1435`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1436`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CompartmentDefinition](/docs/R4B/Resources/CompartmentDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/CompartmentDefinition\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `952`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1181`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CompartmentDefinition](/docs/R5/Resources/CompartmentDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/CompartmentDefinition\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition CompartmentDefinition from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | [R3 CompartmentDefinition](/docs/R3/Resources/CompartmentDefinition.md)| Relationship | R4 CompartmentDefinition| Relationship | [R4B CompartmentDefinition](/docs/R4B/Resources/CompartmentDefinition.md)| Relationship | [R5 CompartmentDefinition](/docs/R5/Resources/CompartmentDefinition.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | `CompartmentDefinition`| →→→→ _RelatedTo_ →→→→ <br/>(12135)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(12136)| **`CompartmentDefinition`**| _Equivalent_<br/>(23957/23958)| `CompartmentDefinition`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(39263)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(39264)| `CompartmentDefinition`
| | | `CompartmentDefinition.id`| _Equivalent_<br/>(12137/12138)| **`CompartmentDefinition.id`**| _Equivalent_<br/>(23959/23960)| `CompartmentDefinition.id`| _Equivalent_<br/>(39265/39266)| `CompartmentDefinition.id`
| | | `CompartmentDefinition.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12139)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12140)| **`CompartmentDefinition.meta`**| _Equivalent_<br/>(23961/23962)| `CompartmentDefinition.meta`| _Equivalent_<br/>(39267/39268)| `CompartmentDefinition.meta`
| | | `CompartmentDefinition.implicitRules`| _Equivalent_<br/>(12141/12142)| **`CompartmentDefinition.implicitRules`**| _Equivalent_<br/>(23963/23964)| `CompartmentDefinition.implicitRules`| _Equivalent_<br/>(39269/39270)| `CompartmentDefinition.implicitRules`
| | | `CompartmentDefinition.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12143)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(12144)| **`CompartmentDefinition.language`**| _Equivalent_<br/>(23965/23966)| `CompartmentDefinition.language`| _Equivalent_<br/>(39271/39272)| `CompartmentDefinition.language`
| | | `CompartmentDefinition.text`| _Equivalent_<br/>(12145/12146)| **`CompartmentDefinition.text`**| _Equivalent_<br/>(23967/23968)| `CompartmentDefinition.text`| _Equivalent_<br/>(39273/39274)| `CompartmentDefinition.text`
| | | `CompartmentDefinition.contained`| _Equivalent_<br/>(12147/12148)| **`CompartmentDefinition.contained`**| _Equivalent_<br/>(23969/23970)| `CompartmentDefinition.contained`| _Equivalent_<br/>(39275/39276)| `CompartmentDefinition.contained`
| | | `CompartmentDefinition.extension`| _Equivalent_<br/>(12149/12150)| **`CompartmentDefinition.extension`**| _Equivalent_<br/>(23971/23972)| `CompartmentDefinition.extension`| _Equivalent_<br/>(39277/39278)| `CompartmentDefinition.extension`
| | | `CompartmentDefinition.modifierExtension`| _Equivalent_<br/>(12151/12152)| **`CompartmentDefinition.modifierExtension`**| _Equivalent_<br/>(23973/23974)| `CompartmentDefinition.modifierExtension`| _Equivalent_<br/>(39279/39280)| `CompartmentDefinition.modifierExtension`
| | | `CompartmentDefinition.url`| _Equivalent_<br/>(12153/12154)| **`CompartmentDefinition.url`**| _Equivalent_<br/>(23975/23976)| `CompartmentDefinition.url`| _Equivalent_<br/>(39281/39282)| `CompartmentDefinition.url`
| | | | | **`CompartmentDefinition.version`**| _Equivalent_<br/>(23977/23978)| `CompartmentDefinition.version`| _Equivalent_<br/>(39283/39284)| `CompartmentDefinition.version`
| | | `CompartmentDefinition.name`| _Equivalent_<br/>(12155/12156)| **`CompartmentDefinition.name`**| _Equivalent_<br/>(23979/23980)| `CompartmentDefinition.name`| _Equivalent_<br/>(39285/39286)| `CompartmentDefinition.name`
| | | `CompartmentDefinition.status`| _Equivalent_<br/>(12157/12158)| **`CompartmentDefinition.status`**| _Equivalent_<br/>(23981/23982)| `CompartmentDefinition.status`| _Equivalent_<br/>(39287/39288)| `CompartmentDefinition.status`
| | | `CompartmentDefinition.experimental`| _Equivalent_<br/>(12159/12160)| **`CompartmentDefinition.experimental`**| _Equivalent_<br/>(23983/23984)| `CompartmentDefinition.experimental`| _Equivalent_<br/>(39289/39290)| `CompartmentDefinition.experimental`
| | | `CompartmentDefinition.date`| _Equivalent_<br/>(12161/12162)| **`CompartmentDefinition.date`**| _Equivalent_<br/>(23985/23986)| `CompartmentDefinition.date`| _Equivalent_<br/>(39291/39292)| `CompartmentDefinition.date`
| | | `CompartmentDefinition.publisher`| _Equivalent_<br/>(12163/12164)| **`CompartmentDefinition.publisher`**| _Equivalent_<br/>(23987/23988)| `CompartmentDefinition.publisher`| _Equivalent_<br/>(39293/39294)| `CompartmentDefinition.publisher`
| | | `CompartmentDefinition.contact`| _Equivalent_<br/>(12165/12166)| **`CompartmentDefinition.contact`**| _Equivalent_<br/>(23989/23990)| `CompartmentDefinition.contact`| _Equivalent_<br/>(39295/39296)| `CompartmentDefinition.contact`
| | | `CompartmentDefinition.description`| _Equivalent_<br/>(12167/12168)| **`CompartmentDefinition.description`**| _Equivalent_<br/>(23991/23992)| `CompartmentDefinition.description`| _Equivalent_<br/>(39297/39298)| `CompartmentDefinition.description`
| | | `CompartmentDefinition.useContext`| _Equivalent_<br/>(12171/12172)| **`CompartmentDefinition.useContext`**| _Equivalent_<br/>(23993/23994)| `CompartmentDefinition.useContext`| _Equivalent_<br/>(39299/39300)| `CompartmentDefinition.useContext`
| | | `CompartmentDefinition.purpose`| _Equivalent_<br/>(12169/12170)| **`CompartmentDefinition.purpose`**| _Equivalent_<br/>(23995/23996)| `CompartmentDefinition.purpose`| _Equivalent_<br/>(39301/39302)| `CompartmentDefinition.purpose`
| | | `CompartmentDefinition.code`| _Equivalent_<br/>(12173/12174)| **`CompartmentDefinition.code`**| _Equivalent_<br/>(23997/23998)| `CompartmentDefinition.code`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(39303)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(39304)| `CompartmentDefinition.code`
| | | `CompartmentDefinition.search`| _Equivalent_<br/>(12175/12176)| **`CompartmentDefinition.search`**| _Equivalent_<br/>(23999/24000)| `CompartmentDefinition.search`| _Equivalent_<br/>(39305/39306)| `CompartmentDefinition.search`
| | | `CompartmentDefinition.resource`| _Equivalent_<br/>(12177/12178)| **`CompartmentDefinition.resource`**| _Equivalent_<br/>(24001/24002)| `CompartmentDefinition.resource`| _Equivalent_<br/>(39307/39308)| `CompartmentDefinition.resource`
| | | `CompartmentDefinition.resource.id`| _Equivalent_<br/>(12179/12180)| **`CompartmentDefinition.resource.id`**| _Equivalent_<br/>(24003/24004)| `CompartmentDefinition.resource.id`| _Equivalent_<br/>(39309/39310)| `CompartmentDefinition.resource.id`
| | | `CompartmentDefinition.resource.extension`| _Equivalent_<br/>(12181/12182)| **`CompartmentDefinition.resource.extension`**| _Equivalent_<br/>(24005/24006)| `CompartmentDefinition.resource.extension`| _Equivalent_<br/>(39311/39312)| `CompartmentDefinition.resource.extension`
| | | `CompartmentDefinition.resource.modifierExtension`| _Equivalent_<br/>(12183/12184)| **`CompartmentDefinition.resource.modifierExtension`**| _Equivalent_<br/>(24007/24008)| `CompartmentDefinition.resource.modifierExtension`| _Equivalent_<br/>(39313/39314)| `CompartmentDefinition.resource.modifierExtension`
| | | `CompartmentDefinition.resource.code`| →→→→ _Equivalent_ →→→→ <br/>(12185)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12186)| **`CompartmentDefinition.resource.code`**| →→→→ _Equivalent_ →→→→ <br/>(24009)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(24010)| `CompartmentDefinition.resource.code`| →→→→ _Equivalent_ →→→→ <br/>(39315)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(39316)| `CompartmentDefinition.resource.code`
| | | `CompartmentDefinition.resource.param`| _Equivalent_<br/>(12187/12188)| **`CompartmentDefinition.resource.param`**| _Equivalent_<br/>(24011/24012)| `CompartmentDefinition.resource.param`| _Equivalent_<br/>(39317/39318)| `CompartmentDefinition.resource.param`
| | | `CompartmentDefinition.resource.documentation`| _Equivalent_<br/>(12189/12190)| **`CompartmentDefinition.resource.documentation`**| _Equivalent_<br/>(24013/24014)| `CompartmentDefinition.resource.documentation`| _Equivalent_<br/>(39319/39320)| `CompartmentDefinition.resource.documentation`
| | | *28 of 30 elements used* <br/>remaining elements:<br/>`CompartmentDefinition.jurisdiction`, `CompartmentDefinition.title`| | *29 of 29 elements used* | | *29 of 29 elements used* | | *29 of 33 elements used* <br/>remaining elements:<br/>`CompartmentDefinition.resource.endParam`, `CompartmentDefinition.resource.startParam`, `CompartmentDefinition.title`, `CompartmentDefinition.versionAlgorithm[x]`

