### Lookup for [FHIR R3](https://hl7.org/fhir/STU3/) [ClinicalImpression](https://hl7.org/fhir/STU3/ClinicalImpression.html) for use in [FHIR R5](https://hl7.org/fhir/R5/)

| Source Element (FHIR R3) | Usage | Target |
| -------------- | ----- | ------ |
| [ClinicalImpression.meta](https://hl7.org/fhir/STU3/ClinicalImpression.html#resource) | `UseElementSameName` | [ClinicalImpression.meta](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
| [ClinicalImpression.implicitRules](https://hl7.org/fhir/STU3/ClinicalImpression.html#resource) | `UseElementSameName` | [ClinicalImpression.implicitRules](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
| [ClinicalImpression.language](https://hl7.org/fhir/STU3/ClinicalImpression.html#resource) | `UseElementSameName` | [ClinicalImpression.language](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
| [ClinicalImpression.text](https://hl7.org/fhir/STU3/ClinicalImpression.html#resource) | `UseElementSameName` | [ClinicalImpression.text](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
| [ClinicalImpression.contained](https://hl7.org/fhir/STU3/ClinicalImpression.html#resource) | `UseElementSameName` | [ClinicalImpression.contained](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
| [ClinicalImpression.identifier](https://hl7.org/fhir/STU3/ClinicalImpression.html#resource) | `UseElementSameName` | [ClinicalImpression.identifier](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
| [ClinicalImpression.status](https://hl7.org/fhir/STU3/ClinicalImpression.html#resource) | `UseElementSameName` | [ClinicalImpression.status](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
| [ClinicalImpression.code](https://hl7.org/fhir/STU3/ClinicalImpression.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-ClinicalImpression.code](StructureDefinition-ext-R3-ClinicalImpression.code.html) |
| [ClinicalImpression.description](https://hl7.org/fhir/STU3/ClinicalImpression.html#resource) | `UseElementSameName` | [ClinicalImpression.description](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
| [ClinicalImpression.subject](https://hl7.org/fhir/STU3/ClinicalImpression.html#resource) | `UseElementSameName` | [ClinicalImpression.subject](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
| [ClinicalImpression.context](https://hl7.org/fhir/STU3/ClinicalImpression.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-ClinicalImpression.context](StructureDefinition-ext-R3-ClinicalImpression.context.html) |
| [ClinicalImpression.effective[x]](https://hl7.org/fhir/STU3/ClinicalImpression.html#resource) | `UseElementSameName` | [ClinicalImpression.effective[x]](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
| [ClinicalImpression.date](https://hl7.org/fhir/STU3/ClinicalImpression.html#resource) | `UseElementSameName` | [ClinicalImpression.date](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
| [ClinicalImpression.assessor](https://hl7.org/fhir/STU3/ClinicalImpression.html#resource) | `UseElementRenamed` | [ClinicalImpression.performer](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
| [ClinicalImpression.previous](https://hl7.org/fhir/STU3/ClinicalImpression.html#resource) | `UseElementSameName` | [ClinicalImpression.previous](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
| [ClinicalImpression.problem](https://hl7.org/fhir/STU3/ClinicalImpression.html#resource) | `UseElementSameName` | [ClinicalImpression.problem](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
| [ClinicalImpression.investigation](https://hl7.org/fhir/STU3/ClinicalImpression.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-ClinicalImpression.investigation](StructureDefinition-ext-R3-ClinicalImpression.investigation.html) |
| [ClinicalImpression.investigation.code](https://hl7.org/fhir/STU3/ClinicalImpression.html#resource) | `UseExtensionFromAncestor` | - |
| [ClinicalImpression.investigation.item](https://hl7.org/fhir/STU3/ClinicalImpression.html#resource) | `UseExtensionFromAncestor` | - |
| [ClinicalImpression.protocol](https://hl7.org/fhir/STU3/ClinicalImpression.html#resource) | `UseElementSameName` | [ClinicalImpression.protocol](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
| [ClinicalImpression.summary](https://hl7.org/fhir/STU3/ClinicalImpression.html#resource) | `UseElementSameName` | [ClinicalImpression.summary](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
| [ClinicalImpression.finding](https://hl7.org/fhir/STU3/ClinicalImpression.html#resource) | `UseElementSameName` | [ClinicalImpression.finding](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
| [ClinicalImpression.finding.item[x]](https://hl7.org/fhir/STU3/ClinicalImpression.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-ClinicalImpression.finding.item](StructureDefinition-ext-R3-ClinicalImpression.fi.item.html) |
| [ClinicalImpression.finding.basis](https://hl7.org/fhir/STU3/ClinicalImpression.html#resource) | `UseElementSameName` | [ClinicalImpression.finding.basis](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
| [ClinicalImpression.prognosisCodeableConcept](https://hl7.org/fhir/STU3/ClinicalImpression.html#resource) | `UseElementSameName` | [ClinicalImpression.prognosisCodeableConcept](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
| [ClinicalImpression.prognosisReference](https://hl7.org/fhir/STU3/ClinicalImpression.html#resource) | `UseElementSameName` | [ClinicalImpression.prognosisReference](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
| [ClinicalImpression.action](https://hl7.org/fhir/STU3/ClinicalImpression.html#resource) | `UseExtension` | [http://hl7.org/fhir/3.0/StructureDefinition/extension-ClinicalImpression.action](StructureDefinition-ext-R3-ClinicalImpression.action.html) |
| [ClinicalImpression.note](https://hl7.org/fhir/STU3/ClinicalImpression.html#resource) | `UseElementSameName` | [ClinicalImpression.note](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
