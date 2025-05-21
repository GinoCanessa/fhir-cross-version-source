### Lookup for FHIR R3 SupplyRequest for use in FHIR R2

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
| SupplyRequest.status | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyRequest.status |
| SupplyRequest.category | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyRequest.category |
| SupplyRequest.priority | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyRequest.priority |
| SupplyRequest.orderedItem | UseElementRenamed | SupplyRequest.orderedItem |
| SupplyRequest.orderedItem.id | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyRequest.orderedItem.id |
| SupplyRequest.orderedItem.extension | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyRequest.orderedItem.extension |
| SupplyRequest.orderedItem.modifierExtension | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyRequest.orderedItem.modifierExtension |
| SupplyRequest.orderedItem.quantity | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyRequest.orderedItem.quantity |
| SupplyRequest.orderedItem.item[x] | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyRequest.orderedItem.item |
| SupplyRequest.occurrence[x] | UseElementSameName | SupplyRequest.when.schedule |
| SupplyRequest.authoredOn | UseElementSameName | SupplyRequest.date |
| SupplyRequest.requester | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyRequest.requester |
| SupplyRequest.requester.id | UseExtensionFromAncestor | - |
| SupplyRequest.requester.extension | UseExtensionFromAncestor | - |
| SupplyRequest.requester.modifierExtension | UseExtensionFromAncestor | - |
| SupplyRequest.requester.agent | UseExtensionFromAncestor | - |
| SupplyRequest.requester.onBehalfOf | UseExtensionFromAncestor | - |
| SupplyRequest.supplier | UseElementSameName | SupplyRequest.supplier |
| SupplyRequest.reason[x] | UseElementRenamed | SupplyRequest.reason[x] |
| SupplyRequest.deliverFrom | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyRequest.deliverFrom |
| SupplyRequest.deliverTo | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyRequest.deliverTo |
