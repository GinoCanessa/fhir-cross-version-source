Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | HealthcareService |  | The details of a healthcare service available at a location. | 50 | 33 |
| Target | HealthcareService |  | The details of a healthcare service available at a location or in a catalog.  In the case where there is a hierarchy of services (for example, Lab -> Pathology -> Wound Cultures), this can be represented using a set of linked HealthcareServices. | 37 | 26 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 16 |
Equivalent | 4 |
RelatedTo | 30 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| HealthcareService | HealthcareService | Equivalent | R4B `HealthcareService` maps as Equivalent to R5 `HealthcareService` |
| HealthcareService.active | HealthcareService.active | Equivalent | R4B `HealthcareService.active` maps as Equivalent to R5 `HealthcareService.active` |
| HealthcareService.appointmentRequired | HealthcareService.appointmentRequired | Equivalent | R4B `HealthcareService.appointmentRequired` maps as Equivalent to R5 `HealthcareService.appointmentRequired` |
| HealthcareService.availabilityExceptions | - | DoesNotExistInTarget | R4B `HealthcareService.availabilityExceptions` does not appear in the target and has no mapping for `HealthcareService`. |
| HealthcareService.availableTime | - | DoesNotExistInTarget | R4B `HealthcareService.availableTime` does not appear in the target and has no mapping for `HealthcareService`. |
| HealthcareService.availableTime.allDay | - | DoesNotExistInTarget | R4B `HealthcareService.availableTime.allDay` does not appear in the target and has no mapping for `HealthcareService`. |
| HealthcareService.availableTime.availableEndTime | - | DoesNotExistInTarget | R4B `HealthcareService.availableTime.availableEndTime` does not appear in the target and has no mapping for `HealthcareService`. |
| HealthcareService.availableTime.availableStartTime | - | DoesNotExistInTarget | R4B `HealthcareService.availableTime.availableStartTime` does not appear in the target and has no mapping for `HealthcareService`. |
| HealthcareService.availableTime.daysOfWeek | - | DoesNotExistInTarget | R4B `HealthcareService.availableTime.daysOfWeek` does not appear in the target and has no mapping for `HealthcareService`. |
| HealthcareService.availableTime.extension | - | DoesNotExistInTarget | R4B `HealthcareService.availableTime.extension` does not appear in the target and has no mapping for `HealthcareService`. |
| HealthcareService.availableTime.id | - | DoesNotExistInTarget | R4B `HealthcareService.availableTime.id` does not appear in the target and has no mapping for `HealthcareService`. |
| HealthcareService.availableTime.modifierExtension | - | DoesNotExistInTarget | R4B `HealthcareService.availableTime.modifierExtension` does not appear in the target and has no mapping for `HealthcareService`. |
| HealthcareService.category | HealthcareService.category | Equivalent | R4B `HealthcareService.category` maps as Equivalent to R5 `HealthcareService.category` |
| HealthcareService.characteristic | HealthcareService.characteristic | Equivalent | R4B `HealthcareService.characteristic` maps as Equivalent to R5 `HealthcareService.characteristic` |
| HealthcareService.comment | HealthcareService.comment | SourceIsBroaderThanTarget | R4B `HealthcareService.comment` maps as SourceIsBroaderThanTarget to R5 `HealthcareService.comment` - comment has change due to type change: R4B comment string has no equivalent or mapped type in R5 comment |
| HealthcareService.communication | HealthcareService.communication | RelatedTo | R4B `HealthcareService.communication` maps as RelatedTo to R5 `HealthcareService.communication` - communication made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| HealthcareService.contained | HealthcareService.contained | Equivalent | R4B `HealthcareService.contained` maps as Equivalent to R5 `HealthcareService.contained` |
| HealthcareService.coverageArea | HealthcareService.coverageArea | Equivalent | R4B `HealthcareService.coverageArea` maps as Equivalent to R5 `HealthcareService.coverageArea` |
| HealthcareService.eligibility | HealthcareService.eligibility | Equivalent | R4B `HealthcareService.eligibility` maps as Equivalent to R5 `HealthcareService.eligibility` |
| HealthcareService.eligibility.code | HealthcareService.eligibility.code | Equivalent | R4B `HealthcareService.eligibility.code` maps as Equivalent to R5 `HealthcareService.eligibility.code` |
| HealthcareService.eligibility.comment | HealthcareService.eligibility.comment | Equivalent | R4B `HealthcareService.eligibility.comment` maps as Equivalent to R5 `HealthcareService.eligibility.comment` |
| HealthcareService.eligibility.extension | HealthcareService.eligibility.extension | RelatedTo | R4B `HealthcareService.eligibility.extension` maps as RelatedTo to R5 `HealthcareService.eligibility.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| HealthcareService.eligibility.id | HealthcareService.eligibility.id | Equivalent | R4B `HealthcareService.eligibility.id` maps as Equivalent to R5 `HealthcareService.eligibility.id` |
| HealthcareService.eligibility.modifierExtension | HealthcareService.eligibility.modifierExtension | RelatedTo | R4B `HealthcareService.eligibility.modifierExtension` maps as RelatedTo to R5 `HealthcareService.eligibility.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| HealthcareService.endpoint | HealthcareService.endpoint | Equivalent | R4B `HealthcareService.endpoint` maps as Equivalent to R5 `HealthcareService.endpoint` |
| HealthcareService.extension | HealthcareService.extension | RelatedTo | R4B `HealthcareService.extension` maps as RelatedTo to R5 `HealthcareService.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| HealthcareService.extraDetails | HealthcareService.extraDetails | Equivalent | R4B `HealthcareService.extraDetails` maps as Equivalent to R5 `HealthcareService.extraDetails` |
| HealthcareService.id | HealthcareService.id | Equivalent | R4B `HealthcareService.id` maps as Equivalent to R5 `HealthcareService.id` |
| HealthcareService.identifier | HealthcareService.identifier | Equivalent | R4B `HealthcareService.identifier` maps as Equivalent to R5 `HealthcareService.identifier` |
| HealthcareService.implicitRules | HealthcareService.implicitRules | Equivalent | R4B `HealthcareService.implicitRules` maps as Equivalent to R5 `HealthcareService.implicitRules` |
| HealthcareService.language | HealthcareService.language | RelatedTo | R4B `HealthcareService.language` maps as RelatedTo to R5 `HealthcareService.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| HealthcareService.location | HealthcareService.location | Equivalent | R4B `HealthcareService.location` maps as Equivalent to R5 `HealthcareService.location` |
| HealthcareService.meta | HealthcareService.meta | Equivalent | R4B `HealthcareService.meta` maps as Equivalent to R5 `HealthcareService.meta` |
| HealthcareService.modifierExtension | HealthcareService.modifierExtension | RelatedTo | R4B `HealthcareService.modifierExtension` maps as RelatedTo to R5 `HealthcareService.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| HealthcareService.name | HealthcareService.name | Equivalent | R4B `HealthcareService.name` maps as Equivalent to R5 `HealthcareService.name` |
| HealthcareService.notAvailable | - | DoesNotExistInTarget | R4B `HealthcareService.notAvailable` does not appear in the target and has no mapping for `HealthcareService`. |
| HealthcareService.notAvailable.description | - | DoesNotExistInTarget | R4B `HealthcareService.notAvailable.description` does not appear in the target and has no mapping for `HealthcareService`. |
| HealthcareService.notAvailable.during | - | DoesNotExistInTarget | R4B `HealthcareService.notAvailable.during` does not appear in the target and has no mapping for `HealthcareService`. |
| HealthcareService.notAvailable.extension | - | DoesNotExistInTarget | R4B `HealthcareService.notAvailable.extension` does not appear in the target and has no mapping for `HealthcareService`. |
| HealthcareService.notAvailable.id | - | DoesNotExistInTarget | R4B `HealthcareService.notAvailable.id` does not appear in the target and has no mapping for `HealthcareService`. |
| HealthcareService.notAvailable.modifierExtension | - | DoesNotExistInTarget | R4B `HealthcareService.notAvailable.modifierExtension` does not appear in the target and has no mapping for `HealthcareService`. |
| HealthcareService.photo | HealthcareService.photo | RelatedTo | R4B `HealthcareService.photo` maps as RelatedTo to R5 `HealthcareService.photo` - photo has change due to type change: R4B `photo` `Attachment` maps as RelatedTo for R5 `photo` |
| HealthcareService.program | HealthcareService.program | Equivalent | R4B `HealthcareService.program` maps as Equivalent to R5 `HealthcareService.program` |
| HealthcareService.providedBy | HealthcareService.providedBy | Equivalent | R4B `HealthcareService.providedBy` maps as Equivalent to R5 `HealthcareService.providedBy` |
| HealthcareService.referralMethod | HealthcareService.referralMethod | Equivalent | R4B `HealthcareService.referralMethod` maps as Equivalent to R5 `HealthcareService.referralMethod` |
| HealthcareService.serviceProvisionCode | HealthcareService.serviceProvisionCode | Equivalent | R4B `HealthcareService.serviceProvisionCode` maps as Equivalent to R5 `HealthcareService.serviceProvisionCode` |
| HealthcareService.specialty | HealthcareService.specialty | Equivalent | R4B `HealthcareService.specialty` maps as Equivalent to R5 `HealthcareService.specialty` |
| HealthcareService.telecom | - | DoesNotExistInTarget | R4B `HealthcareService.telecom` does not appear in the target and has no mapping for `HealthcareService`. |
| HealthcareService.text | HealthcareService.text | Equivalent | R4B `HealthcareService.text` maps as Equivalent to R5 `HealthcareService.text` |
| HealthcareService.type | HealthcareService.type | Equivalent | R4B `HealthcareService.type` maps as Equivalent to R5 `HealthcareService.type` |

