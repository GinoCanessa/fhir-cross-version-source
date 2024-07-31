Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | FamilyMemberHistory |  | Significant health conditions for a person related to the patient relevant in the context of care for the patient. | 49 | 32 |
| Target | FamilyMemberHistory |  | Significant health conditions for a person related to the patient relevant in the context of care for the patient. | 35 | 24 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 15 |
Equivalent | 26 |
RelatedTo | 1 |
SourceIsBroaderThanTarget | 6 |
SourceIsNarrowerThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| FamilyMemberHistory | FamilyMemberHistory | Equivalent | R5 `FamilyMemberHistory` maps as Equivalent to R4 `FamilyMemberHistory` |
| FamilyMemberHistory.age[x] | FamilyMemberHistory.age[x] | Equivalent | R5 `FamilyMemberHistory.age[x]` maps as Equivalent to R4 `FamilyMemberHistory.age[x]` |
| FamilyMemberHistory.born[x] | FamilyMemberHistory.born[x] | Equivalent | R5 `FamilyMemberHistory.born[x]` maps as Equivalent to R4 `FamilyMemberHistory.born[x]` |
| FamilyMemberHistory.condition | FamilyMemberHistory.condition | Equivalent | R5 `FamilyMemberHistory.condition` maps as Equivalent to R4 `FamilyMemberHistory.condition` |
| FamilyMemberHistory.condition.code | FamilyMemberHistory.condition.code | Equivalent | R5 `FamilyMemberHistory.condition.code` maps as Equivalent to R4 `FamilyMemberHistory.condition.code` |
| FamilyMemberHistory.condition.contributedToDeath | FamilyMemberHistory.condition.contributedToDeath | Equivalent | R5 `FamilyMemberHistory.condition.contributedToDeath` maps as Equivalent to R4 `FamilyMemberHistory.condition.contributedToDeath` |
| FamilyMemberHistory.condition.extension | FamilyMemberHistory.condition.extension | SourceIsBroaderThanTarget | R5 `FamilyMemberHistory.condition.extension` maps as SourceIsBroaderThanTarget to R4 `FamilyMemberHistory.condition.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| FamilyMemberHistory.condition.id | FamilyMemberHistory.condition.id | Equivalent | R5 `FamilyMemberHistory.condition.id` maps as Equivalent to R4 `FamilyMemberHistory.condition.id` |
| FamilyMemberHistory.condition.modifierExtension | FamilyMemberHistory.condition.modifierExtension | SourceIsBroaderThanTarget | R5 `FamilyMemberHistory.condition.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `FamilyMemberHistory.condition.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| FamilyMemberHistory.condition.note | FamilyMemberHistory.condition.note | SourceIsBroaderThanTarget | R5 `FamilyMemberHistory.condition.note` maps as SourceIsBroaderThanTarget to R4 `FamilyMemberHistory.condition.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4 `note` |
| FamilyMemberHistory.condition.onset[x] | FamilyMemberHistory.condition.onset[x] | Equivalent | R5 `FamilyMemberHistory.condition.onset[x]` maps as Equivalent to R4 `FamilyMemberHistory.condition.onset[x]` |
| FamilyMemberHistory.condition.outcome | FamilyMemberHistory.condition.outcome | Equivalent | R5 `FamilyMemberHistory.condition.outcome` maps as Equivalent to R4 `FamilyMemberHistory.condition.outcome` |
| FamilyMemberHistory.contained | FamilyMemberHistory.contained | Equivalent | R5 `FamilyMemberHistory.contained` maps as Equivalent to R4 `FamilyMemberHistory.contained` |
| FamilyMemberHistory.dataAbsentReason | FamilyMemberHistory.dataAbsentReason | Equivalent | R5 `FamilyMemberHistory.dataAbsentReason` maps as Equivalent to R4 `FamilyMemberHistory.dataAbsentReason` |
| FamilyMemberHistory.date | FamilyMemberHistory.date | Equivalent | R5 `FamilyMemberHistory.date` maps as Equivalent to R4 `FamilyMemberHistory.date` |
| FamilyMemberHistory.deceased[x] | FamilyMemberHistory.deceased[x] | Equivalent | R5 `FamilyMemberHistory.deceased[x]` maps as Equivalent to R4 `FamilyMemberHistory.deceased[x]` |
| FamilyMemberHistory.estimatedAge | FamilyMemberHistory.estimatedAge | Equivalent | R5 `FamilyMemberHistory.estimatedAge` maps as Equivalent to R4 `FamilyMemberHistory.estimatedAge` |
| FamilyMemberHistory.extension | FamilyMemberHistory.extension | SourceIsBroaderThanTarget | R5 `FamilyMemberHistory.extension` maps as SourceIsBroaderThanTarget to R4 `FamilyMemberHistory.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| FamilyMemberHistory.id | FamilyMemberHistory.id | Equivalent | R5 `FamilyMemberHistory.id` maps as Equivalent to R4 `FamilyMemberHistory.id` |
| FamilyMemberHistory.identifier | FamilyMemberHistory.identifier | Equivalent | R5 `FamilyMemberHistory.identifier` maps as Equivalent to R4 `FamilyMemberHistory.identifier` |
| FamilyMemberHistory.implicitRules | FamilyMemberHistory.implicitRules | Equivalent | R5 `FamilyMemberHistory.implicitRules` maps as Equivalent to R4 `FamilyMemberHistory.implicitRules` |
| FamilyMemberHistory.instantiatesCanonical | FamilyMemberHistory.instantiatesCanonical | Equivalent | R5 `FamilyMemberHistory.instantiatesCanonical` maps as Equivalent to R4 `FamilyMemberHistory.instantiatesCanonical` |
| FamilyMemberHistory.instantiatesUri | FamilyMemberHistory.instantiatesUri | Equivalent | R5 `FamilyMemberHistory.instantiatesUri` maps as Equivalent to R4 `FamilyMemberHistory.instantiatesUri` |
| FamilyMemberHistory.language | FamilyMemberHistory.language | SourceIsNarrowerThanTarget | R5 `FamilyMemberHistory.language` maps as SourceIsNarrowerThanTarget to R4 `FamilyMemberHistory.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| FamilyMemberHistory.meta | FamilyMemberHistory.meta | Equivalent | R5 `FamilyMemberHistory.meta` maps as Equivalent to R4 `FamilyMemberHistory.meta` |
| FamilyMemberHistory.modifierExtension | FamilyMemberHistory.modifierExtension | SourceIsBroaderThanTarget | R5 `FamilyMemberHistory.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `FamilyMemberHistory.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| FamilyMemberHistory.name | FamilyMemberHistory.name | Equivalent | R5 `FamilyMemberHistory.name` maps as Equivalent to R4 `FamilyMemberHistory.name` |
| FamilyMemberHistory.note | FamilyMemberHistory.note | SourceIsBroaderThanTarget | R5 `FamilyMemberHistory.note` maps as SourceIsBroaderThanTarget to R4 `FamilyMemberHistory.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4 `note` |
| FamilyMemberHistory.participant | - | DoesNotExistInTarget | R5 `FamilyMemberHistory.participant` does not appear in the target and has no mapping for `FamilyMemberHistory`. |
| FamilyMemberHistory.participant.actor | - | DoesNotExistInTarget | R5 `FamilyMemberHistory.participant.actor` does not appear in the target and has no mapping for `FamilyMemberHistory`. |
| FamilyMemberHistory.participant.extension | - | DoesNotExistInTarget | R5 `FamilyMemberHistory.participant.extension` does not appear in the target and has no mapping for `FamilyMemberHistory`. |
| FamilyMemberHistory.participant.function | - | DoesNotExistInTarget | R5 `FamilyMemberHistory.participant.function` does not appear in the target and has no mapping for `FamilyMemberHistory`. |
| FamilyMemberHistory.participant.id | - | DoesNotExistInTarget | R5 `FamilyMemberHistory.participant.id` does not appear in the target and has no mapping for `FamilyMemberHistory`. |
| FamilyMemberHistory.participant.modifierExtension | - | DoesNotExistInTarget | R5 `FamilyMemberHistory.participant.modifierExtension` does not appear in the target and has no mapping for `FamilyMemberHistory`. |
| FamilyMemberHistory.patient | FamilyMemberHistory.patient | Equivalent | R5 `FamilyMemberHistory.patient` maps as Equivalent to R4 `FamilyMemberHistory.patient` |
| FamilyMemberHistory.procedure | - | DoesNotExistInTarget | R5 `FamilyMemberHistory.procedure` does not appear in the target and has no mapping for `FamilyMemberHistory`. |
| FamilyMemberHistory.procedure.code | - | DoesNotExistInTarget | R5 `FamilyMemberHistory.procedure.code` does not appear in the target and has no mapping for `FamilyMemberHistory`. |
| FamilyMemberHistory.procedure.contributedToDeath | - | DoesNotExistInTarget | R5 `FamilyMemberHistory.procedure.contributedToDeath` does not appear in the target and has no mapping for `FamilyMemberHistory`. |
| FamilyMemberHistory.procedure.extension | - | DoesNotExistInTarget | R5 `FamilyMemberHistory.procedure.extension` does not appear in the target and has no mapping for `FamilyMemberHistory`. |
| FamilyMemberHistory.procedure.id | - | DoesNotExistInTarget | R5 `FamilyMemberHistory.procedure.id` does not appear in the target and has no mapping for `FamilyMemberHistory`. |
| FamilyMemberHistory.procedure.modifierExtension | - | DoesNotExistInTarget | R5 `FamilyMemberHistory.procedure.modifierExtension` does not appear in the target and has no mapping for `FamilyMemberHistory`. |
| FamilyMemberHistory.procedure.note | - | DoesNotExistInTarget | R5 `FamilyMemberHistory.procedure.note` does not appear in the target and has no mapping for `FamilyMemberHistory`. |
| FamilyMemberHistory.procedure.outcome | - | DoesNotExistInTarget | R5 `FamilyMemberHistory.procedure.outcome` does not appear in the target and has no mapping for `FamilyMemberHistory`. |
| FamilyMemberHistory.procedure.performed[x] | - | DoesNotExistInTarget | R5 `FamilyMemberHistory.procedure.performed[x]` does not appear in the target and has no mapping for `FamilyMemberHistory`. |
| FamilyMemberHistory.reason | FamilyMemberHistory.reasonCode | SourceIsBroaderThanTarget | R5 `FamilyMemberHistory.reason` maps as SourceIsBroaderThanTarget to R4 `FamilyMemberHistory.reasonCode` - reasonCode has change due to type change: R5 reason CodeableReference has no equivalent or mapped type in R4 reasonCode |
| FamilyMemberHistory.reason | FamilyMemberHistory.reasonReference | RelatedTo | R5 `FamilyMemberHistory.reason` maps as RelatedTo to R4 `FamilyMemberHistory.reasonReference` - reasonReference removed a binding requirement - Example http://hl7.org/fhir/ValueSet/clinical-findings; reasonReference has change due to type change: R5 reason CodeableReference has no equivalent or mapped type in R4 reasonReference |
| FamilyMemberHistory.relationship | FamilyMemberHistory.relationship | Equivalent | R5 `FamilyMemberHistory.relationship` maps as Equivalent to R4 `FamilyMemberHistory.relationship` |
| FamilyMemberHistory.sex | FamilyMemberHistory.sex | Equivalent | R5 `FamilyMemberHistory.sex` maps as Equivalent to R4 `FamilyMemberHistory.sex` |
| FamilyMemberHistory.status | FamilyMemberHistory.status | Equivalent | R5 `FamilyMemberHistory.status` maps as Equivalent to R4 `FamilyMemberHistory.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/history-status|5.0.0 and http://hl7.org/fhir/ValueSet/history-status|4.0.1 (Equivalent) |
| FamilyMemberHistory.text | FamilyMemberHistory.text | Equivalent | R5 `FamilyMemberHistory.text` maps as Equivalent to R4 `FamilyMemberHistory.text` |

