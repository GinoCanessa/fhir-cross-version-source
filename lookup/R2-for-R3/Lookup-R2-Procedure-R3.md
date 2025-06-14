### Lookup for FHIR R2 Procedure for use in FHIR R3

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Procedure.id | UseElementSameName | Procedure.id |
| Procedure.meta | UseElementSameName | Procedure.meta |
| Procedure.implicitRules | UseElementSameName | Procedure.implicitRules |
| Procedure.language | UseElementSameName | Procedure.language |
| Procedure.text | UseElementSameName | Procedure.text |
| Procedure.contained | UseElementSameName | Procedure.contained |
| Procedure.extension | UseElementSameName | Procedure.extension |
| Procedure.modifierExtension | UseElementSameName | Procedure.modifierExtension |
| Procedure.identifier | UseElementSameName | Procedure.identifier |
| Procedure.subject | UseElementSameName | Procedure.subject |
| Procedure.status | UseElementSameName | Procedure.status |
| Procedure.category | UseElementSameName | Procedure.category |
| Procedure.code | UseElementSameName | Procedure.code |
| Procedure.notPerformed | UseOneOfElements | Procedure.notDone,Procedure.notDone |
| Procedure.reasonNotPerformed | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Procedure.reasonNotPerformed |
| Procedure.bodySite | UseElementSameName | Procedure.bodySite |
| Procedure.reason[x] | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Procedure.reason |
| Procedure.performer | UseElementSameName | Procedure.performer |
| Procedure.performer.id | UseElementSameName | Procedure.performer.id |
| Procedure.performer.extension | UseElementSameName | Procedure.performer.extension |
| Procedure.performer.modifierExtension | UseElementSameName | Procedure.performer.modifierExtension |
| Procedure.performer.actor | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Procedure.performer.actor |
| Procedure.performer.role | UseElementSameName | Procedure.performer.role |
| Procedure.performed[x] | UseElementSameName | Procedure.performed[x] |
| Procedure.encounter | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Procedure.encounter |
| Procedure.location | UseElementSameName | Procedure.location |
| Procedure.outcome | UseElementSameName | Procedure.outcome |
| Procedure.report | UseElementSameName | Procedure.report |
| Procedure.complication | UseElementSameName | Procedure.complication |
| Procedure.followUp | UseElementSameName | Procedure.followUp |
| Procedure.request | UseElementRenamed | Procedure.basedOn |
| Procedure.notes | UseElementRenamed | Procedure.note |
| Procedure.focalDevice | UseElementSameName | Procedure.focalDevice |
| Procedure.focalDevice.id | UseElementSameName | Procedure.focalDevice.id |
| Procedure.focalDevice.extension | UseElementSameName | Procedure.focalDevice.extension |
| Procedure.focalDevice.modifierExtension | UseElementSameName | Procedure.focalDevice.modifierExtension |
| Procedure.focalDevice.action | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Procedure.focalDevice.action |
| Procedure.focalDevice.manipulated | UseElementSameName | Procedure.focalDevice.manipulated |
| Procedure.used | UseElementRenamed | Procedure.usedReference |
