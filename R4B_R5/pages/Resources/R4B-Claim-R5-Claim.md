Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Claim |  | A provider issued list of professional services and products which have been provided, or are to be provided, to a patient which is sent to an insurer for reimbursement. | 149 | 108 |
| Target | Claim |  | A provider issued list of professional services and products which have been provided, or are to be provided, to a patient which is sent to an insurer for reimbursement. | 175 | 128 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 3 |
Equivalent | 4 |
RelatedTo | 142 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Claim | Claim | Equivalent | R4B `Claim` maps as Equivalent to R5 `Claim` |
| Claim.accident | Claim.accident | Equivalent | R4B `Claim.accident` maps as Equivalent to R5 `Claim.accident` |
| Claim.accident.date | Claim.accident.date | Equivalent | R4B `Claim.accident.date` maps as Equivalent to R5 `Claim.accident.date` |
| Claim.accident.extension | Claim.accident.extension | RelatedTo | R4B `Claim.accident.extension` maps as RelatedTo to R5 `Claim.accident.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Claim.accident.id | Claim.accident.id | Equivalent | R4B `Claim.accident.id` maps as Equivalent to R5 `Claim.accident.id` |
| Claim.accident.location[x] | Claim.accident.location[x] | Equivalent | R4B `Claim.accident.location[x]` maps as Equivalent to R5 `Claim.accident.location[x]` |
| Claim.accident.modifierExtension | Claim.accident.modifierExtension | RelatedTo | R4B `Claim.accident.modifierExtension` maps as RelatedTo to R5 `Claim.accident.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Claim.accident.type | Claim.accident.type | Equivalent | R4B `Claim.accident.type` maps as Equivalent to R5 `Claim.accident.type` |
| Claim.billablePeriod | Claim.billablePeriod | Equivalent | R4B `Claim.billablePeriod` maps as Equivalent to R5 `Claim.billablePeriod` |
| Claim.careTeam | Claim.careTeam | Equivalent | R4B `Claim.careTeam` maps as Equivalent to R5 `Claim.careTeam` |
| Claim.careTeam.extension | Claim.careTeam.extension | RelatedTo | R4B `Claim.careTeam.extension` maps as RelatedTo to R5 `Claim.careTeam.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Claim.careTeam.id | Claim.careTeam.id | Equivalent | R4B `Claim.careTeam.id` maps as Equivalent to R5 `Claim.careTeam.id` |
| Claim.careTeam.modifierExtension | Claim.careTeam.modifierExtension | RelatedTo | R4B `Claim.careTeam.modifierExtension` maps as RelatedTo to R5 `Claim.careTeam.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Claim.careTeam.provider | Claim.careTeam.provider | Equivalent | R4B `Claim.careTeam.provider` maps as Equivalent to R5 `Claim.careTeam.provider` |
| Claim.careTeam.qualification | - | DoesNotExistInTarget | R4B `Claim.careTeam.qualification` does not appear in the target and has no mapping for `Claim`. |
| Claim.careTeam.responsible | Claim.careTeam.responsible | Equivalent | R4B `Claim.careTeam.responsible` maps as Equivalent to R5 `Claim.careTeam.responsible` |
| Claim.careTeam.role | Claim.careTeam.role | Equivalent | R4B `Claim.careTeam.role` maps as Equivalent to R5 `Claim.careTeam.role` |
| Claim.careTeam.sequence | Claim.careTeam.sequence | Equivalent | R4B `Claim.careTeam.sequence` maps as Equivalent to R5 `Claim.careTeam.sequence` |
| Claim.contained | Claim.contained | Equivalent | R4B `Claim.contained` maps as Equivalent to R5 `Claim.contained` |
| Claim.created | Claim.created | Equivalent | R4B `Claim.created` maps as Equivalent to R5 `Claim.created` |
| Claim.diagnosis | Claim.diagnosis | Equivalent | R4B `Claim.diagnosis` maps as Equivalent to R5 `Claim.diagnosis` |
| Claim.diagnosis.diagnosis[x] | Claim.diagnosis.diagnosis[x] | Equivalent | R4B `Claim.diagnosis.diagnosis[x]` maps as Equivalent to R5 `Claim.diagnosis.diagnosis[x]` |
| Claim.diagnosis.extension | Claim.diagnosis.extension | RelatedTo | R4B `Claim.diagnosis.extension` maps as RelatedTo to R5 `Claim.diagnosis.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Claim.diagnosis.id | Claim.diagnosis.id | Equivalent | R4B `Claim.diagnosis.id` maps as Equivalent to R5 `Claim.diagnosis.id` |
| Claim.diagnosis.modifierExtension | Claim.diagnosis.modifierExtension | RelatedTo | R4B `Claim.diagnosis.modifierExtension` maps as RelatedTo to R5 `Claim.diagnosis.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Claim.diagnosis.onAdmission | Claim.diagnosis.onAdmission | Equivalent | R4B `Claim.diagnosis.onAdmission` maps as Equivalent to R5 `Claim.diagnosis.onAdmission` |
| Claim.diagnosis.packageCode | - | DoesNotExistInTarget | R4B `Claim.diagnosis.packageCode` does not appear in the target and has no mapping for `Claim`. |
| Claim.diagnosis.sequence | Claim.diagnosis.sequence | Equivalent | R4B `Claim.diagnosis.sequence` maps as Equivalent to R5 `Claim.diagnosis.sequence` |
| Claim.diagnosis.type | Claim.diagnosis.type | Equivalent | R4B `Claim.diagnosis.type` maps as Equivalent to R5 `Claim.diagnosis.type` |
| Claim.enterer | Claim.enterer | SourceIsNarrowerThanTarget | R4B `Claim.enterer` maps as SourceIsNarrowerThanTarget to R5 `Claim.enterer` - enterer has change due to type change: R4B `enterer` `Reference` maps as SourceIsNarrowerThanTarget for R5 `enterer` |
| Claim.extension | Claim.extension | RelatedTo | R4B `Claim.extension` maps as RelatedTo to R5 `Claim.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Claim.facility | Claim.facility | SourceIsNarrowerThanTarget | R4B `Claim.facility` maps as SourceIsNarrowerThanTarget to R5 `Claim.facility` - facility has change due to type change: R4B `facility` `Reference` maps as SourceIsNarrowerThanTarget for R5 `facility` |
| Claim.fundsReserve | Claim.fundsReserve | Equivalent | R4B `Claim.fundsReserve` maps as Equivalent to R5 `Claim.fundsReserve` |
| Claim.id | Claim.id | Equivalent | R4B `Claim.id` maps as Equivalent to R5 `Claim.id` |
| Claim.identifier | Claim.identifier | Equivalent | R4B `Claim.identifier` maps as Equivalent to R5 `Claim.identifier` |
| Claim.implicitRules | Claim.implicitRules | Equivalent | R4B `Claim.implicitRules` maps as Equivalent to R5 `Claim.implicitRules` |
| Claim.insurance | Claim.insurance | Equivalent | R4B `Claim.insurance` maps as Equivalent to R5 `Claim.insurance` |
| Claim.insurance.businessArrangement | Claim.insurance.businessArrangement | Equivalent | R4B `Claim.insurance.businessArrangement` maps as Equivalent to R5 `Claim.insurance.businessArrangement` |
| Claim.insurance.claimResponse | Claim.insurance.claimResponse | Equivalent | R4B `Claim.insurance.claimResponse` maps as Equivalent to R5 `Claim.insurance.claimResponse` |
| Claim.insurance.coverage | Claim.insurance.coverage | Equivalent | R4B `Claim.insurance.coverage` maps as Equivalent to R5 `Claim.insurance.coverage` |
| Claim.insurance.extension | Claim.insurance.extension | RelatedTo | R4B `Claim.insurance.extension` maps as RelatedTo to R5 `Claim.insurance.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Claim.insurance.focal | Claim.insurance.focal | Equivalent | R4B `Claim.insurance.focal` maps as Equivalent to R5 `Claim.insurance.focal` |
| Claim.insurance.id | Claim.insurance.id | Equivalent | R4B `Claim.insurance.id` maps as Equivalent to R5 `Claim.insurance.id` |
| Claim.insurance.identifier | Claim.insurance.identifier | Equivalent | R4B `Claim.insurance.identifier` maps as Equivalent to R5 `Claim.insurance.identifier` |
| Claim.insurance.modifierExtension | Claim.insurance.modifierExtension | RelatedTo | R4B `Claim.insurance.modifierExtension` maps as RelatedTo to R5 `Claim.insurance.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Claim.insurance.preAuthRef | Claim.insurance.preAuthRef | Equivalent | R4B `Claim.insurance.preAuthRef` maps as Equivalent to R5 `Claim.insurance.preAuthRef` |
| Claim.insurance.sequence | Claim.insurance.sequence | Equivalent | R4B `Claim.insurance.sequence` maps as Equivalent to R5 `Claim.insurance.sequence` |
| Claim.insurer | Claim.insurer | Equivalent | R4B `Claim.insurer` maps as Equivalent to R5 `Claim.insurer` |
| Claim.item | Claim.item | Equivalent | R4B `Claim.item` maps as Equivalent to R5 `Claim.item` |
| Claim.item.bodySite | Claim.item.bodySite | RelatedTo | R4B `Claim.item.bodySite` maps as RelatedTo to R5 `Claim.item.bodySite` - bodySite changed from scalar to array (max cardinality from 1 to *); bodySite removed a binding requirement - Example http://hl7.org/fhir/ValueSet/tooth; bodySite has change due to type change: R4B bodySite CodeableConcept has no equivalent or mapped type in R5 bodySite |
| Claim.item.careTeamSequence | Claim.item.careTeamSequence | Equivalent | R4B `Claim.item.careTeamSequence` maps as Equivalent to R5 `Claim.item.careTeamSequence` |
| Claim.item.category | Claim.item.category | Equivalent | R4B `Claim.item.category` maps as Equivalent to R5 `Claim.item.category` |
| Claim.item.detail | Claim.item.detail | Equivalent | R4B `Claim.item.detail` maps as Equivalent to R5 `Claim.item.detail` |
| Claim.item.detail.category | Claim.item.detail.category | Equivalent | R4B `Claim.item.detail.category` maps as Equivalent to R5 `Claim.item.detail.category` |
| Claim.item.detail.extension | Claim.item.detail.extension | RelatedTo | R4B `Claim.item.detail.extension` maps as RelatedTo to R5 `Claim.item.detail.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Claim.item.detail.factor | Claim.item.detail.factor | Equivalent | R4B `Claim.item.detail.factor` maps as Equivalent to R5 `Claim.item.detail.factor` |
| Claim.item.detail.id | Claim.item.detail.id | Equivalent | R4B `Claim.item.detail.id` maps as Equivalent to R5 `Claim.item.detail.id` |
| Claim.item.detail.modifier | Claim.item.detail.modifier | Equivalent | R4B `Claim.item.detail.modifier` maps as Equivalent to R5 `Claim.item.detail.modifier` |
| Claim.item.detail.modifierExtension | Claim.item.detail.modifierExtension | RelatedTo | R4B `Claim.item.detail.modifierExtension` maps as RelatedTo to R5 `Claim.item.detail.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Claim.item.detail.net | Claim.item.detail.net | RelatedTo | R4B `Claim.item.detail.net` maps as RelatedTo to R5 `Claim.item.detail.net` - net has change due to type change: R4B `net` `Money` maps as RelatedTo for R5 `net` |
| Claim.item.detail.productOrService | Claim.item.detail.productOrService | Equivalent | R4B `Claim.item.detail.productOrService` maps as Equivalent to R5 `Claim.item.detail.productOrService` |
| Claim.item.detail.programCode | Claim.item.detail.programCode | Equivalent | R4B `Claim.item.detail.programCode` maps as Equivalent to R5 `Claim.item.detail.programCode` |
| Claim.item.detail.quantity | Claim.item.detail.quantity | Equivalent | R4B `Claim.item.detail.quantity` maps as Equivalent to R5 `Claim.item.detail.quantity` |
| Claim.item.detail.revenue | Claim.item.detail.revenue | Equivalent | R4B `Claim.item.detail.revenue` maps as Equivalent to R5 `Claim.item.detail.revenue` |
| Claim.item.detail.sequence | Claim.item.detail.sequence | Equivalent | R4B `Claim.item.detail.sequence` maps as Equivalent to R5 `Claim.item.detail.sequence` |
| Claim.item.detail.subDetail | Claim.item.detail.subDetail | Equivalent | R4B `Claim.item.detail.subDetail` maps as Equivalent to R5 `Claim.item.detail.subDetail` |
| Claim.item.detail.subDetail.category | Claim.item.detail.subDetail.category | Equivalent | R4B `Claim.item.detail.subDetail.category` maps as Equivalent to R5 `Claim.item.detail.subDetail.category` |
| Claim.item.detail.subDetail.extension | Claim.item.detail.subDetail.extension | RelatedTo | R4B `Claim.item.detail.subDetail.extension` maps as RelatedTo to R5 `Claim.item.detail.subDetail.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Claim.item.detail.subDetail.factor | Claim.item.detail.subDetail.factor | Equivalent | R4B `Claim.item.detail.subDetail.factor` maps as Equivalent to R5 `Claim.item.detail.subDetail.factor` |
| Claim.item.detail.subDetail.id | Claim.item.detail.subDetail.id | Equivalent | R4B `Claim.item.detail.subDetail.id` maps as Equivalent to R5 `Claim.item.detail.subDetail.id` |
| Claim.item.detail.subDetail.modifier | Claim.item.detail.subDetail.modifier | Equivalent | R4B `Claim.item.detail.subDetail.modifier` maps as Equivalent to R5 `Claim.item.detail.subDetail.modifier` |
| Claim.item.detail.subDetail.modifierExtension | Claim.item.detail.subDetail.modifierExtension | RelatedTo | R4B `Claim.item.detail.subDetail.modifierExtension` maps as RelatedTo to R5 `Claim.item.detail.subDetail.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Claim.item.detail.subDetail.net | Claim.item.detail.subDetail.net | RelatedTo | R4B `Claim.item.detail.subDetail.net` maps as RelatedTo to R5 `Claim.item.detail.subDetail.net` - net has change due to type change: R4B `net` `Money` maps as RelatedTo for R5 `net` |
| Claim.item.detail.subDetail.productOrService | Claim.item.detail.subDetail.productOrService | Equivalent | R4B `Claim.item.detail.subDetail.productOrService` maps as Equivalent to R5 `Claim.item.detail.subDetail.productOrService` |
| Claim.item.detail.subDetail.programCode | Claim.item.detail.subDetail.programCode | Equivalent | R4B `Claim.item.detail.subDetail.programCode` maps as Equivalent to R5 `Claim.item.detail.subDetail.programCode` |
| Claim.item.detail.subDetail.quantity | Claim.item.detail.subDetail.quantity | Equivalent | R4B `Claim.item.detail.subDetail.quantity` maps as Equivalent to R5 `Claim.item.detail.subDetail.quantity` |
| Claim.item.detail.subDetail.revenue | Claim.item.detail.subDetail.revenue | Equivalent | R4B `Claim.item.detail.subDetail.revenue` maps as Equivalent to R5 `Claim.item.detail.subDetail.revenue` |
| Claim.item.detail.subDetail.sequence | Claim.item.detail.subDetail.sequence | Equivalent | R4B `Claim.item.detail.subDetail.sequence` maps as Equivalent to R5 `Claim.item.detail.subDetail.sequence` |
| Claim.item.detail.subDetail.udi | Claim.item.detail.subDetail.udi | Equivalent | R4B `Claim.item.detail.subDetail.udi` maps as Equivalent to R5 `Claim.item.detail.subDetail.udi` |
| Claim.item.detail.subDetail.unitPrice | Claim.item.detail.subDetail.unitPrice | RelatedTo | R4B `Claim.item.detail.subDetail.unitPrice` maps as RelatedTo to R5 `Claim.item.detail.subDetail.unitPrice` - unitPrice has change due to type change: R4B `unitPrice` `Money` maps as RelatedTo for R5 `unitPrice` |
| Claim.item.detail.udi | Claim.item.detail.udi | Equivalent | R4B `Claim.item.detail.udi` maps as Equivalent to R5 `Claim.item.detail.udi` |
| Claim.item.detail.unitPrice | Claim.item.detail.unitPrice | RelatedTo | R4B `Claim.item.detail.unitPrice` maps as RelatedTo to R5 `Claim.item.detail.unitPrice` - unitPrice has change due to type change: R4B `unitPrice` `Money` maps as RelatedTo for R5 `unitPrice` |
| Claim.item.diagnosisSequence | Claim.item.diagnosisSequence | Equivalent | R4B `Claim.item.diagnosisSequence` maps as Equivalent to R5 `Claim.item.diagnosisSequence` |
| Claim.item.encounter | Claim.item.encounter | Equivalent | R4B `Claim.item.encounter` maps as Equivalent to R5 `Claim.item.encounter` |
| Claim.item.extension | Claim.item.extension | RelatedTo | R4B `Claim.item.extension` maps as RelatedTo to R5 `Claim.item.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Claim.item.factor | Claim.item.factor | Equivalent | R4B `Claim.item.factor` maps as Equivalent to R5 `Claim.item.factor` |
| Claim.item.id | Claim.item.id | Equivalent | R4B `Claim.item.id` maps as Equivalent to R5 `Claim.item.id` |
| Claim.item.informationSequence | Claim.item.informationSequence | Equivalent | R4B `Claim.item.informationSequence` maps as Equivalent to R5 `Claim.item.informationSequence` |
| Claim.item.location[x] | Claim.item.location[x] | Equivalent | R4B `Claim.item.location[x]` maps as Equivalent to R5 `Claim.item.location[x]` |
| Claim.item.modifier | Claim.item.modifier | Equivalent | R4B `Claim.item.modifier` maps as Equivalent to R5 `Claim.item.modifier` |
| Claim.item.modifierExtension | Claim.item.modifierExtension | RelatedTo | R4B `Claim.item.modifierExtension` maps as RelatedTo to R5 `Claim.item.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Claim.item.net | Claim.item.net | RelatedTo | R4B `Claim.item.net` maps as RelatedTo to R5 `Claim.item.net` - net has change due to type change: R4B `net` `Money` maps as RelatedTo for R5 `net` |
| Claim.item.procedureSequence | Claim.item.procedureSequence | Equivalent | R4B `Claim.item.procedureSequence` maps as Equivalent to R5 `Claim.item.procedureSequence` |
| Claim.item.productOrService | Claim.item.productOrService | Equivalent | R4B `Claim.item.productOrService` maps as Equivalent to R5 `Claim.item.productOrService` |
| Claim.item.programCode | Claim.item.programCode | Equivalent | R4B `Claim.item.programCode` maps as Equivalent to R5 `Claim.item.programCode` |
| Claim.item.quantity | Claim.item.quantity | Equivalent | R4B `Claim.item.quantity` maps as Equivalent to R5 `Claim.item.quantity` |
| Claim.item.revenue | Claim.item.revenue | Equivalent | R4B `Claim.item.revenue` maps as Equivalent to R5 `Claim.item.revenue` |
| Claim.item.sequence | Claim.item.sequence | Equivalent | R4B `Claim.item.sequence` maps as Equivalent to R5 `Claim.item.sequence` |
| Claim.item.serviced[x] | Claim.item.serviced[x] | Equivalent | R4B `Claim.item.serviced[x]` maps as Equivalent to R5 `Claim.item.serviced[x]` |
| Claim.item.subSite | - | DoesNotExistInTarget | R4B `Claim.item.subSite` does not appear in the target and has no mapping for `Claim`. |
| Claim.item.udi | Claim.item.udi | Equivalent | R4B `Claim.item.udi` maps as Equivalent to R5 `Claim.item.udi` |
| Claim.item.unitPrice | Claim.item.unitPrice | RelatedTo | R4B `Claim.item.unitPrice` maps as RelatedTo to R5 `Claim.item.unitPrice` - unitPrice has change due to type change: R4B `unitPrice` `Money` maps as RelatedTo for R5 `unitPrice` |
| Claim.language | Claim.language | RelatedTo | R4B `Claim.language` maps as RelatedTo to R5 `Claim.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Claim.meta | Claim.meta | Equivalent | R4B `Claim.meta` maps as Equivalent to R5 `Claim.meta` |
| Claim.modifierExtension | Claim.modifierExtension | RelatedTo | R4B `Claim.modifierExtension` maps as RelatedTo to R5 `Claim.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Claim.originalPrescription | Claim.originalPrescription | Equivalent | R4B `Claim.originalPrescription` maps as Equivalent to R5 `Claim.originalPrescription` |
| Claim.patient | Claim.patient | Equivalent | R4B `Claim.patient` maps as Equivalent to R5 `Claim.patient` |
| Claim.payee | Claim.payee | Equivalent | R4B `Claim.payee` maps as Equivalent to R5 `Claim.payee` |
| Claim.payee.extension | Claim.payee.extension | RelatedTo | R4B `Claim.payee.extension` maps as RelatedTo to R5 `Claim.payee.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Claim.payee.id | Claim.payee.id | Equivalent | R4B `Claim.payee.id` maps as Equivalent to R5 `Claim.payee.id` |
| Claim.payee.modifierExtension | Claim.payee.modifierExtension | RelatedTo | R4B `Claim.payee.modifierExtension` maps as RelatedTo to R5 `Claim.payee.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Claim.payee.party | Claim.payee.party | Equivalent | R4B `Claim.payee.party` maps as Equivalent to R5 `Claim.payee.party` |
| Claim.payee.type | Claim.payee.type | Equivalent | R4B `Claim.payee.type` maps as Equivalent to R5 `Claim.payee.type` |
| Claim.prescription | Claim.prescription | Equivalent | R4B `Claim.prescription` maps as Equivalent to R5 `Claim.prescription` |
| Claim.priority | Claim.priority | Equivalent | R4B `Claim.priority` maps as Equivalent to R5 `Claim.priority` |
| Claim.procedure | Claim.procedure | Equivalent | R4B `Claim.procedure` maps as Equivalent to R5 `Claim.procedure` |
| Claim.procedure.date | Claim.procedure.date | Equivalent | R4B `Claim.procedure.date` maps as Equivalent to R5 `Claim.procedure.date` |
| Claim.procedure.extension | Claim.procedure.extension | RelatedTo | R4B `Claim.procedure.extension` maps as RelatedTo to R5 `Claim.procedure.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Claim.procedure.id | Claim.procedure.id | Equivalent | R4B `Claim.procedure.id` maps as Equivalent to R5 `Claim.procedure.id` |
| Claim.procedure.modifierExtension | Claim.procedure.modifierExtension | RelatedTo | R4B `Claim.procedure.modifierExtension` maps as RelatedTo to R5 `Claim.procedure.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Claim.procedure.procedure[x] | Claim.procedure.procedure[x] | Equivalent | R4B `Claim.procedure.procedure[x]` maps as Equivalent to R5 `Claim.procedure.procedure[x]` |
| Claim.procedure.sequence | Claim.procedure.sequence | Equivalent | R4B `Claim.procedure.sequence` maps as Equivalent to R5 `Claim.procedure.sequence` |
| Claim.procedure.type | Claim.procedure.type | Equivalent | R4B `Claim.procedure.type` maps as Equivalent to R5 `Claim.procedure.type` |
| Claim.procedure.udi | Claim.procedure.udi | Equivalent | R4B `Claim.procedure.udi` maps as Equivalent to R5 `Claim.procedure.udi` |
| Claim.provider | Claim.provider | Equivalent | R4B `Claim.provider` maps as Equivalent to R5 `Claim.provider` |
| Claim.referral | Claim.referral | Equivalent | R4B `Claim.referral` maps as Equivalent to R5 `Claim.referral` |
| Claim.related | Claim.related | Equivalent | R4B `Claim.related` maps as Equivalent to R5 `Claim.related` |
| Claim.related.claim | Claim.related.claim | Equivalent | R4B `Claim.related.claim` maps as Equivalent to R5 `Claim.related.claim` |
| Claim.related.extension | Claim.related.extension | RelatedTo | R4B `Claim.related.extension` maps as RelatedTo to R5 `Claim.related.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Claim.related.id | Claim.related.id | Equivalent | R4B `Claim.related.id` maps as Equivalent to R5 `Claim.related.id` |
| Claim.related.modifierExtension | Claim.related.modifierExtension | RelatedTo | R4B `Claim.related.modifierExtension` maps as RelatedTo to R5 `Claim.related.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Claim.related.reference | Claim.related.reference | Equivalent | R4B `Claim.related.reference` maps as Equivalent to R5 `Claim.related.reference` |
| Claim.related.relationship | Claim.related.relationship | Equivalent | R4B `Claim.related.relationship` maps as Equivalent to R5 `Claim.related.relationship` |
| Claim.status | Claim.status | Equivalent | R4B `Claim.status` maps as Equivalent to R5 `Claim.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/fm-status|4.3.0 and http://hl7.org/fhir/ValueSet/fm-status|5.0.0 (Equivalent) |
| Claim.subType | Claim.subType | Equivalent | R4B `Claim.subType` maps as Equivalent to R5 `Claim.subType` |
| Claim.supportingInfo | Claim.supportingInfo | Equivalent | R4B `Claim.supportingInfo` maps as Equivalent to R5 `Claim.supportingInfo` |
| Claim.supportingInfo.category | Claim.supportingInfo.category | Equivalent | R4B `Claim.supportingInfo.category` maps as Equivalent to R5 `Claim.supportingInfo.category` |
| Claim.supportingInfo.code | Claim.supportingInfo.code | Equivalent | R4B `Claim.supportingInfo.code` maps as Equivalent to R5 `Claim.supportingInfo.code` |
| Claim.supportingInfo.extension | Claim.supportingInfo.extension | RelatedTo | R4B `Claim.supportingInfo.extension` maps as RelatedTo to R5 `Claim.supportingInfo.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Claim.supportingInfo.id | Claim.supportingInfo.id | Equivalent | R4B `Claim.supportingInfo.id` maps as Equivalent to R5 `Claim.supportingInfo.id` |
| Claim.supportingInfo.modifierExtension | Claim.supportingInfo.modifierExtension | RelatedTo | R4B `Claim.supportingInfo.modifierExtension` maps as RelatedTo to R5 `Claim.supportingInfo.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Claim.supportingInfo.reason | Claim.supportingInfo.reason | Equivalent | R4B `Claim.supportingInfo.reason` maps as Equivalent to R5 `Claim.supportingInfo.reason` |
| Claim.supportingInfo.sequence | Claim.supportingInfo.sequence | Equivalent | R4B `Claim.supportingInfo.sequence` maps as Equivalent to R5 `Claim.supportingInfo.sequence` |
| Claim.supportingInfo.timing[x] | Claim.supportingInfo.timing[x] | Equivalent | R4B `Claim.supportingInfo.timing[x]` maps as Equivalent to R5 `Claim.supportingInfo.timing[x]` |
| Claim.supportingInfo.value[x] | Claim.supportingInfo.value[x] | RelatedTo | R4B `Claim.supportingInfo.value[x]` maps as RelatedTo to R5 `Claim.supportingInfo.value[x]` - value[x] has change due to type change: R4B `value[x]` `Attachment` maps as RelatedTo for R5 `value[x]` |
| Claim.text | Claim.text | Equivalent | R4B `Claim.text` maps as Equivalent to R5 `Claim.text` |
| Claim.total | Claim.total | RelatedTo | R4B `Claim.total` maps as RelatedTo to R5 `Claim.total` - total has change due to type change: R4B `total` `Money` maps as RelatedTo for R5 `total` |
| Claim.type | Claim.type | Equivalent | R4B `Claim.type` maps as Equivalent to R5 `Claim.type` |
| Claim.use | Claim.use | Equivalent | R4B `Claim.use` maps as Equivalent to R5 `Claim.use` - use has compatible required binding for code type: http://hl7.org/fhir/ValueSet/claim-use|4.3.0 and http://hl7.org/fhir/ValueSet/claim-use|5.0.0 (Equivalent) |

