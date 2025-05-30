### Lookup for FHIR R5 MedicationRequest for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| MedicationRequest.id | UseElementSameName | MedicationOrder.id |
| MedicationRequest.meta | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationRequest.meta |
| MedicationRequest.implicitRules | UseElementSameName | MedicationOrder.implicitRules |
| MedicationRequest.language | UseElementSameName | MedicationOrder.language |
| MedicationRequest.text | UseElementSameName | MedicationOrder.text |
| MedicationRequest.contained | UseElementSameName | MedicationOrder.contained |
| MedicationRequest.extension | UseElementSameName | MedicationOrder.extension |
| MedicationRequest.modifierExtension | UseElementSameName | MedicationOrder.modifierExtension |
| MedicationRequest.identifier | UseElementSameName | MedicationOrder.identifier |
| MedicationRequest.basedOn | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationRequest.basedOn |
| MedicationRequest.priorPrescription | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationRequest.priorPrescription |
| MedicationRequest.groupIdentifier | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationRequest.groupIdentifier |
| MedicationRequest.status | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationRequest.status |
| MedicationRequest.statusReason | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationRequest.statusReason |
| MedicationRequest.statusChanged | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationRequest.statusChanged |
| MedicationRequest.intent | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationRequest.intent |
| MedicationRequest.category | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationRequest.category |
| MedicationRequest.priority | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationRequest.priority |
| MedicationRequest.doNotPerform | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationRequest.doNotPerform |
| MedicationRequest.medication | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationRequest.medication |
| MedicationRequest.subject | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationRequest.subject |
| MedicationRequest.informationSource | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationRequest.informationSource |
| MedicationRequest.encounter | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationRequest.encounter |
| MedicationRequest.supportingInformation | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationRequest.supportingInformation |
| MedicationRequest.authoredOn | UseElementSameName | MedicationOrder.dateWritten |
| MedicationRequest.requester | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationRequest.requester |
| MedicationRequest.reported | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationRequest.reported |
| MedicationRequest.performerType | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationRequest.performerType |
| MedicationRequest.performer | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationRequest.performer |
| MedicationRequest.device | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationRequest.device |
| MedicationRequest.recorder | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationRequest.recorder |
| MedicationRequest.reason | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationRequest.reason |
| MedicationRequest.courseOfTherapyType | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationRequest.courseOfTherapyType |
| MedicationRequest.insurance | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationRequest.insurance |
| MedicationRequest.note | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationRequest.note |
| MedicationRequest.renderedDosageInstruction | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationRequest.renderedDosageInstruction |
| MedicationRequest.effectiveDosePeriod | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationRequest.effectiveDosePeriod |
| MedicationRequest.dosageInstruction | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationRequest.dosageInstruction |
| MedicationRequest.dispenseRequest | UseElementSameName | MedicationOrder.dispenseRequest |
| MedicationRequest.dispenseRequest.id | UseElementSameName | MedicationOrder.dispenseRequest.id |
| MedicationRequest.dispenseRequest.extension | UseElementSameName | MedicationOrder.dispenseRequest.extension |
| MedicationRequest.dispenseRequest.modifierExtension | UseElementSameName | MedicationOrder.dispenseRequest.modifierExtension |
| MedicationRequest.dispenseRequest.initialFill | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationRequest.dispenseRequest.initialFill |
| MedicationRequest.dispenseRequest.initialFill.id | UseExtensionFromAncestor | - |
| MedicationRequest.dispenseRequest.initialFill.extension | UseExtensionFromAncestor | - |
| MedicationRequest.dispenseRequest.initialFill.modifierExtension | UseExtensionFromAncestor | - |
| MedicationRequest.dispenseRequest.initialFill.quantity | UseExtensionFromAncestor | - |
| MedicationRequest.dispenseRequest.initialFill.duration | UseExtensionFromAncestor | - |
| MedicationRequest.dispenseRequest.dispenseInterval | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationRequest.dispenseRequest.dispenseInterval |
| MedicationRequest.dispenseRequest.validityPeriod | UseElementSameName | MedicationOrder.dispenseRequest.validityPeriod |
| MedicationRequest.dispenseRequest.numberOfRepeatsAllowed | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationRequest.dispenseRequest.numberOfRepeatsAllowed |
| MedicationRequest.dispenseRequest.quantity | UseElementSameName | MedicationOrder.dispenseRequest.quantity |
| MedicationRequest.dispenseRequest.expectedSupplyDuration | UseElementSameName | MedicationOrder.dispenseRequest.expectedSupplyDuration |
| MedicationRequest.dispenseRequest.dispenser | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationRequest.dispenseRequest.dispenser |
| MedicationRequest.dispenseRequest.dispenserInstruction | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationRequest.dispenseRequest.dispenserInstruction |
| MedicationRequest.dispenseRequest.doseAdministrationAid | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationRequest.dispenseRequest.doseAdministrationAid |
| MedicationRequest.substitution | UseElementSameName | MedicationOrder.substitution |
| MedicationRequest.substitution.id | UseElementSameName | MedicationOrder.substitution.id |
| MedicationRequest.substitution.extension | UseElementSameName | MedicationOrder.substitution.extension |
| MedicationRequest.substitution.modifierExtension | UseElementSameName | MedicationOrder.substitution.modifierExtension |
| MedicationRequest.substitution.allowed[x] | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationRequest.substitution.allowed |
| MedicationRequest.substitution.reason | UseElementSameName | MedicationOrder.substitution.reason |
| MedicationRequest.eventHistory | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationRequest.eventHistory |
