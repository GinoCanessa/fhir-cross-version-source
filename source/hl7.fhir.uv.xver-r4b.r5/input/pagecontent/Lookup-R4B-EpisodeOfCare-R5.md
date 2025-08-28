### Lookup for [FHIR R4B](https://hl7.org/fhir/R4B/) [EpisodeOfCare](https://hl7.org/fhir/R4B/EpisodeOfCare.html) for use in [FHIR R5](https://hl7.org/fhir/R5/)

| Source Element (FHIR R4B) | Usage | Target |
| -------------- | ----- | ------ |
| [EpisodeOfCare.meta](https://hl7.org/fhir/R4B/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.meta](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.implicitRules](https://hl7.org/fhir/R4B/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.implicitRules](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.language](https://hl7.org/fhir/R4B/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.language](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.text](https://hl7.org/fhir/R4B/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.text](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.contained](https://hl7.org/fhir/R4B/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.contained](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.identifier](https://hl7.org/fhir/R4B/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.identifier](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.status](https://hl7.org/fhir/R4B/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.status](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.statusHistory](https://hl7.org/fhir/R4B/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.statusHistory](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.statusHistory.status](https://hl7.org/fhir/R4B/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.statusHistory.status](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.statusHistory.period](https://hl7.org/fhir/R4B/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.statusHistory.period](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.type](https://hl7.org/fhir/R4B/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.type](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.diagnosis](https://hl7.org/fhir/R4B/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.diagnosis](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.diagnosis.condition](https://hl7.org/fhir/R4B/EpisodeOfCare.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.3/StructureDefinition/extension-EpisodeOfCare.diagnosis.condition](StructureDefinition-ext-R4B-EpisodeOfCare.di.condition.html) |
| [EpisodeOfCare.diagnosis.role](https://hl7.org/fhir/R4B/EpisodeOfCare.html#resource) | `UseElementRenamed` | [EpisodeOfCare.diagnosis.use](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.diagnosis.rank](https://hl7.org/fhir/R4B/EpisodeOfCare.html#resource) | `UseExtension` | [http://hl7.org/fhir/4.3/StructureDefinition/extension-EpisodeOfCare.diagnosis.rank](StructureDefinition-ext-R4B-EpisodeOfCare.di.rank.html) |
| [EpisodeOfCare.patient](https://hl7.org/fhir/R4B/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.patient](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.managingOrganization](https://hl7.org/fhir/R4B/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.managingOrganization](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.period](https://hl7.org/fhir/R4B/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.period](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.referralRequest](https://hl7.org/fhir/R4B/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.referralRequest](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.careManager](https://hl7.org/fhir/R4B/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.careManager](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.team](https://hl7.org/fhir/R4B/EpisodeOfCare.html#resource) | `UseOneOf` | [EpisodeOfCare.careTeam](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource)<br />[EpisodeOfCare.careTeam](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.account](https://hl7.org/fhir/R4B/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.account](https://hl7.org/fhir/R5/EpisodeOfCare.html#resource) |
