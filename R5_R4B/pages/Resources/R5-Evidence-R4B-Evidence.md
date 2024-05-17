Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Evidence |  | The Evidence Resource provides a machine-interpretable expression of an evidence concept including the evidence variables (e.g., population, exposures/interventions, comparators, outcomes, measured variables, confounding variables), the statistics, and the certainty of this evidence. | 104 | 75 |
| Target | Evidence |  | The Evidence Resource provides a machine-interpretable expression of an evidence concept including the evidence variables (eg population, exposures/interventions, comparators, outcomes, measured variables, confounding variables), the statistics, and the certainty of this evidence. | 98 | 69 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 7 |
Equivalent | 4 |
RelatedTo | 93 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Evidence | Evidence | Equivalent | R5 `Evidence` maps as Equivalent to R4B `Evidence` |
| Evidence.approvalDate | Evidence.approvalDate | Equivalent | R5 `Evidence.approvalDate` maps as Equivalent to R4B `Evidence.approvalDate` |
| Evidence.assertion | Evidence.assertion | Equivalent | R5 `Evidence.assertion` maps as Equivalent to R4B `Evidence.assertion` |
| Evidence.author | Evidence.author | Equivalent | R5 `Evidence.author` maps as Equivalent to R4B `Evidence.author` |
| Evidence.certainty | Evidence.certainty | Equivalent | R5 `Evidence.certainty` maps as Equivalent to R4B `Evidence.certainty` |
| Evidence.certainty.description | Evidence.certainty.description | SourceIsBroaderThanTarget | R5 `Evidence.certainty.description` maps as SourceIsBroaderThanTarget to R4B `Evidence.certainty.description` - description has change due to type change: R5 description markdown has no equivalent or mapped type in R4B description |
| Evidence.certainty.extension | Evidence.certainty.extension | SourceIsBroaderThanTarget | R5 `Evidence.certainty.extension` maps as SourceIsBroaderThanTarget to R4B `Evidence.certainty.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Evidence.certainty.id | Evidence.certainty.id | Equivalent | R5 `Evidence.certainty.id` maps as Equivalent to R4B `Evidence.certainty.id` |
| Evidence.certainty.modifierExtension | Evidence.certainty.modifierExtension | SourceIsBroaderThanTarget | R5 `Evidence.certainty.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Evidence.certainty.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Evidence.certainty.note | Evidence.certainty.note | SourceIsBroaderThanTarget | R5 `Evidence.certainty.note` maps as SourceIsBroaderThanTarget to R4B `Evidence.certainty.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4B `note` |
| Evidence.certainty.rater | Evidence.certainty.rater | Equivalent | R5 `Evidence.certainty.rater` maps as Equivalent to R4B `Evidence.certainty.rater` |
| Evidence.certainty.rating | Evidence.certainty.rating | Equivalent | R5 `Evidence.certainty.rating` maps as Equivalent to R4B `Evidence.certainty.rating` |
| Evidence.certainty.subcomponent | Evidence.certainty.subcomponent | Equivalent | R5 `Evidence.certainty.subcomponent` maps as Equivalent to R4B `Evidence.certainty.subcomponent` |
| Evidence.certainty.type | Evidence.certainty.type | Equivalent | R5 `Evidence.certainty.type` maps as Equivalent to R4B `Evidence.certainty.type` |
| Evidence.citeAs[x] | Evidence.citeAs[x] | Equivalent | R5 `Evidence.citeAs[x]` maps as Equivalent to R4B `Evidence.citeAs[x]` |
| Evidence.contact | Evidence.contact | Equivalent | R5 `Evidence.contact` maps as Equivalent to R4B `Evidence.contact` |
| Evidence.contained | Evidence.contained | Equivalent | R5 `Evidence.contained` maps as Equivalent to R4B `Evidence.contained` |
| Evidence.copyright | - | DoesNotExistInTarget | R5 `Evidence.copyright` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.copyrightLabel | - | DoesNotExistInTarget | R5 `Evidence.copyrightLabel` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.date | Evidence.date | Equivalent | R5 `Evidence.date` maps as Equivalent to R4B `Evidence.date` |
| Evidence.description | Evidence.description | Equivalent | R5 `Evidence.description` maps as Equivalent to R4B `Evidence.description` |
| Evidence.editor | Evidence.editor | Equivalent | R5 `Evidence.editor` maps as Equivalent to R4B `Evidence.editor` |
| Evidence.endorser | Evidence.endorser | Equivalent | R5 `Evidence.endorser` maps as Equivalent to R4B `Evidence.endorser` |
| Evidence.experimental | - | DoesNotExistInTarget | R5 `Evidence.experimental` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.extension | Evidence.extension | SourceIsBroaderThanTarget | R5 `Evidence.extension` maps as SourceIsBroaderThanTarget to R4B `Evidence.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Evidence.id | Evidence.id | Equivalent | R5 `Evidence.id` maps as Equivalent to R4B `Evidence.id` |
| Evidence.identifier | Evidence.identifier | Equivalent | R5 `Evidence.identifier` maps as Equivalent to R4B `Evidence.identifier` |
| Evidence.implicitRules | Evidence.implicitRules | Equivalent | R5 `Evidence.implicitRules` maps as Equivalent to R4B `Evidence.implicitRules` |
| Evidence.language | Evidence.language | RelatedTo | R5 `Evidence.language` maps as RelatedTo to R4B `Evidence.language` - language changed the binding strength from Required to Preferred |
| Evidence.lastReviewDate | Evidence.lastReviewDate | Equivalent | R5 `Evidence.lastReviewDate` maps as Equivalent to R4B `Evidence.lastReviewDate` |
| Evidence.meta | Evidence.meta | Equivalent | R5 `Evidence.meta` maps as Equivalent to R4B `Evidence.meta` |
| Evidence.modifierExtension | Evidence.modifierExtension | SourceIsBroaderThanTarget | R5 `Evidence.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Evidence.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Evidence.name | - | DoesNotExistInTarget | R5 `Evidence.name` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.note | Evidence.note | SourceIsBroaderThanTarget | R5 `Evidence.note` maps as SourceIsBroaderThanTarget to R4B `Evidence.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4B `note` |
| Evidence.publisher | Evidence.publisher | Equivalent | R5 `Evidence.publisher` maps as Equivalent to R4B `Evidence.publisher` |
| Evidence.purpose | - | DoesNotExistInTarget | R5 `Evidence.purpose` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.relatedArtifact | Evidence.relatedArtifact | Equivalent | R5 `Evidence.relatedArtifact` maps as Equivalent to R4B `Evidence.relatedArtifact` |
| Evidence.reviewer | Evidence.reviewer | Equivalent | R5 `Evidence.reviewer` maps as Equivalent to R4B `Evidence.reviewer` |
| Evidence.statistic | Evidence.statistic | Equivalent | R5 `Evidence.statistic` maps as Equivalent to R4B `Evidence.statistic` |
| Evidence.statistic.attributeEstimate | Evidence.statistic.attributeEstimate | Equivalent | R5 `Evidence.statistic.attributeEstimate` maps as Equivalent to R4B `Evidence.statistic.attributeEstimate` |
| Evidence.statistic.attributeEstimate.attributeEstimate | Evidence.statistic.attributeEstimate.attributeEstimate | Equivalent | R5 `Evidence.statistic.attributeEstimate.attributeEstimate` maps as Equivalent to R4B `Evidence.statistic.attributeEstimate.attributeEstimate` |
| Evidence.statistic.attributeEstimate.description | Evidence.statistic.attributeEstimate.description | SourceIsBroaderThanTarget | R5 `Evidence.statistic.attributeEstimate.description` maps as SourceIsBroaderThanTarget to R4B `Evidence.statistic.attributeEstimate.description` - description has change due to type change: R5 description markdown has no equivalent or mapped type in R4B description |
| Evidence.statistic.attributeEstimate.extension | Evidence.statistic.attributeEstimate.extension | SourceIsBroaderThanTarget | R5 `Evidence.statistic.attributeEstimate.extension` maps as SourceIsBroaderThanTarget to R4B `Evidence.statistic.attributeEstimate.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Evidence.statistic.attributeEstimate.id | Evidence.statistic.attributeEstimate.id | Equivalent | R5 `Evidence.statistic.attributeEstimate.id` maps as Equivalent to R4B `Evidence.statistic.attributeEstimate.id` |
| Evidence.statistic.attributeEstimate.level | Evidence.statistic.attributeEstimate.level | Equivalent | R5 `Evidence.statistic.attributeEstimate.level` maps as Equivalent to R4B `Evidence.statistic.attributeEstimate.level` |
| Evidence.statistic.attributeEstimate.modifierExtension | Evidence.statistic.attributeEstimate.modifierExtension | SourceIsBroaderThanTarget | R5 `Evidence.statistic.attributeEstimate.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Evidence.statistic.attributeEstimate.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Evidence.statistic.attributeEstimate.note | Evidence.statistic.attributeEstimate.note | SourceIsBroaderThanTarget | R5 `Evidence.statistic.attributeEstimate.note` maps as SourceIsBroaderThanTarget to R4B `Evidence.statistic.attributeEstimate.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4B `note` |
| Evidence.statistic.attributeEstimate.quantity | Evidence.statistic.attributeEstimate.quantity | Equivalent | R5 `Evidence.statistic.attributeEstimate.quantity` maps as Equivalent to R4B `Evidence.statistic.attributeEstimate.quantity` |
| Evidence.statistic.attributeEstimate.range | Evidence.statistic.attributeEstimate.range | Equivalent | R5 `Evidence.statistic.attributeEstimate.range` maps as Equivalent to R4B `Evidence.statistic.attributeEstimate.range` |
| Evidence.statistic.attributeEstimate.type | Evidence.statistic.attributeEstimate.type | Equivalent | R5 `Evidence.statistic.attributeEstimate.type` maps as Equivalent to R4B `Evidence.statistic.attributeEstimate.type` |
| Evidence.statistic.category | Evidence.statistic.category | Equivalent | R5 `Evidence.statistic.category` maps as Equivalent to R4B `Evidence.statistic.category` |
| Evidence.statistic.description | Evidence.statistic.description | SourceIsBroaderThanTarget | R5 `Evidence.statistic.description` maps as SourceIsBroaderThanTarget to R4B `Evidence.statistic.description` - description has change due to type change: R5 description markdown has no equivalent or mapped type in R4B description |
| Evidence.statistic.extension | Evidence.statistic.extension | SourceIsBroaderThanTarget | R5 `Evidence.statistic.extension` maps as SourceIsBroaderThanTarget to R4B `Evidence.statistic.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Evidence.statistic.id | Evidence.statistic.id | Equivalent | R5 `Evidence.statistic.id` maps as Equivalent to R4B `Evidence.statistic.id` |
| Evidence.statistic.modelCharacteristic | Evidence.statistic.modelCharacteristic | Equivalent | R5 `Evidence.statistic.modelCharacteristic` maps as Equivalent to R4B `Evidence.statistic.modelCharacteristic` |
| Evidence.statistic.modelCharacteristic.attributeEstimate | Evidence.statistic.modelCharacteristic.attributeEstimate | Equivalent | R5 `Evidence.statistic.modelCharacteristic.attributeEstimate` maps as Equivalent to R4B `Evidence.statistic.modelCharacteristic.attributeEstimate` |
| Evidence.statistic.modelCharacteristic.code | Evidence.statistic.modelCharacteristic.code | Equivalent | R5 `Evidence.statistic.modelCharacteristic.code` maps as Equivalent to R4B `Evidence.statistic.modelCharacteristic.code` |
| Evidence.statistic.modelCharacteristic.extension | Evidence.statistic.modelCharacteristic.extension | SourceIsBroaderThanTarget | R5 `Evidence.statistic.modelCharacteristic.extension` maps as SourceIsBroaderThanTarget to R4B `Evidence.statistic.modelCharacteristic.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Evidence.statistic.modelCharacteristic.id | Evidence.statistic.modelCharacteristic.id | Equivalent | R5 `Evidence.statistic.modelCharacteristic.id` maps as Equivalent to R4B `Evidence.statistic.modelCharacteristic.id` |
| Evidence.statistic.modelCharacteristic.modifierExtension | Evidence.statistic.modelCharacteristic.modifierExtension | SourceIsBroaderThanTarget | R5 `Evidence.statistic.modelCharacteristic.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Evidence.statistic.modelCharacteristic.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Evidence.statistic.modelCharacteristic.value | Evidence.statistic.modelCharacteristic.value | Equivalent | R5 `Evidence.statistic.modelCharacteristic.value` maps as Equivalent to R4B `Evidence.statistic.modelCharacteristic.value` |
| Evidence.statistic.modelCharacteristic.variable | Evidence.statistic.modelCharacteristic.variable | Equivalent | R5 `Evidence.statistic.modelCharacteristic.variable` maps as Equivalent to R4B `Evidence.statistic.modelCharacteristic.variable` |
| Evidence.statistic.modelCharacteristic.variable.extension | Evidence.statistic.modelCharacteristic.variable.extension | SourceIsBroaderThanTarget | R5 `Evidence.statistic.modelCharacteristic.variable.extension` maps as SourceIsBroaderThanTarget to R4B `Evidence.statistic.modelCharacteristic.variable.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Evidence.statistic.modelCharacteristic.variable.handling | Evidence.statistic.modelCharacteristic.variable.handling | Equivalent | R5 `Evidence.statistic.modelCharacteristic.variable.handling` maps as Equivalent to R4B `Evidence.statistic.modelCharacteristic.variable.handling` - handling has compatible required binding for code type: http://hl7.org/fhir/ValueSet/variable-handling|5.0.0 and http://hl7.org/fhir/ValueSet/variable-handling|4.3.0 (Equivalent) |
| Evidence.statistic.modelCharacteristic.variable.id | Evidence.statistic.modelCharacteristic.variable.id | Equivalent | R5 `Evidence.statistic.modelCharacteristic.variable.id` maps as Equivalent to R4B `Evidence.statistic.modelCharacteristic.variable.id` |
| Evidence.statistic.modelCharacteristic.variable.modifierExtension | Evidence.statistic.modelCharacteristic.variable.modifierExtension | SourceIsBroaderThanTarget | R5 `Evidence.statistic.modelCharacteristic.variable.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Evidence.statistic.modelCharacteristic.variable.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Evidence.statistic.modelCharacteristic.variable.valueCategory | Evidence.statistic.modelCharacteristic.variable.valueCategory | Equivalent | R5 `Evidence.statistic.modelCharacteristic.variable.valueCategory` maps as Equivalent to R4B `Evidence.statistic.modelCharacteristic.variable.valueCategory` |
| Evidence.statistic.modelCharacteristic.variable.valueQuantity | Evidence.statistic.modelCharacteristic.variable.valueQuantity | Equivalent | R5 `Evidence.statistic.modelCharacteristic.variable.valueQuantity` maps as Equivalent to R4B `Evidence.statistic.modelCharacteristic.variable.valueQuantity` |
| Evidence.statistic.modelCharacteristic.variable.valueRange | Evidence.statistic.modelCharacteristic.variable.valueRange | Equivalent | R5 `Evidence.statistic.modelCharacteristic.variable.valueRange` maps as Equivalent to R4B `Evidence.statistic.modelCharacteristic.variable.valueRange` |
| Evidence.statistic.modelCharacteristic.variable.variableDefinition | Evidence.statistic.modelCharacteristic.variable.variableDefinition | Equivalent | R5 `Evidence.statistic.modelCharacteristic.variable.variableDefinition` maps as Equivalent to R4B `Evidence.statistic.modelCharacteristic.variable.variableDefinition` |
| Evidence.statistic.modifierExtension | Evidence.statistic.modifierExtension | SourceIsBroaderThanTarget | R5 `Evidence.statistic.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Evidence.statistic.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Evidence.statistic.note | Evidence.statistic.note | SourceIsBroaderThanTarget | R5 `Evidence.statistic.note` maps as SourceIsBroaderThanTarget to R4B `Evidence.statistic.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4B `note` |
| Evidence.statistic.numberAffected | Evidence.statistic.numberAffected | Equivalent | R5 `Evidence.statistic.numberAffected` maps as Equivalent to R4B `Evidence.statistic.numberAffected` |
| Evidence.statistic.numberOfEvents | Evidence.statistic.numberOfEvents | Equivalent | R5 `Evidence.statistic.numberOfEvents` maps as Equivalent to R4B `Evidence.statistic.numberOfEvents` |
| Evidence.statistic.quantity | Evidence.statistic.quantity | Equivalent | R5 `Evidence.statistic.quantity` maps as Equivalent to R4B `Evidence.statistic.quantity` |
| Evidence.statistic.sampleSize | Evidence.statistic.sampleSize | Equivalent | R5 `Evidence.statistic.sampleSize` maps as Equivalent to R4B `Evidence.statistic.sampleSize` |
| Evidence.statistic.sampleSize.description | Evidence.statistic.sampleSize.description | SourceIsBroaderThanTarget | R5 `Evidence.statistic.sampleSize.description` maps as SourceIsBroaderThanTarget to R4B `Evidence.statistic.sampleSize.description` - description has change due to type change: R5 description markdown has no equivalent or mapped type in R4B description |
| Evidence.statistic.sampleSize.extension | Evidence.statistic.sampleSize.extension | SourceIsBroaderThanTarget | R5 `Evidence.statistic.sampleSize.extension` maps as SourceIsBroaderThanTarget to R4B `Evidence.statistic.sampleSize.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Evidence.statistic.sampleSize.id | Evidence.statistic.sampleSize.id | Equivalent | R5 `Evidence.statistic.sampleSize.id` maps as Equivalent to R4B `Evidence.statistic.sampleSize.id` |
| Evidence.statistic.sampleSize.knownDataCount | Evidence.statistic.sampleSize.knownDataCount | Equivalent | R5 `Evidence.statistic.sampleSize.knownDataCount` maps as Equivalent to R4B `Evidence.statistic.sampleSize.knownDataCount` |
| Evidence.statistic.sampleSize.modifierExtension | Evidence.statistic.sampleSize.modifierExtension | SourceIsBroaderThanTarget | R5 `Evidence.statistic.sampleSize.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Evidence.statistic.sampleSize.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Evidence.statistic.sampleSize.note | Evidence.statistic.sampleSize.note | SourceIsBroaderThanTarget | R5 `Evidence.statistic.sampleSize.note` maps as SourceIsBroaderThanTarget to R4B `Evidence.statistic.sampleSize.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4B `note` |
| Evidence.statistic.sampleSize.numberOfParticipants | Evidence.statistic.sampleSize.numberOfParticipants | Equivalent | R5 `Evidence.statistic.sampleSize.numberOfParticipants` maps as Equivalent to R4B `Evidence.statistic.sampleSize.numberOfParticipants` |
| Evidence.statistic.sampleSize.numberOfStudies | Evidence.statistic.sampleSize.numberOfStudies | Equivalent | R5 `Evidence.statistic.sampleSize.numberOfStudies` maps as Equivalent to R4B `Evidence.statistic.sampleSize.numberOfStudies` |
| Evidence.statistic.statisticType | Evidence.statistic.statisticType | Equivalent | R5 `Evidence.statistic.statisticType` maps as Equivalent to R4B `Evidence.statistic.statisticType` |
| Evidence.status | Evidence.status | Equivalent | R5 `Evidence.status` maps as Equivalent to R4B `Evidence.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|5.0.0 and http://hl7.org/fhir/ValueSet/publication-status|4.3.0 (Equivalent) |
| Evidence.studyDesign | - | DoesNotExistInTarget | R5 `Evidence.studyDesign` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.synthesisType | Evidence.synthesisType | Equivalent | R5 `Evidence.synthesisType` maps as Equivalent to R4B `Evidence.synthesisType` |
| Evidence.text | Evidence.text | Equivalent | R5 `Evidence.text` maps as Equivalent to R4B `Evidence.text` |
| Evidence.title | Evidence.title | Equivalent | R5 `Evidence.title` maps as Equivalent to R4B `Evidence.title` |
| Evidence.url | Evidence.url | Equivalent | R5 `Evidence.url` maps as Equivalent to R4B `Evidence.url` |
| Evidence.useContext | Evidence.useContext | Equivalent | R5 `Evidence.useContext` maps as Equivalent to R4B `Evidence.useContext` |
| Evidence.variableDefinition | Evidence.variableDefinition | Equivalent | R5 `Evidence.variableDefinition` maps as Equivalent to R4B `Evidence.variableDefinition` |
| Evidence.variableDefinition.description | Evidence.variableDefinition.description | Equivalent | R5 `Evidence.variableDefinition.description` maps as Equivalent to R4B `Evidence.variableDefinition.description` |
| Evidence.variableDefinition.directnessMatch | Evidence.variableDefinition.directnessMatch | Equivalent | R5 `Evidence.variableDefinition.directnessMatch` maps as Equivalent to R4B `Evidence.variableDefinition.directnessMatch` |
| Evidence.variableDefinition.extension | Evidence.variableDefinition.extension | SourceIsBroaderThanTarget | R5 `Evidence.variableDefinition.extension` maps as SourceIsBroaderThanTarget to R4B `Evidence.variableDefinition.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Evidence.variableDefinition.id | Evidence.variableDefinition.id | Equivalent | R5 `Evidence.variableDefinition.id` maps as Equivalent to R4B `Evidence.variableDefinition.id` |
| Evidence.variableDefinition.intended | Evidence.variableDefinition.intended | Equivalent | R5 `Evidence.variableDefinition.intended` maps as Equivalent to R4B `Evidence.variableDefinition.intended` |
| Evidence.variableDefinition.modifierExtension | Evidence.variableDefinition.modifierExtension | SourceIsBroaderThanTarget | R5 `Evidence.variableDefinition.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Evidence.variableDefinition.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Evidence.variableDefinition.note | Evidence.variableDefinition.note | SourceIsBroaderThanTarget | R5 `Evidence.variableDefinition.note` maps as SourceIsBroaderThanTarget to R4B `Evidence.variableDefinition.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4B `note` |
| Evidence.variableDefinition.observed | Evidence.variableDefinition.observed | Equivalent | R5 `Evidence.variableDefinition.observed` maps as Equivalent to R4B `Evidence.variableDefinition.observed` |
| Evidence.variableDefinition.variableRole | Evidence.variableDefinition.variableRole | Equivalent | R5 `Evidence.variableDefinition.variableRole` maps as Equivalent to R4B `Evidence.variableDefinition.variableRole` |
| Evidence.version | Evidence.version | Equivalent | R5 `Evidence.version` maps as Equivalent to R4B `Evidence.version` |
| Evidence.versionAlgorithm[x] | - | DoesNotExistInTarget | R5 `Evidence.versionAlgorithm[x]` does not appear in the target and has no mapping for `Evidence`. |

