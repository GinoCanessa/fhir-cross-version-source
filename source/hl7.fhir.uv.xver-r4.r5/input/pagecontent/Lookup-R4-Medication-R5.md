### Lookup for [FHIR R4](https://hl7.org/fhir/R4/) [Medication](https://hl7.org/fhir/R4/Medication.html) for use in [FHIR R5](https://hl7.org/fhir/R5/)

| Source Element (FHIR R4) | Usage | Target |
| -------------- | ----- | ------ |
| [Medication.meta](https://hl7.org/fhir/R4/Medication.html#resource) | `UseElementSameName` | [Medication.meta](https://hl7.org/fhir/R5/Medication.html#resource) |
| [Medication.implicitRules](https://hl7.org/fhir/R4/Medication.html#resource) | `UseElementSameName` | [Medication.implicitRules](https://hl7.org/fhir/R5/Medication.html#resource) |
| [Medication.language](https://hl7.org/fhir/R4/Medication.html#resource) | `UseElementSameName` | [Medication.language](https://hl7.org/fhir/R5/Medication.html#resource) |
| [Medication.text](https://hl7.org/fhir/R4/Medication.html#resource) | `UseElementSameName` | [Medication.text](https://hl7.org/fhir/R5/Medication.html#resource) |
| [Medication.contained](https://hl7.org/fhir/R4/Medication.html#resource) | `UseElementSameName` | [Medication.contained](https://hl7.org/fhir/R5/Medication.html#resource) |
| [Medication.identifier](https://hl7.org/fhir/R4/Medication.html#resource) | `UseElementSameName` | [Medication.identifier](https://hl7.org/fhir/R5/Medication.html#resource) |
| [Medication.code](https://hl7.org/fhir/R4/Medication.html#resource) | `UseElementSameName` | [Medication.code](https://hl7.org/fhir/R5/Medication.html#resource) |
| [Medication.status](https://hl7.org/fhir/R4/Medication.html#resource) | `UseElementSameName` | [Medication.status](https://hl7.org/fhir/R5/Medication.html#resource) |
| [Medication.manufacturer](https://hl7.org/fhir/R4/Medication.html#resource) | `UseElementRenamed` | [Medication.marketingAuthorizationHolder](https://hl7.org/fhir/R5/Medication.html#resource) |
| [Medication.form](https://hl7.org/fhir/R4/Medication.html#resource) | `UseElementRenamed` | [Medication.doseForm](https://hl7.org/fhir/R5/Medication.html#resource) |
| [Medication.amount](https://hl7.org/fhir/R4/Medication.html#resource) | `UseElementRenamed` | [Medication.totalVolume](https://hl7.org/fhir/R5/Medication.html#resource) |
| [Medication.ingredient](https://hl7.org/fhir/R4/Medication.html#resource) | `UseElementSameName` | [Medication.ingredient](https://hl7.org/fhir/R5/Medication.html#resource) |
| [Medication.ingredient.item[x]](https://hl7.org/fhir/R4/Medication.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.0/StructureDefinition/extension-Medication.ingredient.item](StructureDefinition-ext-R4-Medication.in.item.html) |
| [Medication.ingredient.isActive](https://hl7.org/fhir/R4/Medication.html#resource) | `UseElementSameName` | [Medication.ingredient.isActive](https://hl7.org/fhir/R5/Medication.html#resource) |
| [Medication.ingredient.strength](https://hl7.org/fhir/R4/Medication.html#resource) | `UseElementRenamed` | [Medication.ingredient.strength[x]](https://hl7.org/fhir/R5/Medication.html#resource) |
| [Medication.batch](https://hl7.org/fhir/R4/Medication.html#resource) | `UseElementSameName` | [Medication.batch](https://hl7.org/fhir/R5/Medication.html#resource) |
| [Medication.batch.lotNumber](https://hl7.org/fhir/R4/Medication.html#resource) | `UseElementSameName` | [Medication.batch.lotNumber](https://hl7.org/fhir/R5/Medication.html#resource) |
| [Medication.batch.expirationDate](https://hl7.org/fhir/R4/Medication.html#resource) | `UseElementSameName` | [Medication.batch.expirationDate](https://hl7.org/fhir/R5/Medication.html#resource) |
