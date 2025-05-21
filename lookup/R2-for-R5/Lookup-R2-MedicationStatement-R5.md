### Lookup for FHIR R2 MedicationStatement for use in FHIR R5

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| MedicationStatement.id | UseElementSameName | MedicationStatement.id |
| MedicationStatement.meta | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.meta |
| MedicationStatement.implicitRules | UseElementSameName | MedicationStatement.implicitRules |
| MedicationStatement.language | UseElementSameName | MedicationStatement.language |
| MedicationStatement.text | UseElementSameName | MedicationStatement.text |
| MedicationStatement.contained | UseElementSameName | MedicationStatement.contained |
| MedicationStatement.extension | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.extension |
| MedicationStatement.modifierExtension | UseElementSameName | MedicationStatement.modifierExtension |
| MedicationStatement.identifier | UseElementSameName | MedicationStatement.identifier |
| MedicationStatement.patient | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.patient |
| MedicationStatement.informationSource | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.informationSource |
| MedicationStatement.dateAsserted | UseElementSameName | MedicationStatement.dateAsserted |
| MedicationStatement.status | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.status |
| MedicationStatement.wasNotTaken | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.wasNotTaken |
| MedicationStatement.reasonNotTaken | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.reasonNotTaken |
| MedicationStatement.reasonForUse[x] | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.reasonForUse |
| MedicationStatement.effective[x] | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.effective |
| MedicationStatement.note | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.note |
| MedicationStatement.supportingInformation | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.supportingInformation |
| MedicationStatement.medication[x] | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.medication |
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
