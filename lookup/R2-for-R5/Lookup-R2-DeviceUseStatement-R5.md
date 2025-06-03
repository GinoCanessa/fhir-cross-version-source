### Lookup for FHIR R2 DeviceUseStatement for use in FHIR R5

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| DeviceUseStatement.id | UseElementRenamed | DeviceUsage.id |
| DeviceUseStatement.meta | UseElementRenamed | DeviceUsage.meta |
| DeviceUseStatement.implicitRules | UseElementRenamed | DeviceUsage.implicitRules |
| DeviceUseStatement.language | UseElementRenamed | DeviceUsage.language |
| DeviceUseStatement.text | UseElementRenamed | DeviceUsage.text |
| DeviceUseStatement.contained | UseElementRenamed | DeviceUsage.contained |
| DeviceUseStatement.extension | UseElementRenamed | DeviceUsage.extension |
| DeviceUseStatement.modifierExtension | UseElementRenamed | DeviceUsage.modifierExtension |
| DeviceUseStatement.bodySite[x] | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DeviceUseStatement.bodySite |
| DeviceUseStatement.whenUsed | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DeviceUseStatement.whenUsed |
| DeviceUseStatement.device | UseElementRenamed | DeviceUsage.device |
| DeviceUseStatement.identifier | UseElementRenamed | DeviceUsage.identifier |
| DeviceUseStatement.indication | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DeviceUseStatement.indication |
| DeviceUseStatement.notes | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DeviceUseStatement.notes |
| DeviceUseStatement.recordedOn | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DeviceUseStatement.recordedOn |
| DeviceUseStatement.subject | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DeviceUseStatement.subject |
| DeviceUseStatement.timing[x] | UseElementRenamed | DeviceUsage.timing[x] |
