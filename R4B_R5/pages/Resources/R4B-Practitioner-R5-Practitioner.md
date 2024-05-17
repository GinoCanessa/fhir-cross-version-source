Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Practitioner |  | A person who is directly or indirectly involved in the provisioning of healthcare. | 26 | 15 |
| Target | Practitioner |  | A person who is directly or indirectly involved in the provisioning of healthcare or related services. | 32 | 18 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 22 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Practitioner | Practitioner | Equivalent | R4B `Practitioner` maps as Equivalent to R5 `Practitioner` |
| Practitioner.active | Practitioner.active | Equivalent | R4B `Practitioner.active` maps as Equivalent to R5 `Practitioner.active` |
| Practitioner.address | Practitioner.address | Equivalent | R4B `Practitioner.address` maps as Equivalent to R5 `Practitioner.address` |
| Practitioner.birthDate | Practitioner.birthDate | Equivalent | R4B `Practitioner.birthDate` maps as Equivalent to R5 `Practitioner.birthDate` |
| Practitioner.communication | Practitioner.communication | RelatedTo | R4B `Practitioner.communication` maps as RelatedTo to R5 `Practitioner.communication` - communication removed a binding requirement - Preferred http://hl7.org/fhir/ValueSet/languages; communication has change due to type change: R4B communication CodeableConcept has no equivalent or mapped type in R5 communication |
| Practitioner.contained | Practitioner.contained | Equivalent | R4B `Practitioner.contained` maps as Equivalent to R5 `Practitioner.contained` |
| Practitioner.extension | Practitioner.extension | RelatedTo | R4B `Practitioner.extension` maps as RelatedTo to R5 `Practitioner.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Practitioner.gender | Practitioner.gender | Equivalent | R4B `Practitioner.gender` maps as Equivalent to R5 `Practitioner.gender` - gender has compatible required binding for code type: http://hl7.org/fhir/ValueSet/administrative-gender|4.3.0 and http://hl7.org/fhir/ValueSet/administrative-gender|5.0.0 (Equivalent) |
| Practitioner.id | Practitioner.id | Equivalent | R4B `Practitioner.id` maps as Equivalent to R5 `Practitioner.id` |
| Practitioner.identifier | Practitioner.identifier | Equivalent | R4B `Practitioner.identifier` maps as Equivalent to R5 `Practitioner.identifier` |
| Practitioner.implicitRules | Practitioner.implicitRules | Equivalent | R4B `Practitioner.implicitRules` maps as Equivalent to R5 `Practitioner.implicitRules` |
| Practitioner.language | Practitioner.language | RelatedTo | R4B `Practitioner.language` maps as RelatedTo to R5 `Practitioner.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Practitioner.meta | Practitioner.meta | Equivalent | R4B `Practitioner.meta` maps as Equivalent to R5 `Practitioner.meta` |
| Practitioner.modifierExtension | Practitioner.modifierExtension | RelatedTo | R4B `Practitioner.modifierExtension` maps as RelatedTo to R5 `Practitioner.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Practitioner.name | Practitioner.name | Equivalent | R4B `Practitioner.name` maps as Equivalent to R5 `Practitioner.name` |
| Practitioner.photo | Practitioner.photo | RelatedTo | R4B `Practitioner.photo` maps as RelatedTo to R5 `Practitioner.photo` - photo has change due to type change: R4B `photo` `Attachment` maps as RelatedTo for R5 `photo` |
| Practitioner.qualification | Practitioner.qualification | Equivalent | R4B `Practitioner.qualification` maps as Equivalent to R5 `Practitioner.qualification` |
| Practitioner.qualification.code | Practitioner.qualification.code | Equivalent | R4B `Practitioner.qualification.code` maps as Equivalent to R5 `Practitioner.qualification.code` |
| Practitioner.qualification.extension | Practitioner.qualification.extension | RelatedTo | R4B `Practitioner.qualification.extension` maps as RelatedTo to R5 `Practitioner.qualification.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Practitioner.qualification.id | Practitioner.qualification.id | Equivalent | R4B `Practitioner.qualification.id` maps as Equivalent to R5 `Practitioner.qualification.id` |
| Practitioner.qualification.identifier | Practitioner.qualification.identifier | Equivalent | R4B `Practitioner.qualification.identifier` maps as Equivalent to R5 `Practitioner.qualification.identifier` |
| Practitioner.qualification.issuer | Practitioner.qualification.issuer | Equivalent | R4B `Practitioner.qualification.issuer` maps as Equivalent to R5 `Practitioner.qualification.issuer` |
| Practitioner.qualification.modifierExtension | Practitioner.qualification.modifierExtension | RelatedTo | R4B `Practitioner.qualification.modifierExtension` maps as RelatedTo to R5 `Practitioner.qualification.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Practitioner.qualification.period | Practitioner.qualification.period | Equivalent | R4B `Practitioner.qualification.period` maps as Equivalent to R5 `Practitioner.qualification.period` |
| Practitioner.telecom | Practitioner.telecom | Equivalent | R4B `Practitioner.telecom` maps as Equivalent to R5 `Practitioner.telecom` |
| Practitioner.text | Practitioner.text | Equivalent | R4B `Practitioner.text` maps as Equivalent to R5 `Practitioner.text` |

