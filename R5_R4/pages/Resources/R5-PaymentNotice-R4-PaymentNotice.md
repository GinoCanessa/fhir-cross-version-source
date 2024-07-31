Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | PaymentNotice |  | This resource provides the status of the payment for goods and services rendered, and the request and response resource references. | 21 | 13 |
| Target | PaymentNotice |  | This resource provides the status of the payment for goods and services rendered, and the request and response resource references. | 21 | 13 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 17 |
RelatedTo | 1 |
SourceIsBroaderThanTarget | 2 |
SourceIsNarrowerThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| PaymentNotice | PaymentNotice | Equivalent | R5 `PaymentNotice` maps as Equivalent to R4 `PaymentNotice` |
| PaymentNotice.amount | PaymentNotice.amount | Equivalent | R5 `PaymentNotice.amount` maps as Equivalent to R4 `PaymentNotice.amount` |
| PaymentNotice.contained | PaymentNotice.contained | Equivalent | R5 `PaymentNotice.contained` maps as Equivalent to R4 `PaymentNotice.contained` |
| PaymentNotice.created | PaymentNotice.created | Equivalent | R5 `PaymentNotice.created` maps as Equivalent to R4 `PaymentNotice.created` |
| PaymentNotice.extension | PaymentNotice.extension | SourceIsBroaderThanTarget | R5 `PaymentNotice.extension` maps as SourceIsBroaderThanTarget to R4 `PaymentNotice.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| PaymentNotice.id | PaymentNotice.id | Equivalent | R5 `PaymentNotice.id` maps as Equivalent to R4 `PaymentNotice.id` |
| PaymentNotice.identifier | PaymentNotice.identifier | Equivalent | R5 `PaymentNotice.identifier` maps as Equivalent to R4 `PaymentNotice.identifier` |
| PaymentNotice.implicitRules | PaymentNotice.implicitRules | Equivalent | R5 `PaymentNotice.implicitRules` maps as Equivalent to R4 `PaymentNotice.implicitRules` |
| PaymentNotice.language | PaymentNotice.language | SourceIsNarrowerThanTarget | R5 `PaymentNotice.language` maps as SourceIsNarrowerThanTarget to R4 `PaymentNotice.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| PaymentNotice.meta | PaymentNotice.meta | Equivalent | R5 `PaymentNotice.meta` maps as Equivalent to R4 `PaymentNotice.meta` |
| PaymentNotice.modifierExtension | PaymentNotice.modifierExtension | SourceIsBroaderThanTarget | R5 `PaymentNotice.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `PaymentNotice.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| PaymentNotice.payee | PaymentNotice.payee | Equivalent | R5 `PaymentNotice.payee` maps as Equivalent to R4 `PaymentNotice.payee` |
| PaymentNotice.payment | PaymentNotice.payment | RelatedTo | R5 `PaymentNotice.payment` maps as RelatedTo to R4 `PaymentNotice.payment` - payment made the element mandatory; payment increased the minimum cardinality from 0 to 1 |
| PaymentNotice.paymentDate | PaymentNotice.paymentDate | Equivalent | R5 `PaymentNotice.paymentDate` maps as Equivalent to R4 `PaymentNotice.paymentDate` |
| PaymentNotice.paymentStatus | PaymentNotice.paymentStatus | Equivalent | R5 `PaymentNotice.paymentStatus` maps as Equivalent to R4 `PaymentNotice.paymentStatus` |
| PaymentNotice.recipient | PaymentNotice.recipient | Equivalent | R5 `PaymentNotice.recipient` maps as Equivalent to R4 `PaymentNotice.recipient` |
| PaymentNotice.reporter | PaymentNotice.provider | Equivalent | R5 `PaymentNotice.reporter` maps as Equivalent to R4 `PaymentNotice.provider` |
| PaymentNotice.request | PaymentNotice.request | Equivalent | R5 `PaymentNotice.request` maps as Equivalent to R4 `PaymentNotice.request` |
| PaymentNotice.response | PaymentNotice.response | Equivalent | R5 `PaymentNotice.response` maps as Equivalent to R4 `PaymentNotice.response` |
| PaymentNotice.status | PaymentNotice.status | Equivalent | R5 `PaymentNotice.status` maps as Equivalent to R4 `PaymentNotice.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/fm-status|5.0.0 and http://hl7.org/fhir/ValueSet/fm-status|4.0.1 (Equivalent) |
| PaymentNotice.text | PaymentNotice.text | Equivalent | R5 `PaymentNotice.text` maps as Equivalent to R4 `PaymentNotice.text` |

