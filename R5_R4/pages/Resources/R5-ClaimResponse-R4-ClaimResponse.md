Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | ClaimResponse |  | This resource provides the adjudication details from the processing of a Claim resource. | 187 | 134 |
| Target | ClaimResponse |  | This resource provides the adjudication details from the processing of a Claim resource. | 143 | 99 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 45 |
Equivalent | 101 |
RelatedTo | 11 |
SourceIsBroaderThanTarget | 28 |
SourceIsNarrowerThanTarget | 2 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| ClaimResponse | ClaimResponse | Equivalent | R5 `ClaimResponse` maps as Equivalent to R4 `ClaimResponse` |
| ClaimResponse.addItem | ClaimResponse.addItem | Equivalent | R5 `ClaimResponse.addItem` maps as Equivalent to R4 `ClaimResponse.addItem` |
| ClaimResponse.addItem.adjudication | ClaimResponse.addItem.adjudication | RelatedTo | R5 `ClaimResponse.addItem.adjudication` maps as RelatedTo to R4 `ClaimResponse.addItem.adjudication` - adjudication made the element mandatory; adjudication increased the minimum cardinality from 0 to 1 |
| ClaimResponse.addItem.bodySite | ClaimResponse.addItem.bodySite | SourceIsBroaderThanTarget | R5 `ClaimResponse.addItem.bodySite` maps as SourceIsBroaderThanTarget to R4 `ClaimResponse.addItem.bodySite` - bodySite changed from array to scalar (max cardinality from * to 1); bodySite added a binding requirement - Example http://hl7.org/fhir/ValueSet/tooth; bodySite has change due to type change: R5 bodySite BackboneElement has no equivalent or mapped type in R4 bodySite |
| ClaimResponse.addItem.bodySite.extension | - | DoesNotExistInTarget | R5 `ClaimResponse.addItem.bodySite.extension` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.addItem.bodySite.id | - | DoesNotExistInTarget | R5 `ClaimResponse.addItem.bodySite.id` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.addItem.bodySite.modifierExtension | - | DoesNotExistInTarget | R5 `ClaimResponse.addItem.bodySite.modifierExtension` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.addItem.bodySite.site | - | DoesNotExistInTarget | R5 `ClaimResponse.addItem.bodySite.site` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.addItem.bodySite.subSite | - | DoesNotExistInTarget | R5 `ClaimResponse.addItem.bodySite.subSite` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.addItem.detail | ClaimResponse.addItem.detail | Equivalent | R5 `ClaimResponse.addItem.detail` maps as Equivalent to R4 `ClaimResponse.addItem.detail` |
| ClaimResponse.addItem.detail.adjudication | ClaimResponse.addItem.detail.adjudication | RelatedTo | R5 `ClaimResponse.addItem.detail.adjudication` maps as RelatedTo to R4 `ClaimResponse.addItem.detail.adjudication` - adjudication made the element mandatory; adjudication increased the minimum cardinality from 0 to 1 |
| ClaimResponse.addItem.detail.extension | ClaimResponse.addItem.detail.extension | SourceIsBroaderThanTarget | R5 `ClaimResponse.addItem.detail.extension` maps as SourceIsBroaderThanTarget to R4 `ClaimResponse.addItem.detail.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ClaimResponse.addItem.detail.factor | ClaimResponse.addItem.detail.factor | Equivalent | R5 `ClaimResponse.addItem.detail.factor` maps as Equivalent to R4 `ClaimResponse.addItem.detail.factor` |
| ClaimResponse.addItem.detail.id | ClaimResponse.addItem.detail.id | Equivalent | R5 `ClaimResponse.addItem.detail.id` maps as Equivalent to R4 `ClaimResponse.addItem.detail.id` |
| ClaimResponse.addItem.detail.modifier | ClaimResponse.addItem.detail.modifier | Equivalent | R5 `ClaimResponse.addItem.detail.modifier` maps as Equivalent to R4 `ClaimResponse.addItem.detail.modifier` |
| ClaimResponse.addItem.detail.modifierExtension | ClaimResponse.addItem.detail.modifierExtension | SourceIsBroaderThanTarget | R5 `ClaimResponse.addItem.detail.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ClaimResponse.addItem.detail.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ClaimResponse.addItem.detail.net | ClaimResponse.addItem.detail.net | Equivalent | R5 `ClaimResponse.addItem.detail.net` maps as Equivalent to R4 `ClaimResponse.addItem.detail.net` |
| ClaimResponse.addItem.detail.noteNumber | ClaimResponse.addItem.detail.noteNumber | Equivalent | R5 `ClaimResponse.addItem.detail.noteNumber` maps as Equivalent to R4 `ClaimResponse.addItem.detail.noteNumber` |
| ClaimResponse.addItem.detail.productOrService | ClaimResponse.addItem.detail.productOrService | RelatedTo | R5 `ClaimResponse.addItem.detail.productOrService` maps as RelatedTo to R4 `ClaimResponse.addItem.detail.productOrService` - productOrService made the element mandatory; productOrService increased the minimum cardinality from 0 to 1 |
| ClaimResponse.addItem.detail.productOrServiceEnd | - | DoesNotExistInTarget | R5 `ClaimResponse.addItem.detail.productOrServiceEnd` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.addItem.detail.quantity | ClaimResponse.addItem.detail.quantity | Equivalent | R5 `ClaimResponse.addItem.detail.quantity` maps as Equivalent to R4 `ClaimResponse.addItem.detail.quantity` |
| ClaimResponse.addItem.detail.revenue | - | DoesNotExistInTarget | R5 `ClaimResponse.addItem.detail.revenue` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.addItem.detail.reviewOutcome | - | DoesNotExistInTarget | R5 `ClaimResponse.addItem.detail.reviewOutcome` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.addItem.detail.subDetail | ClaimResponse.addItem.detail.subDetail | Equivalent | R5 `ClaimResponse.addItem.detail.subDetail` maps as Equivalent to R4 `ClaimResponse.addItem.detail.subDetail` |
| ClaimResponse.addItem.detail.subDetail.adjudication | ClaimResponse.addItem.detail.subDetail.adjudication | RelatedTo | R5 `ClaimResponse.addItem.detail.subDetail.adjudication` maps as RelatedTo to R4 `ClaimResponse.addItem.detail.subDetail.adjudication` - adjudication made the element mandatory; adjudication increased the minimum cardinality from 0 to 1 |
| ClaimResponse.addItem.detail.subDetail.extension | ClaimResponse.addItem.detail.subDetail.extension | SourceIsBroaderThanTarget | R5 `ClaimResponse.addItem.detail.subDetail.extension` maps as SourceIsBroaderThanTarget to R4 `ClaimResponse.addItem.detail.subDetail.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ClaimResponse.addItem.detail.subDetail.factor | ClaimResponse.addItem.detail.subDetail.factor | Equivalent | R5 `ClaimResponse.addItem.detail.subDetail.factor` maps as Equivalent to R4 `ClaimResponse.addItem.detail.subDetail.factor` |
| ClaimResponse.addItem.detail.subDetail.id | ClaimResponse.addItem.detail.subDetail.id | Equivalent | R5 `ClaimResponse.addItem.detail.subDetail.id` maps as Equivalent to R4 `ClaimResponse.addItem.detail.subDetail.id` |
| ClaimResponse.addItem.detail.subDetail.modifier | ClaimResponse.addItem.detail.subDetail.modifier | Equivalent | R5 `ClaimResponse.addItem.detail.subDetail.modifier` maps as Equivalent to R4 `ClaimResponse.addItem.detail.subDetail.modifier` |
| ClaimResponse.addItem.detail.subDetail.modifierExtension | ClaimResponse.addItem.detail.subDetail.modifierExtension | SourceIsBroaderThanTarget | R5 `ClaimResponse.addItem.detail.subDetail.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ClaimResponse.addItem.detail.subDetail.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ClaimResponse.addItem.detail.subDetail.net | ClaimResponse.addItem.detail.subDetail.net | Equivalent | R5 `ClaimResponse.addItem.detail.subDetail.net` maps as Equivalent to R4 `ClaimResponse.addItem.detail.subDetail.net` |
| ClaimResponse.addItem.detail.subDetail.noteNumber | ClaimResponse.addItem.detail.subDetail.noteNumber | Equivalent | R5 `ClaimResponse.addItem.detail.subDetail.noteNumber` maps as Equivalent to R4 `ClaimResponse.addItem.detail.subDetail.noteNumber` |
| ClaimResponse.addItem.detail.subDetail.productOrService | ClaimResponse.addItem.detail.subDetail.productOrService | RelatedTo | R5 `ClaimResponse.addItem.detail.subDetail.productOrService` maps as RelatedTo to R4 `ClaimResponse.addItem.detail.subDetail.productOrService` - productOrService made the element mandatory; productOrService increased the minimum cardinality from 0 to 1 |
| ClaimResponse.addItem.detail.subDetail.productOrServiceEnd | - | DoesNotExistInTarget | R5 `ClaimResponse.addItem.detail.subDetail.productOrServiceEnd` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.addItem.detail.subDetail.quantity | ClaimResponse.addItem.detail.subDetail.quantity | Equivalent | R5 `ClaimResponse.addItem.detail.subDetail.quantity` maps as Equivalent to R4 `ClaimResponse.addItem.detail.subDetail.quantity` |
| ClaimResponse.addItem.detail.subDetail.revenue | - | DoesNotExistInTarget | R5 `ClaimResponse.addItem.detail.subDetail.revenue` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.addItem.detail.subDetail.reviewOutcome | - | DoesNotExistInTarget | R5 `ClaimResponse.addItem.detail.subDetail.reviewOutcome` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.addItem.detail.subDetail.tax | - | DoesNotExistInTarget | R5 `ClaimResponse.addItem.detail.subDetail.tax` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.addItem.detail.subDetail.traceNumber | - | DoesNotExistInTarget | R5 `ClaimResponse.addItem.detail.subDetail.traceNumber` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.addItem.detail.subDetail.unitPrice | ClaimResponse.addItem.detail.subDetail.unitPrice | Equivalent | R5 `ClaimResponse.addItem.detail.subDetail.unitPrice` maps as Equivalent to R4 `ClaimResponse.addItem.detail.subDetail.unitPrice` |
| ClaimResponse.addItem.detail.tax | - | DoesNotExistInTarget | R5 `ClaimResponse.addItem.detail.tax` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.addItem.detail.traceNumber | - | DoesNotExistInTarget | R5 `ClaimResponse.addItem.detail.traceNumber` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.addItem.detail.unitPrice | ClaimResponse.addItem.detail.unitPrice | Equivalent | R5 `ClaimResponse.addItem.detail.unitPrice` maps as Equivalent to R4 `ClaimResponse.addItem.detail.unitPrice` |
| ClaimResponse.addItem.detailSequence | ClaimResponse.addItem.detailSequence | Equivalent | R5 `ClaimResponse.addItem.detailSequence` maps as Equivalent to R4 `ClaimResponse.addItem.detailSequence` |
| ClaimResponse.addItem.extension | ClaimResponse.addItem.extension | SourceIsBroaderThanTarget | R5 `ClaimResponse.addItem.extension` maps as SourceIsBroaderThanTarget to R4 `ClaimResponse.addItem.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ClaimResponse.addItem.factor | ClaimResponse.addItem.factor | Equivalent | R5 `ClaimResponse.addItem.factor` maps as Equivalent to R4 `ClaimResponse.addItem.factor` |
| ClaimResponse.addItem.id | ClaimResponse.addItem.id | Equivalent | R5 `ClaimResponse.addItem.id` maps as Equivalent to R4 `ClaimResponse.addItem.id` |
| ClaimResponse.addItem.itemSequence | ClaimResponse.addItem.itemSequence | Equivalent | R5 `ClaimResponse.addItem.itemSequence` maps as Equivalent to R4 `ClaimResponse.addItem.itemSequence` |
| ClaimResponse.addItem.location[x] | ClaimResponse.addItem.location[x] | Equivalent | R5 `ClaimResponse.addItem.location[x]` maps as Equivalent to R4 `ClaimResponse.addItem.location[x]` |
| ClaimResponse.addItem.modifier | ClaimResponse.addItem.modifier | Equivalent | R5 `ClaimResponse.addItem.modifier` maps as Equivalent to R4 `ClaimResponse.addItem.modifier` |
| ClaimResponse.addItem.modifierExtension | ClaimResponse.addItem.modifierExtension | SourceIsBroaderThanTarget | R5 `ClaimResponse.addItem.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ClaimResponse.addItem.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ClaimResponse.addItem.net | ClaimResponse.addItem.net | Equivalent | R5 `ClaimResponse.addItem.net` maps as Equivalent to R4 `ClaimResponse.addItem.net` |
| ClaimResponse.addItem.noteNumber | ClaimResponse.addItem.noteNumber | Equivalent | R5 `ClaimResponse.addItem.noteNumber` maps as Equivalent to R4 `ClaimResponse.addItem.noteNumber` |
| ClaimResponse.addItem.productOrService | ClaimResponse.addItem.productOrService | RelatedTo | R5 `ClaimResponse.addItem.productOrService` maps as RelatedTo to R4 `ClaimResponse.addItem.productOrService` - productOrService made the element mandatory; productOrService increased the minimum cardinality from 0 to 1 |
| ClaimResponse.addItem.productOrServiceEnd | - | DoesNotExistInTarget | R5 `ClaimResponse.addItem.productOrServiceEnd` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.addItem.programCode | ClaimResponse.addItem.programCode | Equivalent | R5 `ClaimResponse.addItem.programCode` maps as Equivalent to R4 `ClaimResponse.addItem.programCode` |
| ClaimResponse.addItem.provider | ClaimResponse.addItem.provider | Equivalent | R5 `ClaimResponse.addItem.provider` maps as Equivalent to R4 `ClaimResponse.addItem.provider` |
| ClaimResponse.addItem.quantity | ClaimResponse.addItem.quantity | Equivalent | R5 `ClaimResponse.addItem.quantity` maps as Equivalent to R4 `ClaimResponse.addItem.quantity` |
| ClaimResponse.addItem.request | - | DoesNotExistInTarget | R5 `ClaimResponse.addItem.request` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.addItem.revenue | - | DoesNotExistInTarget | R5 `ClaimResponse.addItem.revenue` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.addItem.reviewOutcome | - | DoesNotExistInTarget | R5 `ClaimResponse.addItem.reviewOutcome` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.addItem.serviced[x] | ClaimResponse.addItem.serviced[x] | Equivalent | R5 `ClaimResponse.addItem.serviced[x]` maps as Equivalent to R4 `ClaimResponse.addItem.serviced[x]` |
| ClaimResponse.addItem.subdetailSequence | ClaimResponse.addItem.subdetailSequence | Equivalent | R5 `ClaimResponse.addItem.subdetailSequence` maps as Equivalent to R4 `ClaimResponse.addItem.subdetailSequence` |
| ClaimResponse.addItem.tax | - | DoesNotExistInTarget | R5 `ClaimResponse.addItem.tax` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.addItem.traceNumber | - | DoesNotExistInTarget | R5 `ClaimResponse.addItem.traceNumber` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.addItem.unitPrice | ClaimResponse.addItem.unitPrice | Equivalent | R5 `ClaimResponse.addItem.unitPrice` maps as Equivalent to R4 `ClaimResponse.addItem.unitPrice` |
| ClaimResponse.adjudication | ClaimResponse.adjudication | Equivalent | R5 `ClaimResponse.adjudication` maps as Equivalent to R4 `ClaimResponse.adjudication` |
| ClaimResponse.communicationRequest | ClaimResponse.communicationRequest | Equivalent | R5 `ClaimResponse.communicationRequest` maps as Equivalent to R4 `ClaimResponse.communicationRequest` |
| ClaimResponse.contained | ClaimResponse.contained | Equivalent | R5 `ClaimResponse.contained` maps as Equivalent to R4 `ClaimResponse.contained` |
| ClaimResponse.created | ClaimResponse.created | Equivalent | R5 `ClaimResponse.created` maps as Equivalent to R4 `ClaimResponse.created` |
| ClaimResponse.decision | - | DoesNotExistInTarget | R5 `ClaimResponse.decision` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.diagnosisRelatedGroup | - | DoesNotExistInTarget | R5 `ClaimResponse.diagnosisRelatedGroup` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.disposition | ClaimResponse.disposition | Equivalent | R5 `ClaimResponse.disposition` maps as Equivalent to R4 `ClaimResponse.disposition` |
| ClaimResponse.encounter | - | DoesNotExistInTarget | R5 `ClaimResponse.encounter` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.error | ClaimResponse.error | Equivalent | R5 `ClaimResponse.error` maps as Equivalent to R4 `ClaimResponse.error` |
| ClaimResponse.error.code | ClaimResponse.error.code | Equivalent | R5 `ClaimResponse.error.code` maps as Equivalent to R4 `ClaimResponse.error.code` |
| ClaimResponse.error.detailSequence | ClaimResponse.error.detailSequence | Equivalent | R5 `ClaimResponse.error.detailSequence` maps as Equivalent to R4 `ClaimResponse.error.detailSequence` |
| ClaimResponse.error.expression | - | DoesNotExistInTarget | R5 `ClaimResponse.error.expression` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.error.extension | ClaimResponse.error.extension | SourceIsBroaderThanTarget | R5 `ClaimResponse.error.extension` maps as SourceIsBroaderThanTarget to R4 `ClaimResponse.error.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ClaimResponse.error.id | ClaimResponse.error.id | Equivalent | R5 `ClaimResponse.error.id` maps as Equivalent to R4 `ClaimResponse.error.id` |
| ClaimResponse.error.itemSequence | ClaimResponse.error.itemSequence | Equivalent | R5 `ClaimResponse.error.itemSequence` maps as Equivalent to R4 `ClaimResponse.error.itemSequence` |
| ClaimResponse.error.modifierExtension | ClaimResponse.error.modifierExtension | SourceIsBroaderThanTarget | R5 `ClaimResponse.error.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ClaimResponse.error.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ClaimResponse.error.subDetailSequence | ClaimResponse.error.subDetailSequence | Equivalent | R5 `ClaimResponse.error.subDetailSequence` maps as Equivalent to R4 `ClaimResponse.error.subDetailSequence` |
| ClaimResponse.event | - | DoesNotExistInTarget | R5 `ClaimResponse.event` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.event.extension | - | DoesNotExistInTarget | R5 `ClaimResponse.event.extension` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.event.id | - | DoesNotExistInTarget | R5 `ClaimResponse.event.id` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.event.modifierExtension | - | DoesNotExistInTarget | R5 `ClaimResponse.event.modifierExtension` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.event.type | - | DoesNotExistInTarget | R5 `ClaimResponse.event.type` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.event.when[x] | - | DoesNotExistInTarget | R5 `ClaimResponse.event.when[x]` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.extension | ClaimResponse.extension | SourceIsBroaderThanTarget | R5 `ClaimResponse.extension` maps as SourceIsBroaderThanTarget to R4 `ClaimResponse.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ClaimResponse.form | ClaimResponse.form | RelatedTo | R5 `ClaimResponse.form` maps as RelatedTo to R4 `ClaimResponse.form` - form has change due to type change: R5 `form` `Attachment` maps as RelatedTo for R4 `form` |
| ClaimResponse.formCode | ClaimResponse.formCode | Equivalent | R5 `ClaimResponse.formCode` maps as Equivalent to R4 `ClaimResponse.formCode` |
| ClaimResponse.fundsReserve | ClaimResponse.fundsReserve | Equivalent | R5 `ClaimResponse.fundsReserve` maps as Equivalent to R4 `ClaimResponse.fundsReserve` |
| ClaimResponse.id | ClaimResponse.id | Equivalent | R5 `ClaimResponse.id` maps as Equivalent to R4 `ClaimResponse.id` |
| ClaimResponse.identifier | ClaimResponse.identifier | Equivalent | R5 `ClaimResponse.identifier` maps as Equivalent to R4 `ClaimResponse.identifier` |
| ClaimResponse.implicitRules | ClaimResponse.implicitRules | Equivalent | R5 `ClaimResponse.implicitRules` maps as Equivalent to R4 `ClaimResponse.implicitRules` |
| ClaimResponse.insurance | ClaimResponse.insurance | Equivalent | R5 `ClaimResponse.insurance` maps as Equivalent to R4 `ClaimResponse.insurance` |
| ClaimResponse.insurance.businessArrangement | ClaimResponse.insurance.businessArrangement | Equivalent | R5 `ClaimResponse.insurance.businessArrangement` maps as Equivalent to R4 `ClaimResponse.insurance.businessArrangement` |
| ClaimResponse.insurance.claimResponse | ClaimResponse.insurance.claimResponse | Equivalent | R5 `ClaimResponse.insurance.claimResponse` maps as Equivalent to R4 `ClaimResponse.insurance.claimResponse` |
| ClaimResponse.insurance.coverage | ClaimResponse.insurance.coverage | Equivalent | R5 `ClaimResponse.insurance.coverage` maps as Equivalent to R4 `ClaimResponse.insurance.coverage` |
| ClaimResponse.insurance.extension | ClaimResponse.insurance.extension | SourceIsBroaderThanTarget | R5 `ClaimResponse.insurance.extension` maps as SourceIsBroaderThanTarget to R4 `ClaimResponse.insurance.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ClaimResponse.insurance.focal | ClaimResponse.insurance.focal | Equivalent | R5 `ClaimResponse.insurance.focal` maps as Equivalent to R4 `ClaimResponse.insurance.focal` |
| ClaimResponse.insurance.id | ClaimResponse.insurance.id | Equivalent | R5 `ClaimResponse.insurance.id` maps as Equivalent to R4 `ClaimResponse.insurance.id` |
| ClaimResponse.insurance.modifierExtension | ClaimResponse.insurance.modifierExtension | SourceIsBroaderThanTarget | R5 `ClaimResponse.insurance.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ClaimResponse.insurance.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ClaimResponse.insurance.sequence | ClaimResponse.insurance.sequence | Equivalent | R5 `ClaimResponse.insurance.sequence` maps as Equivalent to R4 `ClaimResponse.insurance.sequence` |
| ClaimResponse.insurer | ClaimResponse.insurer | RelatedTo | R5 `ClaimResponse.insurer` maps as RelatedTo to R4 `ClaimResponse.insurer` - insurer made the element mandatory; insurer increased the minimum cardinality from 0 to 1 |
| ClaimResponse.item | ClaimResponse.item | Equivalent | R5 `ClaimResponse.item` maps as Equivalent to R4 `ClaimResponse.item` |
| ClaimResponse.item.adjudication | ClaimResponse.item.adjudication | RelatedTo | R5 `ClaimResponse.item.adjudication` maps as RelatedTo to R4 `ClaimResponse.item.adjudication` - adjudication made the element mandatory; adjudication increased the minimum cardinality from 0 to 1 |
| ClaimResponse.item.adjudication.amount | ClaimResponse.item.adjudication.amount | Equivalent | R5 `ClaimResponse.item.adjudication.amount` maps as Equivalent to R4 `ClaimResponse.item.adjudication.amount` |
| ClaimResponse.item.adjudication.category | ClaimResponse.item.adjudication.category | Equivalent | R5 `ClaimResponse.item.adjudication.category` maps as Equivalent to R4 `ClaimResponse.item.adjudication.category` |
| ClaimResponse.item.adjudication.extension | ClaimResponse.item.adjudication.extension | SourceIsBroaderThanTarget | R5 `ClaimResponse.item.adjudication.extension` maps as SourceIsBroaderThanTarget to R4 `ClaimResponse.item.adjudication.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ClaimResponse.item.adjudication.id | ClaimResponse.item.adjudication.id | Equivalent | R5 `ClaimResponse.item.adjudication.id` maps as Equivalent to R4 `ClaimResponse.item.adjudication.id` |
| ClaimResponse.item.adjudication.modifierExtension | ClaimResponse.item.adjudication.modifierExtension | SourceIsBroaderThanTarget | R5 `ClaimResponse.item.adjudication.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ClaimResponse.item.adjudication.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ClaimResponse.item.adjudication.quantity | ClaimResponse.item.adjudication.value | SourceIsBroaderThanTarget | R5 `ClaimResponse.item.adjudication.quantity` maps as SourceIsBroaderThanTarget to R4 `ClaimResponse.item.adjudication.value` - value has change due to type change: R5 quantity Quantity has no equivalent or mapped type in R4 value |
| ClaimResponse.item.adjudication.reason | ClaimResponse.item.adjudication.reason | Equivalent | R5 `ClaimResponse.item.adjudication.reason` maps as Equivalent to R4 `ClaimResponse.item.adjudication.reason` |
| ClaimResponse.item.detail | ClaimResponse.item.detail | Equivalent | R5 `ClaimResponse.item.detail` maps as Equivalent to R4 `ClaimResponse.item.detail` |
| ClaimResponse.item.detail.adjudication | ClaimResponse.item.detail.adjudication | RelatedTo | R5 `ClaimResponse.item.detail.adjudication` maps as RelatedTo to R4 `ClaimResponse.item.detail.adjudication` - adjudication made the element mandatory; adjudication increased the minimum cardinality from 0 to 1 |
| ClaimResponse.item.detail.detailSequence | ClaimResponse.item.detail.detailSequence | Equivalent | R5 `ClaimResponse.item.detail.detailSequence` maps as Equivalent to R4 `ClaimResponse.item.detail.detailSequence` |
| ClaimResponse.item.detail.extension | ClaimResponse.item.detail.extension | SourceIsBroaderThanTarget | R5 `ClaimResponse.item.detail.extension` maps as SourceIsBroaderThanTarget to R4 `ClaimResponse.item.detail.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ClaimResponse.item.detail.id | ClaimResponse.item.detail.id | Equivalent | R5 `ClaimResponse.item.detail.id` maps as Equivalent to R4 `ClaimResponse.item.detail.id` |
| ClaimResponse.item.detail.modifierExtension | ClaimResponse.item.detail.modifierExtension | SourceIsBroaderThanTarget | R5 `ClaimResponse.item.detail.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ClaimResponse.item.detail.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ClaimResponse.item.detail.noteNumber | ClaimResponse.item.detail.noteNumber | Equivalent | R5 `ClaimResponse.item.detail.noteNumber` maps as Equivalent to R4 `ClaimResponse.item.detail.noteNumber` |
| ClaimResponse.item.detail.reviewOutcome | - | DoesNotExistInTarget | R5 `ClaimResponse.item.detail.reviewOutcome` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.item.detail.subDetail | ClaimResponse.item.detail.subDetail | Equivalent | R5 `ClaimResponse.item.detail.subDetail` maps as Equivalent to R4 `ClaimResponse.item.detail.subDetail` |
| ClaimResponse.item.detail.subDetail.adjudication | ClaimResponse.item.detail.subDetail.adjudication | Equivalent | R5 `ClaimResponse.item.detail.subDetail.adjudication` maps as Equivalent to R4 `ClaimResponse.item.detail.subDetail.adjudication` |
| ClaimResponse.item.detail.subDetail.extension | ClaimResponse.item.detail.subDetail.extension | SourceIsBroaderThanTarget | R5 `ClaimResponse.item.detail.subDetail.extension` maps as SourceIsBroaderThanTarget to R4 `ClaimResponse.item.detail.subDetail.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ClaimResponse.item.detail.subDetail.id | ClaimResponse.item.detail.subDetail.id | Equivalent | R5 `ClaimResponse.item.detail.subDetail.id` maps as Equivalent to R4 `ClaimResponse.item.detail.subDetail.id` |
| ClaimResponse.item.detail.subDetail.modifierExtension | ClaimResponse.item.detail.subDetail.modifierExtension | SourceIsBroaderThanTarget | R5 `ClaimResponse.item.detail.subDetail.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ClaimResponse.item.detail.subDetail.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ClaimResponse.item.detail.subDetail.noteNumber | ClaimResponse.item.detail.subDetail.noteNumber | Equivalent | R5 `ClaimResponse.item.detail.subDetail.noteNumber` maps as Equivalent to R4 `ClaimResponse.item.detail.subDetail.noteNumber` |
| ClaimResponse.item.detail.subDetail.reviewOutcome | - | DoesNotExistInTarget | R5 `ClaimResponse.item.detail.subDetail.reviewOutcome` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.item.detail.subDetail.subDetailSequence | ClaimResponse.item.detail.subDetail.subDetailSequence | Equivalent | R5 `ClaimResponse.item.detail.subDetail.subDetailSequence` maps as Equivalent to R4 `ClaimResponse.item.detail.subDetail.subDetailSequence` |
| ClaimResponse.item.detail.subDetail.traceNumber | - | DoesNotExistInTarget | R5 `ClaimResponse.item.detail.subDetail.traceNumber` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.item.detail.traceNumber | - | DoesNotExistInTarget | R5 `ClaimResponse.item.detail.traceNumber` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.item.extension | ClaimResponse.item.extension | SourceIsBroaderThanTarget | R5 `ClaimResponse.item.extension` maps as SourceIsBroaderThanTarget to R4 `ClaimResponse.item.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ClaimResponse.item.id | ClaimResponse.item.id | Equivalent | R5 `ClaimResponse.item.id` maps as Equivalent to R4 `ClaimResponse.item.id` |
| ClaimResponse.item.itemSequence | ClaimResponse.item.itemSequence | Equivalent | R5 `ClaimResponse.item.itemSequence` maps as Equivalent to R4 `ClaimResponse.item.itemSequence` |
| ClaimResponse.item.modifierExtension | ClaimResponse.item.modifierExtension | SourceIsBroaderThanTarget | R5 `ClaimResponse.item.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ClaimResponse.item.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ClaimResponse.item.noteNumber | ClaimResponse.item.noteNumber | Equivalent | R5 `ClaimResponse.item.noteNumber` maps as Equivalent to R4 `ClaimResponse.item.noteNumber` |
| ClaimResponse.item.reviewOutcome | - | DoesNotExistInTarget | R5 `ClaimResponse.item.reviewOutcome` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.item.reviewOutcome.decision | - | DoesNotExistInTarget | R5 `ClaimResponse.item.reviewOutcome.decision` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.item.reviewOutcome.extension | - | DoesNotExistInTarget | R5 `ClaimResponse.item.reviewOutcome.extension` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.item.reviewOutcome.id | - | DoesNotExistInTarget | R5 `ClaimResponse.item.reviewOutcome.id` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.item.reviewOutcome.modifierExtension | - | DoesNotExistInTarget | R5 `ClaimResponse.item.reviewOutcome.modifierExtension` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.item.reviewOutcome.preAuthPeriod | - | DoesNotExistInTarget | R5 `ClaimResponse.item.reviewOutcome.preAuthPeriod` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.item.reviewOutcome.preAuthRef | - | DoesNotExistInTarget | R5 `ClaimResponse.item.reviewOutcome.preAuthRef` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.item.reviewOutcome.reason | - | DoesNotExistInTarget | R5 `ClaimResponse.item.reviewOutcome.reason` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.item.traceNumber | - | DoesNotExistInTarget | R5 `ClaimResponse.item.traceNumber` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.language | ClaimResponse.language | SourceIsNarrowerThanTarget | R5 `ClaimResponse.language` maps as SourceIsNarrowerThanTarget to R4 `ClaimResponse.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| ClaimResponse.meta | ClaimResponse.meta | Equivalent | R5 `ClaimResponse.meta` maps as Equivalent to R4 `ClaimResponse.meta` |
| ClaimResponse.modifierExtension | ClaimResponse.modifierExtension | SourceIsBroaderThanTarget | R5 `ClaimResponse.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ClaimResponse.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ClaimResponse.outcome | ClaimResponse.outcome | Equivalent | R5 `ClaimResponse.outcome` maps as Equivalent to R4 `ClaimResponse.outcome` - outcome has compatible required binding for code type: http://hl7.org/fhir/ValueSet/claim-outcome|5.0.0 and http://hl7.org/fhir/ValueSet/remittance-outcome|4.0.1 (Equivalent) |
| ClaimResponse.patient | ClaimResponse.patient | Equivalent | R5 `ClaimResponse.patient` maps as Equivalent to R4 `ClaimResponse.patient` |
| ClaimResponse.payeeType | ClaimResponse.payeeType | Equivalent | R5 `ClaimResponse.payeeType` maps as Equivalent to R4 `ClaimResponse.payeeType` |
| ClaimResponse.payment | ClaimResponse.payment | Equivalent | R5 `ClaimResponse.payment` maps as Equivalent to R4 `ClaimResponse.payment` |
| ClaimResponse.payment.adjustment | ClaimResponse.payment.adjustment | Equivalent | R5 `ClaimResponse.payment.adjustment` maps as Equivalent to R4 `ClaimResponse.payment.adjustment` |
| ClaimResponse.payment.adjustmentReason | ClaimResponse.payment.adjustmentReason | Equivalent | R5 `ClaimResponse.payment.adjustmentReason` maps as Equivalent to R4 `ClaimResponse.payment.adjustmentReason` |
| ClaimResponse.payment.amount | ClaimResponse.payment.amount | Equivalent | R5 `ClaimResponse.payment.amount` maps as Equivalent to R4 `ClaimResponse.payment.amount` |
| ClaimResponse.payment.date | ClaimResponse.payment.date | Equivalent | R5 `ClaimResponse.payment.date` maps as Equivalent to R4 `ClaimResponse.payment.date` |
| ClaimResponse.payment.extension | ClaimResponse.payment.extension | SourceIsBroaderThanTarget | R5 `ClaimResponse.payment.extension` maps as SourceIsBroaderThanTarget to R4 `ClaimResponse.payment.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ClaimResponse.payment.id | ClaimResponse.payment.id | Equivalent | R5 `ClaimResponse.payment.id` maps as Equivalent to R4 `ClaimResponse.payment.id` |
| ClaimResponse.payment.identifier | ClaimResponse.payment.identifier | Equivalent | R5 `ClaimResponse.payment.identifier` maps as Equivalent to R4 `ClaimResponse.payment.identifier` |
| ClaimResponse.payment.modifierExtension | ClaimResponse.payment.modifierExtension | SourceIsBroaderThanTarget | R5 `ClaimResponse.payment.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ClaimResponse.payment.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ClaimResponse.payment.type | ClaimResponse.payment.type | Equivalent | R5 `ClaimResponse.payment.type` maps as Equivalent to R4 `ClaimResponse.payment.type` |
| ClaimResponse.preAuthPeriod | ClaimResponse.preAuthPeriod | Equivalent | R5 `ClaimResponse.preAuthPeriod` maps as Equivalent to R4 `ClaimResponse.preAuthPeriod` |
| ClaimResponse.preAuthRef | ClaimResponse.preAuthRef | Equivalent | R5 `ClaimResponse.preAuthRef` maps as Equivalent to R4 `ClaimResponse.preAuthRef` |
| ClaimResponse.processNote | ClaimResponse.processNote | Equivalent | R5 `ClaimResponse.processNote` maps as Equivalent to R4 `ClaimResponse.processNote` |
| ClaimResponse.processNote.extension | ClaimResponse.processNote.extension | SourceIsBroaderThanTarget | R5 `ClaimResponse.processNote.extension` maps as SourceIsBroaderThanTarget to R4 `ClaimResponse.processNote.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ClaimResponse.processNote.id | ClaimResponse.processNote.id | Equivalent | R5 `ClaimResponse.processNote.id` maps as Equivalent to R4 `ClaimResponse.processNote.id` |
| ClaimResponse.processNote.language | ClaimResponse.processNote.language | SourceIsNarrowerThanTarget | R5 `ClaimResponse.processNote.language` maps as SourceIsNarrowerThanTarget to R4 `ClaimResponse.processNote.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `CodeableConcept` maps as SourceIsNarrowerThanTarget for R4 `language` |
| ClaimResponse.processNote.modifierExtension | ClaimResponse.processNote.modifierExtension | SourceIsBroaderThanTarget | R5 `ClaimResponse.processNote.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ClaimResponse.processNote.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ClaimResponse.processNote.number | ClaimResponse.processNote.number | Equivalent | R5 `ClaimResponse.processNote.number` maps as Equivalent to R4 `ClaimResponse.processNote.number` |
| ClaimResponse.processNote.text | ClaimResponse.processNote.text | Equivalent | R5 `ClaimResponse.processNote.text` maps as Equivalent to R4 `ClaimResponse.processNote.text` |
| ClaimResponse.processNote.type | ClaimResponse.processNote.type | RelatedTo | R5 `ClaimResponse.processNote.type` maps as RelatedTo to R4 `ClaimResponse.processNote.type` - type made the binding required (from Extensible) for http://hl7.org/fhir/ValueSet/note-type|4.0.1; type has change due to type change: R5 type CodeableConcept has no equivalent or mapped type in R4 type |
| ClaimResponse.request | ClaimResponse.request | Equivalent | R5 `ClaimResponse.request` maps as Equivalent to R4 `ClaimResponse.request` |
| ClaimResponse.requestor | ClaimResponse.requestor | Equivalent | R5 `ClaimResponse.requestor` maps as Equivalent to R4 `ClaimResponse.requestor` |
| ClaimResponse.status | ClaimResponse.status | Equivalent | R5 `ClaimResponse.status` maps as Equivalent to R4 `ClaimResponse.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/fm-status|5.0.0 and http://hl7.org/fhir/ValueSet/fm-status|4.0.1 (Equivalent) |
| ClaimResponse.subType | ClaimResponse.subType | Equivalent | R5 `ClaimResponse.subType` maps as Equivalent to R4 `ClaimResponse.subType` |
| ClaimResponse.text | ClaimResponse.text | Equivalent | R5 `ClaimResponse.text` maps as Equivalent to R4 `ClaimResponse.text` |
| ClaimResponse.total | ClaimResponse.total | Equivalent | R5 `ClaimResponse.total` maps as Equivalent to R4 `ClaimResponse.total` |
| ClaimResponse.total.amount | ClaimResponse.total.amount | Equivalent | R5 `ClaimResponse.total.amount` maps as Equivalent to R4 `ClaimResponse.total.amount` |
| ClaimResponse.total.category | ClaimResponse.total.category | Equivalent | R5 `ClaimResponse.total.category` maps as Equivalent to R4 `ClaimResponse.total.category` |
| ClaimResponse.total.extension | ClaimResponse.total.extension | SourceIsBroaderThanTarget | R5 `ClaimResponse.total.extension` maps as SourceIsBroaderThanTarget to R4 `ClaimResponse.total.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ClaimResponse.total.id | ClaimResponse.total.id | Equivalent | R5 `ClaimResponse.total.id` maps as Equivalent to R4 `ClaimResponse.total.id` |
| ClaimResponse.total.modifierExtension | ClaimResponse.total.modifierExtension | SourceIsBroaderThanTarget | R5 `ClaimResponse.total.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ClaimResponse.total.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ClaimResponse.traceNumber | - | DoesNotExistInTarget | R5 `ClaimResponse.traceNumber` does not appear in the target and has no mapping for `ClaimResponse`. |
| ClaimResponse.type | ClaimResponse.type | Equivalent | R5 `ClaimResponse.type` maps as Equivalent to R4 `ClaimResponse.type` |
| ClaimResponse.use | ClaimResponse.use | Equivalent | R5 `ClaimResponse.use` maps as Equivalent to R4 `ClaimResponse.use` - use has compatible required binding for code type: http://hl7.org/fhir/ValueSet/claim-use|5.0.0 and http://hl7.org/fhir/ValueSet/claim-use|4.0.1 (Equivalent) |

