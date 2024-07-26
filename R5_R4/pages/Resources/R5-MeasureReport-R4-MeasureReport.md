Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1
Generated at Thursday, July 25, 2024 3:56:51 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | MeasureReport |  | The MeasureReport resource contains the results of the calculation of a measure; and optionally a reference to the resources involved in that calculation. | 72 | 46 |
| Target | MeasureReport |  | The MeasureReport resource contains the results of the calculation of a measure; and optionally a reference to the resources involved in that calculation. | 56 | 30 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 20 |
Equivalent | 4 |
RelatedTo | 48 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| MeasureReport | MeasureReport | Equivalent | R5 `MeasureReport` maps as Equivalent to R4 `MeasureReport` |
| MeasureReport.contained | MeasureReport.contained | Equivalent | R5 `MeasureReport.contained` maps as Equivalent to R4 `MeasureReport.contained` |
| MeasureReport.dataUpdateType | - | DoesNotExistInTarget | R5 `MeasureReport.dataUpdateType` does not appear in the target and has no mapping for `MeasureReport`. |
| MeasureReport.date | MeasureReport.date | Equivalent | R5 `MeasureReport.date` maps as Equivalent to R4 `MeasureReport.date` |
| MeasureReport.evaluatedResource | MeasureReport.evaluatedResource | Equivalent | R5 `MeasureReport.evaluatedResource` maps as Equivalent to R4 `MeasureReport.evaluatedResource` |
| MeasureReport.extension | MeasureReport.extension | SourceIsBroaderThanTarget | R5 `MeasureReport.extension` maps as SourceIsBroaderThanTarget to R4 `MeasureReport.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| MeasureReport.group | MeasureReport.group | Equivalent | R5 `MeasureReport.group` maps as Equivalent to R4 `MeasureReport.group` |
| MeasureReport.group.code | MeasureReport.group.code | RelatedTo | R5 `MeasureReport.group.code` maps as RelatedTo to R4 `MeasureReport.group.code` - code removed a binding requirement - Example http://hl7.org/fhir/ValueSet/measure-group-example |
| MeasureReport.group.extension | MeasureReport.group.extension | SourceIsBroaderThanTarget | R5 `MeasureReport.group.extension` maps as SourceIsBroaderThanTarget to R4 `MeasureReport.group.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| MeasureReport.group.id | MeasureReport.group.id | Equivalent | R5 `MeasureReport.group.id` maps as Equivalent to R4 `MeasureReport.group.id` |
| MeasureReport.group.linkId | - | DoesNotExistInTarget | R5 `MeasureReport.group.linkId` does not appear in the target and has no mapping for `MeasureReport`. |
| MeasureReport.group.measureScore[x] | - | DoesNotExistInTarget | R5 `MeasureReport.group.measureScore[x]` does not appear in the target and has no mapping for `MeasureReport`. |
| MeasureReport.group.modifierExtension | MeasureReport.group.modifierExtension | SourceIsBroaderThanTarget | R5 `MeasureReport.group.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `MeasureReport.group.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| MeasureReport.group.population | MeasureReport.group.population | Equivalent | R5 `MeasureReport.group.population` maps as Equivalent to R4 `MeasureReport.group.population` |
| MeasureReport.group.population.code | MeasureReport.group.population.code | Equivalent | R5 `MeasureReport.group.population.code` maps as Equivalent to R4 `MeasureReport.group.population.code` |
| MeasureReport.group.population.count | MeasureReport.group.population.count | Equivalent | R5 `MeasureReport.group.population.count` maps as Equivalent to R4 `MeasureReport.group.population.count` |
| MeasureReport.group.population.extension | MeasureReport.group.population.extension | SourceIsBroaderThanTarget | R5 `MeasureReport.group.population.extension` maps as SourceIsBroaderThanTarget to R4 `MeasureReport.group.population.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| MeasureReport.group.population.id | MeasureReport.group.population.id | Equivalent | R5 `MeasureReport.group.population.id` maps as Equivalent to R4 `MeasureReport.group.population.id` |
| MeasureReport.group.population.linkId | - | DoesNotExistInTarget | R5 `MeasureReport.group.population.linkId` does not appear in the target and has no mapping for `MeasureReport`. |
| MeasureReport.group.population.modifierExtension | MeasureReport.group.population.modifierExtension | SourceIsBroaderThanTarget | R5 `MeasureReport.group.population.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `MeasureReport.group.population.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| MeasureReport.group.population.subjectReport | - | DoesNotExistInTarget | R5 `MeasureReport.group.population.subjectReport` does not appear in the target and has no mapping for `MeasureReport`. |
| MeasureReport.group.population.subjectResults | MeasureReport.group.population.subjectResults | Equivalent | R5 `MeasureReport.group.population.subjectResults` maps as Equivalent to R4 `MeasureReport.group.population.subjectResults` |
| MeasureReport.group.population.subjects | - | DoesNotExistInTarget | R5 `MeasureReport.group.population.subjects` does not appear in the target and has no mapping for `MeasureReport`. |
| MeasureReport.group.stratifier | MeasureReport.group.stratifier | Equivalent | R5 `MeasureReport.group.stratifier` maps as Equivalent to R4 `MeasureReport.group.stratifier` |
| MeasureReport.group.stratifier.code | MeasureReport.group.stratifier.code | RelatedTo | R5 `MeasureReport.group.stratifier.code` maps as RelatedTo to R4 `MeasureReport.group.stratifier.code` - code changed from scalar to array (max cardinality from 1 to *); code removed a binding requirement - Example http://hl7.org/fhir/ValueSet/measure-stratifier-example |
| MeasureReport.group.stratifier.extension | MeasureReport.group.stratifier.extension | SourceIsBroaderThanTarget | R5 `MeasureReport.group.stratifier.extension` maps as SourceIsBroaderThanTarget to R4 `MeasureReport.group.stratifier.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| MeasureReport.group.stratifier.id | MeasureReport.group.stratifier.id | Equivalent | R5 `MeasureReport.group.stratifier.id` maps as Equivalent to R4 `MeasureReport.group.stratifier.id` |
| MeasureReport.group.stratifier.linkId | - | DoesNotExistInTarget | R5 `MeasureReport.group.stratifier.linkId` does not appear in the target and has no mapping for `MeasureReport`. |
| MeasureReport.group.stratifier.modifierExtension | MeasureReport.group.stratifier.modifierExtension | SourceIsBroaderThanTarget | R5 `MeasureReport.group.stratifier.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `MeasureReport.group.stratifier.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| MeasureReport.group.stratifier.stratum | MeasureReport.group.stratifier.stratum | Equivalent | R5 `MeasureReport.group.stratifier.stratum` maps as Equivalent to R4 `MeasureReport.group.stratifier.stratum` |
| MeasureReport.group.stratifier.stratum.component | MeasureReport.group.stratifier.stratum.component | Equivalent | R5 `MeasureReport.group.stratifier.stratum.component` maps as Equivalent to R4 `MeasureReport.group.stratifier.stratum.component` |
| MeasureReport.group.stratifier.stratum.component.code | MeasureReport.group.stratifier.stratum.component.code | RelatedTo | R5 `MeasureReport.group.stratifier.stratum.component.code` maps as RelatedTo to R4 `MeasureReport.group.stratifier.stratum.component.code` - code removed a binding requirement - Example http://hl7.org/fhir/ValueSet/measure-stratifier-example |
| MeasureReport.group.stratifier.stratum.component.extension | MeasureReport.group.stratifier.stratum.component.extension | SourceIsBroaderThanTarget | R5 `MeasureReport.group.stratifier.stratum.component.extension` maps as SourceIsBroaderThanTarget to R4 `MeasureReport.group.stratifier.stratum.component.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| MeasureReport.group.stratifier.stratum.component.id | MeasureReport.group.stratifier.stratum.component.id | Equivalent | R5 `MeasureReport.group.stratifier.stratum.component.id` maps as Equivalent to R4 `MeasureReport.group.stratifier.stratum.component.id` |
| MeasureReport.group.stratifier.stratum.component.linkId | - | DoesNotExistInTarget | R5 `MeasureReport.group.stratifier.stratum.component.linkId` does not appear in the target and has no mapping for `MeasureReport`. |
| MeasureReport.group.stratifier.stratum.component.modifierExtension | MeasureReport.group.stratifier.stratum.component.modifierExtension | SourceIsBroaderThanTarget | R5 `MeasureReport.group.stratifier.stratum.component.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `MeasureReport.group.stratifier.stratum.component.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| MeasureReport.group.stratifier.stratum.component.value[x] | - | DoesNotExistInTarget | R5 `MeasureReport.group.stratifier.stratum.component.value[x]` does not appear in the target and has no mapping for `MeasureReport`. |
| MeasureReport.group.stratifier.stratum.extension | MeasureReport.group.stratifier.stratum.extension | SourceIsBroaderThanTarget | R5 `MeasureReport.group.stratifier.stratum.extension` maps as SourceIsBroaderThanTarget to R4 `MeasureReport.group.stratifier.stratum.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| MeasureReport.group.stratifier.stratum.id | MeasureReport.group.stratifier.stratum.id | Equivalent | R5 `MeasureReport.group.stratifier.stratum.id` maps as Equivalent to R4 `MeasureReport.group.stratifier.stratum.id` |
| MeasureReport.group.stratifier.stratum.measureScore[x] | - | DoesNotExistInTarget | R5 `MeasureReport.group.stratifier.stratum.measureScore[x]` does not appear in the target and has no mapping for `MeasureReport`. |
| MeasureReport.group.stratifier.stratum.modifierExtension | MeasureReport.group.stratifier.stratum.modifierExtension | SourceIsBroaderThanTarget | R5 `MeasureReport.group.stratifier.stratum.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `MeasureReport.group.stratifier.stratum.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| MeasureReport.group.stratifier.stratum.population | MeasureReport.group.stratifier.stratum.population | Equivalent | R5 `MeasureReport.group.stratifier.stratum.population` maps as Equivalent to R4 `MeasureReport.group.stratifier.stratum.population` |
| MeasureReport.group.stratifier.stratum.population.code | MeasureReport.group.stratifier.stratum.population.code | Equivalent | R5 `MeasureReport.group.stratifier.stratum.population.code` maps as Equivalent to R4 `MeasureReport.group.stratifier.stratum.population.code` |
| MeasureReport.group.stratifier.stratum.population.count | MeasureReport.group.stratifier.stratum.population.count | Equivalent | R5 `MeasureReport.group.stratifier.stratum.population.count` maps as Equivalent to R4 `MeasureReport.group.stratifier.stratum.population.count` |
| MeasureReport.group.stratifier.stratum.population.extension | MeasureReport.group.stratifier.stratum.population.extension | SourceIsBroaderThanTarget | R5 `MeasureReport.group.stratifier.stratum.population.extension` maps as SourceIsBroaderThanTarget to R4 `MeasureReport.group.stratifier.stratum.population.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| MeasureReport.group.stratifier.stratum.population.id | MeasureReport.group.stratifier.stratum.population.id | Equivalent | R5 `MeasureReport.group.stratifier.stratum.population.id` maps as Equivalent to R4 `MeasureReport.group.stratifier.stratum.population.id` |
| MeasureReport.group.stratifier.stratum.population.linkId | - | DoesNotExistInTarget | R5 `MeasureReport.group.stratifier.stratum.population.linkId` does not appear in the target and has no mapping for `MeasureReport`. |
| MeasureReport.group.stratifier.stratum.population.modifierExtension | MeasureReport.group.stratifier.stratum.population.modifierExtension | SourceIsBroaderThanTarget | R5 `MeasureReport.group.stratifier.stratum.population.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `MeasureReport.group.stratifier.stratum.population.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| MeasureReport.group.stratifier.stratum.population.subjectReport | - | DoesNotExistInTarget | R5 `MeasureReport.group.stratifier.stratum.population.subjectReport` does not appear in the target and has no mapping for `MeasureReport`. |
| MeasureReport.group.stratifier.stratum.population.subjectResults | MeasureReport.group.stratifier.stratum.population.subjectResults | Equivalent | R5 `MeasureReport.group.stratifier.stratum.population.subjectResults` maps as Equivalent to R4 `MeasureReport.group.stratifier.stratum.population.subjectResults` |
| MeasureReport.group.stratifier.stratum.population.subjects | - | DoesNotExistInTarget | R5 `MeasureReport.group.stratifier.stratum.population.subjects` does not appear in the target and has no mapping for `MeasureReport`. |
| MeasureReport.group.stratifier.stratum.value[x] | - | DoesNotExistInTarget | R5 `MeasureReport.group.stratifier.stratum.value[x]` does not appear in the target and has no mapping for `MeasureReport`. |
| MeasureReport.group.subject | - | DoesNotExistInTarget | R5 `MeasureReport.group.subject` does not appear in the target and has no mapping for `MeasureReport`. |
| MeasureReport.id | MeasureReport.id | Equivalent | R5 `MeasureReport.id` maps as Equivalent to R4 `MeasureReport.id` |
| MeasureReport.identifier | MeasureReport.identifier | Equivalent | R5 `MeasureReport.identifier` maps as Equivalent to R4 `MeasureReport.identifier` |
| MeasureReport.implicitRules | MeasureReport.implicitRules | Equivalent | R5 `MeasureReport.implicitRules` maps as Equivalent to R4 `MeasureReport.implicitRules` |
| MeasureReport.improvementNotation | MeasureReport.improvementNotation | Equivalent | R5 `MeasureReport.improvementNotation` maps as Equivalent to R4 `MeasureReport.improvementNotation` - improvementNotation has compatible required binding for non-code type: http://hl7.org/fhir/ValueSet/measure-improvement-notation|5.0.0 and http://hl7.org/fhir/ValueSet/measure-improvement-notation|4.0.1 (Equivalent) |
| MeasureReport.inputParameters | - | DoesNotExistInTarget | R5 `MeasureReport.inputParameters` does not appear in the target and has no mapping for `MeasureReport`. |
| MeasureReport.language | MeasureReport.language | RelatedTo | R5 `MeasureReport.language` maps as RelatedTo to R4 `MeasureReport.language` - language changed the binding strength from Required to Preferred |
| MeasureReport.location | - | DoesNotExistInTarget | R5 `MeasureReport.location` does not appear in the target and has no mapping for `MeasureReport`. |
| MeasureReport.measure | MeasureReport.measure | RelatedTo | R5 `MeasureReport.measure` maps as RelatedTo to R4 `MeasureReport.measure` - measure made the element mandatory; measure increased the minimum cardinality from 0 to 1 |
| MeasureReport.meta | MeasureReport.meta | Equivalent | R5 `MeasureReport.meta` maps as Equivalent to R4 `MeasureReport.meta` |
| MeasureReport.modifierExtension | MeasureReport.modifierExtension | SourceIsBroaderThanTarget | R5 `MeasureReport.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `MeasureReport.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| MeasureReport.period | MeasureReport.period | Equivalent | R5 `MeasureReport.period` maps as Equivalent to R4 `MeasureReport.period` |
| MeasureReport.reporter | MeasureReport.reporter | RelatedTo | R5 `MeasureReport.reporter` maps as RelatedTo to R4 `MeasureReport.reporter` - reporter has change due to type change: R5 `reporter` `Reference` maps as RelatedTo for R4 `reporter` |
| MeasureReport.reportingVendor | - | DoesNotExistInTarget | R5 `MeasureReport.reportingVendor` does not appear in the target and has no mapping for `MeasureReport`. |
| MeasureReport.scoring | - | DoesNotExistInTarget | R5 `MeasureReport.scoring` does not appear in the target and has no mapping for `MeasureReport`. |
| MeasureReport.status | MeasureReport.status | Equivalent | R5 `MeasureReport.status` maps as Equivalent to R4 `MeasureReport.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/measure-report-status|5.0.0 and http://hl7.org/fhir/ValueSet/measure-report-status|4.0.1 (Equivalent) |
| MeasureReport.subject | MeasureReport.subject | SourceIsBroaderThanTarget | R5 `MeasureReport.subject` maps as SourceIsBroaderThanTarget to R4 `MeasureReport.subject` - subject has change due to type change: R5 `subject` `Reference` maps as SourceIsBroaderThanTarget for R4 `subject` |
| MeasureReport.supplementalData | - | DoesNotExistInTarget | R5 `MeasureReport.supplementalData` does not appear in the target and has no mapping for `MeasureReport`. |
| MeasureReport.text | MeasureReport.text | Equivalent | R5 `MeasureReport.text` maps as Equivalent to R4 `MeasureReport.text` |
| MeasureReport.type | MeasureReport.type | Equivalent | R5 `MeasureReport.type` maps as Equivalent to R4 `MeasureReport.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/measure-report-type|5.0.0 and http://hl7.org/fhir/ValueSet/measure-report-type|4.0.1 (Equivalent) |

