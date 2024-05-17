Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:03 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Extension |  | Base StructureDefinition for Extension Type: Optional Extension Element - found in all resources. | 5 | 3 |
| Target | Extension |  | Extension Type: Optional Extension Element - found in all resources. | 5 | 3 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Extension | Extension | Equivalent | R4B `Extension` maps as Equivalent to R5 `Extension` |
| Extension.extension | Extension.extension | Equivalent | R4B `Extension.extension` maps as Equivalent to R5 `Extension.extension` |
| Extension.id | Extension.id | Equivalent | R4B `Extension.id` maps as Equivalent to R5 `Extension.id` |
| Extension.url | Extension.url | Equivalent | R4B `Extension.url` maps as Equivalent to R5 `Extension.url` |
| Extension.value[x] | Extension.value[x] | RelatedTo | R4B `Extension.value[x]` maps as RelatedTo to R5 `Extension.value[x]` - value[x] has change due to type change: R4B `value[x]` `integer` maps as SourceIsNarrowerThanTarget for R5 `value[x]`; value[x] has change due to type change: R4B `value[x]` `positiveInt` maps as SourceIsNarrowerThanTarget for R5 `value[x]`; value[x] has change due to type change: R4B `value[x]` `unsignedInt` maps as SourceIsNarrowerThanTarget for R5 `value[x]`; value[x] has change due to type change: R4B value[x] Contributor has no equivalent or mapped type in R5 value[x] |

