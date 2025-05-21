### Lookup for FHIR R4 BodyStructure for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| BodyStructure.id | UseElementSameName | BodySite.id |
| BodyStructure.meta | UseElementSameName | BodySite.meta |
| BodyStructure.implicitRules | UseElementSameName | BodySite.implicitRules |
| BodyStructure.language | UseElementSameName | BodySite.language |
| BodyStructure.text | UseElementSameName | BodySite.text |
| BodyStructure.contained | UseElementSameName | BodySite.contained |
| BodyStructure.extension | UseElementSameName | BodySite.extension |
| BodyStructure.modifierExtension | UseElementSameName | BodySite.modifierExtension |
| BodyStructure.identifier | UseElementSameName | BodySite.identifier |
| BodyStructure.active | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-BodyStructure.active |
| BodyStructure.morphology | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-BodyStructure.morphology |
| BodyStructure.location | UseElementSameName | BodySite.code |
| BodyStructure.locationQualifier | UseElementSameName | BodySite.modifier |
| BodyStructure.description | UseElementSameName | BodySite.description |
| BodyStructure.image | UseElementSameName | BodySite.image |
| BodyStructure.patient | UseElementSameName | BodySite.patient |
