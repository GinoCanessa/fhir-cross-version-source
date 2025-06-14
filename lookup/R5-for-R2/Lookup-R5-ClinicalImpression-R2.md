### Lookup for FHIR R5 ClinicalImpression for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| ClinicalImpression.id | UseElementSameName | ClinicalImpression.id |
| ClinicalImpression.meta | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClinicalImpression.meta |
| ClinicalImpression.implicitRules | UseElementSameName | ClinicalImpression.implicitRules |
| ClinicalImpression.language | UseElementSameName | ClinicalImpression.language |
| ClinicalImpression.text | UseElementSameName | ClinicalImpression.text |
| ClinicalImpression.contained | UseElementSameName | ClinicalImpression.contained |
| ClinicalImpression.extension | UseElementSameName | ClinicalImpression.extension |
| ClinicalImpression.modifierExtension | UseElementSameName | ClinicalImpression.modifierExtension |
| ClinicalImpression.identifier | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClinicalImpression.identifier |
| ClinicalImpression.status | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClinicalImpression.status |
| ClinicalImpression.statusReason | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClinicalImpression.statusReason |
| ClinicalImpression.description | UseElementSameName | ClinicalImpression.description |
| ClinicalImpression.subject | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClinicalImpression.subject |
| ClinicalImpression.encounter | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClinicalImpression.encounter |
| ClinicalImpression.effective[x] | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClinicalImpression.effective |
| ClinicalImpression.date | UseElementSameName | ClinicalImpression.date |
| ClinicalImpression.performer | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClinicalImpression.performer |
| ClinicalImpression.previous | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClinicalImpression.previous |
| ClinicalImpression.problem | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClinicalImpression.problem |
| ClinicalImpression.changePattern | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClinicalImpression.changePattern |
| ClinicalImpression.protocol | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClinicalImpression.protocol |
| ClinicalImpression.summary | UseElementSameName | ClinicalImpression.summary |
| ClinicalImpression.finding | UseElementSameName | ClinicalImpression.finding |
| ClinicalImpression.finding.id | UseElementSameName | ClinicalImpression.finding.id |
| ClinicalImpression.finding.extension | UseElementSameName | ClinicalImpression.finding.extension |
| ClinicalImpression.finding.modifierExtension | UseElementSameName | ClinicalImpression.finding.modifierExtension |
| ClinicalImpression.finding.item | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClinicalImpression.finding.item |
| ClinicalImpression.finding.basis | UseElementRenamed | ClinicalImpression.finding.cause |
| ClinicalImpression.prognosisCodeableConcept | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClinicalImpression.prognosisCodeableConcept |
| ClinicalImpression.prognosisReference | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClinicalImpression.prognosisReference |
| ClinicalImpression.supportingInfo | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClinicalImpression.supportingInfo |
| ClinicalImpression.note | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClinicalImpression.note |
