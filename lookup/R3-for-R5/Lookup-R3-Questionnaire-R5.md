### Lookup for FHIR R3 Questionnaire for use in FHIR R5

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Questionnaire.id | UseElementSameName | Questionnaire.id |
| Questionnaire.meta | UseElementSameName | Questionnaire.meta |
| Questionnaire.implicitRules | UseElementSameName | Questionnaire.implicitRules |
| Questionnaire.language | UseElementSameName | Questionnaire.language |
| Questionnaire.text | UseElementSameName | Questionnaire.text |
| Questionnaire.contained | UseElementSameName | Questionnaire.contained |
| Questionnaire.extension | UseElementSameName | Questionnaire.extension |
| Questionnaire.modifierExtension | UseElementSameName | Questionnaire.modifierExtension |
| Questionnaire.url | UseElementSameName | Questionnaire.url |
| Questionnaire.identifier | UseElementSameName | Questionnaire.identifier |
| Questionnaire.version | UseElementSameName | Questionnaire.version |
| Questionnaire.name | UseElementSameName | Questionnaire.name |
| Questionnaire.title | UseElementSameName | Questionnaire.title |
| Questionnaire.status | UseElementSameName | Questionnaire.status |
| Questionnaire.experimental | UseElementSameName | Questionnaire.experimental |
| Questionnaire.date | UseElementSameName | Questionnaire.date |
| Questionnaire.publisher | UseElementSameName | Questionnaire.publisher |
| Questionnaire.description | UseElementSameName | Questionnaire.description |
| Questionnaire.purpose | UseElementSameName | Questionnaire.purpose |
| Questionnaire.approvalDate | UseElementSameName | Questionnaire.approvalDate |
| Questionnaire.lastReviewDate | UseElementSameName | Questionnaire.lastReviewDate |
| Questionnaire.effectivePeriod | UseElementSameName | Questionnaire.effectivePeriod |
| Questionnaire.useContext | UseElementSameName | Questionnaire.useContext |
| Questionnaire.jurisdiction | UseElementSameName | Questionnaire.jurisdiction |
| Questionnaire.contact | UseElementSameName | Questionnaire.contact |
| Questionnaire.copyright | UseElementSameName | Questionnaire.copyright |
| Questionnaire.code | UseElementSameName | Questionnaire.code |
| Questionnaire.subjectType | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Questionnaire.subjectType |
| Questionnaire.item | UseElementSameName | Questionnaire.item |
| Questionnaire.item.id | UseElementSameName | Questionnaire.item.id |
| Questionnaire.item.extension | UseElementSameName | Questionnaire.item.extension |
| Questionnaire.item.modifierExtension | UseElementSameName | Questionnaire.item.modifierExtension |
| Questionnaire.item.linkId | UseElementSameName | Questionnaire.item.linkId |
| Questionnaire.item.definition | UseElementSameName | Questionnaire.item.definition |
| Questionnaire.item.code | UseElementSameName | Questionnaire.item.code |
| Questionnaire.item.prefix | UseElementSameName | Questionnaire.item.prefix |
| Questionnaire.item.text | UseElementSameName | Questionnaire.item.text |
| Questionnaire.item.type | UseElementSameName | Questionnaire.item.type |
| Questionnaire.item.enableWhen | UseElementSameName | Questionnaire.item.enableWhen |
| Questionnaire.item.enableWhen.id | UseElementSameName | Questionnaire.item.enableWhen.id |
| Questionnaire.item.enableWhen.extension | UseElementSameName | Questionnaire.item.enableWhen.extension |
| Questionnaire.item.enableWhen.modifierExtension | UseElementSameName | Questionnaire.item.enableWhen.modifierExtension |
| Questionnaire.item.enableWhen.question | UseElementSameName | Questionnaire.item.enableWhen.question |
| Questionnaire.item.enableWhen.hasAnswer | UseElementRenamed | Questionnaire.item.enableWhen.operator |
| Questionnaire.item.enableWhen.answer[x] | UseElementRenamed | Questionnaire.item.enableWhen.operator |
| Questionnaire.item.required | UseElementSameName | Questionnaire.item.required |
| Questionnaire.item.repeats | UseElementSameName | Questionnaire.item.repeats |
| Questionnaire.item.readOnly | UseElementSameName | Questionnaire.item.readOnly |
| Questionnaire.item.maxLength | UseElementSameName | Questionnaire.item.maxLength |
| Questionnaire.item.options | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Questionnaire.item.options |
| Questionnaire.item.option | UseElementRenamed | Questionnaire.item.answerOption |
| Questionnaire.item.option.id | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Questionnaire.item.option.id |
| Questionnaire.item.option.extension | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Questionnaire.item.option.extension |
| Questionnaire.item.option.modifierExtension | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Questionnaire.item.option.modifierExtension |
| Questionnaire.item.option.value[x] | UseElementRenamed | Questionnaire.item.answerOption.value[x] |
| Questionnaire.item.initial[x] | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Questionnaire.item.initial |
| Questionnaire.item.item | UseElementSameName | Questionnaire.item.item |
