Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | ObservationDefinition |  | Set of definitional characteristics for a kind of observation or measurement produced or consumed by an orderable health care service. | 40 | 26 |
| Target | ObservationDefinition |  | Set of definitional characteristics for a kind of observation or measurement produced or consumed by an orderable health care service. | 68 | 54 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 24 |
Equivalent | 4 |
RelatedTo | 12 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| ObservationDefinition | ObservationDefinition | Equivalent | R4B `ObservationDefinition` maps as Equivalent to R5 `ObservationDefinition` |
| ObservationDefinition.abnormalCodedValueSet | - | DoesNotExistInTarget | R4B `ObservationDefinition.abnormalCodedValueSet` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.category | ObservationDefinition.category | Equivalent | R4B `ObservationDefinition.category` maps as Equivalent to R5 `ObservationDefinition.category` |
| ObservationDefinition.code | ObservationDefinition.code | Equivalent | R4B `ObservationDefinition.code` maps as Equivalent to R5 `ObservationDefinition.code` |
| ObservationDefinition.contained | ObservationDefinition.contained | Equivalent | R4B `ObservationDefinition.contained` maps as Equivalent to R5 `ObservationDefinition.contained` |
| ObservationDefinition.criticalCodedValueSet | - | DoesNotExistInTarget | R4B `ObservationDefinition.criticalCodedValueSet` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.extension | ObservationDefinition.extension | RelatedTo | R4B `ObservationDefinition.extension` maps as RelatedTo to R5 `ObservationDefinition.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ObservationDefinition.id | ObservationDefinition.id | Equivalent | R4B `ObservationDefinition.id` maps as Equivalent to R5 `ObservationDefinition.id` |
| ObservationDefinition.identifier | ObservationDefinition.identifier | RelatedTo | R4B `ObservationDefinition.identifier` maps as RelatedTo to R5 `ObservationDefinition.identifier` - identifier changed from array to scalar (max cardinality from * to 1) |
| ObservationDefinition.implicitRules | ObservationDefinition.implicitRules | Equivalent | R4B `ObservationDefinition.implicitRules` maps as Equivalent to R5 `ObservationDefinition.implicitRules` |
| ObservationDefinition.language | ObservationDefinition.language | RelatedTo | R4B `ObservationDefinition.language` maps as RelatedTo to R5 `ObservationDefinition.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| ObservationDefinition.meta | ObservationDefinition.meta | Equivalent | R4B `ObservationDefinition.meta` maps as Equivalent to R5 `ObservationDefinition.meta` |
| ObservationDefinition.method | ObservationDefinition.method | Equivalent | R4B `ObservationDefinition.method` maps as Equivalent to R5 `ObservationDefinition.method` |
| ObservationDefinition.modifierExtension | ObservationDefinition.modifierExtension | RelatedTo | R4B `ObservationDefinition.modifierExtension` maps as RelatedTo to R5 `ObservationDefinition.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ObservationDefinition.multipleResultsAllowed | ObservationDefinition.multipleResultsAllowed | Equivalent | R4B `ObservationDefinition.multipleResultsAllowed` maps as Equivalent to R5 `ObservationDefinition.multipleResultsAllowed` |
| ObservationDefinition.normalCodedValueSet | - | DoesNotExistInTarget | R4B `ObservationDefinition.normalCodedValueSet` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.permittedDataType | ObservationDefinition.permittedDataType | Equivalent | R4B `ObservationDefinition.permittedDataType` maps as Equivalent to R5 `ObservationDefinition.permittedDataType` - permittedDataType has compatible required binding for code type: http://hl7.org/fhir/ValueSet/permitted-data-type|4.3.0 and http://hl7.org/fhir/ValueSet/permitted-data-type|5.0.0 (Equivalent) |
| ObservationDefinition.preferredReportName | ObservationDefinition.preferredReportName | Equivalent | R4B `ObservationDefinition.preferredReportName` maps as Equivalent to R5 `ObservationDefinition.preferredReportName` |
| ObservationDefinition.qualifiedInterval | - | DoesNotExistInTarget | R4B `ObservationDefinition.qualifiedInterval` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.qualifiedInterval.age | - | DoesNotExistInTarget | R4B `ObservationDefinition.qualifiedInterval.age` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.qualifiedInterval.appliesTo | - | DoesNotExistInTarget | R4B `ObservationDefinition.qualifiedInterval.appliesTo` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.qualifiedInterval.category | - | DoesNotExistInTarget | R4B `ObservationDefinition.qualifiedInterval.category` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.qualifiedInterval.condition | - | DoesNotExistInTarget | R4B `ObservationDefinition.qualifiedInterval.condition` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.qualifiedInterval.context | - | DoesNotExistInTarget | R4B `ObservationDefinition.qualifiedInterval.context` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.qualifiedInterval.extension | - | DoesNotExistInTarget | R4B `ObservationDefinition.qualifiedInterval.extension` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.qualifiedInterval.gender | - | DoesNotExistInTarget | R4B `ObservationDefinition.qualifiedInterval.gender` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.qualifiedInterval.gestationalAge | - | DoesNotExistInTarget | R4B `ObservationDefinition.qualifiedInterval.gestationalAge` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.qualifiedInterval.id | - | DoesNotExistInTarget | R4B `ObservationDefinition.qualifiedInterval.id` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.qualifiedInterval.modifierExtension | - | DoesNotExistInTarget | R4B `ObservationDefinition.qualifiedInterval.modifierExtension` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.qualifiedInterval.range | - | DoesNotExistInTarget | R4B `ObservationDefinition.qualifiedInterval.range` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.quantitativeDetails | - | DoesNotExistInTarget | R4B `ObservationDefinition.quantitativeDetails` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.quantitativeDetails.conversionFactor | - | DoesNotExistInTarget | R4B `ObservationDefinition.quantitativeDetails.conversionFactor` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.quantitativeDetails.customaryUnit | - | DoesNotExistInTarget | R4B `ObservationDefinition.quantitativeDetails.customaryUnit` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.quantitativeDetails.decimalPrecision | - | DoesNotExistInTarget | R4B `ObservationDefinition.quantitativeDetails.decimalPrecision` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.quantitativeDetails.extension | - | DoesNotExistInTarget | R4B `ObservationDefinition.quantitativeDetails.extension` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.quantitativeDetails.id | - | DoesNotExistInTarget | R4B `ObservationDefinition.quantitativeDetails.id` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.quantitativeDetails.modifierExtension | - | DoesNotExistInTarget | R4B `ObservationDefinition.quantitativeDetails.modifierExtension` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.quantitativeDetails.unit | - | DoesNotExistInTarget | R4B `ObservationDefinition.quantitativeDetails.unit` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.text | ObservationDefinition.text | Equivalent | R4B `ObservationDefinition.text` maps as Equivalent to R5 `ObservationDefinition.text` |
| ObservationDefinition.validCodedValueSet | - | DoesNotExistInTarget | R4B `ObservationDefinition.validCodedValueSet` does not appear in the target and has no mapping for `ObservationDefinition`. |

