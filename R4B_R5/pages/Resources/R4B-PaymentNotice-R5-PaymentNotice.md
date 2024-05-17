Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | PaymentNotice |  | This resource provides the status of the payment for goods and services rendered, and the request and response resource references. | 21 | 13 |
| Target | PaymentNotice |  | This resource provides the status of the payment for goods and services rendered, and the request and response resource references. | 21 | 13 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 1 |
Equivalent | 4 |
RelatedTo | 16 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| PaymentNotice | PaymentNotice | Equivalent | R4B `PaymentNotice` maps as Equivalent to R5 `PaymentNotice` |
| PaymentNotice.amount | PaymentNotice.amount | RelatedTo | R4B `PaymentNotice.amount` maps as RelatedTo to R5 `PaymentNotice.amount` - amount has change due to type change: R4B `amount` `Money` maps as RelatedTo for R5 `amount` |
| PaymentNotice.contained | PaymentNotice.contained | Equivalent | R4B `PaymentNotice.contained` maps as Equivalent to R5 `PaymentNotice.contained` |
| PaymentNotice.created | PaymentNotice.created | Equivalent | R4B `PaymentNotice.created` maps as Equivalent to R5 `PaymentNotice.created` |
| PaymentNotice.extension | PaymentNotice.extension | RelatedTo | R4B `PaymentNotice.extension` maps as RelatedTo to R5 `PaymentNotice.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| PaymentNotice.id | PaymentNotice.id | Equivalent | R4B `PaymentNotice.id` maps as Equivalent to R5 `PaymentNotice.id` |
| PaymentNotice.identifier | PaymentNotice.identifier | Equivalent | R4B `PaymentNotice.identifier` maps as Equivalent to R5 `PaymentNotice.identifier` |
| PaymentNotice.implicitRules | PaymentNotice.implicitRules | Equivalent | R4B `PaymentNotice.implicitRules` maps as Equivalent to R5 `PaymentNotice.implicitRules` |
| PaymentNotice.language | PaymentNotice.language | RelatedTo | R4B `PaymentNotice.language` maps as RelatedTo to R5 `PaymentNotice.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| PaymentNotice.meta | PaymentNotice.meta | Equivalent | R4B `PaymentNotice.meta` maps as Equivalent to R5 `PaymentNotice.meta` |
| PaymentNotice.modifierExtension | PaymentNotice.modifierExtension | RelatedTo | R4B `PaymentNotice.modifierExtension` maps as RelatedTo to R5 `PaymentNotice.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| PaymentNotice.payee | PaymentNotice.payee | Equivalent | R4B `PaymentNotice.payee` maps as Equivalent to R5 `PaymentNotice.payee` |
| PaymentNotice.payment | PaymentNotice.payment | Equivalent | R4B `PaymentNotice.payment` maps as Equivalent to R5 `PaymentNotice.payment` |
| PaymentNotice.paymentDate | PaymentNotice.paymentDate | Equivalent | R4B `PaymentNotice.paymentDate` maps as Equivalent to R5 `PaymentNotice.paymentDate` |
| PaymentNotice.paymentStatus | PaymentNotice.paymentStatus | Equivalent | R4B `PaymentNotice.paymentStatus` maps as Equivalent to R5 `PaymentNotice.paymentStatus` |
| PaymentNotice.provider | - | DoesNotExistInTarget | R4B `PaymentNotice.provider` does not appear in the target and has no mapping for `PaymentNotice`. |
| PaymentNotice.recipient | PaymentNotice.recipient | Equivalent | R4B `PaymentNotice.recipient` maps as Equivalent to R5 `PaymentNotice.recipient` |
| PaymentNotice.request | PaymentNotice.request | Equivalent | R4B `PaymentNotice.request` maps as Equivalent to R5 `PaymentNotice.request` |
| PaymentNotice.response | PaymentNotice.response | Equivalent | R4B `PaymentNotice.response` maps as Equivalent to R5 `PaymentNotice.response` |
| PaymentNotice.status | PaymentNotice.status | Equivalent | R4B `PaymentNotice.status` maps as Equivalent to R5 `PaymentNotice.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/fm-status|4.3.0 and http://hl7.org/fhir/ValueSet/fm-status|5.0.0 (Equivalent) |
| PaymentNotice.text | PaymentNotice.text | Equivalent | R4B `PaymentNotice.text` maps as Equivalent to R5 `PaymentNotice.text` |

