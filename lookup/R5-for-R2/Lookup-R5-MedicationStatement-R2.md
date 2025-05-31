### Lookup for FHIR R5 MedicationStatement for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| MedicationStatement.id | UseElementSameName | MedicationStatement.id |
| MedicationStatement.meta | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.meta |
| MedicationStatement.implicitRules | UseElementSameName | MedicationStatement.implicitRules |
| MedicationStatement.language | UseElementSameName | MedicationStatement.language |
| MedicationStatement.text | UseElementSameName | MedicationStatement.text |
| MedicationStatement.contained | UseElementSameName | MedicationStatement.contained |
| MedicationStatement.extension | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.extension |
| MedicationStatement.modifierExtension | UseElementSameName | MedicationStatement.modifierExtension |
| MedicationStatement.identifier | UseElementSameName | MedicationStatement.identifier |
| MedicationStatement.partOf | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.partOf |
| MedicationStatement.status | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.status |
| MedicationStatement.category | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.category |
| MedicationStatement.medication | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.medication |
| MedicationStatement.subject | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.subject |
| MedicationStatement.encounter | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.encounter |
| MedicationStatement.effective[x] | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.effective |
| MedicationStatement.dateAsserted | UseElementSameName | MedicationStatement.dateAsserted |
| MedicationStatement.informationSource | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.informationSource |
| MedicationStatement.derivedFrom | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.derivedFrom |
| MedicationStatement.reason | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.reason |
| MedicationStatement.note | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.note |
| MedicationStatement.relatedClinicalInformation | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.relatedClinicalInformation |
| MedicationStatement.renderedDosageInstruction | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.renderedDosageInstruction |
| MedicationStatement.dosage | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.dosage |
| MedicationStatement.adherence | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.adherence |
| MedicationStatement.adherence.id | UseExtensionFromAncestor | - |
| MedicationStatement.adherence.extension | UseExtensionFromAncestor | - |
| MedicationStatement.adherence.modifierExtension | UseExtensionFromAncestor | - |
| MedicationStatement.adherence.code | UseExtensionFromAncestor | - |
| MedicationStatement.adherence.reason | UseExtensionFromAncestor | - |
