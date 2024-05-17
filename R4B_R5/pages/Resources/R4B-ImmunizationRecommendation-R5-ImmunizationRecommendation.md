Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

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
| ImmunizationRecommendation | ImmunizationRecommendation | Equivalent | R4B `ImmunizationRecommendation` maps as Equivalent to R5 `ImmunizationRecommendation` |
| ImmunizationRecommendation.authority | ImmunizationRecommendation.authority | Equivalent | R4B `ImmunizationRecommendation.authority` maps as Equivalent to R5 `ImmunizationRecommendation.authority` |
| ImmunizationRecommendation.contained | ImmunizationRecommendation.contained | Equivalent | R4B `ImmunizationRecommendation.contained` maps as Equivalent to R5 `ImmunizationRecommendation.contained` |
| ImmunizationRecommendation.date | ImmunizationRecommendation.date | Equivalent | R4B `ImmunizationRecommendation.date` maps as Equivalent to R5 `ImmunizationRecommendation.date` |
| ImmunizationRecommendation.extension | ImmunizationRecommendation.extension | RelatedTo | R4B `ImmunizationRecommendation.extension` maps as RelatedTo to R5 `ImmunizationRecommendation.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ImmunizationRecommendation.id | ImmunizationRecommendation.id | Equivalent | R4B `ImmunizationRecommendation.id` maps as Equivalent to R5 `ImmunizationRecommendation.id` |
| ImmunizationRecommendation.identifier | ImmunizationRecommendation.identifier | Equivalent | R4B `ImmunizationRecommendation.identifier` maps as Equivalent to R5 `ImmunizationRecommendation.identifier` |
| ImmunizationRecommendation.implicitRules | ImmunizationRecommendation.implicitRules | Equivalent | R4B `ImmunizationRecommendation.implicitRules` maps as Equivalent to R5 `ImmunizationRecommendation.implicitRules` |
| ImmunizationRecommendation.language | ImmunizationRecommendation.language | RelatedTo | R4B `ImmunizationRecommendation.language` maps as RelatedTo to R5 `ImmunizationRecommendation.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| ImmunizationRecommendation.meta | ImmunizationRecommendation.meta | Equivalent | R4B `ImmunizationRecommendation.meta` maps as Equivalent to R5 `ImmunizationRecommendation.meta` |
| ImmunizationRecommendation.modifierExtension | ImmunizationRecommendation.modifierExtension | RelatedTo | R4B `ImmunizationRecommendation.modifierExtension` maps as RelatedTo to R5 `ImmunizationRecommendation.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ImmunizationRecommendation.patient | ImmunizationRecommendation.patient | Equivalent | R4B `ImmunizationRecommendation.patient` maps as Equivalent to R5 `ImmunizationRecommendation.patient` |
| ImmunizationRecommendation.recommendation | ImmunizationRecommendation.recommendation | Equivalent | R4B `ImmunizationRecommendation.recommendation` maps as Equivalent to R5 `ImmunizationRecommendation.recommendation` |
| ImmunizationRecommendation.recommendation.contraindicatedVaccineCode | ImmunizationRecommendation.recommendation.contraindicatedVaccineCode | Equivalent | R4B `ImmunizationRecommendation.recommendation.contraindicatedVaccineCode` maps as Equivalent to R5 `ImmunizationRecommendation.recommendation.contraindicatedVaccineCode` |
| ImmunizationRecommendation.recommendation.dateCriterion | ImmunizationRecommendation.recommendation.dateCriterion | Equivalent | R4B `ImmunizationRecommendation.recommendation.dateCriterion` maps as Equivalent to R5 `ImmunizationRecommendation.recommendation.dateCriterion` |
| ImmunizationRecommendation.recommendation.dateCriterion.code | ImmunizationRecommendation.recommendation.dateCriterion.code | Equivalent | R4B `ImmunizationRecommendation.recommendation.dateCriterion.code` maps as Equivalent to R5 `ImmunizationRecommendation.recommendation.dateCriterion.code` |
| ImmunizationRecommendation.recommendation.dateCriterion.extension | ImmunizationRecommendation.recommendation.dateCriterion.extension | RelatedTo | R4B `ImmunizationRecommendation.recommendation.dateCriterion.extension` maps as RelatedTo to R5 `ImmunizationRecommendation.recommendation.dateCriterion.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ImmunizationRecommendation.recommendation.dateCriterion.id | ImmunizationRecommendation.recommendation.dateCriterion.id | Equivalent | R4B `ImmunizationRecommendation.recommendation.dateCriterion.id` maps as Equivalent to R5 `ImmunizationRecommendation.recommendation.dateCriterion.id` |
| ImmunizationRecommendation.recommendation.dateCriterion.modifierExtension | ImmunizationRecommendation.recommendation.dateCriterion.modifierExtension | RelatedTo | R4B `ImmunizationRecommendation.recommendation.dateCriterion.modifierExtension` maps as RelatedTo to R5 `ImmunizationRecommendation.recommendation.dateCriterion.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ImmunizationRecommendation.recommendation.dateCriterion.value | ImmunizationRecommendation.recommendation.dateCriterion.value | Equivalent | R4B `ImmunizationRecommendation.recommendation.dateCriterion.value` maps as Equivalent to R5 `ImmunizationRecommendation.recommendation.dateCriterion.value` |
| ImmunizationRecommendation.recommendation.description | ImmunizationRecommendation.recommendation.description | SourceIsBroaderThanTarget | R4B `ImmunizationRecommendation.recommendation.description` maps as SourceIsBroaderThanTarget to R5 `ImmunizationRecommendation.recommendation.description` - description has change due to type change: R4B description string has no equivalent or mapped type in R5 description |
| ImmunizationRecommendation.recommendation.doseNumber[x] | - | DoesNotExistInTarget | R4B `ImmunizationRecommendation.recommendation.doseNumber[x]` does not appear in the target and has no mapping for `ImmunizationRecommendation`. |
| ImmunizationRecommendation.recommendation.extension | ImmunizationRecommendation.recommendation.extension | RelatedTo | R4B `ImmunizationRecommendation.recommendation.extension` maps as RelatedTo to R5 `ImmunizationRecommendation.recommendation.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ImmunizationRecommendation.recommendation.forecastReason | ImmunizationRecommendation.recommendation.forecastReason | Equivalent | R4B `ImmunizationRecommendation.recommendation.forecastReason` maps as Equivalent to R5 `ImmunizationRecommendation.recommendation.forecastReason` |
| ImmunizationRecommendation.recommendation.forecastStatus | ImmunizationRecommendation.recommendation.forecastStatus | Equivalent | R4B `ImmunizationRecommendation.recommendation.forecastStatus` maps as Equivalent to R5 `ImmunizationRecommendation.recommendation.forecastStatus` |
| ImmunizationRecommendation.recommendation.id | ImmunizationRecommendation.recommendation.id | Equivalent | R4B `ImmunizationRecommendation.recommendation.id` maps as Equivalent to R5 `ImmunizationRecommendation.recommendation.id` |
| ImmunizationRecommendation.recommendation.modifierExtension | ImmunizationRecommendation.recommendation.modifierExtension | RelatedTo | R4B `ImmunizationRecommendation.recommendation.modifierExtension` maps as RelatedTo to R5 `ImmunizationRecommendation.recommendation.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ImmunizationRecommendation.recommendation.series | ImmunizationRecommendation.recommendation.series | Equivalent | R4B `ImmunizationRecommendation.recommendation.series` maps as Equivalent to R5 `ImmunizationRecommendation.recommendation.series` |
| ImmunizationRecommendation.recommendation.seriesDoses[x] | - | DoesNotExistInTarget | R4B `ImmunizationRecommendation.recommendation.seriesDoses[x]` does not appear in the target and has no mapping for `ImmunizationRecommendation`. |
| ImmunizationRecommendation.recommendation.supportingImmunization | ImmunizationRecommendation.recommendation.supportingImmunization | Equivalent | R4B `ImmunizationRecommendation.recommendation.supportingImmunization` maps as Equivalent to R5 `ImmunizationRecommendation.recommendation.supportingImmunization` |
| ImmunizationRecommendation.recommendation.supportingPatientInformation | ImmunizationRecommendation.recommendation.supportingPatientInformation | Equivalent | R4B `ImmunizationRecommendation.recommendation.supportingPatientInformation` maps as Equivalent to R5 `ImmunizationRecommendation.recommendation.supportingPatientInformation` |
| ImmunizationRecommendation.recommendation.targetDisease | ImmunizationRecommendation.recommendation.targetDisease | RelatedTo | R4B `ImmunizationRecommendation.recommendation.targetDisease` maps as RelatedTo to R5 `ImmunizationRecommendation.recommendation.targetDisease` - targetDisease changed from scalar to array (max cardinality from 1 to *) |
| ImmunizationRecommendation.recommendation.vaccineCode | ImmunizationRecommendation.recommendation.vaccineCode | Equivalent | R4B `ImmunizationRecommendation.recommendation.vaccineCode` maps as Equivalent to R5 `ImmunizationRecommendation.recommendation.vaccineCode` |
| ImmunizationRecommendation.text | ImmunizationRecommendation.text | Equivalent | R4B `ImmunizationRecommendation.text` maps as Equivalent to R5 `ImmunizationRecommendation.text` |

