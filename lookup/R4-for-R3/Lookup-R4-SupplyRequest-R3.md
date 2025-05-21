### Lookup for FHIR R4 SupplyRequest for use in FHIR R3

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
| SupplyRequest.item[x] | UseElementSameName | SupplyRequest.orderedItem.item[x] |
| SupplyRequest.quantity | UseElementSameName | SupplyRequest.orderedItem.quantity |
| SupplyRequest.parameter | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-SupplyRequest.parameter |
| SupplyRequest.parameter.id | UseExtensionFromAncestor | - |
| SupplyRequest.parameter.extension | UseExtensionFromAncestor | - |
| SupplyRequest.parameter.modifierExtension | UseExtensionFromAncestor | - |
| SupplyRequest.parameter.code | UseExtensionFromAncestor | - |
| SupplyRequest.parameter.value[x] | UseExtensionFromAncestor | - |
| SupplyRequest.occurrence[x] | UseElementSameName | SupplyRequest.occurrence[x] |
| SupplyRequest.authoredOn | UseElementSameName | SupplyRequest.authoredOn |
| SupplyRequest.requester | UseElementSameName | SupplyRequest.requester |
| SupplyRequest.supplier | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-SupplyRequest.supplier |
| SupplyRequest.reasonCode | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-SupplyRequest.reasonCode |
| SupplyRequest.reasonReference | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-SupplyRequest.reasonReference |
| SupplyRequest.deliverFrom | UseElementSameName | SupplyRequest.deliverFrom |
| SupplyRequest.deliverTo | UseElementSameName | SupplyRequest.deliverTo |
