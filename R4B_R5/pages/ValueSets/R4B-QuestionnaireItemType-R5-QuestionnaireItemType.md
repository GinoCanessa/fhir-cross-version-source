Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:03 AM

| Side | Url | Name | Title | Description |
| --- | --- | --- | --- | --- |
| Source | http://hl7.org/fhir/ValueSet/item-type | QuestionnaireItemType | QuestionnaireItemType | Distinguishes groups from questions and display text and indicates data type for questions. |
| Target | http://hl7.org/fhir/ValueSet/item-type | QuestionnaireItemType | Questionnaire Item Type | Distinguishes groups from questions and display text and indicates data type for questions. |


Comparison Result: SourceIsNarrowerThanTarget


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 15 |
SourceIsNarrowerThanTarget | 2 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| attachment | attachment | Equivalent | R4B `attachment` is equivalent to R5 `attachment`. |
| boolean | boolean | Equivalent | R4B `boolean` is equivalent to R5 `boolean`. |
| choice | coding | SourceIsNarrowerThanTarget | R4B `choice` is narrower than R5 `coding` and is compatible. `coding` is mapped from `choice` and `open-choice`. |
| date | date | Equivalent | R4B `date` is equivalent to R5 `date`. |
| dateTime | dateTime | Equivalent | R4B `dateTime` is equivalent to R5 `dateTime`. |
| decimal | decimal | Equivalent | R4B `decimal` is equivalent to R5 `decimal`. |
| display | display | Equivalent | R4B `display` is equivalent to R5 `display`. |
| group | group | Equivalent | R4B `group` is equivalent to R5 `group`. |
| integer | integer | Equivalent | R4B `integer` is equivalent to R5 `integer`. |
| open-choice | coding | SourceIsNarrowerThanTarget | R4B `open-choice` is narrower than R5 `coding` and is compatible. `coding` is mapped from `choice` and `open-choice`. |
| quantity | quantity | Equivalent | R4B `quantity` is equivalent to R5 `quantity`. |
| question | question | Equivalent | R4B `question` is assumed equivalent to R5 `question` (no map, but codes match) |
| reference | reference | Equivalent | R4B `reference` is equivalent to R5 `reference`. |
| string | string | Equivalent | R4B `string` is equivalent to R5 `string`. |
| text | text | Equivalent | R4B `text` is equivalent to R5 `text`. |
| time | time | Equivalent | R4B `time` is equivalent to R5 `time`. |
| url | url | Equivalent | R4B `url` is equivalent to R5 `url`. |

