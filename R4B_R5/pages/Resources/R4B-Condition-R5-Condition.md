Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Condition |  | A clinical condition, problem, diagnosis, or other event, situation, issue, or clinical concept that has risen to a level of concern. | 37 | 23 |
| Target | Condition |  | A clinical condition, problem, diagnosis, or other event, situation, issue, or clinical concept that has risen to a level of concern. | 36 | 22 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 7 |
Equivalent | 4 |
RelatedTo | 26 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Condition | Condition | Equivalent | R4B `Condition` maps as Equivalent to R5 `Condition` |
| Condition.abatement[x] | Condition.abatement[x] | Equivalent | R4B `Condition.abatement[x]` maps as Equivalent to R5 `Condition.abatement[x]` |
| Condition.asserter | - | DoesNotExistInTarget | R4B `Condition.asserter` does not appear in the target and has no mapping for `Condition`. |
| Condition.bodySite | Condition.bodySite | Equivalent | R4B `Condition.bodySite` maps as Equivalent to R5 `Condition.bodySite` |
| Condition.category | Condition.category | RelatedTo | R4B `Condition.category` maps as RelatedTo to R5 `Condition.category` - category changed the binding strength from Extensible to Preferred |
| Condition.clinicalStatus | Condition.clinicalStatus | RelatedTo | R4B `Condition.clinicalStatus` maps as RelatedTo to R5 `Condition.clinicalStatus` - clinicalStatus made the element mandatory; clinicalStatus increased the minimum cardinality from 0 to 1; clinicalStatus has compatible required binding for non-code type: http://hl7.org/fhir/ValueSet/condition-clinical|4.3.0 and http://hl7.org/fhir/ValueSet/condition-clinical|5.0.0 (Equivalent) |
| Condition.code | Condition.code | Equivalent | R4B `Condition.code` maps as Equivalent to R5 `Condition.code` |
| Condition.contained | Condition.contained | Equivalent | R4B `Condition.contained` maps as Equivalent to R5 `Condition.contained` |
| Condition.encounter | Condition.encounter | Equivalent | R4B `Condition.encounter` maps as Equivalent to R5 `Condition.encounter` |
| Condition.evidence | Condition.evidence | RelatedTo | R4B `Condition.evidence` maps as RelatedTo to R5 `Condition.evidence` - evidence added a binding requirement - Example http://hl7.org/fhir/ValueSet/clinical-findings; evidence has change due to type change: R4B evidence BackboneElement has no equivalent or mapped type in R5 evidence |
| Condition.evidence.code | - | DoesNotExistInTarget | R4B `Condition.evidence.code` does not appear in the target and has no mapping for `Condition`. |
| Condition.evidence.detail | - | DoesNotExistInTarget | R4B `Condition.evidence.detail` does not appear in the target and has no mapping for `Condition`. |
| Condition.evidence.extension | - | DoesNotExistInTarget | R4B `Condition.evidence.extension` does not appear in the target and has no mapping for `Condition`. |
| Condition.evidence.id | - | DoesNotExistInTarget | R4B `Condition.evidence.id` does not appear in the target and has no mapping for `Condition`. |
| Condition.evidence.modifierExtension | - | DoesNotExistInTarget | R4B `Condition.evidence.modifierExtension` does not appear in the target and has no mapping for `Condition`. |
| Condition.extension | Condition.extension | RelatedTo | R4B `Condition.extension` maps as RelatedTo to R5 `Condition.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Condition.id | Condition.id | Equivalent | R4B `Condition.id` maps as Equivalent to R5 `Condition.id` |
| Condition.identifier | Condition.identifier | Equivalent | R4B `Condition.identifier` maps as Equivalent to R5 `Condition.identifier` |
| Condition.implicitRules | Condition.implicitRules | Equivalent | R4B `Condition.implicitRules` maps as Equivalent to R5 `Condition.implicitRules` |
| Condition.language | Condition.language | RelatedTo | R4B `Condition.language` maps as RelatedTo to R5 `Condition.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Condition.meta | Condition.meta | Equivalent | R4B `Condition.meta` maps as Equivalent to R5 `Condition.meta` |
| Condition.modifierExtension | Condition.modifierExtension | RelatedTo | R4B `Condition.modifierExtension` maps as RelatedTo to R5 `Condition.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Condition.note | Condition.note | SourceIsNarrowerThanTarget | R4B `Condition.note` maps as SourceIsNarrowerThanTarget to R5 `Condition.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| Condition.onset[x] | Condition.onset[x] | Equivalent | R4B `Condition.onset[x]` maps as Equivalent to R5 `Condition.onset[x]` |
| Condition.recordedDate | Condition.recordedDate | Equivalent | R4B `Condition.recordedDate` maps as Equivalent to R5 `Condition.recordedDate` |
| Condition.recorder | - | DoesNotExistInTarget | R4B `Condition.recorder` does not appear in the target and has no mapping for `Condition`. |
| Condition.severity | Condition.severity | Equivalent | R4B `Condition.severity` maps as Equivalent to R5 `Condition.severity` |
| Condition.stage | Condition.stage | Equivalent | R4B `Condition.stage` maps as Equivalent to R5 `Condition.stage` |
| Condition.stage.assessment | Condition.stage.assessment | Equivalent | R4B `Condition.stage.assessment` maps as Equivalent to R5 `Condition.stage.assessment` |
| Condition.stage.extension | Condition.stage.extension | RelatedTo | R4B `Condition.stage.extension` maps as RelatedTo to R5 `Condition.stage.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Condition.stage.id | Condition.stage.id | Equivalent | R4B `Condition.stage.id` maps as Equivalent to R5 `Condition.stage.id` |
| Condition.stage.modifierExtension | Condition.stage.modifierExtension | RelatedTo | R4B `Condition.stage.modifierExtension` maps as RelatedTo to R5 `Condition.stage.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Condition.stage.summary | Condition.stage.summary | Equivalent | R4B `Condition.stage.summary` maps as Equivalent to R5 `Condition.stage.summary` |
| Condition.stage.type | Condition.stage.type | Equivalent | R4B `Condition.stage.type` maps as Equivalent to R5 `Condition.stage.type` |
| Condition.subject | Condition.subject | Equivalent | R4B `Condition.subject` maps as Equivalent to R5 `Condition.subject` |
| Condition.text | Condition.text | Equivalent | R4B `Condition.text` maps as Equivalent to R5 `Condition.text` |
| Condition.verificationStatus | Condition.verificationStatus | Equivalent | R4B `Condition.verificationStatus` maps as Equivalent to R5 `Condition.verificationStatus` - verificationStatus has compatible required binding for non-code type: http://hl7.org/fhir/ValueSet/condition-ver-status|4.3.0 and http://hl7.org/fhir/ValueSet/condition-ver-status|5.0.0 (Equivalent) |

