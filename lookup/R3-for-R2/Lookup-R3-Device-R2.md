### Lookup for FHIR R3 Device for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Device.id | UseElementSameName | Device.id |
| Device.meta | UseElementSameName | Device.meta |
| Device.implicitRules | UseElementSameName | Device.implicitRules |
| Device.language | UseElementSameName | Device.language |
| Device.text | UseElementSameName | Device.text |
| Device.contained | UseElementSameName | Device.contained |
| Device.extension | UseElementSameName | Device.extension |
| Device.modifierExtension | UseElementSameName | Device.modifierExtension |
| Device.identifier | UseElementSameName | Device.identifier |
| Device.udi | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Device.udi |
| Device.udi.id | UseExtensionFromAncestor | - |
| Device.udi.extension | UseExtensionFromAncestor | - |
| Device.udi.modifierExtension | UseExtensionFromAncestor | - |
| Device.udi.deviceIdentifier | UseExtensionFromAncestor | - |
| Device.udi.name | UseExtensionFromAncestor | - |
| Device.udi.jurisdiction | UseExtensionFromAncestor | - |
| Device.udi.carrierHRF | UseExtensionFromAncestor | - |
| Device.udi.carrierAIDC | UseExtensionFromAncestor | - |
| Device.udi.issuer | UseExtensionFromAncestor | - |
| Device.udi.entryType | UseExtensionFromAncestor | - |
| Device.status | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Device.status |
| Device.type | UseElementSameName | Device.type |
| Device.lotNumber | UseElementSameName | Device.lotNumber |
| Device.manufacturer | UseElementSameName | Device.manufacturer |
| Device.manufactureDate | UseElementSameName | Device.manufactureDate |
| Device.expirationDate | UseElementRenamed | Device.expiry |
| Device.model | UseElementSameName | Device.model |
| Device.version | UseElementSameName | Device.version |
| Device.patient | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Device.patient |
| Device.owner | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Device.owner |
| Device.contact | UseElementSameName | Device.contact |
| Device.location | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Device.location |
| Device.url | UseElementSameName | Device.url |
| Device.note | UseElementSameName | Device.note |
| Device.safety | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Device.safety |
