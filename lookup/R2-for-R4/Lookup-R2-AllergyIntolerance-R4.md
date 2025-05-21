### Lookup for FHIR R2 AllergyIntolerance for use in FHIR R4

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| AllergyIntolerance.id | UseElementSameName | AllergyIntolerance.id |
| AllergyIntolerance.meta | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-AllergyIntolerance.meta |
| AllergyIntolerance.implicitRules | UseElementSameName | AllergyIntolerance.implicitRules |
| AllergyIntolerance.language | UseElementSameName | AllergyIntolerance.language |
| AllergyIntolerance.text | UseElementSameName | AllergyIntolerance.text |
| AllergyIntolerance.contained | UseElementSameName | AllergyIntolerance.contained |
| AllergyIntolerance.extension | UseElementSameName | AllergyIntolerance.extension |
| AllergyIntolerance.modifierExtension | UseElementSameName | AllergyIntolerance.modifierExtension |
| AllergyIntolerance.identifier | UseElementSameName | AllergyIntolerance.identifier |
| AllergyIntolerance.onset | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-AllergyIntolerance.onset |
| AllergyIntolerance.recordedDate | UseElementSameName | AllergyIntolerance.recordedDate |
| AllergyIntolerance.recorder | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-AllergyIntolerance.recorder |
| AllergyIntolerance.patient | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-AllergyIntolerance.patient |
| AllergyIntolerance.reporter | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-AllergyIntolerance.reporter |
| AllergyIntolerance.substance | UseElementRenamed | AllergyIntolerance.code |
| AllergyIntolerance.status | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-AllergyIntolerance.status |
| AllergyIntolerance.criticality | UseElementSameName | AllergyIntolerance.criticality |
| AllergyIntolerance.type | UseElementSameName | AllergyIntolerance.type |
| AllergyIntolerance.category | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-AllergyIntolerance.category |
| AllergyIntolerance.lastOccurence | UseElementRenamed | AllergyIntolerance.lastOccurrence |
| AllergyIntolerance.note | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-AllergyIntolerance.note |
| AllergyIntolerance.reaction | UseElementSameName | AllergyIntolerance.reaction |
| AllergyIntolerance.reaction.id | UseElementSameName | AllergyIntolerance.reaction.id |
| AllergyIntolerance.reaction.extension | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-AllergyIntolerance.reaction.extension |
| AllergyIntolerance.reaction.modifierExtension | UseElementSameName | AllergyIntolerance.reaction.modifierExtension |
| AllergyIntolerance.reaction.substance | UseElementSameName | AllergyIntolerance.reaction.substance |
| AllergyIntolerance.reaction.certainty | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-AllergyIntolerance.reaction.certainty |
| AllergyIntolerance.reaction.manifestation | UseElementSameName | AllergyIntolerance.reaction.manifestation |
| AllergyIntolerance.reaction.description | UseElementSameName | AllergyIntolerance.reaction.description |
| AllergyIntolerance.reaction.onset | UseElementSameName | AllergyIntolerance.reaction.onset |
| AllergyIntolerance.reaction.severity | UseElementSameName | AllergyIntolerance.reaction.severity |
| AllergyIntolerance.reaction.exposureRoute | UseElementSameName | AllergyIntolerance.reaction.exposureRoute |
| AllergyIntolerance.reaction.note | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-AllergyIntolerance.reaction.note |
