Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Practitioner |  | A person who is directly or indirectly involved in the provisioning of healthcare or related services. | 32 | 18 |
| Target | Practitioner |  | A person who is directly or indirectly involved in the provisioning of healthcare. | 26 | 15 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 6 |
Equivalent | 19 |
RelatedTo | 1 |
SourceIsBroaderThanTarget | 5 |
SourceIsNarrowerThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Practitioner | Practitioner | Equivalent | R5 `Practitioner` maps as Equivalent to R4 `Practitioner` |
| Practitioner.active | Practitioner.active | Equivalent | R5 `Practitioner.active` maps as Equivalent to R4 `Practitioner.active` |
| Practitioner.address | Practitioner.address | Equivalent | R5 `Practitioner.address` maps as Equivalent to R4 `Practitioner.address` |
| Practitioner.birthDate | Practitioner.birthDate | Equivalent | R5 `Practitioner.birthDate` maps as Equivalent to R4 `Practitioner.birthDate` |
| Practitioner.communication | Practitioner.communication | SourceIsBroaderThanTarget | R5 `Practitioner.communication` maps as SourceIsBroaderThanTarget to R4 `Practitioner.communication` - communication added a binding requirement - Preferred http://hl7.org/fhir/ValueSet/languages; communication has change due to type change: R5 communication BackboneElement has no equivalent or mapped type in R4 communication |
| Practitioner.communication.extension | - | DoesNotExistInTarget | R5 `Practitioner.communication.extension` does not appear in the target and has no mapping for `Practitioner`. |
| Practitioner.communication.id | - | DoesNotExistInTarget | R5 `Practitioner.communication.id` does not appear in the target and has no mapping for `Practitioner`. |
| Practitioner.communication.language | - | DoesNotExistInTarget | R5 `Practitioner.communication.language` does not appear in the target and has no mapping for `Practitioner`. |
| Practitioner.communication.modifierExtension | - | DoesNotExistInTarget | R5 `Practitioner.communication.modifierExtension` does not appear in the target and has no mapping for `Practitioner`. |
| Practitioner.communication.preferred | - | DoesNotExistInTarget | R5 `Practitioner.communication.preferred` does not appear in the target and has no mapping for `Practitioner`. |
| Practitioner.contained | Practitioner.contained | Equivalent | R5 `Practitioner.contained` maps as Equivalent to R4 `Practitioner.contained` |
| Practitioner.deceased[x] | - | DoesNotExistInTarget | R5 `Practitioner.deceased[x]` does not appear in the target and has no mapping for `Practitioner`. |
| Practitioner.extension | Practitioner.extension | SourceIsBroaderThanTarget | R5 `Practitioner.extension` maps as SourceIsBroaderThanTarget to R4 `Practitioner.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Practitioner.gender | Practitioner.gender | Equivalent | R5 `Practitioner.gender` maps as Equivalent to R4 `Practitioner.gender` - gender has compatible required binding for code type: http://hl7.org/fhir/ValueSet/administrative-gender|5.0.0 and http://hl7.org/fhir/ValueSet/administrative-gender|4.0.1 (Equivalent) |
| Practitioner.id | Practitioner.id | Equivalent | R5 `Practitioner.id` maps as Equivalent to R4 `Practitioner.id` |
| Practitioner.identifier | Practitioner.identifier | Equivalent | R5 `Practitioner.identifier` maps as Equivalent to R4 `Practitioner.identifier` |
| Practitioner.implicitRules | Practitioner.implicitRules | Equivalent | R5 `Practitioner.implicitRules` maps as Equivalent to R4 `Practitioner.implicitRules` |
| Practitioner.language | Practitioner.language | SourceIsNarrowerThanTarget | R5 `Practitioner.language` maps as SourceIsNarrowerThanTarget to R4 `Practitioner.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| Practitioner.meta | Practitioner.meta | Equivalent | R5 `Practitioner.meta` maps as Equivalent to R4 `Practitioner.meta` |
| Practitioner.modifierExtension | Practitioner.modifierExtension | SourceIsBroaderThanTarget | R5 `Practitioner.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Practitioner.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Practitioner.name | Practitioner.name | Equivalent | R5 `Practitioner.name` maps as Equivalent to R4 `Practitioner.name` |
| Practitioner.photo | Practitioner.photo | RelatedTo | R5 `Practitioner.photo` maps as RelatedTo to R4 `Practitioner.photo` - photo has change due to type change: R5 `photo` `Attachment` maps as RelatedTo for R4 `photo` |
| Practitioner.qualification | Practitioner.qualification | Equivalent | R5 `Practitioner.qualification` maps as Equivalent to R4 `Practitioner.qualification` |
| Practitioner.qualification.code | Practitioner.qualification.code | Equivalent | R5 `Practitioner.qualification.code` maps as Equivalent to R4 `Practitioner.qualification.code` |
| Practitioner.qualification.extension | Practitioner.qualification.extension | SourceIsBroaderThanTarget | R5 `Practitioner.qualification.extension` maps as SourceIsBroaderThanTarget to R4 `Practitioner.qualification.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Practitioner.qualification.id | Practitioner.qualification.id | Equivalent | R5 `Practitioner.qualification.id` maps as Equivalent to R4 `Practitioner.qualification.id` |
| Practitioner.qualification.identifier | Practitioner.qualification.identifier | Equivalent | R5 `Practitioner.qualification.identifier` maps as Equivalent to R4 `Practitioner.qualification.identifier` |
| Practitioner.qualification.issuer | Practitioner.qualification.issuer | Equivalent | R5 `Practitioner.qualification.issuer` maps as Equivalent to R4 `Practitioner.qualification.issuer` |
| Practitioner.qualification.modifierExtension | Practitioner.qualification.modifierExtension | SourceIsBroaderThanTarget | R5 `Practitioner.qualification.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Practitioner.qualification.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Practitioner.qualification.period | Practitioner.qualification.period | Equivalent | R5 `Practitioner.qualification.period` maps as Equivalent to R4 `Practitioner.qualification.period` |
| Practitioner.telecom | Practitioner.telecom | Equivalent | R5 `Practitioner.telecom` maps as Equivalent to R4 `Practitioner.telecom` |
| Practitioner.text | Practitioner.text | Equivalent | R5 `Practitioner.text` maps as Equivalent to R4 `Practitioner.text` |

