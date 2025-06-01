### Lookup for FHIR R4B Medication for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Medication.id | UseElementSameName | Medication.id |
| Medication.meta | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Medication.meta |
| Medication.implicitRules | UseElementSameName | Medication.implicitRules |
| Medication.language | UseElementSameName | Medication.language |
| Medication.text | UseElementSameName | Medication.text |
| Medication.contained | UseElementSameName | Medication.contained |
| Medication.extension | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Medication.extension |
| Medication.modifierExtension | UseElementSameName | Medication.modifierExtension |
| Medication.identifier | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Medication.identifier |
| Medication.code | UseElementSameName | Medication.code |
| Medication.status | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Medication.status |
| Medication.manufacturer | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Medication.manufacturer |
| Medication.form | UseElementRenamed | Medication.product.form |
| Medication.amount | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Medication.amount |
| Medication.ingredient | UseElementRenamed | Medication.product.ingredient |
| Medication.ingredient.id | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Medication.ingredient.id |
| Medication.ingredient.extension | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Medication.ingredient.extension |
| Medication.ingredient.modifierExtension | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Medication.ingredient.modifierExtension |
| Medication.ingredient.item[x] | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Medication.ingredient.item |
| Medication.ingredient.isActive | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Medication.ingredient.isActive |
| Medication.ingredient.strength | UseElementRenamed | Medication.product.ingredient.amount |
| Medication.batch | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Medication.batch |
| Medication.batch.id | UseExtensionFromAncestor | - |
| Medication.batch.extension | UseExtensionFromAncestor | - |
| Medication.batch.modifierExtension | UseExtensionFromAncestor | - |
| Medication.batch.lotNumber | UseExtensionFromAncestor | - |
| Medication.batch.expirationDate | UseExtensionFromAncestor | - |
