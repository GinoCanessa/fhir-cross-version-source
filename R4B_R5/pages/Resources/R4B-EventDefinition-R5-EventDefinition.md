Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | EventDefinition |  | The EventDefinition resource provides a reusable description of when a particular event can occur. | 37 | 29 |
| Target | EventDefinition |  | The EventDefinition resource provides a reusable description of when a particular event can occur. | 39 | 31 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 33 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| EventDefinition | EventDefinition | Equivalent | R4B `EventDefinition` maps as Equivalent to R5 `EventDefinition` |
| EventDefinition.approvalDate | EventDefinition.approvalDate | Equivalent | R4B `EventDefinition.approvalDate` maps as Equivalent to R5 `EventDefinition.approvalDate` |
| EventDefinition.author | EventDefinition.author | Equivalent | R4B `EventDefinition.author` maps as Equivalent to R5 `EventDefinition.author` |
| EventDefinition.contact | EventDefinition.contact | Equivalent | R4B `EventDefinition.contact` maps as Equivalent to R5 `EventDefinition.contact` |
| EventDefinition.contained | EventDefinition.contained | Equivalent | R4B `EventDefinition.contained` maps as Equivalent to R5 `EventDefinition.contained` |
| EventDefinition.copyright | EventDefinition.copyright | Equivalent | R4B `EventDefinition.copyright` maps as Equivalent to R5 `EventDefinition.copyright` |
| EventDefinition.date | EventDefinition.date | Equivalent | R4B `EventDefinition.date` maps as Equivalent to R5 `EventDefinition.date` |
| EventDefinition.description | EventDefinition.description | Equivalent | R4B `EventDefinition.description` maps as Equivalent to R5 `EventDefinition.description` |
| EventDefinition.editor | EventDefinition.editor | Equivalent | R4B `EventDefinition.editor` maps as Equivalent to R5 `EventDefinition.editor` |
| EventDefinition.effectivePeriod | EventDefinition.effectivePeriod | Equivalent | R4B `EventDefinition.effectivePeriod` maps as Equivalent to R5 `EventDefinition.effectivePeriod` |
| EventDefinition.endorser | EventDefinition.endorser | Equivalent | R4B `EventDefinition.endorser` maps as Equivalent to R5 `EventDefinition.endorser` |
| EventDefinition.experimental | EventDefinition.experimental | Equivalent | R4B `EventDefinition.experimental` maps as Equivalent to R5 `EventDefinition.experimental` |
| EventDefinition.extension | EventDefinition.extension | RelatedTo | R4B `EventDefinition.extension` maps as RelatedTo to R5 `EventDefinition.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| EventDefinition.id | EventDefinition.id | Equivalent | R4B `EventDefinition.id` maps as Equivalent to R5 `EventDefinition.id` |
| EventDefinition.identifier | EventDefinition.identifier | Equivalent | R4B `EventDefinition.identifier` maps as Equivalent to R5 `EventDefinition.identifier` |
| EventDefinition.implicitRules | EventDefinition.implicitRules | Equivalent | R4B `EventDefinition.implicitRules` maps as Equivalent to R5 `EventDefinition.implicitRules` |
| EventDefinition.jurisdiction | EventDefinition.jurisdiction | Equivalent | R4B `EventDefinition.jurisdiction` maps as Equivalent to R5 `EventDefinition.jurisdiction` |
| EventDefinition.language | EventDefinition.language | RelatedTo | R4B `EventDefinition.language` maps as RelatedTo to R5 `EventDefinition.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| EventDefinition.lastReviewDate | EventDefinition.lastReviewDate | Equivalent | R4B `EventDefinition.lastReviewDate` maps as Equivalent to R5 `EventDefinition.lastReviewDate` |
| EventDefinition.meta | EventDefinition.meta | Equivalent | R4B `EventDefinition.meta` maps as Equivalent to R5 `EventDefinition.meta` |
| EventDefinition.modifierExtension | EventDefinition.modifierExtension | RelatedTo | R4B `EventDefinition.modifierExtension` maps as RelatedTo to R5 `EventDefinition.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| EventDefinition.name | EventDefinition.name | Equivalent | R4B `EventDefinition.name` maps as Equivalent to R5 `EventDefinition.name` |
| EventDefinition.publisher | EventDefinition.publisher | Equivalent | R4B `EventDefinition.publisher` maps as Equivalent to R5 `EventDefinition.publisher` |
| EventDefinition.purpose | EventDefinition.purpose | Equivalent | R4B `EventDefinition.purpose` maps as Equivalent to R5 `EventDefinition.purpose` |
| EventDefinition.relatedArtifact | EventDefinition.relatedArtifact | Equivalent | R4B `EventDefinition.relatedArtifact` maps as Equivalent to R5 `EventDefinition.relatedArtifact` |
| EventDefinition.reviewer | EventDefinition.reviewer | Equivalent | R4B `EventDefinition.reviewer` maps as Equivalent to R5 `EventDefinition.reviewer` |
| EventDefinition.status | EventDefinition.status | Equivalent | R4B `EventDefinition.status` maps as Equivalent to R5 `EventDefinition.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|4.3.0 and http://hl7.org/fhir/ValueSet/publication-status|5.0.0 (Equivalent) |
| EventDefinition.subject[x] | EventDefinition.subject[x] | Equivalent | R4B `EventDefinition.subject[x]` maps as Equivalent to R5 `EventDefinition.subject[x]` |
| EventDefinition.subtitle | EventDefinition.subtitle | Equivalent | R4B `EventDefinition.subtitle` maps as Equivalent to R5 `EventDefinition.subtitle` |
| EventDefinition.text | EventDefinition.text | Equivalent | R4B `EventDefinition.text` maps as Equivalent to R5 `EventDefinition.text` |
| EventDefinition.title | EventDefinition.title | Equivalent | R4B `EventDefinition.title` maps as Equivalent to R5 `EventDefinition.title` |
| EventDefinition.topic | EventDefinition.topic | Equivalent | R4B `EventDefinition.topic` maps as Equivalent to R5 `EventDefinition.topic` |
| EventDefinition.trigger | EventDefinition.trigger | Equivalent | R4B `EventDefinition.trigger` maps as Equivalent to R5 `EventDefinition.trigger` |
| EventDefinition.url | EventDefinition.url | Equivalent | R4B `EventDefinition.url` maps as Equivalent to R5 `EventDefinition.url` |
| EventDefinition.usage | EventDefinition.usage | SourceIsBroaderThanTarget | R4B `EventDefinition.usage` maps as SourceIsBroaderThanTarget to R5 `EventDefinition.usage` - usage has change due to type change: R4B usage string has no equivalent or mapped type in R5 usage |
| EventDefinition.useContext | EventDefinition.useContext | Equivalent | R4B `EventDefinition.useContext` maps as Equivalent to R5 `EventDefinition.useContext` |
| EventDefinition.version | EventDefinition.version | Equivalent | R4B `EventDefinition.version` maps as Equivalent to R5 `EventDefinition.version` |

