### Lookup for FHIR R5 Medication for use in FHIR R4B

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Medication.id | UseElementSameName | Medication.id |
| Medication.meta | UseElementSameName | Medication.meta |
| Medication.implicitRules | UseElementSameName | Medication.implicitRules |
| Medication.language | UseElementSameName | Medication.language |
| Medication.text | UseElementSameName | Medication.text |
| Medication.contained | UseElementSameName | Medication.contained |
| Medication.extension | UseElementSameName | Medication.extension |
| Medication.modifierExtension | UseElementSameName | Medication.modifierExtension |
| Medication.identifier | UseElementSameName | Medication.identifier |
| Medication.code | UseElementSameName | Medication.code |
| Medication.status | UseElementSameName | Medication.status |
| Medication.marketingAuthorizationHolder | UseElementRenamed | Medication.manufacturer |
| Medication.doseForm | UseElementRenamed | Medication.form |
| Medication.totalVolume | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Medication.totalVolume |
| Medication.ingredient | UseElementSameName | Medication.ingredient |
| Medication.ingredient.id | UseElementSameName | Medication.ingredient.id |
| Medication.ingredient.extension | UseElementSameName | Medication.ingredient.extension |
| Medication.ingredient.modifierExtension | UseElementSameName | Medication.ingredient.modifierExtension |
| Medication.ingredient.item | UseElementRenamed | Medication.ingredient.item[x] |
| Medication.ingredient.isActive | UseElementSameName | Medication.ingredient.isActive |
| Medication.ingredient.strength[x] | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Medication.ingredient.strength |
| Medication.batch | UseElementSameName | Medication.batch |
| Medication.batch.id | UseElementSameName | Medication.batch.id |
| Medication.batch.extension | UseElementSameName | Medication.batch.extension |
| Medication.batch.modifierExtension | UseElementSameName | Medication.batch.modifierExtension |
| Medication.batch.lotNumber | UseElementSameName | Medication.batch.lotNumber |
| Medication.batch.expirationDate | UseElementSameName | Medication.batch.expirationDate |
| Medication.definition | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Medication.definition |
