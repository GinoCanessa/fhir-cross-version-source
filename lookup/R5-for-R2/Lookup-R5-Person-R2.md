### Lookup for FHIR R5 Person for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Person.id | UseElementSameName | Person.id |
| Person.meta | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Person.meta |
| Person.implicitRules | UseElementSameName | Person.implicitRules |
| Person.language | UseElementSameName | Person.language |
| Person.text | UseElementSameName | Person.text |
| Person.contained | UseElementSameName | Person.contained |
| Person.extension | UseElementSameName | Person.extension |
| Person.modifierExtension | UseElementSameName | Person.modifierExtension |
| Person.identifier | UseElementSameName | Person.identifier |
| Person.active | UseElementSameName | Person.active |
| Person.name | UseElementSameName | Person.name |
| Person.telecom | UseElementSameName | Person.telecom |
| Person.gender | UseElementSameName | Person.gender |
| Person.birthDate | UseElementSameName | Person.birthDate |
| Person.deceased[x] | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Person.deceased |
| Person.address | UseElementSameName | Person.address |
| Person.maritalStatus | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Person.maritalStatus |
| Person.photo | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Person.photo |
| Person.communication | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Person.communication |
| Person.communication.id | UseExtensionFromAncestor | - |
| Person.communication.extension | UseExtensionFromAncestor | - |
| Person.communication.modifierExtension | UseExtensionFromAncestor | - |
| Person.communication.language | UseExtensionFromAncestor | - |
| Person.communication.preferred | UseExtensionFromAncestor | - |
| Person.managingOrganization | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Person.managingOrganization |
| Person.link | UseElementSameName | Person.link |
| Person.link.id | UseElementSameName | Person.link.id |
| Person.link.extension | UseElementSameName | Person.link.extension |
| Person.link.modifierExtension | UseElementSameName | Person.link.modifierExtension |
| Person.link.target | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Person.link.target |
| Person.link.assurance | UseElementSameName | Person.link.assurance |
