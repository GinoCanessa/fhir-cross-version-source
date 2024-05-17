Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | RiskAssessment |  | An assessment of the likely outcome(s) for a patient or other subject as well as the likelihood of each outcome. | 34 | 23 |
| Target | RiskAssessment |  | An assessment of the likely outcome(s) for a patient or other subject as well as the likelihood of each outcome. | 35 | 24 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 1 |
Equivalent | 4 |
RelatedTo | 29 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| RiskAssessment | RiskAssessment | Equivalent | R5 `RiskAssessment` maps as Equivalent to R4B `RiskAssessment` |
| RiskAssessment.basedOn | RiskAssessment.basedOn | Equivalent | R5 `RiskAssessment.basedOn` maps as Equivalent to R4B `RiskAssessment.basedOn` |
| RiskAssessment.basis | RiskAssessment.basis | Equivalent | R5 `RiskAssessment.basis` maps as Equivalent to R4B `RiskAssessment.basis` |
| RiskAssessment.code | RiskAssessment.code | Equivalent | R5 `RiskAssessment.code` maps as Equivalent to R4B `RiskAssessment.code` |
| RiskAssessment.condition | RiskAssessment.condition | Equivalent | R5 `RiskAssessment.condition` maps as Equivalent to R4B `RiskAssessment.condition` |
| RiskAssessment.contained | RiskAssessment.contained | Equivalent | R5 `RiskAssessment.contained` maps as Equivalent to R4B `RiskAssessment.contained` |
| RiskAssessment.encounter | RiskAssessment.encounter | Equivalent | R5 `RiskAssessment.encounter` maps as Equivalent to R4B `RiskAssessment.encounter` |
| RiskAssessment.extension | RiskAssessment.extension | SourceIsBroaderThanTarget | R5 `RiskAssessment.extension` maps as SourceIsBroaderThanTarget to R4B `RiskAssessment.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| RiskAssessment.id | RiskAssessment.id | Equivalent | R5 `RiskAssessment.id` maps as Equivalent to R4B `RiskAssessment.id` |
| RiskAssessment.identifier | RiskAssessment.identifier | Equivalent | R5 `RiskAssessment.identifier` maps as Equivalent to R4B `RiskAssessment.identifier` |
| RiskAssessment.implicitRules | RiskAssessment.implicitRules | Equivalent | R5 `RiskAssessment.implicitRules` maps as Equivalent to R4B `RiskAssessment.implicitRules` |
| RiskAssessment.language | RiskAssessment.language | RelatedTo | R5 `RiskAssessment.language` maps as RelatedTo to R4B `RiskAssessment.language` - language changed the binding strength from Required to Preferred |
| RiskAssessment.meta | RiskAssessment.meta | Equivalent | R5 `RiskAssessment.meta` maps as Equivalent to R4B `RiskAssessment.meta` |
| RiskAssessment.method | RiskAssessment.method | Equivalent | R5 `RiskAssessment.method` maps as Equivalent to R4B `RiskAssessment.method` |
| RiskAssessment.mitigation | RiskAssessment.mitigation | Equivalent | R5 `RiskAssessment.mitigation` maps as Equivalent to R4B `RiskAssessment.mitigation` |
| RiskAssessment.modifierExtension | RiskAssessment.modifierExtension | SourceIsBroaderThanTarget | R5 `RiskAssessment.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `RiskAssessment.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| RiskAssessment.note | RiskAssessment.note | SourceIsBroaderThanTarget | R5 `RiskAssessment.note` maps as SourceIsBroaderThanTarget to R4B `RiskAssessment.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4B `note` |
| RiskAssessment.occurrence[x] | RiskAssessment.occurrence[x] | Equivalent | R5 `RiskAssessment.occurrence[x]` maps as Equivalent to R4B `RiskAssessment.occurrence[x]` |
| RiskAssessment.parent | RiskAssessment.parent | Equivalent | R5 `RiskAssessment.parent` maps as Equivalent to R4B `RiskAssessment.parent` |
| RiskAssessment.performer | RiskAssessment.performer | SourceIsBroaderThanTarget | R5 `RiskAssessment.performer` maps as SourceIsBroaderThanTarget to R4B `RiskAssessment.performer` - performer has change due to type change: R5 `performer` `Reference` maps as SourceIsBroaderThanTarget for R4B `performer` |
| RiskAssessment.prediction | RiskAssessment.prediction | Equivalent | R5 `RiskAssessment.prediction` maps as Equivalent to R4B `RiskAssessment.prediction` |
| RiskAssessment.prediction.extension | RiskAssessment.prediction.extension | SourceIsBroaderThanTarget | R5 `RiskAssessment.prediction.extension` maps as SourceIsBroaderThanTarget to R4B `RiskAssessment.prediction.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| RiskAssessment.prediction.id | RiskAssessment.prediction.id | Equivalent | R5 `RiskAssessment.prediction.id` maps as Equivalent to R4B `RiskAssessment.prediction.id` |
| RiskAssessment.prediction.modifierExtension | RiskAssessment.prediction.modifierExtension | SourceIsBroaderThanTarget | R5 `RiskAssessment.prediction.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `RiskAssessment.prediction.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| RiskAssessment.prediction.outcome | RiskAssessment.prediction.outcome | Equivalent | R5 `RiskAssessment.prediction.outcome` maps as Equivalent to R4B `RiskAssessment.prediction.outcome` |
| RiskAssessment.prediction.probability[x] | RiskAssessment.prediction.probability[x] | Equivalent | R5 `RiskAssessment.prediction.probability[x]` maps as Equivalent to R4B `RiskAssessment.prediction.probability[x]` |
| RiskAssessment.prediction.qualitativeRisk | RiskAssessment.prediction.qualitativeRisk | Equivalent | R5 `RiskAssessment.prediction.qualitativeRisk` maps as Equivalent to R4B `RiskAssessment.prediction.qualitativeRisk` |
| RiskAssessment.prediction.rationale | RiskAssessment.prediction.rationale | Equivalent | R5 `RiskAssessment.prediction.rationale` maps as Equivalent to R4B `RiskAssessment.prediction.rationale` |
| RiskAssessment.prediction.relativeRisk | RiskAssessment.prediction.relativeRisk | Equivalent | R5 `RiskAssessment.prediction.relativeRisk` maps as Equivalent to R4B `RiskAssessment.prediction.relativeRisk` |
| RiskAssessment.prediction.when[x] | RiskAssessment.prediction.when[x] | Equivalent | R5 `RiskAssessment.prediction.when[x]` maps as Equivalent to R4B `RiskAssessment.prediction.when[x]` |
| RiskAssessment.reason | - | DoesNotExistInTarget | R5 `RiskAssessment.reason` does not appear in the target and has no mapping for `RiskAssessment`. |
| RiskAssessment.status | RiskAssessment.status | Equivalent | R5 `RiskAssessment.status` maps as Equivalent to R4B `RiskAssessment.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/observation-status|5.0.0 and http://hl7.org/fhir/ValueSet/observation-status|4.3.0 (Equivalent) |
| RiskAssessment.subject | RiskAssessment.subject | Equivalent | R5 `RiskAssessment.subject` maps as Equivalent to R4B `RiskAssessment.subject` |
| RiskAssessment.text | RiskAssessment.text | Equivalent | R5 `RiskAssessment.text` maps as Equivalent to R4B `RiskAssessment.text` |

