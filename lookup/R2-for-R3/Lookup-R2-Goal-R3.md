### Lookup for FHIR R2 Goal for use in FHIR R3

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Goal.id | UseElementSameName | Goal.id |
| Goal.meta | UseElementSameName | Goal.meta |
| Goal.implicitRules | UseElementSameName | Goal.implicitRules |
| Goal.language | UseElementSameName | Goal.language |
| Goal.text | UseElementSameName | Goal.text |
| Goal.contained | UseElementSameName | Goal.contained |
| Goal.extension | UseElementSameName | Goal.extension |
| Goal.modifierExtension | UseElementSameName | Goal.modifierExtension |
| Goal.identifier | UseElementSameName | Goal.identifier |
| Goal.subject | UseElementSameName | Goal.subject |
| Goal.start[x] | UseElementSameName | Goal.start[x] |
| Goal.target[x] | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Goal.target |
| Goal.category | UseElementSameName | Goal.category |
| Goal.description | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Goal.description |
| Goal.status | UseOneOfElements | Goal.status,Goal.status |
| Goal.statusDate | UseElementSameName | Goal.statusDate |
| Goal.statusReason | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Goal.statusReason |
| Goal.author | UseElementRenamed | Goal.expressedBy |
| Goal.priority | UseElementSameName | Goal.priority |
| Goal.addresses | UseElementSameName | Goal.addresses |
| Goal.note | UseElementSameName | Goal.note |
| Goal.outcome | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Goal.outcome |
| Goal.outcome.id | UseExtensionFromAncestor | - |
| Goal.outcome.extension | UseExtensionFromAncestor | - |
| Goal.outcome.modifierExtension | UseExtensionFromAncestor | - |
| Goal.outcome.result[x] | UseExtensionFromAncestor | - |
