Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | PaymentReconciliation |  | This resource provides the details including amount of a payment and allocates the payment items being paid. | 59 | 45 |
| Target | PaymentReconciliation |  | This resource provides the details including amount of a payment and allocates the payment items being paid. | 42 | 28 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 21 |
Equivalent | 30 |
RelatedTo | 2 |
SourceIsBroaderThanTarget | 5 |
SourceIsNarrowerThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| PaymentReconciliation | PaymentReconciliation | Equivalent | R5 `PaymentReconciliation` maps as Equivalent to R4 `PaymentReconciliation` |
| PaymentReconciliation.accountNumber | - | DoesNotExistInTarget | R5 `PaymentReconciliation.accountNumber` does not appear in the target and has no mapping for `PaymentReconciliation`. |
| PaymentReconciliation.allocation | PaymentReconciliation.detail | Equivalent | R5 `PaymentReconciliation.allocation` maps as Equivalent to R4 `PaymentReconciliation.detail` |
| PaymentReconciliation.allocation.account | - | DoesNotExistInTarget | R5 `PaymentReconciliation.allocation.account` does not appear in the target and has no mapping for `PaymentReconciliation`. |
| PaymentReconciliation.allocation.amount | PaymentReconciliation.detail.amount | Equivalent | R5 `PaymentReconciliation.allocation.amount` maps as Equivalent to R4 `PaymentReconciliation.detail.amount` |
| PaymentReconciliation.allocation.date | PaymentReconciliation.detail.date | Equivalent | R5 `PaymentReconciliation.allocation.date` maps as Equivalent to R4 `PaymentReconciliation.detail.date` |
| PaymentReconciliation.allocation.encounter | - | DoesNotExistInTarget | R5 `PaymentReconciliation.allocation.encounter` does not appear in the target and has no mapping for `PaymentReconciliation`. |
| PaymentReconciliation.allocation.extension | - | DoesNotExistInTarget | R5 `PaymentReconciliation.allocation.extension` does not appear in the target and has no mapping for `PaymentReconciliation`. |
| PaymentReconciliation.allocation.id | - | DoesNotExistInTarget | R5 `PaymentReconciliation.allocation.id` does not appear in the target and has no mapping for `PaymentReconciliation`. |
| PaymentReconciliation.allocation.identifier | PaymentReconciliation.detail.identifier | Equivalent | R5 `PaymentReconciliation.allocation.identifier` maps as Equivalent to R4 `PaymentReconciliation.detail.identifier` |
| PaymentReconciliation.allocation.modifierExtension | - | DoesNotExistInTarget | R5 `PaymentReconciliation.allocation.modifierExtension` does not appear in the target and has no mapping for `PaymentReconciliation`. |
| PaymentReconciliation.allocation.payee | PaymentReconciliation.detail.payee | Equivalent | R5 `PaymentReconciliation.allocation.payee` maps as Equivalent to R4 `PaymentReconciliation.detail.payee` |
| PaymentReconciliation.allocation.predecessor | PaymentReconciliation.detail.predecessor | Equivalent | R5 `PaymentReconciliation.allocation.predecessor` maps as Equivalent to R4 `PaymentReconciliation.detail.predecessor` |
| PaymentReconciliation.allocation.response | PaymentReconciliation.detail.response | RelatedTo | R5 `PaymentReconciliation.allocation.response` maps as RelatedTo to R4 `PaymentReconciliation.detail.response` - response has change due to type change: R5 `response` `Reference` maps as RelatedTo for R4 `response` |
| PaymentReconciliation.allocation.responsible | PaymentReconciliation.detail.responsible | Equivalent | R5 `PaymentReconciliation.allocation.responsible` maps as Equivalent to R4 `PaymentReconciliation.detail.responsible` |
| PaymentReconciliation.allocation.submitter | PaymentReconciliation.detail.submitter | Equivalent | R5 `PaymentReconciliation.allocation.submitter` maps as Equivalent to R4 `PaymentReconciliation.detail.submitter` |
| PaymentReconciliation.allocation.target | - | DoesNotExistInTarget | R5 `PaymentReconciliation.allocation.target` does not appear in the target and has no mapping for `PaymentReconciliation`. |
| PaymentReconciliation.allocation.targetItem[x] | - | DoesNotExistInTarget | R5 `PaymentReconciliation.allocation.targetItem[x]` does not appear in the target and has no mapping for `PaymentReconciliation`. |
| PaymentReconciliation.allocation.type | PaymentReconciliation.detail.type | RelatedTo | R5 `PaymentReconciliation.allocation.type` maps as RelatedTo to R4 `PaymentReconciliation.detail.type` - type made the element mandatory; type increased the minimum cardinality from 0 to 1; type changed the binding strength from Extensible to Example; type has change due to type change: R5 `type` `CodeableConcept` maps as SourceIsNarrowerThanTarget for R4 `type` |
| PaymentReconciliation.amount | PaymentReconciliation.paymentAmount | Equivalent | R5 `PaymentReconciliation.amount` maps as Equivalent to R4 `PaymentReconciliation.paymentAmount` |
| PaymentReconciliation.authorization | - | DoesNotExistInTarget | R5 `PaymentReconciliation.authorization` does not appear in the target and has no mapping for `PaymentReconciliation`. |
| PaymentReconciliation.cardBrand | - | DoesNotExistInTarget | R5 `PaymentReconciliation.cardBrand` does not appear in the target and has no mapping for `PaymentReconciliation`. |
| PaymentReconciliation.contained | PaymentReconciliation.contained | Equivalent | R5 `PaymentReconciliation.contained` maps as Equivalent to R4 `PaymentReconciliation.contained` |
| PaymentReconciliation.created | PaymentReconciliation.created | Equivalent | R5 `PaymentReconciliation.created` maps as Equivalent to R4 `PaymentReconciliation.created` |
| PaymentReconciliation.date | PaymentReconciliation.paymentDate | Equivalent | R5 `PaymentReconciliation.date` maps as Equivalent to R4 `PaymentReconciliation.paymentDate` |
| PaymentReconciliation.disposition | PaymentReconciliation.disposition | Equivalent | R5 `PaymentReconciliation.disposition` maps as Equivalent to R4 `PaymentReconciliation.disposition` |
| PaymentReconciliation.enterer | - | DoesNotExistInTarget | R5 `PaymentReconciliation.enterer` does not appear in the target and has no mapping for `PaymentReconciliation`. |
| PaymentReconciliation.expirationDate | - | DoesNotExistInTarget | R5 `PaymentReconciliation.expirationDate` does not appear in the target and has no mapping for `PaymentReconciliation`. |
| PaymentReconciliation.extension | PaymentReconciliation.extension | SourceIsBroaderThanTarget | R5 `PaymentReconciliation.extension` maps as SourceIsBroaderThanTarget to R4 `PaymentReconciliation.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| PaymentReconciliation.formCode | PaymentReconciliation.formCode | Equivalent | R5 `PaymentReconciliation.formCode` maps as Equivalent to R4 `PaymentReconciliation.formCode` |
| PaymentReconciliation.id | PaymentReconciliation.id | Equivalent | R5 `PaymentReconciliation.id` maps as Equivalent to R4 `PaymentReconciliation.id` |
| PaymentReconciliation.identifier | PaymentReconciliation.identifier | Equivalent | R5 `PaymentReconciliation.identifier` maps as Equivalent to R4 `PaymentReconciliation.identifier` |
| PaymentReconciliation.implicitRules | PaymentReconciliation.implicitRules | Equivalent | R5 `PaymentReconciliation.implicitRules` maps as Equivalent to R4 `PaymentReconciliation.implicitRules` |
| PaymentReconciliation.issuerType | - | DoesNotExistInTarget | R5 `PaymentReconciliation.issuerType` does not appear in the target and has no mapping for `PaymentReconciliation`. |
| PaymentReconciliation.kind | - | DoesNotExistInTarget | R5 `PaymentReconciliation.kind` does not appear in the target and has no mapping for `PaymentReconciliation`. |
| PaymentReconciliation.language | PaymentReconciliation.language | SourceIsNarrowerThanTarget | R5 `PaymentReconciliation.language` maps as SourceIsNarrowerThanTarget to R4 `PaymentReconciliation.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| PaymentReconciliation.location | - | DoesNotExistInTarget | R5 `PaymentReconciliation.location` does not appear in the target and has no mapping for `PaymentReconciliation`. |
| PaymentReconciliation.meta | PaymentReconciliation.meta | Equivalent | R5 `PaymentReconciliation.meta` maps as Equivalent to R4 `PaymentReconciliation.meta` |
| PaymentReconciliation.method | - | DoesNotExistInTarget | R5 `PaymentReconciliation.method` does not appear in the target and has no mapping for `PaymentReconciliation`. |
| PaymentReconciliation.modifierExtension | PaymentReconciliation.modifierExtension | SourceIsBroaderThanTarget | R5 `PaymentReconciliation.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `PaymentReconciliation.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| PaymentReconciliation.outcome | PaymentReconciliation.outcome | Equivalent | R5 `PaymentReconciliation.outcome` maps as Equivalent to R4 `PaymentReconciliation.outcome` - outcome has compatible required binding for code type: http://hl7.org/fhir/ValueSet/payment-outcome|5.0.0 and http://hl7.org/fhir/ValueSet/remittance-outcome|4.0.1 (Equivalent) |
| PaymentReconciliation.paymentIdentifier | PaymentReconciliation.paymentIdentifier | Equivalent | R5 `PaymentReconciliation.paymentIdentifier` maps as Equivalent to R4 `PaymentReconciliation.paymentIdentifier` |
| PaymentReconciliation.paymentIssuer | PaymentReconciliation.paymentIssuer | SourceIsBroaderThanTarget | R5 `PaymentReconciliation.paymentIssuer` maps as SourceIsBroaderThanTarget to R4 `PaymentReconciliation.paymentIssuer` - paymentIssuer has change due to type change: R5 `paymentIssuer` `Reference` maps as SourceIsBroaderThanTarget for R4 `paymentIssuer` |
| PaymentReconciliation.period | PaymentReconciliation.period | Equivalent | R5 `PaymentReconciliation.period` maps as Equivalent to R4 `PaymentReconciliation.period` |
| PaymentReconciliation.processNote | PaymentReconciliation.processNote | Equivalent | R5 `PaymentReconciliation.processNote` maps as Equivalent to R4 `PaymentReconciliation.processNote` |
| PaymentReconciliation.processNote.extension | PaymentReconciliation.processNote.extension | SourceIsBroaderThanTarget | R5 `PaymentReconciliation.processNote.extension` maps as SourceIsBroaderThanTarget to R4 `PaymentReconciliation.processNote.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| PaymentReconciliation.processNote.id | PaymentReconciliation.processNote.id | Equivalent | R5 `PaymentReconciliation.processNote.id` maps as Equivalent to R4 `PaymentReconciliation.processNote.id` |
| PaymentReconciliation.processNote.modifierExtension | PaymentReconciliation.processNote.modifierExtension | SourceIsBroaderThanTarget | R5 `PaymentReconciliation.processNote.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `PaymentReconciliation.processNote.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| PaymentReconciliation.processNote.text | PaymentReconciliation.processNote.text | Equivalent | R5 `PaymentReconciliation.processNote.text` maps as Equivalent to R4 `PaymentReconciliation.processNote.text` |
| PaymentReconciliation.processNote.type | PaymentReconciliation.processNote.type | Equivalent | R5 `PaymentReconciliation.processNote.type` maps as Equivalent to R4 `PaymentReconciliation.processNote.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/note-type|5.0.0 and http://hl7.org/fhir/ValueSet/note-type|4.0.1 (Equivalent) |
| PaymentReconciliation.processor | - | DoesNotExistInTarget | R5 `PaymentReconciliation.processor` does not appear in the target and has no mapping for `PaymentReconciliation`. |
| PaymentReconciliation.referenceNumber | - | DoesNotExistInTarget | R5 `PaymentReconciliation.referenceNumber` does not appear in the target and has no mapping for `PaymentReconciliation`. |
| PaymentReconciliation.request | PaymentReconciliation.request | Equivalent | R5 `PaymentReconciliation.request` maps as Equivalent to R4 `PaymentReconciliation.request` |
| PaymentReconciliation.requestor | PaymentReconciliation.requestor | Equivalent | R5 `PaymentReconciliation.requestor` maps as Equivalent to R4 `PaymentReconciliation.requestor` |
| PaymentReconciliation.returnedAmount | - | DoesNotExistInTarget | R5 `PaymentReconciliation.returnedAmount` does not appear in the target and has no mapping for `PaymentReconciliation`. |
| PaymentReconciliation.status | PaymentReconciliation.status | Equivalent | R5 `PaymentReconciliation.status` maps as Equivalent to R4 `PaymentReconciliation.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/fm-status|5.0.0 and http://hl7.org/fhir/ValueSet/fm-status|4.0.1 (Equivalent) |
| PaymentReconciliation.tenderedAmount | - | DoesNotExistInTarget | R5 `PaymentReconciliation.tenderedAmount` does not appear in the target and has no mapping for `PaymentReconciliation`. |
| PaymentReconciliation.text | PaymentReconciliation.text | Equivalent | R5 `PaymentReconciliation.text` maps as Equivalent to R4 `PaymentReconciliation.text` |
| PaymentReconciliation.type | - | DoesNotExistInTarget | R5 `PaymentReconciliation.type` does not appear in the target and has no mapping for `PaymentReconciliation`. |

