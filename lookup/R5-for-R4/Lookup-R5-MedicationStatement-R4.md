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
| MedicationStatement.partOf | UseElementSameName | MedicationStatement.partOf |
| MedicationStatement.status | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.status |
| MedicationStatement.category | UseElementSameName | MedicationStatement.category |
| MedicationStatement.medication | UseElementSameName | MedicationStatement.medication[x] |
| MedicationStatement.subject | UseElementSameName | MedicationStatement.subject |
| MedicationStatement.encounter | UseElementSameName | MedicationStatement.context |
| MedicationStatement.effective[x] | UseElementSameName | MedicationStatement.effective[x] |
| MedicationStatement.dateAsserted | UseElementSameName | MedicationStatement.dateAsserted |
| MedicationStatement.informationSource | UseElementSameName | MedicationStatement.informationSource |
| MedicationStatement.derivedFrom | UseElementSameName | MedicationStatement.derivedFrom |
| MedicationStatement.reason | UseElementSameName | MedicationStatement.reasonCode |
| MedicationStatement.note | UseElementSameName | MedicationStatement.note |
| MedicationStatement.relatedClinicalInformation | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.relatedClinicalInformation |
| MedicationStatement.renderedDosageInstruction | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.renderedDosageInstruction |
| MedicationStatement.dosage | UseElementSameName | MedicationStatement.dosage |
| MedicationStatement.adherence | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-MedicationStatement.adherence |
| MedicationStatement.adherence.id | UseExtensionFromAncestor | - |
| MedicationStatement.adherence.extension | UseExtensionFromAncestor | - |
| MedicationStatement.adherence.modifierExtension | UseExtensionFromAncestor | - |
| MedicationStatement.adherence.code | UseExtensionFromAncestor | - |
| MedicationStatement.adherence.reason | UseExtensionFromAncestor | - |
