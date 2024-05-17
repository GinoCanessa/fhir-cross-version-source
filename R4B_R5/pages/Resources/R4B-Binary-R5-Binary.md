Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Binary |  | A resource that represents the data of a single raw artifact as digital content accessible in its native format.  A Binary resource can contain any content, whether text, image, pdf, zip archive, etc. | 8 | 4 |
| Target | Binary |  | A resource that represents the data of a single raw artifact as digital content accessible in its native format.  A Binary resource can contain any content, whether text, image, pdf, zip archive, etc. | 8 | 4 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 4 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Binary | Binary | Equivalent | R4B `Binary` maps as Equivalent to R5 `Binary` |
| Binary.contentType | Binary.contentType | Equivalent | R4B `Binary.contentType` maps as Equivalent to R5 `Binary.contentType` - contentType using http://hl7.org/fhir/ValueSet/mimetypes is exempted and assumed equivalent |
| Binary.data | Binary.data | Equivalent | R4B `Binary.data` maps as Equivalent to R5 `Binary.data` |
| Binary.id | Binary.id | Equivalent | R4B `Binary.id` maps as Equivalent to R5 `Binary.id` |
| Binary.implicitRules | Binary.implicitRules | Equivalent | R4B `Binary.implicitRules` maps as Equivalent to R5 `Binary.implicitRules` |
| Binary.language | Binary.language | RelatedTo | R4B `Binary.language` maps as RelatedTo to R5 `Binary.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Binary.meta | Binary.meta | Equivalent | R4B `Binary.meta` maps as Equivalent to R5 `Binary.meta` |
| Binary.securityContext | Binary.securityContext | Equivalent | R4B `Binary.securityContext` maps as Equivalent to R5 `Binary.securityContext` |

