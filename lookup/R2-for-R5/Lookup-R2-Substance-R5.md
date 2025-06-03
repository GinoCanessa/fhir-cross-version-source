### Lookup for FHIR R2 Substance for use in FHIR R5

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Substance.id | UseElementSameName | Substance.id |
| Substance.meta | UseElementSameName | Substance.meta |
| Substance.implicitRules | UseElementSameName | Substance.implicitRules |
| Substance.language | UseElementSameName | Substance.language |
| Substance.text | UseElementSameName | Substance.text |
| Substance.contained | UseElementSameName | Substance.contained |
| Substance.extension | UseElementSameName | Substance.extension |
| Substance.modifierExtension | UseElementSameName | Substance.modifierExtension |
| Substance.identifier | UseElementSameName | Substance.identifier |
| Substance.category | UseElementSameName | Substance.category |
| Substance.code | UseElementSameName | Substance.code |
| Substance.description | UseElementSameName | Substance.description |
| Substance.instance | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Substance.instance |
| Substance.instance.id | UseExtensionFromAncestor | - |
| Substance.instance.extension | UseExtensionFromAncestor | - |
| Substance.instance.modifierExtension | UseExtensionFromAncestor | - |
| Substance.instance.identifier | UseExtensionFromAncestor | - |
| Substance.instance.expiry | UseExtensionFromAncestor | - |
| Substance.instance.quantity | UseExtensionFromAncestor | - |
| Substance.ingredient | UseElementSameName | Substance.ingredient |
| Substance.ingredient.id | UseElementSameName | Substance.ingredient.id |
| Substance.ingredient.extension | UseElementSameName | Substance.ingredient.extension |
| Substance.ingredient.modifierExtension | UseElementSameName | Substance.ingredient.modifierExtension |
| Substance.ingredient.quantity | UseElementSameName | Substance.ingredient.quantity |
| Substance.ingredient.substance | UseElementRenamed | Substance.ingredient.substance[x] |
