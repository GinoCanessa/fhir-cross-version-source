### Lookup for FHIR R4 CareTeam for use in FHIR R5

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| CareTeam.id | UseElementSameName | CareTeam.id |
| CareTeam.meta | UseElementSameName | CareTeam.meta |
| CareTeam.implicitRules | UseElementSameName | CareTeam.implicitRules |
| CareTeam.language | UseElementSameName | CareTeam.language |
| CareTeam.text | UseElementSameName | CareTeam.text |
| CareTeam.contained | UseElementSameName | CareTeam.contained |
| CareTeam.extension | UseElementSameName | CareTeam.extension |
| CareTeam.modifierExtension | UseElementSameName | CareTeam.modifierExtension |
| CareTeam.identifier | UseElementSameName | CareTeam.identifier |
| CareTeam.status | UseElementSameName | CareTeam.status |
| CareTeam.category | UseElementSameName | CareTeam.category |
| CareTeam.name | UseElementSameName | CareTeam.name |
| CareTeam.subject | UseElementSameName | CareTeam.subject |
| CareTeam.encounter | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-CareTeam.encounter |
| CareTeam.period | UseElementSameName | CareTeam.period |
| CareTeam.participant | UseElementSameName | CareTeam.participant |
| CareTeam.participant.id | UseElementSameName | CareTeam.participant.id |
| CareTeam.participant.extension | UseElementSameName | CareTeam.participant.extension |
| CareTeam.participant.modifierExtension | UseElementSameName | CareTeam.participant.modifierExtension |
| CareTeam.participant.role | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-CareTeam.participant.role |
| CareTeam.participant.member | UseElementSameName | CareTeam.participant.member |
| CareTeam.participant.onBehalfOf | UseElementSameName | CareTeam.participant.onBehalfOf |
| CareTeam.participant.period | UseElementRenamed | CareTeam.participant.coverage[x] |
| CareTeam.reasonCode | UseElementRenamed | CareTeam.reason |
| CareTeam.reasonReference | UseElementRenamed | CareTeam.reason |
| CareTeam.managingOrganization | UseElementSameName | CareTeam.managingOrganization |
| CareTeam.telecom | UseElementSameName | CareTeam.telecom |
| CareTeam.note | UseElementSameName | CareTeam.note |
