Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | EpisodeOfCare |  | An association between a patient and an organization / healthcare provider(s) during which time encounters may occur. The managing organization assumes a level of responsibility for the patient during this time. | 37 | 20 |
| Target | EpisodeOfCare |  | An association between a patient and an organization / healthcare provider(s) during which time encounters may occur. The managing organization assumes a level of responsibility for the patient during this time. | 32 | 18 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 8 |
Equivalent | 4 |
RelatedTo | 25 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| EpisodeOfCare | EpisodeOfCare | Equivalent | R5 `EpisodeOfCare` maps as Equivalent to R4 `EpisodeOfCare` |
| EpisodeOfCare.account | EpisodeOfCare.account | Equivalent | R5 `EpisodeOfCare.account` maps as Equivalent to R4 `EpisodeOfCare.account` |
| EpisodeOfCare.careManager | EpisodeOfCare.careManager | Equivalent | R5 `EpisodeOfCare.careManager` maps as Equivalent to R4 `EpisodeOfCare.careManager` |
| EpisodeOfCare.careTeam | - | DoesNotExistInTarget | R5 `EpisodeOfCare.careTeam` does not appear in the target and has no mapping for `EpisodeOfCare`. |
| EpisodeOfCare.contained | EpisodeOfCare.contained | Equivalent | R5 `EpisodeOfCare.contained` maps as Equivalent to R4 `EpisodeOfCare.contained` |
| EpisodeOfCare.diagnosis | EpisodeOfCare.diagnosis | Equivalent | R5 `EpisodeOfCare.diagnosis` maps as Equivalent to R4 `EpisodeOfCare.diagnosis` |
| EpisodeOfCare.diagnosis.condition | EpisodeOfCare.diagnosis.condition | RelatedTo | R5 `EpisodeOfCare.diagnosis.condition` maps as RelatedTo to R4 `EpisodeOfCare.diagnosis.condition` - condition made the element mandatory; condition increased the minimum cardinality from 0 to 1; condition changed from array to scalar (max cardinality from * to 1); condition removed a binding requirement - Example http://hl7.org/fhir/ValueSet/condition-code; condition has change due to type change: R5 condition CodeableReference has no equivalent or mapped type in R4 condition |
| EpisodeOfCare.diagnosis.extension | EpisodeOfCare.diagnosis.extension | SourceIsBroaderThanTarget | R5 `EpisodeOfCare.diagnosis.extension` maps as SourceIsBroaderThanTarget to R4 `EpisodeOfCare.diagnosis.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| EpisodeOfCare.diagnosis.id | EpisodeOfCare.diagnosis.id | Equivalent | R5 `EpisodeOfCare.diagnosis.id` maps as Equivalent to R4 `EpisodeOfCare.diagnosis.id` |
| EpisodeOfCare.diagnosis.modifierExtension | EpisodeOfCare.diagnosis.modifierExtension | SourceIsBroaderThanTarget | R5 `EpisodeOfCare.diagnosis.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `EpisodeOfCare.diagnosis.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| EpisodeOfCare.diagnosis.use | - | DoesNotExistInTarget | R5 `EpisodeOfCare.diagnosis.use` does not appear in the target and has no mapping for `EpisodeOfCare`. |
| EpisodeOfCare.extension | EpisodeOfCare.extension | SourceIsBroaderThanTarget | R5 `EpisodeOfCare.extension` maps as SourceIsBroaderThanTarget to R4 `EpisodeOfCare.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| EpisodeOfCare.id | EpisodeOfCare.id | Equivalent | R5 `EpisodeOfCare.id` maps as Equivalent to R4 `EpisodeOfCare.id` |
| EpisodeOfCare.identifier | EpisodeOfCare.identifier | Equivalent | R5 `EpisodeOfCare.identifier` maps as Equivalent to R4 `EpisodeOfCare.identifier` |
| EpisodeOfCare.implicitRules | EpisodeOfCare.implicitRules | Equivalent | R5 `EpisodeOfCare.implicitRules` maps as Equivalent to R4 `EpisodeOfCare.implicitRules` |
| EpisodeOfCare.language | EpisodeOfCare.language | RelatedTo | R5 `EpisodeOfCare.language` maps as RelatedTo to R4 `EpisodeOfCare.language` - language changed the binding strength from Required to Preferred |
| EpisodeOfCare.managingOrganization | EpisodeOfCare.managingOrganization | Equivalent | R5 `EpisodeOfCare.managingOrganization` maps as Equivalent to R4 `EpisodeOfCare.managingOrganization` |
| EpisodeOfCare.meta | EpisodeOfCare.meta | Equivalent | R5 `EpisodeOfCare.meta` maps as Equivalent to R4 `EpisodeOfCare.meta` |
| EpisodeOfCare.modifierExtension | EpisodeOfCare.modifierExtension | SourceIsBroaderThanTarget | R5 `EpisodeOfCare.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `EpisodeOfCare.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| EpisodeOfCare.patient | EpisodeOfCare.patient | Equivalent | R5 `EpisodeOfCare.patient` maps as Equivalent to R4 `EpisodeOfCare.patient` |
| EpisodeOfCare.period | EpisodeOfCare.period | Equivalent | R5 `EpisodeOfCare.period` maps as Equivalent to R4 `EpisodeOfCare.period` |
| EpisodeOfCare.reason | - | DoesNotExistInTarget | R5 `EpisodeOfCare.reason` does not appear in the target and has no mapping for `EpisodeOfCare`. |
| EpisodeOfCare.reason.extension | - | DoesNotExistInTarget | R5 `EpisodeOfCare.reason.extension` does not appear in the target and has no mapping for `EpisodeOfCare`. |
| EpisodeOfCare.reason.id | - | DoesNotExistInTarget | R5 `EpisodeOfCare.reason.id` does not appear in the target and has no mapping for `EpisodeOfCare`. |
| EpisodeOfCare.reason.modifierExtension | - | DoesNotExistInTarget | R5 `EpisodeOfCare.reason.modifierExtension` does not appear in the target and has no mapping for `EpisodeOfCare`. |
| EpisodeOfCare.reason.use | - | DoesNotExistInTarget | R5 `EpisodeOfCare.reason.use` does not appear in the target and has no mapping for `EpisodeOfCare`. |
| EpisodeOfCare.reason.value | - | DoesNotExistInTarget | R5 `EpisodeOfCare.reason.value` does not appear in the target and has no mapping for `EpisodeOfCare`. |
| EpisodeOfCare.referralRequest | EpisodeOfCare.referralRequest | Equivalent | R5 `EpisodeOfCare.referralRequest` maps as Equivalent to R4 `EpisodeOfCare.referralRequest` |
| EpisodeOfCare.status | EpisodeOfCare.status | Equivalent | R5 `EpisodeOfCare.status` maps as Equivalent to R4 `EpisodeOfCare.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/episode-of-care-status|5.0.0 and http://hl7.org/fhir/ValueSet/episode-of-care-status|4.0.1 (Equivalent) |
| EpisodeOfCare.statusHistory | EpisodeOfCare.statusHistory | Equivalent | R5 `EpisodeOfCare.statusHistory` maps as Equivalent to R4 `EpisodeOfCare.statusHistory` |
| EpisodeOfCare.statusHistory.extension | EpisodeOfCare.statusHistory.extension | SourceIsBroaderThanTarget | R5 `EpisodeOfCare.statusHistory.extension` maps as SourceIsBroaderThanTarget to R4 `EpisodeOfCare.statusHistory.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| EpisodeOfCare.statusHistory.id | EpisodeOfCare.statusHistory.id | Equivalent | R5 `EpisodeOfCare.statusHistory.id` maps as Equivalent to R4 `EpisodeOfCare.statusHistory.id` |
| EpisodeOfCare.statusHistory.modifierExtension | EpisodeOfCare.statusHistory.modifierExtension | SourceIsBroaderThanTarget | R5 `EpisodeOfCare.statusHistory.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `EpisodeOfCare.statusHistory.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| EpisodeOfCare.statusHistory.period | EpisodeOfCare.statusHistory.period | Equivalent | R5 `EpisodeOfCare.statusHistory.period` maps as Equivalent to R4 `EpisodeOfCare.statusHistory.period` |
| EpisodeOfCare.statusHistory.status | EpisodeOfCare.statusHistory.status | Equivalent | R5 `EpisodeOfCare.statusHistory.status` maps as Equivalent to R4 `EpisodeOfCare.statusHistory.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/episode-of-care-status|5.0.0 and http://hl7.org/fhir/ValueSet/episode-of-care-status|4.0.1 (Equivalent) |
| EpisodeOfCare.text | EpisodeOfCare.text | Equivalent | R5 `EpisodeOfCare.text` maps as Equivalent to R4 `EpisodeOfCare.text` |
| EpisodeOfCare.type | EpisodeOfCare.type | Equivalent | R5 `EpisodeOfCare.type` maps as Equivalent to R4 `EpisodeOfCare.type` |

