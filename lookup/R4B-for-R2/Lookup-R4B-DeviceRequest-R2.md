### Lookup for FHIR R4B DeviceRequest for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| DeviceRequest.id | UseElementSameName | DeviceUseRequest.id |
| DeviceRequest.meta | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-DeviceRequest.meta |
| DeviceRequest.implicitRules | UseElementSameName | DeviceUseRequest.implicitRules |
| DeviceRequest.language | UseElementSameName | DeviceUseRequest.language |
| DeviceRequest.text | UseElementSameName | DeviceUseRequest.text |
| DeviceRequest.contained | UseElementSameName | DeviceUseRequest.contained |
| DeviceRequest.extension | UseElementSameName | DeviceUseRequest.extension |
| DeviceRequest.modifierExtension | UseElementSameName | DeviceUseRequest.modifierExtension |
| DeviceRequest.identifier | UseElementSameName | DeviceUseRequest.identifier |
| DeviceRequest.instantiatesCanonical | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-DeviceRequest.instantiatesCanonical |
| DeviceRequest.instantiatesUri | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-DeviceRequest.instantiatesUri |
| DeviceRequest.basedOn | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-DeviceRequest.basedOn |
| DeviceRequest.priorRequest | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-DeviceRequest.priorRequest |
| DeviceRequest.groupIdentifier | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-DeviceRequest.groupIdentifier |
| DeviceRequest.status | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-DeviceRequest.status |
| DeviceRequest.intent | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-DeviceRequest.intent |
| DeviceRequest.priority | UseElementSameName | DeviceUseRequest.priority |
| DeviceRequest.code[x] | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-DeviceRequest.code |
| DeviceRequest.parameter | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-DeviceRequest.parameter |
| DeviceRequest.parameter.id | UseExtensionFromAncestor | - |
| DeviceRequest.parameter.extension | UseExtensionFromAncestor | - |
| DeviceRequest.parameter.modifierExtension | UseExtensionFromAncestor | - |
| DeviceRequest.parameter.code | UseExtensionFromAncestor | - |
| DeviceRequest.parameter.value[x] | UseExtensionFromAncestor | - |
| DeviceRequest.subject | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-DeviceRequest.subject |
| DeviceRequest.encounter | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-DeviceRequest.encounter |
| DeviceRequest.occurrence[x] | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-DeviceRequest.occurrence |
| DeviceRequest.authoredOn | UseElementSameName | DeviceUseRequest.recordedOn |
| DeviceRequest.requester | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-DeviceRequest.requester |
| DeviceRequest.performerType | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-DeviceRequest.performerType |
| DeviceRequest.performer | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-DeviceRequest.performer |
| DeviceRequest.reasonCode | UseElementSameName | DeviceUseRequest.indication |
| DeviceRequest.reasonReference | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-DeviceRequest.reasonReference |
| DeviceRequest.insurance | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-DeviceRequest.insurance |
| DeviceRequest.supportingInfo | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-DeviceRequest.supportingInfo |
| DeviceRequest.note | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-DeviceRequest.note |
| DeviceRequest.relevantHistory | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-DeviceRequest.relevantHistory |
