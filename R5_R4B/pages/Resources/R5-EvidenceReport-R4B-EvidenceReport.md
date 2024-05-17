Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | EvidenceReport |  | The EvidenceReport Resource is a specialized container for a collection of resources and codeable concepts, adapted to support compositions of Evidence, EvidenceVariable, and Citation resources and related concepts. | 66 | 43 |
| Target | EvidenceReport |  | The EvidenceReport Resource is a specialized container for a collection of resources and codable concepts, adapted to support compositions of Evidence, EvidenceVariable, and Citation resources and related concepts. | 59 | 39 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 8 |
Equivalent | 4 |
RelatedTo | 54 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| EvidenceReport | EvidenceReport | Equivalent | R5 `EvidenceReport` maps as Equivalent to R4B `EvidenceReport` |
| EvidenceReport.author | EvidenceReport.author | Equivalent | R5 `EvidenceReport.author` maps as Equivalent to R4B `EvidenceReport.author` |
| EvidenceReport.citeAs[x] | EvidenceReport.citeAs[x] | Equivalent | R5 `EvidenceReport.citeAs[x]` maps as Equivalent to R4B `EvidenceReport.citeAs[x]` |
| EvidenceReport.contact | EvidenceReport.contact | Equivalent | R5 `EvidenceReport.contact` maps as Equivalent to R4B `EvidenceReport.contact` |
| EvidenceReport.contained | EvidenceReport.contained | Equivalent | R5 `EvidenceReport.contained` maps as Equivalent to R4B `EvidenceReport.contained` |
| EvidenceReport.editor | EvidenceReport.editor | Equivalent | R5 `EvidenceReport.editor` maps as Equivalent to R4B `EvidenceReport.editor` |
| EvidenceReport.endorser | EvidenceReport.endorser | Equivalent | R5 `EvidenceReport.endorser` maps as Equivalent to R4B `EvidenceReport.endorser` |
| EvidenceReport.extension | EvidenceReport.extension | SourceIsBroaderThanTarget | R5 `EvidenceReport.extension` maps as SourceIsBroaderThanTarget to R4B `EvidenceReport.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| EvidenceReport.id | EvidenceReport.id | Equivalent | R5 `EvidenceReport.id` maps as Equivalent to R4B `EvidenceReport.id` |
| EvidenceReport.identifier | EvidenceReport.identifier | Equivalent | R5 `EvidenceReport.identifier` maps as Equivalent to R4B `EvidenceReport.identifier` |
| EvidenceReport.implicitRules | EvidenceReport.implicitRules | Equivalent | R5 `EvidenceReport.implicitRules` maps as Equivalent to R4B `EvidenceReport.implicitRules` |
| EvidenceReport.language | EvidenceReport.language | RelatedTo | R5 `EvidenceReport.language` maps as RelatedTo to R4B `EvidenceReport.language` - language changed the binding strength from Required to Preferred |
| EvidenceReport.meta | EvidenceReport.meta | Equivalent | R5 `EvidenceReport.meta` maps as Equivalent to R4B `EvidenceReport.meta` |
| EvidenceReport.modifierExtension | EvidenceReport.modifierExtension | SourceIsBroaderThanTarget | R5 `EvidenceReport.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `EvidenceReport.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| EvidenceReport.note | EvidenceReport.note | SourceIsBroaderThanTarget | R5 `EvidenceReport.note` maps as SourceIsBroaderThanTarget to R4B `EvidenceReport.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4B `note` |
| EvidenceReport.publisher | EvidenceReport.publisher | Equivalent | R5 `EvidenceReport.publisher` maps as Equivalent to R4B `EvidenceReport.publisher` |
| EvidenceReport.relatedArtifact | EvidenceReport.relatedArtifact | Equivalent | R5 `EvidenceReport.relatedArtifact` maps as Equivalent to R4B `EvidenceReport.relatedArtifact` |
| EvidenceReport.relatedIdentifier | EvidenceReport.relatedIdentifier | Equivalent | R5 `EvidenceReport.relatedIdentifier` maps as Equivalent to R4B `EvidenceReport.relatedIdentifier` |
| EvidenceReport.relatesTo | EvidenceReport.relatesTo | Equivalent | R5 `EvidenceReport.relatesTo` maps as Equivalent to R4B `EvidenceReport.relatesTo` |
| EvidenceReport.relatesTo.code | EvidenceReport.relatesTo.code | Equivalent | R5 `EvidenceReport.relatesTo.code` maps as Equivalent to R4B `EvidenceReport.relatesTo.code` - code has compatible required binding for code type: http://hl7.org/fhir/ValueSet/report-relation-type|5.0.0 and http://hl7.org/fhir/ValueSet/report-relation-type|4.3.0 (Equivalent) |
| EvidenceReport.relatesTo.extension | EvidenceReport.relatesTo.extension | SourceIsBroaderThanTarget | R5 `EvidenceReport.relatesTo.extension` maps as SourceIsBroaderThanTarget to R4B `EvidenceReport.relatesTo.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| EvidenceReport.relatesTo.id | EvidenceReport.relatesTo.id | Equivalent | R5 `EvidenceReport.relatesTo.id` maps as Equivalent to R4B `EvidenceReport.relatesTo.id` |
| EvidenceReport.relatesTo.modifierExtension | EvidenceReport.relatesTo.modifierExtension | SourceIsBroaderThanTarget | R5 `EvidenceReport.relatesTo.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `EvidenceReport.relatesTo.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| EvidenceReport.relatesTo.target | - | DoesNotExistInTarget | R5 `EvidenceReport.relatesTo.target` does not appear in the target and has no mapping for `EvidenceReport`. |
| EvidenceReport.relatesTo.target.display | - | DoesNotExistInTarget | R5 `EvidenceReport.relatesTo.target.display` does not appear in the target and has no mapping for `EvidenceReport`. |
| EvidenceReport.relatesTo.target.extension | - | DoesNotExistInTarget | R5 `EvidenceReport.relatesTo.target.extension` does not appear in the target and has no mapping for `EvidenceReport`. |
| EvidenceReport.relatesTo.target.id | - | DoesNotExistInTarget | R5 `EvidenceReport.relatesTo.target.id` does not appear in the target and has no mapping for `EvidenceReport`. |
| EvidenceReport.relatesTo.target.identifier | - | DoesNotExistInTarget | R5 `EvidenceReport.relatesTo.target.identifier` does not appear in the target and has no mapping for `EvidenceReport`. |
| EvidenceReport.relatesTo.target.modifierExtension | - | DoesNotExistInTarget | R5 `EvidenceReport.relatesTo.target.modifierExtension` does not appear in the target and has no mapping for `EvidenceReport`. |
| EvidenceReport.relatesTo.target.resource | - | DoesNotExistInTarget | R5 `EvidenceReport.relatesTo.target.resource` does not appear in the target and has no mapping for `EvidenceReport`. |
| EvidenceReport.relatesTo.target.url | - | DoesNotExistInTarget | R5 `EvidenceReport.relatesTo.target.url` does not appear in the target and has no mapping for `EvidenceReport`. |
| EvidenceReport.reviewer | EvidenceReport.reviewer | Equivalent | R5 `EvidenceReport.reviewer` maps as Equivalent to R4B `EvidenceReport.reviewer` |
| EvidenceReport.section | EvidenceReport.section | Equivalent | R5 `EvidenceReport.section` maps as Equivalent to R4B `EvidenceReport.section` |
| EvidenceReport.section.author | EvidenceReport.section.author | RelatedTo | R5 `EvidenceReport.section.author` maps as RelatedTo to R4B `EvidenceReport.section.author` - author has change due to type change: R5 `author` `Reference` maps as RelatedTo for R4B `author` |
| EvidenceReport.section.emptyReason | EvidenceReport.section.emptyReason | Equivalent | R5 `EvidenceReport.section.emptyReason` maps as Equivalent to R4B `EvidenceReport.section.emptyReason` |
| EvidenceReport.section.entryClassifier | EvidenceReport.section.entryClassifier | Equivalent | R5 `EvidenceReport.section.entryClassifier` maps as Equivalent to R4B `EvidenceReport.section.entryClassifier` |
| EvidenceReport.section.entryQuantity | EvidenceReport.section.entryQuantity | Equivalent | R5 `EvidenceReport.section.entryQuantity` maps as Equivalent to R4B `EvidenceReport.section.entryQuantity` |
| EvidenceReport.section.entryReference | EvidenceReport.section.entryReference | Equivalent | R5 `EvidenceReport.section.entryReference` maps as Equivalent to R4B `EvidenceReport.section.entryReference` |
| EvidenceReport.section.extension | EvidenceReport.section.extension | SourceIsBroaderThanTarget | R5 `EvidenceReport.section.extension` maps as SourceIsBroaderThanTarget to R4B `EvidenceReport.section.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| EvidenceReport.section.focus | EvidenceReport.section.focus | Equivalent | R5 `EvidenceReport.section.focus` maps as Equivalent to R4B `EvidenceReport.section.focus` |
| EvidenceReport.section.focusReference | EvidenceReport.section.focusReference | Equivalent | R5 `EvidenceReport.section.focusReference` maps as Equivalent to R4B `EvidenceReport.section.focusReference` |
| EvidenceReport.section.id | EvidenceReport.section.id | Equivalent | R5 `EvidenceReport.section.id` maps as Equivalent to R4B `EvidenceReport.section.id` |
| EvidenceReport.section.mode | EvidenceReport.section.mode | Equivalent | R5 `EvidenceReport.section.mode` maps as Equivalent to R4B `EvidenceReport.section.mode` - mode has compatible required binding for code type: http://hl7.org/fhir/ValueSet/list-mode|5.0.0 and http://hl7.org/fhir/ValueSet/list-mode|4.3.0 (Equivalent) |
| EvidenceReport.section.modifierExtension | EvidenceReport.section.modifierExtension | SourceIsBroaderThanTarget | R5 `EvidenceReport.section.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `EvidenceReport.section.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| EvidenceReport.section.orderedBy | EvidenceReport.section.orderedBy | Equivalent | R5 `EvidenceReport.section.orderedBy` maps as Equivalent to R4B `EvidenceReport.section.orderedBy` |
| EvidenceReport.section.section | EvidenceReport.section.section | Equivalent | R5 `EvidenceReport.section.section` maps as Equivalent to R4B `EvidenceReport.section.section` |
| EvidenceReport.section.text | EvidenceReport.section.text | Equivalent | R5 `EvidenceReport.section.text` maps as Equivalent to R4B `EvidenceReport.section.text` |
| EvidenceReport.section.title | EvidenceReport.section.title | Equivalent | R5 `EvidenceReport.section.title` maps as Equivalent to R4B `EvidenceReport.section.title` |
| EvidenceReport.status | EvidenceReport.status | Equivalent | R5 `EvidenceReport.status` maps as Equivalent to R4B `EvidenceReport.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|5.0.0 and http://hl7.org/fhir/ValueSet/publication-status|4.3.0 (Equivalent) |
| EvidenceReport.subject | EvidenceReport.subject | Equivalent | R5 `EvidenceReport.subject` maps as Equivalent to R4B `EvidenceReport.subject` |
| EvidenceReport.subject.characteristic | EvidenceReport.subject.characteristic | Equivalent | R5 `EvidenceReport.subject.characteristic` maps as Equivalent to R4B `EvidenceReport.subject.characteristic` |
| EvidenceReport.subject.characteristic.code | EvidenceReport.subject.characteristic.code | Equivalent | R5 `EvidenceReport.subject.characteristic.code` maps as Equivalent to R4B `EvidenceReport.subject.characteristic.code` |
| EvidenceReport.subject.characteristic.exclude | EvidenceReport.subject.characteristic.exclude | Equivalent | R5 `EvidenceReport.subject.characteristic.exclude` maps as Equivalent to R4B `EvidenceReport.subject.characteristic.exclude` |
| EvidenceReport.subject.characteristic.extension | EvidenceReport.subject.characteristic.extension | SourceIsBroaderThanTarget | R5 `EvidenceReport.subject.characteristic.extension` maps as SourceIsBroaderThanTarget to R4B `EvidenceReport.subject.characteristic.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| EvidenceReport.subject.characteristic.id | EvidenceReport.subject.characteristic.id | Equivalent | R5 `EvidenceReport.subject.characteristic.id` maps as Equivalent to R4B `EvidenceReport.subject.characteristic.id` |
| EvidenceReport.subject.characteristic.modifierExtension | EvidenceReport.subject.characteristic.modifierExtension | SourceIsBroaderThanTarget | R5 `EvidenceReport.subject.characteristic.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `EvidenceReport.subject.characteristic.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| EvidenceReport.subject.characteristic.period | EvidenceReport.subject.characteristic.period | Equivalent | R5 `EvidenceReport.subject.characteristic.period` maps as Equivalent to R4B `EvidenceReport.subject.characteristic.period` |
| EvidenceReport.subject.characteristic.value[x] | EvidenceReport.subject.characteristic.value[x] | Equivalent | R5 `EvidenceReport.subject.characteristic.value[x]` maps as Equivalent to R4B `EvidenceReport.subject.characteristic.value[x]` |
| EvidenceReport.subject.extension | EvidenceReport.subject.extension | SourceIsBroaderThanTarget | R5 `EvidenceReport.subject.extension` maps as SourceIsBroaderThanTarget to R4B `EvidenceReport.subject.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| EvidenceReport.subject.id | EvidenceReport.subject.id | Equivalent | R5 `EvidenceReport.subject.id` maps as Equivalent to R4B `EvidenceReport.subject.id` |
| EvidenceReport.subject.modifierExtension | EvidenceReport.subject.modifierExtension | SourceIsBroaderThanTarget | R5 `EvidenceReport.subject.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `EvidenceReport.subject.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| EvidenceReport.subject.note | EvidenceReport.subject.note | SourceIsBroaderThanTarget | R5 `EvidenceReport.subject.note` maps as SourceIsBroaderThanTarget to R4B `EvidenceReport.subject.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4B `note` |
| EvidenceReport.text | EvidenceReport.text | Equivalent | R5 `EvidenceReport.text` maps as Equivalent to R4B `EvidenceReport.text` |
| EvidenceReport.type | EvidenceReport.type | Equivalent | R5 `EvidenceReport.type` maps as Equivalent to R4B `EvidenceReport.type` |
| EvidenceReport.url | EvidenceReport.url | Equivalent | R5 `EvidenceReport.url` maps as Equivalent to R4B `EvidenceReport.url` |
| EvidenceReport.useContext | EvidenceReport.useContext | Equivalent | R5 `EvidenceReport.useContext` maps as Equivalent to R4B `EvidenceReport.useContext` |

