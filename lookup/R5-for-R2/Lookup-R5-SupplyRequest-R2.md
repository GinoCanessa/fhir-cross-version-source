### Lookup for FHIR R5 SupplyRequest for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| SupplyRequest.id | UseElementSameName | SupplyRequest.id |
| SupplyRequest.meta | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-SupplyRequest.meta |
| SupplyRequest.implicitRules | UseElementSameName | SupplyRequest.implicitRules |
| SupplyRequest.language | UseElementSameName | SupplyRequest.language |
| SupplyRequest.text | UseElementSameName | SupplyRequest.text |
| SupplyRequest.contained | UseElementSameName | SupplyRequest.contained |
| SupplyRequest.extension | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-SupplyRequest.extension |
| SupplyRequest.modifierExtension | UseElementSameName | SupplyRequest.modifierExtension |
| SupplyRequest.identifier | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-SupplyRequest.identifier |
| SupplyRequest.status | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-SupplyRequest.status |
| SupplyRequest.basedOn | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-SupplyRequest.basedOn |
| SupplyRequest.category | UseElementRenamed | SupplyRequest.kind |
| SupplyRequest.priority | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-SupplyRequest.priority |
| SupplyRequest.deliverFor | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-SupplyRequest.deliverFor |
| SupplyRequest.item | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-SupplyRequest.item |
| SupplyRequest.quantity | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-SupplyRequest.quantity |
| SupplyRequest.parameter | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-SupplyRequest.parameter |
| SupplyRequest.parameter.id | UseExtensionFromAncestor | - |
| SupplyRequest.parameter.extension | UseExtensionFromAncestor | - |
| SupplyRequest.parameter.modifierExtension | UseExtensionFromAncestor | - |
| SupplyRequest.parameter.code | UseExtensionFromAncestor | - |
| SupplyRequest.parameter.value[x] | UseExtensionFromAncestor | - |
| SupplyRequest.occurrence[x] | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-SupplyRequest.occurrence |
| SupplyRequest.authoredOn | UseElementRenamed | SupplyRequest.date |
| SupplyRequest.requester | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-SupplyRequest.requester |
| SupplyRequest.supplier | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-SupplyRequest.supplier |
| SupplyRequest.reason | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-SupplyRequest.reason |
| SupplyRequest.deliverFrom | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-SupplyRequest.deliverFrom |
| SupplyRequest.deliverTo | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-SupplyRequest.deliverTo |
