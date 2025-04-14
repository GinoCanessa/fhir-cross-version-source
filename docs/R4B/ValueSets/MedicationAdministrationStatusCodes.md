Comparison of 
Generated at Monday, April 14, 2025 6:17:34 PM

### MedicationAdministration Status Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | MedicationAdministration Status Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/medication-admin-status` |
| Version | 4.3.0 |
| Description | MedicationAdministration Status Codes |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `3901` |
| Database Concept Count | `7` |
| Database Active Concept Count | `7` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/MedicationAdministration` | `MedicationAdministration.status` | `http://hl7.org/fhir/ValueSet/medication-admin-status\|4.3.0` | `Required` | in-progress \| not-done \| on-hold \| completed \| entered-in-error \| stopped \| unknown |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/medication-admin-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [MedicationAdministrationStatus](/docs/R2/ValueSets/MedicationAdministrationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/medication-admin-status\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `94`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `250`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [MedicationAdministrationStatus](/docs/R3/ValueSets/MedicationAdministrationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/medication-admin-status\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `434`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `656`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [MedicationAdministration Status Codes](/docs/R4/ValueSets/MedicationAdministrationStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/medication-admin-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1593`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1594`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [MedicationAdministration Status Codes](/docs/R4B/ValueSets/MedicationAdministrationStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/medication-admin-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `913`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1174`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [MedicationAdministrationStatusCodes](/docs/R5/ValueSets/MedicationAdministrationStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/medication-admin-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set MedicationAdministration Status Codes from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 MedicationAdministrationStatus](/docs/R2/ValueSets/MedicationAdministrationStatus.md)| Relationship | [R3 MedicationAdministrationStatus](/docs/R3/ValueSets/MedicationAdministrationStatus.md)| Relationship | [R4 MedicationAdministration Status Codes](/docs/R4/ValueSets/MedicationAdministrationStatusCodes.md)| Relationship | R4B MedicationAdministration Status Codes| Relationship | [R5 MedicationAdministrationStatusCodes](/docs/R5/ValueSets/MedicationAdministrationStatusCodes.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://terminology.hl7.org/CodeSystem/medication-admin-status`
| `in-progress`| _Equivalent_ <br/>(792/2152)| `in-progress`| _Equivalent_ <br/>(3930/6249)| `in-progress`| _Equivalent_ <br/>(16486/16487)| **`in-progress`**| _Equivalent_ <br/>(8748/11057)| `in-progress`
| `stopped`| _Equivalent_ <br/>(789/2154)| `stopped`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(3927)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(6247) | `not-done`| _Equivalent_ <br/>(16488/16489)| **`not-done`**| _Equivalent_ <br/>(8746/11055)| `not-done`
| `on-hold`| _Equivalent_ <br/>(793/2153)| `on-hold`| _Equivalent_ <br/>(3931/6250)| `on-hold`| _Equivalent_ <br/>(16490/16491)| **`on-hold`**| _Equivalent_ <br/>(8749/11058)| `on-hold`
| `completed`| _Equivalent_ <br/>(790/2150)| `completed`| _Equivalent_ <br/>(3928/6246)| `completed`| _Equivalent_ <br/>(16492/16493)| **`completed`**| _Equivalent_ <br/>(8745/11054)| `completed`
| `entered-in-error`| _Equivalent_ <br/>(791/2151)| `entered-in-error`| _Equivalent_ <br/>(3929/6248)| `entered-in-error`| _Equivalent_ <br/>(16494/16495)| **`entered-in-error`**| _Equivalent_ <br/>(8747/11056)| `entered-in-error`
| `stopped`| _Equivalent_ <br/>(789/2154)| `stopped`| →→→→ _Equivalent_ →→→→ <br/>(3926)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6245) | `stopped`| _Equivalent_ <br/>(16496/16497)| **`stopped`**| _Equivalent_ <br/>(8744/11053)| `stopped`
| | | `unknown`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3932)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6251) | `unknown`| _Equivalent_ <br/>(16498/16499)| **`unknown`**| _Equivalent_ <br/>(8750/11059)| `unknown`
| *5 of 5 codes used* | | *6 of 6 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* 

