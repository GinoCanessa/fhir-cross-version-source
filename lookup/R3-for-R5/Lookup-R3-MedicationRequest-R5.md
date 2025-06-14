### Lookup for FHIR R3 MedicationRequest for use in FHIR R5

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| MedicationRequest.id | UseElementSameName | MedicationRequest.id |
| MedicationRequest.meta | UseElementSameName | MedicationRequest.meta |
| MedicationRequest.implicitRules | UseElementSameName | MedicationRequest.implicitRules |
| MedicationRequest.language | UseElementSameName | MedicationRequest.language |
| MedicationRequest.text | UseElementSameName | MedicationRequest.text |
| MedicationRequest.contained | UseElementSameName | MedicationRequest.contained |
| MedicationRequest.extension | UseElementSameName | MedicationRequest.extension |
| MedicationRequest.modifierExtension | UseElementSameName | MedicationRequest.modifierExtension |
| MedicationRequest.identifier | UseElementSameName | MedicationRequest.identifier |
| MedicationRequest.definition | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-MedicationRequest.definition |
| MedicationRequest.basedOn | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-MedicationRequest.basedOn |
| MedicationRequest.groupIdentifier | UseElementSameName | MedicationRequest.groupIdentifier |
| MedicationRequest.status | UseElementSameName | MedicationRequest.status |
| MedicationRequest.intent | UseElementSameName | MedicationRequest.intent |
| MedicationRequest.category | UseElementSameName | MedicationRequest.category |
| MedicationRequest.priority | UseElementSameName | MedicationRequest.priority |
| MedicationRequest.medication[x] | UseElementRenamed | MedicationRequest.medication |
| MedicationRequest.subject | UseElementSameName | MedicationRequest.subject |
| MedicationRequest.context | UseElementRenamed | MedicationRequest.encounter |
| MedicationRequest.supportingInformation | UseElementSameName | MedicationRequest.supportingInformation |
| MedicationRequest.authoredOn | UseElementSameName | MedicationRequest.authoredOn |
| MedicationRequest.requester | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-MedicationRequest.requester |
| MedicationRequest.requester.id | UseExtensionFromAncestor | - |
| MedicationRequest.requester.extension | UseExtensionFromAncestor | - |
| MedicationRequest.requester.modifierExtension | UseExtensionFromAncestor | - |
| MedicationRequest.requester.agent | UseExtensionFromAncestor | - |
| MedicationRequest.requester.onBehalfOf | UseExtensionFromAncestor | - |
| MedicationRequest.recorder | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-MedicationRequest.recorder |
| MedicationRequest.reasonCode | UseElementRenamed | MedicationRequest.reason |
| MedicationRequest.reasonReference | UseElementRenamed | MedicationRequest.reason |
| MedicationRequest.note | UseElementSameName | MedicationRequest.note |
| MedicationRequest.dosageInstruction | UseElementSameName | MedicationRequest.dosageInstruction |
| MedicationRequest.dispenseRequest | UseElementSameName | MedicationRequest.dispenseRequest |
| MedicationRequest.dispenseRequest.id | UseElementSameName | MedicationRequest.dispenseRequest.id |
| MedicationRequest.dispenseRequest.extension | UseElementSameName | MedicationRequest.dispenseRequest.extension |
| MedicationRequest.dispenseRequest.modifierExtension | UseElementSameName | MedicationRequest.dispenseRequest.modifierExtension |
| MedicationRequest.dispenseRequest.validityPeriod | UseElementSameName | MedicationRequest.dispenseRequest.validityPeriod |
| MedicationRequest.dispenseRequest.numberOfRepeatsAllowed | UseElementSameName | MedicationRequest.dispenseRequest.numberOfRepeatsAllowed |
| MedicationRequest.dispenseRequest.quantity | UseElementSameName | MedicationRequest.dispenseRequest.quantity |
| MedicationRequest.dispenseRequest.expectedSupplyDuration | UseElementSameName | MedicationRequest.dispenseRequest.expectedSupplyDuration |
| MedicationRequest.dispenseRequest.performer | UseElementRenamed | MedicationRequest.dispenseRequest.dispenser |
| MedicationRequest.substitution | UseElementSameName | MedicationRequest.substitution |
| MedicationRequest.substitution.id | UseElementSameName | MedicationRequest.substitution.id |
| MedicationRequest.substitution.extension | UseElementSameName | MedicationRequest.substitution.extension |
| MedicationRequest.substitution.modifierExtension | UseElementSameName | MedicationRequest.substitution.modifierExtension |
| MedicationRequest.substitution.allowed | UseElementRenamed | MedicationRequest.substitution.allowed[x] |
| MedicationRequest.substitution.reason | UseElementSameName | MedicationRequest.substitution.reason |
| MedicationRequest.priorPrescription | UseElementSameName | MedicationRequest.priorPrescription |
| MedicationRequest.detectedIssue | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-MedicationRequest.detectedIssue |
| MedicationRequest.eventHistory | UseElementSameName | MedicationRequest.eventHistory |
