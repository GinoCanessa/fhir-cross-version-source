Comparison of 
Generated at Tuesday, April 1, 2025 1:39:06 PM

### MedicationAdministrationStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | MedicationAdministrationStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/medication-admin-status` |
| Version | 1.0.2 |
| Description | A set of codes indicating the current status of a MedicationAdministration. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `220` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Immunization` | `Immunization.status` | `http://hl7.org/fhir/ValueSet/medication-admin-status` | `Required` | in-progress \| on-hold \| completed \| entered-in-error \| stopped |
| `http://hl7.org/fhir/StructureDefinition/MedicationAdministration` | `MedicationAdministration.status` | `http://hl7.org/fhir/ValueSet/medication-admin-status` | `Required` | in-progress \| on-hold \| completed \| entered-in-error \| stopped |

### Referenced Systems

* `http://hl7.org/fhir/medication-admin-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [MedicationAdministrationStatus](/docs/R2/ValueSets/MedicationAdministrationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/medication-admin-status\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `94`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `250`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Immunization Status Codes](/docs/R3/ValueSets/ImmunizationStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/immunization-status\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `427`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `649`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ImmunizationStatusCodes](/docs/R4/ValueSets/ImmunizationStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/immunization-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1547`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1548`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ImmunizationStatusCodes](/docs/R4B/ValueSets/ImmunizationStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/immunization-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `902`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1163`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ImmunizationStatusCodes](/docs/R5/ValueSets/ImmunizationStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/immunization-status\|5.0.0` 
| [MedicationAdministrationStatus](/docs/R2/ValueSets/MedicationAdministrationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/medication-admin-status\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `94`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `250`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MedicationAdministrationStatus](/docs/R3/ValueSets/MedicationAdministrationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/medication-admin-status\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `434`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `656`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MedicationAdministration Status Codes](/docs/R4/ValueSets/MedicationAdministrationStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/medication-admin-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1593`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1594`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MedicationAdministration Status Codes](/docs/R4B/ValueSets/MedicationAdministrationStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/medication-admin-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `913`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1174`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MedicationAdministrationStatusCodes](/docs/R5/ValueSets/MedicationAdministrationStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/medication-admin-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set MedicationAdministrationStatus from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 MedicationAdministrationStatus| Relationship | [R3 Immunization Status Codes](/docs/R3/ValueSets/ImmunizationStatusCodes.md)| Relationship | [R4 ImmunizationStatusCodes](/docs/R4/ValueSets/ImmunizationStatusCodes.md)| Relationship | [R4B ImmunizationStatusCodes](/docs/R4B/ValueSets/ImmunizationStatusCodes.md)| Relationship | [R5 ImmunizationStatusCodes](/docs/R5/ValueSets/ImmunizationStatusCodes.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/medication-admin-status`
| **`in-progress`**| _Equivalent_ <br/>(792/2152)| `in-progress`| | | | | | | 
| **`on-hold`**| _Equivalent_ <br/>(793/2153)| `on-hold`| | | | | | | 
| **`completed`**| _Equivalent_ <br/>(790/2150)| `completed`| | | | | | | 
| **`entered-in-error`**| _Equivalent_ <br/>(791/2151)| `entered-in-error`| | | | | | | 
| **`stopped`**| _Equivalent_ <br/>(789/2154)| `stopped`| | | | | | | 
| *5 of 5 codes used* | | *5 of 2 codes used* | | *0 of 3 codes used* | | *0 of 3 codes used* | | *0 of 3 codes used* 


#### Map Group 1

This group is centered on the Value Set MedicationAdministrationStatus from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 MedicationAdministrationStatus| Relationship | [R3 MedicationAdministrationStatus](/docs/R3/ValueSets/MedicationAdministrationStatus.md)| Relationship | [R4 MedicationAdministration Status Codes](/docs/R4/ValueSets/MedicationAdministrationStatusCodes.md)| Relationship | [R4B MedicationAdministration Status Codes](/docs/R4B/ValueSets/MedicationAdministrationStatusCodes.md)| Relationship | [R5 MedicationAdministrationStatusCodes](/docs/R5/ValueSets/MedicationAdministrationStatusCodes.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/medication-admin-status`
| **`in-progress`**| _Equivalent_ <br/>(792/2152)| `in-progress`| _Equivalent_ <br/>(3930/6249)| `in-progress`| _Equivalent_ <br/>(16486/16487)| `in-progress`| _Equivalent_ <br/>(8748/11057)| `in-progress`
| **`on-hold`**| _Equivalent_ <br/>(793/2153)| `on-hold`| _Equivalent_ <br/>(3931/6250)| `on-hold`| _Equivalent_ <br/>(16490/16491)| `on-hold`| _Equivalent_ <br/>(8749/11058)| `on-hold`
| **`completed`**| _Equivalent_ <br/>(790/2150)| `completed`| _Equivalent_ <br/>(3928/6246)| `completed`| _Equivalent_ <br/>(16492/16493)| `completed`| _Equivalent_ <br/>(8745/11054)| `completed`
| **`entered-in-error`**| _Equivalent_ <br/>(791/2151)| `entered-in-error`| _Equivalent_ <br/>(3929/6248)| `entered-in-error`| _Equivalent_ <br/>(16494/16495)| `entered-in-error`| _Equivalent_ <br/>(8747/11056)| `entered-in-error`
| **`stopped`**| _Equivalent_ <br/>(789/2154)| `stopped`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(3926)<hr/>←←←← _Equivalent_ ←←←← <br/>(6245) | `not-done`| _Equivalent_ <br/>(16488/16489)| `not-done`| _Equivalent_ <br/>(8746/11055)| `not-done`
| **`stopped`**| _Equivalent_ <br/>(789/2154)| `stopped`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(3926)<hr/>←←←← _Equivalent_ ←←←← <br/>(6245) | `stopped`| _Equivalent_ <br/>(16496/16497)| `stopped`| _Equivalent_ <br/>(8744/11053)| `stopped`
| *5 of 5 codes used* | | *5 of 6 codes used* | | *6 of 7 codes used* | | *6 of 7 codes used* | | *6 of 7 codes used* 

