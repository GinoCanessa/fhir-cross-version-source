### Lookup for FHIR R2 MedicationAdministration for use in FHIR R5

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| MedicationAdministration.id | UseElementSameName | MedicationAdministration.id |
| MedicationAdministration.meta | UseElementSameName | MedicationAdministration.meta |
| MedicationAdministration.implicitRules | UseElementSameName | MedicationAdministration.implicitRules |
| MedicationAdministration.language | UseElementSameName | MedicationAdministration.language |
| MedicationAdministration.text | UseElementSameName | MedicationAdministration.text |
| MedicationAdministration.contained | UseElementSameName | MedicationAdministration.contained |
| MedicationAdministration.extension | UseElementSameName | MedicationAdministration.extension |
| MedicationAdministration.modifierExtension | UseElementSameName | MedicationAdministration.modifierExtension |
| MedicationAdministration.identifier | UseElementSameName | MedicationAdministration.identifier |
| MedicationAdministration.status | UseElementSameName | MedicationAdministration.status |
| MedicationAdministration.patient | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationAdministration.patient |
| MedicationAdministration.practitioner | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationAdministration.practitioner |
| MedicationAdministration.encounter | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationAdministration.encounter |
| MedicationAdministration.prescription | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationAdministration.prescription |
| MedicationAdministration.wasNotGiven | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationAdministration.wasNotGiven |
| MedicationAdministration.reasonNotGiven | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationAdministration.reasonNotGiven |
| MedicationAdministration.reasonGiven | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationAdministration.reasonGiven |
| MedicationAdministration.effectiveTime[x] | UseElementRenamed | MedicationAdministration.occurence[x] |
| MedicationAdministration.medication[x] | UseElementRenamed | MedicationAdministration.medication |
| MedicationAdministration.device | UseElementSameName | MedicationAdministration.device |
| MedicationAdministration.note | UseElementSameName | MedicationAdministration.note |
| MedicationAdministration.dosage | UseElementSameName | MedicationAdministration.dosage |
| MedicationAdministration.dosage.id | UseElementSameName | MedicationAdministration.dosage.id |
| MedicationAdministration.dosage.extension | UseElementSameName | MedicationAdministration.dosage.extension |
| MedicationAdministration.dosage.modifierExtension | UseElementSameName | MedicationAdministration.dosage.modifierExtension |
| MedicationAdministration.dosage.text | UseElementSameName | MedicationAdministration.dosage.text |
| MedicationAdministration.dosage.site[x] | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationAdministration.dosage.site |
| MedicationAdministration.dosage.route | UseElementSameName | MedicationAdministration.dosage.route |
| MedicationAdministration.dosage.method | UseElementSameName | MedicationAdministration.dosage.method |
| MedicationAdministration.dosage.quantity | UseElementRenamed | MedicationAdministration.dosage.dose |
| MedicationAdministration.dosage.rate[x] | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-MedicationAdministration.dosage.rate |
