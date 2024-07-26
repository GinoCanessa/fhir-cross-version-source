Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1
Generated at Thursday, July 25, 2024 3:56:51 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | ImmunizationRecommendation |  | A patient's point-in-time set of recommendations (i.e. forecasting) according to a published schedule with optional supporting justification. | 34 | 20 |
| Target | ImmunizationRecommendation |  | A patient's point-in-time set of recommendations (i.e. forecasting) according to a published schedule with optional supporting justification. | 34 | 20 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 2 |
Equivalent | 4 |
RelatedTo | 28 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| ImmunizationRecommendation | ImmunizationRecommendation | Equivalent | R5 `ImmunizationRecommendation` maps as Equivalent to R4 `ImmunizationRecommendation` |
| ImmunizationRecommendation.authority | ImmunizationRecommendation.authority | Equivalent | R5 `ImmunizationRecommendation.authority` maps as Equivalent to R4 `ImmunizationRecommendation.authority` |
| ImmunizationRecommendation.contained | ImmunizationRecommendation.contained | Equivalent | R5 `ImmunizationRecommendation.contained` maps as Equivalent to R4 `ImmunizationRecommendation.contained` |
| ImmunizationRecommendation.date | ImmunizationRecommendation.date | Equivalent | R5 `ImmunizationRecommendation.date` maps as Equivalent to R4 `ImmunizationRecommendation.date` |
| ImmunizationRecommendation.extension | ImmunizationRecommendation.extension | SourceIsBroaderThanTarget | R5 `ImmunizationRecommendation.extension` maps as SourceIsBroaderThanTarget to R4 `ImmunizationRecommendation.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ImmunizationRecommendation.id | ImmunizationRecommendation.id | Equivalent | R5 `ImmunizationRecommendation.id` maps as Equivalent to R4 `ImmunizationRecommendation.id` |
| ImmunizationRecommendation.identifier | ImmunizationRecommendation.identifier | Equivalent | R5 `ImmunizationRecommendation.identifier` maps as Equivalent to R4 `ImmunizationRecommendation.identifier` |
| ImmunizationRecommendation.implicitRules | ImmunizationRecommendation.implicitRules | Equivalent | R5 `ImmunizationRecommendation.implicitRules` maps as Equivalent to R4 `ImmunizationRecommendation.implicitRules` |
| ImmunizationRecommendation.language | ImmunizationRecommendation.language | RelatedTo | R5 `ImmunizationRecommendation.language` maps as RelatedTo to R4 `ImmunizationRecommendation.language` - language changed the binding strength from Required to Preferred |
| ImmunizationRecommendation.meta | ImmunizationRecommendation.meta | Equivalent | R5 `ImmunizationRecommendation.meta` maps as Equivalent to R4 `ImmunizationRecommendation.meta` |
| ImmunizationRecommendation.modifierExtension | ImmunizationRecommendation.modifierExtension | SourceIsBroaderThanTarget | R5 `ImmunizationRecommendation.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ImmunizationRecommendation.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ImmunizationRecommendation.patient | ImmunizationRecommendation.patient | Equivalent | R5 `ImmunizationRecommendation.patient` maps as Equivalent to R4 `ImmunizationRecommendation.patient` |
| ImmunizationRecommendation.recommendation | ImmunizationRecommendation.recommendation | Equivalent | R5 `ImmunizationRecommendation.recommendation` maps as Equivalent to R4 `ImmunizationRecommendation.recommendation` |
| ImmunizationRecommendation.recommendation.contraindicatedVaccineCode | ImmunizationRecommendation.recommendation.contraindicatedVaccineCode | Equivalent | R5 `ImmunizationRecommendation.recommendation.contraindicatedVaccineCode` maps as Equivalent to R4 `ImmunizationRecommendation.recommendation.contraindicatedVaccineCode` |
| ImmunizationRecommendation.recommendation.dateCriterion | ImmunizationRecommendation.recommendation.dateCriterion | Equivalent | R5 `ImmunizationRecommendation.recommendation.dateCriterion` maps as Equivalent to R4 `ImmunizationRecommendation.recommendation.dateCriterion` |
| ImmunizationRecommendation.recommendation.dateCriterion.code | ImmunizationRecommendation.recommendation.dateCriterion.code | Equivalent | R5 `ImmunizationRecommendation.recommendation.dateCriterion.code` maps as Equivalent to R4 `ImmunizationRecommendation.recommendation.dateCriterion.code` |
| ImmunizationRecommendation.recommendation.dateCriterion.extension | ImmunizationRecommendation.recommendation.dateCriterion.extension | SourceIsBroaderThanTarget | R5 `ImmunizationRecommendation.recommendation.dateCriterion.extension` maps as SourceIsBroaderThanTarget to R4 `ImmunizationRecommendation.recommendation.dateCriterion.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ImmunizationRecommendation.recommendation.dateCriterion.id | ImmunizationRecommendation.recommendation.dateCriterion.id | Equivalent | R5 `ImmunizationRecommendation.recommendation.dateCriterion.id` maps as Equivalent to R4 `ImmunizationRecommendation.recommendation.dateCriterion.id` |
| ImmunizationRecommendation.recommendation.dateCriterion.modifierExtension | ImmunizationRecommendation.recommendation.dateCriterion.modifierExtension | SourceIsBroaderThanTarget | R5 `ImmunizationRecommendation.recommendation.dateCriterion.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ImmunizationRecommendation.recommendation.dateCriterion.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ImmunizationRecommendation.recommendation.dateCriterion.value | ImmunizationRecommendation.recommendation.dateCriterion.value | Equivalent | R5 `ImmunizationRecommendation.recommendation.dateCriterion.value` maps as Equivalent to R4 `ImmunizationRecommendation.recommendation.dateCriterion.value` |
| ImmunizationRecommendation.recommendation.description | ImmunizationRecommendation.recommendation.description | SourceIsBroaderThanTarget | R5 `ImmunizationRecommendation.recommendation.description` maps as SourceIsBroaderThanTarget to R4 `ImmunizationRecommendation.recommendation.description` - description has change due to type change: R5 description markdown has no equivalent or mapped type in R4 description |
| ImmunizationRecommendation.recommendation.doseNumber | - | DoesNotExistInTarget | R5 `ImmunizationRecommendation.recommendation.doseNumber` does not appear in the target and has no mapping for `ImmunizationRecommendation`. |
| ImmunizationRecommendation.recommendation.extension | ImmunizationRecommendation.recommendation.extension | SourceIsBroaderThanTarget | R5 `ImmunizationRecommendation.recommendation.extension` maps as SourceIsBroaderThanTarget to R4 `ImmunizationRecommendation.recommendation.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ImmunizationRecommendation.recommendation.forecastReason | ImmunizationRecommendation.recommendation.forecastReason | Equivalent | R5 `ImmunizationRecommendation.recommendation.forecastReason` maps as Equivalent to R4 `ImmunizationRecommendation.recommendation.forecastReason` |
| ImmunizationRecommendation.recommendation.forecastStatus | ImmunizationRecommendation.recommendation.forecastStatus | Equivalent | R5 `ImmunizationRecommendation.recommendation.forecastStatus` maps as Equivalent to R4 `ImmunizationRecommendation.recommendation.forecastStatus` |
| ImmunizationRecommendation.recommendation.id | ImmunizationRecommendation.recommendation.id | Equivalent | R5 `ImmunizationRecommendation.recommendation.id` maps as Equivalent to R4 `ImmunizationRecommendation.recommendation.id` |
| ImmunizationRecommendation.recommendation.modifierExtension | ImmunizationRecommendation.recommendation.modifierExtension | SourceIsBroaderThanTarget | R5 `ImmunizationRecommendation.recommendation.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ImmunizationRecommendation.recommendation.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ImmunizationRecommendation.recommendation.series | ImmunizationRecommendation.recommendation.series | Equivalent | R5 `ImmunizationRecommendation.recommendation.series` maps as Equivalent to R4 `ImmunizationRecommendation.recommendation.series` |
| ImmunizationRecommendation.recommendation.seriesDoses | - | DoesNotExistInTarget | R5 `ImmunizationRecommendation.recommendation.seriesDoses` does not appear in the target and has no mapping for `ImmunizationRecommendation`. |
| ImmunizationRecommendation.recommendation.supportingImmunization | ImmunizationRecommendation.recommendation.supportingImmunization | Equivalent | R5 `ImmunizationRecommendation.recommendation.supportingImmunization` maps as Equivalent to R4 `ImmunizationRecommendation.recommendation.supportingImmunization` |
| ImmunizationRecommendation.recommendation.supportingPatientInformation | ImmunizationRecommendation.recommendation.supportingPatientInformation | Equivalent | R5 `ImmunizationRecommendation.recommendation.supportingPatientInformation` maps as Equivalent to R4 `ImmunizationRecommendation.recommendation.supportingPatientInformation` |
| ImmunizationRecommendation.recommendation.targetDisease | ImmunizationRecommendation.recommendation.targetDisease | RelatedTo | R5 `ImmunizationRecommendation.recommendation.targetDisease` maps as RelatedTo to R4 `ImmunizationRecommendation.recommendation.targetDisease` - targetDisease changed from array to scalar (max cardinality from * to 1) |
| ImmunizationRecommendation.recommendation.vaccineCode | ImmunizationRecommendation.recommendation.vaccineCode | Equivalent | R5 `ImmunizationRecommendation.recommendation.vaccineCode` maps as Equivalent to R4 `ImmunizationRecommendation.recommendation.vaccineCode` |
| ImmunizationRecommendation.text | ImmunizationRecommendation.text | Equivalent | R5 `ImmunizationRecommendation.text` maps as Equivalent to R4 `ImmunizationRecommendation.text` |

