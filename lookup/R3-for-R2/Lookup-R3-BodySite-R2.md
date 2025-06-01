### Lookup for FHIR R3 BodySite for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| BodySite.id | UseElementSameName | BodySite.id |
| BodySite.meta | UseElementSameName | BodySite.meta |
| BodySite.implicitRules | UseElementSameName | BodySite.implicitRules |
| BodySite.language | UseElementSameName | BodySite.language |
| BodySite.text | UseElementSameName | BodySite.text |
| BodySite.contained | UseElementSameName | BodySite.contained |
| BodySite.extension | UseElementSameName | BodySite.extension |
| BodySite.modifierExtension | UseElementSameName | BodySite.modifierExtension |
| BodySite.identifier | UseElementSameName | BodySite.identifier |
| BodySite.active | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-BodySite.active |
| BodySite.code | UseElementSameName | BodySite.code |
| BodySite.qualifier | UseElementRenamed | BodySite.modifier |
| BodySite.description | UseElementSameName | BodySite.description |
| BodySite.image | UseElementSameName | BodySite.image |
| BodySite.patient | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-BodySite.patient |
