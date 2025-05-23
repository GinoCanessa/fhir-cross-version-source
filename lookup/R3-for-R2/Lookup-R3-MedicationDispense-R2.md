### Lookup for FHIR R3 MedicationDispense for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| MedicationDispense.id | UseElementSameName | MedicationDispense.id |
| MedicationDispense.meta | UseElementSameName | MedicationDispense.meta |
| MedicationDispense.implicitRules | UseElementSameName | MedicationDispense.implicitRules |
| MedicationDispense.language | UseElementSameName | MedicationDispense.language |
| MedicationDispense.text | UseElementSameName | MedicationDispense.text |
| MedicationDispense.contained | UseElementSameName | MedicationDispense.contained |
| MedicationDispense.extension | UseElementSameName | MedicationDispense.extension |
| MedicationDispense.modifierExtension | UseElementSameName | MedicationDispense.modifierExtension |
| MedicationDispense.identifier | UseElementSameName | MedicationDispense.identifier |
| MedicationDispense.partOf | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-MedicationDispense.partOf |
| MedicationDispense.status | UseElementSameName | MedicationDispense.status |
| MedicationDispense.category | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-MedicationDispense.category |
| MedicationDispense.medication[x] | UseElementSameName | MedicationDispense.medication[x] |
| MedicationDispense.subject | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-MedicationDispense.subject |
| MedicationDispense.context | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-MedicationDispense.context |
| MedicationDispense.supportingInformation | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-MedicationDispense.supportingInformation |
| MedicationDispense.performer | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-MedicationDispense.performer |
| MedicationDispense.performer.id | UseExtensionFromAncestor | - |
| MedicationDispense.performer.extension | UseExtensionFromAncestor | - |
| MedicationDispense.performer.modifierExtension | UseExtensionFromAncestor | - |
| MedicationDispense.performer.actor | UseExtensionFromAncestor | - |
| MedicationDispense.performer.onBehalfOf | UseExtensionFromAncestor | - |
| MedicationDispense.authorizingPrescription | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-MedicationDispense.authorizingPrescription |
| MedicationDispense.type | UseElementSameName | MedicationDispense.type |
| MedicationDispense.quantity | UseElementSameName | MedicationDispense.quantity |
| MedicationDispense.daysSupply | UseElementSameName | MedicationDispense.daysSupply |
| MedicationDispense.whenPrepared | UseElementSameName | MedicationDispense.whenPrepared |
| MedicationDispense.whenHandedOver | UseElementSameName | MedicationDispense.whenHandedOver |
| MedicationDispense.destination | UseElementSameName | MedicationDispense.destination |
| MedicationDispense.receiver | UseElementSameName | MedicationDispense.receiver |
| MedicationDispense.note | UseElementSameName | MedicationDispense.note |
| MedicationDispense.dosageInstruction | UseElementSameName | MedicationDispense.dosageInstruction |
| MedicationDispense.substitution | UseElementSameName | MedicationDispense.substitution |
| MedicationDispense.substitution.id | UseElementSameName | MedicationDispense.substitution.id |
| MedicationDispense.substitution.extension | UseElementSameName | MedicationDispense.substitution.extension |
| MedicationDispense.substitution.modifierExtension | UseElementSameName | MedicationDispense.substitution.modifierExtension |
| MedicationDispense.substitution.wasSubstituted | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-MedicationDispense.substitution.wasSubstituted |
| MedicationDispense.substitution.type | UseElementSameName | MedicationDispense.substitution.type |
| MedicationDispense.substitution.reason | UseElementSameName | MedicationDispense.substitution.reason |
| MedicationDispense.substitution.responsibleParty | UseElementSameName | MedicationDispense.substitution.responsibleParty |
| MedicationDispense.detectedIssue | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-MedicationDispense.detectedIssue |
| MedicationDispense.notDone | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-MedicationDispense.notDone |
| MedicationDispense.notDoneReason[x] | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-MedicationDispense.notDoneReason |
| MedicationDispense.eventHistory | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-MedicationDispense.eventHistory |
