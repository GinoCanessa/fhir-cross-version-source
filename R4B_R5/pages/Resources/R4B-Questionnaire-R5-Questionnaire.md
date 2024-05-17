Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Questionnaire |  | A structured set of questions intended to guide the collection of answers from end-users. Questionnaires provide detailed control over order, presentation, phraseology and grouping to allow coherent, consistent data collection. | 65 | 45 |
| Target | Questionnaire |  | A structured set of questions intended to guide the collection of answers from end-users. Questionnaires provide detailed control over order, presentation, phraseology and grouping to allow coherent, consistent data collection. | 69 | 49 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 61 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Questionnaire | Questionnaire | Equivalent | R4B `Questionnaire` maps as Equivalent to R5 `Questionnaire` |
| Questionnaire.approvalDate | Questionnaire.approvalDate | Equivalent | R4B `Questionnaire.approvalDate` maps as Equivalent to R5 `Questionnaire.approvalDate` |
| Questionnaire.code | Questionnaire.code | Equivalent | R4B `Questionnaire.code` maps as Equivalent to R5 `Questionnaire.code` |
| Questionnaire.contact | Questionnaire.contact | Equivalent | R4B `Questionnaire.contact` maps as Equivalent to R5 `Questionnaire.contact` |
| Questionnaire.contained | Questionnaire.contained | Equivalent | R4B `Questionnaire.contained` maps as Equivalent to R5 `Questionnaire.contained` |
| Questionnaire.copyright | Questionnaire.copyright | Equivalent | R4B `Questionnaire.copyright` maps as Equivalent to R5 `Questionnaire.copyright` |
| Questionnaire.date | Questionnaire.date | Equivalent | R4B `Questionnaire.date` maps as Equivalent to R5 `Questionnaire.date` |
| Questionnaire.derivedFrom | Questionnaire.derivedFrom | Equivalent | R4B `Questionnaire.derivedFrom` maps as Equivalent to R5 `Questionnaire.derivedFrom` |
| Questionnaire.description | Questionnaire.description | Equivalent | R4B `Questionnaire.description` maps as Equivalent to R5 `Questionnaire.description` |
| Questionnaire.effectivePeriod | Questionnaire.effectivePeriod | Equivalent | R4B `Questionnaire.effectivePeriod` maps as Equivalent to R5 `Questionnaire.effectivePeriod` |
| Questionnaire.experimental | Questionnaire.experimental | Equivalent | R4B `Questionnaire.experimental` maps as Equivalent to R5 `Questionnaire.experimental` |
| Questionnaire.extension | Questionnaire.extension | RelatedTo | R4B `Questionnaire.extension` maps as RelatedTo to R5 `Questionnaire.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Questionnaire.id | Questionnaire.id | Equivalent | R4B `Questionnaire.id` maps as Equivalent to R5 `Questionnaire.id` |
| Questionnaire.identifier | Questionnaire.identifier | Equivalent | R4B `Questionnaire.identifier` maps as Equivalent to R5 `Questionnaire.identifier` |
| Questionnaire.implicitRules | Questionnaire.implicitRules | Equivalent | R4B `Questionnaire.implicitRules` maps as Equivalent to R5 `Questionnaire.implicitRules` |
| Questionnaire.item | Questionnaire.item | Equivalent | R4B `Questionnaire.item` maps as Equivalent to R5 `Questionnaire.item` |
| Questionnaire.item.answerOption | Questionnaire.item.answerOption | Equivalent | R4B `Questionnaire.item.answerOption` maps as Equivalent to R5 `Questionnaire.item.answerOption` |
| Questionnaire.item.answerOption.extension | Questionnaire.item.answerOption.extension | RelatedTo | R4B `Questionnaire.item.answerOption.extension` maps as RelatedTo to R5 `Questionnaire.item.answerOption.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Questionnaire.item.answerOption.id | Questionnaire.item.answerOption.id | Equivalent | R4B `Questionnaire.item.answerOption.id` maps as Equivalent to R5 `Questionnaire.item.answerOption.id` |
| Questionnaire.item.answerOption.initialSelected | Questionnaire.item.answerOption.initialSelected | Equivalent | R4B `Questionnaire.item.answerOption.initialSelected` maps as Equivalent to R5 `Questionnaire.item.answerOption.initialSelected` |
| Questionnaire.item.answerOption.modifierExtension | Questionnaire.item.answerOption.modifierExtension | RelatedTo | R4B `Questionnaire.item.answerOption.modifierExtension` maps as RelatedTo to R5 `Questionnaire.item.answerOption.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Questionnaire.item.answerOption.value[x] | Questionnaire.item.answerOption.value[x] | Equivalent | R4B `Questionnaire.item.answerOption.value[x]` maps as Equivalent to R5 `Questionnaire.item.answerOption.value[x]` |
| Questionnaire.item.answerValueSet | Questionnaire.item.answerValueSet | Equivalent | R4B `Questionnaire.item.answerValueSet` maps as Equivalent to R5 `Questionnaire.item.answerValueSet` |
| Questionnaire.item.code | Questionnaire.item.code | Equivalent | R4B `Questionnaire.item.code` maps as Equivalent to R5 `Questionnaire.item.code` |
| Questionnaire.item.definition | Questionnaire.item.definition | Equivalent | R4B `Questionnaire.item.definition` maps as Equivalent to R5 `Questionnaire.item.definition` |
| Questionnaire.item.enableBehavior | Questionnaire.item.enableBehavior | Equivalent | R4B `Questionnaire.item.enableBehavior` maps as Equivalent to R5 `Questionnaire.item.enableBehavior` - enableBehavior has compatible required binding for code type: http://hl7.org/fhir/ValueSet/questionnaire-enable-behavior|4.3.0 and http://hl7.org/fhir/ValueSet/questionnaire-enable-behavior|5.0.0 (Equivalent) |
| Questionnaire.item.enableWhen | Questionnaire.item.enableWhen | Equivalent | R4B `Questionnaire.item.enableWhen` maps as Equivalent to R5 `Questionnaire.item.enableWhen` |
| Questionnaire.item.enableWhen.answer[x] | Questionnaire.item.enableWhen.answer[x] | Equivalent | R4B `Questionnaire.item.enableWhen.answer[x]` maps as Equivalent to R5 `Questionnaire.item.enableWhen.answer[x]` |
| Questionnaire.item.enableWhen.extension | Questionnaire.item.enableWhen.extension | RelatedTo | R4B `Questionnaire.item.enableWhen.extension` maps as RelatedTo to R5 `Questionnaire.item.enableWhen.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Questionnaire.item.enableWhen.id | Questionnaire.item.enableWhen.id | Equivalent | R4B `Questionnaire.item.enableWhen.id` maps as Equivalent to R5 `Questionnaire.item.enableWhen.id` |
| Questionnaire.item.enableWhen.modifierExtension | Questionnaire.item.enableWhen.modifierExtension | RelatedTo | R4B `Questionnaire.item.enableWhen.modifierExtension` maps as RelatedTo to R5 `Questionnaire.item.enableWhen.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Questionnaire.item.enableWhen.operator | Questionnaire.item.enableWhen.operator | Equivalent | R4B `Questionnaire.item.enableWhen.operator` maps as Equivalent to R5 `Questionnaire.item.enableWhen.operator` - operator has compatible required binding for code type: http://hl7.org/fhir/ValueSet/questionnaire-enable-operator|4.3.0 and http://hl7.org/fhir/ValueSet/questionnaire-enable-operator|5.0.0 (Equivalent) |
| Questionnaire.item.enableWhen.question | Questionnaire.item.enableWhen.question | Equivalent | R4B `Questionnaire.item.enableWhen.question` maps as Equivalent to R5 `Questionnaire.item.enableWhen.question` |
| Questionnaire.item.extension | Questionnaire.item.extension | RelatedTo | R4B `Questionnaire.item.extension` maps as RelatedTo to R5 `Questionnaire.item.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Questionnaire.item.id | Questionnaire.item.id | Equivalent | R4B `Questionnaire.item.id` maps as Equivalent to R5 `Questionnaire.item.id` |
| Questionnaire.item.initial | Questionnaire.item.initial | Equivalent | R4B `Questionnaire.item.initial` maps as Equivalent to R5 `Questionnaire.item.initial` |
| Questionnaire.item.initial.extension | Questionnaire.item.initial.extension | RelatedTo | R4B `Questionnaire.item.initial.extension` maps as RelatedTo to R5 `Questionnaire.item.initial.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Questionnaire.item.initial.id | Questionnaire.item.initial.id | Equivalent | R4B `Questionnaire.item.initial.id` maps as Equivalent to R5 `Questionnaire.item.initial.id` |
| Questionnaire.item.initial.modifierExtension | Questionnaire.item.initial.modifierExtension | RelatedTo | R4B `Questionnaire.item.initial.modifierExtension` maps as RelatedTo to R5 `Questionnaire.item.initial.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Questionnaire.item.initial.value[x] | Questionnaire.item.initial.value[x] | RelatedTo | R4B `Questionnaire.item.initial.value[x]` maps as RelatedTo to R5 `Questionnaire.item.initial.value[x]` - value[x] has change due to type change: R4B `value[x]` `Attachment` maps as RelatedTo for R5 `value[x]` |
| Questionnaire.item.item | Questionnaire.item.item | Equivalent | R4B `Questionnaire.item.item` maps as Equivalent to R5 `Questionnaire.item.item` |
| Questionnaire.item.linkId | Questionnaire.item.linkId | Equivalent | R4B `Questionnaire.item.linkId` maps as Equivalent to R5 `Questionnaire.item.linkId` |
| Questionnaire.item.maxLength | Questionnaire.item.maxLength | Equivalent | R4B `Questionnaire.item.maxLength` maps as Equivalent to R5 `Questionnaire.item.maxLength` |
| Questionnaire.item.modifierExtension | Questionnaire.item.modifierExtension | RelatedTo | R4B `Questionnaire.item.modifierExtension` maps as RelatedTo to R5 `Questionnaire.item.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Questionnaire.item.prefix | Questionnaire.item.prefix | Equivalent | R4B `Questionnaire.item.prefix` maps as Equivalent to R5 `Questionnaire.item.prefix` |
| Questionnaire.item.readOnly | Questionnaire.item.readOnly | Equivalent | R4B `Questionnaire.item.readOnly` maps as Equivalent to R5 `Questionnaire.item.readOnly` |
| Questionnaire.item.repeats | Questionnaire.item.repeats | Equivalent | R4B `Questionnaire.item.repeats` maps as Equivalent to R5 `Questionnaire.item.repeats` |
| Questionnaire.item.required | Questionnaire.item.required | Equivalent | R4B `Questionnaire.item.required` maps as Equivalent to R5 `Questionnaire.item.required` |
| Questionnaire.item.text | Questionnaire.item.text | Equivalent | R4B `Questionnaire.item.text` maps as Equivalent to R5 `Questionnaire.item.text` |
| Questionnaire.item.type | Questionnaire.item.type | SourceIsNarrowerThanTarget | R4B `Questionnaire.item.type` maps as SourceIsNarrowerThanTarget to R5 `Questionnaire.item.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/item-type|4.3.0 and http://hl7.org/fhir/ValueSet/item-type|5.0.0 (SourceIsNarrowerThanTarget) |
| Questionnaire.jurisdiction | Questionnaire.jurisdiction | Equivalent | R4B `Questionnaire.jurisdiction` maps as Equivalent to R5 `Questionnaire.jurisdiction` |
| Questionnaire.language | Questionnaire.language | RelatedTo | R4B `Questionnaire.language` maps as RelatedTo to R5 `Questionnaire.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Questionnaire.lastReviewDate | Questionnaire.lastReviewDate | Equivalent | R4B `Questionnaire.lastReviewDate` maps as Equivalent to R5 `Questionnaire.lastReviewDate` |
| Questionnaire.meta | Questionnaire.meta | Equivalent | R4B `Questionnaire.meta` maps as Equivalent to R5 `Questionnaire.meta` |
| Questionnaire.modifierExtension | Questionnaire.modifierExtension | RelatedTo | R4B `Questionnaire.modifierExtension` maps as RelatedTo to R5 `Questionnaire.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Questionnaire.name | Questionnaire.name | Equivalent | R4B `Questionnaire.name` maps as Equivalent to R5 `Questionnaire.name` |
| Questionnaire.publisher | Questionnaire.publisher | Equivalent | R4B `Questionnaire.publisher` maps as Equivalent to R5 `Questionnaire.publisher` |
| Questionnaire.purpose | Questionnaire.purpose | Equivalent | R4B `Questionnaire.purpose` maps as Equivalent to R5 `Questionnaire.purpose` |
| Questionnaire.status | Questionnaire.status | Equivalent | R4B `Questionnaire.status` maps as Equivalent to R5 `Questionnaire.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|4.3.0 and http://hl7.org/fhir/ValueSet/publication-status|5.0.0 (Equivalent) |
| Questionnaire.subjectType | Questionnaire.subjectType | Equivalent | R4B `Questionnaire.subjectType` maps as Equivalent to R5 `Questionnaire.subjectType` - subjectType has compatible required binding for code type: http://hl7.org/fhir/ValueSet/resource-types|4.3.0 and http://hl7.org/fhir/ValueSet/resource-types|5.0.0 (Equivalent) |
| Questionnaire.text | Questionnaire.text | Equivalent | R4B `Questionnaire.text` maps as Equivalent to R5 `Questionnaire.text` |
| Questionnaire.title | Questionnaire.title | Equivalent | R4B `Questionnaire.title` maps as Equivalent to R5 `Questionnaire.title` |
| Questionnaire.url | Questionnaire.url | Equivalent | R4B `Questionnaire.url` maps as Equivalent to R5 `Questionnaire.url` |
| Questionnaire.useContext | Questionnaire.useContext | Equivalent | R4B `Questionnaire.useContext` maps as Equivalent to R5 `Questionnaire.useContext` |
| Questionnaire.version | Questionnaire.version | Equivalent | R4B `Questionnaire.version` maps as Equivalent to R5 `Questionnaire.version` |

