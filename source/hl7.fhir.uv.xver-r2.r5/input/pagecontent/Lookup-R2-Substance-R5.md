### Lookup for [FHIR R2](https://hl7.org/fhir/DSTU2/) [Substance](https://hl7.org/fhir/DSTU2/Substance.html) for use in [FHIR R5](https://hl7.org/fhir/R5/)

| Source Element (FHIR R2) | Usage | Target |
| -------------- | ----- | ------ |
| [Substance.meta](https://hl7.org/fhir/DSTU2/Substance.html#resource) | `UseElementSameName` | [Substance.meta](https://hl7.org/fhir/R5/Substance.html#resource) |
| [Substance.implicitRules](https://hl7.org/fhir/DSTU2/Substance.html#resource) | `UseElementSameName` | [Substance.implicitRules](https://hl7.org/fhir/R5/Substance.html#resource) |
| [Substance.language](https://hl7.org/fhir/DSTU2/Substance.html#resource) | `UseElementSameName` | [Substance.language](https://hl7.org/fhir/R5/Substance.html#resource) |
| [Substance.text](https://hl7.org/fhir/DSTU2/Substance.html#resource) | `UseElementSameName` | [Substance.text](https://hl7.org/fhir/R5/Substance.html#resource) |
| [Substance.contained](https://hl7.org/fhir/DSTU2/Substance.html#resource) | `UseElementSameName` | [Substance.contained](https://hl7.org/fhir/R5/Substance.html#resource) |
| [Substance.identifier](https://hl7.org/fhir/DSTU2/Substance.html#resource) | `UseElementSameName` | [Substance.identifier](https://hl7.org/fhir/R5/Substance.html#resource) |
| [Substance.category](https://hl7.org/fhir/DSTU2/Substance.html#resource) | `UseElementSameName` | [Substance.category](https://hl7.org/fhir/R5/Substance.html#resource) |
| [Substance.code](https://hl7.org/fhir/DSTU2/Substance.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Substance.code](StructureDefinition-ext-R2-Substance.code.html) |
| [Substance.description](https://hl7.org/fhir/DSTU2/Substance.html#resource) | `UseElementSameName` | [Substance.description](https://hl7.org/fhir/R5/Substance.html#resource) |
| [Substance.instance](https://hl7.org/fhir/DSTU2/Substance.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Substance.instance](StructureDefinition-ext-R2-Substance.instance.html) |
| [Substance.instance.id](https://hl7.org/fhir/DSTU2/Substance.html#resource) | `UseExtensionFromAncestor` | - |
| [Substance.instance.identifier](https://hl7.org/fhir/DSTU2/Substance.html#resource) | `UseExtensionFromAncestor` | - |
| [Substance.instance.expiry](https://hl7.org/fhir/DSTU2/Substance.html#resource) | `UseExtensionFromAncestor` | - |
| [Substance.instance.quantity](https://hl7.org/fhir/DSTU2/Substance.html#resource) | `UseExtensionFromAncestor` | - |
| [Substance.ingredient](https://hl7.org/fhir/DSTU2/Substance.html#resource) | `UseElementSameName` | [Substance.ingredient](https://hl7.org/fhir/R5/Substance.html#resource) |
| [Substance.ingredient.id](https://hl7.org/fhir/DSTU2/Substance.html#resource) | `UseElementSameName` | [Substance.ingredient.id](https://hl7.org/fhir/R5/Substance.html#resource) |
| [Substance.ingredient.quantity](https://hl7.org/fhir/DSTU2/Substance.html#resource) | `UseElementSameName` | [Substance.ingredient.quantity](https://hl7.org/fhir/R5/Substance.html#resource) |
| [Substance.ingredient.substance](https://hl7.org/fhir/DSTU2/Substance.html#resource) | `UseElementRenamed` | [Substance.ingredient.substance[x]](https://hl7.org/fhir/R5/Substance.html#resource) |
