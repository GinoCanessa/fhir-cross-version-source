### Lookup for FHIR R2 SearchParameter for use in FHIR R4B

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| SearchParameter.id | UseElementSameName | SearchParameter.id |
| SearchParameter.meta | UseElementSameName | SearchParameter.meta |
| SearchParameter.implicitRules | UseElementSameName | SearchParameter.implicitRules |
| SearchParameter.language | UseElementSameName | SearchParameter.language |
| SearchParameter.text | UseElementSameName | SearchParameter.text |
| SearchParameter.contained | UseElementSameName | SearchParameter.contained |
| SearchParameter.extension | UseElementSameName | SearchParameter.extension |
| SearchParameter.modifierExtension | UseElementSameName | SearchParameter.modifierExtension |
| SearchParameter.url | UseElementSameName | SearchParameter.url |
| SearchParameter.name | UseElementSameName | SearchParameter.name |
| SearchParameter.status | UseElementSameName | SearchParameter.status |
| SearchParameter.experimental | UseElementSameName | SearchParameter.experimental |
| SearchParameter.publisher | UseElementSameName | SearchParameter.publisher |
| SearchParameter.contact | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-SearchParameter.contact |
| SearchParameter.contact.id | UseExtensionFromAncestor | - |
| SearchParameter.contact.extension | UseExtensionFromAncestor | - |
| SearchParameter.contact.modifierExtension | UseExtensionFromAncestor | - |
| SearchParameter.contact.name | UseExtensionFromAncestor | - |
| SearchParameter.contact.telecom | UseExtensionFromAncestor | - |
| SearchParameter.date | UseElementSameName | SearchParameter.date |
| SearchParameter.requirements | UseElementRenamed | SearchParameter.purpose |
| SearchParameter.code | UseElementSameName | SearchParameter.code |
| SearchParameter.base | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-SearchParameter.base |
| SearchParameter.type | UseElementSameName | SearchParameter.type |
| SearchParameter.description | UseElementSameName | SearchParameter.description |
| SearchParameter.xpath | UseElementSameName | SearchParameter.xpath |
| SearchParameter.xpathUsage | UseElementSameName | SearchParameter.xpathUsage |
| SearchParameter.target | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-SearchParameter.target |
