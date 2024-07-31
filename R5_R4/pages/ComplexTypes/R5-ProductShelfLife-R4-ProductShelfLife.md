Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | ProductShelfLife |  | ProductShelfLife Type: The shelf-life and storage information for a medicinal product item or container can be described using this class. | 7 | 4 |
| Target | ProductShelfLife |  | Base StructureDefinition for ProductShelfLife Type: The shelf-life and storage information for a medicinal product item or container can be described using this class. | 8 | 5 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 5 |
RelatedTo | 2 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| ProductShelfLife | ProductShelfLife | Equivalent | R5 `ProductShelfLife` maps as Equivalent to R4 `ProductShelfLife` |
| ProductShelfLife.extension | ProductShelfLife.extension | Equivalent | R5 `ProductShelfLife.extension` maps as Equivalent to R4 `ProductShelfLife.extension` |
| ProductShelfLife.id | ProductShelfLife.id | Equivalent | R5 `ProductShelfLife.id` maps as Equivalent to R4 `ProductShelfLife.id` |
| ProductShelfLife.modifierExtension | ProductShelfLife.modifierExtension | Equivalent | R5 `ProductShelfLife.modifierExtension` maps as Equivalent to R4 `ProductShelfLife.modifierExtension` |
| ProductShelfLife.period[x] | ProductShelfLife.period | RelatedTo | R5 `ProductShelfLife.period[x]` maps as RelatedTo to R4 `ProductShelfLife.period` - period made the element mandatory; period increased the minimum cardinality from 0 to 1; period has change due to type change: R5 period[x] Duration has no equivalent or mapped type in R4 period; period has change due to type change: R5 period[x] string has no equivalent or mapped type in R4 period |
| ProductShelfLife.specialPrecautionsForStorage | ProductShelfLife.specialPrecautionsForStorage | Equivalent | R5 `ProductShelfLife.specialPrecautionsForStorage` maps as Equivalent to R4 `ProductShelfLife.specialPrecautionsForStorage` |
| ProductShelfLife.type | ProductShelfLife.type | RelatedTo | R5 `ProductShelfLife.type` maps as RelatedTo to R4 `ProductShelfLife.type` - type made the element mandatory; type increased the minimum cardinality from 0 to 1 |

