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
| MedicationStatement.partOf | UseElementSameName | MedicationStatement.partOf |
| MedicationStatement.status | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-MedicationStatement.status |
| MedicationStatement.statusReason | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-MedicationStatement.statusReason |
| MedicationStatement.category | UseElementSameName | MedicationStatement.category |
| MedicationStatement.medication[x] | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-MedicationStatement.medication |
| MedicationStatement.subject | UseElementSameName | MedicationStatement.subject |
| MedicationStatement.context | UseElementRenamed | MedicationStatement.encounter |
| MedicationStatement.effective[x] | UseElementSameName | MedicationStatement.effective[x] |
| MedicationStatement.dateAsserted | UseElementSameName | MedicationStatement.dateAsserted |
| MedicationStatement.informationSource | UseElementSameName | MedicationStatement.informationSource |
| MedicationStatement.derivedFrom | UseElementSameName | MedicationStatement.derivedFrom |
| MedicationStatement.reasonCode | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-MedicationStatement.reasonCode |
| MedicationStatement.reasonReference | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-MedicationStatement.reasonReference |
| MedicationStatement.note | UseElementSameName | MedicationStatement.note |
| MedicationStatement.dosage | UseElementSameName | MedicationStatement.dosage |
