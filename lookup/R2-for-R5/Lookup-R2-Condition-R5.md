### Lookup for FHIR R2 Condition for use in FHIR R5

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
| Condition.patient | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Condition.patient |
| Condition.encounter | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Condition.encounter |
| Condition.asserter | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Condition.asserter |
| Condition.dateRecorded | UseElementRenamed | Condition.recordedDate |
| Condition.code | UseElementSameName | Condition.code |
| Condition.category | UseElementSameName | Condition.category |
| Condition.clinicalStatus | UseElementSameName | Condition.clinicalStatus |
| Condition.verificationStatus | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Condition.verificationStatus |
| Condition.severity | UseElementSameName | Condition.severity |
| Condition.onset[x] | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Condition.onset |
| Condition.abatement[x] | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Condition.abatement |
| Condition.stage | UseElementSameName | Condition.stage |
| Condition.stage.id | UseElementSameName | Condition.stage.id |
| Condition.stage.extension | UseElementSameName | Condition.stage.extension |
| Condition.stage.modifierExtension | UseElementSameName | Condition.stage.modifierExtension |
| Condition.stage.summary | UseElementSameName | Condition.stage.summary |
| Condition.stage.assessment | UseElementSameName | Condition.stage.assessment |
| Condition.evidence | UseElementSameName | Condition.evidence |
| Condition.evidence.id | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Condition.evidence.id |
| Condition.evidence.extension | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Condition.evidence.extension |
| Condition.evidence.modifierExtension | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Condition.evidence.modifierExtension |
| Condition.evidence.code | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Condition.evidence.code |
| Condition.evidence.detail | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Condition.evidence.detail |
| Condition.bodySite | UseElementSameName | Condition.bodySite |
| Condition.notes | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Condition.notes |
