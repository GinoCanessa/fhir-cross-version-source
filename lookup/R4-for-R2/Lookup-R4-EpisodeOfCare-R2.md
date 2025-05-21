### Lookup for FHIR R4 EpisodeOfCare for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| EpisodeOfCare.id | UseElementSameName | EpisodeOfCare.id |
| EpisodeOfCare.meta | UseElementSameName | EpisodeOfCare.meta |
| EpisodeOfCare.implicitRules | UseElementSameName | EpisodeOfCare.implicitRules |
| EpisodeOfCare.language | UseElementSameName | EpisodeOfCare.language |
| EpisodeOfCare.text | UseElementSameName | EpisodeOfCare.text |
| EpisodeOfCare.contained | UseElementSameName | EpisodeOfCare.contained |
| EpisodeOfCare.extension | UseElementSameName | EpisodeOfCare.extension |
| EpisodeOfCare.modifierExtension | UseElementSameName | EpisodeOfCare.modifierExtension |
| EpisodeOfCare.identifier | UseElementSameName | EpisodeOfCare.identifier |
| EpisodeOfCare.status | UseElementSameName | EpisodeOfCare.status |
| EpisodeOfCare.statusHistory | UseElementSameName | EpisodeOfCare.statusHistory |
| EpisodeOfCare.statusHistory.id | UseElementSameName | EpisodeOfCare.statusHistory.id |
| EpisodeOfCare.statusHistory.extension | UseElementSameName | EpisodeOfCare.statusHistory.extension |
| EpisodeOfCare.statusHistory.modifierExtension | UseElementSameName | EpisodeOfCare.statusHistory.modifierExtension |
| EpisodeOfCare.statusHistory.status | UseElementSameName | EpisodeOfCare.statusHistory.status |
| EpisodeOfCare.statusHistory.period | UseElementSameName | EpisodeOfCare.statusHistory.period |
| EpisodeOfCare.type | UseElementSameName | EpisodeOfCare.type |
| EpisodeOfCare.diagnosis | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-EpisodeOfCare.diagnosis |
| EpisodeOfCare.diagnosis.id | UseExtensionFromAncestor | - |
| EpisodeOfCare.diagnosis.extension | UseExtensionFromAncestor | - |
| EpisodeOfCare.diagnosis.modifierExtension | UseExtensionFromAncestor | - |
| EpisodeOfCare.diagnosis.condition | UseExtensionFromAncestor | - |
| EpisodeOfCare.diagnosis.role | UseExtensionFromAncestor | - |
| EpisodeOfCare.diagnosis.rank | UseExtensionFromAncestor | - |
| EpisodeOfCare.patient | UseElementSameName | EpisodeOfCare.patient |
| EpisodeOfCare.managingOrganization | UseElementSameName | EpisodeOfCare.managingOrganization |
| EpisodeOfCare.period | UseElementSameName | EpisodeOfCare.period |
| EpisodeOfCare.referralRequest | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-EpisodeOfCare.referralRequest |
| EpisodeOfCare.careManager | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-EpisodeOfCare.careManager |
| EpisodeOfCare.team | UseElementSameName | EpisodeOfCare |
| EpisodeOfCare.account | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-EpisodeOfCare.account |
