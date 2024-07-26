Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1
Generated at Thursday, July 25, 2024 3:56:51 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | EnrollmentResponse |  | This resource provides enrollment and plan details from the processing of an EnrollmentRequest resource. | 17 | 9 |
| Target | EnrollmentResponse |  | This resource provides enrollment and plan details from the processing of an EnrollmentRequest resource. | 17 | 9 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 13 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| EnrollmentResponse | EnrollmentResponse | Equivalent | R5 `EnrollmentResponse` maps as Equivalent to R4 `EnrollmentResponse` |
| EnrollmentResponse.contained | EnrollmentResponse.contained | Equivalent | R5 `EnrollmentResponse.contained` maps as Equivalent to R4 `EnrollmentResponse.contained` |
| EnrollmentResponse.created | EnrollmentResponse.created | Equivalent | R5 `EnrollmentResponse.created` maps as Equivalent to R4 `EnrollmentResponse.created` |
| EnrollmentResponse.disposition | EnrollmentResponse.disposition | Equivalent | R5 `EnrollmentResponse.disposition` maps as Equivalent to R4 `EnrollmentResponse.disposition` |
| EnrollmentResponse.extension | EnrollmentResponse.extension | SourceIsBroaderThanTarget | R5 `EnrollmentResponse.extension` maps as SourceIsBroaderThanTarget to R4 `EnrollmentResponse.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| EnrollmentResponse.id | EnrollmentResponse.id | Equivalent | R5 `EnrollmentResponse.id` maps as Equivalent to R4 `EnrollmentResponse.id` |
| EnrollmentResponse.identifier | EnrollmentResponse.identifier | Equivalent | R5 `EnrollmentResponse.identifier` maps as Equivalent to R4 `EnrollmentResponse.identifier` |
| EnrollmentResponse.implicitRules | EnrollmentResponse.implicitRules | Equivalent | R5 `EnrollmentResponse.implicitRules` maps as Equivalent to R4 `EnrollmentResponse.implicitRules` |
| EnrollmentResponse.language | EnrollmentResponse.language | RelatedTo | R5 `EnrollmentResponse.language` maps as RelatedTo to R4 `EnrollmentResponse.language` - language changed the binding strength from Required to Preferred |
| EnrollmentResponse.meta | EnrollmentResponse.meta | Equivalent | R5 `EnrollmentResponse.meta` maps as Equivalent to R4 `EnrollmentResponse.meta` |
| EnrollmentResponse.modifierExtension | EnrollmentResponse.modifierExtension | SourceIsBroaderThanTarget | R5 `EnrollmentResponse.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `EnrollmentResponse.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| EnrollmentResponse.organization | EnrollmentResponse.organization | Equivalent | R5 `EnrollmentResponse.organization` maps as Equivalent to R4 `EnrollmentResponse.organization` |
| EnrollmentResponse.outcome | EnrollmentResponse.outcome | Equivalent | R5 `EnrollmentResponse.outcome` maps as Equivalent to R4 `EnrollmentResponse.outcome` - outcome has compatible required binding for code type: http://hl7.org/fhir/ValueSet/enrollment-outcome|5.0.0 and http://hl7.org/fhir/ValueSet/remittance-outcome|4.0.1 (Equivalent) |
| EnrollmentResponse.request | EnrollmentResponse.request | Equivalent | R5 `EnrollmentResponse.request` maps as Equivalent to R4 `EnrollmentResponse.request` |
| EnrollmentResponse.requestProvider | EnrollmentResponse.requestProvider | Equivalent | R5 `EnrollmentResponse.requestProvider` maps as Equivalent to R4 `EnrollmentResponse.requestProvider` |
| EnrollmentResponse.status | EnrollmentResponse.status | Equivalent | R5 `EnrollmentResponse.status` maps as Equivalent to R4 `EnrollmentResponse.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/fm-status|5.0.0 and http://hl7.org/fhir/ValueSet/fm-status|4.0.1 (Equivalent) |
| EnrollmentResponse.text | EnrollmentResponse.text | Equivalent | R5 `EnrollmentResponse.text` maps as Equivalent to R4 `EnrollmentResponse.text` |

