### Lookup for [FHIR R3](https://hl7.org/fhir/STU3/) [Money](https://hl7.org/fhir/STU3/Money.html) for use in [FHIR R4](https://hl7.org/fhir/R4/)

| Source Element (FHIR R3) | Usage | Target |
| -------------- | ----- | ------ |
| [Money.value](https://hl7.org/fhir/STU3/Money.html#resource) | `UseElementSameName` | [Money.value](https://hl7.org/fhir/R4/Money.html#resource) |
| [Money.comparator](https://hl7.org/fhir/STU3/Money.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Money.comparator](StructureDefinition-ext-R3-Money.comparator.html) |
| [Money.unit](https://hl7.org/fhir/STU3/Money.html#resource) | `UseElementRenamed` | [Money.currency](https://hl7.org/fhir/R4/Money.html#resource) |
| [Money.system](https://hl7.org/fhir/STU3/Money.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Money.system](StructureDefinition-ext-R3-Money.system.html) |
| [Money.code](https://hl7.org/fhir/STU3/Money.html#resource) | `UseElementRenamed` | [Money.currency](https://hl7.org/fhir/R4/Money.html#resource) |
