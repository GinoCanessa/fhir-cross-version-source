Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Library |  | The Library resource is a general-purpose container for knowledge asset definitions. It can be used to describe and expose existing knowledge assets such as logic libraries and information model descriptions, as well as to describe a collection of knowledge assets. | 42 | 34 |
| Target | Library |  | The Library resource is a general-purpose container for knowledge asset definitions. It can be used to describe and expose existing knowledge assets such as logic libraries and information model descriptions, as well as to describe a collection of knowledge assets. | 40 | 32 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 2 |
Equivalent | 32 |
RelatedTo | 3 |
SourceIsBroaderThanTarget | 4 |
SourceIsNarrowerThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Library | Library | Equivalent | R5 `Library` maps as Equivalent to R4 `Library` |
| Library.approvalDate | Library.approvalDate | Equivalent | R5 `Library.approvalDate` maps as Equivalent to R4 `Library.approvalDate` |
| Library.author | Library.author | Equivalent | R5 `Library.author` maps as Equivalent to R4 `Library.author` |
| Library.contact | Library.contact | Equivalent | R5 `Library.contact` maps as Equivalent to R4 `Library.contact` |
| Library.contained | Library.contained | Equivalent | R5 `Library.contained` maps as Equivalent to R4 `Library.contained` |
| Library.content | Library.content | RelatedTo | R5 `Library.content` maps as RelatedTo to R4 `Library.content` - content has change due to type change: R5 `content` `Attachment` maps as RelatedTo for R4 `content` |
| Library.copyright | Library.copyright | Equivalent | R5 `Library.copyright` maps as Equivalent to R4 `Library.copyright` |
| Library.copyrightLabel | - | DoesNotExistInTarget | R5 `Library.copyrightLabel` does not appear in the target and has no mapping for `Library`. |
| Library.dataRequirement | Library.dataRequirement | RelatedTo | R5 `Library.dataRequirement` maps as RelatedTo to R4 `Library.dataRequirement` - dataRequirement has change due to type change: R5 `dataRequirement` `DataRequirement` maps as RelatedTo for R4 `dataRequirement` |
| Library.date | Library.date | Equivalent | R5 `Library.date` maps as Equivalent to R4 `Library.date` |
| Library.description | Library.description | Equivalent | R5 `Library.description` maps as Equivalent to R4 `Library.description` |
| Library.editor | Library.editor | Equivalent | R5 `Library.editor` maps as Equivalent to R4 `Library.editor` |
| Library.effectivePeriod | Library.effectivePeriod | Equivalent | R5 `Library.effectivePeriod` maps as Equivalent to R4 `Library.effectivePeriod` |
| Library.endorser | Library.endorser | Equivalent | R5 `Library.endorser` maps as Equivalent to R4 `Library.endorser` |
| Library.experimental | Library.experimental | Equivalent | R5 `Library.experimental` maps as Equivalent to R4 `Library.experimental` |
| Library.extension | Library.extension | SourceIsBroaderThanTarget | R5 `Library.extension` maps as SourceIsBroaderThanTarget to R4 `Library.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Library.id | Library.id | Equivalent | R5 `Library.id` maps as Equivalent to R4 `Library.id` |
| Library.identifier | Library.identifier | Equivalent | R5 `Library.identifier` maps as Equivalent to R4 `Library.identifier` |
| Library.implicitRules | Library.implicitRules | Equivalent | R5 `Library.implicitRules` maps as Equivalent to R4 `Library.implicitRules` |
| Library.jurisdiction | Library.jurisdiction | Equivalent | R5 `Library.jurisdiction` maps as Equivalent to R4 `Library.jurisdiction` |
| Library.language | Library.language | SourceIsNarrowerThanTarget | R5 `Library.language` maps as SourceIsNarrowerThanTarget to R4 `Library.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| Library.lastReviewDate | Library.lastReviewDate | Equivalent | R5 `Library.lastReviewDate` maps as Equivalent to R4 `Library.lastReviewDate` |
| Library.meta | Library.meta | Equivalent | R5 `Library.meta` maps as Equivalent to R4 `Library.meta` |
| Library.modifierExtension | Library.modifierExtension | SourceIsBroaderThanTarget | R5 `Library.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Library.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Library.name | Library.name | Equivalent | R5 `Library.name` maps as Equivalent to R4 `Library.name` |
| Library.parameter | Library.parameter | RelatedTo | R5 `Library.parameter` maps as RelatedTo to R4 `Library.parameter` - parameter has change due to type change: R5 `parameter` `ParameterDefinition` maps as RelatedTo for R4 `parameter` |
| Library.publisher | Library.publisher | Equivalent | R5 `Library.publisher` maps as Equivalent to R4 `Library.publisher` |
| Library.purpose | Library.purpose | Equivalent | R5 `Library.purpose` maps as Equivalent to R4 `Library.purpose` |
| Library.relatedArtifact | Library.relatedArtifact | SourceIsBroaderThanTarget | R5 `Library.relatedArtifact` maps as SourceIsBroaderThanTarget to R4 `Library.relatedArtifact` - relatedArtifact has change due to type change: R5 `relatedArtifact` `RelatedArtifact` maps as SourceIsBroaderThanTarget for R4 `relatedArtifact` |
| Library.reviewer | Library.reviewer | Equivalent | R5 `Library.reviewer` maps as Equivalent to R4 `Library.reviewer` |
| Library.status | Library.status | Equivalent | R5 `Library.status` maps as Equivalent to R4 `Library.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|5.0.0 and http://hl7.org/fhir/ValueSet/publication-status|4.0.1 (Equivalent) |
| Library.subject[x] | Library.subject[x] | Equivalent | R5 `Library.subject[x]` maps as Equivalent to R4 `Library.subject[x]` |
| Library.subtitle | Library.subtitle | Equivalent | R5 `Library.subtitle` maps as Equivalent to R4 `Library.subtitle` |
| Library.text | Library.text | Equivalent | R5 `Library.text` maps as Equivalent to R4 `Library.text` |
| Library.title | Library.title | Equivalent | R5 `Library.title` maps as Equivalent to R4 `Library.title` |
| Library.topic | Library.topic | Equivalent | R5 `Library.topic` maps as Equivalent to R4 `Library.topic` |
| Library.type | Library.type | Equivalent | R5 `Library.type` maps as Equivalent to R4 `Library.type` |
| Library.url | Library.url | Equivalent | R5 `Library.url` maps as Equivalent to R4 `Library.url` |
| Library.usage | Library.usage | SourceIsBroaderThanTarget | R5 `Library.usage` maps as SourceIsBroaderThanTarget to R4 `Library.usage` - usage has change due to type change: R5 usage markdown has no equivalent or mapped type in R4 usage |
| Library.useContext | Library.useContext | Equivalent | R5 `Library.useContext` maps as Equivalent to R4 `Library.useContext` |
| Library.version | Library.version | Equivalent | R5 `Library.version` maps as Equivalent to R4 `Library.version` |
| Library.versionAlgorithm[x] | - | DoesNotExistInTarget | R5 `Library.versionAlgorithm[x]` does not appear in the target and has no mapping for `Library`. |

