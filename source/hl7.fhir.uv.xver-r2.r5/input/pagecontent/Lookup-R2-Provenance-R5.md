### Lookup for [FHIR R2](https://hl7.org/fhir/DSTU2/) [Provenance](https://hl7.org/fhir/DSTU2/Provenance.html) for use in [FHIR R5](https://hl7.org/fhir/R5/)

| Source Element (FHIR R2) | Usage | Target |
| -------------- | ----- | ------ |
| [Provenance.meta](https://hl7.org/fhir/DSTU2/Provenance.html#resource) | `UseElementSameName` | [Provenance.meta](https://hl7.org/fhir/R5/Provenance.html#resource) |
| [Provenance.implicitRules](https://hl7.org/fhir/DSTU2/Provenance.html#resource) | `UseElementSameName` | [Provenance.implicitRules](https://hl7.org/fhir/R5/Provenance.html#resource) |
| [Provenance.language](https://hl7.org/fhir/DSTU2/Provenance.html#resource) | `UseElementSameName` | [Provenance.language](https://hl7.org/fhir/R5/Provenance.html#resource) |
| [Provenance.text](https://hl7.org/fhir/DSTU2/Provenance.html#resource) | `UseElementSameName` | [Provenance.text](https://hl7.org/fhir/R5/Provenance.html#resource) |
| [Provenance.contained](https://hl7.org/fhir/DSTU2/Provenance.html#resource) | `UseElementSameName` | [Provenance.contained](https://hl7.org/fhir/R5/Provenance.html#resource) |
| [Provenance.target](https://hl7.org/fhir/DSTU2/Provenance.html#resource) | `UseElementSameName` | [Provenance.target](https://hl7.org/fhir/R5/Provenance.html#resource) |
| [Provenance.period](https://hl7.org/fhir/DSTU2/Provenance.html#resource) | `UseElementRenamed` | [Provenance.occurred[x]](https://hl7.org/fhir/R5/Provenance.html#resource) |
| [Provenance.recorded](https://hl7.org/fhir/DSTU2/Provenance.html#resource) | `UseElementSameName` | [Provenance.recorded](https://hl7.org/fhir/R5/Provenance.html#resource) |
| [Provenance.reason](https://hl7.org/fhir/DSTU2/Provenance.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Provenance.reason](StructureDefinition-ext-R2-Provenance.reason.html) |
| [Provenance.activity](https://hl7.org/fhir/DSTU2/Provenance.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Provenance.activity](StructureDefinition-ext-R2-Provenance.activity.html) |
| [Provenance.location](https://hl7.org/fhir/DSTU2/Provenance.html#resource) | `UseElementSameName` | [Provenance.location](https://hl7.org/fhir/R5/Provenance.html#resource) |
| [Provenance.policy](https://hl7.org/fhir/DSTU2/Provenance.html#resource) | `UseElementSameName` | [Provenance.policy](https://hl7.org/fhir/R5/Provenance.html#resource) |
| [Provenance.agent](https://hl7.org/fhir/DSTU2/Provenance.html#resource) | `UseElementSameName` | [Provenance.agent](https://hl7.org/fhir/R5/Provenance.html#resource) |
| [Provenance.agent.id](https://hl7.org/fhir/DSTU2/Provenance.html#resource) | `UseElementSameName` | [Provenance.agent.id](https://hl7.org/fhir/R5/Provenance.html#resource) |
| [Provenance.agent.role](https://hl7.org/fhir/DSTU2/Provenance.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Provenance.agent.role](StructureDefinition-ext-R2-Provenance.ag.role.html) |
| [Provenance.agent.actor](https://hl7.org/fhir/DSTU2/Provenance.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Provenance.agent.actor](StructureDefinition-ext-R2-Provenance.ag.actor.html) |
| [Provenance.agent.userId](https://hl7.org/fhir/DSTU2/Provenance.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Provenance.agent.userId](StructureDefinition-ext-R2-Provenance.ag.userId.html) |
| [Provenance.agent.relatedAgent](https://hl7.org/fhir/DSTU2/Provenance.html#resource) | `UseElementRenamed` | [Provenance.agent](https://hl7.org/fhir/R5/Provenance.html#resource) |
| [Provenance.agent.relatedAgent.id](https://hl7.org/fhir/DSTU2/Provenance.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Provenance.agent.relatedAgent.id](StructureDefinition-ext-R2-Provenance.ag.re.id.html) |
| [Provenance.agent.relatedAgent.type](https://hl7.org/fhir/DSTU2/Provenance.html#resource) | `UseElementRenamed` | [Provenance.agent.type](https://hl7.org/fhir/R5/Provenance.html#resource) |
| [Provenance.agent.relatedAgent.target](https://hl7.org/fhir/DSTU2/Provenance.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Provenance.agent.relatedAgent.target](StructureDefinition-ext-R2-Provenance.ag.re.target.html) |
| [Provenance.entity](https://hl7.org/fhir/DSTU2/Provenance.html#resource) | `UseElementSameName` | [Provenance.entity](https://hl7.org/fhir/R5/Provenance.html#resource) |
| [Provenance.entity.id](https://hl7.org/fhir/DSTU2/Provenance.html#resource) | `UseElementSameName` | [Provenance.entity.id](https://hl7.org/fhir/R5/Provenance.html#resource) |
| [Provenance.entity.role](https://hl7.org/fhir/DSTU2/Provenance.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Provenance.entity.role](StructureDefinition-ext-R2-Provenance.en.role.html) |
| [Provenance.entity.type](https://hl7.org/fhir/DSTU2/Provenance.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Provenance.entity.type](StructureDefinition-ext-R2-Provenance.en.type.html) |
| [Provenance.entity.reference](https://hl7.org/fhir/DSTU2/Provenance.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Provenance.entity.reference](StructureDefinition-ext-R2-Provenance.en.reference.html) |
| [Provenance.entity.display](https://hl7.org/fhir/DSTU2/Provenance.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Provenance.entity.display](StructureDefinition-ext-R2-Provenance.en.display.html) |
| [Provenance.entity.agent](https://hl7.org/fhir/DSTU2/Provenance.html#resource) | `UseElementSameName` | [Provenance.entity.agent](https://hl7.org/fhir/R5/Provenance.html#resource) |
| [Provenance.signature](https://hl7.org/fhir/DSTU2/Provenance.html#resource) | `UseElementSameName` | [Provenance.signature](https://hl7.org/fhir/R5/Provenance.html#resource) |
