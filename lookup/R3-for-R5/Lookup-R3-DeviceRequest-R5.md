### Lookup for FHIR R3 DeviceRequest for use in FHIR R5

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| DeviceRequest.id | UseElementSameName | DeviceRequest.id |
| DeviceRequest.meta | UseElementSameName | DeviceRequest.meta |
| DeviceRequest.implicitRules | UseElementSameName | DeviceRequest.implicitRules |
| DeviceRequest.language | UseElementSameName | DeviceRequest.language |
| DeviceRequest.text | UseElementSameName | DeviceRequest.text |
| DeviceRequest.contained | UseElementSameName | DeviceRequest.contained |
| DeviceRequest.extension | UseElementSameName | DeviceRequest.extension |
| DeviceRequest.modifierExtension | UseElementSameName | DeviceRequest.modifierExtension |
| DeviceRequest.identifier | UseElementSameName | DeviceRequest.identifier |
| DeviceRequest.definition | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.definition |
| DeviceRequest.basedOn | UseElementSameName | DeviceRequest.basedOn |
| DeviceRequest.priorRequest | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.priorRequest |
| DeviceRequest.groupIdentifier | UseElementSameName | DeviceRequest.groupIdentifier |
| DeviceRequest.status | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.status |
| DeviceRequest.intent | UseElementSameName | DeviceRequest.intent |
| DeviceRequest.priority | UseElementSameName | DeviceRequest.priority |
| DeviceRequest.code[x] | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.code |
| DeviceRequest.subject | UseElementSameName | DeviceRequest.subject |
| DeviceRequest.context | UseElementRenamed | DeviceRequest.encounter |
| DeviceRequest.occurrence[x] | UseElementSameName | DeviceRequest.occurrence[x] |
| DeviceRequest.authoredOn | UseElementSameName | DeviceRequest.authoredOn |
| DeviceRequest.requester | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.requester |
| DeviceRequest.requester.id | UseExtensionFromAncestor | - |
| DeviceRequest.requester.extension | UseExtensionFromAncestor | - |
| DeviceRequest.requester.modifierExtension | UseExtensionFromAncestor | - |
| DeviceRequest.requester.agent | UseExtensionFromAncestor | - |
| DeviceRequest.requester.onBehalfOf | UseExtensionFromAncestor | - |
| DeviceRequest.performerType | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.performerType |
| DeviceRequest.performer | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.performer |
| DeviceRequest.reasonCode | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.reasonCode |
| DeviceRequest.reasonReference | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.reasonReference |
| DeviceRequest.supportingInfo | UseElementSameName | DeviceRequest.supportingInfo |
| DeviceRequest.note | UseElementSameName | DeviceRequest.note |
| DeviceRequest.relevantHistory | UseElementSameName | DeviceRequest.relevantHistory |
