Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | OrganizationAffiliation |  | Defines an affiliation/assotiation/relationship between 2 distinct organizations, that is not a part-of relationship/sub-division relationship. | 21 | 13 |
| Target | OrganizationAffiliation |  | Defines an affiliation/assotiation/relationship between 2 distinct oganizations, that is not a part-of relationship/sub-division relationship. | 21 | 13 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 1 |
Equivalent | 4 |
RelatedTo | 16 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| OrganizationAffiliation | OrganizationAffiliation | Equivalent | R5 `OrganizationAffiliation` maps as Equivalent to R4 `OrganizationAffiliation` |
| OrganizationAffiliation.active | OrganizationAffiliation.active | Equivalent | R5 `OrganizationAffiliation.active` maps as Equivalent to R4 `OrganizationAffiliation.active` |
| OrganizationAffiliation.code | OrganizationAffiliation.code | Equivalent | R5 `OrganizationAffiliation.code` maps as Equivalent to R4 `OrganizationAffiliation.code` |
| OrganizationAffiliation.contact | - | DoesNotExistInTarget | R5 `OrganizationAffiliation.contact` does not appear in the target and has no mapping for `OrganizationAffiliation`. |
| OrganizationAffiliation.contained | OrganizationAffiliation.contained | Equivalent | R5 `OrganizationAffiliation.contained` maps as Equivalent to R4 `OrganizationAffiliation.contained` |
| OrganizationAffiliation.endpoint | OrganizationAffiliation.endpoint | Equivalent | R5 `OrganizationAffiliation.endpoint` maps as Equivalent to R4 `OrganizationAffiliation.endpoint` |
| OrganizationAffiliation.extension | OrganizationAffiliation.extension | SourceIsBroaderThanTarget | R5 `OrganizationAffiliation.extension` maps as SourceIsBroaderThanTarget to R4 `OrganizationAffiliation.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| OrganizationAffiliation.healthcareService | OrganizationAffiliation.healthcareService | Equivalent | R5 `OrganizationAffiliation.healthcareService` maps as Equivalent to R4 `OrganizationAffiliation.healthcareService` |
| OrganizationAffiliation.id | OrganizationAffiliation.id | Equivalent | R5 `OrganizationAffiliation.id` maps as Equivalent to R4 `OrganizationAffiliation.id` |
| OrganizationAffiliation.identifier | OrganizationAffiliation.identifier | Equivalent | R5 `OrganizationAffiliation.identifier` maps as Equivalent to R4 `OrganizationAffiliation.identifier` |
| OrganizationAffiliation.implicitRules | OrganizationAffiliation.implicitRules | Equivalent | R5 `OrganizationAffiliation.implicitRules` maps as Equivalent to R4 `OrganizationAffiliation.implicitRules` |
| OrganizationAffiliation.language | OrganizationAffiliation.language | RelatedTo | R5 `OrganizationAffiliation.language` maps as RelatedTo to R4 `OrganizationAffiliation.language` - language changed the binding strength from Required to Preferred |
| OrganizationAffiliation.location | OrganizationAffiliation.location | Equivalent | R5 `OrganizationAffiliation.location` maps as Equivalent to R4 `OrganizationAffiliation.location` |
| OrganizationAffiliation.meta | OrganizationAffiliation.meta | Equivalent | R5 `OrganizationAffiliation.meta` maps as Equivalent to R4 `OrganizationAffiliation.meta` |
| OrganizationAffiliation.modifierExtension | OrganizationAffiliation.modifierExtension | SourceIsBroaderThanTarget | R5 `OrganizationAffiliation.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `OrganizationAffiliation.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| OrganizationAffiliation.network | OrganizationAffiliation.network | Equivalent | R5 `OrganizationAffiliation.network` maps as Equivalent to R4 `OrganizationAffiliation.network` |
| OrganizationAffiliation.organization | OrganizationAffiliation.organization | Equivalent | R5 `OrganizationAffiliation.organization` maps as Equivalent to R4 `OrganizationAffiliation.organization` |
| OrganizationAffiliation.participatingOrganization | OrganizationAffiliation.participatingOrganization | Equivalent | R5 `OrganizationAffiliation.participatingOrganization` maps as Equivalent to R4 `OrganizationAffiliation.participatingOrganization` |
| OrganizationAffiliation.period | OrganizationAffiliation.period | Equivalent | R5 `OrganizationAffiliation.period` maps as Equivalent to R4 `OrganizationAffiliation.period` |
| OrganizationAffiliation.specialty | OrganizationAffiliation.specialty | Equivalent | R5 `OrganizationAffiliation.specialty` maps as Equivalent to R4 `OrganizationAffiliation.specialty` |
| OrganizationAffiliation.text | OrganizationAffiliation.text | Equivalent | R5 `OrganizationAffiliation.text` maps as Equivalent to R4 `OrganizationAffiliation.text` |

