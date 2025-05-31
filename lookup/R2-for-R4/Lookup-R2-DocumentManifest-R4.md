### Lookup for FHIR R2 DocumentManifest for use in FHIR R4

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| DocumentManifest.id | UseElementSameName | DocumentManifest.id |
| DocumentManifest.meta | UseElementSameName | DocumentManifest.meta |
| DocumentManifest.implicitRules | UseElementSameName | DocumentManifest.implicitRules |
| DocumentManifest.language | UseElementSameName | DocumentManifest.language |
| DocumentManifest.text | UseElementSameName | DocumentManifest.text |
| DocumentManifest.contained | UseElementSameName | DocumentManifest.contained |
| DocumentManifest.extension | UseElementSameName | DocumentManifest.extension |
| DocumentManifest.modifierExtension | UseElementSameName | DocumentManifest.modifierExtension |
| DocumentManifest.masterIdentifier | UseElementSameName | DocumentManifest.masterIdentifier |
| DocumentManifest.identifier | UseElementSameName | DocumentManifest.identifier |
| DocumentManifest.subject | UseElementSameName | DocumentManifest.subject |
| DocumentManifest.recipient | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DocumentManifest.recipient |
| DocumentManifest.type | UseElementSameName | DocumentManifest.type |
| DocumentManifest.author | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DocumentManifest.author |
| DocumentManifest.created | UseElementSameName | DocumentManifest.created |
| DocumentManifest.source | UseElementSameName | DocumentManifest.source |
| DocumentManifest.status | UseElementSameName | DocumentManifest.status |
| DocumentManifest.description | UseElementSameName | DocumentManifest.description |
| DocumentManifest.content | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DocumentManifest.content |
| DocumentManifest.content.id | UseExtensionFromAncestor | - |
| DocumentManifest.content.extension | UseExtensionFromAncestor | - |
| DocumentManifest.content.modifierExtension | UseExtensionFromAncestor | - |
| DocumentManifest.content.p[x] | UseExtensionFromAncestor | - |
| DocumentManifest.related | UseElementSameName | DocumentManifest.related |
| DocumentManifest.related.id | UseElementSameName | DocumentManifest.related.id |
| DocumentManifest.related.extension | UseElementSameName | DocumentManifest.related.extension |
| DocumentManifest.related.modifierExtension | UseElementSameName | DocumentManifest.related.modifierExtension |
| DocumentManifest.related.identifier | UseElementSameName | DocumentManifest.related.identifier |
| DocumentManifest.related.ref | UseElementSameName | DocumentManifest.related.ref |
