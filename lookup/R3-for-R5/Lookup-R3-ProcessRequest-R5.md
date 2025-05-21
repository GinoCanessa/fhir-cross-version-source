### Lookup for FHIR R3 ProcessRequest for use in FHIR R5

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| ProcessRequest.id | UseElementRenamed | Task.id |
| ProcessRequest.meta | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessRequest.meta |
| ProcessRequest.implicitRules | UseElementRenamed | Task.implicitRules |
| ProcessRequest.language | UseElementRenamed | Task.language |
| ProcessRequest.text | UseElementRenamed | Task.text |
| ProcessRequest.contained | UseElementRenamed | Task.contained |
| ProcessRequest.extension | UseElementRenamed | Task.extension |
| ProcessRequest.modifierExtension | UseElementRenamed | Task.modifierExtension |
| ProcessRequest.identifier | UseElementRenamed | Task.identifier |
| ProcessRequest.status | UseElementRenamed | Task.status |
| ProcessRequest.action | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessRequest.action |
| ProcessRequest.target | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessRequest.target |
| ProcessRequest.created | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessRequest.created |
| ProcessRequest.provider | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessRequest.provider |
| ProcessRequest.organization | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessRequest.organization |
| ProcessRequest.request | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessRequest.request |
| ProcessRequest.response | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessRequest.response |
| ProcessRequest.nullify | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessRequest.nullify |
| ProcessRequest.reference | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessRequest.reference |
| ProcessRequest.item | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessRequest.item |
| ProcessRequest.item.id | UseExtensionFromAncestor | - |
| ProcessRequest.item.extension | UseExtensionFromAncestor | - |
| ProcessRequest.item.modifierExtension | UseExtensionFromAncestor | - |
| ProcessRequest.item.sequenceLinkId | UseExtensionFromAncestor | - |
| ProcessRequest.include | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessRequest.include |
| ProcessRequest.exclude | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessRequest.exclude |
| ProcessRequest.period | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ProcessRequest.period |
