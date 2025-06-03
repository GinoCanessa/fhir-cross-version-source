### Lookup for FHIR R3 QuestionnaireResponse for use in FHIR R4

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
| QuestionnaireResponse.identifier | UseElementSameName | QuestionnaireResponse.identifier |
| QuestionnaireResponse.basedOn | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-QuestionnaireResponse.basedOn |
| QuestionnaireResponse.parent | UseElementRenamed | QuestionnaireResponse.partOf |
| QuestionnaireResponse.questionnaire | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-QuestionnaireResponse.questionnaire |
| QuestionnaireResponse.status | UseElementSameName | QuestionnaireResponse.status |
| QuestionnaireResponse.subject | UseElementSameName | QuestionnaireResponse.subject |
| QuestionnaireResponse.context | UseElementRenamed | QuestionnaireResponse.encounter |
| QuestionnaireResponse.authored | UseElementSameName | QuestionnaireResponse.authored |
| QuestionnaireResponse.author | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-QuestionnaireResponse.author |
| QuestionnaireResponse.source | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-QuestionnaireResponse.source |
| QuestionnaireResponse.item | UseOneOfElements | QuestionnaireResponse.item,QuestionnaireResponse.item |
| QuestionnaireResponse.item.id | UseElementSameName | QuestionnaireResponse.item.id |
| QuestionnaireResponse.item.extension | UseElementSameName | QuestionnaireResponse.item.extension |
| QuestionnaireResponse.item.modifierExtension | UseElementSameName | QuestionnaireResponse.item.modifierExtension |
| QuestionnaireResponse.item.linkId | UseOneOfElements | QuestionnaireResponse.item.linkId,QuestionnaireResponse.item.linkId |
| QuestionnaireResponse.item.definition | UseElementSameName | QuestionnaireResponse.item.definition |
| QuestionnaireResponse.item.text | UseOneOfElements | QuestionnaireResponse.item.text,QuestionnaireResponse.item.text,QuestionnaireResponse.item.text,QuestionnaireResponse.item.text |
| QuestionnaireResponse.item.subject | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-QuestionnaireResponse.item.subject |
| QuestionnaireResponse.item.answer | UseElementSameName | QuestionnaireResponse.item.answer |
| QuestionnaireResponse.item.answer.id | UseElementSameName | QuestionnaireResponse.item.answer.id |
| QuestionnaireResponse.item.answer.extension | UseElementSameName | QuestionnaireResponse.item.answer.extension |
| QuestionnaireResponse.item.answer.modifierExtension | UseElementSameName | QuestionnaireResponse.item.answer.modifierExtension |
| QuestionnaireResponse.item.answer.value[x] | UseElementSameName | QuestionnaireResponse.item.answer.value[x] |
| QuestionnaireResponse.item.answer.item | UseElementSameName | QuestionnaireResponse.item.answer.item |
| QuestionnaireResponse.item.item | UseOneOfElements | QuestionnaireResponse.item.item,QuestionnaireResponse.item.item |
