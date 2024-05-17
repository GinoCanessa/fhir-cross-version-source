Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Measure |  | The Measure resource provides the definition of a quality measure. | 110 | 84 |
| Target | Measure |  | The Measure resource provides the definition of a quality measure. | 83 | 60 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 28 |
Equivalent | 4 |
RelatedTo | 78 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Measure | Measure | Equivalent | R5 `Measure` maps as Equivalent to R4B `Measure` |
| Measure.approvalDate | Measure.approvalDate | Equivalent | R5 `Measure.approvalDate` maps as Equivalent to R4B `Measure.approvalDate` |
| Measure.author | Measure.author | Equivalent | R5 `Measure.author` maps as Equivalent to R4B `Measure.author` |
| Measure.basis | - | DoesNotExistInTarget | R5 `Measure.basis` does not appear in the target and has no mapping for `Measure`. |
| Measure.clinicalRecommendationStatement | Measure.clinicalRecommendationStatement | Equivalent | R5 `Measure.clinicalRecommendationStatement` maps as Equivalent to R4B `Measure.clinicalRecommendationStatement` |
| Measure.compositeScoring | Measure.compositeScoring | Equivalent | R5 `Measure.compositeScoring` maps as Equivalent to R4B `Measure.compositeScoring` |
| Measure.contact | Measure.contact | Equivalent | R5 `Measure.contact` maps as Equivalent to R4B `Measure.contact` |
| Measure.contained | Measure.contained | Equivalent | R5 `Measure.contained` maps as Equivalent to R4B `Measure.contained` |
| Measure.copyright | Measure.copyright | Equivalent | R5 `Measure.copyright` maps as Equivalent to R4B `Measure.copyright` |
| Measure.copyrightLabel | - | DoesNotExistInTarget | R5 `Measure.copyrightLabel` does not appear in the target and has no mapping for `Measure`. |
| Measure.date | Measure.date | Equivalent | R5 `Measure.date` maps as Equivalent to R4B `Measure.date` |
| Measure.description | Measure.description | Equivalent | R5 `Measure.description` maps as Equivalent to R4B `Measure.description` |
| Measure.disclaimer | Measure.disclaimer | Equivalent | R5 `Measure.disclaimer` maps as Equivalent to R4B `Measure.disclaimer` |
| Measure.editor | Measure.editor | Equivalent | R5 `Measure.editor` maps as Equivalent to R4B `Measure.editor` |
| Measure.effectivePeriod | Measure.effectivePeriod | Equivalent | R5 `Measure.effectivePeriod` maps as Equivalent to R4B `Measure.effectivePeriod` |
| Measure.endorser | Measure.endorser | Equivalent | R5 `Measure.endorser` maps as Equivalent to R4B `Measure.endorser` |
| Measure.experimental | Measure.experimental | Equivalent | R5 `Measure.experimental` maps as Equivalent to R4B `Measure.experimental` |
| Measure.extension | Measure.extension | SourceIsBroaderThanTarget | R5 `Measure.extension` maps as SourceIsBroaderThanTarget to R4B `Measure.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Measure.group | Measure.group | Equivalent | R5 `Measure.group` maps as Equivalent to R4B `Measure.group` |
| Measure.group.basis | - | DoesNotExistInTarget | R5 `Measure.group.basis` does not appear in the target and has no mapping for `Measure`. |
| Measure.group.code | Measure.group.code | Equivalent | R5 `Measure.group.code` maps as Equivalent to R4B `Measure.group.code` |
| Measure.group.description | Measure.group.description | SourceIsBroaderThanTarget | R5 `Measure.group.description` maps as SourceIsBroaderThanTarget to R4B `Measure.group.description` - description has change due to type change: R5 description markdown has no equivalent or mapped type in R4B description |
| Measure.group.extension | Measure.group.extension | SourceIsBroaderThanTarget | R5 `Measure.group.extension` maps as SourceIsBroaderThanTarget to R4B `Measure.group.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Measure.group.id | Measure.group.id | Equivalent | R5 `Measure.group.id` maps as Equivalent to R4B `Measure.group.id` |
| Measure.group.improvementNotation | - | DoesNotExistInTarget | R5 `Measure.group.improvementNotation` does not appear in the target and has no mapping for `Measure`. |
| Measure.group.library | - | DoesNotExistInTarget | R5 `Measure.group.library` does not appear in the target and has no mapping for `Measure`. |
| Measure.group.linkId | - | DoesNotExistInTarget | R5 `Measure.group.linkId` does not appear in the target and has no mapping for `Measure`. |
| Measure.group.modifierExtension | Measure.group.modifierExtension | SourceIsBroaderThanTarget | R5 `Measure.group.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Measure.group.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Measure.group.population | Measure.group.population | Equivalent | R5 `Measure.group.population` maps as Equivalent to R4B `Measure.group.population` |
| Measure.group.population.aggregateMethod | - | DoesNotExistInTarget | R5 `Measure.group.population.aggregateMethod` does not appear in the target and has no mapping for `Measure`. |
| Measure.group.population.code | Measure.group.population.code | Equivalent | R5 `Measure.group.population.code` maps as Equivalent to R4B `Measure.group.population.code` |
| Measure.group.population.criteria | Measure.group.population.criteria | RelatedTo | R5 `Measure.group.population.criteria` maps as RelatedTo to R4B `Measure.group.population.criteria` - criteria made the element mandatory; criteria increased the minimum cardinality from 0 to 1; criteria has change due to type change: R5 `criteria` `Expression` maps as RelatedTo for R4B `criteria` |
| Measure.group.population.description | Measure.group.population.description | SourceIsBroaderThanTarget | R5 `Measure.group.population.description` maps as SourceIsBroaderThanTarget to R4B `Measure.group.population.description` - description has change due to type change: R5 description markdown has no equivalent or mapped type in R4B description |
| Measure.group.population.extension | Measure.group.population.extension | SourceIsBroaderThanTarget | R5 `Measure.group.population.extension` maps as SourceIsBroaderThanTarget to R4B `Measure.group.population.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Measure.group.population.groupDefinition | - | DoesNotExistInTarget | R5 `Measure.group.population.groupDefinition` does not appear in the target and has no mapping for `Measure`. |
| Measure.group.population.id | Measure.group.population.id | Equivalent | R5 `Measure.group.population.id` maps as Equivalent to R4B `Measure.group.population.id` |
| Measure.group.population.inputPopulationId | - | DoesNotExistInTarget | R5 `Measure.group.population.inputPopulationId` does not appear in the target and has no mapping for `Measure`. |
| Measure.group.population.linkId | - | DoesNotExistInTarget | R5 `Measure.group.population.linkId` does not appear in the target and has no mapping for `Measure`. |
| Measure.group.population.modifierExtension | Measure.group.population.modifierExtension | SourceIsBroaderThanTarget | R5 `Measure.group.population.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Measure.group.population.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Measure.group.rateAggregation | - | DoesNotExistInTarget | R5 `Measure.group.rateAggregation` does not appear in the target and has no mapping for `Measure`. |
| Measure.group.scoring | - | DoesNotExistInTarget | R5 `Measure.group.scoring` does not appear in the target and has no mapping for `Measure`. |
| Measure.group.scoringUnit | - | DoesNotExistInTarget | R5 `Measure.group.scoringUnit` does not appear in the target and has no mapping for `Measure`. |
| Measure.group.stratifier | Measure.group.stratifier | Equivalent | R5 `Measure.group.stratifier` maps as Equivalent to R4B `Measure.group.stratifier` |
| Measure.group.stratifier.code | Measure.group.stratifier.code | Equivalent | R5 `Measure.group.stratifier.code` maps as Equivalent to R4B `Measure.group.stratifier.code` |
| Measure.group.stratifier.component | Measure.group.stratifier.component | Equivalent | R5 `Measure.group.stratifier.component` maps as Equivalent to R4B `Measure.group.stratifier.component` |
| Measure.group.stratifier.component.code | Measure.group.stratifier.component.code | Equivalent | R5 `Measure.group.stratifier.component.code` maps as Equivalent to R4B `Measure.group.stratifier.component.code` |
| Measure.group.stratifier.component.criteria | Measure.group.stratifier.component.criteria | RelatedTo | R5 `Measure.group.stratifier.component.criteria` maps as RelatedTo to R4B `Measure.group.stratifier.component.criteria` - criteria made the element mandatory; criteria increased the minimum cardinality from 0 to 1; criteria has change due to type change: R5 `criteria` `Expression` maps as RelatedTo for R4B `criteria` |
| Measure.group.stratifier.component.description | Measure.group.stratifier.component.description | SourceIsBroaderThanTarget | R5 `Measure.group.stratifier.component.description` maps as SourceIsBroaderThanTarget to R4B `Measure.group.stratifier.component.description` - description has change due to type change: R5 description markdown has no equivalent or mapped type in R4B description |
| Measure.group.stratifier.component.extension | Measure.group.stratifier.component.extension | SourceIsBroaderThanTarget | R5 `Measure.group.stratifier.component.extension` maps as SourceIsBroaderThanTarget to R4B `Measure.group.stratifier.component.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Measure.group.stratifier.component.groupDefinition | - | DoesNotExistInTarget | R5 `Measure.group.stratifier.component.groupDefinition` does not appear in the target and has no mapping for `Measure`. |
| Measure.group.stratifier.component.id | Measure.group.stratifier.component.id | Equivalent | R5 `Measure.group.stratifier.component.id` maps as Equivalent to R4B `Measure.group.stratifier.component.id` |
| Measure.group.stratifier.component.linkId | - | DoesNotExistInTarget | R5 `Measure.group.stratifier.component.linkId` does not appear in the target and has no mapping for `Measure`. |
| Measure.group.stratifier.component.modifierExtension | Measure.group.stratifier.component.modifierExtension | SourceIsBroaderThanTarget | R5 `Measure.group.stratifier.component.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Measure.group.stratifier.component.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Measure.group.stratifier.criteria | Measure.group.stratifier.criteria | RelatedTo | R5 `Measure.group.stratifier.criteria` maps as RelatedTo to R4B `Measure.group.stratifier.criteria` - criteria has change due to type change: R5 `criteria` `Expression` maps as RelatedTo for R4B `criteria` |
| Measure.group.stratifier.description | Measure.group.stratifier.description | SourceIsBroaderThanTarget | R5 `Measure.group.stratifier.description` maps as SourceIsBroaderThanTarget to R4B `Measure.group.stratifier.description` - description has change due to type change: R5 description markdown has no equivalent or mapped type in R4B description |
| Measure.group.stratifier.extension | Measure.group.stratifier.extension | SourceIsBroaderThanTarget | R5 `Measure.group.stratifier.extension` maps as SourceIsBroaderThanTarget to R4B `Measure.group.stratifier.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Measure.group.stratifier.groupDefinition | - | DoesNotExistInTarget | R5 `Measure.group.stratifier.groupDefinition` does not appear in the target and has no mapping for `Measure`. |
| Measure.group.stratifier.id | Measure.group.stratifier.id | Equivalent | R5 `Measure.group.stratifier.id` maps as Equivalent to R4B `Measure.group.stratifier.id` |
| Measure.group.stratifier.linkId | - | DoesNotExistInTarget | R5 `Measure.group.stratifier.linkId` does not appear in the target and has no mapping for `Measure`. |
| Measure.group.stratifier.modifierExtension | Measure.group.stratifier.modifierExtension | SourceIsBroaderThanTarget | R5 `Measure.group.stratifier.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Measure.group.stratifier.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Measure.group.subject[x] | - | DoesNotExistInTarget | R5 `Measure.group.subject[x]` does not appear in the target and has no mapping for `Measure`. |
| Measure.group.type | - | DoesNotExistInTarget | R5 `Measure.group.type` does not appear in the target and has no mapping for `Measure`. |
| Measure.guidance | Measure.guidance | Equivalent | R5 `Measure.guidance` maps as Equivalent to R4B `Measure.guidance` |
| Measure.id | Measure.id | Equivalent | R5 `Measure.id` maps as Equivalent to R4B `Measure.id` |
| Measure.identifier | Measure.identifier | Equivalent | R5 `Measure.identifier` maps as Equivalent to R4B `Measure.identifier` |
| Measure.implicitRules | Measure.implicitRules | Equivalent | R5 `Measure.implicitRules` maps as Equivalent to R4B `Measure.implicitRules` |
| Measure.improvementNotation | Measure.improvementNotation | Equivalent | R5 `Measure.improvementNotation` maps as Equivalent to R4B `Measure.improvementNotation` - improvementNotation has compatible required binding for non-code type: http://hl7.org/fhir/ValueSet/measure-improvement-notation|5.0.0 and http://hl7.org/fhir/ValueSet/measure-improvement-notation|4.3.0 (Equivalent) |
| Measure.jurisdiction | Measure.jurisdiction | Equivalent | R5 `Measure.jurisdiction` maps as Equivalent to R4B `Measure.jurisdiction` |
| Measure.language | Measure.language | RelatedTo | R5 `Measure.language` maps as RelatedTo to R4B `Measure.language` - language changed the binding strength from Required to Preferred |
| Measure.lastReviewDate | Measure.lastReviewDate | Equivalent | R5 `Measure.lastReviewDate` maps as Equivalent to R4B `Measure.lastReviewDate` |
| Measure.library | Measure.library | Equivalent | R5 `Measure.library` maps as Equivalent to R4B `Measure.library` |
| Measure.meta | Measure.meta | Equivalent | R5 `Measure.meta` maps as Equivalent to R4B `Measure.meta` |
| Measure.modifierExtension | Measure.modifierExtension | SourceIsBroaderThanTarget | R5 `Measure.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Measure.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Measure.name | Measure.name | Equivalent | R5 `Measure.name` maps as Equivalent to R4B `Measure.name` |
| Measure.publisher | Measure.publisher | Equivalent | R5 `Measure.publisher` maps as Equivalent to R4B `Measure.publisher` |
| Measure.purpose | Measure.purpose | Equivalent | R5 `Measure.purpose` maps as Equivalent to R4B `Measure.purpose` |
| Measure.rateAggregation | Measure.rateAggregation | SourceIsBroaderThanTarget | R5 `Measure.rateAggregation` maps as SourceIsBroaderThanTarget to R4B `Measure.rateAggregation` - rateAggregation has change due to type change: R5 rateAggregation markdown has no equivalent or mapped type in R4B rateAggregation |
| Measure.rationale | Measure.rationale | Equivalent | R5 `Measure.rationale` maps as Equivalent to R4B `Measure.rationale` |
| Measure.relatedArtifact | Measure.relatedArtifact | Equivalent | R5 `Measure.relatedArtifact` maps as Equivalent to R4B `Measure.relatedArtifact` |
| Measure.reviewer | Measure.reviewer | Equivalent | R5 `Measure.reviewer` maps as Equivalent to R4B `Measure.reviewer` |
| Measure.riskAdjustment | Measure.riskAdjustment | SourceIsBroaderThanTarget | R5 `Measure.riskAdjustment` maps as SourceIsBroaderThanTarget to R4B `Measure.riskAdjustment` - riskAdjustment has change due to type change: R5 riskAdjustment markdown has no equivalent or mapped type in R4B riskAdjustment |
| Measure.scoring | Measure.scoring | Equivalent | R5 `Measure.scoring` maps as Equivalent to R4B `Measure.scoring` |
| Measure.scoringUnit | - | DoesNotExistInTarget | R5 `Measure.scoringUnit` does not appear in the target and has no mapping for `Measure`. |
| Measure.status | Measure.status | Equivalent | R5 `Measure.status` maps as Equivalent to R4B `Measure.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|5.0.0 and http://hl7.org/fhir/ValueSet/publication-status|4.3.0 (Equivalent) |
| Measure.subject[x] | Measure.subject[x] | Equivalent | R5 `Measure.subject[x]` maps as Equivalent to R4B `Measure.subject[x]` |
| Measure.subtitle | Measure.subtitle | Equivalent | R5 `Measure.subtitle` maps as Equivalent to R4B `Measure.subtitle` |
| Measure.supplementalData | Measure.supplementalData | Equivalent | R5 `Measure.supplementalData` maps as Equivalent to R4B `Measure.supplementalData` |
| Measure.supplementalData.code | Measure.supplementalData.code | Equivalent | R5 `Measure.supplementalData.code` maps as Equivalent to R4B `Measure.supplementalData.code` |
| Measure.supplementalData.criteria | Measure.supplementalData.criteria | RelatedTo | R5 `Measure.supplementalData.criteria` maps as RelatedTo to R4B `Measure.supplementalData.criteria` - criteria has change due to type change: R5 `criteria` `Expression` maps as RelatedTo for R4B `criteria` |
| Measure.supplementalData.description | Measure.supplementalData.description | SourceIsBroaderThanTarget | R5 `Measure.supplementalData.description` maps as SourceIsBroaderThanTarget to R4B `Measure.supplementalData.description` - description has change due to type change: R5 description markdown has no equivalent or mapped type in R4B description |
| Measure.supplementalData.extension | Measure.supplementalData.extension | SourceIsBroaderThanTarget | R5 `Measure.supplementalData.extension` maps as SourceIsBroaderThanTarget to R4B `Measure.supplementalData.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Measure.supplementalData.id | Measure.supplementalData.id | Equivalent | R5 `Measure.supplementalData.id` maps as Equivalent to R4B `Measure.supplementalData.id` |
| Measure.supplementalData.linkId | - | DoesNotExistInTarget | R5 `Measure.supplementalData.linkId` does not appear in the target and has no mapping for `Measure`. |
| Measure.supplementalData.modifierExtension | Measure.supplementalData.modifierExtension | SourceIsBroaderThanTarget | R5 `Measure.supplementalData.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Measure.supplementalData.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Measure.supplementalData.usage | Measure.supplementalData.usage | Equivalent | R5 `Measure.supplementalData.usage` maps as Equivalent to R4B `Measure.supplementalData.usage` |
| Measure.term | - | DoesNotExistInTarget | R5 `Measure.term` does not appear in the target and has no mapping for `Measure`. |
| Measure.term.code | - | DoesNotExistInTarget | R5 `Measure.term.code` does not appear in the target and has no mapping for `Measure`. |
| Measure.term.definition | - | DoesNotExistInTarget | R5 `Measure.term.definition` does not appear in the target and has no mapping for `Measure`. |
| Measure.term.extension | - | DoesNotExistInTarget | R5 `Measure.term.extension` does not appear in the target and has no mapping for `Measure`. |
| Measure.term.id | - | DoesNotExistInTarget | R5 `Measure.term.id` does not appear in the target and has no mapping for `Measure`. |
| Measure.term.modifierExtension | - | DoesNotExistInTarget | R5 `Measure.term.modifierExtension` does not appear in the target and has no mapping for `Measure`. |
| Measure.text | Measure.text | Equivalent | R5 `Measure.text` maps as Equivalent to R4B `Measure.text` |
| Measure.title | Measure.title | Equivalent | R5 `Measure.title` maps as Equivalent to R4B `Measure.title` |
| Measure.topic | Measure.topic | Equivalent | R5 `Measure.topic` maps as Equivalent to R4B `Measure.topic` |
| Measure.type | Measure.type | Equivalent | R5 `Measure.type` maps as Equivalent to R4B `Measure.type` |
| Measure.url | Measure.url | Equivalent | R5 `Measure.url` maps as Equivalent to R4B `Measure.url` |
| Measure.usage | Measure.usage | SourceIsBroaderThanTarget | R5 `Measure.usage` maps as SourceIsBroaderThanTarget to R4B `Measure.usage` - usage has change due to type change: R5 usage markdown has no equivalent or mapped type in R4B usage |
| Measure.useContext | Measure.useContext | Equivalent | R5 `Measure.useContext` maps as Equivalent to R4B `Measure.useContext` |
| Measure.version | Measure.version | Equivalent | R5 `Measure.version` maps as Equivalent to R4B `Measure.version` |
| Measure.versionAlgorithm[x] | - | DoesNotExistInTarget | R5 `Measure.versionAlgorithm[x]` does not appear in the target and has no mapping for `Measure`. |

