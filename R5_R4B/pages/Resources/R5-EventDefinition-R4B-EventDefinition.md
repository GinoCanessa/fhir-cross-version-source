Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | EventDefinition |  | The EventDefinition resource provides a reusable description of when a particular event can occur. | 39 | 31 |
| Target | EventDefinition |  | The EventDefinition resource provides a reusable description of when a particular event can occur. | 37 | 29 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 2 |
Equivalent | 4 |
RelatedTo | 33 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| EventDefinition | EventDefinition | Equivalent | R5 `EventDefinition` maps as Equivalent to R4B `EventDefinition` |
| EventDefinition.approvalDate | EventDefinition.approvalDate | Equivalent | R5 `EventDefinition.approvalDate` maps as Equivalent to R4B `EventDefinition.approvalDate` |
| EventDefinition.author | EventDefinition.author | Equivalent | R5 `EventDefinition.author` maps as Equivalent to R4B `EventDefinition.author` |
| EventDefinition.contact | EventDefinition.contact | Equivalent | R5 `EventDefinition.contact` maps as Equivalent to R4B `EventDefinition.contact` |
| EventDefinition.contained | EventDefinition.contained | Equivalent | R5 `EventDefinition.contained` maps as Equivalent to R4B `EventDefinition.contained` |
| EventDefinition.copyright | EventDefinition.copyright | Equivalent | R5 `EventDefinition.copyright` maps as Equivalent to R4B `EventDefinition.copyright` |
| EventDefinition.copyrightLabel | - | DoesNotExistInTarget | R5 `EventDefinition.copyrightLabel` does not appear in the target and has no mapping for `EventDefinition`. |
| EventDefinition.date | EventDefinition.date | Equivalent | R5 `EventDefinition.date` maps as Equivalent to R4B `EventDefinition.date` |
| EventDefinition.description | EventDefinition.description | Equivalent | R5 `EventDefinition.description` maps as Equivalent to R4B `EventDefinition.description` |
| EventDefinition.editor | EventDefinition.editor | Equivalent | R5 `EventDefinition.editor` maps as Equivalent to R4B `EventDefinition.editor` |
| EventDefinition.effectivePeriod | EventDefinition.effectivePeriod | Equivalent | R5 `EventDefinition.effectivePeriod` maps as Equivalent to R4B `EventDefinition.effectivePeriod` |
| EventDefinition.endorser | EventDefinition.endorser | Equivalent | R5 `EventDefinition.endorser` maps as Equivalent to R4B `EventDefinition.endorser` |
| EventDefinition.experimental | EventDefinition.experimental | Equivalent | R5 `EventDefinition.experimental` maps as Equivalent to R4B `EventDefinition.experimental` |
| EventDefinition.extension | EventDefinition.extension | SourceIsBroaderThanTarget | R5 `EventDefinition.extension` maps as SourceIsBroaderThanTarget to R4B `EventDefinition.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| EventDefinition.id | EventDefinition.id | Equivalent | R5 `EventDefinition.id` maps as Equivalent to R4B `EventDefinition.id` |
| EventDefinition.identifier | EventDefinition.identifier | Equivalent | R5 `EventDefinition.identifier` maps as Equivalent to R4B `EventDefinition.identifier` |
| EventDefinition.implicitRules | EventDefinition.implicitRules | Equivalent | R5 `EventDefinition.implicitRules` maps as Equivalent to R4B `EventDefinition.implicitRules` |
| EventDefinition.jurisdiction | EventDefinition.jurisdiction | Equivalent | R5 `EventDefinition.jurisdiction` maps as Equivalent to R4B `EventDefinition.jurisdiction` |
| EventDefinition.language | EventDefinition.language | RelatedTo | R5 `EventDefinition.language` maps as RelatedTo to R4B `EventDefinition.language` - language changed the binding strength from Required to Preferred |
| EventDefinition.lastReviewDate | EventDefinition.lastReviewDate | Equivalent | R5 `EventDefinition.lastReviewDate` maps as Equivalent to R4B `EventDefinition.lastReviewDate` |
| EventDefinition.meta | EventDefinition.meta | Equivalent | R5 `EventDefinition.meta` maps as Equivalent to R4B `EventDefinition.meta` |
| EventDefinition.modifierExtension | EventDefinition.modifierExtension | SourceIsBroaderThanTarget | R5 `EventDefinition.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `EventDefinition.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| EventDefinition.name | EventDefinition.name | Equivalent | R5 `EventDefinition.name` maps as Equivalent to R4B `EventDefinition.name` |
| EventDefinition.publisher | EventDefinition.publisher | Equivalent | R5 `EventDefinition.publisher` maps as Equivalent to R4B `EventDefinition.publisher` |
| EventDefinition.purpose | EventDefinition.purpose | Equivalent | R5 `EventDefinition.purpose` maps as Equivalent to R4B `EventDefinition.purpose` |
| EventDefinition.relatedArtifact | EventDefinition.relatedArtifact | Equivalent | R5 `EventDefinition.relatedArtifact` maps as Equivalent to R4B `EventDefinition.relatedArtifact` |
| EventDefinition.reviewer | EventDefinition.reviewer | Equivalent | R5 `EventDefinition.reviewer` maps as Equivalent to R4B `EventDefinition.reviewer` |
| EventDefinition.status | EventDefinition.status | Equivalent | R5 `EventDefinition.status` maps as Equivalent to R4B `EventDefinition.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|5.0.0 and http://hl7.org/fhir/ValueSet/publication-status|4.3.0 (Equivalent) |
| EventDefinition.subject[x] | EventDefinition.subject[x] | Equivalent | R5 `EventDefinition.subject[x]` maps as Equivalent to R4B `EventDefinition.subject[x]` |
| EventDefinition.subtitle | EventDefinition.subtitle | Equivalent | R5 `EventDefinition.subtitle` maps as Equivalent to R4B `EventDefinition.subtitle` |
| EventDefinition.text | EventDefinition.text | Equivalent | R5 `EventDefinition.text` maps as Equivalent to R4B `EventDefinition.text` |
| EventDefinition.title | EventDefinition.title | Equivalent | R5 `EventDefinition.title` maps as Equivalent to R4B `EventDefinition.title` |
| EventDefinition.topic | EventDefinition.topic | Equivalent | R5 `EventDefinition.topic` maps as Equivalent to R4B `EventDefinition.topic` |
| EventDefinition.trigger | EventDefinition.trigger | Equivalent | R5 `EventDefinition.trigger` maps as Equivalent to R4B `EventDefinition.trigger` |
| EventDefinition.url | EventDefinition.url | Equivalent | R5 `EventDefinition.url` maps as Equivalent to R4B `EventDefinition.url` |
| EventDefinition.usage | EventDefinition.usage | SourceIsBroaderThanTarget | R5 `EventDefinition.usage` maps as SourceIsBroaderThanTarget to R4B `EventDefinition.usage` - usage has change due to type change: R5 usage markdown has no equivalent or mapped type in R4B usage |
| EventDefinition.useContext | EventDefinition.useContext | Equivalent | R5 `EventDefinition.useContext` maps as Equivalent to R4B `EventDefinition.useContext` |
| EventDefinition.version | EventDefinition.version | Equivalent | R5 `EventDefinition.version` maps as Equivalent to R4B `EventDefinition.version` |
| EventDefinition.versionAlgorithm[x] | - | DoesNotExistInTarget | R5 `EventDefinition.versionAlgorithm[x]` does not appear in the target and has no mapping for `EventDefinition`. |

