Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | PractitionerRole |  | A specific set of Roles/Locations/specialties/services that a practitioner may perform, or has performed at an organization during a period of time. | 23 | 15 |
| Target | PractitionerRole |  | A specific set of Roles/Locations/specialties/services that a practitioner may perform at an organization for a period of time. | 35 | 21 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 4 |
Equivalent | 4 |
RelatedTo | 15 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| PractitionerRole | PractitionerRole | Equivalent | R5 `PractitionerRole` maps as Equivalent to R4B `PractitionerRole` |
| PractitionerRole.active | PractitionerRole.active | Equivalent | R5 `PractitionerRole.active` maps as Equivalent to R4B `PractitionerRole.active` |
| PractitionerRole.availability | - | DoesNotExistInTarget | R5 `PractitionerRole.availability` does not appear in the target and has no mapping for `PractitionerRole`. |
| PractitionerRole.characteristic | - | DoesNotExistInTarget | R5 `PractitionerRole.characteristic` does not appear in the target and has no mapping for `PractitionerRole`. |
| PractitionerRole.code | PractitionerRole.code | Equivalent | R5 `PractitionerRole.code` maps as Equivalent to R4B `PractitionerRole.code` |
| PractitionerRole.communication | - | DoesNotExistInTarget | R5 `PractitionerRole.communication` does not appear in the target and has no mapping for `PractitionerRole`. |
| PractitionerRole.contact | - | DoesNotExistInTarget | R5 `PractitionerRole.contact` does not appear in the target and has no mapping for `PractitionerRole`. |
| PractitionerRole.contained | PractitionerRole.contained | Equivalent | R5 `PractitionerRole.contained` maps as Equivalent to R4B `PractitionerRole.contained` |
| PractitionerRole.endpoint | PractitionerRole.endpoint | Equivalent | R5 `PractitionerRole.endpoint` maps as Equivalent to R4B `PractitionerRole.endpoint` |
| PractitionerRole.extension | PractitionerRole.extension | SourceIsBroaderThanTarget | R5 `PractitionerRole.extension` maps as SourceIsBroaderThanTarget to R4B `PractitionerRole.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| PractitionerRole.healthcareService | PractitionerRole.healthcareService | Equivalent | R5 `PractitionerRole.healthcareService` maps as Equivalent to R4B `PractitionerRole.healthcareService` |
| PractitionerRole.id | PractitionerRole.id | Equivalent | R5 `PractitionerRole.id` maps as Equivalent to R4B `PractitionerRole.id` |
| PractitionerRole.identifier | PractitionerRole.identifier | Equivalent | R5 `PractitionerRole.identifier` maps as Equivalent to R4B `PractitionerRole.identifier` |
| PractitionerRole.implicitRules | PractitionerRole.implicitRules | Equivalent | R5 `PractitionerRole.implicitRules` maps as Equivalent to R4B `PractitionerRole.implicitRules` |
| PractitionerRole.language | PractitionerRole.language | RelatedTo | R5 `PractitionerRole.language` maps as RelatedTo to R4B `PractitionerRole.language` - language changed the binding strength from Required to Preferred |
| PractitionerRole.location | PractitionerRole.location | Equivalent | R5 `PractitionerRole.location` maps as Equivalent to R4B `PractitionerRole.location` |
| PractitionerRole.meta | PractitionerRole.meta | Equivalent | R5 `PractitionerRole.meta` maps as Equivalent to R4B `PractitionerRole.meta` |
| PractitionerRole.modifierExtension | PractitionerRole.modifierExtension | SourceIsBroaderThanTarget | R5 `PractitionerRole.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `PractitionerRole.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| PractitionerRole.organization | PractitionerRole.organization | Equivalent | R5 `PractitionerRole.organization` maps as Equivalent to R4B `PractitionerRole.organization` |
| PractitionerRole.period | PractitionerRole.period | Equivalent | R5 `PractitionerRole.period` maps as Equivalent to R4B `PractitionerRole.period` |
| PractitionerRole.practitioner | PractitionerRole.practitioner | Equivalent | R5 `PractitionerRole.practitioner` maps as Equivalent to R4B `PractitionerRole.practitioner` |
| PractitionerRole.specialty | PractitionerRole.specialty | Equivalent | R5 `PractitionerRole.specialty` maps as Equivalent to R4B `PractitionerRole.specialty` |
| PractitionerRole.text | PractitionerRole.text | Equivalent | R5 `PractitionerRole.text` maps as Equivalent to R4B `PractitionerRole.text` |

