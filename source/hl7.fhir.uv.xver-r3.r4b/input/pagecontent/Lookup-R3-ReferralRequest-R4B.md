### Lookup for [FHIR R3](https://hl7.org/fhir/STU3/) [ReferralRequest](https://hl7.org/fhir/STU3/ReferralRequest.html) for use in [FHIR R4B](https://hl7.org/fhir/R4B/)

| Source Element (FHIR R3) | Usage | Target |
| -------------- | ----- | ------ |
| [ReferralRequest.meta](https://hl7.org/fhir/STU3/ReferralRequest.html#resource) | `UseElementRenamed` | [ServiceRequest.meta](https://hl7.org/fhir/R4B/ServiceRequest.html#resource) |
| [ReferralRequest.implicitRules](https://hl7.org/fhir/STU3/ReferralRequest.html#resource) | `UseElementRenamed` | [ServiceRequest.implicitRules](https://hl7.org/fhir/R4B/ServiceRequest.html#resource) |
| [ReferralRequest.language](https://hl7.org/fhir/STU3/ReferralRequest.html#resource) | `UseElementRenamed` | [ServiceRequest.language](https://hl7.org/fhir/R4B/ServiceRequest.html#resource) |
| [ReferralRequest.text](https://hl7.org/fhir/STU3/ReferralRequest.html#resource) | `UseElementRenamed` | [ServiceRequest.text](https://hl7.org/fhir/R4B/ServiceRequest.html#resource) |
| [ReferralRequest.contained](https://hl7.org/fhir/STU3/ReferralRequest.html#resource) | `UseElementRenamed` | [ServiceRequest.contained](https://hl7.org/fhir/R4B/ServiceRequest.html#resource) |
| [ReferralRequest.identifier](https://hl7.org/fhir/STU3/ReferralRequest.html#resource) | `UseElementRenamed` | [ServiceRequest.identifier](https://hl7.org/fhir/R4B/ServiceRequest.html#resource) |
| [ReferralRequest.definition](https://hl7.org/fhir/STU3/ReferralRequest.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-ReferralRequest.definition](StructureDefinition-ext-R3-ReferralRequest.definition.html) |
| [ReferralRequest.basedOn](https://hl7.org/fhir/STU3/ReferralRequest.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-ReferralRequest.basedOn](StructureDefinition-ext-R3-ReferralRequest.basedOn.html) |
| [ReferralRequest.replaces](https://hl7.org/fhir/STU3/ReferralRequest.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-ReferralRequest.replaces](StructureDefinition-ext-R3-ReferralRequest.replaces.html) |
| [ReferralRequest.groupIdentifier](https://hl7.org/fhir/STU3/ReferralRequest.html#resource) | `UseElementRenamed` | [ServiceRequest.requisition](https://hl7.org/fhir/R4B/ServiceRequest.html#resource) |
| [ReferralRequest.status](https://hl7.org/fhir/STU3/ReferralRequest.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-ReferralRequest.status](StructureDefinition-ext-R3-ReferralRequest.status.html) |
| [ReferralRequest.intent](https://hl7.org/fhir/STU3/ReferralRequest.html#resource) | `UseElementRenamed` | [ServiceRequest.intent](https://hl7.org/fhir/R4B/ServiceRequest.html#resource) |
| [ReferralRequest.type](https://hl7.org/fhir/STU3/ReferralRequest.html#resource) | `UseElementRenamed` | [ServiceRequest.category](https://hl7.org/fhir/R4B/ServiceRequest.html#resource) |
| [ReferralRequest.priority](https://hl7.org/fhir/STU3/ReferralRequest.html#resource) | `UseElementRenamed` | [ServiceRequest.priority](https://hl7.org/fhir/R4B/ServiceRequest.html#resource) |
| [ReferralRequest.serviceRequested](https://hl7.org/fhir/STU3/ReferralRequest.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-ReferralRequest.serviceRequested](StructureDefinition-ext-R3-ReferralRequest.serviceRequested.html) |
| [ReferralRequest.subject](https://hl7.org/fhir/STU3/ReferralRequest.html#resource) | `UseElementRenamed` | [ServiceRequest.subject](https://hl7.org/fhir/R4B/ServiceRequest.html#resource) |
| [ReferralRequest.context](https://hl7.org/fhir/STU3/ReferralRequest.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-ReferralRequest.context](StructureDefinition-ext-R3-ReferralRequest.context.html) |
| [ReferralRequest.occurrence[x]](https://hl7.org/fhir/STU3/ReferralRequest.html#resource) | `UseElementRenamed` | [ServiceRequest.occurrence[x]](https://hl7.org/fhir/R4B/ServiceRequest.html#resource) |
| [ReferralRequest.authoredOn](https://hl7.org/fhir/STU3/ReferralRequest.html#resource) | `UseElementRenamed` | [ServiceRequest.authoredOn](https://hl7.org/fhir/R4B/ServiceRequest.html#resource) |
| [ReferralRequest.requester](https://hl7.org/fhir/STU3/ReferralRequest.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-ReferralRequest.requester](StructureDefinition-ext-R3-ReferralRequest.requester.html) |
| [ReferralRequest.requester.agent](https://hl7.org/fhir/STU3/ReferralRequest.html#resource) | `UseExtensionFromAncestor` | - |
| [ReferralRequest.requester.onBehalfOf](https://hl7.org/fhir/STU3/ReferralRequest.html#resource) | `UseExtensionFromAncestor` | - |
| [ReferralRequest.specialty](https://hl7.org/fhir/STU3/ReferralRequest.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-ReferralRequest.specialty](StructureDefinition-ext-R3-ReferralRequest.specialty.html) |
| [ReferralRequest.recipient](https://hl7.org/fhir/STU3/ReferralRequest.html#resource) | `UseElementRenamed` | [ServiceRequest.performer](https://hl7.org/fhir/R4B/ServiceRequest.html#resource) |
| [ReferralRequest.reasonCode](https://hl7.org/fhir/STU3/ReferralRequest.html#resource) | `UseElementRenamed` | [ServiceRequest.reasonCode](https://hl7.org/fhir/R4B/ServiceRequest.html#resource) |
| [ReferralRequest.reasonReference](https://hl7.org/fhir/STU3/ReferralRequest.html#resource) | `UseElementRenamed` | [ServiceRequest.reasonReference](https://hl7.org/fhir/R4B/ServiceRequest.html#resource) |
| [ReferralRequest.description](https://hl7.org/fhir/STU3/ReferralRequest.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-ReferralRequest.description](StructureDefinition-ext-R3-ReferralRequest.description.html) |
| [ReferralRequest.supportingInfo](https://hl7.org/fhir/STU3/ReferralRequest.html#resource) | `UseElementRenamed` | [ServiceRequest.supportingInfo](https://hl7.org/fhir/R4B/ServiceRequest.html#resource) |
| [ReferralRequest.note](https://hl7.org/fhir/STU3/ReferralRequest.html#resource) | `UseElementRenamed` | [ServiceRequest.note](https://hl7.org/fhir/R4B/ServiceRequest.html#resource) |
| [ReferralRequest.relevantHistory](https://hl7.org/fhir/STU3/ReferralRequest.html#resource) | `UseElementRenamed` | [ServiceRequest.relevantHistory](https://hl7.org/fhir/R4B/ServiceRequest.html#resource) |
