Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | DetectedIssue |  | Indicates an actual or potential clinical issue with or between one or more active or proposed clinical actions for a patient; e.g. Drug-drug interaction, Ineffective treatment frequency, Procedure-condition conflict, gaps in care, etc. | 35 | 21 |
| Target | DetectedIssue |  | Indicates an actual or potential clinical issue with or between one or more active or proposed clinical actions for a patient; e.g. Drug-drug interaction, Ineffective treatment frequency, Procedure-condition conflict, etc. | 32 | 18 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 3 |
Equivalent | 21 |
RelatedTo | 1 |
SourceIsBroaderThanTarget | 9 |
SourceIsNarrowerThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| DetectedIssue | DetectedIssue | Equivalent | R5 `DetectedIssue` maps as Equivalent to R4 `DetectedIssue` |
| DetectedIssue.author | DetectedIssue.author | SourceIsBroaderThanTarget | R5 `DetectedIssue.author` maps as SourceIsBroaderThanTarget to R4 `DetectedIssue.author` - author has change due to type change: R5 `author` `Reference` maps as SourceIsBroaderThanTarget for R4 `author` |
| DetectedIssue.category | - | DoesNotExistInTarget | R5 `DetectedIssue.category` does not appear in the target and has no mapping for `DetectedIssue`. |
| DetectedIssue.code | DetectedIssue.code | Equivalent | R5 `DetectedIssue.code` maps as Equivalent to R4 `DetectedIssue.code` |
| DetectedIssue.contained | DetectedIssue.contained | Equivalent | R5 `DetectedIssue.contained` maps as Equivalent to R4 `DetectedIssue.contained` |
| DetectedIssue.detail | DetectedIssue.detail | SourceIsBroaderThanTarget | R5 `DetectedIssue.detail` maps as SourceIsBroaderThanTarget to R4 `DetectedIssue.detail` - detail has change due to type change: R5 detail markdown has no equivalent or mapped type in R4 detail |
| DetectedIssue.encounter | - | DoesNotExistInTarget | R5 `DetectedIssue.encounter` does not appear in the target and has no mapping for `DetectedIssue`. |
| DetectedIssue.evidence | DetectedIssue.evidence | Equivalent | R5 `DetectedIssue.evidence` maps as Equivalent to R4 `DetectedIssue.evidence` |
| DetectedIssue.evidence.code | DetectedIssue.evidence.code | Equivalent | R5 `DetectedIssue.evidence.code` maps as Equivalent to R4 `DetectedIssue.evidence.code` |
| DetectedIssue.evidence.detail | DetectedIssue.evidence.detail | Equivalent | R5 `DetectedIssue.evidence.detail` maps as Equivalent to R4 `DetectedIssue.evidence.detail` |
| DetectedIssue.evidence.extension | DetectedIssue.evidence.extension | SourceIsBroaderThanTarget | R5 `DetectedIssue.evidence.extension` maps as SourceIsBroaderThanTarget to R4 `DetectedIssue.evidence.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| DetectedIssue.evidence.id | DetectedIssue.evidence.id | Equivalent | R5 `DetectedIssue.evidence.id` maps as Equivalent to R4 `DetectedIssue.evidence.id` |
| DetectedIssue.evidence.modifierExtension | DetectedIssue.evidence.modifierExtension | SourceIsBroaderThanTarget | R5 `DetectedIssue.evidence.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `DetectedIssue.evidence.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| DetectedIssue.extension | DetectedIssue.extension | SourceIsBroaderThanTarget | R5 `DetectedIssue.extension` maps as SourceIsBroaderThanTarget to R4 `DetectedIssue.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| DetectedIssue.id | DetectedIssue.id | Equivalent | R5 `DetectedIssue.id` maps as Equivalent to R4 `DetectedIssue.id` |
| DetectedIssue.identified[x] | DetectedIssue.identified[x] | Equivalent | R5 `DetectedIssue.identified[x]` maps as Equivalent to R4 `DetectedIssue.identified[x]` |
| DetectedIssue.identifier | DetectedIssue.identifier | Equivalent | R5 `DetectedIssue.identifier` maps as Equivalent to R4 `DetectedIssue.identifier` |
| DetectedIssue.implicated | DetectedIssue.implicated | Equivalent | R5 `DetectedIssue.implicated` maps as Equivalent to R4 `DetectedIssue.implicated` |
| DetectedIssue.implicitRules | DetectedIssue.implicitRules | Equivalent | R5 `DetectedIssue.implicitRules` maps as Equivalent to R4 `DetectedIssue.implicitRules` |
| DetectedIssue.language | DetectedIssue.language | SourceIsNarrowerThanTarget | R5 `DetectedIssue.language` maps as SourceIsNarrowerThanTarget to R4 `DetectedIssue.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| DetectedIssue.meta | DetectedIssue.meta | Equivalent | R5 `DetectedIssue.meta` maps as Equivalent to R4 `DetectedIssue.meta` |
| DetectedIssue.mitigation | DetectedIssue.mitigation | Equivalent | R5 `DetectedIssue.mitigation` maps as Equivalent to R4 `DetectedIssue.mitigation` |
| DetectedIssue.mitigation.action | DetectedIssue.mitigation.action | Equivalent | R5 `DetectedIssue.mitigation.action` maps as Equivalent to R4 `DetectedIssue.mitigation.action` |
| DetectedIssue.mitigation.author | DetectedIssue.mitigation.author | Equivalent | R5 `DetectedIssue.mitigation.author` maps as Equivalent to R4 `DetectedIssue.mitigation.author` |
| DetectedIssue.mitigation.date | DetectedIssue.mitigation.date | Equivalent | R5 `DetectedIssue.mitigation.date` maps as Equivalent to R4 `DetectedIssue.mitigation.date` |
| DetectedIssue.mitigation.extension | DetectedIssue.mitigation.extension | SourceIsBroaderThanTarget | R5 `DetectedIssue.mitigation.extension` maps as SourceIsBroaderThanTarget to R4 `DetectedIssue.mitigation.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| DetectedIssue.mitigation.id | DetectedIssue.mitigation.id | Equivalent | R5 `DetectedIssue.mitigation.id` maps as Equivalent to R4 `DetectedIssue.mitigation.id` |
| DetectedIssue.mitigation.modifierExtension | DetectedIssue.mitigation.modifierExtension | SourceIsBroaderThanTarget | R5 `DetectedIssue.mitigation.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `DetectedIssue.mitigation.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| DetectedIssue.mitigation.note | - | DoesNotExistInTarget | R5 `DetectedIssue.mitigation.note` does not appear in the target and has no mapping for `DetectedIssue`. |
| DetectedIssue.modifierExtension | DetectedIssue.modifierExtension | SourceIsBroaderThanTarget | R5 `DetectedIssue.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `DetectedIssue.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| DetectedIssue.reference | DetectedIssue.reference | Equivalent | R5 `DetectedIssue.reference` maps as Equivalent to R4 `DetectedIssue.reference` |
| DetectedIssue.severity | DetectedIssue.severity | Equivalent | R5 `DetectedIssue.severity` maps as Equivalent to R4 `DetectedIssue.severity` - severity has compatible required binding for code type: http://hl7.org/fhir/ValueSet/detectedissue-severity|5.0.0 and http://hl7.org/fhir/ValueSet/detectedissue-severity|4.0.1 (Equivalent) |
| DetectedIssue.status | DetectedIssue.status | RelatedTo | R5 `DetectedIssue.status` maps as RelatedTo to R4 `DetectedIssue.status` - (status failed to compare required binding of http://hl7.org/fhir/ValueSet/detectedissue-status|5.0.0 and http://hl7.org/fhir/ValueSet/observation-status|4.0.1); status has change due to type change: R5 `status` `code` maps as RelatedTo for R4 `status` |
| DetectedIssue.subject | DetectedIssue.patient | SourceIsBroaderThanTarget | R5 `DetectedIssue.subject` maps as SourceIsBroaderThanTarget to R4 `DetectedIssue.patient` - patient has change due to type change: R5 `subject` `Reference` maps as SourceIsBroaderThanTarget for R4 `patient` |
| DetectedIssue.text | DetectedIssue.text | Equivalent | R5 `DetectedIssue.text` maps as Equivalent to R4 `DetectedIssue.text` |

