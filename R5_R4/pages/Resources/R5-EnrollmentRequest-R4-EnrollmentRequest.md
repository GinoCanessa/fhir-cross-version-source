Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

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
| EnrollmentRequest | EnrollmentRequest | Equivalent | R5 `EnrollmentRequest` maps as Equivalent to R4 `EnrollmentRequest` |
| EnrollmentRequest.candidate | EnrollmentRequest.candidate | Equivalent | R5 `EnrollmentRequest.candidate` maps as Equivalent to R4 `EnrollmentRequest.candidate` |
| EnrollmentRequest.contained | EnrollmentRequest.contained | Equivalent | R5 `EnrollmentRequest.contained` maps as Equivalent to R4 `EnrollmentRequest.contained` |
| EnrollmentRequest.coverage | EnrollmentRequest.coverage | Equivalent | R5 `EnrollmentRequest.coverage` maps as Equivalent to R4 `EnrollmentRequest.coverage` |
| EnrollmentRequest.created | EnrollmentRequest.created | Equivalent | R5 `EnrollmentRequest.created` maps as Equivalent to R4 `EnrollmentRequest.created` |
| EnrollmentRequest.extension | EnrollmentRequest.extension | SourceIsBroaderThanTarget | R5 `EnrollmentRequest.extension` maps as SourceIsBroaderThanTarget to R4 `EnrollmentRequest.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| EnrollmentRequest.id | EnrollmentRequest.id | Equivalent | R5 `EnrollmentRequest.id` maps as Equivalent to R4 `EnrollmentRequest.id` |
| EnrollmentRequest.identifier | EnrollmentRequest.identifier | Equivalent | R5 `EnrollmentRequest.identifier` maps as Equivalent to R4 `EnrollmentRequest.identifier` |
| EnrollmentRequest.implicitRules | EnrollmentRequest.implicitRules | Equivalent | R5 `EnrollmentRequest.implicitRules` maps as Equivalent to R4 `EnrollmentRequest.implicitRules` |
| EnrollmentRequest.insurer | EnrollmentRequest.insurer | Equivalent | R5 `EnrollmentRequest.insurer` maps as Equivalent to R4 `EnrollmentRequest.insurer` |
| EnrollmentRequest.language | EnrollmentRequest.language | RelatedTo | R5 `EnrollmentRequest.language` maps as RelatedTo to R4 `EnrollmentRequest.language` - language changed the binding strength from Required to Preferred |
| EnrollmentRequest.meta | EnrollmentRequest.meta | Equivalent | R5 `EnrollmentRequest.meta` maps as Equivalent to R4 `EnrollmentRequest.meta` |
| EnrollmentRequest.modifierExtension | EnrollmentRequest.modifierExtension | SourceIsBroaderThanTarget | R5 `EnrollmentRequest.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `EnrollmentRequest.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| EnrollmentRequest.provider | EnrollmentRequest.provider | Equivalent | R5 `EnrollmentRequest.provider` maps as Equivalent to R4 `EnrollmentRequest.provider` |
| EnrollmentRequest.status | EnrollmentRequest.status | Equivalent | R5 `EnrollmentRequest.status` maps as Equivalent to R4 `EnrollmentRequest.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/fm-status|5.0.0 and http://hl7.org/fhir/ValueSet/fm-status|4.0.1 (Equivalent) |
| EnrollmentRequest.text | EnrollmentRequest.text | Equivalent | R5 `EnrollmentRequest.text` maps as Equivalent to R4 `EnrollmentRequest.text` |

