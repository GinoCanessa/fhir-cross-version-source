### Lookup for FHIR R5 DeviceMetric for use in FHIR R4B

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| DeviceMetric.id | UseElementSameName | DeviceMetric.id |
| DeviceMetric.meta | UseElementSameName | DeviceMetric.meta |
| DeviceMetric.implicitRules | UseElementSameName | DeviceMetric.implicitRules |
| DeviceMetric.language | UseElementSameName | DeviceMetric.language |
| DeviceMetric.text | UseElementSameName | DeviceMetric.text |
| DeviceMetric.contained | UseElementSameName | DeviceMetric.contained |
| DeviceMetric.extension | UseElementSameName | DeviceMetric.extension |
| DeviceMetric.modifierExtension | UseElementSameName | DeviceMetric.modifierExtension |
| DeviceMetric.identifier | UseElementSameName | DeviceMetric.identifier |
| DeviceMetric.type | UseElementSameName | DeviceMetric.type |
| DeviceMetric.unit | UseElementSameName | DeviceMetric.unit |
| DeviceMetric.device | UseElementRenamed | DeviceMetric.parent |
| DeviceMetric.operationalStatus | UseElementSameName | DeviceMetric.operationalStatus |
| DeviceMetric.color | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-DeviceMetric.color |
| DeviceMetric.category | UseElementSameName | DeviceMetric.category |
| DeviceMetric.measurementFrequency | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-DeviceMetric.measurementFrequency |
| DeviceMetric.calibration | UseElementSameName | DeviceMetric.calibration |
| DeviceMetric.calibration.id | UseElementSameName | DeviceMetric.calibration.id |
| DeviceMetric.calibration.extension | UseElementSameName | DeviceMetric.calibration.extension |
| DeviceMetric.calibration.modifierExtension | UseElementSameName | DeviceMetric.calibration.modifierExtension |
| DeviceMetric.calibration.type | UseElementSameName | DeviceMetric.calibration.type |
| DeviceMetric.calibration.state | UseElementSameName | DeviceMetric.calibration.state |
| DeviceMetric.calibration.time | UseElementSameName | DeviceMetric.calibration.time |
