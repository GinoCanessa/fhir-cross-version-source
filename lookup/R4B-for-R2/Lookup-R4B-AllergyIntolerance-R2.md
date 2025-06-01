### Lookup for FHIR R4B AllergyIntolerance for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| AllergyIntolerance.id | UseElementSameName | AllergyIntolerance.id |
| AllergyIntolerance.meta | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-AllergyIntolerance.meta |
| AllergyIntolerance.implicitRules | UseElementSameName | AllergyIntolerance.implicitRules |
| AllergyIntolerance.language | UseElementSameName | AllergyIntolerance.language |
| AllergyIntolerance.text | UseElementSameName | AllergyIntolerance.text |
| AllergyIntolerance.contained | UseElementSameName | AllergyIntolerance.contained |
| AllergyIntolerance.extension | UseElementSameName | AllergyIntolerance.extension |
| AllergyIntolerance.modifierExtension | UseElementSameName | AllergyIntolerance.modifierExtension |
| AllergyIntolerance.identifier | UseElementSameName | AllergyIntolerance.identifier |
| AllergyIntolerance.clinicalStatus | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-AllergyIntolerance.clinicalStatus |
| AllergyIntolerance.verificationStatus | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-AllergyIntolerance.verificationStatus |
| AllergyIntolerance.type | UseElementSameName | AllergyIntolerance.type |
| AllergyIntolerance.category | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-AllergyIntolerance.category |
| AllergyIntolerance.criticality | UseElementSameName | AllergyIntolerance.criticality |
| AllergyIntolerance.code | UseElementRenamed | AllergyIntolerance.substance |
| AllergyIntolerance.patient | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-AllergyIntolerance.patient |
| AllergyIntolerance.encounter | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-AllergyIntolerance.encounter |
| AllergyIntolerance.onset[x] | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-AllergyIntolerance.onset |
| AllergyIntolerance.recordedDate | UseElementSameName | AllergyIntolerance.recordedDate |
| AllergyIntolerance.recorder | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-AllergyIntolerance.recorder |
| AllergyIntolerance.asserter | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-AllergyIntolerance.asserter |
| AllergyIntolerance.lastOccurrence | UseElementRenamed | AllergyIntolerance.lastOccurence |
| AllergyIntolerance.note | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-AllergyIntolerance.note |
| AllergyIntolerance.reaction | UseElementSameName | AllergyIntolerance.reaction |
| AllergyIntolerance.reaction.id | UseElementSameName | AllergyIntolerance.reaction.id |
| AllergyIntolerance.reaction.extension | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-AllergyIntolerance.reaction.extension |
| AllergyIntolerance.reaction.modifierExtension | UseElementSameName | AllergyIntolerance.reaction.modifierExtension |
| AllergyIntolerance.reaction.substance | UseElementSameName | AllergyIntolerance.reaction.substance |
| AllergyIntolerance.reaction.manifestation | UseElementSameName | AllergyIntolerance.reaction.manifestation |
| AllergyIntolerance.reaction.description | UseElementSameName | AllergyIntolerance.reaction.description |
| AllergyIntolerance.reaction.onset | UseElementSameName | AllergyIntolerance.reaction.onset |
| AllergyIntolerance.reaction.severity | UseElementSameName | AllergyIntolerance.reaction.severity |
| AllergyIntolerance.reaction.exposureRoute | UseElementSameName | AllergyIntolerance.reaction.exposureRoute |
| AllergyIntolerance.reaction.note | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-AllergyIntolerance.reaction.note |
