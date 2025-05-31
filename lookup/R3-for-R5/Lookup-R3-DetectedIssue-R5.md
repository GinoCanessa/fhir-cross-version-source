### Lookup for FHIR R3 DetectedIssue for use in FHIR R5

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| DetectedIssue.id | UseElementSameName | DetectedIssue.id |
| DetectedIssue.meta | UseElementSameName | DetectedIssue.meta |
| DetectedIssue.implicitRules | UseElementSameName | DetectedIssue.implicitRules |
| DetectedIssue.language | UseElementSameName | DetectedIssue.language |
| DetectedIssue.text | UseElementSameName | DetectedIssue.text |
| DetectedIssue.contained | UseElementSameName | DetectedIssue.contained |
| DetectedIssue.extension | UseElementSameName | DetectedIssue.extension |
| DetectedIssue.modifierExtension | UseElementSameName | DetectedIssue.modifierExtension |
| DetectedIssue.identifier | UseElementSameName | DetectedIssue.identifier |
| DetectedIssue.status | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DetectedIssue.status |
| DetectedIssue.category | UseElementRenamed | DetectedIssue.code |
| DetectedIssue.severity | UseElementSameName | DetectedIssue.severity |
| DetectedIssue.patient | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DetectedIssue.patient |
| DetectedIssue.date | UseElementRenamed | DetectedIssue.identified[x] |
| DetectedIssue.author | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DetectedIssue.author |
| DetectedIssue.implicated | UseElementSameName | DetectedIssue.implicated |
| DetectedIssue.detail | UseElementSameName | DetectedIssue.detail |
| DetectedIssue.reference | UseElementSameName | DetectedIssue.reference |
| DetectedIssue.mitigation | UseElementSameName | DetectedIssue.mitigation |
| DetectedIssue.mitigation.id | UseElementSameName | DetectedIssue.mitigation.id |
| DetectedIssue.mitigation.extension | UseElementSameName | DetectedIssue.mitigation.extension |
| DetectedIssue.mitigation.modifierExtension | UseElementSameName | DetectedIssue.mitigation.modifierExtension |
| DetectedIssue.mitigation.action | UseElementSameName | DetectedIssue.mitigation.action |
| DetectedIssue.mitigation.date | UseElementSameName | DetectedIssue.mitigation.date |
| DetectedIssue.mitigation.author | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DetectedIssue.mitigation.author |
