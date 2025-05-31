### Lookup for FHIR R5 Endpoint for use in FHIR R3

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Endpoint.id | UseElementSameName | Endpoint.id |
| Endpoint.meta | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Endpoint.meta |
| Endpoint.implicitRules | UseElementSameName | Endpoint.implicitRules |
| Endpoint.language | UseElementSameName | Endpoint.language |
| Endpoint.text | UseElementSameName | Endpoint.text |
| Endpoint.contained | UseElementSameName | Endpoint.contained |
| Endpoint.extension | UseElementSameName | Endpoint.extension |
| Endpoint.modifierExtension | UseElementSameName | Endpoint.modifierExtension |
| Endpoint.identifier | UseElementSameName | Endpoint.identifier |
| Endpoint.status | UseElementSameName | Endpoint.status |
| Endpoint.connectionType | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Endpoint.connectionType |
| Endpoint.name | UseElementSameName | Endpoint.name |
| Endpoint.description | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Endpoint.description |
| Endpoint.environmentType | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Endpoint.environmentType |
| Endpoint.managingOrganization | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Endpoint.managingOrganization |
| Endpoint.contact | UseElementSameName | Endpoint.contact |
| Endpoint.period | UseElementSameName | Endpoint.period |
| Endpoint.payload | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Endpoint.payload |
| Endpoint.payload.id | UseExtensionFromAncestor | - |
| Endpoint.payload.extension | UseExtensionFromAncestor | - |
| Endpoint.payload.modifierExtension | UseExtensionFromAncestor | - |
| Endpoint.payload.type | UseExtensionFromAncestor | - |
| Endpoint.payload.mimeType | UseExtensionFromAncestor | - |
| Endpoint.address | UseElementSameName | Endpoint.address |
| Endpoint.header | UseElementSameName | Endpoint.header |
