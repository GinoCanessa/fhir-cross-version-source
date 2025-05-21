### Lookup for FHIR R2 SupplyDelivery for use in FHIR R3

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| SupplyDelivery.id | UseElementSameName | SupplyDelivery.id |
| SupplyDelivery.meta | UseElementSameName | SupplyDelivery.meta |
| SupplyDelivery.implicitRules | UseElementSameName | SupplyDelivery.implicitRules |
| SupplyDelivery.language | UseElementSameName | SupplyDelivery.language |
| SupplyDelivery.text | UseElementSameName | SupplyDelivery.text |
| SupplyDelivery.contained | UseElementSameName | SupplyDelivery.contained |
| SupplyDelivery.extension | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-SupplyDelivery.extension |
| SupplyDelivery.modifierExtension | UseElementSameName | SupplyDelivery.modifierExtension |
| SupplyDelivery.identifier | UseElementSameName | SupplyDelivery.identifier |
| SupplyDelivery.status | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-SupplyDelivery.status |
| SupplyDelivery.patient | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-SupplyDelivery.patient |
| SupplyDelivery.type | UseElementSameName | SupplyDelivery.type |
| SupplyDelivery.quantity | UseElementRenamed | SupplyDelivery.suppliedItem.quantity |
| SupplyDelivery.suppliedItem | UseElementSameName | SupplyDelivery.suppliedItem |
| SupplyDelivery.supplier | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-SupplyDelivery.supplier |
| SupplyDelivery.whenPrepared | UseElementRenamed | SupplyDelivery.extension |
| SupplyDelivery.time | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-SupplyDelivery.time |
| SupplyDelivery.destination | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-SupplyDelivery.destination |
| SupplyDelivery.receiver | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-SupplyDelivery.receiver |
