### Lookup for FHIR R3 DeviceRequest for use in FHIR R4

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
| DeviceRequest.priorRequest | UseElementSameName | DeviceRequest.priorRequest |
| DeviceRequest.groupIdentifier | UseElementSameName | DeviceRequest.groupIdentifier |
| DeviceRequest.status | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.status |
| DeviceRequest.intent | UseElementSameName | DeviceRequest.intent |
| DeviceRequest.priority | UseElementSameName | DeviceRequest.priority |
| DeviceRequest.code[x] | UseElementSameName | DeviceRequest.code[x] |
| DeviceRequest.subject | UseElementSameName | DeviceRequest.subject |
| DeviceRequest.context | UseElementRenamed | DeviceRequest.encounter |
| DeviceRequest.occurrence[x] | UseOneOfElements | DeviceRequest.occurrence[x],DeviceRequest.occurrence[x] |
| DeviceRequest.authoredOn | UseElementSameName | DeviceRequest.authoredOn |
| DeviceRequest.requester | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.requester |
| DeviceRequest.requester.id | UseExtensionFromAncestor | - |
| DeviceRequest.requester.extension | UseExtensionFromAncestor | - |
| DeviceRequest.requester.modifierExtension | UseExtensionFromAncestor | - |
| DeviceRequest.requester.agent | UseExtensionFromAncestor | - |
| DeviceRequest.requester.onBehalfOf | UseExtensionFromAncestor | - |
| DeviceRequest.performerType | UseElementSameName | DeviceRequest.performerType |
| DeviceRequest.performer | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.performer |
| DeviceRequest.reasonCode | UseElementSameName | DeviceRequest.reasonCode |
| DeviceRequest.reasonReference | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.reasonReference |
| DeviceRequest.supportingInfo | UseElementSameName | DeviceRequest.supportingInfo |
| DeviceRequest.note | UseElementSameName | DeviceRequest.note |
| DeviceRequest.relevantHistory | UseElementSameName | DeviceRequest.relevantHistory |
