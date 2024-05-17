Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | MeasureReport |  | The MeasureReport resource contains the results of the calculation of a measure; and optionally a reference to the resources involved in that calculation. | 56 | 30 |
| Target | MeasureReport |  | The MeasureReport resource contains the results of the calculation of a measure; and optionally a reference to the resources involved in that calculation. | 72 | 46 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 4 |
Equivalent | 4 |
RelatedTo | 48 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| MeasureReport | MeasureReport | Equivalent | R4B `MeasureReport` maps as Equivalent to R5 `MeasureReport` |
| MeasureReport.contained | MeasureReport.contained | Equivalent | R4B `MeasureReport.contained` maps as Equivalent to R5 `MeasureReport.contained` |
| MeasureReport.date | MeasureReport.date | Equivalent | R4B `MeasureReport.date` maps as Equivalent to R5 `MeasureReport.date` |
| MeasureReport.evaluatedResource | MeasureReport.evaluatedResource | Equivalent | R4B `MeasureReport.evaluatedResource` maps as Equivalent to R5 `MeasureReport.evaluatedResource` |
| MeasureReport.extension | MeasureReport.extension | RelatedTo | R4B `MeasureReport.extension` maps as RelatedTo to R5 `MeasureReport.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| MeasureReport.group | MeasureReport.group | Equivalent | R4B `MeasureReport.group` maps as Equivalent to R5 `MeasureReport.group` |
| MeasureReport.group.code | MeasureReport.group.code | Equivalent | R4B `MeasureReport.group.code` maps as Equivalent to R5 `MeasureReport.group.code` |
| MeasureReport.group.extension | MeasureReport.group.extension | RelatedTo | R4B `MeasureReport.group.extension` maps as RelatedTo to R5 `MeasureReport.group.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| MeasureReport.group.id | MeasureReport.group.id | Equivalent | R4B `MeasureReport.group.id` maps as Equivalent to R5 `MeasureReport.group.id` |
| MeasureReport.group.measureScore | - | DoesNotExistInTarget | R4B `MeasureReport.group.measureScore` does not appear in the target and has no mapping for `MeasureReport`. |
| MeasureReport.group.modifierExtension | MeasureReport.group.modifierExtension | RelatedTo | R4B `MeasureReport.group.modifierExtension` maps as RelatedTo to R5 `MeasureReport.group.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| MeasureReport.group.population | MeasureReport.group.population | Equivalent | R4B `MeasureReport.group.population` maps as Equivalent to R5 `MeasureReport.group.population` |
| MeasureReport.group.population.code | MeasureReport.group.population.code | Equivalent | R4B `MeasureReport.group.population.code` maps as Equivalent to R5 `MeasureReport.group.population.code` |
| MeasureReport.group.population.count | MeasureReport.group.population.count | Equivalent | R4B `MeasureReport.group.population.count` maps as Equivalent to R5 `MeasureReport.group.population.count` |
| MeasureReport.group.population.extension | MeasureReport.group.population.extension | RelatedTo | R4B `MeasureReport.group.population.extension` maps as RelatedTo to R5 `MeasureReport.group.population.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| MeasureReport.group.population.id | MeasureReport.group.population.id | Equivalent | R4B `MeasureReport.group.population.id` maps as Equivalent to R5 `MeasureReport.group.population.id` |
| MeasureReport.group.population.modifierExtension | MeasureReport.group.population.modifierExtension | RelatedTo | R4B `MeasureReport.group.population.modifierExtension` maps as RelatedTo to R5 `MeasureReport.group.population.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| MeasureReport.group.population.subjectResults | MeasureReport.group.population.subjectResults | Equivalent | R4B `MeasureReport.group.population.subjectResults` maps as Equivalent to R5 `MeasureReport.group.population.subjectResults` |
| MeasureReport.group.stratifier | MeasureReport.group.stratifier | Equivalent | R4B `MeasureReport.group.stratifier` maps as Equivalent to R5 `MeasureReport.group.stratifier` |
| MeasureReport.group.stratifier.code | MeasureReport.group.stratifier.code | RelatedTo | R4B `MeasureReport.group.stratifier.code` maps as RelatedTo to R5 `MeasureReport.group.stratifier.code` - code changed from array to scalar (max cardinality from * to 1) |
| MeasureReport.group.stratifier.extension | MeasureReport.group.stratifier.extension | RelatedTo | R4B `MeasureReport.group.stratifier.extension` maps as RelatedTo to R5 `MeasureReport.group.stratifier.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| MeasureReport.group.stratifier.id | MeasureReport.group.stratifier.id | Equivalent | R4B `MeasureReport.group.stratifier.id` maps as Equivalent to R5 `MeasureReport.group.stratifier.id` |
| MeasureReport.group.stratifier.modifierExtension | MeasureReport.group.stratifier.modifierExtension | RelatedTo | R4B `MeasureReport.group.stratifier.modifierExtension` maps as RelatedTo to R5 `MeasureReport.group.stratifier.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| MeasureReport.group.stratifier.stratum | MeasureReport.group.stratifier.stratum | Equivalent | R4B `MeasureReport.group.stratifier.stratum` maps as Equivalent to R5 `MeasureReport.group.stratifier.stratum` |
| MeasureReport.group.stratifier.stratum.component | MeasureReport.group.stratifier.stratum.component | Equivalent | R4B `MeasureReport.group.stratifier.stratum.component` maps as Equivalent to R5 `MeasureReport.group.stratifier.stratum.component` |
| MeasureReport.group.stratifier.stratum.component.code | MeasureReport.group.stratifier.stratum.component.code | Equivalent | R4B `MeasureReport.group.stratifier.stratum.component.code` maps as Equivalent to R5 `MeasureReport.group.stratifier.stratum.component.code` |
| MeasureReport.group.stratifier.stratum.component.extension | MeasureReport.group.stratifier.stratum.component.extension | RelatedTo | R4B `MeasureReport.group.stratifier.stratum.component.extension` maps as RelatedTo to R5 `MeasureReport.group.stratifier.stratum.component.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| MeasureReport.group.stratifier.stratum.component.id | MeasureReport.group.stratifier.stratum.component.id | Equivalent | R4B `MeasureReport.group.stratifier.stratum.component.id` maps as Equivalent to R5 `MeasureReport.group.stratifier.stratum.component.id` |
| MeasureReport.group.stratifier.stratum.component.modifierExtension | MeasureReport.group.stratifier.stratum.component.modifierExtension | RelatedTo | R4B `MeasureReport.group.stratifier.stratum.component.modifierExtension` maps as RelatedTo to R5 `MeasureReport.group.stratifier.stratum.component.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| MeasureReport.group.stratifier.stratum.component.value | - | DoesNotExistInTarget | R4B `MeasureReport.group.stratifier.stratum.component.value` does not appear in the target and has no mapping for `MeasureReport`. |
| MeasureReport.group.stratifier.stratum.extension | MeasureReport.group.stratifier.stratum.extension | RelatedTo | R4B `MeasureReport.group.stratifier.stratum.extension` maps as RelatedTo to R5 `MeasureReport.group.stratifier.stratum.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| MeasureReport.group.stratifier.stratum.id | MeasureReport.group.stratifier.stratum.id | Equivalent | R4B `MeasureReport.group.stratifier.stratum.id` maps as Equivalent to R5 `MeasureReport.group.stratifier.stratum.id` |
| MeasureReport.group.stratifier.stratum.measureScore | - | DoesNotExistInTarget | R4B `MeasureReport.group.stratifier.stratum.measureScore` does not appear in the target and has no mapping for `MeasureReport`. |
| MeasureReport.group.stratifier.stratum.modifierExtension | MeasureReport.group.stratifier.stratum.modifierExtension | RelatedTo | R4B `MeasureReport.group.stratifier.stratum.modifierExtension` maps as RelatedTo to R5 `MeasureReport.group.stratifier.stratum.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| MeasureReport.group.stratifier.stratum.population | MeasureReport.group.stratifier.stratum.population | Equivalent | R4B `MeasureReport.group.stratifier.stratum.population` maps as Equivalent to R5 `MeasureReport.group.stratifier.stratum.population` |
| MeasureReport.group.stratifier.stratum.population.code | MeasureReport.group.stratifier.stratum.population.code | Equivalent | R4B `MeasureReport.group.stratifier.stratum.population.code` maps as Equivalent to R5 `MeasureReport.group.stratifier.stratum.population.code` |
| MeasureReport.group.stratifier.stratum.population.count | MeasureReport.group.stratifier.stratum.population.count | Equivalent | R4B `MeasureReport.group.stratifier.stratum.population.count` maps as Equivalent to R5 `MeasureReport.group.stratifier.stratum.population.count` |
| MeasureReport.group.stratifier.stratum.population.extension | MeasureReport.group.stratifier.stratum.population.extension | RelatedTo | R4B `MeasureReport.group.stratifier.stratum.population.extension` maps as RelatedTo to R5 `MeasureReport.group.stratifier.stratum.population.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| MeasureReport.group.stratifier.stratum.population.id | MeasureReport.group.stratifier.stratum.population.id | Equivalent | R4B `MeasureReport.group.stratifier.stratum.population.id` maps as Equivalent to R5 `MeasureReport.group.stratifier.stratum.population.id` |
| MeasureReport.group.stratifier.stratum.population.modifierExtension | MeasureReport.group.stratifier.stratum.population.modifierExtension | RelatedTo | R4B `MeasureReport.group.stratifier.stratum.population.modifierExtension` maps as RelatedTo to R5 `MeasureReport.group.stratifier.stratum.population.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| MeasureReport.group.stratifier.stratum.population.subjectResults | MeasureReport.group.stratifier.stratum.population.subjectResults | Equivalent | R4B `MeasureReport.group.stratifier.stratum.population.subjectResults` maps as Equivalent to R5 `MeasureReport.group.stratifier.stratum.population.subjectResults` |
| MeasureReport.group.stratifier.stratum.value | - | DoesNotExistInTarget | R4B `MeasureReport.group.stratifier.stratum.value` does not appear in the target and has no mapping for `MeasureReport`. |
| MeasureReport.id | MeasureReport.id | Equivalent | R4B `MeasureReport.id` maps as Equivalent to R5 `MeasureReport.id` |
| MeasureReport.identifier | MeasureReport.identifier | Equivalent | R4B `MeasureReport.identifier` maps as Equivalent to R5 `MeasureReport.identifier` |
| MeasureReport.implicitRules | MeasureReport.implicitRules | Equivalent | R4B `MeasureReport.implicitRules` maps as Equivalent to R5 `MeasureReport.implicitRules` |
| MeasureReport.improvementNotation | MeasureReport.improvementNotation | Equivalent | R4B `MeasureReport.improvementNotation` maps as Equivalent to R5 `MeasureReport.improvementNotation` - improvementNotation has compatible required binding for non-code type: http://hl7.org/fhir/ValueSet/measure-improvement-notation|4.3.0 and http://hl7.org/fhir/ValueSet/measure-improvement-notation|5.0.0 (Equivalent) |
| MeasureReport.language | MeasureReport.language | RelatedTo | R4B `MeasureReport.language` maps as RelatedTo to R5 `MeasureReport.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| MeasureReport.measure | MeasureReport.measure | Equivalent | R4B `MeasureReport.measure` maps as Equivalent to R5 `MeasureReport.measure` |
| MeasureReport.meta | MeasureReport.meta | Equivalent | R4B `MeasureReport.meta` maps as Equivalent to R5 `MeasureReport.meta` |
| MeasureReport.modifierExtension | MeasureReport.modifierExtension | RelatedTo | R4B `MeasureReport.modifierExtension` maps as RelatedTo to R5 `MeasureReport.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| MeasureReport.period | MeasureReport.period | Equivalent | R4B `MeasureReport.period` maps as Equivalent to R5 `MeasureReport.period` |
| MeasureReport.reporter | MeasureReport.reporter | RelatedTo | R4B `MeasureReport.reporter` maps as RelatedTo to R5 `MeasureReport.reporter` - reporter has change due to type change: R4B `reporter` `Reference` maps as RelatedTo for R5 `reporter` |
| MeasureReport.status | MeasureReport.status | Equivalent | R4B `MeasureReport.status` maps as Equivalent to R5 `MeasureReport.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/measure-report-status|4.3.0 and http://hl7.org/fhir/ValueSet/measure-report-status|5.0.0 (Equivalent) |
| MeasureReport.subject | MeasureReport.subject | SourceIsNarrowerThanTarget | R4B `MeasureReport.subject` maps as SourceIsNarrowerThanTarget to R5 `MeasureReport.subject` - subject has change due to type change: R4B `subject` `Reference` maps as SourceIsNarrowerThanTarget for R5 `subject` |
| MeasureReport.text | MeasureReport.text | Equivalent | R4B `MeasureReport.text` maps as Equivalent to R5 `MeasureReport.text` |
| MeasureReport.type | MeasureReport.type | Equivalent | R4B `MeasureReport.type` maps as Equivalent to R5 `MeasureReport.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/measure-report-type|4.3.0 and http://hl7.org/fhir/ValueSet/measure-report-type|5.0.0 (Equivalent) |

