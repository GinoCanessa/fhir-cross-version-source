### Lookup for FHIR R3 ProcessResponse for use in FHIR R4B

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| ProcessResponse.id | UseElementRenamed | Task.id |
| ProcessResponse.meta | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessResponse.meta |
| ProcessResponse.implicitRules | UseElementRenamed | Task.implicitRules |
| ProcessResponse.language | UseElementRenamed | Task.language |
| ProcessResponse.text | UseElementRenamed | Task.text |
| ProcessResponse.contained | UseElementRenamed | Task.contained |
| ProcessResponse.extension | UseElementRenamed | Task.extension |
| ProcessResponse.modifierExtension | UseElementRenamed | Task.modifierExtension |
| ProcessResponse.identifier | UseElementRenamed | Task.identifier |
| ProcessResponse.status | UseElementRenamed | Task.status |
| ProcessResponse.created | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessResponse.created |
| ProcessResponse.organization | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessResponse.organization |
| ProcessResponse.request | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessResponse.request |
| ProcessResponse.outcome | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessResponse.outcome |
| ProcessResponse.disposition | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessResponse.disposition |
| ProcessResponse.requestProvider | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessResponse.requestProvider |
| ProcessResponse.requestOrganization | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessResponse.requestOrganization |
| ProcessResponse.form | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessResponse.form |
| ProcessResponse.processNote | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessResponse.processNote |
| ProcessResponse.processNote.id | UseExtensionFromAncestor | - |
| ProcessResponse.processNote.extension | UseExtensionFromAncestor | - |
| ProcessResponse.processNote.modifierExtension | UseExtensionFromAncestor | - |
| ProcessResponse.processNote.type | UseExtensionFromAncestor | - |
| ProcessResponse.processNote.text | UseExtensionFromAncestor | - |
| ProcessResponse.error | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessResponse.error |
| ProcessResponse.communicationRequest | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessResponse.communicationRequest |
