Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | EventDefinition |  | The EventDefinition resource provides a reusable description of when a particular event can occur. | 39 | 31 |
| Target | EventDefinition |  | The EventDefinition resource provides a reusable description of when a particular event can occur. | 37 | 29 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 2 |
Equivalent | 31 |
SourceIsBroaderThanTarget | 5 |
SourceIsNarrowerThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| EventDefinition | EventDefinition | Equivalent | R5 `EventDefinition` maps as Equivalent to R4 `EventDefinition` |
| EventDefinition.approvalDate | EventDefinition.approvalDate | Equivalent | R5 `EventDefinition.approvalDate` maps as Equivalent to R4 `EventDefinition.approvalDate` |
| EventDefinition.author | EventDefinition.author | Equivalent | R5 `EventDefinition.author` maps as Equivalent to R4 `EventDefinition.author` |
| EventDefinition.contact | EventDefinition.contact | Equivalent | R5 `EventDefinition.contact` maps as Equivalent to R4 `EventDefinition.contact` |
| EventDefinition.contained | EventDefinition.contained | Equivalent | R5 `EventDefinition.contained` maps as Equivalent to R4 `EventDefinition.contained` |
| EventDefinition.copyright | EventDefinition.copyright | Equivalent | R5 `EventDefinition.copyright` maps as Equivalent to R4 `EventDefinition.copyright` |
| EventDefinition.copyrightLabel | - | DoesNotExistInTarget | R5 `EventDefinition.copyrightLabel` does not appear in the target and has no mapping for `EventDefinition`. |
| EventDefinition.date | EventDefinition.date | Equivalent | R5 `EventDefinition.date` maps as Equivalent to R4 `EventDefinition.date` |
| EventDefinition.description | EventDefinition.description | Equivalent | R5 `EventDefinition.description` maps as Equivalent to R4 `EventDefinition.description` |
| EventDefinition.editor | EventDefinition.editor | Equivalent | R5 `EventDefinition.editor` maps as Equivalent to R4 `EventDefinition.editor` |
| EventDefinition.effectivePeriod | EventDefinition.effectivePeriod | Equivalent | R5 `EventDefinition.effectivePeriod` maps as Equivalent to R4 `EventDefinition.effectivePeriod` |
| EventDefinition.endorser | EventDefinition.endorser | Equivalent | R5 `EventDefinition.endorser` maps as Equivalent to R4 `EventDefinition.endorser` |
| EventDefinition.experimental | EventDefinition.experimental | Equivalent | R5 `EventDefinition.experimental` maps as Equivalent to R4 `EventDefinition.experimental` |
| EventDefinition.extension | EventDefinition.extension | SourceIsBroaderThanTarget | R5 `EventDefinition.extension` maps as SourceIsBroaderThanTarget to R4 `EventDefinition.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| EventDefinition.id | EventDefinition.id | Equivalent | R5 `EventDefinition.id` maps as Equivalent to R4 `EventDefinition.id` |
| EventDefinition.identifier | EventDefinition.identifier | Equivalent | R5 `EventDefinition.identifier` maps as Equivalent to R4 `EventDefinition.identifier` |
| EventDefinition.implicitRules | EventDefinition.implicitRules | Equivalent | R5 `EventDefinition.implicitRules` maps as Equivalent to R4 `EventDefinition.implicitRules` |
| EventDefinition.jurisdiction | EventDefinition.jurisdiction | Equivalent | R5 `EventDefinition.jurisdiction` maps as Equivalent to R4 `EventDefinition.jurisdiction` |
| EventDefinition.language | EventDefinition.language | SourceIsNarrowerThanTarget | R5 `EventDefinition.language` maps as SourceIsNarrowerThanTarget to R4 `EventDefinition.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| EventDefinition.lastReviewDate | EventDefinition.lastReviewDate | Equivalent | R5 `EventDefinition.lastReviewDate` maps as Equivalent to R4 `EventDefinition.lastReviewDate` |
| EventDefinition.meta | EventDefinition.meta | Equivalent | R5 `EventDefinition.meta` maps as Equivalent to R4 `EventDefinition.meta` |
| EventDefinition.modifierExtension | EventDefinition.modifierExtension | SourceIsBroaderThanTarget | R5 `EventDefinition.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `EventDefinition.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| EventDefinition.name | EventDefinition.name | Equivalent | R5 `EventDefinition.name` maps as Equivalent to R4 `EventDefinition.name` |
| EventDefinition.publisher | EventDefinition.publisher | Equivalent | R5 `EventDefinition.publisher` maps as Equivalent to R4 `EventDefinition.publisher` |
| EventDefinition.purpose | EventDefinition.purpose | Equivalent | R5 `EventDefinition.purpose` maps as Equivalent to R4 `EventDefinition.purpose` |
| EventDefinition.relatedArtifact | EventDefinition.relatedArtifact | SourceIsBroaderThanTarget | R5 `EventDefinition.relatedArtifact` maps as SourceIsBroaderThanTarget to R4 `EventDefinition.relatedArtifact` - relatedArtifact has change due to type change: R5 `relatedArtifact` `RelatedArtifact` maps as SourceIsBroaderThanTarget for R4 `relatedArtifact` |
| EventDefinition.reviewer | EventDefinition.reviewer | Equivalent | R5 `EventDefinition.reviewer` maps as Equivalent to R4 `EventDefinition.reviewer` |
| EventDefinition.status | EventDefinition.status | Equivalent | R5 `EventDefinition.status` maps as Equivalent to R4 `EventDefinition.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|5.0.0 and http://hl7.org/fhir/ValueSet/publication-status|4.0.1 (Equivalent) |
| EventDefinition.subject[x] | EventDefinition.subject[x] | Equivalent | R5 `EventDefinition.subject[x]` maps as Equivalent to R4 `EventDefinition.subject[x]` |
| EventDefinition.subtitle | EventDefinition.subtitle | Equivalent | R5 `EventDefinition.subtitle` maps as Equivalent to R4 `EventDefinition.subtitle` |
| EventDefinition.text | EventDefinition.text | Equivalent | R5 `EventDefinition.text` maps as Equivalent to R4 `EventDefinition.text` |
| EventDefinition.title | EventDefinition.title | Equivalent | R5 `EventDefinition.title` maps as Equivalent to R4 `EventDefinition.title` |
| EventDefinition.topic | EventDefinition.topic | Equivalent | R5 `EventDefinition.topic` maps as Equivalent to R4 `EventDefinition.topic` |
| EventDefinition.trigger | EventDefinition.trigger | SourceIsBroaderThanTarget | R5 `EventDefinition.trigger` maps as SourceIsBroaderThanTarget to R4 `EventDefinition.trigger` - trigger has change due to type change: R5 `trigger` `TriggerDefinition` maps as SourceIsBroaderThanTarget for R4 `trigger` |
| EventDefinition.url | EventDefinition.url | Equivalent | R5 `EventDefinition.url` maps as Equivalent to R4 `EventDefinition.url` |
| EventDefinition.usage | EventDefinition.usage | SourceIsBroaderThanTarget | R5 `EventDefinition.usage` maps as SourceIsBroaderThanTarget to R4 `EventDefinition.usage` - usage has change due to type change: R5 usage markdown has no equivalent or mapped type in R4 usage |
| EventDefinition.useContext | EventDefinition.useContext | Equivalent | R5 `EventDefinition.useContext` maps as Equivalent to R4 `EventDefinition.useContext` |
| EventDefinition.version | EventDefinition.version | Equivalent | R5 `EventDefinition.version` maps as Equivalent to R4 `EventDefinition.version` |
| EventDefinition.versionAlgorithm[x] | - | DoesNotExistInTarget | R5 `EventDefinition.versionAlgorithm[x]` does not appear in the target and has no mapping for `EventDefinition`. |

