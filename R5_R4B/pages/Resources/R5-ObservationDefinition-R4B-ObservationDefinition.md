Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | ObservationDefinition |  | Set of definitional characteristics for a kind of observation or measurement produced or consumed by an orderable health care service. | 68 | 54 |
| Target | ObservationDefinition |  | Set of definitional characteristics for a kind of observation or measurement produced or consumed by an orderable health care service. | 40 | 26 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 52 |
Equivalent | 4 |
RelatedTo | 12 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| ObservationDefinition | ObservationDefinition | Equivalent | R5 `ObservationDefinition` maps as Equivalent to R4B `ObservationDefinition` |
| ObservationDefinition.approvalDate | - | DoesNotExistInTarget | R5 `ObservationDefinition.approvalDate` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.bodySite | - | DoesNotExistInTarget | R5 `ObservationDefinition.bodySite` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.category | ObservationDefinition.category | Equivalent | R5 `ObservationDefinition.category` maps as Equivalent to R4B `ObservationDefinition.category` |
| ObservationDefinition.code | ObservationDefinition.code | Equivalent | R5 `ObservationDefinition.code` maps as Equivalent to R4B `ObservationDefinition.code` |
| ObservationDefinition.component | - | DoesNotExistInTarget | R5 `ObservationDefinition.component` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.component.code | - | DoesNotExistInTarget | R5 `ObservationDefinition.component.code` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.component.extension | - | DoesNotExistInTarget | R5 `ObservationDefinition.component.extension` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.component.id | - | DoesNotExistInTarget | R5 `ObservationDefinition.component.id` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.component.modifierExtension | - | DoesNotExistInTarget | R5 `ObservationDefinition.component.modifierExtension` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.component.permittedDataType | - | DoesNotExistInTarget | R5 `ObservationDefinition.component.permittedDataType` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.component.permittedUnit | - | DoesNotExistInTarget | R5 `ObservationDefinition.component.permittedUnit` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.component.qualifiedValue | - | DoesNotExistInTarget | R5 `ObservationDefinition.component.qualifiedValue` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.contact | - | DoesNotExistInTarget | R5 `ObservationDefinition.contact` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.contained | ObservationDefinition.contained | Equivalent | R5 `ObservationDefinition.contained` maps as Equivalent to R4B `ObservationDefinition.contained` |
| ObservationDefinition.copyright | - | DoesNotExistInTarget | R5 `ObservationDefinition.copyright` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.copyrightLabel | - | DoesNotExistInTarget | R5 `ObservationDefinition.copyrightLabel` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.date | - | DoesNotExistInTarget | R5 `ObservationDefinition.date` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.derivedFromCanonical | - | DoesNotExistInTarget | R5 `ObservationDefinition.derivedFromCanonical` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.derivedFromUri | - | DoesNotExistInTarget | R5 `ObservationDefinition.derivedFromUri` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.description | - | DoesNotExistInTarget | R5 `ObservationDefinition.description` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.device | - | DoesNotExistInTarget | R5 `ObservationDefinition.device` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.effectivePeriod | - | DoesNotExistInTarget | R5 `ObservationDefinition.effectivePeriod` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.experimental | - | DoesNotExistInTarget | R5 `ObservationDefinition.experimental` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.extension | ObservationDefinition.extension | SourceIsBroaderThanTarget | R5 `ObservationDefinition.extension` maps as SourceIsBroaderThanTarget to R4B `ObservationDefinition.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| ObservationDefinition.hasMember | - | DoesNotExistInTarget | R5 `ObservationDefinition.hasMember` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.id | ObservationDefinition.id | Equivalent | R5 `ObservationDefinition.id` maps as Equivalent to R4B `ObservationDefinition.id` |
| ObservationDefinition.identifier | ObservationDefinition.identifier | RelatedTo | R5 `ObservationDefinition.identifier` maps as RelatedTo to R4B `ObservationDefinition.identifier` - identifier changed from scalar to array (max cardinality from 1 to *) |
| ObservationDefinition.implicitRules | ObservationDefinition.implicitRules | Equivalent | R5 `ObservationDefinition.implicitRules` maps as Equivalent to R4B `ObservationDefinition.implicitRules` |
| ObservationDefinition.jurisdiction | - | DoesNotExistInTarget | R5 `ObservationDefinition.jurisdiction` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.language | ObservationDefinition.language | RelatedTo | R5 `ObservationDefinition.language` maps as RelatedTo to R4B `ObservationDefinition.language` - language changed the binding strength from Required to Preferred |
| ObservationDefinition.lastReviewDate | - | DoesNotExistInTarget | R5 `ObservationDefinition.lastReviewDate` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.meta | ObservationDefinition.meta | Equivalent | R5 `ObservationDefinition.meta` maps as Equivalent to R4B `ObservationDefinition.meta` |
| ObservationDefinition.method | ObservationDefinition.method | Equivalent | R5 `ObservationDefinition.method` maps as Equivalent to R4B `ObservationDefinition.method` |
| ObservationDefinition.modifierExtension | ObservationDefinition.modifierExtension | SourceIsBroaderThanTarget | R5 `ObservationDefinition.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `ObservationDefinition.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| ObservationDefinition.multipleResultsAllowed | ObservationDefinition.multipleResultsAllowed | Equivalent | R5 `ObservationDefinition.multipleResultsAllowed` maps as Equivalent to R4B `ObservationDefinition.multipleResultsAllowed` |
| ObservationDefinition.name | - | DoesNotExistInTarget | R5 `ObservationDefinition.name` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.performerType | - | DoesNotExistInTarget | R5 `ObservationDefinition.performerType` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.permittedDataType | ObservationDefinition.permittedDataType | Equivalent | R5 `ObservationDefinition.permittedDataType` maps as Equivalent to R4B `ObservationDefinition.permittedDataType` - permittedDataType has compatible required binding for code type: http://hl7.org/fhir/ValueSet/permitted-data-type|5.0.0 and http://hl7.org/fhir/ValueSet/permitted-data-type|4.3.0 (Equivalent) |
| ObservationDefinition.permittedUnit | - | DoesNotExistInTarget | R5 `ObservationDefinition.permittedUnit` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.preferredReportName | ObservationDefinition.preferredReportName | Equivalent | R5 `ObservationDefinition.preferredReportName` maps as Equivalent to R4B `ObservationDefinition.preferredReportName` |
| ObservationDefinition.publisher | - | DoesNotExistInTarget | R5 `ObservationDefinition.publisher` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.purpose | - | DoesNotExistInTarget | R5 `ObservationDefinition.purpose` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.qualifiedValue | - | DoesNotExistInTarget | R5 `ObservationDefinition.qualifiedValue` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.qualifiedValue.abnormalCodedValueSet | - | DoesNotExistInTarget | R5 `ObservationDefinition.qualifiedValue.abnormalCodedValueSet` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.qualifiedValue.age | - | DoesNotExistInTarget | R5 `ObservationDefinition.qualifiedValue.age` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.qualifiedValue.appliesTo | - | DoesNotExistInTarget | R5 `ObservationDefinition.qualifiedValue.appliesTo` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.qualifiedValue.condition | - | DoesNotExistInTarget | R5 `ObservationDefinition.qualifiedValue.condition` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.qualifiedValue.context | - | DoesNotExistInTarget | R5 `ObservationDefinition.qualifiedValue.context` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.qualifiedValue.criticalCodedValueSet | - | DoesNotExistInTarget | R5 `ObservationDefinition.qualifiedValue.criticalCodedValueSet` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.qualifiedValue.extension | - | DoesNotExistInTarget | R5 `ObservationDefinition.qualifiedValue.extension` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.qualifiedValue.gender | - | DoesNotExistInTarget | R5 `ObservationDefinition.qualifiedValue.gender` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.qualifiedValue.gestationalAge | - | DoesNotExistInTarget | R5 `ObservationDefinition.qualifiedValue.gestationalAge` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.qualifiedValue.id | - | DoesNotExistInTarget | R5 `ObservationDefinition.qualifiedValue.id` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.qualifiedValue.modifierExtension | - | DoesNotExistInTarget | R5 `ObservationDefinition.qualifiedValue.modifierExtension` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.qualifiedValue.normalCodedValueSet | - | DoesNotExistInTarget | R5 `ObservationDefinition.qualifiedValue.normalCodedValueSet` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.qualifiedValue.range | - | DoesNotExistInTarget | R5 `ObservationDefinition.qualifiedValue.range` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.qualifiedValue.rangeCategory | - | DoesNotExistInTarget | R5 `ObservationDefinition.qualifiedValue.rangeCategory` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.qualifiedValue.validCodedValueSet | - | DoesNotExistInTarget | R5 `ObservationDefinition.qualifiedValue.validCodedValueSet` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.specimen | - | DoesNotExistInTarget | R5 `ObservationDefinition.specimen` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.status | - | DoesNotExistInTarget | R5 `ObservationDefinition.status` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.subject | - | DoesNotExistInTarget | R5 `ObservationDefinition.subject` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.text | ObservationDefinition.text | Equivalent | R5 `ObservationDefinition.text` maps as Equivalent to R4B `ObservationDefinition.text` |
| ObservationDefinition.title | - | DoesNotExistInTarget | R5 `ObservationDefinition.title` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.url | - | DoesNotExistInTarget | R5 `ObservationDefinition.url` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.useContext | - | DoesNotExistInTarget | R5 `ObservationDefinition.useContext` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.version | - | DoesNotExistInTarget | R5 `ObservationDefinition.version` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.versionAlgorithm[x] | - | DoesNotExistInTarget | R5 `ObservationDefinition.versionAlgorithm[x]` does not appear in the target and has no mapping for `ObservationDefinition`. |

