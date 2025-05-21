### Lookup for FHIR R2 ProcedureRequest for use in FHIR R3

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| ProcedureRequest.id | UseElementSameName | ProcedureRequest.id |
| ProcedureRequest.meta | UseElementSameName | ProcedureRequest.meta |
| ProcedureRequest.implicitRules | UseElementSameName | ProcedureRequest.implicitRules |
| ProcedureRequest.language | UseElementSameName | ProcedureRequest.language |
| ProcedureRequest.text | UseElementSameName | ProcedureRequest.text |
| ProcedureRequest.contained | UseElementSameName | ProcedureRequest.contained |
| ProcedureRequest.extension | UseElementSameName | ProcedureRequest.extension |
| ProcedureRequest.modifierExtension | UseElementSameName | ProcedureRequest.modifierExtension |
| ProcedureRequest.identifier | UseElementSameName | ProcedureRequest.identifier |
| ProcedureRequest.subject | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ProcedureRequest.subject |
| ProcedureRequest.code | UseElementSameName | ProcedureRequest.code |
| ProcedureRequest.bodySite | UseElementSameName | ProcedureRequest.bodySite |
| ProcedureRequest.reason[x] | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ProcedureRequest.reason |
| ProcedureRequest.scheduled[x] | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ProcedureRequest.scheduled |
| ProcedureRequest.encounter | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ProcedureRequest.encounter |
| ProcedureRequest.performer | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ProcedureRequest.performer |
| ProcedureRequest.status | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ProcedureRequest.status |
| ProcedureRequest.notes | UseElementRenamed | ProcedureRequest.note |
| ProcedureRequest.asNeeded[x] | UseElementSameName | ProcedureRequest.asNeeded[x] |
| ProcedureRequest.orderedOn | UseElementRenamed | ProcedureRequest.authoredOn |
| ProcedureRequest.orderer | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ProcedureRequest.orderer |
| ProcedureRequest.priority | UseElementSameName | ProcedureRequest.priority |
