Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Schedule |  | A container for slots of time that may be available for booking appointments. | 18 | 10 |
| Target | Schedule |  | A container for slots of time that may be available for booking appointments. | 17 | 9 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 1 |
Equivalent | 4 |
RelatedTo | 13 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Schedule | Schedule | Equivalent | R5 `Schedule` maps as Equivalent to R4 `Schedule` |
| Schedule.active | Schedule.active | Equivalent | R5 `Schedule.active` maps as Equivalent to R4 `Schedule.active` |
| Schedule.actor | Schedule.actor | SourceIsBroaderThanTarget | R5 `Schedule.actor` maps as SourceIsBroaderThanTarget to R4 `Schedule.actor` - actor has change due to type change: R5 `actor` `Reference` maps as SourceIsBroaderThanTarget for R4 `actor` |
| Schedule.comment | Schedule.comment | SourceIsBroaderThanTarget | R5 `Schedule.comment` maps as SourceIsBroaderThanTarget to R4 `Schedule.comment` - comment has change due to type change: R5 comment markdown has no equivalent or mapped type in R4 comment |
| Schedule.contained | Schedule.contained | Equivalent | R5 `Schedule.contained` maps as Equivalent to R4 `Schedule.contained` |
| Schedule.extension | Schedule.extension | SourceIsBroaderThanTarget | R5 `Schedule.extension` maps as SourceIsBroaderThanTarget to R4 `Schedule.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Schedule.id | Schedule.id | Equivalent | R5 `Schedule.id` maps as Equivalent to R4 `Schedule.id` |
| Schedule.identifier | Schedule.identifier | Equivalent | R5 `Schedule.identifier` maps as Equivalent to R4 `Schedule.identifier` |
| Schedule.implicitRules | Schedule.implicitRules | Equivalent | R5 `Schedule.implicitRules` maps as Equivalent to R4 `Schedule.implicitRules` |
| Schedule.language | Schedule.language | RelatedTo | R5 `Schedule.language` maps as RelatedTo to R4 `Schedule.language` - language changed the binding strength from Required to Preferred |
| Schedule.meta | Schedule.meta | Equivalent | R5 `Schedule.meta` maps as Equivalent to R4 `Schedule.meta` |
| Schedule.modifierExtension | Schedule.modifierExtension | SourceIsBroaderThanTarget | R5 `Schedule.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Schedule.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Schedule.name | - | DoesNotExistInTarget | R5 `Schedule.name` does not appear in the target and has no mapping for `Schedule`. |
| Schedule.planningHorizon | Schedule.planningHorizon | Equivalent | R5 `Schedule.planningHorizon` maps as Equivalent to R4 `Schedule.planningHorizon` |
| Schedule.serviceCategory | Schedule.serviceCategory | Equivalent | R5 `Schedule.serviceCategory` maps as Equivalent to R4 `Schedule.serviceCategory` |
| Schedule.serviceType | Schedule.serviceType | SourceIsBroaderThanTarget | R5 `Schedule.serviceType` maps as SourceIsBroaderThanTarget to R4 `Schedule.serviceType` - serviceType has change due to type change: R5 serviceType CodeableReference has no equivalent or mapped type in R4 serviceType |
| Schedule.specialty | Schedule.specialty | Equivalent | R5 `Schedule.specialty` maps as Equivalent to R4 `Schedule.specialty` |
| Schedule.text | Schedule.text | Equivalent | R5 `Schedule.text` maps as Equivalent to R4 `Schedule.text` |

