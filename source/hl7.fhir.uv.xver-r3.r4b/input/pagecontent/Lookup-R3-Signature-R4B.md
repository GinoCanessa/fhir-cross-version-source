### Lookup for [FHIR R3](https://hl7.org/fhir/STU3/) [Signature](https://hl7.org/fhir/STU3/Signature.html) for use in [FHIR R4B](https://hl7.org/fhir/R4B/)

| Source Element (FHIR R3) | Usage | Target |
| -------------- | ----- | ------ |
| [Signature.type](https://hl7.org/fhir/STU3/Signature.html#resource) | `UseElementSameName` | [Signature.type](https://hl7.org/fhir/R4B/Signature.html#resource) |
| [Signature.when](https://hl7.org/fhir/STU3/Signature.html#resource) | `UseElementSameName` | [Signature.when](https://hl7.org/fhir/R4B/Signature.html#resource) |
| [Signature.who[x]](https://hl7.org/fhir/STU3/Signature.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Signature.who](StructureDefinition-ext-R3-Signature.who.html) |
| [Signature.onBehalfOf[x]](https://hl7.org/fhir/STU3/Signature.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Signature.onBehalfOf](StructureDefinition-ext-R3-Signature.onBehalfOf.html) |
| [Signature.contentType](https://hl7.org/fhir/STU3/Signature.html#resource) | `UseElementRenamed` | [Signature.sigFormat](https://hl7.org/fhir/R4B/Signature.html#resource) |
| [Signature.blob](https://hl7.org/fhir/STU3/Signature.html#resource) | `UseElementRenamed` | [Signature.data](https://hl7.org/fhir/R4B/Signature.html#resource) |
