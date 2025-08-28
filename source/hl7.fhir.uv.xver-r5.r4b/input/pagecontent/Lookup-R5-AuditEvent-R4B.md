### Lookup for [FHIR R5](https://hl7.org/fhir/R5/) [AuditEvent](https://hl7.org/fhir/R5/AuditEvent.html) for use in [FHIR R4B](https://hl7.org/fhir/R4B/)

| Source Element (FHIR R5) | Usage | Target |
| -------------- | ----- | ------ |
| [AuditEvent.meta](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseElementSameName` | [AuditEvent.meta](https://hl7.org/fhir/R4B/AuditEvent.html#resource) |
| [AuditEvent.implicitRules](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseElementSameName` | [AuditEvent.implicitRules](https://hl7.org/fhir/R4B/AuditEvent.html#resource) |
| [AuditEvent.language](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseElementSameName` | [AuditEvent.language](https://hl7.org/fhir/R4B/AuditEvent.html#resource) |
| [AuditEvent.text](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseElementSameName` | [AuditEvent.text](https://hl7.org/fhir/R4B/AuditEvent.html#resource) |
| [AuditEvent.contained](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseElementSameName` | [AuditEvent.contained](https://hl7.org/fhir/R4B/AuditEvent.html#resource) |
| [AuditEvent.category](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.category](StructureDefinition-ext-R5-AuditEvent.category.html) |
| [AuditEvent.code](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.code](StructureDefinition-ext-R5-AuditEvent.code.html) |
| [AuditEvent.action](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseElementSameName` | [AuditEvent.action](https://hl7.org/fhir/R4B/AuditEvent.html#resource) |
| [AuditEvent.severity](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.severity](StructureDefinition-ext-R5-AuditEvent.severity.html) |
| [AuditEvent.occurred[x]](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.occurred](StructureDefinition-ext-R5-AuditEvent.occurred.html) |
| [AuditEvent.recorded](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseElementSameName` | [AuditEvent.recorded](https://hl7.org/fhir/R4B/AuditEvent.html#resource) |
| [AuditEvent.outcome](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseElementSameName` | [AuditEvent.outcome](https://hl7.org/fhir/R4B/AuditEvent.html#resource) |
| [AuditEvent.outcome.code](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.outcome.code](StructureDefinition-ext-R5-AuditEvent.ou.code.html) |
| [AuditEvent.outcome.detail](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.outcome.detail](StructureDefinition-ext-R5-AuditEvent.ou.detail.html) |
| [AuditEvent.authorization](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseElementRenamed` | [AuditEvent.purposeOfEvent](https://hl7.org/fhir/R4B/AuditEvent.html#resource) |
| [AuditEvent.basedOn](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.basedOn](StructureDefinition-ext-R5-AuditEvent.basedOn.html) |
| [AuditEvent.patient](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.patient](StructureDefinition-ext-R5-AuditEvent.patient.html) |
| [AuditEvent.encounter](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.encounter](StructureDefinition-ext-R5-AuditEvent.encounter.html) |
| [AuditEvent.agent](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseElementSameName` | [AuditEvent.agent](https://hl7.org/fhir/R4B/AuditEvent.html#resource) |
| [AuditEvent.agent.type](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseElementSameName` | [AuditEvent.agent.type](https://hl7.org/fhir/R4B/AuditEvent.html#resource) |
| [AuditEvent.agent.role](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseElementSameName` | [AuditEvent.agent.role](https://hl7.org/fhir/R4B/AuditEvent.html#resource) |
| [AuditEvent.agent.who](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.agent.who](StructureDefinition-ext-R5-AuditEvent.ag.who.html) |
| [AuditEvent.agent.requestor](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseElementSameName` | [AuditEvent.agent.requestor](https://hl7.org/fhir/R4B/AuditEvent.html#resource) |
| [AuditEvent.agent.location](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseElementSameName` | [AuditEvent.agent.location](https://hl7.org/fhir/R4B/AuditEvent.html#resource) |
| [AuditEvent.agent.policy](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseElementSameName` | [AuditEvent.agent.policy](https://hl7.org/fhir/R4B/AuditEvent.html#resource) |
| [AuditEvent.agent.network[x]](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.agent.network](StructureDefinition-ext-R5-AuditEvent.ag.network.html) |
| [AuditEvent.agent.authorization](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseElementRenamed` | [AuditEvent.agent.purposeOfUse](https://hl7.org/fhir/R4B/AuditEvent.html#resource) |
| [AuditEvent.source](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseElementSameName` | [AuditEvent.source](https://hl7.org/fhir/R4B/AuditEvent.html#resource) |
| [AuditEvent.source.site](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.source.site](StructureDefinition-ext-R5-AuditEvent.so.site.html) |
| [AuditEvent.source.observer](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.source.observer](StructureDefinition-ext-R5-AuditEvent.so.observer.html) |
| [AuditEvent.source.type](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.source.type](StructureDefinition-ext-R5-AuditEvent.so.type.html) |
| [AuditEvent.entity](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseElementSameName` | [AuditEvent.entity](https://hl7.org/fhir/R4B/AuditEvent.html#resource) |
| [AuditEvent.entity.what](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseOneOf` | [AuditEvent.entity.what](https://hl7.org/fhir/R4B/AuditEvent.html#resource)<br />[AuditEvent.entity.what](https://hl7.org/fhir/R4B/AuditEvent.html#resource) |
| [AuditEvent.entity.role](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.entity.role](StructureDefinition-ext-R5-AuditEvent.en.role.html) |
| [AuditEvent.entity.securityLabel](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.entity.securityLabel](StructureDefinition-ext-R5-AuditEvent.en.securityLabel.html) |
| [AuditEvent.entity.query](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseElementSameName` | [AuditEvent.entity.query](https://hl7.org/fhir/R4B/AuditEvent.html#resource) |
| [AuditEvent.entity.detail](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseElementSameName` | [AuditEvent.entity.detail](https://hl7.org/fhir/R4B/AuditEvent.html#resource) |
| [AuditEvent.entity.detail.type](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.entity.detail.type](StructureDefinition-ext-R5-AuditEvent.en.de.type.html) |
| [AuditEvent.entity.detail.value[x]](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.entity.detail.value](StructureDefinition-ext-R5-AuditEvent.en.de.value.html) |
| [AuditEvent.entity.agent](https://hl7.org/fhir/R5/AuditEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.entity.agent](StructureDefinition-ext-R5-AuditEvent.en.agent.html) |
