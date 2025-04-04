Comparison of 
Generated at Friday, April 4, 2025 2:58:31 PM

### MedicationOrderStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | MedicationOrderStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/medication-order-status` |
| Version | 1.0.2 |
| Description | A code specifying the state of the prescribing event. Describes the lifecycle of the prescription. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `224` |
| Database Concept Count | `6` |
| Database Active Concept Count | `6` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/MedicationOrder` | `MedicationOrder.status` | `http://hl7.org/fhir/ValueSet/medication-order-status` | `Required` | active \| on-hold \| completed \| entered-in-error \| stopped \| draft |

### Referenced Systems

* `http://hl7.org/fhir/medication-order-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [MedicationOrderStatus](/docs/R2/ValueSets/MedicationOrderStatus.md)<br/> `http://hl7.org/fhir/ValueSet/medication-order-status\|1.0.2` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `97`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`RelatedTo`<br/>- DBKey: `253`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MedicationRequestStatus](/docs/R3/ValueSets/MedicationRequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/medication-request-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `445`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `667`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [medicationrequest Status](/docs/R4/ValueSets/MedicationrequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/medicationrequest-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1605`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1606`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [medicationrequest Status](/docs/R4B/ValueSets/MedicationrequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/medicationrequest-status\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `925`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1186`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MedicationrequestStatus](/docs/R5/ValueSets/MedicationrequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/medicationrequest-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set MedicationOrderStatus from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 MedicationOrderStatus| Relationship | [R3 MedicationRequestStatus](/docs/R3/ValueSets/MedicationRequestStatus.md)| Relationship | [R4 medicationrequest Status](/docs/R4/ValueSets/MedicationrequestStatus.md)| Relationship | [R4B medicationrequest Status](/docs/R4B/ValueSets/MedicationrequestStatus.md)| Relationship | [R5 MedicationrequestStatus](/docs/R5/ValueSets/MedicationrequestStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/medication-order-status`
| **`active`**| _Equivalent_ <br/>(805/2165)| `active`| _Equivalent_ <br/>(3981/6305)| `active`| _Equivalent_ <br/>(16562/16563)| `active`| _Equivalent_ <br/>(8980/11287)| `active`
| **`on-hold`**| _Equivalent_ <br/>(808/2170)| `on-hold`| _Equivalent_ <br/>(3985/6309)| `on-hold`| _Equivalent_ <br/>(16564/16565)| `on-hold`| _Equivalent_ <br/>(8985/11293)| `on-hold`
| **`completed`**| _Equivalent_ <br/>(806/2167)| `completed`| _Equivalent_ <br/>(3983/6307)| `completed`| _Equivalent_ <br/>(16568/16569)| `completed`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(8983)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11291) | `ended`
| **`completed`**| _Equivalent_ <br/>(806/2167)| `completed`| _Equivalent_ <br/>(3983/6307)| `completed`| _Equivalent_ <br/>(16568/16569)| `completed`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(8982)<hr/>←←←← _Equivalent_ ←←←← <br/>(11289) | `completed`
| **`entered-in-error`**| _Equivalent_ <br/>(807/2169)| `entered-in-error`| _Equivalent_ <br/>(3984/6308)| `entered-in-error`| _Equivalent_ <br/>(16570/16571)| `entered-in-error`| _Equivalent_ <br/>(8984/11292)| `entered-in-error`
| **`stopped`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(803)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2166) | `cancelled`| _Equivalent_ <br/>(3982/6306)| `cancelled`| _Equivalent_ <br/>(16566/16567)| `cancelled`| _Equivalent_ <br/>(8981/11288)| `cancelled`
| **`stopped`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(802)<hr/>←←←← _Equivalent_ ←←←← <br/>(2171) | `stopped`| _Equivalent_ <br/>(3979/6303)| `stopped`| _Equivalent_ <br/>(16572/16573)| `stopped`| _Equivalent_ <br/>(8978/11294)| `stopped`
| **`draft`**| _Equivalent_ <br/>(804/2168)| `draft`| _Equivalent_ <br/>(3980/6304)| `draft`| _Equivalent_ <br/>(16574/16575)| `draft`| _Equivalent_ <br/>(8979/11290)| `draft`
| *6 of 6 codes used* | | *7 of 8 codes used* <br/>remaining codes:<br/>`unknown`| | *7 of 8 codes used* <br/>remaining codes:<br/>`unknown`| | *7 of 8 codes used* <br/>remaining codes:<br/>`unknown`| | *8 of 9 codes used* <br/>remaining codes:<br/>`unknown`

