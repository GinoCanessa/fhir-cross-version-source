### Lookup for FHIR R4B ImmunizationRecommendation for use in FHIR R3

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| ImmunizationRecommendation.id | UseElementSameName | ImmunizationRecommendation.id |
| ImmunizationRecommendation.meta | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-ImmunizationRecommendation.meta |
| ImmunizationRecommendation.implicitRules | UseElementSameName | ImmunizationRecommendation.implicitRules |
| ImmunizationRecommendation.language | UseElementSameName | ImmunizationRecommendation.language |
| ImmunizationRecommendation.text | UseElementSameName | ImmunizationRecommendation.text |
| ImmunizationRecommendation.contained | UseElementSameName | ImmunizationRecommendation.contained |
| ImmunizationRecommendation.extension | UseElementSameName | ImmunizationRecommendation.extension |
| ImmunizationRecommendation.modifierExtension | UseElementSameName | ImmunizationRecommendation.modifierExtension |
| ImmunizationRecommendation.identifier | UseElementSameName | ImmunizationRecommendation.identifier |
| ImmunizationRecommendation.patient | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-ImmunizationRecommendation.patient |
| ImmunizationRecommendation.date | UseElementRenamed | ImmunizationRecommendation.recommendation.date |
| ImmunizationRecommendation.authority | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-ImmunizationRecommendation.authority |
| ImmunizationRecommendation.recommendation | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-ImmunizationRecommendation.recommendation |
| ImmunizationRecommendation.recommendation.id | UseExtensionFromAncestor | - |
| ImmunizationRecommendation.recommendation.extension | UseExtensionFromAncestor | - |
| ImmunizationRecommendation.recommendation.modifierExtension | UseExtensionFromAncestor | - |
| ImmunizationRecommendation.recommendation.vaccineCode | UseExtensionFromAncestor | - |
| ImmunizationRecommendation.recommendation.targetDisease | UseExtensionFromAncestor | - |
| ImmunizationRecommendation.recommendation.contraindicatedVaccineCode | UseExtensionFromAncestor | - |
| ImmunizationRecommendation.recommendation.forecastStatus | UseExtensionFromAncestor | - |
| ImmunizationRecommendation.recommendation.forecastReason | UseExtensionFromAncestor | - |
| ImmunizationRecommendation.recommendation.dateCriterion | UseExtensionFromAncestor | - |
| ImmunizationRecommendation.recommendation.dateCriterion.id | UseExtensionFromAncestor | - |
| ImmunizationRecommendation.recommendation.dateCriterion.extension | UseExtensionFromAncestor | - |
| ImmunizationRecommendation.recommendation.dateCriterion.modifierExtension | UseExtensionFromAncestor | - |
| ImmunizationRecommendation.recommendation.dateCriterion.code | UseExtensionFromAncestor | - |
| ImmunizationRecommendation.recommendation.dateCriterion.value | UseExtensionFromAncestor | - |
| ImmunizationRecommendation.recommendation.description | UseExtensionFromAncestor | - |
| ImmunizationRecommendation.recommendation.series | UseExtensionFromAncestor | - |
| ImmunizationRecommendation.recommendation.doseNumber[x] | UseExtensionFromAncestor | - |
| ImmunizationRecommendation.recommendation.seriesDoses[x] | UseExtensionFromAncestor | - |
| ImmunizationRecommendation.recommendation.supportingImmunization | UseExtensionFromAncestor | - |
| ImmunizationRecommendation.recommendation.supportingPatientInformation | UseExtensionFromAncestor | - |
