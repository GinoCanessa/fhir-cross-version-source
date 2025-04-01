Comparison of 
Generated at Tuesday, April 1, 2025 1:39:19 PM

### MedicationDispense Status Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | MedicationDispense Status Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/medicationdispense-status` |
| Version | 4.0.1 |
| Description | MedicationDispense Status Codes |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `2579` |
| Database Concept Count | `9` |
| Database Active Concept Count | `9` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/MedicationDispense` | `MedicationDispense.status` | `http://hl7.org/fhir/ValueSet/medicationdispense-status\|4.0.1` | `Required` | preparation \| in-progress \| cancelled \| on-hold \| completed \| entered-in-error \| stopped \| declined \| unknown |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/medicationdispense-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [MedicationDispenseStatus](/docs/R2/ValueSets/MedicationDispenseStatus.md)<br/> `http://hl7.org/fhir/ValueSet/medication-dispense-status\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `96`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `252`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MedicationDispenseStatus](/docs/R3/ValueSets/MedicationDispenseStatus.md)<br/> `http://hl7.org/fhir/ValueSet/medication-dispense-status\|3.0.2` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `436`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`RelatedTo`<br/>- DBKey: `658`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MedicationDispense Status Codes](/docs/R4/ValueSets/MedicationDispenseStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/medicationdispense-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1599`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1600`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MedicationDispense Status Codes](/docs/R4B/ValueSets/MedicationDispenseStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/medicationdispense-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `914`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1175`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MedicationDispenseStatusCodes](/docs/R5/ValueSets/MedicationDispenseStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/medicationdispense-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set MedicationDispense Status Codes from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 MedicationDispenseStatus](/docs/R2/ValueSets/MedicationDispenseStatus.md)| Relationship | [R3 MedicationDispenseStatus](/docs/R3/ValueSets/MedicationDispenseStatus.md)| Relationship | R4 MedicationDispense Status Codes| Relationship | [R4B MedicationDispense Status Codes](/docs/R4B/ValueSets/MedicationDispenseStatusCodes.md)| Relationship | [R5 MedicationDispenseStatusCodes](/docs/R5/ValueSets/MedicationDispenseStatusCodes.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://terminology.hl7.org/CodeSystem/medicationdispense-status`
| | | `preparation`| _Equivalent_ <br/>(3943/6262)| **`preparation`**| _Equivalent_ <br/>(16522/16523)| `preparation`| _Equivalent_ <br/>(8758/11067)| `preparation`
| `in-progress`| _Equivalent_ <br/>(800/2161)| `in-progress`| _Equivalent_ <br/>(3941/6260)| **`in-progress`**| _Equivalent_ <br/>(16524/16525)| `in-progress`| _Equivalent_ <br/>(8756/11065)| `in-progress`
| `stopped`| _Equivalent_ <br/>(797/2164)| `stopped`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(3937)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(6257) | **`cancelled`**| _Equivalent_ <br/>(16526/16527)| `cancelled`| _Equivalent_ <br/>(8753/11062)| `cancelled`
| `on-hold`| _Equivalent_ <br/>(801/2162)| `on-hold`| _Equivalent_ <br/>(3942/6261)| **`on-hold`**| _Equivalent_ <br/>(16528/16529)| `on-hold`| _Equivalent_ <br/>(8757/11066)| `on-hold`
| `completed`| _Equivalent_ <br/>(798/2159)| `completed`| _Equivalent_ <br/>(3939/6258)| **`completed`**| _Equivalent_ <br/>(16530/16531)| `completed`| _Equivalent_ <br/>(8754/11063)| `completed`
| `entered-in-error`| _Equivalent_ <br/>(799/2160)| `entered-in-error`| _Equivalent_ <br/>(3940/6259)| **`entered-in-error`**| _Equivalent_ <br/>(16532/16533)| `entered-in-error`| _Equivalent_ <br/>(8755/11064)| `entered-in-error`
| `stopped`| _Equivalent_ <br/>(797/2164)| `stopped`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(3936)<hr/>←←←← _Equivalent_ ←←←← <br/>(6255) | **`stopped`**| _Equivalent_ <br/>(16534/16535)| `stopped`| _Equivalent_ <br/>(8751/11060)| `stopped`
| `stopped`| _Equivalent_ <br/>(797/2164)| `stopped`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(3938)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(6256) | **`declined`**| _Equivalent_ <br/>(16536/16537)| `declined`| _Equivalent_ <br/>(8752/11061)| `declined`
| | | | | **`unknown`**| _Equivalent_ <br/>(16538/16539)| `unknown`| _Equivalent_ <br/>(8759/11068)| `unknown`
| *5 of 5 codes used* | | *6 of 6 codes used* | | *9 of 9 codes used* | | *9 of 9 codes used* | | *9 of 9 codes used* 

