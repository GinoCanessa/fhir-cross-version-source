### Lookup for FHIR R4B PaymentReconciliation for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| PaymentReconciliation.id | UseElementSameName | PaymentReconciliation.id |
| PaymentReconciliation.meta | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-PaymentReconciliation.meta |
| PaymentReconciliation.implicitRules | UseElementSameName | PaymentReconciliation.implicitRules |
| PaymentReconciliation.language | UseElementSameName | PaymentReconciliation.language |
| PaymentReconciliation.text | UseElementSameName | PaymentReconciliation.text |
| PaymentReconciliation.contained | UseElementSameName | PaymentReconciliation.contained |
| PaymentReconciliation.extension | UseElementSameName | PaymentReconciliation.extension |
| PaymentReconciliation.modifierExtension | UseElementSameName | PaymentReconciliation.modifierExtension |
| PaymentReconciliation.identifier | UseElementSameName | PaymentReconciliation.identifier |
| PaymentReconciliation.status | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-PaymentReconciliation.status |
| PaymentReconciliation.period | UseElementSameName | PaymentReconciliation.period |
| PaymentReconciliation.created | UseElementSameName | PaymentReconciliation.created |
| PaymentReconciliation.paymentIssuer | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-PaymentReconciliation.paymentIssuer |
| PaymentReconciliation.request | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-PaymentReconciliation.request |
| PaymentReconciliation.requestor | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-PaymentReconciliation.requestor |
| PaymentReconciliation.outcome | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-PaymentReconciliation.outcome |
| PaymentReconciliation.disposition | UseElementSameName | PaymentReconciliation.disposition |
| PaymentReconciliation.paymentDate | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-PaymentReconciliation.paymentDate |
| PaymentReconciliation.paymentAmount | UseElementRenamed | PaymentReconciliation.total |
| PaymentReconciliation.paymentIdentifier | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-PaymentReconciliation.paymentIdentifier |
| PaymentReconciliation.detail | UseElementSameName | PaymentReconciliation.detail |
| PaymentReconciliation.detail.id | UseElementSameName | PaymentReconciliation.detail.id |
| PaymentReconciliation.detail.extension | UseElementSameName | PaymentReconciliation.detail.extension |
| PaymentReconciliation.detail.modifierExtension | UseElementSameName | PaymentReconciliation.detail.modifierExtension |
| PaymentReconciliation.detail.identifier | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-PaymentReconciliation.detail.identifier |
| PaymentReconciliation.detail.predecessor | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-PaymentReconciliation.detail.predecessor |
| PaymentReconciliation.detail.type | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-PaymentReconciliation.detail.type |
| PaymentReconciliation.detail.request | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-PaymentReconciliation.detail.request |
| PaymentReconciliation.detail.submitter | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-PaymentReconciliation.detail.submitter |
| PaymentReconciliation.detail.response | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-PaymentReconciliation.detail.response |
| PaymentReconciliation.detail.date | UseElementSameName | PaymentReconciliation.detail.date |
| PaymentReconciliation.detail.responsible | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-PaymentReconciliation.detail.responsible |
| PaymentReconciliation.detail.payee | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-PaymentReconciliation.detail.payee |
| PaymentReconciliation.detail.amount | UseElementSameName | PaymentReconciliation.detail.amount |
| PaymentReconciliation.formCode | UseElementRenamed | PaymentReconciliation.form |
| PaymentReconciliation.processNote | UseElementRenamed | PaymentReconciliation.note |
| PaymentReconciliation.processNote.id | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-PaymentReconciliation.processNote.id |
| PaymentReconciliation.processNote.extension | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-PaymentReconciliation.processNote.extension |
| PaymentReconciliation.processNote.modifierExtension | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-PaymentReconciliation.processNote.modifierExtension |
| PaymentReconciliation.processNote.type | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-PaymentReconciliation.processNote.type |
| PaymentReconciliation.processNote.text | UseElementRenamed | PaymentReconciliation.note.text |
