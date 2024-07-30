Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Claim |  | A provider issued list of professional services and products which have been provided, or are to be provided, to a patient which is sent to an insurer for reimbursement. | 175 | 128 |
| Target | Claim |  | A provider issued list of professional services and products which have been provided, or are to be provided, to a patient which is sent to an insurer for reimbursement. | 149 | 108 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 29 |
Equivalent | 4 |
RelatedTo | 142 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Claim | Claim | Equivalent | R5 `Claim` maps as Equivalent to R4 `Claim` |
| Claim.accident | Claim.accident | Equivalent | R5 `Claim.accident` maps as Equivalent to R4 `Claim.accident` |
| Claim.accident.date | Claim.accident.date | Equivalent | R5 `Claim.accident.date` maps as Equivalent to R4 `Claim.accident.date` |
| Claim.accident.extension | Claim.accident.extension | SourceIsBroaderThanTarget | R5 `Claim.accident.extension` maps as SourceIsBroaderThanTarget to R4 `Claim.accident.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Claim.accident.id | Claim.accident.id | Equivalent | R5 `Claim.accident.id` maps as Equivalent to R4 `Claim.accident.id` |
| Claim.accident.location[x] | Claim.accident.location[x] | Equivalent | R5 `Claim.accident.location[x]` maps as Equivalent to R4 `Claim.accident.location[x]` |
| Claim.accident.modifierExtension | Claim.accident.modifierExtension | SourceIsBroaderThanTarget | R5 `Claim.accident.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Claim.accident.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Claim.accident.type | Claim.accident.type | Equivalent | R5 `Claim.accident.type` maps as Equivalent to R4 `Claim.accident.type` |
| Claim.billablePeriod | Claim.billablePeriod | Equivalent | R5 `Claim.billablePeriod` maps as Equivalent to R4 `Claim.billablePeriod` |
| Claim.careTeam | Claim.careTeam | Equivalent | R5 `Claim.careTeam` maps as Equivalent to R4 `Claim.careTeam` |
| Claim.careTeam.extension | Claim.careTeam.extension | SourceIsBroaderThanTarget | R5 `Claim.careTeam.extension` maps as SourceIsBroaderThanTarget to R4 `Claim.careTeam.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Claim.careTeam.id | Claim.careTeam.id | Equivalent | R5 `Claim.careTeam.id` maps as Equivalent to R4 `Claim.careTeam.id` |
| Claim.careTeam.modifierExtension | Claim.careTeam.modifierExtension | SourceIsBroaderThanTarget | R5 `Claim.careTeam.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Claim.careTeam.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Claim.careTeam.provider | Claim.careTeam.provider | Equivalent | R5 `Claim.careTeam.provider` maps as Equivalent to R4 `Claim.careTeam.provider` |
| Claim.careTeam.responsible | Claim.careTeam.responsible | Equivalent | R5 `Claim.careTeam.responsible` maps as Equivalent to R4 `Claim.careTeam.responsible` |
| Claim.careTeam.role | Claim.careTeam.role | Equivalent | R5 `Claim.careTeam.role` maps as Equivalent to R4 `Claim.careTeam.role` |
| Claim.careTeam.sequence | Claim.careTeam.sequence | Equivalent | R5 `Claim.careTeam.sequence` maps as Equivalent to R4 `Claim.careTeam.sequence` |
| Claim.careTeam.specialty | - | DoesNotExistInTarget | R5 `Claim.careTeam.specialty` does not appear in the target and has no mapping for `Claim`. |
| Claim.contained | Claim.contained | Equivalent | R5 `Claim.contained` maps as Equivalent to R4 `Claim.contained` |
| Claim.created | Claim.created | Equivalent | R5 `Claim.created` maps as Equivalent to R4 `Claim.created` |
| Claim.diagnosis | Claim.diagnosis | Equivalent | R5 `Claim.diagnosis` maps as Equivalent to R4 `Claim.diagnosis` |
| Claim.diagnosis.diagnosis[x] | Claim.diagnosis.diagnosis[x] | Equivalent | R5 `Claim.diagnosis.diagnosis[x]` maps as Equivalent to R4 `Claim.diagnosis.diagnosis[x]` |
| Claim.diagnosis.extension | Claim.diagnosis.extension | SourceIsBroaderThanTarget | R5 `Claim.diagnosis.extension` maps as SourceIsBroaderThanTarget to R4 `Claim.diagnosis.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Claim.diagnosis.id | Claim.diagnosis.id | Equivalent | R5 `Claim.diagnosis.id` maps as Equivalent to R4 `Claim.diagnosis.id` |
| Claim.diagnosis.modifierExtension | Claim.diagnosis.modifierExtension | SourceIsBroaderThanTarget | R5 `Claim.diagnosis.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Claim.diagnosis.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Claim.diagnosis.onAdmission | Claim.diagnosis.onAdmission | Equivalent | R5 `Claim.diagnosis.onAdmission` maps as Equivalent to R4 `Claim.diagnosis.onAdmission` |
| Claim.diagnosis.sequence | Claim.diagnosis.sequence | Equivalent | R5 `Claim.diagnosis.sequence` maps as Equivalent to R4 `Claim.diagnosis.sequence` |
| Claim.diagnosis.type | Claim.diagnosis.type | Equivalent | R5 `Claim.diagnosis.type` maps as Equivalent to R4 `Claim.diagnosis.type` |
| Claim.diagnosisRelatedGroup | - | DoesNotExistInTarget | R5 `Claim.diagnosisRelatedGroup` does not appear in the target and has no mapping for `Claim`. |
| Claim.encounter | - | DoesNotExistInTarget | R5 `Claim.encounter` does not appear in the target and has no mapping for `Claim`. |
| Claim.enterer | Claim.enterer | SourceIsBroaderThanTarget | R5 `Claim.enterer` maps as SourceIsBroaderThanTarget to R4 `Claim.enterer` - enterer has change due to type change: R5 `enterer` `Reference` maps as SourceIsBroaderThanTarget for R4 `enterer` |
| Claim.event | - | DoesNotExistInTarget | R5 `Claim.event` does not appear in the target and has no mapping for `Claim`. |
| Claim.event.extension | - | DoesNotExistInTarget | R5 `Claim.event.extension` does not appear in the target and has no mapping for `Claim`. |
| Claim.event.id | - | DoesNotExistInTarget | R5 `Claim.event.id` does not appear in the target and has no mapping for `Claim`. |
| Claim.event.modifierExtension | - | DoesNotExistInTarget | R5 `Claim.event.modifierExtension` does not appear in the target and has no mapping for `Claim`. |
| Claim.event.type | - | DoesNotExistInTarget | R5 `Claim.event.type` does not appear in the target and has no mapping for `Claim`. |
| Claim.event.when[x] | - | DoesNotExistInTarget | R5 `Claim.event.when[x]` does not appear in the target and has no mapping for `Claim`. |
| Claim.extension | Claim.extension | SourceIsBroaderThanTarget | R5 `Claim.extension` maps as SourceIsBroaderThanTarget to R4 `Claim.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Claim.facility | Claim.facility | SourceIsBroaderThanTarget | R5 `Claim.facility` maps as SourceIsBroaderThanTarget to R4 `Claim.facility` - facility has change due to type change: R5 `facility` `Reference` maps as SourceIsBroaderThanTarget for R4 `facility` |
| Claim.fundsReserve | Claim.fundsReserve | Equivalent | R5 `Claim.fundsReserve` maps as Equivalent to R4 `Claim.fundsReserve` |
| Claim.id | Claim.id | Equivalent | R5 `Claim.id` maps as Equivalent to R4 `Claim.id` |
| Claim.identifier | Claim.identifier | Equivalent | R5 `Claim.identifier` maps as Equivalent to R4 `Claim.identifier` |
| Claim.implicitRules | Claim.implicitRules | Equivalent | R5 `Claim.implicitRules` maps as Equivalent to R4 `Claim.implicitRules` |
| Claim.insurance | Claim.insurance | RelatedTo | R5 `Claim.insurance` maps as RelatedTo to R4 `Claim.insurance` - insurance made the element mandatory; insurance increased the minimum cardinality from 0 to 1 |
| Claim.insurance.businessArrangement | Claim.insurance.businessArrangement | Equivalent | R5 `Claim.insurance.businessArrangement` maps as Equivalent to R4 `Claim.insurance.businessArrangement` |
| Claim.insurance.claimResponse | Claim.insurance.claimResponse | Equivalent | R5 `Claim.insurance.claimResponse` maps as Equivalent to R4 `Claim.insurance.claimResponse` |
| Claim.insurance.coverage | Claim.insurance.coverage | Equivalent | R5 `Claim.insurance.coverage` maps as Equivalent to R4 `Claim.insurance.coverage` |
| Claim.insurance.extension | Claim.insurance.extension | SourceIsBroaderThanTarget | R5 `Claim.insurance.extension` maps as SourceIsBroaderThanTarget to R4 `Claim.insurance.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Claim.insurance.focal | Claim.insurance.focal | Equivalent | R5 `Claim.insurance.focal` maps as Equivalent to R4 `Claim.insurance.focal` |
| Claim.insurance.id | Claim.insurance.id | Equivalent | R5 `Claim.insurance.id` maps as Equivalent to R4 `Claim.insurance.id` |
| Claim.insurance.identifier | Claim.insurance.identifier | Equivalent | R5 `Claim.insurance.identifier` maps as Equivalent to R4 `Claim.insurance.identifier` |
| Claim.insurance.modifierExtension | Claim.insurance.modifierExtension | SourceIsBroaderThanTarget | R5 `Claim.insurance.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Claim.insurance.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Claim.insurance.preAuthRef | Claim.insurance.preAuthRef | Equivalent | R5 `Claim.insurance.preAuthRef` maps as Equivalent to R4 `Claim.insurance.preAuthRef` |
| Claim.insurance.sequence | Claim.insurance.sequence | Equivalent | R5 `Claim.insurance.sequence` maps as Equivalent to R4 `Claim.insurance.sequence` |
| Claim.insurer | Claim.insurer | Equivalent | R5 `Claim.insurer` maps as Equivalent to R4 `Claim.insurer` |
| Claim.item | Claim.item | Equivalent | R5 `Claim.item` maps as Equivalent to R4 `Claim.item` |
| Claim.item.bodySite | Claim.item.bodySite | RelatedTo | R5 `Claim.item.bodySite` maps as RelatedTo to R4 `Claim.item.bodySite` - bodySite changed from array to scalar (max cardinality from * to 1); bodySite added a binding requirement - Example http://hl7.org/fhir/ValueSet/tooth; bodySite has change due to type change: R5 bodySite BackboneElement has no equivalent or mapped type in R4 bodySite |
| Claim.item.bodySite.extension | - | DoesNotExistInTarget | R5 `Claim.item.bodySite.extension` does not appear in the target and has no mapping for `Claim`. |
| Claim.item.bodySite.id | - | DoesNotExistInTarget | R5 `Claim.item.bodySite.id` does not appear in the target and has no mapping for `Claim`. |
| Claim.item.bodySite.modifierExtension | - | DoesNotExistInTarget | R5 `Claim.item.bodySite.modifierExtension` does not appear in the target and has no mapping for `Claim`. |
| Claim.item.bodySite.site | - | DoesNotExistInTarget | R5 `Claim.item.bodySite.site` does not appear in the target and has no mapping for `Claim`. |
| Claim.item.bodySite.subSite | - | DoesNotExistInTarget | R5 `Claim.item.bodySite.subSite` does not appear in the target and has no mapping for `Claim`. |
| Claim.item.careTeamSequence | Claim.item.careTeamSequence | Equivalent | R5 `Claim.item.careTeamSequence` maps as Equivalent to R4 `Claim.item.careTeamSequence` |
| Claim.item.category | Claim.item.category | Equivalent | R5 `Claim.item.category` maps as Equivalent to R4 `Claim.item.category` |
| Claim.item.detail | Claim.item.detail | Equivalent | R5 `Claim.item.detail` maps as Equivalent to R4 `Claim.item.detail` |
| Claim.item.detail.category | Claim.item.detail.category | Equivalent | R5 `Claim.item.detail.category` maps as Equivalent to R4 `Claim.item.detail.category` |
| Claim.item.detail.extension | Claim.item.detail.extension | SourceIsBroaderThanTarget | R5 `Claim.item.detail.extension` maps as SourceIsBroaderThanTarget to R4 `Claim.item.detail.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Claim.item.detail.factor | Claim.item.detail.factor | Equivalent | R5 `Claim.item.detail.factor` maps as Equivalent to R4 `Claim.item.detail.factor` |
| Claim.item.detail.id | Claim.item.detail.id | Equivalent | R5 `Claim.item.detail.id` maps as Equivalent to R4 `Claim.item.detail.id` |
| Claim.item.detail.modifier | Claim.item.detail.modifier | Equivalent | R5 `Claim.item.detail.modifier` maps as Equivalent to R4 `Claim.item.detail.modifier` |
| Claim.item.detail.modifierExtension | Claim.item.detail.modifierExtension | SourceIsBroaderThanTarget | R5 `Claim.item.detail.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Claim.item.detail.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Claim.item.detail.net | Claim.item.detail.net | Equivalent | R5 `Claim.item.detail.net` maps as Equivalent to R4 `Claim.item.detail.net` |
| Claim.item.detail.patientPaid | - | DoesNotExistInTarget | R5 `Claim.item.detail.patientPaid` does not appear in the target and has no mapping for `Claim`. |
| Claim.item.detail.productOrService | Claim.item.detail.productOrService | RelatedTo | R5 `Claim.item.detail.productOrService` maps as RelatedTo to R4 `Claim.item.detail.productOrService` - productOrService made the element mandatory; productOrService increased the minimum cardinality from 0 to 1 |
| Claim.item.detail.productOrServiceEnd | - | DoesNotExistInTarget | R5 `Claim.item.detail.productOrServiceEnd` does not appear in the target and has no mapping for `Claim`. |
| Claim.item.detail.programCode | Claim.item.detail.programCode | Equivalent | R5 `Claim.item.detail.programCode` maps as Equivalent to R4 `Claim.item.detail.programCode` |
| Claim.item.detail.quantity | Claim.item.detail.quantity | Equivalent | R5 `Claim.item.detail.quantity` maps as Equivalent to R4 `Claim.item.detail.quantity` |
| Claim.item.detail.revenue | Claim.item.detail.revenue | Equivalent | R5 `Claim.item.detail.revenue` maps as Equivalent to R4 `Claim.item.detail.revenue` |
| Claim.item.detail.sequence | Claim.item.detail.sequence | Equivalent | R5 `Claim.item.detail.sequence` maps as Equivalent to R4 `Claim.item.detail.sequence` |
| Claim.item.detail.subDetail | Claim.item.detail.subDetail | Equivalent | R5 `Claim.item.detail.subDetail` maps as Equivalent to R4 `Claim.item.detail.subDetail` |
| Claim.item.detail.subDetail.category | Claim.item.detail.subDetail.category | Equivalent | R5 `Claim.item.detail.subDetail.category` maps as Equivalent to R4 `Claim.item.detail.subDetail.category` |
| Claim.item.detail.subDetail.extension | Claim.item.detail.subDetail.extension | SourceIsBroaderThanTarget | R5 `Claim.item.detail.subDetail.extension` maps as SourceIsBroaderThanTarget to R4 `Claim.item.detail.subDetail.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Claim.item.detail.subDetail.factor | Claim.item.detail.subDetail.factor | Equivalent | R5 `Claim.item.detail.subDetail.factor` maps as Equivalent to R4 `Claim.item.detail.subDetail.factor` |
| Claim.item.detail.subDetail.id | Claim.item.detail.subDetail.id | Equivalent | R5 `Claim.item.detail.subDetail.id` maps as Equivalent to R4 `Claim.item.detail.subDetail.id` |
| Claim.item.detail.subDetail.modifier | Claim.item.detail.subDetail.modifier | Equivalent | R5 `Claim.item.detail.subDetail.modifier` maps as Equivalent to R4 `Claim.item.detail.subDetail.modifier` |
| Claim.item.detail.subDetail.modifierExtension | Claim.item.detail.subDetail.modifierExtension | SourceIsBroaderThanTarget | R5 `Claim.item.detail.subDetail.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Claim.item.detail.subDetail.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Claim.item.detail.subDetail.net | Claim.item.detail.subDetail.net | Equivalent | R5 `Claim.item.detail.subDetail.net` maps as Equivalent to R4 `Claim.item.detail.subDetail.net` |
| Claim.item.detail.subDetail.patientPaid | - | DoesNotExistInTarget | R5 `Claim.item.detail.subDetail.patientPaid` does not appear in the target and has no mapping for `Claim`. |
| Claim.item.detail.subDetail.productOrService | Claim.item.detail.subDetail.productOrService | RelatedTo | R5 `Claim.item.detail.subDetail.productOrService` maps as RelatedTo to R4 `Claim.item.detail.subDetail.productOrService` - productOrService made the element mandatory; productOrService increased the minimum cardinality from 0 to 1 |
| Claim.item.detail.subDetail.productOrServiceEnd | - | DoesNotExistInTarget | R5 `Claim.item.detail.subDetail.productOrServiceEnd` does not appear in the target and has no mapping for `Claim`. |
| Claim.item.detail.subDetail.programCode | Claim.item.detail.subDetail.programCode | Equivalent | R5 `Claim.item.detail.subDetail.programCode` maps as Equivalent to R4 `Claim.item.detail.subDetail.programCode` |
| Claim.item.detail.subDetail.quantity | Claim.item.detail.subDetail.quantity | Equivalent | R5 `Claim.item.detail.subDetail.quantity` maps as Equivalent to R4 `Claim.item.detail.subDetail.quantity` |
| Claim.item.detail.subDetail.revenue | Claim.item.detail.subDetail.revenue | Equivalent | R5 `Claim.item.detail.subDetail.revenue` maps as Equivalent to R4 `Claim.item.detail.subDetail.revenue` |
| Claim.item.detail.subDetail.sequence | Claim.item.detail.subDetail.sequence | Equivalent | R5 `Claim.item.detail.subDetail.sequence` maps as Equivalent to R4 `Claim.item.detail.subDetail.sequence` |
| Claim.item.detail.subDetail.tax | - | DoesNotExistInTarget | R5 `Claim.item.detail.subDetail.tax` does not appear in the target and has no mapping for `Claim`. |
| Claim.item.detail.subDetail.traceNumber | - | DoesNotExistInTarget | R5 `Claim.item.detail.subDetail.traceNumber` does not appear in the target and has no mapping for `Claim`. |
| Claim.item.detail.subDetail.udi | Claim.item.detail.subDetail.udi | Equivalent | R5 `Claim.item.detail.subDetail.udi` maps as Equivalent to R4 `Claim.item.detail.subDetail.udi` |
| Claim.item.detail.subDetail.unitPrice | Claim.item.detail.subDetail.unitPrice | Equivalent | R5 `Claim.item.detail.subDetail.unitPrice` maps as Equivalent to R4 `Claim.item.detail.subDetail.unitPrice` |
| Claim.item.detail.tax | - | DoesNotExistInTarget | R5 `Claim.item.detail.tax` does not appear in the target and has no mapping for `Claim`. |
| Claim.item.detail.traceNumber | - | DoesNotExistInTarget | R5 `Claim.item.detail.traceNumber` does not appear in the target and has no mapping for `Claim`. |
| Claim.item.detail.udi | Claim.item.detail.udi | Equivalent | R5 `Claim.item.detail.udi` maps as Equivalent to R4 `Claim.item.detail.udi` |
| Claim.item.detail.unitPrice | Claim.item.detail.unitPrice | Equivalent | R5 `Claim.item.detail.unitPrice` maps as Equivalent to R4 `Claim.item.detail.unitPrice` |
| Claim.item.diagnosisSequence | Claim.item.diagnosisSequence | Equivalent | R5 `Claim.item.diagnosisSequence` maps as Equivalent to R4 `Claim.item.diagnosisSequence` |
| Claim.item.encounter | Claim.item.encounter | Equivalent | R5 `Claim.item.encounter` maps as Equivalent to R4 `Claim.item.encounter` |
| Claim.item.extension | Claim.item.extension | SourceIsBroaderThanTarget | R5 `Claim.item.extension` maps as SourceIsBroaderThanTarget to R4 `Claim.item.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Claim.item.factor | Claim.item.factor | Equivalent | R5 `Claim.item.factor` maps as Equivalent to R4 `Claim.item.factor` |
| Claim.item.id | Claim.item.id | Equivalent | R5 `Claim.item.id` maps as Equivalent to R4 `Claim.item.id` |
| Claim.item.informationSequence | Claim.item.informationSequence | Equivalent | R5 `Claim.item.informationSequence` maps as Equivalent to R4 `Claim.item.informationSequence` |
| Claim.item.location[x] | Claim.item.location[x] | Equivalent | R5 `Claim.item.location[x]` maps as Equivalent to R4 `Claim.item.location[x]` |
| Claim.item.modifier | Claim.item.modifier | Equivalent | R5 `Claim.item.modifier` maps as Equivalent to R4 `Claim.item.modifier` |
| Claim.item.modifierExtension | Claim.item.modifierExtension | SourceIsBroaderThanTarget | R5 `Claim.item.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Claim.item.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Claim.item.net | Claim.item.net | Equivalent | R5 `Claim.item.net` maps as Equivalent to R4 `Claim.item.net` |
| Claim.item.patientPaid | - | DoesNotExistInTarget | R5 `Claim.item.patientPaid` does not appear in the target and has no mapping for `Claim`. |
| Claim.item.procedureSequence | Claim.item.procedureSequence | Equivalent | R5 `Claim.item.procedureSequence` maps as Equivalent to R4 `Claim.item.procedureSequence` |
| Claim.item.productOrService | Claim.item.productOrService | RelatedTo | R5 `Claim.item.productOrService` maps as RelatedTo to R4 `Claim.item.productOrService` - productOrService made the element mandatory; productOrService increased the minimum cardinality from 0 to 1 |
| Claim.item.productOrServiceEnd | - | DoesNotExistInTarget | R5 `Claim.item.productOrServiceEnd` does not appear in the target and has no mapping for `Claim`. |
| Claim.item.programCode | Claim.item.programCode | Equivalent | R5 `Claim.item.programCode` maps as Equivalent to R4 `Claim.item.programCode` |
| Claim.item.quantity | Claim.item.quantity | Equivalent | R5 `Claim.item.quantity` maps as Equivalent to R4 `Claim.item.quantity` |
| Claim.item.request | - | DoesNotExistInTarget | R5 `Claim.item.request` does not appear in the target and has no mapping for `Claim`. |
| Claim.item.revenue | Claim.item.revenue | Equivalent | R5 `Claim.item.revenue` maps as Equivalent to R4 `Claim.item.revenue` |
| Claim.item.sequence | Claim.item.sequence | Equivalent | R5 `Claim.item.sequence` maps as Equivalent to R4 `Claim.item.sequence` |
| Claim.item.serviced[x] | Claim.item.serviced[x] | Equivalent | R5 `Claim.item.serviced[x]` maps as Equivalent to R4 `Claim.item.serviced[x]` |
| Claim.item.tax | - | DoesNotExistInTarget | R5 `Claim.item.tax` does not appear in the target and has no mapping for `Claim`. |
| Claim.item.traceNumber | - | DoesNotExistInTarget | R5 `Claim.item.traceNumber` does not appear in the target and has no mapping for `Claim`. |
| Claim.item.udi | Claim.item.udi | Equivalent | R5 `Claim.item.udi` maps as Equivalent to R4 `Claim.item.udi` |
| Claim.item.unitPrice | Claim.item.unitPrice | Equivalent | R5 `Claim.item.unitPrice` maps as Equivalent to R4 `Claim.item.unitPrice` |
| Claim.language | Claim.language | RelatedTo | R5 `Claim.language` maps as RelatedTo to R4 `Claim.language` - language changed the binding strength from Required to Preferred |
| Claim.meta | Claim.meta | Equivalent | R5 `Claim.meta` maps as Equivalent to R4 `Claim.meta` |
| Claim.modifierExtension | Claim.modifierExtension | SourceIsBroaderThanTarget | R5 `Claim.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Claim.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Claim.originalPrescription | Claim.originalPrescription | Equivalent | R5 `Claim.originalPrescription` maps as Equivalent to R4 `Claim.originalPrescription` |
| Claim.patient | Claim.patient | Equivalent | R5 `Claim.patient` maps as Equivalent to R4 `Claim.patient` |
| Claim.patientPaid | - | DoesNotExistInTarget | R5 `Claim.patientPaid` does not appear in the target and has no mapping for `Claim`. |
| Claim.payee | Claim.payee | Equivalent | R5 `Claim.payee` maps as Equivalent to R4 `Claim.payee` |
| Claim.payee.extension | Claim.payee.extension | SourceIsBroaderThanTarget | R5 `Claim.payee.extension` maps as SourceIsBroaderThanTarget to R4 `Claim.payee.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Claim.payee.id | Claim.payee.id | Equivalent | R5 `Claim.payee.id` maps as Equivalent to R4 `Claim.payee.id` |
| Claim.payee.modifierExtension | Claim.payee.modifierExtension | SourceIsBroaderThanTarget | R5 `Claim.payee.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Claim.payee.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Claim.payee.party | Claim.payee.party | Equivalent | R5 `Claim.payee.party` maps as Equivalent to R4 `Claim.payee.party` |
| Claim.payee.type | Claim.payee.type | Equivalent | R5 `Claim.payee.type` maps as Equivalent to R4 `Claim.payee.type` |
| Claim.prescription | Claim.prescription | Equivalent | R5 `Claim.prescription` maps as Equivalent to R4 `Claim.prescription` |
| Claim.priority | Claim.priority | RelatedTo | R5 `Claim.priority` maps as RelatedTo to R4 `Claim.priority` - priority made the element mandatory; priority increased the minimum cardinality from 0 to 1 |
| Claim.procedure | Claim.procedure | Equivalent | R5 `Claim.procedure` maps as Equivalent to R4 `Claim.procedure` |
| Claim.procedure.date | Claim.procedure.date | Equivalent | R5 `Claim.procedure.date` maps as Equivalent to R4 `Claim.procedure.date` |
| Claim.procedure.extension | Claim.procedure.extension | SourceIsBroaderThanTarget | R5 `Claim.procedure.extension` maps as SourceIsBroaderThanTarget to R4 `Claim.procedure.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Claim.procedure.id | Claim.procedure.id | Equivalent | R5 `Claim.procedure.id` maps as Equivalent to R4 `Claim.procedure.id` |
| Claim.procedure.modifierExtension | Claim.procedure.modifierExtension | SourceIsBroaderThanTarget | R5 `Claim.procedure.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Claim.procedure.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Claim.procedure.procedure[x] | Claim.procedure.procedure[x] | Equivalent | R5 `Claim.procedure.procedure[x]` maps as Equivalent to R4 `Claim.procedure.procedure[x]` |
| Claim.procedure.sequence | Claim.procedure.sequence | Equivalent | R5 `Claim.procedure.sequence` maps as Equivalent to R4 `Claim.procedure.sequence` |
| Claim.procedure.type | Claim.procedure.type | Equivalent | R5 `Claim.procedure.type` maps as Equivalent to R4 `Claim.procedure.type` |
| Claim.procedure.udi | Claim.procedure.udi | Equivalent | R5 `Claim.procedure.udi` maps as Equivalent to R4 `Claim.procedure.udi` |
| Claim.provider | Claim.provider | RelatedTo | R5 `Claim.provider` maps as RelatedTo to R4 `Claim.provider` - provider made the element mandatory; provider increased the minimum cardinality from 0 to 1 |
| Claim.referral | Claim.referral | Equivalent | R5 `Claim.referral` maps as Equivalent to R4 `Claim.referral` |
| Claim.related | Claim.related | Equivalent | R5 `Claim.related` maps as Equivalent to R4 `Claim.related` |
| Claim.related.claim | Claim.related.claim | Equivalent | R5 `Claim.related.claim` maps as Equivalent to R4 `Claim.related.claim` |
| Claim.related.extension | Claim.related.extension | SourceIsBroaderThanTarget | R5 `Claim.related.extension` maps as SourceIsBroaderThanTarget to R4 `Claim.related.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Claim.related.id | Claim.related.id | Equivalent | R5 `Claim.related.id` maps as Equivalent to R4 `Claim.related.id` |
| Claim.related.modifierExtension | Claim.related.modifierExtension | SourceIsBroaderThanTarget | R5 `Claim.related.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Claim.related.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Claim.related.reference | Claim.related.reference | Equivalent | R5 `Claim.related.reference` maps as Equivalent to R4 `Claim.related.reference` |
| Claim.related.relationship | Claim.related.relationship | Equivalent | R5 `Claim.related.relationship` maps as Equivalent to R4 `Claim.related.relationship` |
| Claim.status | Claim.status | Equivalent | R5 `Claim.status` maps as Equivalent to R4 `Claim.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/fm-status|5.0.0 and http://hl7.org/fhir/ValueSet/fm-status|4.0.1 (Equivalent) |
| Claim.subType | Claim.subType | Equivalent | R5 `Claim.subType` maps as Equivalent to R4 `Claim.subType` |
| Claim.supportingInfo | Claim.supportingInfo | Equivalent | R5 `Claim.supportingInfo` maps as Equivalent to R4 `Claim.supportingInfo` |
| Claim.supportingInfo.category | Claim.supportingInfo.category | Equivalent | R5 `Claim.supportingInfo.category` maps as Equivalent to R4 `Claim.supportingInfo.category` |
| Claim.supportingInfo.code | Claim.supportingInfo.code | Equivalent | R5 `Claim.supportingInfo.code` maps as Equivalent to R4 `Claim.supportingInfo.code` |
| Claim.supportingInfo.extension | Claim.supportingInfo.extension | SourceIsBroaderThanTarget | R5 `Claim.supportingInfo.extension` maps as SourceIsBroaderThanTarget to R4 `Claim.supportingInfo.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Claim.supportingInfo.id | Claim.supportingInfo.id | Equivalent | R5 `Claim.supportingInfo.id` maps as Equivalent to R4 `Claim.supportingInfo.id` |
| Claim.supportingInfo.modifierExtension | Claim.supportingInfo.modifierExtension | SourceIsBroaderThanTarget | R5 `Claim.supportingInfo.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Claim.supportingInfo.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Claim.supportingInfo.reason | Claim.supportingInfo.reason | Equivalent | R5 `Claim.supportingInfo.reason` maps as Equivalent to R4 `Claim.supportingInfo.reason` |
| Claim.supportingInfo.sequence | Claim.supportingInfo.sequence | Equivalent | R5 `Claim.supportingInfo.sequence` maps as Equivalent to R4 `Claim.supportingInfo.sequence` |
| Claim.supportingInfo.timing[x] | Claim.supportingInfo.timing[x] | Equivalent | R5 `Claim.supportingInfo.timing[x]` maps as Equivalent to R4 `Claim.supportingInfo.timing[x]` |
| Claim.supportingInfo.value[x] | Claim.supportingInfo.value[x] | RelatedTo | R5 `Claim.supportingInfo.value[x]` maps as RelatedTo to R4 `Claim.supportingInfo.value[x]` - value[x] has change due to type change: R5 `value[x]` `Attachment` maps as RelatedTo for R4 `value[x]`; value[x] has change due to type change: R5 value[x] Identifier has no equivalent or mapped type in R4 value[x] |
| Claim.text | Claim.text | Equivalent | R5 `Claim.text` maps as Equivalent to R4 `Claim.text` |
| Claim.total | Claim.total | Equivalent | R5 `Claim.total` maps as Equivalent to R4 `Claim.total` |
| Claim.traceNumber | - | DoesNotExistInTarget | R5 `Claim.traceNumber` does not appear in the target and has no mapping for `Claim`. |
| Claim.type | Claim.type | Equivalent | R5 `Claim.type` maps as Equivalent to R4 `Claim.type` |
| Claim.use | Claim.use | Equivalent | R5 `Claim.use` maps as Equivalent to R4 `Claim.use` - use has compatible required binding for code type: http://hl7.org/fhir/ValueSet/claim-use|5.0.0 and http://hl7.org/fhir/ValueSet/claim-use|4.0.1 (Equivalent) |

