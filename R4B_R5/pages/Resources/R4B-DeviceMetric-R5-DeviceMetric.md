Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | DeviceMetric |  | Describes a measurement, calculation or setting capability of a medical device. | 25 | 14 |
| Target | DeviceMetric |  | Describes a measurement, calculation or setting capability of a device.  The DeviceMetric resource is derived from the ISO/IEEE 11073-10201 Domain Information Model standard, but is more widely applicable.  | 24 | 13 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 3 |
Equivalent | 4 |
RelatedTo | 18 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| DeviceMetric | DeviceMetric | Equivalent | R4B `DeviceMetric` maps as Equivalent to R5 `DeviceMetric` |
| DeviceMetric.calibration | DeviceMetric.calibration | Equivalent | R4B `DeviceMetric.calibration` maps as Equivalent to R5 `DeviceMetric.calibration` |
| DeviceMetric.calibration.extension | DeviceMetric.calibration.extension | RelatedTo | R4B `DeviceMetric.calibration.extension` maps as RelatedTo to R5 `DeviceMetric.calibration.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| DeviceMetric.calibration.id | DeviceMetric.calibration.id | Equivalent | R4B `DeviceMetric.calibration.id` maps as Equivalent to R5 `DeviceMetric.calibration.id` |
| DeviceMetric.calibration.modifierExtension | DeviceMetric.calibration.modifierExtension | RelatedTo | R4B `DeviceMetric.calibration.modifierExtension` maps as RelatedTo to R5 `DeviceMetric.calibration.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| DeviceMetric.calibration.state | DeviceMetric.calibration.state | Equivalent | R4B `DeviceMetric.calibration.state` maps as Equivalent to R5 `DeviceMetric.calibration.state` - state has compatible required binding for code type: http://hl7.org/fhir/ValueSet/metric-calibration-state|4.3.0 and http://hl7.org/fhir/ValueSet/metric-calibration-state|5.0.0 (Equivalent) |
| DeviceMetric.calibration.time | DeviceMetric.calibration.time | Equivalent | R4B `DeviceMetric.calibration.time` maps as Equivalent to R5 `DeviceMetric.calibration.time` |
| DeviceMetric.calibration.type | DeviceMetric.calibration.type | Equivalent | R4B `DeviceMetric.calibration.type` maps as Equivalent to R5 `DeviceMetric.calibration.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/metric-calibration-type|4.3.0 and http://hl7.org/fhir/ValueSet/metric-calibration-type|5.0.0 (Equivalent) |
| DeviceMetric.category | DeviceMetric.category | Equivalent | R4B `DeviceMetric.category` maps as Equivalent to R5 `DeviceMetric.category` - category has compatible required binding for code type: http://hl7.org/fhir/ValueSet/metric-category|4.3.0 and http://hl7.org/fhir/ValueSet/metric-category|5.0.0 (Equivalent) |
| DeviceMetric.color | DeviceMetric.color | RelatedTo | R4B `DeviceMetric.color` maps as RelatedTo to R5 `DeviceMetric.color` - (color failed to compare required binding of http://hl7.org/fhir/ValueSet/metric-color|4.3.0 and http://hl7.org/fhir/ValueSet/color-codes|5.0.0) |
| DeviceMetric.contained | DeviceMetric.contained | Equivalent | R4B `DeviceMetric.contained` maps as Equivalent to R5 `DeviceMetric.contained` |
| DeviceMetric.extension | DeviceMetric.extension | RelatedTo | R4B `DeviceMetric.extension` maps as RelatedTo to R5 `DeviceMetric.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| DeviceMetric.id | DeviceMetric.id | Equivalent | R4B `DeviceMetric.id` maps as Equivalent to R5 `DeviceMetric.id` |
| DeviceMetric.identifier | DeviceMetric.identifier | Equivalent | R4B `DeviceMetric.identifier` maps as Equivalent to R5 `DeviceMetric.identifier` |
| DeviceMetric.implicitRules | DeviceMetric.implicitRules | Equivalent | R4B `DeviceMetric.implicitRules` maps as Equivalent to R5 `DeviceMetric.implicitRules` |
| DeviceMetric.language | DeviceMetric.language | RelatedTo | R4B `DeviceMetric.language` maps as RelatedTo to R5 `DeviceMetric.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| DeviceMetric.measurementPeriod | - | DoesNotExistInTarget | R4B `DeviceMetric.measurementPeriod` does not appear in the target and has no mapping for `DeviceMetric`. |
| DeviceMetric.meta | DeviceMetric.meta | Equivalent | R4B `DeviceMetric.meta` maps as Equivalent to R5 `DeviceMetric.meta` |
| DeviceMetric.modifierExtension | DeviceMetric.modifierExtension | RelatedTo | R4B `DeviceMetric.modifierExtension` maps as RelatedTo to R5 `DeviceMetric.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| DeviceMetric.operationalStatus | DeviceMetric.operationalStatus | Equivalent | R4B `DeviceMetric.operationalStatus` maps as Equivalent to R5 `DeviceMetric.operationalStatus` - operationalStatus has compatible required binding for code type: http://hl7.org/fhir/ValueSet/metric-operational-status|4.3.0 and http://hl7.org/fhir/ValueSet/metric-operational-status|5.0.0 (Equivalent) |
| DeviceMetric.parent | - | DoesNotExistInTarget | R4B `DeviceMetric.parent` does not appear in the target and has no mapping for `DeviceMetric`. |
| DeviceMetric.source | - | DoesNotExistInTarget | R4B `DeviceMetric.source` does not appear in the target and has no mapping for `DeviceMetric`. |
| DeviceMetric.text | DeviceMetric.text | Equivalent | R4B `DeviceMetric.text` maps as Equivalent to R5 `DeviceMetric.text` |
| DeviceMetric.type | DeviceMetric.type | Equivalent | R4B `DeviceMetric.type` maps as Equivalent to R5 `DeviceMetric.type` |
| DeviceMetric.unit | DeviceMetric.unit | Equivalent | R4B `DeviceMetric.unit` maps as Equivalent to R5 `DeviceMetric.unit` |

