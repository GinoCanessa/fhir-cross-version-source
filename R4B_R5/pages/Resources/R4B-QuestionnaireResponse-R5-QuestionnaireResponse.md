Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

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
| QuestionnaireResponse | QuestionnaireResponse | Equivalent | R4B `QuestionnaireResponse` maps as Equivalent to R5 `QuestionnaireResponse` |
| QuestionnaireResponse.author | QuestionnaireResponse.author | Equivalent | R4B `QuestionnaireResponse.author` maps as Equivalent to R5 `QuestionnaireResponse.author` |
| QuestionnaireResponse.authored | QuestionnaireResponse.authored | Equivalent | R4B `QuestionnaireResponse.authored` maps as Equivalent to R5 `QuestionnaireResponse.authored` |
| QuestionnaireResponse.basedOn | QuestionnaireResponse.basedOn | Equivalent | R4B `QuestionnaireResponse.basedOn` maps as Equivalent to R5 `QuestionnaireResponse.basedOn` |
| QuestionnaireResponse.contained | QuestionnaireResponse.contained | Equivalent | R4B `QuestionnaireResponse.contained` maps as Equivalent to R5 `QuestionnaireResponse.contained` |
| QuestionnaireResponse.encounter | QuestionnaireResponse.encounter | Equivalent | R4B `QuestionnaireResponse.encounter` maps as Equivalent to R5 `QuestionnaireResponse.encounter` |
| QuestionnaireResponse.extension | QuestionnaireResponse.extension | RelatedTo | R4B `QuestionnaireResponse.extension` maps as RelatedTo to R5 `QuestionnaireResponse.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| QuestionnaireResponse.id | QuestionnaireResponse.id | Equivalent | R4B `QuestionnaireResponse.id` maps as Equivalent to R5 `QuestionnaireResponse.id` |
| QuestionnaireResponse.identifier | QuestionnaireResponse.identifier | RelatedTo | R4B `QuestionnaireResponse.identifier` maps as RelatedTo to R5 `QuestionnaireResponse.identifier` - identifier changed from scalar to array (max cardinality from 1 to *) |
| QuestionnaireResponse.implicitRules | QuestionnaireResponse.implicitRules | Equivalent | R4B `QuestionnaireResponse.implicitRules` maps as Equivalent to R5 `QuestionnaireResponse.implicitRules` |
| QuestionnaireResponse.item | QuestionnaireResponse.item | Equivalent | R4B `QuestionnaireResponse.item` maps as Equivalent to R5 `QuestionnaireResponse.item` |
| QuestionnaireResponse.item.answer | QuestionnaireResponse.item.answer | Equivalent | R4B `QuestionnaireResponse.item.answer` maps as Equivalent to R5 `QuestionnaireResponse.item.answer` |
| QuestionnaireResponse.item.answer.extension | QuestionnaireResponse.item.answer.extension | RelatedTo | R4B `QuestionnaireResponse.item.answer.extension` maps as RelatedTo to R5 `QuestionnaireResponse.item.answer.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| QuestionnaireResponse.item.answer.id | QuestionnaireResponse.item.answer.id | Equivalent | R4B `QuestionnaireResponse.item.answer.id` maps as Equivalent to R5 `QuestionnaireResponse.item.answer.id` |
| QuestionnaireResponse.item.answer.item | QuestionnaireResponse.item.answer.item | Equivalent | R4B `QuestionnaireResponse.item.answer.item` maps as Equivalent to R5 `QuestionnaireResponse.item.answer.item` |
| QuestionnaireResponse.item.answer.modifierExtension | QuestionnaireResponse.item.answer.modifierExtension | RelatedTo | R4B `QuestionnaireResponse.item.answer.modifierExtension` maps as RelatedTo to R5 `QuestionnaireResponse.item.answer.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| QuestionnaireResponse.item.answer.value[x] | QuestionnaireResponse.item.answer.value[x] | RelatedTo | R4B `QuestionnaireResponse.item.answer.value[x]` maps as RelatedTo to R5 `QuestionnaireResponse.item.answer.value[x]` - value[x] made the element mandatory; value[x] increased the minimum cardinality from 0 to 1; value[x] has change due to type change: R4B `value[x]` `Attachment` maps as RelatedTo for R5 `value[x]`; value[x] has change due to type change: R4B `value[x]` `Quantity` maps as SourceIsNarrowerThanTarget for R5 `value[x]` |
| QuestionnaireResponse.item.definition | QuestionnaireResponse.item.definition | Equivalent | R4B `QuestionnaireResponse.item.definition` maps as Equivalent to R5 `QuestionnaireResponse.item.definition` |
| QuestionnaireResponse.item.extension | QuestionnaireResponse.item.extension | RelatedTo | R4B `QuestionnaireResponse.item.extension` maps as RelatedTo to R5 `QuestionnaireResponse.item.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| QuestionnaireResponse.item.id | QuestionnaireResponse.item.id | Equivalent | R4B `QuestionnaireResponse.item.id` maps as Equivalent to R5 `QuestionnaireResponse.item.id` |
| QuestionnaireResponse.item.item | QuestionnaireResponse.item.item | Equivalent | R4B `QuestionnaireResponse.item.item` maps as Equivalent to R5 `QuestionnaireResponse.item.item` |
| QuestionnaireResponse.item.linkId | QuestionnaireResponse.item.linkId | Equivalent | R4B `QuestionnaireResponse.item.linkId` maps as Equivalent to R5 `QuestionnaireResponse.item.linkId` |
| QuestionnaireResponse.item.modifierExtension | QuestionnaireResponse.item.modifierExtension | RelatedTo | R4B `QuestionnaireResponse.item.modifierExtension` maps as RelatedTo to R5 `QuestionnaireResponse.item.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| QuestionnaireResponse.item.text | QuestionnaireResponse.item.text | Equivalent | R4B `QuestionnaireResponse.item.text` maps as Equivalent to R5 `QuestionnaireResponse.item.text` |
| QuestionnaireResponse.language | QuestionnaireResponse.language | RelatedTo | R4B `QuestionnaireResponse.language` maps as RelatedTo to R5 `QuestionnaireResponse.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| QuestionnaireResponse.meta | QuestionnaireResponse.meta | Equivalent | R4B `QuestionnaireResponse.meta` maps as Equivalent to R5 `QuestionnaireResponse.meta` |
| QuestionnaireResponse.modifierExtension | QuestionnaireResponse.modifierExtension | RelatedTo | R4B `QuestionnaireResponse.modifierExtension` maps as RelatedTo to R5 `QuestionnaireResponse.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| QuestionnaireResponse.partOf | QuestionnaireResponse.partOf | Equivalent | R4B `QuestionnaireResponse.partOf` maps as Equivalent to R5 `QuestionnaireResponse.partOf` |
| QuestionnaireResponse.questionnaire | QuestionnaireResponse.questionnaire | RelatedTo | R4B `QuestionnaireResponse.questionnaire` maps as RelatedTo to R5 `QuestionnaireResponse.questionnaire` - questionnaire made the element mandatory; questionnaire increased the minimum cardinality from 0 to 1 |
| QuestionnaireResponse.source | QuestionnaireResponse.source | SourceIsNarrowerThanTarget | R4B `QuestionnaireResponse.source` maps as SourceIsNarrowerThanTarget to R5 `QuestionnaireResponse.source` - source has change due to type change: R4B `source` `Reference` maps as SourceIsNarrowerThanTarget for R5 `source` |
| QuestionnaireResponse.status | QuestionnaireResponse.status | Equivalent | R4B `QuestionnaireResponse.status` maps as Equivalent to R5 `QuestionnaireResponse.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/questionnaire-answers-status|4.3.0 and http://hl7.org/fhir/ValueSet/questionnaire-answers-status|5.0.0 (Equivalent) |
| QuestionnaireResponse.subject | QuestionnaireResponse.subject | Equivalent | R4B `QuestionnaireResponse.subject` maps as Equivalent to R5 `QuestionnaireResponse.subject` |
| QuestionnaireResponse.text | QuestionnaireResponse.text | Equivalent | R4B `QuestionnaireResponse.text` maps as Equivalent to R5 `QuestionnaireResponse.text` |

