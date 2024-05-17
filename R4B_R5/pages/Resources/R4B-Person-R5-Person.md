Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Person |  | Demographics and administrative information about a person independent of a specific health-related context. | 24 | 13 |
| Target | Person |  | Demographics and administrative information about a person independent of a specific health-related context. | 32 | 18 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 20 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Person | Person | Equivalent | R4B `Person` maps as Equivalent to R5 `Person` |
| Person.active | Person.active | Equivalent | R4B `Person.active` maps as Equivalent to R5 `Person.active` |
| Person.address | Person.address | Equivalent | R4B `Person.address` maps as Equivalent to R5 `Person.address` |
| Person.birthDate | Person.birthDate | Equivalent | R4B `Person.birthDate` maps as Equivalent to R5 `Person.birthDate` |
| Person.contained | Person.contained | Equivalent | R4B `Person.contained` maps as Equivalent to R5 `Person.contained` |
| Person.extension | Person.extension | RelatedTo | R4B `Person.extension` maps as RelatedTo to R5 `Person.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Person.gender | Person.gender | Equivalent | R4B `Person.gender` maps as Equivalent to R5 `Person.gender` - gender has compatible required binding for code type: http://hl7.org/fhir/ValueSet/administrative-gender|4.3.0 and http://hl7.org/fhir/ValueSet/administrative-gender|5.0.0 (Equivalent) |
| Person.id | Person.id | Equivalent | R4B `Person.id` maps as Equivalent to R5 `Person.id` |
| Person.identifier | Person.identifier | Equivalent | R4B `Person.identifier` maps as Equivalent to R5 `Person.identifier` |
| Person.implicitRules | Person.implicitRules | Equivalent | R4B `Person.implicitRules` maps as Equivalent to R5 `Person.implicitRules` |
| Person.language | Person.language | RelatedTo | R4B `Person.language` maps as RelatedTo to R5 `Person.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Person.link | Person.link | Equivalent | R4B `Person.link` maps as Equivalent to R5 `Person.link` |
| Person.link.assurance | Person.link.assurance | Equivalent | R4B `Person.link.assurance` maps as Equivalent to R5 `Person.link.assurance` - assurance has compatible required binding for code type: http://hl7.org/fhir/ValueSet/identity-assuranceLevel|4.3.0 and http://hl7.org/fhir/ValueSet/identity-assuranceLevel|5.0.0 (Equivalent) |
| Person.link.extension | Person.link.extension | RelatedTo | R4B `Person.link.extension` maps as RelatedTo to R5 `Person.link.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Person.link.id | Person.link.id | Equivalent | R4B `Person.link.id` maps as Equivalent to R5 `Person.link.id` |
| Person.link.modifierExtension | Person.link.modifierExtension | RelatedTo | R4B `Person.link.modifierExtension` maps as RelatedTo to R5 `Person.link.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Person.link.target | Person.link.target | Equivalent | R4B `Person.link.target` maps as Equivalent to R5 `Person.link.target` |
| Person.managingOrganization | Person.managingOrganization | Equivalent | R4B `Person.managingOrganization` maps as Equivalent to R5 `Person.managingOrganization` |
| Person.meta | Person.meta | Equivalent | R4B `Person.meta` maps as Equivalent to R5 `Person.meta` |
| Person.modifierExtension | Person.modifierExtension | RelatedTo | R4B `Person.modifierExtension` maps as RelatedTo to R5 `Person.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Person.name | Person.name | Equivalent | R4B `Person.name` maps as Equivalent to R5 `Person.name` |
| Person.photo | Person.photo | RelatedTo | R4B `Person.photo` maps as RelatedTo to R5 `Person.photo` - photo changed from scalar to array (max cardinality from 1 to *); photo has change due to type change: R4B `photo` `Attachment` maps as RelatedTo for R5 `photo` |
| Person.telecom | Person.telecom | Equivalent | R4B `Person.telecom` maps as Equivalent to R5 `Person.telecom` |
| Person.text | Person.text | Equivalent | R4B `Person.text` maps as Equivalent to R5 `Person.text` |

