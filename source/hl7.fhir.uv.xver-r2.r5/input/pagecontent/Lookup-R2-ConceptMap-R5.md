### Lookup for [FHIR R2](https://hl7.org/fhir/DSTU2/) [ConceptMap](https://hl7.org/fhir/DSTU2/ConceptMap.html) for use in [FHIR R5](https://hl7.org/fhir/R5/)

| Source Element (FHIR R2) | Usage | Target |
| -------------- | ----- | ------ |
| [ConceptMap.meta](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseElementSameName` | [ConceptMap.meta](https://hl7.org/fhir/R5/ConceptMap.html#resource) |
| [ConceptMap.implicitRules](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseElementSameName` | [ConceptMap.implicitRules](https://hl7.org/fhir/R5/ConceptMap.html#resource) |
| [ConceptMap.language](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseElementSameName` | [ConceptMap.language](https://hl7.org/fhir/R5/ConceptMap.html#resource) |
| [ConceptMap.text](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseElementSameName` | [ConceptMap.text](https://hl7.org/fhir/R5/ConceptMap.html#resource) |
| [ConceptMap.contained](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseElementSameName` | [ConceptMap.contained](https://hl7.org/fhir/R5/ConceptMap.html#resource) |
| [ConceptMap.url](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseElementSameName` | [ConceptMap.url](https://hl7.org/fhir/R5/ConceptMap.html#resource) |
| [ConceptMap.identifier](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseElementSameName` | [ConceptMap.identifier](https://hl7.org/fhir/R5/ConceptMap.html#resource) |
| [ConceptMap.version](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseElementSameName` | [ConceptMap.version](https://hl7.org/fhir/R5/ConceptMap.html#resource) |
| [ConceptMap.name](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseElementSameName` | [ConceptMap.name](https://hl7.org/fhir/R5/ConceptMap.html#resource) |
| [ConceptMap.status](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseElementSameName` | [ConceptMap.status](https://hl7.org/fhir/R5/ConceptMap.html#resource) |
| [ConceptMap.experimental](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseElementSameName` | [ConceptMap.experimental](https://hl7.org/fhir/R5/ConceptMap.html#resource) |
| [ConceptMap.publisher](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseElementSameName` | [ConceptMap.publisher](https://hl7.org/fhir/R5/ConceptMap.html#resource) |
| [ConceptMap.contact](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-ConceptMap.contact](StructureDefinition-ext-R2-ConceptMap.contact.html) |
| [ConceptMap.contact.id](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseExtensionFromAncestor` | - |
| [ConceptMap.contact.name](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseExtensionFromAncestor` | - |
| [ConceptMap.contact.telecom](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseExtensionFromAncestor` | - |
| [ConceptMap.date](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseElementSameName` | [ConceptMap.date](https://hl7.org/fhir/R5/ConceptMap.html#resource) |
| [ConceptMap.description](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseElementSameName` | [ConceptMap.description](https://hl7.org/fhir/R5/ConceptMap.html#resource) |
| [ConceptMap.useContext](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseOneOf` | [ConceptMap.useContext](https://hl7.org/fhir/R5/ConceptMap.html#resource)<br />[ConceptMap.jurisdiction](https://hl7.org/fhir/R5/ConceptMap.html#resource) |
| [ConceptMap.requirements](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseElementRenamed` | [ConceptMap.purpose](https://hl7.org/fhir/R5/ConceptMap.html#resource) |
| [ConceptMap.copyright](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseElementSameName` | [ConceptMap.copyright](https://hl7.org/fhir/R5/ConceptMap.html#resource) |
| [ConceptMap.source[x]](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-ConceptMap.source](StructureDefinition-ext-R2-ConceptMap.source.html) |
| [ConceptMap.target[x]](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-ConceptMap.target](StructureDefinition-ext-R2-ConceptMap.target.html) |
| [ConceptMap.element](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseElementRenamed` | [ConceptMap.group.element](https://hl7.org/fhir/R5/ConceptMap.html#resource) |
| [ConceptMap.element.id](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-ConceptMap.element.id](StructureDefinition-ext-R2-ConceptMap.el.id.html) |
| [ConceptMap.element.codeSystem](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-ConceptMap.element.codeSystem](StructureDefinition-ext-R2-ConceptMap.el.codeSystem.html) |
| [ConceptMap.element.code](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseElementRenamed` | [ConceptMap.group.element.code](https://hl7.org/fhir/R5/ConceptMap.html#resource) |
| [ConceptMap.element.target](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseElementRenamed` | [ConceptMap.group.element.target](https://hl7.org/fhir/R5/ConceptMap.html#resource) |
| [ConceptMap.element.target.id](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-ConceptMap.element.target.id](StructureDefinition-ext-R2-ConceptMap.el.ta.id.html) |
| [ConceptMap.element.target.codeSystem](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseElementRenamed` | [ConceptMap.group.element.target.dependsOn.value[x]](https://hl7.org/fhir/R5/ConceptMap.html#resource) |
| [ConceptMap.element.target.code](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseElementRenamed` | [ConceptMap.group.element.target.code](https://hl7.org/fhir/R5/ConceptMap.html#resource) |
| [ConceptMap.element.target.equivalence](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-ConceptMap.element.target.equivalence](StructureDefinition-ext-R2-ConceptMap.el.ta.equivalence.html) |
| [ConceptMap.element.target.comments](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseElementRenamed` | [ConceptMap.group.element.target.comment](https://hl7.org/fhir/R5/ConceptMap.html#resource) |
| [ConceptMap.element.target.dependsOn](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseElementRenamed` | [ConceptMap.group.element.target.dependsOn](https://hl7.org/fhir/R5/ConceptMap.html#resource) |
| [ConceptMap.element.target.dependsOn.id](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-ConceptMap.element.target.dependsOn.id](StructureDefinition-ext-R2-ConceptMap.el.ta.de.id.html) |
| [ConceptMap.element.target.dependsOn.element](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseElementRenamed` | [ConceptMap.group.element.target.dependsOn.attribute](https://hl7.org/fhir/R5/ConceptMap.html#resource) |
| [ConceptMap.element.target.dependsOn.codeSystem](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-ConceptMap.element.target.dependsOn.codeSystem](StructureDefinition-ext-R2-ConceptMap.el.ta.de.codeSystem.html) |
| [ConceptMap.element.target.dependsOn.code](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseElementRenamed` | [ConceptMap.group.element.target.dependsOn.value[x]](https://hl7.org/fhir/R5/ConceptMap.html#resource) |
| [ConceptMap.element.target.product](https://hl7.org/fhir/DSTU2/ConceptMap.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-ConceptMap.element.target.product](StructureDefinition-ext-R2-ConceptMap.el.ta.product.html) |
