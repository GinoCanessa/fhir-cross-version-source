Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Url | Name | Title | Description |
| --- | --- | --- | --- | --- |
| Source | http://hl7.org/fhir/ValueSet/item-type | QuestionnaireItemType | Questionnaire Item Type | Distinguishes groups from questions and display text and indicates data type for questions. |
| Target | http://hl7.org/fhir/ValueSet/item-type | QuestionnaireItemType | QuestionnaireItemType | Distinguishes groups from questions and display text and indicates data type for questions. |


Comparison Result: SourceIsBroaderThanTarget


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 15 |
SourceIsBroaderThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| attachment | attachment | Equivalent | R5 `attachment` is equivalent to R4B `attachment`. |
| boolean | boolean | Equivalent | R5 `boolean` is equivalent to R4B `boolean`. |
| coding | choice | SourceIsBroaderThanTarget | R5 `coding` is broader than R4B choice and requires mapping choice. `coding` maps to `choice` and `open-choice`. |
| coding | open-choice | SourceIsBroaderThanTarget | R5 `coding` is broader than R4B open-choice and requires mapping choice. `coding` maps to `choice` and `open-choice`. |
| date | date | Equivalent | R5 `date` is equivalent to R4B `date`. |
| dateTime | dateTime | Equivalent | R5 `dateTime` is equivalent to R4B `dateTime`. |
| decimal | decimal | Equivalent | R5 `decimal` is equivalent to R4B `decimal`. |
| display | display | Equivalent | R5 `display` is equivalent to R4B `display`. |
| group | group | Equivalent | R5 `group` is equivalent to R4B `group`. |
| integer | integer | Equivalent | R5 `integer` is equivalent to R4B `integer`. |
| quantity | quantity | Equivalent | R5 `quantity` is equivalent to R4B `quantity`. |
| question | question | Equivalent | R5 `question` is assumed equivalent to R4B `question` (no map, but codes match) |
| reference | reference | Equivalent | R5 `reference` is equivalent to R4B `reference`. |
| string | string | Equivalent | R5 `string` is equivalent to R4B `string`. |
| text | text | Equivalent | R5 `text` is equivalent to R4B `text`. |
| time | time | Equivalent | R5 `time` is equivalent to R4B `time`. |
| url | url | Equivalent | R5 `url` is equivalent to R4B `url`. |

