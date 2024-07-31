Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | RiskAssessment |  | An assessment of the likely outcome(s) for a patient or other subject as well as the likelihood of each outcome. | 34 | 23 |
| Target | RiskAssessment |  | An assessment of the likely outcome(s) for a patient or other subject as well as the likelihood of each outcome. | 35 | 24 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 26 |
SourceIsBroaderThanTarget | 7 |
SourceIsNarrowerThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| RiskAssessment | RiskAssessment | Equivalent | R5 `RiskAssessment` maps as Equivalent to R4 `RiskAssessment` |
| RiskAssessment.basedOn | RiskAssessment.basedOn | Equivalent | R5 `RiskAssessment.basedOn` maps as Equivalent to R4 `RiskAssessment.basedOn` |
| RiskAssessment.basis | RiskAssessment.basis | Equivalent | R5 `RiskAssessment.basis` maps as Equivalent to R4 `RiskAssessment.basis` |
| RiskAssessment.code | RiskAssessment.code | Equivalent | R5 `RiskAssessment.code` maps as Equivalent to R4 `RiskAssessment.code` |
| RiskAssessment.condition | RiskAssessment.condition | Equivalent | R5 `RiskAssessment.condition` maps as Equivalent to R4 `RiskAssessment.condition` |
| RiskAssessment.contained | RiskAssessment.contained | Equivalent | R5 `RiskAssessment.contained` maps as Equivalent to R4 `RiskAssessment.contained` |
| RiskAssessment.encounter | RiskAssessment.encounter | Equivalent | R5 `RiskAssessment.encounter` maps as Equivalent to R4 `RiskAssessment.encounter` |
| RiskAssessment.extension | RiskAssessment.extension | SourceIsBroaderThanTarget | R5 `RiskAssessment.extension` maps as SourceIsBroaderThanTarget to R4 `RiskAssessment.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| RiskAssessment.id | RiskAssessment.id | Equivalent | R5 `RiskAssessment.id` maps as Equivalent to R4 `RiskAssessment.id` |
| RiskAssessment.identifier | RiskAssessment.identifier | Equivalent | R5 `RiskAssessment.identifier` maps as Equivalent to R4 `RiskAssessment.identifier` |
| RiskAssessment.implicitRules | RiskAssessment.implicitRules | Equivalent | R5 `RiskAssessment.implicitRules` maps as Equivalent to R4 `RiskAssessment.implicitRules` |
| RiskAssessment.language | RiskAssessment.language | SourceIsNarrowerThanTarget | R5 `RiskAssessment.language` maps as SourceIsNarrowerThanTarget to R4 `RiskAssessment.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| RiskAssessment.meta | RiskAssessment.meta | Equivalent | R5 `RiskAssessment.meta` maps as Equivalent to R4 `RiskAssessment.meta` |
| RiskAssessment.method | RiskAssessment.method | Equivalent | R5 `RiskAssessment.method` maps as Equivalent to R4 `RiskAssessment.method` |
| RiskAssessment.mitigation | RiskAssessment.mitigation | Equivalent | R5 `RiskAssessment.mitigation` maps as Equivalent to R4 `RiskAssessment.mitigation` |
| RiskAssessment.modifierExtension | RiskAssessment.modifierExtension | SourceIsBroaderThanTarget | R5 `RiskAssessment.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `RiskAssessment.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| RiskAssessment.note | RiskAssessment.note | SourceIsBroaderThanTarget | R5 `RiskAssessment.note` maps as SourceIsBroaderThanTarget to R4 `RiskAssessment.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4 `note` |
| RiskAssessment.occurrence[x] | RiskAssessment.occurrence[x] | Equivalent | R5 `RiskAssessment.occurrence[x]` maps as Equivalent to R4 `RiskAssessment.occurrence[x]` |
| RiskAssessment.parent | RiskAssessment.parent | Equivalent | R5 `RiskAssessment.parent` maps as Equivalent to R4 `RiskAssessment.parent` |
| RiskAssessment.performer | RiskAssessment.performer | SourceIsBroaderThanTarget | R5 `RiskAssessment.performer` maps as SourceIsBroaderThanTarget to R4 `RiskAssessment.performer` - performer has change due to type change: R5 `performer` `Reference` maps as SourceIsBroaderThanTarget for R4 `performer` |
| RiskAssessment.prediction | RiskAssessment.prediction | Equivalent | R5 `RiskAssessment.prediction` maps as Equivalent to R4 `RiskAssessment.prediction` |
| RiskAssessment.prediction.extension | RiskAssessment.prediction.extension | SourceIsBroaderThanTarget | R5 `RiskAssessment.prediction.extension` maps as SourceIsBroaderThanTarget to R4 `RiskAssessment.prediction.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| RiskAssessment.prediction.id | RiskAssessment.prediction.id | Equivalent | R5 `RiskAssessment.prediction.id` maps as Equivalent to R4 `RiskAssessment.prediction.id` |
| RiskAssessment.prediction.modifierExtension | RiskAssessment.prediction.modifierExtension | SourceIsBroaderThanTarget | R5 `RiskAssessment.prediction.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `RiskAssessment.prediction.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| RiskAssessment.prediction.outcome | RiskAssessment.prediction.outcome | Equivalent | R5 `RiskAssessment.prediction.outcome` maps as Equivalent to R4 `RiskAssessment.prediction.outcome` |
| RiskAssessment.prediction.probability[x] | RiskAssessment.prediction.probability[x] | Equivalent | R5 `RiskAssessment.prediction.probability[x]` maps as Equivalent to R4 `RiskAssessment.prediction.probability[x]` |
| RiskAssessment.prediction.qualitativeRisk | RiskAssessment.prediction.qualitativeRisk | Equivalent | R5 `RiskAssessment.prediction.qualitativeRisk` maps as Equivalent to R4 `RiskAssessment.prediction.qualitativeRisk` |
| RiskAssessment.prediction.rationale | RiskAssessment.prediction.rationale | Equivalent | R5 `RiskAssessment.prediction.rationale` maps as Equivalent to R4 `RiskAssessment.prediction.rationale` |
| RiskAssessment.prediction.relativeRisk | RiskAssessment.prediction.relativeRisk | Equivalent | R5 `RiskAssessment.prediction.relativeRisk` maps as Equivalent to R4 `RiskAssessment.prediction.relativeRisk` |
| RiskAssessment.prediction.when[x] | RiskAssessment.prediction.when[x] | Equivalent | R5 `RiskAssessment.prediction.when[x]` maps as Equivalent to R4 `RiskAssessment.prediction.when[x]` |
| RiskAssessment.reason | RiskAssessment.reasonCode | SourceIsBroaderThanTarget | R5 `RiskAssessment.reason` maps as SourceIsBroaderThanTarget to R4 `RiskAssessment.reasonCode` - reasonCode has change due to type change: R5 reason CodeableReference has no equivalent or mapped type in R4 reasonCode |
| RiskAssessment.reason | RiskAssessment.reasonReference | SourceIsBroaderThanTarget | R5 `RiskAssessment.reason` maps as SourceIsBroaderThanTarget to R4 `RiskAssessment.reasonReference` - reasonReference has change due to type change: R5 reason CodeableReference has no equivalent or mapped type in R4 reasonReference |
| RiskAssessment.status | RiskAssessment.status | Equivalent | R5 `RiskAssessment.status` maps as Equivalent to R4 `RiskAssessment.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/observation-status|5.0.0 and http://hl7.org/fhir/ValueSet/observation-status|4.0.1 (Equivalent) |
| RiskAssessment.subject | RiskAssessment.subject | Equivalent | R5 `RiskAssessment.subject` maps as Equivalent to R4 `RiskAssessment.subject` |
| RiskAssessment.text | RiskAssessment.text | Equivalent | R5 `RiskAssessment.text` maps as Equivalent to R4 `RiskAssessment.text` |

