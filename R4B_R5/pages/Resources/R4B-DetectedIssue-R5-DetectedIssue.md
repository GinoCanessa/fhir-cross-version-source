Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | DetectedIssue |  | Indicates an actual or potential clinical issue with or between one or more active or proposed clinical actions for a patient; e.g. Drug-drug interaction, Ineffective treatment frequency, Procedure-condition conflict, etc. | 32 | 18 |
| Target | DetectedIssue |  | Indicates an actual or potential clinical issue with or between one or more active or proposed clinical actions for a patient; e.g. Drug-drug interaction, Ineffective treatment frequency, Procedure-condition conflict, gaps in care, etc. | 35 | 21 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 1 |
Equivalent | 4 |
RelatedTo | 27 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| DetectedIssue | DetectedIssue | Equivalent | R4B `DetectedIssue` maps as Equivalent to R5 `DetectedIssue` |
| DetectedIssue.author | DetectedIssue.author | SourceIsNarrowerThanTarget | R4B `DetectedIssue.author` maps as SourceIsNarrowerThanTarget to R5 `DetectedIssue.author` - author has change due to type change: R4B `author` `Reference` maps as SourceIsNarrowerThanTarget for R5 `author` |
| DetectedIssue.code | DetectedIssue.code | Equivalent | R4B `DetectedIssue.code` maps as Equivalent to R5 `DetectedIssue.code` |
| DetectedIssue.contained | DetectedIssue.contained | Equivalent | R4B `DetectedIssue.contained` maps as Equivalent to R5 `DetectedIssue.contained` |
| DetectedIssue.detail | DetectedIssue.detail | SourceIsBroaderThanTarget | R4B `DetectedIssue.detail` maps as SourceIsBroaderThanTarget to R5 `DetectedIssue.detail` - detail has change due to type change: R4B detail string has no equivalent or mapped type in R5 detail |
| DetectedIssue.evidence | DetectedIssue.evidence | Equivalent | R4B `DetectedIssue.evidence` maps as Equivalent to R5 `DetectedIssue.evidence` |
| DetectedIssue.evidence.code | DetectedIssue.evidence.code | Equivalent | R4B `DetectedIssue.evidence.code` maps as Equivalent to R5 `DetectedIssue.evidence.code` |
| DetectedIssue.evidence.detail | DetectedIssue.evidence.detail | Equivalent | R4B `DetectedIssue.evidence.detail` maps as Equivalent to R5 `DetectedIssue.evidence.detail` |
| DetectedIssue.evidence.extension | DetectedIssue.evidence.extension | RelatedTo | R4B `DetectedIssue.evidence.extension` maps as RelatedTo to R5 `DetectedIssue.evidence.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| DetectedIssue.evidence.id | DetectedIssue.evidence.id | Equivalent | R4B `DetectedIssue.evidence.id` maps as Equivalent to R5 `DetectedIssue.evidence.id` |
| DetectedIssue.evidence.modifierExtension | DetectedIssue.evidence.modifierExtension | RelatedTo | R4B `DetectedIssue.evidence.modifierExtension` maps as RelatedTo to R5 `DetectedIssue.evidence.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| DetectedIssue.extension | DetectedIssue.extension | RelatedTo | R4B `DetectedIssue.extension` maps as RelatedTo to R5 `DetectedIssue.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| DetectedIssue.id | DetectedIssue.id | Equivalent | R4B `DetectedIssue.id` maps as Equivalent to R5 `DetectedIssue.id` |
| DetectedIssue.identified[x] | DetectedIssue.identified[x] | Equivalent | R4B `DetectedIssue.identified[x]` maps as Equivalent to R5 `DetectedIssue.identified[x]` |
| DetectedIssue.identifier | DetectedIssue.identifier | Equivalent | R4B `DetectedIssue.identifier` maps as Equivalent to R5 `DetectedIssue.identifier` |
| DetectedIssue.implicated | DetectedIssue.implicated | Equivalent | R4B `DetectedIssue.implicated` maps as Equivalent to R5 `DetectedIssue.implicated` |
| DetectedIssue.implicitRules | DetectedIssue.implicitRules | Equivalent | R4B `DetectedIssue.implicitRules` maps as Equivalent to R5 `DetectedIssue.implicitRules` |
| DetectedIssue.language | DetectedIssue.language | RelatedTo | R4B `DetectedIssue.language` maps as RelatedTo to R5 `DetectedIssue.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| DetectedIssue.meta | DetectedIssue.meta | Equivalent | R4B `DetectedIssue.meta` maps as Equivalent to R5 `DetectedIssue.meta` |
| DetectedIssue.mitigation | DetectedIssue.mitigation | Equivalent | R4B `DetectedIssue.mitigation` maps as Equivalent to R5 `DetectedIssue.mitigation` |
| DetectedIssue.mitigation.action | DetectedIssue.mitigation.action | Equivalent | R4B `DetectedIssue.mitigation.action` maps as Equivalent to R5 `DetectedIssue.mitigation.action` |
| DetectedIssue.mitigation.author | DetectedIssue.mitigation.author | Equivalent | R4B `DetectedIssue.mitigation.author` maps as Equivalent to R5 `DetectedIssue.mitigation.author` |
| DetectedIssue.mitigation.date | DetectedIssue.mitigation.date | Equivalent | R4B `DetectedIssue.mitigation.date` maps as Equivalent to R5 `DetectedIssue.mitigation.date` |
| DetectedIssue.mitigation.extension | DetectedIssue.mitigation.extension | RelatedTo | R4B `DetectedIssue.mitigation.extension` maps as RelatedTo to R5 `DetectedIssue.mitigation.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| DetectedIssue.mitigation.id | DetectedIssue.mitigation.id | Equivalent | R4B `DetectedIssue.mitigation.id` maps as Equivalent to R5 `DetectedIssue.mitigation.id` |
| DetectedIssue.mitigation.modifierExtension | DetectedIssue.mitigation.modifierExtension | RelatedTo | R4B `DetectedIssue.mitigation.modifierExtension` maps as RelatedTo to R5 `DetectedIssue.mitigation.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| DetectedIssue.modifierExtension | DetectedIssue.modifierExtension | RelatedTo | R4B `DetectedIssue.modifierExtension` maps as RelatedTo to R5 `DetectedIssue.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| DetectedIssue.patient | - | DoesNotExistInTarget | R4B `DetectedIssue.patient` does not appear in the target and has no mapping for `DetectedIssue`. |
| DetectedIssue.reference | DetectedIssue.reference | Equivalent | R4B `DetectedIssue.reference` maps as Equivalent to R5 `DetectedIssue.reference` |
| DetectedIssue.severity | DetectedIssue.severity | Equivalent | R4B `DetectedIssue.severity` maps as Equivalent to R5 `DetectedIssue.severity` - severity has compatible required binding for code type: http://hl7.org/fhir/ValueSet/detectedissue-severity|4.3.0 and http://hl7.org/fhir/ValueSet/detectedissue-severity|5.0.0 (Equivalent) |
| DetectedIssue.status | DetectedIssue.status | Equivalent | R4B `DetectedIssue.status` maps as Equivalent to R5 `DetectedIssue.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/observation-status|4.3.0 and http://hl7.org/fhir/ValueSet/detectedissue-status|5.0.0 (Equivalent) |
| DetectedIssue.text | DetectedIssue.text | Equivalent | R4B `DetectedIssue.text` maps as Equivalent to R5 `DetectedIssue.text` |

