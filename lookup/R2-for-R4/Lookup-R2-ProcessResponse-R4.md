### Lookup for FHIR R2 ProcessResponse for use in FHIR R4

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| ProcessResponse.id | UseElementRenamed | Task.id |
| ProcessResponse.meta | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ProcessResponse.meta |
| ProcessResponse.implicitRules | UseElementRenamed | Task.implicitRules |
| ProcessResponse.language | UseElementRenamed | Task.language |
| ProcessResponse.text | UseElementRenamed | Task.text |
| ProcessResponse.contained | UseElementRenamed | Task.contained |
| ProcessResponse.extension | UseElementRenamed | Task.extension |
| ProcessResponse.modifierExtension | UseElementRenamed | Task.modifierExtension |
| ProcessResponse.identifier | UseElementRenamed | Task.identifier |
| ProcessResponse.request | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ProcessResponse.request |
| ProcessResponse.outcome | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ProcessResponse.outcome |
| ProcessResponse.disposition | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ProcessResponse.disposition |
| ProcessResponse.ruleset | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ProcessResponse.ruleset |
| ProcessResponse.originalRuleset | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ProcessResponse.originalRuleset |
| ProcessResponse.created | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ProcessResponse.created |
| ProcessResponse.organization | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ProcessResponse.organization |
| ProcessResponse.requestProvider | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ProcessResponse.requestProvider |
| ProcessResponse.requestOrganization | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ProcessResponse.requestOrganization |
| ProcessResponse.form | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ProcessResponse.form |
| ProcessResponse.notes | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ProcessResponse.notes |
| ProcessResponse.notes.id | UseExtensionFromAncestor | - |
| ProcessResponse.notes.extension | UseExtensionFromAncestor | - |
| ProcessResponse.notes.modifierExtension | UseExtensionFromAncestor | - |
| ProcessResponse.notes.type | UseExtensionFromAncestor | - |
| ProcessResponse.notes.text | UseExtensionFromAncestor | - |
| ProcessResponse.error | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ProcessResponse.error |
