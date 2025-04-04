Comparison of 
Generated at Friday, April 4, 2025 2:58:47 PM

### DeviceUseStatement

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | DeviceUseStatement |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/DeviceUseStatement` |
| Version | 4.0.1 |
| Description | A record of a device being used by a patient where the record is the result of a report from the patient or another clinician. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1069` |
| Database Snapshot Count | `22` |
| Database Differential Count | `14` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `DeviceUseStatement` | `DeviceUseStatement` | `DeviceUseStatement` | DeviceUseStatement | Record of use of a device | 0..* | DeviceUseStatement |  |  |
| `DeviceUseStatement.basedOn` | `DeviceUseStatement.basedOn` | `basedOn` | DeviceUseStatement.basedOn | Fulfills plan, proposal or order | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/ServiceRequest) |  |  |
| `DeviceUseStatement.bodySite` | `DeviceUseStatement.bodySite` | `bodySite` | DeviceUseStatement.bodySite | Target body site | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/body-site` |
| `DeviceUseStatement.contained` | `DeviceUseStatement.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `DeviceUseStatement.derivedFrom` | `DeviceUseStatement.derivedFrom` | `derivedFrom` | DeviceUseStatement.derivedFrom | Supporting information | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Claim), Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference), Reference(http://hl7.org/fhir/StructureDefinition/Observation), Reference(http://hl7.org/fhir/StructureDefinition/Procedure), Reference(http://hl7.org/fhir/StructureDefinition/QuestionnaireResponse), Reference(http://hl7.org/fhir/StructureDefinition/ServiceRequest) |  |  |
| `DeviceUseStatement.device` | `DeviceUseStatement.device` | `device` | DeviceUseStatement.device | Reference to device used | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device) |  |  |
| `DeviceUseStatement.extension` | `DeviceUseStatement.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DeviceUseStatement.id` | `DeviceUseStatement.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `DeviceUseStatement.identifier` | `DeviceUseStatement.identifier` | `identifier` | DeviceUseStatement.identifier | External identifier for this record | 0..* | Identifier |  |  |
| `DeviceUseStatement.implicitRules` | `DeviceUseStatement.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `DeviceUseStatement.language` | `DeviceUseStatement.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `DeviceUseStatement.meta` | `DeviceUseStatement.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `DeviceUseStatement.modifierExtension` | `DeviceUseStatement.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `DeviceUseStatement.note` | `DeviceUseStatement.note` | `note` | DeviceUseStatement.note | Addition details (comments, instructions) | 0..* | Annotation |  |  |
| `DeviceUseStatement.reasonCode` | `DeviceUseStatement.reasonCode` | `reasonCode` | DeviceUseStatement.reasonCode | Why device was used | 0..* | CodeableConcept |  |  |
| `DeviceUseStatement.reasonReference` | `DeviceUseStatement.reasonReference` | `reasonReference` | DeviceUseStatement.reasonReference | Why was DeviceUseStatement performed? | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Condition), Reference(http://hl7.org/fhir/StructureDefinition/DiagnosticReport), Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference), Reference(http://hl7.org/fhir/StructureDefinition/Media), Reference(http://hl7.org/fhir/StructureDefinition/Observation) |  |  |
| `DeviceUseStatement.recordedOn` | `DeviceUseStatement.recordedOn` | `recordedOn` | DeviceUseStatement.recordedOn | When statement was recorded | 0..1 | dateTime |  |  |
| `DeviceUseStatement.source` | `DeviceUseStatement.source` | `source` | DeviceUseStatement.source | Who made the statement | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `DeviceUseStatement.status` | `DeviceUseStatement.status` | `status` | DeviceUseStatement.status | active \| completed \| entered-in-error + | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/device-statement-status|4.0.1` |
| `DeviceUseStatement.subject` | `DeviceUseStatement.subject` | `subject` | DeviceUseStatement.subject | Patient using device | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `DeviceUseStatement.text` | `DeviceUseStatement.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `DeviceUseStatement.timing[x]` | `DeviceUseStatement.timing[x]` | `timing[x]` | DeviceUseStatement.timing[x] | How often  the device was used | 0..1 | dateTime, Period, Timing |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [DeviceUseStatement](/docs/R2/Resources/DeviceUseStatement.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceUseStatement\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `101`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `268`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DeviceUseStatement](/docs/R3/Resources/DeviceUseStatement.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceUseStatement\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `450`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `645`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DeviceUseStatement](/docs/R4/Resources/DeviceUseStatement.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceUseStatement\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1463`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1464`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DeviceUseStatement](/docs/R4B/Resources/DeviceUseStatement.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceUseStatement\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `966`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1195`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DeviceUsage](/docs/R5/Resources/DeviceUsage.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceUsage\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition DeviceUseStatement from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 DeviceUseStatement](/docs/R2/Resources/DeviceUseStatement.md)| Relationship | [R3 DeviceUseStatement](/docs/R3/Resources/DeviceUseStatement.md)| Relationship | R4 DeviceUseStatement| Relationship | [R4B DeviceUseStatement](/docs/R4B/Resources/DeviceUseStatement.md)| Relationship | [R5 DeviceUsage](/docs/R5/Resources/DeviceUsage.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `DeviceUseStatement`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4651)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4652)| `DeviceUseStatement`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13069)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13070)| **`DeviceUseStatement`**| _Equivalent_<br/>(25874/25875)| `DeviceUseStatement`| | | 
| `DeviceUseStatement.id`| _Equivalent_<br/>(4653/4654)| `DeviceUseStatement.id`| _Equivalent_<br/>(13071/13072)| **`DeviceUseStatement.id`**| _Equivalent_<br/>(25876/25877)| `DeviceUseStatement.id`| | | 
| `DeviceUseStatement.meta`| _Equivalent_<br/>(4655/4656)| `DeviceUseStatement.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13073)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13074)| **`DeviceUseStatement.meta`**| _Equivalent_<br/>(25878/25879)| `DeviceUseStatement.meta`| | | 
| `DeviceUseStatement.implicitRules`| _Equivalent_<br/>(4657/4658)| `DeviceUseStatement.implicitRules`| _Equivalent_<br/>(13075/13076)| **`DeviceUseStatement.implicitRules`**| _Equivalent_<br/>(25880/25881)| `DeviceUseStatement.implicitRules`| | | 
| `DeviceUseStatement.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4659)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(4660)| `DeviceUseStatement.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13077)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(13078)| **`DeviceUseStatement.language`**| _Equivalent_<br/>(25882/25883)| `DeviceUseStatement.language`| | | 
| `DeviceUseStatement.text`| _Equivalent_<br/>(4661/4662)| `DeviceUseStatement.text`| _Equivalent_<br/>(13079/13080)| **`DeviceUseStatement.text`**| _Equivalent_<br/>(25884/25885)| `DeviceUseStatement.text`| | | 
| `DeviceUseStatement.contained`| _Equivalent_<br/>(4663/4664)| `DeviceUseStatement.contained`| _Equivalent_<br/>(13081/13082)| **`DeviceUseStatement.contained`**| _Equivalent_<br/>(25886/25887)| `DeviceUseStatement.contained`| | | 
| `DeviceUseStatement.extension`| _Equivalent_<br/>(4665/4666)| `DeviceUseStatement.extension`| _Equivalent_<br/>(13083/13084)| **`DeviceUseStatement.extension`**| _Equivalent_<br/>(25888/25889)| `DeviceUseStatement.extension`| | | 
| `DeviceUseStatement.modifierExtension`| _Equivalent_<br/>(4667/4668)| `DeviceUseStatement.modifierExtension`| _Equivalent_<br/>(13085/13086)| **`DeviceUseStatement.modifierExtension`**| _Equivalent_<br/>(25890/25891)| `DeviceUseStatement.modifierExtension`| | | 
| `DeviceUseStatement.identifier`| _Equivalent_<br/>(4673/4674)| `DeviceUseStatement.identifier`| _Equivalent_<br/>(13087/13088)| **`DeviceUseStatement.identifier`**| _Equivalent_<br/>(25892/25893)| `DeviceUseStatement.identifier`| | | 
| | | | | **`DeviceUseStatement.basedOn`**| _Equivalent_<br/>(25894/25895)| `DeviceUseStatement.basedOn`| | | 
| | | `DeviceUseStatement.status`| _Equivalent_<br/>(13089/13090)| **`DeviceUseStatement.status`**| _Equivalent_<br/>(25896/25897)| `DeviceUseStatement.status`| | | 
| `DeviceUseStatement.subject`| →→→→ _RelatedTo_ →→→→ <br/>(4679)<hr/>←←←← _RelatedTo_ ←←←← <br/>(4680)| `DeviceUseStatement.subject`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13091)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13092)| **`DeviceUseStatement.subject`**| _Equivalent_<br/>(25898/25899)| `DeviceUseStatement.subject`| | | 
| | | | | **`DeviceUseStatement.derivedFrom`**| _Equivalent_<br/>(25900/25901)| `DeviceUseStatement.derivedFrom`| | | 
| `DeviceUseStatement.timing[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4681)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4682)| `DeviceUseStatement.timing[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13093)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13094)| **`DeviceUseStatement.timing[x]`**| _Equivalent_<br/>(25902/25903)| `DeviceUseStatement.timing[x]`| | | 
| `DeviceUseStatement.recordedOn`| _Equivalent_<br/>(4677/4678)| `DeviceUseStatement.recordedOn`| _Equivalent_<br/>(13095/13096)| **`DeviceUseStatement.recordedOn`**| _Equivalent_<br/>(25904/25905)| `DeviceUseStatement.recordedOn`| | | 
| | | `DeviceUseStatement.source`| →→→→ _RelatedTo_ →→→→ <br/>(13097)<hr/>←←←← _RelatedTo_ ←←←← <br/>(13098)| **`DeviceUseStatement.source`**| _Equivalent_<br/>(25906/25907)| `DeviceUseStatement.source`| | | 
| `DeviceUseStatement.device`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4671)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4672)| `DeviceUseStatement.device`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13099)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13100)| **`DeviceUseStatement.device`**| _Equivalent_<br/>(25908/25909)| `DeviceUseStatement.device`| | | 
| `DeviceUseStatement.indication`| _Equivalent_<br/>(4675/4676)| `DeviceUseStatement.indication`| _Equivalent_<br/>(999/1484)| **`DeviceUseStatement.reasonCode`**| _Equivalent_<br/>(25910/25911)| `DeviceUseStatement.reasonCode`| | | 
| | | | | **`DeviceUseStatement.reasonReference`**| _Equivalent_<br/>(25912/25913)| `DeviceUseStatement.reasonReference`| | | 
| `DeviceUseStatement.bodySite[x]`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(189)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(601)| `DeviceUseStatement.bodySite`| _Equivalent_<br/>(13101/13102)| **`DeviceUseStatement.bodySite`**| _Equivalent_<br/>(25914/25915)| `DeviceUseStatement.bodySite`| | | 
| `DeviceUseStatement.notes`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(190)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(602)| `DeviceUseStatement.note`| _Equivalent_<br/>(13103/13104)| **`DeviceUseStatement.note`**| _Equivalent_<br/>(25916/25917)| `DeviceUseStatement.note`| | | 
| *17 of 18 elements used* <br/>remaining elements:<br/>`DeviceUseStatement.whenUsed`| | *19 of 20 elements used* <br/>remaining elements:<br/>`DeviceUseStatement.whenUsed`| | *22 of 22 elements used* | | *22 of 22 elements used* | | *0 of 31 elements used* <br/>remaining elements:<br/>`DeviceUsage`, `DeviceUsage.adherence`, `DeviceUsage.adherence.code`, `DeviceUsage.adherence.extension`, `DeviceUsage.adherence.id`, `DeviceUsage.adherence.modifierExtension`, `DeviceUsage.adherence.reason`, `DeviceUsage.basedOn`, `DeviceUsage.bodySite`, `DeviceUsage.category`, `DeviceUsage.contained`, `DeviceUsage.context`, `DeviceUsage.dateAsserted`, `DeviceUsage.derivedFrom`, `DeviceUsage.device`, `DeviceUsage.extension`, `DeviceUsage.id`, `DeviceUsage.identifier`, `DeviceUsage.implicitRules`, `DeviceUsage.informationSource`, `DeviceUsage.language`, `DeviceUsage.meta`, `DeviceUsage.modifierExtension`, `DeviceUsage.note`, `DeviceUsage.patient`, `DeviceUsage.reason`, `DeviceUsage.status`, `DeviceUsage.text`, `DeviceUsage.timing[x]`, `DeviceUsage.usageReason`, `DeviceUsage.usageStatus`

