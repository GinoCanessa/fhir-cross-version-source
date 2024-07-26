Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1
Generated at Thursday, July 25, 2024 3:56:50 PM

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
| Binary | Binary | Equivalent | R5 `Binary` maps as Equivalent to R4 `Binary` |
| Binary.contentType | Binary.contentType | Equivalent | R5 `Binary.contentType` maps as Equivalent to R4 `Binary.contentType` - contentType using http://hl7.org/fhir/ValueSet/mimetypes is exempted and assumed equivalent |
| Binary.data | Binary.data | Equivalent | R5 `Binary.data` maps as Equivalent to R4 `Binary.data` |
| Binary.id | Binary.id | Equivalent | R5 `Binary.id` maps as Equivalent to R4 `Binary.id` |
| Binary.implicitRules | Binary.implicitRules | Equivalent | R5 `Binary.implicitRules` maps as Equivalent to R4 `Binary.implicitRules` |
| Binary.language | Binary.language | RelatedTo | R5 `Binary.language` maps as RelatedTo to R4 `Binary.language` - language changed the binding strength from Required to Preferred |
| Binary.meta | Binary.meta | Equivalent | R5 `Binary.meta` maps as Equivalent to R4 `Binary.meta` |
| Binary.securityContext | Binary.securityContext | Equivalent | R5 `Binary.securityContext` maps as Equivalent to R4 `Binary.securityContext` |

