Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

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
| PaymentNotice | PaymentNotice | Equivalent | R5 `PaymentNotice` maps as Equivalent to R4B `PaymentNotice` |
| PaymentNotice.amount | PaymentNotice.amount | RelatedTo | R5 `PaymentNotice.amount` maps as RelatedTo to R4B `PaymentNotice.amount` - amount has change due to type change: R5 `amount` `Money` maps as RelatedTo for R4B `amount` |
| PaymentNotice.contained | PaymentNotice.contained | Equivalent | R5 `PaymentNotice.contained` maps as Equivalent to R4B `PaymentNotice.contained` |
| PaymentNotice.created | PaymentNotice.created | Equivalent | R5 `PaymentNotice.created` maps as Equivalent to R4B `PaymentNotice.created` |
| PaymentNotice.extension | PaymentNotice.extension | SourceIsBroaderThanTarget | R5 `PaymentNotice.extension` maps as SourceIsBroaderThanTarget to R4B `PaymentNotice.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| PaymentNotice.id | PaymentNotice.id | Equivalent | R5 `PaymentNotice.id` maps as Equivalent to R4B `PaymentNotice.id` |
| PaymentNotice.identifier | PaymentNotice.identifier | Equivalent | R5 `PaymentNotice.identifier` maps as Equivalent to R4B `PaymentNotice.identifier` |
| PaymentNotice.implicitRules | PaymentNotice.implicitRules | Equivalent | R5 `PaymentNotice.implicitRules` maps as Equivalent to R4B `PaymentNotice.implicitRules` |
| PaymentNotice.language | PaymentNotice.language | RelatedTo | R5 `PaymentNotice.language` maps as RelatedTo to R4B `PaymentNotice.language` - language changed the binding strength from Required to Preferred |
| PaymentNotice.meta | PaymentNotice.meta | Equivalent | R5 `PaymentNotice.meta` maps as Equivalent to R4B `PaymentNotice.meta` |
| PaymentNotice.modifierExtension | PaymentNotice.modifierExtension | SourceIsBroaderThanTarget | R5 `PaymentNotice.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `PaymentNotice.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| PaymentNotice.payee | PaymentNotice.payee | Equivalent | R5 `PaymentNotice.payee` maps as Equivalent to R4B `PaymentNotice.payee` |
| PaymentNotice.payment | PaymentNotice.payment | RelatedTo | R5 `PaymentNotice.payment` maps as RelatedTo to R4B `PaymentNotice.payment` - payment made the element mandatory; payment increased the minimum cardinality from 0 to 1 |
| PaymentNotice.paymentDate | PaymentNotice.paymentDate | Equivalent | R5 `PaymentNotice.paymentDate` maps as Equivalent to R4B `PaymentNotice.paymentDate` |
| PaymentNotice.paymentStatus | PaymentNotice.paymentStatus | Equivalent | R5 `PaymentNotice.paymentStatus` maps as Equivalent to R4B `PaymentNotice.paymentStatus` |
| PaymentNotice.recipient | PaymentNotice.recipient | Equivalent | R5 `PaymentNotice.recipient` maps as Equivalent to R4B `PaymentNotice.recipient` |
| PaymentNotice.reporter | - | DoesNotExistInTarget | R5 `PaymentNotice.reporter` does not appear in the target and has no mapping for `PaymentNotice`. |
| PaymentNotice.request | PaymentNotice.request | Equivalent | R5 `PaymentNotice.request` maps as Equivalent to R4B `PaymentNotice.request` |
| PaymentNotice.response | PaymentNotice.response | Equivalent | R5 `PaymentNotice.response` maps as Equivalent to R4B `PaymentNotice.response` |
| PaymentNotice.status | PaymentNotice.status | Equivalent | R5 `PaymentNotice.status` maps as Equivalent to R4B `PaymentNotice.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/fm-status|5.0.0 and http://hl7.org/fhir/ValueSet/fm-status|4.3.0 (Equivalent) |
| PaymentNotice.text | PaymentNotice.text | Equivalent | R5 `PaymentNotice.text` maps as Equivalent to R4B `PaymentNotice.text` |

