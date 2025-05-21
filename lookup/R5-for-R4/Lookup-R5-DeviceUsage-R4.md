### Lookup for FHIR R5 DeviceUsage for use in FHIR R4

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| DeviceUsage.id | UseElementSameName | DeviceUseStatement.id |
| DeviceUsage.meta | UseElementSameName | DeviceUseStatement.meta |
| DeviceUsage.implicitRules | UseElementSameName | DeviceUseStatement.implicitRules |
| DeviceUsage.language | UseElementSameName | DeviceUseStatement.language |
| DeviceUsage.text | UseElementSameName | DeviceUseStatement.text |
| DeviceUsage.contained | UseElementSameName | DeviceUseStatement.contained |
| DeviceUsage.extension | UseElementSameName | DeviceUseStatement.extension |
| DeviceUsage.modifierExtension | UseElementSameName | DeviceUseStatement.modifierExtension |
| DeviceUsage.identifier | UseElementSameName | DeviceUseStatement.identifier |
| DeviceUsage.basedOn | UseElementSameName | DeviceUseStatement.basedOn |
| DeviceUsage.status | UseElementSameName | DeviceUseStatement.status |
| DeviceUsage.category | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-DeviceUsage.category |
| DeviceUsage.patient | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-DeviceUsage.patient |
| DeviceUsage.derivedFrom | UseElementSameName | DeviceUseStatement.derivedFrom |
| DeviceUsage.context | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-DeviceUsage.context |
| DeviceUsage.timing[x] | UseElementSameName | DeviceUseStatement.timing[x] |
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
| DeviceUsage.device | UseElementSameName | DeviceUseStatement.device |
| DeviceUsage.reason | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-DeviceUsage.reason |
| DeviceUsage.bodySite | UseElementSameName | DeviceUseStatement.bodySite |
| DeviceUsage.note | UseElementSameName | DeviceUseStatement.note |
