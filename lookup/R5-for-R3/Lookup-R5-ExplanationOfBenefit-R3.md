### Lookup for FHIR R5 ExplanationOfBenefit for use in FHIR R3

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| ExplanationOfBenefit.id | UseElementSameName | ExplanationOfBenefit.id |
| ExplanationOfBenefit.meta | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.meta |
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
| ExplanationOfBenefit.use | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.use |
| ExplanationOfBenefit.patient | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.patient |
| ExplanationOfBenefit.billablePeriod | UseElementSameName | ExplanationOfBenefit.billablePeriod |
| ExplanationOfBenefit.created | UseElementSameName | ExplanationOfBenefit.created |
| ExplanationOfBenefit.enterer | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.enterer |
| ExplanationOfBenefit.insurer | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.insurer |
| ExplanationOfBenefit.provider | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.provider |
| ExplanationOfBenefit.priority | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.priority |
| ExplanationOfBenefit.fundsReserveRequested | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.fundsReserveRequested |
| ExplanationOfBenefit.fundsReserve | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.fundsReserve |
| ExplanationOfBenefit.related | UseElementSameName | ExplanationOfBenefit.related |
| ExplanationOfBenefit.related.id | UseElementSameName | ExplanationOfBenefit.related.id |
| ExplanationOfBenefit.related.extension | UseElementSameName | ExplanationOfBenefit.related.extension |
| ExplanationOfBenefit.related.modifierExtension | UseElementSameName | ExplanationOfBenefit.related.modifierExtension |
| ExplanationOfBenefit.related.claim | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.related.claim |
| ExplanationOfBenefit.related.relationship | UseElementSameName | ExplanationOfBenefit.related.relationship |
| ExplanationOfBenefit.related.reference | UseElementSameName | ExplanationOfBenefit.related.reference |
| ExplanationOfBenefit.prescription | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.prescription |
| ExplanationOfBenefit.originalPrescription | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.originalPrescription |
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
| ExplanationOfBenefit.payee.party | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.payee.party |
| ExplanationOfBenefit.referral | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.referral |
| ExplanationOfBenefit.encounter | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.encounter |
| ExplanationOfBenefit.facility | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.facility |
| ExplanationOfBenefit.claim | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.claim |
| ExplanationOfBenefit.claimResponse | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.claimResponse |
| ExplanationOfBenefit.outcome | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.outcome |
| ExplanationOfBenefit.decision | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.decision |
| ExplanationOfBenefit.disposition | UseElementSameName | ExplanationOfBenefit.disposition |
| ExplanationOfBenefit.preAuthRef | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.preAuthRef |
| ExplanationOfBenefit.preAuthRefPeriod | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.preAuthRefPeriod |
| ExplanationOfBenefit.diagnosisRelatedGroup | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.diagnosisRelatedGroup |
| ExplanationOfBenefit.careTeam | UseElementSameName | ExplanationOfBenefit.careTeam |
| ExplanationOfBenefit.careTeam.id | UseElementSameName | ExplanationOfBenefit.careTeam.id |
| ExplanationOfBenefit.careTeam.extension | UseElementSameName | ExplanationOfBenefit.careTeam.extension |
| ExplanationOfBenefit.careTeam.modifierExtension | UseElementSameName | ExplanationOfBenefit.careTeam.modifierExtension |
| ExplanationOfBenefit.careTeam.sequence | UseElementSameName | ExplanationOfBenefit.careTeam.sequence |
| ExplanationOfBenefit.careTeam.provider | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.careTeam.provider |
| ExplanationOfBenefit.careTeam.responsible | UseElementSameName | ExplanationOfBenefit.careTeam.responsible |
| ExplanationOfBenefit.careTeam.role | UseElementSameName | ExplanationOfBenefit.careTeam.role |
| ExplanationOfBenefit.careTeam.specialty | UseElementRenamed | ExplanationOfBenefit.careTeam.qualification |
| ExplanationOfBenefit.supportingInfo | UseElementRenamed | ExplanationOfBenefit.information |
| ExplanationOfBenefit.supportingInfo.id | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.supportingInfo.id |
| ExplanationOfBenefit.supportingInfo.extension | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.supportingInfo.extension |
| ExplanationOfBenefit.supportingInfo.modifierExtension | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.supportingInfo.modifierExtension |
| ExplanationOfBenefit.supportingInfo.sequence | UseElementRenamed | ExplanationOfBenefit.information.sequence |
| ExplanationOfBenefit.supportingInfo.category | UseElementRenamed | ExplanationOfBenefit.information.category |
| ExplanationOfBenefit.supportingInfo.code | UseElementRenamed | ExplanationOfBenefit.information.code |
| ExplanationOfBenefit.supportingInfo.timing[x] | UseElementRenamed | ExplanationOfBenefit.information.timing[x] |
| ExplanationOfBenefit.supportingInfo.value[x] | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.supportingInfo.value |
| ExplanationOfBenefit.supportingInfo.reason | UseElementRenamed | ExplanationOfBenefit.information.reason |
| ExplanationOfBenefit.diagnosis | UseElementSameName | ExplanationOfBenefit.diagnosis |
| ExplanationOfBenefit.diagnosis.id | UseElementSameName | ExplanationOfBenefit.diagnosis.id |
| ExplanationOfBenefit.diagnosis.extension | UseElementSameName | ExplanationOfBenefit.diagnosis.extension |
| ExplanationOfBenefit.diagnosis.modifierExtension | UseElementSameName | ExplanationOfBenefit.diagnosis.modifierExtension |
| ExplanationOfBenefit.diagnosis.sequence | UseElementSameName | ExplanationOfBenefit.diagnosis.sequence |
| ExplanationOfBenefit.diagnosis.diagnosis[x] | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.diagnosis.diagnosis |
| ExplanationOfBenefit.diagnosis.type | UseElementSameName | ExplanationOfBenefit.diagnosis.type |
| ExplanationOfBenefit.diagnosis.onAdmission | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.diagnosis.onAdmission |
| ExplanationOfBenefit.procedure | UseElementSameName | ExplanationOfBenefit.procedure |
| ExplanationOfBenefit.procedure.id | UseElementSameName | ExplanationOfBenefit.procedure.id |
| ExplanationOfBenefit.procedure.extension | UseElementSameName | ExplanationOfBenefit.procedure.extension |
| ExplanationOfBenefit.procedure.modifierExtension | UseElementSameName | ExplanationOfBenefit.procedure.modifierExtension |
| ExplanationOfBenefit.procedure.sequence | UseElementSameName | ExplanationOfBenefit.procedure.sequence |
| ExplanationOfBenefit.procedure.type | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.procedure.type |
| ExplanationOfBenefit.procedure.date | UseElementSameName | ExplanationOfBenefit.procedure.date |
| ExplanationOfBenefit.procedure.procedure[x] | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.procedure.procedure |
| ExplanationOfBenefit.procedure.udi | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.procedure.udi |
| ExplanationOfBenefit.precedence | UseElementSameName | ExplanationOfBenefit.precedence |
| ExplanationOfBenefit.insurance | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.insurance |
| ExplanationOfBenefit.insurance.id | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.insurance.extension | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.insurance.modifierExtension | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.insurance.focal | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.insurance.coverage | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.insurance.preAuthRef | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.accident | UseElementSameName | ExplanationOfBenefit.accident |
| ExplanationOfBenefit.accident.id | UseElementSameName | ExplanationOfBenefit.accident.id |
| ExplanationOfBenefit.accident.extension | UseElementSameName | ExplanationOfBenefit.accident.extension |
| ExplanationOfBenefit.accident.modifierExtension | UseElementSameName | ExplanationOfBenefit.accident.modifierExtension |
| ExplanationOfBenefit.accident.date | UseElementSameName | ExplanationOfBenefit.accident.date |
| ExplanationOfBenefit.accident.type | UseElementSameName | ExplanationOfBenefit.accident.type |
| ExplanationOfBenefit.accident.location[x] | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.accident.location |
| ExplanationOfBenefit.patientPaid | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.patientPaid |
| ExplanationOfBenefit.item | UseElementSameName | ExplanationOfBenefit.item |
| ExplanationOfBenefit.item.id | UseElementSameName | ExplanationOfBenefit.item.id |
| ExplanationOfBenefit.item.extension | UseElementSameName | ExplanationOfBenefit.item.extension |
| ExplanationOfBenefit.item.modifierExtension | UseElementSameName | ExplanationOfBenefit.item.modifierExtension |
| ExplanationOfBenefit.item.sequence | UseElementSameName | ExplanationOfBenefit.item.sequence |
| ExplanationOfBenefit.item.careTeamSequence | UseElementRenamed | ExplanationOfBenefit.item.careTeamLinkId |
| ExplanationOfBenefit.item.diagnosisSequence | UseElementRenamed | ExplanationOfBenefit.item.diagnosisLinkId |
| ExplanationOfBenefit.item.procedureSequence | UseElementRenamed | ExplanationOfBenefit.item.procedureLinkId |
| ExplanationOfBenefit.item.informationSequence | UseElementRenamed | ExplanationOfBenefit.item.informationLinkId |
| ExplanationOfBenefit.item.traceNumber | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.item.traceNumber |
| ExplanationOfBenefit.item.revenue | UseElementSameName | ExplanationOfBenefit.item.revenue |
| ExplanationOfBenefit.item.category | UseElementSameName | ExplanationOfBenefit.item.category |
| ExplanationOfBenefit.item.productOrService | UseElementRenamed | ExplanationOfBenefit.item.service |
| ExplanationOfBenefit.item.productOrServiceEnd | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.item.productOrServiceEnd |
| ExplanationOfBenefit.item.request | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.item.request |
| ExplanationOfBenefit.item.modifier | UseElementSameName | ExplanationOfBenefit.item.modifier |
| ExplanationOfBenefit.item.programCode | UseElementSameName | ExplanationOfBenefit.item.programCode |
| ExplanationOfBenefit.item.serviced[x] | UseElementSameName | ExplanationOfBenefit.item.serviced[x] |
| ExplanationOfBenefit.item.location[x] | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.item.location |
| ExplanationOfBenefit.item.patientPaid | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.item.patientPaid |
| ExplanationOfBenefit.item.quantity | UseElementSameName | ExplanationOfBenefit.item.quantity |
| ExplanationOfBenefit.item.unitPrice | UseElementSameName | ExplanationOfBenefit.item.unitPrice |
| ExplanationOfBenefit.item.factor | UseElementSameName | ExplanationOfBenefit.item.factor |
| ExplanationOfBenefit.item.tax | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.item.tax |
| ExplanationOfBenefit.item.net | UseElementSameName | ExplanationOfBenefit.item.net |
| ExplanationOfBenefit.item.udi | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.item.udi |
| ExplanationOfBenefit.item.bodySite | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.item.bodySite |
| ExplanationOfBenefit.item.bodySite.id | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.item.bodySite.extension | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.item.bodySite.modifierExtension | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.item.bodySite.site | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.item.bodySite.subSite | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.item.encounter | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.item.encounter |
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
| ExplanationOfBenefit.item.detail.productOrService | UseElementRenamed | ExplanationOfBenefit.item.detail.service |
| ExplanationOfBenefit.item.detail.productOrServiceEnd | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.item.detail.productOrServiceEnd |
| ExplanationOfBenefit.item.detail.modifier | UseElementSameName | ExplanationOfBenefit.item.detail.modifier |
| ExplanationOfBenefit.item.detail.programCode | UseElementSameName | ExplanationOfBenefit.item.detail.programCode |
| ExplanationOfBenefit.item.detail.patientPaid | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.item.detail.patientPaid |
| ExplanationOfBenefit.item.detail.quantity | UseElementSameName | ExplanationOfBenefit.item.detail.quantity |
| ExplanationOfBenefit.item.detail.unitPrice | UseElementSameName | ExplanationOfBenefit.item.detail.unitPrice |
| ExplanationOfBenefit.item.detail.factor | UseElementSameName | ExplanationOfBenefit.item.detail.factor |
| ExplanationOfBenefit.item.detail.tax | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.item.detail.tax |
| ExplanationOfBenefit.item.detail.net | UseElementSameName | ExplanationOfBenefit.item.detail.net |
| ExplanationOfBenefit.item.detail.udi | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.item.detail.udi |
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
| ExplanationOfBenefit.item.detail.subDetail.productOrService | UseElementRenamed | ExplanationOfBenefit.item.detail.subDetail.service |
| ExplanationOfBenefit.item.detail.subDetail.productOrServiceEnd | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.item.detail.subDetail.productOrServiceEnd |
| ExplanationOfBenefit.item.detail.subDetail.modifier | UseElementSameName | ExplanationOfBenefit.item.detail.subDetail.modifier |
| ExplanationOfBenefit.item.detail.subDetail.programCode | UseElementSameName | ExplanationOfBenefit.item.detail.subDetail.programCode |
| ExplanationOfBenefit.item.detail.subDetail.patientPaid | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.item.detail.subDetail.patientPaid |
| ExplanationOfBenefit.item.detail.subDetail.quantity | UseElementSameName | ExplanationOfBenefit.item.detail.subDetail.quantity |
| ExplanationOfBenefit.item.detail.subDetail.unitPrice | UseElementSameName | ExplanationOfBenefit.item.detail.subDetail.unitPrice |
| ExplanationOfBenefit.item.detail.subDetail.factor | UseElementSameName | ExplanationOfBenefit.item.detail.subDetail.factor |
| ExplanationOfBenefit.item.detail.subDetail.tax | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.item.detail.subDetail.tax |
| ExplanationOfBenefit.item.detail.subDetail.net | UseElementSameName | ExplanationOfBenefit.item.detail.subDetail.net |
| ExplanationOfBenefit.item.detail.subDetail.udi | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.item.detail.subDetail.udi |
| ExplanationOfBenefit.item.detail.subDetail.noteNumber | UseElementSameName | ExplanationOfBenefit.item.detail.subDetail.noteNumber |
| ExplanationOfBenefit.item.detail.subDetail.reviewOutcome | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.item.detail.subDetail.reviewOutcome |
| ExplanationOfBenefit.item.detail.subDetail.adjudication | UseElementSameName | ExplanationOfBenefit.item.detail.subDetail.adjudication |
| ExplanationOfBenefit.addItem | UseElementSameName | ExplanationOfBenefit.addItem |
| ExplanationOfBenefit.addItem.id | UseElementSameName | ExplanationOfBenefit.addItem.id |
| ExplanationOfBenefit.addItem.extension | UseElementSameName | ExplanationOfBenefit.addItem.extension |
| ExplanationOfBenefit.addItem.modifierExtension | UseElementSameName | ExplanationOfBenefit.addItem.modifierExtension |
| ExplanationOfBenefit.addItem.itemSequence | UseElementRenamed | ExplanationOfBenefit.addItem.sequenceLinkId |
| ExplanationOfBenefit.addItem.detailSequence | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.detailSequence |
| ExplanationOfBenefit.addItem.subDetailSequence | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.subDetailSequence |
| ExplanationOfBenefit.addItem.traceNumber | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.traceNumber |
| ExplanationOfBenefit.addItem.provider | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.provider |
| ExplanationOfBenefit.addItem.revenue | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.revenue |
| ExplanationOfBenefit.addItem.productOrService | UseElementRenamed | ExplanationOfBenefit.addItem.service |
| ExplanationOfBenefit.addItem.productOrServiceEnd | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.productOrServiceEnd |
| ExplanationOfBenefit.addItem.request | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.request |
| ExplanationOfBenefit.addItem.modifier | UseElementSameName | ExplanationOfBenefit.addItem.modifier |
| ExplanationOfBenefit.addItem.programCode | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.programCode |
| ExplanationOfBenefit.addItem.serviced[x] | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.serviced |
| ExplanationOfBenefit.addItem.location[x] | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.location |
| ExplanationOfBenefit.addItem.patientPaid | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.patientPaid |
| ExplanationOfBenefit.addItem.quantity | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.quantity |
| ExplanationOfBenefit.addItem.unitPrice | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.unitPrice |
| ExplanationOfBenefit.addItem.factor | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.factor |
| ExplanationOfBenefit.addItem.tax | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.tax |
| ExplanationOfBenefit.addItem.net | UseElementRenamed | ExplanationOfBenefit.addItem.fee |
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
| ExplanationOfBenefit.addItem.detail.productOrService | UseElementRenamed | ExplanationOfBenefit.addItem.detail.service |
| ExplanationOfBenefit.addItem.detail.productOrServiceEnd | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.detail.productOrServiceEnd |
| ExplanationOfBenefit.addItem.detail.modifier | UseElementSameName | ExplanationOfBenefit.addItem.detail.modifier |
| ExplanationOfBenefit.addItem.detail.patientPaid | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.detail.patientPaid |
| ExplanationOfBenefit.addItem.detail.quantity | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.detail.quantity |
| ExplanationOfBenefit.addItem.detail.unitPrice | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.detail.unitPrice |
| ExplanationOfBenefit.addItem.detail.factor | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.detail.factor |
| ExplanationOfBenefit.addItem.detail.tax | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.detail.tax |
| ExplanationOfBenefit.addItem.detail.net | UseElementRenamed | ExplanationOfBenefit.addItem.detail.fee |
| ExplanationOfBenefit.addItem.detail.noteNumber | UseElementSameName | ExplanationOfBenefit.addItem.detail.noteNumber |
| ExplanationOfBenefit.addItem.detail.reviewOutcome | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.detail.reviewOutcome |
| ExplanationOfBenefit.addItem.detail.adjudication | UseElementSameName | ExplanationOfBenefit.addItem.detail.adjudication |
| ExplanationOfBenefit.addItem.detail.subDetail | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.addItem.detail.subDetail |
| ExplanationOfBenefit.addItem.detail.subDetail.id | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.addItem.detail.subDetail.extension | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.addItem.detail.subDetail.modifierExtension | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.addItem.detail.subDetail.traceNumber | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.addItem.detail.subDetail.revenue | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.addItem.detail.subDetail.productOrService | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.addItem.detail.subDetail.productOrServiceEnd | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.addItem.detail.subDetail.modifier | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.addItem.detail.subDetail.patientPaid | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.addItem.detail.subDetail.quantity | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.addItem.detail.subDetail.unitPrice | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.addItem.detail.subDetail.factor | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.addItem.detail.subDetail.tax | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.addItem.detail.subDetail.net | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.addItem.detail.subDetail.noteNumber | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.addItem.detail.subDetail.reviewOutcome | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.addItem.detail.subDetail.adjudication | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.adjudication | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.adjudication |
| ExplanationOfBenefit.total | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.total |
| ExplanationOfBenefit.total.id | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.total.extension | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.total.modifierExtension | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.total.category | UseExtensionFromAncestor | - |
| ExplanationOfBenefit.total.amount | UseExtensionFromAncestor | - |
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
| ExplanationOfBenefit.formCode | UseElementRenamed | ExplanationOfBenefit.form |
| ExplanationOfBenefit.form | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.form |
| ExplanationOfBenefit.processNote | UseElementSameName | ExplanationOfBenefit.processNote |
| ExplanationOfBenefit.processNote.id | UseElementSameName | ExplanationOfBenefit.processNote.id |
| ExplanationOfBenefit.processNote.extension | UseElementSameName | ExplanationOfBenefit.processNote.extension |
| ExplanationOfBenefit.processNote.modifierExtension | UseElementSameName | ExplanationOfBenefit.processNote.modifierExtension |
| ExplanationOfBenefit.processNote.number | UseElementSameName | ExplanationOfBenefit.processNote.number |
| ExplanationOfBenefit.processNote.type | UseElementSameName | ExplanationOfBenefit.processNote.type |
| ExplanationOfBenefit.processNote.text | UseElementSameName | ExplanationOfBenefit.processNote.text |
| ExplanationOfBenefit.processNote.language | UseElementSameName | ExplanationOfBenefit.processNote.language |
| ExplanationOfBenefit.benefitPeriod | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ExplanationOfBenefit.benefitPeriod |
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
