Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | PractitionerRole |  | A specific set of Roles/Locations/specialties/services that a practitioner may perform, or has performed at an organization during a period of time. | 23 | 15 |
| Target | PractitionerRole |  | A specific set of Roles/Locations/specialties/services that a practitioner may perform at an organization for a period of time. | 35 | 21 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 4 |
Equivalent | 16 |
SourceIsBroaderThanTarget | 2 |
SourceIsNarrowerThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| PractitionerRole | PractitionerRole | Equivalent | R5 `PractitionerRole` maps as Equivalent to R4 `PractitionerRole` |
| PractitionerRole.active | PractitionerRole.active | Equivalent | R5 `PractitionerRole.active` maps as Equivalent to R4 `PractitionerRole.active` |
| PractitionerRole.availability | - | DoesNotExistInTarget | R5 `PractitionerRole.availability` does not appear in the target and has no mapping for `PractitionerRole`. |
| PractitionerRole.characteristic | - | DoesNotExistInTarget | R5 `PractitionerRole.characteristic` does not appear in the target and has no mapping for `PractitionerRole`. |
| PractitionerRole.code | PractitionerRole.code | Equivalent | R5 `PractitionerRole.code` maps as Equivalent to R4 `PractitionerRole.code` |
| PractitionerRole.communication | - | DoesNotExistInTarget | R5 `PractitionerRole.communication` does not appear in the target and has no mapping for `PractitionerRole`. |
| PractitionerRole.contact | - | DoesNotExistInTarget | R5 `PractitionerRole.contact` does not appear in the target and has no mapping for `PractitionerRole`. |
| PractitionerRole.contained | PractitionerRole.contained | Equivalent | R5 `PractitionerRole.contained` maps as Equivalent to R4 `PractitionerRole.contained` |
| PractitionerRole.endpoint | PractitionerRole.endpoint | Equivalent | R5 `PractitionerRole.endpoint` maps as Equivalent to R4 `PractitionerRole.endpoint` |
| PractitionerRole.extension | PractitionerRole.extension | SourceIsBroaderThanTarget | R5 `PractitionerRole.extension` maps as SourceIsBroaderThanTarget to R4 `PractitionerRole.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| PractitionerRole.healthcareService | PractitionerRole.healthcareService | Equivalent | R5 `PractitionerRole.healthcareService` maps as Equivalent to R4 `PractitionerRole.healthcareService` |
| PractitionerRole.id | PractitionerRole.id | Equivalent | R5 `PractitionerRole.id` maps as Equivalent to R4 `PractitionerRole.id` |
| PractitionerRole.identifier | PractitionerRole.identifier | Equivalent | R5 `PractitionerRole.identifier` maps as Equivalent to R4 `PractitionerRole.identifier` |
| PractitionerRole.implicitRules | PractitionerRole.implicitRules | Equivalent | R5 `PractitionerRole.implicitRules` maps as Equivalent to R4 `PractitionerRole.implicitRules` |
| PractitionerRole.language | PractitionerRole.language | SourceIsNarrowerThanTarget | R5 `PractitionerRole.language` maps as SourceIsNarrowerThanTarget to R4 `PractitionerRole.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| PractitionerRole.location | PractitionerRole.location | Equivalent | R5 `PractitionerRole.location` maps as Equivalent to R4 `PractitionerRole.location` |
| PractitionerRole.meta | PractitionerRole.meta | Equivalent | R5 `PractitionerRole.meta` maps as Equivalent to R4 `PractitionerRole.meta` |
| PractitionerRole.modifierExtension | PractitionerRole.modifierExtension | SourceIsBroaderThanTarget | R5 `PractitionerRole.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `PractitionerRole.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| PractitionerRole.organization | PractitionerRole.organization | Equivalent | R5 `PractitionerRole.organization` maps as Equivalent to R4 `PractitionerRole.organization` |
| PractitionerRole.period | PractitionerRole.period | Equivalent | R5 `PractitionerRole.period` maps as Equivalent to R4 `PractitionerRole.period` |
| PractitionerRole.practitioner | PractitionerRole.practitioner | Equivalent | R5 `PractitionerRole.practitioner` maps as Equivalent to R4 `PractitionerRole.practitioner` |
| PractitionerRole.specialty | PractitionerRole.specialty | Equivalent | R5 `PractitionerRole.specialty` maps as Equivalent to R4 `PractitionerRole.specialty` |
| PractitionerRole.text | PractitionerRole.text | Equivalent | R5 `PractitionerRole.text` maps as Equivalent to R4 `PractitionerRole.text` |

