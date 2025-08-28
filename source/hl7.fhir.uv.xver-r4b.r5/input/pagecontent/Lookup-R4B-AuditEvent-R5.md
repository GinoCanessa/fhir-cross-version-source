### Lookup for [FHIR R4B](https://hl7.org/fhir/R4B/) [AuditEvent](https://hl7.org/fhir/R4B/AuditEvent.html) for use in [FHIR R5](https://hl7.org/fhir/R5/)

| Source Element (FHIR R4B) | Usage | Target |
| -------------- | ----- | ------ |
| [AuditEvent.meta](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseElementSameName` | [AuditEvent.meta](https://hl7.org/fhir/R5/AuditEvent.html#resource) |
| [AuditEvent.implicitRules](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseElementSameName` | [AuditEvent.implicitRules](https://hl7.org/fhir/R5/AuditEvent.html#resource) |
| [AuditEvent.language](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseElementSameName` | [AuditEvent.language](https://hl7.org/fhir/R5/AuditEvent.html#resource) |
| [AuditEvent.text](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseElementSameName` | [AuditEvent.text](https://hl7.org/fhir/R5/AuditEvent.html#resource) |
| [AuditEvent.contained](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseElementSameName` | [AuditEvent.contained](https://hl7.org/fhir/R5/AuditEvent.html#resource) |
| [AuditEvent.type](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.3/StructureDefinition/extension-AuditEvent.type](StructureDefinition-ext-R4B-AuditEvent.type.html) |
| [AuditEvent.subtype](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.3/StructureDefinition/extension-AuditEvent.subtype](StructureDefinition-ext-R4B-AuditEvent.subtype.html) |
| [AuditEvent.action](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseElementSameName` | [AuditEvent.action](https://hl7.org/fhir/R5/AuditEvent.html#resource) |
| [AuditEvent.period](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.3/StructureDefinition/extension-AuditEvent.period](StructureDefinition-ext-R4B-AuditEvent.period.html) |
| [AuditEvent.recorded](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseElementSameName` | [AuditEvent.recorded](https://hl7.org/fhir/R5/AuditEvent.html#resource) |
| [AuditEvent.outcome](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.3/StructureDefinition/extension-AuditEvent.outcome](StructureDefinition-ext-R4B-AuditEvent.outcome.html) |
| [AuditEvent.outcomeDesc](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.3/StructureDefinition/extension-AuditEvent.outcomeDesc](StructureDefinition-ext-R4B-AuditEvent.outcomeDesc.html) |
| [AuditEvent.purposeOfEvent](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseElementRenamed` | [AuditEvent.authorization](https://hl7.org/fhir/R5/AuditEvent.html#resource) |
| [AuditEvent.agent](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseElementSameName` | [AuditEvent.agent](https://hl7.org/fhir/R5/AuditEvent.html#resource) |
| [AuditEvent.agent.type](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseElementSameName` | [AuditEvent.agent.type](https://hl7.org/fhir/R5/AuditEvent.html#resource) |
| [AuditEvent.agent.role](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseElementSameName` | [AuditEvent.agent.role](https://hl7.org/fhir/R5/AuditEvent.html#resource) |
| [AuditEvent.agent.who](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseOneOf` | [AuditEvent.agent.who](https://hl7.org/fhir/R5/AuditEvent.html#resource)<br />[AuditEvent.agent.who](https://hl7.org/fhir/R5/AuditEvent.html#resource) |
| [AuditEvent.agent.altId](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.3/StructureDefinition/extension-AuditEvent.agent.altId](StructureDefinition-ext-R4B-AuditEvent.ag.altId.html) |
| [AuditEvent.agent.name](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.3/StructureDefinition/extension-AuditEvent.agent.name](StructureDefinition-ext-R4B-AuditEvent.ag.name.html) |
| [AuditEvent.agent.requestor](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseElementSameName` | [AuditEvent.agent.requestor](https://hl7.org/fhir/R5/AuditEvent.html#resource) |
| [AuditEvent.agent.location](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseElementSameName` | [AuditEvent.agent.location](https://hl7.org/fhir/R5/AuditEvent.html#resource) |
| [AuditEvent.agent.policy](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseElementSameName` | [AuditEvent.agent.policy](https://hl7.org/fhir/R5/AuditEvent.html#resource) |
| [AuditEvent.agent.media](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.3/StructureDefinition/extension-AuditEvent.agent.media](StructureDefinition-ext-R4B-AuditEvent.ag.media.html) |
| [AuditEvent.agent.network](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.3/StructureDefinition/extension-AuditEvent.agent.network](StructureDefinition-ext-R4B-AuditEvent.ag.network.html) |
| [AuditEvent.agent.network.address](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseExtensionFromAncestor` | - |
| [AuditEvent.agent.network.type](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseExtensionFromAncestor` | - |
| [AuditEvent.agent.purposeOfUse](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseElementRenamed` | [AuditEvent.agent.authorization](https://hl7.org/fhir/R5/AuditEvent.html#resource) |
| [AuditEvent.source](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseElementSameName` | [AuditEvent.source](https://hl7.org/fhir/R5/AuditEvent.html#resource) |
| [AuditEvent.source.site](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.3/StructureDefinition/extension-AuditEvent.source.site](StructureDefinition-ext-R4B-AuditEvent.so.site.html) |
| [AuditEvent.source.observer](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseElementSameName` | [AuditEvent.source.observer](https://hl7.org/fhir/R5/AuditEvent.html#resource) |
| [AuditEvent.source.type](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.3/StructureDefinition/extension-AuditEvent.source.type](StructureDefinition-ext-R4B-AuditEvent.so.type.html) |
| [AuditEvent.entity](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseElementSameName` | [AuditEvent.entity](https://hl7.org/fhir/R5/AuditEvent.html#resource) |
| [AuditEvent.entity.what](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseOneOf` | [AuditEvent.entity.what](https://hl7.org/fhir/R5/AuditEvent.html#resource)<br />[AuditEvent.entity.what](https://hl7.org/fhir/R5/AuditEvent.html#resource) |
| [AuditEvent.entity.type](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.3/StructureDefinition/extension-AuditEvent.entity.type](StructureDefinition-ext-R4B-AuditEvent.en.type.html) |
| [AuditEvent.entity.role](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.3/StructureDefinition/extension-AuditEvent.entity.role](StructureDefinition-ext-R4B-AuditEvent.en.role.html) |
| [AuditEvent.entity.lifecycle](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.3/StructureDefinition/extension-AuditEvent.entity.lifecycle](StructureDefinition-ext-R4B-AuditEvent.en.lifecycle.html) |
| [AuditEvent.entity.securityLabel](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.3/StructureDefinition/extension-AuditEvent.entity.securityLabel](StructureDefinition-ext-R4B-AuditEvent.en.securityLabel.html) |
| [AuditEvent.entity.name](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.3/StructureDefinition/extension-AuditEvent.entity.name](StructureDefinition-ext-R4B-AuditEvent.en.name.html) |
| [AuditEvent.entity.description](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.3/StructureDefinition/extension-AuditEvent.entity.description](StructureDefinition-ext-R4B-AuditEvent.en.description.html) |
| [AuditEvent.entity.query](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseElementSameName` | [AuditEvent.entity.query](https://hl7.org/fhir/R5/AuditEvent.html#resource) |
| [AuditEvent.entity.detail](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseElementSameName` | [AuditEvent.entity.detail](https://hl7.org/fhir/R5/AuditEvent.html#resource) |
| [AuditEvent.entity.detail.type](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.3/StructureDefinition/extension-AuditEvent.entity.detail.type](StructureDefinition-ext-R4B-AuditEvent.en.de.type.html) |
| [AuditEvent.entity.detail.value[x]](https://hl7.org/fhir/R4B/AuditEvent.html#resource) | `UseElementSameName` | [AuditEvent.entity.detail.value[x]](https://hl7.org/fhir/R5/AuditEvent.html#resource) |
