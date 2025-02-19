Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Annotation |  | Annotation Type: A  text note which also  contains information about who made the statement and when. | 6 | 4 |
| Target | Annotation |  | Base StructureDefinition for Annotation Type: A  text note which also  contains information about who made the statement and when. | 6 | 4 |


Comparison Result: SourceIsBroaderThanTarget


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 5 |
SourceIsBroaderThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Annotation | Annotation | Equivalent | R5 `Annotation` maps as Equivalent to R4 `Annotation` |
| Annotation.author[x] | Annotation.author[x] | SourceIsBroaderThanTarget | R5 `Annotation.author[x]` maps as SourceIsBroaderThanTarget to R4 `Annotation.author[x]` - author[x] has change due to type change: R5 `author[x]` `Reference` maps as SourceIsBroaderThanTarget for R4 `author[x]` |
| Annotation.extension | Annotation.extension | Equivalent | R5 `Annotation.extension` maps as Equivalent to R4 `Annotation.extension` |
| Annotation.id | Annotation.id | Equivalent | R5 `Annotation.id` maps as Equivalent to R4 `Annotation.id` |
| Annotation.text | Annotation.text | Equivalent | R5 `Annotation.text` maps as Equivalent to R4 `Annotation.text` |
| Annotation.time | Annotation.time | Equivalent | R5 `Annotation.time` maps as Equivalent to R4 `Annotation.time` |

