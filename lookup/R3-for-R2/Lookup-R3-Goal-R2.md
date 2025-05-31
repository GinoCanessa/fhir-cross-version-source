### Lookup for FHIR R3 Goal for use in FHIR R2

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
| Goal.status | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Goal.status |
| Goal.category | UseElementSameName | Goal.category |
| Goal.priority | UseElementSameName | Goal.priority |
| Goal.description | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Goal.description |
| Goal.subject | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Goal.subject |
| Goal.start[x] | UseElementSameName | Goal.start[x] |
| Goal.target | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Goal.target |
| Goal.target.id | UseExtensionFromAncestor | - |
| Goal.target.extension | UseExtensionFromAncestor | - |
| Goal.target.modifierExtension | UseExtensionFromAncestor | - |
| Goal.target.measure | UseExtensionFromAncestor | - |
| Goal.target.detail[x] | UseExtensionFromAncestor | - |
| Goal.target.due[x] | UseExtensionFromAncestor | - |
| Goal.statusDate | UseElementSameName | Goal.statusDate |
| Goal.statusReason | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Goal.statusReason |
| Goal.expressedBy | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Goal.expressedBy |
| Goal.addresses | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Goal.addresses |
| Goal.note | UseElementSameName | Goal.note |
| Goal.outcomeCode | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Goal.outcomeCode |
| Goal.outcomeReference | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Goal.outcomeReference |
