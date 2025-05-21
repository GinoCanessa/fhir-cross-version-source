### Lookup for FHIR R4 MedicationStatement for use in FHIR R5

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
| MedicationStatement.basedOn | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-MedicationStatement.basedOn |
| MedicationStatement.partOf | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-MedicationStatement.partOf |
| MedicationStatement.status | UseElementSameName | MedicationStatement.status |
| MedicationStatement.statusReason | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-MedicationStatement.statusReason |
| MedicationStatement.category | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-MedicationStatement.category |
| MedicationStatement.medication[x] | UseElementRenamed | MedicationStatement.medication |
| MedicationStatement.subject | UseElementSameName | MedicationStatement.subject |
| MedicationStatement.context | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-MedicationStatement.context |
| MedicationStatement.effective[x] | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-MedicationStatement.effective |
| MedicationStatement.dateAsserted | UseElementSameName | MedicationStatement.dateAsserted |
| MedicationStatement.informationSource | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-MedicationStatement.informationSource |
| MedicationStatement.derivedFrom | UseElementSameName | MedicationStatement.derivedFrom |
| MedicationStatement.reasonCode | UseElementRenamed | MedicationStatement.reason |
| MedicationStatement.reasonReference | UseElementRenamed | MedicationStatement.reason |
| MedicationStatement.note | UseElementSameName | MedicationStatement.note |
| MedicationStatement.dosage | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-MedicationStatement.dosage |
