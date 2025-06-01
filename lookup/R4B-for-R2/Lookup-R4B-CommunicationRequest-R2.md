### Lookup for FHIR R4B CommunicationRequest for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| CommunicationRequest.id | UseElementSameName | CommunicationRequest.id |
| CommunicationRequest.meta | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CommunicationRequest.meta |
| CommunicationRequest.implicitRules | UseElementSameName | CommunicationRequest.implicitRules |
| CommunicationRequest.language | UseElementSameName | CommunicationRequest.language |
| CommunicationRequest.text | UseElementSameName | CommunicationRequest.text |
| CommunicationRequest.contained | UseElementSameName | CommunicationRequest.contained |
| CommunicationRequest.extension | UseElementSameName | CommunicationRequest.extension |
| CommunicationRequest.modifierExtension | UseElementSameName | CommunicationRequest.modifierExtension |
| CommunicationRequest.identifier | UseElementSameName | CommunicationRequest.identifier |
| CommunicationRequest.basedOn | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CommunicationRequest.basedOn |
| CommunicationRequest.replaces | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CommunicationRequest.replaces |
| CommunicationRequest.groupIdentifier | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CommunicationRequest.groupIdentifier |
| CommunicationRequest.status | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CommunicationRequest.status |
| CommunicationRequest.statusReason | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CommunicationRequest.statusReason |
| CommunicationRequest.category | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CommunicationRequest.category |
| CommunicationRequest.priority | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CommunicationRequest.priority |
| CommunicationRequest.doNotPerform | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CommunicationRequest.doNotPerform |
| CommunicationRequest.medium | UseElementSameName | CommunicationRequest.medium |
| CommunicationRequest.subject | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CommunicationRequest.subject |
| CommunicationRequest.about | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CommunicationRequest.about |
| CommunicationRequest.encounter | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CommunicationRequest.encounter |
| CommunicationRequest.payload | UseElementSameName | CommunicationRequest.payload |
| CommunicationRequest.payload.id | UseElementSameName | CommunicationRequest.payload.id |
| CommunicationRequest.payload.extension | UseElementSameName | CommunicationRequest.payload.extension |
| CommunicationRequest.payload.modifierExtension | UseElementSameName | CommunicationRequest.payload.modifierExtension |
| CommunicationRequest.payload.content[x] | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CommunicationRequest.payload.content |
| CommunicationRequest.occurrence[x] | UseElementRenamed | CommunicationRequest.scheduled[x] |
| CommunicationRequest.authoredOn | UseElementRenamed | CommunicationRequest.requestedOn |
| CommunicationRequest.requester | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CommunicationRequest.requester |
| CommunicationRequest.recipient | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CommunicationRequest.recipient |
| CommunicationRequest.sender | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CommunicationRequest.sender |
| CommunicationRequest.reasonCode | UseElementRenamed | CommunicationRequest.reason |
| CommunicationRequest.reasonReference | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CommunicationRequest.reasonReference |
| CommunicationRequest.note | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-CommunicationRequest.note |
