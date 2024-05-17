Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | EpisodeOfCare |  | An association between a patient and an organization / healthcare provider(s) during which time encounters may occur. The managing organization assumes a level of responsibility for the patient during this time. | 32 | 18 |
| Target | EpisodeOfCare |  | An association between a patient and an organization / healthcare provider(s) during which time encounters may occur. The managing organization assumes a level of responsibility for the patient during this time. | 37 | 20 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 3 |
Equivalent | 4 |
RelatedTo | 25 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| EpisodeOfCare | EpisodeOfCare | Equivalent | R4B `EpisodeOfCare` maps as Equivalent to R5 `EpisodeOfCare` |
| EpisodeOfCare.account | EpisodeOfCare.account | Equivalent | R4B `EpisodeOfCare.account` maps as Equivalent to R5 `EpisodeOfCare.account` |
| EpisodeOfCare.careManager | EpisodeOfCare.careManager | Equivalent | R4B `EpisodeOfCare.careManager` maps as Equivalent to R5 `EpisodeOfCare.careManager` |
| EpisodeOfCare.contained | EpisodeOfCare.contained | Equivalent | R4B `EpisodeOfCare.contained` maps as Equivalent to R5 `EpisodeOfCare.contained` |
| EpisodeOfCare.diagnosis | EpisodeOfCare.diagnosis | Equivalent | R4B `EpisodeOfCare.diagnosis` maps as Equivalent to R5 `EpisodeOfCare.diagnosis` |
| EpisodeOfCare.diagnosis.condition | EpisodeOfCare.diagnosis.condition | RelatedTo | R4B `EpisodeOfCare.diagnosis.condition` maps as RelatedTo to R5 `EpisodeOfCare.diagnosis.condition` - condition changed from scalar to array (max cardinality from 1 to *); condition added a binding requirement - Example http://hl7.org/fhir/ValueSet/condition-code; condition has change due to type change: R4B condition Reference has no equivalent or mapped type in R5 condition |
| EpisodeOfCare.diagnosis.extension | EpisodeOfCare.diagnosis.extension | RelatedTo | R4B `EpisodeOfCare.diagnosis.extension` maps as RelatedTo to R5 `EpisodeOfCare.diagnosis.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| EpisodeOfCare.diagnosis.id | EpisodeOfCare.diagnosis.id | Equivalent | R4B `EpisodeOfCare.diagnosis.id` maps as Equivalent to R5 `EpisodeOfCare.diagnosis.id` |
| EpisodeOfCare.diagnosis.modifierExtension | EpisodeOfCare.diagnosis.modifierExtension | RelatedTo | R4B `EpisodeOfCare.diagnosis.modifierExtension` maps as RelatedTo to R5 `EpisodeOfCare.diagnosis.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| EpisodeOfCare.diagnosis.rank | - | DoesNotExistInTarget | R4B `EpisodeOfCare.diagnosis.rank` does not appear in the target and has no mapping for `EpisodeOfCare`. |
| EpisodeOfCare.diagnosis.role | - | DoesNotExistInTarget | R4B `EpisodeOfCare.diagnosis.role` does not appear in the target and has no mapping for `EpisodeOfCare`. |
| EpisodeOfCare.extension | EpisodeOfCare.extension | RelatedTo | R4B `EpisodeOfCare.extension` maps as RelatedTo to R5 `EpisodeOfCare.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| EpisodeOfCare.id | EpisodeOfCare.id | Equivalent | R4B `EpisodeOfCare.id` maps as Equivalent to R5 `EpisodeOfCare.id` |
| EpisodeOfCare.identifier | EpisodeOfCare.identifier | Equivalent | R4B `EpisodeOfCare.identifier` maps as Equivalent to R5 `EpisodeOfCare.identifier` |
| EpisodeOfCare.implicitRules | EpisodeOfCare.implicitRules | Equivalent | R4B `EpisodeOfCare.implicitRules` maps as Equivalent to R5 `EpisodeOfCare.implicitRules` |
| EpisodeOfCare.language | EpisodeOfCare.language | RelatedTo | R4B `EpisodeOfCare.language` maps as RelatedTo to R5 `EpisodeOfCare.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| EpisodeOfCare.managingOrganization | EpisodeOfCare.managingOrganization | Equivalent | R4B `EpisodeOfCare.managingOrganization` maps as Equivalent to R5 `EpisodeOfCare.managingOrganization` |
| EpisodeOfCare.meta | EpisodeOfCare.meta | Equivalent | R4B `EpisodeOfCare.meta` maps as Equivalent to R5 `EpisodeOfCare.meta` |
| EpisodeOfCare.modifierExtension | EpisodeOfCare.modifierExtension | RelatedTo | R4B `EpisodeOfCare.modifierExtension` maps as RelatedTo to R5 `EpisodeOfCare.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| EpisodeOfCare.patient | EpisodeOfCare.patient | Equivalent | R4B `EpisodeOfCare.patient` maps as Equivalent to R5 `EpisodeOfCare.patient` |
| EpisodeOfCare.period | EpisodeOfCare.period | Equivalent | R4B `EpisodeOfCare.period` maps as Equivalent to R5 `EpisodeOfCare.period` |
| EpisodeOfCare.referralRequest | EpisodeOfCare.referralRequest | Equivalent | R4B `EpisodeOfCare.referralRequest` maps as Equivalent to R5 `EpisodeOfCare.referralRequest` |
| EpisodeOfCare.status | EpisodeOfCare.status | Equivalent | R4B `EpisodeOfCare.status` maps as Equivalent to R5 `EpisodeOfCare.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/episode-of-care-status|4.3.0 and http://hl7.org/fhir/ValueSet/episode-of-care-status|5.0.0 (Equivalent) |
| EpisodeOfCare.statusHistory | EpisodeOfCare.statusHistory | Equivalent | R4B `EpisodeOfCare.statusHistory` maps as Equivalent to R5 `EpisodeOfCare.statusHistory` |
| EpisodeOfCare.statusHistory.extension | EpisodeOfCare.statusHistory.extension | RelatedTo | R4B `EpisodeOfCare.statusHistory.extension` maps as RelatedTo to R5 `EpisodeOfCare.statusHistory.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| EpisodeOfCare.statusHistory.id | EpisodeOfCare.statusHistory.id | Equivalent | R4B `EpisodeOfCare.statusHistory.id` maps as Equivalent to R5 `EpisodeOfCare.statusHistory.id` |
| EpisodeOfCare.statusHistory.modifierExtension | EpisodeOfCare.statusHistory.modifierExtension | RelatedTo | R4B `EpisodeOfCare.statusHistory.modifierExtension` maps as RelatedTo to R5 `EpisodeOfCare.statusHistory.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| EpisodeOfCare.statusHistory.period | EpisodeOfCare.statusHistory.period | Equivalent | R4B `EpisodeOfCare.statusHistory.period` maps as Equivalent to R5 `EpisodeOfCare.statusHistory.period` |
| EpisodeOfCare.statusHistory.status | EpisodeOfCare.statusHistory.status | Equivalent | R4B `EpisodeOfCare.statusHistory.status` maps as Equivalent to R5 `EpisodeOfCare.statusHistory.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/episode-of-care-status|4.3.0 and http://hl7.org/fhir/ValueSet/episode-of-care-status|5.0.0 (Equivalent) |
| EpisodeOfCare.team | - | DoesNotExistInTarget | R4B `EpisodeOfCare.team` does not appear in the target and has no mapping for `EpisodeOfCare`. |
| EpisodeOfCare.text | EpisodeOfCare.text | Equivalent | R4B `EpisodeOfCare.text` maps as Equivalent to R5 `EpisodeOfCare.text` |
| EpisodeOfCare.type | EpisodeOfCare.type | Equivalent | R4B `EpisodeOfCare.type` maps as Equivalent to R5 `EpisodeOfCare.type` |

