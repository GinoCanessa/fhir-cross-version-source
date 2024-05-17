Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | GuidanceResponse |  | A guidance response is the formal response to a guidance request, including any output parameters returned by the evaluation, as well as the description of any proposed actions to be taken. | 24 | 16 |
| Target | GuidanceResponse |  | A guidance response is the formal response to a guidance request, including any output parameters returned by the evaluation, as well as the description of any proposed actions to be taken. | 23 | 15 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 2 |
Equivalent | 4 |
RelatedTo | 18 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| GuidanceResponse | GuidanceResponse | Equivalent | R4B `GuidanceResponse` maps as Equivalent to R5 `GuidanceResponse` |
| GuidanceResponse.contained | GuidanceResponse.contained | Equivalent | R4B `GuidanceResponse.contained` maps as Equivalent to R5 `GuidanceResponse.contained` |
| GuidanceResponse.dataRequirement | GuidanceResponse.dataRequirement | RelatedTo | R4B `GuidanceResponse.dataRequirement` maps as RelatedTo to R5 `GuidanceResponse.dataRequirement` - dataRequirement has change due to type change: R4B `dataRequirement` `DataRequirement` maps as RelatedTo for R5 `dataRequirement` |
| GuidanceResponse.encounter | GuidanceResponse.encounter | Equivalent | R4B `GuidanceResponse.encounter` maps as Equivalent to R5 `GuidanceResponse.encounter` |
| GuidanceResponse.evaluationMessage | GuidanceResponse.evaluationMessage | RelatedTo | R4B `GuidanceResponse.evaluationMessage` maps as RelatedTo to R5 `GuidanceResponse.evaluationMessage` - evaluationMessage changed from array to scalar (max cardinality from * to 1) |
| GuidanceResponse.extension | GuidanceResponse.extension | RelatedTo | R4B `GuidanceResponse.extension` maps as RelatedTo to R5 `GuidanceResponse.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| GuidanceResponse.id | GuidanceResponse.id | Equivalent | R4B `GuidanceResponse.id` maps as Equivalent to R5 `GuidanceResponse.id` |
| GuidanceResponse.identifier | GuidanceResponse.identifier | Equivalent | R4B `GuidanceResponse.identifier` maps as Equivalent to R5 `GuidanceResponse.identifier` |
| GuidanceResponse.implicitRules | GuidanceResponse.implicitRules | Equivalent | R4B `GuidanceResponse.implicitRules` maps as Equivalent to R5 `GuidanceResponse.implicitRules` |
| GuidanceResponse.language | GuidanceResponse.language | RelatedTo | R4B `GuidanceResponse.language` maps as RelatedTo to R5 `GuidanceResponse.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| GuidanceResponse.meta | GuidanceResponse.meta | Equivalent | R4B `GuidanceResponse.meta` maps as Equivalent to R5 `GuidanceResponse.meta` |
| GuidanceResponse.modifierExtension | GuidanceResponse.modifierExtension | RelatedTo | R4B `GuidanceResponse.modifierExtension` maps as RelatedTo to R5 `GuidanceResponse.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| GuidanceResponse.module[x] | GuidanceResponse.module[x] | RelatedTo | R4B `GuidanceResponse.module[x]` maps as RelatedTo to R5 `GuidanceResponse.module[x]` - module[x] added a binding requirement - Example http://hl7.org/fhir/ValueSet/guidance-module-code |
| GuidanceResponse.note | GuidanceResponse.note | SourceIsNarrowerThanTarget | R4B `GuidanceResponse.note` maps as SourceIsNarrowerThanTarget to R5 `GuidanceResponse.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| GuidanceResponse.occurrenceDateTime | GuidanceResponse.occurrenceDateTime | Equivalent | R4B `GuidanceResponse.occurrenceDateTime` maps as Equivalent to R5 `GuidanceResponse.occurrenceDateTime` |
| GuidanceResponse.outputParameters | GuidanceResponse.outputParameters | Equivalent | R4B `GuidanceResponse.outputParameters` maps as Equivalent to R5 `GuidanceResponse.outputParameters` |
| GuidanceResponse.performer | GuidanceResponse.performer | Equivalent | R4B `GuidanceResponse.performer` maps as Equivalent to R5 `GuidanceResponse.performer` |
| GuidanceResponse.reasonCode | - | DoesNotExistInTarget | R4B `GuidanceResponse.reasonCode` does not appear in the target and has no mapping for `GuidanceResponse`. |
| GuidanceResponse.reasonReference | - | DoesNotExistInTarget | R4B `GuidanceResponse.reasonReference` does not appear in the target and has no mapping for `GuidanceResponse`. |
| GuidanceResponse.requestIdentifier | GuidanceResponse.requestIdentifier | Equivalent | R4B `GuidanceResponse.requestIdentifier` maps as Equivalent to R5 `GuidanceResponse.requestIdentifier` |
| GuidanceResponse.result | GuidanceResponse.result | RelatedTo | R4B `GuidanceResponse.result` maps as RelatedTo to R5 `GuidanceResponse.result` - result changed from scalar to array (max cardinality from 1 to *); result has change due to type change: R4B `result` `Reference` maps as RelatedTo for R5 `result` |
| GuidanceResponse.status | GuidanceResponse.status | Equivalent | R4B `GuidanceResponse.status` maps as Equivalent to R5 `GuidanceResponse.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/guidance-response-status|4.3.0 and http://hl7.org/fhir/ValueSet/guidance-response-status|5.0.0 (Equivalent) |
| GuidanceResponse.subject | GuidanceResponse.subject | Equivalent | R4B `GuidanceResponse.subject` maps as Equivalent to R5 `GuidanceResponse.subject` |
| GuidanceResponse.text | GuidanceResponse.text | Equivalent | R4B `GuidanceResponse.text` maps as Equivalent to R5 `GuidanceResponse.text` |

