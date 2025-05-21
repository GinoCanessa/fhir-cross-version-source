### Lookup for FHIR R2 ReferralRequest for use in FHIR R4

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| ReferralRequest.id | UseElementRenamed | ServiceRequest.id |
| ReferralRequest.meta | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.meta |
| ReferralRequest.implicitRules | UseElementRenamed | ServiceRequest.implicitRules |
| ReferralRequest.language | UseElementRenamed | ServiceRequest.language |
| ReferralRequest.text | UseElementRenamed | ServiceRequest.text |
| ReferralRequest.contained | UseElementRenamed | ServiceRequest.contained |
| ReferralRequest.extension | UseElementRenamed | ServiceRequest.extension |
| ReferralRequest.modifierExtension | UseElementRenamed | ServiceRequest.modifierExtension |
| ReferralRequest.status | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.status |
| ReferralRequest.identifier | UseElementRenamed | ServiceRequest.identifier |
| ReferralRequest.date | UseElementRenamed | ServiceRequest.authoredOn |
| ReferralRequest.type | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.type |
| ReferralRequest.specialty | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.specialty |
| ReferralRequest.priority | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.priority |
| ReferralRequest.patient | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.patient |
| ReferralRequest.requester | UseElementRenamed | ServiceRequest.requester |
| ReferralRequest.recipient | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.recipient |
| ReferralRequest.encounter | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.encounter |
| ReferralRequest.dateSent | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.dateSent |
| ReferralRequest.reason | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.reason |
| ReferralRequest.description | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.description |
| ReferralRequest.serviceRequested | UseElementRenamed | ServiceRequest.code |
| ReferralRequest.supportingInformation | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.supportingInformation |
| ReferralRequest.fulfillmentTime | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.fulfillmentTime |
