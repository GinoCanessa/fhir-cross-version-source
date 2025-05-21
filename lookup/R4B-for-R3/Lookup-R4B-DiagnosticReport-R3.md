### Lookup for FHIR R4B DiagnosticReport for use in FHIR R3

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
| DiagnosticReport.basedOn | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-DiagnosticReport.basedOn |
| DiagnosticReport.status | UseElementSameName | DiagnosticReport.status |
| DiagnosticReport.category | UseElementSameName | DiagnosticReport.category |
| DiagnosticReport.code | UseElementSameName | DiagnosticReport.code |
| DiagnosticReport.subject | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-DiagnosticReport.subject |
| DiagnosticReport.encounter | UseElementSameName | DiagnosticReport.context |
| DiagnosticReport.effective[x] | UseElementSameName | DiagnosticReport.effective[x] |
| DiagnosticReport.issued | UseElementSameName | DiagnosticReport.issued |
| DiagnosticReport.performer | UseElementSameName | DiagnosticReport.performer |
| DiagnosticReport.resultsInterpreter | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-DiagnosticReport.resultsInterpreter |
| DiagnosticReport.specimen | UseElementSameName | DiagnosticReport.specimen |
| DiagnosticReport.result | UseElementSameName | DiagnosticReport.result |
| DiagnosticReport.imagingStudy | UseElementSameName | DiagnosticReport.imagingStudy |
| DiagnosticReport.media | UseElementSameName | DiagnosticReport.image |
| DiagnosticReport.media.id | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-DiagnosticReport.media.id |
| DiagnosticReport.media.extension | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-DiagnosticReport.media.extension |
| DiagnosticReport.media.modifierExtension | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-DiagnosticReport.media.modifierExtension |
| DiagnosticReport.media.comment | UseElementSameName | DiagnosticReport.image.comment |
| DiagnosticReport.media.link | UseElementSameName | DiagnosticReport.image.link |
| DiagnosticReport.conclusion | UseElementSameName | DiagnosticReport.conclusion |
| DiagnosticReport.conclusionCode | UseElementSameName | DiagnosticReport.codedDiagnosis |
| DiagnosticReport.presentedForm | UseElementSameName | DiagnosticReport.presentedForm |
