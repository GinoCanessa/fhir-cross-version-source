Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | ObservationDefinition |  | Set of definitional characteristics for a kind of observation or measurement produced or consumed by an orderable health care service. | 68 | 54 |
| Target | ObservationDefinition |  | Set of definitional characteristics for a kind of observation or measurement produced or consumed by an orderable health care service. | 40 | 26 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 40 |
Equivalent | 20 |
SourceIsBroaderThanTarget | 6 |
SourceIsNarrowerThanTarget | 2 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| ObservationDefinition | ObservationDefinition | Equivalent | R5 `ObservationDefinition` maps as Equivalent to R4 `ObservationDefinition` |
| ObservationDefinition.approvalDate | - | DoesNotExistInTarget | R5 `ObservationDefinition.approvalDate` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.bodySite | - | DoesNotExistInTarget | R5 `ObservationDefinition.bodySite` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.category | ObservationDefinition.category | Equivalent | R5 `ObservationDefinition.category` maps as Equivalent to R4 `ObservationDefinition.category` |
| ObservationDefinition.code | ObservationDefinition.code | Equivalent | R5 `ObservationDefinition.code` maps as Equivalent to R4 `ObservationDefinition.code` |
| ObservationDefinition.component | - | DoesNotExistInTarget | R5 `ObservationDefinition.component` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.component.code | - | DoesNotExistInTarget | R5 `ObservationDefinition.component.code` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.component.extension | - | DoesNotExistInTarget | R5 `ObservationDefinition.component.extension` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.component.id | - | DoesNotExistInTarget | R5 `ObservationDefinition.component.id` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.component.modifierExtension | - | DoesNotExistInTarget | R5 `ObservationDefinition.component.modifierExtension` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.component.permittedDataType | - | DoesNotExistInTarget | R5 `ObservationDefinition.component.permittedDataType` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.component.permittedUnit | - | DoesNotExistInTarget | R5 `ObservationDefinition.component.permittedUnit` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.component.qualifiedValue | - | DoesNotExistInTarget | R5 `ObservationDefinition.component.qualifiedValue` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.contact | - | DoesNotExistInTarget | R5 `ObservationDefinition.contact` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.contained | ObservationDefinition.contained | Equivalent | R5 `ObservationDefinition.contained` maps as Equivalent to R4 `ObservationDefinition.contained` |
| ObservationDefinition.copyright | - | DoesNotExistInTarget | R5 `ObservationDefinition.copyright` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.copyrightLabel | - | DoesNotExistInTarget | R5 `ObservationDefinition.copyrightLabel` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.date | - | DoesNotExistInTarget | R5 `ObservationDefinition.date` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.derivedFromCanonical | - | DoesNotExistInTarget | R5 `ObservationDefinition.derivedFromCanonical` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.derivedFromUri | - | DoesNotExistInTarget | R5 `ObservationDefinition.derivedFromUri` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.description | - | DoesNotExistInTarget | R5 `ObservationDefinition.description` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.device | - | DoesNotExistInTarget | R5 `ObservationDefinition.device` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.effectivePeriod | - | DoesNotExistInTarget | R5 `ObservationDefinition.effectivePeriod` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.experimental | - | DoesNotExistInTarget | R5 `ObservationDefinition.experimental` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.extension | ObservationDefinition.extension | SourceIsBroaderThanTarget | R5 `ObservationDefinition.extension` maps as SourceIsBroaderThanTarget to R4 `ObservationDefinition.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ObservationDefinition.hasMember | - | DoesNotExistInTarget | R5 `ObservationDefinition.hasMember` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.id | ObservationDefinition.id | Equivalent | R5 `ObservationDefinition.id` maps as Equivalent to R4 `ObservationDefinition.id` |
| ObservationDefinition.identifier | ObservationDefinition.identifier | SourceIsNarrowerThanTarget | R5 `ObservationDefinition.identifier` maps as SourceIsNarrowerThanTarget to R4 `ObservationDefinition.identifier` - identifier changed from scalar to array (max cardinality from 1 to *) |
| ObservationDefinition.implicitRules | ObservationDefinition.implicitRules | Equivalent | R5 `ObservationDefinition.implicitRules` maps as Equivalent to R4 `ObservationDefinition.implicitRules` |
| ObservationDefinition.jurisdiction | - | DoesNotExistInTarget | R5 `ObservationDefinition.jurisdiction` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.language | ObservationDefinition.language | SourceIsNarrowerThanTarget | R5 `ObservationDefinition.language` maps as SourceIsNarrowerThanTarget to R4 `ObservationDefinition.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| ObservationDefinition.lastReviewDate | - | DoesNotExistInTarget | R5 `ObservationDefinition.lastReviewDate` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.meta | ObservationDefinition.meta | Equivalent | R5 `ObservationDefinition.meta` maps as Equivalent to R4 `ObservationDefinition.meta` |
| ObservationDefinition.method | ObservationDefinition.method | Equivalent | R5 `ObservationDefinition.method` maps as Equivalent to R4 `ObservationDefinition.method` |
| ObservationDefinition.modifierExtension | ObservationDefinition.modifierExtension | SourceIsBroaderThanTarget | R5 `ObservationDefinition.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ObservationDefinition.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ObservationDefinition.multipleResultsAllowed | ObservationDefinition.multipleResultsAllowed | Equivalent | R5 `ObservationDefinition.multipleResultsAllowed` maps as Equivalent to R4 `ObservationDefinition.multipleResultsAllowed` |
| ObservationDefinition.name | - | DoesNotExistInTarget | R5 `ObservationDefinition.name` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.performerType | - | DoesNotExistInTarget | R5 `ObservationDefinition.performerType` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.permittedDataType | ObservationDefinition.permittedDataType | Equivalent | R5 `ObservationDefinition.permittedDataType` maps as Equivalent to R4 `ObservationDefinition.permittedDataType` - permittedDataType has compatible required binding for code type: http://hl7.org/fhir/ValueSet/permitted-data-type|5.0.0 and http://hl7.org/fhir/ValueSet/permitted-data-type|4.0.1 (Equivalent) |
| ObservationDefinition.permittedUnit | - | DoesNotExistInTarget | R5 `ObservationDefinition.permittedUnit` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.preferredReportName | ObservationDefinition.preferredReportName | Equivalent | R5 `ObservationDefinition.preferredReportName` maps as Equivalent to R4 `ObservationDefinition.preferredReportName` |
| ObservationDefinition.publisher | - | DoesNotExistInTarget | R5 `ObservationDefinition.publisher` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.purpose | - | DoesNotExistInTarget | R5 `ObservationDefinition.purpose` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.qualifiedValue | - | DoesNotExistInTarget | R5 `ObservationDefinition.qualifiedValue` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.qualifiedValue.abnormalCodedValueSet | ObservationDefinition.abnormalCodedValueSet | SourceIsBroaderThanTarget | R5 `ObservationDefinition.qualifiedValue.abnormalCodedValueSet` maps as SourceIsBroaderThanTarget to R4 `ObservationDefinition.abnormalCodedValueSet` - abnormalCodedValueSet has change due to type change: R5 abnormalCodedValueSet canonical has no equivalent or mapped type in R4 abnormalCodedValueSet |
| ObservationDefinition.qualifiedValue.age | ObservationDefinition.qualifiedInterval.age | Equivalent | R5 `ObservationDefinition.qualifiedValue.age` maps as Equivalent to R4 `ObservationDefinition.qualifiedInterval.age` |
| ObservationDefinition.qualifiedValue.appliesTo | ObservationDefinition.qualifiedInterval.appliesTo | Equivalent | R5 `ObservationDefinition.qualifiedValue.appliesTo` maps as Equivalent to R4 `ObservationDefinition.qualifiedInterval.appliesTo` |
| ObservationDefinition.qualifiedValue.condition | ObservationDefinition.qualifiedInterval.condition | Equivalent | R5 `ObservationDefinition.qualifiedValue.condition` maps as Equivalent to R4 `ObservationDefinition.qualifiedInterval.condition` |
| ObservationDefinition.qualifiedValue.context | ObservationDefinition.qualifiedInterval.context | Equivalent | R5 `ObservationDefinition.qualifiedValue.context` maps as Equivalent to R4 `ObservationDefinition.qualifiedInterval.context` |
| ObservationDefinition.qualifiedValue.criticalCodedValueSet | ObservationDefinition.criticalCodedValueSet | SourceIsBroaderThanTarget | R5 `ObservationDefinition.qualifiedValue.criticalCodedValueSet` maps as SourceIsBroaderThanTarget to R4 `ObservationDefinition.criticalCodedValueSet` - criticalCodedValueSet has change due to type change: R5 criticalCodedValueSet canonical has no equivalent or mapped type in R4 criticalCodedValueSet |
| ObservationDefinition.qualifiedValue.extension | - | DoesNotExistInTarget | R5 `ObservationDefinition.qualifiedValue.extension` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.qualifiedValue.gender | ObservationDefinition.qualifiedInterval.gender | Equivalent | R5 `ObservationDefinition.qualifiedValue.gender` maps as Equivalent to R4 `ObservationDefinition.qualifiedInterval.gender` - gender has compatible required binding for code type: http://hl7.org/fhir/ValueSet/administrative-gender|5.0.0 and http://hl7.org/fhir/ValueSet/administrative-gender|4.0.1 (Equivalent) |
| ObservationDefinition.qualifiedValue.gestationalAge | ObservationDefinition.qualifiedInterval.gestationalAge | Equivalent | R5 `ObservationDefinition.qualifiedValue.gestationalAge` maps as Equivalent to R4 `ObservationDefinition.qualifiedInterval.gestationalAge` |
| ObservationDefinition.qualifiedValue.id | - | DoesNotExistInTarget | R5 `ObservationDefinition.qualifiedValue.id` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.qualifiedValue.modifierExtension | - | DoesNotExistInTarget | R5 `ObservationDefinition.qualifiedValue.modifierExtension` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.qualifiedValue.normalCodedValueSet | ObservationDefinition.normalCodedValueSet | SourceIsBroaderThanTarget | R5 `ObservationDefinition.qualifiedValue.normalCodedValueSet` maps as SourceIsBroaderThanTarget to R4 `ObservationDefinition.normalCodedValueSet` - normalCodedValueSet has change due to type change: R5 normalCodedValueSet canonical has no equivalent or mapped type in R4 normalCodedValueSet |
| ObservationDefinition.qualifiedValue.range | ObservationDefinition.qualifiedInterval.range | Equivalent | R5 `ObservationDefinition.qualifiedValue.range` maps as Equivalent to R4 `ObservationDefinition.qualifiedInterval.range` |
| ObservationDefinition.qualifiedValue.rangeCategory | ObservationDefinition.qualifiedInterval.category | Equivalent | R5 `ObservationDefinition.qualifiedValue.rangeCategory` maps as Equivalent to R4 `ObservationDefinition.qualifiedInterval.category` - category has compatible required binding for code type: http://hl7.org/fhir/ValueSet/observation-range-category|5.0.0 and http://hl7.org/fhir/ValueSet/observation-range-category|4.0.1 (Equivalent) |
| ObservationDefinition.qualifiedValue.validCodedValueSet | ObservationDefinition.validCodedValueSet | SourceIsBroaderThanTarget | R5 `ObservationDefinition.qualifiedValue.validCodedValueSet` maps as SourceIsBroaderThanTarget to R4 `ObservationDefinition.validCodedValueSet` - validCodedValueSet has change due to type change: R5 validCodedValueSet canonical has no equivalent or mapped type in R4 validCodedValueSet |
| ObservationDefinition.specimen | - | DoesNotExistInTarget | R5 `ObservationDefinition.specimen` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.status | - | DoesNotExistInTarget | R5 `ObservationDefinition.status` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.subject | - | DoesNotExistInTarget | R5 `ObservationDefinition.subject` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.text | ObservationDefinition.text | Equivalent | R5 `ObservationDefinition.text` maps as Equivalent to R4 `ObservationDefinition.text` |
| ObservationDefinition.title | - | DoesNotExistInTarget | R5 `ObservationDefinition.title` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.url | - | DoesNotExistInTarget | R5 `ObservationDefinition.url` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.useContext | - | DoesNotExistInTarget | R5 `ObservationDefinition.useContext` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.version | - | DoesNotExistInTarget | R5 `ObservationDefinition.version` does not appear in the target and has no mapping for `ObservationDefinition`. |
| ObservationDefinition.versionAlgorithm[x] | - | DoesNotExistInTarget | R5 `ObservationDefinition.versionAlgorithm[x]` does not appear in the target and has no mapping for `ObservationDefinition`. |

