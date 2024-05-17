Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | CareTeam |  | The Care Team includes all the people and organizations who plan to participate in the coordination and delivery of care for a patient. | 29 | 18 |
| Target | CareTeam |  | The Care Team includes all the people and organizations who plan to participate in the coordination and delivery of care. | 27 | 16 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 4 |
Equivalent | 4 |
RelatedTo | 21 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| CareTeam | CareTeam | Equivalent | R4B `CareTeam` maps as Equivalent to R5 `CareTeam` |
| CareTeam.category | CareTeam.category | Equivalent | R4B `CareTeam.category` maps as Equivalent to R5 `CareTeam.category` |
| CareTeam.contained | CareTeam.contained | Equivalent | R4B `CareTeam.contained` maps as Equivalent to R5 `CareTeam.contained` |
| CareTeam.encounter | - | DoesNotExistInTarget | R4B `CareTeam.encounter` does not appear in the target and has no mapping for `CareTeam`. |
| CareTeam.extension | CareTeam.extension | RelatedTo | R4B `CareTeam.extension` maps as RelatedTo to R5 `CareTeam.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| CareTeam.id | CareTeam.id | Equivalent | R4B `CareTeam.id` maps as Equivalent to R5 `CareTeam.id` |
| CareTeam.identifier | CareTeam.identifier | Equivalent | R4B `CareTeam.identifier` maps as Equivalent to R5 `CareTeam.identifier` |
| CareTeam.implicitRules | CareTeam.implicitRules | Equivalent | R4B `CareTeam.implicitRules` maps as Equivalent to R5 `CareTeam.implicitRules` |
| CareTeam.language | CareTeam.language | RelatedTo | R4B `CareTeam.language` maps as RelatedTo to R5 `CareTeam.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| CareTeam.managingOrganization | CareTeam.managingOrganization | Equivalent | R4B `CareTeam.managingOrganization` maps as Equivalent to R5 `CareTeam.managingOrganization` |
| CareTeam.meta | CareTeam.meta | Equivalent | R4B `CareTeam.meta` maps as Equivalent to R5 `CareTeam.meta` |
| CareTeam.modifierExtension | CareTeam.modifierExtension | RelatedTo | R4B `CareTeam.modifierExtension` maps as RelatedTo to R5 `CareTeam.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| CareTeam.name | CareTeam.name | Equivalent | R4B `CareTeam.name` maps as Equivalent to R5 `CareTeam.name` |
| CareTeam.note | CareTeam.note | SourceIsNarrowerThanTarget | R4B `CareTeam.note` maps as SourceIsNarrowerThanTarget to R5 `CareTeam.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| CareTeam.participant | CareTeam.participant | Equivalent | R4B `CareTeam.participant` maps as Equivalent to R5 `CareTeam.participant` |
| CareTeam.participant.extension | CareTeam.participant.extension | RelatedTo | R4B `CareTeam.participant.extension` maps as RelatedTo to R5 `CareTeam.participant.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| CareTeam.participant.id | CareTeam.participant.id | Equivalent | R4B `CareTeam.participant.id` maps as Equivalent to R5 `CareTeam.participant.id` |
| CareTeam.participant.member | CareTeam.participant.member | Equivalent | R4B `CareTeam.participant.member` maps as Equivalent to R5 `CareTeam.participant.member` |
| CareTeam.participant.modifierExtension | CareTeam.participant.modifierExtension | RelatedTo | R4B `CareTeam.participant.modifierExtension` maps as RelatedTo to R5 `CareTeam.participant.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| CareTeam.participant.onBehalfOf | CareTeam.participant.onBehalfOf | Equivalent | R4B `CareTeam.participant.onBehalfOf` maps as Equivalent to R5 `CareTeam.participant.onBehalfOf` |
| CareTeam.participant.period | - | DoesNotExistInTarget | R4B `CareTeam.participant.period` does not appear in the target and has no mapping for `CareTeam`. |
| CareTeam.participant.role | CareTeam.participant.role | RelatedTo | R4B `CareTeam.participant.role` maps as RelatedTo to R5 `CareTeam.participant.role` - role changed from array to scalar (max cardinality from * to 1) |
| CareTeam.period | CareTeam.period | Equivalent | R4B `CareTeam.period` maps as Equivalent to R5 `CareTeam.period` |
| CareTeam.reasonCode | - | DoesNotExistInTarget | R4B `CareTeam.reasonCode` does not appear in the target and has no mapping for `CareTeam`. |
| CareTeam.reasonReference | - | DoesNotExistInTarget | R4B `CareTeam.reasonReference` does not appear in the target and has no mapping for `CareTeam`. |
| CareTeam.status | CareTeam.status | Equivalent | R4B `CareTeam.status` maps as Equivalent to R5 `CareTeam.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/care-team-status|4.3.0 and http://hl7.org/fhir/ValueSet/care-team-status|5.0.0 (Equivalent) |
| CareTeam.subject | CareTeam.subject | Equivalent | R4B `CareTeam.subject` maps as Equivalent to R5 `CareTeam.subject` |
| CareTeam.telecom | CareTeam.telecom | Equivalent | R4B `CareTeam.telecom` maps as Equivalent to R5 `CareTeam.telecom` |
| CareTeam.text | CareTeam.text | Equivalent | R4B `CareTeam.text` maps as Equivalent to R5 `CareTeam.text` |

