### Lookup for FHIR R3 Organization for use in FHIR R5

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Organization.id | UseElementSameName | Organization.id |
| Organization.meta | UseElementSameName | Organization.meta |
| Organization.implicitRules | UseElementSameName | Organization.implicitRules |
| Organization.language | UseElementSameName | Organization.language |
| Organization.text | UseElementSameName | Organization.text |
| Organization.contained | UseElementSameName | Organization.contained |
| Organization.extension | UseElementSameName | Organization.extension |
| Organization.modifierExtension | UseElementSameName | Organization.modifierExtension |
| Organization.identifier | UseElementSameName | Organization.identifier |
| Organization.active | UseElementSameName | Organization.active |
| Organization.type | UseElementSameName | Organization.type |
| Organization.name | UseElementSameName | Organization.name |
| Organization.alias | UseElementSameName | Organization.alias |
| Organization.telecom | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Organization.telecom |
| Organization.address | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Organization.address |
| Organization.partOf | UseElementSameName | Organization.partOf |
| Organization.contact | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Organization.contact |
| Organization.contact.id | UseExtensionFromAncestor | - |
| Organization.contact.extension | UseExtensionFromAncestor | - |
| Organization.contact.modifierExtension | UseExtensionFromAncestor | - |
| Organization.contact.purpose | UseExtensionFromAncestor | - |
| Organization.contact.name | UseExtensionFromAncestor | - |
| Organization.contact.telecom | UseExtensionFromAncestor | - |
| Organization.contact.address | UseExtensionFromAncestor | - |
| Organization.endpoint | UseElementSameName | Organization.endpoint |
