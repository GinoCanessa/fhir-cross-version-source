### Lookup for FHIR R2 Device for use in FHIR R4

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
| Device.type | UseElementSameName | Device.type |
| Device.note | UseElementSameName | Device.note |
| Device.status | UseElementSameName | Device.status |
| Device.manufacturer | UseElementSameName | Device.manufacturer |
| Device.model | UseElementRenamed | Device.modelNumber |
| Device.version | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Device.version |
| Device.manufactureDate | UseElementSameName | Device.manufactureDate |
| Device.expiry | UseElementRenamed | Device.expirationDate |
| Device.udi | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Device.udi |
| Device.lotNumber | UseElementSameName | Device.lotNumber |
| Device.owner | UseElementSameName | Device.owner |
| Device.location | UseElementSameName | Device.location |
| Device.patient | UseElementSameName | Device.patient |
| Device.contact | UseElementSameName | Device.contact |
| Device.url | UseElementSameName | Device.url |
