Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Schedule |  | A container for slots of time that may be available for booking appointments. | 17 | 9 |
| Target | Schedule |  | A container for slots of time that may be available for booking appointments. | 18 | 10 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 13 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Schedule | Schedule | Equivalent | R4B `Schedule` maps as Equivalent to R5 `Schedule` |
| Schedule.active | Schedule.active | Equivalent | R4B `Schedule.active` maps as Equivalent to R5 `Schedule.active` |
| Schedule.actor | Schedule.actor | SourceIsNarrowerThanTarget | R4B `Schedule.actor` maps as SourceIsNarrowerThanTarget to R5 `Schedule.actor` - actor has change due to type change: R4B `actor` `Reference` maps as SourceIsNarrowerThanTarget for R5 `actor` |
| Schedule.comment | Schedule.comment | SourceIsBroaderThanTarget | R4B `Schedule.comment` maps as SourceIsBroaderThanTarget to R5 `Schedule.comment` - comment has change due to type change: R4B comment string has no equivalent or mapped type in R5 comment |
| Schedule.contained | Schedule.contained | Equivalent | R4B `Schedule.contained` maps as Equivalent to R5 `Schedule.contained` |
| Schedule.extension | Schedule.extension | RelatedTo | R4B `Schedule.extension` maps as RelatedTo to R5 `Schedule.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Schedule.id | Schedule.id | Equivalent | R4B `Schedule.id` maps as Equivalent to R5 `Schedule.id` |
| Schedule.identifier | Schedule.identifier | Equivalent | R4B `Schedule.identifier` maps as Equivalent to R5 `Schedule.identifier` |
| Schedule.implicitRules | Schedule.implicitRules | Equivalent | R4B `Schedule.implicitRules` maps as Equivalent to R5 `Schedule.implicitRules` |
| Schedule.language | Schedule.language | RelatedTo | R4B `Schedule.language` maps as RelatedTo to R5 `Schedule.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Schedule.meta | Schedule.meta | Equivalent | R4B `Schedule.meta` maps as Equivalent to R5 `Schedule.meta` |
| Schedule.modifierExtension | Schedule.modifierExtension | RelatedTo | R4B `Schedule.modifierExtension` maps as RelatedTo to R5 `Schedule.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Schedule.planningHorizon | Schedule.planningHorizon | Equivalent | R4B `Schedule.planningHorizon` maps as Equivalent to R5 `Schedule.planningHorizon` |
| Schedule.serviceCategory | Schedule.serviceCategory | Equivalent | R4B `Schedule.serviceCategory` maps as Equivalent to R5 `Schedule.serviceCategory` |
| Schedule.serviceType | Schedule.serviceType | SourceIsBroaderThanTarget | R4B `Schedule.serviceType` maps as SourceIsBroaderThanTarget to R5 `Schedule.serviceType` - serviceType has change due to type change: R4B serviceType CodeableConcept has no equivalent or mapped type in R5 serviceType |
| Schedule.specialty | Schedule.specialty | Equivalent | R4B `Schedule.specialty` maps as Equivalent to R5 `Schedule.specialty` |
| Schedule.text | Schedule.text | Equivalent | R4B `Schedule.text` maps as Equivalent to R5 `Schedule.text` |

