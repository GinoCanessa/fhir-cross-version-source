Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1
Generated at Thursday, July 25, 2024 3:56:51 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | RelatedPerson |  | Information about a person that is involved in a patient's health or the care for a patient, but who is not the target of healthcare, nor has a formal responsibility in the care process. | 26 | 15 |
| Target | RelatedPerson |  | Information about a person that is involved in the care for a patient, but who is not the target of healthcare, nor has a formal responsibility in the care process. | 26 | 15 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 22 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| RelatedPerson | RelatedPerson | Equivalent | R5 `RelatedPerson` maps as Equivalent to R4 `RelatedPerson` |
| RelatedPerson.active | RelatedPerson.active | Equivalent | R5 `RelatedPerson.active` maps as Equivalent to R4 `RelatedPerson.active` |
| RelatedPerson.address | RelatedPerson.address | Equivalent | R5 `RelatedPerson.address` maps as Equivalent to R4 `RelatedPerson.address` |
| RelatedPerson.birthDate | RelatedPerson.birthDate | Equivalent | R5 `RelatedPerson.birthDate` maps as Equivalent to R4 `RelatedPerson.birthDate` |
| RelatedPerson.communication | RelatedPerson.communication | Equivalent | R5 `RelatedPerson.communication` maps as Equivalent to R4 `RelatedPerson.communication` |
| RelatedPerson.communication.extension | RelatedPerson.communication.extension | SourceIsBroaderThanTarget | R5 `RelatedPerson.communication.extension` maps as SourceIsBroaderThanTarget to R4 `RelatedPerson.communication.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| RelatedPerson.communication.id | RelatedPerson.communication.id | Equivalent | R5 `RelatedPerson.communication.id` maps as Equivalent to R4 `RelatedPerson.communication.id` |
| RelatedPerson.communication.language | RelatedPerson.communication.language | RelatedTo | R5 `RelatedPerson.communication.language` maps as RelatedTo to R4 `RelatedPerson.communication.language` - language changed the binding strength from Required to Preferred |
| RelatedPerson.communication.modifierExtension | RelatedPerson.communication.modifierExtension | SourceIsBroaderThanTarget | R5 `RelatedPerson.communication.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `RelatedPerson.communication.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| RelatedPerson.communication.preferred | RelatedPerson.communication.preferred | Equivalent | R5 `RelatedPerson.communication.preferred` maps as Equivalent to R4 `RelatedPerson.communication.preferred` |
| RelatedPerson.contained | RelatedPerson.contained | Equivalent | R5 `RelatedPerson.contained` maps as Equivalent to R4 `RelatedPerson.contained` |
| RelatedPerson.extension | RelatedPerson.extension | SourceIsBroaderThanTarget | R5 `RelatedPerson.extension` maps as SourceIsBroaderThanTarget to R4 `RelatedPerson.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| RelatedPerson.gender | RelatedPerson.gender | Equivalent | R5 `RelatedPerson.gender` maps as Equivalent to R4 `RelatedPerson.gender` - gender has compatible required binding for code type: http://hl7.org/fhir/ValueSet/administrative-gender|5.0.0 and http://hl7.org/fhir/ValueSet/administrative-gender|4.0.1 (Equivalent) |
| RelatedPerson.id | RelatedPerson.id | Equivalent | R5 `RelatedPerson.id` maps as Equivalent to R4 `RelatedPerson.id` |
| RelatedPerson.identifier | RelatedPerson.identifier | Equivalent | R5 `RelatedPerson.identifier` maps as Equivalent to R4 `RelatedPerson.identifier` |
| RelatedPerson.implicitRules | RelatedPerson.implicitRules | Equivalent | R5 `RelatedPerson.implicitRules` maps as Equivalent to R4 `RelatedPerson.implicitRules` |
| RelatedPerson.language | RelatedPerson.language | RelatedTo | R5 `RelatedPerson.language` maps as RelatedTo to R4 `RelatedPerson.language` - language changed the binding strength from Required to Preferred |
| RelatedPerson.meta | RelatedPerson.meta | Equivalent | R5 `RelatedPerson.meta` maps as Equivalent to R4 `RelatedPerson.meta` |
| RelatedPerson.modifierExtension | RelatedPerson.modifierExtension | SourceIsBroaderThanTarget | R5 `RelatedPerson.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `RelatedPerson.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| RelatedPerson.name | RelatedPerson.name | Equivalent | R5 `RelatedPerson.name` maps as Equivalent to R4 `RelatedPerson.name` |
| RelatedPerson.patient | RelatedPerson.patient | Equivalent | R5 `RelatedPerson.patient` maps as Equivalent to R4 `RelatedPerson.patient` |
| RelatedPerson.period | RelatedPerson.period | Equivalent | R5 `RelatedPerson.period` maps as Equivalent to R4 `RelatedPerson.period` |
| RelatedPerson.photo | RelatedPerson.photo | RelatedTo | R5 `RelatedPerson.photo` maps as RelatedTo to R4 `RelatedPerson.photo` - photo has change due to type change: R5 `photo` `Attachment` maps as RelatedTo for R4 `photo` |
| RelatedPerson.relationship | RelatedPerson.relationship | Equivalent | R5 `RelatedPerson.relationship` maps as Equivalent to R4 `RelatedPerson.relationship` |
| RelatedPerson.telecom | RelatedPerson.telecom | Equivalent | R5 `RelatedPerson.telecom` maps as Equivalent to R4 `RelatedPerson.telecom` |
| RelatedPerson.text | RelatedPerson.text | Equivalent | R5 `RelatedPerson.text` maps as Equivalent to R4 `RelatedPerson.text` |

