### Lookup for [FHIR R5](https://hl7.org/fhir/R5/) [Provenance](https://hl7.org/fhir/R5/Provenance.html) for use in [FHIR R4](https://hl7.org/fhir/R4/)

| Source Element (FHIR R5) | Usage | Target |
| -------------- | ----- | ------ |
| [Provenance.meta](https://hl7.org/fhir/R5/Provenance.html#resource) | `UseElementSameName` | [Provenance.meta](https://hl7.org/fhir/R4/Provenance.html#resource) |
| [Provenance.implicitRules](https://hl7.org/fhir/R5/Provenance.html#resource) | `UseElementSameName` | [Provenance.implicitRules](https://hl7.org/fhir/R4/Provenance.html#resource) |
| [Provenance.language](https://hl7.org/fhir/R5/Provenance.html#resource) | `UseElementSameName` | [Provenance.language](https://hl7.org/fhir/R4/Provenance.html#resource) |
| [Provenance.text](https://hl7.org/fhir/R5/Provenance.html#resource) | `UseElementSameName` | [Provenance.text](https://hl7.org/fhir/R4/Provenance.html#resource) |
| [Provenance.contained](https://hl7.org/fhir/R5/Provenance.html#resource) | `UseElementSameName` | [Provenance.contained](https://hl7.org/fhir/R4/Provenance.html#resource) |
| [Provenance.target](https://hl7.org/fhir/R5/Provenance.html#resource) | `UseElementSameName` | [Provenance.target](https://hl7.org/fhir/R4/Provenance.html#resource) |
| [Provenance.occurred[x]](https://hl7.org/fhir/R5/Provenance.html#resource) | `UseElementSameName` | [Provenance.occurred[x]](https://hl7.org/fhir/R4/Provenance.html#resource) |
| [Provenance.recorded](https://hl7.org/fhir/R5/Provenance.html#resource) | `UseElementSameName` | [Provenance.recorded](https://hl7.org/fhir/R4/Provenance.html#resource) |
| [Provenance.policy](https://hl7.org/fhir/R5/Provenance.html#resource) | `UseElementSameName` | [Provenance.policy](https://hl7.org/fhir/R4/Provenance.html#resource) |
| [Provenance.location](https://hl7.org/fhir/R5/Provenance.html#resource) | `UseElementSameName` | [Provenance.location](https://hl7.org/fhir/R4/Provenance.html#resource) |
| [Provenance.authorization](https://hl7.org/fhir/R5/Provenance.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-Provenance.authorization](StructureDefinition-ext-R5-Provenance.authorization.html) |
| [Provenance.activity](https://hl7.org/fhir/R5/Provenance.html#resource) | `UseElementSameName` | [Provenance.activity](https://hl7.org/fhir/R4/Provenance.html#resource) |
| [Provenance.basedOn](https://hl7.org/fhir/R5/Provenance.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-Provenance.basedOn](StructureDefinition-ext-R5-Provenance.basedOn.html) |
| [Provenance.patient](https://hl7.org/fhir/R5/Provenance.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-Provenance.patient](StructureDefinition-ext-R5-Provenance.patient.html) |
| [Provenance.encounter](https://hl7.org/fhir/R5/Provenance.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-Provenance.encounter](StructureDefinition-ext-R5-Provenance.encounter.html) |
| [Provenance.agent](https://hl7.org/fhir/R5/Provenance.html#resource) | `UseOneOf` | [Provenance.agent](https://hl7.org/fhir/R4/Provenance.html#resource)<br />[Provenance.agent](https://hl7.org/fhir/R4/Provenance.html#resource) |
| [Provenance.agent.type](https://hl7.org/fhir/R5/Provenance.html#resource) | `UseElementSameName` | [Provenance.agent.type](https://hl7.org/fhir/R4/Provenance.html#resource) |
| [Provenance.agent.role](https://hl7.org/fhir/R5/Provenance.html#resource) | `UseElementSameName` | [Provenance.agent.role](https://hl7.org/fhir/R4/Provenance.html#resource) |
| [Provenance.agent.who](https://hl7.org/fhir/R5/Provenance.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-Provenance.agent.who](StructureDefinition-ext-R5-Provenance.ag.who.html) |
| [Provenance.agent.onBehalfOf](https://hl7.org/fhir/R5/Provenance.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-Provenance.agent.onBehalfOf](StructureDefinition-ext-R5-Provenance.ag.onBehalfOf.html) |
| [Provenance.entity](https://hl7.org/fhir/R5/Provenance.html#resource) | `UseElementSameName` | [Provenance.entity](https://hl7.org/fhir/R4/Provenance.html#resource) |
| [Provenance.entity.role](https://hl7.org/fhir/R5/Provenance.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-Provenance.entity.role](StructureDefinition-ext-R5-Provenance.en.role.html) |
| [Provenance.entity.what](https://hl7.org/fhir/R5/Provenance.html#resource) | `UseElementSameName` | [Provenance.entity.what](https://hl7.org/fhir/R4/Provenance.html#resource) |
| [Provenance.entity.agent](https://hl7.org/fhir/R5/Provenance.html#resource) | `UseElementSameName` | [Provenance.entity.agent](https://hl7.org/fhir/R4/Provenance.html#resource) |
| [Provenance.signature](https://hl7.org/fhir/R5/Provenance.html#resource) | `UseElementSameName` | [Provenance.signature](https://hl7.org/fhir/R4/Provenance.html#resource) |
