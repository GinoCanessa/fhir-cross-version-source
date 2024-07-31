Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | ClinicalImpression |  | A record of a clinical assessment performed to determine what problem(s) may affect the patient and before planning the treatments or management strategies that are best to manage a patient's condition. Assessments are often 1:1 with a clinical consultation / encounter,  but this varies greatly depending on the clinical workflow. This resource is called "ClinicalImpression" rather than "ClinicalAssessment" to avoid confusion with the recording of assessment tools such as Apgar score. | 33 | 22 |
| Target | ClinicalImpression |  | A record of a clinical assessment performed to determine what problem(s) may affect the patient and before planning the treatments or management strategies that are best to manage a patient's condition. Assessments are often 1:1 with a clinical consultation / encounter,  but this varies greatly depending on the clinical workflow. This resource is called "ClinicalImpression" rather than "ClinicalAssessment" to avoid confusion with the recording of assessment tools such as Apgar score. | 40 | 26 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 1 |
Equivalent | 25 |
RelatedTo | 1 |
SourceIsBroaderThanTarget | 5 |
SourceIsNarrowerThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| ClinicalImpression | ClinicalImpression | Equivalent | R5 `ClinicalImpression` maps as Equivalent to R4 `ClinicalImpression` |
| ClinicalImpression.changePattern | - | DoesNotExistInTarget | R5 `ClinicalImpression.changePattern` does not appear in the target and has no mapping for `ClinicalImpression`. |
| ClinicalImpression.contained | ClinicalImpression.contained | Equivalent | R5 `ClinicalImpression.contained` maps as Equivalent to R4 `ClinicalImpression.contained` |
| ClinicalImpression.date | ClinicalImpression.date | Equivalent | R5 `ClinicalImpression.date` maps as Equivalent to R4 `ClinicalImpression.date` |
| ClinicalImpression.description | ClinicalImpression.description | Equivalent | R5 `ClinicalImpression.description` maps as Equivalent to R4 `ClinicalImpression.description` |
| ClinicalImpression.effective[x] | ClinicalImpression.effective[x] | Equivalent | R5 `ClinicalImpression.effective[x]` maps as Equivalent to R4 `ClinicalImpression.effective[x]` |
| ClinicalImpression.encounter | ClinicalImpression.encounter | Equivalent | R5 `ClinicalImpression.encounter` maps as Equivalent to R4 `ClinicalImpression.encounter` |
| ClinicalImpression.extension | ClinicalImpression.extension | SourceIsBroaderThanTarget | R5 `ClinicalImpression.extension` maps as SourceIsBroaderThanTarget to R4 `ClinicalImpression.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ClinicalImpression.finding | ClinicalImpression.finding | Equivalent | R5 `ClinicalImpression.finding` maps as Equivalent to R4 `ClinicalImpression.finding` |
| ClinicalImpression.finding.basis | ClinicalImpression.finding.basis | Equivalent | R5 `ClinicalImpression.finding.basis` maps as Equivalent to R4 `ClinicalImpression.finding.basis` |
| ClinicalImpression.finding.extension | ClinicalImpression.finding.extension | SourceIsBroaderThanTarget | R5 `ClinicalImpression.finding.extension` maps as SourceIsBroaderThanTarget to R4 `ClinicalImpression.finding.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ClinicalImpression.finding.id | ClinicalImpression.finding.id | Equivalent | R5 `ClinicalImpression.finding.id` maps as Equivalent to R4 `ClinicalImpression.finding.id` |
| ClinicalImpression.finding.item | ClinicalImpression.finding.itemCodeableConcept | SourceIsBroaderThanTarget | R5 `ClinicalImpression.finding.item` maps as SourceIsBroaderThanTarget to R4 `ClinicalImpression.finding.itemCodeableConcept` - itemCodeableConcept has change due to type change: R5 item CodeableReference has no equivalent or mapped type in R4 itemCodeableConcept |
| ClinicalImpression.finding.item | ClinicalImpression.finding.itemReference | RelatedTo | R5 `ClinicalImpression.finding.item` maps as RelatedTo to R4 `ClinicalImpression.finding.itemReference` - itemReference removed a binding requirement - Example http://hl7.org/fhir/ValueSet/condition-code; itemReference has change due to type change: R5 item CodeableReference has no equivalent or mapped type in R4 itemReference |
| ClinicalImpression.finding.modifierExtension | ClinicalImpression.finding.modifierExtension | SourceIsBroaderThanTarget | R5 `ClinicalImpression.finding.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ClinicalImpression.finding.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ClinicalImpression.id | ClinicalImpression.id | Equivalent | R5 `ClinicalImpression.id` maps as Equivalent to R4 `ClinicalImpression.id` |
| ClinicalImpression.identifier | ClinicalImpression.identifier | Equivalent | R5 `ClinicalImpression.identifier` maps as Equivalent to R4 `ClinicalImpression.identifier` |
| ClinicalImpression.implicitRules | ClinicalImpression.implicitRules | Equivalent | R5 `ClinicalImpression.implicitRules` maps as Equivalent to R4 `ClinicalImpression.implicitRules` |
| ClinicalImpression.language | ClinicalImpression.language | SourceIsNarrowerThanTarget | R5 `ClinicalImpression.language` maps as SourceIsNarrowerThanTarget to R4 `ClinicalImpression.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| ClinicalImpression.meta | ClinicalImpression.meta | Equivalent | R5 `ClinicalImpression.meta` maps as Equivalent to R4 `ClinicalImpression.meta` |
| ClinicalImpression.modifierExtension | ClinicalImpression.modifierExtension | SourceIsBroaderThanTarget | R5 `ClinicalImpression.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ClinicalImpression.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ClinicalImpression.note | ClinicalImpression.note | SourceIsBroaderThanTarget | R5 `ClinicalImpression.note` maps as SourceIsBroaderThanTarget to R4 `ClinicalImpression.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4 `note` |
| ClinicalImpression.performer | ClinicalImpression.assessor | Equivalent | R5 `ClinicalImpression.performer` maps as Equivalent to R4 `ClinicalImpression.assessor` |
| ClinicalImpression.previous | ClinicalImpression.previous | Equivalent | R5 `ClinicalImpression.previous` maps as Equivalent to R4 `ClinicalImpression.previous` |
| ClinicalImpression.problem | ClinicalImpression.problem | Equivalent | R5 `ClinicalImpression.problem` maps as Equivalent to R4 `ClinicalImpression.problem` |
| ClinicalImpression.prognosisCodeableConcept | ClinicalImpression.prognosisCodeableConcept | Equivalent | R5 `ClinicalImpression.prognosisCodeableConcept` maps as Equivalent to R4 `ClinicalImpression.prognosisCodeableConcept` |
| ClinicalImpression.prognosisReference | ClinicalImpression.prognosisReference | Equivalent | R5 `ClinicalImpression.prognosisReference` maps as Equivalent to R4 `ClinicalImpression.prognosisReference` |
| ClinicalImpression.protocol | ClinicalImpression.protocol | Equivalent | R5 `ClinicalImpression.protocol` maps as Equivalent to R4 `ClinicalImpression.protocol` |
| ClinicalImpression.status | ClinicalImpression.status | Equivalent | R5 `ClinicalImpression.status` maps as Equivalent to R4 `ClinicalImpression.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/event-status|5.0.0 and http://hl7.org/fhir/ValueSet/clinicalimpression-status|4.0.1 (Equivalent) |
| ClinicalImpression.statusReason | ClinicalImpression.statusReason | Equivalent | R5 `ClinicalImpression.statusReason` maps as Equivalent to R4 `ClinicalImpression.statusReason` |
| ClinicalImpression.subject | ClinicalImpression.subject | Equivalent | R5 `ClinicalImpression.subject` maps as Equivalent to R4 `ClinicalImpression.subject` |
| ClinicalImpression.summary | ClinicalImpression.summary | Equivalent | R5 `ClinicalImpression.summary` maps as Equivalent to R4 `ClinicalImpression.summary` |
| ClinicalImpression.supportingInfo | ClinicalImpression.supportingInfo | Equivalent | R5 `ClinicalImpression.supportingInfo` maps as Equivalent to R4 `ClinicalImpression.supportingInfo` |
| ClinicalImpression.text | ClinicalImpression.text | Equivalent | R5 `ClinicalImpression.text` maps as Equivalent to R4 `ClinicalImpression.text` |

