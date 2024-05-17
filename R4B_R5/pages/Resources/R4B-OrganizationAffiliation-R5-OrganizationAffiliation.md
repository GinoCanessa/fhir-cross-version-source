Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | OrganizationAffiliation |  | Defines an affiliation/assotiation/relationship between 2 distinct oganizations, that is not a part-of relationship/sub-division relationship. | 21 | 13 |
| Target | OrganizationAffiliation |  | Defines an affiliation/assotiation/relationship between 2 distinct organizations, that is not a part-of relationship/sub-division relationship. | 21 | 13 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 1 |
Equivalent | 4 |
RelatedTo | 16 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| OrganizationAffiliation | OrganizationAffiliation | Equivalent | R4B `OrganizationAffiliation` maps as Equivalent to R5 `OrganizationAffiliation` |
| OrganizationAffiliation.active | OrganizationAffiliation.active | Equivalent | R4B `OrganizationAffiliation.active` maps as Equivalent to R5 `OrganizationAffiliation.active` |
| OrganizationAffiliation.code | OrganizationAffiliation.code | Equivalent | R4B `OrganizationAffiliation.code` maps as Equivalent to R5 `OrganizationAffiliation.code` |
| OrganizationAffiliation.contained | OrganizationAffiliation.contained | Equivalent | R4B `OrganizationAffiliation.contained` maps as Equivalent to R5 `OrganizationAffiliation.contained` |
| OrganizationAffiliation.endpoint | OrganizationAffiliation.endpoint | Equivalent | R4B `OrganizationAffiliation.endpoint` maps as Equivalent to R5 `OrganizationAffiliation.endpoint` |
| OrganizationAffiliation.extension | OrganizationAffiliation.extension | RelatedTo | R4B `OrganizationAffiliation.extension` maps as RelatedTo to R5 `OrganizationAffiliation.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| OrganizationAffiliation.healthcareService | OrganizationAffiliation.healthcareService | Equivalent | R4B `OrganizationAffiliation.healthcareService` maps as Equivalent to R5 `OrganizationAffiliation.healthcareService` |
| OrganizationAffiliation.id | OrganizationAffiliation.id | Equivalent | R4B `OrganizationAffiliation.id` maps as Equivalent to R5 `OrganizationAffiliation.id` |
| OrganizationAffiliation.identifier | OrganizationAffiliation.identifier | Equivalent | R4B `OrganizationAffiliation.identifier` maps as Equivalent to R5 `OrganizationAffiliation.identifier` |
| OrganizationAffiliation.implicitRules | OrganizationAffiliation.implicitRules | Equivalent | R4B `OrganizationAffiliation.implicitRules` maps as Equivalent to R5 `OrganizationAffiliation.implicitRules` |
| OrganizationAffiliation.language | OrganizationAffiliation.language | RelatedTo | R4B `OrganizationAffiliation.language` maps as RelatedTo to R5 `OrganizationAffiliation.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| OrganizationAffiliation.location | OrganizationAffiliation.location | Equivalent | R4B `OrganizationAffiliation.location` maps as Equivalent to R5 `OrganizationAffiliation.location` |
| OrganizationAffiliation.meta | OrganizationAffiliation.meta | Equivalent | R4B `OrganizationAffiliation.meta` maps as Equivalent to R5 `OrganizationAffiliation.meta` |
| OrganizationAffiliation.modifierExtension | OrganizationAffiliation.modifierExtension | RelatedTo | R4B `OrganizationAffiliation.modifierExtension` maps as RelatedTo to R5 `OrganizationAffiliation.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| OrganizationAffiliation.network | OrganizationAffiliation.network | Equivalent | R4B `OrganizationAffiliation.network` maps as Equivalent to R5 `OrganizationAffiliation.network` |
| OrganizationAffiliation.organization | OrganizationAffiliation.organization | Equivalent | R4B `OrganizationAffiliation.organization` maps as Equivalent to R5 `OrganizationAffiliation.organization` |
| OrganizationAffiliation.participatingOrganization | OrganizationAffiliation.participatingOrganization | Equivalent | R4B `OrganizationAffiliation.participatingOrganization` maps as Equivalent to R5 `OrganizationAffiliation.participatingOrganization` |
| OrganizationAffiliation.period | OrganizationAffiliation.period | Equivalent | R4B `OrganizationAffiliation.period` maps as Equivalent to R5 `OrganizationAffiliation.period` |
| OrganizationAffiliation.specialty | OrganizationAffiliation.specialty | Equivalent | R4B `OrganizationAffiliation.specialty` maps as Equivalent to R5 `OrganizationAffiliation.specialty` |
| OrganizationAffiliation.telecom | - | DoesNotExistInTarget | R4B `OrganizationAffiliation.telecom` does not appear in the target and has no mapping for `OrganizationAffiliation`. |
| OrganizationAffiliation.text | OrganizationAffiliation.text | Equivalent | R4B `OrganizationAffiliation.text` maps as Equivalent to R5 `OrganizationAffiliation.text` |

