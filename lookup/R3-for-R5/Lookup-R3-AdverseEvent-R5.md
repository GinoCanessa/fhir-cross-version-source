### Lookup for FHIR R3 AdverseEvent for use in FHIR R5

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| AdverseEvent.id | UseElementSameName | AdverseEvent.id |
| AdverseEvent.meta | UseElementSameName | AdverseEvent.meta |
| AdverseEvent.implicitRules | UseElementSameName | AdverseEvent.implicitRules |
| AdverseEvent.language | UseElementSameName | AdverseEvent.language |
| AdverseEvent.text | UseElementSameName | AdverseEvent.text |
| AdverseEvent.contained | UseElementSameName | AdverseEvent.contained |
| AdverseEvent.extension | UseElementSameName | AdverseEvent.extension |
| AdverseEvent.modifierExtension | UseElementSameName | AdverseEvent.modifierExtension |
| AdverseEvent.identifier | UseElementSameName | AdverseEvent.identifier |
| AdverseEvent.category | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.category |
| AdverseEvent.type | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.type |
| AdverseEvent.subject | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.subject |
| AdverseEvent.date | UseElementRenamed | AdverseEvent.occurrence[x] |
| AdverseEvent.reaction | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.reaction |
| AdverseEvent.location | UseElementSameName | AdverseEvent.location |
| AdverseEvent.seriousness | UseElementSameName | AdverseEvent.seriousness |
| AdverseEvent.outcome | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.outcome |
| AdverseEvent.recorder | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.recorder |
| AdverseEvent.eventParticipant | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.eventParticipant |
| AdverseEvent.description | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.description |
| AdverseEvent.suspectEntity | UseElementSameName | AdverseEvent.suspectEntity |
| AdverseEvent.suspectEntity.id | UseElementSameName | AdverseEvent.suspectEntity.id |
| AdverseEvent.suspectEntity.extension | UseElementSameName | AdverseEvent.suspectEntity.extension |
| AdverseEvent.suspectEntity.modifierExtension | UseElementSameName | AdverseEvent.suspectEntity.modifierExtension |
| AdverseEvent.suspectEntity.instance | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.suspectEntity.instance |
| AdverseEvent.suspectEntity.causality | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.suspectEntity.causality |
| AdverseEvent.suspectEntity.causalityAssessment | UseElementRenamed | AdverseEvent.suspectEntity.causality.assessmentMethod |
| AdverseEvent.suspectEntity.causalityProductRelatedness | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.suspectEntity.causalityProductRelatedness |
| AdverseEvent.suspectEntity.causalityMethod | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.suspectEntity.causalityMethod |
| AdverseEvent.suspectEntity.causalityAuthor | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.suspectEntity.causalityAuthor |
| AdverseEvent.suspectEntity.causalityResult | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.suspectEntity.causalityResult |
| AdverseEvent.subjectMedicalHistory | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.subjectMedicalHistory |
| AdverseEvent.referenceDocument | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.referenceDocument |
| AdverseEvent.study | UseElementSameName | AdverseEvent.study |
