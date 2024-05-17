Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

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
| ImmunizationEvaluation | ImmunizationEvaluation | Equivalent | R5 `ImmunizationEvaluation` maps as Equivalent to R4B `ImmunizationEvaluation` |
| ImmunizationEvaluation.authority | ImmunizationEvaluation.authority | Equivalent | R5 `ImmunizationEvaluation.authority` maps as Equivalent to R4B `ImmunizationEvaluation.authority` |
| ImmunizationEvaluation.contained | ImmunizationEvaluation.contained | Equivalent | R5 `ImmunizationEvaluation.contained` maps as Equivalent to R4B `ImmunizationEvaluation.contained` |
| ImmunizationEvaluation.date | ImmunizationEvaluation.date | Equivalent | R5 `ImmunizationEvaluation.date` maps as Equivalent to R4B `ImmunizationEvaluation.date` |
| ImmunizationEvaluation.description | ImmunizationEvaluation.description | SourceIsBroaderThanTarget | R5 `ImmunizationEvaluation.description` maps as SourceIsBroaderThanTarget to R4B `ImmunizationEvaluation.description` - description has change due to type change: R5 description markdown has no equivalent or mapped type in R4B description |
| ImmunizationEvaluation.doseNumber | - | DoesNotExistInTarget | R5 `ImmunizationEvaluation.doseNumber` does not appear in the target and has no mapping for `ImmunizationEvaluation`. |
| ImmunizationEvaluation.doseStatus | ImmunizationEvaluation.doseStatus | Equivalent | R5 `ImmunizationEvaluation.doseStatus` maps as Equivalent to R4B `ImmunizationEvaluation.doseStatus` |
| ImmunizationEvaluation.doseStatusReason | ImmunizationEvaluation.doseStatusReason | Equivalent | R5 `ImmunizationEvaluation.doseStatusReason` maps as Equivalent to R4B `ImmunizationEvaluation.doseStatusReason` |
| ImmunizationEvaluation.extension | ImmunizationEvaluation.extension | SourceIsBroaderThanTarget | R5 `ImmunizationEvaluation.extension` maps as SourceIsBroaderThanTarget to R4B `ImmunizationEvaluation.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| ImmunizationEvaluation.id | ImmunizationEvaluation.id | Equivalent | R5 `ImmunizationEvaluation.id` maps as Equivalent to R4B `ImmunizationEvaluation.id` |
| ImmunizationEvaluation.identifier | ImmunizationEvaluation.identifier | Equivalent | R5 `ImmunizationEvaluation.identifier` maps as Equivalent to R4B `ImmunizationEvaluation.identifier` |
| ImmunizationEvaluation.immunizationEvent | ImmunizationEvaluation.immunizationEvent | Equivalent | R5 `ImmunizationEvaluation.immunizationEvent` maps as Equivalent to R4B `ImmunizationEvaluation.immunizationEvent` |
| ImmunizationEvaluation.implicitRules | ImmunizationEvaluation.implicitRules | Equivalent | R5 `ImmunizationEvaluation.implicitRules` maps as Equivalent to R4B `ImmunizationEvaluation.implicitRules` |
| ImmunizationEvaluation.language | ImmunizationEvaluation.language | RelatedTo | R5 `ImmunizationEvaluation.language` maps as RelatedTo to R4B `ImmunizationEvaluation.language` - language changed the binding strength from Required to Preferred |
| ImmunizationEvaluation.meta | ImmunizationEvaluation.meta | Equivalent | R5 `ImmunizationEvaluation.meta` maps as Equivalent to R4B `ImmunizationEvaluation.meta` |
| ImmunizationEvaluation.modifierExtension | ImmunizationEvaluation.modifierExtension | SourceIsBroaderThanTarget | R5 `ImmunizationEvaluation.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `ImmunizationEvaluation.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| ImmunizationEvaluation.patient | ImmunizationEvaluation.patient | Equivalent | R5 `ImmunizationEvaluation.patient` maps as Equivalent to R4B `ImmunizationEvaluation.patient` |
| ImmunizationEvaluation.series | ImmunizationEvaluation.series | Equivalent | R5 `ImmunizationEvaluation.series` maps as Equivalent to R4B `ImmunizationEvaluation.series` |
| ImmunizationEvaluation.seriesDoses | - | DoesNotExistInTarget | R5 `ImmunizationEvaluation.seriesDoses` does not appear in the target and has no mapping for `ImmunizationEvaluation`. |
| ImmunizationEvaluation.status | ImmunizationEvaluation.status | Equivalent | R5 `ImmunizationEvaluation.status` maps as Equivalent to R4B `ImmunizationEvaluation.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/immunization-evaluation-status|5.0.0 and http://hl7.org/fhir/ValueSet/immunization-evaluation-status|4.3.0 (Equivalent) |
| ImmunizationEvaluation.targetDisease | ImmunizationEvaluation.targetDisease | Equivalent | R5 `ImmunizationEvaluation.targetDisease` maps as Equivalent to R4B `ImmunizationEvaluation.targetDisease` |
| ImmunizationEvaluation.text | ImmunizationEvaluation.text | Equivalent | R5 `ImmunizationEvaluation.text` maps as Equivalent to R4B `ImmunizationEvaluation.text` |

