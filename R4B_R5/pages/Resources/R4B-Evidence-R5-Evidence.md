Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Evidence |  | The Evidence Resource provides a machine-interpretable expression of an evidence concept including the evidence variables (eg population, exposures/interventions, comparators, outcomes, measured variables, confounding variables), the statistics, and the certainty of this evidence. | 98 | 69 |
| Target | Evidence |  | The Evidence Resource provides a machine-interpretable expression of an evidence concept including the evidence variables (e.g., population, exposures/interventions, comparators, outcomes, measured variables, confounding variables), the statistics, and the certainty of this evidence. | 104 | 75 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 1 |
Equivalent | 4 |
RelatedTo | 93 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Evidence | Evidence | Equivalent | R4B `Evidence` maps as Equivalent to R5 `Evidence` |
| Evidence.approvalDate | Evidence.approvalDate | Equivalent | R4B `Evidence.approvalDate` maps as Equivalent to R5 `Evidence.approvalDate` |
| Evidence.assertion | Evidence.assertion | Equivalent | R4B `Evidence.assertion` maps as Equivalent to R5 `Evidence.assertion` |
| Evidence.author | Evidence.author | Equivalent | R4B `Evidence.author` maps as Equivalent to R5 `Evidence.author` |
| Evidence.certainty | Evidence.certainty | Equivalent | R4B `Evidence.certainty` maps as Equivalent to R5 `Evidence.certainty` |
| Evidence.certainty.description | Evidence.certainty.description | SourceIsBroaderThanTarget | R4B `Evidence.certainty.description` maps as SourceIsBroaderThanTarget to R5 `Evidence.certainty.description` - description has change due to type change: R4B description string has no equivalent or mapped type in R5 description |
| Evidence.certainty.extension | Evidence.certainty.extension | RelatedTo | R4B `Evidence.certainty.extension` maps as RelatedTo to R5 `Evidence.certainty.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Evidence.certainty.id | Evidence.certainty.id | Equivalent | R4B `Evidence.certainty.id` maps as Equivalent to R5 `Evidence.certainty.id` |
| Evidence.certainty.modifierExtension | Evidence.certainty.modifierExtension | RelatedTo | R4B `Evidence.certainty.modifierExtension` maps as RelatedTo to R5 `Evidence.certainty.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Evidence.certainty.note | Evidence.certainty.note | SourceIsNarrowerThanTarget | R4B `Evidence.certainty.note` maps as SourceIsNarrowerThanTarget to R5 `Evidence.certainty.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| Evidence.certainty.rater | Evidence.certainty.rater | Equivalent | R4B `Evidence.certainty.rater` maps as Equivalent to R5 `Evidence.certainty.rater` |
| Evidence.certainty.rating | Evidence.certainty.rating | Equivalent | R4B `Evidence.certainty.rating` maps as Equivalent to R5 `Evidence.certainty.rating` |
| Evidence.certainty.subcomponent | Evidence.certainty.subcomponent | Equivalent | R4B `Evidence.certainty.subcomponent` maps as Equivalent to R5 `Evidence.certainty.subcomponent` |
| Evidence.certainty.type | Evidence.certainty.type | Equivalent | R4B `Evidence.certainty.type` maps as Equivalent to R5 `Evidence.certainty.type` |
| Evidence.citeAs[x] | Evidence.citeAs[x] | Equivalent | R4B `Evidence.citeAs[x]` maps as Equivalent to R5 `Evidence.citeAs[x]` |
| Evidence.contact | Evidence.contact | Equivalent | R4B `Evidence.contact` maps as Equivalent to R5 `Evidence.contact` |
| Evidence.contained | Evidence.contained | Equivalent | R4B `Evidence.contained` maps as Equivalent to R5 `Evidence.contained` |
| Evidence.date | Evidence.date | Equivalent | R4B `Evidence.date` maps as Equivalent to R5 `Evidence.date` |
| Evidence.description | Evidence.description | Equivalent | R4B `Evidence.description` maps as Equivalent to R5 `Evidence.description` |
| Evidence.editor | Evidence.editor | Equivalent | R4B `Evidence.editor` maps as Equivalent to R5 `Evidence.editor` |
| Evidence.endorser | Evidence.endorser | Equivalent | R4B `Evidence.endorser` maps as Equivalent to R5 `Evidence.endorser` |
| Evidence.extension | Evidence.extension | RelatedTo | R4B `Evidence.extension` maps as RelatedTo to R5 `Evidence.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Evidence.id | Evidence.id | Equivalent | R4B `Evidence.id` maps as Equivalent to R5 `Evidence.id` |
| Evidence.identifier | Evidence.identifier | Equivalent | R4B `Evidence.identifier` maps as Equivalent to R5 `Evidence.identifier` |
| Evidence.implicitRules | Evidence.implicitRules | Equivalent | R4B `Evidence.implicitRules` maps as Equivalent to R5 `Evidence.implicitRules` |
| Evidence.language | Evidence.language | RelatedTo | R4B `Evidence.language` maps as RelatedTo to R5 `Evidence.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Evidence.lastReviewDate | Evidence.lastReviewDate | Equivalent | R4B `Evidence.lastReviewDate` maps as Equivalent to R5 `Evidence.lastReviewDate` |
| Evidence.meta | Evidence.meta | Equivalent | R4B `Evidence.meta` maps as Equivalent to R5 `Evidence.meta` |
| Evidence.modifierExtension | Evidence.modifierExtension | RelatedTo | R4B `Evidence.modifierExtension` maps as RelatedTo to R5 `Evidence.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Evidence.note | Evidence.note | SourceIsNarrowerThanTarget | R4B `Evidence.note` maps as SourceIsNarrowerThanTarget to R5 `Evidence.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| Evidence.publisher | Evidence.publisher | Equivalent | R4B `Evidence.publisher` maps as Equivalent to R5 `Evidence.publisher` |
| Evidence.relatedArtifact | Evidence.relatedArtifact | Equivalent | R4B `Evidence.relatedArtifact` maps as Equivalent to R5 `Evidence.relatedArtifact` |
| Evidence.reviewer | Evidence.reviewer | Equivalent | R4B `Evidence.reviewer` maps as Equivalent to R5 `Evidence.reviewer` |
| Evidence.statistic | Evidence.statistic | Equivalent | R4B `Evidence.statistic` maps as Equivalent to R5 `Evidence.statistic` |
| Evidence.statistic.attributeEstimate | Evidence.statistic.attributeEstimate | Equivalent | R4B `Evidence.statistic.attributeEstimate` maps as Equivalent to R5 `Evidence.statistic.attributeEstimate` |
| Evidence.statistic.attributeEstimate.attributeEstimate | Evidence.statistic.attributeEstimate.attributeEstimate | Equivalent | R4B `Evidence.statistic.attributeEstimate.attributeEstimate` maps as Equivalent to R5 `Evidence.statistic.attributeEstimate.attributeEstimate` |
| Evidence.statistic.attributeEstimate.description | Evidence.statistic.attributeEstimate.description | SourceIsBroaderThanTarget | R4B `Evidence.statistic.attributeEstimate.description` maps as SourceIsBroaderThanTarget to R5 `Evidence.statistic.attributeEstimate.description` - description has change due to type change: R4B description string has no equivalent or mapped type in R5 description |
| Evidence.statistic.attributeEstimate.extension | Evidence.statistic.attributeEstimate.extension | RelatedTo | R4B `Evidence.statistic.attributeEstimate.extension` maps as RelatedTo to R5 `Evidence.statistic.attributeEstimate.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Evidence.statistic.attributeEstimate.id | Evidence.statistic.attributeEstimate.id | Equivalent | R4B `Evidence.statistic.attributeEstimate.id` maps as Equivalent to R5 `Evidence.statistic.attributeEstimate.id` |
| Evidence.statistic.attributeEstimate.level | Evidence.statistic.attributeEstimate.level | Equivalent | R4B `Evidence.statistic.attributeEstimate.level` maps as Equivalent to R5 `Evidence.statistic.attributeEstimate.level` |
| Evidence.statistic.attributeEstimate.modifierExtension | Evidence.statistic.attributeEstimate.modifierExtension | RelatedTo | R4B `Evidence.statistic.attributeEstimate.modifierExtension` maps as RelatedTo to R5 `Evidence.statistic.attributeEstimate.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Evidence.statistic.attributeEstimate.note | Evidence.statistic.attributeEstimate.note | SourceIsNarrowerThanTarget | R4B `Evidence.statistic.attributeEstimate.note` maps as SourceIsNarrowerThanTarget to R5 `Evidence.statistic.attributeEstimate.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| Evidence.statistic.attributeEstimate.quantity | Evidence.statistic.attributeEstimate.quantity | Equivalent | R4B `Evidence.statistic.attributeEstimate.quantity` maps as Equivalent to R5 `Evidence.statistic.attributeEstimate.quantity` |
| Evidence.statistic.attributeEstimate.range | Evidence.statistic.attributeEstimate.range | Equivalent | R4B `Evidence.statistic.attributeEstimate.range` maps as Equivalent to R5 `Evidence.statistic.attributeEstimate.range` |
| Evidence.statistic.attributeEstimate.type | Evidence.statistic.attributeEstimate.type | Equivalent | R4B `Evidence.statistic.attributeEstimate.type` maps as Equivalent to R5 `Evidence.statistic.attributeEstimate.type` |
| Evidence.statistic.category | Evidence.statistic.category | Equivalent | R4B `Evidence.statistic.category` maps as Equivalent to R5 `Evidence.statistic.category` |
| Evidence.statistic.description | Evidence.statistic.description | SourceIsBroaderThanTarget | R4B `Evidence.statistic.description` maps as SourceIsBroaderThanTarget to R5 `Evidence.statistic.description` - description has change due to type change: R4B description string has no equivalent or mapped type in R5 description |
| Evidence.statistic.extension | Evidence.statistic.extension | RelatedTo | R4B `Evidence.statistic.extension` maps as RelatedTo to R5 `Evidence.statistic.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Evidence.statistic.id | Evidence.statistic.id | Equivalent | R4B `Evidence.statistic.id` maps as Equivalent to R5 `Evidence.statistic.id` |
| Evidence.statistic.modelCharacteristic | Evidence.statistic.modelCharacteristic | Equivalent | R4B `Evidence.statistic.modelCharacteristic` maps as Equivalent to R5 `Evidence.statistic.modelCharacteristic` |
| Evidence.statistic.modelCharacteristic.attributeEstimate | Evidence.statistic.modelCharacteristic.attributeEstimate | Equivalent | R4B `Evidence.statistic.modelCharacteristic.attributeEstimate` maps as Equivalent to R5 `Evidence.statistic.modelCharacteristic.attributeEstimate` |
| Evidence.statistic.modelCharacteristic.code | Evidence.statistic.modelCharacteristic.code | Equivalent | R4B `Evidence.statistic.modelCharacteristic.code` maps as Equivalent to R5 `Evidence.statistic.modelCharacteristic.code` |
| Evidence.statistic.modelCharacteristic.extension | Evidence.statistic.modelCharacteristic.extension | RelatedTo | R4B `Evidence.statistic.modelCharacteristic.extension` maps as RelatedTo to R5 `Evidence.statistic.modelCharacteristic.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Evidence.statistic.modelCharacteristic.id | Evidence.statistic.modelCharacteristic.id | Equivalent | R4B `Evidence.statistic.modelCharacteristic.id` maps as Equivalent to R5 `Evidence.statistic.modelCharacteristic.id` |
| Evidence.statistic.modelCharacteristic.modifierExtension | Evidence.statistic.modelCharacteristic.modifierExtension | RelatedTo | R4B `Evidence.statistic.modelCharacteristic.modifierExtension` maps as RelatedTo to R5 `Evidence.statistic.modelCharacteristic.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Evidence.statistic.modelCharacteristic.value | Evidence.statistic.modelCharacteristic.value | Equivalent | R4B `Evidence.statistic.modelCharacteristic.value` maps as Equivalent to R5 `Evidence.statistic.modelCharacteristic.value` |
| Evidence.statistic.modelCharacteristic.variable | Evidence.statistic.modelCharacteristic.variable | Equivalent | R4B `Evidence.statistic.modelCharacteristic.variable` maps as Equivalent to R5 `Evidence.statistic.modelCharacteristic.variable` |
| Evidence.statistic.modelCharacteristic.variable.extension | Evidence.statistic.modelCharacteristic.variable.extension | RelatedTo | R4B `Evidence.statistic.modelCharacteristic.variable.extension` maps as RelatedTo to R5 `Evidence.statistic.modelCharacteristic.variable.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Evidence.statistic.modelCharacteristic.variable.handling | Evidence.statistic.modelCharacteristic.variable.handling | Equivalent | R4B `Evidence.statistic.modelCharacteristic.variable.handling` maps as Equivalent to R5 `Evidence.statistic.modelCharacteristic.variable.handling` - handling has compatible required binding for code type: http://hl7.org/fhir/ValueSet/variable-handling|4.3.0 and http://hl7.org/fhir/ValueSet/variable-handling|5.0.0 (Equivalent) |
| Evidence.statistic.modelCharacteristic.variable.id | Evidence.statistic.modelCharacteristic.variable.id | Equivalent | R4B `Evidence.statistic.modelCharacteristic.variable.id` maps as Equivalent to R5 `Evidence.statistic.modelCharacteristic.variable.id` |
| Evidence.statistic.modelCharacteristic.variable.modifierExtension | Evidence.statistic.modelCharacteristic.variable.modifierExtension | RelatedTo | R4B `Evidence.statistic.modelCharacteristic.variable.modifierExtension` maps as RelatedTo to R5 `Evidence.statistic.modelCharacteristic.variable.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Evidence.statistic.modelCharacteristic.variable.valueCategory | Evidence.statistic.modelCharacteristic.variable.valueCategory | Equivalent | R4B `Evidence.statistic.modelCharacteristic.variable.valueCategory` maps as Equivalent to R5 `Evidence.statistic.modelCharacteristic.variable.valueCategory` |
| Evidence.statistic.modelCharacteristic.variable.valueQuantity | Evidence.statistic.modelCharacteristic.variable.valueQuantity | Equivalent | R4B `Evidence.statistic.modelCharacteristic.variable.valueQuantity` maps as Equivalent to R5 `Evidence.statistic.modelCharacteristic.variable.valueQuantity` |
| Evidence.statistic.modelCharacteristic.variable.valueRange | Evidence.statistic.modelCharacteristic.variable.valueRange | Equivalent | R4B `Evidence.statistic.modelCharacteristic.variable.valueRange` maps as Equivalent to R5 `Evidence.statistic.modelCharacteristic.variable.valueRange` |
| Evidence.statistic.modelCharacteristic.variable.variableDefinition | Evidence.statistic.modelCharacteristic.variable.variableDefinition | Equivalent | R4B `Evidence.statistic.modelCharacteristic.variable.variableDefinition` maps as Equivalent to R5 `Evidence.statistic.modelCharacteristic.variable.variableDefinition` |
| Evidence.statistic.modifierExtension | Evidence.statistic.modifierExtension | RelatedTo | R4B `Evidence.statistic.modifierExtension` maps as RelatedTo to R5 `Evidence.statistic.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Evidence.statistic.note | Evidence.statistic.note | SourceIsNarrowerThanTarget | R4B `Evidence.statistic.note` maps as SourceIsNarrowerThanTarget to R5 `Evidence.statistic.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| Evidence.statistic.numberAffected | Evidence.statistic.numberAffected | Equivalent | R4B `Evidence.statistic.numberAffected` maps as Equivalent to R5 `Evidence.statistic.numberAffected` |
| Evidence.statistic.numberOfEvents | Evidence.statistic.numberOfEvents | Equivalent | R4B `Evidence.statistic.numberOfEvents` maps as Equivalent to R5 `Evidence.statistic.numberOfEvents` |
| Evidence.statistic.quantity | Evidence.statistic.quantity | Equivalent | R4B `Evidence.statistic.quantity` maps as Equivalent to R5 `Evidence.statistic.quantity` |
| Evidence.statistic.sampleSize | Evidence.statistic.sampleSize | Equivalent | R4B `Evidence.statistic.sampleSize` maps as Equivalent to R5 `Evidence.statistic.sampleSize` |
| Evidence.statistic.sampleSize.description | Evidence.statistic.sampleSize.description | SourceIsBroaderThanTarget | R4B `Evidence.statistic.sampleSize.description` maps as SourceIsBroaderThanTarget to R5 `Evidence.statistic.sampleSize.description` - description has change due to type change: R4B description string has no equivalent or mapped type in R5 description |
| Evidence.statistic.sampleSize.extension | Evidence.statistic.sampleSize.extension | RelatedTo | R4B `Evidence.statistic.sampleSize.extension` maps as RelatedTo to R5 `Evidence.statistic.sampleSize.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Evidence.statistic.sampleSize.id | Evidence.statistic.sampleSize.id | Equivalent | R4B `Evidence.statistic.sampleSize.id` maps as Equivalent to R5 `Evidence.statistic.sampleSize.id` |
| Evidence.statistic.sampleSize.knownDataCount | Evidence.statistic.sampleSize.knownDataCount | Equivalent | R4B `Evidence.statistic.sampleSize.knownDataCount` maps as Equivalent to R5 `Evidence.statistic.sampleSize.knownDataCount` |
| Evidence.statistic.sampleSize.modifierExtension | Evidence.statistic.sampleSize.modifierExtension | RelatedTo | R4B `Evidence.statistic.sampleSize.modifierExtension` maps as RelatedTo to R5 `Evidence.statistic.sampleSize.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Evidence.statistic.sampleSize.note | Evidence.statistic.sampleSize.note | SourceIsNarrowerThanTarget | R4B `Evidence.statistic.sampleSize.note` maps as SourceIsNarrowerThanTarget to R5 `Evidence.statistic.sampleSize.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| Evidence.statistic.sampleSize.numberOfParticipants | Evidence.statistic.sampleSize.numberOfParticipants | Equivalent | R4B `Evidence.statistic.sampleSize.numberOfParticipants` maps as Equivalent to R5 `Evidence.statistic.sampleSize.numberOfParticipants` |
| Evidence.statistic.sampleSize.numberOfStudies | Evidence.statistic.sampleSize.numberOfStudies | Equivalent | R4B `Evidence.statistic.sampleSize.numberOfStudies` maps as Equivalent to R5 `Evidence.statistic.sampleSize.numberOfStudies` |
| Evidence.statistic.statisticType | Evidence.statistic.statisticType | Equivalent | R4B `Evidence.statistic.statisticType` maps as Equivalent to R5 `Evidence.statistic.statisticType` |
| Evidence.status | Evidence.status | Equivalent | R4B `Evidence.status` maps as Equivalent to R5 `Evidence.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|4.3.0 and http://hl7.org/fhir/ValueSet/publication-status|5.0.0 (Equivalent) |
| Evidence.studyType | - | DoesNotExistInTarget | R4B `Evidence.studyType` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.synthesisType | Evidence.synthesisType | Equivalent | R4B `Evidence.synthesisType` maps as Equivalent to R5 `Evidence.synthesisType` |
| Evidence.text | Evidence.text | Equivalent | R4B `Evidence.text` maps as Equivalent to R5 `Evidence.text` |
| Evidence.title | Evidence.title | Equivalent | R4B `Evidence.title` maps as Equivalent to R5 `Evidence.title` |
| Evidence.url | Evidence.url | Equivalent | R4B `Evidence.url` maps as Equivalent to R5 `Evidence.url` |
| Evidence.useContext | Evidence.useContext | Equivalent | R4B `Evidence.useContext` maps as Equivalent to R5 `Evidence.useContext` |
| Evidence.variableDefinition | Evidence.variableDefinition | Equivalent | R4B `Evidence.variableDefinition` maps as Equivalent to R5 `Evidence.variableDefinition` |
| Evidence.variableDefinition.description | Evidence.variableDefinition.description | Equivalent | R4B `Evidence.variableDefinition.description` maps as Equivalent to R5 `Evidence.variableDefinition.description` |
| Evidence.variableDefinition.directnessMatch | Evidence.variableDefinition.directnessMatch | Equivalent | R4B `Evidence.variableDefinition.directnessMatch` maps as Equivalent to R5 `Evidence.variableDefinition.directnessMatch` |
| Evidence.variableDefinition.extension | Evidence.variableDefinition.extension | RelatedTo | R4B `Evidence.variableDefinition.extension` maps as RelatedTo to R5 `Evidence.variableDefinition.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Evidence.variableDefinition.id | Evidence.variableDefinition.id | Equivalent | R4B `Evidence.variableDefinition.id` maps as Equivalent to R5 `Evidence.variableDefinition.id` |
| Evidence.variableDefinition.intended | Evidence.variableDefinition.intended | Equivalent | R4B `Evidence.variableDefinition.intended` maps as Equivalent to R5 `Evidence.variableDefinition.intended` |
| Evidence.variableDefinition.modifierExtension | Evidence.variableDefinition.modifierExtension | RelatedTo | R4B `Evidence.variableDefinition.modifierExtension` maps as RelatedTo to R5 `Evidence.variableDefinition.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Evidence.variableDefinition.note | Evidence.variableDefinition.note | SourceIsNarrowerThanTarget | R4B `Evidence.variableDefinition.note` maps as SourceIsNarrowerThanTarget to R5 `Evidence.variableDefinition.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| Evidence.variableDefinition.observed | Evidence.variableDefinition.observed | Equivalent | R4B `Evidence.variableDefinition.observed` maps as Equivalent to R5 `Evidence.variableDefinition.observed` |
| Evidence.variableDefinition.variableRole | Evidence.variableDefinition.variableRole | Equivalent | R4B `Evidence.variableDefinition.variableRole` maps as Equivalent to R5 `Evidence.variableDefinition.variableRole` |
| Evidence.version | Evidence.version | Equivalent | R4B `Evidence.version` maps as Equivalent to R5 `Evidence.version` |

