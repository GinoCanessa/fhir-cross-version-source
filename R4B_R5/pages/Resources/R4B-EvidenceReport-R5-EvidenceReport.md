Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | EvidenceReport |  | The EvidenceReport Resource is a specialized container for a collection of resources and codable concepts, adapted to support compositions of Evidence, EvidenceVariable, and Citation resources and related concepts. | 59 | 39 |
| Target | EvidenceReport |  | The EvidenceReport Resource is a specialized container for a collection of resources and codeable concepts, adapted to support compositions of Evidence, EvidenceVariable, and Citation resources and related concepts. | 66 | 43 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 1 |
Equivalent | 4 |
RelatedTo | 54 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| EvidenceReport | EvidenceReport | Equivalent | R4B `EvidenceReport` maps as Equivalent to R5 `EvidenceReport` |
| EvidenceReport.author | EvidenceReport.author | Equivalent | R4B `EvidenceReport.author` maps as Equivalent to R5 `EvidenceReport.author` |
| EvidenceReport.citeAs[x] | EvidenceReport.citeAs[x] | Equivalent | R4B `EvidenceReport.citeAs[x]` maps as Equivalent to R5 `EvidenceReport.citeAs[x]` |
| EvidenceReport.contact | EvidenceReport.contact | Equivalent | R4B `EvidenceReport.contact` maps as Equivalent to R5 `EvidenceReport.contact` |
| EvidenceReport.contained | EvidenceReport.contained | Equivalent | R4B `EvidenceReport.contained` maps as Equivalent to R5 `EvidenceReport.contained` |
| EvidenceReport.editor | EvidenceReport.editor | Equivalent | R4B `EvidenceReport.editor` maps as Equivalent to R5 `EvidenceReport.editor` |
| EvidenceReport.endorser | EvidenceReport.endorser | Equivalent | R4B `EvidenceReport.endorser` maps as Equivalent to R5 `EvidenceReport.endorser` |
| EvidenceReport.extension | EvidenceReport.extension | RelatedTo | R4B `EvidenceReport.extension` maps as RelatedTo to R5 `EvidenceReport.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| EvidenceReport.id | EvidenceReport.id | Equivalent | R4B `EvidenceReport.id` maps as Equivalent to R5 `EvidenceReport.id` |
| EvidenceReport.identifier | EvidenceReport.identifier | Equivalent | R4B `EvidenceReport.identifier` maps as Equivalent to R5 `EvidenceReport.identifier` |
| EvidenceReport.implicitRules | EvidenceReport.implicitRules | Equivalent | R4B `EvidenceReport.implicitRules` maps as Equivalent to R5 `EvidenceReport.implicitRules` |
| EvidenceReport.language | EvidenceReport.language | RelatedTo | R4B `EvidenceReport.language` maps as RelatedTo to R5 `EvidenceReport.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| EvidenceReport.meta | EvidenceReport.meta | Equivalent | R4B `EvidenceReport.meta` maps as Equivalent to R5 `EvidenceReport.meta` |
| EvidenceReport.modifierExtension | EvidenceReport.modifierExtension | RelatedTo | R4B `EvidenceReport.modifierExtension` maps as RelatedTo to R5 `EvidenceReport.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| EvidenceReport.note | EvidenceReport.note | SourceIsNarrowerThanTarget | R4B `EvidenceReport.note` maps as SourceIsNarrowerThanTarget to R5 `EvidenceReport.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| EvidenceReport.publisher | EvidenceReport.publisher | Equivalent | R4B `EvidenceReport.publisher` maps as Equivalent to R5 `EvidenceReport.publisher` |
| EvidenceReport.relatedArtifact | EvidenceReport.relatedArtifact | Equivalent | R4B `EvidenceReport.relatedArtifact` maps as Equivalent to R5 `EvidenceReport.relatedArtifact` |
| EvidenceReport.relatedIdentifier | EvidenceReport.relatedIdentifier | Equivalent | R4B `EvidenceReport.relatedIdentifier` maps as Equivalent to R5 `EvidenceReport.relatedIdentifier` |
| EvidenceReport.relatesTo | EvidenceReport.relatesTo | Equivalent | R4B `EvidenceReport.relatesTo` maps as Equivalent to R5 `EvidenceReport.relatesTo` |
| EvidenceReport.relatesTo.code | EvidenceReport.relatesTo.code | Equivalent | R4B `EvidenceReport.relatesTo.code` maps as Equivalent to R5 `EvidenceReport.relatesTo.code` - code has compatible required binding for code type: http://hl7.org/fhir/ValueSet/report-relation-type|4.3.0 and http://hl7.org/fhir/ValueSet/report-relation-type|5.0.0 (Equivalent) |
| EvidenceReport.relatesTo.extension | EvidenceReport.relatesTo.extension | RelatedTo | R4B `EvidenceReport.relatesTo.extension` maps as RelatedTo to R5 `EvidenceReport.relatesTo.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| EvidenceReport.relatesTo.id | EvidenceReport.relatesTo.id | Equivalent | R4B `EvidenceReport.relatesTo.id` maps as Equivalent to R5 `EvidenceReport.relatesTo.id` |
| EvidenceReport.relatesTo.modifierExtension | EvidenceReport.relatesTo.modifierExtension | RelatedTo | R4B `EvidenceReport.relatesTo.modifierExtension` maps as RelatedTo to R5 `EvidenceReport.relatesTo.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| EvidenceReport.relatesTo.target[x] | - | DoesNotExistInTarget | R4B `EvidenceReport.relatesTo.target[x]` does not appear in the target and has no mapping for `EvidenceReport`. |
| EvidenceReport.reviewer | EvidenceReport.reviewer | Equivalent | R4B `EvidenceReport.reviewer` maps as Equivalent to R5 `EvidenceReport.reviewer` |
| EvidenceReport.section | EvidenceReport.section | Equivalent | R4B `EvidenceReport.section` maps as Equivalent to R5 `EvidenceReport.section` |
| EvidenceReport.section.author | EvidenceReport.section.author | RelatedTo | R4B `EvidenceReport.section.author` maps as RelatedTo to R5 `EvidenceReport.section.author` - author has change due to type change: R4B `author` `Reference` maps as RelatedTo for R5 `author` |
| EvidenceReport.section.emptyReason | EvidenceReport.section.emptyReason | Equivalent | R4B `EvidenceReport.section.emptyReason` maps as Equivalent to R5 `EvidenceReport.section.emptyReason` |
| EvidenceReport.section.entryClassifier | EvidenceReport.section.entryClassifier | Equivalent | R4B `EvidenceReport.section.entryClassifier` maps as Equivalent to R5 `EvidenceReport.section.entryClassifier` |
| EvidenceReport.section.entryQuantity | EvidenceReport.section.entryQuantity | Equivalent | R4B `EvidenceReport.section.entryQuantity` maps as Equivalent to R5 `EvidenceReport.section.entryQuantity` |
| EvidenceReport.section.entryReference | EvidenceReport.section.entryReference | Equivalent | R4B `EvidenceReport.section.entryReference` maps as Equivalent to R5 `EvidenceReport.section.entryReference` |
| EvidenceReport.section.extension | EvidenceReport.section.extension | RelatedTo | R4B `EvidenceReport.section.extension` maps as RelatedTo to R5 `EvidenceReport.section.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| EvidenceReport.section.focus | EvidenceReport.section.focus | Equivalent | R4B `EvidenceReport.section.focus` maps as Equivalent to R5 `EvidenceReport.section.focus` |
| EvidenceReport.section.focusReference | EvidenceReport.section.focusReference | Equivalent | R4B `EvidenceReport.section.focusReference` maps as Equivalent to R5 `EvidenceReport.section.focusReference` |
| EvidenceReport.section.id | EvidenceReport.section.id | Equivalent | R4B `EvidenceReport.section.id` maps as Equivalent to R5 `EvidenceReport.section.id` |
| EvidenceReport.section.mode | EvidenceReport.section.mode | Equivalent | R4B `EvidenceReport.section.mode` maps as Equivalent to R5 `EvidenceReport.section.mode` - mode has compatible required binding for code type: http://hl7.org/fhir/ValueSet/list-mode|4.3.0 and http://hl7.org/fhir/ValueSet/list-mode|5.0.0 (Equivalent) |
| EvidenceReport.section.modifierExtension | EvidenceReport.section.modifierExtension | RelatedTo | R4B `EvidenceReport.section.modifierExtension` maps as RelatedTo to R5 `EvidenceReport.section.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| EvidenceReport.section.orderedBy | EvidenceReport.section.orderedBy | Equivalent | R4B `EvidenceReport.section.orderedBy` maps as Equivalent to R5 `EvidenceReport.section.orderedBy` |
| EvidenceReport.section.section | EvidenceReport.section.section | Equivalent | R4B `EvidenceReport.section.section` maps as Equivalent to R5 `EvidenceReport.section.section` |
| EvidenceReport.section.text | EvidenceReport.section.text | Equivalent | R4B `EvidenceReport.section.text` maps as Equivalent to R5 `EvidenceReport.section.text` |
| EvidenceReport.section.title | EvidenceReport.section.title | Equivalent | R4B `EvidenceReport.section.title` maps as Equivalent to R5 `EvidenceReport.section.title` |
| EvidenceReport.status | EvidenceReport.status | Equivalent | R4B `EvidenceReport.status` maps as Equivalent to R5 `EvidenceReport.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|4.3.0 and http://hl7.org/fhir/ValueSet/publication-status|5.0.0 (Equivalent) |
| EvidenceReport.subject | EvidenceReport.subject | Equivalent | R4B `EvidenceReport.subject` maps as Equivalent to R5 `EvidenceReport.subject` |
| EvidenceReport.subject.characteristic | EvidenceReport.subject.characteristic | Equivalent | R4B `EvidenceReport.subject.characteristic` maps as Equivalent to R5 `EvidenceReport.subject.characteristic` |
| EvidenceReport.subject.characteristic.code | EvidenceReport.subject.characteristic.code | Equivalent | R4B `EvidenceReport.subject.characteristic.code` maps as Equivalent to R5 `EvidenceReport.subject.characteristic.code` |
| EvidenceReport.subject.characteristic.exclude | EvidenceReport.subject.characteristic.exclude | Equivalent | R4B `EvidenceReport.subject.characteristic.exclude` maps as Equivalent to R5 `EvidenceReport.subject.characteristic.exclude` |
| EvidenceReport.subject.characteristic.extension | EvidenceReport.subject.characteristic.extension | RelatedTo | R4B `EvidenceReport.subject.characteristic.extension` maps as RelatedTo to R5 `EvidenceReport.subject.characteristic.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| EvidenceReport.subject.characteristic.id | EvidenceReport.subject.characteristic.id | Equivalent | R4B `EvidenceReport.subject.characteristic.id` maps as Equivalent to R5 `EvidenceReport.subject.characteristic.id` |
| EvidenceReport.subject.characteristic.modifierExtension | EvidenceReport.subject.characteristic.modifierExtension | RelatedTo | R4B `EvidenceReport.subject.characteristic.modifierExtension` maps as RelatedTo to R5 `EvidenceReport.subject.characteristic.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| EvidenceReport.subject.characteristic.period | EvidenceReport.subject.characteristic.period | Equivalent | R4B `EvidenceReport.subject.characteristic.period` maps as Equivalent to R5 `EvidenceReport.subject.characteristic.period` |
| EvidenceReport.subject.characteristic.value[x] | EvidenceReport.subject.characteristic.value[x] | Equivalent | R4B `EvidenceReport.subject.characteristic.value[x]` maps as Equivalent to R5 `EvidenceReport.subject.characteristic.value[x]` |
| EvidenceReport.subject.extension | EvidenceReport.subject.extension | RelatedTo | R4B `EvidenceReport.subject.extension` maps as RelatedTo to R5 `EvidenceReport.subject.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| EvidenceReport.subject.id | EvidenceReport.subject.id | Equivalent | R4B `EvidenceReport.subject.id` maps as Equivalent to R5 `EvidenceReport.subject.id` |
| EvidenceReport.subject.modifierExtension | EvidenceReport.subject.modifierExtension | RelatedTo | R4B `EvidenceReport.subject.modifierExtension` maps as RelatedTo to R5 `EvidenceReport.subject.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| EvidenceReport.subject.note | EvidenceReport.subject.note | SourceIsNarrowerThanTarget | R4B `EvidenceReport.subject.note` maps as SourceIsNarrowerThanTarget to R5 `EvidenceReport.subject.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| EvidenceReport.text | EvidenceReport.text | Equivalent | R4B `EvidenceReport.text` maps as Equivalent to R5 `EvidenceReport.text` |
| EvidenceReport.type | EvidenceReport.type | Equivalent | R4B `EvidenceReport.type` maps as Equivalent to R5 `EvidenceReport.type` |
| EvidenceReport.url | EvidenceReport.url | Equivalent | R4B `EvidenceReport.url` maps as Equivalent to R5 `EvidenceReport.url` |
| EvidenceReport.useContext | EvidenceReport.useContext | Equivalent | R4B `EvidenceReport.useContext` maps as Equivalent to R5 `EvidenceReport.useContext` |

