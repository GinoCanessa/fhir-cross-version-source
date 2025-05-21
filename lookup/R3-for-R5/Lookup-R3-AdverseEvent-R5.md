### Lookup for FHIR R3 AdverseEvent for use in FHIR R5

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| AdverseEvent.id | UseElementSameName | AdverseEvent.id |
| AdverseEvent.meta | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.meta |
| AdverseEvent.implicitRules | UseElementSameName | AdverseEvent.implicitRules |
| AdverseEvent.language | UseElementSameName | AdverseEvent.language |
| AdverseEvent.text | UseElementSameName | AdverseEvent.text |
| AdverseEvent.contained | UseElementSameName | AdverseEvent.contained |
| AdverseEvent.extension | UseElementSameName | AdverseEvent.extension |
| AdverseEvent.modifierExtension | UseElementSameName | AdverseEvent.modifierExtension |
| AdverseEvent.identifier | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.identifier |
| AdverseEvent.category | UseElementSameName | AdverseEvent.category |
| AdverseEvent.type | UseElementRenamed | AdverseEvent.actuality |
| AdverseEvent.subject | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.subject |
| AdverseEvent.date | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.date |
| AdverseEvent.reaction | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.reaction |
| AdverseEvent.location | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.location |
| AdverseEvent.seriousness | UseElementSameName | AdverseEvent.seriousness |
| AdverseEvent.outcome | UseElementSameName | AdverseEvent.outcome |
| AdverseEvent.recorder | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.recorder |
| AdverseEvent.eventParticipant | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.eventParticipant |
| AdverseEvent.description | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.description |
| AdverseEvent.suspectEntity | UseElementSameName | AdverseEvent.suspectEntity |
| AdverseEvent.suspectEntity.id | UseElementSameName | AdverseEvent.suspectEntity.id |
| AdverseEvent.suspectEntity.extension | UseElementSameName | AdverseEvent.suspectEntity.extension |
| AdverseEvent.suspectEntity.modifierExtension | UseElementSameName | AdverseEvent.suspectEntity.modifierExtension |
| AdverseEvent.suspectEntity.instance | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.suspectEntity.instance |
| AdverseEvent.suspectEntity.causality | UseElementSameName | AdverseEvent.suspectEntity.causality |
| AdverseEvent.suspectEntity.causalityAssessment | UseElementRenamed | AdverseEvent.suspectEntity.causality.assessmentMethod |
| AdverseEvent.suspectEntity.causalityProductRelatedness | UseElementRenamed | AdverseEvent.suspectEntity.causality.entityRelatedness |
| AdverseEvent.suspectEntity.causalityMethod | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.suspectEntity.causalityMethod |
| AdverseEvent.suspectEntity.causalityAuthor | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.suspectEntity.causalityAuthor |
| AdverseEvent.suspectEntity.causalityResult | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.suspectEntity.causalityResult |
| AdverseEvent.subjectMedicalHistory | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.subjectMedicalHistory |
| AdverseEvent.referenceDocument | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.referenceDocument |
| AdverseEvent.study | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-AdverseEvent.study |
