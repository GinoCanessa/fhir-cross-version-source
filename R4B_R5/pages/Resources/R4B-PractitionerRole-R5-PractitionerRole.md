Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | PractitionerRole |  | A specific set of Roles/Locations/specialties/services that a practitioner may perform at an organization for a period of time. | 35 | 21 |
| Target | PractitionerRole |  | A specific set of Roles/Locations/specialties/services that a practitioner may perform, or has performed at an organization during a period of time. | 23 | 15 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 16 |
Equivalent | 4 |
RelatedTo | 15 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| PractitionerRole | PractitionerRole | Equivalent | R4B `PractitionerRole` maps as Equivalent to R5 `PractitionerRole` |
| PractitionerRole.active | PractitionerRole.active | Equivalent | R4B `PractitionerRole.active` maps as Equivalent to R5 `PractitionerRole.active` |
| PractitionerRole.availabilityExceptions | - | DoesNotExistInTarget | R4B `PractitionerRole.availabilityExceptions` does not appear in the target and has no mapping for `PractitionerRole`. |
| PractitionerRole.availableTime | - | DoesNotExistInTarget | R4B `PractitionerRole.availableTime` does not appear in the target and has no mapping for `PractitionerRole`. |
| PractitionerRole.availableTime.allDay | - | DoesNotExistInTarget | R4B `PractitionerRole.availableTime.allDay` does not appear in the target and has no mapping for `PractitionerRole`. |
| PractitionerRole.availableTime.availableEndTime | - | DoesNotExistInTarget | R4B `PractitionerRole.availableTime.availableEndTime` does not appear in the target and has no mapping for `PractitionerRole`. |
| PractitionerRole.availableTime.availableStartTime | - | DoesNotExistInTarget | R4B `PractitionerRole.availableTime.availableStartTime` does not appear in the target and has no mapping for `PractitionerRole`. |
| PractitionerRole.availableTime.daysOfWeek | - | DoesNotExistInTarget | R4B `PractitionerRole.availableTime.daysOfWeek` does not appear in the target and has no mapping for `PractitionerRole`. |
| PractitionerRole.availableTime.extension | - | DoesNotExistInTarget | R4B `PractitionerRole.availableTime.extension` does not appear in the target and has no mapping for `PractitionerRole`. |
| PractitionerRole.availableTime.id | - | DoesNotExistInTarget | R4B `PractitionerRole.availableTime.id` does not appear in the target and has no mapping for `PractitionerRole`. |
| PractitionerRole.availableTime.modifierExtension | - | DoesNotExistInTarget | R4B `PractitionerRole.availableTime.modifierExtension` does not appear in the target and has no mapping for `PractitionerRole`. |
| PractitionerRole.code | PractitionerRole.code | Equivalent | R4B `PractitionerRole.code` maps as Equivalent to R5 `PractitionerRole.code` |
| PractitionerRole.contained | PractitionerRole.contained | Equivalent | R4B `PractitionerRole.contained` maps as Equivalent to R5 `PractitionerRole.contained` |
| PractitionerRole.endpoint | PractitionerRole.endpoint | Equivalent | R4B `PractitionerRole.endpoint` maps as Equivalent to R5 `PractitionerRole.endpoint` |
| PractitionerRole.extension | PractitionerRole.extension | RelatedTo | R4B `PractitionerRole.extension` maps as RelatedTo to R5 `PractitionerRole.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| PractitionerRole.healthcareService | PractitionerRole.healthcareService | Equivalent | R4B `PractitionerRole.healthcareService` maps as Equivalent to R5 `PractitionerRole.healthcareService` |
| PractitionerRole.id | PractitionerRole.id | Equivalent | R4B `PractitionerRole.id` maps as Equivalent to R5 `PractitionerRole.id` |
| PractitionerRole.identifier | PractitionerRole.identifier | Equivalent | R4B `PractitionerRole.identifier` maps as Equivalent to R5 `PractitionerRole.identifier` |
| PractitionerRole.implicitRules | PractitionerRole.implicitRules | Equivalent | R4B `PractitionerRole.implicitRules` maps as Equivalent to R5 `PractitionerRole.implicitRules` |
| PractitionerRole.language | PractitionerRole.language | RelatedTo | R4B `PractitionerRole.language` maps as RelatedTo to R5 `PractitionerRole.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| PractitionerRole.location | PractitionerRole.location | Equivalent | R4B `PractitionerRole.location` maps as Equivalent to R5 `PractitionerRole.location` |
| PractitionerRole.meta | PractitionerRole.meta | Equivalent | R4B `PractitionerRole.meta` maps as Equivalent to R5 `PractitionerRole.meta` |
| PractitionerRole.modifierExtension | PractitionerRole.modifierExtension | RelatedTo | R4B `PractitionerRole.modifierExtension` maps as RelatedTo to R5 `PractitionerRole.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| PractitionerRole.notAvailable | - | DoesNotExistInTarget | R4B `PractitionerRole.notAvailable` does not appear in the target and has no mapping for `PractitionerRole`. |
| PractitionerRole.notAvailable.description | - | DoesNotExistInTarget | R4B `PractitionerRole.notAvailable.description` does not appear in the target and has no mapping for `PractitionerRole`. |
| PractitionerRole.notAvailable.during | - | DoesNotExistInTarget | R4B `PractitionerRole.notAvailable.during` does not appear in the target and has no mapping for `PractitionerRole`. |
| PractitionerRole.notAvailable.extension | - | DoesNotExistInTarget | R4B `PractitionerRole.notAvailable.extension` does not appear in the target and has no mapping for `PractitionerRole`. |
| PractitionerRole.notAvailable.id | - | DoesNotExistInTarget | R4B `PractitionerRole.notAvailable.id` does not appear in the target and has no mapping for `PractitionerRole`. |
| PractitionerRole.notAvailable.modifierExtension | - | DoesNotExistInTarget | R4B `PractitionerRole.notAvailable.modifierExtension` does not appear in the target and has no mapping for `PractitionerRole`. |
| PractitionerRole.organization | PractitionerRole.organization | Equivalent | R4B `PractitionerRole.organization` maps as Equivalent to R5 `PractitionerRole.organization` |
| PractitionerRole.period | PractitionerRole.period | Equivalent | R4B `PractitionerRole.period` maps as Equivalent to R5 `PractitionerRole.period` |
| PractitionerRole.practitioner | PractitionerRole.practitioner | Equivalent | R4B `PractitionerRole.practitioner` maps as Equivalent to R5 `PractitionerRole.practitioner` |
| PractitionerRole.specialty | PractitionerRole.specialty | Equivalent | R4B `PractitionerRole.specialty` maps as Equivalent to R5 `PractitionerRole.specialty` |
| PractitionerRole.telecom | - | DoesNotExistInTarget | R4B `PractitionerRole.telecom` does not appear in the target and has no mapping for `PractitionerRole`. |
| PractitionerRole.text | PractitionerRole.text | Equivalent | R4B `PractitionerRole.text` maps as Equivalent to R5 `PractitionerRole.text` |

