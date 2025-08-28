### Lookup for [FHIR R2](https://hl7.org/fhir/DSTU2/) [Questionnaire](https://hl7.org/fhir/DSTU2/Questionnaire.html) for use in [FHIR R4](https://hl7.org/fhir/R4/)

| Source Element (FHIR R2) | Usage | Target |
| -------------- | ----- | ------ |
| [Questionnaire.meta](https://hl7.org/fhir/DSTU2/Questionnaire.html#resource) | `UseElementSameName` | [Questionnaire.meta](https://hl7.org/fhir/R4/Questionnaire.html#resource) |
| [Questionnaire.implicitRules](https://hl7.org/fhir/DSTU2/Questionnaire.html#resource) | `UseElementSameName` | [Questionnaire.implicitRules](https://hl7.org/fhir/R4/Questionnaire.html#resource) |
| [Questionnaire.language](https://hl7.org/fhir/DSTU2/Questionnaire.html#resource) | `UseElementSameName` | [Questionnaire.language](https://hl7.org/fhir/R4/Questionnaire.html#resource) |
| [Questionnaire.text](https://hl7.org/fhir/DSTU2/Questionnaire.html#resource) | `UseElementSameName` | [Questionnaire.text](https://hl7.org/fhir/R4/Questionnaire.html#resource) |
| [Questionnaire.contained](https://hl7.org/fhir/DSTU2/Questionnaire.html#resource) | `UseElementSameName` | [Questionnaire.contained](https://hl7.org/fhir/R4/Questionnaire.html#resource) |
| [Questionnaire.identifier](https://hl7.org/fhir/DSTU2/Questionnaire.html#resource) | `UseElementSameName` | [Questionnaire.identifier](https://hl7.org/fhir/R4/Questionnaire.html#resource) |
| [Questionnaire.version](https://hl7.org/fhir/DSTU2/Questionnaire.html#resource) | `UseElementSameName` | [Questionnaire.version](https://hl7.org/fhir/R4/Questionnaire.html#resource) |
| [Questionnaire.status](https://hl7.org/fhir/DSTU2/Questionnaire.html#resource) | `UseElementSameName` | [Questionnaire.status](https://hl7.org/fhir/R4/Questionnaire.html#resource) |
| [Questionnaire.date](https://hl7.org/fhir/DSTU2/Questionnaire.html#resource) | `UseElementSameName` | [Questionnaire.date](https://hl7.org/fhir/R4/Questionnaire.html#resource) |
| [Questionnaire.publisher](https://hl7.org/fhir/DSTU2/Questionnaire.html#resource) | `UseElementSameName` | [Questionnaire.publisher](https://hl7.org/fhir/R4/Questionnaire.html#resource) |
| [Questionnaire.telecom](https://hl7.org/fhir/DSTU2/Questionnaire.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Questionnaire.telecom](StructureDefinition-ext-R2-Questionnaire.telecom.html) |
| [Questionnaire.subjectType](https://hl7.org/fhir/DSTU2/Questionnaire.html#resource) | `UseElementSameName` | [Questionnaire.subjectType](https://hl7.org/fhir/R4/Questionnaire.html#resource) |
| [Questionnaire.group](https://hl7.org/fhir/DSTU2/Questionnaire.html#resource) | `UseElementRenamed` | [Questionnaire.item](https://hl7.org/fhir/R4/Questionnaire.html#resource) |
| [Questionnaire.group.id](https://hl7.org/fhir/DSTU2/Questionnaire.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Questionnaire.group.id](StructureDefinition-ext-R2-Questionnaire.gr.id.html) |
| [Questionnaire.group.linkId](https://hl7.org/fhir/DSTU2/Questionnaire.html#resource) | `UseElementRenamed` | [Questionnaire.item.linkId](https://hl7.org/fhir/R4/Questionnaire.html#resource) |
| [Questionnaire.group.title](https://hl7.org/fhir/DSTU2/Questionnaire.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Questionnaire.group.title](StructureDefinition-ext-R2-Questionnaire.gr.title.html) |
| [Questionnaire.group.concept](https://hl7.org/fhir/DSTU2/Questionnaire.html#resource) | `UseElementRenamed` | [Questionnaire.item.code](https://hl7.org/fhir/R4/Questionnaire.html#resource) |
| [Questionnaire.group.text](https://hl7.org/fhir/DSTU2/Questionnaire.html#resource) | `UseElementRenamed` | [Questionnaire.item.text](https://hl7.org/fhir/R4/Questionnaire.html#resource) |
| [Questionnaire.group.required](https://hl7.org/fhir/DSTU2/Questionnaire.html#resource) | `UseElementRenamed` | [Questionnaire.item.required](https://hl7.org/fhir/R4/Questionnaire.html#resource) |
| [Questionnaire.group.repeats](https://hl7.org/fhir/DSTU2/Questionnaire.html#resource) | `UseElementRenamed` | [Questionnaire.item.repeats](https://hl7.org/fhir/R4/Questionnaire.html#resource) |
| [Questionnaire.group.group](https://hl7.org/fhir/DSTU2/Questionnaire.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Questionnaire.group.group](StructureDefinition-ext-R2-Questionnaire.gr.group.html) |
| [Questionnaire.group.question](https://hl7.org/fhir/DSTU2/Questionnaire.html#resource) | `UseElementRenamed` | [Questionnaire.item](https://hl7.org/fhir/R4/Questionnaire.html#resource) |
| [Questionnaire.group.question.id](https://hl7.org/fhir/DSTU2/Questionnaire.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Questionnaire.group.question.id](StructureDefinition-ext-R2-Questionnaire.gr.qu.id.html) |
| [Questionnaire.group.question.linkId](https://hl7.org/fhir/DSTU2/Questionnaire.html#resource) | `UseElementRenamed` | [Questionnaire.item.linkId](https://hl7.org/fhir/R4/Questionnaire.html#resource) |
| [Questionnaire.group.question.concept](https://hl7.org/fhir/DSTU2/Questionnaire.html#resource) | `UseElementRenamed` | [Questionnaire.item.code](https://hl7.org/fhir/R4/Questionnaire.html#resource) |
| [Questionnaire.group.question.text](https://hl7.org/fhir/DSTU2/Questionnaire.html#resource) | `UseElementRenamed` | [Questionnaire.item.text](https://hl7.org/fhir/R4/Questionnaire.html#resource) |
| [Questionnaire.group.question.type](https://hl7.org/fhir/DSTU2/Questionnaire.html#resource) | `UseOneOf` | [Questionnaire.item.type](https://hl7.org/fhir/R4/Questionnaire.html#resource)<br />[Questionnaire.item.type](https://hl7.org/fhir/R4/Questionnaire.html#resource) |
| [Questionnaire.group.question.required](https://hl7.org/fhir/DSTU2/Questionnaire.html#resource) | `UseElementRenamed` | [Questionnaire.item.required](https://hl7.org/fhir/R4/Questionnaire.html#resource) |
| [Questionnaire.group.question.repeats](https://hl7.org/fhir/DSTU2/Questionnaire.html#resource) | `UseElementRenamed` | [Questionnaire.item.repeats](https://hl7.org/fhir/R4/Questionnaire.html#resource) |
| [Questionnaire.group.question.options](https://hl7.org/fhir/DSTU2/Questionnaire.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Questionnaire.group.question.options](StructureDefinition-ext-R2-Questionnaire.gr.qu.options.html) |
| [Questionnaire.group.question.option](https://hl7.org/fhir/DSTU2/Questionnaire.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Questionnaire.group.question.option](StructureDefinition-ext-R2-Questionnaire.gr.qu.option.html) |
| [Questionnaire.group.question.group](https://hl7.org/fhir/DSTU2/Questionnaire.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Questionnaire.group.question.group](StructureDefinition-ext-R2-Questionnaire.gr.qu.group.html) |
