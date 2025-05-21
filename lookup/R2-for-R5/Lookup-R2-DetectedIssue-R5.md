### Lookup for FHIR R2 DetectedIssue for use in FHIR R5

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| DetectedIssue.id | UseElementSameName | DetectedIssue.id |
| DetectedIssue.meta | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DetectedIssue.meta |
| DetectedIssue.implicitRules | UseElementSameName | DetectedIssue.implicitRules |
| DetectedIssue.language | UseElementSameName | DetectedIssue.language |
| DetectedIssue.text | UseElementSameName | DetectedIssue.text |
| DetectedIssue.contained | UseElementSameName | DetectedIssue.contained |
| DetectedIssue.extension | UseElementSameName | DetectedIssue.extension |
| DetectedIssue.modifierExtension | UseElementSameName | DetectedIssue.modifierExtension |
| DetectedIssue.patient | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DetectedIssue.patient |
| DetectedIssue.category | UseElementRenamed | DetectedIssue.code |
| DetectedIssue.severity | UseElementSameName | DetectedIssue.severity |
| DetectedIssue.implicated | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DetectedIssue.implicated |
| DetectedIssue.detail | UseElementSameName | DetectedIssue.detail |
| DetectedIssue.date | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DetectedIssue.date |
| DetectedIssue.author | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DetectedIssue.author |
| DetectedIssue.identifier | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DetectedIssue.identifier |
| DetectedIssue.reference | UseElementSameName | DetectedIssue.reference |
| DetectedIssue.mitigation | UseElementSameName | DetectedIssue.mitigation |
| DetectedIssue.mitigation.id | UseElementSameName | DetectedIssue.mitigation.id |
| DetectedIssue.mitigation.extension | UseElementSameName | DetectedIssue.mitigation.extension |
| DetectedIssue.mitigation.modifierExtension | UseElementSameName | DetectedIssue.mitigation.modifierExtension |
| DetectedIssue.mitigation.action | UseElementSameName | DetectedIssue.mitigation.action |
| DetectedIssue.mitigation.date | UseElementSameName | DetectedIssue.mitigation.date |
| DetectedIssue.mitigation.author | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DetectedIssue.mitigation.author |
