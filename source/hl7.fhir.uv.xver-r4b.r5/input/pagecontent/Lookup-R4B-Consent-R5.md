### Lookup for [FHIR R4B](https://hl7.org/fhir/R4B/) [Consent](https://hl7.org/fhir/R4B/Consent.html) for use in [FHIR R5](https://hl7.org/fhir/R5/)

| Source Element (FHIR R4B) | Usage | Target |
| -------------- | ----- | ------ |
| [Consent.meta](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseElementSameName` | [Consent.meta](https://hl7.org/fhir/R5/Consent.html#resource) |
| [Consent.implicitRules](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseElementSameName` | [Consent.implicitRules](https://hl7.org/fhir/R5/Consent.html#resource) |
| [Consent.language](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseElementSameName` | [Consent.language](https://hl7.org/fhir/R5/Consent.html#resource) |
| [Consent.text](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseElementSameName` | [Consent.text](https://hl7.org/fhir/R5/Consent.html#resource) |
| [Consent.contained](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseElementSameName` | [Consent.contained](https://hl7.org/fhir/R5/Consent.html#resource) |
| [Consent.identifier](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseElementSameName` | [Consent.identifier](https://hl7.org/fhir/R5/Consent.html#resource) |
| [Consent.status](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseElementSameName` | [Consent.status](https://hl7.org/fhir/R5/Consent.html#resource) |
| [Consent.scope](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.3/StructureDefinition/extension-Consent.scope](StructureDefinition-ext-R4B-Consent.scope.html) |
| [Consent.category](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseElementSameName` | [Consent.category](https://hl7.org/fhir/R5/Consent.html#resource) |
| [Consent.patient](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseElementRenamed` | [Consent.subject](https://hl7.org/fhir/R5/Consent.html#resource) |
| [Consent.dateTime](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.3/StructureDefinition/extension-Consent.dateTime](StructureDefinition-ext-R4B-Consent.dateTime.html) |
| [Consent.performer](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseElementRenamed` | [Consent.grantee](https://hl7.org/fhir/R5/Consent.html#resource) |
| [Consent.organization](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.3/StructureDefinition/extension-Consent.organization](StructureDefinition-ext-R4B-Consent.organization.html) |
| [Consent.source[x]](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.3/StructureDefinition/extension-Consent.source](StructureDefinition-ext-R4B-Consent.source.html) |
| [Consent.policy](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.3/StructureDefinition/extension-Consent.policy](StructureDefinition-ext-R4B-Consent.policy.html) |
| [Consent.policy.authority](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseExtensionFromAncestor` | - |
| [Consent.policy.uri](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseExtensionFromAncestor` | - |
| [Consent.policyRule](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseElementRenamed` | [Consent.regulatoryBasis](https://hl7.org/fhir/R5/Consent.html#resource) |
| [Consent.verification](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseElementSameName` | [Consent.verification](https://hl7.org/fhir/R5/Consent.html#resource) |
| [Consent.verification.verified](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseElementSameName` | [Consent.verification.verified](https://hl7.org/fhir/R5/Consent.html#resource) |
| [Consent.verification.verifiedWith](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseElementSameName` | [Consent.verification.verifiedWith](https://hl7.org/fhir/R5/Consent.html#resource) |
| [Consent.verification.verificationDate](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseElementSameName` | [Consent.verification.verificationDate](https://hl7.org/fhir/R5/Consent.html#resource) |
| [Consent.provision](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseElementSameName` | [Consent.provision](https://hl7.org/fhir/R5/Consent.html#resource) |
| [Consent.provision.type](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.3/StructureDefinition/extension-Consent.provision.type](StructureDefinition-ext-R4B-Consent.pr.type.html) |
| [Consent.provision.period](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseElementSameName` | [Consent.provision.period](https://hl7.org/fhir/R5/Consent.html#resource) |
| [Consent.provision.actor](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseOneOf` | [Consent.provision.actor](https://hl7.org/fhir/R5/Consent.html#resource)<br />[Consent.provision.actor](https://hl7.org/fhir/R5/Consent.html#resource) |
| [Consent.provision.actor.role](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseOneOf` | [Consent.provision.actor.role](https://hl7.org/fhir/R5/Consent.html#resource)<br />[Consent.provision.actor.role](https://hl7.org/fhir/R5/Consent.html#resource) |
| [Consent.provision.actor.reference](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseOneOf` | [Consent.provision.actor.reference](https://hl7.org/fhir/R5/Consent.html#resource)<br />[Consent.provision.actor.reference](https://hl7.org/fhir/R5/Consent.html#resource) |
| [Consent.provision.action](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseOneOf` | [Consent.provision.action](https://hl7.org/fhir/R5/Consent.html#resource)<br />[Consent.provision.action](https://hl7.org/fhir/R5/Consent.html#resource) |
| [Consent.provision.securityLabel](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseOneOf` | [Consent.provision.securityLabel](https://hl7.org/fhir/R5/Consent.html#resource)<br />[Consent.provision.securityLabel](https://hl7.org/fhir/R5/Consent.html#resource) |
| [Consent.provision.purpose](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseOneOf` | [Consent.provision.purpose](https://hl7.org/fhir/R5/Consent.html#resource)<br />[Consent.provision.purpose](https://hl7.org/fhir/R5/Consent.html#resource) |
| [Consent.provision.class](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.3/StructureDefinition/extension-Consent.provision.class](StructureDefinition-ext-R4B-Consent.pr.class.html) |
| [Consent.provision.code](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseElementSameName` | [Consent.provision.code](https://hl7.org/fhir/R5/Consent.html#resource) |
| [Consent.provision.dataPeriod](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseOneOf` | [Consent.provision.dataPeriod](https://hl7.org/fhir/R5/Consent.html#resource)<br />[Consent.provision.dataPeriod](https://hl7.org/fhir/R5/Consent.html#resource) |
| [Consent.provision.data](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseOneOf` | [Consent.provision.data](https://hl7.org/fhir/R5/Consent.html#resource)<br />[Consent.provision.data](https://hl7.org/fhir/R5/Consent.html#resource) |
| [Consent.provision.data.meaning](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseOneOf` | [Consent.provision.data.meaning](https://hl7.org/fhir/R5/Consent.html#resource)<br />[Consent.provision.data.meaning](https://hl7.org/fhir/R5/Consent.html#resource) |
| [Consent.provision.data.reference](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseOneOf` | [Consent.provision.data.reference](https://hl7.org/fhir/R5/Consent.html#resource)<br />[Consent.provision.data.reference](https://hl7.org/fhir/R5/Consent.html#resource) |
| [Consent.provision.provision](https://hl7.org/fhir/R4B/Consent.html#resource) | `UseElementSameName` | [Consent.provision.provision](https://hl7.org/fhir/R5/Consent.html#resource) |
