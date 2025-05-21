### Lookup for FHIR R3 SupplyDelivery for use in FHIR R2

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
| SupplyDelivery.basedOn | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyDelivery.basedOn |
| SupplyDelivery.partOf | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyDelivery.partOf |
| SupplyDelivery.status | UseElementSameName | SupplyDelivery.status |
| SupplyDelivery.patient | UseElementSameName | SupplyDelivery.patient |
| SupplyDelivery.type | UseElementSameName | SupplyDelivery.type |
| SupplyDelivery.suppliedItem | UseElementSameName | SupplyDelivery.suppliedItem |
| SupplyDelivery.suppliedItem.id | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyDelivery.suppliedItem.id |
| SupplyDelivery.suppliedItem.extension | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyDelivery.suppliedItem.extension |
| SupplyDelivery.suppliedItem.modifierExtension | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyDelivery.suppliedItem.modifierExtension |
| SupplyDelivery.suppliedItem.quantity | UseElementSameName | SupplyDelivery.quantity |
| SupplyDelivery.suppliedItem.item[x] | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyDelivery.suppliedItem.item |
| SupplyDelivery.occurrence[x] | UseElementSameName | SupplyDelivery.whenPrepared |
| SupplyDelivery.supplier | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-SupplyDelivery.supplier |
| SupplyDelivery.destination | UseElementSameName | SupplyDelivery.destination |
| SupplyDelivery.receiver | UseElementSameName | SupplyDelivery.receiver |
