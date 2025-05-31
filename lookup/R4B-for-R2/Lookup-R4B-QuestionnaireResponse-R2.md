### Lookup for FHIR R4B QuestionnaireResponse for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| QuestionnaireResponse.id | UseElementSameName | QuestionnaireResponse.id |
| QuestionnaireResponse.meta | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-QuestionnaireResponse.meta |
| QuestionnaireResponse.implicitRules | UseElementSameName | QuestionnaireResponse.implicitRules |
| QuestionnaireResponse.language | UseElementSameName | QuestionnaireResponse.language |
| QuestionnaireResponse.text | UseElementSameName | QuestionnaireResponse.text |
| QuestionnaireResponse.contained | UseElementSameName | QuestionnaireResponse.contained |
| QuestionnaireResponse.extension | UseElementSameName | QuestionnaireResponse.extension |
| QuestionnaireResponse.modifierExtension | UseElementSameName | QuestionnaireResponse.modifierExtension |
| QuestionnaireResponse.identifier | UseElementSameName | QuestionnaireResponse.identifier |
| QuestionnaireResponse.basedOn | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-QuestionnaireResponse.basedOn |
| QuestionnaireResponse.partOf | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-QuestionnaireResponse.partOf |
| QuestionnaireResponse.questionnaire | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-QuestionnaireResponse.questionnaire |
| QuestionnaireResponse.status | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-QuestionnaireResponse.status |
| QuestionnaireResponse.subject | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-QuestionnaireResponse.subject |
| QuestionnaireResponse.encounter | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-QuestionnaireResponse.encounter |
| QuestionnaireResponse.authored | UseElementSameName | QuestionnaireResponse.authored |
| QuestionnaireResponse.author | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-QuestionnaireResponse.author |
| QuestionnaireResponse.source | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-QuestionnaireResponse.source |
| QuestionnaireResponse.item | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-QuestionnaireResponse.item |
| QuestionnaireResponse.item.id | UseExtensionFromAncestor | - |
| QuestionnaireResponse.item.extension | UseExtensionFromAncestor | - |
| QuestionnaireResponse.item.modifierExtension | UseExtensionFromAncestor | - |
| QuestionnaireResponse.item.linkId | UseExtensionFromAncestor | - |
| QuestionnaireResponse.item.definition | UseExtensionFromAncestor | - |
| QuestionnaireResponse.item.text | UseExtensionFromAncestor | - |
| QuestionnaireResponse.item.answer | UseExtensionFromAncestor | - |
| QuestionnaireResponse.item.answer.id | UseExtensionFromAncestor | - |
| QuestionnaireResponse.item.answer.extension | UseExtensionFromAncestor | - |
| QuestionnaireResponse.item.answer.modifierExtension | UseExtensionFromAncestor | - |
| QuestionnaireResponse.item.answer.value[x] | UseExtensionFromAncestor | - |
| QuestionnaireResponse.item.answer.item | UseExtensionFromAncestor | - |
| QuestionnaireResponse.item.item | UseExtensionFromAncestor | - |
