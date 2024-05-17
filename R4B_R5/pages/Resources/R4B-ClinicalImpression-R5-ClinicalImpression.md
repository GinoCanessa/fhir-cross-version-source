Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | ClinicalImpression |  | A record of a clinical assessment performed to determine what problem(s) may affect the patient and before planning the treatments or management strategies that are best to manage a patient's condition. Assessments are often 1:1 with a clinical consultation / encounter,  but this varies greatly depending on the clinical workflow. This resource is called "ClinicalImpression" rather than "ClinicalAssessment" to avoid confusion with the recording of assessment tools such as Apgar score. | 40 | 26 |
| Target | ClinicalImpression |  | A record of a clinical assessment performed to determine what problem(s) may affect the patient and before planning the treatments or management strategies that are best to manage a patient's condition. Assessments are often 1:1 with a clinical consultation / encounter,  but this varies greatly depending on the clinical workflow. This resource is called "ClinicalImpression" rather than "ClinicalAssessment" to avoid confusion with the recording of assessment tools such as Apgar score. | 33 | 22 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 10 |
Equivalent | 4 |
RelatedTo | 26 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| ClinicalImpression | ClinicalImpression | Equivalent | R4B `ClinicalImpression` maps as Equivalent to R5 `ClinicalImpression` |
| ClinicalImpression.assessor | - | DoesNotExistInTarget | R4B `ClinicalImpression.assessor` does not appear in the target and has no mapping for `ClinicalImpression`. |
| ClinicalImpression.code | - | DoesNotExistInTarget | R4B `ClinicalImpression.code` does not appear in the target and has no mapping for `ClinicalImpression`. |
| ClinicalImpression.contained | ClinicalImpression.contained | Equivalent | R4B `ClinicalImpression.contained` maps as Equivalent to R5 `ClinicalImpression.contained` |
| ClinicalImpression.date | ClinicalImpression.date | Equivalent | R4B `ClinicalImpression.date` maps as Equivalent to R5 `ClinicalImpression.date` |
| ClinicalImpression.description | ClinicalImpression.description | Equivalent | R4B `ClinicalImpression.description` maps as Equivalent to R5 `ClinicalImpression.description` |
| ClinicalImpression.effective[x] | ClinicalImpression.effective[x] | Equivalent | R4B `ClinicalImpression.effective[x]` maps as Equivalent to R5 `ClinicalImpression.effective[x]` |
| ClinicalImpression.encounter | ClinicalImpression.encounter | Equivalent | R4B `ClinicalImpression.encounter` maps as Equivalent to R5 `ClinicalImpression.encounter` |
| ClinicalImpression.extension | ClinicalImpression.extension | RelatedTo | R4B `ClinicalImpression.extension` maps as RelatedTo to R5 `ClinicalImpression.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ClinicalImpression.finding | ClinicalImpression.finding | Equivalent | R4B `ClinicalImpression.finding` maps as Equivalent to R5 `ClinicalImpression.finding` |
| ClinicalImpression.finding.basis | ClinicalImpression.finding.basis | Equivalent | R4B `ClinicalImpression.finding.basis` maps as Equivalent to R5 `ClinicalImpression.finding.basis` |
| ClinicalImpression.finding.extension | ClinicalImpression.finding.extension | RelatedTo | R4B `ClinicalImpression.finding.extension` maps as RelatedTo to R5 `ClinicalImpression.finding.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ClinicalImpression.finding.id | ClinicalImpression.finding.id | Equivalent | R4B `ClinicalImpression.finding.id` maps as Equivalent to R5 `ClinicalImpression.finding.id` |
| ClinicalImpression.finding.itemCodeableConcept | - | DoesNotExistInTarget | R4B `ClinicalImpression.finding.itemCodeableConcept` does not appear in the target and has no mapping for `ClinicalImpression`. |
| ClinicalImpression.finding.itemReference | - | DoesNotExistInTarget | R4B `ClinicalImpression.finding.itemReference` does not appear in the target and has no mapping for `ClinicalImpression`. |
| ClinicalImpression.finding.modifierExtension | ClinicalImpression.finding.modifierExtension | RelatedTo | R4B `ClinicalImpression.finding.modifierExtension` maps as RelatedTo to R5 `ClinicalImpression.finding.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ClinicalImpression.id | ClinicalImpression.id | Equivalent | R4B `ClinicalImpression.id` maps as Equivalent to R5 `ClinicalImpression.id` |
| ClinicalImpression.identifier | ClinicalImpression.identifier | Equivalent | R4B `ClinicalImpression.identifier` maps as Equivalent to R5 `ClinicalImpression.identifier` |
| ClinicalImpression.implicitRules | ClinicalImpression.implicitRules | Equivalent | R4B `ClinicalImpression.implicitRules` maps as Equivalent to R5 `ClinicalImpression.implicitRules` |
| ClinicalImpression.investigation | - | DoesNotExistInTarget | R4B `ClinicalImpression.investigation` does not appear in the target and has no mapping for `ClinicalImpression`. |
| ClinicalImpression.investigation.code | - | DoesNotExistInTarget | R4B `ClinicalImpression.investigation.code` does not appear in the target and has no mapping for `ClinicalImpression`. |
| ClinicalImpression.investigation.extension | - | DoesNotExistInTarget | R4B `ClinicalImpression.investigation.extension` does not appear in the target and has no mapping for `ClinicalImpression`. |
| ClinicalImpression.investigation.id | - | DoesNotExistInTarget | R4B `ClinicalImpression.investigation.id` does not appear in the target and has no mapping for `ClinicalImpression`. |
| ClinicalImpression.investigation.item | - | DoesNotExistInTarget | R4B `ClinicalImpression.investigation.item` does not appear in the target and has no mapping for `ClinicalImpression`. |
| ClinicalImpression.investigation.modifierExtension | - | DoesNotExistInTarget | R4B `ClinicalImpression.investigation.modifierExtension` does not appear in the target and has no mapping for `ClinicalImpression`. |
| ClinicalImpression.language | ClinicalImpression.language | RelatedTo | R4B `ClinicalImpression.language` maps as RelatedTo to R5 `ClinicalImpression.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| ClinicalImpression.meta | ClinicalImpression.meta | Equivalent | R4B `ClinicalImpression.meta` maps as Equivalent to R5 `ClinicalImpression.meta` |
| ClinicalImpression.modifierExtension | ClinicalImpression.modifierExtension | RelatedTo | R4B `ClinicalImpression.modifierExtension` maps as RelatedTo to R5 `ClinicalImpression.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ClinicalImpression.note | ClinicalImpression.note | SourceIsNarrowerThanTarget | R4B `ClinicalImpression.note` maps as SourceIsNarrowerThanTarget to R5 `ClinicalImpression.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| ClinicalImpression.previous | ClinicalImpression.previous | Equivalent | R4B `ClinicalImpression.previous` maps as Equivalent to R5 `ClinicalImpression.previous` |
| ClinicalImpression.problem | ClinicalImpression.problem | Equivalent | R4B `ClinicalImpression.problem` maps as Equivalent to R5 `ClinicalImpression.problem` |
| ClinicalImpression.prognosisCodeableConcept | ClinicalImpression.prognosisCodeableConcept | Equivalent | R4B `ClinicalImpression.prognosisCodeableConcept` maps as Equivalent to R5 `ClinicalImpression.prognosisCodeableConcept` |
| ClinicalImpression.prognosisReference | ClinicalImpression.prognosisReference | Equivalent | R4B `ClinicalImpression.prognosisReference` maps as Equivalent to R5 `ClinicalImpression.prognosisReference` |
| ClinicalImpression.protocol | ClinicalImpression.protocol | Equivalent | R4B `ClinicalImpression.protocol` maps as Equivalent to R5 `ClinicalImpression.protocol` |
| ClinicalImpression.status | ClinicalImpression.status | Equivalent | R4B `ClinicalImpression.status` maps as Equivalent to R5 `ClinicalImpression.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/clinicalimpression-status|4.3.0 and http://hl7.org/fhir/ValueSet/event-status|5.0.0 (Equivalent) |
| ClinicalImpression.statusReason | ClinicalImpression.statusReason | Equivalent | R4B `ClinicalImpression.statusReason` maps as Equivalent to R5 `ClinicalImpression.statusReason` |
| ClinicalImpression.subject | ClinicalImpression.subject | Equivalent | R4B `ClinicalImpression.subject` maps as Equivalent to R5 `ClinicalImpression.subject` |
| ClinicalImpression.summary | ClinicalImpression.summary | Equivalent | R4B `ClinicalImpression.summary` maps as Equivalent to R5 `ClinicalImpression.summary` |
| ClinicalImpression.supportingInfo | ClinicalImpression.supportingInfo | Equivalent | R4B `ClinicalImpression.supportingInfo` maps as Equivalent to R5 `ClinicalImpression.supportingInfo` |
| ClinicalImpression.text | ClinicalImpression.text | Equivalent | R4B `ClinicalImpression.text` maps as Equivalent to R5 `ClinicalImpression.text` |

