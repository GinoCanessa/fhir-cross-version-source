Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | RelatedPerson |  | Information about a person that is involved in the care for a patient, but who is not the target of healthcare, nor has a formal responsibility in the care process. | 26 | 15 |
| Target | RelatedPerson |  | Information about a person that is involved in a patient's health or the care for a patient, but who is not the target of healthcare, nor has a formal responsibility in the care process. | 26 | 15 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 22 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| RelatedPerson | RelatedPerson | Equivalent | R4B `RelatedPerson` maps as Equivalent to R5 `RelatedPerson` |
| RelatedPerson.active | RelatedPerson.active | Equivalent | R4B `RelatedPerson.active` maps as Equivalent to R5 `RelatedPerson.active` |
| RelatedPerson.address | RelatedPerson.address | Equivalent | R4B `RelatedPerson.address` maps as Equivalent to R5 `RelatedPerson.address` |
| RelatedPerson.birthDate | RelatedPerson.birthDate | Equivalent | R4B `RelatedPerson.birthDate` maps as Equivalent to R5 `RelatedPerson.birthDate` |
| RelatedPerson.communication | RelatedPerson.communication | Equivalent | R4B `RelatedPerson.communication` maps as Equivalent to R5 `RelatedPerson.communication` |
| RelatedPerson.communication.extension | RelatedPerson.communication.extension | RelatedTo | R4B `RelatedPerson.communication.extension` maps as RelatedTo to R5 `RelatedPerson.communication.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| RelatedPerson.communication.id | RelatedPerson.communication.id | Equivalent | R4B `RelatedPerson.communication.id` maps as Equivalent to R5 `RelatedPerson.communication.id` |
| RelatedPerson.communication.language | RelatedPerson.communication.language | RelatedTo | R4B `RelatedPerson.communication.language` maps as RelatedTo to R5 `RelatedPerson.communication.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| RelatedPerson.communication.modifierExtension | RelatedPerson.communication.modifierExtension | RelatedTo | R4B `RelatedPerson.communication.modifierExtension` maps as RelatedTo to R5 `RelatedPerson.communication.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| RelatedPerson.communication.preferred | RelatedPerson.communication.preferred | Equivalent | R4B `RelatedPerson.communication.preferred` maps as Equivalent to R5 `RelatedPerson.communication.preferred` |
| RelatedPerson.contained | RelatedPerson.contained | Equivalent | R4B `RelatedPerson.contained` maps as Equivalent to R5 `RelatedPerson.contained` |
| RelatedPerson.extension | RelatedPerson.extension | RelatedTo | R4B `RelatedPerson.extension` maps as RelatedTo to R5 `RelatedPerson.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| RelatedPerson.gender | RelatedPerson.gender | Equivalent | R4B `RelatedPerson.gender` maps as Equivalent to R5 `RelatedPerson.gender` - gender has compatible required binding for code type: http://hl7.org/fhir/ValueSet/administrative-gender|4.3.0 and http://hl7.org/fhir/ValueSet/administrative-gender|5.0.0 (Equivalent) |
| RelatedPerson.id | RelatedPerson.id | Equivalent | R4B `RelatedPerson.id` maps as Equivalent to R5 `RelatedPerson.id` |
| RelatedPerson.identifier | RelatedPerson.identifier | Equivalent | R4B `RelatedPerson.identifier` maps as Equivalent to R5 `RelatedPerson.identifier` |
| RelatedPerson.implicitRules | RelatedPerson.implicitRules | Equivalent | R4B `RelatedPerson.implicitRules` maps as Equivalent to R5 `RelatedPerson.implicitRules` |
| RelatedPerson.language | RelatedPerson.language | RelatedTo | R4B `RelatedPerson.language` maps as RelatedTo to R5 `RelatedPerson.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| RelatedPerson.meta | RelatedPerson.meta | Equivalent | R4B `RelatedPerson.meta` maps as Equivalent to R5 `RelatedPerson.meta` |
| RelatedPerson.modifierExtension | RelatedPerson.modifierExtension | RelatedTo | R4B `RelatedPerson.modifierExtension` maps as RelatedTo to R5 `RelatedPerson.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| RelatedPerson.name | RelatedPerson.name | Equivalent | R4B `RelatedPerson.name` maps as Equivalent to R5 `RelatedPerson.name` |
| RelatedPerson.patient | RelatedPerson.patient | Equivalent | R4B `RelatedPerson.patient` maps as Equivalent to R5 `RelatedPerson.patient` |
| RelatedPerson.period | RelatedPerson.period | Equivalent | R4B `RelatedPerson.period` maps as Equivalent to R5 `RelatedPerson.period` |
| RelatedPerson.photo | RelatedPerson.photo | RelatedTo | R4B `RelatedPerson.photo` maps as RelatedTo to R5 `RelatedPerson.photo` - photo has change due to type change: R4B `photo` `Attachment` maps as RelatedTo for R5 `photo` |
| RelatedPerson.relationship | RelatedPerson.relationship | Equivalent | R4B `RelatedPerson.relationship` maps as Equivalent to R5 `RelatedPerson.relationship` |
| RelatedPerson.telecom | RelatedPerson.telecom | Equivalent | R4B `RelatedPerson.telecom` maps as Equivalent to R5 `RelatedPerson.telecom` |
| RelatedPerson.text | RelatedPerson.text | Equivalent | R4B `RelatedPerson.text` maps as Equivalent to R5 `RelatedPerson.text` |

