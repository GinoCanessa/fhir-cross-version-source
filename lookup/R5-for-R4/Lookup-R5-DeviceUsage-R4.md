### Lookup for FHIR R5 DeviceUsage for use in FHIR R4

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| DeviceUsage.id | UseElementRenamed | DeviceUseStatement.id |
| DeviceUsage.meta | UseElementRenamed | DeviceUseStatement.meta |
| DeviceUsage.implicitRules | UseElementRenamed | DeviceUseStatement.implicitRules |
| DeviceUsage.language | UseElementRenamed | DeviceUseStatement.language |
| DeviceUsage.text | UseElementRenamed | DeviceUseStatement.text |
| DeviceUsage.contained | UseElementRenamed | DeviceUseStatement.contained |
| DeviceUsage.extension | UseElementRenamed | DeviceUseStatement.extension |
| DeviceUsage.modifierExtension | UseElementRenamed | DeviceUseStatement.modifierExtension |
| DeviceUsage.identifier | UseElementRenamed | DeviceUseStatement.identifier |
| DeviceUsage.basedOn | UseElementRenamed | DeviceUseStatement.basedOn |
| DeviceUsage.status | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-DeviceUsage.status |
| DeviceUsage.category | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-DeviceUsage.category |
| DeviceUsage.patient | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-DeviceUsage.patient |
| DeviceUsage.derivedFrom | UseElementRenamed | DeviceUseStatement.derivedFrom |
| DeviceUsage.context | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-DeviceUsage.context |
| DeviceUsage.timing[x] | UseElementRenamed | DeviceUseStatement.timing[x] |
| DeviceUsage.dateAsserted | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-DeviceUsage.dateAsserted |
| DeviceUsage.usageStatus | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-DeviceUsage.usageStatus |
| DeviceUsage.usageReason | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-DeviceUsage.usageReason |
| DeviceUsage.adherence | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-DeviceUsage.adherence |
| DeviceUsage.adherence.id | UseExtensionFromAncestor | - |
| DeviceUsage.adherence.extension | UseExtensionFromAncestor | - |
| DeviceUsage.adherence.modifierExtension | UseExtensionFromAncestor | - |
| DeviceUsage.adherence.code | UseExtensionFromAncestor | - |
| DeviceUsage.adherence.reason | UseExtensionFromAncestor | - |
| DeviceUsage.informationSource | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-DeviceUsage.informationSource |
| DeviceUsage.device | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-DeviceUsage.device |
| DeviceUsage.reason | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-DeviceUsage.reason |
| DeviceUsage.bodySite | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-DeviceUsage.bodySite |
| DeviceUsage.note | UseElementRenamed | DeviceUseStatement.note |
