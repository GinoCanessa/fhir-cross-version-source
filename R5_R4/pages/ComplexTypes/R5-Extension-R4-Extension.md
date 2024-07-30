Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Extension |  | Extension Type: Optional Extension Element - found in all resources. | 5 | 3 |
| Target | Extension |  | Base StructureDefinition for Extension Type: Optional Extension Element - found in all resources. | 5 | 3 |


Comparison Result: SourceIsBroaderThanTarget


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
SourceIsBroaderThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Extension | Extension | Equivalent | R5 `Extension` maps as Equivalent to R4 `Extension` |
| Extension.extension | Extension.extension | Equivalent | R5 `Extension.extension` maps as Equivalent to R4 `Extension.extension` |
| Extension.id | Extension.id | Equivalent | R5 `Extension.id` maps as Equivalent to R4 `Extension.id` |
| Extension.url | Extension.url | Equivalent | R5 `Extension.url` maps as Equivalent to R4 `Extension.url` |
| Extension.value[x] | Extension.value[x] | SourceIsBroaderThanTarget | R5 `Extension.value[x]` maps as SourceIsBroaderThanTarget to R4 `Extension.value[x]` - value[x] has change due to type change: R5 `value[x]` `integer64` maps as SourceIsBroaderThanTarget for R4 `value[x]`; value[x] has change due to type change: R5 value[x] CodeableReference has no equivalent or mapped type in R4 value[x]; value[x] has change due to type change: R5 value[x] RatioRange has no equivalent or mapped type in R4 value[x]; value[x] has change due to type change: R5 value[x] Availability has no equivalent or mapped type in R4 value[x]; value[x] has change due to type change: R5 value[x] ExtendedContactDetail has no equivalent or mapped type in R4 value[x] |

