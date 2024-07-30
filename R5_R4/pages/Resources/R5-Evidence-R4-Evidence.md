Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Evidence |  | The Evidence Resource provides a machine-interpretable expression of an evidence concept including the evidence variables (e.g., population, exposures/interventions, comparators, outcomes, measured variables, confounding variables), the statistics, and the certainty of this evidence. | 104 | 75 |
| Target | Evidence |  | The Evidence resource describes the conditional state (population and any exposures being compared within the population) and outcome (if specified) that the knowledge (evidence, assertion, recommendation) is about. | 37 | 29 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 75 |
Equivalent | 4 |
RelatedTo | 25 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Evidence | Evidence | Equivalent | R5 `Evidence` maps as Equivalent to R4 `Evidence` |
| Evidence.approvalDate | Evidence.approvalDate | Equivalent | R5 `Evidence.approvalDate` maps as Equivalent to R4 `Evidence.approvalDate` |
| Evidence.assertion | - | DoesNotExistInTarget | R5 `Evidence.assertion` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.author | Evidence.author | Equivalent | R5 `Evidence.author` maps as Equivalent to R4 `Evidence.author` |
| Evidence.certainty | - | DoesNotExistInTarget | R5 `Evidence.certainty` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.certainty.description | - | DoesNotExistInTarget | R5 `Evidence.certainty.description` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.certainty.extension | - | DoesNotExistInTarget | R5 `Evidence.certainty.extension` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.certainty.id | - | DoesNotExistInTarget | R5 `Evidence.certainty.id` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.certainty.modifierExtension | - | DoesNotExistInTarget | R5 `Evidence.certainty.modifierExtension` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.certainty.note | - | DoesNotExistInTarget | R5 `Evidence.certainty.note` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.certainty.rater | - | DoesNotExistInTarget | R5 `Evidence.certainty.rater` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.certainty.rating | - | DoesNotExistInTarget | R5 `Evidence.certainty.rating` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.certainty.subcomponent | - | DoesNotExistInTarget | R5 `Evidence.certainty.subcomponent` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.certainty.type | - | DoesNotExistInTarget | R5 `Evidence.certainty.type` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.citeAs[x] | - | DoesNotExistInTarget | R5 `Evidence.citeAs[x]` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.contact | Evidence.contact | Equivalent | R5 `Evidence.contact` maps as Equivalent to R4 `Evidence.contact` |
| Evidence.contained | Evidence.contained | Equivalent | R5 `Evidence.contained` maps as Equivalent to R4 `Evidence.contained` |
| Evidence.copyright | Evidence.copyright | Equivalent | R5 `Evidence.copyright` maps as Equivalent to R4 `Evidence.copyright` |
| Evidence.copyrightLabel | - | DoesNotExistInTarget | R5 `Evidence.copyrightLabel` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.date | Evidence.date | Equivalent | R5 `Evidence.date` maps as Equivalent to R4 `Evidence.date` |
| Evidence.description | Evidence.description | Equivalent | R5 `Evidence.description` maps as Equivalent to R4 `Evidence.description` |
| Evidence.editor | Evidence.editor | Equivalent | R5 `Evidence.editor` maps as Equivalent to R4 `Evidence.editor` |
| Evidence.endorser | Evidence.endorser | Equivalent | R5 `Evidence.endorser` maps as Equivalent to R4 `Evidence.endorser` |
| Evidence.experimental | - | DoesNotExistInTarget | R5 `Evidence.experimental` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.extension | Evidence.extension | SourceIsBroaderThanTarget | R5 `Evidence.extension` maps as SourceIsBroaderThanTarget to R4 `Evidence.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Evidence.id | Evidence.id | Equivalent | R5 `Evidence.id` maps as Equivalent to R4 `Evidence.id` |
| Evidence.identifier | Evidence.identifier | Equivalent | R5 `Evidence.identifier` maps as Equivalent to R4 `Evidence.identifier` |
| Evidence.implicitRules | Evidence.implicitRules | Equivalent | R5 `Evidence.implicitRules` maps as Equivalent to R4 `Evidence.implicitRules` |
| Evidence.language | Evidence.language | RelatedTo | R5 `Evidence.language` maps as RelatedTo to R4 `Evidence.language` - language changed the binding strength from Required to Preferred |
| Evidence.lastReviewDate | Evidence.lastReviewDate | Equivalent | R5 `Evidence.lastReviewDate` maps as Equivalent to R4 `Evidence.lastReviewDate` |
| Evidence.meta | Evidence.meta | Equivalent | R5 `Evidence.meta` maps as Equivalent to R4 `Evidence.meta` |
| Evidence.modifierExtension | Evidence.modifierExtension | SourceIsBroaderThanTarget | R5 `Evidence.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Evidence.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Evidence.name | Evidence.name | Equivalent | R5 `Evidence.name` maps as Equivalent to R4 `Evidence.name` |
| Evidence.note | Evidence.note | SourceIsBroaderThanTarget | R5 `Evidence.note` maps as SourceIsBroaderThanTarget to R4 `Evidence.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4 `note` |
| Evidence.publisher | Evidence.publisher | Equivalent | R5 `Evidence.publisher` maps as Equivalent to R4 `Evidence.publisher` |
| Evidence.purpose | - | DoesNotExistInTarget | R5 `Evidence.purpose` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.relatedArtifact | Evidence.relatedArtifact | Equivalent | R5 `Evidence.relatedArtifact` maps as Equivalent to R4 `Evidence.relatedArtifact` |
| Evidence.reviewer | Evidence.reviewer | Equivalent | R5 `Evidence.reviewer` maps as Equivalent to R4 `Evidence.reviewer` |
| Evidence.statistic | - | DoesNotExistInTarget | R5 `Evidence.statistic` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.attributeEstimate | - | DoesNotExistInTarget | R5 `Evidence.statistic.attributeEstimate` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.attributeEstimate.attributeEstimate | - | DoesNotExistInTarget | R5 `Evidence.statistic.attributeEstimate.attributeEstimate` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.attributeEstimate.description | - | DoesNotExistInTarget | R5 `Evidence.statistic.attributeEstimate.description` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.attributeEstimate.extension | - | DoesNotExistInTarget | R5 `Evidence.statistic.attributeEstimate.extension` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.attributeEstimate.id | - | DoesNotExistInTarget | R5 `Evidence.statistic.attributeEstimate.id` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.attributeEstimate.level | - | DoesNotExistInTarget | R5 `Evidence.statistic.attributeEstimate.level` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.attributeEstimate.modifierExtension | - | DoesNotExistInTarget | R5 `Evidence.statistic.attributeEstimate.modifierExtension` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.attributeEstimate.note | - | DoesNotExistInTarget | R5 `Evidence.statistic.attributeEstimate.note` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.attributeEstimate.quantity | - | DoesNotExistInTarget | R5 `Evidence.statistic.attributeEstimate.quantity` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.attributeEstimate.range | - | DoesNotExistInTarget | R5 `Evidence.statistic.attributeEstimate.range` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.attributeEstimate.type | - | DoesNotExistInTarget | R5 `Evidence.statistic.attributeEstimate.type` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.category | - | DoesNotExistInTarget | R5 `Evidence.statistic.category` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.description | - | DoesNotExistInTarget | R5 `Evidence.statistic.description` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.extension | - | DoesNotExistInTarget | R5 `Evidence.statistic.extension` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.id | - | DoesNotExistInTarget | R5 `Evidence.statistic.id` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.modelCharacteristic | - | DoesNotExistInTarget | R5 `Evidence.statistic.modelCharacteristic` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.modelCharacteristic.attributeEstimate | - | DoesNotExistInTarget | R5 `Evidence.statistic.modelCharacteristic.attributeEstimate` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.modelCharacteristic.code | - | DoesNotExistInTarget | R5 `Evidence.statistic.modelCharacteristic.code` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.modelCharacteristic.extension | - | DoesNotExistInTarget | R5 `Evidence.statistic.modelCharacteristic.extension` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.modelCharacteristic.id | - | DoesNotExistInTarget | R5 `Evidence.statistic.modelCharacteristic.id` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.modelCharacteristic.modifierExtension | - | DoesNotExistInTarget | R5 `Evidence.statistic.modelCharacteristic.modifierExtension` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.modelCharacteristic.value | - | DoesNotExistInTarget | R5 `Evidence.statistic.modelCharacteristic.value` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.modelCharacteristic.variable | - | DoesNotExistInTarget | R5 `Evidence.statistic.modelCharacteristic.variable` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.modelCharacteristic.variable.extension | - | DoesNotExistInTarget | R5 `Evidence.statistic.modelCharacteristic.variable.extension` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.modelCharacteristic.variable.handling | - | DoesNotExistInTarget | R5 `Evidence.statistic.modelCharacteristic.variable.handling` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.modelCharacteristic.variable.id | - | DoesNotExistInTarget | R5 `Evidence.statistic.modelCharacteristic.variable.id` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.modelCharacteristic.variable.modifierExtension | - | DoesNotExistInTarget | R5 `Evidence.statistic.modelCharacteristic.variable.modifierExtension` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.modelCharacteristic.variable.valueCategory | - | DoesNotExistInTarget | R5 `Evidence.statistic.modelCharacteristic.variable.valueCategory` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.modelCharacteristic.variable.valueQuantity | - | DoesNotExistInTarget | R5 `Evidence.statistic.modelCharacteristic.variable.valueQuantity` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.modelCharacteristic.variable.valueRange | - | DoesNotExistInTarget | R5 `Evidence.statistic.modelCharacteristic.variable.valueRange` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.modelCharacteristic.variable.variableDefinition | - | DoesNotExistInTarget | R5 `Evidence.statistic.modelCharacteristic.variable.variableDefinition` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.modifierExtension | - | DoesNotExistInTarget | R5 `Evidence.statistic.modifierExtension` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.note | - | DoesNotExistInTarget | R5 `Evidence.statistic.note` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.numberAffected | - | DoesNotExistInTarget | R5 `Evidence.statistic.numberAffected` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.numberOfEvents | - | DoesNotExistInTarget | R5 `Evidence.statistic.numberOfEvents` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.quantity | - | DoesNotExistInTarget | R5 `Evidence.statistic.quantity` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.sampleSize | - | DoesNotExistInTarget | R5 `Evidence.statistic.sampleSize` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.sampleSize.description | - | DoesNotExistInTarget | R5 `Evidence.statistic.sampleSize.description` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.sampleSize.extension | - | DoesNotExistInTarget | R5 `Evidence.statistic.sampleSize.extension` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.sampleSize.id | - | DoesNotExistInTarget | R5 `Evidence.statistic.sampleSize.id` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.sampleSize.knownDataCount | - | DoesNotExistInTarget | R5 `Evidence.statistic.sampleSize.knownDataCount` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.sampleSize.modifierExtension | - | DoesNotExistInTarget | R5 `Evidence.statistic.sampleSize.modifierExtension` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.sampleSize.note | - | DoesNotExistInTarget | R5 `Evidence.statistic.sampleSize.note` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.sampleSize.numberOfParticipants | - | DoesNotExistInTarget | R5 `Evidence.statistic.sampleSize.numberOfParticipants` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.sampleSize.numberOfStudies | - | DoesNotExistInTarget | R5 `Evidence.statistic.sampleSize.numberOfStudies` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.statistic.statisticType | - | DoesNotExistInTarget | R5 `Evidence.statistic.statisticType` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.status | Evidence.status | Equivalent | R5 `Evidence.status` maps as Equivalent to R4 `Evidence.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|5.0.0 and http://hl7.org/fhir/ValueSet/publication-status|4.0.1 (Equivalent) |
| Evidence.studyDesign | - | DoesNotExistInTarget | R5 `Evidence.studyDesign` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.synthesisType | - | DoesNotExistInTarget | R5 `Evidence.synthesisType` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.text | Evidence.text | Equivalent | R5 `Evidence.text` maps as Equivalent to R4 `Evidence.text` |
| Evidence.title | Evidence.title | Equivalent | R5 `Evidence.title` maps as Equivalent to R4 `Evidence.title` |
| Evidence.url | Evidence.url | Equivalent | R5 `Evidence.url` maps as Equivalent to R4 `Evidence.url` |
| Evidence.useContext | Evidence.useContext | Equivalent | R5 `Evidence.useContext` maps as Equivalent to R4 `Evidence.useContext` |
| Evidence.variableDefinition | - | DoesNotExistInTarget | R5 `Evidence.variableDefinition` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.variableDefinition.description | - | DoesNotExistInTarget | R5 `Evidence.variableDefinition.description` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.variableDefinition.directnessMatch | - | DoesNotExistInTarget | R5 `Evidence.variableDefinition.directnessMatch` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.variableDefinition.extension | - | DoesNotExistInTarget | R5 `Evidence.variableDefinition.extension` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.variableDefinition.id | - | DoesNotExistInTarget | R5 `Evidence.variableDefinition.id` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.variableDefinition.intended | - | DoesNotExistInTarget | R5 `Evidence.variableDefinition.intended` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.variableDefinition.modifierExtension | - | DoesNotExistInTarget | R5 `Evidence.variableDefinition.modifierExtension` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.variableDefinition.note | - | DoesNotExistInTarget | R5 `Evidence.variableDefinition.note` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.variableDefinition.observed | - | DoesNotExistInTarget | R5 `Evidence.variableDefinition.observed` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.variableDefinition.variableRole | - | DoesNotExistInTarget | R5 `Evidence.variableDefinition.variableRole` does not appear in the target and has no mapping for `Evidence`. |
| Evidence.version | Evidence.version | Equivalent | R5 `Evidence.version` maps as Equivalent to R4 `Evidence.version` |
| Evidence.versionAlgorithm[x] | - | DoesNotExistInTarget | R5 `Evidence.versionAlgorithm[x]` does not appear in the target and has no mapping for `Evidence`. |

