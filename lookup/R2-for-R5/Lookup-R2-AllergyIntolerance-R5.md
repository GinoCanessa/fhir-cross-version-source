### Lookup for FHIR R2 AllergyIntolerance for use in FHIR R5

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| AllergyIntolerance.id | UseElementSameName | AllergyIntolerance.id |
| AllergyIntolerance.meta | UseElementSameName | AllergyIntolerance.meta |
| AllergyIntolerance.implicitRules | UseElementSameName | AllergyIntolerance.implicitRules |
| AllergyIntolerance.language | UseElementSameName | AllergyIntolerance.language |
| AllergyIntolerance.text | UseElementSameName | AllergyIntolerance.text |
| AllergyIntolerance.contained | UseElementSameName | AllergyIntolerance.contained |
| AllergyIntolerance.extension | UseElementSameName | AllergyIntolerance.extension |
| AllergyIntolerance.modifierExtension | UseElementSameName | AllergyIntolerance.modifierExtension |
| AllergyIntolerance.identifier | UseElementSameName | AllergyIntolerance.identifier |
| AllergyIntolerance.onset | UseElementRenamed | AllergyIntolerance.onset[x] |
| AllergyIntolerance.recordedDate | UseElementSameName | AllergyIntolerance.recordedDate |
| AllergyIntolerance.recorder | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-AllergyIntolerance.recorder |
| AllergyIntolerance.patient | UseElementSameName | AllergyIntolerance.patient |
| AllergyIntolerance.reporter | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-AllergyIntolerance.reporter |
| AllergyIntolerance.substance | UseElementRenamed | AllergyIntolerance.code |
| AllergyIntolerance.status | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-AllergyIntolerance.status |
| AllergyIntolerance.criticality | UseElementSameName | AllergyIntolerance.criticality |
| AllergyIntolerance.type | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-AllergyIntolerance.type |
| AllergyIntolerance.category | UseElementSameName | AllergyIntolerance.category |
| AllergyIntolerance.lastOccurence | UseElementRenamed | AllergyIntolerance.lastOccurrence |
| AllergyIntolerance.note | UseElementSameName | AllergyIntolerance.note |
| AllergyIntolerance.reaction | UseElementSameName | AllergyIntolerance.reaction |
| AllergyIntolerance.reaction.id | UseElementSameName | AllergyIntolerance.reaction.id |
| AllergyIntolerance.reaction.extension | UseElementSameName | AllergyIntolerance.reaction.extension |
| AllergyIntolerance.reaction.modifierExtension | UseElementSameName | AllergyIntolerance.reaction.modifierExtension |
| AllergyIntolerance.reaction.substance | UseElementSameName | AllergyIntolerance.reaction.substance |
| AllergyIntolerance.reaction.certainty | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-AllergyIntolerance.reaction.certainty |
| AllergyIntolerance.reaction.manifestation | UseElementSameName | AllergyIntolerance.reaction.manifestation |
| AllergyIntolerance.reaction.description | UseElementSameName | AllergyIntolerance.reaction.description |
| AllergyIntolerance.reaction.onset | UseElementSameName | AllergyIntolerance.reaction.onset |
| AllergyIntolerance.reaction.severity | UseElementSameName | AllergyIntolerance.reaction.severity |
| AllergyIntolerance.reaction.exposureRoute | UseElementSameName | AllergyIntolerance.reaction.exposureRoute |
| AllergyIntolerance.reaction.note | UseElementSameName | AllergyIntolerance.reaction.note |
