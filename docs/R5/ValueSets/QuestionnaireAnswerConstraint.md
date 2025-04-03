Comparison of 
Generated at Thursday, April 3, 2025 8:18:32 AM

### QuestionnaireAnswerConstraint

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | QuestionnaireAnswerConstraint |
| Canonical URL | `http://hl7.org/fhir/ValueSet/questionnaire-answer-constraint` |
| Version | 5.0.0 |
| Description | Codes that describe the types of constraints possible on a question item that has a list of permitted answers |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `4821` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Questionnaire` | `Questionnaire.item.answerConstraint` | `http://hl7.org/fhir/ValueSet/questionnaire-answer-constraint\|5.0.0` | `Required` | optionsOnly \| optionsOrType \| optionsOrString |

### Referenced Systems

* `http://hl7.org/fhir/questionnaire-answer-constraint`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/questionnaire-answer-constraint` | `optionsOnly` | Options only |
| `http://hl7.org/fhir/questionnaire-answer-constraint` | `optionsOrString` | Options or string |
| `http://hl7.org/fhir/questionnaire-answer-constraint` | `optionsOrType` | Options or 'type' |
