Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | PaymentReconciliation |  | This resource provides the details including amount of a payment and allocates the payment items being paid. | 42 | 28 |
| Target | PaymentReconciliation |  | This resource provides the details including amount of a payment and allocates the payment items being paid. | 59 | 45 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 16 |
Equivalent | 4 |
RelatedTo | 22 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| PaymentReconciliation | PaymentReconciliation | Equivalent | R4B `PaymentReconciliation` maps as Equivalent to R5 `PaymentReconciliation` |
| PaymentReconciliation.contained | PaymentReconciliation.contained | Equivalent | R4B `PaymentReconciliation.contained` maps as Equivalent to R5 `PaymentReconciliation.contained` |
| PaymentReconciliation.created | PaymentReconciliation.created | Equivalent | R4B `PaymentReconciliation.created` maps as Equivalent to R5 `PaymentReconciliation.created` |
| PaymentReconciliation.detail | - | DoesNotExistInTarget | R4B `PaymentReconciliation.detail` does not appear in the target and has no mapping for `PaymentReconciliation`. |
| PaymentReconciliation.detail.amount | - | DoesNotExistInTarget | R4B `PaymentReconciliation.detail.amount` does not appear in the target and has no mapping for `PaymentReconciliation`. |
| PaymentReconciliation.detail.date | - | DoesNotExistInTarget | R4B `PaymentReconciliation.detail.date` does not appear in the target and has no mapping for `PaymentReconciliation`. |
| PaymentReconciliation.detail.extension | - | DoesNotExistInTarget | R4B `PaymentReconciliation.detail.extension` does not appear in the target and has no mapping for `PaymentReconciliation`. |
| PaymentReconciliation.detail.id | - | DoesNotExistInTarget | R4B `PaymentReconciliation.detail.id` does not appear in the target and has no mapping for `PaymentReconciliation`. |
| PaymentReconciliation.detail.identifier | - | DoesNotExistInTarget | R4B `PaymentReconciliation.detail.identifier` does not appear in the target and has no mapping for `PaymentReconciliation`. |
| PaymentReconciliation.detail.modifierExtension | - | DoesNotExistInTarget | R4B `PaymentReconciliation.detail.modifierExtension` does not appear in the target and has no mapping for `PaymentReconciliation`. |
| PaymentReconciliation.detail.payee | - | DoesNotExistInTarget | R4B `PaymentReconciliation.detail.payee` does not appear in the target and has no mapping for `PaymentReconciliation`. |
| PaymentReconciliation.detail.predecessor | - | DoesNotExistInTarget | R4B `PaymentReconciliation.detail.predecessor` does not appear in the target and has no mapping for `PaymentReconciliation`. |
| PaymentReconciliation.detail.request | - | DoesNotExistInTarget | R4B `PaymentReconciliation.detail.request` does not appear in the target and has no mapping for `PaymentReconciliation`. |
| PaymentReconciliation.detail.response | - | DoesNotExistInTarget | R4B `PaymentReconciliation.detail.response` does not appear in the target and has no mapping for `PaymentReconciliation`. |
| PaymentReconciliation.detail.responsible | - | DoesNotExistInTarget | R4B `PaymentReconciliation.detail.responsible` does not appear in the target and has no mapping for `PaymentReconciliation`. |
| PaymentReconciliation.detail.submitter | - | DoesNotExistInTarget | R4B `PaymentReconciliation.detail.submitter` does not appear in the target and has no mapping for `PaymentReconciliation`. |
| PaymentReconciliation.detail.type | - | DoesNotExistInTarget | R4B `PaymentReconciliation.detail.type` does not appear in the target and has no mapping for `PaymentReconciliation`. |
| PaymentReconciliation.disposition | PaymentReconciliation.disposition | Equivalent | R4B `PaymentReconciliation.disposition` maps as Equivalent to R5 `PaymentReconciliation.disposition` |
| PaymentReconciliation.extension | PaymentReconciliation.extension | RelatedTo | R4B `PaymentReconciliation.extension` maps as RelatedTo to R5 `PaymentReconciliation.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| PaymentReconciliation.formCode | PaymentReconciliation.formCode | Equivalent | R4B `PaymentReconciliation.formCode` maps as Equivalent to R5 `PaymentReconciliation.formCode` |
| PaymentReconciliation.id | PaymentReconciliation.id | Equivalent | R4B `PaymentReconciliation.id` maps as Equivalent to R5 `PaymentReconciliation.id` |
| PaymentReconciliation.identifier | PaymentReconciliation.identifier | Equivalent | R4B `PaymentReconciliation.identifier` maps as Equivalent to R5 `PaymentReconciliation.identifier` |
| PaymentReconciliation.implicitRules | PaymentReconciliation.implicitRules | Equivalent | R4B `PaymentReconciliation.implicitRules` maps as Equivalent to R5 `PaymentReconciliation.implicitRules` |
| PaymentReconciliation.language | PaymentReconciliation.language | RelatedTo | R4B `PaymentReconciliation.language` maps as RelatedTo to R5 `PaymentReconciliation.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| PaymentReconciliation.meta | PaymentReconciliation.meta | Equivalent | R4B `PaymentReconciliation.meta` maps as Equivalent to R5 `PaymentReconciliation.meta` |
| PaymentReconciliation.modifierExtension | PaymentReconciliation.modifierExtension | RelatedTo | R4B `PaymentReconciliation.modifierExtension` maps as RelatedTo to R5 `PaymentReconciliation.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| PaymentReconciliation.outcome | PaymentReconciliation.outcome | Equivalent | R4B `PaymentReconciliation.outcome` maps as Equivalent to R5 `PaymentReconciliation.outcome` - outcome has compatible required binding for code type: http://hl7.org/fhir/ValueSet/remittance-outcome|4.3.0 and http://hl7.org/fhir/ValueSet/payment-outcome|5.0.0 (Equivalent) |
| PaymentReconciliation.paymentAmount | - | DoesNotExistInTarget | R4B `PaymentReconciliation.paymentAmount` does not appear in the target and has no mapping for `PaymentReconciliation`. |
| PaymentReconciliation.paymentDate | - | DoesNotExistInTarget | R4B `PaymentReconciliation.paymentDate` does not appear in the target and has no mapping for `PaymentReconciliation`. |
| PaymentReconciliation.paymentIdentifier | PaymentReconciliation.paymentIdentifier | Equivalent | R4B `PaymentReconciliation.paymentIdentifier` maps as Equivalent to R5 `PaymentReconciliation.paymentIdentifier` |
| PaymentReconciliation.paymentIssuer | PaymentReconciliation.paymentIssuer | SourceIsNarrowerThanTarget | R4B `PaymentReconciliation.paymentIssuer` maps as SourceIsNarrowerThanTarget to R5 `PaymentReconciliation.paymentIssuer` - paymentIssuer has change due to type change: R4B `paymentIssuer` `Reference` maps as SourceIsNarrowerThanTarget for R5 `paymentIssuer` |
| PaymentReconciliation.period | PaymentReconciliation.period | Equivalent | R4B `PaymentReconciliation.period` maps as Equivalent to R5 `PaymentReconciliation.period` |
| PaymentReconciliation.processNote | PaymentReconciliation.processNote | Equivalent | R4B `PaymentReconciliation.processNote` maps as Equivalent to R5 `PaymentReconciliation.processNote` |
| PaymentReconciliation.processNote.extension | PaymentReconciliation.processNote.extension | RelatedTo | R4B `PaymentReconciliation.processNote.extension` maps as RelatedTo to R5 `PaymentReconciliation.processNote.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| PaymentReconciliation.processNote.id | PaymentReconciliation.processNote.id | Equivalent | R4B `PaymentReconciliation.processNote.id` maps as Equivalent to R5 `PaymentReconciliation.processNote.id` |
| PaymentReconciliation.processNote.modifierExtension | PaymentReconciliation.processNote.modifierExtension | RelatedTo | R4B `PaymentReconciliation.processNote.modifierExtension` maps as RelatedTo to R5 `PaymentReconciliation.processNote.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| PaymentReconciliation.processNote.text | PaymentReconciliation.processNote.text | Equivalent | R4B `PaymentReconciliation.processNote.text` maps as Equivalent to R5 `PaymentReconciliation.processNote.text` |
| PaymentReconciliation.processNote.type | PaymentReconciliation.processNote.type | Equivalent | R4B `PaymentReconciliation.processNote.type` maps as Equivalent to R5 `PaymentReconciliation.processNote.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/note-type|4.3.0 and http://hl7.org/fhir/ValueSet/note-type|5.0.0 (Equivalent) |
| PaymentReconciliation.request | PaymentReconciliation.request | Equivalent | R4B `PaymentReconciliation.request` maps as Equivalent to R5 `PaymentReconciliation.request` |
| PaymentReconciliation.requestor | PaymentReconciliation.requestor | Equivalent | R4B `PaymentReconciliation.requestor` maps as Equivalent to R5 `PaymentReconciliation.requestor` |
| PaymentReconciliation.status | PaymentReconciliation.status | Equivalent | R4B `PaymentReconciliation.status` maps as Equivalent to R5 `PaymentReconciliation.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/fm-status|4.3.0 and http://hl7.org/fhir/ValueSet/fm-status|5.0.0 (Equivalent) |
| PaymentReconciliation.text | PaymentReconciliation.text | Equivalent | R4B `PaymentReconciliation.text` maps as Equivalent to R5 `PaymentReconciliation.text` |

