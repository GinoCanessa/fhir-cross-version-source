### Lookup for FHIR R5 PaymentReconciliation for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| PaymentReconciliation.id | UseElementSameName | PaymentReconciliation.id |
| PaymentReconciliation.meta | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-PaymentReconciliation.meta |
| PaymentReconciliation.implicitRules | UseElementSameName | PaymentReconciliation.implicitRules |
| PaymentReconciliation.language | UseElementSameName | PaymentReconciliation.language |
| PaymentReconciliation.text | UseElementSameName | PaymentReconciliation.text |
| PaymentReconciliation.contained | UseElementSameName | PaymentReconciliation.contained |
| PaymentReconciliation.extension | UseElementSameName | PaymentReconciliation.extension |
| PaymentReconciliation.modifierExtension | UseElementSameName | PaymentReconciliation.modifierExtension |
| PaymentReconciliation.identifier | UseElementSameName | PaymentReconciliation.identifier |
| PaymentReconciliation.type | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-PaymentReconciliation.type |
| PaymentReconciliation.status | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-PaymentReconciliation.status |
| PaymentReconciliation.kind | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-PaymentReconciliation.kind |
| PaymentReconciliation.period | UseElementSameName | PaymentReconciliation.period |
| PaymentReconciliation.created | UseElementSameName | PaymentReconciliation.created |
| PaymentReconciliation.enterer | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-PaymentReconciliation.enterer |
| PaymentReconciliation.issuerType | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-PaymentReconciliation.issuerType |
| PaymentReconciliation.paymentIssuer | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-PaymentReconciliation.paymentIssuer |
| PaymentReconciliation.request | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-PaymentReconciliation.request |
| PaymentReconciliation.requestor | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-PaymentReconciliation.requestor |
| PaymentReconciliation.outcome | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-PaymentReconciliation.outcome |
| PaymentReconciliation.disposition | UseElementSameName | PaymentReconciliation.disposition |
| PaymentReconciliation.date | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-PaymentReconciliation.date |
| PaymentReconciliation.location | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-PaymentReconciliation.location |
| PaymentReconciliation.method | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-PaymentReconciliation.method |
| PaymentReconciliation.cardBrand | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-PaymentReconciliation.cardBrand |
| PaymentReconciliation.accountNumber | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-PaymentReconciliation.accountNumber |
| PaymentReconciliation.expirationDate | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-PaymentReconciliation.expirationDate |
| PaymentReconciliation.processor | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-PaymentReconciliation.processor |
| PaymentReconciliation.referenceNumber | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-PaymentReconciliation.referenceNumber |
| PaymentReconciliation.authorization | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-PaymentReconciliation.authorization |
| PaymentReconciliation.tenderedAmount | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-PaymentReconciliation.tenderedAmount |
| PaymentReconciliation.returnedAmount | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-PaymentReconciliation.returnedAmount |
| PaymentReconciliation.amount | UseElementRenamed | PaymentReconciliation.total |
| PaymentReconciliation.paymentIdentifier | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-PaymentReconciliation.paymentIdentifier |
| PaymentReconciliation.allocation | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-PaymentReconciliation.allocation |
| PaymentReconciliation.allocation.id | UseExtensionFromAncestor | - |
| PaymentReconciliation.allocation.extension | UseExtensionFromAncestor | - |
| PaymentReconciliation.allocation.modifierExtension | UseExtensionFromAncestor | - |
| PaymentReconciliation.allocation.identifier | UseExtensionFromAncestor | - |
| PaymentReconciliation.allocation.predecessor | UseExtensionFromAncestor | - |
| PaymentReconciliation.allocation.target | UseExtensionFromAncestor | - |
| PaymentReconciliation.allocation.targetItem[x] | UseExtensionFromAncestor | - |
| PaymentReconciliation.allocation.encounter | UseExtensionFromAncestor | - |
| PaymentReconciliation.allocation.account | UseExtensionFromAncestor | - |
| PaymentReconciliation.allocation.type | UseExtensionFromAncestor | - |
| PaymentReconciliation.allocation.submitter | UseExtensionFromAncestor | - |
| PaymentReconciliation.allocation.response | UseExtensionFromAncestor | - |
| PaymentReconciliation.allocation.date | UseExtensionFromAncestor | - |
| PaymentReconciliation.allocation.responsible | UseExtensionFromAncestor | - |
| PaymentReconciliation.allocation.payee | UseExtensionFromAncestor | - |
| PaymentReconciliation.allocation.amount | UseExtensionFromAncestor | - |
| PaymentReconciliation.formCode | UseElementRenamed | PaymentReconciliation.form |
| PaymentReconciliation.processNote | UseElementRenamed | PaymentReconciliation.note |
| PaymentReconciliation.processNote.id | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-PaymentReconciliation.processNote.id |
| PaymentReconciliation.processNote.extension | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-PaymentReconciliation.processNote.extension |
| PaymentReconciliation.processNote.modifierExtension | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-PaymentReconciliation.processNote.modifierExtension |
| PaymentReconciliation.processNote.type | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-PaymentReconciliation.processNote.type |
| PaymentReconciliation.processNote.text | UseElementRenamed | PaymentReconciliation.note.text |
