### Lookup for FHIR R5 SupplyRequest for use in FHIR R3

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| SupplyRequest.id | UseElementSameName | SupplyRequest.id |
| SupplyRequest.meta | UseElementSameName | SupplyRequest.meta |
| SupplyRequest.implicitRules | UseElementSameName | SupplyRequest.implicitRules |
| SupplyRequest.language | UseElementSameName | SupplyRequest.language |
| SupplyRequest.text | UseElementSameName | SupplyRequest.text |
| SupplyRequest.contained | UseElementSameName | SupplyRequest.contained |
| SupplyRequest.extension | UseElementSameName | SupplyRequest.extension |
| SupplyRequest.modifierExtension | UseElementSameName | SupplyRequest.modifierExtension |
| SupplyRequest.identifier | UseElementSameName | SupplyRequest.identifier |
| SupplyRequest.status | UseElementSameName | SupplyRequest.status |
| SupplyRequest.basedOn | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-SupplyRequest.basedOn |
| SupplyRequest.category | UseElementSameName | SupplyRequest.category |
| SupplyRequest.priority | UseElementSameName | SupplyRequest.priority |
| SupplyRequest.deliverFor | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-SupplyRequest.deliverFor |
| SupplyRequest.item | UseElementRenamed | SupplyRequest.orderedItem.item[x] |
| SupplyRequest.quantity | UseElementSameName | SupplyRequest.orderedItem.quantity |
| SupplyRequest.parameter | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-SupplyRequest.parameter |
| SupplyRequest.parameter.id | UseExtensionFromAncestor | - |
| SupplyRequest.parameter.extension | UseExtensionFromAncestor | - |
| SupplyRequest.parameter.modifierExtension | UseExtensionFromAncestor | - |
| SupplyRequest.parameter.code | UseExtensionFromAncestor | - |
| SupplyRequest.parameter.value[x] | UseExtensionFromAncestor | - |
| SupplyRequest.occurrence[x] | UseElementSameName | SupplyRequest.occurrence[x] |
| SupplyRequest.authoredOn | UseElementSameName | SupplyRequest.authoredOn |
| SupplyRequest.requester | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-SupplyRequest.requester |
| SupplyRequest.supplier | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-SupplyRequest.supplier |
| SupplyRequest.reason | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-SupplyRequest.reason |
| SupplyRequest.deliverFrom | UseElementSameName | SupplyRequest.deliverFrom |
| SupplyRequest.deliverTo | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-SupplyRequest.deliverTo |
