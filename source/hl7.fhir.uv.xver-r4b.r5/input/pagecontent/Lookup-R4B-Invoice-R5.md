### Lookup for [FHIR R4B](https://hl7.org/fhir/R4B/) [Invoice](https://hl7.org/fhir/R4B/Invoice.html) for use in [FHIR R5](https://hl7.org/fhir/R5/)

| Source Element (FHIR R4B) | Usage | Target |
| -------------- | ----- | ------ |
| [Invoice.meta](https://hl7.org/fhir/R4B/Invoice.html#resource) | `UseElementSameName` | [Invoice.meta](https://hl7.org/fhir/R5/Invoice.html#resource) |
| [Invoice.implicitRules](https://hl7.org/fhir/R4B/Invoice.html#resource) | `UseElementSameName` | [Invoice.implicitRules](https://hl7.org/fhir/R5/Invoice.html#resource) |
| [Invoice.language](https://hl7.org/fhir/R4B/Invoice.html#resource) | `UseElementSameName` | [Invoice.language](https://hl7.org/fhir/R5/Invoice.html#resource) |
| [Invoice.text](https://hl7.org/fhir/R4B/Invoice.html#resource) | `UseElementSameName` | [Invoice.text](https://hl7.org/fhir/R5/Invoice.html#resource) |
| [Invoice.contained](https://hl7.org/fhir/R4B/Invoice.html#resource) | `UseElementSameName` | [Invoice.contained](https://hl7.org/fhir/R5/Invoice.html#resource) |
| [Invoice.identifier](https://hl7.org/fhir/R4B/Invoice.html#resource) | `UseElementSameName` | [Invoice.identifier](https://hl7.org/fhir/R5/Invoice.html#resource) |
| [Invoice.status](https://hl7.org/fhir/R4B/Invoice.html#resource) | `UseElementSameName` | [Invoice.status](https://hl7.org/fhir/R5/Invoice.html#resource) |
| [Invoice.cancelledReason](https://hl7.org/fhir/R4B/Invoice.html#resource) | `UseElementSameName` | [Invoice.cancelledReason](https://hl7.org/fhir/R5/Invoice.html#resource) |
| [Invoice.type](https://hl7.org/fhir/R4B/Invoice.html#resource) | `UseElementSameName` | [Invoice.type](https://hl7.org/fhir/R5/Invoice.html#resource) |
| [Invoice.subject](https://hl7.org/fhir/R4B/Invoice.html#resource) | `UseElementSameName` | [Invoice.subject](https://hl7.org/fhir/R5/Invoice.html#resource) |
| [Invoice.recipient](https://hl7.org/fhir/R4B/Invoice.html#resource) | `UseElementSameName` | [Invoice.recipient](https://hl7.org/fhir/R5/Invoice.html#resource) |
| [Invoice.date](https://hl7.org/fhir/R4B/Invoice.html#resource) | `UseElementSameName` | [Invoice.date](https://hl7.org/fhir/R5/Invoice.html#resource) |
| [Invoice.participant](https://hl7.org/fhir/R4B/Invoice.html#resource) | `UseElementSameName` | [Invoice.participant](https://hl7.org/fhir/R5/Invoice.html#resource) |
| [Invoice.participant.role](https://hl7.org/fhir/R4B/Invoice.html#resource) | `UseElementSameName` | [Invoice.participant.role](https://hl7.org/fhir/R5/Invoice.html#resource) |
| [Invoice.participant.actor](https://hl7.org/fhir/R4B/Invoice.html#resource) | `UseElementSameName` | [Invoice.participant.actor](https://hl7.org/fhir/R5/Invoice.html#resource) |
| [Invoice.issuer](https://hl7.org/fhir/R4B/Invoice.html#resource) | `UseElementSameName` | [Invoice.issuer](https://hl7.org/fhir/R5/Invoice.html#resource) |
| [Invoice.account](https://hl7.org/fhir/R4B/Invoice.html#resource) | `UseElementSameName` | [Invoice.account](https://hl7.org/fhir/R5/Invoice.html#resource) |
| [Invoice.lineItem](https://hl7.org/fhir/R4B/Invoice.html#resource) | `UseElementSameName` | [Invoice.lineItem](https://hl7.org/fhir/R5/Invoice.html#resource) |
| [Invoice.lineItem.sequence](https://hl7.org/fhir/R4B/Invoice.html#resource) | `UseElementSameName` | [Invoice.lineItem.sequence](https://hl7.org/fhir/R5/Invoice.html#resource) |
| [Invoice.lineItem.chargeItem[x]](https://hl7.org/fhir/R4B/Invoice.html#resource) | `UseElementSameName` | [Invoice.lineItem.chargeItem[x]](https://hl7.org/fhir/R5/Invoice.html#resource) |
| [Invoice.lineItem.priceComponent](https://hl7.org/fhir/R4B/Invoice.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.3/StructureDefinition/extension-Invoice.lineItem.priceComponent](StructureDefinition-ext-R4B-Invoice.li.priceComponent.html) |
| [Invoice.lineItem.priceComponent.type](https://hl7.org/fhir/R4B/Invoice.html#resource) | `UseExtensionFromAncestor` | - |
| [Invoice.lineItem.priceComponent.code](https://hl7.org/fhir/R4B/Invoice.html#resource) | `UseExtensionFromAncestor` | - |
| [Invoice.lineItem.priceComponent.factor](https://hl7.org/fhir/R4B/Invoice.html#resource) | `UseExtensionFromAncestor` | - |
| [Invoice.lineItem.priceComponent.amount](https://hl7.org/fhir/R4B/Invoice.html#resource) | `UseExtensionFromAncestor` | - |
| [Invoice.totalPriceComponent](https://hl7.org/fhir/R4B/Invoice.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.3/StructureDefinition/extension-Invoice.totalPriceComponent](StructureDefinition-ext-R4B-Invoice.totalPriceComponent.html) |
| [Invoice.totalNet](https://hl7.org/fhir/R4B/Invoice.html#resource) | `UseElementSameName` | [Invoice.totalNet](https://hl7.org/fhir/R5/Invoice.html#resource) |
| [Invoice.totalGross](https://hl7.org/fhir/R4B/Invoice.html#resource) | `UseElementSameName` | [Invoice.totalGross](https://hl7.org/fhir/R5/Invoice.html#resource) |
| [Invoice.paymentTerms](https://hl7.org/fhir/R4B/Invoice.html#resource) | `UseElementSameName` | [Invoice.paymentTerms](https://hl7.org/fhir/R5/Invoice.html#resource) |
| [Invoice.note](https://hl7.org/fhir/R4B/Invoice.html#resource) | `UseElementSameName` | [Invoice.note](https://hl7.org/fhir/R5/Invoice.html#resource) |
