### Lookup for [FHIR R3](https://hl7.org/fhir/STU3/) [AdverseEvent](https://hl7.org/fhir/STU3/AdverseEvent.html) for use in [FHIR R4B](https://hl7.org/fhir/R4B/)

| Source Element (FHIR R3) | Usage | Target |
| -------------- | ----- | ------ |
| [AdverseEvent.meta](https://hl7.org/fhir/STU3/AdverseEvent.html#resource) | `UseElementSameName` | [AdverseEvent.meta](https://hl7.org/fhir/R4B/AdverseEvent.html#resource) |
| [AdverseEvent.implicitRules](https://hl7.org/fhir/STU3/AdverseEvent.html#resource) | `UseElementSameName` | [AdverseEvent.implicitRules](https://hl7.org/fhir/R4B/AdverseEvent.html#resource) |
| [AdverseEvent.language](https://hl7.org/fhir/STU3/AdverseEvent.html#resource) | `UseElementSameName` | [AdverseEvent.language](https://hl7.org/fhir/R4B/AdverseEvent.html#resource) |
| [AdverseEvent.text](https://hl7.org/fhir/STU3/AdverseEvent.html#resource) | `UseElementSameName` | [AdverseEvent.text](https://hl7.org/fhir/R4B/AdverseEvent.html#resource) |
| [AdverseEvent.contained](https://hl7.org/fhir/STU3/AdverseEvent.html#resource) | `UseElementSameName` | [AdverseEvent.contained](https://hl7.org/fhir/R4B/AdverseEvent.html#resource) |
| [AdverseEvent.identifier](https://hl7.org/fhir/STU3/AdverseEvent.html#resource) | `UseElementSameName` | [AdverseEvent.identifier](https://hl7.org/fhir/R4B/AdverseEvent.html#resource) |
| [AdverseEvent.category](https://hl7.org/fhir/STU3/AdverseEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.category](StructureDefinition-ext-R3-AdverseEvent.category.html) |
| [AdverseEvent.type](https://hl7.org/fhir/STU3/AdverseEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.type](StructureDefinition-ext-R3-AdverseEvent.type.html) |
| [AdverseEvent.subject](https://hl7.org/fhir/STU3/AdverseEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.subject](StructureDefinition-ext-R3-AdverseEvent.subject.html) |
| [AdverseEvent.date](https://hl7.org/fhir/STU3/AdverseEvent.html#resource) | `UseElementSameName` | [AdverseEvent.date](https://hl7.org/fhir/R4B/AdverseEvent.html#resource) |
| [AdverseEvent.reaction](https://hl7.org/fhir/STU3/AdverseEvent.html#resource) | `UseElementRenamed` | [AdverseEvent.resultingCondition](https://hl7.org/fhir/R4B/AdverseEvent.html#resource) |
| [AdverseEvent.location](https://hl7.org/fhir/STU3/AdverseEvent.html#resource) | `UseElementSameName` | [AdverseEvent.location](https://hl7.org/fhir/R4B/AdverseEvent.html#resource) |
| [AdverseEvent.seriousness](https://hl7.org/fhir/STU3/AdverseEvent.html#resource) | `UseElementSameName` | [AdverseEvent.seriousness](https://hl7.org/fhir/R4B/AdverseEvent.html#resource) |
| [AdverseEvent.outcome](https://hl7.org/fhir/STU3/AdverseEvent.html#resource) | `UseElementSameName` | [AdverseEvent.outcome](https://hl7.org/fhir/R4B/AdverseEvent.html#resource) |
| [AdverseEvent.recorder](https://hl7.org/fhir/STU3/AdverseEvent.html#resource) | `UseElementSameName` | [AdverseEvent.recorder](https://hl7.org/fhir/R4B/AdverseEvent.html#resource) |
| [AdverseEvent.eventParticipant](https://hl7.org/fhir/STU3/AdverseEvent.html#resource) | `UseElementRenamed` | [AdverseEvent.contributor](https://hl7.org/fhir/R4B/AdverseEvent.html#resource) |
| [AdverseEvent.description](https://hl7.org/fhir/STU3/AdverseEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.description](StructureDefinition-ext-R3-AdverseEvent.description.html) |
| [AdverseEvent.suspectEntity](https://hl7.org/fhir/STU3/AdverseEvent.html#resource) | `UseElementSameName` | [AdverseEvent.suspectEntity](https://hl7.org/fhir/R4B/AdverseEvent.html#resource) |
| [AdverseEvent.suspectEntity.instance](https://hl7.org/fhir/STU3/AdverseEvent.html#resource) | `UseElementSameName` | [AdverseEvent.suspectEntity.instance](https://hl7.org/fhir/R4B/AdverseEvent.html#resource) |
| [AdverseEvent.suspectEntity.causality](https://hl7.org/fhir/STU3/AdverseEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.suspectEntity.causality](StructureDefinition-ext-R3-AdverseEvent.su.causality.html) |
| [AdverseEvent.suspectEntity.causalityAssessment](https://hl7.org/fhir/STU3/AdverseEvent.html#resource) | `UseElementRenamed` | [AdverseEvent.suspectEntity.causality.assessment](https://hl7.org/fhir/R4B/AdverseEvent.html#resource) |
| [AdverseEvent.suspectEntity.causalityProductRelatedness](https://hl7.org/fhir/STU3/AdverseEvent.html#resource) | `UseElementRenamed` | [AdverseEvent.suspectEntity.causality.productRelatedness](https://hl7.org/fhir/R4B/AdverseEvent.html#resource) |
| [AdverseEvent.suspectEntity.causalityMethod](https://hl7.org/fhir/STU3/AdverseEvent.html#resource) | `UseElementRenamed` | [AdverseEvent.suspectEntity.causality.method](https://hl7.org/fhir/R4B/AdverseEvent.html#resource) |
| [AdverseEvent.suspectEntity.causalityAuthor](https://hl7.org/fhir/STU3/AdverseEvent.html#resource) | `UseElementRenamed` | [AdverseEvent.suspectEntity.causality.author](https://hl7.org/fhir/R4B/AdverseEvent.html#resource) |
| [AdverseEvent.suspectEntity.causalityResult](https://hl7.org/fhir/STU3/AdverseEvent.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.suspectEntity.causalityResult](StructureDefinition-ext-R3-AdverseEvent.su.causalityResult.html) |
| [AdverseEvent.subjectMedicalHistory](https://hl7.org/fhir/STU3/AdverseEvent.html#resource) | `UseElementSameName` | [AdverseEvent.subjectMedicalHistory](https://hl7.org/fhir/R4B/AdverseEvent.html#resource) |
| [AdverseEvent.referenceDocument](https://hl7.org/fhir/STU3/AdverseEvent.html#resource) | `UseElementSameName` | [AdverseEvent.referenceDocument](https://hl7.org/fhir/R4B/AdverseEvent.html#resource) |
| [AdverseEvent.study](https://hl7.org/fhir/STU3/AdverseEvent.html#resource) | `UseElementSameName` | [AdverseEvent.study](https://hl7.org/fhir/R4B/AdverseEvent.html#resource) |
