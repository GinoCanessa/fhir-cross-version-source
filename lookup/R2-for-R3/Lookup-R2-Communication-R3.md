### Lookup for FHIR R2 Communication for use in FHIR R3

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
| Communication.category | UseElementSameName | Communication.category |
| Communication.sender | UseElementSameName | Communication.sender |
| Communication.recipient | UseElementSameName | Communication.recipient |
| Communication.payload | UseElementSameName | Communication.payload |
| Communication.payload.id | UseElementSameName | Communication.payload.id |
| Communication.payload.extension | UseElementSameName | Communication.payload.extension |
| Communication.payload.modifierExtension | UseElementSameName | Communication.payload.modifierExtension |
| Communication.payload.content[x] | UseElementSameName | Communication.payload.content[x] |
| Communication.medium | UseElementSameName | Communication.medium |
| Communication.status | UseElementSameName | Communication.status |
| Communication.encounter | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Communication.encounter |
| Communication.sent | UseElementSameName | Communication.sent |
| Communication.received | UseElementSameName | Communication.received |
| Communication.reason | UseElementRenamed | Communication.reasonCode |
| Communication.subject | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Communication.subject |
| Communication.requestDetail | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Communication.requestDetail |
