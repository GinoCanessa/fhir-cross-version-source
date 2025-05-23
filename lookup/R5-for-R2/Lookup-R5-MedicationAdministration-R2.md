### Lookup for FHIR R5 MedicationAdministration for use in FHIR R2

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
| MedicationAdministration.basedOn | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationAdministration.basedOn |
| MedicationAdministration.partOf | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationAdministration.partOf |
| MedicationAdministration.status | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationAdministration.status |
| MedicationAdministration.statusReason | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationAdministration.statusReason |
| MedicationAdministration.category | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationAdministration.category |
| MedicationAdministration.medication | UseElementRenamed | MedicationAdministration.medication[x] |
| MedicationAdministration.subject | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationAdministration.subject |
| MedicationAdministration.encounter | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationAdministration.encounter |
| MedicationAdministration.supportingInformation | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationAdministration.supportingInformation |
| MedicationAdministration.occurence[x] | UseElementRenamed | MedicationAdministration.effectiveTime[x] |
| MedicationAdministration.recorded | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationAdministration.recorded |
| MedicationAdministration.isSubPotent | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationAdministration.isSubPotent |
| MedicationAdministration.subPotentReason | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationAdministration.subPotentReason |
| MedicationAdministration.performer | UseElementSameName | MedicationAdministration.practitioner |
| MedicationAdministration.performer.id | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationAdministration.performer.id |
| MedicationAdministration.performer.extension | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationAdministration.performer.extension |
| MedicationAdministration.performer.modifierExtension | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationAdministration.performer.modifierExtension |
| MedicationAdministration.performer.function | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationAdministration.performer.function |
| MedicationAdministration.performer.actor | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationAdministration.performer.actor |
| MedicationAdministration.reason | UseElementRenamed | MedicationAdministration.reasonNotGiven |
| MedicationAdministration.request | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationAdministration.request |
| MedicationAdministration.device | UseElementSameName | MedicationAdministration.device |
| MedicationAdministration.note | UseElementSameName | MedicationAdministration.note |
| MedicationAdministration.dosage | UseElementSameName | MedicationAdministration.dosage |
| MedicationAdministration.dosage.id | UseElementSameName | MedicationAdministration.dosage.id |
| MedicationAdministration.dosage.extension | UseElementSameName | MedicationAdministration.dosage.extension |
| MedicationAdministration.dosage.modifierExtension | UseElementSameName | MedicationAdministration.dosage.modifierExtension |
| MedicationAdministration.dosage.text | UseElementSameName | MedicationAdministration.dosage.text |
| MedicationAdministration.dosage.site | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationAdministration.dosage.site |
| MedicationAdministration.dosage.route | UseElementSameName | MedicationAdministration.dosage.route |
| MedicationAdministration.dosage.method | UseElementSameName | MedicationAdministration.dosage.method |
| MedicationAdministration.dosage.dose | UseElementSameName | MedicationAdministration.dosage.quantity |
| MedicationAdministration.dosage.rate[x] | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationAdministration.dosage.rate |
| MedicationAdministration.eventHistory | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationAdministration.eventHistory |
