### Lookup for FHIR R2 DiagnosticReport for use in FHIR R5

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| DiagnosticReport.id | UseElementSameName | DiagnosticReport.id |
| DiagnosticReport.meta | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DiagnosticReport.meta |
| DiagnosticReport.implicitRules | UseElementSameName | DiagnosticReport.implicitRules |
| DiagnosticReport.language | UseElementSameName | DiagnosticReport.language |
| DiagnosticReport.text | UseElementSameName | DiagnosticReport.text |
| DiagnosticReport.contained | UseElementSameName | DiagnosticReport.contained |
| DiagnosticReport.extension | UseElementSameName | DiagnosticReport.extension |
| DiagnosticReport.modifierExtension | UseElementSameName | DiagnosticReport.modifierExtension |
| DiagnosticReport.identifier | UseElementSameName | DiagnosticReport.identifier |
| DiagnosticReport.status | UseElementSameName | DiagnosticReport.status |
| DiagnosticReport.category | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DiagnosticReport.category |
| DiagnosticReport.code | UseElementSameName | DiagnosticReport.code |
| DiagnosticReport.subject | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DiagnosticReport.subject |
| DiagnosticReport.encounter | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DiagnosticReport.encounter |
| DiagnosticReport.effective[x] | UseElementSameName | DiagnosticReport.effective[x] |
| DiagnosticReport.issued | UseElementSameName | DiagnosticReport.issued |
| DiagnosticReport.performer | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DiagnosticReport.performer |
| DiagnosticReport.request | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DiagnosticReport.request |
| DiagnosticReport.specimen | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DiagnosticReport.specimen |
| DiagnosticReport.result | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DiagnosticReport.result |
| DiagnosticReport.imagingStudy | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DiagnosticReport.imagingStudy |
| DiagnosticReport.image | UseElementRenamed | DiagnosticReport.media |
| DiagnosticReport.image.id | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DiagnosticReport.image.id |
| DiagnosticReport.image.extension | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DiagnosticReport.image.extension |
| DiagnosticReport.image.modifierExtension | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DiagnosticReport.image.modifierExtension |
| DiagnosticReport.image.comment | UseElementRenamed | DiagnosticReport.media.comment |
| DiagnosticReport.image.link | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DiagnosticReport.image.link |
| DiagnosticReport.conclusion | UseElementSameName | DiagnosticReport.conclusion |
| DiagnosticReport.codedDiagnosis | UseElementRenamed | DiagnosticReport.conclusionCode |
| DiagnosticReport.presentedForm | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-DiagnosticReport.presentedForm |
