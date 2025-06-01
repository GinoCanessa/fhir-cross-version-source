### Lookup for FHIR R4 Medication for use in FHIR R3

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Medication.id | UseElementSameName | Medication.id |
| Medication.meta | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Medication.meta |
| Medication.implicitRules | UseElementSameName | Medication.implicitRules |
| Medication.language | UseElementSameName | Medication.language |
| Medication.text | UseElementSameName | Medication.text |
| Medication.contained | UseElementSameName | Medication.contained |
| Medication.extension | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Medication.extension |
| Medication.modifierExtension | UseElementSameName | Medication.modifierExtension |
| Medication.identifier | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Medication.identifier |
| Medication.code | UseElementSameName | Medication.code |
| Medication.status | UseElementSameName | Medication.status |
| Medication.manufacturer | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Medication.manufacturer |
| Medication.form | UseElementSameName | Medication.form |
| Medication.amount | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Medication.amount |
| Medication.ingredient | UseElementSameName | Medication.ingredient |
| Medication.ingredient.id | UseElementSameName | Medication.ingredient.id |
| Medication.ingredient.extension | UseElementSameName | Medication.ingredient.extension |
| Medication.ingredient.modifierExtension | UseElementSameName | Medication.ingredient.modifierExtension |
| Medication.ingredient.item[x] | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Medication.ingredient.item |
| Medication.ingredient.isActive | UseElementSameName | Medication.ingredient.isActive |
| Medication.ingredient.strength | UseElementRenamed | Medication.ingredient.amount |
| Medication.batch | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Medication.batch |
| Medication.batch.id | UseExtensionFromAncestor | - |
| Medication.batch.extension | UseExtensionFromAncestor | - |
| Medication.batch.modifierExtension | UseExtensionFromAncestor | - |
| Medication.batch.lotNumber | UseExtensionFromAncestor | - |
| Medication.batch.expirationDate | UseExtensionFromAncestor | - |
