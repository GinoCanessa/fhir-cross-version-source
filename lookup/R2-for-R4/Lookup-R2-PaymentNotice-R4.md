### Lookup for FHIR R2 PaymentNotice for use in FHIR R4

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| PaymentNotice.id | UseElementSameName | PaymentNotice.id |
| PaymentNotice.meta | UseElementSameName | PaymentNotice.meta |
| PaymentNotice.implicitRules | UseElementSameName | PaymentNotice.implicitRules |
| PaymentNotice.language | UseElementSameName | PaymentNotice.language |
| PaymentNotice.text | UseElementSameName | PaymentNotice.text |
| PaymentNotice.contained | UseElementSameName | PaymentNotice.contained |
| PaymentNotice.extension | UseElementSameName | PaymentNotice.extension |
| PaymentNotice.modifierExtension | UseElementSameName | PaymentNotice.modifierExtension |
| PaymentNotice.identifier | UseElementSameName | PaymentNotice.identifier |
| PaymentNotice.ruleset | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-PaymentNotice.ruleset |
| PaymentNotice.originalRuleset | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-PaymentNotice.originalRuleset |
| PaymentNotice.created | UseElementSameName | PaymentNotice.created |
| PaymentNotice.target | UseElementRenamed | PaymentNotice.recipient |
| PaymentNotice.provider | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-PaymentNotice.provider |
| PaymentNotice.organization | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-PaymentNotice.organization |
| PaymentNotice.request | UseElementSameName | PaymentNotice.request |
| PaymentNotice.response | UseElementSameName | PaymentNotice.response |
| PaymentNotice.paymentStatus | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-PaymentNotice.paymentStatus |
