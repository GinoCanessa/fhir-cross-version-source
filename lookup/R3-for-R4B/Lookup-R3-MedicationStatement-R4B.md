### Lookup for FHIR R3 MedicationStatement for use in FHIR R4B

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
| MedicationStatement.basedOn | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-MedicationStatement.basedOn |
| MedicationStatement.partOf | UseElementSameName | MedicationStatement.partOf |
| MedicationStatement.context | UseElementSameName | MedicationStatement.context |
| MedicationStatement.status | UseElementSameName | MedicationStatement.status |
| MedicationStatement.category | UseElementSameName | MedicationStatement.category |
| MedicationStatement.medication[x] | UseElementSameName | MedicationStatement.medication[x] |
| MedicationStatement.effective[x] | UseElementSameName | MedicationStatement.effective[x] |
| MedicationStatement.dateAsserted | UseElementSameName | MedicationStatement.dateAsserted |
| MedicationStatement.informationSource | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-MedicationStatement.informationSource |
| MedicationStatement.subject | UseElementSameName | MedicationStatement.subject |
| MedicationStatement.derivedFrom | UseElementSameName | MedicationStatement.derivedFrom |
| MedicationStatement.taken | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-MedicationStatement.taken |
| MedicationStatement.reasonNotTaken | UseElementRenamed | MedicationStatement.reasonCode |
| MedicationStatement.reasonCode | UseElementSameName | MedicationStatement.reasonCode |
| MedicationStatement.reasonReference | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-MedicationStatement.reasonReference |
| MedicationStatement.note | UseElementSameName | MedicationStatement.note |
| MedicationStatement.dosage | UseElementSameName | MedicationStatement.dosage |
