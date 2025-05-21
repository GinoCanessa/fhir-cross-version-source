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
| FamilyMemberHistory.patient | UseElementSameName | FamilyMemberHistory.patient |
| FamilyMemberHistory.date | UseElementSameName | FamilyMemberHistory.date |
| FamilyMemberHistory.name | UseElementSameName | FamilyMemberHistory.name |
| FamilyMemberHistory.relationship | UseElementSameName | FamilyMemberHistory.relationship |
| FamilyMemberHistory.gender | UseElementRenamed | FamilyMemberHistory.gender |
| FamilyMemberHistory.born[x] | UseElementSameName | FamilyMemberHistory.born[x] |
| FamilyMemberHistory.age[x] | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-FamilyMemberHistory.age |
| FamilyMemberHistory.estimatedAge | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-FamilyMemberHistory.estimatedAge |
| FamilyMemberHistory.deceased[x] | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-FamilyMemberHistory.deceased |
| FamilyMemberHistory.reasonCode | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-FamilyMemberHistory.reasonCode |
| FamilyMemberHistory.reasonReference | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-FamilyMemberHistory.reasonReference |
| FamilyMemberHistory.note | UseElementSameName | FamilyMemberHistory.note |
| FamilyMemberHistory.condition | UseElementSameName | FamilyMemberHistory.condition |
| FamilyMemberHistory.condition.id | UseElementSameName | FamilyMemberHistory.condition.id |
| FamilyMemberHistory.condition.extension | UseElementSameName | FamilyMemberHistory.condition.extension |
| FamilyMemberHistory.condition.modifierExtension | UseElementSameName | FamilyMemberHistory.condition.modifierExtension |
| FamilyMemberHistory.condition.code | UseElementSameName | FamilyMemberHistory.condition.code |
| FamilyMemberHistory.condition.outcome | UseElementSameName | FamilyMemberHistory.condition.outcome |
| FamilyMemberHistory.condition.onset[x] | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-FamilyMemberHistory.condition.onset |
| FamilyMemberHistory.condition.note | UseElementSameName | FamilyMemberHistory.condition.note |
