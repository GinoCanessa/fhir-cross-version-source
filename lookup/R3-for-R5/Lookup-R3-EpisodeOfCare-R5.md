### Lookup for FHIR R3 EpisodeOfCare for use in FHIR R5

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
| EpisodeOfCare.diagnosis | UseElementSameName | EpisodeOfCare.diagnosis |
| EpisodeOfCare.diagnosis.id | UseElementSameName | EpisodeOfCare.diagnosis.id |
| EpisodeOfCare.diagnosis.extension | UseElementSameName | EpisodeOfCare.diagnosis.extension |
| EpisodeOfCare.diagnosis.modifierExtension | UseElementSameName | EpisodeOfCare.diagnosis.modifierExtension |
| EpisodeOfCare.diagnosis.condition | UseElementSameName | EpisodeOfCare.diagnosis.condition |
| EpisodeOfCare.diagnosis.role | UseElementRenamed | EpisodeOfCare.diagnosis.use |
| EpisodeOfCare.diagnosis.rank | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-EpisodeOfCare.diagnosis.rank |
| EpisodeOfCare.patient | UseElementSameName | EpisodeOfCare.patient |
| EpisodeOfCare.managingOrganization | UseElementSameName | EpisodeOfCare.managingOrganization |
| EpisodeOfCare.period | UseElementSameName | EpisodeOfCare.period |
| EpisodeOfCare.referralRequest | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-EpisodeOfCare.referralRequest |
| EpisodeOfCare.careManager | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-EpisodeOfCare.careManager |
| EpisodeOfCare.team | UseOneOfElements | EpisodeOfCare.careTeam,EpisodeOfCare.careTeam |
| EpisodeOfCare.account | UseElementSameName | EpisodeOfCare.account |
