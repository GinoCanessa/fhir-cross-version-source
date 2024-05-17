Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Organization |  | A formally or informally recognized grouping of people or organizations formed for the purpose of achieving some form of collective action.  Includes companies, institutions, corporations, departments, community groups, healthcare practice groups, payer/insurer, etc. | 26 | 15 |
| Target | Organization |  | A formally or informally recognized grouping of people or organizations formed for the purpose of achieving some form of collective action.  Includes companies, institutions, corporations, departments, community groups, healthcare practice groups, payer/insurer, etc. | 26 | 15 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 9 |
Equivalent | 4 |
RelatedTo | 13 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Organization | Organization | Equivalent | R4B `Organization` maps as Equivalent to R5 `Organization` |
| Organization.active | Organization.active | Equivalent | R4B `Organization.active` maps as Equivalent to R5 `Organization.active` |
| Organization.address | - | DoesNotExistInTarget | R4B `Organization.address` does not appear in the target and has no mapping for `Organization`. |
| Organization.alias | Organization.alias | Equivalent | R4B `Organization.alias` maps as Equivalent to R5 `Organization.alias` |
| Organization.contact | Organization.contact | SourceIsBroaderThanTarget | R4B `Organization.contact` maps as SourceIsBroaderThanTarget to R5 `Organization.contact` - contact has change due to type change: R4B contact BackboneElement has no equivalent or mapped type in R5 contact |
| Organization.contact.address | - | DoesNotExistInTarget | R4B `Organization.contact.address` does not appear in the target and has no mapping for `Organization`. |
| Organization.contact.extension | - | DoesNotExistInTarget | R4B `Organization.contact.extension` does not appear in the target and has no mapping for `Organization`. |
| Organization.contact.id | - | DoesNotExistInTarget | R4B `Organization.contact.id` does not appear in the target and has no mapping for `Organization`. |
| Organization.contact.modifierExtension | - | DoesNotExistInTarget | R4B `Organization.contact.modifierExtension` does not appear in the target and has no mapping for `Organization`. |
| Organization.contact.name | - | DoesNotExistInTarget | R4B `Organization.contact.name` does not appear in the target and has no mapping for `Organization`. |
| Organization.contact.purpose | - | DoesNotExistInTarget | R4B `Organization.contact.purpose` does not appear in the target and has no mapping for `Organization`. |
| Organization.contact.telecom | - | DoesNotExistInTarget | R4B `Organization.contact.telecom` does not appear in the target and has no mapping for `Organization`. |
| Organization.contained | Organization.contained | Equivalent | R4B `Organization.contained` maps as Equivalent to R5 `Organization.contained` |
| Organization.endpoint | Organization.endpoint | Equivalent | R4B `Organization.endpoint` maps as Equivalent to R5 `Organization.endpoint` |
| Organization.extension | Organization.extension | RelatedTo | R4B `Organization.extension` maps as RelatedTo to R5 `Organization.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Organization.id | Organization.id | Equivalent | R4B `Organization.id` maps as Equivalent to R5 `Organization.id` |
| Organization.identifier | Organization.identifier | Equivalent | R4B `Organization.identifier` maps as Equivalent to R5 `Organization.identifier` |
| Organization.implicitRules | Organization.implicitRules | Equivalent | R4B `Organization.implicitRules` maps as Equivalent to R5 `Organization.implicitRules` |
| Organization.language | Organization.language | RelatedTo | R4B `Organization.language` maps as RelatedTo to R5 `Organization.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Organization.meta | Organization.meta | Equivalent | R4B `Organization.meta` maps as Equivalent to R5 `Organization.meta` |
| Organization.modifierExtension | Organization.modifierExtension | RelatedTo | R4B `Organization.modifierExtension` maps as RelatedTo to R5 `Organization.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Organization.name | Organization.name | Equivalent | R4B `Organization.name` maps as Equivalent to R5 `Organization.name` |
| Organization.partOf | Organization.partOf | Equivalent | R4B `Organization.partOf` maps as Equivalent to R5 `Organization.partOf` |
| Organization.telecom | - | DoesNotExistInTarget | R4B `Organization.telecom` does not appear in the target and has no mapping for `Organization`. |
| Organization.text | Organization.text | Equivalent | R4B `Organization.text` maps as Equivalent to R5 `Organization.text` |
| Organization.type | Organization.type | Equivalent | R4B `Organization.type` maps as Equivalent to R5 `Organization.type` |

