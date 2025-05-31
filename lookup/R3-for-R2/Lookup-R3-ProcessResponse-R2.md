### Lookup for FHIR R3 ProcessResponse for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| ProcessResponse.id | UseElementRenamed | ProcessResponse.id |
| ProcessResponse.meta | UseElementRenamed | ProcessResponse.meta |
| ProcessResponse.implicitRules | UseElementRenamed | ProcessResponse.implicitRules |
| ProcessResponse.language | UseElementRenamed | ProcessResponse.language |
| ProcessResponse.text | UseElementRenamed | ProcessResponse.text |
| ProcessResponse.contained | UseElementRenamed | ProcessResponse.contained |
| ProcessResponse.extension | UseElementRenamed | ProcessResponse.extension |
| ProcessResponse.modifierExtension | UseElementRenamed | ProcessResponse.modifierExtension |
| ProcessResponse.identifier | UseElementRenamed | ProcessResponse.identifier |
| ProcessResponse.status | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessResponse.status |
| ProcessResponse.created | UseElementRenamed | ProcessResponse.created |
| ProcessResponse.organization | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessResponse.organization |
| ProcessResponse.request | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessResponse.request |
| ProcessResponse.outcome | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessResponse.outcome |
| ProcessResponse.disposition | UseElementRenamed | ProcessResponse.disposition |
| ProcessResponse.requestProvider | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessResponse.requestProvider |
| ProcessResponse.requestOrganization | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessResponse.requestOrganization |
| ProcessResponse.form | UseElementRenamed | ProcessResponse.form |
| ProcessResponse.processNote | UseElementRenamed | ProcessResponse.notes |
| ProcessResponse.processNote.id | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessResponse.processNote.id |
| ProcessResponse.processNote.extension | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessResponse.processNote.extension |
| ProcessResponse.processNote.modifierExtension | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessResponse.processNote.modifierExtension |
| ProcessResponse.processNote.type | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessResponse.processNote.type |
| ProcessResponse.processNote.text | UseElementRenamed | ProcessResponse.notes.text |
| ProcessResponse.error | UseElementRenamed | ProcessResponse.error |
| ProcessResponse.communicationRequest | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessResponse.communicationRequest |
