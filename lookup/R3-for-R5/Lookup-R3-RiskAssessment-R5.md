### Lookup for FHIR R3 RiskAssessment for use in FHIR R5

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
| RiskAssessment.identifier | UseElementSameName | RiskAssessment.identifier |
| RiskAssessment.basedOn | UseElementSameName | RiskAssessment.basedOn |
| RiskAssessment.parent | UseElementSameName | RiskAssessment.parent |
| RiskAssessment.status | UseElementSameName | RiskAssessment.status |
| RiskAssessment.method | UseElementSameName | RiskAssessment.method |
| RiskAssessment.code | UseElementSameName | RiskAssessment.code |
| RiskAssessment.subject | UseElementSameName | RiskAssessment.subject |
| RiskAssessment.context | UseElementRenamed | RiskAssessment.encounter |
| RiskAssessment.occurrence[x] | UseElementSameName | RiskAssessment.occurrence[x] |
| RiskAssessment.condition | UseElementSameName | RiskAssessment.condition |
| RiskAssessment.performer | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-RiskAssessment.performer |
| RiskAssessment.reason[x] | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-RiskAssessment.reason |
| RiskAssessment.basis | UseElementSameName | RiskAssessment.basis |
| RiskAssessment.prediction | UseElementSameName | RiskAssessment.prediction |
| RiskAssessment.prediction.id | UseElementSameName | RiskAssessment.prediction.id |
| RiskAssessment.prediction.extension | UseElementSameName | RiskAssessment.prediction.extension |
| RiskAssessment.prediction.modifierExtension | UseElementSameName | RiskAssessment.prediction.modifierExtension |
| RiskAssessment.prediction.outcome | UseElementSameName | RiskAssessment.prediction.outcome |
| RiskAssessment.prediction.probability[x] | UseElementSameName | RiskAssessment.prediction.probability[x] |
| RiskAssessment.prediction.qualitativeRisk | UseElementSameName | RiskAssessment.prediction.qualitativeRisk |
| RiskAssessment.prediction.relativeRisk | UseElementSameName | RiskAssessment.prediction.relativeRisk |
| RiskAssessment.prediction.when[x] | UseElementSameName | RiskAssessment.prediction.when[x] |
| RiskAssessment.prediction.rationale | UseElementSameName | RiskAssessment.prediction.rationale |
| RiskAssessment.mitigation | UseElementSameName | RiskAssessment.mitigation |
| RiskAssessment.comment | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-RiskAssessment.comment |
