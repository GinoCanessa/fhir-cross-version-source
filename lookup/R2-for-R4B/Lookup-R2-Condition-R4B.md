### Lookup for FHIR R2 Condition for use in FHIR R4B

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Condition.id | UseElementSameName | Condition.id |
| Condition.meta | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Condition.meta |
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
| Condition.dateRecorded | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Condition.dateRecorded |
| Condition.code | UseElementSameName | Condition.code |
| Condition.category | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Condition.category |
| Condition.clinicalStatus | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Condition.clinicalStatus |
| Condition.verificationStatus | UseElementSameName | Condition.verificationStatus |
| Condition.severity | UseElementSameName | Condition.severity |
| Condition.onset[x] | UseElementSameName | Condition.onset[x] |
| Condition.abatement[x] | UseElementSameName | Condition.abatement[x] |
| Condition.stage | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Condition.stage |
| Condition.stage.id | UseExtensionFromAncestor | - |
| Condition.stage.extension | UseExtensionFromAncestor | - |
| Condition.stage.modifierExtension | UseExtensionFromAncestor | - |
| Condition.stage.summary | UseExtensionFromAncestor | - |
| Condition.stage.assessment | UseExtensionFromAncestor | - |
| Condition.evidence | UseElementSameName | Condition.evidence |
| Condition.evidence.id | UseElementSameName | Condition.evidence.id |
| Condition.evidence.extension | UseElementSameName | Condition.evidence.extension |
| Condition.evidence.modifierExtension | UseElementSameName | Condition.evidence.modifierExtension |
| Condition.evidence.code | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Condition.evidence.code |
| Condition.evidence.detail | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Condition.evidence.detail |
| Condition.bodySite | UseElementSameName | Condition.bodySite |
| Condition.notes | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-Condition.notes |
