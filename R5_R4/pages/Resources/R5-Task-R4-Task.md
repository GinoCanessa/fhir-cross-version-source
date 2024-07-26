Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1
Generated at Thursday, July 25, 2024 3:56:51 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Task |  | A task to be performed. | 63 | 43 |
| Target | Task |  | A task to be performed. | 56 | 39 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 10 |
Equivalent | 4 |
RelatedTo | 49 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Task | Task | Equivalent | R5 `Task` maps as Equivalent to R4 `Task` |
| Task.authoredOn | Task.authoredOn | Equivalent | R5 `Task.authoredOn` maps as Equivalent to R4 `Task.authoredOn` |
| Task.basedOn | Task.basedOn | Equivalent | R5 `Task.basedOn` maps as Equivalent to R4 `Task.basedOn` |
| Task.businessStatus | Task.businessStatus | Equivalent | R5 `Task.businessStatus` maps as Equivalent to R4 `Task.businessStatus` |
| Task.code | Task.code | Equivalent | R5 `Task.code` maps as Equivalent to R4 `Task.code` |
| Task.contained | Task.contained | Equivalent | R5 `Task.contained` maps as Equivalent to R4 `Task.contained` |
| Task.description | Task.description | Equivalent | R5 `Task.description` maps as Equivalent to R4 `Task.description` |
| Task.doNotPerform | - | DoesNotExistInTarget | R5 `Task.doNotPerform` does not appear in the target and has no mapping for `Task`. |
| Task.encounter | Task.encounter | Equivalent | R5 `Task.encounter` maps as Equivalent to R4 `Task.encounter` |
| Task.executionPeriod | Task.executionPeriod | Equivalent | R5 `Task.executionPeriod` maps as Equivalent to R4 `Task.executionPeriod` |
| Task.extension | Task.extension | SourceIsBroaderThanTarget | R5 `Task.extension` maps as SourceIsBroaderThanTarget to R4 `Task.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Task.focus | Task.focus | Equivalent | R5 `Task.focus` maps as Equivalent to R4 `Task.focus` |
| Task.for | Task.for | Equivalent | R5 `Task.for` maps as Equivalent to R4 `Task.for` |
| Task.groupIdentifier | Task.groupIdentifier | Equivalent | R5 `Task.groupIdentifier` maps as Equivalent to R4 `Task.groupIdentifier` |
| Task.id | Task.id | Equivalent | R5 `Task.id` maps as Equivalent to R4 `Task.id` |
| Task.identifier | Task.identifier | Equivalent | R5 `Task.identifier` maps as Equivalent to R4 `Task.identifier` |
| Task.implicitRules | Task.implicitRules | Equivalent | R5 `Task.implicitRules` maps as Equivalent to R4 `Task.implicitRules` |
| Task.input | Task.input | Equivalent | R5 `Task.input` maps as Equivalent to R4 `Task.input` |
| Task.input.extension | Task.input.extension | SourceIsBroaderThanTarget | R5 `Task.input.extension` maps as SourceIsBroaderThanTarget to R4 `Task.input.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Task.input.id | Task.input.id | Equivalent | R5 `Task.input.id` maps as Equivalent to R4 `Task.input.id` |
| Task.input.modifierExtension | Task.input.modifierExtension | SourceIsBroaderThanTarget | R5 `Task.input.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Task.input.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Task.input.type | Task.input.type | Equivalent | R5 `Task.input.type` maps as Equivalent to R4 `Task.input.type` |
| Task.input.value[x] | Task.input.value[x] | RelatedTo | R5 `Task.input.value[x]` maps as RelatedTo to R4 `Task.input.value[x]` - value[x] has change due to type change: R5 `value[x]` `integer64` maps as SourceIsBroaderThanTarget for R4 `value[x]`; value[x] has change due to type change: R5 `value[x]` `Annotation` maps as SourceIsBroaderThanTarget for R4 `value[x]`; value[x] has change due to type change: R5 `value[x]` `Attachment` maps as RelatedTo for R4 `value[x]`; value[x] has change due to type change: R5 value[x] CodeableReference has no equivalent or mapped type in R4 value[x]; value[x] has change due to type change: R5 `value[x]` `Ratio` maps as SourceIsBroaderThanTarget for R4 `value[x]`; value[x] has change due to type change: R5 value[x] RatioRange has no equivalent or mapped type in R4 value[x]; value[x] has change due to type change: R5 `value[x]` `Signature` maps as RelatedTo for R4 `value[x]`; value[x] has change due to type change: R5 `value[x]` `DataRequirement` maps as RelatedTo for R4 `value[x]`; value[x] has change due to type change: R5 `value[x]` `Expression` maps as RelatedTo for R4 `value[x]`; value[x] has change due to type change: R5 `value[x]` `ParameterDefinition` maps as RelatedTo for R4 `value[x]`; value[x] has change due to type change: R5 value[x] Availability has no equivalent or mapped type in R4 value[x]; value[x] has change due to type change: R5 value[x] ExtendedContactDetail has no equivalent or mapped type in R4 value[x]; value[x] has change due to type change: R5 `value[x]` `Dosage` maps as RelatedTo for R4 `value[x]` |
| Task.instantiatesCanonical | Task.instantiatesCanonical | Equivalent | R5 `Task.instantiatesCanonical` maps as Equivalent to R4 `Task.instantiatesCanonical` |
| Task.instantiatesUri | Task.instantiatesUri | Equivalent | R5 `Task.instantiatesUri` maps as Equivalent to R4 `Task.instantiatesUri` |
| Task.insurance | Task.insurance | Equivalent | R5 `Task.insurance` maps as Equivalent to R4 `Task.insurance` |
| Task.intent | Task.intent | Equivalent | R5 `Task.intent` maps as Equivalent to R4 `Task.intent` - intent has compatible required binding for code type: http://hl7.org/fhir/ValueSet/task-intent|5.0.0 and http://hl7.org/fhir/ValueSet/task-intent|4.0.1 (Equivalent) |
| Task.language | Task.language | RelatedTo | R5 `Task.language` maps as RelatedTo to R4 `Task.language` - language changed the binding strength from Required to Preferred |
| Task.lastModified | Task.lastModified | Equivalent | R5 `Task.lastModified` maps as Equivalent to R4 `Task.lastModified` |
| Task.location | Task.location | Equivalent | R5 `Task.location` maps as Equivalent to R4 `Task.location` |
| Task.meta | Task.meta | Equivalent | R5 `Task.meta` maps as Equivalent to R4 `Task.meta` |
| Task.modifierExtension | Task.modifierExtension | SourceIsBroaderThanTarget | R5 `Task.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Task.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Task.note | Task.note | SourceIsBroaderThanTarget | R5 `Task.note` maps as SourceIsBroaderThanTarget to R4 `Task.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4 `note` |
| Task.output | Task.output | Equivalent | R5 `Task.output` maps as Equivalent to R4 `Task.output` |
| Task.output.extension | Task.output.extension | SourceIsBroaderThanTarget | R5 `Task.output.extension` maps as SourceIsBroaderThanTarget to R4 `Task.output.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Task.output.id | Task.output.id | Equivalent | R5 `Task.output.id` maps as Equivalent to R4 `Task.output.id` |
| Task.output.modifierExtension | Task.output.modifierExtension | SourceIsBroaderThanTarget | R5 `Task.output.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Task.output.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Task.output.type | Task.output.type | Equivalent | R5 `Task.output.type` maps as Equivalent to R4 `Task.output.type` |
| Task.output.value[x] | Task.output.value[x] | RelatedTo | R5 `Task.output.value[x]` maps as RelatedTo to R4 `Task.output.value[x]` - value[x] has change due to type change: R5 `value[x]` `integer64` maps as SourceIsBroaderThanTarget for R4 `value[x]`; value[x] has change due to type change: R5 `value[x]` `Annotation` maps as SourceIsBroaderThanTarget for R4 `value[x]`; value[x] has change due to type change: R5 `value[x]` `Attachment` maps as RelatedTo for R4 `value[x]`; value[x] has change due to type change: R5 value[x] CodeableReference has no equivalent or mapped type in R4 value[x]; value[x] has change due to type change: R5 `value[x]` `Ratio` maps as SourceIsBroaderThanTarget for R4 `value[x]`; value[x] has change due to type change: R5 value[x] RatioRange has no equivalent or mapped type in R4 value[x]; value[x] has change due to type change: R5 `value[x]` `Signature` maps as RelatedTo for R4 `value[x]`; value[x] has change due to type change: R5 `value[x]` `DataRequirement` maps as RelatedTo for R4 `value[x]`; value[x] has change due to type change: R5 `value[x]` `Expression` maps as RelatedTo for R4 `value[x]`; value[x] has change due to type change: R5 `value[x]` `ParameterDefinition` maps as RelatedTo for R4 `value[x]`; value[x] has change due to type change: R5 value[x] Availability has no equivalent or mapped type in R4 value[x]; value[x] has change due to type change: R5 value[x] ExtendedContactDetail has no equivalent or mapped type in R4 value[x]; value[x] has change due to type change: R5 `value[x]` `Dosage` maps as RelatedTo for R4 `value[x]` |
| Task.owner | Task.owner | SourceIsNarrowerThanTarget | R5 `Task.owner` maps as SourceIsNarrowerThanTarget to R4 `Task.owner` - owner has change due to type change: R5 `owner` `Reference` maps as SourceIsNarrowerThanTarget for R4 `owner` |
| Task.partOf | Task.partOf | Equivalent | R5 `Task.partOf` maps as Equivalent to R4 `Task.partOf` |
| Task.performer | - | DoesNotExistInTarget | R5 `Task.performer` does not appear in the target and has no mapping for `Task`. |
| Task.performer.actor | - | DoesNotExistInTarget | R5 `Task.performer.actor` does not appear in the target and has no mapping for `Task`. |
| Task.performer.extension | - | DoesNotExistInTarget | R5 `Task.performer.extension` does not appear in the target and has no mapping for `Task`. |
| Task.performer.function | - | DoesNotExistInTarget | R5 `Task.performer.function` does not appear in the target and has no mapping for `Task`. |
| Task.performer.id | - | DoesNotExistInTarget | R5 `Task.performer.id` does not appear in the target and has no mapping for `Task`. |
| Task.performer.modifierExtension | - | DoesNotExistInTarget | R5 `Task.performer.modifierExtension` does not appear in the target and has no mapping for `Task`. |
| Task.priority | Task.priority | Equivalent | R5 `Task.priority` maps as Equivalent to R4 `Task.priority` - priority has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-priority|5.0.0 and http://hl7.org/fhir/ValueSet/request-priority|4.0.1 (Equivalent) |
| Task.reason | - | DoesNotExistInTarget | R5 `Task.reason` does not appear in the target and has no mapping for `Task`. |
| Task.relevantHistory | Task.relevantHistory | Equivalent | R5 `Task.relevantHistory` maps as Equivalent to R4 `Task.relevantHistory` |
| Task.requestedPerformer | - | DoesNotExistInTarget | R5 `Task.requestedPerformer` does not appear in the target and has no mapping for `Task`. |
| Task.requestedPeriod | - | DoesNotExistInTarget | R5 `Task.requestedPeriod` does not appear in the target and has no mapping for `Task`. |
| Task.requester | Task.requester | Equivalent | R5 `Task.requester` maps as Equivalent to R4 `Task.requester` |
| Task.restriction | Task.restriction | Equivalent | R5 `Task.restriction` maps as Equivalent to R4 `Task.restriction` |
| Task.restriction.extension | Task.restriction.extension | SourceIsBroaderThanTarget | R5 `Task.restriction.extension` maps as SourceIsBroaderThanTarget to R4 `Task.restriction.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Task.restriction.id | Task.restriction.id | Equivalent | R5 `Task.restriction.id` maps as Equivalent to R4 `Task.restriction.id` |
| Task.restriction.modifierExtension | Task.restriction.modifierExtension | SourceIsBroaderThanTarget | R5 `Task.restriction.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Task.restriction.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Task.restriction.period | Task.restriction.period | Equivalent | R5 `Task.restriction.period` maps as Equivalent to R4 `Task.restriction.period` |
| Task.restriction.recipient | Task.restriction.recipient | Equivalent | R5 `Task.restriction.recipient` maps as Equivalent to R4 `Task.restriction.recipient` |
| Task.restriction.repetitions | Task.restriction.repetitions | Equivalent | R5 `Task.restriction.repetitions` maps as Equivalent to R4 `Task.restriction.repetitions` |
| Task.status | Task.status | Equivalent | R5 `Task.status` maps as Equivalent to R4 `Task.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/task-status|5.0.0 and http://hl7.org/fhir/ValueSet/task-status|4.0.1 (Equivalent) |
| Task.statusReason | Task.statusReason | SourceIsBroaderThanTarget | R5 `Task.statusReason` maps as SourceIsBroaderThanTarget to R4 `Task.statusReason` - statusReason has change due to type change: R5 statusReason CodeableReference has no equivalent or mapped type in R4 statusReason |
| Task.text | Task.text | Equivalent | R5 `Task.text` maps as Equivalent to R4 `Task.text` |

