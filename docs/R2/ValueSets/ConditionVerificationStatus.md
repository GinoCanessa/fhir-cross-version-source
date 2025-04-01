Comparison of 
Generated at Tuesday, April 1, 2025 1:39:06 PM

### ConditionVerificationStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | ConditionVerificationStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/condition-ver-status` |
| Version | 1.0.2 |
| Description | The verification status to support or decline the clinical status of the condition or diagnosis. |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `70` |
| Database Concept Count | `6` |
| Database Active Concept Count | `6` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Condition` | `Condition.verificationStatus` | `http://hl7.org/fhir/ValueSet/condition-ver-status` | `Required` | provisional \| differential \| confirmed \| refuted \| entered-in-error \| unknown |

### Referenced Systems

* `http://hl7.org/fhir/condition-ver-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ConditionVerificationStatus](/docs/R2/ValueSets/ConditionVerificationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/condition-ver-status\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `32`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `191`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ConditionVerificationStatus](/docs/R3/ValueSets/ConditionVerificationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/condition-ver-status\|3.0.2` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `360`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `583`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ConditionVerificationStatus](/docs/R4/ValueSets/ConditionVerificationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/condition-ver-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1437`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1438`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ConditionVerificationStatus](/docs/R4B/ValueSets/ConditionVerificationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/condition-ver-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `803`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1064`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ConditionVerificationStatus](/docs/R5/ValueSets/ConditionVerificationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/condition-ver-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set ConditionVerificationStatus from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 ConditionVerificationStatus| Relationship | [R3 ConditionVerificationStatus](/docs/R3/ValueSets/ConditionVerificationStatus.md)| Relationship | [R4 ConditionVerificationStatus](/docs/R4/ValueSets/ConditionVerificationStatus.md)| Relationship | [R4B ConditionVerificationStatus](/docs/R4B/ValueSets/ConditionVerificationStatus.md)| Relationship | [R5 ConditionVerificationStatus](/docs/R5/ValueSets/ConditionVerificationStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/condition-ver-status`
| **`provisional`**| _Equivalent_ <br/>(159/1525)| `provisional`| _Equivalent_ <br/>(3071/5278)| `provisional`| _Equivalent_ <br/>(14766/14767)| `provisional`| _Equivalent_ <br/>(7586/9856)| `provisional`
| **`differential`**| _Equivalent_ <br/>(163/1529)| `differential`| _Equivalent_ <br/>(3069/5276)| `differential`| _Equivalent_ <br/>(14768/14769)| `differential`| _Equivalent_ <br/>(7584/9854)| `differential`
| **`confirmed`**| _Equivalent_ <br/>(162/1528)| `confirmed`| _Equivalent_ <br/>(3068/5275)| `confirmed`| _Equivalent_ <br/>(14770/14771)| `confirmed`| _Equivalent_ <br/>(7583/9853)| `confirmed`
| **`refuted`**| _Equivalent_ <br/>(160/1526)| `refuted`| _Equivalent_ <br/>(3072/5279)| `refuted`| _Equivalent_ <br/>(14772/14773)| `refuted`| _Equivalent_ <br/>(7587/9857)| `refuted`
| **`entered-in-error`**| _Equivalent_ <br/>(161/1527)| `entered-in-error`| _Equivalent_ <br/>(3070/5277)| `entered-in-error`| _Equivalent_ <br/>(14774/14775)| `entered-in-error`| _Equivalent_ <br/>(7585/9855)| `entered-in-error`
| **`unknown`**| _Equivalent_ <br/>(164/1530)| `unknown`| | | | | | | 
| *6 of 6 codes used* | | *6 of 6 codes used* | | *5 of 6 codes used* | | *5 of 6 codes used* | | *5 of 6 codes used* 

