Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | ProductShelfLife |  | ProductShelfLife Type: The shelf-life and storage information for a medicinal product item or container can be described using this class. | 7 | 4 |
| Target | ProductShelfLife |  | Base StructureDefinition for ProductShelfLife Type: The shelf-life and storage information for a medicinal product item or container can be described using this class. | 8 | 5 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 1 |
Equivalent | 4 |
RelatedTo | 2 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| ProductShelfLife | ProductShelfLife | Equivalent | R5 `ProductShelfLife` maps as Equivalent to R4B `ProductShelfLife` |
| ProductShelfLife.extension | ProductShelfLife.extension | Equivalent | R5 `ProductShelfLife.extension` maps as Equivalent to R4B `ProductShelfLife.extension` |
| ProductShelfLife.id | ProductShelfLife.id | Equivalent | R5 `ProductShelfLife.id` maps as Equivalent to R4B `ProductShelfLife.id` |
| ProductShelfLife.modifierExtension | ProductShelfLife.modifierExtension | Equivalent | R5 `ProductShelfLife.modifierExtension` maps as Equivalent to R4B `ProductShelfLife.modifierExtension` |
| ProductShelfLife.period[x] | - | DoesNotExistInTarget | R5 `ProductShelfLife.period[x]` does not appear in the target and has no mapping for `ProductShelfLife`. |
| ProductShelfLife.specialPrecautionsForStorage | ProductShelfLife.specialPrecautionsForStorage | Equivalent | R5 `ProductShelfLife.specialPrecautionsForStorage` maps as Equivalent to R4B `ProductShelfLife.specialPrecautionsForStorage` |
| ProductShelfLife.type | ProductShelfLife.type | RelatedTo | R5 `ProductShelfLife.type` maps as RelatedTo to R4B `ProductShelfLife.type` - type made the element mandatory; type increased the minimum cardinality from 0 to 1 |

