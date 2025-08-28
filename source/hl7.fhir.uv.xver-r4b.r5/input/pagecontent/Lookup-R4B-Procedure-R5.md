### Lookup for [FHIR R4B](https://hl7.org/fhir/R4B/) [Procedure](https://hl7.org/fhir/R4B/Procedure.html) for use in [FHIR R5](https://hl7.org/fhir/R5/)

| Source Element (FHIR R4B) | Usage | Target |
| -------------- | ----- | ------ |
| [Procedure.meta](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseElementSameName` | [Procedure.meta](https://hl7.org/fhir/R5/Procedure.html#resource) |
| [Procedure.implicitRules](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseElementSameName` | [Procedure.implicitRules](https://hl7.org/fhir/R5/Procedure.html#resource) |
| [Procedure.language](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseElementSameName` | [Procedure.language](https://hl7.org/fhir/R5/Procedure.html#resource) |
| [Procedure.text](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseElementSameName` | [Procedure.text](https://hl7.org/fhir/R5/Procedure.html#resource) |
| [Procedure.contained](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseElementSameName` | [Procedure.contained](https://hl7.org/fhir/R5/Procedure.html#resource) |
| [Procedure.identifier](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseElementSameName` | [Procedure.identifier](https://hl7.org/fhir/R5/Procedure.html#resource) |
| [Procedure.instantiatesCanonical](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseElementSameName` | [Procedure.instantiatesCanonical](https://hl7.org/fhir/R5/Procedure.html#resource) |
| [Procedure.instantiatesUri](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseElementSameName` | [Procedure.instantiatesUri](https://hl7.org/fhir/R5/Procedure.html#resource) |
| [Procedure.basedOn](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseElementSameName` | [Procedure.basedOn](https://hl7.org/fhir/R5/Procedure.html#resource) |
| [Procedure.partOf](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseElementSameName` | [Procedure.partOf](https://hl7.org/fhir/R5/Procedure.html#resource) |
| [Procedure.status](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseOneOf` | [Procedure.status](https://hl7.org/fhir/R5/Procedure.html#resource)<br />[Procedure.status](https://hl7.org/fhir/R5/Procedure.html#resource) |
| [Procedure.statusReason](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseElementSameName` | [Procedure.statusReason](https://hl7.org/fhir/R5/Procedure.html#resource) |
| [Procedure.category](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseElementSameName` | [Procedure.category](https://hl7.org/fhir/R5/Procedure.html#resource) |
| [Procedure.code](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseElementSameName` | [Procedure.code](https://hl7.org/fhir/R5/Procedure.html#resource) |
| [Procedure.subject](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseElementSameName` | [Procedure.subject](https://hl7.org/fhir/R5/Procedure.html#resource) |
| [Procedure.encounter](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseElementSameName` | [Procedure.encounter](https://hl7.org/fhir/R5/Procedure.html#resource) |
| [Procedure.performed[x]](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseElementRenamed` | [Procedure.occurrence[x]](https://hl7.org/fhir/R5/Procedure.html#resource) |
| [Procedure.recorder](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseElementSameName` | [Procedure.recorder](https://hl7.org/fhir/R5/Procedure.html#resource) |
| [Procedure.asserter](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.3/StructureDefinition/extension-Procedure.asserter](StructureDefinition-ext-R4B-Procedure.asserter.html) |
| [Procedure.performer](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseElementSameName` | [Procedure.performer](https://hl7.org/fhir/R5/Procedure.html#resource) |
| [Procedure.performer.function](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseElementSameName` | [Procedure.performer.function](https://hl7.org/fhir/R5/Procedure.html#resource) |
| [Procedure.performer.actor](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseElementSameName` | [Procedure.performer.actor](https://hl7.org/fhir/R5/Procedure.html#resource) |
| [Procedure.performer.onBehalfOf](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseElementSameName` | [Procedure.performer.onBehalfOf](https://hl7.org/fhir/R5/Procedure.html#resource) |
| [Procedure.location](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseElementSameName` | [Procedure.location](https://hl7.org/fhir/R5/Procedure.html#resource) |
| [Procedure.reasonCode](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.3/StructureDefinition/extension-Procedure.reasonCode](StructureDefinition-ext-R4B-Procedure.reasonCode.html) |
| [Procedure.reasonReference](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.3/StructureDefinition/extension-Procedure.reasonReference](StructureDefinition-ext-R4B-Procedure.reasonReference.html) |
| [Procedure.bodySite](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseElementSameName` | [Procedure.bodySite](https://hl7.org/fhir/R5/Procedure.html#resource) |
| [Procedure.outcome](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseElementSameName` | [Procedure.outcome](https://hl7.org/fhir/R5/Procedure.html#resource) |
| [Procedure.report](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseElementSameName` | [Procedure.report](https://hl7.org/fhir/R5/Procedure.html#resource) |
| [Procedure.complication](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.3/StructureDefinition/extension-Procedure.complication](StructureDefinition-ext-R4B-Procedure.complication.html) |
| [Procedure.complicationDetail](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.3/StructureDefinition/extension-Procedure.complicationDetail](StructureDefinition-ext-R4B-Procedure.complicationDetail.html) |
| [Procedure.followUp](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseElementSameName` | [Procedure.followUp](https://hl7.org/fhir/R5/Procedure.html#resource) |
| [Procedure.note](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseElementSameName` | [Procedure.note](https://hl7.org/fhir/R5/Procedure.html#resource) |
| [Procedure.focalDevice](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseElementSameName` | [Procedure.focalDevice](https://hl7.org/fhir/R5/Procedure.html#resource) |
| [Procedure.focalDevice.action](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseElementSameName` | [Procedure.focalDevice.action](https://hl7.org/fhir/R5/Procedure.html#resource) |
| [Procedure.focalDevice.manipulated](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseElementSameName` | [Procedure.focalDevice.manipulated](https://hl7.org/fhir/R5/Procedure.html#resource) |
| [Procedure.usedReference](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.3/StructureDefinition/extension-Procedure.usedReference](StructureDefinition-ext-R4B-Procedure.usedReference.html) |
| [Procedure.usedCode](https://hl7.org/fhir/R4B/Procedure.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.3/StructureDefinition/extension-Procedure.usedCode](StructureDefinition-ext-R4B-Procedure.usedCode.html) |
