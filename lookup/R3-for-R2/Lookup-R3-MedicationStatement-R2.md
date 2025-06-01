### Lookup for FHIR R3 MedicationStatement for use in FHIR R2

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
| MedicationStatement.partOf | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-MedicationStatement.partOf |
| MedicationStatement.context | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-MedicationStatement.context |
| MedicationStatement.status | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-MedicationStatement.status |
| MedicationStatement.category | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-MedicationStatement.category |
| MedicationStatement.medication[x] | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-MedicationStatement.medication |
| MedicationStatement.effective[x] | UseElementSameName | MedicationStatement.effective[x] |
| MedicationStatement.dateAsserted | UseElementSameName | MedicationStatement.dateAsserted |
| MedicationStatement.informationSource | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-MedicationStatement.informationSource |
| MedicationStatement.subject | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-MedicationStatement.subject |
| MedicationStatement.derivedFrom | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-MedicationStatement.derivedFrom |
| MedicationStatement.taken | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-MedicationStatement.taken |
| MedicationStatement.reasonNotTaken | UseElementSameName | MedicationStatement.reasonNotTaken |
| MedicationStatement.reasonCode | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-MedicationStatement.reasonCode |
| MedicationStatement.reasonReference | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-MedicationStatement.reasonReference |
| MedicationStatement.note | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-MedicationStatement.note |
| MedicationStatement.dosage | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-MedicationStatement.dosage |
