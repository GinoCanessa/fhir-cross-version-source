### Lookup for FHIR R3 FamilyMemberHistory for use in FHIR R5

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
| FamilyMemberHistory.definition | UseElementRenamed | FamilyMemberHistory.instantiatesCanonical |
| FamilyMemberHistory.status | UseElementSameName | FamilyMemberHistory.status |
| FamilyMemberHistory.notDone | UseElementRenamed | FamilyMemberHistory.dataAbsentReason |
| FamilyMemberHistory.notDoneReason | UseElementRenamed | FamilyMemberHistory.dataAbsentReason |
| FamilyMemberHistory.patient | UseElementSameName | FamilyMemberHistory.patient |
| FamilyMemberHistory.date | UseElementSameName | FamilyMemberHistory.date |
| FamilyMemberHistory.name | UseElementSameName | FamilyMemberHistory.name |
| FamilyMemberHistory.relationship | UseElementSameName | FamilyMemberHistory.relationship |
| FamilyMemberHistory.gender | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-FamilyMemberHistory.gender |
| FamilyMemberHistory.born[x] | UseElementSameName | FamilyMemberHistory.born[x] |
| FamilyMemberHistory.age[x] | UseElementSameName | FamilyMemberHistory.age[x] |
| FamilyMemberHistory.estimatedAge | UseElementSameName | FamilyMemberHistory.estimatedAge |
| FamilyMemberHistory.deceased[x] | UseElementSameName | FamilyMemberHistory.deceased[x] |
| FamilyMemberHistory.reasonCode | UseElementRenamed | FamilyMemberHistory.reason |
| FamilyMemberHistory.reasonReference | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-FamilyMemberHistory.reasonReference |
| FamilyMemberHistory.note | UseElementSameName | FamilyMemberHistory.note |
| FamilyMemberHistory.condition | UseElementSameName | FamilyMemberHistory.condition |
| FamilyMemberHistory.condition.id | UseElementSameName | FamilyMemberHistory.condition.id |
| FamilyMemberHistory.condition.extension | UseElementSameName | FamilyMemberHistory.condition.extension |
| FamilyMemberHistory.condition.modifierExtension | UseElementSameName | FamilyMemberHistory.condition.modifierExtension |
| FamilyMemberHistory.condition.code | UseElementSameName | FamilyMemberHistory.condition.code |
| FamilyMemberHistory.condition.outcome | UseElementSameName | FamilyMemberHistory.condition.outcome |
| FamilyMemberHistory.condition.onset[x] | UseElementSameName | FamilyMemberHistory.condition.onset[x] |
| FamilyMemberHistory.condition.note | UseElementSameName | FamilyMemberHistory.condition.note |
