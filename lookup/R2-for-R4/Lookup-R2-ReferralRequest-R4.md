### Lookup for FHIR R2 ReferralRequest for use in FHIR R4

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| ReferralRequest.id | UseElementRenamed | ServiceRequest.id |
| ReferralRequest.meta | UseElementRenamed | ServiceRequest.meta |
| ReferralRequest.implicitRules | UseElementRenamed | ServiceRequest.implicitRules |
| ReferralRequest.language | UseElementRenamed | ServiceRequest.language |
| ReferralRequest.text | UseElementRenamed | ServiceRequest.text |
| ReferralRequest.contained | UseElementRenamed | ServiceRequest.contained |
| ReferralRequest.extension | UseElementRenamed | ServiceRequest.extension |
| ReferralRequest.modifierExtension | UseElementRenamed | ServiceRequest.modifierExtension |
| ReferralRequest.status | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.status |
| ReferralRequest.identifier | UseElementRenamed | ServiceRequest.identifier |
| ReferralRequest.date | UseElementRenamed | ServiceRequest.authoredOn |
| ReferralRequest.type | UseElementRenamed | ServiceRequest.category |
| ReferralRequest.specialty | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.specialty |
| ReferralRequest.priority | UseElementRenamed | ServiceRequest.priority |
| ReferralRequest.patient | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.patient |
| ReferralRequest.requester | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.requester |
| ReferralRequest.recipient | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.recipient |
| ReferralRequest.encounter | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.encounter |
| ReferralRequest.dateSent | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.dateSent |
| ReferralRequest.reason | UseElementRenamed | ServiceRequest.reasonCode |
| ReferralRequest.description | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.description |
| ReferralRequest.serviceRequested | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.serviceRequested |
| ReferralRequest.supportingInformation | UseElementRenamed | ServiceRequest.supportingInfo |
| ReferralRequest.fulfillmentTime | UseElementRenamed | ServiceRequest.occurrence[x] |
