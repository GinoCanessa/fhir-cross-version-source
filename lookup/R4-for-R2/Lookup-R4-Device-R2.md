### Lookup for FHIR R4 Device for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Device.id | UseElementSameName | Device.id |
| Device.meta | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Device.meta |
| Device.implicitRules | UseElementSameName | Device.implicitRules |
| Device.language | UseElementSameName | Device.language |
| Device.text | UseElementSameName | Device.text |
| Device.contained | UseElementSameName | Device.contained |
| Device.extension | UseElementSameName | Device.extension |
| Device.modifierExtension | UseElementSameName | Device.modifierExtension |
| Device.identifier | UseElementSameName | Device.identifier |
| Device.definition | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Device.definition |
| Device.udiCarrier | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Device.udiCarrier |
| Device.udiCarrier.id | UseExtensionFromAncestor | - |
| Device.udiCarrier.extension | UseExtensionFromAncestor | - |
| Device.udiCarrier.modifierExtension | UseExtensionFromAncestor | - |
| Device.udiCarrier.deviceIdentifier | UseExtensionFromAncestor | - |
| Device.udiCarrier.issuer | UseExtensionFromAncestor | - |
| Device.udiCarrier.jurisdiction | UseExtensionFromAncestor | - |
| Device.udiCarrier.carrierAIDC | UseExtensionFromAncestor | - |
| Device.udiCarrier.carrierHRF | UseExtensionFromAncestor | - |
| Device.udiCarrier.entryType | UseExtensionFromAncestor | - |
| Device.status | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Device.status |
| Device.statusReason | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Device.statusReason |
| Device.distinctIdentifier | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Device.distinctIdentifier |
| Device.manufacturer | UseElementSameName | Device.manufacturer |
| Device.manufactureDate | UseElementSameName | Device.manufactureDate |
| Device.expirationDate | UseElementRenamed | Device.expiry |
| Device.lotNumber | UseElementSameName | Device.lotNumber |
| Device.serialNumber | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Device.serialNumber |
| Device.deviceName | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Device.deviceName |
| Device.deviceName.id | UseExtensionFromAncestor | - |
| Device.deviceName.extension | UseExtensionFromAncestor | - |
| Device.deviceName.modifierExtension | UseExtensionFromAncestor | - |
| Device.deviceName.name | UseExtensionFromAncestor | - |
| Device.deviceName.type | UseExtensionFromAncestor | - |
| Device.modelNumber | UseElementRenamed | Device.model |
| Device.partNumber | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Device.partNumber |
| Device.type | UseElementSameName | Device.type |
| Device.specialization | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Device.specialization |
| Device.specialization.id | UseExtensionFromAncestor | - |
| Device.specialization.extension | UseExtensionFromAncestor | - |
| Device.specialization.modifierExtension | UseExtensionFromAncestor | - |
| Device.specialization.systemType | UseExtensionFromAncestor | - |
| Device.specialization.version | UseExtensionFromAncestor | - |
| Device.version | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Device.version |
| Device.version.id | UseExtensionFromAncestor | - |
| Device.version.extension | UseExtensionFromAncestor | - |
| Device.version.modifierExtension | UseExtensionFromAncestor | - |
| Device.version.type | UseExtensionFromAncestor | - |
| Device.version.component | UseExtensionFromAncestor | - |
| Device.version.value | UseExtensionFromAncestor | - |
| Device.property | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Device.property |
| Device.property.id | UseExtensionFromAncestor | - |
| Device.property.extension | UseExtensionFromAncestor | - |
| Device.property.modifierExtension | UseExtensionFromAncestor | - |
| Device.property.type | UseExtensionFromAncestor | - |
| Device.property.valueQuantity | UseExtensionFromAncestor | - |
| Device.property.valueCode | UseExtensionFromAncestor | - |
| Device.patient | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Device.patient |
| Device.owner | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Device.owner |
| Device.contact | UseElementSameName | Device.contact |
| Device.location | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Device.location |
| Device.url | UseElementSameName | Device.url |
| Device.note | UseElementSameName | Device.note |
| Device.safety | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Device.safety |
| Device.parent | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Device.parent |
