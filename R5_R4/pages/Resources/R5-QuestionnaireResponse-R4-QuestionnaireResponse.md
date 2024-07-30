Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | QuestionnaireResponse |  | A structured set of questions and their answers. The questions are ordered and grouped into coherent subsets, corresponding to the structure of the grouping of the questionnaire being responded to. | 33 | 19 |
| Target | QuestionnaireResponse |  | A structured set of questions and their answers. The questions are ordered and grouped into coherent subsets, corresponding to the structure of the grouping of the questionnaire being responded to. | 33 | 19 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 29 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| QuestionnaireResponse | QuestionnaireResponse | Equivalent | R5 `QuestionnaireResponse` maps as Equivalent to R4 `QuestionnaireResponse` |
| QuestionnaireResponse.author | QuestionnaireResponse.author | Equivalent | R5 `QuestionnaireResponse.author` maps as Equivalent to R4 `QuestionnaireResponse.author` |
| QuestionnaireResponse.authored | QuestionnaireResponse.authored | Equivalent | R5 `QuestionnaireResponse.authored` maps as Equivalent to R4 `QuestionnaireResponse.authored` |
| QuestionnaireResponse.basedOn | QuestionnaireResponse.basedOn | Equivalent | R5 `QuestionnaireResponse.basedOn` maps as Equivalent to R4 `QuestionnaireResponse.basedOn` |
| QuestionnaireResponse.contained | QuestionnaireResponse.contained | Equivalent | R5 `QuestionnaireResponse.contained` maps as Equivalent to R4 `QuestionnaireResponse.contained` |
| QuestionnaireResponse.encounter | QuestionnaireResponse.encounter | Equivalent | R5 `QuestionnaireResponse.encounter` maps as Equivalent to R4 `QuestionnaireResponse.encounter` |
| QuestionnaireResponse.extension | QuestionnaireResponse.extension | SourceIsBroaderThanTarget | R5 `QuestionnaireResponse.extension` maps as SourceIsBroaderThanTarget to R4 `QuestionnaireResponse.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| QuestionnaireResponse.id | QuestionnaireResponse.id | Equivalent | R5 `QuestionnaireResponse.id` maps as Equivalent to R4 `QuestionnaireResponse.id` |
| QuestionnaireResponse.identifier | QuestionnaireResponse.identifier | RelatedTo | R5 `QuestionnaireResponse.identifier` maps as RelatedTo to R4 `QuestionnaireResponse.identifier` - identifier changed from array to scalar (max cardinality from * to 1) |
| QuestionnaireResponse.implicitRules | QuestionnaireResponse.implicitRules | Equivalent | R5 `QuestionnaireResponse.implicitRules` maps as Equivalent to R4 `QuestionnaireResponse.implicitRules` |
| QuestionnaireResponse.item | QuestionnaireResponse.item | Equivalent | R5 `QuestionnaireResponse.item` maps as Equivalent to R4 `QuestionnaireResponse.item` |
| QuestionnaireResponse.item.answer | QuestionnaireResponse.item.answer | Equivalent | R5 `QuestionnaireResponse.item.answer` maps as Equivalent to R4 `QuestionnaireResponse.item.answer` |
| QuestionnaireResponse.item.answer.extension | QuestionnaireResponse.item.answer.extension | SourceIsBroaderThanTarget | R5 `QuestionnaireResponse.item.answer.extension` maps as SourceIsBroaderThanTarget to R4 `QuestionnaireResponse.item.answer.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| QuestionnaireResponse.item.answer.id | QuestionnaireResponse.item.answer.id | Equivalent | R5 `QuestionnaireResponse.item.answer.id` maps as Equivalent to R4 `QuestionnaireResponse.item.answer.id` |
| QuestionnaireResponse.item.answer.item | QuestionnaireResponse.item.answer.item | Equivalent | R5 `QuestionnaireResponse.item.answer.item` maps as Equivalent to R4 `QuestionnaireResponse.item.answer.item` |
| QuestionnaireResponse.item.answer.modifierExtension | QuestionnaireResponse.item.answer.modifierExtension | SourceIsBroaderThanTarget | R5 `QuestionnaireResponse.item.answer.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `QuestionnaireResponse.item.answer.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| QuestionnaireResponse.item.answer.value[x] | QuestionnaireResponse.item.answer.value[x] | RelatedTo | R5 `QuestionnaireResponse.item.answer.value[x]` maps as RelatedTo to R4 `QuestionnaireResponse.item.answer.value[x]` - value[x] has change due to type change: R5 `value[x]` `Attachment` maps as RelatedTo for R4 `value[x]`; value[x] has change due to type change: R5 `value[x]` `Quantity` maps as SourceIsBroaderThanTarget for R4 `value[x]` |
| QuestionnaireResponse.item.definition | QuestionnaireResponse.item.definition | Equivalent | R5 `QuestionnaireResponse.item.definition` maps as Equivalent to R4 `QuestionnaireResponse.item.definition` |
| QuestionnaireResponse.item.extension | QuestionnaireResponse.item.extension | SourceIsBroaderThanTarget | R5 `QuestionnaireResponse.item.extension` maps as SourceIsBroaderThanTarget to R4 `QuestionnaireResponse.item.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| QuestionnaireResponse.item.id | QuestionnaireResponse.item.id | Equivalent | R5 `QuestionnaireResponse.item.id` maps as Equivalent to R4 `QuestionnaireResponse.item.id` |
| QuestionnaireResponse.item.item | QuestionnaireResponse.item.item | Equivalent | R5 `QuestionnaireResponse.item.item` maps as Equivalent to R4 `QuestionnaireResponse.item.item` |
| QuestionnaireResponse.item.linkId | QuestionnaireResponse.item.linkId | Equivalent | R5 `QuestionnaireResponse.item.linkId` maps as Equivalent to R4 `QuestionnaireResponse.item.linkId` |
| QuestionnaireResponse.item.modifierExtension | QuestionnaireResponse.item.modifierExtension | SourceIsBroaderThanTarget | R5 `QuestionnaireResponse.item.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `QuestionnaireResponse.item.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| QuestionnaireResponse.item.text | QuestionnaireResponse.item.text | Equivalent | R5 `QuestionnaireResponse.item.text` maps as Equivalent to R4 `QuestionnaireResponse.item.text` |
| QuestionnaireResponse.language | QuestionnaireResponse.language | RelatedTo | R5 `QuestionnaireResponse.language` maps as RelatedTo to R4 `QuestionnaireResponse.language` - language changed the binding strength from Required to Preferred |
| QuestionnaireResponse.meta | QuestionnaireResponse.meta | Equivalent | R5 `QuestionnaireResponse.meta` maps as Equivalent to R4 `QuestionnaireResponse.meta` |
| QuestionnaireResponse.modifierExtension | QuestionnaireResponse.modifierExtension | SourceIsBroaderThanTarget | R5 `QuestionnaireResponse.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `QuestionnaireResponse.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| QuestionnaireResponse.partOf | QuestionnaireResponse.partOf | Equivalent | R5 `QuestionnaireResponse.partOf` maps as Equivalent to R4 `QuestionnaireResponse.partOf` |
| QuestionnaireResponse.questionnaire | QuestionnaireResponse.questionnaire | Equivalent | R5 `QuestionnaireResponse.questionnaire` maps as Equivalent to R4 `QuestionnaireResponse.questionnaire` |
| QuestionnaireResponse.source | QuestionnaireResponse.source | SourceIsBroaderThanTarget | R5 `QuestionnaireResponse.source` maps as SourceIsBroaderThanTarget to R4 `QuestionnaireResponse.source` - source has change due to type change: R5 `source` `Reference` maps as SourceIsBroaderThanTarget for R4 `source` |
| QuestionnaireResponse.status | QuestionnaireResponse.status | Equivalent | R5 `QuestionnaireResponse.status` maps as Equivalent to R4 `QuestionnaireResponse.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/questionnaire-answers-status|5.0.0 and http://hl7.org/fhir/ValueSet/questionnaire-answers-status|4.0.1 (Equivalent) |
| QuestionnaireResponse.subject | QuestionnaireResponse.subject | Equivalent | R5 `QuestionnaireResponse.subject` maps as Equivalent to R4 `QuestionnaireResponse.subject` |
| QuestionnaireResponse.text | QuestionnaireResponse.text | Equivalent | R5 `QuestionnaireResponse.text` maps as Equivalent to R4 `QuestionnaireResponse.text` |

