Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | EvidenceVariable |  | The EvidenceVariable resource describes an element that knowledge (Evidence) is about. | 83 | 60 |
| Target | EvidenceVariable |  | The EvidenceVariable resource describes an element that knowledge (Evidence) is about. | 55 | 38 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 42 |
Equivalent | 4 |
RelatedTo | 37 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| EvidenceVariable | EvidenceVariable | Equivalent | R5 `EvidenceVariable` maps as Equivalent to R4B `EvidenceVariable` |
| EvidenceVariable.actual | EvidenceVariable.actual | Equivalent | R5 `EvidenceVariable.actual` maps as Equivalent to R4B `EvidenceVariable.actual` |
| EvidenceVariable.approvalDate | - | DoesNotExistInTarget | R5 `EvidenceVariable.approvalDate` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.author | EvidenceVariable.author | Equivalent | R5 `EvidenceVariable.author` maps as Equivalent to R4B `EvidenceVariable.author` |
| EvidenceVariable.category | EvidenceVariable.category | Equivalent | R5 `EvidenceVariable.category` maps as Equivalent to R4B `EvidenceVariable.category` |
| EvidenceVariable.category.extension | EvidenceVariable.category.extension | SourceIsBroaderThanTarget | R5 `EvidenceVariable.category.extension` maps as SourceIsBroaderThanTarget to R4B `EvidenceVariable.category.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| EvidenceVariable.category.id | EvidenceVariable.category.id | Equivalent | R5 `EvidenceVariable.category.id` maps as Equivalent to R4B `EvidenceVariable.category.id` |
| EvidenceVariable.category.modifierExtension | EvidenceVariable.category.modifierExtension | SourceIsBroaderThanTarget | R5 `EvidenceVariable.category.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `EvidenceVariable.category.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| EvidenceVariable.category.name | EvidenceVariable.category.name | Equivalent | R5 `EvidenceVariable.category.name` maps as Equivalent to R4B `EvidenceVariable.category.name` |
| EvidenceVariable.category.value[x] | EvidenceVariable.category.value[x] | Equivalent | R5 `EvidenceVariable.category.value[x]` maps as Equivalent to R4B `EvidenceVariable.category.value[x]` |
| EvidenceVariable.characteristic | EvidenceVariable.characteristic | Equivalent | R5 `EvidenceVariable.characteristic` maps as Equivalent to R4B `EvidenceVariable.characteristic` |
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
| EvidenceVariable.characteristic.definitionCanonical | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.definitionCanonical` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.definitionCodeableConcept | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.definitionCodeableConcept` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.definitionExpression | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.definitionExpression` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.definitionId | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.definitionId` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.definitionReference | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.definitionReference` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.description | EvidenceVariable.characteristic.description | SourceIsBroaderThanTarget | R5 `EvidenceVariable.characteristic.description` maps as SourceIsBroaderThanTarget to R4B `EvidenceVariable.characteristic.description` - description has change due to type change: R5 description markdown has no equivalent or mapped type in R4B description |
| EvidenceVariable.characteristic.duration[x] | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.duration[x]` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.exclude | EvidenceVariable.characteristic.exclude | Equivalent | R5 `EvidenceVariable.characteristic.exclude` maps as Equivalent to R4B `EvidenceVariable.characteristic.exclude` |
| EvidenceVariable.characteristic.extension | EvidenceVariable.characteristic.extension | SourceIsBroaderThanTarget | R5 `EvidenceVariable.characteristic.extension` maps as SourceIsBroaderThanTarget to R4B `EvidenceVariable.characteristic.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| EvidenceVariable.characteristic.id | EvidenceVariable.characteristic.id | Equivalent | R5 `EvidenceVariable.characteristic.id` maps as Equivalent to R4B `EvidenceVariable.characteristic.id` |
| EvidenceVariable.characteristic.instances[x] | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.instances[x]` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.linkId | - | DoesNotExistInTarget | R5 `EvidenceVariable.characteristic.linkId` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.modifierExtension | EvidenceVariable.characteristic.modifierExtension | SourceIsBroaderThanTarget | R5 `EvidenceVariable.characteristic.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `EvidenceVariable.characteristic.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
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
| EvidenceVariable.contact | EvidenceVariable.contact | Equivalent | R5 `EvidenceVariable.contact` maps as Equivalent to R4B `EvidenceVariable.contact` |
| EvidenceVariable.contained | EvidenceVariable.contained | Equivalent | R5 `EvidenceVariable.contained` maps as Equivalent to R4B `EvidenceVariable.contained` |
| EvidenceVariable.copyright | - | DoesNotExistInTarget | R5 `EvidenceVariable.copyright` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.copyrightLabel | - | DoesNotExistInTarget | R5 `EvidenceVariable.copyrightLabel` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.date | EvidenceVariable.date | Equivalent | R5 `EvidenceVariable.date` maps as Equivalent to R4B `EvidenceVariable.date` |
| EvidenceVariable.description | EvidenceVariable.description | Equivalent | R5 `EvidenceVariable.description` maps as Equivalent to R4B `EvidenceVariable.description` |
| EvidenceVariable.editor | EvidenceVariable.editor | Equivalent | R5 `EvidenceVariable.editor` maps as Equivalent to R4B `EvidenceVariable.editor` |
| EvidenceVariable.effectivePeriod | - | DoesNotExistInTarget | R5 `EvidenceVariable.effectivePeriod` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.endorser | EvidenceVariable.endorser | Equivalent | R5 `EvidenceVariable.endorser` maps as Equivalent to R4B `EvidenceVariable.endorser` |
| EvidenceVariable.experimental | - | DoesNotExistInTarget | R5 `EvidenceVariable.experimental` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.extension | EvidenceVariable.extension | SourceIsBroaderThanTarget | R5 `EvidenceVariable.extension` maps as SourceIsBroaderThanTarget to R4B `EvidenceVariable.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| EvidenceVariable.handling | EvidenceVariable.handling | Equivalent | R5 `EvidenceVariable.handling` maps as Equivalent to R4B `EvidenceVariable.handling` - handling has compatible required binding for code type: http://hl7.org/fhir/ValueSet/variable-handling|5.0.0 and http://hl7.org/fhir/ValueSet/variable-handling|4.3.0 (Equivalent) |
| EvidenceVariable.id | EvidenceVariable.id | Equivalent | R5 `EvidenceVariable.id` maps as Equivalent to R4B `EvidenceVariable.id` |
| EvidenceVariable.identifier | EvidenceVariable.identifier | Equivalent | R5 `EvidenceVariable.identifier` maps as Equivalent to R4B `EvidenceVariable.identifier` |
| EvidenceVariable.implicitRules | EvidenceVariable.implicitRules | Equivalent | R5 `EvidenceVariable.implicitRules` maps as Equivalent to R4B `EvidenceVariable.implicitRules` |
| EvidenceVariable.language | EvidenceVariable.language | RelatedTo | R5 `EvidenceVariable.language` maps as RelatedTo to R4B `EvidenceVariable.language` - language changed the binding strength from Required to Preferred |
| EvidenceVariable.lastReviewDate | - | DoesNotExistInTarget | R5 `EvidenceVariable.lastReviewDate` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.meta | EvidenceVariable.meta | Equivalent | R5 `EvidenceVariable.meta` maps as Equivalent to R4B `EvidenceVariable.meta` |
| EvidenceVariable.modifierExtension | EvidenceVariable.modifierExtension | SourceIsBroaderThanTarget | R5 `EvidenceVariable.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `EvidenceVariable.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| EvidenceVariable.name | EvidenceVariable.name | Equivalent | R5 `EvidenceVariable.name` maps as Equivalent to R4B `EvidenceVariable.name` |
| EvidenceVariable.note | EvidenceVariable.note | SourceIsBroaderThanTarget | R5 `EvidenceVariable.note` maps as SourceIsBroaderThanTarget to R4B `EvidenceVariable.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4B `note` |
| EvidenceVariable.publisher | EvidenceVariable.publisher | Equivalent | R5 `EvidenceVariable.publisher` maps as Equivalent to R4B `EvidenceVariable.publisher` |
| EvidenceVariable.purpose | - | DoesNotExistInTarget | R5 `EvidenceVariable.purpose` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.relatedArtifact | EvidenceVariable.relatedArtifact | Equivalent | R5 `EvidenceVariable.relatedArtifact` maps as Equivalent to R4B `EvidenceVariable.relatedArtifact` |
| EvidenceVariable.reviewer | EvidenceVariable.reviewer | Equivalent | R5 `EvidenceVariable.reviewer` maps as Equivalent to R4B `EvidenceVariable.reviewer` |
| EvidenceVariable.shortTitle | EvidenceVariable.shortTitle | Equivalent | R5 `EvidenceVariable.shortTitle` maps as Equivalent to R4B `EvidenceVariable.shortTitle` |
| EvidenceVariable.status | EvidenceVariable.status | Equivalent | R5 `EvidenceVariable.status` maps as Equivalent to R4B `EvidenceVariable.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|5.0.0 and http://hl7.org/fhir/ValueSet/publication-status|4.3.0 (Equivalent) |
| EvidenceVariable.text | EvidenceVariable.text | Equivalent | R5 `EvidenceVariable.text` maps as Equivalent to R4B `EvidenceVariable.text` |
| EvidenceVariable.title | EvidenceVariable.title | Equivalent | R5 `EvidenceVariable.title` maps as Equivalent to R4B `EvidenceVariable.title` |
| EvidenceVariable.url | EvidenceVariable.url | Equivalent | R5 `EvidenceVariable.url` maps as Equivalent to R4B `EvidenceVariable.url` |
| EvidenceVariable.useContext | EvidenceVariable.useContext | Equivalent | R5 `EvidenceVariable.useContext` maps as Equivalent to R4B `EvidenceVariable.useContext` |
| EvidenceVariable.version | EvidenceVariable.version | Equivalent | R5 `EvidenceVariable.version` maps as Equivalent to R4B `EvidenceVariable.version` |
| EvidenceVariable.versionAlgorithm[x] | - | DoesNotExistInTarget | R5 `EvidenceVariable.versionAlgorithm[x]` does not appear in the target and has no mapping for `EvidenceVariable`. |

