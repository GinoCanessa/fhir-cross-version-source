### Lookup for FHIR R2 Order for use in FHIR R4

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Order.id | UseElementRenamed | Task.id |
| Order.meta | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Order.meta |
| Order.implicitRules | UseElementRenamed | Task.implicitRules |
| Order.language | UseElementRenamed | Task.language |
| Order.text | UseElementRenamed | Task.text |
| Order.contained | UseElementRenamed | Task.contained |
| Order.extension | UseElementRenamed | Task.extension |
| Order.modifierExtension | UseElementRenamed | Task.modifierExtension |
| Order.identifier | UseElementRenamed | Task.identifier |
| Order.date | UseElementRenamed | Task.authoredOn |
| Order.subject | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Order.subject |
| Order.source | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Order.source |
| Order.target | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Order.target |
| Order.reason[x] | UseElementRenamed | Task.reasonCode |
| Order.when | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Order.when |
| Order.when.id | UseExtensionFromAncestor | - |
| Order.when.extension | UseExtensionFromAncestor | - |
| Order.when.modifierExtension | UseExtensionFromAncestor | - |
| Order.when.code | UseExtensionFromAncestor | - |
| Order.when.schedule | UseExtensionFromAncestor | - |
| Order.detail | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Order.detail |
