### Lookup for FHIR R4 CommunicationRequest for use in FHIR R5

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| CommunicationRequest.id | UseElementSameName | CommunicationRequest.id |
| CommunicationRequest.meta | UseElementSameName | CommunicationRequest.meta |
| CommunicationRequest.implicitRules | UseElementSameName | CommunicationRequest.implicitRules |
| CommunicationRequest.language | UseElementSameName | CommunicationRequest.language |
| CommunicationRequest.text | UseElementSameName | CommunicationRequest.text |
| CommunicationRequest.contained | UseElementSameName | CommunicationRequest.contained |
| CommunicationRequest.extension | UseElementSameName | CommunicationRequest.extension |
| CommunicationRequest.modifierExtension | UseElementSameName | CommunicationRequest.modifierExtension |
| CommunicationRequest.identifier | UseElementSameName | CommunicationRequest.identifier |
| CommunicationRequest.basedOn | UseElementSameName | CommunicationRequest.basedOn |
| CommunicationRequest.replaces | UseElementSameName | CommunicationRequest.replaces |
| CommunicationRequest.groupIdentifier | UseElementSameName | CommunicationRequest.groupIdentifier |
| CommunicationRequest.status | UseElementSameName | CommunicationRequest.status |
| CommunicationRequest.statusReason | UseElementSameName | CommunicationRequest.statusReason |
| CommunicationRequest.category | UseElementSameName | CommunicationRequest.category |
| CommunicationRequest.priority | UseElementSameName | CommunicationRequest.priority |
| CommunicationRequest.doNotPerform | UseElementSameName | CommunicationRequest.doNotPerform |
| CommunicationRequest.medium | UseElementSameName | CommunicationRequest.medium |
| CommunicationRequest.subject | UseElementSameName | CommunicationRequest.subject |
| CommunicationRequest.about | UseElementSameName | CommunicationRequest.about |
| CommunicationRequest.encounter | UseElementSameName | CommunicationRequest.encounter |
| CommunicationRequest.payload | UseElementSameName | CommunicationRequest.payload |
| CommunicationRequest.payload.id | UseElementSameName | CommunicationRequest.payload.id |
| CommunicationRequest.payload.extension | UseElementSameName | CommunicationRequest.payload.extension |
| CommunicationRequest.payload.modifierExtension | UseElementSameName | CommunicationRequest.payload.modifierExtension |
| CommunicationRequest.payload.content[x] | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-CommunicationRequest.payload.content |
| CommunicationRequest.occurrence[x] | UseElementSameName | CommunicationRequest.occurrence[x] |
| CommunicationRequest.authoredOn | UseElementSameName | CommunicationRequest.authoredOn |
| CommunicationRequest.requester | UseOneOfElements | CommunicationRequest.requester,CommunicationRequest.requester |
| CommunicationRequest.recipient | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-CommunicationRequest.recipient |
| CommunicationRequest.sender | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-CommunicationRequest.sender |
| CommunicationRequest.reasonCode | UseElementRenamed | CommunicationRequest.reason |
| CommunicationRequest.reasonReference | UseElementRenamed | CommunicationRequest.reason |
| CommunicationRequest.note | UseElementSameName | CommunicationRequest.note |
