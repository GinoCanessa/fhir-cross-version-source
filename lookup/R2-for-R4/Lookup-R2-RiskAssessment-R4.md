### Lookup for FHIR R2 RiskAssessment for use in FHIR R4

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| RiskAssessment.id | UseElementSameName | RiskAssessment.id |
| RiskAssessment.meta | UseElementSameName | RiskAssessment.meta |
| RiskAssessment.implicitRules | UseElementSameName | RiskAssessment.implicitRules |
| RiskAssessment.language | UseElementSameName | RiskAssessment.language |
| RiskAssessment.text | UseElementSameName | RiskAssessment.text |
| RiskAssessment.contained | UseElementSameName | RiskAssessment.contained |
| RiskAssessment.extension | UseElementSameName | RiskAssessment.extension |
| RiskAssessment.modifierExtension | UseElementSameName | RiskAssessment.modifierExtension |
| RiskAssessment.subject | UseElementSameName | RiskAssessment.subject |
| RiskAssessment.date | UseElementRenamed | RiskAssessment.occurrence[x] |
| RiskAssessment.condition | UseElementSameName | RiskAssessment.condition |
| RiskAssessment.encounter | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-RiskAssessment.encounter |
| RiskAssessment.performer | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-RiskAssessment.performer |
| RiskAssessment.identifier | UseElementSameName | RiskAssessment.identifier |
| RiskAssessment.method | UseElementSameName | RiskAssessment.method |
| RiskAssessment.basis | UseElementSameName | RiskAssessment.basis |
| RiskAssessment.prediction | UseElementSameName | RiskAssessment.prediction |
| RiskAssessment.prediction.id | UseElementSameName | RiskAssessment.prediction.id |
| RiskAssessment.prediction.extension | UseElementSameName | RiskAssessment.prediction.extension |
| RiskAssessment.prediction.modifierExtension | UseElementSameName | RiskAssessment.prediction.modifierExtension |
| RiskAssessment.prediction.outcome | UseElementSameName | RiskAssessment.prediction.outcome |
| RiskAssessment.prediction.probability[x] | UseExtension | http://hl7.org/fhir/1.0/StructureDefinition/extension-RiskAssessment.prediction.probability |
| RiskAssessment.prediction.relativeRisk | UseElementSameName | RiskAssessment.prediction.relativeRisk |
| RiskAssessment.prediction.when[x] | UseElementSameName | RiskAssessment.prediction.when[x] |
| RiskAssessment.prediction.rationale | UseElementSameName | RiskAssessment.prediction.rationale |
| RiskAssessment.mitigation | UseElementSameName | RiskAssessment.mitigation |
