### Lookup for FHIR R3 FamilyMemberHistory for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| FamilyMemberHistory.id | UseElementSameName | FamilyMemberHistory.id |
| FamilyMemberHistory.meta | UseElementSameName | FamilyMemberHistory.meta |
| FamilyMemberHistory.implicitRules | UseElementSameName | FamilyMemberHistory.implicitRules |
| FamilyMemberHistory.language | UseElementSameName | FamilyMemberHistory.language |
| FamilyMemberHistory.text | UseElementSameName | FamilyMemberHistory.text |
| FamilyMemberHistory.contained | UseElementSameName | FamilyMemberHistory.contained |
| FamilyMemberHistory.extension | UseElementSameName | FamilyMemberHistory.extension |
| FamilyMemberHistory.modifierExtension | UseElementSameName | FamilyMemberHistory.modifierExtension |
| FamilyMemberHistory.identifier | UseElementSameName | FamilyMemberHistory.identifier |
| FamilyMemberHistory.definition | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-FamilyMemberHistory.definition |
| FamilyMemberHistory.status | UseElementSameName | FamilyMemberHistory.status |
| FamilyMemberHistory.notDone | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-FamilyMemberHistory.notDone |
| FamilyMemberHistory.notDoneReason | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-FamilyMemberHistory.notDoneReason |
| FamilyMemberHistory.patient | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-FamilyMemberHistory.patient |
| FamilyMemberHistory.date | UseElementSameName | FamilyMemberHistory.date |
| FamilyMemberHistory.name | UseElementSameName | FamilyMemberHistory.name |
| FamilyMemberHistory.relationship | UseElementSameName | FamilyMemberHistory.relationship |
| FamilyMemberHistory.gender | UseElementRenamed | FamilyMemberHistory.gender |
| FamilyMemberHistory.born[x] | UseElementSameName | FamilyMemberHistory.born[x] |
| FamilyMemberHistory.age[x] | UseElementSameName | FamilyMemberHistory.age[x] |
| FamilyMemberHistory.estimatedAge | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-FamilyMemberHistory.estimatedAge |
| FamilyMemberHistory.deceased[x] | UseElementSameName | FamilyMemberHistory.deceased[x] |
| FamilyMemberHistory.reasonCode | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-FamilyMemberHistory.reasonCode |
| FamilyMemberHistory.reasonReference | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-FamilyMemberHistory.reasonReference |
| FamilyMemberHistory.note | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-FamilyMemberHistory.note |
| FamilyMemberHistory.condition | UseElementSameName | FamilyMemberHistory.condition |
| FamilyMemberHistory.condition.id | UseElementSameName | FamilyMemberHistory.condition.id |
| FamilyMemberHistory.condition.extension | UseElementSameName | FamilyMemberHistory.condition.extension |
| FamilyMemberHistory.condition.modifierExtension | UseElementSameName | FamilyMemberHistory.condition.modifierExtension |
| FamilyMemberHistory.condition.code | UseElementSameName | FamilyMemberHistory.condition.code |
| FamilyMemberHistory.condition.outcome | UseElementSameName | FamilyMemberHistory.condition.outcome |
| FamilyMemberHistory.condition.onset[x] | UseElementSameName | FamilyMemberHistory.condition.onset[x] |
| FamilyMemberHistory.condition.note | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-FamilyMemberHistory.condition.note |
