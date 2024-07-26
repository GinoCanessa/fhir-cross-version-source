Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1
Generated at Thursday, July 25, 2024 3:56:51 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | DeviceMetric |  | Describes a measurement, calculation or setting capability of a device.  The DeviceMetric resource is derived from the ISO/IEEE 11073-10201 Domain Information Model standard, but is more widely applicable.  | 24 | 13 |
| Target | DeviceMetric |  | Describes a measurement, calculation or setting capability of a medical device. | 25 | 14 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 2 |
Equivalent | 4 |
RelatedTo | 18 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| DeviceMetric | DeviceMetric | Equivalent | R5 `DeviceMetric` maps as Equivalent to R4 `DeviceMetric` |
| DeviceMetric.calibration | DeviceMetric.calibration | Equivalent | R5 `DeviceMetric.calibration` maps as Equivalent to R4 `DeviceMetric.calibration` |
| DeviceMetric.calibration.extension | DeviceMetric.calibration.extension | SourceIsBroaderThanTarget | R5 `DeviceMetric.calibration.extension` maps as SourceIsBroaderThanTarget to R4 `DeviceMetric.calibration.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| DeviceMetric.calibration.id | DeviceMetric.calibration.id | Equivalent | R5 `DeviceMetric.calibration.id` maps as Equivalent to R4 `DeviceMetric.calibration.id` |
| DeviceMetric.calibration.modifierExtension | DeviceMetric.calibration.modifierExtension | SourceIsBroaderThanTarget | R5 `DeviceMetric.calibration.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `DeviceMetric.calibration.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| DeviceMetric.calibration.state | DeviceMetric.calibration.state | Equivalent | R5 `DeviceMetric.calibration.state` maps as Equivalent to R4 `DeviceMetric.calibration.state` - state has compatible required binding for code type: http://hl7.org/fhir/ValueSet/metric-calibration-state|5.0.0 and http://hl7.org/fhir/ValueSet/metric-calibration-state|4.0.1 (Equivalent) |
| DeviceMetric.calibration.time | DeviceMetric.calibration.time | Equivalent | R5 `DeviceMetric.calibration.time` maps as Equivalent to R4 `DeviceMetric.calibration.time` |
| DeviceMetric.calibration.type | DeviceMetric.calibration.type | Equivalent | R5 `DeviceMetric.calibration.type` maps as Equivalent to R4 `DeviceMetric.calibration.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/metric-calibration-type|5.0.0 and http://hl7.org/fhir/ValueSet/metric-calibration-type|4.0.1 (Equivalent) |
| DeviceMetric.category | DeviceMetric.category | Equivalent | R5 `DeviceMetric.category` maps as Equivalent to R4 `DeviceMetric.category` - category has compatible required binding for code type: http://hl7.org/fhir/ValueSet/metric-category|5.0.0 and http://hl7.org/fhir/ValueSet/metric-category|4.0.1 (Equivalent) |
| DeviceMetric.color | DeviceMetric.color | RelatedTo | R5 `DeviceMetric.color` maps as RelatedTo to R4 `DeviceMetric.color` - (color failed to compare required binding of http://hl7.org/fhir/ValueSet/color-codes|5.0.0 and http://hl7.org/fhir/ValueSet/metric-color|4.0.1) |
| DeviceMetric.contained | DeviceMetric.contained | Equivalent | R5 `DeviceMetric.contained` maps as Equivalent to R4 `DeviceMetric.contained` |
| DeviceMetric.device | - | DoesNotExistInTarget | R5 `DeviceMetric.device` does not appear in the target and has no mapping for `DeviceMetric`. |
| DeviceMetric.extension | DeviceMetric.extension | SourceIsBroaderThanTarget | R5 `DeviceMetric.extension` maps as SourceIsBroaderThanTarget to R4 `DeviceMetric.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| DeviceMetric.id | DeviceMetric.id | Equivalent | R5 `DeviceMetric.id` maps as Equivalent to R4 `DeviceMetric.id` |
| DeviceMetric.identifier | DeviceMetric.identifier | Equivalent | R5 `DeviceMetric.identifier` maps as Equivalent to R4 `DeviceMetric.identifier` |
| DeviceMetric.implicitRules | DeviceMetric.implicitRules | Equivalent | R5 `DeviceMetric.implicitRules` maps as Equivalent to R4 `DeviceMetric.implicitRules` |
| DeviceMetric.language | DeviceMetric.language | RelatedTo | R5 `DeviceMetric.language` maps as RelatedTo to R4 `DeviceMetric.language` - language changed the binding strength from Required to Preferred |
| DeviceMetric.measurementFrequency | - | DoesNotExistInTarget | R5 `DeviceMetric.measurementFrequency` does not appear in the target and has no mapping for `DeviceMetric`. |
| DeviceMetric.meta | DeviceMetric.meta | Equivalent | R5 `DeviceMetric.meta` maps as Equivalent to R4 `DeviceMetric.meta` |
| DeviceMetric.modifierExtension | DeviceMetric.modifierExtension | SourceIsBroaderThanTarget | R5 `DeviceMetric.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `DeviceMetric.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| DeviceMetric.operationalStatus | DeviceMetric.operationalStatus | Equivalent | R5 `DeviceMetric.operationalStatus` maps as Equivalent to R4 `DeviceMetric.operationalStatus` - operationalStatus has compatible required binding for code type: http://hl7.org/fhir/ValueSet/metric-operational-status|5.0.0 and http://hl7.org/fhir/ValueSet/metric-operational-status|4.0.1 (Equivalent) |
| DeviceMetric.text | DeviceMetric.text | Equivalent | R5 `DeviceMetric.text` maps as Equivalent to R4 `DeviceMetric.text` |
| DeviceMetric.type | DeviceMetric.type | Equivalent | R5 `DeviceMetric.type` maps as Equivalent to R4 `DeviceMetric.type` |
| DeviceMetric.unit | DeviceMetric.unit | Equivalent | R5 `DeviceMetric.unit` maps as Equivalent to R4 `DeviceMetric.unit` |

