Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Annotation |  | Annotation Type: A  text note which also  contains information about who made the statement and when. | 6 | 4 |
| Target | Annotation |  | Base StructureDefinition for Annotation Type: A  text note which also  contains information about who made the statement and when. | 6 | 4 |


Comparison Result: SourceIsBroaderThanTarget


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 3 |
SourceIsBroaderThanTarget | 3 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Annotation | Annotation | Equivalent | R5 `Annotation` maps as Equivalent to R4B `Annotation` |
| Annotation.author[x] | Annotation.author[x] | SourceIsBroaderThanTarget | R5 `Annotation.author[x]` maps as SourceIsBroaderThanTarget to R4B `Annotation.author[x]` - author[x] has change due to type change: R5 `author[x]` `Reference` maps as SourceIsBroaderThanTarget for R4B `author[x]` |
| Annotation.extension | Annotation.extension | Equivalent | R5 `Annotation.extension` maps as Equivalent to R4B `Annotation.extension` |
| Annotation.id | Annotation.id | Equivalent | R5 `Annotation.id` maps as Equivalent to R4B `Annotation.id` |
| Annotation.text | Annotation.text | Equivalent | R5 `Annotation.text` maps as Equivalent to R4B `Annotation.text` |
| Annotation.time | Annotation.time | Equivalent | R5 `Annotation.time` maps as Equivalent to R4B `Annotation.time` |

