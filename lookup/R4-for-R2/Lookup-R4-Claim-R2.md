### Lookup for FHIR R4 Claim for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Claim.id | UseElementSameName | Claim.id |
| Claim.meta | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.meta |
| Claim.implicitRules | UseElementSameName | Claim.implicitRules |
| Claim.language | UseElementSameName | Claim.language |
| Claim.text | UseElementSameName | Claim.text |
| Claim.contained | UseElementSameName | Claim.contained |
| Claim.extension | UseElementSameName | Claim.extension |
| Claim.modifierExtension | UseElementSameName | Claim.modifierExtension |
| Claim.identifier | UseElementSameName | Claim.identifier |
| Claim.status | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.status |
| Claim.type | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.type |
| Claim.subType | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.subType |
| Claim.use | UseElementSameName | Claim.use |
| Claim.patient | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.patient |
| Claim.billablePeriod | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.billablePeriod |
| Claim.created | UseElementSameName | Claim.created |
| Claim.enterer | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.enterer |
| Claim.insurer | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.insurer |
| Claim.provider | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.provider |
| Claim.priority | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.priority |
| Claim.fundsReserve | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.fundsReserve |
| Claim.related | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.related |
| Claim.related.id | UseExtensionFromAncestor | - |
| Claim.related.extension | UseExtensionFromAncestor | - |
| Claim.related.modifierExtension | UseExtensionFromAncestor | - |
| Claim.related.claim | UseExtensionFromAncestor | - |
| Claim.related.relationship | UseExtensionFromAncestor | - |
| Claim.related.reference | UseExtensionFromAncestor | - |
| Claim.prescription | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.prescription |
| Claim.originalPrescription | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.originalPrescription |
| Claim.payee | UseElementSameName | Claim.payee |
| Claim.payee.id | UseElementSameName | Claim.payee.id |
| Claim.payee.extension | UseElementSameName | Claim.payee.extension |
| Claim.payee.modifierExtension | UseElementSameName | Claim.payee.modifierExtension |
| Claim.payee.type | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.payee.type |
| Claim.payee.party | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.payee.party |
| Claim.referral | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.referral |
| Claim.facility | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.facility |
| Claim.careTeam | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.careTeam |
| Claim.careTeam.id | UseExtensionFromAncestor | - |
| Claim.careTeam.extension | UseExtensionFromAncestor | - |
| Claim.careTeam.modifierExtension | UseExtensionFromAncestor | - |
| Claim.careTeam.sequence | UseExtensionFromAncestor | - |
| Claim.careTeam.provider | UseExtensionFromAncestor | - |
| Claim.careTeam.responsible | UseExtensionFromAncestor | - |
| Claim.careTeam.role | UseExtensionFromAncestor | - |
| Claim.careTeam.qualification | UseExtensionFromAncestor | - |
| Claim.supportingInfo | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.supportingInfo |
| Claim.supportingInfo.id | UseExtensionFromAncestor | - |
| Claim.supportingInfo.extension | UseExtensionFromAncestor | - |
| Claim.supportingInfo.modifierExtension | UseExtensionFromAncestor | - |
| Claim.supportingInfo.sequence | UseExtensionFromAncestor | - |
| Claim.supportingInfo.category | UseExtensionFromAncestor | - |
| Claim.supportingInfo.code | UseExtensionFromAncestor | - |
| Claim.supportingInfo.timing[x] | UseExtensionFromAncestor | - |
| Claim.supportingInfo.value[x] | UseExtensionFromAncestor | - |
| Claim.supportingInfo.reason | UseExtensionFromAncestor | - |
| Claim.diagnosis | UseElementSameName | Claim.diagnosis |
| Claim.diagnosis.id | UseElementSameName | Claim.diagnosis.id |
| Claim.diagnosis.extension | UseElementSameName | Claim.diagnosis.extension |
| Claim.diagnosis.modifierExtension | UseElementSameName | Claim.diagnosis.modifierExtension |
| Claim.diagnosis.sequence | UseElementSameName | Claim.diagnosis.sequence |
| Claim.diagnosis.diagnosis[x] | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.diagnosis.diagnosis |
| Claim.diagnosis.type | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.diagnosis.type |
| Claim.diagnosis.onAdmission | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.diagnosis.onAdmission |
| Claim.diagnosis.packageCode | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.diagnosis.packageCode |
| Claim.procedure | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.procedure |
| Claim.procedure.id | UseExtensionFromAncestor | - |
| Claim.procedure.extension | UseExtensionFromAncestor | - |
| Claim.procedure.modifierExtension | UseExtensionFromAncestor | - |
| Claim.procedure.sequence | UseExtensionFromAncestor | - |
| Claim.procedure.type | UseExtensionFromAncestor | - |
| Claim.procedure.date | UseExtensionFromAncestor | - |
| Claim.procedure.procedure[x] | UseExtensionFromAncestor | - |
| Claim.procedure.udi | UseExtensionFromAncestor | - |
| Claim.insurance | UseElementRenamed | Claim.coverage |
| Claim.insurance.id | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.insurance.id |
| Claim.insurance.extension | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.insurance.extension |
| Claim.insurance.modifierExtension | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.insurance.modifierExtension |
| Claim.insurance.sequence | UseElementRenamed | Claim.coverage.sequence |
| Claim.insurance.focal | UseElementRenamed | Claim.coverage.focal |
| Claim.insurance.identifier | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.insurance.identifier |
| Claim.insurance.coverage | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.insurance.coverage |
| Claim.insurance.businessArrangement | UseElementRenamed | Claim.coverage.businessArrangement |
| Claim.insurance.preAuthRef | UseElementRenamed | Claim.coverage.preAuthRef |
| Claim.insurance.claimResponse | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.insurance.claimResponse |
| Claim.accident | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.accident |
| Claim.accident.id | UseExtensionFromAncestor | - |
| Claim.accident.extension | UseExtensionFromAncestor | - |
| Claim.accident.modifierExtension | UseExtensionFromAncestor | - |
| Claim.accident.date | UseExtensionFromAncestor | - |
| Claim.accident.type | UseExtensionFromAncestor | - |
| Claim.accident.location[x] | UseExtensionFromAncestor | - |
| Claim.item | UseElementSameName | Claim.item |
| Claim.item.id | UseElementSameName | Claim.item.id |
| Claim.item.extension | UseElementSameName | Claim.item.extension |
| Claim.item.modifierExtension | UseElementSameName | Claim.item.modifierExtension |
| Claim.item.sequence | UseElementSameName | Claim.item.sequence |
| Claim.item.careTeamSequence | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.item.careTeamSequence |
| Claim.item.diagnosisSequence | UseElementRenamed | Claim.item.diagnosisLinkId |
| Claim.item.procedureSequence | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.item.procedureSequence |
| Claim.item.informationSequence | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.item.informationSequence |
| Claim.item.revenue | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.item.revenue |
| Claim.item.category | UseElementRenamed | Claim.item.type |
| Claim.item.productOrService | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.item.productOrService |
| Claim.item.modifier | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.item.modifier |
| Claim.item.programCode | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.item.programCode |
| Claim.item.serviced[x] | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.item.serviced |
| Claim.item.location[x] | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.item.location |
| Claim.item.quantity | UseElementSameName | Claim.item.quantity |
| Claim.item.unitPrice | UseElementSameName | Claim.item.unitPrice |
| Claim.item.factor | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.item.factor |
| Claim.item.net | UseElementSameName | Claim.item.net |
| Claim.item.udi | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.item.udi |
| Claim.item.bodySite | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.item.bodySite |
| Claim.item.subSite | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.item.subSite |
| Claim.item.encounter | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.item.encounter |
| Claim.item.detail | UseElementSameName | Claim.item.detail |
| Claim.item.detail.id | UseElementSameName | Claim.item.detail.id |
| Claim.item.detail.extension | UseElementSameName | Claim.item.detail.extension |
| Claim.item.detail.modifierExtension | UseElementSameName | Claim.item.detail.modifierExtension |
| Claim.item.detail.sequence | UseElementSameName | Claim.item.detail.sequence |
| Claim.item.detail.revenue | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.item.detail.revenue |
| Claim.item.detail.category | UseElementRenamed | Claim.item.detail.type |
| Claim.item.detail.productOrService | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.item.detail.productOrService |
| Claim.item.detail.modifier | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.item.detail.modifier |
| Claim.item.detail.programCode | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.item.detail.programCode |
| Claim.item.detail.quantity | UseElementSameName | Claim.item.detail.quantity |
| Claim.item.detail.unitPrice | UseElementSameName | Claim.item.detail.unitPrice |
| Claim.item.detail.factor | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.item.detail.factor |
| Claim.item.detail.net | UseElementSameName | Claim.item.detail.net |
| Claim.item.detail.udi | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.item.detail.udi |
| Claim.item.detail.subDetail | UseElementSameName | Claim.item.detail.subDetail |
| Claim.item.detail.subDetail.id | UseElementSameName | Claim.item.detail.subDetail.id |
| Claim.item.detail.subDetail.extension | UseElementSameName | Claim.item.detail.subDetail.extension |
| Claim.item.detail.subDetail.modifierExtension | UseElementSameName | Claim.item.detail.subDetail.modifierExtension |
| Claim.item.detail.subDetail.sequence | UseElementSameName | Claim.item.detail.subDetail.sequence |
| Claim.item.detail.subDetail.revenue | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.item.detail.subDetail.revenue |
| Claim.item.detail.subDetail.category | UseElementRenamed | Claim.item.detail.subDetail.type |
| Claim.item.detail.subDetail.productOrService | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.item.detail.subDetail.productOrService |
| Claim.item.detail.subDetail.modifier | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.item.detail.subDetail.modifier |
| Claim.item.detail.subDetail.programCode | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.item.detail.subDetail.programCode |
| Claim.item.detail.subDetail.quantity | UseElementSameName | Claim.item.detail.subDetail.quantity |
| Claim.item.detail.subDetail.unitPrice | UseElementSameName | Claim.item.detail.subDetail.unitPrice |
| Claim.item.detail.subDetail.factor | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.item.detail.subDetail.factor |
| Claim.item.detail.subDetail.net | UseElementSameName | Claim.item.detail.subDetail.net |
| Claim.item.detail.subDetail.udi | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.item.detail.subDetail.udi |
| Claim.total | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Claim.total |
