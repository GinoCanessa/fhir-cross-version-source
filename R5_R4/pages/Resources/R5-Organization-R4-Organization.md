Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1
Generated at Thursday, July 25, 2024 3:56:51 PM

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
| Organization | Organization | Equivalent | R5 `Organization` maps as Equivalent to R4 `Organization` |
| Organization.active | Organization.active | Equivalent | R5 `Organization.active` maps as Equivalent to R4 `Organization.active` |
| Organization.alias | Organization.alias | Equivalent | R5 `Organization.alias` maps as Equivalent to R4 `Organization.alias` |
| Organization.contact | Organization.contact | SourceIsBroaderThanTarget | R5 `Organization.contact` maps as SourceIsBroaderThanTarget to R4 `Organization.contact` - contact has change due to type change: R5 contact ExtendedContactDetail has no equivalent or mapped type in R4 contact |
| Organization.contained | Organization.contained | Equivalent | R5 `Organization.contained` maps as Equivalent to R4 `Organization.contained` |
| Organization.description | - | DoesNotExistInTarget | R5 `Organization.description` does not appear in the target and has no mapping for `Organization`. |
| Organization.endpoint | Organization.endpoint | Equivalent | R5 `Organization.endpoint` maps as Equivalent to R4 `Organization.endpoint` |
| Organization.extension | Organization.extension | SourceIsBroaderThanTarget | R5 `Organization.extension` maps as SourceIsBroaderThanTarget to R4 `Organization.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Organization.id | Organization.id | Equivalent | R5 `Organization.id` maps as Equivalent to R4 `Organization.id` |
| Organization.identifier | Organization.identifier | Equivalent | R5 `Organization.identifier` maps as Equivalent to R4 `Organization.identifier` |
| Organization.implicitRules | Organization.implicitRules | Equivalent | R5 `Organization.implicitRules` maps as Equivalent to R4 `Organization.implicitRules` |
| Organization.language | Organization.language | RelatedTo | R5 `Organization.language` maps as RelatedTo to R4 `Organization.language` - language changed the binding strength from Required to Preferred |
| Organization.meta | Organization.meta | Equivalent | R5 `Organization.meta` maps as Equivalent to R4 `Organization.meta` |
| Organization.modifierExtension | Organization.modifierExtension | SourceIsBroaderThanTarget | R5 `Organization.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Organization.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Organization.name | Organization.name | Equivalent | R5 `Organization.name` maps as Equivalent to R4 `Organization.name` |
| Organization.partOf | Organization.partOf | Equivalent | R5 `Organization.partOf` maps as Equivalent to R4 `Organization.partOf` |
| Organization.qualification | - | DoesNotExistInTarget | R5 `Organization.qualification` does not appear in the target and has no mapping for `Organization`. |
| Organization.qualification.code | - | DoesNotExistInTarget | R5 `Organization.qualification.code` does not appear in the target and has no mapping for `Organization`. |
| Organization.qualification.extension | - | DoesNotExistInTarget | R5 `Organization.qualification.extension` does not appear in the target and has no mapping for `Organization`. |
| Organization.qualification.id | - | DoesNotExistInTarget | R5 `Organization.qualification.id` does not appear in the target and has no mapping for `Organization`. |
| Organization.qualification.identifier | - | DoesNotExistInTarget | R5 `Organization.qualification.identifier` does not appear in the target and has no mapping for `Organization`. |
| Organization.qualification.issuer | - | DoesNotExistInTarget | R5 `Organization.qualification.issuer` does not appear in the target and has no mapping for `Organization`. |
| Organization.qualification.modifierExtension | - | DoesNotExistInTarget | R5 `Organization.qualification.modifierExtension` does not appear in the target and has no mapping for `Organization`. |
| Organization.qualification.period | - | DoesNotExistInTarget | R5 `Organization.qualification.period` does not appear in the target and has no mapping for `Organization`. |
| Organization.text | Organization.text | Equivalent | R5 `Organization.text` maps as Equivalent to R4 `Organization.text` |
| Organization.type | Organization.type | Equivalent | R5 `Organization.type` maps as Equivalent to R4 `Organization.type` |

