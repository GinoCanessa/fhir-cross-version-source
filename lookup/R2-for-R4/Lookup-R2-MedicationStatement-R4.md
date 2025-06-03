### Lookup for FHIR R2 MedicationStatement for use in FHIR R4

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| MedicationStatement.id | UseElementSameName | MedicationStatement.id |
| MedicationStatement.meta | UseElementSameName | MedicationStatement.meta |
| MedicationStatement.implicitRules | UseElementSameName | MedicationStatement.implicitRules |
| MedicationStatement.language | UseElementSameName | MedicationStatement.language |
| MedicationStatement.text | UseElementSameName | MedicationStatement.text |
| MedicationStatement.contained | UseElementSameName | MedicationStatement.contained |
| MedicationStatement.extension | UseElementSameName | MedicationStatement.extension |
| MedicationStatement.modifierExtension | UseElementSameName | MedicationStatement.modifierExtension |
| MedicationStatement.identifier | UseElementSameName | MedicationStatement.identifier |
| MedicationStatement.patient | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.patient |
| MedicationStatement.informationSource | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.informationSource |
| MedicationStatement.dateAsserted | UseElementSameName | MedicationStatement.dateAsserted |
| MedicationStatement.status | UseElementSameName | MedicationStatement.status |
| MedicationStatement.wasNotTaken | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.wasNotTaken |
| MedicationStatement.reasonNotTaken | UseElementRenamed | MedicationStatement.reasonCode |
| MedicationStatement.reasonForUse[x] | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.reasonForUse |
| MedicationStatement.effective[x] | UseElementSameName | MedicationStatement.effective[x] |
| MedicationStatement.note | UseElementSameName | MedicationStatement.note |
| MedicationStatement.supportingInformation | UseElementRenamed | MedicationStatement.derivedFrom |
| MedicationStatement.medication[x] | UseElementSameName | MedicationStatement.medication[x] |
| MedicationStatement.dosage | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.dosage |
| MedicationStatement.dosage.id | UseExtensionFromAncestor | - |
| MedicationStatement.dosage.extension | UseExtensionFromAncestor | - |
| MedicationStatement.dosage.modifierExtension | UseExtensionFromAncestor | - |
| MedicationStatement.dosage.text | UseExtensionFromAncestor | - |
| MedicationStatement.dosage.timing | UseExtensionFromAncestor | - |
| MedicationStatement.dosage.asNeeded[x] | UseExtensionFromAncestor | - |
| MedicationStatement.dosage.site[x] | UseExtensionFromAncestor | - |
| MedicationStatement.dosage.route | UseExtensionFromAncestor | - |
| MedicationStatement.dosage.method | UseExtensionFromAncestor | - |
| MedicationStatement.dosage.quantity[x] | UseExtensionFromAncestor | - |
| MedicationStatement.dosage.rate[x] | UseExtensionFromAncestor | - |
| MedicationStatement.dosage.maxDosePerPeriod | UseExtensionFromAncestor | - |
