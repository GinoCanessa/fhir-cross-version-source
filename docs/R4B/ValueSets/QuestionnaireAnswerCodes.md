Comparison of 
Generated at Friday, April 4, 2025 2:58:51 PM

### QuestionnaireAnswerCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | QuestionnaireAnswerCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/questionnaire-answers` |
| Version | 4.3.0 |
| Description | Example list of codes for answers to questions. (Not complete or necessarily appropriate.) |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `4020` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Questionnaire` | `Questionnaire.item.enableWhen.answer[x]` | `http://hl7.org/fhir/ValueSet/questionnaire-answers` | `Example` | Value for question comparison based on operator |
| `http://hl7.org/fhir/StructureDefinition/Questionnaire` | `Questionnaire.item.answerOption.value[x]` | `http://hl7.org/fhir/ValueSet/questionnaire-answers` | `Example` | Answer value |
| `http://hl7.org/fhir/StructureDefinition/Questionnaire` | `Questionnaire.item.initial.value[x]` | `http://hl7.org/fhir/ValueSet/questionnaire-answers` | `Example` | Actual value for initializing the question |
| `http://hl7.org/fhir/StructureDefinition/QuestionnaireResponse` | `QuestionnaireResponse.item.answer.value[x]` | `http://hl7.org/fhir/ValueSet/questionnaire-answers` | `Example` | Single-valued answer to the question |

### Expansion Failure

Failed to expand this value set: Expansion is limited
