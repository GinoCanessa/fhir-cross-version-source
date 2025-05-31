### Lookup for FHIR R3 SupplyRequest for use in FHIR R4B

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
| SupplyRequest.category | UseElementSameName | SupplyRequest.category |
| SupplyRequest.priority | UseElementSameName | SupplyRequest.priority |
| SupplyRequest.orderedItem | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyRequest.orderedItem |
| SupplyRequest.orderedItem.id | UseExtensionFromAncestor | - |
| SupplyRequest.orderedItem.extension | UseExtensionFromAncestor | - |
| SupplyRequest.orderedItem.modifierExtension | UseExtensionFromAncestor | - |
| SupplyRequest.orderedItem.quantity | UseExtensionFromAncestor | - |
| SupplyRequest.orderedItem.item[x] | UseExtensionFromAncestor | - |
| SupplyRequest.occurrence[x] | UseElementSameName | SupplyRequest.occurrence[x] |
| SupplyRequest.authoredOn | UseElementSameName | SupplyRequest.authoredOn |
| SupplyRequest.requester | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyRequest.requester |
| SupplyRequest.requester.id | UseExtensionFromAncestor | - |
| SupplyRequest.requester.extension | UseExtensionFromAncestor | - |
| SupplyRequest.requester.modifierExtension | UseExtensionFromAncestor | - |
| SupplyRequest.requester.agent | UseExtensionFromAncestor | - |
| SupplyRequest.requester.onBehalfOf | UseExtensionFromAncestor | - |
| SupplyRequest.supplier | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyRequest.supplier |
| SupplyRequest.reason[x] | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyRequest.reason |
| SupplyRequest.deliverFrom | UseElementSameName | SupplyRequest.deliverFrom |
| SupplyRequest.deliverTo | UseElementSameName | SupplyRequest.deliverTo |
