Comparison of 
Generated at Monday, April 14, 2025 6:17:16 PM

### DeviceUseStatement

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | DeviceUseStatement |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/DeviceUseStatement` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for DeviceUseStatement Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `68` |
| Database Snapshot Count | `18` |
| Database Differential Count | `10` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `DeviceUseStatement` | `DeviceUseStatement` | `DeviceUseStatement` | DeviceUseStatement |  | 0..* | DeviceUseStatement |  |  |
| `DeviceUseStatement.bodySite[x]` | `DeviceUseStatement.bodySite[x]` | `bodySite[x]` |  | Target body site | 0..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/BodySite) |  |  |
| `DeviceUseStatement.contained` | `DeviceUseStatement.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `DeviceUseStatement.device` | `DeviceUseStatement.device` | `device` |  |  | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device) |  |  |
| `DeviceUseStatement.extension` | `DeviceUseStatement.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `DeviceUseStatement.id` | `DeviceUseStatement.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `DeviceUseStatement.identifier` | `DeviceUseStatement.identifier` | `identifier` |  |  | 0..* | Identifier |  |  |
| `DeviceUseStatement.implicitRules` | `DeviceUseStatement.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `DeviceUseStatement.indication` | `DeviceUseStatement.indication` | `indication` |  |  | 0..* | CodeableConcept |  |  |
| `DeviceUseStatement.language` | `DeviceUseStatement.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `DeviceUseStatement.meta` | `DeviceUseStatement.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `DeviceUseStatement.modifierExtension` | `DeviceUseStatement.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `DeviceUseStatement.notes` | `DeviceUseStatement.notes` | `notes` |  |  | 0..* | string |  |  |
| `DeviceUseStatement.recordedOn` | `DeviceUseStatement.recordedOn` | `recordedOn` |  |  | 0..1 | dateTime |  |  |
| `DeviceUseStatement.subject` | `DeviceUseStatement.subject` | `subject` |  |  | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `DeviceUseStatement.text` | `DeviceUseStatement.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `DeviceUseStatement.timing[x]` | `DeviceUseStatement.timing[x]` | `timing[x]` |  |  | 0..1 | dateTime, Period, Timing |  |  |
| `DeviceUseStatement.whenUsed` | `DeviceUseStatement.whenUsed` | `whenUsed` |  |  | 0..1 | Period |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [DeviceUseStatement](/docs/R2/Resources/DeviceUseStatement.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceUseStatement\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `101`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `268`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [DeviceUseStatement](/docs/R3/Resources/DeviceUseStatement.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceUseStatement\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `450`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `645`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [DeviceUseStatement](/docs/R4/Resources/DeviceUseStatement.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceUseStatement\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1463`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1464`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [DeviceUseStatement](/docs/R4B/Resources/DeviceUseStatement.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceUseStatement\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `966`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1195`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [DeviceUsage](/docs/R5/Resources/DeviceUsage.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceUsage\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition DeviceUseStatement from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 DeviceUseStatement| Relationship | [R3 DeviceUseStatement](/docs/R3/Resources/DeviceUseStatement.md)| Relationship | [R4 DeviceUseStatement](/docs/R4/Resources/DeviceUseStatement.md)| Relationship | [R4B DeviceUseStatement](/docs/R4B/Resources/DeviceUseStatement.md)| Relationship | [R5 DeviceUsage](/docs/R5/Resources/DeviceUsage.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`DeviceUseStatement`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4651)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4652)| `DeviceUseStatement`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13069)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13070)| `DeviceUseStatement`| _Equivalent_<br/>(25874/25875)| `DeviceUseStatement`| | | 
| **`DeviceUseStatement.id`**| _Equivalent_<br/>(4653/4654)| `DeviceUseStatement.id`| _Equivalent_<br/>(13071/13072)| `DeviceUseStatement.id`| _Equivalent_<br/>(25876/25877)| `DeviceUseStatement.id`| | | 
| **`DeviceUseStatement.meta`**| _Equivalent_<br/>(4655/4656)| `DeviceUseStatement.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13073)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13074)| `DeviceUseStatement.meta`| _Equivalent_<br/>(25878/25879)| `DeviceUseStatement.meta`| | | 
| **`DeviceUseStatement.implicitRules`**| _Equivalent_<br/>(4657/4658)| `DeviceUseStatement.implicitRules`| _Equivalent_<br/>(13075/13076)| `DeviceUseStatement.implicitRules`| _Equivalent_<br/>(25880/25881)| `DeviceUseStatement.implicitRules`| | | 
| **`DeviceUseStatement.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4659)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(4660)| `DeviceUseStatement.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13077)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(13078)| `DeviceUseStatement.language`| _Equivalent_<br/>(25882/25883)| `DeviceUseStatement.language`| | | 
| **`DeviceUseStatement.text`**| _Equivalent_<br/>(4661/4662)| `DeviceUseStatement.text`| _Equivalent_<br/>(13079/13080)| `DeviceUseStatement.text`| _Equivalent_<br/>(25884/25885)| `DeviceUseStatement.text`| | | 
| **`DeviceUseStatement.contained`**| _Equivalent_<br/>(4663/4664)| `DeviceUseStatement.contained`| _Equivalent_<br/>(13081/13082)| `DeviceUseStatement.contained`| _Equivalent_<br/>(25886/25887)| `DeviceUseStatement.contained`| | | 
| **`DeviceUseStatement.extension`**| _Equivalent_<br/>(4665/4666)| `DeviceUseStatement.extension`| _Equivalent_<br/>(13083/13084)| `DeviceUseStatement.extension`| _Equivalent_<br/>(25888/25889)| `DeviceUseStatement.extension`| | | 
| **`DeviceUseStatement.modifierExtension`**| _Equivalent_<br/>(4667/4668)| `DeviceUseStatement.modifierExtension`| _Equivalent_<br/>(13085/13086)| `DeviceUseStatement.modifierExtension`| _Equivalent_<br/>(25890/25891)| `DeviceUseStatement.modifierExtension`| | | 
| **`DeviceUseStatement.bodySite[x]`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(189)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(601)| `DeviceUseStatement.bodySite`| _Equivalent_<br/>(13101/13102)| `DeviceUseStatement.bodySite`| _Equivalent_<br/>(25914/25915)| `DeviceUseStatement.bodySite`| | | 
| **`DeviceUseStatement.whenUsed`**| _Equivalent_<br/>(4669/4670)| `DeviceUseStatement.whenUsed`| | | | | | | 
| **`DeviceUseStatement.device`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4671)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4672)| `DeviceUseStatement.device`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13099)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13100)| `DeviceUseStatement.device`| _Equivalent_<br/>(25908/25909)| `DeviceUseStatement.device`| | | 
| **`DeviceUseStatement.identifier`**| _Equivalent_<br/>(4673/4674)| `DeviceUseStatement.identifier`| _Equivalent_<br/>(13087/13088)| `DeviceUseStatement.identifier`| _Equivalent_<br/>(25892/25893)| `DeviceUseStatement.identifier`| | | 
| **`DeviceUseStatement.indication`**| _Equivalent_<br/>(4675/4676)| `DeviceUseStatement.indication`| _Equivalent_<br/>(999/1484)| `DeviceUseStatement.reasonCode`| _Equivalent_<br/>(25910/25911)| `DeviceUseStatement.reasonCode`| | | 
| **`DeviceUseStatement.notes`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(190)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(602)| `DeviceUseStatement.note`| _Equivalent_<br/>(13103/13104)| `DeviceUseStatement.note`| _Equivalent_<br/>(25916/25917)| `DeviceUseStatement.note`| | | 
| **`DeviceUseStatement.recordedOn`**| _Equivalent_<br/>(4677/4678)| `DeviceUseStatement.recordedOn`| _Equivalent_<br/>(13095/13096)| `DeviceUseStatement.recordedOn`| _Equivalent_<br/>(25904/25905)| `DeviceUseStatement.recordedOn`| | | 
| **`DeviceUseStatement.subject`**| →→→→ _RelatedTo_ →→→→ <br/>(4679)<hr/>←←←← _RelatedTo_ ←←←← <br/>(4680)| `DeviceUseStatement.subject`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13091)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13092)| `DeviceUseStatement.subject`| _Equivalent_<br/>(25898/25899)| `DeviceUseStatement.subject`| | | 
| **`DeviceUseStatement.timing[x]`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4681)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4682)| `DeviceUseStatement.timing[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13093)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13094)| `DeviceUseStatement.timing[x]`| _Equivalent_<br/>(25902/25903)| `DeviceUseStatement.timing[x]`| | | 
| *18 of 18 elements used* | | *18 of 20 elements used* <br/>remaining elements:<br/>`DeviceUseStatement.source`, `DeviceUseStatement.status`| | *17 of 22 elements used* <br/>remaining elements:<br/>`DeviceUseStatement.basedOn`, `DeviceUseStatement.derivedFrom`, `DeviceUseStatement.reasonReference`, `DeviceUseStatement.source`, `DeviceUseStatement.status`| | *17 of 22 elements used* <br/>remaining elements:<br/>`DeviceUseStatement.basedOn`, `DeviceUseStatement.derivedFrom`, `DeviceUseStatement.reasonReference`, `DeviceUseStatement.source`, `DeviceUseStatement.status`| | *0 of 31 elements used* <br/>remaining elements:<br/>`DeviceUsage`, `DeviceUsage.adherence`, `DeviceUsage.adherence.code`, `DeviceUsage.adherence.extension`, `DeviceUsage.adherence.id`, `DeviceUsage.adherence.modifierExtension`, `DeviceUsage.adherence.reason`, `DeviceUsage.basedOn`, `DeviceUsage.bodySite`, `DeviceUsage.category`, `DeviceUsage.contained`, `DeviceUsage.context`, `DeviceUsage.dateAsserted`, `DeviceUsage.derivedFrom`, `DeviceUsage.device`, `DeviceUsage.extension`, `DeviceUsage.id`, `DeviceUsage.identifier`, `DeviceUsage.implicitRules`, `DeviceUsage.informationSource`, `DeviceUsage.language`, `DeviceUsage.meta`, `DeviceUsage.modifierExtension`, `DeviceUsage.note`, `DeviceUsage.patient`, `DeviceUsage.reason`, `DeviceUsage.status`, `DeviceUsage.text`, `DeviceUsage.timing[x]`, `DeviceUsage.usageReason`, `DeviceUsage.usageStatus`

