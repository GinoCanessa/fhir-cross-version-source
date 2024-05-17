Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | ImmunizationEvaluation |  | Describes a comparison of an immunization event against published recommendations to determine if the administration is "valid" in relation to those  recommendations. | 22 | 14 |
| Target | ImmunizationEvaluation |  | Describes a comparison of an immunization event against published recommendations to determine if the administration is "valid" in relation to those  recommendations. | 22 | 14 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 2 |
Equivalent | 4 |
RelatedTo | 16 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| ImmunizationEvaluation | ImmunizationEvaluation | Equivalent | R4B `ImmunizationEvaluation` maps as Equivalent to R5 `ImmunizationEvaluation` |
| ImmunizationEvaluation.authority | ImmunizationEvaluation.authority | Equivalent | R4B `ImmunizationEvaluation.authority` maps as Equivalent to R5 `ImmunizationEvaluation.authority` |
| ImmunizationEvaluation.contained | ImmunizationEvaluation.contained | Equivalent | R4B `ImmunizationEvaluation.contained` maps as Equivalent to R5 `ImmunizationEvaluation.contained` |
| ImmunizationEvaluation.date | ImmunizationEvaluation.date | Equivalent | R4B `ImmunizationEvaluation.date` maps as Equivalent to R5 `ImmunizationEvaluation.date` |
| ImmunizationEvaluation.description | ImmunizationEvaluation.description | SourceIsBroaderThanTarget | R4B `ImmunizationEvaluation.description` maps as SourceIsBroaderThanTarget to R5 `ImmunizationEvaluation.description` - description has change due to type change: R4B description string has no equivalent or mapped type in R5 description |
| ImmunizationEvaluation.doseNumber[x] | - | DoesNotExistInTarget | R4B `ImmunizationEvaluation.doseNumber[x]` does not appear in the target and has no mapping for `ImmunizationEvaluation`. |
| ImmunizationEvaluation.doseStatus | ImmunizationEvaluation.doseStatus | Equivalent | R4B `ImmunizationEvaluation.doseStatus` maps as Equivalent to R5 `ImmunizationEvaluation.doseStatus` |
| ImmunizationEvaluation.doseStatusReason | ImmunizationEvaluation.doseStatusReason | Equivalent | R4B `ImmunizationEvaluation.doseStatusReason` maps as Equivalent to R5 `ImmunizationEvaluation.doseStatusReason` |
| ImmunizationEvaluation.extension | ImmunizationEvaluation.extension | RelatedTo | R4B `ImmunizationEvaluation.extension` maps as RelatedTo to R5 `ImmunizationEvaluation.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ImmunizationEvaluation.id | ImmunizationEvaluation.id | Equivalent | R4B `ImmunizationEvaluation.id` maps as Equivalent to R5 `ImmunizationEvaluation.id` |
| ImmunizationEvaluation.identifier | ImmunizationEvaluation.identifier | Equivalent | R4B `ImmunizationEvaluation.identifier` maps as Equivalent to R5 `ImmunizationEvaluation.identifier` |
| ImmunizationEvaluation.immunizationEvent | ImmunizationEvaluation.immunizationEvent | Equivalent | R4B `ImmunizationEvaluation.immunizationEvent` maps as Equivalent to R5 `ImmunizationEvaluation.immunizationEvent` |
| ImmunizationEvaluation.implicitRules | ImmunizationEvaluation.implicitRules | Equivalent | R4B `ImmunizationEvaluation.implicitRules` maps as Equivalent to R5 `ImmunizationEvaluation.implicitRules` |
| ImmunizationEvaluation.language | ImmunizationEvaluation.language | RelatedTo | R4B `ImmunizationEvaluation.language` maps as RelatedTo to R5 `ImmunizationEvaluation.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| ImmunizationEvaluation.meta | ImmunizationEvaluation.meta | Equivalent | R4B `ImmunizationEvaluation.meta` maps as Equivalent to R5 `ImmunizationEvaluation.meta` |
| ImmunizationEvaluation.modifierExtension | ImmunizationEvaluation.modifierExtension | RelatedTo | R4B `ImmunizationEvaluation.modifierExtension` maps as RelatedTo to R5 `ImmunizationEvaluation.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ImmunizationEvaluation.patient | ImmunizationEvaluation.patient | Equivalent | R4B `ImmunizationEvaluation.patient` maps as Equivalent to R5 `ImmunizationEvaluation.patient` |
| ImmunizationEvaluation.series | ImmunizationEvaluation.series | Equivalent | R4B `ImmunizationEvaluation.series` maps as Equivalent to R5 `ImmunizationEvaluation.series` |
| ImmunizationEvaluation.seriesDoses[x] | - | DoesNotExistInTarget | R4B `ImmunizationEvaluation.seriesDoses[x]` does not appear in the target and has no mapping for `ImmunizationEvaluation`. |
| ImmunizationEvaluation.status | ImmunizationEvaluation.status | Equivalent | R4B `ImmunizationEvaluation.status` maps as Equivalent to R5 `ImmunizationEvaluation.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/immunization-evaluation-status|4.3.0 and http://hl7.org/fhir/ValueSet/immunization-evaluation-status|5.0.0 (Equivalent) |
| ImmunizationEvaluation.targetDisease | ImmunizationEvaluation.targetDisease | Equivalent | R4B `ImmunizationEvaluation.targetDisease` maps as Equivalent to R5 `ImmunizationEvaluation.targetDisease` |
| ImmunizationEvaluation.text | ImmunizationEvaluation.text | Equivalent | R4B `ImmunizationEvaluation.text` maps as Equivalent to R5 `ImmunizationEvaluation.text` |

