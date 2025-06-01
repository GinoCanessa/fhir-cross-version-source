### Lookup for FHIR R5 ResearchSubject for use in FHIR R4B

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| ResearchSubject.id | UseElementSameName | ResearchSubject.id |
| ResearchSubject.meta | UseElementSameName | ResearchSubject.meta |
| ResearchSubject.implicitRules | UseElementSameName | ResearchSubject.implicitRules |
| ResearchSubject.language | UseElementSameName | ResearchSubject.language |
| ResearchSubject.text | UseElementSameName | ResearchSubject.text |
| ResearchSubject.contained | UseElementSameName | ResearchSubject.contained |
| ResearchSubject.extension | UseElementSameName | ResearchSubject.extension |
| ResearchSubject.modifierExtension | UseElementSameName | ResearchSubject.modifierExtension |
| ResearchSubject.identifier | UseElementSameName | ResearchSubject.identifier |
| ResearchSubject.status | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ResearchSubject.status |
| ResearchSubject.progress | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ResearchSubject.progress |
| ResearchSubject.progress.id | UseExtensionFromAncestor | - |
| ResearchSubject.progress.extension | UseExtensionFromAncestor | - |
| ResearchSubject.progress.modifierExtension | UseExtensionFromAncestor | - |
| ResearchSubject.progress.type | UseExtensionFromAncestor | - |
| ResearchSubject.progress.subjectState | UseExtensionFromAncestor | - |
| ResearchSubject.progress.milestone | UseExtensionFromAncestor | - |
| ResearchSubject.progress.reason | UseExtensionFromAncestor | - |
| ResearchSubject.progress.startDate | UseExtensionFromAncestor | - |
| ResearchSubject.progress.endDate | UseExtensionFromAncestor | - |
| ResearchSubject.period | UseElementSameName | ResearchSubject.period |
| ResearchSubject.study | UseElementSameName | ResearchSubject.study |
| ResearchSubject.subject | UseElementRenamed | ResearchSubject.individual |
| ResearchSubject.assignedComparisonGroup | UseElementRenamed | ResearchSubject.assignedArm |
| ResearchSubject.actualComparisonGroup | UseElementRenamed | ResearchSubject.actualArm |
| ResearchSubject.consent | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ResearchSubject.consent |
