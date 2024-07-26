Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1
Generated at Thursday, July 25, 2024 3:56:51 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Person |  | Demographics and administrative information about a person independent of a specific health-related context. | 32 | 18 |
| Target | Person |  | Demographics and administrative information about a person independent of a specific health-related context. | 24 | 13 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 8 |
Equivalent | 4 |
RelatedTo | 20 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Person | Person | Equivalent | R5 `Person` maps as Equivalent to R4 `Person` |
| Person.active | Person.active | Equivalent | R5 `Person.active` maps as Equivalent to R4 `Person.active` |
| Person.address | Person.address | Equivalent | R5 `Person.address` maps as Equivalent to R4 `Person.address` |
| Person.birthDate | Person.birthDate | Equivalent | R5 `Person.birthDate` maps as Equivalent to R4 `Person.birthDate` |
| Person.communication | - | DoesNotExistInTarget | R5 `Person.communication` does not appear in the target and has no mapping for `Person`. |
| Person.communication.extension | - | DoesNotExistInTarget | R5 `Person.communication.extension` does not appear in the target and has no mapping for `Person`. |
| Person.communication.id | - | DoesNotExistInTarget | R5 `Person.communication.id` does not appear in the target and has no mapping for `Person`. |
| Person.communication.language | - | DoesNotExistInTarget | R5 `Person.communication.language` does not appear in the target and has no mapping for `Person`. |
| Person.communication.modifierExtension | - | DoesNotExistInTarget | R5 `Person.communication.modifierExtension` does not appear in the target and has no mapping for `Person`. |
| Person.communication.preferred | - | DoesNotExistInTarget | R5 `Person.communication.preferred` does not appear in the target and has no mapping for `Person`. |
| Person.contained | Person.contained | Equivalent | R5 `Person.contained` maps as Equivalent to R4 `Person.contained` |
| Person.deceased[x] | - | DoesNotExistInTarget | R5 `Person.deceased[x]` does not appear in the target and has no mapping for `Person`. |
| Person.extension | Person.extension | SourceIsBroaderThanTarget | R5 `Person.extension` maps as SourceIsBroaderThanTarget to R4 `Person.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Person.gender | Person.gender | Equivalent | R5 `Person.gender` maps as Equivalent to R4 `Person.gender` - gender has compatible required binding for code type: http://hl7.org/fhir/ValueSet/administrative-gender|5.0.0 and http://hl7.org/fhir/ValueSet/administrative-gender|4.0.1 (Equivalent) |
| Person.id | Person.id | Equivalent | R5 `Person.id` maps as Equivalent to R4 `Person.id` |
| Person.identifier | Person.identifier | Equivalent | R5 `Person.identifier` maps as Equivalent to R4 `Person.identifier` |
| Person.implicitRules | Person.implicitRules | Equivalent | R5 `Person.implicitRules` maps as Equivalent to R4 `Person.implicitRules` |
| Person.language | Person.language | RelatedTo | R5 `Person.language` maps as RelatedTo to R4 `Person.language` - language changed the binding strength from Required to Preferred |
| Person.link | Person.link | Equivalent | R5 `Person.link` maps as Equivalent to R4 `Person.link` |
| Person.link.assurance | Person.link.assurance | Equivalent | R5 `Person.link.assurance` maps as Equivalent to R4 `Person.link.assurance` - assurance has compatible required binding for code type: http://hl7.org/fhir/ValueSet/identity-assuranceLevel|5.0.0 and http://hl7.org/fhir/ValueSet/identity-assuranceLevel|4.0.1 (Equivalent) |
| Person.link.extension | Person.link.extension | SourceIsBroaderThanTarget | R5 `Person.link.extension` maps as SourceIsBroaderThanTarget to R4 `Person.link.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Person.link.id | Person.link.id | Equivalent | R5 `Person.link.id` maps as Equivalent to R4 `Person.link.id` |
| Person.link.modifierExtension | Person.link.modifierExtension | SourceIsBroaderThanTarget | R5 `Person.link.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Person.link.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Person.link.target | Person.link.target | Equivalent | R5 `Person.link.target` maps as Equivalent to R4 `Person.link.target` |
| Person.managingOrganization | Person.managingOrganization | Equivalent | R5 `Person.managingOrganization` maps as Equivalent to R4 `Person.managingOrganization` |
| Person.maritalStatus | - | DoesNotExistInTarget | R5 `Person.maritalStatus` does not appear in the target and has no mapping for `Person`. |
| Person.meta | Person.meta | Equivalent | R5 `Person.meta` maps as Equivalent to R4 `Person.meta` |
| Person.modifierExtension | Person.modifierExtension | SourceIsBroaderThanTarget | R5 `Person.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Person.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Person.name | Person.name | Equivalent | R5 `Person.name` maps as Equivalent to R4 `Person.name` |
| Person.photo | Person.photo | RelatedTo | R5 `Person.photo` maps as RelatedTo to R4 `Person.photo` - photo changed from array to scalar (max cardinality from * to 1); photo has change due to type change: R5 `photo` `Attachment` maps as RelatedTo for R4 `photo` |
| Person.telecom | Person.telecom | Equivalent | R5 `Person.telecom` maps as Equivalent to R4 `Person.telecom` |
| Person.text | Person.text | Equivalent | R5 `Person.text` maps as Equivalent to R4 `Person.text` |

