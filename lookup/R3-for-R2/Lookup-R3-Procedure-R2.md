### Lookup for FHIR R3 Procedure for use in FHIR R2

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
| Procedure.definition | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Procedure.definition |
| Procedure.basedOn | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Procedure.basedOn |
| Procedure.partOf | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Procedure.partOf |
| Procedure.status | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Procedure.status |
| Procedure.notDone | UseOneOfElements | Procedure.notPerformed,Procedure.notPerformed |
| Procedure.notDoneReason | UseOneOfElements | Procedure.reasonNotPerformed,Procedure.reasonNotPerformed |
| Procedure.category | UseElementSameName | Procedure.category |
| Procedure.code | UseElementSameName | Procedure.code |
| Procedure.subject | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Procedure.subject |
| Procedure.context | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Procedure.context |
| Procedure.performed[x] | UseElementSameName | Procedure.performed[x] |
| Procedure.performer | UseElementSameName | Procedure.performer |
| Procedure.performer.id | UseElementSameName | Procedure.performer.id |
| Procedure.performer.extension | UseElementSameName | Procedure.performer.extension |
| Procedure.performer.modifierExtension | UseElementSameName | Procedure.performer.modifierExtension |
| Procedure.performer.role | UseElementSameName | Procedure.performer.role |
| Procedure.performer.actor | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Procedure.performer.actor |
| Procedure.performer.onBehalfOf | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Procedure.performer.onBehalfOf |
| Procedure.location | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Procedure.location |
| Procedure.reasonCode | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Procedure.reasonCode |
| Procedure.reasonReference | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Procedure.reasonReference |
| Procedure.bodySite | UseElementSameName | Procedure.bodySite |
| Procedure.outcome | UseElementSameName | Procedure.outcome |
| Procedure.report | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Procedure.report |
| Procedure.complication | UseElementSameName | Procedure.complication |
| Procedure.complicationDetail | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Procedure.complicationDetail |
| Procedure.followUp | UseElementSameName | Procedure.followUp |
| Procedure.note | UseElementRenamed | Procedure.notes |
| Procedure.focalDevice | UseElementSameName | Procedure.focalDevice |
| Procedure.focalDevice.id | UseElementSameName | Procedure.focalDevice.id |
| Procedure.focalDevice.extension | UseElementSameName | Procedure.focalDevice.extension |
| Procedure.focalDevice.modifierExtension | UseElementSameName | Procedure.focalDevice.modifierExtension |
| Procedure.focalDevice.action | UseElementSameName | Procedure.focalDevice.action |
| Procedure.focalDevice.manipulated | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Procedure.focalDevice.manipulated |
| Procedure.usedReference | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Procedure.usedReference |
| Procedure.usedCode | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Procedure.usedCode |
