Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1
Generated at Thursday, July 25, 2024 3:56:51 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Goal |  | Describes the intended objective(s) for a patient, group or organization care, for example, weight loss, restoring an activity of daily living, obtaining herd immunity via immunization, meeting a process improvement objective, etc. | 31 | 20 |
| Target | Goal |  | Describes the intended objective(s) for a patient, group or organization care, for example, weight loss, restoring an activity of daily living, obtaining herd immunity via immunization, meeting a process improvement objective, etc. | 31 | 20 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 3 |
Equivalent | 4 |
RelatedTo | 24 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Goal | Goal | Equivalent | R5 `Goal` maps as Equivalent to R4 `Goal` |
| Goal.achievementStatus | Goal.achievementStatus | Equivalent | R5 `Goal.achievementStatus` maps as Equivalent to R4 `Goal.achievementStatus` |
| Goal.addresses | Goal.addresses | SourceIsBroaderThanTarget | R5 `Goal.addresses` maps as SourceIsBroaderThanTarget to R4 `Goal.addresses` - addresses has change due to type change: R5 `addresses` `Reference` maps as SourceIsBroaderThanTarget for R4 `addresses` |
| Goal.category | Goal.category | Equivalent | R5 `Goal.category` maps as Equivalent to R4 `Goal.category` |
| Goal.contained | Goal.contained | Equivalent | R5 `Goal.contained` maps as Equivalent to R4 `Goal.contained` |
| Goal.continuous | - | DoesNotExistInTarget | R5 `Goal.continuous` does not appear in the target and has no mapping for `Goal`. |
| Goal.description | Goal.description | Equivalent | R5 `Goal.description` maps as Equivalent to R4 `Goal.description` |
| Goal.extension | Goal.extension | SourceIsBroaderThanTarget | R5 `Goal.extension` maps as SourceIsBroaderThanTarget to R4 `Goal.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Goal.id | Goal.id | Equivalent | R5 `Goal.id` maps as Equivalent to R4 `Goal.id` |
| Goal.identifier | Goal.identifier | Equivalent | R5 `Goal.identifier` maps as Equivalent to R4 `Goal.identifier` |
| Goal.implicitRules | Goal.implicitRules | Equivalent | R5 `Goal.implicitRules` maps as Equivalent to R4 `Goal.implicitRules` |
| Goal.language | Goal.language | RelatedTo | R5 `Goal.language` maps as RelatedTo to R4 `Goal.language` - language changed the binding strength from Required to Preferred |
| Goal.lifecycleStatus | Goal.lifecycleStatus | Equivalent | R5 `Goal.lifecycleStatus` maps as Equivalent to R4 `Goal.lifecycleStatus` - lifecycleStatus has compatible required binding for code type: http://hl7.org/fhir/ValueSet/goal-status|5.0.0 and http://hl7.org/fhir/ValueSet/goal-status|4.0.1 (Equivalent) |
| Goal.meta | Goal.meta | Equivalent | R5 `Goal.meta` maps as Equivalent to R4 `Goal.meta` |
| Goal.modifierExtension | Goal.modifierExtension | SourceIsBroaderThanTarget | R5 `Goal.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Goal.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Goal.note | Goal.note | SourceIsBroaderThanTarget | R5 `Goal.note` maps as SourceIsBroaderThanTarget to R4 `Goal.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4 `note` |
| Goal.outcome | - | DoesNotExistInTarget | R5 `Goal.outcome` does not appear in the target and has no mapping for `Goal`. |
| Goal.priority | Goal.priority | Equivalent | R5 `Goal.priority` maps as Equivalent to R4 `Goal.priority` |
| Goal.source | - | DoesNotExistInTarget | R5 `Goal.source` does not appear in the target and has no mapping for `Goal`. |
| Goal.start[x] | Goal.start[x] | Equivalent | R5 `Goal.start[x]` maps as Equivalent to R4 `Goal.start[x]` |
| Goal.statusDate | Goal.statusDate | Equivalent | R5 `Goal.statusDate` maps as Equivalent to R4 `Goal.statusDate` |
| Goal.statusReason | Goal.statusReason | Equivalent | R5 `Goal.statusReason` maps as Equivalent to R4 `Goal.statusReason` |
| Goal.subject | Goal.subject | Equivalent | R5 `Goal.subject` maps as Equivalent to R4 `Goal.subject` |
| Goal.target | Goal.target | Equivalent | R5 `Goal.target` maps as Equivalent to R4 `Goal.target` |
| Goal.target.detail[x] | Goal.target.detail[x] | SourceIsBroaderThanTarget | R5 `Goal.target.detail[x]` maps as SourceIsBroaderThanTarget to R4 `Goal.target.detail[x]` - detail[x] has change due to type change: R5 `detail[x]` `Ratio` maps as SourceIsBroaderThanTarget for R4 `detail[x]` |
| Goal.target.due[x] | Goal.target.due[x] | Equivalent | R5 `Goal.target.due[x]` maps as Equivalent to R4 `Goal.target.due[x]` |
| Goal.target.extension | Goal.target.extension | SourceIsBroaderThanTarget | R5 `Goal.target.extension` maps as SourceIsBroaderThanTarget to R4 `Goal.target.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Goal.target.id | Goal.target.id | Equivalent | R5 `Goal.target.id` maps as Equivalent to R4 `Goal.target.id` |
| Goal.target.measure | Goal.target.measure | Equivalent | R5 `Goal.target.measure` maps as Equivalent to R4 `Goal.target.measure` |
| Goal.target.modifierExtension | Goal.target.modifierExtension | SourceIsBroaderThanTarget | R5 `Goal.target.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Goal.target.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Goal.text | Goal.text | Equivalent | R5 `Goal.text` maps as Equivalent to R4 `Goal.text` |

