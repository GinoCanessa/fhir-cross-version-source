Comparison of 
Generated at Thursday, April 3, 2025 8:18:17 AM

### Medication Status Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | Medication Status Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/medication-status` |
| Version | 4.0.1 |
| Description | Medication Status Codes |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2576` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Medication` | `Medication.status` | `http://hl7.org/fhir/ValueSet/medication-status\|4.0.1` | `Required` | active \| inactive \| entered-in-error |

### Referenced Systems

* `http://hl7.org/fhir/CodeSystem/medication-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [MedicationStatus](/docs/R3/ValueSets/MedicationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/medication-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `442`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `664`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Medication Status Codes](/docs/R4/ValueSets/MedicationStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/medication-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1597`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1598`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Medication Status Codes](/docs/R4B/ValueSets/MedicationStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/medication-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `920`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1181`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MedicationStatusCodes](/docs/R5/ValueSets/MedicationStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/medication-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set Medication Status Codes from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | [R3 MedicationStatus](/docs/R3/ValueSets/MedicationStatus.md)| Relationship | R4 Medication Status Codes| Relationship | [R4B Medication Status Codes](/docs/R4B/ValueSets/MedicationStatusCodes.md)| Relationship | [R5 MedicationStatusCodes](/docs/R5/ValueSets/MedicationStatusCodes.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://hl7.org/fhir/CodeSystem/medication-status`
| | | `active`| _Equivalent_ <br/>(3969/6289)| **`active`**| _Equivalent_ <br/>(16516/16517)| `active`| _Equivalent_ <br/>(8783/11092)| `active`
| | | `inactive`| _Equivalent_ <br/>(3968/6288)| **`inactive`**| _Equivalent_ <br/>(16518/16519)| `inactive`| _Equivalent_ <br/>(8782/11091)| `inactive`
| | | `entered-in-error`| _Equivalent_ <br/>(3970/6290)| **`entered-in-error`**| _Equivalent_ <br/>(16520/16521)| `entered-in-error`| _Equivalent_ <br/>(8784/11093)| `entered-in-error`
| | | *3 of 3 codes used* | | *3 of 3 codes used* | | *3 of 3 codes used* | | *3 of 3 codes used* 

