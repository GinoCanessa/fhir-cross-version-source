### Lookup for FHIR R4 DetectedIssue for use in FHIR R3

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| DetectedIssue.id | UseElementSameName | DetectedIssue.id |
| DetectedIssue.meta | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-DetectedIssue.meta |
| DetectedIssue.implicitRules | UseElementSameName | DetectedIssue.implicitRules |
| DetectedIssue.language | UseElementSameName | DetectedIssue.language |
| DetectedIssue.text | UseElementSameName | DetectedIssue.text |
| DetectedIssue.contained | UseElementSameName | DetectedIssue.contained |
| DetectedIssue.extension | UseElementSameName | DetectedIssue.extension |
| DetectedIssue.modifierExtension | UseElementSameName | DetectedIssue.modifierExtension |
| DetectedIssue.identifier | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-DetectedIssue.identifier |
| DetectedIssue.status | UseElementSameName | DetectedIssue.status |
| DetectedIssue.code | UseElementRenamed | DetectedIssue.category |
| DetectedIssue.severity | UseElementSameName | DetectedIssue.severity |
| DetectedIssue.patient | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-DetectedIssue.patient |
| DetectedIssue.identified[x] | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-DetectedIssue.identified |
| DetectedIssue.author | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-DetectedIssue.author |
| DetectedIssue.implicated | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-DetectedIssue.implicated |
| DetectedIssue.evidence | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-DetectedIssue.evidence |
| DetectedIssue.evidence.id | UseExtensionFromAncestor | - |
| DetectedIssue.evidence.extension | UseExtensionFromAncestor | - |
| DetectedIssue.evidence.modifierExtension | UseExtensionFromAncestor | - |
| DetectedIssue.evidence.code | UseExtensionFromAncestor | - |
| DetectedIssue.evidence.detail | UseExtensionFromAncestor | - |
| DetectedIssue.detail | UseElementSameName | DetectedIssue.detail |
| DetectedIssue.reference | UseElementSameName | DetectedIssue.reference |
| DetectedIssue.mitigation | UseElementSameName | DetectedIssue.mitigation |
| DetectedIssue.mitigation.id | UseElementSameName | DetectedIssue.mitigation.id |
| DetectedIssue.mitigation.extension | UseElementSameName | DetectedIssue.mitigation.extension |
| DetectedIssue.mitigation.modifierExtension | UseElementSameName | DetectedIssue.mitigation.modifierExtension |
| DetectedIssue.mitigation.action | UseElementSameName | DetectedIssue.mitigation.action |
| DetectedIssue.mitigation.date | UseElementSameName | DetectedIssue.mitigation.date |
| DetectedIssue.mitigation.author | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-DetectedIssue.mitigation.author |
