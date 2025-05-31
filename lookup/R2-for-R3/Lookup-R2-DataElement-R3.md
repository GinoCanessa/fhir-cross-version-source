### Lookup for FHIR R2 DataElement for use in FHIR R3

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| DataElement.id | UseElementSameName | DataElement.id |
| DataElement.meta | UseElementSameName | DataElement.meta |
| DataElement.implicitRules | UseElementSameName | DataElement.implicitRules |
| DataElement.language | UseElementSameName | DataElement.language |
| DataElement.text | UseElementSameName | DataElement.text |
| DataElement.contained | UseElementSameName | DataElement.contained |
| DataElement.extension | UseElementSameName | DataElement.extension |
| DataElement.modifierExtension | UseElementSameName | DataElement.modifierExtension |
| DataElement.url | UseElementSameName | DataElement.url |
| DataElement.identifier | UseElementSameName | DataElement.identifier |
| DataElement.version | UseElementSameName | DataElement.version |
| DataElement.name | UseElementSameName | DataElement.name |
| DataElement.status | UseElementSameName | DataElement.status |
| DataElement.experimental | UseElementSameName | DataElement.experimental |
| DataElement.publisher | UseElementSameName | DataElement.publisher |
| DataElement.contact | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DataElement.contact |
| DataElement.contact.id | UseExtensionFromAncestor | - |
| DataElement.contact.extension | UseExtensionFromAncestor | - |
| DataElement.contact.modifierExtension | UseExtensionFromAncestor | - |
| DataElement.contact.name | UseExtensionFromAncestor | - |
| DataElement.contact.telecom | UseExtensionFromAncestor | - |
| DataElement.date | UseElementSameName | DataElement.date |
| DataElement.useContext | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DataElement.useContext |
| DataElement.copyright | UseElementSameName | DataElement.copyright |
| DataElement.stringency | UseElementSameName | DataElement.stringency |
| DataElement.mapping | UseElementSameName | DataElement.mapping |
| DataElement.mapping.id | UseElementSameName | DataElement.mapping.id |
| DataElement.mapping.extension | UseElementSameName | DataElement.mapping.extension |
| DataElement.mapping.modifierExtension | UseElementSameName | DataElement.mapping.modifierExtension |
| DataElement.mapping.identity | UseElementSameName | DataElement.mapping.identity |
| DataElement.mapping.uri | UseElementSameName | DataElement.mapping.uri |
| DataElement.mapping.name | UseElementSameName | DataElement.mapping.name |
| DataElement.mapping.comments | UseElementRenamed | DataElement.mapping.comment |
| DataElement.element | UseElementSameName | DataElement.element |
