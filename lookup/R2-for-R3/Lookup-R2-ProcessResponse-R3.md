### Lookup for FHIR R2 ProcessResponse for use in FHIR R3

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
| ProcessResponse.request | UseElementSameName | ProcessResponse.request |
| ProcessResponse.outcome | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ProcessResponse.outcome |
| ProcessResponse.disposition | UseElementSameName | ProcessResponse.disposition |
| ProcessResponse.ruleset | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ProcessResponse.ruleset |
| ProcessResponse.originalRuleset | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ProcessResponse.originalRuleset |
| ProcessResponse.created | UseElementSameName | ProcessResponse.created |
| ProcessResponse.organization | UseElementSameName | ProcessResponse.organization |
| ProcessResponse.requestProvider | UseElementSameName | ProcessResponse.requestProvider |
| ProcessResponse.requestOrganization | UseElementSameName | ProcessResponse.requestOrganization |
| ProcessResponse.form | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ProcessResponse.form |
| ProcessResponse.notes | UseElementRenamed | ProcessResponse.processNote |
| ProcessResponse.notes.id | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ProcessResponse.notes.id |
| ProcessResponse.notes.extension | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ProcessResponse.notes.extension |
| ProcessResponse.notes.modifierExtension | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ProcessResponse.notes.modifierExtension |
| ProcessResponse.notes.type | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ProcessResponse.notes.type |
| ProcessResponse.notes.text | UseElementRenamed | ProcessResponse.processNote.text |
| ProcessResponse.error | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-ProcessResponse.error |
