Comparison of 
Generated at Thursday, April 3, 2025 8:18:05 AM

### MedicationStatementStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | MedicationStatementStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/medication-statement-status` |
| Version | 1.0.2 |
| Description | A set of codes indicating the current status of a MedicationStatement. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `226` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/MedicationStatement` | `MedicationStatement.status` | `http://hl7.org/fhir/ValueSet/medication-statement-status` | `Required` | active \| completed \| entered-in-error \| intended |

### Referenced Systems

* `http://hl7.org/fhir/medication-statement-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [MedicationStatementStatus](/docs/R2/ValueSets/MedicationStatementStatus.md)<br/> `http://hl7.org/fhir/ValueSet/medication-statement-status\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `99`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `255`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MedicationStatementStatus](/docs/R3/ValueSets/MedicationStatementStatus.md)<br/> `http://hl7.org/fhir/ValueSet/medication-statement-status\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `450`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `674`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Medication Status Codes](/docs/R4/ValueSets/MedicationStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/medication-statement-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1595`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1596`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MedicationStatement Status Codes](/docs/R4B/ValueSets/MedicationStatementStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/medication-statement-status\|4.3.0` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `934`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1195`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MedicationStatementStatusCodes](/docs/R5/ValueSets/MedicationStatementStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/medication-statement-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set MedicationStatementStatus from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 MedicationStatementStatus| Relationship | [R3 MedicationStatementStatus](/docs/R3/ValueSets/MedicationStatementStatus.md)| Relationship | [R4 Medication Status Codes](/docs/R4/ValueSets/MedicationStatusCodes.md)| Relationship | [R4B MedicationStatement Status Codes](/docs/R4B/ValueSets/MedicationStatementStatusCodes.md)| Relationship | [R5 MedicationStatementStatusCodes](/docs/R5/ValueSets/MedicationStatementStatusCodes.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/medication-statement-status`
| **`active`**| _Equivalent_ <br/>(813/2176)| `active`| _Equivalent_ <br/>(4001/6332)| `active`| _Equivalent_ <br/>(16500/16501)| `active`| →→→→ _Equivalent_ →→→→ <br/>(9013)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11320) | `draft`
| **`completed`**| _Equivalent_ <br/>(814/2177)| `completed`| _Equivalent_ <br/>(4002/6333)| `completed`| _Equivalent_ <br/>(16502/16503)| `completed`| →→→→ _Equivalent_ →→→→ <br/>(9015)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11325) | `recorded`
| **`entered-in-error`**| _Equivalent_ <br/>(815/2178)| `entered-in-error`| _Equivalent_ <br/>(4003/6334)| `entered-in-error`| _Equivalent_ <br/>(16504/16505)| `entered-in-error`| _Equivalent_ <br/>(9016/11324)| `entered-in-error`
| **`intended`**| _Equivalent_ <br/>(812/2179)| `intended`| _Equivalent_ <br/>(4000/6335)| `intended`| _Equivalent_ <br/>(16506/16507)| `intended`| →→→→ _Equivalent_ →→→→ <br/>(9012)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11321) | `draft`
| *4 of 4 codes used* | | *4 of 6 codes used* <br/>remaining codes:<br/>`on-hold`, `stopped`| | *4 of 8 codes used* <br/>remaining codes:<br/>`not-taken`, `on-hold`, `stopped`, `unknown`| | *4 of 8 codes used* <br/>remaining codes:<br/>`not-taken`, `on-hold`, `stopped`, `unknown`| | *3 of 3 codes used* 

