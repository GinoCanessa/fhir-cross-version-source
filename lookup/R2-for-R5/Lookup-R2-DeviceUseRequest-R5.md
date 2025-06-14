### Lookup for FHIR R2 DeviceUseRequest for use in FHIR R5

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| DeviceUseRequest.id | UseElementRenamed | DeviceRequest.id |
| DeviceUseRequest.meta | UseElementRenamed | DeviceRequest.meta |
| DeviceUseRequest.implicitRules | UseElementRenamed | DeviceRequest.implicitRules |
| DeviceUseRequest.language | UseElementRenamed | DeviceRequest.language |
| DeviceUseRequest.text | UseElementRenamed | DeviceRequest.text |
| DeviceUseRequest.contained | UseElementRenamed | DeviceRequest.contained |
| DeviceUseRequest.extension | UseElementRenamed | DeviceRequest.extension |
| DeviceUseRequest.modifierExtension | UseElementRenamed | DeviceRequest.modifierExtension |
| DeviceUseRequest.bodySite[x] | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DeviceUseRequest.bodySite |
| DeviceUseRequest.status | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DeviceUseRequest.status |
| DeviceUseRequest.device | UseElementRenamed | DeviceRequest.code |
| DeviceUseRequest.encounter | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DeviceUseRequest.encounter |
| DeviceUseRequest.identifier | UseElementRenamed | DeviceRequest.identifier |
| DeviceUseRequest.indication | UseElementRenamed | DeviceRequest.reason |
| DeviceUseRequest.notes | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DeviceUseRequest.notes |
| DeviceUseRequest.prnReason | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DeviceUseRequest.prnReason |
| DeviceUseRequest.orderedOn | UseElementRenamed | DeviceRequest.occurrence[x] |
| DeviceUseRequest.recordedOn | UseElementRenamed | DeviceRequest.authoredOn |
| DeviceUseRequest.subject | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DeviceUseRequest.subject |
| DeviceUseRequest.timing[x] | UseElementRenamed | DeviceRequest.occurrence[x] |
| DeviceUseRequest.priority | UseElementRenamed | DeviceRequest.priority |
