### Lookup for [FHIR R3](https://hl7.org/fhir/STU3/) [Medication](https://hl7.org/fhir/STU3/Medication.html) for use in [FHIR R4B](https://hl7.org/fhir/R4B/)

| Source Element (FHIR R3) | Usage | Target |
| -------------- | ----- | ------ |
| [Medication.meta](https://hl7.org/fhir/STU3/Medication.html#resource) | `UseElementSameName` | [Medication.meta](https://hl7.org/fhir/R4B/Medication.html#resource) |
| [Medication.implicitRules](https://hl7.org/fhir/STU3/Medication.html#resource) | `UseElementSameName` | [Medication.implicitRules](https://hl7.org/fhir/R4B/Medication.html#resource) |
| [Medication.language](https://hl7.org/fhir/STU3/Medication.html#resource) | `UseElementSameName` | [Medication.language](https://hl7.org/fhir/R4B/Medication.html#resource) |
| [Medication.text](https://hl7.org/fhir/STU3/Medication.html#resource) | `UseElementSameName` | [Medication.text](https://hl7.org/fhir/R4B/Medication.html#resource) |
| [Medication.contained](https://hl7.org/fhir/STU3/Medication.html#resource) | `UseElementSameName` | [Medication.contained](https://hl7.org/fhir/R4B/Medication.html#resource) |
| [Medication.code](https://hl7.org/fhir/STU3/Medication.html#resource) | `UseElementSameName` | [Medication.code](https://hl7.org/fhir/R4B/Medication.html#resource) |
| [Medication.status](https://hl7.org/fhir/STU3/Medication.html#resource) | `UseOneOf` | [Medication.extension](https://hl7.org/fhir/R4B/Medication.html#resource)<br />[Medication.status](https://hl7.org/fhir/R4B/Medication.html#resource) |
| [Medication.isBrand](https://hl7.org/fhir/STU3/Medication.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Medication.isBrand](StructureDefinition-ext-R3-Medication.isBrand.html) |
| [Medication.isOverTheCounter](https://hl7.org/fhir/STU3/Medication.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Medication.isOverTheCounter](StructureDefinition-ext-R3-Medication.isOverTheCounter.html) |
| [Medication.manufacturer](https://hl7.org/fhir/STU3/Medication.html#resource) | `UseElementSameName` | [Medication.manufacturer](https://hl7.org/fhir/R4B/Medication.html#resource) |
| [Medication.form](https://hl7.org/fhir/STU3/Medication.html#resource) | `UseElementSameName` | [Medication.form](https://hl7.org/fhir/R4B/Medication.html#resource) |
| [Medication.ingredient](https://hl7.org/fhir/STU3/Medication.html#resource) | `UseElementSameName` | [Medication.ingredient](https://hl7.org/fhir/R4B/Medication.html#resource) |
| [Medication.ingredient.item[x]](https://hl7.org/fhir/STU3/Medication.html#resource) | `UseElementSameName` | [Medication.ingredient.item[x]](https://hl7.org/fhir/R4B/Medication.html#resource) |
| [Medication.ingredient.isActive](https://hl7.org/fhir/STU3/Medication.html#resource) | `UseElementSameName` | [Medication.ingredient.isActive](https://hl7.org/fhir/R4B/Medication.html#resource) |
| [Medication.ingredient.amount](https://hl7.org/fhir/STU3/Medication.html#resource) | `UseElementRenamed` | [Medication.ingredient.strength](https://hl7.org/fhir/R4B/Medication.html#resource) |
| [Medication.package](https://hl7.org/fhir/STU3/Medication.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Medication.package](StructureDefinition-ext-R3-Medication.package.html) |
| [Medication.package.container](https://hl7.org/fhir/STU3/Medication.html#resource) | `UseExtensionFromAncestor` | - |
| [Medication.package.content](https://hl7.org/fhir/STU3/Medication.html#resource) | `UseExtensionFromAncestor` | - |
| [Medication.package.content.item[x]](https://hl7.org/fhir/STU3/Medication.html#resource) | `UseExtensionFromAncestor` | - |
| [Medication.package.content.amount](https://hl7.org/fhir/STU3/Medication.html#resource) | `UseExtensionFromAncestor` | - |
| [Medication.package.batch](https://hl7.org/fhir/STU3/Medication.html#resource) | `UseExtensionFromAncestor` | - |
| [Medication.package.batch.lotNumber](https://hl7.org/fhir/STU3/Medication.html#resource) | `UseExtensionFromAncestor` | - |
| [Medication.package.batch.expirationDate](https://hl7.org/fhir/STU3/Medication.html#resource) | `UseExtensionFromAncestor` | - |
| [Medication.image](https://hl7.org/fhir/STU3/Medication.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Medication.image](StructureDefinition-ext-R3-Medication.image.html) |
