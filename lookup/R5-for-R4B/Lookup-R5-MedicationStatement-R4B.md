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
| MedicationStatement.partOf | UseElementRenamed | MedicationStatement.partOf |
| MedicationStatement.status | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.status |
| MedicationStatement.category | UseElementRenamed | MedicationStatement.category |
| MedicationStatement.medication | UseElementRenamed | MedicationStatement.medication[x] |
| MedicationStatement.subject | UseElementRenamed | MedicationStatement.subject |
| MedicationStatement.encounter | UseElementRenamed | MedicationStatement.context |
| MedicationStatement.effective[x] | UseElementRenamed | MedicationStatement.effective[x] |
| MedicationStatement.dateAsserted | UseElementRenamed | MedicationStatement.dateAsserted |
| MedicationStatement.informationSource | UseElementRenamed | MedicationStatement.informationSource |
| MedicationStatement.derivedFrom | UseElementRenamed | MedicationStatement.derivedFrom |
| MedicationStatement.reason | UseElementRenamed | MedicationStatement.reasonCode |
| MedicationStatement.note | UseElementRenamed | MedicationStatement.note |
| MedicationStatement.relatedClinicalInformation | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.relatedClinicalInformation |
| MedicationStatement.renderedDosageInstruction | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.renderedDosageInstruction |
| MedicationStatement.dosage | UseElementRenamed | MedicationStatement.dosage |
| MedicationStatement.adherence | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.adherence |
| MedicationStatement.adherence.id | UseExtensionFromAncestor | - |
| MedicationStatement.adherence.extension | UseExtensionFromAncestor | - |
| MedicationStatement.adherence.modifierExtension | UseExtensionFromAncestor | - |
| MedicationStatement.adherence.code | UseExtensionFromAncestor | - |
| MedicationStatement.adherence.reason | UseExtensionFromAncestor | - |
