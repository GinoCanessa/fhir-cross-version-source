Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

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
| Patient | Patient | Equivalent | R4B `Patient` maps as Equivalent to R5 `Patient` |
| Patient.active | Patient.active | Equivalent | R4B `Patient.active` maps as Equivalent to R5 `Patient.active` |
| Patient.address | Patient.address | Equivalent | R4B `Patient.address` maps as Equivalent to R5 `Patient.address` |
| Patient.birthDate | Patient.birthDate | Equivalent | R4B `Patient.birthDate` maps as Equivalent to R5 `Patient.birthDate` |
| Patient.communication | Patient.communication | Equivalent | R4B `Patient.communication` maps as Equivalent to R5 `Patient.communication` |
| Patient.communication.extension | Patient.communication.extension | RelatedTo | R4B `Patient.communication.extension` maps as RelatedTo to R5 `Patient.communication.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Patient.communication.id | Patient.communication.id | Equivalent | R4B `Patient.communication.id` maps as Equivalent to R5 `Patient.communication.id` |
| Patient.communication.language | Patient.communication.language | RelatedTo | R4B `Patient.communication.language` maps as RelatedTo to R5 `Patient.communication.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Patient.communication.modifierExtension | Patient.communication.modifierExtension | RelatedTo | R4B `Patient.communication.modifierExtension` maps as RelatedTo to R5 `Patient.communication.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Patient.communication.preferred | Patient.communication.preferred | Equivalent | R4B `Patient.communication.preferred` maps as Equivalent to R5 `Patient.communication.preferred` |
| Patient.contact | Patient.contact | Equivalent | R4B `Patient.contact` maps as Equivalent to R5 `Patient.contact` |
| Patient.contact.address | Patient.contact.address | Equivalent | R4B `Patient.contact.address` maps as Equivalent to R5 `Patient.contact.address` |
| Patient.contact.extension | Patient.contact.extension | RelatedTo | R4B `Patient.contact.extension` maps as RelatedTo to R5 `Patient.contact.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Patient.contact.gender | Patient.contact.gender | Equivalent | R4B `Patient.contact.gender` maps as Equivalent to R5 `Patient.contact.gender` - gender has compatible required binding for code type: http://hl7.org/fhir/ValueSet/administrative-gender|4.3.0 and http://hl7.org/fhir/ValueSet/administrative-gender|5.0.0 (Equivalent) |
| Patient.contact.id | Patient.contact.id | Equivalent | R4B `Patient.contact.id` maps as Equivalent to R5 `Patient.contact.id` |
| Patient.contact.modifierExtension | Patient.contact.modifierExtension | RelatedTo | R4B `Patient.contact.modifierExtension` maps as RelatedTo to R5 `Patient.contact.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Patient.contact.name | Patient.contact.name | Equivalent | R4B `Patient.contact.name` maps as Equivalent to R5 `Patient.contact.name` |
| Patient.contact.organization | Patient.contact.organization | Equivalent | R4B `Patient.contact.organization` maps as Equivalent to R5 `Patient.contact.organization` |
| Patient.contact.period | Patient.contact.period | Equivalent | R4B `Patient.contact.period` maps as Equivalent to R5 `Patient.contact.period` |
| Patient.contact.relationship | Patient.contact.relationship | Equivalent | R4B `Patient.contact.relationship` maps as Equivalent to R5 `Patient.contact.relationship` |
| Patient.contact.telecom | Patient.contact.telecom | Equivalent | R4B `Patient.contact.telecom` maps as Equivalent to R5 `Patient.contact.telecom` |
| Patient.contained | Patient.contained | Equivalent | R4B `Patient.contained` maps as Equivalent to R5 `Patient.contained` |
| Patient.deceased[x] | Patient.deceased[x] | Equivalent | R4B `Patient.deceased[x]` maps as Equivalent to R5 `Patient.deceased[x]` |
| Patient.extension | Patient.extension | RelatedTo | R4B `Patient.extension` maps as RelatedTo to R5 `Patient.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Patient.gender | Patient.gender | Equivalent | R4B `Patient.gender` maps as Equivalent to R5 `Patient.gender` - gender has compatible required binding for code type: http://hl7.org/fhir/ValueSet/administrative-gender|4.3.0 and http://hl7.org/fhir/ValueSet/administrative-gender|5.0.0 (Equivalent) |
| Patient.generalPractitioner | Patient.generalPractitioner | Equivalent | R4B `Patient.generalPractitioner` maps as Equivalent to R5 `Patient.generalPractitioner` |
| Patient.id | Patient.id | Equivalent | R4B `Patient.id` maps as Equivalent to R5 `Patient.id` |
| Patient.identifier | Patient.identifier | Equivalent | R4B `Patient.identifier` maps as Equivalent to R5 `Patient.identifier` |
| Patient.implicitRules | Patient.implicitRules | Equivalent | R4B `Patient.implicitRules` maps as Equivalent to R5 `Patient.implicitRules` |
| Patient.language | Patient.language | RelatedTo | R4B `Patient.language` maps as RelatedTo to R5 `Patient.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Patient.link | Patient.link | Equivalent | R4B `Patient.link` maps as Equivalent to R5 `Patient.link` |
| Patient.link.extension | Patient.link.extension | RelatedTo | R4B `Patient.link.extension` maps as RelatedTo to R5 `Patient.link.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Patient.link.id | Patient.link.id | Equivalent | R4B `Patient.link.id` maps as Equivalent to R5 `Patient.link.id` |
| Patient.link.modifierExtension | Patient.link.modifierExtension | RelatedTo | R4B `Patient.link.modifierExtension` maps as RelatedTo to R5 `Patient.link.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Patient.link.other | Patient.link.other | Equivalent | R4B `Patient.link.other` maps as Equivalent to R5 `Patient.link.other` |
| Patient.link.type | Patient.link.type | Equivalent | R4B `Patient.link.type` maps as Equivalent to R5 `Patient.link.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/link-type|4.3.0 and http://hl7.org/fhir/ValueSet/link-type|5.0.0 (Equivalent) |
| Patient.managingOrganization | Patient.managingOrganization | Equivalent | R4B `Patient.managingOrganization` maps as Equivalent to R5 `Patient.managingOrganization` |
| Patient.maritalStatus | Patient.maritalStatus | Equivalent | R4B `Patient.maritalStatus` maps as Equivalent to R5 `Patient.maritalStatus` |
| Patient.meta | Patient.meta | Equivalent | R4B `Patient.meta` maps as Equivalent to R5 `Patient.meta` |
| Patient.modifierExtension | Patient.modifierExtension | RelatedTo | R4B `Patient.modifierExtension` maps as RelatedTo to R5 `Patient.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Patient.multipleBirth[x] | Patient.multipleBirth[x] | Equivalent | R4B `Patient.multipleBirth[x]` maps as Equivalent to R5 `Patient.multipleBirth[x]` |
| Patient.name | Patient.name | Equivalent | R4B `Patient.name` maps as Equivalent to R5 `Patient.name` |
| Patient.photo | Patient.photo | RelatedTo | R4B `Patient.photo` maps as RelatedTo to R5 `Patient.photo` - photo has change due to type change: R4B `photo` `Attachment` maps as RelatedTo for R5 `photo` |
| Patient.telecom | Patient.telecom | Equivalent | R4B `Patient.telecom` maps as Equivalent to R5 `Patient.telecom` |
| Patient.text | Patient.text | Equivalent | R4B `Patient.text` maps as Equivalent to R5 `Patient.text` |

