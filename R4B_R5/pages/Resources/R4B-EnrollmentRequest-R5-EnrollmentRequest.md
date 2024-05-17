Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | EnrollmentRequest |  | This resource provides the insurance enrollment details to the insurer regarding a specified coverage. | 16 | 8 |
| Target | EnrollmentRequest |  | This resource provides the insurance enrollment details to the insurer regarding a specified coverage. | 16 | 8 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 12 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| EnrollmentRequest | EnrollmentRequest | Equivalent | R4B `EnrollmentRequest` maps as Equivalent to R5 `EnrollmentRequest` |
| EnrollmentRequest.candidate | EnrollmentRequest.candidate | Equivalent | R4B `EnrollmentRequest.candidate` maps as Equivalent to R5 `EnrollmentRequest.candidate` |
| EnrollmentRequest.contained | EnrollmentRequest.contained | Equivalent | R4B `EnrollmentRequest.contained` maps as Equivalent to R5 `EnrollmentRequest.contained` |
| EnrollmentRequest.coverage | EnrollmentRequest.coverage | Equivalent | R4B `EnrollmentRequest.coverage` maps as Equivalent to R5 `EnrollmentRequest.coverage` |
| EnrollmentRequest.created | EnrollmentRequest.created | Equivalent | R4B `EnrollmentRequest.created` maps as Equivalent to R5 `EnrollmentRequest.created` |
| EnrollmentRequest.extension | EnrollmentRequest.extension | RelatedTo | R4B `EnrollmentRequest.extension` maps as RelatedTo to R5 `EnrollmentRequest.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| EnrollmentRequest.id | EnrollmentRequest.id | Equivalent | R4B `EnrollmentRequest.id` maps as Equivalent to R5 `EnrollmentRequest.id` |
| EnrollmentRequest.identifier | EnrollmentRequest.identifier | Equivalent | R4B `EnrollmentRequest.identifier` maps as Equivalent to R5 `EnrollmentRequest.identifier` |
| EnrollmentRequest.implicitRules | EnrollmentRequest.implicitRules | Equivalent | R4B `EnrollmentRequest.implicitRules` maps as Equivalent to R5 `EnrollmentRequest.implicitRules` |
| EnrollmentRequest.insurer | EnrollmentRequest.insurer | Equivalent | R4B `EnrollmentRequest.insurer` maps as Equivalent to R5 `EnrollmentRequest.insurer` |
| EnrollmentRequest.language | EnrollmentRequest.language | RelatedTo | R4B `EnrollmentRequest.language` maps as RelatedTo to R5 `EnrollmentRequest.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| EnrollmentRequest.meta | EnrollmentRequest.meta | Equivalent | R4B `EnrollmentRequest.meta` maps as Equivalent to R5 `EnrollmentRequest.meta` |
| EnrollmentRequest.modifierExtension | EnrollmentRequest.modifierExtension | RelatedTo | R4B `EnrollmentRequest.modifierExtension` maps as RelatedTo to R5 `EnrollmentRequest.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| EnrollmentRequest.provider | EnrollmentRequest.provider | Equivalent | R4B `EnrollmentRequest.provider` maps as Equivalent to R5 `EnrollmentRequest.provider` |
| EnrollmentRequest.status | EnrollmentRequest.status | Equivalent | R4B `EnrollmentRequest.status` maps as Equivalent to R5 `EnrollmentRequest.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/fm-status|4.3.0 and http://hl7.org/fhir/ValueSet/fm-status|5.0.0 (Equivalent) |
| EnrollmentRequest.text | EnrollmentRequest.text | Equivalent | R4B `EnrollmentRequest.text` maps as Equivalent to R5 `EnrollmentRequest.text` |

