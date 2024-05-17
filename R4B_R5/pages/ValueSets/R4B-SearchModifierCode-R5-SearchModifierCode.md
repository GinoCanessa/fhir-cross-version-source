Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:03 AM

| Side | Url | Name | Title | Description |
| --- | --- | --- | --- | --- |
| Source | http://hl7.org/fhir/ValueSet/search-modifier-code | SearchModifierCode | SearchModifierCode | A supported modifier for a search parameter. |
| Target | http://hl7.org/fhir/ValueSet/search-modifier-code | SearchModifierCode | Search Modifier Code | A supported modifier for a search parameter. |


Comparison Result: SourceIsBroaderThanTarget


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 11 |
SourceIsBroaderThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| above | above | Equivalent | R4B `above` is equivalent to R5 `above`. |
| below | below | Equivalent | R4B `below` is equivalent to R5 `below`. |
| contains | contains | Equivalent | R4B `contains` is equivalent to R5 `contains`. |
| exact | exact | Equivalent | R4B `exact` is equivalent to R5 `exact`. |
| identifier | identifier | Equivalent | R4B `identifier` is equivalent to R5 `identifier`. |
| in | in | Equivalent | R4B `in` is equivalent to R5 `in`. |
| missing | missing | Equivalent | R4B `missing` is equivalent to R5 `missing`. |
| not | not | Equivalent | R4B `not` is equivalent to R5 `not`. |
| not-in | not-in | Equivalent | R4B `not-in` is equivalent to R5 `not-in`. |
| ofType | of-type | Equivalent | R4B `ofType` is equivalent to R5 `of-type`. |
| text | text | Equivalent | R4B `text` is equivalent to R5 `text`. |
| text | code-text | SourceIsBroaderThanTarget | R4B `text` is broader than R5 code-text and requires mapping choice. `text` maps to `text` and `code-text` and `text-advanced`. |
| text | text-advanced | SourceIsBroaderThanTarget | R4B `text` is broader than R5 text-advanced and requires mapping choice. `text` maps to `text` and `code-text` and `text-advanced`. |
| type | type | Equivalent | R4B `type` is equivalent to R5 `type`. |

