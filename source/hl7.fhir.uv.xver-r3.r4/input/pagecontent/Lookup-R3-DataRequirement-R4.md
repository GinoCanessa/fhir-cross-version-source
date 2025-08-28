### Lookup for [FHIR R3](https://hl7.org/fhir/STU3/) [DataRequirement](https://hl7.org/fhir/STU3/DataRequirement.html) for use in [FHIR R4](https://hl7.org/fhir/R4/)

| Source Element (FHIR R3) | Usage | Target |
| -------------- | ----- | ------ |
| [DataRequirement.type](https://hl7.org/fhir/STU3/DataRequirement.html#resource) | `UseElementSameName` | [DataRequirement.type](https://hl7.org/fhir/R4/DataRequirement.html#resource) |
| [DataRequirement.profile](https://hl7.org/fhir/STU3/DataRequirement.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-DataRequirement.profile](StructureDefinition-ext-R3-DataRequirement.profile.html) |
| [DataRequirement.mustSupport](https://hl7.org/fhir/STU3/DataRequirement.html#resource) | `UseElementSameName` | [DataRequirement.mustSupport](https://hl7.org/fhir/R4/DataRequirement.html#resource) |
| [DataRequirement.codeFilter](https://hl7.org/fhir/STU3/DataRequirement.html#resource) | `UseElementSameName` | [DataRequirement.codeFilter](https://hl7.org/fhir/R4/DataRequirement.html#resource) |
| [DataRequirement.codeFilter.path](https://hl7.org/fhir/STU3/DataRequirement.html#resource) | `UseElementSameName` | [DataRequirement.codeFilter.path](https://hl7.org/fhir/R4/DataRequirement.html#resource) |
| [DataRequirement.codeFilter.valueSet[x]](https://hl7.org/fhir/STU3/DataRequirement.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-DataRequirement.codeFilter.valueSet](StructureDefinition-ext-R3-DataRequirement.co.valueSet.html) |
| [DataRequirement.codeFilter.valueCode](https://hl7.org/fhir/STU3/DataRequirement.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-DataRequirement.codeFilter.valueCode](StructureDefinition-ext-R3-DataRequirement.co.valueCode.html) |
| [DataRequirement.codeFilter.valueCoding](https://hl7.org/fhir/STU3/DataRequirement.html#resource) | `UseElementRenamed` | [DataRequirement.codeFilter.code](https://hl7.org/fhir/R4/DataRequirement.html#resource) |
| [DataRequirement.codeFilter.valueCodeableConcept](https://hl7.org/fhir/STU3/DataRequirement.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-DataRequirement.codeFilter.valueCodeableConcept](StructureDefinition-ext-R3-DataRequirement.co.valueCodeableConcept.html) |
| [DataRequirement.dateFilter](https://hl7.org/fhir/STU3/DataRequirement.html#resource) | `UseElementSameName` | [DataRequirement.dateFilter](https://hl7.org/fhir/R4/DataRequirement.html#resource) |
| [DataRequirement.dateFilter.path](https://hl7.org/fhir/STU3/DataRequirement.html#resource) | `UseElementSameName` | [DataRequirement.dateFilter.path](https://hl7.org/fhir/R4/DataRequirement.html#resource) |
| [DataRequirement.dateFilter.value[x]](https://hl7.org/fhir/STU3/DataRequirement.html#resource) | `UseElementSameName` | [DataRequirement.dateFilter.value[x]](https://hl7.org/fhir/R4/DataRequirement.html#resource) |
