Comparison of 
Generated at Thursday, April 3, 2025 8:18:24 AM

### medicationrequest Status

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | medicationrequest Status |
| Canonical URL | `http://hl7.org/fhir/ValueSet/medicationrequest-status` |
| Version | 4.3.0 |
| Description | MedicationRequest Status Codes |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `3918` |
| Database Concept Count | `8` |
| Database Active Concept Count | `8` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/MedicationRequest` | `MedicationRequest.status` | `http://hl7.org/fhir/ValueSet/medicationrequest-status\|4.3.0` | `Required` | active \| on-hold \| cancelled \| completed \| entered-in-error \| stopped \| draft \| unknown |

### Referenced Systems

* `http://hl7.org/fhir/CodeSystem/medicationrequest-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [MedicationOrderStatus](/docs/R2/ValueSets/MedicationOrderStatus.md)<br/> `http://hl7.org/fhir/ValueSet/medication-order-status\|1.0.2` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `97`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`RelatedTo`<br/>- DBKey: `253`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MedicationRequestStatus](/docs/R3/ValueSets/MedicationRequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/medication-request-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `445`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `667`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [medicationrequest Status](/docs/R4/ValueSets/MedicationrequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/medicationrequest-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1605`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1606`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [medicationrequest Status](/docs/R4B/ValueSets/MedicationrequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/medicationrequest-status\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `925`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1186`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MedicationrequestStatus](/docs/R5/ValueSets/MedicationrequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/medicationrequest-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set medicationrequest Status from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 MedicationOrderStatus](/docs/R2/ValueSets/MedicationOrderStatus.md)| Relationship | [R3 MedicationRequestStatus](/docs/R3/ValueSets/MedicationRequestStatus.md)| Relationship | [R4 medicationrequest Status](/docs/R4/ValueSets/MedicationrequestStatus.md)| Relationship | R4B medicationrequest Status| Relationship | [R5 MedicationrequestStatus](/docs/R5/ValueSets/MedicationrequestStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://hl7.org/fhir/CodeSystem/medicationrequest-status`
| `active`| _Equivalent_ <br/>(805/2165)| `active`| _Equivalent_ <br/>(3981/6305)| `active`| _Equivalent_ <br/>(16562/16563)| **`active`**| _Equivalent_ <br/>(8980/11287)| `active`
| `on-hold`| _Equivalent_ <br/>(808/2170)| `on-hold`| _Equivalent_ <br/>(3985/6309)| `on-hold`| _Equivalent_ <br/>(16564/16565)| **`on-hold`**| _Equivalent_ <br/>(8985/11293)| `on-hold`
| `stopped`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(803)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2166) | `cancelled`| _Equivalent_ <br/>(3982/6306)| `cancelled`| _Equivalent_ <br/>(16566/16567)| **`cancelled`**| _Equivalent_ <br/>(8981/11288)| `cancelled`
| `completed`| _Equivalent_ <br/>(806/2167)| `completed`| _Equivalent_ <br/>(3983/6307)| `completed`| _Equivalent_ <br/>(16568/16569)| **`completed`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(8982)<hr/>←←←← _Equivalent_ ←←←← <br/>(11289) | `ended`
| `completed`| _Equivalent_ <br/>(806/2167)| `completed`| _Equivalent_ <br/>(3983/6307)| `completed`| _Equivalent_ <br/>(16568/16569)| **`completed`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(8982)<hr/>←←←← _Equivalent_ ←←←← <br/>(11289) | `completed`
| `entered-in-error`| _Equivalent_ <br/>(807/2169)| `entered-in-error`| _Equivalent_ <br/>(3984/6308)| `entered-in-error`| _Equivalent_ <br/>(16570/16571)| **`entered-in-error`**| _Equivalent_ <br/>(8984/11292)| `entered-in-error`
| `stopped`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(802)<hr/>←←←← _Equivalent_ ←←←← <br/>(2171) | `stopped`| _Equivalent_ <br/>(3979/6303)| `stopped`| _Equivalent_ <br/>(16572/16573)| **`stopped`**| _Equivalent_ <br/>(8978/11294)| `stopped`
| `draft`| _Equivalent_ <br/>(804/2168)| `draft`| _Equivalent_ <br/>(3980/6304)| `draft`| _Equivalent_ <br/>(16574/16575)| **`draft`**| _Equivalent_ <br/>(8979/11290)| `draft`
| | | `unknown`| _Equivalent_ <br/>(3986/6310)| `unknown`| _Equivalent_ <br/>(16576/16577)| **`unknown`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(8986)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11295) | `unknown`
| *6 of 6 codes used* | | *8 of 8 codes used* | | *8 of 8 codes used* | | *8 of 8 codes used* | | *9 of 9 codes used* 

