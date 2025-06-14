### Lookup for FHIR R5 FamilyMemberHistory for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| FamilyMemberHistory.id | UseElementSameName | FamilyMemberHistory.id |
| FamilyMemberHistory.meta | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-FamilyMemberHistory.meta |
| FamilyMemberHistory.implicitRules | UseElementSameName | FamilyMemberHistory.implicitRules |
| FamilyMemberHistory.language | UseElementSameName | FamilyMemberHistory.language |
| FamilyMemberHistory.text | UseElementSameName | FamilyMemberHistory.text |
| FamilyMemberHistory.contained | UseElementSameName | FamilyMemberHistory.contained |
| FamilyMemberHistory.extension | UseElementSameName | FamilyMemberHistory.extension |
| FamilyMemberHistory.modifierExtension | UseElementSameName | FamilyMemberHistory.modifierExtension |
| FamilyMemberHistory.identifier | UseElementSameName | FamilyMemberHistory.identifier |
| FamilyMemberHistory.instantiatesCanonical | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-FamilyMemberHistory.instantiatesCanonical |
| FamilyMemberHistory.instantiatesUri | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-FamilyMemberHistory.instantiatesUri |
| FamilyMemberHistory.status | UseElementSameName | FamilyMemberHistory.status |
| FamilyMemberHistory.dataAbsentReason | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-FamilyMemberHistory.dataAbsentReason |
| FamilyMemberHistory.patient | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-FamilyMemberHistory.patient |
| FamilyMemberHistory.date | UseElementSameName | FamilyMemberHistory.date |
| FamilyMemberHistory.participant | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-FamilyMemberHistory.participant |
| FamilyMemberHistory.participant.id | UseExtensionFromAncestor | - |
| FamilyMemberHistory.participant.extension | UseExtensionFromAncestor | - |
| FamilyMemberHistory.participant.modifierExtension | UseExtensionFromAncestor | - |
| FamilyMemberHistory.participant.function | UseExtensionFromAncestor | - |
| FamilyMemberHistory.participant.actor | UseExtensionFromAncestor | - |
| FamilyMemberHistory.name | UseElementSameName | FamilyMemberHistory.name |
| FamilyMemberHistory.relationship | UseElementSameName | FamilyMemberHistory.relationship |
| FamilyMemberHistory.sex | UseElementRenamed | FamilyMemberHistory.gender |
| FamilyMemberHistory.born[x] | UseElementSameName | FamilyMemberHistory.born[x] |
| FamilyMemberHistory.age[x] | UseElementSameName | FamilyMemberHistory.age[x] |
| FamilyMemberHistory.estimatedAge | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-FamilyMemberHistory.estimatedAge |
| FamilyMemberHistory.deceased[x] | UseElementSameName | FamilyMemberHistory.deceased[x] |
| FamilyMemberHistory.reason | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-FamilyMemberHistory.reason |
| FamilyMemberHistory.note | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-FamilyMemberHistory.note |
| FamilyMemberHistory.condition | UseElementSameName | FamilyMemberHistory.condition |
| FamilyMemberHistory.condition.id | UseElementSameName | FamilyMemberHistory.condition.id |
| FamilyMemberHistory.condition.extension | UseElementSameName | FamilyMemberHistory.condition.extension |
| FamilyMemberHistory.condition.modifierExtension | UseElementSameName | FamilyMemberHistory.condition.modifierExtension |
| FamilyMemberHistory.condition.code | UseElementSameName | FamilyMemberHistory.condition.code |
| FamilyMemberHistory.condition.outcome | UseElementSameName | FamilyMemberHistory.condition.outcome |
| FamilyMemberHistory.condition.contributedToDeath | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-FamilyMemberHistory.condition.contributedToDeath |
| FamilyMemberHistory.condition.onset[x] | UseElementSameName | FamilyMemberHistory.condition.onset[x] |
| FamilyMemberHistory.condition.note | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-FamilyMemberHistory.condition.note |
| FamilyMemberHistory.procedure | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-FamilyMemberHistory.procedure |
| FamilyMemberHistory.procedure.id | UseExtensionFromAncestor | - |
| FamilyMemberHistory.procedure.extension | UseExtensionFromAncestor | - |
| FamilyMemberHistory.procedure.modifierExtension | UseExtensionFromAncestor | - |
| FamilyMemberHistory.procedure.code | UseExtensionFromAncestor | - |
| FamilyMemberHistory.procedure.outcome | UseExtensionFromAncestor | - |
| FamilyMemberHistory.procedure.contributedToDeath | UseExtensionFromAncestor | - |
| FamilyMemberHistory.procedure.performed[x] | UseExtensionFromAncestor | - |
| FamilyMemberHistory.procedure.note | UseExtensionFromAncestor | - |
