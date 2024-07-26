Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1
Generated at Thursday, July 25, 2024 3:56:51 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Questionnaire |  | A structured set of questions intended to guide the collection of answers from end-users. Questionnaires provide detailed control over order, presentation, phraseology and grouping to allow coherent, consistent data collection. | 69 | 49 |
| Target | Questionnaire |  | A structured set of questions intended to guide the collection of answers from end-users. Questionnaires provide detailed control over order, presentation, phraseology and grouping to allow coherent, consistent data collection. | 65 | 45 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 4 |
Equivalent | 4 |
RelatedTo | 61 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Questionnaire | Questionnaire | Equivalent | R5 `Questionnaire` maps as Equivalent to R4 `Questionnaire` |
| Questionnaire.approvalDate | Questionnaire.approvalDate | Equivalent | R5 `Questionnaire.approvalDate` maps as Equivalent to R4 `Questionnaire.approvalDate` |
| Questionnaire.code | Questionnaire.code | Equivalent | R5 `Questionnaire.code` maps as Equivalent to R4 `Questionnaire.code` |
| Questionnaire.contact | Questionnaire.contact | Equivalent | R5 `Questionnaire.contact` maps as Equivalent to R4 `Questionnaire.contact` |
| Questionnaire.contained | Questionnaire.contained | Equivalent | R5 `Questionnaire.contained` maps as Equivalent to R4 `Questionnaire.contained` |
| Questionnaire.copyright | Questionnaire.copyright | Equivalent | R5 `Questionnaire.copyright` maps as Equivalent to R4 `Questionnaire.copyright` |
| Questionnaire.copyrightLabel | - | DoesNotExistInTarget | R5 `Questionnaire.copyrightLabel` does not appear in the target and has no mapping for `Questionnaire`. |
| Questionnaire.date | Questionnaire.date | Equivalent | R5 `Questionnaire.date` maps as Equivalent to R4 `Questionnaire.date` |
| Questionnaire.derivedFrom | Questionnaire.derivedFrom | Equivalent | R5 `Questionnaire.derivedFrom` maps as Equivalent to R4 `Questionnaire.derivedFrom` |
| Questionnaire.description | Questionnaire.description | Equivalent | R5 `Questionnaire.description` maps as Equivalent to R4 `Questionnaire.description` |
| Questionnaire.effectivePeriod | Questionnaire.effectivePeriod | Equivalent | R5 `Questionnaire.effectivePeriod` maps as Equivalent to R4 `Questionnaire.effectivePeriod` |
| Questionnaire.experimental | Questionnaire.experimental | Equivalent | R5 `Questionnaire.experimental` maps as Equivalent to R4 `Questionnaire.experimental` |
| Questionnaire.extension | Questionnaire.extension | SourceIsBroaderThanTarget | R5 `Questionnaire.extension` maps as SourceIsBroaderThanTarget to R4 `Questionnaire.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Questionnaire.id | Questionnaire.id | Equivalent | R5 `Questionnaire.id` maps as Equivalent to R4 `Questionnaire.id` |
| Questionnaire.identifier | Questionnaire.identifier | Equivalent | R5 `Questionnaire.identifier` maps as Equivalent to R4 `Questionnaire.identifier` |
| Questionnaire.implicitRules | Questionnaire.implicitRules | Equivalent | R5 `Questionnaire.implicitRules` maps as Equivalent to R4 `Questionnaire.implicitRules` |
| Questionnaire.item | Questionnaire.item | Equivalent | R5 `Questionnaire.item` maps as Equivalent to R4 `Questionnaire.item` |
| Questionnaire.item.answerConstraint | - | DoesNotExistInTarget | R5 `Questionnaire.item.answerConstraint` does not appear in the target and has no mapping for `Questionnaire`. |
| Questionnaire.item.answerOption | Questionnaire.item.answerOption | Equivalent | R5 `Questionnaire.item.answerOption` maps as Equivalent to R4 `Questionnaire.item.answerOption` |
| Questionnaire.item.answerOption.extension | Questionnaire.item.answerOption.extension | SourceIsBroaderThanTarget | R5 `Questionnaire.item.answerOption.extension` maps as SourceIsBroaderThanTarget to R4 `Questionnaire.item.answerOption.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Questionnaire.item.answerOption.id | Questionnaire.item.answerOption.id | Equivalent | R5 `Questionnaire.item.answerOption.id` maps as Equivalent to R4 `Questionnaire.item.answerOption.id` |
| Questionnaire.item.answerOption.initialSelected | Questionnaire.item.answerOption.initialSelected | Equivalent | R5 `Questionnaire.item.answerOption.initialSelected` maps as Equivalent to R4 `Questionnaire.item.answerOption.initialSelected` |
| Questionnaire.item.answerOption.modifierExtension | Questionnaire.item.answerOption.modifierExtension | SourceIsBroaderThanTarget | R5 `Questionnaire.item.answerOption.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Questionnaire.item.answerOption.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Questionnaire.item.answerOption.value[x] | Questionnaire.item.answerOption.value[x] | Equivalent | R5 `Questionnaire.item.answerOption.value[x]` maps as Equivalent to R4 `Questionnaire.item.answerOption.value[x]` |
| Questionnaire.item.answerValueSet | Questionnaire.item.answerValueSet | Equivalent | R5 `Questionnaire.item.answerValueSet` maps as Equivalent to R4 `Questionnaire.item.answerValueSet` |
| Questionnaire.item.code | Questionnaire.item.code | Equivalent | R5 `Questionnaire.item.code` maps as Equivalent to R4 `Questionnaire.item.code` |
| Questionnaire.item.definition | Questionnaire.item.definition | Equivalent | R5 `Questionnaire.item.definition` maps as Equivalent to R4 `Questionnaire.item.definition` |
| Questionnaire.item.disabledDisplay | - | DoesNotExistInTarget | R5 `Questionnaire.item.disabledDisplay` does not appear in the target and has no mapping for `Questionnaire`. |
| Questionnaire.item.enableBehavior | Questionnaire.item.enableBehavior | Equivalent | R5 `Questionnaire.item.enableBehavior` maps as Equivalent to R4 `Questionnaire.item.enableBehavior` - enableBehavior has compatible required binding for code type: http://hl7.org/fhir/ValueSet/questionnaire-enable-behavior|5.0.0 and http://hl7.org/fhir/ValueSet/questionnaire-enable-behavior|4.0.1 (Equivalent) |
| Questionnaire.item.enableWhen | Questionnaire.item.enableWhen | Equivalent | R5 `Questionnaire.item.enableWhen` maps as Equivalent to R4 `Questionnaire.item.enableWhen` |
| Questionnaire.item.enableWhen.answer[x] | Questionnaire.item.enableWhen.answer[x] | Equivalent | R5 `Questionnaire.item.enableWhen.answer[x]` maps as Equivalent to R4 `Questionnaire.item.enableWhen.answer[x]` |
| Questionnaire.item.enableWhen.extension | Questionnaire.item.enableWhen.extension | SourceIsBroaderThanTarget | R5 `Questionnaire.item.enableWhen.extension` maps as SourceIsBroaderThanTarget to R4 `Questionnaire.item.enableWhen.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Questionnaire.item.enableWhen.id | Questionnaire.item.enableWhen.id | Equivalent | R5 `Questionnaire.item.enableWhen.id` maps as Equivalent to R4 `Questionnaire.item.enableWhen.id` |
| Questionnaire.item.enableWhen.modifierExtension | Questionnaire.item.enableWhen.modifierExtension | SourceIsBroaderThanTarget | R5 `Questionnaire.item.enableWhen.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Questionnaire.item.enableWhen.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Questionnaire.item.enableWhen.operator | Questionnaire.item.enableWhen.operator | Equivalent | R5 `Questionnaire.item.enableWhen.operator` maps as Equivalent to R4 `Questionnaire.item.enableWhen.operator` - operator has compatible required binding for code type: http://hl7.org/fhir/ValueSet/questionnaire-enable-operator|5.0.0 and http://hl7.org/fhir/ValueSet/questionnaire-enable-operator|4.0.1 (Equivalent) |
| Questionnaire.item.enableWhen.question | Questionnaire.item.enableWhen.question | Equivalent | R5 `Questionnaire.item.enableWhen.question` maps as Equivalent to R4 `Questionnaire.item.enableWhen.question` |
| Questionnaire.item.extension | Questionnaire.item.extension | SourceIsBroaderThanTarget | R5 `Questionnaire.item.extension` maps as SourceIsBroaderThanTarget to R4 `Questionnaire.item.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Questionnaire.item.id | Questionnaire.item.id | Equivalent | R5 `Questionnaire.item.id` maps as Equivalent to R4 `Questionnaire.item.id` |
| Questionnaire.item.initial | Questionnaire.item.initial | Equivalent | R5 `Questionnaire.item.initial` maps as Equivalent to R4 `Questionnaire.item.initial` |
| Questionnaire.item.initial.extension | Questionnaire.item.initial.extension | SourceIsBroaderThanTarget | R5 `Questionnaire.item.initial.extension` maps as SourceIsBroaderThanTarget to R4 `Questionnaire.item.initial.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Questionnaire.item.initial.id | Questionnaire.item.initial.id | Equivalent | R5 `Questionnaire.item.initial.id` maps as Equivalent to R4 `Questionnaire.item.initial.id` |
| Questionnaire.item.initial.modifierExtension | Questionnaire.item.initial.modifierExtension | SourceIsBroaderThanTarget | R5 `Questionnaire.item.initial.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Questionnaire.item.initial.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Questionnaire.item.initial.value[x] | Questionnaire.item.initial.value[x] | RelatedTo | R5 `Questionnaire.item.initial.value[x]` maps as RelatedTo to R4 `Questionnaire.item.initial.value[x]` - value[x] has change due to type change: R5 `value[x]` `Attachment` maps as RelatedTo for R4 `value[x]` |
| Questionnaire.item.item | Questionnaire.item.item | Equivalent | R5 `Questionnaire.item.item` maps as Equivalent to R4 `Questionnaire.item.item` |
| Questionnaire.item.linkId | Questionnaire.item.linkId | Equivalent | R5 `Questionnaire.item.linkId` maps as Equivalent to R4 `Questionnaire.item.linkId` |
| Questionnaire.item.maxLength | Questionnaire.item.maxLength | Equivalent | R5 `Questionnaire.item.maxLength` maps as Equivalent to R4 `Questionnaire.item.maxLength` |
| Questionnaire.item.modifierExtension | Questionnaire.item.modifierExtension | SourceIsBroaderThanTarget | R5 `Questionnaire.item.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Questionnaire.item.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Questionnaire.item.prefix | Questionnaire.item.prefix | Equivalent | R5 `Questionnaire.item.prefix` maps as Equivalent to R4 `Questionnaire.item.prefix` |
| Questionnaire.item.readOnly | Questionnaire.item.readOnly | Equivalent | R5 `Questionnaire.item.readOnly` maps as Equivalent to R4 `Questionnaire.item.readOnly` |
| Questionnaire.item.repeats | Questionnaire.item.repeats | Equivalent | R5 `Questionnaire.item.repeats` maps as Equivalent to R4 `Questionnaire.item.repeats` |
| Questionnaire.item.required | Questionnaire.item.required | Equivalent | R5 `Questionnaire.item.required` maps as Equivalent to R4 `Questionnaire.item.required` |
| Questionnaire.item.text | Questionnaire.item.text | Equivalent | R5 `Questionnaire.item.text` maps as Equivalent to R4 `Questionnaire.item.text` |
| Questionnaire.item.type | Questionnaire.item.type | SourceIsBroaderThanTarget | R5 `Questionnaire.item.type` maps as SourceIsBroaderThanTarget to R4 `Questionnaire.item.type` - type has INCOMPATIBLE required binding for code type: http://hl7.org/fhir/ValueSet/item-type|5.0.0 and http://hl7.org/fhir/ValueSet/item-type|4.0.1 |
| Questionnaire.jurisdiction | Questionnaire.jurisdiction | Equivalent | R5 `Questionnaire.jurisdiction` maps as Equivalent to R4 `Questionnaire.jurisdiction` |
| Questionnaire.language | Questionnaire.language | RelatedTo | R5 `Questionnaire.language` maps as RelatedTo to R4 `Questionnaire.language` - language changed the binding strength from Required to Preferred |
| Questionnaire.lastReviewDate | Questionnaire.lastReviewDate | Equivalent | R5 `Questionnaire.lastReviewDate` maps as Equivalent to R4 `Questionnaire.lastReviewDate` |
| Questionnaire.meta | Questionnaire.meta | Equivalent | R5 `Questionnaire.meta` maps as Equivalent to R4 `Questionnaire.meta` |
| Questionnaire.modifierExtension | Questionnaire.modifierExtension | SourceIsBroaderThanTarget | R5 `Questionnaire.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Questionnaire.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Questionnaire.name | Questionnaire.name | Equivalent | R5 `Questionnaire.name` maps as Equivalent to R4 `Questionnaire.name` |
| Questionnaire.publisher | Questionnaire.publisher | Equivalent | R5 `Questionnaire.publisher` maps as Equivalent to R4 `Questionnaire.publisher` |
| Questionnaire.purpose | Questionnaire.purpose | Equivalent | R5 `Questionnaire.purpose` maps as Equivalent to R4 `Questionnaire.purpose` |
| Questionnaire.status | Questionnaire.status | Equivalent | R5 `Questionnaire.status` maps as Equivalent to R4 `Questionnaire.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|5.0.0 and http://hl7.org/fhir/ValueSet/publication-status|4.0.1 (Equivalent) |
| Questionnaire.subjectType | Questionnaire.subjectType | Equivalent | R5 `Questionnaire.subjectType` maps as Equivalent to R4 `Questionnaire.subjectType` - subjectType has compatible required binding for code type: http://hl7.org/fhir/ValueSet/resource-types|5.0.0 and http://hl7.org/fhir/ValueSet/resource-types|4.0.1 (Equivalent) |
| Questionnaire.text | Questionnaire.text | Equivalent | R5 `Questionnaire.text` maps as Equivalent to R4 `Questionnaire.text` |
| Questionnaire.title | Questionnaire.title | Equivalent | R5 `Questionnaire.title` maps as Equivalent to R4 `Questionnaire.title` |
| Questionnaire.url | Questionnaire.url | Equivalent | R5 `Questionnaire.url` maps as Equivalent to R4 `Questionnaire.url` |
| Questionnaire.useContext | Questionnaire.useContext | Equivalent | R5 `Questionnaire.useContext` maps as Equivalent to R4 `Questionnaire.useContext` |
| Questionnaire.version | Questionnaire.version | Equivalent | R5 `Questionnaire.version` maps as Equivalent to R4 `Questionnaire.version` |
| Questionnaire.versionAlgorithm[x] | - | DoesNotExistInTarget | R5 `Questionnaire.versionAlgorithm[x]` does not appear in the target and has no mapping for `Questionnaire`. |

