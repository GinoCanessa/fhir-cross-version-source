### Lookup for [FHIR R2](https://hl7.org/fhir/DSTU2/) [Signature](https://hl7.org/fhir/DSTU2/Signature.html) for use in [FHIR R5](https://hl7.org/fhir/R5/)

| Source Element (FHIR R2) | Usage | Target |
| -------------- | ----- | ------ |
| [Signature.type](https://hl7.org/fhir/DSTU2/Signature.html#resource) | `UseElementSameName` | [Signature.type](https://hl7.org/fhir/R5/Signature.html#resource) |
| [Signature.when](https://hl7.org/fhir/DSTU2/Signature.html#resource) | `UseElementSameName` | [Signature.when](https://hl7.org/fhir/R5/Signature.html#resource) |
| [Signature.who[x]](https://hl7.org/fhir/DSTU2/Signature.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Signature.who](StructureDefinition-ext-R2-Signature.who.html) |
| [Signature.contentType](https://hl7.org/fhir/DSTU2/Signature.html#resource) | `UseElementRenamed` | [Signature.sigFormat](https://hl7.org/fhir/R5/Signature.html#resource) |
| [Signature.blob](https://hl7.org/fhir/DSTU2/Signature.html#resource) | `UseElementRenamed` | [Signature.data](https://hl7.org/fhir/R5/Signature.html#resource) |
