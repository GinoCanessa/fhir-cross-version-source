### Lookup for [FHIR R2](https://hl7.org/fhir/DSTU2/) [EpisodeOfCare](https://hl7.org/fhir/DSTU2/EpisodeOfCare.html) for use in [FHIR R4](https://hl7.org/fhir/R4/)

| Source Element (FHIR R2) | Usage | Target |
| -------------- | ----- | ------ |
| [EpisodeOfCare.meta](https://hl7.org/fhir/DSTU2/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.meta](https://hl7.org/fhir/R4/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.implicitRules](https://hl7.org/fhir/DSTU2/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.implicitRules](https://hl7.org/fhir/R4/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.language](https://hl7.org/fhir/DSTU2/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.language](https://hl7.org/fhir/R4/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.text](https://hl7.org/fhir/DSTU2/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.text](https://hl7.org/fhir/R4/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.contained](https://hl7.org/fhir/DSTU2/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.contained](https://hl7.org/fhir/R4/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.identifier](https://hl7.org/fhir/DSTU2/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.identifier](https://hl7.org/fhir/R4/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.status](https://hl7.org/fhir/DSTU2/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.status](https://hl7.org/fhir/R4/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.statusHistory](https://hl7.org/fhir/DSTU2/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.statusHistory](https://hl7.org/fhir/R4/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.statusHistory.id](https://hl7.org/fhir/DSTU2/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.statusHistory.id](https://hl7.org/fhir/R4/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.statusHistory.status](https://hl7.org/fhir/DSTU2/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.statusHistory.status](https://hl7.org/fhir/R4/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.statusHistory.period](https://hl7.org/fhir/DSTU2/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.statusHistory.period](https://hl7.org/fhir/R4/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.type](https://hl7.org/fhir/DSTU2/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.type](https://hl7.org/fhir/R4/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.condition](https://hl7.org/fhir/DSTU2/EpisodeOfCare.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-EpisodeOfCare.condition](StructureDefinition-ext-R2-EpisodeOfCare.condition.html) |
| [EpisodeOfCare.patient](https://hl7.org/fhir/DSTU2/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.patient](https://hl7.org/fhir/R4/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.managingOrganization](https://hl7.org/fhir/DSTU2/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.managingOrganization](https://hl7.org/fhir/R4/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.period](https://hl7.org/fhir/DSTU2/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.period](https://hl7.org/fhir/R4/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.referralRequest](https://hl7.org/fhir/DSTU2/EpisodeOfCare.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-EpisodeOfCare.referralRequest](StructureDefinition-ext-R2-EpisodeOfCare.referralRequest.html) |
| [EpisodeOfCare.careManager](https://hl7.org/fhir/DSTU2/EpisodeOfCare.html#resource) | `UseElementSameName` | [EpisodeOfCare.careManager](https://hl7.org/fhir/R4/EpisodeOfCare.html#resource) |
| [EpisodeOfCare.careTeam](https://hl7.org/fhir/DSTU2/EpisodeOfCare.html#resource) | `UseExtension` | [http://hl7.org/fhir/1.0/StructureDefinition/extension-EpisodeOfCare.careTeam](StructureDefinition-ext-R2-EpisodeOfCare.careTeam.html) |
| [EpisodeOfCare.careTeam.id](https://hl7.org/fhir/DSTU2/EpisodeOfCare.html#resource) | `UseExtensionFromAncestor` | - |
| [EpisodeOfCare.careTeam.role](https://hl7.org/fhir/DSTU2/EpisodeOfCare.html#resource) | `UseExtensionFromAncestor` | - |
| [EpisodeOfCare.careTeam.period](https://hl7.org/fhir/DSTU2/EpisodeOfCare.html#resource) | `UseExtensionFromAncestor` | - |
| [EpisodeOfCare.careTeam.member](https://hl7.org/fhir/DSTU2/EpisodeOfCare.html#resource) | `UseExtensionFromAncestor` | - |
