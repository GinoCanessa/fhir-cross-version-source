### Lookup for FHIR R2 Composition for use in FHIR R5

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Composition.id | UseElementSameName | Composition.id |
| Composition.meta | UseElementSameName | Composition.meta |
| Composition.implicitRules | UseElementSameName | Composition.implicitRules |
| Composition.language | UseElementSameName | Composition.language |
| Composition.text | UseElementSameName | Composition.text |
| Composition.contained | UseElementSameName | Composition.contained |
| Composition.extension | UseElementSameName | Composition.extension |
| Composition.modifierExtension | UseElementSameName | Composition.modifierExtension |
| Composition.identifier | UseElementSameName | Composition.identifier |
| Composition.date | UseElementSameName | Composition.date |
| Composition.type | UseElementSameName | Composition.type |
| Composition.class | UseElementRenamed | Composition.category |
| Composition.title | UseElementSameName | Composition.title |
| Composition.status | UseElementSameName | Composition.status |
| Composition.confidentiality | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Composition.confidentiality |
| Composition.subject | UseElementSameName | Composition.subject |
| Composition.author | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Composition.author |
| Composition.attester | UseElementSameName | Composition.attester |
| Composition.attester.id | UseElementSameName | Composition.attester.id |
| Composition.attester.extension | UseElementSameName | Composition.attester.extension |
| Composition.attester.modifierExtension | UseElementSameName | Composition.attester.modifierExtension |
| Composition.attester.mode | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Composition.attester.mode |
| Composition.attester.time | UseElementSameName | Composition.attester.time |
| Composition.attester.party | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Composition.attester.party |
| Composition.custodian | UseElementSameName | Composition.custodian |
| Composition.event | UseElementSameName | Composition.event |
| Composition.event.id | UseElementSameName | Composition.event.id |
| Composition.event.extension | UseElementSameName | Composition.event.extension |
| Composition.event.modifierExtension | UseElementSameName | Composition.event.modifierExtension |
| Composition.event.code | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Composition.event.code |
| Composition.event.period | UseElementSameName | Composition.event.period |
| Composition.event.detail | UseElementSameName | Composition.event.detail |
| Composition.encounter | UseElementSameName | Composition.encounter |
| Composition.section | UseElementSameName | Composition.section |
| Composition.section.id | UseElementSameName | Composition.section.id |
| Composition.section.extension | UseElementSameName | Composition.section.extension |
| Composition.section.modifierExtension | UseElementSameName | Composition.section.modifierExtension |
| Composition.section.title | UseElementSameName | Composition.section.title |
| Composition.section.code | UseElementSameName | Composition.section.code |
| Composition.section.text | UseElementSameName | Composition.section.text |
| Composition.section.mode | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Composition.section.mode |
| Composition.section.orderedBy | UseElementSameName | Composition.section.orderedBy |
| Composition.section.entry | UseElementSameName | Composition.section.entry |
| Composition.section.emptyReason | UseElementSameName | Composition.section.emptyReason |
| Composition.section.section | UseElementSameName | Composition.section.section |
