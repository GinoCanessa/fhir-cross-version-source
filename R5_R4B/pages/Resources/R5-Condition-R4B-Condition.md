Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Condition |  | A clinical condition, problem, diagnosis, or other event, situation, issue, or clinical concept that has risen to a level of concern. | 36 | 22 |
| Target | Condition |  | A clinical condition, problem, diagnosis, or other event, situation, issue, or clinical concept that has risen to a level of concern. | 37 | 23 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 6 |
Equivalent | 4 |
RelatedTo | 26 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Condition | Condition | Equivalent | R5 `Condition` maps as Equivalent to R4B `Condition` |
| Condition.abatement[x] | Condition.abatement[x] | Equivalent | R5 `Condition.abatement[x]` maps as Equivalent to R4B `Condition.abatement[x]` |
| Condition.bodySite | Condition.bodySite | Equivalent | R5 `Condition.bodySite` maps as Equivalent to R4B `Condition.bodySite` |
| Condition.category | Condition.category | RelatedTo | R5 `Condition.category` maps as RelatedTo to R4B `Condition.category` - category changed the binding strength from Preferred to Extensible |
| Condition.clinicalStatus | Condition.clinicalStatus | Equivalent | R5 `Condition.clinicalStatus` maps as Equivalent to R4B `Condition.clinicalStatus` - clinicalStatus has compatible required binding for non-code type: http://hl7.org/fhir/ValueSet/condition-clinical|5.0.0 and http://hl7.org/fhir/ValueSet/condition-clinical|4.3.0 (Equivalent) |
| Condition.code | Condition.code | Equivalent | R5 `Condition.code` maps as Equivalent to R4B `Condition.code` |
| Condition.contained | Condition.contained | Equivalent | R5 `Condition.contained` maps as Equivalent to R4B `Condition.contained` |
| Condition.encounter | Condition.encounter | Equivalent | R5 `Condition.encounter` maps as Equivalent to R4B `Condition.encounter` |
| Condition.evidence | Condition.evidence | RelatedTo | R5 `Condition.evidence` maps as RelatedTo to R4B `Condition.evidence` - evidence removed a binding requirement - Example http://hl7.org/fhir/ValueSet/clinical-findings; evidence has change due to type change: R5 evidence CodeableReference has no equivalent or mapped type in R4B evidence |
| Condition.extension | Condition.extension | SourceIsBroaderThanTarget | R5 `Condition.extension` maps as SourceIsBroaderThanTarget to R4B `Condition.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Condition.id | Condition.id | Equivalent | R5 `Condition.id` maps as Equivalent to R4B `Condition.id` |
| Condition.identifier | Condition.identifier | Equivalent | R5 `Condition.identifier` maps as Equivalent to R4B `Condition.identifier` |
| Condition.implicitRules | Condition.implicitRules | Equivalent | R5 `Condition.implicitRules` maps as Equivalent to R4B `Condition.implicitRules` |
| Condition.language | Condition.language | RelatedTo | R5 `Condition.language` maps as RelatedTo to R4B `Condition.language` - language changed the binding strength from Required to Preferred |
| Condition.meta | Condition.meta | Equivalent | R5 `Condition.meta` maps as Equivalent to R4B `Condition.meta` |
| Condition.modifierExtension | Condition.modifierExtension | SourceIsBroaderThanTarget | R5 `Condition.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Condition.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Condition.note | Condition.note | SourceIsBroaderThanTarget | R5 `Condition.note` maps as SourceIsBroaderThanTarget to R4B `Condition.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4B `note` |
| Condition.onset[x] | Condition.onset[x] | Equivalent | R5 `Condition.onset[x]` maps as Equivalent to R4B `Condition.onset[x]` |
| Condition.participant | - | DoesNotExistInTarget | R5 `Condition.participant` does not appear in the target and has no mapping for `Condition`. |
| Condition.participant.actor | - | DoesNotExistInTarget | R5 `Condition.participant.actor` does not appear in the target and has no mapping for `Condition`. |
| Condition.participant.extension | - | DoesNotExistInTarget | R5 `Condition.participant.extension` does not appear in the target and has no mapping for `Condition`. |
| Condition.participant.function | - | DoesNotExistInTarget | R5 `Condition.participant.function` does not appear in the target and has no mapping for `Condition`. |
| Condition.participant.id | - | DoesNotExistInTarget | R5 `Condition.participant.id` does not appear in the target and has no mapping for `Condition`. |
| Condition.participant.modifierExtension | - | DoesNotExistInTarget | R5 `Condition.participant.modifierExtension` does not appear in the target and has no mapping for `Condition`. |
| Condition.recordedDate | Condition.recordedDate | Equivalent | R5 `Condition.recordedDate` maps as Equivalent to R4B `Condition.recordedDate` |
| Condition.severity | Condition.severity | Equivalent | R5 `Condition.severity` maps as Equivalent to R4B `Condition.severity` |
| Condition.stage | Condition.stage | Equivalent | R5 `Condition.stage` maps as Equivalent to R4B `Condition.stage` |
| Condition.stage.assessment | Condition.stage.assessment | Equivalent | R5 `Condition.stage.assessment` maps as Equivalent to R4B `Condition.stage.assessment` |
| Condition.stage.extension | Condition.stage.extension | SourceIsBroaderThanTarget | R5 `Condition.stage.extension` maps as SourceIsBroaderThanTarget to R4B `Condition.stage.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Condition.stage.id | Condition.stage.id | Equivalent | R5 `Condition.stage.id` maps as Equivalent to R4B `Condition.stage.id` |
| Condition.stage.modifierExtension | Condition.stage.modifierExtension | SourceIsBroaderThanTarget | R5 `Condition.stage.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Condition.stage.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Condition.stage.summary | Condition.stage.summary | Equivalent | R5 `Condition.stage.summary` maps as Equivalent to R4B `Condition.stage.summary` |
| Condition.stage.type | Condition.stage.type | Equivalent | R5 `Condition.stage.type` maps as Equivalent to R4B `Condition.stage.type` |
| Condition.subject | Condition.subject | Equivalent | R5 `Condition.subject` maps as Equivalent to R4B `Condition.subject` |
| Condition.text | Condition.text | Equivalent | R5 `Condition.text` maps as Equivalent to R4B `Condition.text` |
| Condition.verificationStatus | Condition.verificationStatus | Equivalent | R5 `Condition.verificationStatus` maps as Equivalent to R4B `Condition.verificationStatus` - verificationStatus has compatible required binding for non-code type: http://hl7.org/fhir/ValueSet/condition-ver-status|5.0.0 and http://hl7.org/fhir/ValueSet/condition-ver-status|4.3.0 (Equivalent) |

