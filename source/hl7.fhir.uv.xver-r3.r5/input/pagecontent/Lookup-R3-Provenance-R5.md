### Lookup for [FHIR R3](https://hl7.org/fhir/STU3/) [Provenance](https://hl7.org/fhir/STU3/Provenance.html) for use in [FHIR R5](https://hl7.org/fhir/R5/)

| Source Element (FHIR R3) | Usage | Target |
| -------------- | ----- | ------ |
| [Provenance.meta](https://hl7.org/fhir/STU3/Provenance.html#resource) | `UseElementSameName` | [Provenance.meta](https://hl7.org/fhir/R5/Provenance.html#resource) |
| [Provenance.implicitRules](https://hl7.org/fhir/STU3/Provenance.html#resource) | `UseElementSameName` | [Provenance.implicitRules](https://hl7.org/fhir/R5/Provenance.html#resource) |
| [Provenance.language](https://hl7.org/fhir/STU3/Provenance.html#resource) | `UseElementSameName` | [Provenance.language](https://hl7.org/fhir/R5/Provenance.html#resource) |
| [Provenance.text](https://hl7.org/fhir/STU3/Provenance.html#resource) | `UseElementSameName` | [Provenance.text](https://hl7.org/fhir/R5/Provenance.html#resource) |
| [Provenance.contained](https://hl7.org/fhir/STU3/Provenance.html#resource) | `UseElementSameName` | [Provenance.contained](https://hl7.org/fhir/R5/Provenance.html#resource) |
| [Provenance.target](https://hl7.org/fhir/STU3/Provenance.html#resource) | `UseElementSameName` | [Provenance.target](https://hl7.org/fhir/R5/Provenance.html#resource) |
| [Provenance.period](https://hl7.org/fhir/STU3/Provenance.html#resource) | `UseElementRenamed` | [Provenance.occurred[x]](https://hl7.org/fhir/R5/Provenance.html#resource) |
| [Provenance.recorded](https://hl7.org/fhir/STU3/Provenance.html#resource) | `UseElementSameName` | [Provenance.recorded](https://hl7.org/fhir/R5/Provenance.html#resource) |
| [Provenance.policy](https://hl7.org/fhir/STU3/Provenance.html#resource) | `UseElementSameName` | [Provenance.policy](https://hl7.org/fhir/R5/Provenance.html#resource) |
| [Provenance.location](https://hl7.org/fhir/STU3/Provenance.html#resource) | `UseElementSameName` | [Provenance.location](https://hl7.org/fhir/R5/Provenance.html#resource) |
| [Provenance.reason](https://hl7.org/fhir/STU3/Provenance.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Provenance.reason](StructureDefinition-ext-R3-Provenance.reason.html) |
| [Provenance.activity](https://hl7.org/fhir/STU3/Provenance.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Provenance.activity](StructureDefinition-ext-R3-Provenance.activity.html) |
| [Provenance.agent](https://hl7.org/fhir/STU3/Provenance.html#resource) | `UseOneOf` | [Provenance.agent](https://hl7.org/fhir/R5/Provenance.html#resource)<br />[Provenance.agent](https://hl7.org/fhir/R5/Provenance.html#resource) |
| [Provenance.agent.role](https://hl7.org/fhir/STU3/Provenance.html#resource) | `UseElementSameName` | [Provenance.agent.role](https://hl7.org/fhir/R5/Provenance.html#resource) |
| [Provenance.agent.who[x]](https://hl7.org/fhir/STU3/Provenance.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Provenance.agent.who](StructureDefinition-ext-R3-Provenance.ag.who.html) |
| [Provenance.agent.onBehalfOf[x]](https://hl7.org/fhir/STU3/Provenance.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Provenance.agent.onBehalfOf](StructureDefinition-ext-R3-Provenance.ag.onBehalfOf.html) |
| [Provenance.agent.relatedAgentType](https://hl7.org/fhir/STU3/Provenance.html#resource) | `UseElementRenamed` | [Provenance.agent.type](https://hl7.org/fhir/R5/Provenance.html#resource) |
| [Provenance.entity](https://hl7.org/fhir/STU3/Provenance.html#resource) | `UseElementSameName` | [Provenance.entity](https://hl7.org/fhir/R5/Provenance.html#resource) |
| [Provenance.entity.role](https://hl7.org/fhir/STU3/Provenance.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Provenance.entity.role](StructureDefinition-ext-R3-Provenance.en.role.html) |
| [Provenance.entity.what[x]](https://hl7.org/fhir/STU3/Provenance.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-Provenance.entity.what](StructureDefinition-ext-R3-Provenance.en.what.html) |
| [Provenance.entity.agent](https://hl7.org/fhir/STU3/Provenance.html#resource) | `UseElementSameName` | [Provenance.entity.agent](https://hl7.org/fhir/R5/Provenance.html#resource) |
| [Provenance.signature](https://hl7.org/fhir/STU3/Provenance.html#resource) | `UseElementSameName` | [Provenance.signature](https://hl7.org/fhir/R5/Provenance.html#resource) |
