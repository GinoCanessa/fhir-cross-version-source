### Lookup for FHIR R4B QuestionnaireResponse for use in FHIR R2

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
| QuestionnaireResponse.basedOn | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-QuestionnaireResponse.basedOn |
| QuestionnaireResponse.partOf | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-QuestionnaireResponse.partOf |
| QuestionnaireResponse.questionnaire | UseElementSameName | QuestionnaireResponse.questionnaire |
| QuestionnaireResponse.status | UseElementSameName | QuestionnaireResponse.status |
| QuestionnaireResponse.subject | UseElementSameName | QuestionnaireResponse.subject |
| QuestionnaireResponse.encounter | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-QuestionnaireResponse.encounter |
| QuestionnaireResponse.authored | UseElementSameName | QuestionnaireResponse.authored |
| QuestionnaireResponse.author | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-QuestionnaireResponse.author |
| QuestionnaireResponse.source | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-QuestionnaireResponse.source |
| QuestionnaireResponse.item | UseElementSameName | QuestionnaireResponse.group |
| QuestionnaireResponse.item.id | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-QuestionnaireResponse.item.id |
| QuestionnaireResponse.item.extension | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-QuestionnaireResponse.item.extension |
| QuestionnaireResponse.item.modifierExtension | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-QuestionnaireResponse.item.modifierExtension |
| QuestionnaireResponse.item.linkId | UseElementSameName | QuestionnaireResponse.group.linkId |
| QuestionnaireResponse.item.definition | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-QuestionnaireResponse.item.definition |
| QuestionnaireResponse.item.text | UseElementSameName | QuestionnaireResponse.group.title |
| QuestionnaireResponse.item.answer | UseElementSameName | QuestionnaireResponse.group.question.answer |
| QuestionnaireResponse.item.answer.id | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-QuestionnaireResponse.item.answer.id |
| QuestionnaireResponse.item.answer.extension | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-QuestionnaireResponse.item.answer.extension |
| QuestionnaireResponse.item.answer.modifierExtension | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-QuestionnaireResponse.item.answer.modifierExtension |
| QuestionnaireResponse.item.answer.value[x] | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-QuestionnaireResponse.item.answer.value |
| QuestionnaireResponse.item.answer.item | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-QuestionnaireResponse.item.answer.item |
| QuestionnaireResponse.item.item | UseElementSameName | QuestionnaireResponse.group.group |
