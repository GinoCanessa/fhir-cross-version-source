### Lookup for FHIR R4B Medication for use in FHIR R5

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
| Medication.manufacturer | UseElementRenamed | Medication.marketingAuthorizationHolder |
| Medication.form | UseElementRenamed | Medication.doseForm |
| Medication.amount | UseElementRenamed | Medication.totalVolume |
| Medication.ingredient | UseElementSameName | Medication.ingredient |
| Medication.ingredient.id | UseElementSameName | Medication.ingredient.id |
| Medication.ingredient.extension | UseElementSameName | Medication.ingredient.extension |
| Medication.ingredient.modifierExtension | UseElementSameName | Medication.ingredient.modifierExtension |
| Medication.ingredient.item[x] | UseElementRenamed | Medication.ingredient.item |
| Medication.ingredient.isActive | UseElementSameName | Medication.ingredient.isActive |
| Medication.ingredient.strength | UseElementRenamed | Medication.ingredient.strength[x] |
| Medication.batch | UseElementSameName | Medication.batch |
| Medication.batch.id | UseElementSameName | Medication.batch.id |
| Medication.batch.extension | UseElementSameName | Medication.batch.extension |
| Medication.batch.modifierExtension | UseElementSameName | Medication.batch.modifierExtension |
| Medication.batch.lotNumber | UseElementSameName | Medication.batch.lotNumber |
| Medication.batch.expirationDate | UseElementSameName | Medication.batch.expirationDate |
