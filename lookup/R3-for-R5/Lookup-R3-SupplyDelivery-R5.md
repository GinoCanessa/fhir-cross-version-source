### Lookup for FHIR R3 SupplyDelivery for use in FHIR R5

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| SupplyDelivery.id | UseElementSameName | SupplyDelivery.id |
| SupplyDelivery.meta | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyDelivery.meta |
| SupplyDelivery.implicitRules | UseElementSameName | SupplyDelivery.implicitRules |
| SupplyDelivery.language | UseElementSameName | SupplyDelivery.language |
| SupplyDelivery.text | UseElementSameName | SupplyDelivery.text |
| SupplyDelivery.contained | UseElementSameName | SupplyDelivery.contained |
| SupplyDelivery.extension | UseElementSameName | SupplyDelivery.extension |
| SupplyDelivery.modifierExtension | UseElementSameName | SupplyDelivery.modifierExtension |
| SupplyDelivery.identifier | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyDelivery.identifier |
| SupplyDelivery.basedOn | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyDelivery.basedOn |
| SupplyDelivery.partOf | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyDelivery.partOf |
| SupplyDelivery.status | UseElementSameName | SupplyDelivery.status |
| SupplyDelivery.patient | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyDelivery.patient |
| SupplyDelivery.type | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyDelivery.type |
| SupplyDelivery.suppliedItem | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyDelivery.suppliedItem |
| SupplyDelivery.suppliedItem.id | UseExtensionFromAncestor | - |
| SupplyDelivery.suppliedItem.extension | UseExtensionFromAncestor | - |
| SupplyDelivery.suppliedItem.modifierExtension | UseExtensionFromAncestor | - |
| SupplyDelivery.suppliedItem.quantity | UseExtensionFromAncestor | - |
| SupplyDelivery.suppliedItem.item[x] | UseExtensionFromAncestor | - |
| SupplyDelivery.occurrence[x] | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyDelivery.occurrence |
| SupplyDelivery.supplier | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyDelivery.supplier |
| SupplyDelivery.destination | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyDelivery.destination |
| SupplyDelivery.receiver | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyDelivery.receiver |
