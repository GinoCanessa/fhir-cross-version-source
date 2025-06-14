### Lookup for FHIR R5 ClaimResponse for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| ClaimResponse.id | UseElementSameName | ClaimResponse.id |
| ClaimResponse.meta | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.meta |
| ClaimResponse.implicitRules | UseElementSameName | ClaimResponse.implicitRules |
| ClaimResponse.language | UseElementSameName | ClaimResponse.language |
| ClaimResponse.text | UseElementSameName | ClaimResponse.text |
| ClaimResponse.contained | UseElementSameName | ClaimResponse.contained |
| ClaimResponse.extension | UseElementSameName | ClaimResponse.extension |
| ClaimResponse.modifierExtension | UseElementSameName | ClaimResponse.modifierExtension |
| ClaimResponse.identifier | UseElementSameName | ClaimResponse.identifier |
| ClaimResponse.traceNumber | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.traceNumber |
| ClaimResponse.status | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.status |
| ClaimResponse.type | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.type |
| ClaimResponse.subType | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.subType |
| ClaimResponse.use | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.use |
| ClaimResponse.patient | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.patient |
| ClaimResponse.created | UseElementSameName | ClaimResponse.created |
| ClaimResponse.insurer | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.insurer |
| ClaimResponse.requestor | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.requestor |
| ClaimResponse.request | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.request |
| ClaimResponse.outcome | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.outcome |
| ClaimResponse.decision | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.decision |
| ClaimResponse.disposition | UseElementSameName | ClaimResponse.disposition |
| ClaimResponse.preAuthRef | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.preAuthRef |
| ClaimResponse.preAuthPeriod | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.preAuthPeriod |
| ClaimResponse.event | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.event |
| ClaimResponse.event.id | UseExtensionFromAncestor | - |
| ClaimResponse.event.extension | UseExtensionFromAncestor | - |
| ClaimResponse.event.modifierExtension | UseExtensionFromAncestor | - |
| ClaimResponse.event.type | UseExtensionFromAncestor | - |
| ClaimResponse.event.when[x] | UseExtensionFromAncestor | - |
| ClaimResponse.payeeType | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.payeeType |
| ClaimResponse.encounter | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.encounter |
| ClaimResponse.diagnosisRelatedGroup | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.diagnosisRelatedGroup |
| ClaimResponse.item | UseElementSameName | ClaimResponse.item |
| ClaimResponse.item.id | UseElementSameName | ClaimResponse.item.id |
| ClaimResponse.item.extension | UseElementSameName | ClaimResponse.item.extension |
| ClaimResponse.item.modifierExtension | UseElementSameName | ClaimResponse.item.modifierExtension |
| ClaimResponse.item.itemSequence | UseElementRenamed | ClaimResponse.item.sequenceLinkId |
| ClaimResponse.item.traceNumber | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.item.traceNumber |
| ClaimResponse.item.noteNumber | UseElementSameName | ClaimResponse.item.noteNumber |
| ClaimResponse.item.reviewOutcome | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.item.reviewOutcome |
| ClaimResponse.item.reviewOutcome.id | UseExtensionFromAncestor | - |
| ClaimResponse.item.reviewOutcome.extension | UseExtensionFromAncestor | - |
| ClaimResponse.item.reviewOutcome.modifierExtension | UseExtensionFromAncestor | - |
| ClaimResponse.item.reviewOutcome.decision | UseExtensionFromAncestor | - |
| ClaimResponse.item.reviewOutcome.reason | UseExtensionFromAncestor | - |
| ClaimResponse.item.reviewOutcome.preAuthRef | UseExtensionFromAncestor | - |
| ClaimResponse.item.reviewOutcome.preAuthPeriod | UseExtensionFromAncestor | - |
| ClaimResponse.item.adjudication | UseElementSameName | ClaimResponse.item.adjudication |
| ClaimResponse.item.adjudication.id | UseElementSameName | ClaimResponse.item.adjudication.id |
| ClaimResponse.item.adjudication.extension | UseElementSameName | ClaimResponse.item.adjudication.extension |
| ClaimResponse.item.adjudication.modifierExtension | UseElementSameName | ClaimResponse.item.adjudication.modifierExtension |
| ClaimResponse.item.adjudication.category | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.item.adjudication.category |
| ClaimResponse.item.adjudication.reason | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.item.adjudication.reason |
| ClaimResponse.item.adjudication.amount | UseElementSameName | ClaimResponse.item.adjudication.amount |
| ClaimResponse.item.adjudication.quantity | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.item.adjudication.quantity |
| ClaimResponse.item.detail | UseElementSameName | ClaimResponse.item.detail |
| ClaimResponse.item.detail.id | UseElementSameName | ClaimResponse.item.detail.id |
| ClaimResponse.item.detail.extension | UseElementSameName | ClaimResponse.item.detail.extension |
| ClaimResponse.item.detail.modifierExtension | UseElementSameName | ClaimResponse.item.detail.modifierExtension |
| ClaimResponse.item.detail.detailSequence | UseElementRenamed | ClaimResponse.item.detail.sequenceLinkId |
| ClaimResponse.item.detail.traceNumber | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.item.detail.traceNumber |
| ClaimResponse.item.detail.noteNumber | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.item.detail.noteNumber |
| ClaimResponse.item.detail.reviewOutcome | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.item.detail.reviewOutcome |
| ClaimResponse.item.detail.adjudication | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.item.detail.adjudication |
| ClaimResponse.item.detail.subDetail | UseElementSameName | ClaimResponse.item.detail.subDetail |
| ClaimResponse.item.detail.subDetail.id | UseElementSameName | ClaimResponse.item.detail.subDetail.id |
| ClaimResponse.item.detail.subDetail.extension | UseElementSameName | ClaimResponse.item.detail.subDetail.extension |
| ClaimResponse.item.detail.subDetail.modifierExtension | UseElementSameName | ClaimResponse.item.detail.subDetail.modifierExtension |
| ClaimResponse.item.detail.subDetail.subDetailSequence | UseElementRenamed | ClaimResponse.item.detail.subDetail.sequenceLinkId |
| ClaimResponse.item.detail.subDetail.traceNumber | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.item.detail.subDetail.traceNumber |
| ClaimResponse.item.detail.subDetail.noteNumber | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.item.detail.subDetail.noteNumber |
| ClaimResponse.item.detail.subDetail.reviewOutcome | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.item.detail.subDetail.reviewOutcome |
| ClaimResponse.item.detail.subDetail.adjudication | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.item.detail.subDetail.adjudication |
| ClaimResponse.addItem | UseElementSameName | ClaimResponse.addItem |
| ClaimResponse.addItem.id | UseElementSameName | ClaimResponse.addItem.id |
| ClaimResponse.addItem.extension | UseElementSameName | ClaimResponse.addItem.extension |
| ClaimResponse.addItem.modifierExtension | UseElementSameName | ClaimResponse.addItem.modifierExtension |
| ClaimResponse.addItem.itemSequence | UseElementRenamed | ClaimResponse.addItem.sequenceLinkId |
| ClaimResponse.addItem.detailSequence | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.addItem.detailSequence |
| ClaimResponse.addItem.subdetailSequence | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.addItem.subdetailSequence |
| ClaimResponse.addItem.traceNumber | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.addItem.traceNumber |
| ClaimResponse.addItem.provider | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.addItem.provider |
| ClaimResponse.addItem.revenue | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.addItem.revenue |
| ClaimResponse.addItem.productOrService | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.addItem.productOrService |
| ClaimResponse.addItem.productOrServiceEnd | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.addItem.productOrServiceEnd |
| ClaimResponse.addItem.request | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.addItem.request |
| ClaimResponse.addItem.modifier | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.addItem.modifier |
| ClaimResponse.addItem.programCode | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.addItem.programCode |
| ClaimResponse.addItem.serviced[x] | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.addItem.serviced |
| ClaimResponse.addItem.location[x] | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.addItem.location |
| ClaimResponse.addItem.quantity | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.addItem.quantity |
| ClaimResponse.addItem.unitPrice | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.addItem.unitPrice |
| ClaimResponse.addItem.factor | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.addItem.factor |
| ClaimResponse.addItem.tax | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.addItem.tax |
| ClaimResponse.addItem.net | UseElementRenamed | ClaimResponse.addItem.fee |
| ClaimResponse.addItem.bodySite | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.addItem.bodySite |
| ClaimResponse.addItem.bodySite.id | UseExtensionFromAncestor | - |
| ClaimResponse.addItem.bodySite.extension | UseExtensionFromAncestor | - |
| ClaimResponse.addItem.bodySite.modifierExtension | UseExtensionFromAncestor | - |
| ClaimResponse.addItem.bodySite.site | UseExtensionFromAncestor | - |
| ClaimResponse.addItem.bodySite.subSite | UseExtensionFromAncestor | - |
| ClaimResponse.addItem.noteNumber | UseElementRenamed | ClaimResponse.addItem.noteNumberLinkId |
| ClaimResponse.addItem.reviewOutcome | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.addItem.reviewOutcome |
| ClaimResponse.addItem.adjudication | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.addItem.adjudication |
| ClaimResponse.addItem.detail | UseElementSameName | ClaimResponse.addItem.detail |
| ClaimResponse.addItem.detail.id | UseElementSameName | ClaimResponse.addItem.detail.id |
| ClaimResponse.addItem.detail.extension | UseElementSameName | ClaimResponse.addItem.detail.extension |
| ClaimResponse.addItem.detail.modifierExtension | UseElementSameName | ClaimResponse.addItem.detail.modifierExtension |
| ClaimResponse.addItem.detail.traceNumber | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.addItem.detail.traceNumber |
| ClaimResponse.addItem.detail.revenue | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.addItem.detail.revenue |
| ClaimResponse.addItem.detail.productOrService | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.addItem.detail.productOrService |
| ClaimResponse.addItem.detail.productOrServiceEnd | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.addItem.detail.productOrServiceEnd |
| ClaimResponse.addItem.detail.modifier | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.addItem.detail.modifier |
| ClaimResponse.addItem.detail.quantity | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.addItem.detail.quantity |
| ClaimResponse.addItem.detail.unitPrice | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.addItem.detail.unitPrice |
| ClaimResponse.addItem.detail.factor | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.addItem.detail.factor |
| ClaimResponse.addItem.detail.tax | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.addItem.detail.tax |
| ClaimResponse.addItem.detail.net | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.addItem.detail.net |
| ClaimResponse.addItem.detail.noteNumber | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.addItem.detail.noteNumber |
| ClaimResponse.addItem.detail.reviewOutcome | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.addItem.detail.reviewOutcome |
| ClaimResponse.addItem.detail.adjudication | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.addItem.detail.adjudication |
| ClaimResponse.addItem.detail.subDetail | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.addItem.detail.subDetail |
| ClaimResponse.addItem.detail.subDetail.id | UseExtensionFromAncestor | - |
| ClaimResponse.addItem.detail.subDetail.extension | UseExtensionFromAncestor | - |
| ClaimResponse.addItem.detail.subDetail.modifierExtension | UseExtensionFromAncestor | - |
| ClaimResponse.addItem.detail.subDetail.traceNumber | UseExtensionFromAncestor | - |
| ClaimResponse.addItem.detail.subDetail.revenue | UseExtensionFromAncestor | - |
| ClaimResponse.addItem.detail.subDetail.productOrService | UseExtensionFromAncestor | - |
| ClaimResponse.addItem.detail.subDetail.productOrServiceEnd | UseExtensionFromAncestor | - |
| ClaimResponse.addItem.detail.subDetail.modifier | UseExtensionFromAncestor | - |
| ClaimResponse.addItem.detail.subDetail.quantity | UseExtensionFromAncestor | - |
| ClaimResponse.addItem.detail.subDetail.unitPrice | UseExtensionFromAncestor | - |
| ClaimResponse.addItem.detail.subDetail.factor | UseExtensionFromAncestor | - |
| ClaimResponse.addItem.detail.subDetail.tax | UseExtensionFromAncestor | - |
| ClaimResponse.addItem.detail.subDetail.net | UseExtensionFromAncestor | - |
| ClaimResponse.addItem.detail.subDetail.noteNumber | UseExtensionFromAncestor | - |
| ClaimResponse.addItem.detail.subDetail.reviewOutcome | UseExtensionFromAncestor | - |
| ClaimResponse.addItem.detail.subDetail.adjudication | UseExtensionFromAncestor | - |
| ClaimResponse.adjudication | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.adjudication |
| ClaimResponse.total | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.total |
| ClaimResponse.total.id | UseExtensionFromAncestor | - |
| ClaimResponse.total.extension | UseExtensionFromAncestor | - |
| ClaimResponse.total.modifierExtension | UseExtensionFromAncestor | - |
| ClaimResponse.total.category | UseExtensionFromAncestor | - |
| ClaimResponse.total.amount | UseExtensionFromAncestor | - |
| ClaimResponse.payment | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.payment |
| ClaimResponse.payment.id | UseExtensionFromAncestor | - |
| ClaimResponse.payment.extension | UseExtensionFromAncestor | - |
| ClaimResponse.payment.modifierExtension | UseExtensionFromAncestor | - |
| ClaimResponse.payment.type | UseExtensionFromAncestor | - |
| ClaimResponse.payment.adjustment | UseExtensionFromAncestor | - |
| ClaimResponse.payment.adjustmentReason | UseExtensionFromAncestor | - |
| ClaimResponse.payment.date | UseExtensionFromAncestor | - |
| ClaimResponse.payment.amount | UseExtensionFromAncestor | - |
| ClaimResponse.payment.identifier | UseExtensionFromAncestor | - |
| ClaimResponse.fundsReserve | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.fundsReserve |
| ClaimResponse.formCode | UseElementRenamed | ClaimResponse.form |
| ClaimResponse.form | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.form |
| ClaimResponse.processNote | UseElementRenamed | ClaimResponse.note |
| ClaimResponse.processNote.id | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.processNote.id |
| ClaimResponse.processNote.extension | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.processNote.extension |
| ClaimResponse.processNote.modifierExtension | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.processNote.modifierExtension |
| ClaimResponse.processNote.number | UseElementRenamed | ClaimResponse.note.number |
| ClaimResponse.processNote.type | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.processNote.type |
| ClaimResponse.processNote.text | UseElementRenamed | ClaimResponse.note.text |
| ClaimResponse.processNote.language | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.processNote.language |
| ClaimResponse.communicationRequest | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.communicationRequest |
| ClaimResponse.insurance | UseElementRenamed | ClaimResponse.coverage |
| ClaimResponse.insurance.id | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.insurance.id |
| ClaimResponse.insurance.extension | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.insurance.extension |
| ClaimResponse.insurance.modifierExtension | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.insurance.modifierExtension |
| ClaimResponse.insurance.sequence | UseElementRenamed | ClaimResponse.coverage.sequence |
| ClaimResponse.insurance.focal | UseElementRenamed | ClaimResponse.coverage.focal |
| ClaimResponse.insurance.coverage | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.insurance.coverage |
| ClaimResponse.insurance.businessArrangement | UseElementRenamed | ClaimResponse.coverage.businessArrangement |
| ClaimResponse.insurance.claimResponse | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.insurance.claimResponse |
| ClaimResponse.error | UseElementSameName | ClaimResponse.error |
| ClaimResponse.error.id | UseElementSameName | ClaimResponse.error.id |
| ClaimResponse.error.extension | UseElementSameName | ClaimResponse.error.extension |
| ClaimResponse.error.modifierExtension | UseElementSameName | ClaimResponse.error.modifierExtension |
| ClaimResponse.error.itemSequence | UseElementRenamed | ClaimResponse.error.sequenceLinkId |
| ClaimResponse.error.detailSequence | UseElementRenamed | ClaimResponse.error.detailSequenceLinkId |
| ClaimResponse.error.subDetailSequence | UseElementRenamed | ClaimResponse.error.subdetailSequenceLinkId |
| ClaimResponse.error.code | UseElementSameName | ClaimResponse.error.code |
| ClaimResponse.error.expression | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClaimResponse.error.expression |
