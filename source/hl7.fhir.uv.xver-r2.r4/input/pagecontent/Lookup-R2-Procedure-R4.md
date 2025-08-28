### Lookup for [FHIR R2](https://hl7.org/fhir/DSTU2/) [Procedure](https://hl7.org/fhir/DSTU2/Procedure.html) for use in [FHIR R4](https://hl7.org/fhir/R4/)

| Source Element (FHIR R2) | Usage | Target |
| -------------- | ----- | ------ |
| [Procedure.meta](https://hl7.org/fhir/DSTU2/Procedure.html#resource) | `UseElementSameName` | [Procedure.meta](https://hl7.org/fhir/R4/Procedure.html#resource) |
| [Procedure.implicitRules](https://hl7.org/fhir/DSTU2/Procedure.html#resource) | `UseElementSameName` | [Procedure.implicitRules](https://hl7.org/fhir/R4/Procedure.html#resource) |
| [Procedure.language](https://hl7.org/fhir/DSTU2/Procedure.html#resource) | `UseElementSameName` | [Procedure.language](https://hl7.org/fhir/R4/Procedure.html#resource) |
| [Procedure.text](https://hl7.org/fhir/DSTU2/Procedure.html#resource) | `UseElementSameName` | [Procedure.text](https://hl7.org/fhir/R4/Procedure.html#resource) |
| [Procedure.contained](https://hl7.org/fhir/DSTU2/Procedure.html#resource) | `UseElementSameName` | [Procedure.contained](https://hl7.org/fhir/R4/Procedure.html#resource) |
| [Procedure.identifier](https://hl7.org/fhir/DSTU2/Procedure.html#resource) | `UseElementSameName` | [Procedure.identifier](https://hl7.org/fhir/R4/Procedure.html#resource) |
| [Procedure.subject](https://hl7.org/fhir/DSTU2/Procedure.html#resource) | `UseElementSameName` | [Procedure.subject](https://hl7.org/fhir/R4/Procedure.html#resource) |
| [Procedure.status](https://hl7.org/fhir/DSTU2/Procedure.html#resource) | `UseElementSameName` | [Procedure.status](https://hl7.org/fhir/R4/Procedure.html#resource) |
| [Procedure.category](https://hl7.org/fhir/DSTU2/Procedure.html#resource) | `UseElementSameName` | [Procedure.category](https://hl7.org/fhir/R4/Procedure.html#resource) |
| [Procedure.code](https://hl7.org/fhir/DSTU2/Procedure.html#resource) | `UseElementSameName` | [Procedure.code](https://hl7.org/fhir/R4/Procedure.html#resource) |
| [Procedure.notPerformed](https://hl7.org/fhir/DSTU2/Procedure.html#resource) | `UseElementRenamed` | [Procedure.status](https://hl7.org/fhir/R4/Procedure.html#resource) |
| [Procedure.reasonNotPerformed](https://hl7.org/fhir/DSTU2/Procedure.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Procedure.reasonNotPerformed](StructureDefinition-ext-R2-Procedure.reasonNotPerformed.html) |
| [Procedure.bodySite](https://hl7.org/fhir/DSTU2/Procedure.html#resource) | `UseElementSameName` | [Procedure.bodySite](https://hl7.org/fhir/R4/Procedure.html#resource) |
| [Procedure.reason[x]](https://hl7.org/fhir/DSTU2/Procedure.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Procedure.reason](StructureDefinition-ext-R2-Procedure.reason.html) |
| [Procedure.performer](https://hl7.org/fhir/DSTU2/Procedure.html#resource) | `UseElementSameName` | [Procedure.performer](https://hl7.org/fhir/R4/Procedure.html#resource) |
| [Procedure.performer.id](https://hl7.org/fhir/DSTU2/Procedure.html#resource) | `UseElementSameName` | [Procedure.performer.id](https://hl7.org/fhir/R4/Procedure.html#resource) |
| [Procedure.performer.actor](https://hl7.org/fhir/DSTU2/Procedure.html#resource) | `UseElementSameName` | [Procedure.performer.actor](https://hl7.org/fhir/R4/Procedure.html#resource) |
| [Procedure.performer.role](https://hl7.org/fhir/DSTU2/Procedure.html#resource) | `UseElementRenamed` | [Procedure.performer.function](https://hl7.org/fhir/R4/Procedure.html#resource) |
| [Procedure.performed[x]](https://hl7.org/fhir/DSTU2/Procedure.html#resource) | `UseElementSameName` | [Procedure.performed[x]](https://hl7.org/fhir/R4/Procedure.html#resource) |
| [Procedure.encounter](https://hl7.org/fhir/DSTU2/Procedure.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Procedure.encounter](StructureDefinition-ext-R2-Procedure.encounter.html) |
| [Procedure.location](https://hl7.org/fhir/DSTU2/Procedure.html#resource) | `UseElementSameName` | [Procedure.location](https://hl7.org/fhir/R4/Procedure.html#resource) |
| [Procedure.outcome](https://hl7.org/fhir/DSTU2/Procedure.html#resource) | `UseElementSameName` | [Procedure.outcome](https://hl7.org/fhir/R4/Procedure.html#resource) |
| [Procedure.report](https://hl7.org/fhir/DSTU2/Procedure.html#resource) | `UseElementSameName` | [Procedure.report](https://hl7.org/fhir/R4/Procedure.html#resource) |
| [Procedure.complication](https://hl7.org/fhir/DSTU2/Procedure.html#resource) | `UseElementSameName` | [Procedure.complication](https://hl7.org/fhir/R4/Procedure.html#resource) |
| [Procedure.followUp](https://hl7.org/fhir/DSTU2/Procedure.html#resource) | `UseElementSameName` | [Procedure.followUp](https://hl7.org/fhir/R4/Procedure.html#resource) |
| [Procedure.request](https://hl7.org/fhir/DSTU2/Procedure.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Procedure.request](StructureDefinition-ext-R2-Procedure.request.html) |
| [Procedure.notes](https://hl7.org/fhir/DSTU2/Procedure.html#resource) | `UseElementRenamed` | [Procedure.note](https://hl7.org/fhir/R4/Procedure.html#resource) |
| [Procedure.focalDevice](https://hl7.org/fhir/DSTU2/Procedure.html#resource) | `UseElementSameName` | [Procedure.focalDevice](https://hl7.org/fhir/R4/Procedure.html#resource) |
| [Procedure.focalDevice.id](https://hl7.org/fhir/DSTU2/Procedure.html#resource) | `UseElementSameName` | [Procedure.focalDevice.id](https://hl7.org/fhir/R4/Procedure.html#resource) |
| [Procedure.focalDevice.action](https://hl7.org/fhir/DSTU2/Procedure.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-Procedure.focalDevice.action](StructureDefinition-ext-R2-Procedure.fo.action.html) |
| [Procedure.focalDevice.manipulated](https://hl7.org/fhir/DSTU2/Procedure.html#resource) | `UseElementSameName` | [Procedure.focalDevice.manipulated](https://hl7.org/fhir/R4/Procedure.html#resource) |
| [Procedure.used](https://hl7.org/fhir/DSTU2/Procedure.html#resource) | `UseElementRenamed` | [Procedure.usedReference](https://hl7.org/fhir/R4/Procedure.html#resource) |
