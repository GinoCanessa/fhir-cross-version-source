Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | EvidenceVariable |  | The EvidenceVariable resource describes an element that knowledge (Evidence) is about. | 83 | 60 |
| Target | EvidenceVariable |  | The EvidenceVariable resource describes a "PICO" element that knowledge (evidence, assertion, recommendation) is about. | 46 | 35 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 42 |
Equivalent | 28 |
RelatedTo | 5 |
SourceIsBroaderThanTarget | 7 |
SourceIsNarrowerThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| EvidenceVariable | EvidenceVariable | Equivalent | R5 `EvidenceVariable` maps as Equivalent to R4 `EvidenceVariable` |
| EvidenceVariable.actual | - | DoesNotExistInTarget | R5 `EvidenceVariable.actual` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.approvalDate | EvidenceVariable.approvalDate | Equivalent | R5 `EvidenceVariable.approvalDate` maps as Equivalent to R4 `EvidenceVariable.approvalDate` |
| EvidenceVariable.author | EvidenceVariable.author | Equivalent | R5 `EvidenceVariable.author` maps as Equivalent to R4 `EvidenceVariable.author` |
| EvidenceVariable.category | - | DoesNotExistInTarget | R5 `EvidenceVariable.category` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.category.extension | - | DoesNotExistInTarget | R5 `EvidenceVariable.category.extension` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.category.id | - | DoesNotExistInTarget | R5 `EvidenceVariable.category.id` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.category.modifierExtension | - | DoesNotExistInTarget | R5 `EvidenceVariable.category.modifierExtension` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.category.name | - | DoesNotExistInTarget | R5 `EvidenceVariable.category.name` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.category.value[x] | - | DoesNotExistInTarget | R5 `EvidenceVariable.category.value[x]` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic | EvidenceVariable.characteristic | RelatedTo | R5 `EvidenceVariable.characteristic` maps as RelatedTo to R4 `EvidenceVariable.characteristic` - characteristic made the element mandatory; characteristic increased the minimum cardinality from 0 to 1 |
| EvidenceVariable.characteristic.definitionByCombination | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.definitionByCombination` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.definitionByCombination.characteristic | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.definitionByCombination.characteristic` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.definitionByCombination.code | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.definitionByCombination.code` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.definitionByCombination.extension | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.definitionByCombination.extension` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.definitionByCombination.id | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.definitionByCombination.id` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.definitionByCombination.modifierExtension | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.definitionByCombination.modifierExtension` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.definitionByCombination.threshold | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.definitionByCombination.threshold` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.definitionByTypeAndValue | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.definitionByTypeAndValue` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.definitionByTypeAndValue.device | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.definitionByTypeAndValue.device` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.definitionByTypeAndValue.extension | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.definitionByTypeAndValue.extension` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.definitionByTypeAndValue.id | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.definitionByTypeAndValue.id` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.definitionByTypeAndValue.method | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.definitionByTypeAndValue.method` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.definitionByTypeAndValue.modifierExtension | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.definitionByTypeAndValue.modifierExtension` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.definitionByTypeAndValue.offset | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.definitionByTypeAndValue.offset` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.definitionByTypeAndValue.type | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.definitionByTypeAndValue.type` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.definitionByTypeAndValue.value[x] | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.definitionByTypeAndValue.value[x]` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.definitionCanonical | EvidenceVariable.characteristic.definition[x] | RelatedTo | R5 `EvidenceVariable.characteristic.definitionCanonical` maps as RelatedTo to R4 `EvidenceVariable.characteristic.definition[x]` - definition[x] made the element mandatory; definition[x] increased the minimum cardinality from 0 to 1; definition[x] has change due to type change: R5 `definitionCanonical` `canonical` maps as RelatedTo for R4 `definition[x]` |
| EvidenceVariable.characteristic.definitionCodeableConcept | EvidenceVariable.characteristic.definition[x] | RelatedTo | R5 `EvidenceVariable.characteristic.definitionCodeableConcept` maps as RelatedTo to R4 `EvidenceVariable.characteristic.definition[x]` - definition[x] made the element mandatory; definition[x] increased the minimum cardinality from 0 to 1 |
| EvidenceVariable.characteristic.definitionExpression | EvidenceVariable.characteristic.definition[x] | RelatedTo | R5 `EvidenceVariable.characteristic.definitionExpression` maps as RelatedTo to R4 `EvidenceVariable.characteristic.definition[x]` - definition[x] made the element mandatory; definition[x] increased the minimum cardinality from 0 to 1; definition[x] has change due to type change: R5 `definitionExpression` `Expression` maps as RelatedTo for R4 `definition[x]` |
| EvidenceVariable.characteristic.definitionId | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.definitionId` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.definitionReference | EvidenceVariable.characteristic.definition[x] | RelatedTo | R5 `EvidenceVariable.characteristic.definitionReference` maps as RelatedTo to R4 `EvidenceVariable.characteristic.definition[x]` - definition[x] made the element mandatory; definition[x] increased the minimum cardinality from 0 to 1; definition[x] has change due to type change: R5 `definitionReference` `Reference` maps as SourceIsBroaderThanTarget for R4 `definition[x]` |
| EvidenceVariable.characteristic.description | EvidenceVariable.characteristic.description | SourceIsBroaderThanTarget | R5 `EvidenceVariable.characteristic.description` maps as SourceIsBroaderThanTarget to R4 `EvidenceVariable.characteristic.description` - description has change due to type change: R5 description markdown has no equivalent or mapped type in R4 description |
| EvidenceVariable.characteristic.duration[x] | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.duration[x]` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.exclude | EvidenceVariable.characteristic.exclude | Equivalent | R5 `EvidenceVariable.characteristic.exclude` maps as Equivalent to R4 `EvidenceVariable.characteristic.exclude` |
| EvidenceVariable.characteristic.extension | EvidenceVariable.characteristic.extension | SourceIsBroaderThanTarget | R5 `EvidenceVariable.characteristic.extension` maps as SourceIsBroaderThanTarget to R4 `EvidenceVariable.characteristic.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| EvidenceVariable.characteristic.id | EvidenceVariable.characteristic.id | Equivalent | R5 `EvidenceVariable.characteristic.id` maps as Equivalent to R4 `EvidenceVariable.characteristic.id` |
| EvidenceVariable.characteristic.instances[x] | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.instances[x]` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.linkId | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.linkId` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.modifierExtension | EvidenceVariable.characteristic.modifierExtension | SourceIsBroaderThanTarget | R5 `EvidenceVariable.characteristic.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `EvidenceVariable.characteristic.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| EvidenceVariable.characteristic.note | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.note` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.timeFromEvent | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.timeFromEvent` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.timeFromEvent.description | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.timeFromEvent.description` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.timeFromEvent.event[x] | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.timeFromEvent.event[x]` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.timeFromEvent.extension | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.timeFromEvent.extension` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.timeFromEvent.id | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.timeFromEvent.id` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.timeFromEvent.modifierExtension | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.timeFromEvent.modifierExtension` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.timeFromEvent.note | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.timeFromEvent.note` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.timeFromEvent.quantity | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.timeFromEvent.quantity` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.timeFromEvent.range | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.timeFromEvent.range` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.contact | EvidenceVariable.contact | Equivalent | R5 `EvidenceVariable.contact` maps as Equivalent to R4 `EvidenceVariable.contact` |
| EvidenceVariable.contained | EvidenceVariable.contained | Equivalent | R5 `EvidenceVariable.contained` maps as Equivalent to R4 `EvidenceVariable.contained` |
| EvidenceVariable.copyright | EvidenceVariable.copyright | Equivalent | R5 `EvidenceVariable.copyright` maps as Equivalent to R4 `EvidenceVariable.copyright` |
| EvidenceVariable.copyrightLabel | - | DoesNotExistInTarget | R5 `EvidenceVariable.copyrightLabel` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.date | EvidenceVariable.date | Equivalent | R5 `EvidenceVariable.date` maps as Equivalent to R4 `EvidenceVariable.date` |
| EvidenceVariable.description | EvidenceVariable.description | Equivalent | R5 `EvidenceVariable.description` maps as Equivalent to R4 `EvidenceVariable.description` |
| EvidenceVariable.editor | EvidenceVariable.editor | Equivalent | R5 `EvidenceVariable.editor` maps as Equivalent to R4 `EvidenceVariable.editor` |
| EvidenceVariable.effectivePeriod | EvidenceVariable.effectivePeriod | Equivalent | R5 `EvidenceVariable.effectivePeriod` maps as Equivalent to R4 `EvidenceVariable.effectivePeriod` |
| EvidenceVariable.endorser | EvidenceVariable.endorser | Equivalent | R5 `EvidenceVariable.endorser` maps as Equivalent to R4 `EvidenceVariable.endorser` |
| EvidenceVariable.experimental | - | DoesNotExistInTarget | R5 `EvidenceVariable.experimental` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.extension | EvidenceVariable.extension | SourceIsBroaderThanTarget | R5 `EvidenceVariable.extension` maps as SourceIsBroaderThanTarget to R4 `EvidenceVariable.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| EvidenceVariable.handling | - | DoesNotExistInTarget | R5 `EvidenceVariable.handling` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.id | EvidenceVariable.id | Equivalent | R5 `EvidenceVariable.id` maps as Equivalent to R4 `EvidenceVariable.id` |
| EvidenceVariable.identifier | EvidenceVariable.identifier | Equivalent | R5 `EvidenceVariable.identifier` maps as Equivalent to R4 `EvidenceVariable.identifier` |
| EvidenceVariable.implicitRules | EvidenceVariable.implicitRules | Equivalent | R5 `EvidenceVariable.implicitRules` maps as Equivalent to R4 `EvidenceVariable.implicitRules` |
| EvidenceVariable.language | EvidenceVariable.language | SourceIsNarrowerThanTarget | R5 `EvidenceVariable.language` maps as SourceIsNarrowerThanTarget to R4 `EvidenceVariable.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| EvidenceVariable.lastReviewDate | EvidenceVariable.lastReviewDate | Equivalent | R5 `EvidenceVariable.lastReviewDate` maps as Equivalent to R4 `EvidenceVariable.lastReviewDate` |
| EvidenceVariable.meta | EvidenceVariable.meta | Equivalent | R5 `EvidenceVariable.meta` maps as Equivalent to R4 `EvidenceVariable.meta` |
| EvidenceVariable.modifierExtension | EvidenceVariable.modifierExtension | SourceIsBroaderThanTarget | R5 `EvidenceVariable.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `EvidenceVariable.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| EvidenceVariable.name | EvidenceVariable.name | Equivalent | R5 `EvidenceVariable.name` maps as Equivalent to R4 `EvidenceVariable.name` |
| EvidenceVariable.note | EvidenceVariable.note | SourceIsBroaderThanTarget | R5 `EvidenceVariable.note` maps as SourceIsBroaderThanTarget to R4 `EvidenceVariable.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4 `note` |
| EvidenceVariable.publisher | EvidenceVariable.publisher | Equivalent | R5 `EvidenceVariable.publisher` maps as Equivalent to R4 `EvidenceVariable.publisher` |
| EvidenceVariable.purpose | - | DoesNotExistInTarget | R5 `EvidenceVariable.purpose` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.relatedArtifact | EvidenceVariable.relatedArtifact | SourceIsBroaderThanTarget | R5 `EvidenceVariable.relatedArtifact` maps as SourceIsBroaderThanTarget to R4 `EvidenceVariable.relatedArtifact` - relatedArtifact has change due to type change: R5 `relatedArtifact` `RelatedArtifact` maps as SourceIsBroaderThanTarget for R4 `relatedArtifact` |
| EvidenceVariable.reviewer | EvidenceVariable.reviewer | Equivalent | R5 `EvidenceVariable.reviewer` maps as Equivalent to R4 `EvidenceVariable.reviewer` |
| EvidenceVariable.shortTitle | EvidenceVariable.shortTitle | Equivalent | R5 `EvidenceVariable.shortTitle` maps as Equivalent to R4 `EvidenceVariable.shortTitle` |
| EvidenceVariable.status | EvidenceVariable.status | Equivalent | R5 `EvidenceVariable.status` maps as Equivalent to R4 `EvidenceVariable.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|5.0.0 and http://hl7.org/fhir/ValueSet/publication-status|4.0.1 (Equivalent) |
| EvidenceVariable.text | EvidenceVariable.text | Equivalent | R5 `EvidenceVariable.text` maps as Equivalent to R4 `EvidenceVariable.text` |
| EvidenceVariable.title | EvidenceVariable.title | Equivalent | R5 `EvidenceVariable.title` maps as Equivalent to R4 `EvidenceVariable.title` |
| EvidenceVariable.url | EvidenceVariable.url | Equivalent | R5 `EvidenceVariable.url` maps as Equivalent to R4 `EvidenceVariable.url` |
| EvidenceVariable.useContext | EvidenceVariable.useContext | Equivalent | R5 `EvidenceVariable.useContext` maps as Equivalent to R4 `EvidenceVariable.useContext` |
| EvidenceVariable.version | EvidenceVariable.version | Equivalent | R5 `EvidenceVariable.version` maps as Equivalent to R4 `EvidenceVariable.version` |
| EvidenceVariable.versionAlgorithm[x] | - | DoesNotExistInTarget | R5 `EvidenceVariable.versionAlgorithm[x]` does not appear in the target and has no mapping for `EvidenceVariable`. |

