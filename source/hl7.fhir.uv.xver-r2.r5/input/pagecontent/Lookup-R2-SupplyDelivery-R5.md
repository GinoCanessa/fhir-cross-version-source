### Lookup for [FHIR R2](https://hl7.org/fhir/DSTU2/) [SupplyDelivery](https://hl7.org/fhir/DSTU2/SupplyDelivery.html) for use in [FHIR R5](https://hl7.org/fhir/R5/)

| Source Element (FHIR R2) | Usage | Target |
| -------------- | ----- | ------ |
| [SupplyDelivery.meta](https://hl7.org/fhir/DSTU2/SupplyDelivery.html#resource) | `UseElementSameName` | [SupplyDelivery.meta](https://hl7.org/fhir/R5/SupplyDelivery.html#resource) |
| [SupplyDelivery.implicitRules](https://hl7.org/fhir/DSTU2/SupplyDelivery.html#resource) | `UseElementSameName` | [SupplyDelivery.implicitRules](https://hl7.org/fhir/R5/SupplyDelivery.html#resource) |
| [SupplyDelivery.language](https://hl7.org/fhir/DSTU2/SupplyDelivery.html#resource) | `UseElementSameName` | [SupplyDelivery.language](https://hl7.org/fhir/R5/SupplyDelivery.html#resource) |
| [SupplyDelivery.text](https://hl7.org/fhir/DSTU2/SupplyDelivery.html#resource) | `UseElementSameName` | [SupplyDelivery.text](https://hl7.org/fhir/R5/SupplyDelivery.html#resource) |
| [SupplyDelivery.contained](https://hl7.org/fhir/DSTU2/SupplyDelivery.html#resource) | `UseElementSameName` | [SupplyDelivery.contained](https://hl7.org/fhir/R5/SupplyDelivery.html#resource) |
| [SupplyDelivery.identifier](https://hl7.org/fhir/DSTU2/SupplyDelivery.html#resource) | `UseElementSameName` | [SupplyDelivery.identifier](https://hl7.org/fhir/R5/SupplyDelivery.html#resource) |
| [SupplyDelivery.status](https://hl7.org/fhir/DSTU2/SupplyDelivery.html#resource) | `UseElementSameName` | [SupplyDelivery.status](https://hl7.org/fhir/R5/SupplyDelivery.html#resource) |
| [SupplyDelivery.patient](https://hl7.org/fhir/DSTU2/SupplyDelivery.html#resource) | `UseElementSameName` | [SupplyDelivery.patient](https://hl7.org/fhir/R5/SupplyDelivery.html#resource) |
| [SupplyDelivery.type](https://hl7.org/fhir/DSTU2/SupplyDelivery.html#resource) | `UseElementSameName` | [SupplyDelivery.type](https://hl7.org/fhir/R5/SupplyDelivery.html#resource) |
| [SupplyDelivery.quantity](https://hl7.org/fhir/DSTU2/SupplyDelivery.html#resource) | `UseElementRenamed` | [SupplyDelivery.suppliedItem.quantity](https://hl7.org/fhir/R5/SupplyDelivery.html#resource) |
| [SupplyDelivery.suppliedItem](https://hl7.org/fhir/DSTU2/SupplyDelivery.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-SupplyDelivery.suppliedItem](StructureDefinition-ext-R2-SupplyDelivery.suppliedItem.html) |
| [SupplyDelivery.supplier](https://hl7.org/fhir/DSTU2/SupplyDelivery.html#resource) | `UseElementSameName` | [SupplyDelivery.supplier](https://hl7.org/fhir/R5/SupplyDelivery.html#resource) |
| [SupplyDelivery.whenPrepared](https://hl7.org/fhir/DSTU2/SupplyDelivery.html#resource) | `UseOneOf` | [SupplyDelivery.extension](https://hl7.org/fhir/R5/SupplyDelivery.html#resource)<br />[SupplyDelivery.occurrence[x]](https://hl7.org/fhir/R5/SupplyDelivery.html#resource) |
| [SupplyDelivery.time](https://hl7.org/fhir/DSTU2/SupplyDelivery.html#resource) | `UseElementRenamed` | [SupplyDelivery.occurrence[x]](https://hl7.org/fhir/R5/SupplyDelivery.html#resource) |
| [SupplyDelivery.destination](https://hl7.org/fhir/DSTU2/SupplyDelivery.html#resource) | `UseElementSameName` | [SupplyDelivery.destination](https://hl7.org/fhir/R5/SupplyDelivery.html#resource) |
| [SupplyDelivery.receiver](https://hl7.org/fhir/DSTU2/SupplyDelivery.html#resource) | `UseElementSameName` | [SupplyDelivery.receiver](https://hl7.org/fhir/R5/SupplyDelivery.html#resource) |
