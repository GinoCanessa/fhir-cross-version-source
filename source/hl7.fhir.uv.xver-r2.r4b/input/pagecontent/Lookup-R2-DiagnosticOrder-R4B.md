### Lookup for [FHIR R2](https://hl7.org/fhir/DSTU2/) [DiagnosticOrder](https://hl7.org/fhir/DSTU2/DiagnosticOrder.html) for use in [FHIR R4B](https://hl7.org/fhir/R4B/)

| Source Element (FHIR R2) | Usage | Target |
| -------------- | ----- | ------ |
| [DiagnosticOrder.meta](https://hl7.org/fhir/DSTU2/DiagnosticOrder.html#resource) | `UseElementRenamed` | [ServiceRequest.meta](https://hl7.org/fhir/R4B/ServiceRequest.html#resource) |
| [DiagnosticOrder.implicitRules](https://hl7.org/fhir/DSTU2/DiagnosticOrder.html#resource) | `UseElementRenamed` | [ServiceRequest.implicitRules](https://hl7.org/fhir/R4B/ServiceRequest.html#resource) |
| [DiagnosticOrder.language](https://hl7.org/fhir/DSTU2/DiagnosticOrder.html#resource) | `UseElementRenamed` | [ServiceRequest.language](https://hl7.org/fhir/R4B/ServiceRequest.html#resource) |
| [DiagnosticOrder.text](https://hl7.org/fhir/DSTU2/DiagnosticOrder.html#resource) | `UseElementRenamed` | [ServiceRequest.text](https://hl7.org/fhir/R4B/ServiceRequest.html#resource) |
| [DiagnosticOrder.contained](https://hl7.org/fhir/DSTU2/DiagnosticOrder.html#resource) | `UseElementRenamed` | [ServiceRequest.contained](https://hl7.org/fhir/R4B/ServiceRequest.html#resource) |
| [DiagnosticOrder.subject](https://hl7.org/fhir/DSTU2/DiagnosticOrder.html#resource) | `UseElementRenamed` | [ServiceRequest.subject](https://hl7.org/fhir/R4B/ServiceRequest.html#resource) |
| [DiagnosticOrder.orderer](https://hl7.org/fhir/DSTU2/DiagnosticOrder.html#resource) | `UseElementRenamed` | [ServiceRequest.requester](https://hl7.org/fhir/R4B/ServiceRequest.html#resource) |
| [DiagnosticOrder.identifier](https://hl7.org/fhir/DSTU2/DiagnosticOrder.html#resource) | `UseElementRenamed` | [ServiceRequest.identifier](https://hl7.org/fhir/R4B/ServiceRequest.html#resource) |
| [DiagnosticOrder.encounter](https://hl7.org/fhir/DSTU2/DiagnosticOrder.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-DiagnosticOrder.encounter](StructureDefinition-ext-R2-DiagnosticOrder.encounter.html) |
| [DiagnosticOrder.reason](https://hl7.org/fhir/DSTU2/DiagnosticOrder.html#resource) | `UseElementRenamed` | [ServiceRequest.reasonCode](https://hl7.org/fhir/R4B/ServiceRequest.html#resource) |
| [DiagnosticOrder.supportingInformation](https://hl7.org/fhir/DSTU2/DiagnosticOrder.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-DiagnosticOrder.supportingInformation](StructureDefinition-ext-R2-DiagnosticOrder.supportingInformation.html) |
| [DiagnosticOrder.specimen](https://hl7.org/fhir/DSTU2/DiagnosticOrder.html#resource) | `UseElementRenamed` | [ServiceRequest.specimen](https://hl7.org/fhir/R4B/ServiceRequest.html#resource) |
| [DiagnosticOrder.status](https://hl7.org/fhir/DSTU2/DiagnosticOrder.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-DiagnosticOrder.status](StructureDefinition-ext-R2-DiagnosticOrder.status.html) |
| [DiagnosticOrder.priority](https://hl7.org/fhir/DSTU2/DiagnosticOrder.html#resource) | `UseElementRenamed` | [ServiceRequest.priority](https://hl7.org/fhir/R4B/ServiceRequest.html#resource) |
| [DiagnosticOrder.event](https://hl7.org/fhir/DSTU2/DiagnosticOrder.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-DiagnosticOrder.event](StructureDefinition-ext-R2-DiagnosticOrder.event.html) |
| [DiagnosticOrder.event.id](https://hl7.org/fhir/DSTU2/DiagnosticOrder.html#resource) | `UseExtensionFromAncestor` | - |
| [DiagnosticOrder.event.status](https://hl7.org/fhir/DSTU2/DiagnosticOrder.html#resource) | `UseExtensionFromAncestor` | - |
| [DiagnosticOrder.event.description](https://hl7.org/fhir/DSTU2/DiagnosticOrder.html#resource) | `UseExtensionFromAncestor` | - |
| [DiagnosticOrder.event.dateTime](https://hl7.org/fhir/DSTU2/DiagnosticOrder.html#resource) | `UseExtensionFromAncestor` | - |
| [DiagnosticOrder.event.actor](https://hl7.org/fhir/DSTU2/DiagnosticOrder.html#resource) | `UseExtensionFromAncestor` | - |
| [DiagnosticOrder.item](https://hl7.org/fhir/DSTU2/DiagnosticOrder.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-DiagnosticOrder.item](StructureDefinition-ext-R2-DiagnosticOrder.item.html) |
| [DiagnosticOrder.item.id](https://hl7.org/fhir/DSTU2/DiagnosticOrder.html#resource) | `UseExtensionFromAncestor` | - |
| [DiagnosticOrder.item.code](https://hl7.org/fhir/DSTU2/DiagnosticOrder.html#resource) | `UseExtensionFromAncestor` | - |
| [DiagnosticOrder.item.specimen](https://hl7.org/fhir/DSTU2/DiagnosticOrder.html#resource) | `UseExtensionFromAncestor` | - |
| [DiagnosticOrder.item.bodySite](https://hl7.org/fhir/DSTU2/DiagnosticOrder.html#resource) | `UseExtensionFromAncestor` | - |
| [DiagnosticOrder.item.status](https://hl7.org/fhir/DSTU2/DiagnosticOrder.html#resource) | `UseExtensionFromAncestor` | - |
| [DiagnosticOrder.item.event](https://hl7.org/fhir/DSTU2/DiagnosticOrder.html#resource) | `UseExtensionFromAncestor` | - |
| [DiagnosticOrder.note](https://hl7.org/fhir/DSTU2/DiagnosticOrder.html#resource) | `UseElementRenamed` | [ServiceRequest.note](https://hl7.org/fhir/R4B/ServiceRequest.html#resource) |
