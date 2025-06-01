### Lookup for FHIR R5 ClinicalImpression for use in FHIR R4

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| ClinicalImpression.id | UseElementSameName | ClinicalImpression.id |
| ClinicalImpression.meta | UseElementSameName | ClinicalImpression.meta |
| ClinicalImpression.implicitRules | UseElementSameName | ClinicalImpression.implicitRules |
| ClinicalImpression.language | UseElementSameName | ClinicalImpression.language |
| ClinicalImpression.text | UseElementSameName | ClinicalImpression.text |
| ClinicalImpression.contained | UseElementSameName | ClinicalImpression.contained |
| ClinicalImpression.extension | UseElementSameName | ClinicalImpression.extension |
| ClinicalImpression.modifierExtension | UseElementSameName | ClinicalImpression.modifierExtension |
| ClinicalImpression.identifier | UseElementSameName | ClinicalImpression.identifier |
| ClinicalImpression.status | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClinicalImpression.status |
| ClinicalImpression.statusReason | UseElementSameName | ClinicalImpression.statusReason |
| ClinicalImpression.description | UseElementSameName | ClinicalImpression.description |
| ClinicalImpression.subject | UseElementSameName | ClinicalImpression.subject |
| ClinicalImpression.encounter | UseElementSameName | ClinicalImpression.encounter |
| ClinicalImpression.effective[x] | UseElementSameName | ClinicalImpression.effective[x] |
| ClinicalImpression.date | UseElementSameName | ClinicalImpression.date |
| ClinicalImpression.performer | UseElementRenamed | ClinicalImpression.assessor |
| ClinicalImpression.previous | UseElementSameName | ClinicalImpression.previous |
| ClinicalImpression.problem | UseElementSameName | ClinicalImpression.problem |
| ClinicalImpression.changePattern | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClinicalImpression.changePattern |
| ClinicalImpression.protocol | UseElementSameName | ClinicalImpression.protocol |
| ClinicalImpression.summary | UseElementSameName | ClinicalImpression.summary |
| ClinicalImpression.finding | UseElementSameName | ClinicalImpression.finding |
| ClinicalImpression.finding.id | UseElementSameName | ClinicalImpression.finding.id |
| ClinicalImpression.finding.extension | UseElementSameName | ClinicalImpression.finding.extension |
| ClinicalImpression.finding.modifierExtension | UseElementSameName | ClinicalImpression.finding.modifierExtension |
| ClinicalImpression.finding.item | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-ClinicalImpression.finding.item |
| ClinicalImpression.finding.basis | UseElementSameName | ClinicalImpression.finding.basis |
| ClinicalImpression.prognosisCodeableConcept | UseElementSameName | ClinicalImpression.prognosisCodeableConcept |
| ClinicalImpression.prognosisReference | UseElementSameName | ClinicalImpression.prognosisReference |
| ClinicalImpression.supportingInfo | UseElementSameName | ClinicalImpression.supportingInfo |
| ClinicalImpression.note | UseElementSameName | ClinicalImpression.note |
