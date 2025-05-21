### Lookup for FHIR R3 PaymentNotice for use in FHIR R2

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
| PaymentNotice.status | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-PaymentNotice.status |
| PaymentNotice.request | UseElementSameName | PaymentNotice.request |
| PaymentNotice.response | UseElementSameName | PaymentNotice.response |
| PaymentNotice.statusDate | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-PaymentNotice.statusDate |
| PaymentNotice.created | UseElementSameName | PaymentNotice.created |
| PaymentNotice.target | UseElementRenamed | PaymentNotice.target |
| PaymentNotice.provider | UseElementSameName | PaymentNotice.provider |
| PaymentNotice.organization | UseElementRenamed | PaymentNotice.organization |
| PaymentNotice.paymentStatus | UseElementSameName | PaymentNotice.paymentStatus |
