### Lookup for [FHIR R3](https://hl7.org/fhir/STU3/) [PaymentReconciliation](https://hl7.org/fhir/STU3/PaymentReconciliation.html) for use in [FHIR R5](https://hl7.org/fhir/R5/)

| Source Element (FHIR R3) | Usage | Target |
| -------------- | ----- | ------ |
| [PaymentReconciliation.meta](https://hl7.org/fhir/STU3/PaymentReconciliation.html#resource) | `UseElementSameName` | [PaymentReconciliation.meta](https://hl7.org/fhir/R5/PaymentReconciliation.html#resource) |
| [PaymentReconciliation.implicitRules](https://hl7.org/fhir/STU3/PaymentReconciliation.html#resource) | `UseElementSameName` | [PaymentReconciliation.implicitRules](https://hl7.org/fhir/R5/PaymentReconciliation.html#resource) |
| [PaymentReconciliation.language](https://hl7.org/fhir/STU3/PaymentReconciliation.html#resource) | `UseElementSameName` | [PaymentReconciliation.language](https://hl7.org/fhir/R5/PaymentReconciliation.html#resource) |
| [PaymentReconciliation.text](https://hl7.org/fhir/STU3/PaymentReconciliation.html#resource) | `UseElementSameName` | [PaymentReconciliation.text](https://hl7.org/fhir/R5/PaymentReconciliation.html#resource) |
| [PaymentReconciliation.contained](https://hl7.org/fhir/STU3/PaymentReconciliation.html#resource) | `UseElementSameName` | [PaymentReconciliation.contained](https://hl7.org/fhir/R5/PaymentReconciliation.html#resource) |
| [PaymentReconciliation.identifier](https://hl7.org/fhir/STU3/PaymentReconciliation.html#resource) | `UseElementSameName` | [PaymentReconciliation.identifier](https://hl7.org/fhir/R5/PaymentReconciliation.html#resource) |
| [PaymentReconciliation.status](https://hl7.org/fhir/STU3/PaymentReconciliation.html#resource) | `UseElementSameName` | [PaymentReconciliation.status](https://hl7.org/fhir/R5/PaymentReconciliation.html#resource) |
| [PaymentReconciliation.period](https://hl7.org/fhir/STU3/PaymentReconciliation.html#resource) | `UseElementSameName` | [PaymentReconciliation.period](https://hl7.org/fhir/R5/PaymentReconciliation.html#resource) |
| [PaymentReconciliation.created](https://hl7.org/fhir/STU3/PaymentReconciliation.html#resource) | `UseElementSameName` | [PaymentReconciliation.created](https://hl7.org/fhir/R5/PaymentReconciliation.html#resource) |
| [PaymentReconciliation.organization](https://hl7.org/fhir/STU3/PaymentReconciliation.html#resource) | `UseElementRenamed` | [PaymentReconciliation.paymentIssuer](https://hl7.org/fhir/R5/PaymentReconciliation.html#resource) |
| [PaymentReconciliation.request](https://hl7.org/fhir/STU3/PaymentReconciliation.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-PaymentReconciliation.request](StructureDefinition-ext-R3-PaymentReconciliation.request.html) |
| [PaymentReconciliation.outcome](https://hl7.org/fhir/STU3/PaymentReconciliation.html#resource) | `UseElementSameName` | [PaymentReconciliation.outcome](https://hl7.org/fhir/R5/PaymentReconciliation.html#resource) |
| [PaymentReconciliation.disposition](https://hl7.org/fhir/STU3/PaymentReconciliation.html#resource) | `UseElementSameName` | [PaymentReconciliation.disposition](https://hl7.org/fhir/R5/PaymentReconciliation.html#resource) |
| [PaymentReconciliation.requestProvider](https://hl7.org/fhir/STU3/PaymentReconciliation.html#resource) | `UseElementRenamed` | [PaymentReconciliation.requestor](https://hl7.org/fhir/R5/PaymentReconciliation.html#resource) |
| [PaymentReconciliation.requestOrganization](https://hl7.org/fhir/STU3/PaymentReconciliation.html#resource) | `UseElementRenamed` | [PaymentReconciliation.requestor](https://hl7.org/fhir/R5/PaymentReconciliation.html#resource) |
| [PaymentReconciliation.detail](https://hl7.org/fhir/STU3/PaymentReconciliation.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-PaymentReconciliation.detail](StructureDefinition-ext-R3-PaymentReconciliation.detail.html) |
| [PaymentReconciliation.detail.type](https://hl7.org/fhir/STU3/PaymentReconciliation.html#resource) | `UseExtensionFromAncestor` | - |
| [PaymentReconciliation.detail.request](https://hl7.org/fhir/STU3/PaymentReconciliation.html#resource) | `UseExtensionFromAncestor` | - |
| [PaymentReconciliation.detail.response](https://hl7.org/fhir/STU3/PaymentReconciliation.html#resource) | `UseExtensionFromAncestor` | - |
| [PaymentReconciliation.detail.submitter](https://hl7.org/fhir/STU3/PaymentReconciliation.html#resource) | `UseExtensionFromAncestor` | - |
| [PaymentReconciliation.detail.payee](https://hl7.org/fhir/STU3/PaymentReconciliation.html#resource) | `UseExtensionFromAncestor` | - |
| [PaymentReconciliation.detail.date](https://hl7.org/fhir/STU3/PaymentReconciliation.html#resource) | `UseExtensionFromAncestor` | - |
| [PaymentReconciliation.detail.amount](https://hl7.org/fhir/STU3/PaymentReconciliation.html#resource) | `UseExtensionFromAncestor` | - |
| [PaymentReconciliation.form](https://hl7.org/fhir/STU3/PaymentReconciliation.html#resource) | `UseElementRenamed` | [PaymentReconciliation.formCode](https://hl7.org/fhir/R5/PaymentReconciliation.html#resource) |
| [PaymentReconciliation.total](https://hl7.org/fhir/STU3/PaymentReconciliation.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-PaymentReconciliation.total](StructureDefinition-ext-R3-PaymentReconciliation.total.html) |
| [PaymentReconciliation.processNote](https://hl7.org/fhir/STU3/PaymentReconciliation.html#resource) | `UseElementSameName` | [PaymentReconciliation.processNote](https://hl7.org/fhir/R5/PaymentReconciliation.html#resource) |
| [PaymentReconciliation.processNote.type](https://hl7.org/fhir/STU3/PaymentReconciliation.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-PaymentReconciliation.processNote.type](StructureDefinition-ext-R3-PR.pr.type.html) |
| [PaymentReconciliation.processNote.text](https://hl7.org/fhir/STU3/PaymentReconciliation.html#resource) | `UseElementSameName` | [PaymentReconciliation.processNote.text](https://hl7.org/fhir/R5/PaymentReconciliation.html#resource) |
