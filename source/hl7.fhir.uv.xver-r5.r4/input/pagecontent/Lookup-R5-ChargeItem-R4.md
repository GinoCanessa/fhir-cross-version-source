### Lookup for [FHIR R5](https://hl7.org/fhir/R5/) [ChargeItem](https://hl7.org/fhir/R5/ChargeItem.html) for use in [FHIR R4](https://hl7.org/fhir/R4/)

| Source Element (FHIR R5) | Usage | Target |
| -------------- | ----- | ------ |
| [ChargeItem.meta](https://hl7.org/fhir/R5/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.meta](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.implicitRules](https://hl7.org/fhir/R5/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.implicitRules](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.language](https://hl7.org/fhir/R5/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.language](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.text](https://hl7.org/fhir/R5/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.text](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.contained](https://hl7.org/fhir/R5/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.contained](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.identifier](https://hl7.org/fhir/R5/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.identifier](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.definitionUri](https://hl7.org/fhir/R5/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.definitionUri](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.definitionCanonical](https://hl7.org/fhir/R5/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.definitionCanonical](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.status](https://hl7.org/fhir/R5/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.status](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.partOf](https://hl7.org/fhir/R5/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.partOf](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.code](https://hl7.org/fhir/R5/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.code](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.subject](https://hl7.org/fhir/R5/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.subject](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.encounter](https://hl7.org/fhir/R5/ChargeItem.html#resource) | `UseElementRenamed` | [ChargeItem.context](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.occurrence[x]](https://hl7.org/fhir/R5/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.occurrence[x]](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.performer](https://hl7.org/fhir/R5/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.performer](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.performer.function](https://hl7.org/fhir/R5/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.performer.function](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.performer.actor](https://hl7.org/fhir/R5/ChargeItem.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-ChargeItem.performer.actor](StructureDefinition-ext-R5-ChargeItem.pe.actor.html) |
| [ChargeItem.performingOrganization](https://hl7.org/fhir/R5/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.performingOrganization](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.requestingOrganization](https://hl7.org/fhir/R5/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.requestingOrganization](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.costCenter](https://hl7.org/fhir/R5/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.costCenter](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.quantity](https://hl7.org/fhir/R5/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.quantity](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.bodysite](https://hl7.org/fhir/R5/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.bodysite](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.unitPriceComponent](https://hl7.org/fhir/R5/ChargeItem.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-ChargeItem.unitPriceComponent](StructureDefinition-ext-R5-ChargeItem.unitPriceComponent.html) |
| [ChargeItem.totalPriceComponent](https://hl7.org/fhir/R5/ChargeItem.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-ChargeItem.totalPriceComponent](StructureDefinition-ext-R5-ChargeItem.totalPriceComponent.html) |
| [ChargeItem.overrideReason](https://hl7.org/fhir/R5/ChargeItem.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-ChargeItem.overrideReason](StructureDefinition-ext-R5-ChargeItem.overrideReason.html) |
| [ChargeItem.enterer](https://hl7.org/fhir/R5/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.enterer](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.enteredDate](https://hl7.org/fhir/R5/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.enteredDate](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.reason](https://hl7.org/fhir/R5/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.reason](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.service](https://hl7.org/fhir/R5/ChargeItem.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-ChargeItem.service](StructureDefinition-ext-R5-ChargeItem.service.html) |
| [ChargeItem.product](https://hl7.org/fhir/R5/ChargeItem.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-ChargeItem.product](StructureDefinition-ext-R5-ChargeItem.product.html) |
| [ChargeItem.account](https://hl7.org/fhir/R5/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.account](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.note](https://hl7.org/fhir/R5/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.note](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
| [ChargeItem.supportingInformation](https://hl7.org/fhir/R5/ChargeItem.html#resource) | `UseElementSameName` | [ChargeItem.supportingInformation](https://hl7.org/fhir/R4/ChargeItem.html#resource) |
