Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Patient |  | Demographics and other administrative information about an individual or animal receiving care or other health-related services. | 45 | 28 |
| Target | Patient |  | Demographics and other administrative information about an individual or animal receiving care or other health-related services. | 45 | 28 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 41 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Patient | Patient | Equivalent | R5 `Patient` maps as Equivalent to R4B `Patient` |
| Patient.active | Patient.active | Equivalent | R5 `Patient.active` maps as Equivalent to R4B `Patient.active` |
| Patient.address | Patient.address | Equivalent | R5 `Patient.address` maps as Equivalent to R4B `Patient.address` |
| Patient.birthDate | Patient.birthDate | Equivalent | R5 `Patient.birthDate` maps as Equivalent to R4B `Patient.birthDate` |
| Patient.communication | Patient.communication | Equivalent | R5 `Patient.communication` maps as Equivalent to R4B `Patient.communication` |
| Patient.communication.extension | Patient.communication.extension | SourceIsBroaderThanTarget | R5 `Patient.communication.extension` maps as SourceIsBroaderThanTarget to R4B `Patient.communication.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Patient.communication.id | Patient.communication.id | Equivalent | R5 `Patient.communication.id` maps as Equivalent to R4B `Patient.communication.id` |
| Patient.communication.language | Patient.communication.language | RelatedTo | R5 `Patient.communication.language` maps as RelatedTo to R4B `Patient.communication.language` - language changed the binding strength from Required to Preferred |
| Patient.communication.modifierExtension | Patient.communication.modifierExtension | SourceIsBroaderThanTarget | R5 `Patient.communication.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Patient.communication.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Patient.communication.preferred | Patient.communication.preferred | Equivalent | R5 `Patient.communication.preferred` maps as Equivalent to R4B `Patient.communication.preferred` |
| Patient.contact | Patient.contact | Equivalent | R5 `Patient.contact` maps as Equivalent to R4B `Patient.contact` |
| Patient.contact.address | Patient.contact.address | Equivalent | R5 `Patient.contact.address` maps as Equivalent to R4B `Patient.contact.address` |
| Patient.contact.extension | Patient.contact.extension | SourceIsBroaderThanTarget | R5 `Patient.contact.extension` maps as SourceIsBroaderThanTarget to R4B `Patient.contact.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Patient.contact.gender | Patient.contact.gender | Equivalent | R5 `Patient.contact.gender` maps as Equivalent to R4B `Patient.contact.gender` - gender has compatible required binding for code type: http://hl7.org/fhir/ValueSet/administrative-gender|5.0.0 and http://hl7.org/fhir/ValueSet/administrative-gender|4.3.0 (Equivalent) |
| Patient.contact.id | Patient.contact.id | Equivalent | R5 `Patient.contact.id` maps as Equivalent to R4B `Patient.contact.id` |
| Patient.contact.modifierExtension | Patient.contact.modifierExtension | SourceIsBroaderThanTarget | R5 `Patient.contact.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Patient.contact.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Patient.contact.name | Patient.contact.name | Equivalent | R5 `Patient.contact.name` maps as Equivalent to R4B `Patient.contact.name` |
| Patient.contact.organization | Patient.contact.organization | Equivalent | R5 `Patient.contact.organization` maps as Equivalent to R4B `Patient.contact.organization` |
| Patient.contact.period | Patient.contact.period | Equivalent | R5 `Patient.contact.period` maps as Equivalent to R4B `Patient.contact.period` |
| Patient.contact.relationship | Patient.contact.relationship | Equivalent | R5 `Patient.contact.relationship` maps as Equivalent to R4B `Patient.contact.relationship` |
| Patient.contact.telecom | Patient.contact.telecom | Equivalent | R5 `Patient.contact.telecom` maps as Equivalent to R4B `Patient.contact.telecom` |
| Patient.contained | Patient.contained | Equivalent | R5 `Patient.contained` maps as Equivalent to R4B `Patient.contained` |
| Patient.deceased[x] | Patient.deceased[x] | Equivalent | R5 `Patient.deceased[x]` maps as Equivalent to R4B `Patient.deceased[x]` |
| Patient.extension | Patient.extension | SourceIsBroaderThanTarget | R5 `Patient.extension` maps as SourceIsBroaderThanTarget to R4B `Patient.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Patient.gender | Patient.gender | Equivalent | R5 `Patient.gender` maps as Equivalent to R4B `Patient.gender` - gender has compatible required binding for code type: http://hl7.org/fhir/ValueSet/administrative-gender|5.0.0 and http://hl7.org/fhir/ValueSet/administrative-gender|4.3.0 (Equivalent) |
| Patient.generalPractitioner | Patient.generalPractitioner | Equivalent | R5 `Patient.generalPractitioner` maps as Equivalent to R4B `Patient.generalPractitioner` |
| Patient.id | Patient.id | Equivalent | R5 `Patient.id` maps as Equivalent to R4B `Patient.id` |
| Patient.identifier | Patient.identifier | Equivalent | R5 `Patient.identifier` maps as Equivalent to R4B `Patient.identifier` |
| Patient.implicitRules | Patient.implicitRules | Equivalent | R5 `Patient.implicitRules` maps as Equivalent to R4B `Patient.implicitRules` |
| Patient.language | Patient.language | RelatedTo | R5 `Patient.language` maps as RelatedTo to R4B `Patient.language` - language changed the binding strength from Required to Preferred |
| Patient.link | Patient.link | Equivalent | R5 `Patient.link` maps as Equivalent to R4B `Patient.link` |
| Patient.link.extension | Patient.link.extension | SourceIsBroaderThanTarget | R5 `Patient.link.extension` maps as SourceIsBroaderThanTarget to R4B `Patient.link.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Patient.link.id | Patient.link.id | Equivalent | R5 `Patient.link.id` maps as Equivalent to R4B `Patient.link.id` |
| Patient.link.modifierExtension | Patient.link.modifierExtension | SourceIsBroaderThanTarget | R5 `Patient.link.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Patient.link.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Patient.link.other | Patient.link.other | Equivalent | R5 `Patient.link.other` maps as Equivalent to R4B `Patient.link.other` |
| Patient.link.type | Patient.link.type | Equivalent | R5 `Patient.link.type` maps as Equivalent to R4B `Patient.link.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/link-type|5.0.0 and http://hl7.org/fhir/ValueSet/link-type|4.3.0 (Equivalent) |
| Patient.managingOrganization | Patient.managingOrganization | Equivalent | R5 `Patient.managingOrganization` maps as Equivalent to R4B `Patient.managingOrganization` |
| Patient.maritalStatus | Patient.maritalStatus | Equivalent | R5 `Patient.maritalStatus` maps as Equivalent to R4B `Patient.maritalStatus` |
| Patient.meta | Patient.meta | Equivalent | R5 `Patient.meta` maps as Equivalent to R4B `Patient.meta` |
| Patient.modifierExtension | Patient.modifierExtension | SourceIsBroaderThanTarget | R5 `Patient.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Patient.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Patient.multipleBirth[x] | Patient.multipleBirth[x] | Equivalent | R5 `Patient.multipleBirth[x]` maps as Equivalent to R4B `Patient.multipleBirth[x]` |
| Patient.name | Patient.name | Equivalent | R5 `Patient.name` maps as Equivalent to R4B `Patient.name` |
| Patient.photo | Patient.photo | RelatedTo | R5 `Patient.photo` maps as RelatedTo to R4B `Patient.photo` - photo has change due to type change: R5 `photo` `Attachment` maps as RelatedTo for R4B `photo` |
| Patient.telecom | Patient.telecom | Equivalent | R5 `Patient.telecom` maps as Equivalent to R4B `Patient.telecom` |
| Patient.text | Patient.text | Equivalent | R5 `Patient.text` maps as Equivalent to R4B `Patient.text` |

