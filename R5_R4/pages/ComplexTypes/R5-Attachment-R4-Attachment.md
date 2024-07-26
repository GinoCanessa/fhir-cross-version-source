Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1
Generated at Thursday, July 25, 2024 3:56:50 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Attachment |  | Attachment Type: For referring to data content defined in other formats. | 16 | 14 |
| Target | Attachment |  | Base StructureDefinition for Attachment Type: For referring to data content defined in other formats. | 11 | 9 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 5 |
Equivalent | 4 |
RelatedTo | 7 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Attachment | Attachment | Equivalent | R5 `Attachment` maps as Equivalent to R4 `Attachment` |
| Attachment.contentType | Attachment.contentType | Equivalent | R5 `Attachment.contentType` maps as Equivalent to R4 `Attachment.contentType` - contentType using http://hl7.org/fhir/ValueSet/mimetypes is exempted and assumed equivalent |
| Attachment.creation | Attachment.creation | Equivalent | R5 `Attachment.creation` maps as Equivalent to R4 `Attachment.creation` |
| Attachment.data | Attachment.data | Equivalent | R5 `Attachment.data` maps as Equivalent to R4 `Attachment.data` |
| Attachment.duration | - | DoesNotExistInTarget | R5 `Attachment.duration` does not appear in the target and has no mapping for `Attachment`. |
| Attachment.extension | Attachment.extension | Equivalent | R5 `Attachment.extension` maps as Equivalent to R4 `Attachment.extension` |
| Attachment.frames | - | DoesNotExistInTarget | R5 `Attachment.frames` does not appear in the target and has no mapping for `Attachment`. |
| Attachment.hash | Attachment.hash | Equivalent | R5 `Attachment.hash` maps as Equivalent to R4 `Attachment.hash` |
| Attachment.height | - | DoesNotExistInTarget | R5 `Attachment.height` does not appear in the target and has no mapping for `Attachment`. |
| Attachment.id | Attachment.id | Equivalent | R5 `Attachment.id` maps as Equivalent to R4 `Attachment.id` |
| Attachment.language | Attachment.language | RelatedTo | R5 `Attachment.language` maps as RelatedTo to R4 `Attachment.language` - language changed the binding strength from Required to Preferred |
| Attachment.pages | - | DoesNotExistInTarget | R5 `Attachment.pages` does not appear in the target and has no mapping for `Attachment`. |
| Attachment.size | Attachment.size | SourceIsBroaderThanTarget | R5 `Attachment.size` maps as SourceIsBroaderThanTarget to R4 `Attachment.size` - size has change due to type change: R5 size integer64 has no equivalent or mapped type in R4 size |
| Attachment.title | Attachment.title | Equivalent | R5 `Attachment.title` maps as Equivalent to R4 `Attachment.title` |
| Attachment.url | Attachment.url | Equivalent | R5 `Attachment.url` maps as Equivalent to R4 `Attachment.url` |
| Attachment.width | - | DoesNotExistInTarget | R5 `Attachment.width` does not appear in the target and has no mapping for `Attachment`. |

