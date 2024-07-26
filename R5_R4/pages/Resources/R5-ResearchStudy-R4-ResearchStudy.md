Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1
Generated at Thursday, July 25, 2024 3:56:51 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | ResearchStudy |  | A scientific study of nature that sometimes includes processes involved in health and disease. For example, clinical trials are research studies that involve people. These studies may be related to new ways to screen, prevent, diagnose, and treat disease. They may also study certain outcomes and certain groups of people by looking at data collected in the past or future. | 89 | 60 |
| Target | ResearchStudy |  | A process where a researcher or organization plans and then executes a series of steps intended to increase the field of healthcare-related knowledge.  This includes studies of safety, efficacy, comparative effectiveness and other information about medications, devices, therapies and other interventional and investigative techniques.  A ResearchStudy involves the gathering of information about human or animal subjects. | 44 | 30 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 59 |
Equivalent | 4 |
RelatedTo | 26 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| ResearchStudy | ResearchStudy | Equivalent | R5 `ResearchStudy` maps as Equivalent to R4 `ResearchStudy` |
| ResearchStudy.associatedParty | - | DoesNotExistInTarget | R5 `ResearchStudy.associatedParty` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.associatedParty.classifier | - | DoesNotExistInTarget | R5 `ResearchStudy.associatedParty.classifier` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.associatedParty.extension | - | DoesNotExistInTarget | R5 `ResearchStudy.associatedParty.extension` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.associatedParty.id | - | DoesNotExistInTarget | R5 `ResearchStudy.associatedParty.id` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.associatedParty.modifierExtension | - | DoesNotExistInTarget | R5 `ResearchStudy.associatedParty.modifierExtension` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.associatedParty.name | - | DoesNotExistInTarget | R5 `ResearchStudy.associatedParty.name` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.associatedParty.party | - | DoesNotExistInTarget | R5 `ResearchStudy.associatedParty.party` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.associatedParty.period | - | DoesNotExistInTarget | R5 `ResearchStudy.associatedParty.period` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.associatedParty.role | - | DoesNotExistInTarget | R5 `ResearchStudy.associatedParty.role` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.classifier | - | DoesNotExistInTarget | R5 `ResearchStudy.classifier` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.comparisonGroup | - | DoesNotExistInTarget | R5 `ResearchStudy.comparisonGroup` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.comparisonGroup.description | - | DoesNotExistInTarget | R5 `ResearchStudy.comparisonGroup.description` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.comparisonGroup.extension | - | DoesNotExistInTarget | R5 `ResearchStudy.comparisonGroup.extension` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.comparisonGroup.id | - | DoesNotExistInTarget | R5 `ResearchStudy.comparisonGroup.id` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.comparisonGroup.intendedExposure | - | DoesNotExistInTarget | R5 `ResearchStudy.comparisonGroup.intendedExposure` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.comparisonGroup.linkId | - | DoesNotExistInTarget | R5 `ResearchStudy.comparisonGroup.linkId` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.comparisonGroup.modifierExtension | - | DoesNotExistInTarget | R5 `ResearchStudy.comparisonGroup.modifierExtension` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.comparisonGroup.name | - | DoesNotExistInTarget | R5 `ResearchStudy.comparisonGroup.name` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.comparisonGroup.observedGroup | - | DoesNotExistInTarget | R5 `ResearchStudy.comparisonGroup.observedGroup` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.comparisonGroup.type | - | DoesNotExistInTarget | R5 `ResearchStudy.comparisonGroup.type` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.condition | ResearchStudy.condition | Equivalent | R5 `ResearchStudy.condition` maps as Equivalent to R4 `ResearchStudy.condition` |
| ResearchStudy.contained | ResearchStudy.contained | Equivalent | R5 `ResearchStudy.contained` maps as Equivalent to R4 `ResearchStudy.contained` |
| ResearchStudy.date | - | DoesNotExistInTarget | R5 `ResearchStudy.date` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.description | ResearchStudy.description | Equivalent | R5 `ResearchStudy.description` maps as Equivalent to R4 `ResearchStudy.description` |
| ResearchStudy.descriptionSummary | - | DoesNotExistInTarget | R5 `ResearchStudy.descriptionSummary` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.extension | ResearchStudy.extension | SourceIsBroaderThanTarget | R5 `ResearchStudy.extension` maps as SourceIsBroaderThanTarget to R4 `ResearchStudy.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ResearchStudy.focus | ResearchStudy.focus | SourceIsBroaderThanTarget | R5 `ResearchStudy.focus` maps as SourceIsBroaderThanTarget to R4 `ResearchStudy.focus` - focus has change due to type change: R5 focus CodeableReference has no equivalent or mapped type in R4 focus |
| ResearchStudy.id | ResearchStudy.id | Equivalent | R5 `ResearchStudy.id` maps as Equivalent to R4 `ResearchStudy.id` |
| ResearchStudy.identifier | ResearchStudy.identifier | Equivalent | R5 `ResearchStudy.identifier` maps as Equivalent to R4 `ResearchStudy.identifier` |
| ResearchStudy.implicitRules | ResearchStudy.implicitRules | Equivalent | R5 `ResearchStudy.implicitRules` maps as Equivalent to R4 `ResearchStudy.implicitRules` |
| ResearchStudy.keyword | ResearchStudy.keyword | Equivalent | R5 `ResearchStudy.keyword` maps as Equivalent to R4 `ResearchStudy.keyword` |
| ResearchStudy.label | - | DoesNotExistInTarget | R5 `ResearchStudy.label` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.label.extension | - | DoesNotExistInTarget | R5 `ResearchStudy.label.extension` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.label.id | - | DoesNotExistInTarget | R5 `ResearchStudy.label.id` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.label.modifierExtension | - | DoesNotExistInTarget | R5 `ResearchStudy.label.modifierExtension` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.label.type | - | DoesNotExistInTarget | R5 `ResearchStudy.label.type` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.label.value | - | DoesNotExistInTarget | R5 `ResearchStudy.label.value` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.language | ResearchStudy.language | RelatedTo | R5 `ResearchStudy.language` maps as RelatedTo to R4 `ResearchStudy.language` - language changed the binding strength from Required to Preferred |
| ResearchStudy.meta | ResearchStudy.meta | Equivalent | R5 `ResearchStudy.meta` maps as Equivalent to R4 `ResearchStudy.meta` |
| ResearchStudy.modifierExtension | ResearchStudy.modifierExtension | SourceIsBroaderThanTarget | R5 `ResearchStudy.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ResearchStudy.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ResearchStudy.name | - | DoesNotExistInTarget | R5 `ResearchStudy.name` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.note | ResearchStudy.note | SourceIsBroaderThanTarget | R5 `ResearchStudy.note` maps as SourceIsBroaderThanTarget to R4 `ResearchStudy.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4 `note` |
| ResearchStudy.objective | ResearchStudy.objective | Equivalent | R5 `ResearchStudy.objective` maps as Equivalent to R4 `ResearchStudy.objective` |
| ResearchStudy.objective.description | - | DoesNotExistInTarget | R5 `ResearchStudy.objective.description` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.objective.extension | ResearchStudy.objective.extension | SourceIsBroaderThanTarget | R5 `ResearchStudy.objective.extension` maps as SourceIsBroaderThanTarget to R4 `ResearchStudy.objective.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ResearchStudy.objective.id | ResearchStudy.objective.id | Equivalent | R5 `ResearchStudy.objective.id` maps as Equivalent to R4 `ResearchStudy.objective.id` |
| ResearchStudy.objective.modifierExtension | ResearchStudy.objective.modifierExtension | SourceIsBroaderThanTarget | R5 `ResearchStudy.objective.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ResearchStudy.objective.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ResearchStudy.objective.name | ResearchStudy.objective.name | Equivalent | R5 `ResearchStudy.objective.name` maps as Equivalent to R4 `ResearchStudy.objective.name` |
| ResearchStudy.objective.type | ResearchStudy.objective.type | Equivalent | R5 `ResearchStudy.objective.type` maps as Equivalent to R4 `ResearchStudy.objective.type` |
| ResearchStudy.outcomeMeasure | - | DoesNotExistInTarget | R5 `ResearchStudy.outcomeMeasure` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.outcomeMeasure.description | - | DoesNotExistInTarget | R5 `ResearchStudy.outcomeMeasure.description` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.outcomeMeasure.extension | - | DoesNotExistInTarget | R5 `ResearchStudy.outcomeMeasure.extension` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.outcomeMeasure.id | - | DoesNotExistInTarget | R5 `ResearchStudy.outcomeMeasure.id` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.outcomeMeasure.modifierExtension | - | DoesNotExistInTarget | R5 `ResearchStudy.outcomeMeasure.modifierExtension` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.outcomeMeasure.name | - | DoesNotExistInTarget | R5 `ResearchStudy.outcomeMeasure.name` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.outcomeMeasure.reference | - | DoesNotExistInTarget | R5 `ResearchStudy.outcomeMeasure.reference` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.outcomeMeasure.type | - | DoesNotExistInTarget | R5 `ResearchStudy.outcomeMeasure.type` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.partOf | ResearchStudy.partOf | Equivalent | R5 `ResearchStudy.partOf` maps as Equivalent to R4 `ResearchStudy.partOf` |
| ResearchStudy.period | ResearchStudy.period | Equivalent | R5 `ResearchStudy.period` maps as Equivalent to R4 `ResearchStudy.period` |
| ResearchStudy.phase | ResearchStudy.phase | Equivalent | R5 `ResearchStudy.phase` maps as Equivalent to R4 `ResearchStudy.phase` |
| ResearchStudy.primaryPurposeType | ResearchStudy.primaryPurposeType | RelatedTo | R5 `ResearchStudy.primaryPurposeType` maps as RelatedTo to R4 `ResearchStudy.primaryPurposeType` - primaryPurposeType changed the binding strength from Preferred to Extensible |
| ResearchStudy.progressStatus | - | DoesNotExistInTarget | R5 `ResearchStudy.progressStatus` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.progressStatus.actual | - | DoesNotExistInTarget | R5 `ResearchStudy.progressStatus.actual` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.progressStatus.extension | - | DoesNotExistInTarget | R5 `ResearchStudy.progressStatus.extension` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.progressStatus.id | - | DoesNotExistInTarget | R5 `ResearchStudy.progressStatus.id` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.progressStatus.modifierExtension | - | DoesNotExistInTarget | R5 `ResearchStudy.progressStatus.modifierExtension` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.progressStatus.period | - | DoesNotExistInTarget | R5 `ResearchStudy.progressStatus.period` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.progressStatus.state | - | DoesNotExistInTarget | R5 `ResearchStudy.progressStatus.state` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.protocol | ResearchStudy.protocol | Equivalent | R5 `ResearchStudy.protocol` maps as Equivalent to R4 `ResearchStudy.protocol` |
| ResearchStudy.recruitment | - | DoesNotExistInTarget | R5 `ResearchStudy.recruitment` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.recruitment.actualGroup | - | DoesNotExistInTarget | R5 `ResearchStudy.recruitment.actualGroup` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.recruitment.actualNumber | - | DoesNotExistInTarget | R5 `ResearchStudy.recruitment.actualNumber` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.recruitment.eligibility | - | DoesNotExistInTarget | R5 `ResearchStudy.recruitment.eligibility` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.recruitment.extension | - | DoesNotExistInTarget | R5 `ResearchStudy.recruitment.extension` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.recruitment.id | - | DoesNotExistInTarget | R5 `ResearchStudy.recruitment.id` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.recruitment.modifierExtension | - | DoesNotExistInTarget | R5 `ResearchStudy.recruitment.modifierExtension` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.recruitment.targetNumber | - | DoesNotExistInTarget | R5 `ResearchStudy.recruitment.targetNumber` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.region | - | DoesNotExistInTarget | R5 `ResearchStudy.region` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.relatedArtifact | ResearchStudy.relatedArtifact | Equivalent | R5 `ResearchStudy.relatedArtifact` maps as Equivalent to R4 `ResearchStudy.relatedArtifact` |
| ResearchStudy.result | - | DoesNotExistInTarget | R5 `ResearchStudy.result` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.site | ResearchStudy.site | SourceIsBroaderThanTarget | R5 `ResearchStudy.site` maps as SourceIsBroaderThanTarget to R4 `ResearchStudy.site` - site has change due to type change: R5 `site` `Reference` maps as SourceIsBroaderThanTarget for R4 `site` |
| ResearchStudy.status | ResearchStudy.status | Equivalent | R5 `ResearchStudy.status` maps as Equivalent to R4 `ResearchStudy.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|5.0.0 and http://hl7.org/fhir/ValueSet/research-study-status|4.0.1 (Equivalent) |
| ResearchStudy.studyDesign | - | DoesNotExistInTarget | R5 `ResearchStudy.studyDesign` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.text | ResearchStudy.text | Equivalent | R5 `ResearchStudy.text` maps as Equivalent to R4 `ResearchStudy.text` |
| ResearchStudy.title | ResearchStudy.title | Equivalent | R5 `ResearchStudy.title` maps as Equivalent to R4 `ResearchStudy.title` |
| ResearchStudy.url | - | DoesNotExistInTarget | R5 `ResearchStudy.url` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.version | - | DoesNotExistInTarget | R5 `ResearchStudy.version` does not appear in the target and has no mapping for `ResearchStudy`. |
| ResearchStudy.whyStopped | - | DoesNotExistInTarget | R5 `ResearchStudy.whyStopped` does not appear in the target and has no mapping for `ResearchStudy`. |

