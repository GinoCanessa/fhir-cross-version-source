### Lookup for FHIR R5 SupplyDelivery for use in FHIR R4B

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| SupplyDelivery.id | UseElementRenamed | SupplyDelivery.id |
| SupplyDelivery.meta | UseElementRenamed | SupplyDelivery.meta |
| SupplyDelivery.implicitRules | UseElementRenamed | SupplyDelivery.implicitRules |
| SupplyDelivery.language | UseElementRenamed | SupplyDelivery.language |
| SupplyDelivery.text | UseElementRenamed | SupplyDelivery.text |
| SupplyDelivery.contained | UseElementRenamed | SupplyDelivery.contained |
| SupplyDelivery.extension | UseElementRenamed | SupplyDelivery.extension |
| SupplyDelivery.modifierExtension | UseElementRenamed | SupplyDelivery.modifierExtension |
| SupplyDelivery.identifier | UseElementRenamed | SupplyDelivery.identifier |
| SupplyDelivery.basedOn | UseElementRenamed | SupplyDelivery.basedOn |
| SupplyDelivery.partOf | UseElementRenamed | SupplyDelivery.partOf |
| SupplyDelivery.status | UseElementRenamed | SupplyDelivery.status |
| SupplyDelivery.patient | UseElementRenamed | SupplyDelivery.patient |
| SupplyDelivery.type | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-SupplyDelivery.type |
| SupplyDelivery.suppliedItem | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-SupplyDelivery.suppliedItem |
| SupplyDelivery.suppliedItem.id | UseExtensionFromAncestor | - |
| SupplyDelivery.suppliedItem.extension | UseExtensionFromAncestor | - |
| SupplyDelivery.suppliedItem.modifierExtension | UseExtensionFromAncestor | - |
| SupplyDelivery.suppliedItem.quantity | UseExtensionFromAncestor | - |
| SupplyDelivery.suppliedItem.item[x] | UseExtensionFromAncestor | - |
| SupplyDelivery.occurrence[x] | UseElementRenamed | SupplyDelivery.occurrence[x] |
| SupplyDelivery.supplier | UseElementRenamed | SupplyDelivery.supplier |
| SupplyDelivery.destination | UseElementRenamed | SupplyDelivery.destination |
| SupplyDelivery.receiver | UseElementRenamed | SupplyDelivery.receiver |
