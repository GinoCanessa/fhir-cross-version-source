Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

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
| Extension | Extension | Equivalent | R5 `Extension` maps as Equivalent to R4B `Extension` |
| Extension.extension | Extension.extension | Equivalent | R5 `Extension.extension` maps as Equivalent to R4B `Extension.extension` |
| Extension.id | Extension.id | Equivalent | R5 `Extension.id` maps as Equivalent to R4B `Extension.id` |
| Extension.url | Extension.url | Equivalent | R5 `Extension.url` maps as Equivalent to R4B `Extension.url` |
| Extension.value[x] | Extension.value[x] | SourceIsBroaderThanTarget | R5 `Extension.value[x]` maps as SourceIsBroaderThanTarget to R4B `Extension.value[x]` - value[x] has change due to type change: R5 value[x] integer64 has no equivalent or mapped type in R4B value[x]; value[x] has change due to type change: R5 type Availability does not exist in R4B; value[x] has change due to type change: R5 type ExtendedContactDetail does not exist in R4B; value[x] has change due to type change: R5 value[x] Meta has no equivalent or mapped type in R4B value[x] |

