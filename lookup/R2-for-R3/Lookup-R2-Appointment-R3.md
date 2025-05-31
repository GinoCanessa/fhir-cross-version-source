### Lookup for FHIR R2 Appointment for use in FHIR R3

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Appointment.id | UseElementSameName | Appointment.id |
| Appointment.meta | UseElementSameName | Appointment.meta |
| Appointment.implicitRules | UseElementSameName | Appointment.implicitRules |
| Appointment.language | UseElementSameName | Appointment.language |
| Appointment.text | UseElementSameName | Appointment.text |
| Appointment.contained | UseElementSameName | Appointment.contained |
| Appointment.extension | UseElementSameName | Appointment.extension |
| Appointment.modifierExtension | UseElementSameName | Appointment.modifierExtension |
| Appointment.identifier | UseElementSameName | Appointment.identifier |
| Appointment.status | UseElementSameName | Appointment.status |
| Appointment.type | UseElementRenamed | Appointment.serviceType |
| Appointment.reason | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Appointment.reason |
| Appointment.priority | UseElementSameName | Appointment.priority |
| Appointment.description | UseElementSameName | Appointment.description |
| Appointment.start | UseElementSameName | Appointment.start |
| Appointment.end | UseElementSameName | Appointment.end |
| Appointment.minutesDuration | UseElementSameName | Appointment.minutesDuration |
| Appointment.slot | UseElementSameName | Appointment.slot |
| Appointment.comment | UseElementSameName | Appointment.comment |
| Appointment.participant | UseElementSameName | Appointment.participant |
| Appointment.participant.id | UseElementSameName | Appointment.participant.id |
| Appointment.participant.extension | UseElementSameName | Appointment.participant.extension |
| Appointment.participant.modifierExtension | UseElementSameName | Appointment.participant.modifierExtension |
| Appointment.participant.type | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Appointment.participant.type |
| Appointment.participant.actor | UseElementSameName | Appointment.participant.actor |
| Appointment.participant.required | UseElementSameName | Appointment.participant.required |
| Appointment.participant.status | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Appointment.participant.status |
