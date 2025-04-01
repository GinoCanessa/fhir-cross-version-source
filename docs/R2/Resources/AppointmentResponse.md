Comparison of 
Generated at Tuesday, April 1, 2025 1:39:07 PM

### AppointmentResponse

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | AppointmentResponse |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/AppointmentResponse` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for AppointmentResponse Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `44` |
| Database Snapshot Count | `17` |
| Database Differential Count | `9` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `AppointmentResponse` | `AppointmentResponse` | `AppointmentResponse` | AppointmentResponse | A reply to an appointment request for a patient and/or practitioner(s), such as a confirmation or rejection | 0..* | AppointmentResponse |  |  |
| `AppointmentResponse.actor` | `AppointmentResponse.actor` | `actor` |  | Person, Location/HealthcareService or Device | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/HealthcareService), Reference(http://hl7.org/fhir/StructureDefinition/Location), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `AppointmentResponse.appointment` | `AppointmentResponse.appointment` | `appointment` |  | Appointment this response relates to | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Appointment) |  |  |
| `AppointmentResponse.comment` | `AppointmentResponse.comment` | `comment` |  | Additional comments | 0..1 | string |  |  |
| `AppointmentResponse.contained` | `AppointmentResponse.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `AppointmentResponse.end` | `AppointmentResponse.end` | `end` |  | Time from appointment, or requested new end time | 0..1 | instant |  |  |
| `AppointmentResponse.extension` | `AppointmentResponse.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `AppointmentResponse.id` | `AppointmentResponse.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `AppointmentResponse.identifier` | `AppointmentResponse.identifier` | `identifier` |  | External Ids for this item | 0..* | Identifier |  |  |
| `AppointmentResponse.implicitRules` | `AppointmentResponse.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `AppointmentResponse.language` | `AppointmentResponse.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `AppointmentResponse.meta` | `AppointmentResponse.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `AppointmentResponse.modifierExtension` | `AppointmentResponse.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `AppointmentResponse.participantStatus` | `AppointmentResponse.participantStatus` | `participantStatus` |  | accepted \| declined \| tentative \| in-process \| completed \| needs-action | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/participantstatus` |
| `AppointmentResponse.participantType` | `AppointmentResponse.participantType` | `participantType` |  | Role of participant in the appointment | 0..* | CodeableConcept | `Required` | `http://hl7.org/fhir/ValueSet/encounter-participant-type` |
| `AppointmentResponse.start` | `AppointmentResponse.start` | `start` |  | Time from appointment, or requested new start time | 0..1 | instant |  |  |
| `AppointmentResponse.text` | `AppointmentResponse.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [AppointmentResponse](/docs/R2/Resources/AppointmentResponse.md)<br/> `http://hl7.org/fhir/StructureDefinition/AppointmentResponse\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `75`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `241`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AppointmentResponse](/docs/R3/Resources/AppointmentResponse.md)<br/> `http://hl7.org/fhir/StructureDefinition/AppointmentResponse\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `420`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `616`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AppointmentResponse](/docs/R4/Resources/AppointmentResponse.md)<br/> `http://hl7.org/fhir/StructureDefinition/AppointmentResponse\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1397`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1398`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AppointmentResponse](/docs/R4B/Resources/AppointmentResponse.md)<br/> `http://hl7.org/fhir/StructureDefinition/AppointmentResponse\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `934`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1163`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AppointmentResponse](/docs/R5/Resources/AppointmentResponse.md)<br/> `http://hl7.org/fhir/StructureDefinition/AppointmentResponse\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition AppointmentResponse from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 AppointmentResponse| Relationship | [R3 AppointmentResponse](/docs/R3/Resources/AppointmentResponse.md)| Relationship | [R4 AppointmentResponse](/docs/R4/Resources/AppointmentResponse.md)| Relationship | [R4B AppointmentResponse](/docs/R4B/Resources/AppointmentResponse.md)| Relationship | [R5 AppointmentResponse](/docs/R5/Resources/AppointmentResponse.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`AppointmentResponse`**| _Equivalent_<br/>(3037/3038)| `AppointmentResponse`| _Equivalent_<br/>(10250/10251)| `AppointmentResponse`| _Equivalent_<br/>(21813/21814)| `AppointmentResponse`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36917)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(36918)| `AppointmentResponse`
| **`AppointmentResponse.id`**| _Equivalent_<br/>(3039/3040)| `AppointmentResponse.id`| _Equivalent_<br/>(10252/10253)| `AppointmentResponse.id`| _Equivalent_<br/>(21815/21816)| `AppointmentResponse.id`| _Equivalent_<br/>(36919/36920)| `AppointmentResponse.id`
| **`AppointmentResponse.meta`**| _Equivalent_<br/>(3041/3042)| `AppointmentResponse.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10254)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10255)| `AppointmentResponse.meta`| _Equivalent_<br/>(21817/21818)| `AppointmentResponse.meta`| _Equivalent_<br/>(36921/36922)| `AppointmentResponse.meta`
| **`AppointmentResponse.implicitRules`**| _Equivalent_<br/>(3043/3044)| `AppointmentResponse.implicitRules`| _Equivalent_<br/>(10256/10257)| `AppointmentResponse.implicitRules`| _Equivalent_<br/>(21819/21820)| `AppointmentResponse.implicitRules`| _Equivalent_<br/>(36923/36924)| `AppointmentResponse.implicitRules`
| **`AppointmentResponse.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3045)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(3046)| `AppointmentResponse.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10258)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(10259)| `AppointmentResponse.language`| _Equivalent_<br/>(21821/21822)| `AppointmentResponse.language`| _Equivalent_<br/>(36925/36926)| `AppointmentResponse.language`
| **`AppointmentResponse.text`**| _Equivalent_<br/>(3047/3048)| `AppointmentResponse.text`| _Equivalent_<br/>(10260/10261)| `AppointmentResponse.text`| _Equivalent_<br/>(21823/21824)| `AppointmentResponse.text`| _Equivalent_<br/>(36927/36928)| `AppointmentResponse.text`
| **`AppointmentResponse.contained`**| _Equivalent_<br/>(3049/3050)| `AppointmentResponse.contained`| _Equivalent_<br/>(10262/10263)| `AppointmentResponse.contained`| _Equivalent_<br/>(21825/21826)| `AppointmentResponse.contained`| _Equivalent_<br/>(36929/36930)| `AppointmentResponse.contained`
| **`AppointmentResponse.extension`**| _Equivalent_<br/>(3051/3052)| `AppointmentResponse.extension`| _Equivalent_<br/>(10264/10265)| `AppointmentResponse.extension`| _Equivalent_<br/>(21827/21828)| `AppointmentResponse.extension`| _Equivalent_<br/>(36931/36932)| `AppointmentResponse.extension`
| **`AppointmentResponse.modifierExtension`**| _Equivalent_<br/>(3053/3054)| `AppointmentResponse.modifierExtension`| _Equivalent_<br/>(10266/10267)| `AppointmentResponse.modifierExtension`| _Equivalent_<br/>(21829/21830)| `AppointmentResponse.modifierExtension`| _Equivalent_<br/>(36933/36934)| `AppointmentResponse.modifierExtension`
| **`AppointmentResponse.identifier`**| _Equivalent_<br/>(3055/3056)| `AppointmentResponse.identifier`| _Equivalent_<br/>(10268/10269)| `AppointmentResponse.identifier`| _Equivalent_<br/>(21831/21832)| `AppointmentResponse.identifier`| _Equivalent_<br/>(36935/36936)| `AppointmentResponse.identifier`
| **`AppointmentResponse.appointment`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3057)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3058)| `AppointmentResponse.appointment`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10270)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10271)| `AppointmentResponse.appointment`| _Equivalent_<br/>(21833/21834)| `AppointmentResponse.appointment`| _Equivalent_<br/>(36937/36938)| `AppointmentResponse.appointment`
| **`AppointmentResponse.start`**| _Equivalent_<br/>(3059/3060)| `AppointmentResponse.start`| _Equivalent_<br/>(10272/10273)| `AppointmentResponse.start`| _Equivalent_<br/>(21835/21836)| `AppointmentResponse.start`| _Equivalent_<br/>(36939/36940)| `AppointmentResponse.start`
| **`AppointmentResponse.end`**| _Equivalent_<br/>(3061/3062)| `AppointmentResponse.end`| _Equivalent_<br/>(10274/10275)| `AppointmentResponse.end`| _Equivalent_<br/>(21837/21838)| `AppointmentResponse.end`| _Equivalent_<br/>(36941/36942)| `AppointmentResponse.end`
| **`AppointmentResponse.participantType`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3063)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(3064)| `AppointmentResponse.participantType`| _Equivalent_<br/>(10276/10277)| `AppointmentResponse.participantType`| _Equivalent_<br/>(21839/21840)| `AppointmentResponse.participantType`| _Equivalent_<br/>(36943/36944)| `AppointmentResponse.participantType`
| **`AppointmentResponse.actor`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3065)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3066)| `AppointmentResponse.actor`| →→→→ _RelatedTo_ →→→→ <br/>(10278)<hr/>←←←← _RelatedTo_ ←←←← <br/>(10279)| `AppointmentResponse.actor`| _Equivalent_<br/>(21841/21842)| `AppointmentResponse.actor`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(36945)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(36946)| `AppointmentResponse.actor`
| **`AppointmentResponse.participantStatus`**| →→→→ _RelatedTo_ →→→→ <br/>(3067)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3068)| `AppointmentResponse.participantStatus`| _Equivalent_<br/>(10280/10281)| `AppointmentResponse.participantStatus`| _Equivalent_<br/>(21843/21844)| `AppointmentResponse.participantStatus`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36947)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(36948)| `AppointmentResponse.participantStatus`
| **`AppointmentResponse.comment`**| _Equivalent_<br/>(3069/3070)| `AppointmentResponse.comment`| _Equivalent_<br/>(10282/10283)| `AppointmentResponse.comment`| _Equivalent_<br/>(21845/21846)| `AppointmentResponse.comment`| _Equivalent_<br/>(36949/36950)| `AppointmentResponse.comment`
| *17 of 17 elements used* | | *17 of 17 elements used* | | *17 of 17 elements used* | | *17 of 17 elements used* | | *17 of 21 elements used* 

