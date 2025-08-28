### Lookup for [FHIR R3](https://hl7.org/fhir/STU3/) [Specimen](https://hl7.org/fhir/STU3/Specimen.html) for use in [FHIR R5](https://hl7.org/fhir/R5/)

| Source Element (FHIR R3) | Usage | Target |
| -------------- | ----- | ------ |
| [Specimen.meta](https://hl7.org/fhir/STU3/Specimen.html#resource) | `UseElementSameName` | [Specimen.meta](https://hl7.org/fhir/R5/Specimen.html#resource) |
| [Specimen.implicitRules](https://hl7.org/fhir/STU3/Specimen.html#resource) | `UseElementSameName` | [Specimen.implicitRules](https://hl7.org/fhir/R5/Specimen.html#resource) |
| [Specimen.language](https://hl7.org/fhir/STU3/Specimen.html#resource) | `UseElementSameName` | [Specimen.language](https://hl7.org/fhir/R5/Specimen.html#resource) |
| [Specimen.text](https://hl7.org/fhir/STU3/Specimen.html#resource) | `UseElementSameName` | [Specimen.text](https://hl7.org/fhir/R5/Specimen.html#resource) |
| [Specimen.contained](https://hl7.org/fhir/STU3/Specimen.html#resource) | `UseElementSameName` | [Specimen.contained](https://hl7.org/fhir/R5/Specimen.html#resource) |
| [Specimen.identifier](https://hl7.org/fhir/STU3/Specimen.html#resource) | `UseElementSameName` | [Specimen.identifier](https://hl7.org/fhir/R5/Specimen.html#resource) |
| [Specimen.accessionIdentifier](https://hl7.org/fhir/STU3/Specimen.html#resource) | `UseElementSameName` | [Specimen.accessionIdentifier](https://hl7.org/fhir/R5/Specimen.html#resource) |
| [Specimen.status](https://hl7.org/fhir/STU3/Specimen.html#resource) | `UseElementSameName` | [Specimen.status](https://hl7.org/fhir/R5/Specimen.html#resource) |
| [Specimen.type](https://hl7.org/fhir/STU3/Specimen.html#resource) | `UseElementSameName` | [Specimen.type](https://hl7.org/fhir/R5/Specimen.html#resource) |
| [Specimen.subject](https://hl7.org/fhir/STU3/Specimen.html#resource) | `UseElementSameName` | [Specimen.subject](https://hl7.org/fhir/R5/Specimen.html#resource) |
| [Specimen.receivedTime](https://hl7.org/fhir/STU3/Specimen.html#resource) | `UseElementSameName` | [Specimen.receivedTime](https://hl7.org/fhir/R5/Specimen.html#resource) |
| [Specimen.parent](https://hl7.org/fhir/STU3/Specimen.html#resource) | `UseElementSameName` | [Specimen.parent](https://hl7.org/fhir/R5/Specimen.html#resource) |
| [Specimen.request](https://hl7.org/fhir/STU3/Specimen.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Specimen.request](StructureDefinition-ext-R3-Specimen.request.html) |
| [Specimen.collection](https://hl7.org/fhir/STU3/Specimen.html#resource) | `UseElementSameName` | [Specimen.collection](https://hl7.org/fhir/R5/Specimen.html#resource) |
| [Specimen.collection.collector](https://hl7.org/fhir/STU3/Specimen.html#resource) | `UseElementSameName` | [Specimen.collection.collector](https://hl7.org/fhir/R5/Specimen.html#resource) |
| [Specimen.collection.collected[x]](https://hl7.org/fhir/STU3/Specimen.html#resource) | `UseElementSameName` | [Specimen.collection.collected[x]](https://hl7.org/fhir/R5/Specimen.html#resource) |
| [Specimen.collection.quantity](https://hl7.org/fhir/STU3/Specimen.html#resource) | `UseElementSameName` | [Specimen.collection.quantity](https://hl7.org/fhir/R5/Specimen.html#resource) |
| [Specimen.collection.method](https://hl7.org/fhir/STU3/Specimen.html#resource) | `UseElementSameName` | [Specimen.collection.method](https://hl7.org/fhir/R5/Specimen.html#resource) |
| [Specimen.collection.bodySite](https://hl7.org/fhir/STU3/Specimen.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Specimen.collection.bodySite](StructureDefinition-ext-R3-Specimen.co.bodySite.html) |
| [Specimen.processing](https://hl7.org/fhir/STU3/Specimen.html#resource) | `UseElementSameName` | [Specimen.processing](https://hl7.org/fhir/R5/Specimen.html#resource) |
| [Specimen.processing.description](https://hl7.org/fhir/STU3/Specimen.html#resource) | `UseElementSameName` | [Specimen.processing.description](https://hl7.org/fhir/R5/Specimen.html#resource) |
| [Specimen.processing.procedure](https://hl7.org/fhir/STU3/Specimen.html#resource) | `UseElementRenamed` | [Specimen.processing.method](https://hl7.org/fhir/R5/Specimen.html#resource) |
| [Specimen.processing.additive](https://hl7.org/fhir/STU3/Specimen.html#resource) | `UseElementSameName` | [Specimen.processing.additive](https://hl7.org/fhir/R5/Specimen.html#resource) |
| [Specimen.processing.time[x]](https://hl7.org/fhir/STU3/Specimen.html#resource) | `UseElementSameName` | [Specimen.processing.time[x]](https://hl7.org/fhir/R5/Specimen.html#resource) |
| [Specimen.container](https://hl7.org/fhir/STU3/Specimen.html#resource) | `UseElementSameName` | [Specimen.container](https://hl7.org/fhir/R5/Specimen.html#resource) |
| [Specimen.container.identifier](https://hl7.org/fhir/STU3/Specimen.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Specimen.container.identifier](StructureDefinition-ext-R3-Specimen.co.identifier.html) |
| [Specimen.container.description](https://hl7.org/fhir/STU3/Specimen.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Specimen.container.description](StructureDefinition-ext-R3-Specimen.co.description.html) |
| [Specimen.container.type](https://hl7.org/fhir/STU3/Specimen.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Specimen.container.type](StructureDefinition-ext-R3-Specimen.co.type.html) |
| [Specimen.container.capacity](https://hl7.org/fhir/STU3/Specimen.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Specimen.container.capacity](StructureDefinition-ext-R3-Specimen.co.capacity.html) |
| [Specimen.container.specimenQuantity](https://hl7.org/fhir/STU3/Specimen.html#resource) | `UseElementSameName` | [Specimen.container.specimenQuantity](https://hl7.org/fhir/R5/Specimen.html#resource) |
| [Specimen.container.additive[x]](https://hl7.org/fhir/STU3/Specimen.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Specimen.container.additive](StructureDefinition-ext-R3-Specimen.co.additive.html) |
| [Specimen.note](https://hl7.org/fhir/STU3/Specimen.html#resource) | `UseElementSameName` | [Specimen.note](https://hl7.org/fhir/R5/Specimen.html#resource) |
