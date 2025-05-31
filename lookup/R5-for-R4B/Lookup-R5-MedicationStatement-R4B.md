### Lookup for FHIR R5 MedicationStatement for use in FHIR R4B

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| MedicationStatement.id | UseElementRenamed | MedicationStatement.id |
| MedicationStatement.meta | UseElementRenamed | MedicationStatement.meta |
| MedicationStatement.implicitRules | UseElementRenamed | MedicationStatement.implicitRules |
| MedicationStatement.language | UseElementRenamed | MedicationStatement.language |
| MedicationStatement.text | UseElementRenamed | MedicationStatement.text |
| MedicationStatement.contained | UseElementRenamed | MedicationStatement.contained |
| MedicationStatement.extension | UseElementRenamed | MedicationStatement.extension |
| MedicationStatement.modifierExtension | UseElementRenamed | MedicationStatement.modifierExtension |
| MedicationStatement.identifier | UseElementRenamed | MedicationStatement.identifier |
| MedicationStatement.partOf | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.partOf |
| MedicationStatement.status | UseElementRenamed | MedicationStatement.status |
| MedicationStatement.category | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.category |
| MedicationStatement.medication | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.medication |
| MedicationStatement.subject | UseElementRenamed | MedicationStatement.subject |
| MedicationStatement.encounter | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.encounter |
| MedicationStatement.effective[x] | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.effective |
| MedicationStatement.dateAsserted | UseElementRenamed | MedicationStatement.dateAsserted |
| MedicationStatement.informationSource | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.informationSource |
| MedicationStatement.derivedFrom | UseElementRenamed | MedicationStatement.derivedFrom |
| MedicationStatement.reason | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.reason |
| MedicationStatement.note | UseElementRenamed | MedicationStatement.note |
| MedicationStatement.relatedClinicalInformation | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.relatedClinicalInformation |
| MedicationStatement.renderedDosageInstruction | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.renderedDosageInstruction |
| MedicationStatement.dosage | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.dosage |
| MedicationStatement.adherence | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.adherence |
| MedicationStatement.adherence.id | UseExtensionFromAncestor | - |
| MedicationStatement.adherence.extension | UseExtensionFromAncestor | - |
| MedicationStatement.adherence.modifierExtension | UseExtensionFromAncestor | - |
| MedicationStatement.adherence.code | UseExtensionFromAncestor | - |
| MedicationStatement.adherence.reason | UseExtensionFromAncestor | - |
