Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | DetectedIssue |  | Indicates an actual or potential clinical issue with or between one or more active or proposed clinical actions for a patient; e.g. Drug-drug interaction, Ineffective treatment frequency, Procedure-condition conflict, gaps in care, etc. | 35 | 21 |
| Target | DetectedIssue |  | Indicates an actual or potential clinical issue with or between one or more active or proposed clinical actions for a patient; e.g. Drug-drug interaction, Ineffective treatment frequency, Procedure-condition conflict, etc. | 32 | 18 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 4 |
Equivalent | 4 |
RelatedTo | 27 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| DetectedIssue | DetectedIssue | Equivalent | R5 `DetectedIssue` maps as Equivalent to R4B `DetectedIssue` |
| DetectedIssue.author | DetectedIssue.author | SourceIsBroaderThanTarget | R5 `DetectedIssue.author` maps as SourceIsBroaderThanTarget to R4B `DetectedIssue.author` - author has change due to type change: R5 `author` `Reference` maps as SourceIsBroaderThanTarget for R4B `author` |
| DetectedIssue.category | - | DoesNotExistInTarget | R5 `DetectedIssue.category` does not appear in the target and has no mapping for `DetectedIssue`. |
| DetectedIssue.code | DetectedIssue.code | Equivalent | R5 `DetectedIssue.code` maps as Equivalent to R4B `DetectedIssue.code` |
| DetectedIssue.contained | DetectedIssue.contained | Equivalent | R5 `DetectedIssue.contained` maps as Equivalent to R4B `DetectedIssue.contained` |
| DetectedIssue.detail | DetectedIssue.detail | SourceIsBroaderThanTarget | R5 `DetectedIssue.detail` maps as SourceIsBroaderThanTarget to R4B `DetectedIssue.detail` - detail has change due to type change: R5 detail markdown has no equivalent or mapped type in R4B detail |
| DetectedIssue.encounter | - | DoesNotExistInTarget | R5 `DetectedIssue.encounter` does not appear in the target and has no mapping for `DetectedIssue`. |
| DetectedIssue.evidence | DetectedIssue.evidence | Equivalent | R5 `DetectedIssue.evidence` maps as Equivalent to R4B `DetectedIssue.evidence` |
| DetectedIssue.evidence.code | DetectedIssue.evidence.code | Equivalent | R5 `DetectedIssue.evidence.code` maps as Equivalent to R4B `DetectedIssue.evidence.code` |
| DetectedIssue.evidence.detail | DetectedIssue.evidence.detail | Equivalent | R5 `DetectedIssue.evidence.detail` maps as Equivalent to R4B `DetectedIssue.evidence.detail` |
| DetectedIssue.evidence.extension | DetectedIssue.evidence.extension | SourceIsBroaderThanTarget | R5 `DetectedIssue.evidence.extension` maps as SourceIsBroaderThanTarget to R4B `DetectedIssue.evidence.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| DetectedIssue.evidence.id | DetectedIssue.evidence.id | Equivalent | R5 `DetectedIssue.evidence.id` maps as Equivalent to R4B `DetectedIssue.evidence.id` |
| DetectedIssue.evidence.modifierExtension | DetectedIssue.evidence.modifierExtension | SourceIsBroaderThanTarget | R5 `DetectedIssue.evidence.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `DetectedIssue.evidence.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| DetectedIssue.extension | DetectedIssue.extension | SourceIsBroaderThanTarget | R5 `DetectedIssue.extension` maps as SourceIsBroaderThanTarget to R4B `DetectedIssue.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| DetectedIssue.id | DetectedIssue.id | Equivalent | R5 `DetectedIssue.id` maps as Equivalent to R4B `DetectedIssue.id` |
| DetectedIssue.identified[x] | DetectedIssue.identified[x] | Equivalent | R5 `DetectedIssue.identified[x]` maps as Equivalent to R4B `DetectedIssue.identified[x]` |
| DetectedIssue.identifier | DetectedIssue.identifier | Equivalent | R5 `DetectedIssue.identifier` maps as Equivalent to R4B `DetectedIssue.identifier` |
| DetectedIssue.implicated | DetectedIssue.implicated | Equivalent | R5 `DetectedIssue.implicated` maps as Equivalent to R4B `DetectedIssue.implicated` |
| DetectedIssue.implicitRules | DetectedIssue.implicitRules | Equivalent | R5 `DetectedIssue.implicitRules` maps as Equivalent to R4B `DetectedIssue.implicitRules` |
| DetectedIssue.language | DetectedIssue.language | RelatedTo | R5 `DetectedIssue.language` maps as RelatedTo to R4B `DetectedIssue.language` - language changed the binding strength from Required to Preferred |
| DetectedIssue.meta | DetectedIssue.meta | Equivalent | R5 `DetectedIssue.meta` maps as Equivalent to R4B `DetectedIssue.meta` |
| DetectedIssue.mitigation | DetectedIssue.mitigation | Equivalent | R5 `DetectedIssue.mitigation` maps as Equivalent to R4B `DetectedIssue.mitigation` |
| DetectedIssue.mitigation.action | DetectedIssue.mitigation.action | Equivalent | R5 `DetectedIssue.mitigation.action` maps as Equivalent to R4B `DetectedIssue.mitigation.action` |
| DetectedIssue.mitigation.author | DetectedIssue.mitigation.author | Equivalent | R5 `DetectedIssue.mitigation.author` maps as Equivalent to R4B `DetectedIssue.mitigation.author` |
| DetectedIssue.mitigation.date | DetectedIssue.mitigation.date | Equivalent | R5 `DetectedIssue.mitigation.date` maps as Equivalent to R4B `DetectedIssue.mitigation.date` |
| DetectedIssue.mitigation.extension | DetectedIssue.mitigation.extension | SourceIsBroaderThanTarget | R5 `DetectedIssue.mitigation.extension` maps as SourceIsBroaderThanTarget to R4B `DetectedIssue.mitigation.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| DetectedIssue.mitigation.id | DetectedIssue.mitigation.id | Equivalent | R5 `DetectedIssue.mitigation.id` maps as Equivalent to R4B `DetectedIssue.mitigation.id` |
| DetectedIssue.mitigation.modifierExtension | DetectedIssue.mitigation.modifierExtension | SourceIsBroaderThanTarget | R5 `DetectedIssue.mitigation.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `DetectedIssue.mitigation.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| DetectedIssue.mitigation.note | - | DoesNotExistInTarget | R5 `DetectedIssue.mitigation.note` does not appear in the target and has no mapping for `DetectedIssue`. |
| DetectedIssue.modifierExtension | DetectedIssue.modifierExtension | SourceIsBroaderThanTarget | R5 `DetectedIssue.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `DetectedIssue.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| DetectedIssue.reference | DetectedIssue.reference | Equivalent | R5 `DetectedIssue.reference` maps as Equivalent to R4B `DetectedIssue.reference` |
| DetectedIssue.severity | DetectedIssue.severity | Equivalent | R5 `DetectedIssue.severity` maps as Equivalent to R4B `DetectedIssue.severity` - severity has compatible required binding for code type: http://hl7.org/fhir/ValueSet/detectedissue-severity|5.0.0 and http://hl7.org/fhir/ValueSet/detectedissue-severity|4.3.0 (Equivalent) |
| DetectedIssue.status | DetectedIssue.status | Equivalent | R5 `DetectedIssue.status` maps as Equivalent to R4B `DetectedIssue.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/detectedissue-status|5.0.0 and http://hl7.org/fhir/ValueSet/observation-status|4.3.0 (Equivalent) |
| DetectedIssue.subject | - | DoesNotExistInTarget | R5 `DetectedIssue.subject` does not appear in the target and has no mapping for `DetectedIssue`. |
| DetectedIssue.text | DetectedIssue.text | Equivalent | R5 `DetectedIssue.text` maps as Equivalent to R4B `DetectedIssue.text` |

