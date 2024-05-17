Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Library |  | The Library resource is a general-purpose container for knowledge asset definitions. It can be used to describe and expose existing knowledge assets such as logic libraries and information model descriptions, as well as to describe a collection of knowledge assets. | 40 | 32 |
| Target | Library |  | The Library resource is a general-purpose container for knowledge asset definitions. It can be used to describe and expose existing knowledge assets such as logic libraries and information model descriptions, as well as to describe a collection of knowledge assets. | 42 | 34 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 36 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Library | Library | Equivalent | R4B `Library` maps as Equivalent to R5 `Library` |
| Library.approvalDate | Library.approvalDate | Equivalent | R4B `Library.approvalDate` maps as Equivalent to R5 `Library.approvalDate` |
| Library.author | Library.author | Equivalent | R4B `Library.author` maps as Equivalent to R5 `Library.author` |
| Library.contact | Library.contact | Equivalent | R4B `Library.contact` maps as Equivalent to R5 `Library.contact` |
| Library.contained | Library.contained | Equivalent | R4B `Library.contained` maps as Equivalent to R5 `Library.contained` |
| Library.content | Library.content | RelatedTo | R4B `Library.content` maps as RelatedTo to R5 `Library.content` - content has change due to type change: R4B `content` `Attachment` maps as RelatedTo for R5 `content` |
| Library.copyright | Library.copyright | Equivalent | R4B `Library.copyright` maps as Equivalent to R5 `Library.copyright` |
| Library.dataRequirement | Library.dataRequirement | RelatedTo | R4B `Library.dataRequirement` maps as RelatedTo to R5 `Library.dataRequirement` - dataRequirement has change due to type change: R4B `dataRequirement` `DataRequirement` maps as RelatedTo for R5 `dataRequirement` |
| Library.date | Library.date | Equivalent | R4B `Library.date` maps as Equivalent to R5 `Library.date` |
| Library.description | Library.description | Equivalent | R4B `Library.description` maps as Equivalent to R5 `Library.description` |
| Library.editor | Library.editor | Equivalent | R4B `Library.editor` maps as Equivalent to R5 `Library.editor` |
| Library.effectivePeriod | Library.effectivePeriod | Equivalent | R4B `Library.effectivePeriod` maps as Equivalent to R5 `Library.effectivePeriod` |
| Library.endorser | Library.endorser | Equivalent | R4B `Library.endorser` maps as Equivalent to R5 `Library.endorser` |
| Library.experimental | Library.experimental | Equivalent | R4B `Library.experimental` maps as Equivalent to R5 `Library.experimental` |
| Library.extension | Library.extension | RelatedTo | R4B `Library.extension` maps as RelatedTo to R5 `Library.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Library.id | Library.id | Equivalent | R4B `Library.id` maps as Equivalent to R5 `Library.id` |
| Library.identifier | Library.identifier | Equivalent | R4B `Library.identifier` maps as Equivalent to R5 `Library.identifier` |
| Library.implicitRules | Library.implicitRules | Equivalent | R4B `Library.implicitRules` maps as Equivalent to R5 `Library.implicitRules` |
| Library.jurisdiction | Library.jurisdiction | Equivalent | R4B `Library.jurisdiction` maps as Equivalent to R5 `Library.jurisdiction` |
| Library.language | Library.language | RelatedTo | R4B `Library.language` maps as RelatedTo to R5 `Library.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Library.lastReviewDate | Library.lastReviewDate | Equivalent | R4B `Library.lastReviewDate` maps as Equivalent to R5 `Library.lastReviewDate` |
| Library.meta | Library.meta | Equivalent | R4B `Library.meta` maps as Equivalent to R5 `Library.meta` |
| Library.modifierExtension | Library.modifierExtension | RelatedTo | R4B `Library.modifierExtension` maps as RelatedTo to R5 `Library.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Library.name | Library.name | Equivalent | R4B `Library.name` maps as Equivalent to R5 `Library.name` |
| Library.parameter | Library.parameter | RelatedTo | R4B `Library.parameter` maps as RelatedTo to R5 `Library.parameter` - parameter has change due to type change: R4B `parameter` `ParameterDefinition` maps as RelatedTo for R5 `parameter` |
| Library.publisher | Library.publisher | Equivalent | R4B `Library.publisher` maps as Equivalent to R5 `Library.publisher` |
| Library.purpose | Library.purpose | Equivalent | R4B `Library.purpose` maps as Equivalent to R5 `Library.purpose` |
| Library.relatedArtifact | Library.relatedArtifact | Equivalent | R4B `Library.relatedArtifact` maps as Equivalent to R5 `Library.relatedArtifact` |
| Library.reviewer | Library.reviewer | Equivalent | R4B `Library.reviewer` maps as Equivalent to R5 `Library.reviewer` |
| Library.status | Library.status | Equivalent | R4B `Library.status` maps as Equivalent to R5 `Library.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|4.3.0 and http://hl7.org/fhir/ValueSet/publication-status|5.0.0 (Equivalent) |
| Library.subject[x] | Library.subject[x] | Equivalent | R4B `Library.subject[x]` maps as Equivalent to R5 `Library.subject[x]` |
| Library.subtitle | Library.subtitle | Equivalent | R4B `Library.subtitle` maps as Equivalent to R5 `Library.subtitle` |
| Library.text | Library.text | Equivalent | R4B `Library.text` maps as Equivalent to R5 `Library.text` |
| Library.title | Library.title | Equivalent | R4B `Library.title` maps as Equivalent to R5 `Library.title` |
| Library.topic | Library.topic | Equivalent | R4B `Library.topic` maps as Equivalent to R5 `Library.topic` |
| Library.type | Library.type | Equivalent | R4B `Library.type` maps as Equivalent to R5 `Library.type` |
| Library.url | Library.url | Equivalent | R4B `Library.url` maps as Equivalent to R5 `Library.url` |
| Library.usage | Library.usage | SourceIsBroaderThanTarget | R4B `Library.usage` maps as SourceIsBroaderThanTarget to R5 `Library.usage` - usage has change due to type change: R4B usage string has no equivalent or mapped type in R5 usage |
| Library.useContext | Library.useContext | Equivalent | R4B `Library.useContext` maps as Equivalent to R5 `Library.useContext` |
| Library.version | Library.version | Equivalent | R4B `Library.version` maps as Equivalent to R5 `Library.version` |

