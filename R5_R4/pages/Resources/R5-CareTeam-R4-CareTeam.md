Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | CareTeam |  | The Care Team includes all the people and organizations who plan to participate in the coordination and delivery of care. | 27 | 16 |
| Target | CareTeam |  | The Care Team includes all the people and organizations who plan to participate in the coordination and delivery of care for a patient. | 29 | 18 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 2 |
Equivalent | 4 |
RelatedTo | 21 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| CareTeam | CareTeam | Equivalent | R5 `CareTeam` maps as Equivalent to R4 `CareTeam` |
| CareTeam.category | CareTeam.category | Equivalent | R5 `CareTeam.category` maps as Equivalent to R4 `CareTeam.category` |
| CareTeam.contained | CareTeam.contained | Equivalent | R5 `CareTeam.contained` maps as Equivalent to R4 `CareTeam.contained` |
| CareTeam.extension | CareTeam.extension | SourceIsBroaderThanTarget | R5 `CareTeam.extension` maps as SourceIsBroaderThanTarget to R4 `CareTeam.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| CareTeam.id | CareTeam.id | Equivalent | R5 `CareTeam.id` maps as Equivalent to R4 `CareTeam.id` |
| CareTeam.identifier | CareTeam.identifier | Equivalent | R5 `CareTeam.identifier` maps as Equivalent to R4 `CareTeam.identifier` |
| CareTeam.implicitRules | CareTeam.implicitRules | Equivalent | R5 `CareTeam.implicitRules` maps as Equivalent to R4 `CareTeam.implicitRules` |
| CareTeam.language | CareTeam.language | RelatedTo | R5 `CareTeam.language` maps as RelatedTo to R4 `CareTeam.language` - language changed the binding strength from Required to Preferred |
| CareTeam.managingOrganization | CareTeam.managingOrganization | Equivalent | R5 `CareTeam.managingOrganization` maps as Equivalent to R4 `CareTeam.managingOrganization` |
| CareTeam.meta | CareTeam.meta | Equivalent | R5 `CareTeam.meta` maps as Equivalent to R4 `CareTeam.meta` |
| CareTeam.modifierExtension | CareTeam.modifierExtension | SourceIsBroaderThanTarget | R5 `CareTeam.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `CareTeam.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| CareTeam.name | CareTeam.name | Equivalent | R5 `CareTeam.name` maps as Equivalent to R4 `CareTeam.name` |
| CareTeam.note | CareTeam.note | SourceIsBroaderThanTarget | R5 `CareTeam.note` maps as SourceIsBroaderThanTarget to R4 `CareTeam.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4 `note` |
| CareTeam.participant | CareTeam.participant | Equivalent | R5 `CareTeam.participant` maps as Equivalent to R4 `CareTeam.participant` |
| CareTeam.participant.coverage[x] | - | DoesNotExistInTarget | R5 `CareTeam.participant.coverage[x]` does not appear in the target and has no mapping for `CareTeam`. |
| CareTeam.participant.extension | CareTeam.participant.extension | SourceIsBroaderThanTarget | R5 `CareTeam.participant.extension` maps as SourceIsBroaderThanTarget to R4 `CareTeam.participant.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| CareTeam.participant.id | CareTeam.participant.id | Equivalent | R5 `CareTeam.participant.id` maps as Equivalent to R4 `CareTeam.participant.id` |
| CareTeam.participant.member | CareTeam.participant.member | Equivalent | R5 `CareTeam.participant.member` maps as Equivalent to R4 `CareTeam.participant.member` |
| CareTeam.participant.modifierExtension | CareTeam.participant.modifierExtension | SourceIsBroaderThanTarget | R5 `CareTeam.participant.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `CareTeam.participant.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| CareTeam.participant.onBehalfOf | CareTeam.participant.onBehalfOf | Equivalent | R5 `CareTeam.participant.onBehalfOf` maps as Equivalent to R4 `CareTeam.participant.onBehalfOf` |
| CareTeam.participant.role | CareTeam.participant.role | RelatedTo | R5 `CareTeam.participant.role` maps as RelatedTo to R4 `CareTeam.participant.role` - role changed from scalar to array (max cardinality from 1 to *) |
| CareTeam.period | CareTeam.period | Equivalent | R5 `CareTeam.period` maps as Equivalent to R4 `CareTeam.period` |
| CareTeam.reason | - | DoesNotExistInTarget | R5 `CareTeam.reason` does not appear in the target and has no mapping for `CareTeam`. |
| CareTeam.status | CareTeam.status | Equivalent | R5 `CareTeam.status` maps as Equivalent to R4 `CareTeam.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/care-team-status|5.0.0 and http://hl7.org/fhir/ValueSet/care-team-status|4.0.1 (Equivalent) |
| CareTeam.subject | CareTeam.subject | Equivalent | R5 `CareTeam.subject` maps as Equivalent to R4 `CareTeam.subject` |
| CareTeam.telecom | CareTeam.telecom | Equivalent | R5 `CareTeam.telecom` maps as Equivalent to R4 `CareTeam.telecom` |
| CareTeam.text | CareTeam.text | Equivalent | R5 `CareTeam.text` maps as Equivalent to R4 `CareTeam.text` |

