Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:03 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Annotation |  | Base StructureDefinition for Annotation Type: A  text note which also  contains information about who made the statement and when. | 6 | 4 |
| Target | Annotation |  | Annotation Type: A  text note which also  contains information about who made the statement and when. | 6 | 4 |


Comparison Result: SourceIsNarrowerThanTarget


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 3 |
SourceIsNarrowerThanTarget | 3 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Annotation | Annotation | Equivalent | R4B `Annotation` maps as Equivalent to R5 `Annotation` |
| Annotation.author[x] | Annotation.author[x] | SourceIsNarrowerThanTarget | R4B `Annotation.author[x]` maps as SourceIsNarrowerThanTarget to R5 `Annotation.author[x]` - author[x] has change due to type change: R4B `author[x]` `Reference` maps as SourceIsNarrowerThanTarget for R5 `author[x]` |
| Annotation.extension | Annotation.extension | Equivalent | R4B `Annotation.extension` maps as Equivalent to R5 `Annotation.extension` |
| Annotation.id | Annotation.id | Equivalent | R4B `Annotation.id` maps as Equivalent to R5 `Annotation.id` |
| Annotation.text | Annotation.text | Equivalent | R4B `Annotation.text` maps as Equivalent to R5 `Annotation.text` |
| Annotation.time | Annotation.time | Equivalent | R4B `Annotation.time` maps as Equivalent to R5 `Annotation.time` |

