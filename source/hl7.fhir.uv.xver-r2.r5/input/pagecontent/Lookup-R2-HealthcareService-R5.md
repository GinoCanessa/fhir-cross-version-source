### Lookup for [FHIR R2](https://hl7.org/fhir/DSTU2/) [HealthcareService](https://hl7.org/fhir/DSTU2/HealthcareService.html) for use in [FHIR R5](https://hl7.org/fhir/R5/)

| Source Element (FHIR R2) | Usage | Target |
| -------------- | ----- | ------ |
| [HealthcareService.meta](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseElementSameName` | [HealthcareService.meta](https://hl7.org/fhir/R5/HealthcareService.html#resource) |
| [HealthcareService.implicitRules](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseElementSameName` | [HealthcareService.implicitRules](https://hl7.org/fhir/R5/HealthcareService.html#resource) |
| [HealthcareService.language](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseElementSameName` | [HealthcareService.language](https://hl7.org/fhir/R5/HealthcareService.html#resource) |
| [HealthcareService.text](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseElementSameName` | [HealthcareService.text](https://hl7.org/fhir/R5/HealthcareService.html#resource) |
| [HealthcareService.contained](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseElementSameName` | [HealthcareService.contained](https://hl7.org/fhir/R5/HealthcareService.html#resource) |
| [HealthcareService.identifier](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseElementSameName` | [HealthcareService.identifier](https://hl7.org/fhir/R5/HealthcareService.html#resource) |
| [HealthcareService.providedBy](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseElementSameName` | [HealthcareService.providedBy](https://hl7.org/fhir/R5/HealthcareService.html#resource) |
| [HealthcareService.serviceCategory](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseElementRenamed` | [HealthcareService.category](https://hl7.org/fhir/R5/HealthcareService.html#resource) |
| [HealthcareService.serviceType](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-HealthcareService.serviceType](StructureDefinition-ext-R2-HealthcareService.serviceType.html) |
| [HealthcareService.serviceType.id](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseExtensionFromAncestor` | - |
| [HealthcareService.serviceType.type](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseExtensionFromAncestor` | - |
| [HealthcareService.serviceType.specialty](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseExtensionFromAncestor` | - |
| [HealthcareService.location](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseElementSameName` | [HealthcareService.location](https://hl7.org/fhir/R5/HealthcareService.html#resource) |
| [HealthcareService.serviceName](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseElementRenamed` | [HealthcareService.name](https://hl7.org/fhir/R5/HealthcareService.html#resource) |
| [HealthcareService.comment](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseElementSameName` | [HealthcareService.comment](https://hl7.org/fhir/R5/HealthcareService.html#resource) |
| [HealthcareService.extraDetails](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseElementSameName` | [HealthcareService.extraDetails](https://hl7.org/fhir/R5/HealthcareService.html#resource) |
| [HealthcareService.photo](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseElementSameName` | [HealthcareService.photo](https://hl7.org/fhir/R5/HealthcareService.html#resource) |
| [HealthcareService.telecom](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-HealthcareService.telecom](StructureDefinition-ext-R2-HealthcareService.telecom.html) |
| [HealthcareService.coverageArea](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseElementSameName` | [HealthcareService.coverageArea](https://hl7.org/fhir/R5/HealthcareService.html#resource) |
| [HealthcareService.serviceProvisionCode](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseElementSameName` | [HealthcareService.serviceProvisionCode](https://hl7.org/fhir/R5/HealthcareService.html#resource) |
| [HealthcareService.eligibility](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseOneOf` | [HealthcareService.eligibility](https://hl7.org/fhir/R5/HealthcareService.html#resource)<br />[HealthcareService.eligibility.code](https://hl7.org/fhir/R5/HealthcareService.html#resource) |
| [HealthcareService.eligibilityNote](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseElementRenamed` | [HealthcareService.eligibility.comment](https://hl7.org/fhir/R5/HealthcareService.html#resource) |
| [HealthcareService.programName](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-HealthcareService.programName](StructureDefinition-ext-R2-HealthcareService.programName.html) |
| [HealthcareService.characteristic](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseElementSameName` | [HealthcareService.characteristic](https://hl7.org/fhir/R5/HealthcareService.html#resource) |
| [HealthcareService.referralMethod](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseElementSameName` | [HealthcareService.referralMethod](https://hl7.org/fhir/R5/HealthcareService.html#resource) |
| [HealthcareService.publicKey](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-HealthcareService.publicKey](StructureDefinition-ext-R2-HealthcareService.publicKey.html) |
| [HealthcareService.appointmentRequired](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseElementSameName` | [HealthcareService.appointmentRequired](https://hl7.org/fhir/R5/HealthcareService.html#resource) |
| [HealthcareService.availableTime](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-HealthcareService.availableTime](StructureDefinition-ext-R2-HealthcareService.availableTime.html) |
| [HealthcareService.availableTime.id](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseExtensionFromAncestor` | - |
| [HealthcareService.availableTime.daysOfWeek](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseExtensionFromAncestor` | - |
| [HealthcareService.availableTime.allDay](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseExtensionFromAncestor` | - |
| [HealthcareService.availableTime.availableStartTime](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseExtensionFromAncestor` | - |
| [HealthcareService.availableTime.availableEndTime](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseExtensionFromAncestor` | - |
| [HealthcareService.notAvailable](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-HealthcareService.notAvailable](StructureDefinition-ext-R2-HealthcareService.notAvailable.html) |
| [HealthcareService.notAvailable.id](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseExtensionFromAncestor` | - |
| [HealthcareService.notAvailable.description](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseExtensionFromAncestor` | - |
| [HealthcareService.notAvailable.during](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseExtensionFromAncestor` | - |
| [HealthcareService.availabilityExceptions](https://hl7.org/fhir/DSTU2/HealthcareService.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-HealthcareService.availabilityExceptions](StructureDefinition-ext-R2-HealthcareService.availabilityExceptions.html) |
