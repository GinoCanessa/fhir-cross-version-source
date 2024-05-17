Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:03 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Attachment |  | Base StructureDefinition for Attachment Type: For referring to data content defined in other formats. | 11 | 9 |
| Target | Attachment |  | Attachment Type: For referring to data content defined in other formats. | 16 | 14 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 7 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Attachment | Attachment | Equivalent | R4B `Attachment` maps as Equivalent to R5 `Attachment` |
| Attachment.contentType | Attachment.contentType | Equivalent | R4B `Attachment.contentType` maps as Equivalent to R5 `Attachment.contentType` - contentType using http://hl7.org/fhir/ValueSet/mimetypes is exempted and assumed equivalent |
| Attachment.creation | Attachment.creation | Equivalent | R4B `Attachment.creation` maps as Equivalent to R5 `Attachment.creation` |
| Attachment.data | Attachment.data | Equivalent | R4B `Attachment.data` maps as Equivalent to R5 `Attachment.data` |
| Attachment.extension | Attachment.extension | Equivalent | R4B `Attachment.extension` maps as Equivalent to R5 `Attachment.extension` |
| Attachment.hash | Attachment.hash | Equivalent | R4B `Attachment.hash` maps as Equivalent to R5 `Attachment.hash` |
| Attachment.id | Attachment.id | Equivalent | R4B `Attachment.id` maps as Equivalent to R5 `Attachment.id` |
| Attachment.language | Attachment.language | RelatedTo | R4B `Attachment.language` maps as RelatedTo to R5 `Attachment.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Attachment.size | Attachment.size | SourceIsNarrowerThanTarget | R4B `Attachment.size` maps as SourceIsNarrowerThanTarget to R5 `Attachment.size` - size has change due to type change: R4B `size` `unsignedInt` maps as SourceIsNarrowerThanTarget for R5 `size` |
| Attachment.title | Attachment.title | Equivalent | R4B `Attachment.title` maps as Equivalent to R5 `Attachment.title` |
| Attachment.url | Attachment.url | Equivalent | R4B `Attachment.url` maps as Equivalent to R5 `Attachment.url` |

