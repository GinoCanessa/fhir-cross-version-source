### Lookup for FHIR R3 Communication for use in FHIR R4

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Communication.id | UseElementSameName | Communication.id |
| Communication.meta | UseElementSameName | Communication.meta |
| Communication.implicitRules | UseElementSameName | Communication.implicitRules |
| Communication.language | UseElementSameName | Communication.language |
| Communication.text | UseElementSameName | Communication.text |
| Communication.contained | UseElementSameName | Communication.contained |
| Communication.extension | UseElementSameName | Communication.extension |
| Communication.modifierExtension | UseElementSameName | Communication.modifierExtension |
| Communication.identifier | UseElementSameName | Communication.identifier |
| Communication.definition | UseElementRenamed | Communication.instantiatesCanonical |
| Communication.basedOn | UseElementSameName | Communication.basedOn |
| Communication.partOf | UseElementSameName | Communication.partOf |
| Communication.status | UseElementSameName | Communication.status |
| Communication.notDone | UseElementRenamed | Communication.status |
| Communication.notDoneReason | UseElementRenamed | Communication.statusReason |
| Communication.category | UseElementSameName | Communication.category |
| Communication.medium | UseElementSameName | Communication.medium |
| Communication.subject | UseElementSameName | Communication.subject |
| Communication.recipient | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Communication.recipient |
| Communication.topic | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Communication.topic |
| Communication.context | UseElementRenamed | Communication.encounter |
| Communication.sent | UseElementSameName | Communication.sent |
| Communication.received | UseElementSameName | Communication.received |
| Communication.sender | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Communication.sender |
| Communication.reasonCode | UseElementSameName | Communication.reasonCode |
| Communication.reasonReference | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Communication.reasonReference |
| Communication.payload | UseElementSameName | Communication.payload |
| Communication.payload.id | UseElementSameName | Communication.payload.id |
| Communication.payload.extension | UseElementSameName | Communication.payload.extension |
| Communication.payload.modifierExtension | UseElementSameName | Communication.payload.modifierExtension |
| Communication.payload.content[x] | UseElementSameName | Communication.payload.content[x] |
| Communication.note | UseElementSameName | Communication.note |
