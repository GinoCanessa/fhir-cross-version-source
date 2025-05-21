### Lookup for FHIR R2 CommunicationRequest for use in FHIR R4

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| CommunicationRequest.id | UseElementSameName | CommunicationRequest.id |
| CommunicationRequest.meta | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-CommunicationRequest.meta |
| CommunicationRequest.implicitRules | UseElementSameName | CommunicationRequest.implicitRules |
| CommunicationRequest.language | UseElementSameName | CommunicationRequest.language |
| CommunicationRequest.text | UseElementSameName | CommunicationRequest.text |
| CommunicationRequest.contained | UseElementSameName | CommunicationRequest.contained |
| CommunicationRequest.extension | UseElementSameName | CommunicationRequest.extension |
| CommunicationRequest.modifierExtension | UseElementSameName | CommunicationRequest.modifierExtension |
| CommunicationRequest.identifier | UseElementSameName | CommunicationRequest.identifier |
| CommunicationRequest.category | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-CommunicationRequest.category |
| CommunicationRequest.sender | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-CommunicationRequest.sender |
| CommunicationRequest.recipient | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-CommunicationRequest.recipient |
| CommunicationRequest.payload | UseElementSameName | CommunicationRequest.payload |
| CommunicationRequest.payload.id | UseElementSameName | CommunicationRequest.payload.id |
| CommunicationRequest.payload.extension | UseElementSameName | CommunicationRequest.payload.extension |
| CommunicationRequest.payload.modifierExtension | UseElementSameName | CommunicationRequest.payload.modifierExtension |
| CommunicationRequest.payload.content[x] | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-CommunicationRequest.payload.content |
| CommunicationRequest.medium | UseElementSameName | CommunicationRequest.medium |
| CommunicationRequest.requester | UseElementSameName | CommunicationRequest.requester |
| CommunicationRequest.status | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-CommunicationRequest.status |
| CommunicationRequest.encounter | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-CommunicationRequest.encounter |
| CommunicationRequest.scheduled[x] | UseElementRenamed | CommunicationRequest.occurrence[x] |
| CommunicationRequest.reason | UseElementRenamed | CommunicationRequest.reasonCode |
| CommunicationRequest.requestedOn | UseElementRenamed | CommunicationRequest.authoredOn |
| CommunicationRequest.subject | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-CommunicationRequest.subject |
| CommunicationRequest.priority | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-CommunicationRequest.priority |
