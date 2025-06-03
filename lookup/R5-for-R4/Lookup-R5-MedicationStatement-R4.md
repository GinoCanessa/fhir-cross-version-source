### Lookup for FHIR R5 MedicationStatement for use in FHIR R4

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
| MedicationStatement.partOf | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.partOf |
| MedicationStatement.status | UseElementSameName | MedicationStatement.status |
| MedicationStatement.category | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.category |
| MedicationStatement.medication | UseElementRenamed | MedicationStatement.medication[x] |
| MedicationStatement.subject | UseElementSameName | MedicationStatement.subject |
| MedicationStatement.encounter | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.encounter |
| MedicationStatement.effective[x] | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.effective |
| MedicationStatement.dateAsserted | UseElementSameName | MedicationStatement.dateAsserted |
| MedicationStatement.informationSource | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.informationSource |
| MedicationStatement.derivedFrom | UseElementSameName | MedicationStatement.derivedFrom |
| MedicationStatement.reason | UseOneOfElements | MedicationStatement.reasonCode,MedicationStatement.reasonCode,MedicationStatement.reasonReference |
| MedicationStatement.note | UseElementSameName | MedicationStatement.note |
| MedicationStatement.relatedClinicalInformation | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.relatedClinicalInformation |
| MedicationStatement.renderedDosageInstruction | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.renderedDosageInstruction |
| MedicationStatement.dosage | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.dosage |
| MedicationStatement.adherence | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.adherence |
| MedicationStatement.adherence.id | UseExtensionFromAncestor | - |
| MedicationStatement.adherence.extension | UseExtensionFromAncestor | - |
| MedicationStatement.adherence.modifierExtension | UseExtensionFromAncestor | - |
| MedicationStatement.adherence.code | UseExtensionFromAncestor | - |
| MedicationStatement.adherence.reason | UseExtensionFromAncestor | - |
