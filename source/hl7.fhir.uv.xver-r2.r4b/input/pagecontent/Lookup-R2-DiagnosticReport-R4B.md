### Lookup for [FHIR R2](https://hl7.org/fhir/DSTU2/) [DiagnosticReport](https://hl7.org/fhir/DSTU2/DiagnosticReport.html) for use in [FHIR R4B](https://hl7.org/fhir/R4B/)

| Source Element (FHIR R2) | Usage | Target |
| -------------- | ----- | ------ |
| [DiagnosticReport.meta](https://hl7.org/fhir/DSTU2/DiagnosticReport.html#resource) | `UseElementSameName` | [DiagnosticReport.meta](https://hl7.org/fhir/R4B/DiagnosticReport.html#resource) |
| [DiagnosticReport.implicitRules](https://hl7.org/fhir/DSTU2/DiagnosticReport.html#resource) | `UseElementSameName` | [DiagnosticReport.implicitRules](https://hl7.org/fhir/R4B/DiagnosticReport.html#resource) |
| [DiagnosticReport.language](https://hl7.org/fhir/DSTU2/DiagnosticReport.html#resource) | `UseElementSameName` | [DiagnosticReport.language](https://hl7.org/fhir/R4B/DiagnosticReport.html#resource) |
| [DiagnosticReport.text](https://hl7.org/fhir/DSTU2/DiagnosticReport.html#resource) | `UseElementSameName` | [DiagnosticReport.text](https://hl7.org/fhir/R4B/DiagnosticReport.html#resource) |
| [DiagnosticReport.contained](https://hl7.org/fhir/DSTU2/DiagnosticReport.html#resource) | `UseElementSameName` | [DiagnosticReport.contained](https://hl7.org/fhir/R4B/DiagnosticReport.html#resource) |
| [DiagnosticReport.identifier](https://hl7.org/fhir/DSTU2/DiagnosticReport.html#resource) | `UseElementSameName` | [DiagnosticReport.identifier](https://hl7.org/fhir/R4B/DiagnosticReport.html#resource) |
| [DiagnosticReport.status](https://hl7.org/fhir/DSTU2/DiagnosticReport.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-DiagnosticReport.status](StructureDefinition-ext-R2-DiagnosticReport.status.html) |
| [DiagnosticReport.category](https://hl7.org/fhir/DSTU2/DiagnosticReport.html#resource) | `UseElementSameName` | [DiagnosticReport.category](https://hl7.org/fhir/R4B/DiagnosticReport.html#resource) |
| [DiagnosticReport.code](https://hl7.org/fhir/DSTU2/DiagnosticReport.html#resource) | `UseElementSameName` | [DiagnosticReport.code](https://hl7.org/fhir/R4B/DiagnosticReport.html#resource) |
| [DiagnosticReport.subject](https://hl7.org/fhir/DSTU2/DiagnosticReport.html#resource) | `UseElementSameName` | [DiagnosticReport.subject](https://hl7.org/fhir/R4B/DiagnosticReport.html#resource) |
| [DiagnosticReport.encounter](https://hl7.org/fhir/DSTU2/DiagnosticReport.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-DiagnosticReport.encounter](StructureDefinition-ext-R2-DiagnosticReport.encounter.html) |
| [DiagnosticReport.effective[x]](https://hl7.org/fhir/DSTU2/DiagnosticReport.html#resource) | `UseElementSameName` | [DiagnosticReport.effective[x]](https://hl7.org/fhir/R4B/DiagnosticReport.html#resource) |
| [DiagnosticReport.issued](https://hl7.org/fhir/DSTU2/DiagnosticReport.html#resource) | `UseElementSameName` | [DiagnosticReport.issued](https://hl7.org/fhir/R4B/DiagnosticReport.html#resource) |
| [DiagnosticReport.performer](https://hl7.org/fhir/DSTU2/DiagnosticReport.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-DiagnosticReport.performer](StructureDefinition-ext-R2-DiagnosticReport.performer.html) |
| [DiagnosticReport.request](https://hl7.org/fhir/DSTU2/DiagnosticReport.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-DiagnosticReport.request](StructureDefinition-ext-R2-DiagnosticReport.request.html) |
| [DiagnosticReport.specimen](https://hl7.org/fhir/DSTU2/DiagnosticReport.html#resource) | `UseElementSameName` | [DiagnosticReport.specimen](https://hl7.org/fhir/R4B/DiagnosticReport.html#resource) |
| [DiagnosticReport.result](https://hl7.org/fhir/DSTU2/DiagnosticReport.html#resource) | `UseElementSameName` | [DiagnosticReport.result](https://hl7.org/fhir/R4B/DiagnosticReport.html#resource) |
| [DiagnosticReport.imagingStudy](https://hl7.org/fhir/DSTU2/DiagnosticReport.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-DiagnosticReport.imagingStudy](StructureDefinition-ext-R2-DiagnosticReport.imagingStudy.html) |
| [DiagnosticReport.image](https://hl7.org/fhir/DSTU2/DiagnosticReport.html#resource) | `UseElementRenamed` | [DiagnosticReport.media](https://hl7.org/fhir/R4B/DiagnosticReport.html#resource) |
| [DiagnosticReport.image.id](https://hl7.org/fhir/DSTU2/DiagnosticReport.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-DiagnosticReport.image.id](StructureDefinition-ext-R2-DiagnosticReport.im.id.html) |
| [DiagnosticReport.image.comment](https://hl7.org/fhir/DSTU2/DiagnosticReport.html#resource) | `UseElementRenamed` | [DiagnosticReport.media.comment](https://hl7.org/fhir/R4B/DiagnosticReport.html#resource) |
| [DiagnosticReport.image.link](https://hl7.org/fhir/DSTU2/DiagnosticReport.html#resource) | `UseElementRenamed` | [DiagnosticReport.media.link](https://hl7.org/fhir/R4B/DiagnosticReport.html#resource) |
| [DiagnosticReport.conclusion](https://hl7.org/fhir/DSTU2/DiagnosticReport.html#resource) | `UseElementSameName` | [DiagnosticReport.conclusion](https://hl7.org/fhir/R4B/DiagnosticReport.html#resource) |
| [DiagnosticReport.codedDiagnosis](https://hl7.org/fhir/DSTU2/DiagnosticReport.html#resource) | `UseElementRenamed` | [DiagnosticReport.conclusionCode](https://hl7.org/fhir/R4B/DiagnosticReport.html#resource) |
| [DiagnosticReport.presentedForm](https://hl7.org/fhir/DSTU2/DiagnosticReport.html#resource) | `UseElementSameName` | [DiagnosticReport.presentedForm](https://hl7.org/fhir/R4B/DiagnosticReport.html#resource) |
