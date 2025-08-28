### Lookup for [FHIR R2](https://hl7.org/fhir/DSTU2/) [ReferralRequest](https://hl7.org/fhir/DSTU2/ReferralRequest.html) for use in [FHIR R5](https://hl7.org/fhir/R5/)

| Source Element (FHIR R2) | Usage | Target |
| -------------- | ----- | ------ |
| [ReferralRequest.meta](https://hl7.org/fhir/DSTU2/ReferralRequest.html#resource) | `UseElementRenamed` | [ServiceRequest.meta](https://hl7.org/fhir/R5/ServiceRequest.html#resource) |
| [ReferralRequest.implicitRules](https://hl7.org/fhir/DSTU2/ReferralRequest.html#resource) | `UseElementRenamed` | [ServiceRequest.implicitRules](https://hl7.org/fhir/R5/ServiceRequest.html#resource) |
| [ReferralRequest.language](https://hl7.org/fhir/DSTU2/ReferralRequest.html#resource) | `UseElementRenamed` | [ServiceRequest.language](https://hl7.org/fhir/R5/ServiceRequest.html#resource) |
| [ReferralRequest.text](https://hl7.org/fhir/DSTU2/ReferralRequest.html#resource) | `UseElementRenamed` | [ServiceRequest.text](https://hl7.org/fhir/R5/ServiceRequest.html#resource) |
| [ReferralRequest.contained](https://hl7.org/fhir/DSTU2/ReferralRequest.html#resource) | `UseElementRenamed` | [ServiceRequest.contained](https://hl7.org/fhir/R5/ServiceRequest.html#resource) |
| [ReferralRequest.status](https://hl7.org/fhir/DSTU2/ReferralRequest.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.status](StructureDefinition-ext-R2-ReferralRequest.status.html) |
| [ReferralRequest.identifier](https://hl7.org/fhir/DSTU2/ReferralRequest.html#resource) | `UseElementRenamed` | [ServiceRequest.identifier](https://hl7.org/fhir/R5/ServiceRequest.html#resource) |
| [ReferralRequest.date](https://hl7.org/fhir/DSTU2/ReferralRequest.html#resource) | `UseElementRenamed` | [ServiceRequest.authoredOn](https://hl7.org/fhir/R5/ServiceRequest.html#resource) |
| [ReferralRequest.type](https://hl7.org/fhir/DSTU2/ReferralRequest.html#resource) | `UseElementRenamed` | [ServiceRequest.category](https://hl7.org/fhir/R5/ServiceRequest.html#resource) |
| [ReferralRequest.specialty](https://hl7.org/fhir/DSTU2/ReferralRequest.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.specialty](StructureDefinition-ext-R2-ReferralRequest.specialty.html) |
| [ReferralRequest.priority](https://hl7.org/fhir/DSTU2/ReferralRequest.html#resource) | `UseElementRenamed` | [ServiceRequest.priority](https://hl7.org/fhir/R5/ServiceRequest.html#resource) |
| [ReferralRequest.patient](https://hl7.org/fhir/DSTU2/ReferralRequest.html#resource) | `UseElementRenamed` | [ServiceRequest.subject](https://hl7.org/fhir/R5/ServiceRequest.html#resource) |
| [ReferralRequest.requester](https://hl7.org/fhir/DSTU2/ReferralRequest.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.requester](StructureDefinition-ext-R2-ReferralRequest.requester.html) |
| [ReferralRequest.recipient](https://hl7.org/fhir/DSTU2/ReferralRequest.html#resource) | `UseElementRenamed` | [ServiceRequest.performer](https://hl7.org/fhir/R5/ServiceRequest.html#resource) |
| [ReferralRequest.encounter](https://hl7.org/fhir/DSTU2/ReferralRequest.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.encounter](StructureDefinition-ext-R2-ReferralRequest.encounter.html) |
| [ReferralRequest.dateSent](https://hl7.org/fhir/DSTU2/ReferralRequest.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.dateSent](StructureDefinition-ext-R2-ReferralRequest.dateSent.html) |
| [ReferralRequest.reason](https://hl7.org/fhir/DSTU2/ReferralRequest.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.reason](StructureDefinition-ext-R2-ReferralRequest.reason.html) |
| [ReferralRequest.description](https://hl7.org/fhir/DSTU2/ReferralRequest.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.description](StructureDefinition-ext-R2-ReferralRequest.description.html) |
| [ReferralRequest.serviceRequested](https://hl7.org/fhir/DSTU2/ReferralRequest.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.serviceRequested](StructureDefinition-ext-R2-ReferralRequest.serviceRequested.html) |
| [ReferralRequest.supportingInformation](https://hl7.org/fhir/DSTU2/ReferralRequest.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-ReferralRequest.supportingInformation](StructureDefinition-ext-R2-ReferralRequest.supportingInformation.html) |
| [ReferralRequest.fulfillmentTime](https://hl7.org/fhir/DSTU2/ReferralRequest.html#resource) | `UseElementRenamed` | [ServiceRequest.occurrence[x]](https://hl7.org/fhir/R5/ServiceRequest.html#resource) |
