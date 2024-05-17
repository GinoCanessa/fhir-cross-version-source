Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

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
| Goal | Goal | Equivalent | R4B `Goal` maps as Equivalent to R5 `Goal` |
| Goal.achievementStatus | Goal.achievementStatus | Equivalent | R4B `Goal.achievementStatus` maps as Equivalent to R5 `Goal.achievementStatus` |
| Goal.addresses | Goal.addresses | SourceIsNarrowerThanTarget | R4B `Goal.addresses` maps as SourceIsNarrowerThanTarget to R5 `Goal.addresses` - addresses has change due to type change: R4B `addresses` `Reference` maps as SourceIsNarrowerThanTarget for R5 `addresses` |
| Goal.category | Goal.category | Equivalent | R4B `Goal.category` maps as Equivalent to R5 `Goal.category` |
| Goal.contained | Goal.contained | Equivalent | R4B `Goal.contained` maps as Equivalent to R5 `Goal.contained` |
| Goal.description | Goal.description | Equivalent | R4B `Goal.description` maps as Equivalent to R5 `Goal.description` |
| Goal.expressedBy | - | DoesNotExistInTarget | R4B `Goal.expressedBy` does not appear in the target and has no mapping for `Goal`. |
| Goal.extension | Goal.extension | RelatedTo | R4B `Goal.extension` maps as RelatedTo to R5 `Goal.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Goal.id | Goal.id | Equivalent | R4B `Goal.id` maps as Equivalent to R5 `Goal.id` |
| Goal.identifier | Goal.identifier | Equivalent | R4B `Goal.identifier` maps as Equivalent to R5 `Goal.identifier` |
| Goal.implicitRules | Goal.implicitRules | Equivalent | R4B `Goal.implicitRules` maps as Equivalent to R5 `Goal.implicitRules` |
| Goal.language | Goal.language | RelatedTo | R4B `Goal.language` maps as RelatedTo to R5 `Goal.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Goal.lifecycleStatus | Goal.lifecycleStatus | Equivalent | R4B `Goal.lifecycleStatus` maps as Equivalent to R5 `Goal.lifecycleStatus` - lifecycleStatus has compatible required binding for code type: http://hl7.org/fhir/ValueSet/goal-status|4.3.0 and http://hl7.org/fhir/ValueSet/goal-status|5.0.0 (Equivalent) |
| Goal.meta | Goal.meta | Equivalent | R4B `Goal.meta` maps as Equivalent to R5 `Goal.meta` |
| Goal.modifierExtension | Goal.modifierExtension | RelatedTo | R4B `Goal.modifierExtension` maps as RelatedTo to R5 `Goal.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Goal.note | Goal.note | SourceIsNarrowerThanTarget | R4B `Goal.note` maps as SourceIsNarrowerThanTarget to R5 `Goal.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| Goal.outcomeCode | - | DoesNotExistInTarget | R4B `Goal.outcomeCode` does not appear in the target and has no mapping for `Goal`. |
| Goal.outcomeReference | - | DoesNotExistInTarget | R4B `Goal.outcomeReference` does not appear in the target and has no mapping for `Goal`. |
| Goal.priority | Goal.priority | Equivalent | R4B `Goal.priority` maps as Equivalent to R5 `Goal.priority` |
| Goal.start[x] | Goal.start[x] | Equivalent | R4B `Goal.start[x]` maps as Equivalent to R5 `Goal.start[x]` |
| Goal.statusDate | Goal.statusDate | Equivalent | R4B `Goal.statusDate` maps as Equivalent to R5 `Goal.statusDate` |
| Goal.statusReason | Goal.statusReason | Equivalent | R4B `Goal.statusReason` maps as Equivalent to R5 `Goal.statusReason` |
| Goal.subject | Goal.subject | Equivalent | R4B `Goal.subject` maps as Equivalent to R5 `Goal.subject` |
| Goal.target | Goal.target | Equivalent | R4B `Goal.target` maps as Equivalent to R5 `Goal.target` |
| Goal.target.detail[x] | Goal.target.detail[x] | SourceIsNarrowerThanTarget | R4B `Goal.target.detail[x]` maps as SourceIsNarrowerThanTarget to R5 `Goal.target.detail[x]` - detail[x] has change due to type change: R4B `detail[x]` `Ratio` maps as SourceIsNarrowerThanTarget for R5 `detail[x]` |
| Goal.target.due[x] | Goal.target.due[x] | Equivalent | R4B `Goal.target.due[x]` maps as Equivalent to R5 `Goal.target.due[x]` |
| Goal.target.extension | Goal.target.extension | RelatedTo | R4B `Goal.target.extension` maps as RelatedTo to R5 `Goal.target.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Goal.target.id | Goal.target.id | Equivalent | R4B `Goal.target.id` maps as Equivalent to R5 `Goal.target.id` |
| Goal.target.measure | Goal.target.measure | Equivalent | R4B `Goal.target.measure` maps as Equivalent to R5 `Goal.target.measure` |
| Goal.target.modifierExtension | Goal.target.modifierExtension | RelatedTo | R4B `Goal.target.modifierExtension` maps as RelatedTo to R5 `Goal.target.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Goal.text | Goal.text | Equivalent | R4B `Goal.text` maps as Equivalent to R5 `Goal.text` |

