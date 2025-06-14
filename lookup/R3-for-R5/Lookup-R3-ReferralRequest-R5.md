### Lookup for FHIR R3 ReferralRequest for use in FHIR R5

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| ReferralRequest.id | UseElementRenamed | ServiceRequest.id |
| ReferralRequest.meta | UseElementRenamed | ServiceRequest.meta |
| ReferralRequest.implicitRules | UseElementRenamed | ServiceRequest.implicitRules |
| ReferralRequest.language | UseElementRenamed | ServiceRequest.language |
| ReferralRequest.text | UseElementRenamed | ServiceRequest.text |
| ReferralRequest.contained | UseElementRenamed | ServiceRequest.contained |
| ReferralRequest.extension | UseElementRenamed | ServiceRequest.extension |
| ReferralRequest.modifierExtension | UseElementRenamed | ServiceRequest.modifierExtension |
| ReferralRequest.identifier | UseElementRenamed | ServiceRequest.identifier |
| ReferralRequest.definition | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ReferralRequest.definition |
| ReferralRequest.basedOn | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ReferralRequest.basedOn |
| ReferralRequest.replaces | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ReferralRequest.replaces |
| ReferralRequest.groupIdentifier | UseElementRenamed | ServiceRequest.requisition |
| ReferralRequest.status | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ReferralRequest.status |
| ReferralRequest.intent | UseElementRenamed | ServiceRequest.intent |
| ReferralRequest.type | UseElementRenamed | ServiceRequest.category |
| ReferralRequest.priority | UseElementRenamed | ServiceRequest.priority |
| ReferralRequest.serviceRequested | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ReferralRequest.serviceRequested |
| ReferralRequest.subject | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ReferralRequest.subject |
| ReferralRequest.context | UseElementRenamed | ServiceRequest.encounter |
| ReferralRequest.occurrence[x] | UseElementRenamed | ServiceRequest.occurrence[x] |
| ReferralRequest.authoredOn | UseElementRenamed | ServiceRequest.authoredOn |
| ReferralRequest.requester | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ReferralRequest.requester |
| ReferralRequest.requester.id | UseExtensionFromAncestor | - |
| ReferralRequest.requester.extension | UseExtensionFromAncestor | - |
| ReferralRequest.requester.modifierExtension | UseExtensionFromAncestor | - |
| ReferralRequest.requester.agent | UseExtensionFromAncestor | - |
| ReferralRequest.requester.onBehalfOf | UseExtensionFromAncestor | - |
| ReferralRequest.specialty | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ReferralRequest.specialty |
| ReferralRequest.recipient | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ReferralRequest.recipient |
| ReferralRequest.reasonCode | UseElementRenamed | ServiceRequest.reason |
| ReferralRequest.reasonReference | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ReferralRequest.reasonReference |
| ReferralRequest.description | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-ReferralRequest.description |
| ReferralRequest.supportingInfo | UseElementRenamed | ServiceRequest.supportingInfo |
| ReferralRequest.note | UseElementRenamed | ServiceRequest.note |
| ReferralRequest.relevantHistory | UseElementRenamed | ServiceRequest.relevantHistory |
