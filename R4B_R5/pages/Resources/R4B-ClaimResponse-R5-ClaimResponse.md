Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | ClaimResponse |  | This resource provides the adjudication details from the processing of a Claim resource. | 143 | 99 |
| Target | ClaimResponse |  | This resource provides the adjudication details from the processing of a Claim resource. | 187 | 134 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 2 |
Equivalent | 4 |
RelatedTo | 137 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| ClaimResponse | ClaimResponse | Equivalent | R4B `ClaimResponse` maps as Equivalent to R5 `ClaimResponse` |
| ClaimResponse.addItem | ClaimResponse.addItem | Equivalent | R4B `ClaimResponse.addItem` maps as Equivalent to R5 `ClaimResponse.addItem` |
| ClaimResponse.addItem.adjudication | ClaimResponse.addItem.adjudication | Equivalent | R4B `ClaimResponse.addItem.adjudication` maps as Equivalent to R5 `ClaimResponse.addItem.adjudication` |
| ClaimResponse.addItem.bodySite | ClaimResponse.addItem.bodySite | RelatedTo | R4B `ClaimResponse.addItem.bodySite` maps as RelatedTo to R5 `ClaimResponse.addItem.bodySite` - bodySite changed from scalar to array (max cardinality from 1 to *); bodySite removed a binding requirement - Example http://hl7.org/fhir/ValueSet/tooth; bodySite has change due to type change: R4B bodySite CodeableConcept has no equivalent or mapped type in R5 bodySite |
| ClaimResponse.addItem.detail | ClaimResponse.addItem.detail | Equivalent | R4B `ClaimResponse.addItem.detail` maps as Equivalent to R5 `ClaimResponse.addItem.detail` |
| ClaimResponse.addItem.detail.adjudication | ClaimResponse.addItem.detail.adjudication | Equivalent | R4B `ClaimResponse.addItem.detail.adjudication` maps as Equivalent to R5 `ClaimResponse.addItem.detail.adjudication` |
| ClaimResponse.addItem.detail.extension | ClaimResponse.addItem.detail.extension | RelatedTo | R4B `ClaimResponse.addItem.detail.extension` maps as RelatedTo to R5 `ClaimResponse.addItem.detail.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ClaimResponse.addItem.detail.factor | ClaimResponse.addItem.detail.factor | Equivalent | R4B `ClaimResponse.addItem.detail.factor` maps as Equivalent to R5 `ClaimResponse.addItem.detail.factor` |
| ClaimResponse.addItem.detail.id | ClaimResponse.addItem.detail.id | Equivalent | R4B `ClaimResponse.addItem.detail.id` maps as Equivalent to R5 `ClaimResponse.addItem.detail.id` |
| ClaimResponse.addItem.detail.modifier | ClaimResponse.addItem.detail.modifier | Equivalent | R4B `ClaimResponse.addItem.detail.modifier` maps as Equivalent to R5 `ClaimResponse.addItem.detail.modifier` |
| ClaimResponse.addItem.detail.modifierExtension | ClaimResponse.addItem.detail.modifierExtension | RelatedTo | R4B `ClaimResponse.addItem.detail.modifierExtension` maps as RelatedTo to R5 `ClaimResponse.addItem.detail.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ClaimResponse.addItem.detail.net | ClaimResponse.addItem.detail.net | RelatedTo | R4B `ClaimResponse.addItem.detail.net` maps as RelatedTo to R5 `ClaimResponse.addItem.detail.net` - net has change due to type change: R4B `net` `Money` maps as RelatedTo for R5 `net` |
| ClaimResponse.addItem.detail.noteNumber | ClaimResponse.addItem.detail.noteNumber | Equivalent | R4B `ClaimResponse.addItem.detail.noteNumber` maps as Equivalent to R5 `ClaimResponse.addItem.detail.noteNumber` |
| ClaimResponse.addItem.detail.productOrService | ClaimResponse.addItem.detail.productOrService | Equivalent | R4B `ClaimResponse.addItem.detail.productOrService` maps as Equivalent to R5 `ClaimResponse.addItem.detail.productOrService` |
| ClaimResponse.addItem.detail.quantity | ClaimResponse.addItem.detail.quantity | Equivalent | R4B `ClaimResponse.addItem.detail.quantity` maps as Equivalent to R5 `ClaimResponse.addItem.detail.quantity` |
| ClaimResponse.addItem.detail.subDetail | ClaimResponse.addItem.detail.subDetail | Equivalent | R4B `ClaimResponse.addItem.detail.subDetail` maps as Equivalent to R5 `ClaimResponse.addItem.detail.subDetail` |
| ClaimResponse.addItem.detail.subDetail.adjudication | ClaimResponse.addItem.detail.subDetail.adjudication | Equivalent | R4B `ClaimResponse.addItem.detail.subDetail.adjudication` maps as Equivalent to R5 `ClaimResponse.addItem.detail.subDetail.adjudication` |
| ClaimResponse.addItem.detail.subDetail.extension | ClaimResponse.addItem.detail.subDetail.extension | RelatedTo | R4B `ClaimResponse.addItem.detail.subDetail.extension` maps as RelatedTo to R5 `ClaimResponse.addItem.detail.subDetail.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ClaimResponse.addItem.detail.subDetail.factor | ClaimResponse.addItem.detail.subDetail.factor | Equivalent | R4B `ClaimResponse.addItem.detail.subDetail.factor` maps as Equivalent to R5 `ClaimResponse.addItem.detail.subDetail.factor` |
| ClaimResponse.addItem.detail.subDetail.id | ClaimResponse.addItem.detail.subDetail.id | Equivalent | R4B `ClaimResponse.addItem.detail.subDetail.id` maps as Equivalent to R5 `ClaimResponse.addItem.detail.subDetail.id` |
| ClaimResponse.addItem.detail.subDetail.modifier | ClaimResponse.addItem.detail.subDetail.modifier | Equivalent | R4B `ClaimResponse.addItem.detail.subDetail.modifier` maps as Equivalent to R5 `ClaimResponse.addItem.detail.subDetail.modifier` |
| ClaimResponse.addItem.detail.subDetail.modifierExtension | ClaimResponse.addItem.detail.subDetail.modifierExtension | RelatedTo | R4B `ClaimResponse.addItem.detail.subDetail.modifierExtension` maps as RelatedTo to R5 `ClaimResponse.addItem.detail.subDetail.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ClaimResponse.addItem.detail.subDetail.net | ClaimResponse.addItem.detail.subDetail.net | RelatedTo | R4B `ClaimResponse.addItem.detail.subDetail.net` maps as RelatedTo to R5 `ClaimResponse.addItem.detail.subDetail.net` - net has change due to type change: R4B `net` `Money` maps as RelatedTo for R5 `net` |
| ClaimResponse.addItem.detail.subDetail.noteNumber | ClaimResponse.addItem.detail.subDetail.noteNumber | Equivalent | R4B `ClaimResponse.addItem.detail.subDetail.noteNumber` maps as Equivalent to R5 `ClaimResponse.addItem.detail.subDetail.noteNumber` |
| ClaimResponse.addItem.detail.subDetail.productOrService | ClaimResponse.addItem.detail.subDetail.productOrService | Equivalent | R4B `ClaimResponse.addItem.detail.subDetail.productOrService` maps as Equivalent to R5 `ClaimResponse.addItem.detail.subDetail.productOrService` |
| ClaimResponse.addItem.detail.subDetail.quantity | ClaimResponse.addItem.detail.subDetail.quantity | Equivalent | R4B `ClaimResponse.addItem.detail.subDetail.quantity` maps as Equivalent to R5 `ClaimResponse.addItem.detail.subDetail.quantity` |
| ClaimResponse.addItem.detail.subDetail.unitPrice | ClaimResponse.addItem.detail.subDetail.unitPrice | RelatedTo | R4B `ClaimResponse.addItem.detail.subDetail.unitPrice` maps as RelatedTo to R5 `ClaimResponse.addItem.detail.subDetail.unitPrice` - unitPrice has change due to type change: R4B `unitPrice` `Money` maps as RelatedTo for R5 `unitPrice` |
| ClaimResponse.addItem.detail.unitPrice | ClaimResponse.addItem.detail.unitPrice | RelatedTo | R4B `ClaimResponse.addItem.detail.unitPrice` maps as RelatedTo to R5 `ClaimResponse.addItem.detail.unitPrice` - unitPrice has change due to type change: R4B `unitPrice` `Money` maps as RelatedTo for R5 `unitPrice` |
| ClaimResponse.addItem.detailSequence | ClaimResponse.addItem.detailSequence | Equivalent | R4B `ClaimResponse.addItem.detailSequence` maps as Equivalent to R5 `ClaimResponse.addItem.detailSequence` |
| ClaimResponse.addItem.extension | ClaimResponse.addItem.extension | RelatedTo | R4B `ClaimResponse.addItem.extension` maps as RelatedTo to R5 `ClaimResponse.addItem.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ClaimResponse.addItem.factor | ClaimResponse.addItem.factor | Equivalent | R4B `ClaimResponse.addItem.factor` maps as Equivalent to R5 `ClaimResponse.addItem.factor` |
| ClaimResponse.addItem.id | ClaimResponse.addItem.id | Equivalent | R4B `ClaimResponse.addItem.id` maps as Equivalent to R5 `ClaimResponse.addItem.id` |
| ClaimResponse.addItem.itemSequence | ClaimResponse.addItem.itemSequence | Equivalent | R4B `ClaimResponse.addItem.itemSequence` maps as Equivalent to R5 `ClaimResponse.addItem.itemSequence` |
| ClaimResponse.addItem.location[x] | ClaimResponse.addItem.location[x] | Equivalent | R4B `ClaimResponse.addItem.location[x]` maps as Equivalent to R5 `ClaimResponse.addItem.location[x]` |
| ClaimResponse.addItem.modifier | ClaimResponse.addItem.modifier | Equivalent | R4B `ClaimResponse.addItem.modifier` maps as Equivalent to R5 `ClaimResponse.addItem.modifier` |
| ClaimResponse.addItem.modifierExtension | ClaimResponse.addItem.modifierExtension | RelatedTo | R4B `ClaimResponse.addItem.modifierExtension` maps as RelatedTo to R5 `ClaimResponse.addItem.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ClaimResponse.addItem.net | ClaimResponse.addItem.net | RelatedTo | R4B `ClaimResponse.addItem.net` maps as RelatedTo to R5 `ClaimResponse.addItem.net` - net has change due to type change: R4B `net` `Money` maps as RelatedTo for R5 `net` |
| ClaimResponse.addItem.noteNumber | ClaimResponse.addItem.noteNumber | Equivalent | R4B `ClaimResponse.addItem.noteNumber` maps as Equivalent to R5 `ClaimResponse.addItem.noteNumber` |
| ClaimResponse.addItem.productOrService | ClaimResponse.addItem.productOrService | Equivalent | R4B `ClaimResponse.addItem.productOrService` maps as Equivalent to R5 `ClaimResponse.addItem.productOrService` |
| ClaimResponse.addItem.programCode | ClaimResponse.addItem.programCode | Equivalent | R4B `ClaimResponse.addItem.programCode` maps as Equivalent to R5 `ClaimResponse.addItem.programCode` |
| ClaimResponse.addItem.provider | ClaimResponse.addItem.provider | Equivalent | R4B `ClaimResponse.addItem.provider` maps as Equivalent to R5 `ClaimResponse.addItem.provider` |
| ClaimResponse.addItem.quantity | ClaimResponse.addItem.quantity | Equivalent | R4B `ClaimResponse.addItem.quantity` maps as Equivalent to R5 `ClaimResponse.addItem.quantity` |
| ClaimResponse.addItem.serviced[x] | ClaimResponse.addItem.serviced[x] | Equivalent | R4B `ClaimResponse.addItem.serviced[x]` maps as Equivalent to R5 `ClaimResponse.addItem.serviced[x]` |
| ClaimResponse.addItem.subdetailSequence | ClaimResponse.addItem.subdetailSequence | Equivalent | R4B `ClaimResponse.addItem.subdetailSequence` maps as Equivalent to R5 `ClaimResponse.addItem.subdetailSequence` |
| ClaimResponse.addItem.subSite | - | DoesNotExistInTarget | R4B `ClaimResponse.addItem.subSite` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.addItem.unitPrice | ClaimResponse.addItem.unitPrice | RelatedTo | R4B `ClaimResponse.addItem.unitPrice` maps as RelatedTo to R5 `ClaimResponse.addItem.unitPrice` - unitPrice has change due to type change: R4B `unitPrice` `Money` maps as RelatedTo for R5 `unitPrice` |
| ClaimResponse.adjudication | ClaimResponse.adjudication | Equivalent | R4B `ClaimResponse.adjudication` maps as Equivalent to R5 `ClaimResponse.adjudication` |
| ClaimResponse.communicationRequest | ClaimResponse.communicationRequest | Equivalent | R4B `ClaimResponse.communicationRequest` maps as Equivalent to R5 `ClaimResponse.communicationRequest` |
| ClaimResponse.contained | ClaimResponse.contained | Equivalent | R4B `ClaimResponse.contained` maps as Equivalent to R5 `ClaimResponse.contained` |
| ClaimResponse.created | ClaimResponse.created | Equivalent | R4B `ClaimResponse.created` maps as Equivalent to R5 `ClaimResponse.created` |
| ClaimResponse.disposition | ClaimResponse.disposition | Equivalent | R4B `ClaimResponse.disposition` maps as Equivalent to R5 `ClaimResponse.disposition` |
| ClaimResponse.error | ClaimResponse.error | Equivalent | R4B `ClaimResponse.error` maps as Equivalent to R5 `ClaimResponse.error` |
| ClaimResponse.error.code | ClaimResponse.error.code | Equivalent | R4B `ClaimResponse.error.code` maps as Equivalent to R5 `ClaimResponse.error.code` |
| ClaimResponse.error.detailSequence | ClaimResponse.error.detailSequence | Equivalent | R4B `ClaimResponse.error.detailSequence` maps as Equivalent to R5 `ClaimResponse.error.detailSequence` |
| ClaimResponse.error.extension | ClaimResponse.error.extension | RelatedTo | R4B `ClaimResponse.error.extension` maps as RelatedTo to R5 `ClaimResponse.error.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ClaimResponse.error.id | ClaimResponse.error.id | Equivalent | R4B `ClaimResponse.error.id` maps as Equivalent to R5 `ClaimResponse.error.id` |
| ClaimResponse.error.itemSequence | ClaimResponse.error.itemSequence | Equivalent | R4B `ClaimResponse.error.itemSequence` maps as Equivalent to R5 `ClaimResponse.error.itemSequence` |
| ClaimResponse.error.modifierExtension | ClaimResponse.error.modifierExtension | RelatedTo | R4B `ClaimResponse.error.modifierExtension` maps as RelatedTo to R5 `ClaimResponse.error.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ClaimResponse.error.subDetailSequence | ClaimResponse.error.subDetailSequence | Equivalent | R4B `ClaimResponse.error.subDetailSequence` maps as Equivalent to R5 `ClaimResponse.error.subDetailSequence` |
| ClaimResponse.extension | ClaimResponse.extension | RelatedTo | R4B `ClaimResponse.extension` maps as RelatedTo to R5 `ClaimResponse.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ClaimResponse.form | ClaimResponse.form | RelatedTo | R4B `ClaimResponse.form` maps as RelatedTo to R5 `ClaimResponse.form` - form has change due to type change: R4B `form` `Attachment` maps as RelatedTo for R5 `form` |
| ClaimResponse.formCode | ClaimResponse.formCode | Equivalent | R4B `ClaimResponse.formCode` maps as Equivalent to R5 `ClaimResponse.formCode` |
| ClaimResponse.fundsReserve | ClaimResponse.fundsReserve | Equivalent | R4B `ClaimResponse.fundsReserve` maps as Equivalent to R5 `ClaimResponse.fundsReserve` |
| ClaimResponse.id | ClaimResponse.id | Equivalent | R4B `ClaimResponse.id` maps as Equivalent to R5 `ClaimResponse.id` |
| ClaimResponse.identifier | ClaimResponse.identifier | Equivalent | R4B `ClaimResponse.identifier` maps as Equivalent to R5 `ClaimResponse.identifier` |
| ClaimResponse.implicitRules | ClaimResponse.implicitRules | Equivalent | R4B `ClaimResponse.implicitRules` maps as Equivalent to R5 `ClaimResponse.implicitRules` |
| ClaimResponse.insurance | ClaimResponse.insurance | Equivalent | R4B `ClaimResponse.insurance` maps as Equivalent to R5 `ClaimResponse.insurance` |
| ClaimResponse.insurance.businessArrangement | ClaimResponse.insurance.businessArrangement | Equivalent | R4B `ClaimResponse.insurance.businessArrangement` maps as Equivalent to R5 `ClaimResponse.insurance.businessArrangement` |
| ClaimResponse.insurance.claimResponse | ClaimResponse.insurance.claimResponse | Equivalent | R4B `ClaimResponse.insurance.claimResponse` maps as Equivalent to R5 `ClaimResponse.insurance.claimResponse` |
| ClaimResponse.insurance.coverage | ClaimResponse.insurance.coverage | Equivalent | R4B `ClaimResponse.insurance.coverage` maps as Equivalent to R5 `ClaimResponse.insurance.coverage` |
| ClaimResponse.insurance.extension | ClaimResponse.insurance.extension | RelatedTo | R4B `ClaimResponse.insurance.extension` maps as RelatedTo to R5 `ClaimResponse.insurance.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ClaimResponse.insurance.focal | ClaimResponse.insurance.focal | Equivalent | R4B `ClaimResponse.insurance.focal` maps as Equivalent to R5 `ClaimResponse.insurance.focal` |
| ClaimResponse.insurance.id | ClaimResponse.insurance.id | Equivalent | R4B `ClaimResponse.insurance.id` maps as Equivalent to R5 `ClaimResponse.insurance.id` |
| ClaimResponse.insurance.modifierExtension | ClaimResponse.insurance.modifierExtension | RelatedTo | R4B `ClaimResponse.insurance.modifierExtension` maps as RelatedTo to R5 `ClaimResponse.insurance.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ClaimResponse.insurance.sequence | ClaimResponse.insurance.sequence | Equivalent | R4B `ClaimResponse.insurance.sequence` maps as Equivalent to R5 `ClaimResponse.insurance.sequence` |
| ClaimResponse.insurer | ClaimResponse.insurer | Equivalent | R4B `ClaimResponse.insurer` maps as Equivalent to R5 `ClaimResponse.insurer` |
| ClaimResponse.item | ClaimResponse.item | Equivalent | R4B `ClaimResponse.item` maps as Equivalent to R5 `ClaimResponse.item` |
| ClaimResponse.item.adjudication | ClaimResponse.item.adjudication | Equivalent | R4B `ClaimResponse.item.adjudication` maps as Equivalent to R5 `ClaimResponse.item.adjudication` |
| ClaimResponse.item.adjudication.amount | ClaimResponse.item.adjudication.amount | RelatedTo | R4B `ClaimResponse.item.adjudication.amount` maps as RelatedTo to R5 `ClaimResponse.item.adjudication.amount` - amount has change due to type change: R4B `amount` `Money` maps as RelatedTo for R5 `amount` |
| ClaimResponse.item.adjudication.category | ClaimResponse.item.adjudication.category | Equivalent | R4B `ClaimResponse.item.adjudication.category` maps as Equivalent to R5 `ClaimResponse.item.adjudication.category` |
| ClaimResponse.item.adjudication.extension | ClaimResponse.item.adjudication.extension | RelatedTo | R4B `ClaimResponse.item.adjudication.extension` maps as RelatedTo to R5 `ClaimResponse.item.adjudication.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ClaimResponse.item.adjudication.id | ClaimResponse.item.adjudication.id | Equivalent | R4B `ClaimResponse.item.adjudication.id` maps as Equivalent to R5 `ClaimResponse.item.adjudication.id` |
| ClaimResponse.item.adjudication.modifierExtension | ClaimResponse.item.adjudication.modifierExtension | RelatedTo | R4B `ClaimResponse.item.adjudication.modifierExtension` maps as RelatedTo to R5 `ClaimResponse.item.adjudication.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ClaimResponse.item.adjudication.reason | ClaimResponse.item.adjudication.reason | Equivalent | R4B `ClaimResponse.item.adjudication.reason` maps as Equivalent to R5 `ClaimResponse.item.adjudication.reason` |
| ClaimResponse.item.adjudication.value | - | DoesNotExistInTarget | R4B `ClaimResponse.item.adjudication.value` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.item.detail | ClaimResponse.item.detail | Equivalent | R4B `ClaimResponse.item.detail` maps as Equivalent to R5 `ClaimResponse.item.detail` |
| ClaimResponse.item.detail.adjudication | ClaimResponse.item.detail.adjudication | Equivalent | R4B `ClaimResponse.item.detail.adjudication` maps as Equivalent to R5 `ClaimResponse.item.detail.adjudication` |
| ClaimResponse.item.detail.detailSequence | ClaimResponse.item.detail.detailSequence | Equivalent | R4B `ClaimResponse.item.detail.detailSequence` maps as Equivalent to R5 `ClaimResponse.item.detail.detailSequence` |
| ClaimResponse.item.detail.extension | ClaimResponse.item.detail.extension | RelatedTo | R4B `ClaimResponse.item.detail.extension` maps as RelatedTo to R5 `ClaimResponse.item.detail.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ClaimResponse.item.detail.id | ClaimResponse.item.detail.id | Equivalent | R4B `ClaimResponse.item.detail.id` maps as Equivalent to R5 `ClaimResponse.item.detail.id` |
| ClaimResponse.item.detail.modifierExtension | ClaimResponse.item.detail.modifierExtension | RelatedTo | R4B `ClaimResponse.item.detail.modifierExtension` maps as RelatedTo to R5 `ClaimResponse.item.detail.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ClaimResponse.item.detail.noteNumber | ClaimResponse.item.detail.noteNumber | Equivalent | R4B `ClaimResponse.item.detail.noteNumber` maps as Equivalent to R5 `ClaimResponse.item.detail.noteNumber` |
| ClaimResponse.item.detail.subDetail | ClaimResponse.item.detail.subDetail | Equivalent | R4B `ClaimResponse.item.detail.subDetail` maps as Equivalent to R5 `ClaimResponse.item.detail.subDetail` |
| ClaimResponse.item.detail.subDetail.adjudication | ClaimResponse.item.detail.subDetail.adjudication | Equivalent | R4B `ClaimResponse.item.detail.subDetail.adjudication` maps as Equivalent to R5 `ClaimResponse.item.detail.subDetail.adjudication` |
| ClaimResponse.item.detail.subDetail.extension | ClaimResponse.item.detail.subDetail.extension | RelatedTo | R4B `ClaimResponse.item.detail.subDetail.extension` maps as RelatedTo to R5 `ClaimResponse.item.detail.subDetail.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ClaimResponse.item.detail.subDetail.id | ClaimResponse.item.detail.subDetail.id | Equivalent | R4B `ClaimResponse.item.detail.subDetail.id` maps as Equivalent to R5 `ClaimResponse.item.detail.subDetail.id` |
| ClaimResponse.item.detail.subDetail.modifierExtension | ClaimResponse.item.detail.subDetail.modifierExtension | RelatedTo | R4B `ClaimResponse.item.detail.subDetail.modifierExtension` maps as RelatedTo to R5 `ClaimResponse.item.detail.subDetail.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ClaimResponse.item.detail.subDetail.noteNumber | ClaimResponse.item.detail.subDetail.noteNumber | Equivalent | R4B `ClaimResponse.item.detail.subDetail.noteNumber` maps as Equivalent to R5 `ClaimResponse.item.detail.subDetail.noteNumber` |
| ClaimResponse.item.detail.subDetail.subDetailSequence | ClaimResponse.item.detail.subDetail.subDetailSequence | Equivalent | R4B `ClaimResponse.item.detail.subDetail.subDetailSequence` maps as Equivalent to R5 `ClaimResponse.item.detail.subDetail.subDetailSequence` |
| ClaimResponse.item.extension | ClaimResponse.item.extension | RelatedTo | R4B `ClaimResponse.item.extension` maps as RelatedTo to R5 `ClaimResponse.item.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ClaimResponse.item.id | ClaimResponse.item.id | Equivalent | R4B `ClaimResponse.item.id` maps as Equivalent to R5 `ClaimResponse.item.id` |
| ClaimResponse.item.itemSequence | ClaimResponse.item.itemSequence | Equivalent | R4B `ClaimResponse.item.itemSequence` maps as Equivalent to R5 `ClaimResponse.item.itemSequence` |
| ClaimResponse.item.modifierExtension | ClaimResponse.item.modifierExtension | RelatedTo | R4B `ClaimResponse.item.modifierExtension` maps as RelatedTo to R5 `ClaimResponse.item.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ClaimResponse.item.noteNumber | ClaimResponse.item.noteNumber | Equivalent | R4B `ClaimResponse.item.noteNumber` maps as Equivalent to R5 `ClaimResponse.item.noteNumber` |
| ClaimResponse.language | ClaimResponse.language | RelatedTo | R4B `ClaimResponse.language` maps as RelatedTo to R5 `ClaimResponse.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| ClaimResponse.meta | ClaimResponse.meta | Equivalent | R4B `ClaimResponse.meta` maps as Equivalent to R5 `ClaimResponse.meta` |
| ClaimResponse.modifierExtension | ClaimResponse.modifierExtension | RelatedTo | R4B `ClaimResponse.modifierExtension` maps as RelatedTo to R5 `ClaimResponse.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ClaimResponse.outcome | ClaimResponse.outcome | Equivalent | R4B `ClaimResponse.outcome` maps as Equivalent to R5 `ClaimResponse.outcome` - outcome has compatible required binding for code type: http://hl7.org/fhir/ValueSet/remittance-outcome|4.3.0 and http://hl7.org/fhir/ValueSet/claim-outcome|5.0.0 (Equivalent) |
| ClaimResponse.patient | ClaimResponse.patient | Equivalent | R4B `ClaimResponse.patient` maps as Equivalent to R5 `ClaimResponse.patient` |
| ClaimResponse.payeeType | ClaimResponse.payeeType | Equivalent | R4B `ClaimResponse.payeeType` maps as Equivalent to R5 `ClaimResponse.payeeType` |
| ClaimResponse.payment | ClaimResponse.payment | Equivalent | R4B `ClaimResponse.payment` maps as Equivalent to R5 `ClaimResponse.payment` |
| ClaimResponse.payment.adjustment | ClaimResponse.payment.adjustment | RelatedTo | R4B `ClaimResponse.payment.adjustment` maps as RelatedTo to R5 `ClaimResponse.payment.adjustment` - adjustment has change due to type change: R4B `adjustment` `Money` maps as RelatedTo for R5 `adjustment` |
| ClaimResponse.payment.adjustmentReason | ClaimResponse.payment.adjustmentReason | Equivalent | R4B `ClaimResponse.payment.adjustmentReason` maps as Equivalent to R5 `ClaimResponse.payment.adjustmentReason` |
| ClaimResponse.payment.amount | ClaimResponse.payment.amount | RelatedTo | R4B `ClaimResponse.payment.amount` maps as RelatedTo to R5 `ClaimResponse.payment.amount` - amount has change due to type change: R4B `amount` `Money` maps as RelatedTo for R5 `amount` |
| ClaimResponse.payment.date | ClaimResponse.payment.date | Equivalent | R4B `ClaimResponse.payment.date` maps as Equivalent to R5 `ClaimResponse.payment.date` |
| ClaimResponse.payment.extension | ClaimResponse.payment.extension | RelatedTo | R4B `ClaimResponse.payment.extension` maps as RelatedTo to R5 `ClaimResponse.payment.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ClaimResponse.payment.id | ClaimResponse.payment.id | Equivalent | R4B `ClaimResponse.payment.id` maps as Equivalent to R5 `ClaimResponse.payment.id` |
| ClaimResponse.payment.identifier | ClaimResponse.payment.identifier | Equivalent | R4B `ClaimResponse.payment.identifier` maps as Equivalent to R5 `ClaimResponse.payment.identifier` |
| ClaimResponse.payment.modifierExtension | ClaimResponse.payment.modifierExtension | RelatedTo | R4B `ClaimResponse.payment.modifierExtension` maps as RelatedTo to R5 `ClaimResponse.payment.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ClaimResponse.payment.type | ClaimResponse.payment.type | Equivalent | R4B `ClaimResponse.payment.type` maps as Equivalent to R5 `ClaimResponse.payment.type` |
| ClaimResponse.preAuthPeriod | ClaimResponse.preAuthPeriod | Equivalent | R4B `ClaimResponse.preAuthPeriod` maps as Equivalent to R5 `ClaimResponse.preAuthPeriod` |
| ClaimResponse.preAuthRef | ClaimResponse.preAuthRef | Equivalent | R4B `ClaimResponse.preAuthRef` maps as Equivalent to R5 `ClaimResponse.preAuthRef` |
| ClaimResponse.processNote | ClaimResponse.processNote | Equivalent | R4B `ClaimResponse.processNote` maps as Equivalent to R5 `ClaimResponse.processNote` |
| ClaimResponse.processNote.extension | ClaimResponse.processNote.extension | RelatedTo | R4B `ClaimResponse.processNote.extension` maps as RelatedTo to R5 `ClaimResponse.processNote.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ClaimResponse.processNote.id | ClaimResponse.processNote.id | Equivalent | R4B `ClaimResponse.processNote.id` maps as Equivalent to R5 `ClaimResponse.processNote.id` |
| ClaimResponse.processNote.language | ClaimResponse.processNote.language | RelatedTo | R4B `ClaimResponse.processNote.language` maps as RelatedTo to R5 `ClaimResponse.processNote.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| ClaimResponse.processNote.modifierExtension | ClaimResponse.processNote.modifierExtension | RelatedTo | R4B `ClaimResponse.processNote.modifierExtension` maps as RelatedTo to R5 `ClaimResponse.processNote.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ClaimResponse.processNote.number | ClaimResponse.processNote.number | Equivalent | R4B `ClaimResponse.processNote.number` maps as Equivalent to R5 `ClaimResponse.processNote.number` |
| ClaimResponse.processNote.text | ClaimResponse.processNote.text | Equivalent | R4B `ClaimResponse.processNote.text` maps as Equivalent to R5 `ClaimResponse.processNote.text` |
| ClaimResponse.processNote.type | ClaimResponse.processNote.type | RelatedTo | R4B `ClaimResponse.processNote.type` maps as RelatedTo to R5 `ClaimResponse.processNote.type` - type changed the binding strength from Required to Extensible; type has change due to type change: R4B type code has no equivalent or mapped type in R5 type |
| ClaimResponse.request | ClaimResponse.request | Equivalent | R4B `ClaimResponse.request` maps as Equivalent to R5 `ClaimResponse.request` |
| ClaimResponse.requestor | ClaimResponse.requestor | Equivalent | R4B `ClaimResponse.requestor` maps as Equivalent to R5 `ClaimResponse.requestor` |
| ClaimResponse.status | ClaimResponse.status | Equivalent | R4B `ClaimResponse.status` maps as Equivalent to R5 `ClaimResponse.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/fm-status|4.3.0 and http://hl7.org/fhir/ValueSet/fm-status|5.0.0 (Equivalent) |
| ClaimResponse.subType | ClaimResponse.subType | Equivalent | R4B `ClaimResponse.subType` maps as Equivalent to R5 `ClaimResponse.subType` |
| ClaimResponse.text | ClaimResponse.text | Equivalent | R4B `ClaimResponse.text` maps as Equivalent to R5 `ClaimResponse.text` |
| ClaimResponse.total | ClaimResponse.total | Equivalent | R4B `ClaimResponse.total` maps as Equivalent to R5 `ClaimResponse.total` |
| ClaimResponse.total.amount | ClaimResponse.total.amount | RelatedTo | R4B `ClaimResponse.total.amount` maps as RelatedTo to R5 `ClaimResponse.total.amount` - amount has change due to type change: R4B `amount` `Money` maps as RelatedTo for R5 `amount` |
| ClaimResponse.total.category | ClaimResponse.total.category | Equivalent | R4B `ClaimResponse.total.category` maps as Equivalent to R5 `ClaimResponse.total.category` |
| ClaimResponse.total.extension | ClaimResponse.total.extension | RelatedTo | R4B `ClaimResponse.total.extension` maps as RelatedTo to R5 `ClaimResponse.total.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ClaimResponse.total.id | ClaimResponse.total.id | Equivalent | R4B `ClaimResponse.total.id` maps as Equivalent to R5 `ClaimResponse.total.id` |
| ClaimResponse.total.modifierExtension | ClaimResponse.total.modifierExtension | RelatedTo | R4B `ClaimResponse.total.modifierExtension` maps as RelatedTo to R5 `ClaimResponse.total.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ClaimResponse.type | ClaimResponse.type | Equivalent | R4B `ClaimResponse.type` maps as Equivalent to R5 `ClaimResponse.type` |
| ClaimResponse.use | ClaimResponse.use | Equivalent | R4B `ClaimResponse.use` maps as Equivalent to R5 `ClaimResponse.use` - use has compatible required binding for code type: http://hl7.org/fhir/ValueSet/claim-use|4.3.0 and http://hl7.org/fhir/ValueSet/claim-use|5.0.0 (Equivalent) |

