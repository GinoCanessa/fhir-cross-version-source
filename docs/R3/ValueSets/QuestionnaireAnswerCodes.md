Comparison of 
Generated at Monday, April 14, 2025 6:17:19 PM

### Questionnaire Answer Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Questionnaire Answer Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/questionnaire-answers` |
| Version | 3.0.2 |
| Description | Example list of codes for answers to questions. (Not complete or necessarily appropriate.) |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `1417` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Questionnaire` | `Questionnaire.item.enableWhen.answer[x]` | `http://hl7.org/fhir/ValueSet/questionnaire-answers` | `Example` | Value question must have |
| `http://hl7.org/fhir/StructureDefinition/Questionnaire` | `Questionnaire.item.option.value[x]` | `http://hl7.org/fhir/ValueSet/questionnaire-answers` | `Example` | Answer value |
| `http://hl7.org/fhir/StructureDefinition/Questionnaire` | `Questionnaire.item.initial[x]` | `http://hl7.org/fhir/ValueSet/questionnaire-answers` | `Example` | Default value when item is first rendered |
| `http://hl7.org/fhir/StructureDefinition/QuestionnaireResponse` | `QuestionnaireResponse.item.answer.value[x]` | `http://hl7.org/fhir/ValueSet/questionnaire-answers` | `Example` | Single-valued answer to the question |

### Expansion Failure

Failed to expand this value set: Expansion is limited
