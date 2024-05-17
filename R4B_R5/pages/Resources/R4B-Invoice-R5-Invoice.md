Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Invoice |  | Invoice containing collected ChargeItems from an Account with calculated individual and total price for Billing purpose. | 43 | 26 |
| Target | Invoice |  | Invoice containing collected ChargeItems from an Account with calculated individual and total price for Billing purpose. | 39 | 25 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 7 |
Equivalent | 4 |
RelatedTo | 32 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Invoice | Invoice | Equivalent | R4B `Invoice` maps as Equivalent to R5 `Invoice` |
| Invoice.account | Invoice.account | Equivalent | R4B `Invoice.account` maps as Equivalent to R5 `Invoice.account` |
| Invoice.cancelledReason | Invoice.cancelledReason | Equivalent | R4B `Invoice.cancelledReason` maps as Equivalent to R5 `Invoice.cancelledReason` |
| Invoice.contained | Invoice.contained | Equivalent | R4B `Invoice.contained` maps as Equivalent to R5 `Invoice.contained` |
| Invoice.date | Invoice.date | Equivalent | R4B `Invoice.date` maps as Equivalent to R5 `Invoice.date` |
| Invoice.extension | Invoice.extension | RelatedTo | R4B `Invoice.extension` maps as RelatedTo to R5 `Invoice.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Invoice.id | Invoice.id | Equivalent | R4B `Invoice.id` maps as Equivalent to R5 `Invoice.id` |
| Invoice.identifier | Invoice.identifier | Equivalent | R4B `Invoice.identifier` maps as Equivalent to R5 `Invoice.identifier` |
| Invoice.implicitRules | Invoice.implicitRules | Equivalent | R4B `Invoice.implicitRules` maps as Equivalent to R5 `Invoice.implicitRules` |
| Invoice.issuer | Invoice.issuer | Equivalent | R4B `Invoice.issuer` maps as Equivalent to R5 `Invoice.issuer` |
| Invoice.language | Invoice.language | RelatedTo | R4B `Invoice.language` maps as RelatedTo to R5 `Invoice.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Invoice.lineItem | Invoice.lineItem | Equivalent | R4B `Invoice.lineItem` maps as Equivalent to R5 `Invoice.lineItem` |
| Invoice.lineItem.chargeItem[x] | Invoice.lineItem.chargeItem[x] | Equivalent | R4B `Invoice.lineItem.chargeItem[x]` maps as Equivalent to R5 `Invoice.lineItem.chargeItem[x]` |
| Invoice.lineItem.extension | Invoice.lineItem.extension | RelatedTo | R4B `Invoice.lineItem.extension` maps as RelatedTo to R5 `Invoice.lineItem.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Invoice.lineItem.id | Invoice.lineItem.id | Equivalent | R4B `Invoice.lineItem.id` maps as Equivalent to R5 `Invoice.lineItem.id` |
| Invoice.lineItem.modifierExtension | Invoice.lineItem.modifierExtension | RelatedTo | R4B `Invoice.lineItem.modifierExtension` maps as RelatedTo to R5 `Invoice.lineItem.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Invoice.lineItem.priceComponent | Invoice.lineItem.priceComponent | SourceIsBroaderThanTarget | R4B `Invoice.lineItem.priceComponent` maps as SourceIsBroaderThanTarget to R5 `Invoice.lineItem.priceComponent` - priceComponent has change due to type change: R4B priceComponent BackboneElement has no equivalent or mapped type in R5 priceComponent |
| Invoice.lineItem.priceComponent.amount | - | DoesNotExistInTarget | R4B `Invoice.lineItem.priceComponent.amount` does not appear in the target and has no mapping for `Invoice`. |
| Invoice.lineItem.priceComponent.code | - | DoesNotExistInTarget | R4B `Invoice.lineItem.priceComponent.code` does not appear in the target and has no mapping for `Invoice`. |
| Invoice.lineItem.priceComponent.extension | - | DoesNotExistInTarget | R4B `Invoice.lineItem.priceComponent.extension` does not appear in the target and has no mapping for `Invoice`. |
| Invoice.lineItem.priceComponent.factor | - | DoesNotExistInTarget | R4B `Invoice.lineItem.priceComponent.factor` does not appear in the target and has no mapping for `Invoice`. |
| Invoice.lineItem.priceComponent.id | - | DoesNotExistInTarget | R4B `Invoice.lineItem.priceComponent.id` does not appear in the target and has no mapping for `Invoice`. |
| Invoice.lineItem.priceComponent.modifierExtension | - | DoesNotExistInTarget | R4B `Invoice.lineItem.priceComponent.modifierExtension` does not appear in the target and has no mapping for `Invoice`. |
| Invoice.lineItem.priceComponent.type | - | DoesNotExistInTarget | R4B `Invoice.lineItem.priceComponent.type` does not appear in the target and has no mapping for `Invoice`. |
| Invoice.lineItem.sequence | Invoice.lineItem.sequence | Equivalent | R4B `Invoice.lineItem.sequence` maps as Equivalent to R5 `Invoice.lineItem.sequence` |
| Invoice.meta | Invoice.meta | Equivalent | R4B `Invoice.meta` maps as Equivalent to R5 `Invoice.meta` |
| Invoice.modifierExtension | Invoice.modifierExtension | RelatedTo | R4B `Invoice.modifierExtension` maps as RelatedTo to R5 `Invoice.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Invoice.note | Invoice.note | SourceIsNarrowerThanTarget | R4B `Invoice.note` maps as SourceIsNarrowerThanTarget to R5 `Invoice.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| Invoice.participant | Invoice.participant | Equivalent | R4B `Invoice.participant` maps as Equivalent to R5 `Invoice.participant` |
| Invoice.participant.actor | Invoice.participant.actor | Equivalent | R4B `Invoice.participant.actor` maps as Equivalent to R5 `Invoice.participant.actor` |
| Invoice.participant.extension | Invoice.participant.extension | RelatedTo | R4B `Invoice.participant.extension` maps as RelatedTo to R5 `Invoice.participant.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Invoice.participant.id | Invoice.participant.id | Equivalent | R4B `Invoice.participant.id` maps as Equivalent to R5 `Invoice.participant.id` |
| Invoice.participant.modifierExtension | Invoice.participant.modifierExtension | RelatedTo | R4B `Invoice.participant.modifierExtension` maps as RelatedTo to R5 `Invoice.participant.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Invoice.participant.role | Invoice.participant.role | Equivalent | R4B `Invoice.participant.role` maps as Equivalent to R5 `Invoice.participant.role` |
| Invoice.paymentTerms | Invoice.paymentTerms | Equivalent | R4B `Invoice.paymentTerms` maps as Equivalent to R5 `Invoice.paymentTerms` |
| Invoice.recipient | Invoice.recipient | Equivalent | R4B `Invoice.recipient` maps as Equivalent to R5 `Invoice.recipient` |
| Invoice.status | Invoice.status | Equivalent | R4B `Invoice.status` maps as Equivalent to R5 `Invoice.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/invoice-status|4.3.0 and http://hl7.org/fhir/ValueSet/invoice-status|5.0.0 (Equivalent) |
| Invoice.subject | Invoice.subject | Equivalent | R4B `Invoice.subject` maps as Equivalent to R5 `Invoice.subject` |
| Invoice.text | Invoice.text | Equivalent | R4B `Invoice.text` maps as Equivalent to R5 `Invoice.text` |
| Invoice.totalGross | Invoice.totalGross | RelatedTo | R4B `Invoice.totalGross` maps as RelatedTo to R5 `Invoice.totalGross` - totalGross has change due to type change: R4B `totalGross` `Money` maps as RelatedTo for R5 `totalGross` |
| Invoice.totalNet | Invoice.totalNet | RelatedTo | R4B `Invoice.totalNet` maps as RelatedTo to R5 `Invoice.totalNet` - totalNet has change due to type change: R4B `totalNet` `Money` maps as RelatedTo for R5 `totalNet` |
| Invoice.totalPriceComponent | Invoice.totalPriceComponent | Equivalent | R4B `Invoice.totalPriceComponent` maps as Equivalent to R5 `Invoice.totalPriceComponent` |
| Invoice.type | Invoice.type | Equivalent | R4B `Invoice.type` maps as Equivalent to R5 `Invoice.type` |

