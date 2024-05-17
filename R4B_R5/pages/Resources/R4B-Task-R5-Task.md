Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Task |  | A task to be performed. | 56 | 39 |
| Target | Task |  | A task to be performed. | 63 | 43 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 3 |
Equivalent | 4 |
RelatedTo | 49 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Task | Task | Equivalent | R4B `Task` maps as Equivalent to R5 `Task` |
| Task.authoredOn | Task.authoredOn | Equivalent | R4B `Task.authoredOn` maps as Equivalent to R5 `Task.authoredOn` |
| Task.basedOn | Task.basedOn | Equivalent | R4B `Task.basedOn` maps as Equivalent to R5 `Task.basedOn` |
| Task.businessStatus | Task.businessStatus | Equivalent | R4B `Task.businessStatus` maps as Equivalent to R5 `Task.businessStatus` |
| Task.code | Task.code | Equivalent | R4B `Task.code` maps as Equivalent to R5 `Task.code` |
| Task.contained | Task.contained | Equivalent | R4B `Task.contained` maps as Equivalent to R5 `Task.contained` |
| Task.description | Task.description | Equivalent | R4B `Task.description` maps as Equivalent to R5 `Task.description` |
| Task.encounter | Task.encounter | Equivalent | R4B `Task.encounter` maps as Equivalent to R5 `Task.encounter` |
| Task.executionPeriod | Task.executionPeriod | Equivalent | R4B `Task.executionPeriod` maps as Equivalent to R5 `Task.executionPeriod` |
| Task.extension | Task.extension | RelatedTo | R4B `Task.extension` maps as RelatedTo to R5 `Task.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Task.focus | Task.focus | Equivalent | R4B `Task.focus` maps as Equivalent to R5 `Task.focus` |
| Task.for | Task.for | Equivalent | R4B `Task.for` maps as Equivalent to R5 `Task.for` |
| Task.groupIdentifier | Task.groupIdentifier | Equivalent | R4B `Task.groupIdentifier` maps as Equivalent to R5 `Task.groupIdentifier` |
| Task.id | Task.id | Equivalent | R4B `Task.id` maps as Equivalent to R5 `Task.id` |
| Task.identifier | Task.identifier | Equivalent | R4B `Task.identifier` maps as Equivalent to R5 `Task.identifier` |
| Task.implicitRules | Task.implicitRules | Equivalent | R4B `Task.implicitRules` maps as Equivalent to R5 `Task.implicitRules` |
| Task.input | Task.input | Equivalent | R4B `Task.input` maps as Equivalent to R5 `Task.input` |
| Task.input.extension | Task.input.extension | RelatedTo | R4B `Task.input.extension` maps as RelatedTo to R5 `Task.input.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Task.input.id | Task.input.id | Equivalent | R4B `Task.input.id` maps as Equivalent to R5 `Task.input.id` |
| Task.input.modifierExtension | Task.input.modifierExtension | RelatedTo | R4B `Task.input.modifierExtension` maps as RelatedTo to R5 `Task.input.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Task.input.type | Task.input.type | Equivalent | R4B `Task.input.type` maps as Equivalent to R5 `Task.input.type` |
| Task.input.value[x] | Task.input.value[x] | RelatedTo | R4B `Task.input.value[x]` maps as RelatedTo to R5 `Task.input.value[x]` - value[x] has change due to type change: R4B `value[x]` `integer` maps as SourceIsNarrowerThanTarget for R5 `value[x]`; value[x] has change due to type change: R4B `value[x]` `positiveInt` maps as SourceIsNarrowerThanTarget for R5 `value[x]`; value[x] has change due to type change: R4B `value[x]` `unsignedInt` maps as SourceIsNarrowerThanTarget for R5 `value[x]`; value[x] has change due to type change: R4B `value[x]` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `value[x]`; value[x] has change due to type change: R4B `value[x]` `Attachment` maps as RelatedTo for R5 `value[x]`; value[x] has change due to type change: R4B `value[x]` `Money` maps as RelatedTo for R5 `value[x]`; value[x] has change due to type change: R4B `value[x]` `Ratio` maps as SourceIsNarrowerThanTarget for R5 `value[x]`; value[x] has change due to type change: R4B value[x] Contributor has no equivalent or mapped type in R5 value[x]; value[x] has change due to type change: R4B `value[x]` `DataRequirement` maps as RelatedTo for R5 `value[x]`; value[x] has change due to type change: R4B `value[x]` `Expression` maps as SourceIsBroaderThanTarget for R5 `value[x]`; value[x] has change due to type change: R4B `value[x]` `ParameterDefinition` maps as RelatedTo for R5 `value[x]`; value[x] has change due to type change: R4B `value[x]` `Dosage` maps as RelatedTo for R5 `value[x]` |
| Task.instantiatesCanonical | Task.instantiatesCanonical | Equivalent | R4B `Task.instantiatesCanonical` maps as Equivalent to R5 `Task.instantiatesCanonical` |
| Task.instantiatesUri | Task.instantiatesUri | Equivalent | R4B `Task.instantiatesUri` maps as Equivalent to R5 `Task.instantiatesUri` |
| Task.insurance | Task.insurance | Equivalent | R4B `Task.insurance` maps as Equivalent to R5 `Task.insurance` |
| Task.intent | Task.intent | Equivalent | R4B `Task.intent` maps as Equivalent to R5 `Task.intent` - intent has compatible required binding for code type: http://hl7.org/fhir/ValueSet/task-intent|4.3.0 and http://hl7.org/fhir/ValueSet/task-intent|5.0.0 (Equivalent) |
| Task.language | Task.language | RelatedTo | R4B `Task.language` maps as RelatedTo to R5 `Task.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Task.lastModified | Task.lastModified | Equivalent | R4B `Task.lastModified` maps as Equivalent to R5 `Task.lastModified` |
| Task.location | Task.location | Equivalent | R4B `Task.location` maps as Equivalent to R5 `Task.location` |
| Task.meta | Task.meta | Equivalent | R4B `Task.meta` maps as Equivalent to R5 `Task.meta` |
| Task.modifierExtension | Task.modifierExtension | RelatedTo | R4B `Task.modifierExtension` maps as RelatedTo to R5 `Task.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Task.note | Task.note | SourceIsNarrowerThanTarget | R4B `Task.note` maps as SourceIsNarrowerThanTarget to R5 `Task.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| Task.output | Task.output | Equivalent | R4B `Task.output` maps as Equivalent to R5 `Task.output` |
| Task.output.extension | Task.output.extension | RelatedTo | R4B `Task.output.extension` maps as RelatedTo to R5 `Task.output.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Task.output.id | Task.output.id | Equivalent | R4B `Task.output.id` maps as Equivalent to R5 `Task.output.id` |
| Task.output.modifierExtension | Task.output.modifierExtension | RelatedTo | R4B `Task.output.modifierExtension` maps as RelatedTo to R5 `Task.output.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Task.output.type | Task.output.type | Equivalent | R4B `Task.output.type` maps as Equivalent to R5 `Task.output.type` |
| Task.output.value[x] | Task.output.value[x] | RelatedTo | R4B `Task.output.value[x]` maps as RelatedTo to R5 `Task.output.value[x]` - value[x] has change due to type change: R4B `value[x]` `integer` maps as SourceIsNarrowerThanTarget for R5 `value[x]`; value[x] has change due to type change: R4B `value[x]` `positiveInt` maps as SourceIsNarrowerThanTarget for R5 `value[x]`; value[x] has change due to type change: R4B `value[x]` `unsignedInt` maps as SourceIsNarrowerThanTarget for R5 `value[x]`; value[x] has change due to type change: R4B `value[x]` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `value[x]`; value[x] has change due to type change: R4B `value[x]` `Attachment` maps as RelatedTo for R5 `value[x]`; value[x] has change due to type change: R4B `value[x]` `Money` maps as RelatedTo for R5 `value[x]`; value[x] has change due to type change: R4B `value[x]` `Ratio` maps as SourceIsNarrowerThanTarget for R5 `value[x]`; value[x] has change due to type change: R4B value[x] Contributor has no equivalent or mapped type in R5 value[x]; value[x] has change due to type change: R4B `value[x]` `DataRequirement` maps as RelatedTo for R5 `value[x]`; value[x] has change due to type change: R4B `value[x]` `Expression` maps as SourceIsBroaderThanTarget for R5 `value[x]`; value[x] has change due to type change: R4B `value[x]` `ParameterDefinition` maps as RelatedTo for R5 `value[x]`; value[x] has change due to type change: R4B `value[x]` `Dosage` maps as RelatedTo for R5 `value[x]` |
| Task.owner | Task.owner | SourceIsBroaderThanTarget | R4B `Task.owner` maps as SourceIsBroaderThanTarget to R5 `Task.owner` - owner has change due to type change: R4B `owner` `Reference` maps as SourceIsBroaderThanTarget for R5 `owner` |
| Task.partOf | Task.partOf | Equivalent | R4B `Task.partOf` maps as Equivalent to R5 `Task.partOf` |
| Task.performerType | - | DoesNotExistInTarget | R4B `Task.performerType` does not appear in the target and has no mapping for `Task`. |
| Task.priority | Task.priority | Equivalent | R4B `Task.priority` maps as Equivalent to R5 `Task.priority` - priority has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-priority|4.3.0 and http://hl7.org/fhir/ValueSet/request-priority|5.0.0 (Equivalent) |
| Task.reasonCode | - | DoesNotExistInTarget | R4B `Task.reasonCode` does not appear in the target and has no mapping for `Task`. |
| Task.reasonReference | - | DoesNotExistInTarget | R4B `Task.reasonReference` does not appear in the target and has no mapping for `Task`. |
| Task.relevantHistory | Task.relevantHistory | Equivalent | R4B `Task.relevantHistory` maps as Equivalent to R5 `Task.relevantHistory` |
| Task.requester | Task.requester | Equivalent | R4B `Task.requester` maps as Equivalent to R5 `Task.requester` |
| Task.restriction | Task.restriction | Equivalent | R4B `Task.restriction` maps as Equivalent to R5 `Task.restriction` |
| Task.restriction.extension | Task.restriction.extension | RelatedTo | R4B `Task.restriction.extension` maps as RelatedTo to R5 `Task.restriction.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Task.restriction.id | Task.restriction.id | Equivalent | R4B `Task.restriction.id` maps as Equivalent to R5 `Task.restriction.id` |
| Task.restriction.modifierExtension | Task.restriction.modifierExtension | RelatedTo | R4B `Task.restriction.modifierExtension` maps as RelatedTo to R5 `Task.restriction.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Task.restriction.period | Task.restriction.period | Equivalent | R4B `Task.restriction.period` maps as Equivalent to R5 `Task.restriction.period` |
| Task.restriction.recipient | Task.restriction.recipient | Equivalent | R4B `Task.restriction.recipient` maps as Equivalent to R5 `Task.restriction.recipient` |
| Task.restriction.repetitions | Task.restriction.repetitions | Equivalent | R4B `Task.restriction.repetitions` maps as Equivalent to R5 `Task.restriction.repetitions` |
| Task.status | Task.status | Equivalent | R4B `Task.status` maps as Equivalent to R5 `Task.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/task-status|4.3.0 and http://hl7.org/fhir/ValueSet/task-status|5.0.0 (Equivalent) |
| Task.statusReason | Task.statusReason | SourceIsBroaderThanTarget | R4B `Task.statusReason` maps as SourceIsBroaderThanTarget to R5 `Task.statusReason` - statusReason has change due to type change: R4B statusReason CodeableConcept has no equivalent or mapped type in R5 statusReason |
| Task.text | Task.text | Equivalent | R4B `Task.text` maps as Equivalent to R5 `Task.text` |

