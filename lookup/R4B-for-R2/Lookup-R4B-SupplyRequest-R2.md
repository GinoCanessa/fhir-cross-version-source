### Lookup for FHIR R4B SupplyRequest for use in FHIR R2

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
| SupplyRequest.status | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-SupplyRequest.status |
| SupplyRequest.category | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-SupplyRequest.category |
| SupplyRequest.priority | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-SupplyRequest.priority |
| SupplyRequest.item[x] | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-SupplyRequest.item |
| SupplyRequest.quantity | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-SupplyRequest.quantity |
| SupplyRequest.parameter | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-SupplyRequest.parameter |
| SupplyRequest.parameter.id | UseExtensionFromAncestor | - |
| SupplyRequest.parameter.extension | UseExtensionFromAncestor | - |
| SupplyRequest.parameter.modifierExtension | UseExtensionFromAncestor | - |
| SupplyRequest.parameter.code | UseExtensionFromAncestor | - |
| SupplyRequest.parameter.value[x] | UseExtensionFromAncestor | - |
| SupplyRequest.occurrence[x] | UseElementSameName | SupplyRequest.when.schedule |
| SupplyRequest.authoredOn | UseElementSameName | SupplyRequest.date |
| SupplyRequest.requester | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-SupplyRequest.requester |
| SupplyRequest.supplier | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-SupplyRequest.supplier |
| SupplyRequest.reasonCode | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-SupplyRequest.reasonCode |
| SupplyRequest.reasonReference | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-SupplyRequest.reasonReference |
| SupplyRequest.deliverFrom | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-SupplyRequest.deliverFrom |
| SupplyRequest.deliverTo | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-SupplyRequest.deliverTo |
