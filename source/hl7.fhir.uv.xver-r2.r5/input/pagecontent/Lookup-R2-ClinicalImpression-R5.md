### Lookup for [FHIR R2](https://hl7.org/fhir/DSTU2/) [ClinicalImpression](https://hl7.org/fhir/DSTU2/ClinicalImpression.html) for use in [FHIR R5](https://hl7.org/fhir/R5/)

| Source Element (FHIR R2) | Usage | Target |
| -------------- | ----- | ------ |
| [ClinicalImpression.meta](https://hl7.org/fhir/DSTU2/ClinicalImpression.html#resource) | `UseElementSameName` | [ClinicalImpression.meta](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
| [ClinicalImpression.implicitRules](https://hl7.org/fhir/DSTU2/ClinicalImpression.html#resource) | `UseElementSameName` | [ClinicalImpression.implicitRules](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
| [ClinicalImpression.language](https://hl7.org/fhir/DSTU2/ClinicalImpression.html#resource) | `UseElementSameName` | [ClinicalImpression.language](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
| [ClinicalImpression.text](https://hl7.org/fhir/DSTU2/ClinicalImpression.html#resource) | `UseElementSameName` | [ClinicalImpression.text](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
| [ClinicalImpression.contained](https://hl7.org/fhir/DSTU2/ClinicalImpression.html#resource) | `UseElementSameName` | [ClinicalImpression.contained](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
| [ClinicalImpression.patient](https://hl7.org/fhir/DSTU2/ClinicalImpression.html#resource) | `UseElementRenamed` | [ClinicalImpression.subject](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
| [ClinicalImpression.assessor](https://hl7.org/fhir/DSTU2/ClinicalImpression.html#resource) | `UseElementRenamed` | [ClinicalImpression.performer](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
| [ClinicalImpression.status](https://hl7.org/fhir/DSTU2/ClinicalImpression.html#resource) | `UseElementSameName` | [ClinicalImpression.status](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
| [ClinicalImpression.date](https://hl7.org/fhir/DSTU2/ClinicalImpression.html#resource) | `UseElementSameName` | [ClinicalImpression.date](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
| [ClinicalImpression.description](https://hl7.org/fhir/DSTU2/ClinicalImpression.html#resource) | `UseElementSameName` | [ClinicalImpression.description](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
| [ClinicalImpression.previous](https://hl7.org/fhir/DSTU2/ClinicalImpression.html#resource) | `UseElementSameName` | [ClinicalImpression.previous](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
| [ClinicalImpression.problem](https://hl7.org/fhir/DSTU2/ClinicalImpression.html#resource) | `UseElementSameName` | [ClinicalImpression.problem](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
| [ClinicalImpression.trigger[x]](https://hl7.org/fhir/DSTU2/ClinicalImpression.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-ClinicalImpression.trigger](StructureDefinition-ext-R2-ClinicalImpression.trigger.html) |
| [ClinicalImpression.investigations](https://hl7.org/fhir/DSTU2/ClinicalImpression.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-ClinicalImpression.investigations](StructureDefinition-ext-R2-ClinicalImpression.investigations.html) |
| [ClinicalImpression.investigations.id](https://hl7.org/fhir/DSTU2/ClinicalImpression.html#resource) | `UseExtensionFromAncestor` | - |
| [ClinicalImpression.investigations.code](https://hl7.org/fhir/DSTU2/ClinicalImpression.html#resource) | `UseExtensionFromAncestor` | - |
| [ClinicalImpression.investigations.item](https://hl7.org/fhir/DSTU2/ClinicalImpression.html#resource) | `UseExtensionFromAncestor` | - |
| [ClinicalImpression.protocol](https://hl7.org/fhir/DSTU2/ClinicalImpression.html#resource) | `UseElementSameName` | [ClinicalImpression.protocol](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
| [ClinicalImpression.summary](https://hl7.org/fhir/DSTU2/ClinicalImpression.html#resource) | `UseElementSameName` | [ClinicalImpression.summary](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
| [ClinicalImpression.finding](https://hl7.org/fhir/DSTU2/ClinicalImpression.html#resource) | `UseElementSameName` | [ClinicalImpression.finding](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
| [ClinicalImpression.finding.id](https://hl7.org/fhir/DSTU2/ClinicalImpression.html#resource) | `UseElementSameName` | [ClinicalImpression.finding.id](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
| [ClinicalImpression.finding.item](https://hl7.org/fhir/DSTU2/ClinicalImpression.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-ClinicalImpression.finding.item](StructureDefinition-ext-R2-ClinicalImpression.fi.item.html) |
| [ClinicalImpression.finding.cause](https://hl7.org/fhir/DSTU2/ClinicalImpression.html#resource) | `UseElementRenamed` | [ClinicalImpression.finding.basis](https://hl7.org/fhir/R5/ClinicalImpression.html#resource) |
| [ClinicalImpression.resolved](https://hl7.org/fhir/DSTU2/ClinicalImpression.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-ClinicalImpression.resolved](StructureDefinition-ext-R2-ClinicalImpression.resolved.html) |
| [ClinicalImpression.ruledOut](https://hl7.org/fhir/DSTU2/ClinicalImpression.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-ClinicalImpression.ruledOut](StructureDefinition-ext-R2-ClinicalImpression.ruledOut.html) |
| [ClinicalImpression.ruledOut.id](https://hl7.org/fhir/DSTU2/ClinicalImpression.html#resource) | `UseExtensionFromAncestor` | - |
| [ClinicalImpression.ruledOut.item](https://hl7.org/fhir/DSTU2/ClinicalImpression.html#resource) | `UseExtensionFromAncestor` | - |
| [ClinicalImpression.ruledOut.reason](https://hl7.org/fhir/DSTU2/ClinicalImpression.html#resource) | `UseExtensionFromAncestor` | - |
| [ClinicalImpression.prognosis](https://hl7.org/fhir/DSTU2/ClinicalImpression.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-ClinicalImpression.prognosis](StructureDefinition-ext-R2-ClinicalImpression.prognosis.html) |
| [ClinicalImpression.plan](https://hl7.org/fhir/DSTU2/ClinicalImpression.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-ClinicalImpression.plan](StructureDefinition-ext-R2-ClinicalImpression.plan.html) |
| [ClinicalImpression.action](https://hl7.org/fhir/DSTU2/ClinicalImpression.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-ClinicalImpression.action](StructureDefinition-ext-R2-ClinicalImpression.action.html) |
