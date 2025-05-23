### Lookup for FHIR R3 DiagnosticReport for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| DiagnosticReport.id | UseElementSameName | DiagnosticReport.id |
| DiagnosticReport.meta | UseElementSameName | DiagnosticReport.meta |
| DiagnosticReport.implicitRules | UseElementSameName | DiagnosticReport.implicitRules |
| DiagnosticReport.language | UseElementSameName | DiagnosticReport.language |
| DiagnosticReport.text | UseElementSameName | DiagnosticReport.text |
| DiagnosticReport.contained | UseElementSameName | DiagnosticReport.contained |
| DiagnosticReport.extension | UseElementSameName | DiagnosticReport.extension |
| DiagnosticReport.modifierExtension | UseElementSameName | DiagnosticReport.modifierExtension |
| DiagnosticReport.identifier | UseElementSameName | DiagnosticReport.identifier |
| DiagnosticReport.basedOn | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DiagnosticReport.basedOn |
| DiagnosticReport.status | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DiagnosticReport.status |
| DiagnosticReport.category | UseElementSameName | DiagnosticReport.category |
| DiagnosticReport.code | UseElementSameName | DiagnosticReport.code |
| DiagnosticReport.subject | UseElementSameName | DiagnosticReport.subject |
| DiagnosticReport.context | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DiagnosticReport.context |
| DiagnosticReport.effective[x] | UseElementSameName | DiagnosticReport.effective[x] |
| DiagnosticReport.issued | UseElementSameName | DiagnosticReport.issued |
| DiagnosticReport.performer | UseElementSameName | DiagnosticReport.performer |
| DiagnosticReport.performer.id | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DiagnosticReport.performer.id |
| DiagnosticReport.performer.extension | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DiagnosticReport.performer.extension |
| DiagnosticReport.performer.modifierExtension | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DiagnosticReport.performer.modifierExtension |
| DiagnosticReport.performer.role | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DiagnosticReport.performer.role |
| DiagnosticReport.performer.actor | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DiagnosticReport.performer.actor |
| DiagnosticReport.specimen | UseElementSameName | DiagnosticReport.specimen |
| DiagnosticReport.result | UseElementSameName | DiagnosticReport.result |
| DiagnosticReport.imagingStudy | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-DiagnosticReport.imagingStudy |
| DiagnosticReport.image | UseElementRenamed | DiagnosticReport.image |
| DiagnosticReport.image.id | UseElementRenamed | DiagnosticReport.image.id |
| DiagnosticReport.image.extension | UseElementRenamed | DiagnosticReport.image.extension |
| DiagnosticReport.image.modifierExtension | UseElementRenamed | DiagnosticReport.image.modifierExtension |
| DiagnosticReport.image.comment | UseElementRenamed | DiagnosticReport.image.comment |
| DiagnosticReport.image.link | UseElementRenamed | DiagnosticReport.image.link |
| DiagnosticReport.conclusion | UseElementSameName | DiagnosticReport.conclusion |
| DiagnosticReport.codedDiagnosis | UseElementRenamed | DiagnosticReport.codedDiagnosis |
| DiagnosticReport.presentedForm | UseElementSameName | DiagnosticReport.presentedForm |
