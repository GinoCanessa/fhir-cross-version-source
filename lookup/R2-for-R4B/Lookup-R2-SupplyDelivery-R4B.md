### Lookup for FHIR R2 SupplyDelivery for use in FHIR R4B

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
| SupplyDelivery.status | UseElementSameName | SupplyDelivery.status |
| SupplyDelivery.patient | UseElementSameName | SupplyDelivery.patient |
| SupplyDelivery.type | UseElementSameName | SupplyDelivery.type |
| SupplyDelivery.quantity | UseElementRenamed | SupplyDelivery.suppliedItem.quantity |
| SupplyDelivery.suppliedItem | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-SupplyDelivery.suppliedItem |
| SupplyDelivery.supplier | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-SupplyDelivery.supplier |
| SupplyDelivery.whenPrepared | UseElementRenamed | SupplyDelivery.occurrence[x] |
| SupplyDelivery.time | UseElementRenamed | SupplyDelivery.occurrence[x] |
| SupplyDelivery.destination | UseElementSameName | SupplyDelivery.destination |
| SupplyDelivery.receiver | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-SupplyDelivery.receiver |
