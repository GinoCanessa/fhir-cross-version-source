### Lookup for [FHIR R2](https://hl7.org/fhir/DSTU2/) [SupplyRequest](https://hl7.org/fhir/DSTU2/SupplyRequest.html) for use in [FHIR R4B](https://hl7.org/fhir/R4B/)

| Source Element (FHIR R2) | Usage | Target |
| -------------- | ----- | ------ |
| [SupplyRequest.meta](https://hl7.org/fhir/DSTU2/SupplyRequest.html#resource) | `UseElementSameName` | [SupplyRequest.meta](https://hl7.org/fhir/R4B/SupplyRequest.html#resource) |
| [SupplyRequest.implicitRules](https://hl7.org/fhir/DSTU2/SupplyRequest.html#resource) | `UseElementSameName` | [SupplyRequest.implicitRules](https://hl7.org/fhir/R4B/SupplyRequest.html#resource) |
| [SupplyRequest.language](https://hl7.org/fhir/DSTU2/SupplyRequest.html#resource) | `UseElementSameName` | [SupplyRequest.language](https://hl7.org/fhir/R4B/SupplyRequest.html#resource) |
| [SupplyRequest.text](https://hl7.org/fhir/DSTU2/SupplyRequest.html#resource) | `UseElementSameName` | [SupplyRequest.text](https://hl7.org/fhir/R4B/SupplyRequest.html#resource) |
| [SupplyRequest.contained](https://hl7.org/fhir/DSTU2/SupplyRequest.html#resource) | `UseElementSameName` | [SupplyRequest.contained](https://hl7.org/fhir/R4B/SupplyRequest.html#resource) |
| [SupplyRequest.patient](https://hl7.org/fhir/DSTU2/SupplyRequest.html#resource) | `UseElementRenamed` | [SupplyRequest.extension](https://hl7.org/fhir/R4B/SupplyRequest.html#resource) |
| [SupplyRequest.source](https://hl7.org/fhir/DSTU2/SupplyRequest.html#resource) | `UseElementRenamed` | [SupplyRequest.requester](https://hl7.org/fhir/R4B/SupplyRequest.html#resource) |
| [SupplyRequest.date](https://hl7.org/fhir/DSTU2/SupplyRequest.html#resource) | `UseElementRenamed` | [SupplyRequest.authoredOn](https://hl7.org/fhir/R4B/SupplyRequest.html#resource) |
| [SupplyRequest.identifier](https://hl7.org/fhir/DSTU2/SupplyRequest.html#resource) | `UseElementSameName` | [SupplyRequest.identifier](https://hl7.org/fhir/R4B/SupplyRequest.html#resource) |
| [SupplyRequest.status](https://hl7.org/fhir/DSTU2/SupplyRequest.html#resource) | `UseElementSameName` | [SupplyRequest.status](https://hl7.org/fhir/R4B/SupplyRequest.html#resource) |
| [SupplyRequest.kind](https://hl7.org/fhir/DSTU2/SupplyRequest.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-SupplyRequest.kind](StructureDefinition-ext-R2-SupplyRequest.kind.html) |
| [SupplyRequest.orderedItem](https://hl7.org/fhir/DSTU2/SupplyRequest.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-SupplyRequest.orderedItem](StructureDefinition-ext-R2-SupplyRequest.orderedItem.html) |
| [SupplyRequest.supplier](https://hl7.org/fhir/DSTU2/SupplyRequest.html#resource) | `UseElementSameName` | [SupplyRequest.supplier](https://hl7.org/fhir/R4B/SupplyRequest.html#resource) |
| [SupplyRequest.reason[x]](https://hl7.org/fhir/DSTU2/SupplyRequest.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-SupplyRequest.reason](StructureDefinition-ext-R2-SupplyRequest.reason.html) |
| [SupplyRequest.when](https://hl7.org/fhir/DSTU2/SupplyRequest.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-SupplyRequest.when](StructureDefinition-ext-R2-SupplyRequest.when.html) |
| [SupplyRequest.when.id](https://hl7.org/fhir/DSTU2/SupplyRequest.html#resource) | `UseExtensionFromAncestor` | - |
| [SupplyRequest.when.code](https://hl7.org/fhir/DSTU2/SupplyRequest.html#resource) | `UseExtensionFromAncestor` | - |
| [SupplyRequest.when.schedule](https://hl7.org/fhir/DSTU2/SupplyRequest.html#resource) | `UseExtensionFromAncestor` | - |
