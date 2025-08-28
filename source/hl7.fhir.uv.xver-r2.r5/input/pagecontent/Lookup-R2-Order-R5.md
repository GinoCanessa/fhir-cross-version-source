### Lookup for [FHIR R2](https://hl7.org/fhir/DSTU2/) [Order](https://hl7.org/fhir/DSTU2/Order.html) for use in [FHIR R5](https://hl7.org/fhir/R5/)

| Source Element (FHIR R2) | Usage | Target |
| -------------- | ----- | ------ |
| [Order.meta](https://hl7.org/fhir/DSTU2/Order.html#resource) | `UseElementRenamed` | [Task.meta](https://hl7.org/fhir/R5/Task.html#resource) |
| [Order.implicitRules](https://hl7.org/fhir/DSTU2/Order.html#resource) | `UseElementRenamed` | [Task.implicitRules](https://hl7.org/fhir/R5/Task.html#resource) |
| [Order.language](https://hl7.org/fhir/DSTU2/Order.html#resource) | `UseElementRenamed` | [Task.language](https://hl7.org/fhir/R5/Task.html#resource) |
| [Order.text](https://hl7.org/fhir/DSTU2/Order.html#resource) | `UseElementRenamed` | [Task.text](https://hl7.org/fhir/R5/Task.html#resource) |
| [Order.contained](https://hl7.org/fhir/DSTU2/Order.html#resource) | `UseElementRenamed` | [Task.contained](https://hl7.org/fhir/R5/Task.html#resource) |
| [Order.identifier](https://hl7.org/fhir/DSTU2/Order.html#resource) | `UseElementRenamed` | [Task.identifier](https://hl7.org/fhir/R5/Task.html#resource) |
| [Order.date](https://hl7.org/fhir/DSTU2/Order.html#resource) | `UseElementRenamed` | [Task.authoredOn](https://hl7.org/fhir/R5/Task.html#resource) |
| [Order.subject](https://hl7.org/fhir/DSTU2/Order.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Order.subject](StructureDefinition-ext-R2-Order.subject.html) |
| [Order.source](https://hl7.org/fhir/DSTU2/Order.html#resource) | `UseElementRenamed` | [Task.requester](https://hl7.org/fhir/R5/Task.html#resource) |
| [Order.target](https://hl7.org/fhir/DSTU2/Order.html#resource) | `UseElementRenamed` | [Task.requester](https://hl7.org/fhir/R5/Task.html#resource) |
| [Order.reason[x]](https://hl7.org/fhir/DSTU2/Order.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Order.reason](StructureDefinition-ext-R2-Order.reason.html) |
| [Order.when](https://hl7.org/fhir/DSTU2/Order.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Order.when](StructureDefinition-ext-R2-Order.when.html) |
| [Order.when.id](https://hl7.org/fhir/DSTU2/Order.html#resource) | `UseExtensionFromAncestor` | - |
| [Order.when.code](https://hl7.org/fhir/DSTU2/Order.html#resource) | `UseExtensionFromAncestor` | - |
| [Order.when.schedule](https://hl7.org/fhir/DSTU2/Order.html#resource) | `UseExtensionFromAncestor` | - |
| [Order.detail](https://hl7.org/fhir/DSTU2/Order.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Order.detail](StructureDefinition-ext-R2-Order.detail.html) |
