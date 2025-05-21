### Lookup for FHIR R3 SupplyRequest for use in FHIR R5

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| SupplyRequest.id | UseElementSameName | SupplyRequest.id |
| SupplyRequest.meta | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyRequest.meta |
| SupplyRequest.implicitRules | UseElementSameName | SupplyRequest.implicitRules |
| SupplyRequest.language | UseElementSameName | SupplyRequest.language |
| SupplyRequest.text | UseElementSameName | SupplyRequest.text |
| SupplyRequest.contained | UseElementSameName | SupplyRequest.contained |
| SupplyRequest.extension | UseElementSameName | SupplyRequest.extension |
| SupplyRequest.modifierExtension | UseElementSameName | SupplyRequest.modifierExtension |
| SupplyRequest.identifier | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyRequest.identifier |
| SupplyRequest.status | UseElementSameName | SupplyRequest.status |
| SupplyRequest.category | UseElementSameName | SupplyRequest.category |
| SupplyRequest.priority | UseElementSameName | SupplyRequest.priority |
| SupplyRequest.orderedItem | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyRequest.orderedItem |
| SupplyRequest.orderedItem.id | UseExtensionFromAncestor | - |
| SupplyRequest.orderedItem.extension | UseExtensionFromAncestor | - |
| SupplyRequest.orderedItem.modifierExtension | UseExtensionFromAncestor | - |
| SupplyRequest.orderedItem.quantity | UseExtensionFromAncestor | - |
| SupplyRequest.orderedItem.item[x] | UseExtensionFromAncestor | - |
| SupplyRequest.occurrence[x] | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyRequest.occurrence |
| SupplyRequest.authoredOn | UseElementSameName | SupplyRequest.authoredOn |
| SupplyRequest.requester | UseElementSameName | SupplyRequest.requester |
| SupplyRequest.requester.id | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyRequest.requester.id |
| SupplyRequest.requester.extension | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyRequest.requester.extension |
| SupplyRequest.requester.modifierExtension | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyRequest.requester.modifierExtension |
| SupplyRequest.requester.agent | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyRequest.requester.agent |
| SupplyRequest.requester.onBehalfOf | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyRequest.requester.onBehalfOf |
| SupplyRequest.supplier | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyRequest.supplier |
| SupplyRequest.reason[x] | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyRequest.reason |
| SupplyRequest.deliverFrom | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyRequest.deliverFrom |
| SupplyRequest.deliverTo | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyRequest.deliverTo |
