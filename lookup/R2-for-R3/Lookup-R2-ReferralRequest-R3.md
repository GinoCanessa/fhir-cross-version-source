### Lookup for FHIR R2 ReferralRequest for use in FHIR R3

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| ReferralRequest.id | UseElementSameName | ReferralRequest.id |
| ReferralRequest.meta | UseElementSameName | ReferralRequest.meta |
| ReferralRequest.implicitRules | UseElementSameName | ReferralRequest.implicitRules |
| ReferralRequest.language | UseElementSameName | ReferralRequest.language |
| ReferralRequest.text | UseElementSameName | ReferralRequest.text |
| ReferralRequest.contained | UseElementSameName | ReferralRequest.contained |
| ReferralRequest.extension | UseElementSameName | ReferralRequest.extension |
| ReferralRequest.modifierExtension | UseElementSameName | ReferralRequest.modifierExtension |
| ReferralRequest.status | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.status |
| ReferralRequest.identifier | UseElementSameName | ReferralRequest.identifier |
| ReferralRequest.date | UseElementRenamed | ReferralRequest.authoredOn |
| ReferralRequest.type | UseElementSameName | ReferralRequest.type |
| ReferralRequest.specialty | UseElementSameName | ReferralRequest.specialty |
| ReferralRequest.priority | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.priority |
| ReferralRequest.patient | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.patient |
| ReferralRequest.requester | UseElementSameName | ReferralRequest.requester |
| ReferralRequest.recipient | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.recipient |
| ReferralRequest.encounter | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.encounter |
| ReferralRequest.dateSent | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.dateSent |
| ReferralRequest.reason | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.reason |
| ReferralRequest.description | UseElementSameName | ReferralRequest.description |
| ReferralRequest.serviceRequested | UseElementSameName | ReferralRequest.serviceRequested |
| ReferralRequest.supportingInformation | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.supportingInformation |
| ReferralRequest.fulfillmentTime | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.fulfillmentTime |
