Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1
Generated at Thursday, July 25, 2024 3:56:51 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | ValueSet |  | A ValueSet resource instance specifies a set of codes drawn from one or more code systems, intended for use in a particular context. Value sets link between [[[CodeSystem]]] definitions and their use in [coded elements](terminologies.html). | 124 | 80 |
| Target | ValueSet |  | A ValueSet resource instance specifies a set of codes drawn from one or more code systems, intended for use in a particular context. Value sets link between [[[CodeSystem]]] definitions and their use in [coded elements](terminologies.html). | 85 | 53 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 39 |
Equivalent | 4 |
RelatedTo | 81 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| ValueSet | ValueSet | Equivalent | R5 `ValueSet` maps as Equivalent to R4 `ValueSet` |
| ValueSet.approvalDate | - | DoesNotExistInTarget | R5 `ValueSet.approvalDate` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.author | - | DoesNotExistInTarget | R5 `ValueSet.author` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.compose | ValueSet.compose | Equivalent | R5 `ValueSet.compose` maps as Equivalent to R4 `ValueSet.compose` |
| ValueSet.compose.exclude | ValueSet.compose.exclude | Equivalent | R5 `ValueSet.compose.exclude` maps as Equivalent to R4 `ValueSet.compose.exclude` |
| ValueSet.compose.extension | ValueSet.compose.extension | SourceIsBroaderThanTarget | R5 `ValueSet.compose.extension` maps as SourceIsBroaderThanTarget to R4 `ValueSet.compose.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ValueSet.compose.id | ValueSet.compose.id | Equivalent | R5 `ValueSet.compose.id` maps as Equivalent to R4 `ValueSet.compose.id` |
| ValueSet.compose.inactive | ValueSet.compose.inactive | Equivalent | R5 `ValueSet.compose.inactive` maps as Equivalent to R4 `ValueSet.compose.inactive` |
| ValueSet.compose.include | ValueSet.compose.include | Equivalent | R5 `ValueSet.compose.include` maps as Equivalent to R4 `ValueSet.compose.include` |
| ValueSet.compose.include.concept | ValueSet.compose.include.concept | Equivalent | R5 `ValueSet.compose.include.concept` maps as Equivalent to R4 `ValueSet.compose.include.concept` |
| ValueSet.compose.include.concept.code | ValueSet.compose.include.concept.code | Equivalent | R5 `ValueSet.compose.include.concept.code` maps as Equivalent to R4 `ValueSet.compose.include.concept.code` |
| ValueSet.compose.include.concept.designation | ValueSet.compose.include.concept.designation | Equivalent | R5 `ValueSet.compose.include.concept.designation` maps as Equivalent to R4 `ValueSet.compose.include.concept.designation` |
| ValueSet.compose.include.concept.designation.additionalUse | - | DoesNotExistInTarget | R5 `ValueSet.compose.include.concept.designation.additionalUse` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.compose.include.concept.designation.extension | ValueSet.compose.include.concept.designation.extension | SourceIsBroaderThanTarget | R5 `ValueSet.compose.include.concept.designation.extension` maps as SourceIsBroaderThanTarget to R4 `ValueSet.compose.include.concept.designation.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ValueSet.compose.include.concept.designation.id | ValueSet.compose.include.concept.designation.id | Equivalent | R5 `ValueSet.compose.include.concept.designation.id` maps as Equivalent to R4 `ValueSet.compose.include.concept.designation.id` |
| ValueSet.compose.include.concept.designation.language | ValueSet.compose.include.concept.designation.language | RelatedTo | R5 `ValueSet.compose.include.concept.designation.language` maps as RelatedTo to R4 `ValueSet.compose.include.concept.designation.language` - language changed the binding strength from Required to Preferred |
| ValueSet.compose.include.concept.designation.modifierExtension | ValueSet.compose.include.concept.designation.modifierExtension | SourceIsBroaderThanTarget | R5 `ValueSet.compose.include.concept.designation.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ValueSet.compose.include.concept.designation.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ValueSet.compose.include.concept.designation.use | ValueSet.compose.include.concept.designation.use | Equivalent | R5 `ValueSet.compose.include.concept.designation.use` maps as Equivalent to R4 `ValueSet.compose.include.concept.designation.use` |
| ValueSet.compose.include.concept.designation.value | ValueSet.compose.include.concept.designation.value | Equivalent | R5 `ValueSet.compose.include.concept.designation.value` maps as Equivalent to R4 `ValueSet.compose.include.concept.designation.value` |
| ValueSet.compose.include.concept.display | ValueSet.compose.include.concept.display | Equivalent | R5 `ValueSet.compose.include.concept.display` maps as Equivalent to R4 `ValueSet.compose.include.concept.display` |
| ValueSet.compose.include.concept.extension | ValueSet.compose.include.concept.extension | SourceIsBroaderThanTarget | R5 `ValueSet.compose.include.concept.extension` maps as SourceIsBroaderThanTarget to R4 `ValueSet.compose.include.concept.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ValueSet.compose.include.concept.id | ValueSet.compose.include.concept.id | Equivalent | R5 `ValueSet.compose.include.concept.id` maps as Equivalent to R4 `ValueSet.compose.include.concept.id` |
| ValueSet.compose.include.concept.modifierExtension | ValueSet.compose.include.concept.modifierExtension | SourceIsBroaderThanTarget | R5 `ValueSet.compose.include.concept.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ValueSet.compose.include.concept.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ValueSet.compose.include.copyright | - | DoesNotExistInTarget | R5 `ValueSet.compose.include.copyright` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.compose.include.extension | ValueSet.compose.include.extension | SourceIsBroaderThanTarget | R5 `ValueSet.compose.include.extension` maps as SourceIsBroaderThanTarget to R4 `ValueSet.compose.include.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ValueSet.compose.include.filter | ValueSet.compose.include.filter | Equivalent | R5 `ValueSet.compose.include.filter` maps as Equivalent to R4 `ValueSet.compose.include.filter` |
| ValueSet.compose.include.filter.extension | ValueSet.compose.include.filter.extension | SourceIsBroaderThanTarget | R5 `ValueSet.compose.include.filter.extension` maps as SourceIsBroaderThanTarget to R4 `ValueSet.compose.include.filter.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ValueSet.compose.include.filter.id | ValueSet.compose.include.filter.id | Equivalent | R5 `ValueSet.compose.include.filter.id` maps as Equivalent to R4 `ValueSet.compose.include.filter.id` |
| ValueSet.compose.include.filter.modifierExtension | ValueSet.compose.include.filter.modifierExtension | SourceIsBroaderThanTarget | R5 `ValueSet.compose.include.filter.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ValueSet.compose.include.filter.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ValueSet.compose.include.filter.op | ValueSet.compose.include.filter.op | Equivalent | R5 `ValueSet.compose.include.filter.op` maps as Equivalent to R4 `ValueSet.compose.include.filter.op` - op has compatible required binding for code type: http://hl7.org/fhir/ValueSet/filter-operator|5.0.0 and http://hl7.org/fhir/ValueSet/filter-operator|4.0.1 (Equivalent) |
| ValueSet.compose.include.filter.property | ValueSet.compose.include.filter.property | Equivalent | R5 `ValueSet.compose.include.filter.property` maps as Equivalent to R4 `ValueSet.compose.include.filter.property` |
| ValueSet.compose.include.filter.value | ValueSet.compose.include.filter.value | Equivalent | R5 `ValueSet.compose.include.filter.value` maps as Equivalent to R4 `ValueSet.compose.include.filter.value` |
| ValueSet.compose.include.id | ValueSet.compose.include.id | Equivalent | R5 `ValueSet.compose.include.id` maps as Equivalent to R4 `ValueSet.compose.include.id` |
| ValueSet.compose.include.modifierExtension | ValueSet.compose.include.modifierExtension | SourceIsBroaderThanTarget | R5 `ValueSet.compose.include.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ValueSet.compose.include.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ValueSet.compose.include.system | ValueSet.compose.include.system | Equivalent | R5 `ValueSet.compose.include.system` maps as Equivalent to R4 `ValueSet.compose.include.system` |
| ValueSet.compose.include.valueSet | ValueSet.compose.include.valueSet | Equivalent | R5 `ValueSet.compose.include.valueSet` maps as Equivalent to R4 `ValueSet.compose.include.valueSet` |
| ValueSet.compose.include.version | ValueSet.compose.include.version | Equivalent | R5 `ValueSet.compose.include.version` maps as Equivalent to R4 `ValueSet.compose.include.version` |
| ValueSet.compose.lockedDate | ValueSet.compose.lockedDate | Equivalent | R5 `ValueSet.compose.lockedDate` maps as Equivalent to R4 `ValueSet.compose.lockedDate` |
| ValueSet.compose.modifierExtension | ValueSet.compose.modifierExtension | SourceIsBroaderThanTarget | R5 `ValueSet.compose.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ValueSet.compose.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ValueSet.compose.property | - | DoesNotExistInTarget | R5 `ValueSet.compose.property` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.contact | ValueSet.contact | Equivalent | R5 `ValueSet.contact` maps as Equivalent to R4 `ValueSet.contact` |
| ValueSet.contained | ValueSet.contained | Equivalent | R5 `ValueSet.contained` maps as Equivalent to R4 `ValueSet.contained` |
| ValueSet.copyright | ValueSet.copyright | Equivalent | R5 `ValueSet.copyright` maps as Equivalent to R4 `ValueSet.copyright` |
| ValueSet.copyrightLabel | - | DoesNotExistInTarget | R5 `ValueSet.copyrightLabel` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.date | ValueSet.date | Equivalent | R5 `ValueSet.date` maps as Equivalent to R4 `ValueSet.date` |
| ValueSet.description | ValueSet.description | Equivalent | R5 `ValueSet.description` maps as Equivalent to R4 `ValueSet.description` |
| ValueSet.editor | - | DoesNotExistInTarget | R5 `ValueSet.editor` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.effectivePeriod | - | DoesNotExistInTarget | R5 `ValueSet.effectivePeriod` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.endorser | - | DoesNotExistInTarget | R5 `ValueSet.endorser` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.expansion | ValueSet.expansion | Equivalent | R5 `ValueSet.expansion` maps as Equivalent to R4 `ValueSet.expansion` |
| ValueSet.expansion.contains | ValueSet.expansion.contains | Equivalent | R5 `ValueSet.expansion.contains` maps as Equivalent to R4 `ValueSet.expansion.contains` |
| ValueSet.expansion.contains.abstract | ValueSet.expansion.contains.abstract | Equivalent | R5 `ValueSet.expansion.contains.abstract` maps as Equivalent to R4 `ValueSet.expansion.contains.abstract` |
| ValueSet.expansion.contains.code | ValueSet.expansion.contains.code | Equivalent | R5 `ValueSet.expansion.contains.code` maps as Equivalent to R4 `ValueSet.expansion.contains.code` |
| ValueSet.expansion.contains.contains | ValueSet.expansion.contains.contains | Equivalent | R5 `ValueSet.expansion.contains.contains` maps as Equivalent to R4 `ValueSet.expansion.contains.contains` |
| ValueSet.expansion.contains.designation | ValueSet.expansion.contains.designation | Equivalent | R5 `ValueSet.expansion.contains.designation` maps as Equivalent to R4 `ValueSet.expansion.contains.designation` |
| ValueSet.expansion.contains.display | ValueSet.expansion.contains.display | Equivalent | R5 `ValueSet.expansion.contains.display` maps as Equivalent to R4 `ValueSet.expansion.contains.display` |
| ValueSet.expansion.contains.extension | ValueSet.expansion.contains.extension | SourceIsBroaderThanTarget | R5 `ValueSet.expansion.contains.extension` maps as SourceIsBroaderThanTarget to R4 `ValueSet.expansion.contains.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ValueSet.expansion.contains.id | ValueSet.expansion.contains.id | Equivalent | R5 `ValueSet.expansion.contains.id` maps as Equivalent to R4 `ValueSet.expansion.contains.id` |
| ValueSet.expansion.contains.inactive | ValueSet.expansion.contains.inactive | Equivalent | R5 `ValueSet.expansion.contains.inactive` maps as Equivalent to R4 `ValueSet.expansion.contains.inactive` |
| ValueSet.expansion.contains.modifierExtension | ValueSet.expansion.contains.modifierExtension | SourceIsBroaderThanTarget | R5 `ValueSet.expansion.contains.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ValueSet.expansion.contains.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ValueSet.expansion.contains.property | - | DoesNotExistInTarget | R5 `ValueSet.expansion.contains.property` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.expansion.contains.property.code | - | DoesNotExistInTarget | R5 `ValueSet.expansion.contains.property.code` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.expansion.contains.property.extension | - | DoesNotExistInTarget | R5 `ValueSet.expansion.contains.property.extension` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.expansion.contains.property.id | - | DoesNotExistInTarget | R5 `ValueSet.expansion.contains.property.id` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.expansion.contains.property.modifierExtension | - | DoesNotExistInTarget | R5 `ValueSet.expansion.contains.property.modifierExtension` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.expansion.contains.property.subProperty | - | DoesNotExistInTarget | R5 `ValueSet.expansion.contains.property.subProperty` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.expansion.contains.property.subProperty.code | - | DoesNotExistInTarget | R5 `ValueSet.expansion.contains.property.subProperty.code` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.expansion.contains.property.subProperty.extension | - | DoesNotExistInTarget | R5 `ValueSet.expansion.contains.property.subProperty.extension` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.expansion.contains.property.subProperty.id | - | DoesNotExistInTarget | R5 `ValueSet.expansion.contains.property.subProperty.id` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.expansion.contains.property.subProperty.modifierExtension | - | DoesNotExistInTarget | R5 `ValueSet.expansion.contains.property.subProperty.modifierExtension` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.expansion.contains.property.subProperty.value[x] | - | DoesNotExistInTarget | R5 `ValueSet.expansion.contains.property.subProperty.value[x]` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.expansion.contains.property.value[x] | - | DoesNotExistInTarget | R5 `ValueSet.expansion.contains.property.value[x]` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.expansion.contains.system | ValueSet.expansion.contains.system | Equivalent | R5 `ValueSet.expansion.contains.system` maps as Equivalent to R4 `ValueSet.expansion.contains.system` |
| ValueSet.expansion.contains.version | ValueSet.expansion.contains.version | Equivalent | R5 `ValueSet.expansion.contains.version` maps as Equivalent to R4 `ValueSet.expansion.contains.version` |
| ValueSet.expansion.extension | ValueSet.expansion.extension | SourceIsBroaderThanTarget | R5 `ValueSet.expansion.extension` maps as SourceIsBroaderThanTarget to R4 `ValueSet.expansion.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ValueSet.expansion.id | ValueSet.expansion.id | Equivalent | R5 `ValueSet.expansion.id` maps as Equivalent to R4 `ValueSet.expansion.id` |
| ValueSet.expansion.identifier | ValueSet.expansion.identifier | Equivalent | R5 `ValueSet.expansion.identifier` maps as Equivalent to R4 `ValueSet.expansion.identifier` |
| ValueSet.expansion.modifierExtension | ValueSet.expansion.modifierExtension | SourceIsBroaderThanTarget | R5 `ValueSet.expansion.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ValueSet.expansion.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ValueSet.expansion.next | - | DoesNotExistInTarget | R5 `ValueSet.expansion.next` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.expansion.offset | ValueSet.expansion.offset | Equivalent | R5 `ValueSet.expansion.offset` maps as Equivalent to R4 `ValueSet.expansion.offset` |
| ValueSet.expansion.parameter | ValueSet.expansion.parameter | Equivalent | R5 `ValueSet.expansion.parameter` maps as Equivalent to R4 `ValueSet.expansion.parameter` |
| ValueSet.expansion.parameter.extension | ValueSet.expansion.parameter.extension | SourceIsBroaderThanTarget | R5 `ValueSet.expansion.parameter.extension` maps as SourceIsBroaderThanTarget to R4 `ValueSet.expansion.parameter.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ValueSet.expansion.parameter.id | ValueSet.expansion.parameter.id | Equivalent | R5 `ValueSet.expansion.parameter.id` maps as Equivalent to R4 `ValueSet.expansion.parameter.id` |
| ValueSet.expansion.parameter.modifierExtension | ValueSet.expansion.parameter.modifierExtension | SourceIsBroaderThanTarget | R5 `ValueSet.expansion.parameter.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ValueSet.expansion.parameter.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ValueSet.expansion.parameter.name | ValueSet.expansion.parameter.name | Equivalent | R5 `ValueSet.expansion.parameter.name` maps as Equivalent to R4 `ValueSet.expansion.parameter.name` |
| ValueSet.expansion.parameter.value[x] | ValueSet.expansion.parameter.value[x] | Equivalent | R5 `ValueSet.expansion.parameter.value[x]` maps as Equivalent to R4 `ValueSet.expansion.parameter.value[x]` |
| ValueSet.expansion.property | - | DoesNotExistInTarget | R5 `ValueSet.expansion.property` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.expansion.property.code | - | DoesNotExistInTarget | R5 `ValueSet.expansion.property.code` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.expansion.property.extension | - | DoesNotExistInTarget | R5 `ValueSet.expansion.property.extension` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.expansion.property.id | - | DoesNotExistInTarget | R5 `ValueSet.expansion.property.id` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.expansion.property.modifierExtension | - | DoesNotExistInTarget | R5 `ValueSet.expansion.property.modifierExtension` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.expansion.property.uri | - | DoesNotExistInTarget | R5 `ValueSet.expansion.property.uri` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.expansion.timestamp | ValueSet.expansion.timestamp | Equivalent | R5 `ValueSet.expansion.timestamp` maps as Equivalent to R4 `ValueSet.expansion.timestamp` |
| ValueSet.expansion.total | ValueSet.expansion.total | Equivalent | R5 `ValueSet.expansion.total` maps as Equivalent to R4 `ValueSet.expansion.total` |
| ValueSet.experimental | ValueSet.experimental | Equivalent | R5 `ValueSet.experimental` maps as Equivalent to R4 `ValueSet.experimental` |
| ValueSet.extension | ValueSet.extension | SourceIsBroaderThanTarget | R5 `ValueSet.extension` maps as SourceIsBroaderThanTarget to R4 `ValueSet.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ValueSet.id | ValueSet.id | Equivalent | R5 `ValueSet.id` maps as Equivalent to R4 `ValueSet.id` |
| ValueSet.identifier | ValueSet.identifier | Equivalent | R5 `ValueSet.identifier` maps as Equivalent to R4 `ValueSet.identifier` |
| ValueSet.immutable | ValueSet.immutable | Equivalent | R5 `ValueSet.immutable` maps as Equivalent to R4 `ValueSet.immutable` |
| ValueSet.implicitRules | ValueSet.implicitRules | Equivalent | R5 `ValueSet.implicitRules` maps as Equivalent to R4 `ValueSet.implicitRules` |
| ValueSet.jurisdiction | ValueSet.jurisdiction | Equivalent | R5 `ValueSet.jurisdiction` maps as Equivalent to R4 `ValueSet.jurisdiction` |
| ValueSet.language | ValueSet.language | RelatedTo | R5 `ValueSet.language` maps as RelatedTo to R4 `ValueSet.language` - language changed the binding strength from Required to Preferred |
| ValueSet.lastReviewDate | - | DoesNotExistInTarget | R5 `ValueSet.lastReviewDate` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.meta | ValueSet.meta | Equivalent | R5 `ValueSet.meta` maps as Equivalent to R4 `ValueSet.meta` |
| ValueSet.modifierExtension | ValueSet.modifierExtension | SourceIsBroaderThanTarget | R5 `ValueSet.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ValueSet.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ValueSet.name | ValueSet.name | Equivalent | R5 `ValueSet.name` maps as Equivalent to R4 `ValueSet.name` |
| ValueSet.publisher | ValueSet.publisher | Equivalent | R5 `ValueSet.publisher` maps as Equivalent to R4 `ValueSet.publisher` |
| ValueSet.purpose | ValueSet.purpose | Equivalent | R5 `ValueSet.purpose` maps as Equivalent to R4 `ValueSet.purpose` |
| ValueSet.relatedArtifact | - | DoesNotExistInTarget | R5 `ValueSet.relatedArtifact` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.reviewer | - | DoesNotExistInTarget | R5 `ValueSet.reviewer` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.scope | - | DoesNotExistInTarget | R5 `ValueSet.scope` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.scope.exclusionCriteria | - | DoesNotExistInTarget | R5 `ValueSet.scope.exclusionCriteria` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.scope.extension | - | DoesNotExistInTarget | R5 `ValueSet.scope.extension` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.scope.id | - | DoesNotExistInTarget | R5 `ValueSet.scope.id` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.scope.inclusionCriteria | - | DoesNotExistInTarget | R5 `ValueSet.scope.inclusionCriteria` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.scope.modifierExtension | - | DoesNotExistInTarget | R5 `ValueSet.scope.modifierExtension` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.status | ValueSet.status | Equivalent | R5 `ValueSet.status` maps as Equivalent to R4 `ValueSet.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|5.0.0 and http://hl7.org/fhir/ValueSet/publication-status|4.0.1 (Equivalent) |
| ValueSet.text | ValueSet.text | Equivalent | R5 `ValueSet.text` maps as Equivalent to R4 `ValueSet.text` |
| ValueSet.title | ValueSet.title | Equivalent | R5 `ValueSet.title` maps as Equivalent to R4 `ValueSet.title` |
| ValueSet.topic | - | DoesNotExistInTarget | R5 `ValueSet.topic` does not appear in the target and has no mapping for `ValueSet`. |
| ValueSet.url | ValueSet.url | Equivalent | R5 `ValueSet.url` maps as Equivalent to R4 `ValueSet.url` |
| ValueSet.useContext | ValueSet.useContext | Equivalent | R5 `ValueSet.useContext` maps as Equivalent to R4 `ValueSet.useContext` |
| ValueSet.version | ValueSet.version | Equivalent | R5 `ValueSet.version` maps as Equivalent to R4 `ValueSet.version` |
| ValueSet.versionAlgorithm[x] | - | DoesNotExistInTarget | R5 `ValueSet.versionAlgorithm[x]` does not appear in the target and has no mapping for `ValueSet`. |

