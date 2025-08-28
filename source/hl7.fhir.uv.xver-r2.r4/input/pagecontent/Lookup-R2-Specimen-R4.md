### Lookup for [FHIR R2](https://hl7.org/fhir/DSTU2/) [Specimen](https://hl7.org/fhir/DSTU2/Specimen.html) for use in [FHIR R4](https://hl7.org/fhir/R4/)

| Source Element (FHIR R2) | Usage | Target |
| -------------- | ----- | ------ |
| [Specimen.meta](https://hl7.org/fhir/DSTU2/Specimen.html#resource) | `UseElementSameName` | [Specimen.meta](https://hl7.org/fhir/R4/Specimen.html#resource) |
| [Specimen.implicitRules](https://hl7.org/fhir/DSTU2/Specimen.html#resource) | `UseElementSameName` | [Specimen.implicitRules](https://hl7.org/fhir/R4/Specimen.html#resource) |
| [Specimen.language](https://hl7.org/fhir/DSTU2/Specimen.html#resource) | `UseElementSameName` | [Specimen.language](https://hl7.org/fhir/R4/Specimen.html#resource) |
| [Specimen.text](https://hl7.org/fhir/DSTU2/Specimen.html#resource) | `UseElementSameName` | [Specimen.text](https://hl7.org/fhir/R4/Specimen.html#resource) |
| [Specimen.contained](https://hl7.org/fhir/DSTU2/Specimen.html#resource) | `UseElementSameName` | [Specimen.contained](https://hl7.org/fhir/R4/Specimen.html#resource) |
| [Specimen.identifier](https://hl7.org/fhir/DSTU2/Specimen.html#resource) | `UseElementSameName` | [Specimen.identifier](https://hl7.org/fhir/R4/Specimen.html#resource) |
| [Specimen.status](https://hl7.org/fhir/DSTU2/Specimen.html#resource) | `UseElementSameName` | [Specimen.status](https://hl7.org/fhir/R4/Specimen.html#resource) |
| [Specimen.type](https://hl7.org/fhir/DSTU2/Specimen.html#resource) | `UseElementSameName` | [Specimen.type](https://hl7.org/fhir/R4/Specimen.html#resource) |
| [Specimen.parent](https://hl7.org/fhir/DSTU2/Specimen.html#resource) | `UseElementSameName` | [Specimen.parent](https://hl7.org/fhir/R4/Specimen.html#resource) |
| [Specimen.subject](https://hl7.org/fhir/DSTU2/Specimen.html#resource) | `UseElementSameName` | [Specimen.subject](https://hl7.org/fhir/R4/Specimen.html#resource) |
| [Specimen.accessionIdentifier](https://hl7.org/fhir/DSTU2/Specimen.html#resource) | `UseElementSameName` | [Specimen.accessionIdentifier](https://hl7.org/fhir/R4/Specimen.html#resource) |
| [Specimen.receivedTime](https://hl7.org/fhir/DSTU2/Specimen.html#resource) | `UseElementSameName` | [Specimen.receivedTime](https://hl7.org/fhir/R4/Specimen.html#resource) |
| [Specimen.collection](https://hl7.org/fhir/DSTU2/Specimen.html#resource) | `UseElementSameName` | [Specimen.collection](https://hl7.org/fhir/R4/Specimen.html#resource) |
| [Specimen.collection.id](https://hl7.org/fhir/DSTU2/Specimen.html#resource) | `UseElementSameName` | [Specimen.collection.id](https://hl7.org/fhir/R4/Specimen.html#resource) |
| [Specimen.collection.collector](https://hl7.org/fhir/DSTU2/Specimen.html#resource) | `UseElementSameName` | [Specimen.collection.collector](https://hl7.org/fhir/R4/Specimen.html#resource) |
| [Specimen.collection.comment](https://hl7.org/fhir/DSTU2/Specimen.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Specimen.collection.comment](StructureDefinition-ext-R2-Specimen.co.comment.html) |
| [Specimen.collection.collected[x]](https://hl7.org/fhir/DSTU2/Specimen.html#resource) | `UseElementSameName` | [Specimen.collection.collected[x]](https://hl7.org/fhir/R4/Specimen.html#resource) |
| [Specimen.collection.quantity](https://hl7.org/fhir/DSTU2/Specimen.html#resource) | `UseElementSameName` | [Specimen.collection.quantity](https://hl7.org/fhir/R4/Specimen.html#resource) |
| [Specimen.collection.method](https://hl7.org/fhir/DSTU2/Specimen.html#resource) | `UseElementSameName` | [Specimen.collection.method](https://hl7.org/fhir/R4/Specimen.html#resource) |
| [Specimen.collection.bodySite](https://hl7.org/fhir/DSTU2/Specimen.html#resource) | `UseElementSameName` | [Specimen.collection.bodySite](https://hl7.org/fhir/R4/Specimen.html#resource) |
| [Specimen.treatment](https://hl7.org/fhir/DSTU2/Specimen.html#resource) | `UseElementRenamed` | [Specimen.processing](https://hl7.org/fhir/R4/Specimen.html#resource) |
| [Specimen.treatment.id](https://hl7.org/fhir/DSTU2/Specimen.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Specimen.treatment.id](StructureDefinition-ext-R2-Specimen.tr.id.html) |
| [Specimen.treatment.description](https://hl7.org/fhir/DSTU2/Specimen.html#resource) | `UseElementRenamed` | [Specimen.processing.description](https://hl7.org/fhir/R4/Specimen.html#resource) |
| [Specimen.treatment.procedure](https://hl7.org/fhir/DSTU2/Specimen.html#resource) | `UseElementRenamed` | [Specimen.processing.procedure](https://hl7.org/fhir/R4/Specimen.html#resource) |
| [Specimen.treatment.additive](https://hl7.org/fhir/DSTU2/Specimen.html#resource) | `UseElementRenamed` | [Specimen.processing.additive](https://hl7.org/fhir/R4/Specimen.html#resource) |
| [Specimen.container](https://hl7.org/fhir/DSTU2/Specimen.html#resource) | `UseElementSameName` | [Specimen.container](https://hl7.org/fhir/R4/Specimen.html#resource) |
| [Specimen.container.id](https://hl7.org/fhir/DSTU2/Specimen.html#resource) | `UseElementSameName` | [Specimen.container.id](https://hl7.org/fhir/R4/Specimen.html#resource) |
| [Specimen.container.identifier](https://hl7.org/fhir/DSTU2/Specimen.html#resource) | `UseElementSameName` | [Specimen.container.identifier](https://hl7.org/fhir/R4/Specimen.html#resource) |
| [Specimen.container.description](https://hl7.org/fhir/DSTU2/Specimen.html#resource) | `UseElementSameName` | [Specimen.container.description](https://hl7.org/fhir/R4/Specimen.html#resource) |
| [Specimen.container.type](https://hl7.org/fhir/DSTU2/Specimen.html#resource) | `UseElementSameName` | [Specimen.container.type](https://hl7.org/fhir/R4/Specimen.html#resource) |
| [Specimen.container.capacity](https://hl7.org/fhir/DSTU2/Specimen.html#resource) | `UseElementSameName` | [Specimen.container.capacity](https://hl7.org/fhir/R4/Specimen.html#resource) |
| [Specimen.container.specimenQuantity](https://hl7.org/fhir/DSTU2/Specimen.html#resource) | `UseElementSameName` | [Specimen.container.specimenQuantity](https://hl7.org/fhir/R4/Specimen.html#resource) |
| [Specimen.container.additive[x]](https://hl7.org/fhir/DSTU2/Specimen.html#resource) | `UseElementSameName` | [Specimen.container.additive[x]](https://hl7.org/fhir/R4/Specimen.html#resource) |
