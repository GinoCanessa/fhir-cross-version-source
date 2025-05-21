### Lookup for FHIR R4B SupplyDelivery for use in FHIR R5

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| SupplyDelivery.id | UseElementSameName | SupplyDelivery.id |
| SupplyDelivery.meta | UseElementSameName | SupplyDelivery.meta |
| SupplyDelivery.implicitRules | UseElementSameName | SupplyDelivery.implicitRules |
| SupplyDelivery.language | UseElementSameName | SupplyDelivery.language |
| SupplyDelivery.text | UseElementSameName | SupplyDelivery.text |
| SupplyDelivery.contained | UseElementSameName | SupplyDelivery.contained |
| SupplyDelivery.extension | UseElementSameName | SupplyDelivery.extension |
| SupplyDelivery.modifierExtension | UseElementSameName | SupplyDelivery.modifierExtension |
| SupplyDelivery.identifier | UseElementSameName | SupplyDelivery.identifier |
| SupplyDelivery.basedOn | UseElementSameName | SupplyDelivery.basedOn |
| SupplyDelivery.partOf | UseElementSameName | SupplyDelivery.partOf |
| SupplyDelivery.status | UseElementSameName | SupplyDelivery.status |
| SupplyDelivery.patient | UseElementSameName | SupplyDelivery.patient |
| SupplyDelivery.type | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-SupplyDelivery.type |
| SupplyDelivery.suppliedItem | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-SupplyDelivery.suppliedItem |
| SupplyDelivery.suppliedItem.id | UseExtensionFromAncestor | - |
| SupplyDelivery.suppliedItem.extension | UseExtensionFromAncestor | - |
| SupplyDelivery.suppliedItem.modifierExtension | UseExtensionFromAncestor | - |
| SupplyDelivery.suppliedItem.quantity | UseExtensionFromAncestor | - |
| SupplyDelivery.suppliedItem.item[x] | UseExtensionFromAncestor | - |
| SupplyDelivery.occurrence[x] | UseElementSameName | SupplyDelivery.occurrence[x] |
| SupplyDelivery.supplier | UseElementSameName | SupplyDelivery.supplier |
| SupplyDelivery.destination | UseElementSameName | SupplyDelivery.destination |
| SupplyDelivery.receiver | UseElementSameName | SupplyDelivery.receiver |
