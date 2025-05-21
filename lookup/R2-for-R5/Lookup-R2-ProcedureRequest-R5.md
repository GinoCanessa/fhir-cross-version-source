### Lookup for FHIR R2 ProcedureRequest for use in FHIR R5

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| ProcedureRequest.id | UseElementRenamed | ServiceRequest.id |
| ProcedureRequest.meta | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ProcedureRequest.meta |
| ProcedureRequest.implicitRules | UseElementRenamed | ServiceRequest.implicitRules |
| ProcedureRequest.language | UseElementRenamed | ServiceRequest.language |
| ProcedureRequest.text | UseElementRenamed | ServiceRequest.text |
| ProcedureRequest.contained | UseElementRenamed | ServiceRequest.contained |
| ProcedureRequest.extension | UseElementRenamed | ServiceRequest.extension |
| ProcedureRequest.modifierExtension | UseElementRenamed | ServiceRequest.modifierExtension |
| ProcedureRequest.identifier | UseElementRenamed | ServiceRequest.identifier |
| ProcedureRequest.subject | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ProcedureRequest.subject |
| ProcedureRequest.code | UseElementRenamed | ServiceRequest.code |
| ProcedureRequest.bodySite | UseElementRenamed | ServiceRequest.bodySite |
| ProcedureRequest.reason[x] | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ProcedureRequest.reason |
| ProcedureRequest.scheduled[x] | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ProcedureRequest.scheduled |
| ProcedureRequest.encounter | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ProcedureRequest.encounter |
| ProcedureRequest.performer | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ProcedureRequest.performer |
| ProcedureRequest.status | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ProcedureRequest.status |
| ProcedureRequest.notes | UseElementRenamed | ServiceRequest.note |
| ProcedureRequest.asNeeded[x] | UseElementRenamed | ServiceRequest.asNeeded[x] |
| ProcedureRequest.orderedOn | UseElementRenamed | ServiceRequest.authoredOn |
| ProcedureRequest.orderer | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ProcedureRequest.orderer |
| ProcedureRequest.priority | UseElementRenamed | ServiceRequest.priority |
