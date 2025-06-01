### Lookup for FHIR R3 ProcessResponse for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| ProcessResponse.id | UseElementSameName | ProcessResponse.id |
| ProcessResponse.meta | UseElementSameName | ProcessResponse.meta |
| ProcessResponse.implicitRules | UseElementSameName | ProcessResponse.implicitRules |
| ProcessResponse.language | UseElementSameName | ProcessResponse.language |
| ProcessResponse.text | UseElementSameName | ProcessResponse.text |
| ProcessResponse.contained | UseElementSameName | ProcessResponse.contained |
| ProcessResponse.extension | UseElementSameName | ProcessResponse.extension |
| ProcessResponse.modifierExtension | UseElementSameName | ProcessResponse.modifierExtension |
| ProcessResponse.identifier | UseElementSameName | ProcessResponse.identifier |
| ProcessResponse.status | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessResponse.status |
| ProcessResponse.created | UseElementSameName | ProcessResponse.created |
| ProcessResponse.organization | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessResponse.organization |
| ProcessResponse.request | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessResponse.request |
| ProcessResponse.outcome | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessResponse.outcome |
| ProcessResponse.disposition | UseElementSameName | ProcessResponse.disposition |
| ProcessResponse.requestProvider | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessResponse.requestProvider |
| ProcessResponse.requestOrganization | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessResponse.requestOrganization |
| ProcessResponse.form | UseElementSameName | ProcessResponse.form |
| ProcessResponse.processNote | UseElementRenamed | ProcessResponse.notes |
| ProcessResponse.processNote.id | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessResponse.processNote.id |
| ProcessResponse.processNote.extension | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessResponse.processNote.extension |
| ProcessResponse.processNote.modifierExtension | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessResponse.processNote.modifierExtension |
| ProcessResponse.processNote.type | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessResponse.processNote.type |
| ProcessResponse.processNote.text | UseElementRenamed | ProcessResponse.notes.text |
| ProcessResponse.error | UseElementSameName | ProcessResponse.error |
| ProcessResponse.communicationRequest | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessResponse.communicationRequest |
