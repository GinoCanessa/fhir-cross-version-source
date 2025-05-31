### Lookup for FHIR R3 Media for use in FHIR R4

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Media.id | UseElementSameName | Media.id |
| Media.meta | UseElementSameName | Media.meta |
| Media.implicitRules | UseElementSameName | Media.implicitRules |
| Media.language | UseElementSameName | Media.language |
| Media.text | UseElementSameName | Media.text |
| Media.contained | UseElementSameName | Media.contained |
| Media.extension | UseElementSameName | Media.extension |
| Media.modifierExtension | UseElementSameName | Media.modifierExtension |
| Media.identifier | UseElementSameName | Media.identifier |
| Media.basedOn | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Media.basedOn |
| Media.type | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Media.type |
| Media.subtype | UseElementRenamed | Media.modality |
| Media.view | UseElementSameName | Media.view |
| Media.subject | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Media.subject |
| Media.context | UseElementRenamed | Media.encounter |
| Media.occurrence[x] | UseElementRenamed | Media.created[x] |
| Media.operator | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Media.operator |
| Media.reasonCode | UseElementSameName | Media.reasonCode |
| Media.bodySite | UseElementSameName | Media.bodySite |
| Media.device | UseElementSameName | Media.device |
| Media.height | UseElementSameName | Media.height |
| Media.width | UseElementSameName | Media.width |
| Media.frames | UseElementSameName | Media.frames |
| Media.duration | UseElementSameName | Media.duration |
| Media.content | UseElementSameName | Media.content |
| Media.note | UseElementSameName | Media.note |
