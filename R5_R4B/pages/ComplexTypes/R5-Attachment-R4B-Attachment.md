Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

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
| Attachment | Attachment | Equivalent | R5 `Attachment` maps as Equivalent to R4B `Attachment` |
| Attachment.contentType | Attachment.contentType | Equivalent | R5 `Attachment.contentType` maps as Equivalent to R4B `Attachment.contentType` - contentType using http://hl7.org/fhir/ValueSet/mimetypes is exempted and assumed equivalent |
| Attachment.creation | Attachment.creation | Equivalent | R5 `Attachment.creation` maps as Equivalent to R4B `Attachment.creation` |
| Attachment.data | Attachment.data | Equivalent | R5 `Attachment.data` maps as Equivalent to R4B `Attachment.data` |
| Attachment.duration | - | DoesNotExistInTarget | R5 `Attachment.duration` does not appear in the target and has no mapping for `Attachment`. |
| Attachment.extension | Attachment.extension | Equivalent | R5 `Attachment.extension` maps as Equivalent to R4B `Attachment.extension` |
| Attachment.frames | - | DoesNotExistInTarget | R5 `Attachment.frames` does not appear in the target and has no mapping for `Attachment`. |
| Attachment.hash | Attachment.hash | Equivalent | R5 `Attachment.hash` maps as Equivalent to R4B `Attachment.hash` |
| Attachment.height | - | DoesNotExistInTarget | R5 `Attachment.height` does not appear in the target and has no mapping for `Attachment`. |
| Attachment.id | Attachment.id | Equivalent | R5 `Attachment.id` maps as Equivalent to R4B `Attachment.id` |
| Attachment.language | Attachment.language | RelatedTo | R5 `Attachment.language` maps as RelatedTo to R4B `Attachment.language` - language changed the binding strength from Required to Preferred |
| Attachment.pages | - | DoesNotExistInTarget | R5 `Attachment.pages` does not appear in the target and has no mapping for `Attachment`. |
| Attachment.size | Attachment.size | SourceIsBroaderThanTarget | R5 `Attachment.size` maps as SourceIsBroaderThanTarget to R4B `Attachment.size` - size has change due to type change: R5 size integer64 has no equivalent or mapped type in R4B size |
| Attachment.title | Attachment.title | Equivalent | R5 `Attachment.title` maps as Equivalent to R4B `Attachment.title` |
| Attachment.url | Attachment.url | Equivalent | R5 `Attachment.url` maps as Equivalent to R4B `Attachment.url` |
| Attachment.width | - | DoesNotExistInTarget | R5 `Attachment.width` does not appear in the target and has no mapping for `Attachment`. |

