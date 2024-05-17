Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Measure |  | The Measure resource provides the definition of a quality measure. | 83 | 60 |
| Target | Measure |  | The Measure resource provides the definition of a quality measure. | 110 | 84 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 1 |
Equivalent | 4 |
RelatedTo | 78 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Measure | Measure | Equivalent | R4B `Measure` maps as Equivalent to R5 `Measure` |
| Measure.approvalDate | Measure.approvalDate | Equivalent | R4B `Measure.approvalDate` maps as Equivalent to R5 `Measure.approvalDate` |
| Measure.author | Measure.author | Equivalent | R4B `Measure.author` maps as Equivalent to R5 `Measure.author` |
| Measure.clinicalRecommendationStatement | Measure.clinicalRecommendationStatement | Equivalent | R4B `Measure.clinicalRecommendationStatement` maps as Equivalent to R5 `Measure.clinicalRecommendationStatement` |
| Measure.compositeScoring | Measure.compositeScoring | Equivalent | R4B `Measure.compositeScoring` maps as Equivalent to R5 `Measure.compositeScoring` |
| Measure.contact | Measure.contact | Equivalent | R4B `Measure.contact` maps as Equivalent to R5 `Measure.contact` |
| Measure.contained | Measure.contained | Equivalent | R4B `Measure.contained` maps as Equivalent to R5 `Measure.contained` |
| Measure.copyright | Measure.copyright | Equivalent | R4B `Measure.copyright` maps as Equivalent to R5 `Measure.copyright` |
| Measure.date | Measure.date | Equivalent | R4B `Measure.date` maps as Equivalent to R5 `Measure.date` |
| Measure.definition | - | DoesNotExistInTarget | R4B `Measure.definition` does not appear in the target and has no mapping for `Measure`. |
| Measure.description | Measure.description | Equivalent | R4B `Measure.description` maps as Equivalent to R5 `Measure.description` |
| Measure.disclaimer | Measure.disclaimer | Equivalent | R4B `Measure.disclaimer` maps as Equivalent to R5 `Measure.disclaimer` |
| Measure.editor | Measure.editor | Equivalent | R4B `Measure.editor` maps as Equivalent to R5 `Measure.editor` |
| Measure.effectivePeriod | Measure.effectivePeriod | Equivalent | R4B `Measure.effectivePeriod` maps as Equivalent to R5 `Measure.effectivePeriod` |
| Measure.endorser | Measure.endorser | Equivalent | R4B `Measure.endorser` maps as Equivalent to R5 `Measure.endorser` |
| Measure.experimental | Measure.experimental | Equivalent | R4B `Measure.experimental` maps as Equivalent to R5 `Measure.experimental` |
| Measure.extension | Measure.extension | RelatedTo | R4B `Measure.extension` maps as RelatedTo to R5 `Measure.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Measure.group | Measure.group | Equivalent | R4B `Measure.group` maps as Equivalent to R5 `Measure.group` |
| Measure.group.code | Measure.group.code | Equivalent | R4B `Measure.group.code` maps as Equivalent to R5 `Measure.group.code` |
| Measure.group.description | Measure.group.description | SourceIsBroaderThanTarget | R4B `Measure.group.description` maps as SourceIsBroaderThanTarget to R5 `Measure.group.description` - description has change due to type change: R4B description string has no equivalent or mapped type in R5 description |
| Measure.group.extension | Measure.group.extension | RelatedTo | R4B `Measure.group.extension` maps as RelatedTo to R5 `Measure.group.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Measure.group.id | Measure.group.id | Equivalent | R4B `Measure.group.id` maps as Equivalent to R5 `Measure.group.id` |
| Measure.group.modifierExtension | Measure.group.modifierExtension | RelatedTo | R4B `Measure.group.modifierExtension` maps as RelatedTo to R5 `Measure.group.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Measure.group.population | Measure.group.population | Equivalent | R4B `Measure.group.population` maps as Equivalent to R5 `Measure.group.population` |
| Measure.group.population.code | Measure.group.population.code | Equivalent | R4B `Measure.group.population.code` maps as Equivalent to R5 `Measure.group.population.code` |
| Measure.group.population.criteria | Measure.group.population.criteria | SourceIsBroaderThanTarget | R4B `Measure.group.population.criteria` maps as SourceIsBroaderThanTarget to R5 `Measure.group.population.criteria` - criteria has change due to type change: R4B `criteria` `Expression` maps as SourceIsBroaderThanTarget for R5 `criteria` |
| Measure.group.population.description | Measure.group.population.description | SourceIsBroaderThanTarget | R4B `Measure.group.population.description` maps as SourceIsBroaderThanTarget to R5 `Measure.group.population.description` - description has change due to type change: R4B description string has no equivalent or mapped type in R5 description |
| Measure.group.population.extension | Measure.group.population.extension | RelatedTo | R4B `Measure.group.population.extension` maps as RelatedTo to R5 `Measure.group.population.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Measure.group.population.id | Measure.group.population.id | Equivalent | R4B `Measure.group.population.id` maps as Equivalent to R5 `Measure.group.population.id` |
| Measure.group.population.modifierExtension | Measure.group.population.modifierExtension | RelatedTo | R4B `Measure.group.population.modifierExtension` maps as RelatedTo to R5 `Measure.group.population.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Measure.group.stratifier | Measure.group.stratifier | Equivalent | R4B `Measure.group.stratifier` maps as Equivalent to R5 `Measure.group.stratifier` |
| Measure.group.stratifier.code | Measure.group.stratifier.code | Equivalent | R4B `Measure.group.stratifier.code` maps as Equivalent to R5 `Measure.group.stratifier.code` |
| Measure.group.stratifier.component | Measure.group.stratifier.component | Equivalent | R4B `Measure.group.stratifier.component` maps as Equivalent to R5 `Measure.group.stratifier.component` |
| Measure.group.stratifier.component.code | Measure.group.stratifier.component.code | Equivalent | R4B `Measure.group.stratifier.component.code` maps as Equivalent to R5 `Measure.group.stratifier.component.code` |
| Measure.group.stratifier.component.criteria | Measure.group.stratifier.component.criteria | SourceIsBroaderThanTarget | R4B `Measure.group.stratifier.component.criteria` maps as SourceIsBroaderThanTarget to R5 `Measure.group.stratifier.component.criteria` - criteria has change due to type change: R4B `criteria` `Expression` maps as SourceIsBroaderThanTarget for R5 `criteria` |
| Measure.group.stratifier.component.description | Measure.group.stratifier.component.description | SourceIsBroaderThanTarget | R4B `Measure.group.stratifier.component.description` maps as SourceIsBroaderThanTarget to R5 `Measure.group.stratifier.component.description` - description has change due to type change: R4B description string has no equivalent or mapped type in R5 description |
| Measure.group.stratifier.component.extension | Measure.group.stratifier.component.extension | RelatedTo | R4B `Measure.group.stratifier.component.extension` maps as RelatedTo to R5 `Measure.group.stratifier.component.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Measure.group.stratifier.component.id | Measure.group.stratifier.component.id | Equivalent | R4B `Measure.group.stratifier.component.id` maps as Equivalent to R5 `Measure.group.stratifier.component.id` |
| Measure.group.stratifier.component.modifierExtension | Measure.group.stratifier.component.modifierExtension | RelatedTo | R4B `Measure.group.stratifier.component.modifierExtension` maps as RelatedTo to R5 `Measure.group.stratifier.component.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Measure.group.stratifier.criteria | Measure.group.stratifier.criteria | SourceIsBroaderThanTarget | R4B `Measure.group.stratifier.criteria` maps as SourceIsBroaderThanTarget to R5 `Measure.group.stratifier.criteria` - criteria has change due to type change: R4B `criteria` `Expression` maps as SourceIsBroaderThanTarget for R5 `criteria` |
| Measure.group.stratifier.description | Measure.group.stratifier.description | SourceIsBroaderThanTarget | R4B `Measure.group.stratifier.description` maps as SourceIsBroaderThanTarget to R5 `Measure.group.stratifier.description` - description has change due to type change: R4B description string has no equivalent or mapped type in R5 description |
| Measure.group.stratifier.extension | Measure.group.stratifier.extension | RelatedTo | R4B `Measure.group.stratifier.extension` maps as RelatedTo to R5 `Measure.group.stratifier.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Measure.group.stratifier.id | Measure.group.stratifier.id | Equivalent | R4B `Measure.group.stratifier.id` maps as Equivalent to R5 `Measure.group.stratifier.id` |
| Measure.group.stratifier.modifierExtension | Measure.group.stratifier.modifierExtension | RelatedTo | R4B `Measure.group.stratifier.modifierExtension` maps as RelatedTo to R5 `Measure.group.stratifier.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Measure.guidance | Measure.guidance | Equivalent | R4B `Measure.guidance` maps as Equivalent to R5 `Measure.guidance` |
| Measure.id | Measure.id | Equivalent | R4B `Measure.id` maps as Equivalent to R5 `Measure.id` |
| Measure.identifier | Measure.identifier | Equivalent | R4B `Measure.identifier` maps as Equivalent to R5 `Measure.identifier` |
| Measure.implicitRules | Measure.implicitRules | Equivalent | R4B `Measure.implicitRules` maps as Equivalent to R5 `Measure.implicitRules` |
| Measure.improvementNotation | Measure.improvementNotation | Equivalent | R4B `Measure.improvementNotation` maps as Equivalent to R5 `Measure.improvementNotation` - improvementNotation has compatible required binding for non-code type: http://hl7.org/fhir/ValueSet/measure-improvement-notation|4.3.0 and http://hl7.org/fhir/ValueSet/measure-improvement-notation|5.0.0 (Equivalent) |
| Measure.jurisdiction | Measure.jurisdiction | Equivalent | R4B `Measure.jurisdiction` maps as Equivalent to R5 `Measure.jurisdiction` |
| Measure.language | Measure.language | RelatedTo | R4B `Measure.language` maps as RelatedTo to R5 `Measure.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Measure.lastReviewDate | Measure.lastReviewDate | Equivalent | R4B `Measure.lastReviewDate` maps as Equivalent to R5 `Measure.lastReviewDate` |
| Measure.library | Measure.library | Equivalent | R4B `Measure.library` maps as Equivalent to R5 `Measure.library` |
| Measure.meta | Measure.meta | Equivalent | R4B `Measure.meta` maps as Equivalent to R5 `Measure.meta` |
| Measure.modifierExtension | Measure.modifierExtension | RelatedTo | R4B `Measure.modifierExtension` maps as RelatedTo to R5 `Measure.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Measure.name | Measure.name | Equivalent | R4B `Measure.name` maps as Equivalent to R5 `Measure.name` |
| Measure.publisher | Measure.publisher | Equivalent | R4B `Measure.publisher` maps as Equivalent to R5 `Measure.publisher` |
| Measure.purpose | Measure.purpose | Equivalent | R4B `Measure.purpose` maps as Equivalent to R5 `Measure.purpose` |
| Measure.rateAggregation | Measure.rateAggregation | SourceIsBroaderThanTarget | R4B `Measure.rateAggregation` maps as SourceIsBroaderThanTarget to R5 `Measure.rateAggregation` - rateAggregation has change due to type change: R4B rateAggregation string has no equivalent or mapped type in R5 rateAggregation |
| Measure.rationale | Measure.rationale | Equivalent | R4B `Measure.rationale` maps as Equivalent to R5 `Measure.rationale` |
| Measure.relatedArtifact | Measure.relatedArtifact | Equivalent | R4B `Measure.relatedArtifact` maps as Equivalent to R5 `Measure.relatedArtifact` |
| Measure.reviewer | Measure.reviewer | Equivalent | R4B `Measure.reviewer` maps as Equivalent to R5 `Measure.reviewer` |
| Measure.riskAdjustment | Measure.riskAdjustment | SourceIsBroaderThanTarget | R4B `Measure.riskAdjustment` maps as SourceIsBroaderThanTarget to R5 `Measure.riskAdjustment` - riskAdjustment has change due to type change: R4B riskAdjustment string has no equivalent or mapped type in R5 riskAdjustment |
| Measure.scoring | Measure.scoring | Equivalent | R4B `Measure.scoring` maps as Equivalent to R5 `Measure.scoring` |
| Measure.status | Measure.status | Equivalent | R4B `Measure.status` maps as Equivalent to R5 `Measure.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|4.3.0 and http://hl7.org/fhir/ValueSet/publication-status|5.0.0 (Equivalent) |
| Measure.subject[x] | Measure.subject[x] | Equivalent | R4B `Measure.subject[x]` maps as Equivalent to R5 `Measure.subject[x]` |
| Measure.subtitle | Measure.subtitle | Equivalent | R4B `Measure.subtitle` maps as Equivalent to R5 `Measure.subtitle` |
| Measure.supplementalData | Measure.supplementalData | Equivalent | R4B `Measure.supplementalData` maps as Equivalent to R5 `Measure.supplementalData` |
| Measure.supplementalData.code | Measure.supplementalData.code | Equivalent | R4B `Measure.supplementalData.code` maps as Equivalent to R5 `Measure.supplementalData.code` |
| Measure.supplementalData.criteria | Measure.supplementalData.criteria | SourceIsBroaderThanTarget | R4B `Measure.supplementalData.criteria` maps as SourceIsBroaderThanTarget to R5 `Measure.supplementalData.criteria` - criteria has change due to type change: R4B `criteria` `Expression` maps as SourceIsBroaderThanTarget for R5 `criteria` |
| Measure.supplementalData.description | Measure.supplementalData.description | SourceIsBroaderThanTarget | R4B `Measure.supplementalData.description` maps as SourceIsBroaderThanTarget to R5 `Measure.supplementalData.description` - description has change due to type change: R4B description string has no equivalent or mapped type in R5 description |
| Measure.supplementalData.extension | Measure.supplementalData.extension | RelatedTo | R4B `Measure.supplementalData.extension` maps as RelatedTo to R5 `Measure.supplementalData.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Measure.supplementalData.id | Measure.supplementalData.id | Equivalent | R4B `Measure.supplementalData.id` maps as Equivalent to R5 `Measure.supplementalData.id` |
| Measure.supplementalData.modifierExtension | Measure.supplementalData.modifierExtension | RelatedTo | R4B `Measure.supplementalData.modifierExtension` maps as RelatedTo to R5 `Measure.supplementalData.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Measure.supplementalData.usage | Measure.supplementalData.usage | Equivalent | R4B `Measure.supplementalData.usage` maps as Equivalent to R5 `Measure.supplementalData.usage` |
| Measure.text | Measure.text | Equivalent | R4B `Measure.text` maps as Equivalent to R5 `Measure.text` |
| Measure.title | Measure.title | Equivalent | R4B `Measure.title` maps as Equivalent to R5 `Measure.title` |
| Measure.topic | Measure.topic | Equivalent | R4B `Measure.topic` maps as Equivalent to R5 `Measure.topic` |
| Measure.type | Measure.type | Equivalent | R4B `Measure.type` maps as Equivalent to R5 `Measure.type` |
| Measure.url | Measure.url | Equivalent | R4B `Measure.url` maps as Equivalent to R5 `Measure.url` |
| Measure.usage | Measure.usage | SourceIsBroaderThanTarget | R4B `Measure.usage` maps as SourceIsBroaderThanTarget to R5 `Measure.usage` - usage has change due to type change: R4B usage string has no equivalent or mapped type in R5 usage |
| Measure.useContext | Measure.useContext | Equivalent | R4B `Measure.useContext` maps as Equivalent to R5 `Measure.useContext` |
| Measure.version | Measure.version | Equivalent | R4B `Measure.version` maps as Equivalent to R5 `Measure.version` |

