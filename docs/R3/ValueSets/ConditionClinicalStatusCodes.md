Comparison of 
Generated at Monday, April 14, 2025 6:17:19 PM

### Condition Clinical Status Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Condition Clinical Status Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/condition-clinical` |
| Version | 3.0.2 |
| Description | Preferred value set for Condition Clinical Status. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1129` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Condition` | `Condition.clinicalStatus` | `http://hl7.org/fhir/ValueSet/condition-clinical` | `Required` | active \| recurrence \| inactive \| remission \| resolved |

### Referenced Systems

* `http://hl7.org/fhir/condition-clinical`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Condition Clinical Status Codes](/docs/R2/ValueSets/ConditionClinicalStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/condition-clinical\|1.0.2` | →→→→→→→<br/>``<br/>- DBKey: `1320`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `1319`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Condition Clinical Status Codes](/docs/R3/ValueSets/ConditionClinicalStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/condition-clinical\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `359`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `582`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ConditionClinicalStatusCodes](/docs/R4/ValueSets/ConditionClinicalStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/condition-clinical\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1435`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1436`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ConditionClinicalStatusCodes](/docs/R4B/ValueSets/ConditionClinicalStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/condition-clinical\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `802`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1063`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ConditionClinicalStatusCodes](/docs/R5/ValueSets/ConditionClinicalStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/condition-clinical\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set Condition Clinical Status Codes from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 Condition Clinical Status Codes](/docs/R2/ValueSets/ConditionClinicalStatusCodes.md)| Relationship | R3 Condition Clinical Status Codes| Relationship | [R4 ConditionClinicalStatusCodes](/docs/R4/ValueSets/ConditionClinicalStatusCodes.md)| Relationship | [R4B ConditionClinicalStatusCodes](/docs/R4B/ValueSets/ConditionClinicalStatusCodes.md)| Relationship | [R5 ConditionClinicalStatusCodes](/docs/R5/ValueSets/ConditionClinicalStatusCodes.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/condition-clinical`
| `active`| _Equivalent_ <br/>(13159/13158)| **`active`**| _Equivalent_ <br/>(3066/5269)| `active`| _Equivalent_ <br/>(14752/14753)| `active`| _Equivalent_ <br/>(7577/9847)| `active`
| | | **`recurrence`**| _Equivalent_ <br/>(3063/5271)| `recurrence`| _Equivalent_ <br/>(14754/14755)| `recurrence`| _Equivalent_ <br/>(7579/9849)| `recurrence`
| | | **`inactive`**| _Equivalent_ <br/>(3064/5270)| `inactive`| _Equivalent_ <br/>(14758/14759)| `inactive`| _Equivalent_ <br/>(7578/9848)| `inactive`
| `remission`| _Equivalent_ <br/>(13163/13162)| **`remission`**| _Equivalent_ <br/>(3065/5273)| `remission`| _Equivalent_ <br/>(14760/14761)| `remission`| _Equivalent_ <br/>(7581/9851)| `remission`
| `resolved`| _Equivalent_ <br/>(13165/13164)| **`resolved`**| _Equivalent_ <br/>(3067/5274)| `resolved`| _Equivalent_ <br/>(14762/14763)| `resolved`| _Equivalent_ <br/>(7582/9852)| `resolved`
| *3 of 4 codes used* <br/>remaining codes:<br/>`relapse`| | *5 of 5 codes used* | | *5 of 6 codes used* <br/>remaining codes:<br/>`relapse`| | *5 of 6 codes used* <br/>remaining codes:<br/>`relapse`| | *5 of 7 codes used* <br/>remaining codes:<br/>`relapse`, `unknown`

