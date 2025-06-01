### Lookup for FHIR R3 DeviceRequest for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| DeviceRequest.id | UseElementRenamed | DeviceUseRequest.id |
| DeviceRequest.meta | UseElementRenamed | DeviceUseRequest.meta |
| DeviceRequest.implicitRules | UseElementRenamed | DeviceUseRequest.implicitRules |
| DeviceRequest.language | UseElementRenamed | DeviceUseRequest.language |
| DeviceRequest.text | UseElementRenamed | DeviceUseRequest.text |
| DeviceRequest.contained | UseElementRenamed | DeviceUseRequest.contained |
| DeviceRequest.extension | UseElementRenamed | DeviceUseRequest.extension |
| DeviceRequest.modifierExtension | UseElementRenamed | DeviceUseRequest.modifierExtension |
| DeviceRequest.identifier | UseElementRenamed | DeviceUseRequest.identifier |
| DeviceRequest.definition | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.definition |
| DeviceRequest.basedOn | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.basedOn |
| DeviceRequest.priorRequest | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.priorRequest |
| DeviceRequest.groupIdentifier | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.groupIdentifier |
| DeviceRequest.status | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.status |
| DeviceRequest.intent | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.intent |
| DeviceRequest.priority | UseElementRenamed | DeviceUseRequest.priority |
| DeviceRequest.code[x] | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.code |
| DeviceRequest.subject | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.subject |
| DeviceRequest.context | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.context |
| DeviceRequest.occurrence[x] | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.occurrence |
| DeviceRequest.authoredOn | UseElementRenamed | DeviceUseRequest.recordedOn |
| DeviceRequest.requester | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.requester |
| DeviceRequest.requester.id | UseExtensionFromAncestor | - |
| DeviceRequest.requester.extension | UseExtensionFromAncestor | - |
| DeviceRequest.requester.modifierExtension | UseExtensionFromAncestor | - |
| DeviceRequest.requester.agent | UseExtensionFromAncestor | - |
| DeviceRequest.requester.onBehalfOf | UseExtensionFromAncestor | - |
| DeviceRequest.performerType | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.performerType |
| DeviceRequest.performer | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.performer |
| DeviceRequest.reasonCode | UseElementRenamed | DeviceUseRequest.indication |
| DeviceRequest.reasonReference | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.reasonReference |
| DeviceRequest.supportingInfo | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.supportingInfo |
| DeviceRequest.note | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.note |
| DeviceRequest.relevantHistory | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DeviceRequest.relevantHistory |
