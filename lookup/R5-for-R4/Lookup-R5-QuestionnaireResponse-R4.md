### Lookup for FHIR R5 QuestionnaireResponse for use in FHIR R4

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| QuestionnaireResponse.id | UseElementSameName | QuestionnaireResponse.id |
| QuestionnaireResponse.meta | UseElementSameName | QuestionnaireResponse.meta |
| QuestionnaireResponse.implicitRules | UseElementSameName | QuestionnaireResponse.implicitRules |
| QuestionnaireResponse.language | UseElementSameName | QuestionnaireResponse.language |
| QuestionnaireResponse.text | UseElementSameName | QuestionnaireResponse.text |
| QuestionnaireResponse.contained | UseElementSameName | QuestionnaireResponse.contained |
| QuestionnaireResponse.extension | UseElementSameName | QuestionnaireResponse.extension |
| QuestionnaireResponse.modifierExtension | UseElementSameName | QuestionnaireResponse.modifierExtension |
| QuestionnaireResponse.identifier | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-QuestionnaireResponse.identifier |
| QuestionnaireResponse.basedOn | UseElementSameName | QuestionnaireResponse.basedOn |
| QuestionnaireResponse.partOf | UseElementSameName | QuestionnaireResponse.partOf |
| QuestionnaireResponse.questionnaire | UseElementSameName | QuestionnaireResponse.questionnaire |
| QuestionnaireResponse.status | UseElementSameName | QuestionnaireResponse.status |
| QuestionnaireResponse.subject | UseElementSameName | QuestionnaireResponse.subject |
| QuestionnaireResponse.encounter | UseElementSameName | QuestionnaireResponse.encounter |
| QuestionnaireResponse.authored | UseElementSameName | QuestionnaireResponse.authored |
| QuestionnaireResponse.author | UseElementSameName | QuestionnaireResponse.author |
| QuestionnaireResponse.source | UseElementSameName | QuestionnaireResponse.source |
| QuestionnaireResponse.item | UseOneOfElements | QuestionnaireResponse.item,QuestionnaireResponse.item |
| QuestionnaireResponse.item.id | UseElementSameName | QuestionnaireResponse.item.id |
| QuestionnaireResponse.item.extension | UseElementSameName | QuestionnaireResponse.item.extension |
| QuestionnaireResponse.item.modifierExtension | UseElementSameName | QuestionnaireResponse.item.modifierExtension |
| QuestionnaireResponse.item.linkId | UseOneOfElements | QuestionnaireResponse.item.linkId,QuestionnaireResponse.item.linkId |
| QuestionnaireResponse.item.definition | UseElementSameName | QuestionnaireResponse.item.definition |
| QuestionnaireResponse.item.text | UseOneOfElements | QuestionnaireResponse.item.text,QuestionnaireResponse.item.text,QuestionnaireResponse.item.text,QuestionnaireResponse.item.text |
| QuestionnaireResponse.item.answer | UseElementSameName | QuestionnaireResponse.item.answer |
| QuestionnaireResponse.item.answer.id | UseElementSameName | QuestionnaireResponse.item.answer.id |
| QuestionnaireResponse.item.answer.extension | UseElementSameName | QuestionnaireResponse.item.answer.extension |
| QuestionnaireResponse.item.answer.modifierExtension | UseElementSameName | QuestionnaireResponse.item.answer.modifierExtension |
| QuestionnaireResponse.item.answer.value[x] | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-QuestionnaireResponse.item.answer.value |
| QuestionnaireResponse.item.answer.item | UseElementSameName | QuestionnaireResponse.item.answer.item |
| QuestionnaireResponse.item.item | UseOneOfElements | QuestionnaireResponse.item.item,QuestionnaireResponse.item.item |
