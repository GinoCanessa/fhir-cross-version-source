### Lookup for FHIR R2 DeviceUseStatement for use in FHIR R4

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| DeviceUseStatement.id | UseElementSameName | DeviceUseStatement.id |
| DeviceUseStatement.meta | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DeviceUseStatement.meta |
| DeviceUseStatement.implicitRules | UseElementSameName | DeviceUseStatement.implicitRules |
| DeviceUseStatement.language | UseElementSameName | DeviceUseStatement.language |
| DeviceUseStatement.text | UseElementSameName | DeviceUseStatement.text |
| DeviceUseStatement.contained | UseElementSameName | DeviceUseStatement.contained |
| DeviceUseStatement.extension | UseElementSameName | DeviceUseStatement.extension |
| DeviceUseStatement.modifierExtension | UseElementSameName | DeviceUseStatement.modifierExtension |
| DeviceUseStatement.bodySite[x] | UseElementRenamed | DeviceUseStatement.bodySite |
| DeviceUseStatement.whenUsed | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DeviceUseStatement.whenUsed |
| DeviceUseStatement.device | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DeviceUseStatement.device |
| DeviceUseStatement.identifier | UseElementSameName | DeviceUseStatement.identifier |
| DeviceUseStatement.indication | UseElementRenamed | DeviceUseStatement.reasonCode |
| DeviceUseStatement.notes | UseElementRenamed | DeviceUseStatement.note |
| DeviceUseStatement.recordedOn | UseElementSameName | DeviceUseStatement.recordedOn |
| DeviceUseStatement.subject | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DeviceUseStatement.subject |
| DeviceUseStatement.timing[x] | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DeviceUseStatement.timing |
