### Lookup for FHIR R2 MedicationStatement for use in FHIR R3

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
| MedicationStatement.status | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.status |
| MedicationStatement.wasNotTaken | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.wasNotTaken |
| MedicationStatement.reasonNotTaken | UseElementSameName | MedicationStatement.reasonNotTaken |
| MedicationStatement.reasonForUse[x] | UseElementRenamed | MedicationStatement.reasonCode |
| MedicationStatement.effective[x] | UseElementSameName | MedicationStatement.effective[x] |
| MedicationStatement.note | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.note |
| MedicationStatement.supportingInformation | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.supportingInformation |
| MedicationStatement.medication[x] | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.medication |
| MedicationStatement.dosage | UseElementSameName | MedicationStatement.dosage |
| MedicationStatement.dosage.id | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.dosage.id |
| MedicationStatement.dosage.extension | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.dosage.extension |
| MedicationStatement.dosage.modifierExtension | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.dosage.modifierExtension |
| MedicationStatement.dosage.text | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.dosage.text |
| MedicationStatement.dosage.timing | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.dosage.timing |
| MedicationStatement.dosage.asNeeded[x] | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.dosage.asNeeded |
| MedicationStatement.dosage.site[x] | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.dosage.site |
| MedicationStatement.dosage.route | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.dosage.route |
| MedicationStatement.dosage.method | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.dosage.method |
| MedicationStatement.dosage.quantity[x] | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.dosage.quantity |
| MedicationStatement.dosage.rate[x] | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.dosage.rate |
| MedicationStatement.dosage.maxDosePerPeriod | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationStatement.dosage.maxDosePerPeriod |
