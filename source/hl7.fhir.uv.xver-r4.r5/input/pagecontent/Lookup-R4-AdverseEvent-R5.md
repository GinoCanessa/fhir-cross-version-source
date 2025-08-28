### Lookup for [FHIR R4](https://hl7.org/fhir/R4/) [AdverseEvent](https://hl7.org/fhir/R4/AdverseEvent.html) for use in [FHIR R5](https://hl7.org/fhir/R5/)

| Source Element (FHIR R4) | Usage | Target |
| -------------- | ----- | ------ |
| [AdverseEvent.meta](https://hl7.org/fhir/R4/AdverseEvent.html#resource) | `UseElementSameName` | [AdverseEvent.meta](https://hl7.org/fhir/R5/AdverseEvent.html#resource) |
| [AdverseEvent.implicitRules](https://hl7.org/fhir/R4/AdverseEvent.html#resource) | `UseElementSameName` | [AdverseEvent.implicitRules](https://hl7.org/fhir/R5/AdverseEvent.html#resource) |
| [AdverseEvent.language](https://hl7.org/fhir/R4/AdverseEvent.html#resource) | `UseElementSameName` | [AdverseEvent.language](https://hl7.org/fhir/R5/AdverseEvent.html#resource) |
| [AdverseEvent.text](https://hl7.org/fhir/R4/AdverseEvent.html#resource) | `UseElementSameName` | [AdverseEvent.text](https://hl7.org/fhir/R5/AdverseEvent.html#resource) |
| [AdverseEvent.contained](https://hl7.org/fhir/R4/AdverseEvent.html#resource) | `UseElementSameName` | [AdverseEvent.contained](https://hl7.org/fhir/R5/AdverseEvent.html#resource) |
| [AdverseEvent.identifier](https://hl7.org/fhir/R4/AdverseEvent.html#resource) | `UseElementSameName` | [AdverseEvent.identifier](https://hl7.org/fhir/R5/AdverseEvent.html#resource) |
| [AdverseEvent.actuality](https://hl7.org/fhir/R4/AdverseEvent.html#resource) | `UseElementSameName` | [AdverseEvent.actuality](https://hl7.org/fhir/R5/AdverseEvent.html#resource) |
| [AdverseEvent.category](https://hl7.org/fhir/R4/AdverseEvent.html#resource) | `UseElementSameName` | [AdverseEvent.category](https://hl7.org/fhir/R5/AdverseEvent.html#resource) |
| [AdverseEvent.event](https://hl7.org/fhir/R4/AdverseEvent.html#resource) | `UseElementRenamed` | [AdverseEvent.code](https://hl7.org/fhir/R5/AdverseEvent.html#resource) |
| [AdverseEvent.subject](https://hl7.org/fhir/R4/AdverseEvent.html#resource) | `UseElementSameName` | [AdverseEvent.subject](https://hl7.org/fhir/R5/AdverseEvent.html#resource) |
| [AdverseEvent.encounter](https://hl7.org/fhir/R4/AdverseEvent.html#resource) | `UseElementSameName` | [AdverseEvent.encounter](https://hl7.org/fhir/R5/AdverseEvent.html#resource) |
| [AdverseEvent.date](https://hl7.org/fhir/R4/AdverseEvent.html#resource) | `UseElementRenamed` | [AdverseEvent.occurrence[x]](https://hl7.org/fhir/R5/AdverseEvent.html#resource) |
| [AdverseEvent.detected](https://hl7.org/fhir/R4/AdverseEvent.html#resource) | `UseElementSameName` | [AdverseEvent.detected](https://hl7.org/fhir/R5/AdverseEvent.html#resource) |
| [AdverseEvent.recordedDate](https://hl7.org/fhir/R4/AdverseEvent.html#resource) | `UseElementSameName` | [AdverseEvent.recordedDate](https://hl7.org/fhir/R5/AdverseEvent.html#resource) |
| [AdverseEvent.resultingCondition](https://hl7.org/fhir/R4/AdverseEvent.html#resource) | `UseElementRenamed` | [AdverseEvent.resultingEffect](https://hl7.org/fhir/R5/AdverseEvent.html#resource) |
| [AdverseEvent.location](https://hl7.org/fhir/R4/AdverseEvent.html#resource) | `UseElementSameName` | [AdverseEvent.location](https://hl7.org/fhir/R5/AdverseEvent.html#resource) |
| [AdverseEvent.seriousness](https://hl7.org/fhir/R4/AdverseEvent.html#resource) | `UseElementSameName` | [AdverseEvent.seriousness](https://hl7.org/fhir/R5/AdverseEvent.html#resource) |
| [AdverseEvent.severity](https://hl7.org/fhir/R4/AdverseEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.0/StructureDefinition/extension-AdverseEvent.severity](StructureDefinition-ext-R4-AdverseEvent.severity.html) |
| [AdverseEvent.outcome](https://hl7.org/fhir/R4/AdverseEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.0/StructureDefinition/extension-AdverseEvent.outcome](StructureDefinition-ext-R4-AdverseEvent.outcome.html) |
| [AdverseEvent.recorder](https://hl7.org/fhir/R4/AdverseEvent.html#resource) | `UseElementSameName` | [AdverseEvent.recorder](https://hl7.org/fhir/R5/AdverseEvent.html#resource) |
| [AdverseEvent.contributor](https://hl7.org/fhir/R4/AdverseEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.0/StructureDefinition/extension-AdverseEvent.contributor](StructureDefinition-ext-R4-AdverseEvent.contributor.html) |
| [AdverseEvent.suspectEntity](https://hl7.org/fhir/R4/AdverseEvent.html#resource) | `UseElementSameName` | [AdverseEvent.suspectEntity](https://hl7.org/fhir/R5/AdverseEvent.html#resource) |
| [AdverseEvent.suspectEntity.instance](https://hl7.org/fhir/R4/AdverseEvent.html#resource) | `UseElementRenamed` | [AdverseEvent.suspectEntity.instance[x]](https://hl7.org/fhir/R5/AdverseEvent.html#resource) |
| [AdverseEvent.suspectEntity.causality](https://hl7.org/fhir/R4/AdverseEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.0/StructureDefinition/extension-AdverseEvent.suspectEntity.causality](StructureDefinition-ext-R4-AdverseEvent.su.causality.html) |
| [AdverseEvent.suspectEntity.causality.assessment](https://hl7.org/fhir/R4/AdverseEvent.html#resource) | `UseExtensionFromAncestor` | - |
| [AdverseEvent.suspectEntity.causality.productRelatedness](https://hl7.org/fhir/R4/AdverseEvent.html#resource) | `UseExtensionFromAncestor` | - |
| [AdverseEvent.suspectEntity.causality.author](https://hl7.org/fhir/R4/AdverseEvent.html#resource) | `UseExtensionFromAncestor` | - |
| [AdverseEvent.suspectEntity.causality.method](https://hl7.org/fhir/R4/AdverseEvent.html#resource) | `UseExtensionFromAncestor` | - |
| [AdverseEvent.subjectMedicalHistory](https://hl7.org/fhir/R4/AdverseEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.0/StructureDefinition/extension-AdverseEvent.subjectMedicalHistory](StructureDefinition-ext-R4-AdverseEvent.subjectMedicalHistory.html) |
| [AdverseEvent.referenceDocument](https://hl7.org/fhir/R4/AdverseEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.0/StructureDefinition/extension-AdverseEvent.referenceDocument](StructureDefinition-ext-R4-AdverseEvent.referenceDocument.html) |
| [AdverseEvent.study](https://hl7.org/fhir/R4/AdverseEvent.html#resource) | `UseElementSameName` | [AdverseEvent.study](https://hl7.org/fhir/R5/AdverseEvent.html#resource) |
