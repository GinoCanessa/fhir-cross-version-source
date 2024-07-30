Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | SampledData |  | SampledData Type: A series of measurements taken by a device, with upper and lower limits. There may be more than one dimension in the data. | 13 | 11 |
| Target | SampledData |  | Base StructureDefinition for SampledData Type: A series of measurements taken by a device, with upper and lower limits. There may be more than one dimension in the data. | 10 | 8 |


Comparison Result: Equivalent


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 4 |
Equivalent | 9 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| SampledData | SampledData | Equivalent | R5 `SampledData` maps as Equivalent to R4 `SampledData` |
| SampledData.codeMap | - | DoesNotExistInTarget | R5 `SampledData.codeMap` does not appear in the target and has no mapping for `SampledData`. |
| SampledData.data | SampledData.data | Equivalent | R5 `SampledData.data` maps as Equivalent to R4 `SampledData.data` |
| SampledData.dimensions | SampledData.dimensions | Equivalent | R5 `SampledData.dimensions` maps as Equivalent to R4 `SampledData.dimensions` |
| SampledData.extension | SampledData.extension | Equivalent | R5 `SampledData.extension` maps as Equivalent to R4 `SampledData.extension` |
| SampledData.factor | SampledData.factor | Equivalent | R5 `SampledData.factor` maps as Equivalent to R4 `SampledData.factor` |
| SampledData.id | SampledData.id | Equivalent | R5 `SampledData.id` maps as Equivalent to R4 `SampledData.id` |
| SampledData.interval | - | DoesNotExistInTarget | R5 `SampledData.interval` does not appear in the target and has no mapping for `SampledData`. |
| SampledData.intervalUnit | - | DoesNotExistInTarget | R5 `SampledData.intervalUnit` does not appear in the target and has no mapping for `SampledData`. |
| SampledData.lowerLimit | SampledData.lowerLimit | Equivalent | R5 `SampledData.lowerLimit` maps as Equivalent to R4 `SampledData.lowerLimit` |
| SampledData.offsets | - | DoesNotExistInTarget | R5 `SampledData.offsets` does not appear in the target and has no mapping for `SampledData`. |
| SampledData.origin | SampledData.origin | Equivalent | R5 `SampledData.origin` maps as Equivalent to R4 `SampledData.origin` |
| SampledData.upperLimit | SampledData.upperLimit | Equivalent | R5 `SampledData.upperLimit` maps as Equivalent to R4 `SampledData.upperLimit` |

