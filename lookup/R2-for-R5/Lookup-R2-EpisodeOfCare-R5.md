### Lookup for FHIR R2 EpisodeOfCare for use in FHIR R5

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| EpisodeOfCare.id | UseElementSameName | EpisodeOfCare.id |
| EpisodeOfCare.meta | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-EpisodeOfCare.meta |
| EpisodeOfCare.implicitRules | UseElementSameName | EpisodeOfCare.implicitRules |
| EpisodeOfCare.language | UseElementSameName | EpisodeOfCare.language |
| EpisodeOfCare.text | UseElementSameName | EpisodeOfCare.text |
| EpisodeOfCare.contained | UseElementSameName | EpisodeOfCare.contained |
| EpisodeOfCare.extension | UseElementSameName | EpisodeOfCare.extension |
| EpisodeOfCare.modifierExtension | UseElementSameName | EpisodeOfCare.modifierExtension |
| EpisodeOfCare.identifier | UseElementSameName | EpisodeOfCare.identifier |
| EpisodeOfCare.status | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-EpisodeOfCare.status |
| EpisodeOfCare.statusHistory | UseElementSameName | EpisodeOfCare.statusHistory |
| EpisodeOfCare.statusHistory.id | UseElementSameName | EpisodeOfCare.statusHistory.id |
| EpisodeOfCare.statusHistory.extension | UseElementSameName | EpisodeOfCare.statusHistory.extension |
| EpisodeOfCare.statusHistory.modifierExtension | UseElementSameName | EpisodeOfCare.statusHistory.modifierExtension |
| EpisodeOfCare.statusHistory.status | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-EpisodeOfCare.statusHistory.status |
| EpisodeOfCare.statusHistory.period | UseElementSameName | EpisodeOfCare.statusHistory.period |
| EpisodeOfCare.type | UseElementSameName | EpisodeOfCare.type |
| EpisodeOfCare.condition | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-EpisodeOfCare.condition |
| EpisodeOfCare.patient | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-EpisodeOfCare.patient |
| EpisodeOfCare.managingOrganization | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-EpisodeOfCare.managingOrganization |
| EpisodeOfCare.period | UseElementSameName | EpisodeOfCare.period |
| EpisodeOfCare.referralRequest | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-EpisodeOfCare.referralRequest |
| EpisodeOfCare.careManager | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-EpisodeOfCare.careManager |
| EpisodeOfCare.careTeam | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-EpisodeOfCare.careTeam |
| EpisodeOfCare.careTeam.id | UseExtensionFromAncestor | - |
| EpisodeOfCare.careTeam.extension | UseExtensionFromAncestor | - |
| EpisodeOfCare.careTeam.modifierExtension | UseExtensionFromAncestor | - |
| EpisodeOfCare.careTeam.role | UseExtensionFromAncestor | - |
| EpisodeOfCare.careTeam.period | UseExtensionFromAncestor | - |
| EpisodeOfCare.careTeam.member | UseExtensionFromAncestor | - |
