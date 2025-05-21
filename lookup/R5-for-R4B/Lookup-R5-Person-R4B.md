### Lookup for FHIR R5 Person for use in FHIR R4B

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Person.id | UseElementRenamed | Person.id |
| Person.meta | UseElementRenamed | Person.meta |
| Person.implicitRules | UseElementRenamed | Person.implicitRules |
| Person.language | UseElementRenamed | Person.language |
| Person.text | UseElementRenamed | Person.text |
| Person.contained | UseElementRenamed | Person.contained |
| Person.extension | UseElementRenamed | Person.extension |
| Person.modifierExtension | UseElementRenamed | Person.modifierExtension |
| Person.identifier | UseElementRenamed | Person.identifier |
| Person.active | UseElementRenamed | Person.active |
| Person.name | UseElementRenamed | Person.name |
| Person.telecom | UseElementRenamed | Person.telecom |
| Person.gender | UseElementRenamed | Person.gender |
| Person.birthDate | UseElementRenamed | Person.birthDate |
| Person.deceased[x] | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Person.deceased |
| Person.address | UseElementRenamed | Person.address |
| Person.maritalStatus | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Person.maritalStatus |
| Person.photo | UseElementRenamed | Person.photo |
| Person.communication | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Person.communication |
| Person.communication.id | UseExtensionFromAncestor | - |
| Person.communication.extension | UseExtensionFromAncestor | - |
| Person.communication.modifierExtension | UseExtensionFromAncestor | - |
| Person.communication.language | UseExtensionFromAncestor | - |
| Person.communication.preferred | UseExtensionFromAncestor | - |
| Person.managingOrganization | UseElementRenamed | Person.managingOrganization |
| Person.link | UseElementRenamed | Person.link |
| Person.link.id | UseElementRenamed | Person.link.id |
| Person.link.extension | UseElementRenamed | Person.link.extension |
| Person.link.modifierExtension | UseElementRenamed | Person.link.modifierExtension |
| Person.link.target | UseElementRenamed | Person.link.target |
| Person.link.assurance | UseElementRenamed | Person.link.assurance |
