### Lookup for [FHIR R3](https://hl7.org/fhir/STU3/) [ChargeItem](https://hl7.org/fhir/STU3/ChargeItem.html) for use in [FHIR R4](https://hl7.org/fhir/R4/)

| Source Element (FHIR R3) | Usage | Target |
| -------------- | ----- | ------ |
| [ChargeItem.meta](https://hl7.org/fhir/STU3/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.meta](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.implicitRules](https://hl7.org/fhir/STU3/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.implicitRules](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.language](https://hl7.org/fhir/STU3/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.language](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.text](https://hl7.org/fhir/STU3/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.text](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.contained](https://hl7.org/fhir/STU3/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.contained](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.identifier](https://hl7.org/fhir/STU3/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.identifier](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.definition](https://hl7.org/fhir/STU3/ChargeItem.html#resource) | `UseElementRenamed` | [ChargeItem.definitionUri](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.status](https://hl7.org/fhir/STU3/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.status](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.partOf](https://hl7.org/fhir/STU3/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.partOf](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.code](https://hl7.org/fhir/STU3/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.code](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.subject](https://hl7.org/fhir/STU3/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.subject](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.context](https://hl7.org/fhir/STU3/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.context](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.occurrence[x]](https://hl7.org/fhir/STU3/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.occurrence[x]](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.participant](https://hl7.org/fhir/STU3/ChargeItem.html#resource) | `UseElementRenamed` | [ChargeItem.performer](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.participant.role](https://hl7.org/fhir/STU3/ChargeItem.html#resource) | `UseElementRenamed` | [ChargeItem.performer.function](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.participant.actor](https://hl7.org/fhir/STU3/ChargeItem.html#resource) | `UseElementRenamed` | [ChargeItem.performer.actor](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.performingOrganization](https://hl7.org/fhir/STU3/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.performingOrganization](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.requestingOrganization](https://hl7.org/fhir/STU3/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.requestingOrganization](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.quantity](https://hl7.org/fhir/STU3/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.quantity](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.bodysite](https://hl7.org/fhir/STU3/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.bodysite](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.factorOverride](https://hl7.org/fhir/STU3/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.factorOverride](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.priceOverride](https://hl7.org/fhir/STU3/ChargeItem.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-ChargeItem.priceOverride](StructureDefinition-ext-R3-ChargeItem.priceOverride.html) |
| [ChargeItem.overrideReason](https://hl7.org/fhir/STU3/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.overrideReason](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.enterer](https://hl7.org/fhir/STU3/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.enterer](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.enteredDate](https://hl7.org/fhir/STU3/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.enteredDate](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.reason](https://hl7.org/fhir/STU3/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.reason](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.service](https://hl7.org/fhir/STU3/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.service](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.account](https://hl7.org/fhir/STU3/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.account](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.note](https://hl7.org/fhir/STU3/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.note](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.supportingInformation](https://hl7.org/fhir/STU3/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.supportingInformation](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
