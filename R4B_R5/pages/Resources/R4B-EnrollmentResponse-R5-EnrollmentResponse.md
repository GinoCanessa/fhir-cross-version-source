Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

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
| EnrollmentResponse | EnrollmentResponse | Equivalent | R4B `EnrollmentResponse` maps as Equivalent to R5 `EnrollmentResponse` |
| EnrollmentResponse.contained | EnrollmentResponse.contained | Equivalent | R4B `EnrollmentResponse.contained` maps as Equivalent to R5 `EnrollmentResponse.contained` |
| EnrollmentResponse.created | EnrollmentResponse.created | Equivalent | R4B `EnrollmentResponse.created` maps as Equivalent to R5 `EnrollmentResponse.created` |
| EnrollmentResponse.disposition | EnrollmentResponse.disposition | Equivalent | R4B `EnrollmentResponse.disposition` maps as Equivalent to R5 `EnrollmentResponse.disposition` |
| EnrollmentResponse.extension | EnrollmentResponse.extension | RelatedTo | R4B `EnrollmentResponse.extension` maps as RelatedTo to R5 `EnrollmentResponse.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| EnrollmentResponse.id | EnrollmentResponse.id | Equivalent | R4B `EnrollmentResponse.id` maps as Equivalent to R5 `EnrollmentResponse.id` |
| EnrollmentResponse.identifier | EnrollmentResponse.identifier | Equivalent | R4B `EnrollmentResponse.identifier` maps as Equivalent to R5 `EnrollmentResponse.identifier` |
| EnrollmentResponse.implicitRules | EnrollmentResponse.implicitRules | Equivalent | R4B `EnrollmentResponse.implicitRules` maps as Equivalent to R5 `EnrollmentResponse.implicitRules` |
| EnrollmentResponse.language | EnrollmentResponse.language | RelatedTo | R4B `EnrollmentResponse.language` maps as RelatedTo to R5 `EnrollmentResponse.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| EnrollmentResponse.meta | EnrollmentResponse.meta | Equivalent | R4B `EnrollmentResponse.meta` maps as Equivalent to R5 `EnrollmentResponse.meta` |
| EnrollmentResponse.modifierExtension | EnrollmentResponse.modifierExtension | RelatedTo | R4B `EnrollmentResponse.modifierExtension` maps as RelatedTo to R5 `EnrollmentResponse.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| EnrollmentResponse.organization | EnrollmentResponse.organization | Equivalent | R4B `EnrollmentResponse.organization` maps as Equivalent to R5 `EnrollmentResponse.organization` |
| EnrollmentResponse.outcome | EnrollmentResponse.outcome | Equivalent | R4B `EnrollmentResponse.outcome` maps as Equivalent to R5 `EnrollmentResponse.outcome` - outcome has compatible required binding for code type: http://hl7.org/fhir/ValueSet/remittance-outcome|4.3.0 and http://hl7.org/fhir/ValueSet/enrollment-outcome|5.0.0 (Equivalent) |
| EnrollmentResponse.request | EnrollmentResponse.request | Equivalent | R4B `EnrollmentResponse.request` maps as Equivalent to R5 `EnrollmentResponse.request` |
| EnrollmentResponse.requestProvider | EnrollmentResponse.requestProvider | Equivalent | R4B `EnrollmentResponse.requestProvider` maps as Equivalent to R5 `EnrollmentResponse.requestProvider` |
| EnrollmentResponse.status | EnrollmentResponse.status | Equivalent | R4B `EnrollmentResponse.status` maps as Equivalent to R5 `EnrollmentResponse.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/fm-status|4.3.0 and http://hl7.org/fhir/ValueSet/fm-status|5.0.0 (Equivalent) |
| EnrollmentResponse.text | EnrollmentResponse.text | Equivalent | R4B `EnrollmentResponse.text` maps as Equivalent to R5 `EnrollmentResponse.text` |

