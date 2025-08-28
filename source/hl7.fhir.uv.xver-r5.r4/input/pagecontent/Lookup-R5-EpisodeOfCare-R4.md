### Lookup for [FHIR R5](https://hl7.org/fhir/R5/) [EpisodeOfCare](https://hl7.org/fhir/R5/EpisodeOfCare.html) for use in [FHIR R4](https://hl7.org/fhir/R4/)

| Source Element (FHIR R5) | Usage | Target |
| -------------- | ----- | ------ |
| [EpisodeOfCare.meta](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.meta](https://hl7.org/fhir/R4/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.implicitRules](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.implicitRules](https://hl7.org/fhir/R4/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.language](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.language](https://hl7.org/fhir/R4/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.text](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.text](https://hl7.org/fhir/R4/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.contained](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.contained](https://hl7.org/fhir/R4/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.identifier](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.identifier](https://hl7.org/fhir/R4/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.status](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.status](https://hl7.org/fhir/R4/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.statusHistory](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.statusHistory](https://hl7.org/fhir/R4/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.statusHistory.status](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.statusHistory.status](https://hl7.org/fhir/R4/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.statusHistory.period](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.statusHistory.period](https://hl7.org/fhir/R4/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.type](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.type](https://hl7.org/fhir/R4/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.reason](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-EpisodeOfCare.reason](StructureDefinition-ext-R5-EpisodeOfCare.reason.html) |
| [EpisodeOfCare.reason.use](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) | `UseExtensionFromAncestor` | - |
| [EpisodeOfCare.reason.value](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) | `UseExtensionFromAncestor` | - |
| [EpisodeOfCare.diagnosis](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.diagnosis](https://hl7.org/fhir/R4/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.diagnosis.condition](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) | `UseExtension` | [http://hl7.org/fhir/5.0/StructureDefinition/extension-EpisodeOfCare.diagnosis.condition](StructureDefinition-ext-R5-EpisodeOfCare.di.condition.html) |
| [EpisodeOfCare.diagnosis.use](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) | `UseElementRenamed` | [EpisodeOfCare.diagnosis.role](https://hl7.org/fhir/R4/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.patient](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.patient](https://hl7.org/fhir/R4/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.managingOrganization](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.managingOrganization](https://hl7.org/fhir/R4/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.period](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.period](https://hl7.org/fhir/R4/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.referralRequest](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.referralRequest](https://hl7.org/fhir/R4/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.careManager](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.careManager](https://hl7.org/fhir/R4/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.careTeam](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) | `UseOneOf` | [EpisodeOfCare.team](https://hl7.org/fhir/R4/EpisodeOfCare.html#resource)<br />[EpisodeOfCare.team](https://hl7.org/fhir/R4/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.account](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.account](https://hl7.org/fhir/R4/EpisodeOfCare.html#resource) |
