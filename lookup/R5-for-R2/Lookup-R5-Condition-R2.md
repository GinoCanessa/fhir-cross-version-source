### Lookup for FHIR R5 Condition for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Condition.id | UseElementSameName | Condition.id |
| Condition.meta | UseElementSameName | Condition.meta |
| Condition.implicitRules | UseElementSameName | Condition.implicitRules |
| Condition.language | UseElementSameName | Condition.language |
| Condition.text | UseElementSameName | Condition.text |
| Condition.contained | UseElementSameName | Condition.contained |
| Condition.extension | UseElementSameName | Condition.extension |
| Condition.modifierExtension | UseElementSameName | Condition.modifierExtension |
| Condition.identifier | UseElementSameName | Condition.identifier |
| Condition.clinicalStatus | UseElementSameName | Condition.clinicalStatus |
| Condition.verificationStatus | UseElementSameName | Condition.verificationStatus |
| Condition.category | UseElementSameName | Condition.category |
| Condition.severity | UseElementSameName | Condition.severity |
| Condition.code | UseElementSameName | Condition.code |
| Condition.bodySite | UseElementSameName | Condition.bodySite |
| Condition.subject | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Condition.subject |
| Condition.encounter | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Condition.encounter |
| Condition.onset[x] | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Condition.onset |
| Condition.abatement[x] | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Condition.abatement |
| Condition.recordedDate | UseElementSameName | Condition.dateRecorded |
| Condition.participant | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Condition.participant |
| Condition.participant.id | UseExtensionFromAncestor | - |
| Condition.participant.extension | UseExtensionFromAncestor | - |
| Condition.participant.modifierExtension | UseExtensionFromAncestor | - |
| Condition.participant.function | UseExtensionFromAncestor | - |
| Condition.participant.actor | UseExtensionFromAncestor | - |
| Condition.stage | UseElementSameName | Condition.stage |
| Condition.stage.id | UseElementSameName | Condition.stage.id |
| Condition.stage.extension | UseElementSameName | Condition.stage.extension |
| Condition.stage.modifierExtension | UseElementSameName | Condition.stage.modifierExtension |
| Condition.stage.summary | UseElementSameName | Condition.stage.summary |
| Condition.stage.assessment | UseElementSameName | Condition.stage.assessment |
| Condition.stage.type | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-Condition.stage.type |
| Condition.evidence | UseElementSameName | Condition.evidence |
| Condition.note | UseElementSameName | Condition.notes |
