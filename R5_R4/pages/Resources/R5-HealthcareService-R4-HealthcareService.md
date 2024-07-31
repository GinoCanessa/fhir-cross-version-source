Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | HealthcareService |  | The details of a healthcare service available at a location or in a catalog.  In the case where there is a hierarchy of services (for example, Lab -> Pathology -> Wound Cultures), this can be represented using a set of linked HealthcareServices. | 37 | 26 |
| Target | HealthcareService |  | The details of a healthcare service available at a location. | 50 | 33 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 3 |
Equivalent | 26 |
RelatedTo | 1 |
SourceIsBroaderThanTarget | 5 |
SourceIsNarrowerThanTarget | 2 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| HealthcareService | HealthcareService | Equivalent | R5 `HealthcareService` maps as Equivalent to R4 `HealthcareService` |
| HealthcareService.active | HealthcareService.active | Equivalent | R5 `HealthcareService.active` maps as Equivalent to R4 `HealthcareService.active` |
| HealthcareService.appointmentRequired | HealthcareService.appointmentRequired | Equivalent | R5 `HealthcareService.appointmentRequired` maps as Equivalent to R4 `HealthcareService.appointmentRequired` |
| HealthcareService.availability | - | DoesNotExistInTarget | R5 `HealthcareService.availability` does not appear in the target and has no mapping for `HealthcareService`. |
| HealthcareService.category | HealthcareService.category | Equivalent | R5 `HealthcareService.category` maps as Equivalent to R4 `HealthcareService.category` |
| HealthcareService.characteristic | HealthcareService.characteristic | Equivalent | R5 `HealthcareService.characteristic` maps as Equivalent to R4 `HealthcareService.characteristic` |
| HealthcareService.comment | HealthcareService.comment | SourceIsBroaderThanTarget | R5 `HealthcareService.comment` maps as SourceIsBroaderThanTarget to R4 `HealthcareService.comment` - comment has change due to type change: R5 comment markdown has no equivalent or mapped type in R4 comment |
| HealthcareService.communication | HealthcareService.communication | SourceIsNarrowerThanTarget | R5 `HealthcareService.communication` maps as SourceIsNarrowerThanTarget to R4 `HealthcareService.communication` - communication changed the binding strength from Required to Preferred; communication has change due to type change: R5 `communication` `CodeableConcept` maps as SourceIsNarrowerThanTarget for R4 `communication` |
| HealthcareService.contact | - | DoesNotExistInTarget | R5 `HealthcareService.contact` does not appear in the target and has no mapping for `HealthcareService`. |
| HealthcareService.contained | HealthcareService.contained | Equivalent | R5 `HealthcareService.contained` maps as Equivalent to R4 `HealthcareService.contained` |
| HealthcareService.coverageArea | HealthcareService.coverageArea | Equivalent | R5 `HealthcareService.coverageArea` maps as Equivalent to R4 `HealthcareService.coverageArea` |
| HealthcareService.eligibility | HealthcareService.eligibility | Equivalent | R5 `HealthcareService.eligibility` maps as Equivalent to R4 `HealthcareService.eligibility` |
| HealthcareService.eligibility.code | HealthcareService.eligibility.code | Equivalent | R5 `HealthcareService.eligibility.code` maps as Equivalent to R4 `HealthcareService.eligibility.code` |
| HealthcareService.eligibility.comment | HealthcareService.eligibility.comment | Equivalent | R5 `HealthcareService.eligibility.comment` maps as Equivalent to R4 `HealthcareService.eligibility.comment` |
| HealthcareService.eligibility.extension | HealthcareService.eligibility.extension | SourceIsBroaderThanTarget | R5 `HealthcareService.eligibility.extension` maps as SourceIsBroaderThanTarget to R4 `HealthcareService.eligibility.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| HealthcareService.eligibility.id | HealthcareService.eligibility.id | Equivalent | R5 `HealthcareService.eligibility.id` maps as Equivalent to R4 `HealthcareService.eligibility.id` |
| HealthcareService.eligibility.modifierExtension | HealthcareService.eligibility.modifierExtension | SourceIsBroaderThanTarget | R5 `HealthcareService.eligibility.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `HealthcareService.eligibility.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| HealthcareService.endpoint | HealthcareService.endpoint | Equivalent | R5 `HealthcareService.endpoint` maps as Equivalent to R4 `HealthcareService.endpoint` |
| HealthcareService.extension | HealthcareService.extension | SourceIsBroaderThanTarget | R5 `HealthcareService.extension` maps as SourceIsBroaderThanTarget to R4 `HealthcareService.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| HealthcareService.extraDetails | HealthcareService.extraDetails | Equivalent | R5 `HealthcareService.extraDetails` maps as Equivalent to R4 `HealthcareService.extraDetails` |
| HealthcareService.id | HealthcareService.id | Equivalent | R5 `HealthcareService.id` maps as Equivalent to R4 `HealthcareService.id` |
| HealthcareService.identifier | HealthcareService.identifier | Equivalent | R5 `HealthcareService.identifier` maps as Equivalent to R4 `HealthcareService.identifier` |
| HealthcareService.implicitRules | HealthcareService.implicitRules | Equivalent | R5 `HealthcareService.implicitRules` maps as Equivalent to R4 `HealthcareService.implicitRules` |
| HealthcareService.language | HealthcareService.language | SourceIsNarrowerThanTarget | R5 `HealthcareService.language` maps as SourceIsNarrowerThanTarget to R4 `HealthcareService.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| HealthcareService.location | HealthcareService.location | Equivalent | R5 `HealthcareService.location` maps as Equivalent to R4 `HealthcareService.location` |
| HealthcareService.meta | HealthcareService.meta | Equivalent | R5 `HealthcareService.meta` maps as Equivalent to R4 `HealthcareService.meta` |
| HealthcareService.modifierExtension | HealthcareService.modifierExtension | SourceIsBroaderThanTarget | R5 `HealthcareService.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `HealthcareService.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| HealthcareService.name | HealthcareService.name | Equivalent | R5 `HealthcareService.name` maps as Equivalent to R4 `HealthcareService.name` |
| HealthcareService.offeredIn | - | DoesNotExistInTarget | R5 `HealthcareService.offeredIn` does not appear in the target and has no mapping for `HealthcareService`. |
| HealthcareService.photo | HealthcareService.photo | RelatedTo | R5 `HealthcareService.photo` maps as RelatedTo to R4 `HealthcareService.photo` - photo has change due to type change: R5 `photo` `Attachment` maps as RelatedTo for R4 `photo` |
| HealthcareService.program | HealthcareService.program | Equivalent | R5 `HealthcareService.program` maps as Equivalent to R4 `HealthcareService.program` |
| HealthcareService.providedBy | HealthcareService.providedBy | Equivalent | R5 `HealthcareService.providedBy` maps as Equivalent to R4 `HealthcareService.providedBy` |
| HealthcareService.referralMethod | HealthcareService.referralMethod | Equivalent | R5 `HealthcareService.referralMethod` maps as Equivalent to R4 `HealthcareService.referralMethod` |
| HealthcareService.serviceProvisionCode | HealthcareService.serviceProvisionCode | Equivalent | R5 `HealthcareService.serviceProvisionCode` maps as Equivalent to R4 `HealthcareService.serviceProvisionCode` |
| HealthcareService.specialty | HealthcareService.specialty | Equivalent | R5 `HealthcareService.specialty` maps as Equivalent to R4 `HealthcareService.specialty` |
| HealthcareService.text | HealthcareService.text | Equivalent | R5 `HealthcareService.text` maps as Equivalent to R4 `HealthcareService.text` |
| HealthcareService.type | HealthcareService.type | Equivalent | R5 `HealthcareService.type` maps as Equivalent to R4 `HealthcareService.type` |

