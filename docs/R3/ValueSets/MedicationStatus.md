Comparison of 
Generated at Tuesday, April 1, 2025 1:39:11 PM

### MedicationStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | MedicationStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/medication-status` |
| Version | 3.0.2 |
| Description | A coded concept defining if the medication is in active use |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1339` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Medication` | `Medication.status` | `http://hl7.org/fhir/ValueSet/medication-status` | `Required` | active \| inactive \| entered-in-error |

### Referenced Systems

* `http://hl7.org/fhir/medication-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [MedicationStatus](/docs/R3/ValueSets/MedicationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/medication-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `442`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `664`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Medication Status Codes](/docs/R4/ValueSets/MedicationStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/medication-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1597`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1598`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Medication Status Codes](/docs/R4B/ValueSets/MedicationStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/medication-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `920`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1181`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MedicationStatusCodes](/docs/R5/ValueSets/MedicationStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/medication-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set MedicationStatus from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | R3 MedicationStatus| Relationship | [R4 Medication Status Codes](/docs/R4/ValueSets/MedicationStatusCodes.md)| Relationship | [R4B Medication Status Codes](/docs/R4B/ValueSets/MedicationStatusCodes.md)| Relationship | [R5 MedicationStatusCodes](/docs/R5/ValueSets/MedicationStatusCodes.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/medication-status`
| | | **`active`**| _Equivalent_ <br/>(3969/6289)| `active`| _Equivalent_ <br/>(16516/16517)| `active`| _Equivalent_ <br/>(8783/11092)| `active`
| | | **`inactive`**| _Equivalent_ <br/>(3968/6288)| `inactive`| _Equivalent_ <br/>(16518/16519)| `inactive`| _Equivalent_ <br/>(8782/11091)| `inactive`
| | | **`entered-in-error`**| _Equivalent_ <br/>(3970/6290)| `entered-in-error`| _Equivalent_ <br/>(16520/16521)| `entered-in-error`| _Equivalent_ <br/>(8784/11093)| `entered-in-error`
| | | *3 of 3 codes used* | | *3 of 3 codes used* | | *3 of 3 codes used* | | *3 of 3 codes used* 

