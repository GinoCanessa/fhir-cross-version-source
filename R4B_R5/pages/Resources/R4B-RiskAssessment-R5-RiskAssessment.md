Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | RiskAssessment |  | An assessment of the likely outcome(s) for a patient or other subject as well as the likelihood of each outcome. | 35 | 24 |
| Target | RiskAssessment |  | An assessment of the likely outcome(s) for a patient or other subject as well as the likelihood of each outcome. | 34 | 23 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 2 |
Equivalent | 4 |
RelatedTo | 29 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| RiskAssessment | RiskAssessment | Equivalent | R4B `RiskAssessment` maps as Equivalent to R5 `RiskAssessment` |
| RiskAssessment.basedOn | RiskAssessment.basedOn | Equivalent | R4B `RiskAssessment.basedOn` maps as Equivalent to R5 `RiskAssessment.basedOn` |
| RiskAssessment.basis | RiskAssessment.basis | Equivalent | R4B `RiskAssessment.basis` maps as Equivalent to R5 `RiskAssessment.basis` |
| RiskAssessment.code | RiskAssessment.code | Equivalent | R4B `RiskAssessment.code` maps as Equivalent to R5 `RiskAssessment.code` |
| RiskAssessment.condition | RiskAssessment.condition | Equivalent | R4B `RiskAssessment.condition` maps as Equivalent to R5 `RiskAssessment.condition` |
| RiskAssessment.contained | RiskAssessment.contained | Equivalent | R4B `RiskAssessment.contained` maps as Equivalent to R5 `RiskAssessment.contained` |
| RiskAssessment.encounter | RiskAssessment.encounter | Equivalent | R4B `RiskAssessment.encounter` maps as Equivalent to R5 `RiskAssessment.encounter` |
| RiskAssessment.extension | RiskAssessment.extension | RelatedTo | R4B `RiskAssessment.extension` maps as RelatedTo to R5 `RiskAssessment.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| RiskAssessment.id | RiskAssessment.id | Equivalent | R4B `RiskAssessment.id` maps as Equivalent to R5 `RiskAssessment.id` |
| RiskAssessment.identifier | RiskAssessment.identifier | Equivalent | R4B `RiskAssessment.identifier` maps as Equivalent to R5 `RiskAssessment.identifier` |
| RiskAssessment.implicitRules | RiskAssessment.implicitRules | Equivalent | R4B `RiskAssessment.implicitRules` maps as Equivalent to R5 `RiskAssessment.implicitRules` |
| RiskAssessment.language | RiskAssessment.language | RelatedTo | R4B `RiskAssessment.language` maps as RelatedTo to R5 `RiskAssessment.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| RiskAssessment.meta | RiskAssessment.meta | Equivalent | R4B `RiskAssessment.meta` maps as Equivalent to R5 `RiskAssessment.meta` |
| RiskAssessment.method | RiskAssessment.method | Equivalent | R4B `RiskAssessment.method` maps as Equivalent to R5 `RiskAssessment.method` |
| RiskAssessment.mitigation | RiskAssessment.mitigation | Equivalent | R4B `RiskAssessment.mitigation` maps as Equivalent to R5 `RiskAssessment.mitigation` |
| RiskAssessment.modifierExtension | RiskAssessment.modifierExtension | RelatedTo | R4B `RiskAssessment.modifierExtension` maps as RelatedTo to R5 `RiskAssessment.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| RiskAssessment.note | RiskAssessment.note | SourceIsNarrowerThanTarget | R4B `RiskAssessment.note` maps as SourceIsNarrowerThanTarget to R5 `RiskAssessment.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| RiskAssessment.occurrence[x] | RiskAssessment.occurrence[x] | Equivalent | R4B `RiskAssessment.occurrence[x]` maps as Equivalent to R5 `RiskAssessment.occurrence[x]` |
| RiskAssessment.parent | RiskAssessment.parent | Equivalent | R4B `RiskAssessment.parent` maps as Equivalent to R5 `RiskAssessment.parent` |
| RiskAssessment.performer | RiskAssessment.performer | SourceIsNarrowerThanTarget | R4B `RiskAssessment.performer` maps as SourceIsNarrowerThanTarget to R5 `RiskAssessment.performer` - performer has change due to type change: R4B `performer` `Reference` maps as SourceIsNarrowerThanTarget for R5 `performer` |
| RiskAssessment.prediction | RiskAssessment.prediction | Equivalent | R4B `RiskAssessment.prediction` maps as Equivalent to R5 `RiskAssessment.prediction` |
| RiskAssessment.prediction.extension | RiskAssessment.prediction.extension | RelatedTo | R4B `RiskAssessment.prediction.extension` maps as RelatedTo to R5 `RiskAssessment.prediction.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| RiskAssessment.prediction.id | RiskAssessment.prediction.id | Equivalent | R4B `RiskAssessment.prediction.id` maps as Equivalent to R5 `RiskAssessment.prediction.id` |
| RiskAssessment.prediction.modifierExtension | RiskAssessment.prediction.modifierExtension | RelatedTo | R4B `RiskAssessment.prediction.modifierExtension` maps as RelatedTo to R5 `RiskAssessment.prediction.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| RiskAssessment.prediction.outcome | RiskAssessment.prediction.outcome | Equivalent | R4B `RiskAssessment.prediction.outcome` maps as Equivalent to R5 `RiskAssessment.prediction.outcome` |
| RiskAssessment.prediction.probability[x] | RiskAssessment.prediction.probability[x] | Equivalent | R4B `RiskAssessment.prediction.probability[x]` maps as Equivalent to R5 `RiskAssessment.prediction.probability[x]` |
| RiskAssessment.prediction.qualitativeRisk | RiskAssessment.prediction.qualitativeRisk | Equivalent | R4B `RiskAssessment.prediction.qualitativeRisk` maps as Equivalent to R5 `RiskAssessment.prediction.qualitativeRisk` |
| RiskAssessment.prediction.rationale | RiskAssessment.prediction.rationale | Equivalent | R4B `RiskAssessment.prediction.rationale` maps as Equivalent to R5 `RiskAssessment.prediction.rationale` |
| RiskAssessment.prediction.relativeRisk | RiskAssessment.prediction.relativeRisk | Equivalent | R4B `RiskAssessment.prediction.relativeRisk` maps as Equivalent to R5 `RiskAssessment.prediction.relativeRisk` |
| RiskAssessment.prediction.when[x] | RiskAssessment.prediction.when[x] | Equivalent | R4B `RiskAssessment.prediction.when[x]` maps as Equivalent to R5 `RiskAssessment.prediction.when[x]` |
| RiskAssessment.reasonCode | - | DoesNotExistInTarget | R4B `RiskAssessment.reasonCode` does not appear in the target and has no mapping for `RiskAssessment`. |
| RiskAssessment.reasonReference | - | DoesNotExistInTarget | R4B `RiskAssessment.reasonReference` does not appear in the target and has no mapping for `RiskAssessment`. |
| RiskAssessment.status | RiskAssessment.status | Equivalent | R4B `RiskAssessment.status` maps as Equivalent to R5 `RiskAssessment.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/observation-status|4.3.0 and http://hl7.org/fhir/ValueSet/observation-status|5.0.0 (Equivalent) |
| RiskAssessment.subject | RiskAssessment.subject | Equivalent | R4B `RiskAssessment.subject` maps as Equivalent to R5 `RiskAssessment.subject` |
| RiskAssessment.text | RiskAssessment.text | Equivalent | R4B `RiskAssessment.text` maps as Equivalent to R5 `RiskAssessment.text` |

