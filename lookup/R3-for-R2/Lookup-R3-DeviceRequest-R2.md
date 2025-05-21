### Lookup for FHIR R3 DeviceRequest for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| DeviceRequest.id | UseElementSameName | DeviceUseRequest.id |
| DeviceRequest.meta | UseElementSameName | DeviceUseRequest.meta |
| DeviceRequest.implicitRules | UseElementSameName | DeviceUseRequest.implicitRules |
| DeviceRequest.language | UseElementSameName | DeviceUseRequest.language |
| DeviceRequest.text | UseElementSameName | DeviceUseRequest.text |
| DeviceRequest.contained | UseElementSameName | DeviceUseRequest.contained |
| DeviceRequest.extension | UseElementSameName | DeviceUseRequest.extension |
| DeviceRequest.modifierExtension | UseElementSameName | DeviceUseRequest.modifierExtension |
| DeviceRequest.identifier | UseElementSameName | DeviceUseRequest.identifier |
| DeviceRequest.definition | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.definition |
| DeviceRequest.basedOn | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.basedOn |
| DeviceRequest.priorRequest | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.priorRequest |
| DeviceRequest.groupIdentifier | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.groupIdentifier |
| DeviceRequest.status | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.status |
| DeviceRequest.intent | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.intent |
| DeviceRequest.priority | UseElementSameName | DeviceUseRequest.priority |
| DeviceRequest.code[x] | UseElementSameName | DeviceUseRequest.device |
| DeviceRequest.subject | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.subject |
| DeviceRequest.context | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.context |
| DeviceRequest.occurrence[x] | UseElementSameName | DeviceUseRequest.orderedOn |
| DeviceRequest.authoredOn | UseElementSameName | DeviceUseRequest.recordedOn |
| DeviceRequest.requester | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.requester |
| DeviceRequest.requester.id | UseExtensionFromAncestor | - |
| DeviceRequest.requester.extension | UseExtensionFromAncestor | - |
| DeviceRequest.requester.modifierExtension | UseExtensionFromAncestor | - |
| DeviceRequest.requester.agent | UseExtensionFromAncestor | - |
| DeviceRequest.requester.onBehalfOf | UseExtensionFromAncestor | - |
| DeviceRequest.performerType | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.performerType |
| DeviceRequest.performer | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.performer |
| DeviceRequest.reasonCode | UseElementSameName | DeviceUseRequest.indication |
| DeviceRequest.reasonReference | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.reasonReference |
| DeviceRequest.supportingInfo | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.supportingInfo |
| DeviceRequest.note | UseElementSameName | DeviceUseRequest.notes |
| DeviceRequest.relevantHistory | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.relevantHistory |
