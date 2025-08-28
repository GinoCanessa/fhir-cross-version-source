### Lookup for [FHIR R3](https://hl7.org/fhir/STU3/) [DiagnosticReport](https://hl7.org/fhir/STU3/DiagnosticReport.html) for use in [FHIR R5](https://hl7.org/fhir/R5/)

| Source Element (FHIR R3) | Usage | Target |
| -------------- | ----- | ------ |
| [DiagnosticReport.meta](https://hl7.org/fhir/STU3/DiagnosticReport.html#resource) | `UseElementSameName` | [DiagnosticReport.meta](https://hl7.org/fhir/R5/DiagnosticReport.html#resource) |
| [DiagnosticReport.implicitRules](https://hl7.org/fhir/STU3/DiagnosticReport.html#resource) | `UseElementSameName` | [DiagnosticReport.implicitRules](https://hl7.org/fhir/R5/DiagnosticReport.html#resource) |
| [DiagnosticReport.language](https://hl7.org/fhir/STU3/DiagnosticReport.html#resource) | `UseElementSameName` | [DiagnosticReport.language](https://hl7.org/fhir/R5/DiagnosticReport.html#resource) |
| [DiagnosticReport.text](https://hl7.org/fhir/STU3/DiagnosticReport.html#resource) | `UseElementSameName` | [DiagnosticReport.text](https://hl7.org/fhir/R5/DiagnosticReport.html#resource) |
| [DiagnosticReport.contained](https://hl7.org/fhir/STU3/DiagnosticReport.html#resource) | `UseElementSameName` | [DiagnosticReport.contained](https://hl7.org/fhir/R5/DiagnosticReport.html#resource) |
| [DiagnosticReport.identifier](https://hl7.org/fhir/STU3/DiagnosticReport.html#resource) | `UseElementSameName` | [DiagnosticReport.identifier](https://hl7.org/fhir/R5/DiagnosticReport.html#resource) |
| [DiagnosticReport.basedOn](https://hl7.org/fhir/STU3/DiagnosticReport.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-DiagnosticReport.basedOn](StructureDefinition-ext-R3-DiagnosticReport.basedOn.html) |
| [DiagnosticReport.status](https://hl7.org/fhir/STU3/DiagnosticReport.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-DiagnosticReport.status](StructureDefinition-ext-R3-DiagnosticReport.status.html) |
| [DiagnosticReport.category](https://hl7.org/fhir/STU3/DiagnosticReport.html#resource) | `UseElementSameName` | [DiagnosticReport.category](https://hl7.org/fhir/R5/DiagnosticReport.html#resource) |
| [DiagnosticReport.code](https://hl7.org/fhir/STU3/DiagnosticReport.html#resource) | `UseElementSameName` | [DiagnosticReport.code](https://hl7.org/fhir/R5/DiagnosticReport.html#resource) |
| [DiagnosticReport.subject](https://hl7.org/fhir/STU3/DiagnosticReport.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-DiagnosticReport.subject](StructureDefinition-ext-R3-DiagnosticReport.subject.html) |
| [DiagnosticReport.context](https://hl7.org/fhir/STU3/DiagnosticReport.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-DiagnosticReport.context](StructureDefinition-ext-R3-DiagnosticReport.context.html) |
| [DiagnosticReport.effective[x]](https://hl7.org/fhir/STU3/DiagnosticReport.html#resource) | `UseElementSameName` | [DiagnosticReport.effective[x]](https://hl7.org/fhir/R5/DiagnosticReport.html#resource) |
| [DiagnosticReport.issued](https://hl7.org/fhir/STU3/DiagnosticReport.html#resource) | `UseElementSameName` | [DiagnosticReport.issued](https://hl7.org/fhir/R5/DiagnosticReport.html#resource) |
| [DiagnosticReport.performer](https://hl7.org/fhir/STU3/DiagnosticReport.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-DiagnosticReport.performer](StructureDefinition-ext-R3-DiagnosticReport.performer.html) |
| [DiagnosticReport.performer.role](https://hl7.org/fhir/STU3/DiagnosticReport.html#resource) | `UseExtensionFromAncestor` | - |
| [DiagnosticReport.performer.actor](https://hl7.org/fhir/STU3/DiagnosticReport.html#resource) | `UseExtensionFromAncestor` | - |
| [DiagnosticReport.specimen](https://hl7.org/fhir/STU3/DiagnosticReport.html#resource) | `UseElementSameName` | [DiagnosticReport.specimen](https://hl7.org/fhir/R5/DiagnosticReport.html#resource) |
| [DiagnosticReport.result](https://hl7.org/fhir/STU3/DiagnosticReport.html#resource) | `UseElementSameName` | [DiagnosticReport.result](https://hl7.org/fhir/R5/DiagnosticReport.html#resource) |
| [DiagnosticReport.imagingStudy](https://hl7.org/fhir/STU3/DiagnosticReport.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-DiagnosticReport.imagingStudy](StructureDefinition-ext-R3-DiagnosticReport.imagingStudy.html) |
| [DiagnosticReport.image](https://hl7.org/fhir/STU3/DiagnosticReport.html#resource) | `UseElementRenamed` | [DiagnosticReport.media](https://hl7.org/fhir/R5/DiagnosticReport.html#resource) |
| [DiagnosticReport.image.comment](https://hl7.org/fhir/STU3/DiagnosticReport.html#resource) | `UseElementRenamed` | [DiagnosticReport.media.comment](https://hl7.org/fhir/R5/DiagnosticReport.html#resource) |
| [DiagnosticReport.image.link](https://hl7.org/fhir/STU3/DiagnosticReport.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-DiagnosticReport.image.link](StructureDefinition-ext-R3-DiagnosticReport.im.link.html) |
| [DiagnosticReport.conclusion](https://hl7.org/fhir/STU3/DiagnosticReport.html#resource) | `UseElementSameName` | [DiagnosticReport.conclusion](https://hl7.org/fhir/R5/DiagnosticReport.html#resource) |
| [DiagnosticReport.codedDiagnosis](https://hl7.org/fhir/STU3/DiagnosticReport.html#resource) | `UseElementRenamed` | [DiagnosticReport.conclusionCode](https://hl7.org/fhir/R5/DiagnosticReport.html#resource) |
| [DiagnosticReport.presentedForm](https://hl7.org/fhir/STU3/DiagnosticReport.html#resource) | `UseElementSameName` | [DiagnosticReport.presentedForm](https://hl7.org/fhir/R5/DiagnosticReport.html#resource) |
