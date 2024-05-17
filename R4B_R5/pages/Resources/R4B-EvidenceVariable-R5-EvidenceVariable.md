Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | EvidenceVariable |  | The EvidenceVariable resource describes an element that knowledge (Evidence) is about. | 55 | 38 |
| Target | EvidenceVariable |  | The EvidenceVariable resource describes an element that knowledge (Evidence) is about. | 83 | 60 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 14 |
Equivalent | 4 |
RelatedTo | 37 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| EvidenceVariable | EvidenceVariable | Equivalent | R4B `EvidenceVariable` maps as Equivalent to R5 `EvidenceVariable` |
| EvidenceVariable.actual | EvidenceVariable.actual | Equivalent | R4B `EvidenceVariable.actual` maps as Equivalent to R5 `EvidenceVariable.actual` |
| EvidenceVariable.author | EvidenceVariable.author | Equivalent | R4B `EvidenceVariable.author` maps as Equivalent to R5 `EvidenceVariable.author` |
| EvidenceVariable.category | EvidenceVariable.category | Equivalent | R4B `EvidenceVariable.category` maps as Equivalent to R5 `EvidenceVariable.category` |
| EvidenceVariable.category.extension | EvidenceVariable.category.extension | RelatedTo | R4B `EvidenceVariable.category.extension` maps as RelatedTo to R5 `EvidenceVariable.category.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| EvidenceVariable.category.id | EvidenceVariable.category.id | Equivalent | R4B `EvidenceVariable.category.id` maps as Equivalent to R5 `EvidenceVariable.category.id` |
| EvidenceVariable.category.modifierExtension | EvidenceVariable.category.modifierExtension | RelatedTo | R4B `EvidenceVariable.category.modifierExtension` maps as RelatedTo to R5 `EvidenceVariable.category.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| EvidenceVariable.category.name | EvidenceVariable.category.name | Equivalent | R4B `EvidenceVariable.category.name` maps as Equivalent to R5 `EvidenceVariable.category.name` |
| EvidenceVariable.category.value[x] | EvidenceVariable.category.value[x] | Equivalent | R4B `EvidenceVariable.category.value[x]` maps as Equivalent to R5 `EvidenceVariable.category.value[x]` |
| EvidenceVariable.characteristic | EvidenceVariable.characteristic | Equivalent | R4B `EvidenceVariable.characteristic` maps as Equivalent to R5 `EvidenceVariable.characteristic` |
| EvidenceVariable.characteristic.definition[x] | - | DoesNotExistInTarget | R4B `EvidenceVariable.characteristic.definition[x]` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.description | EvidenceVariable.characteristic.description | SourceIsBroaderThanTarget | R4B `EvidenceVariable.characteristic.description` maps as SourceIsBroaderThanTarget to R5 `EvidenceVariable.characteristic.description` - description has change due to type change: R4B description string has no equivalent or mapped type in R5 description |
| EvidenceVariable.characteristic.device | - | DoesNotExistInTarget | R4B `EvidenceVariable.characteristic.device` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.exclude | EvidenceVariable.characteristic.exclude | Equivalent | R4B `EvidenceVariable.characteristic.exclude` maps as Equivalent to R5 `EvidenceVariable.characteristic.exclude` |
| EvidenceVariable.characteristic.extension | EvidenceVariable.characteristic.extension | RelatedTo | R4B `EvidenceVariable.characteristic.extension` maps as RelatedTo to R5 `EvidenceVariable.characteristic.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| EvidenceVariable.characteristic.groupMeasure | - | DoesNotExistInTarget | R4B `EvidenceVariable.characteristic.groupMeasure` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.id | EvidenceVariable.characteristic.id | Equivalent | R4B `EvidenceVariable.characteristic.id` maps as Equivalent to R5 `EvidenceVariable.characteristic.id` |
| EvidenceVariable.characteristic.method | - | DoesNotExistInTarget | R4B `EvidenceVariable.characteristic.method` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.modifierExtension | EvidenceVariable.characteristic.modifierExtension | RelatedTo | R4B `EvidenceVariable.characteristic.modifierExtension` maps as RelatedTo to R5 `EvidenceVariable.characteristic.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| EvidenceVariable.characteristic.timeFromStart | - | DoesNotExistInTarget | R4B `EvidenceVariable.characteristic.timeFromStart` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.timeFromStart.description | - | DoesNotExistInTarget | R4B `EvidenceVariable.characteristic.timeFromStart.description` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.timeFromStart.extension | - | DoesNotExistInTarget | R4B `EvidenceVariable.characteristic.timeFromStart.extension` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.timeFromStart.id | - | DoesNotExistInTarget | R4B `EvidenceVariable.characteristic.timeFromStart.id` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.timeFromStart.modifierExtension | - | DoesNotExistInTarget | R4B `EvidenceVariable.characteristic.timeFromStart.modifierExtension` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.timeFromStart.note | - | DoesNotExistInTarget | R4B `EvidenceVariable.characteristic.timeFromStart.note` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.timeFromStart.quantity | - | DoesNotExistInTarget | R4B `EvidenceVariable.characteristic.timeFromStart.quantity` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristic.timeFromStart.range | - | DoesNotExistInTarget | R4B `EvidenceVariable.characteristic.timeFromStart.range` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.characteristicCombination | - | DoesNotExistInTarget | R4B `EvidenceVariable.characteristicCombination` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.contact | EvidenceVariable.contact | Equivalent | R4B `EvidenceVariable.contact` maps as Equivalent to R5 `EvidenceVariable.contact` |
| EvidenceVariable.contained | EvidenceVariable.contained | Equivalent | R4B `EvidenceVariable.contained` maps as Equivalent to R5 `EvidenceVariable.contained` |
| EvidenceVariable.date | EvidenceVariable.date | Equivalent | R4B `EvidenceVariable.date` maps as Equivalent to R5 `EvidenceVariable.date` |
| EvidenceVariable.description | EvidenceVariable.description | Equivalent | R4B `EvidenceVariable.description` maps as Equivalent to R5 `EvidenceVariable.description` |
| EvidenceVariable.editor | EvidenceVariable.editor | Equivalent | R4B `EvidenceVariable.editor` maps as Equivalent to R5 `EvidenceVariable.editor` |
| EvidenceVariable.endorser | EvidenceVariable.endorser | Equivalent | R4B `EvidenceVariable.endorser` maps as Equivalent to R5 `EvidenceVariable.endorser` |
| EvidenceVariable.extension | EvidenceVariable.extension | RelatedTo | R4B `EvidenceVariable.extension` maps as RelatedTo to R5 `EvidenceVariable.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| EvidenceVariable.handling | EvidenceVariable.handling | Equivalent | R4B `EvidenceVariable.handling` maps as Equivalent to R5 `EvidenceVariable.handling` - handling has compatible required binding for code type: http://hl7.org/fhir/ValueSet/variable-handling|4.3.0 and http://hl7.org/fhir/ValueSet/variable-handling|5.0.0 (Equivalent) |
| EvidenceVariable.id | EvidenceVariable.id | Equivalent | R4B `EvidenceVariable.id` maps as Equivalent to R5 `EvidenceVariable.id` |
| EvidenceVariable.identifier | EvidenceVariable.identifier | Equivalent | R4B `EvidenceVariable.identifier` maps as Equivalent to R5 `EvidenceVariable.identifier` |
| EvidenceVariable.implicitRules | EvidenceVariable.implicitRules | Equivalent | R4B `EvidenceVariable.implicitRules` maps as Equivalent to R5 `EvidenceVariable.implicitRules` |
| EvidenceVariable.language | EvidenceVariable.language | RelatedTo | R4B `EvidenceVariable.language` maps as RelatedTo to R5 `EvidenceVariable.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| EvidenceVariable.meta | EvidenceVariable.meta | Equivalent | R4B `EvidenceVariable.meta` maps as Equivalent to R5 `EvidenceVariable.meta` |
| EvidenceVariable.modifierExtension | EvidenceVariable.modifierExtension | RelatedTo | R4B `EvidenceVariable.modifierExtension` maps as RelatedTo to R5 `EvidenceVariable.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| EvidenceVariable.name | EvidenceVariable.name | Equivalent | R4B `EvidenceVariable.name` maps as Equivalent to R5 `EvidenceVariable.name` |
| EvidenceVariable.note | EvidenceVariable.note | SourceIsNarrowerThanTarget | R4B `EvidenceVariable.note` maps as SourceIsNarrowerThanTarget to R5 `EvidenceVariable.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| EvidenceVariable.publisher | EvidenceVariable.publisher | Equivalent | R4B `EvidenceVariable.publisher` maps as Equivalent to R5 `EvidenceVariable.publisher` |
| EvidenceVariable.relatedArtifact | EvidenceVariable.relatedArtifact | Equivalent | R4B `EvidenceVariable.relatedArtifact` maps as Equivalent to R5 `EvidenceVariable.relatedArtifact` |
| EvidenceVariable.reviewer | EvidenceVariable.reviewer | Equivalent | R4B `EvidenceVariable.reviewer` maps as Equivalent to R5 `EvidenceVariable.reviewer` |
| EvidenceVariable.shortTitle | EvidenceVariable.shortTitle | Equivalent | R4B `EvidenceVariable.shortTitle` maps as Equivalent to R5 `EvidenceVariable.shortTitle` |
| EvidenceVariable.status | EvidenceVariable.status | Equivalent | R4B `EvidenceVariable.status` maps as Equivalent to R5 `EvidenceVariable.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|4.3.0 and http://hl7.org/fhir/ValueSet/publication-status|5.0.0 (Equivalent) |
| EvidenceVariable.subtitle | - | DoesNotExistInTarget | R4B `EvidenceVariable.subtitle` does not appear in the target and has no mapping for `EvidenceVariable`. |
| EvidenceVariable.text | EvidenceVariable.text | Equivalent | R4B `EvidenceVariable.text` maps as Equivalent to R5 `EvidenceVariable.text` |
| EvidenceVariable.title | EvidenceVariable.title | Equivalent | R4B `EvidenceVariable.title` maps as Equivalent to R5 `EvidenceVariable.title` |
| EvidenceVariable.url | EvidenceVariable.url | Equivalent | R4B `EvidenceVariable.url` maps as Equivalent to R5 `EvidenceVariable.url` |
| EvidenceVariable.useContext | EvidenceVariable.useContext | Equivalent | R4B `EvidenceVariable.useContext` maps as Equivalent to R5 `EvidenceVariable.useContext` |
| EvidenceVariable.version | EvidenceVariable.version | Equivalent | R4B `EvidenceVariable.version` maps as Equivalent to R5 `EvidenceVariable.version` |

