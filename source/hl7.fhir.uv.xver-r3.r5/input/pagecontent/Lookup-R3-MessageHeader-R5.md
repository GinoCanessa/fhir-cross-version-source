### Lookup for [FHIR R3](https://hl7.org/fhir/STU3/) [MessageHeader](https://hl7.org/fhir/STU3/MessageHeader.html) for use in [FHIR R5](https://hl7.org/fhir/R5/)

| Source Element (FHIR R3) | Usage | Target |
| -------------- | ----- | ------ |
| [MessageHeader.meta](https://hl7.org/fhir/STU3/MessageHeader.html#resource) | `UseElementSameName` | [MessageHeader.meta](https://hl7.org/fhir/R5/MessageHeader.html#resource) |
| [MessageHeader.implicitRules](https://hl7.org/fhir/STU3/MessageHeader.html#resource) | `UseElementSameName` | [MessageHeader.implicitRules](https://hl7.org/fhir/R5/MessageHeader.html#resource) |
| [MessageHeader.language](https://hl7.org/fhir/STU3/MessageHeader.html#resource) | `UseElementSameName` | [MessageHeader.language](https://hl7.org/fhir/R5/MessageHeader.html#resource) |
| [MessageHeader.text](https://hl7.org/fhir/STU3/MessageHeader.html#resource) | `UseElementSameName` | [MessageHeader.text](https://hl7.org/fhir/R5/MessageHeader.html#resource) |
| [MessageHeader.contained](https://hl7.org/fhir/STU3/MessageHeader.html#resource) | `UseElementSameName` | [MessageHeader.contained](https://hl7.org/fhir/R5/MessageHeader.html#resource) |
| [MessageHeader.event](https://hl7.org/fhir/STU3/MessageHeader.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-MessageHeader.event](StructureDefinition-ext-R3-MessageHeader.event.html) |
| [MessageHeader.destination](https://hl7.org/fhir/STU3/MessageHeader.html#resource) | `UseElementSameName` | [MessageHeader.destination](https://hl7.org/fhir/R5/MessageHeader.html#resource) |
| [MessageHeader.destination.name](https://hl7.org/fhir/STU3/MessageHeader.html#resource) | `UseElementSameName` | [MessageHeader.destination.name](https://hl7.org/fhir/R5/MessageHeader.html#resource) |
| [MessageHeader.destination.target](https://hl7.org/fhir/STU3/MessageHeader.html#resource) | `UseElementSameName` | [MessageHeader.destination.target](https://hl7.org/fhir/R5/MessageHeader.html#resource) |
| [MessageHeader.destination.endpoint](https://hl7.org/fhir/STU3/MessageHeader.html#resource) | `UseElementRenamed` | [MessageHeader.destination.endpoint[x]](https://hl7.org/fhir/R5/MessageHeader.html#resource) |
| [MessageHeader.receiver](https://hl7.org/fhir/STU3/MessageHeader.html#resource) | `UseElementRenamed` | [MessageHeader.destination.receiver](https://hl7.org/fhir/R5/MessageHeader.html#resource) |
| [MessageHeader.sender](https://hl7.org/fhir/STU3/MessageHeader.html#resource) | `UseElementSameName` | [MessageHeader.sender](https://hl7.org/fhir/R5/MessageHeader.html#resource) |
| [MessageHeader.timestamp](https://hl7.org/fhir/STU3/MessageHeader.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-MessageHeader.timestamp](StructureDefinition-ext-R3-MessageHeader.timestamp.html) |
| [MessageHeader.enterer](https://hl7.org/fhir/STU3/MessageHeader.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-MessageHeader.enterer](StructureDefinition-ext-R3-MessageHeader.enterer.html) |
| [MessageHeader.author](https://hl7.org/fhir/STU3/MessageHeader.html#resource) | `UseElementSameName` | [MessageHeader.author](https://hl7.org/fhir/R5/MessageHeader.html#resource) |
| [MessageHeader.source](https://hl7.org/fhir/STU3/MessageHeader.html#resource) | `UseElementSameName` | [MessageHeader.source](https://hl7.org/fhir/R5/MessageHeader.html#resource) |
| [MessageHeader.source.name](https://hl7.org/fhir/STU3/MessageHeader.html#resource) | `UseElementSameName` | [MessageHeader.source.name](https://hl7.org/fhir/R5/MessageHeader.html#resource) |
| [MessageHeader.source.software](https://hl7.org/fhir/STU3/MessageHeader.html#resource) | `UseElementSameName` | [MessageHeader.source.software](https://hl7.org/fhir/R5/MessageHeader.html#resource) |
| [MessageHeader.source.version](https://hl7.org/fhir/STU3/MessageHeader.html#resource) | `UseElementSameName` | [MessageHeader.source.version](https://hl7.org/fhir/R5/MessageHeader.html#resource) |
| [MessageHeader.source.contact](https://hl7.org/fhir/STU3/MessageHeader.html#resource) | `UseElementSameName` | [MessageHeader.source.contact](https://hl7.org/fhir/R5/MessageHeader.html#resource) |
| [MessageHeader.source.endpoint](https://hl7.org/fhir/STU3/MessageHeader.html#resource) | `UseElementRenamed` | [MessageHeader.source.endpoint[x]](https://hl7.org/fhir/R5/MessageHeader.html#resource) |
| [MessageHeader.responsible](https://hl7.org/fhir/STU3/MessageHeader.html#resource) | `UseElementSameName` | [MessageHeader.responsible](https://hl7.org/fhir/R5/MessageHeader.html#resource) |
| [MessageHeader.reason](https://hl7.org/fhir/STU3/MessageHeader.html#resource) | `UseElementSameName` | [MessageHeader.reason](https://hl7.org/fhir/R5/MessageHeader.html#resource) |
| [MessageHeader.response](https://hl7.org/fhir/STU3/MessageHeader.html#resource) | `UseElementSameName` | [MessageHeader.response](https://hl7.org/fhir/R5/MessageHeader.html#resource) |
| [MessageHeader.response.identifier](https://hl7.org/fhir/STU3/MessageHeader.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-MessageHeader.response.identifier](StructureDefinition-ext-R3-MessageHeader.re.identifier.html) |
| [MessageHeader.response.code](https://hl7.org/fhir/STU3/MessageHeader.html#resource) | `UseElementSameName` | [MessageHeader.response.code](https://hl7.org/fhir/R5/MessageHeader.html#resource) |
| [MessageHeader.response.details](https://hl7.org/fhir/STU3/MessageHeader.html#resource) | `UseElementSameName` | [MessageHeader.response.details](https://hl7.org/fhir/R5/MessageHeader.html#resource) |
| [MessageHeader.focus](https://hl7.org/fhir/STU3/MessageHeader.html#resource) | `UseElementSameName` | [MessageHeader.focus](https://hl7.org/fhir/R5/MessageHeader.html#resource) |
