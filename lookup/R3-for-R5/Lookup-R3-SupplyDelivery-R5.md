### Lookup for FHIR R3 SupplyDelivery for use in FHIR R5

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
| SupplyDelivery.type | UseElementSameName | SupplyDelivery.type |
| SupplyDelivery.suppliedItem | UseElementSameName | SupplyDelivery.suppliedItem |
| SupplyDelivery.suppliedItem.id | UseElementSameName | SupplyDelivery.suppliedItem.id |
| SupplyDelivery.suppliedItem.extension | UseElementSameName | SupplyDelivery.suppliedItem.extension |
| SupplyDelivery.suppliedItem.modifierExtension | UseElementSameName | SupplyDelivery.suppliedItem.modifierExtension |
| SupplyDelivery.suppliedItem.quantity | UseElementSameName | SupplyDelivery.suppliedItem.quantity |
| SupplyDelivery.suppliedItem.item[x] | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyDelivery.suppliedItem.item |
| SupplyDelivery.occurrence[x] | UseOneOfElements | SupplyDelivery.occurrence[x],SupplyDelivery.occurrence[x] |
| SupplyDelivery.supplier | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyDelivery.supplier |
| SupplyDelivery.destination | UseElementSameName | SupplyDelivery.destination |
| SupplyDelivery.receiver | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyDelivery.receiver |
