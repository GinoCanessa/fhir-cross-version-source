### Lookup for FHIR R5 Communication for use in FHIR R4B

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
| Communication.instantiatesCanonical | UseElementSameName | Communication.instantiatesCanonical |
| Communication.instantiatesUri | UseElementSameName | Communication.instantiatesUri |
| Communication.basedOn | UseElementSameName | Communication.basedOn |
| Communication.partOf | UseElementSameName | Communication.partOf |
| Communication.inResponseTo | UseElementSameName | Communication.inResponseTo |
| Communication.status | UseOneOfElements | Communication.status,Communication.status |
| Communication.statusReason | UseElementSameName | Communication.statusReason |
| Communication.category | UseElementSameName | Communication.category |
| Communication.priority | UseElementSameName | Communication.priority |
| Communication.medium | UseElementSameName | Communication.medium |
| Communication.subject | UseElementSameName | Communication.subject |
| Communication.topic | UseElementSameName | Communication.topic |
| Communication.about | UseElementSameName | Communication.about |
| Communication.encounter | UseElementSameName | Communication.encounter |
| Communication.sent | UseElementSameName | Communication.sent |
| Communication.received | UseElementSameName | Communication.received |
| Communication.recipient | UseElementSameName | Communication.recipient |
| Communication.sender | UseElementSameName | Communication.sender |
| Communication.reason | UseOneOfElements | Communication.reasonCode,Communication.reasonReference |
| Communication.payload | UseElementSameName | Communication.payload |
| Communication.payload.id | UseElementSameName | Communication.payload.id |
| Communication.payload.extension | UseElementSameName | Communication.payload.extension |
| Communication.payload.modifierExtension | UseElementSameName | Communication.payload.modifierExtension |
| Communication.payload.content[x] | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Communication.payload.content |
| Communication.note | UseElementSameName | Communication.note |
