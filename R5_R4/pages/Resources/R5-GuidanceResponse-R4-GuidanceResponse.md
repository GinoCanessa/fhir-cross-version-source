Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | GuidanceResponse |  | A guidance response is the formal response to a guidance request, including any output parameters returned by the evaluation, as well as the description of any proposed actions to be taken. | 23 | 15 |
| Target | GuidanceResponse |  | A guidance response is the formal response to a guidance request, including any output parameters returned by the evaluation, as well as the description of any proposed actions to be taken. | 24 | 16 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 1 |
Equivalent | 4 |
RelatedTo | 18 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| GuidanceResponse | GuidanceResponse | Equivalent | R5 `GuidanceResponse` maps as Equivalent to R4 `GuidanceResponse` |
| GuidanceResponse.contained | GuidanceResponse.contained | Equivalent | R5 `GuidanceResponse.contained` maps as Equivalent to R4 `GuidanceResponse.contained` |
| GuidanceResponse.dataRequirement | GuidanceResponse.dataRequirement | RelatedTo | R5 `GuidanceResponse.dataRequirement` maps as RelatedTo to R4 `GuidanceResponse.dataRequirement` - dataRequirement has change due to type change: R5 `dataRequirement` `DataRequirement` maps as RelatedTo for R4 `dataRequirement` |
| GuidanceResponse.encounter | GuidanceResponse.encounter | Equivalent | R5 `GuidanceResponse.encounter` maps as Equivalent to R4 `GuidanceResponse.encounter` |
| GuidanceResponse.evaluationMessage | GuidanceResponse.evaluationMessage | RelatedTo | R5 `GuidanceResponse.evaluationMessage` maps as RelatedTo to R4 `GuidanceResponse.evaluationMessage` - evaluationMessage changed from scalar to array (max cardinality from 1 to *) |
| GuidanceResponse.extension | GuidanceResponse.extension | SourceIsBroaderThanTarget | R5 `GuidanceResponse.extension` maps as SourceIsBroaderThanTarget to R4 `GuidanceResponse.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| GuidanceResponse.id | GuidanceResponse.id | Equivalent | R5 `GuidanceResponse.id` maps as Equivalent to R4 `GuidanceResponse.id` |
| GuidanceResponse.identifier | GuidanceResponse.identifier | Equivalent | R5 `GuidanceResponse.identifier` maps as Equivalent to R4 `GuidanceResponse.identifier` |
| GuidanceResponse.implicitRules | GuidanceResponse.implicitRules | Equivalent | R5 `GuidanceResponse.implicitRules` maps as Equivalent to R4 `GuidanceResponse.implicitRules` |
| GuidanceResponse.language | GuidanceResponse.language | RelatedTo | R5 `GuidanceResponse.language` maps as RelatedTo to R4 `GuidanceResponse.language` - language changed the binding strength from Required to Preferred |
| GuidanceResponse.meta | GuidanceResponse.meta | Equivalent | R5 `GuidanceResponse.meta` maps as Equivalent to R4 `GuidanceResponse.meta` |
| GuidanceResponse.modifierExtension | GuidanceResponse.modifierExtension | SourceIsBroaderThanTarget | R5 `GuidanceResponse.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `GuidanceResponse.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| GuidanceResponse.module[x] | GuidanceResponse.module[x] | RelatedTo | R5 `GuidanceResponse.module[x]` maps as RelatedTo to R4 `GuidanceResponse.module[x]` - module[x] removed a binding requirement - Example http://hl7.org/fhir/ValueSet/guidance-module-code |
| GuidanceResponse.note | GuidanceResponse.note | SourceIsBroaderThanTarget | R5 `GuidanceResponse.note` maps as SourceIsBroaderThanTarget to R4 `GuidanceResponse.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4 `note` |
| GuidanceResponse.occurrenceDateTime | GuidanceResponse.occurrenceDateTime | Equivalent | R5 `GuidanceResponse.occurrenceDateTime` maps as Equivalent to R4 `GuidanceResponse.occurrenceDateTime` |
| GuidanceResponse.outputParameters | GuidanceResponse.outputParameters | Equivalent | R5 `GuidanceResponse.outputParameters` maps as Equivalent to R4 `GuidanceResponse.outputParameters` |
| GuidanceResponse.performer | GuidanceResponse.performer | Equivalent | R5 `GuidanceResponse.performer` maps as Equivalent to R4 `GuidanceResponse.performer` |
| GuidanceResponse.reason | - | DoesNotExistInTarget | R5 `GuidanceResponse.reason` does not appear in the target and has no mapping for `GuidanceResponse`. |
| GuidanceResponse.requestIdentifier | GuidanceResponse.requestIdentifier | Equivalent | R5 `GuidanceResponse.requestIdentifier` maps as Equivalent to R4 `GuidanceResponse.requestIdentifier` |
| GuidanceResponse.result | GuidanceResponse.result | RelatedTo | R5 `GuidanceResponse.result` maps as RelatedTo to R4 `GuidanceResponse.result` - result changed from array to scalar (max cardinality from * to 1); result has change due to type change: R5 `result` `Reference` maps as RelatedTo for R4 `result` |
| GuidanceResponse.status | GuidanceResponse.status | Equivalent | R5 `GuidanceResponse.status` maps as Equivalent to R4 `GuidanceResponse.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/guidance-response-status|5.0.0 and http://hl7.org/fhir/ValueSet/guidance-response-status|4.0.1 (Equivalent) |
| GuidanceResponse.subject | GuidanceResponse.subject | Equivalent | R5 `GuidanceResponse.subject` maps as Equivalent to R4 `GuidanceResponse.subject` |
| GuidanceResponse.text | GuidanceResponse.text | Equivalent | R5 `GuidanceResponse.text` maps as Equivalent to R4 `GuidanceResponse.text` |

