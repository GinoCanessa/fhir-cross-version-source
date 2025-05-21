### Lookup for FHIR R3 Condition for use in FHIR R5

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Condition.id | UseElementSameName | Condition.id |
| Condition.meta | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Condition.meta |
| Condition.implicitRules | UseElementSameName | Condition.implicitRules |
| Condition.language | UseElementSameName | Condition.language |
| Condition.text | UseElementSameName | Condition.text |
| Condition.contained | UseElementSameName | Condition.contained |
| Condition.extension | UseElementSameName | Condition.extension |
| Condition.modifierExtension | UseElementSameName | Condition.modifierExtension |
| Condition.identifier | UseElementSameName | Condition.identifier |
| Condition.clinicalStatus | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Condition.clinicalStatus |
| Condition.verificationStatus | UseElementSameName | Condition.verificationStatus |
| Condition.category | UseElementSameName | Condition.category |
| Condition.severity | UseElementSameName | Condition.severity |
| Condition.code | UseElementSameName | Condition.code |
| Condition.bodySite | UseElementSameName | Condition.bodySite |
| Condition.subject | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Condition.subject |
| Condition.context | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Condition.context |
| Condition.onset[x] | UseElementSameName | Condition.onset[x] |
| Condition.abatement[x] | UseElementSameName | Condition.abatement[x] |
| Condition.assertedDate | UseElementRenamed | Condition.recordedDate |
| Condition.asserter | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Condition.asserter |
| Condition.stage | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Condition.stage |
| Condition.stage.id | UseExtensionFromAncestor | - |
| Condition.stage.extension | UseExtensionFromAncestor | - |
| Condition.stage.modifierExtension | UseExtensionFromAncestor | - |
| Condition.stage.summary | UseExtensionFromAncestor | - |
| Condition.stage.assessment | UseExtensionFromAncestor | - |
| Condition.evidence | UseElementSameName | Condition.evidence |
| Condition.evidence.id | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Condition.evidence.id |
| Condition.evidence.extension | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Condition.evidence.extension |
| Condition.evidence.modifierExtension | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Condition.evidence.modifierExtension |
| Condition.evidence.code | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Condition.evidence.code |
| Condition.evidence.detail | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Condition.evidence.detail |
| Condition.note | UseElementSameName | Condition.note |
