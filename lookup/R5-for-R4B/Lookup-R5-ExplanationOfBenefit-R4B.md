### Lookup for FHIR R5 ExplanationOfBenefit for use in FHIR R4B

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| ExplanationOfBenefit.id | UseElementSameName | ExplanationOfBenefit.id |
| ExplanationOfBenefit.meta | UseElementSameName | ExplanationOfBenefit.meta |
| ExplanationOfBenefit.implicitRules | UseElementSameName | ExplanationOfBenefit.implicitRules |
| ExplanationOfBenefit.language | UseElementSameName | ExplanationOfBenefit.language |
| ExplanationOfBenefit.text | UseElementSameName | ExplanationOfBenefit.text |
| ExplanationOfBenefit.contained | UseElementSameName | ExplanationOfBenefit.contained |
| ExplanationOfBenefit.extension | UseElementSameName | ExplanationOfBenefit.extension |
| ExplanationOfBenefit.modifierExtension | UseElementSameName | ExplanationOfBenefit.modifierExtension |
| ExplanationOfBenefit.identifier | UseElementSameName | ExplanationOfBenefit.identifier |
| ExplanationOfBenefit.traceNumber | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.traceNumber |
| ExplanationOfBenefit.status | UseElementSameName | ExplanationOfBenefit.status |
| ExplanationOfBenefit.type | UseElementSameName | ExplanationOfBenefit.type |
| ExplanationOfBenefit.subType | UseElementSameName | ExplanationOfBenefit.subType |
| ExplanationOfBenefit.use | UseElementSameName | ExplanationOfBenefit.use |
| ExplanationOfBenefit.patient | UseElementSameName | ExplanationOfBenefit.patient |
| ExplanationOfBenefit.billablePeriod | UseElementSameName | ExplanationOfBenefit.billablePeriod |
| ExplanationOfBenefit.created | UseElementSameName | ExplanationOfBenefit.created |
| ExplanationOfBenefit.enterer | UseElementSameName | ExplanationOfBenefit.enterer |
| ExplanationOfBenefit.insurer | UseElementSameName | ExplanationOfBenefit.insurer |
| ExplanationOfBenefit.provider | UseOneOfElements | ExplanationOfBenefit.provider,ExplanationOfBenefit.provider |
| ExplanationOfBenefit.priority | UseElementSameName | ExplanationOfBenefit.priority |
| ExplanationOfBenefit.fundsReserveRequested | UseElementSameName | ExplanationOfBenefit.fundsReserveRequested |
| ExplanationOfBenefit.fundsReserve | UseElementSameName | ExplanationOfBenefit.fundsReserve |
| ExplanationOfBenefit.related | UseElementSameName | ExplanationOfBenefit.related |
| ExplanationOfBenefit.related.id | UseElementSameName | ExplanationOfBenefit.related.id |
| ExplanationOfBenefit.related.extension | UseElementSameName | ExplanationOfBenefit.related.extension |
| ExplanationOfBenefit.related.modifierExtension | UseElementSameName | ExplanationOfBenefit.related.modifierExtension |
| ExplanationOfBenefit.related.claim | UseElementSameName | ExplanationOfBenefit.related.claim |
| ExplanationOfBenefit.related.relationship | UseElementSameName | ExplanationOfBenefit.related.relationship |
| ExplanationOfBenefit.related.reference | UseElementSameName | ExplanationOfBenefit.related.reference |
| ExplanationOfBenefit.prescription | UseElementSameName | ExplanationOfBenefit.prescription |
| ExplanationOfBenefit.originalPrescription | UseElementSameName | ExplanationOfBenefit.originalPrescription |
| ExplanationOfBenefit.event | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.event |
| ExplanationOfBenefit.event.id | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.event.extension | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.event.modifierExtension | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.event.type | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.event.when[x] | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.payee | UseElementSameName | ExplanationOfBenefit.payee |
| ExplanationOfBenefit.payee.id | UseElementSameName | ExplanationOfBenefit.payee.id |
| ExplanationOfBenefit.payee.extension | UseElementSameName | ExplanationOfBenefit.payee.extension |
| ExplanationOfBenefit.payee.modifierExtension | UseElementSameName | ExplanationOfBenefit.payee.modifierExtension |
| ExplanationOfBenefit.payee.type | UseElementSameName | ExplanationOfBenefit.payee.type |
| ExplanationOfBenefit.payee.party | UseElementSameName | ExplanationOfBenefit.payee.party |
| ExplanationOfBenefit.referral | UseElementSameName | ExplanationOfBenefit.referral |
| ExplanationOfBenefit.encounter | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.encounter |
| ExplanationOfBenefit.facility | UseElementSameName | ExplanationOfBenefit.facility |
| ExplanationOfBenefit.claim | UseElementSameName | ExplanationOfBenefit.claim |
| ExplanationOfBenefit.claimResponse | UseElementSameName | ExplanationOfBenefit.claimResponse |
| ExplanationOfBenefit.outcome | UseElementSameName | ExplanationOfBenefit.outcome |
| ExplanationOfBenefit.decision | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.decision |
| ExplanationOfBenefit.disposition | UseElementSameName | ExplanationOfBenefit.disposition |
| ExplanationOfBenefit.preAuthRef | UseElementSameName | ExplanationOfBenefit.preAuthRef |
| ExplanationOfBenefit.preAuthRefPeriod | UseElementSameName | ExplanationOfBenefit.preAuthRefPeriod |
| ExplanationOfBenefit.diagnosisRelatedGroup | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.diagnosisRelatedGroup |
| ExplanationOfBenefit.careTeam | UseElementSameName | ExplanationOfBenefit.careTeam |
| ExplanationOfBenefit.careTeam.id | UseElementSameName | ExplanationOfBenefit.careTeam.id |
| ExplanationOfBenefit.careTeam.extension | UseElementSameName | ExplanationOfBenefit.careTeam.extension |
| ExplanationOfBenefit.careTeam.modifierExtension | UseElementSameName | ExplanationOfBenefit.careTeam.modifierExtension |
| ExplanationOfBenefit.careTeam.sequence | UseElementSameName | ExplanationOfBenefit.careTeam.sequence |
| ExplanationOfBenefit.careTeam.provider | UseElementSameName | ExplanationOfBenefit.careTeam.provider |
| ExplanationOfBenefit.careTeam.responsible | UseElementSameName | ExplanationOfBenefit.careTeam.responsible |
| ExplanationOfBenefit.careTeam.role | UseElementSameName | ExplanationOfBenefit.careTeam.role |
| ExplanationOfBenefit.careTeam.specialty | UseElementRenamed | ExplanationOfBenefit.careTeam.qualification |
| ExplanationOfBenefit.supportingInfo | UseElementSameName | ExplanationOfBenefit.supportingInfo |
| ExplanationOfBenefit.supportingInfo.id | UseElementSameName | ExplanationOfBenefit.supportingInfo.id |
| ExplanationOfBenefit.supportingInfo.extension | UseElementSameName | ExplanationOfBenefit.supportingInfo.extension |
| ExplanationOfBenefit.supportingInfo.modifierExtension | UseElementSameName | ExplanationOfBenefit.supportingInfo.modifierExtension |
| ExplanationOfBenefit.supportingInfo.sequence | UseElementSameName | ExplanationOfBenefit.supportingInfo.sequence |
| ExplanationOfBenefit.supportingInfo.category | UseElementSameName | ExplanationOfBenefit.supportingInfo.category |
| ExplanationOfBenefit.supportingInfo.code | UseElementSameName | ExplanationOfBenefit.supportingInfo.code |
| ExplanationOfBenefit.supportingInfo.timing[x] | UseElementSameName | ExplanationOfBenefit.supportingInfo.timing[x] |
| ExplanationOfBenefit.supportingInfo.value[x] | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.supportingInfo.value |
| ExplanationOfBenefit.supportingInfo.reason | UseElementSameName | ExplanationOfBenefit.supportingInfo.reason |
| ExplanationOfBenefit.diagnosis | UseElementSameName | ExplanationOfBenefit.diagnosis |
| ExplanationOfBenefit.diagnosis.id | UseElementSameName | ExplanationOfBenefit.diagnosis.id |
| ExplanationOfBenefit.diagnosis.extension | UseElementSameName | ExplanationOfBenefit.diagnosis.extension |
| ExplanationOfBenefit.diagnosis.modifierExtension | UseElementSameName | ExplanationOfBenefit.diagnosis.modifierExtension |
| ExplanationOfBenefit.diagnosis.sequence | UseElementSameName | ExplanationOfBenefit.diagnosis.sequence |
| ExplanationOfBenefit.diagnosis.diagnosis[x] | UseElementSameName | ExplanationOfBenefit.diagnosis.diagnosis[x] |
| ExplanationOfBenefit.diagnosis.type | UseElementSameName | ExplanationOfBenefit.diagnosis.type |
| ExplanationOfBenefit.diagnosis.onAdmission | UseElementSameName | ExplanationOfBenefit.diagnosis.onAdmission |
| ExplanationOfBenefit.procedure | UseElementSameName | ExplanationOfBenefit.procedure |
| ExplanationOfBenefit.procedure.id | UseElementSameName | ExplanationOfBenefit.procedure.id |
| ExplanationOfBenefit.procedure.extension | UseElementSameName | ExplanationOfBenefit.procedure.extension |
| ExplanationOfBenefit.procedure.modifierExtension | UseElementSameName | ExplanationOfBenefit.procedure.modifierExtension |
| ExplanationOfBenefit.procedure.sequence | UseElementSameName | ExplanationOfBenefit.procedure.sequence |
| ExplanationOfBenefit.procedure.type | UseElementSameName | ExplanationOfBenefit.procedure.type |
| ExplanationOfBenefit.procedure.date | UseElementSameName | ExplanationOfBenefit.procedure.date |
| ExplanationOfBenefit.procedure.procedure[x] | UseElementSameName | ExplanationOfBenefit.procedure.procedure[x] |
| ExplanationOfBenefit.procedure.udi | UseElementSameName | ExplanationOfBenefit.procedure.udi |
| ExplanationOfBenefit.precedence | UseElementSameName | ExplanationOfBenefit.precedence |
| ExplanationOfBenefit.insurance | UseElementSameName | ExplanationOfBenefit.insurance |
| ExplanationOfBenefit.insurance.id | UseElementSameName | ExplanationOfBenefit.insurance.id |
| ExplanationOfBenefit.insurance.extension | UseElementSameName | ExplanationOfBenefit.insurance.extension |
| ExplanationOfBenefit.insurance.modifierExtension | UseElementSameName | ExplanationOfBenefit.insurance.modifierExtension |
| ExplanationOfBenefit.insurance.focal | UseElementSameName | ExplanationOfBenefit.insurance.focal |
| ExplanationOfBenefit.insurance.coverage | UseElementSameName | ExplanationOfBenefit.insurance.coverage |
| ExplanationOfBenefit.insurance.preAuthRef | UseElementSameName | ExplanationOfBenefit.insurance.preAuthRef |
| ExplanationOfBenefit.accident | UseElementSameName | ExplanationOfBenefit.accident |
| ExplanationOfBenefit.accident.id | UseElementSameName | ExplanationOfBenefit.accident.id |
| ExplanationOfBenefit.accident.extension | UseElementSameName | ExplanationOfBenefit.accident.extension |
| ExplanationOfBenefit.accident.modifierExtension | UseElementSameName | ExplanationOfBenefit.accident.modifierExtension |
| ExplanationOfBenefit.accident.date | UseElementSameName | ExplanationOfBenefit.accident.date |
| ExplanationOfBenefit.accident.type | UseElementSameName | ExplanationOfBenefit.accident.type |
| ExplanationOfBenefit.accident.location[x] | UseElementSameName | ExplanationOfBenefit.accident.location[x] |
| ExplanationOfBenefit.patientPaid | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.patientPaid |
| ExplanationOfBenefit.item | UseElementSameName | ExplanationOfBenefit.item |
| ExplanationOfBenefit.item.id | UseElementSameName | ExplanationOfBenefit.item.id |
| ExplanationOfBenefit.item.extension | UseElementSameName | ExplanationOfBenefit.item.extension |
| ExplanationOfBenefit.item.modifierExtension | UseElementSameName | ExplanationOfBenefit.item.modifierExtension |
| ExplanationOfBenefit.item.sequence | UseElementSameName | ExplanationOfBenefit.item.sequence |
| ExplanationOfBenefit.item.careTeamSequence | UseElementSameName | ExplanationOfBenefit.item.careTeamSequence |
| ExplanationOfBenefit.item.diagnosisSequence | UseElementSameName | ExplanationOfBenefit.item.diagnosisSequence |
| ExplanationOfBenefit.item.procedureSequence | UseElementSameName | ExplanationOfBenefit.item.procedureSequence |
| ExplanationOfBenefit.item.informationSequence | UseElementSameName | ExplanationOfBenefit.item.informationSequence |
| ExplanationOfBenefit.item.traceNumber | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.item.traceNumber |
| ExplanationOfBenefit.item.revenue | UseElementSameName | ExplanationOfBenefit.item.revenue |
| ExplanationOfBenefit.item.category | UseElementSameName | ExplanationOfBenefit.item.category |
| ExplanationOfBenefit.item.productOrService | UseElementSameName | ExplanationOfBenefit.item.productOrService |
| ExplanationOfBenefit.item.productOrServiceEnd | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.item.productOrServiceEnd |
| ExplanationOfBenefit.item.request | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.item.request |
| ExplanationOfBenefit.item.modifier | UseElementSameName | ExplanationOfBenefit.item.modifier |
| ExplanationOfBenefit.item.programCode | UseElementSameName | ExplanationOfBenefit.item.programCode |
| ExplanationOfBenefit.item.serviced[x] | UseElementSameName | ExplanationOfBenefit.item.serviced[x] |
| ExplanationOfBenefit.item.location[x] | UseElementSameName | ExplanationOfBenefit.item.location[x] |
| ExplanationOfBenefit.item.patientPaid | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.item.patientPaid |
| ExplanationOfBenefit.item.quantity | UseElementSameName | ExplanationOfBenefit.item.quantity |
| ExplanationOfBenefit.item.unitPrice | UseElementSameName | ExplanationOfBenefit.item.unitPrice |
| ExplanationOfBenefit.item.factor | UseElementSameName | ExplanationOfBenefit.item.factor |
| ExplanationOfBenefit.item.tax | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.item.tax |
| ExplanationOfBenefit.item.net | UseElementSameName | ExplanationOfBenefit.item.net |
| ExplanationOfBenefit.item.udi | UseElementSameName | ExplanationOfBenefit.item.udi |
| ExplanationOfBenefit.item.bodySite | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.item.bodySite |
| ExplanationOfBenefit.item.bodySite.id | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.item.bodySite.extension | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.item.bodySite.modifierExtension | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.item.bodySite.site | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.item.bodySite.subSite | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.item.encounter | UseElementSameName | ExplanationOfBenefit.item.encounter |
| ExplanationOfBenefit.item.noteNumber | UseElementSameName | ExplanationOfBenefit.item.noteNumber |
| ExplanationOfBenefit.item.reviewOutcome | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.item.reviewOutcome |
| ExplanationOfBenefit.item.reviewOutcome.id | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.item.reviewOutcome.extension | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.item.reviewOutcome.modifierExtension | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.item.reviewOutcome.decision | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.item.reviewOutcome.reason | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.item.reviewOutcome.preAuthRef | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.item.reviewOutcome.preAuthPeriod | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.item.adjudication | UseElementSameName | ExplanationOfBenefit.item.adjudication |
| ExplanationOfBenefit.item.adjudication.id | UseElementSameName | ExplanationOfBenefit.item.adjudication.id |
| ExplanationOfBenefit.item.adjudication.extension | UseElementSameName | ExplanationOfBenefit.item.adjudication.extension |
| ExplanationOfBenefit.item.adjudication.modifierExtension | UseElementSameName | ExplanationOfBenefit.item.adjudication.modifierExtension |
| ExplanationOfBenefit.item.adjudication.category | UseElementSameName | ExplanationOfBenefit.item.adjudication.category |
| ExplanationOfBenefit.item.adjudication.reason | UseElementSameName | ExplanationOfBenefit.item.adjudication.reason |
| ExplanationOfBenefit.item.adjudication.amount | UseElementSameName | ExplanationOfBenefit.item.adjudication.amount |
| ExplanationOfBenefit.item.adjudication.quantity | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.item.adjudication.quantity |
| ExplanationOfBenefit.item.detail | UseElementSameName | ExplanationOfBenefit.item.detail |
| ExplanationOfBenefit.item.detail.id | UseElementSameName | ExplanationOfBenefit.item.detail.id |
| ExplanationOfBenefit.item.detail.extension | UseElementSameName | ExplanationOfBenefit.item.detail.extension |
| ExplanationOfBenefit.item.detail.modifierExtension | UseElementSameName | ExplanationOfBenefit.item.detail.modifierExtension |
| ExplanationOfBenefit.item.detail.sequence | UseElementSameName | ExplanationOfBenefit.item.detail.sequence |
| ExplanationOfBenefit.item.detail.traceNumber | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.item.detail.traceNumber |
| ExplanationOfBenefit.item.detail.revenue | UseElementSameName | ExplanationOfBenefit.item.detail.revenue |
| ExplanationOfBenefit.item.detail.category | UseElementSameName | ExplanationOfBenefit.item.detail.category |
| ExplanationOfBenefit.item.detail.productOrService | UseElementSameName | ExplanationOfBenefit.item.detail.productOrService |
| ExplanationOfBenefit.item.detail.productOrServiceEnd | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.item.detail.productOrServiceEnd |
| ExplanationOfBenefit.item.detail.modifier | UseElementSameName | ExplanationOfBenefit.item.detail.modifier |
| ExplanationOfBenefit.item.detail.programCode | UseElementSameName | ExplanationOfBenefit.item.detail.programCode |
| ExplanationOfBenefit.item.detail.patientPaid | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.item.detail.patientPaid |
| ExplanationOfBenefit.item.detail.quantity | UseElementSameName | ExplanationOfBenefit.item.detail.quantity |
| ExplanationOfBenefit.item.detail.unitPrice | UseElementSameName | ExplanationOfBenefit.item.detail.unitPrice |
| ExplanationOfBenefit.item.detail.factor | UseElementSameName | ExplanationOfBenefit.item.detail.factor |
| ExplanationOfBenefit.item.detail.tax | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.item.detail.tax |
| ExplanationOfBenefit.item.detail.net | UseElementSameName | ExplanationOfBenefit.item.detail.net |
| ExplanationOfBenefit.item.detail.udi | UseElementSameName | ExplanationOfBenefit.item.detail.udi |
| ExplanationOfBenefit.item.detail.noteNumber | UseElementSameName | ExplanationOfBenefit.item.detail.noteNumber |
| ExplanationOfBenefit.item.detail.reviewOutcome | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.item.detail.reviewOutcome |
| ExplanationOfBenefit.item.detail.adjudication | UseElementSameName | ExplanationOfBenefit.item.detail.adjudication |
| ExplanationOfBenefit.item.detail.subDetail | UseElementSameName | ExplanationOfBenefit.item.detail.subDetail |
| ExplanationOfBenefit.item.detail.subDetail.id | UseElementSameName | ExplanationOfBenefit.item.detail.subDetail.id |
| ExplanationOfBenefit.item.detail.subDetail.extension | UseElementSameName | ExplanationOfBenefit.item.detail.subDetail.extension |
| ExplanationOfBenefit.item.detail.subDetail.modifierExtension | UseElementSameName | ExplanationOfBenefit.item.detail.subDetail.modifierExtension |
| ExplanationOfBenefit.item.detail.subDetail.sequence | UseElementSameName | ExplanationOfBenefit.item.detail.subDetail.sequence |
| ExplanationOfBenefit.item.detail.subDetail.traceNumber | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.item.detail.subDetail.traceNumber |
| ExplanationOfBenefit.item.detail.subDetail.revenue | UseElementSameName | ExplanationOfBenefit.item.detail.subDetail.revenue |
| ExplanationOfBenefit.item.detail.subDetail.category | UseElementSameName | ExplanationOfBenefit.item.detail.subDetail.category |
| ExplanationOfBenefit.item.detail.subDetail.productOrService | UseElementSameName | ExplanationOfBenefit.item.detail.subDetail.productOrService |
| ExplanationOfBenefit.item.detail.subDetail.productOrServiceEnd | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.item.detail.subDetail.productOrServiceEnd |
| ExplanationOfBenefit.item.detail.subDetail.modifier | UseElementSameName | ExplanationOfBenefit.item.detail.subDetail.modifier |
| ExplanationOfBenefit.item.detail.subDetail.programCode | UseElementSameName | ExplanationOfBenefit.item.detail.subDetail.programCode |
| ExplanationOfBenefit.item.detail.subDetail.patientPaid | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.item.detail.subDetail.patientPaid |
| ExplanationOfBenefit.item.detail.subDetail.quantity | UseElementSameName | ExplanationOfBenefit.item.detail.subDetail.quantity |
| ExplanationOfBenefit.item.detail.subDetail.unitPrice | UseElementSameName | ExplanationOfBenefit.item.detail.subDetail.unitPrice |
| ExplanationOfBenefit.item.detail.subDetail.factor | UseElementSameName | ExplanationOfBenefit.item.detail.subDetail.factor |
| ExplanationOfBenefit.item.detail.subDetail.tax | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.item.detail.subDetail.tax |
| ExplanationOfBenefit.item.detail.subDetail.net | UseElementSameName | ExplanationOfBenefit.item.detail.subDetail.net |
| ExplanationOfBenefit.item.detail.subDetail.udi | UseElementSameName | ExplanationOfBenefit.item.detail.subDetail.udi |
| ExplanationOfBenefit.item.detail.subDetail.noteNumber | UseElementSameName | ExplanationOfBenefit.item.detail.subDetail.noteNumber |
| ExplanationOfBenefit.item.detail.subDetail.reviewOutcome | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.item.detail.subDetail.reviewOutcome |
| ExplanationOfBenefit.item.detail.subDetail.adjudication | UseElementSameName | ExplanationOfBenefit.item.detail.subDetail.adjudication |
| ExplanationOfBenefit.addItem | UseElementSameName | ExplanationOfBenefit.addItem |
| ExplanationOfBenefit.addItem.id | UseElementSameName | ExplanationOfBenefit.addItem.id |
| ExplanationOfBenefit.addItem.extension | UseElementSameName | ExplanationOfBenefit.addItem.extension |
| ExplanationOfBenefit.addItem.modifierExtension | UseElementSameName | ExplanationOfBenefit.addItem.modifierExtension |
| ExplanationOfBenefit.addItem.itemSequence | UseElementSameName | ExplanationOfBenefit.addItem.itemSequence |
| ExplanationOfBenefit.addItem.detailSequence | UseElementSameName | ExplanationOfBenefit.addItem.detailSequence |
| ExplanationOfBenefit.addItem.subDetailSequence | UseElementSameName | ExplanationOfBenefit.addItem.subDetailSequence |
| ExplanationOfBenefit.addItem.traceNumber | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.traceNumber |
| ExplanationOfBenefit.addItem.provider | UseElementSameName | ExplanationOfBenefit.addItem.provider |
| ExplanationOfBenefit.addItem.revenue | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.revenue |
| ExplanationOfBenefit.addItem.productOrService | UseElementSameName | ExplanationOfBenefit.addItem.productOrService |
| ExplanationOfBenefit.addItem.productOrServiceEnd | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.productOrServiceEnd |
| ExplanationOfBenefit.addItem.request | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.request |
| ExplanationOfBenefit.addItem.modifier | UseElementSameName | ExplanationOfBenefit.addItem.modifier |
| ExplanationOfBenefit.addItem.programCode | UseElementSameName | ExplanationOfBenefit.addItem.programCode |
| ExplanationOfBenefit.addItem.serviced[x] | UseElementSameName | ExplanationOfBenefit.addItem.serviced[x] |
| ExplanationOfBenefit.addItem.location[x] | UseElementSameName | ExplanationOfBenefit.addItem.location[x] |
| ExplanationOfBenefit.addItem.patientPaid | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.patientPaid |
| ExplanationOfBenefit.addItem.quantity | UseElementSameName | ExplanationOfBenefit.addItem.quantity |
| ExplanationOfBenefit.addItem.unitPrice | UseElementSameName | ExplanationOfBenefit.addItem.unitPrice |
| ExplanationOfBenefit.addItem.factor | UseElementSameName | ExplanationOfBenefit.addItem.factor |
| ExplanationOfBenefit.addItem.tax | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.tax |
| ExplanationOfBenefit.addItem.net | UseElementSameName | ExplanationOfBenefit.addItem.net |
| ExplanationOfBenefit.addItem.bodySite | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.bodySite |
| ExplanationOfBenefit.addItem.bodySite.id | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.addItem.bodySite.extension | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.addItem.bodySite.modifierExtension | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.addItem.bodySite.site | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.addItem.bodySite.subSite | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.addItem.noteNumber | UseElementSameName | ExplanationOfBenefit.addItem.noteNumber |
| ExplanationOfBenefit.addItem.reviewOutcome | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.reviewOutcome |
| ExplanationOfBenefit.addItem.adjudication | UseElementSameName | ExplanationOfBenefit.addItem.adjudication |
| ExplanationOfBenefit.addItem.detail | UseElementSameName | ExplanationOfBenefit.addItem.detail |
| ExplanationOfBenefit.addItem.detail.id | UseElementSameName | ExplanationOfBenefit.addItem.detail.id |
| ExplanationOfBenefit.addItem.detail.extension | UseElementSameName | ExplanationOfBenefit.addItem.detail.extension |
| ExplanationOfBenefit.addItem.detail.modifierExtension | UseElementSameName | ExplanationOfBenefit.addItem.detail.modifierExtension |
| ExplanationOfBenefit.addItem.detail.traceNumber | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.detail.traceNumber |
| ExplanationOfBenefit.addItem.detail.revenue | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.detail.revenue |
| ExplanationOfBenefit.addItem.detail.productOrService | UseElementSameName | ExplanationOfBenefit.addItem.detail.productOrService |
| ExplanationOfBenefit.addItem.detail.productOrServiceEnd | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.detail.productOrServiceEnd |
| ExplanationOfBenefit.addItem.detail.modifier | UseElementSameName | ExplanationOfBenefit.addItem.detail.modifier |
| ExplanationOfBenefit.addItem.detail.patientPaid | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.detail.patientPaid |
| ExplanationOfBenefit.addItem.detail.quantity | UseElementSameName | ExplanationOfBenefit.addItem.detail.quantity |
| ExplanationOfBenefit.addItem.detail.unitPrice | UseElementSameName | ExplanationOfBenefit.addItem.detail.unitPrice |
| ExplanationOfBenefit.addItem.detail.factor | UseElementSameName | ExplanationOfBenefit.addItem.detail.factor |
| ExplanationOfBenefit.addItem.detail.tax | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.detail.tax |
| ExplanationOfBenefit.addItem.detail.net | UseElementSameName | ExplanationOfBenefit.addItem.detail.net |
| ExplanationOfBenefit.addItem.detail.noteNumber | UseElementSameName | ExplanationOfBenefit.addItem.detail.noteNumber |
| ExplanationOfBenefit.addItem.detail.reviewOutcome | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.detail.reviewOutcome |
| ExplanationOfBenefit.addItem.detail.adjudication | UseElementSameName | ExplanationOfBenefit.addItem.detail.adjudication |
| ExplanationOfBenefit.addItem.detail.subDetail | UseElementSameName | ExplanationOfBenefit.addItem.detail.subDetail |
| ExplanationOfBenefit.addItem.detail.subDetail.id | UseElementSameName | ExplanationOfBenefit.addItem.detail.subDetail.id |
| ExplanationOfBenefit.addItem.detail.subDetail.extension | UseElementSameName | ExplanationOfBenefit.addItem.detail.subDetail.extension |
| ExplanationOfBenefit.addItem.detail.subDetail.modifierExtension | UseElementSameName | ExplanationOfBenefit.addItem.detail.subDetail.modifierExtension |
| ExplanationOfBenefit.addItem.detail.subDetail.traceNumber | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.detail.subDetail.traceNumber |
| ExplanationOfBenefit.addItem.detail.subDetail.revenue | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.detail.subDetail.revenue |
| ExplanationOfBenefit.addItem.detail.subDetail.productOrService | UseElementSameName | ExplanationOfBenefit.addItem.detail.subDetail.productOrService |
| ExplanationOfBenefit.addItem.detail.subDetail.productOrServiceEnd | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.detail.subDetail.productOrServiceEnd |
| ExplanationOfBenefit.addItem.detail.subDetail.modifier | UseElementSameName | ExplanationOfBenefit.addItem.detail.subDetail.modifier |
| ExplanationOfBenefit.addItem.detail.subDetail.patientPaid | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.detail.subDetail.patientPaid |
| ExplanationOfBenefit.addItem.detail.subDetail.quantity | UseElementSameName | ExplanationOfBenefit.addItem.detail.subDetail.quantity |
| ExplanationOfBenefit.addItem.detail.subDetail.unitPrice | UseElementSameName | ExplanationOfBenefit.addItem.detail.subDetail.unitPrice |
| ExplanationOfBenefit.addItem.detail.subDetail.factor | UseElementSameName | ExplanationOfBenefit.addItem.detail.subDetail.factor |
| ExplanationOfBenefit.addItem.detail.subDetail.tax | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.detail.subDetail.tax |
| ExplanationOfBenefit.addItem.detail.subDetail.net | UseElementSameName | ExplanationOfBenefit.addItem.detail.subDetail.net |
| ExplanationOfBenefit.addItem.detail.subDetail.noteNumber | UseElementSameName | ExplanationOfBenefit.addItem.detail.subDetail.noteNumber |
| ExplanationOfBenefit.addItem.detail.subDetail.reviewOutcome | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.detail.subDetail.reviewOutcome |
| ExplanationOfBenefit.addItem.detail.subDetail.adjudication | UseElementSameName | ExplanationOfBenefit.addItem.detail.subDetail.adjudication |
| ExplanationOfBenefit.adjudication | UseElementSameName | ExplanationOfBenefit.adjudication |
| ExplanationOfBenefit.total | UseElementSameName | ExplanationOfBenefit.total |
| ExplanationOfBenefit.total.id | UseElementSameName | ExplanationOfBenefit.total.id |
| ExplanationOfBenefit.total.extension | UseElementSameName | ExplanationOfBenefit.total.extension |
| ExplanationOfBenefit.total.modifierExtension | UseElementSameName | ExplanationOfBenefit.total.modifierExtension |
| ExplanationOfBenefit.total.category | UseElementSameName | ExplanationOfBenefit.total.category |
| ExplanationOfBenefit.total.amount | UseOneOfElements | ExplanationOfBenefit.total.amount,ExplanationOfBenefit.total.amount |
| ExplanationOfBenefit.payment | UseElementSameName | ExplanationOfBenefit.payment |
| ExplanationOfBenefit.payment.id | UseElementSameName | ExplanationOfBenefit.payment.id |
| ExplanationOfBenefit.payment.extension | UseElementSameName | ExplanationOfBenefit.payment.extension |
| ExplanationOfBenefit.payment.modifierExtension | UseElementSameName | ExplanationOfBenefit.payment.modifierExtension |
| ExplanationOfBenefit.payment.type | UseElementSameName | ExplanationOfBenefit.payment.type |
| ExplanationOfBenefit.payment.adjustment | UseElementSameName | ExplanationOfBenefit.payment.adjustment |
| ExplanationOfBenefit.payment.adjustmentReason | UseElementSameName | ExplanationOfBenefit.payment.adjustmentReason |
| ExplanationOfBenefit.payment.date | UseElementSameName | ExplanationOfBenefit.payment.date |
| ExplanationOfBenefit.payment.amount | UseElementSameName | ExplanationOfBenefit.payment.amount |
| ExplanationOfBenefit.payment.identifier | UseElementSameName | ExplanationOfBenefit.payment.identifier |
| ExplanationOfBenefit.formCode | UseElementSameName | ExplanationOfBenefit.formCode |
| ExplanationOfBenefit.form | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.form |
| ExplanationOfBenefit.processNote | UseElementSameName | ExplanationOfBenefit.processNote |
| ExplanationOfBenefit.processNote.id | UseElementSameName | ExplanationOfBenefit.processNote.id |
| ExplanationOfBenefit.processNote.extension | UseElementSameName | ExplanationOfBenefit.processNote.extension |
| ExplanationOfBenefit.processNote.modifierExtension | UseElementSameName | ExplanationOfBenefit.processNote.modifierExtension |
| ExplanationOfBenefit.processNote.number | UseElementSameName | ExplanationOfBenefit.processNote.number |
| ExplanationOfBenefit.processNote.type | UseElementSameName | ExplanationOfBenefit.processNote.type |
| ExplanationOfBenefit.processNote.text | UseElementSameName | ExplanationOfBenefit.processNote.text |
| ExplanationOfBenefit.processNote.language | UseElementSameName | ExplanationOfBenefit.processNote.language |
| ExplanationOfBenefit.benefitPeriod | UseElementSameName | ExplanationOfBenefit.benefitPeriod |
| ExplanationOfBenefit.benefitBalance | UseElementSameName | ExplanationOfBenefit.benefitBalance |
| ExplanationOfBenefit.benefitBalance.id | UseElementSameName | ExplanationOfBenefit.benefitBalance.id |
| ExplanationOfBenefit.benefitBalance.extension | UseElementSameName | ExplanationOfBenefit.benefitBalance.extension |
| ExplanationOfBenefit.benefitBalance.modifierExtension | UseElementSameName | ExplanationOfBenefit.benefitBalance.modifierExtension |
| ExplanationOfBenefit.benefitBalance.category | UseElementSameName | ExplanationOfBenefit.benefitBalance.category |
| ExplanationOfBenefit.benefitBalance.excluded | UseElementSameName | ExplanationOfBenefit.benefitBalance.excluded |
| ExplanationOfBenefit.benefitBalance.name | UseElementSameName | ExplanationOfBenefit.benefitBalance.name |
| ExplanationOfBenefit.benefitBalance.description | UseElementSameName | ExplanationOfBenefit.benefitBalance.description |
| ExplanationOfBenefit.benefitBalance.network | UseElementSameName | ExplanationOfBenefit.benefitBalance.network |
| ExplanationOfBenefit.benefitBalance.unit | UseElementSameName | ExplanationOfBenefit.benefitBalance.unit |
| ExplanationOfBenefit.benefitBalance.term | UseElementSameName | ExplanationOfBenefit.benefitBalance.term |
| ExplanationOfBenefit.benefitBalance.financial | UseElementSameName | ExplanationOfBenefit.benefitBalance.financial |
| ExplanationOfBenefit.benefitBalance.financial.id | UseElementSameName | ExplanationOfBenefit.benefitBalance.financial.id |
| ExplanationOfBenefit.benefitBalance.financial.extension | UseElementSameName | ExplanationOfBenefit.benefitBalance.financial.extension |
| ExplanationOfBenefit.benefitBalance.financial.modifierExtension | UseElementSameName | ExplanationOfBenefit.benefitBalance.financial.modifierExtension |
| ExplanationOfBenefit.benefitBalance.financial.type | UseElementSameName | ExplanationOfBenefit.benefitBalance.financial.type |
| ExplanationOfBenefit.benefitBalance.financial.allowed[x] | UseElementSameName | ExplanationOfBenefit.benefitBalance.financial.allowed[x] |
| ExplanationOfBenefit.benefitBalance.financial.used[x] | UseElementSameName | ExplanationOfBenefit.benefitBalance.financial.used[x] |
