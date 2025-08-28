### Lookup for [FHIR R5](https://hl7.org/fhir/R5/) [Medication](https://hl7.org/fhir/R5/Medication.html) for use in [FHIR R4B](https://hl7.org/fhir/R4B/)

| Source Element (FHIR R5) | Usage | Target |
| -------------- | ----- | ------ |
| [Medication.meta](https://hl7.org/fhir/R5/Medication.html#resource) | `UseElementSameName` | [Medication.meta](https://hl7.org/fhir/R4B/Medication.html#resource) |
| [Medication.implicitRules](https://hl7.org/fhir/R5/Medication.html#resource) | `UseElementSameName` | [Medication.implicitRules](https://hl7.org/fhir/R4B/Medication.html#resource) |
| [Medication.language](https://hl7.org/fhir/R5/Medication.html#resource) | `UseElementSameName` | [Medication.language](https://hl7.org/fhir/R4B/Medication.html#resource) |
| [Medication.text](https://hl7.org/fhir/R5/Medication.html#resource) | `UseElementSameName` | [Medication.text](https://hl7.org/fhir/R4B/Medication.html#resource) |
| [Medication.contained](https://hl7.org/fhir/R5/Medication.html#resource) | `UseElementSameName` | [Medication.contained](https://hl7.org/fhir/R4B/Medication.html#resource) |
| [Medication.identifier](https://hl7.org/fhir/R5/Medication.html#resource) | `UseElementSameName` | [Medication.identifier](https://hl7.org/fhir/R4B/Medication.html#resource) |
| [Medication.code](https://hl7.org/fhir/R5/Medication.html#resource) | `UseElementSameName` | [Medication.code](https://hl7.org/fhir/R4B/Medication.html#resource) |
| [Medication.status](https://hl7.org/fhir/R5/Medication.html#resource) | `UseElementSameName` | [Medication.status](https://hl7.org/fhir/R4B/Medication.html#resource) |
| [Medication.marketingAuthorizationHolder](https://hl7.org/fhir/R5/Medication.html#resource) | `UseElementRenamed` | [Medication.manufacturer](https://hl7.org/fhir/R4B/Medication.html#resource) |
| [Medication.doseForm](https://hl7.org/fhir/R5/Medication.html#resource) | `UseElementRenamed` | [Medication.form](https://hl7.org/fhir/R4B/Medication.html#resource) |
| [Medication.totalVolume](https://hl7.org/fhir/R5/Medication.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-Medication.totalVolume](StructureDefinition-ext-R5-Medication.totalVolume.html) |
| [Medication.ingredient](https://hl7.org/fhir/R5/Medication.html#resource) | `UseElementSameName` | [Medication.ingredient](https://hl7.org/fhir/R4B/Medication.html#resource) |
| [Medication.ingredient.item](https://hl7.org/fhir/R5/Medication.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-Medication.ingredient.item](StructureDefinition-ext-R5-Medication.in.item.html) |
| [Medication.ingredient.isActive](https://hl7.org/fhir/R5/Medication.html#resource) | `UseElementSameName` | [Medication.ingredient.isActive](https://hl7.org/fhir/R4B/Medication.html#resource) |
| [Medication.ingredient.strength[x]](https://hl7.org/fhir/R5/Medication.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-Medication.ingredient.strength](StructureDefinition-ext-R5-Medication.in.strength.html) |
| [Medication.batch](https://hl7.org/fhir/R5/Medication.html#resource) | `UseElementSameName` | [Medication.batch](https://hl7.org/fhir/R4B/Medication.html#resource) |
| [Medication.batch.lotNumber](https://hl7.org/fhir/R5/Medication.html#resource) | `UseElementSameName` | [Medication.batch.lotNumber](https://hl7.org/fhir/R4B/Medication.html#resource) |
| [Medication.batch.expirationDate](https://hl7.org/fhir/R5/Medication.html#resource) | `UseElementSameName` | [Medication.batch.expirationDate](https://hl7.org/fhir/R4B/Medication.html#resource) |
| [Medication.definition](https://hl7.org/fhir/R5/Medication.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-Medication.definition](StructureDefinition-ext-R5-Medication.definition.html) |
