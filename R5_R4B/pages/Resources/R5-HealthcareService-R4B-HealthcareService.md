Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | HealthcareService |  | The details of a healthcare service available at a location or in a catalog.  In the case where there is a hierarchy of services (for example, Lab -> Pathology -> Wound Cultures), this can be represented using a set of linked HealthcareServices. | 37 | 26 |
| Target | HealthcareService |  | The details of a healthcare service available at a location. | 50 | 33 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 3 |
Equivalent | 4 |
RelatedTo | 30 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| HealthcareService | HealthcareService | Equivalent | R5 `HealthcareService` maps as Equivalent to R4B `HealthcareService` |
| HealthcareService.active | HealthcareService.active | Equivalent | R5 `HealthcareService.active` maps as Equivalent to R4B `HealthcareService.active` |
| HealthcareService.appointmentRequired | HealthcareService.appointmentRequired | Equivalent | R5 `HealthcareService.appointmentRequired` maps as Equivalent to R4B `HealthcareService.appointmentRequired` |
| HealthcareService.availability | - | DoesNotExistInTarget | R5 `HealthcareService.availability` does not appear in the target and has no mapping for `HealthcareService`. |
| HealthcareService.category | HealthcareService.category | Equivalent | R5 `HealthcareService.category` maps as Equivalent to R4B `HealthcareService.category` |
| HealthcareService.characteristic | HealthcareService.characteristic | Equivalent | R5 `HealthcareService.characteristic` maps as Equivalent to R4B `HealthcareService.characteristic` |
| HealthcareService.comment | HealthcareService.comment | SourceIsBroaderThanTarget | R5 `HealthcareService.comment` maps as SourceIsBroaderThanTarget to R4B `HealthcareService.comment` - comment has change due to type change: R5 comment markdown has no equivalent or mapped type in R4B comment |
| HealthcareService.communication | HealthcareService.communication | RelatedTo | R5 `HealthcareService.communication` maps as RelatedTo to R4B `HealthcareService.communication` - communication changed the binding strength from Required to Preferred |
| HealthcareService.contact | - | DoesNotExistInTarget | R5 `HealthcareService.contact` does not appear in the target and has no mapping for `HealthcareService`. |
| HealthcareService.contained | HealthcareService.contained | Equivalent | R5 `HealthcareService.contained` maps as Equivalent to R4B `HealthcareService.contained` |
| HealthcareService.coverageArea | HealthcareService.coverageArea | Equivalent | R5 `HealthcareService.coverageArea` maps as Equivalent to R4B `HealthcareService.coverageArea` |
| HealthcareService.eligibility | HealthcareService.eligibility | Equivalent | R5 `HealthcareService.eligibility` maps as Equivalent to R4B `HealthcareService.eligibility` |
| HealthcareService.eligibility.code | HealthcareService.eligibility.code | Equivalent | R5 `HealthcareService.eligibility.code` maps as Equivalent to R4B `HealthcareService.eligibility.code` |
| HealthcareService.eligibility.comment | HealthcareService.eligibility.comment | Equivalent | R5 `HealthcareService.eligibility.comment` maps as Equivalent to R4B `HealthcareService.eligibility.comment` |
| HealthcareService.eligibility.extension | HealthcareService.eligibility.extension | SourceIsBroaderThanTarget | R5 `HealthcareService.eligibility.extension` maps as SourceIsBroaderThanTarget to R4B `HealthcareService.eligibility.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| HealthcareService.eligibility.id | HealthcareService.eligibility.id | Equivalent | R5 `HealthcareService.eligibility.id` maps as Equivalent to R4B `HealthcareService.eligibility.id` |
| HealthcareService.eligibility.modifierExtension | HealthcareService.eligibility.modifierExtension | SourceIsBroaderThanTarget | R5 `HealthcareService.eligibility.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `HealthcareService.eligibility.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| HealthcareService.endpoint | HealthcareService.endpoint | Equivalent | R5 `HealthcareService.endpoint` maps as Equivalent to R4B `HealthcareService.endpoint` |
| HealthcareService.extension | HealthcareService.extension | SourceIsBroaderThanTarget | R5 `HealthcareService.extension` maps as SourceIsBroaderThanTarget to R4B `HealthcareService.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| HealthcareService.extraDetails | HealthcareService.extraDetails | Equivalent | R5 `HealthcareService.extraDetails` maps as Equivalent to R4B `HealthcareService.extraDetails` |
| HealthcareService.id | HealthcareService.id | Equivalent | R5 `HealthcareService.id` maps as Equivalent to R4B `HealthcareService.id` |
| HealthcareService.identifier | HealthcareService.identifier | Equivalent | R5 `HealthcareService.identifier` maps as Equivalent to R4B `HealthcareService.identifier` |
| HealthcareService.implicitRules | HealthcareService.implicitRules | Equivalent | R5 `HealthcareService.implicitRules` maps as Equivalent to R4B `HealthcareService.implicitRules` |
| HealthcareService.language | HealthcareService.language | RelatedTo | R5 `HealthcareService.language` maps as RelatedTo to R4B `HealthcareService.language` - language changed the binding strength from Required to Preferred |
| HealthcareService.location | HealthcareService.location | Equivalent | R5 `HealthcareService.location` maps as Equivalent to R4B `HealthcareService.location` |
| HealthcareService.meta | HealthcareService.meta | Equivalent | R5 `HealthcareService.meta` maps as Equivalent to R4B `HealthcareService.meta` |
| HealthcareService.modifierExtension | HealthcareService.modifierExtension | SourceIsBroaderThanTarget | R5 `HealthcareService.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `HealthcareService.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| HealthcareService.name | HealthcareService.name | Equivalent | R5 `HealthcareService.name` maps as Equivalent to R4B `HealthcareService.name` |
| HealthcareService.offeredIn | - | DoesNotExistInTarget | R5 `HealthcareService.offeredIn` does not appear in the target and has no mapping for `HealthcareService`. |
| HealthcareService.photo | HealthcareService.photo | RelatedTo | R5 `HealthcareService.photo` maps as RelatedTo to R4B `HealthcareService.photo` - photo has change due to type change: R5 `photo` `Attachment` maps as RelatedTo for R4B `photo` |
| HealthcareService.program | HealthcareService.program | Equivalent | R5 `HealthcareService.program` maps as Equivalent to R4B `HealthcareService.program` |
| HealthcareService.providedBy | HealthcareService.providedBy | Equivalent | R5 `HealthcareService.providedBy` maps as Equivalent to R4B `HealthcareService.providedBy` |
| HealthcareService.referralMethod | HealthcareService.referralMethod | Equivalent | R5 `HealthcareService.referralMethod` maps as Equivalent to R4B `HealthcareService.referralMethod` |
| HealthcareService.serviceProvisionCode | HealthcareService.serviceProvisionCode | Equivalent | R5 `HealthcareService.serviceProvisionCode` maps as Equivalent to R4B `HealthcareService.serviceProvisionCode` |
| HealthcareService.specialty | HealthcareService.specialty | Equivalent | R5 `HealthcareService.specialty` maps as Equivalent to R4B `HealthcareService.specialty` |
| HealthcareService.text | HealthcareService.text | Equivalent | R5 `HealthcareService.text` maps as Equivalent to R4B `HealthcareService.text` |
| HealthcareService.type | HealthcareService.type | Equivalent | R5 `HealthcareService.type` maps as Equivalent to R4B `HealthcareService.type` |

