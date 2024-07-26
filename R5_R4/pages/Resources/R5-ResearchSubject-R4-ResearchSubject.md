Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1
Generated at Thursday, July 25, 2024 3:56:51 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | ResearchSubject |  | A ResearchSubject is a participant or object which is the recipient of investigative activities in a research study. | 27 | 16 |
| Target | ResearchSubject |  | A physical entity which is the primary unit of operational and/or administrative interest in a study. | 17 | 9 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 13 |
Equivalent | 4 |
RelatedTo | 10 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| ResearchSubject | ResearchSubject | Equivalent | R5 `ResearchSubject` maps as Equivalent to R4 `ResearchSubject` |
| ResearchSubject.actualComparisonGroup | - | DoesNotExistInTarget | R5 `ResearchSubject.actualComparisonGroup` does not appear in the target and has no mapping for `ResearchSubject`. |
| ResearchSubject.assignedComparisonGroup | - | DoesNotExistInTarget | R5 `ResearchSubject.assignedComparisonGroup` does not appear in the target and has no mapping for `ResearchSubject`. |
| ResearchSubject.consent | ResearchSubject.consent | RelatedTo | R5 `ResearchSubject.consent` maps as RelatedTo to R4 `ResearchSubject.consent` - consent changed from array to scalar (max cardinality from * to 1) |
| ResearchSubject.contained | ResearchSubject.contained | Equivalent | R5 `ResearchSubject.contained` maps as Equivalent to R4 `ResearchSubject.contained` |
| ResearchSubject.extension | ResearchSubject.extension | SourceIsBroaderThanTarget | R5 `ResearchSubject.extension` maps as SourceIsBroaderThanTarget to R4 `ResearchSubject.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ResearchSubject.id | ResearchSubject.id | Equivalent | R5 `ResearchSubject.id` maps as Equivalent to R4 `ResearchSubject.id` |
| ResearchSubject.identifier | ResearchSubject.identifier | Equivalent | R5 `ResearchSubject.identifier` maps as Equivalent to R4 `ResearchSubject.identifier` |
| ResearchSubject.implicitRules | ResearchSubject.implicitRules | Equivalent | R5 `ResearchSubject.implicitRules` maps as Equivalent to R4 `ResearchSubject.implicitRules` |
| ResearchSubject.language | ResearchSubject.language | RelatedTo | R5 `ResearchSubject.language` maps as RelatedTo to R4 `ResearchSubject.language` - language changed the binding strength from Required to Preferred |
| ResearchSubject.meta | ResearchSubject.meta | Equivalent | R5 `ResearchSubject.meta` maps as Equivalent to R4 `ResearchSubject.meta` |
| ResearchSubject.modifierExtension | ResearchSubject.modifierExtension | SourceIsBroaderThanTarget | R5 `ResearchSubject.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ResearchSubject.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ResearchSubject.period | ResearchSubject.period | Equivalent | R5 `ResearchSubject.period` maps as Equivalent to R4 `ResearchSubject.period` |
| ResearchSubject.progress | - | DoesNotExistInTarget | R5 `ResearchSubject.progress` does not appear in the target and has no mapping for `ResearchSubject`. |
| ResearchSubject.progress.endDate | - | DoesNotExistInTarget | R5 `ResearchSubject.progress.endDate` does not appear in the target and has no mapping for `ResearchSubject`. |
| ResearchSubject.progress.extension | - | DoesNotExistInTarget | R5 `ResearchSubject.progress.extension` does not appear in the target and has no mapping for `ResearchSubject`. |
| ResearchSubject.progress.id | - | DoesNotExistInTarget | R5 `ResearchSubject.progress.id` does not appear in the target and has no mapping for `ResearchSubject`. |
| ResearchSubject.progress.milestone | - | DoesNotExistInTarget | R5 `ResearchSubject.progress.milestone` does not appear in the target and has no mapping for `ResearchSubject`. |
| ResearchSubject.progress.modifierExtension | - | DoesNotExistInTarget | R5 `ResearchSubject.progress.modifierExtension` does not appear in the target and has no mapping for `ResearchSubject`. |
| ResearchSubject.progress.reason | - | DoesNotExistInTarget | R5 `ResearchSubject.progress.reason` does not appear in the target and has no mapping for `ResearchSubject`. |
| ResearchSubject.progress.startDate | - | DoesNotExistInTarget | R5 `ResearchSubject.progress.startDate` does not appear in the target and has no mapping for `ResearchSubject`. |
| ResearchSubject.progress.subjectState | - | DoesNotExistInTarget | R5 `ResearchSubject.progress.subjectState` does not appear in the target and has no mapping for `ResearchSubject`. |
| ResearchSubject.progress.type | - | DoesNotExistInTarget | R5 `ResearchSubject.progress.type` does not appear in the target and has no mapping for `ResearchSubject`. |
| ResearchSubject.status | ResearchSubject.status | Equivalent | R5 `ResearchSubject.status` maps as Equivalent to R4 `ResearchSubject.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|5.0.0 and http://hl7.org/fhir/ValueSet/research-subject-status|4.0.1 (Equivalent) |
| ResearchSubject.study | ResearchSubject.study | Equivalent | R5 `ResearchSubject.study` maps as Equivalent to R4 `ResearchSubject.study` |
| ResearchSubject.subject | - | DoesNotExistInTarget | R5 `ResearchSubject.subject` does not appear in the target and has no mapping for `ResearchSubject`. |
| ResearchSubject.text | ResearchSubject.text | Equivalent | R5 `ResearchSubject.text` maps as Equivalent to R4 `ResearchSubject.text` |

