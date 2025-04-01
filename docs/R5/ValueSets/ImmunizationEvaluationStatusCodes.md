Comparison of 
Generated at Tuesday, April 1, 2025 1:39:34 PM

### ImmunizationEvaluationStatusCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | ImmunizationEvaluationStatusCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/immunization-evaluation-status` |
| Version | 5.0.0 |
| Description | The value set to instantiate this attribute should be drawn from a terminologically robust code system that consists of or contains concepts to support describing the current status of the evaluation for vaccine administration event. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4617` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ImmunizationEvaluation` | `ImmunizationEvaluation.status` | `http://hl7.org/fhir/ValueSet/immunization-evaluation-status\|5.0.0` | `Required` | completed \| entered-in-error |

### Referenced Systems

* `http://hl7.org/fhir/CodeSystem/medication-admin-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [ImmunizationEvaluationStatusCodes](/docs/R4/ValueSets/ImmunizationEvaluationStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/immunization-evaluation-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1545`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1546`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ImmunizationEvaluationStatusCodes](/docs/R4B/ValueSets/ImmunizationEvaluationStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/immunization-evaluation-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1006`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1267`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ImmunizationEvaluationStatusCodes](/docs/R5/ValueSets/ImmunizationEvaluationStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/immunization-evaluation-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set ImmunizationEvaluationStatusCodes from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | [R4 ImmunizationEvaluationStatusCodes](/docs/R4/ValueSets/ImmunizationEvaluationStatusCodes.md)| Relationship | [R4B ImmunizationEvaluationStatusCodes](/docs/R4B/ValueSets/ImmunizationEvaluationStatusCodes.md)| Relationship | R5 ImmunizationEvaluationStatusCodes
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/CodeSystem/medication-admin-status`
| | | | | `completed`| _Equivalent_ <br/>(16218/16219)| `completed`| _Equivalent_ <br/>(9490/11829)| **`completed`**
| | | | | `entered-in-error`| _Equivalent_ <br/>(16220/16221)| `entered-in-error`| _Equivalent_ <br/>(9491/11830)| **`entered-in-error`**
| | | | | *2 of 2 codes used* | | *2 of 2 codes used* | | *2 of 2 codes used* 

