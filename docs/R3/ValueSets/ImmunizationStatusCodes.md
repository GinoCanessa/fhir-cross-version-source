Comparison of 
Generated at Monday, April 14, 2025 6:17:20 PM

### Immunization Status Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Immunization Status Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/immunization-status` |
| Version | 3.0.2 |
| Description | The value set to instantiate this attribute should be drawn from a terminologically robust code system that consists of or contains concepts to support describing the current status of the administered dose of vaccine. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1281` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Immunization` | `Immunization.status` | `http://hl7.org/fhir/ValueSet/immunization-status` | `Required` | completed \| entered-in-error |

### Referenced Systems

* `http://hl7.org/fhir/medication-admin-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [MedicationAdministrationStatus](/docs/R2/ValueSets/MedicationAdministrationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/medication-admin-status\|1.0.2` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `87`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `243`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Immunization Status Codes](/docs/R3/ValueSets/ImmunizationStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/immunization-status\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `427`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `649`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ImmunizationStatusCodes](/docs/R4/ValueSets/ImmunizationStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/immunization-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1547`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1548`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ImmunizationStatusCodes](/docs/R4B/ValueSets/ImmunizationStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/immunization-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `902`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1163`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [ImmunizationStatusCodes](/docs/R5/ValueSets/ImmunizationStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/immunization-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set Immunization Status Codes from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 MedicationAdministrationStatus](/docs/R2/ValueSets/MedicationAdministrationStatus.md)| Relationship | R3 Immunization Status Codes| Relationship | [R4 ImmunizationStatusCodes](/docs/R4/ValueSets/ImmunizationStatusCodes.md)| Relationship | [R4B ImmunizationStatusCodes](/docs/R4B/ValueSets/ImmunizationStatusCodes.md)| Relationship | [R5 ImmunizationStatusCodes](/docs/R5/ValueSets/ImmunizationStatusCodes.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/medication-admin-status`
| `completed`| _Equivalent_ <br/>(615/1976)| **`completed`**| _Equivalent_ <br/>(3786/6104)| `completed`| _Equivalent_ <br/>(16222/16223)| `completed`| _Equivalent_ <br/>(8705/11014)| `completed`
| `entered-in-error`| _Equivalent_ <br/>(616/1977)| **`entered-in-error`**| _Equivalent_ <br/>(3787/6106)| `entered-in-error`| _Equivalent_ <br/>(16224/16225)| `entered-in-error`| _Equivalent_ <br/>(8707/11016)| `entered-in-error`
| *2 of 5 codes used* <br/>remaining codes:<br/>`in-progress`, `on-hold`, `stopped`| | *2 of 2 codes used* | | *2 of 3 codes used* <br/>remaining codes:<br/>`not-done`| | *2 of 3 codes used* <br/>remaining codes:<br/>`not-done`| | *2 of 3 codes used* <br/>remaining codes:<br/>`not-done`

