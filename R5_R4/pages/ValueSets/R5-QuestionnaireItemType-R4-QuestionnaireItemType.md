Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1
Generated at Thursday, July 25, 2024 3:56:50 PM

| Side | Url | Name | Title | Description |
| --- | --- | --- | --- | --- |
| Source | http://hl7.org/fhir/ValueSet/item-type | QuestionnaireItemType | Questionnaire Item Type | Distinguishes groups from questions and display text and indicates data type for questions. |
| Target | http://hl7.org/fhir/ValueSet/item-type | QuestionnaireItemType | QuestionnaireItemType | Distinguishes groups from questions and display text and indicates data type for questions. |


Comparison Result: SourceIsBroaderThanTarget


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 1 |
Equivalent | 14 |
SourceIsBroaderThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| attachment | attachment | Equivalent | R5 `attachment` is equivalent to R4 `attachment`. |
| boolean | boolean | Equivalent | R5 `boolean` is equivalent to R4 `boolean`. |
| coding | open-choice | SourceIsBroaderThanTarget | definition mismatch |
| coding | choice | SourceIsBroaderThanTarget | definition mismatch |
| date | date | Equivalent | R5 `date` is equivalent to R4 `date`. |
| dateTime | dateTime | Equivalent | R5 `dateTime` is equivalent to R4 `dateTime`. |
| decimal | decimal | Equivalent | R5 `decimal` is equivalent to R4 `decimal`. |
| display | display | Equivalent | R5 `display` is equivalent to R4 `display`. |
| group | group | Equivalent | R5 `group` is equivalent to R4 `group`. |
| integer | integer | Equivalent | R5 `integer` is equivalent to R4 `integer`. |
| quantity | quantity | Equivalent | R5 `quantity` is equivalent to R4 `quantity`. |
| question | - | DoesNotExistInTarget | R5 `question` does not appear in the target and has no mapping for http://hl7.org/fhir/ValueSet/item-type. |
| reference | reference | Equivalent | R5 `reference` is equivalent to R4 `reference`. |
| string | string | Equivalent | R5 `string` is equivalent to R4 `string`. |
| text | text | Equivalent | R5 `text` is equivalent to R4 `text`. |
| time | time | Equivalent | R5 `time` is equivalent to R4 `time`. |
| url | url | Equivalent | R5 `url` is equivalent to R4 `url`. |

