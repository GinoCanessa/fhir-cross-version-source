Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Invoice |  | Invoice containing collected ChargeItems from an Account with calculated individual and total price for Billing purpose. | 39 | 25 |
| Target | Invoice |  | Invoice containing collected ChargeItems from an Account with calculated individual and total price for Billing purpose. | 43 | 26 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 3 |
Equivalent | 4 |
RelatedTo | 32 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Invoice | Invoice | Equivalent | R5 `Invoice` maps as Equivalent to R4B `Invoice` |
| Invoice.account | Invoice.account | Equivalent | R5 `Invoice.account` maps as Equivalent to R4B `Invoice.account` |
| Invoice.cancelledReason | Invoice.cancelledReason | Equivalent | R5 `Invoice.cancelledReason` maps as Equivalent to R4B `Invoice.cancelledReason` |
| Invoice.contained | Invoice.contained | Equivalent | R5 `Invoice.contained` maps as Equivalent to R4B `Invoice.contained` |
| Invoice.creation | - | DoesNotExistInTarget | R5 `Invoice.creation` does not appear in the target and has no mapping for `Invoice`. |
| Invoice.date | Invoice.date | Equivalent | R5 `Invoice.date` maps as Equivalent to R4B `Invoice.date` |
| Invoice.extension | Invoice.extension | SourceIsBroaderThanTarget | R5 `Invoice.extension` maps as SourceIsBroaderThanTarget to R4B `Invoice.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Invoice.id | Invoice.id | Equivalent | R5 `Invoice.id` maps as Equivalent to R4B `Invoice.id` |
| Invoice.identifier | Invoice.identifier | Equivalent | R5 `Invoice.identifier` maps as Equivalent to R4B `Invoice.identifier` |
| Invoice.implicitRules | Invoice.implicitRules | Equivalent | R5 `Invoice.implicitRules` maps as Equivalent to R4B `Invoice.implicitRules` |
| Invoice.issuer | Invoice.issuer | Equivalent | R5 `Invoice.issuer` maps as Equivalent to R4B `Invoice.issuer` |
| Invoice.language | Invoice.language | RelatedTo | R5 `Invoice.language` maps as RelatedTo to R4B `Invoice.language` - language changed the binding strength from Required to Preferred |
| Invoice.lineItem | Invoice.lineItem | Equivalent | R5 `Invoice.lineItem` maps as Equivalent to R4B `Invoice.lineItem` |
| Invoice.lineItem.chargeItem[x] | Invoice.lineItem.chargeItem[x] | Equivalent | R5 `Invoice.lineItem.chargeItem[x]` maps as Equivalent to R4B `Invoice.lineItem.chargeItem[x]` |
| Invoice.lineItem.extension | Invoice.lineItem.extension | SourceIsBroaderThanTarget | R5 `Invoice.lineItem.extension` maps as SourceIsBroaderThanTarget to R4B `Invoice.lineItem.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Invoice.lineItem.id | Invoice.lineItem.id | Equivalent | R5 `Invoice.lineItem.id` maps as Equivalent to R4B `Invoice.lineItem.id` |
| Invoice.lineItem.modifierExtension | Invoice.lineItem.modifierExtension | SourceIsBroaderThanTarget | R5 `Invoice.lineItem.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Invoice.lineItem.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Invoice.lineItem.priceComponent | Invoice.lineItem.priceComponent | SourceIsBroaderThanTarget | R5 `Invoice.lineItem.priceComponent` maps as SourceIsBroaderThanTarget to R4B `Invoice.lineItem.priceComponent` - priceComponent has change due to type change: R5 type MonetaryComponent does not exist in R4B |
| Invoice.lineItem.sequence | Invoice.lineItem.sequence | Equivalent | R5 `Invoice.lineItem.sequence` maps as Equivalent to R4B `Invoice.lineItem.sequence` |
| Invoice.lineItem.serviced[x] | - | DoesNotExistInTarget | R5 `Invoice.lineItem.serviced[x]` does not appear in the target and has no mapping for `Invoice`. |
| Invoice.meta | Invoice.meta | Equivalent | R5 `Invoice.meta` maps as Equivalent to R4B `Invoice.meta` |
| Invoice.modifierExtension | Invoice.modifierExtension | SourceIsBroaderThanTarget | R5 `Invoice.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Invoice.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Invoice.note | Invoice.note | SourceIsBroaderThanTarget | R5 `Invoice.note` maps as SourceIsBroaderThanTarget to R4B `Invoice.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4B `note` |
| Invoice.participant | Invoice.participant | Equivalent | R5 `Invoice.participant` maps as Equivalent to R4B `Invoice.participant` |
| Invoice.participant.actor | Invoice.participant.actor | Equivalent | R5 `Invoice.participant.actor` maps as Equivalent to R4B `Invoice.participant.actor` |
| Invoice.participant.extension | Invoice.participant.extension | SourceIsBroaderThanTarget | R5 `Invoice.participant.extension` maps as SourceIsBroaderThanTarget to R4B `Invoice.participant.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Invoice.participant.id | Invoice.participant.id | Equivalent | R5 `Invoice.participant.id` maps as Equivalent to R4B `Invoice.participant.id` |
| Invoice.participant.modifierExtension | Invoice.participant.modifierExtension | SourceIsBroaderThanTarget | R5 `Invoice.participant.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Invoice.participant.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Invoice.participant.role | Invoice.participant.role | Equivalent | R5 `Invoice.participant.role` maps as Equivalent to R4B `Invoice.participant.role` |
| Invoice.paymentTerms | Invoice.paymentTerms | Equivalent | R5 `Invoice.paymentTerms` maps as Equivalent to R4B `Invoice.paymentTerms` |
| Invoice.period[x] | - | DoesNotExistInTarget | R5 `Invoice.period[x]` does not appear in the target and has no mapping for `Invoice`. |
| Invoice.recipient | Invoice.recipient | Equivalent | R5 `Invoice.recipient` maps as Equivalent to R4B `Invoice.recipient` |
| Invoice.status | Invoice.status | Equivalent | R5 `Invoice.status` maps as Equivalent to R4B `Invoice.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/invoice-status|5.0.0 and http://hl7.org/fhir/ValueSet/invoice-status|4.3.0 (Equivalent) |
| Invoice.subject | Invoice.subject | Equivalent | R5 `Invoice.subject` maps as Equivalent to R4B `Invoice.subject` |
| Invoice.text | Invoice.text | Equivalent | R5 `Invoice.text` maps as Equivalent to R4B `Invoice.text` |
| Invoice.totalGross | Invoice.totalGross | RelatedTo | R5 `Invoice.totalGross` maps as RelatedTo to R4B `Invoice.totalGross` - totalGross has change due to type change: R5 `totalGross` `Money` maps as RelatedTo for R4B `totalGross` |
| Invoice.totalNet | Invoice.totalNet | RelatedTo | R5 `Invoice.totalNet` maps as RelatedTo to R4B `Invoice.totalNet` - totalNet has change due to type change: R5 `totalNet` `Money` maps as RelatedTo for R4B `totalNet` |
| Invoice.totalPriceComponent | Invoice.totalPriceComponent | SourceIsBroaderThanTarget | R5 `Invoice.totalPriceComponent` maps as SourceIsBroaderThanTarget to R4B `Invoice.totalPriceComponent` - totalPriceComponent has change due to type change: R5 type MonetaryComponent does not exist in R4B |
| Invoice.type | Invoice.type | Equivalent | R5 `Invoice.type` maps as Equivalent to R4B `Invoice.type` |

