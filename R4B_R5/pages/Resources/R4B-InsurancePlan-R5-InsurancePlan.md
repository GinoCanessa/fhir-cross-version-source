Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | InsurancePlan |  | Details of a Health Insurance product/plan provided by an organization. | 80 | 45 |
| Target | InsurancePlan |  | Details of a Health Insurance product/plan provided by an organization. | 73 | 41 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 7 |
Equivalent | 4 |
RelatedTo | 69 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| InsurancePlan | InsurancePlan | Equivalent | R4B `InsurancePlan` maps as Equivalent to R5 `InsurancePlan` |
| InsurancePlan.administeredBy | InsurancePlan.administeredBy | Equivalent | R4B `InsurancePlan.administeredBy` maps as Equivalent to R5 `InsurancePlan.administeredBy` |
| InsurancePlan.alias | InsurancePlan.alias | Equivalent | R4B `InsurancePlan.alias` maps as Equivalent to R5 `InsurancePlan.alias` |
| InsurancePlan.contact | InsurancePlan.contact | SourceIsBroaderThanTarget | R4B `InsurancePlan.contact` maps as SourceIsBroaderThanTarget to R5 `InsurancePlan.contact` - contact has change due to type change: R4B contact BackboneElement has no equivalent or mapped type in R5 contact |
| InsurancePlan.contact.address | - | DoesNotExistInTarget | R4B `InsurancePlan.contact.address` does not appear in the target and has no mapping for `InsurancePlan`. |
| InsurancePlan.contact.extension | - | DoesNotExistInTarget | R4B `InsurancePlan.contact.extension` does not appear in the target and has no mapping for `InsurancePlan`. |
| InsurancePlan.contact.id | - | DoesNotExistInTarget | R4B `InsurancePlan.contact.id` does not appear in the target and has no mapping for `InsurancePlan`. |
| InsurancePlan.contact.modifierExtension | - | DoesNotExistInTarget | R4B `InsurancePlan.contact.modifierExtension` does not appear in the target and has no mapping for `InsurancePlan`. |
| InsurancePlan.contact.name | - | DoesNotExistInTarget | R4B `InsurancePlan.contact.name` does not appear in the target and has no mapping for `InsurancePlan`. |
| InsurancePlan.contact.purpose | - | DoesNotExistInTarget | R4B `InsurancePlan.contact.purpose` does not appear in the target and has no mapping for `InsurancePlan`. |
| InsurancePlan.contact.telecom | - | DoesNotExistInTarget | R4B `InsurancePlan.contact.telecom` does not appear in the target and has no mapping for `InsurancePlan`. |
| InsurancePlan.contained | InsurancePlan.contained | Equivalent | R4B `InsurancePlan.contained` maps as Equivalent to R5 `InsurancePlan.contained` |
| InsurancePlan.coverage | InsurancePlan.coverage | Equivalent | R4B `InsurancePlan.coverage` maps as Equivalent to R5 `InsurancePlan.coverage` |
| InsurancePlan.coverage.benefit | InsurancePlan.coverage.benefit | Equivalent | R4B `InsurancePlan.coverage.benefit` maps as Equivalent to R5 `InsurancePlan.coverage.benefit` |
| InsurancePlan.coverage.benefit.extension | InsurancePlan.coverage.benefit.extension | RelatedTo | R4B `InsurancePlan.coverage.benefit.extension` maps as RelatedTo to R5 `InsurancePlan.coverage.benefit.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| InsurancePlan.coverage.benefit.id | InsurancePlan.coverage.benefit.id | Equivalent | R4B `InsurancePlan.coverage.benefit.id` maps as Equivalent to R5 `InsurancePlan.coverage.benefit.id` |
| InsurancePlan.coverage.benefit.limit | InsurancePlan.coverage.benefit.limit | Equivalent | R4B `InsurancePlan.coverage.benefit.limit` maps as Equivalent to R5 `InsurancePlan.coverage.benefit.limit` |
| InsurancePlan.coverage.benefit.limit.code | InsurancePlan.coverage.benefit.limit.code | Equivalent | R4B `InsurancePlan.coverage.benefit.limit.code` maps as Equivalent to R5 `InsurancePlan.coverage.benefit.limit.code` |
| InsurancePlan.coverage.benefit.limit.extension | InsurancePlan.coverage.benefit.limit.extension | RelatedTo | R4B `InsurancePlan.coverage.benefit.limit.extension` maps as RelatedTo to R5 `InsurancePlan.coverage.benefit.limit.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| InsurancePlan.coverage.benefit.limit.id | InsurancePlan.coverage.benefit.limit.id | Equivalent | R4B `InsurancePlan.coverage.benefit.limit.id` maps as Equivalent to R5 `InsurancePlan.coverage.benefit.limit.id` |
| InsurancePlan.coverage.benefit.limit.modifierExtension | InsurancePlan.coverage.benefit.limit.modifierExtension | RelatedTo | R4B `InsurancePlan.coverage.benefit.limit.modifierExtension` maps as RelatedTo to R5 `InsurancePlan.coverage.benefit.limit.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| InsurancePlan.coverage.benefit.limit.value | InsurancePlan.coverage.benefit.limit.value | Equivalent | R4B `InsurancePlan.coverage.benefit.limit.value` maps as Equivalent to R5 `InsurancePlan.coverage.benefit.limit.value` |
| InsurancePlan.coverage.benefit.modifierExtension | InsurancePlan.coverage.benefit.modifierExtension | RelatedTo | R4B `InsurancePlan.coverage.benefit.modifierExtension` maps as RelatedTo to R5 `InsurancePlan.coverage.benefit.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| InsurancePlan.coverage.benefit.requirement | InsurancePlan.coverage.benefit.requirement | Equivalent | R4B `InsurancePlan.coverage.benefit.requirement` maps as Equivalent to R5 `InsurancePlan.coverage.benefit.requirement` |
| InsurancePlan.coverage.benefit.type | InsurancePlan.coverage.benefit.type | Equivalent | R4B `InsurancePlan.coverage.benefit.type` maps as Equivalent to R5 `InsurancePlan.coverage.benefit.type` |
| InsurancePlan.coverage.extension | InsurancePlan.coverage.extension | RelatedTo | R4B `InsurancePlan.coverage.extension` maps as RelatedTo to R5 `InsurancePlan.coverage.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| InsurancePlan.coverage.id | InsurancePlan.coverage.id | Equivalent | R4B `InsurancePlan.coverage.id` maps as Equivalent to R5 `InsurancePlan.coverage.id` |
| InsurancePlan.coverage.modifierExtension | InsurancePlan.coverage.modifierExtension | RelatedTo | R4B `InsurancePlan.coverage.modifierExtension` maps as RelatedTo to R5 `InsurancePlan.coverage.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| InsurancePlan.coverage.network | InsurancePlan.coverage.network | Equivalent | R4B `InsurancePlan.coverage.network` maps as Equivalent to R5 `InsurancePlan.coverage.network` |
| InsurancePlan.coverage.type | InsurancePlan.coverage.type | Equivalent | R4B `InsurancePlan.coverage.type` maps as Equivalent to R5 `InsurancePlan.coverage.type` |
| InsurancePlan.coverageArea | InsurancePlan.coverageArea | Equivalent | R4B `InsurancePlan.coverageArea` maps as Equivalent to R5 `InsurancePlan.coverageArea` |
| InsurancePlan.endpoint | InsurancePlan.endpoint | Equivalent | R4B `InsurancePlan.endpoint` maps as Equivalent to R5 `InsurancePlan.endpoint` |
| InsurancePlan.extension | InsurancePlan.extension | RelatedTo | R4B `InsurancePlan.extension` maps as RelatedTo to R5 `InsurancePlan.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| InsurancePlan.id | InsurancePlan.id | Equivalent | R4B `InsurancePlan.id` maps as Equivalent to R5 `InsurancePlan.id` |
| InsurancePlan.identifier | InsurancePlan.identifier | Equivalent | R4B `InsurancePlan.identifier` maps as Equivalent to R5 `InsurancePlan.identifier` |
| InsurancePlan.implicitRules | InsurancePlan.implicitRules | Equivalent | R4B `InsurancePlan.implicitRules` maps as Equivalent to R5 `InsurancePlan.implicitRules` |
| InsurancePlan.language | InsurancePlan.language | RelatedTo | R4B `InsurancePlan.language` maps as RelatedTo to R5 `InsurancePlan.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| InsurancePlan.meta | InsurancePlan.meta | Equivalent | R4B `InsurancePlan.meta` maps as Equivalent to R5 `InsurancePlan.meta` |
| InsurancePlan.modifierExtension | InsurancePlan.modifierExtension | RelatedTo | R4B `InsurancePlan.modifierExtension` maps as RelatedTo to R5 `InsurancePlan.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| InsurancePlan.name | InsurancePlan.name | Equivalent | R4B `InsurancePlan.name` maps as Equivalent to R5 `InsurancePlan.name` |
| InsurancePlan.network | InsurancePlan.network | Equivalent | R4B `InsurancePlan.network` maps as Equivalent to R5 `InsurancePlan.network` |
| InsurancePlan.ownedBy | InsurancePlan.ownedBy | Equivalent | R4B `InsurancePlan.ownedBy` maps as Equivalent to R5 `InsurancePlan.ownedBy` |
| InsurancePlan.period | InsurancePlan.period | Equivalent | R4B `InsurancePlan.period` maps as Equivalent to R5 `InsurancePlan.period` |
| InsurancePlan.plan | InsurancePlan.plan | Equivalent | R4B `InsurancePlan.plan` maps as Equivalent to R5 `InsurancePlan.plan` |
| InsurancePlan.plan.coverageArea | InsurancePlan.plan.coverageArea | Equivalent | R4B `InsurancePlan.plan.coverageArea` maps as Equivalent to R5 `InsurancePlan.plan.coverageArea` |
| InsurancePlan.plan.extension | InsurancePlan.plan.extension | RelatedTo | R4B `InsurancePlan.plan.extension` maps as RelatedTo to R5 `InsurancePlan.plan.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| InsurancePlan.plan.generalCost | InsurancePlan.plan.generalCost | Equivalent | R4B `InsurancePlan.plan.generalCost` maps as Equivalent to R5 `InsurancePlan.plan.generalCost` |
| InsurancePlan.plan.generalCost.comment | InsurancePlan.plan.generalCost.comment | Equivalent | R4B `InsurancePlan.plan.generalCost.comment` maps as Equivalent to R5 `InsurancePlan.plan.generalCost.comment` |
| InsurancePlan.plan.generalCost.cost | InsurancePlan.plan.generalCost.cost | RelatedTo | R4B `InsurancePlan.plan.generalCost.cost` maps as RelatedTo to R5 `InsurancePlan.plan.generalCost.cost` - cost has change due to type change: R4B `cost` `Money` maps as RelatedTo for R5 `cost` |
| InsurancePlan.plan.generalCost.extension | InsurancePlan.plan.generalCost.extension | RelatedTo | R4B `InsurancePlan.plan.generalCost.extension` maps as RelatedTo to R5 `InsurancePlan.plan.generalCost.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| InsurancePlan.plan.generalCost.groupSize | InsurancePlan.plan.generalCost.groupSize | Equivalent | R4B `InsurancePlan.plan.generalCost.groupSize` maps as Equivalent to R5 `InsurancePlan.plan.generalCost.groupSize` |
| InsurancePlan.plan.generalCost.id | InsurancePlan.plan.generalCost.id | Equivalent | R4B `InsurancePlan.plan.generalCost.id` maps as Equivalent to R5 `InsurancePlan.plan.generalCost.id` |
| InsurancePlan.plan.generalCost.modifierExtension | InsurancePlan.plan.generalCost.modifierExtension | RelatedTo | R4B `InsurancePlan.plan.generalCost.modifierExtension` maps as RelatedTo to R5 `InsurancePlan.plan.generalCost.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| InsurancePlan.plan.generalCost.type | InsurancePlan.plan.generalCost.type | Equivalent | R4B `InsurancePlan.plan.generalCost.type` maps as Equivalent to R5 `InsurancePlan.plan.generalCost.type` |
| InsurancePlan.plan.id | InsurancePlan.plan.id | Equivalent | R4B `InsurancePlan.plan.id` maps as Equivalent to R5 `InsurancePlan.plan.id` |
| InsurancePlan.plan.identifier | InsurancePlan.plan.identifier | Equivalent | R4B `InsurancePlan.plan.identifier` maps as Equivalent to R5 `InsurancePlan.plan.identifier` |
| InsurancePlan.plan.modifierExtension | InsurancePlan.plan.modifierExtension | RelatedTo | R4B `InsurancePlan.plan.modifierExtension` maps as RelatedTo to R5 `InsurancePlan.plan.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| InsurancePlan.plan.network | InsurancePlan.plan.network | Equivalent | R4B `InsurancePlan.plan.network` maps as Equivalent to R5 `InsurancePlan.plan.network` |
| InsurancePlan.plan.specificCost | InsurancePlan.plan.specificCost | Equivalent | R4B `InsurancePlan.plan.specificCost` maps as Equivalent to R5 `InsurancePlan.plan.specificCost` |
| InsurancePlan.plan.specificCost.benefit | InsurancePlan.plan.specificCost.benefit | Equivalent | R4B `InsurancePlan.plan.specificCost.benefit` maps as Equivalent to R5 `InsurancePlan.plan.specificCost.benefit` |
| InsurancePlan.plan.specificCost.benefit.cost | InsurancePlan.plan.specificCost.benefit.cost | Equivalent | R4B `InsurancePlan.plan.specificCost.benefit.cost` maps as Equivalent to R5 `InsurancePlan.plan.specificCost.benefit.cost` |
| InsurancePlan.plan.specificCost.benefit.cost.applicability | InsurancePlan.plan.specificCost.benefit.cost.applicability | Equivalent | R4B `InsurancePlan.plan.specificCost.benefit.cost.applicability` maps as Equivalent to R5 `InsurancePlan.plan.specificCost.benefit.cost.applicability` - applicability has compatible required binding for non-code type: http://hl7.org/fhir/ValueSet/insuranceplan-applicability|4.3.0 and http://hl7.org/fhir/ValueSet/insuranceplan-applicability|5.0.0 (Equivalent) |
| InsurancePlan.plan.specificCost.benefit.cost.extension | InsurancePlan.plan.specificCost.benefit.cost.extension | RelatedTo | R4B `InsurancePlan.plan.specificCost.benefit.cost.extension` maps as RelatedTo to R5 `InsurancePlan.plan.specificCost.benefit.cost.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| InsurancePlan.plan.specificCost.benefit.cost.id | InsurancePlan.plan.specificCost.benefit.cost.id | Equivalent | R4B `InsurancePlan.plan.specificCost.benefit.cost.id` maps as Equivalent to R5 `InsurancePlan.plan.specificCost.benefit.cost.id` |
| InsurancePlan.plan.specificCost.benefit.cost.modifierExtension | InsurancePlan.plan.specificCost.benefit.cost.modifierExtension | RelatedTo | R4B `InsurancePlan.plan.specificCost.benefit.cost.modifierExtension` maps as RelatedTo to R5 `InsurancePlan.plan.specificCost.benefit.cost.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| InsurancePlan.plan.specificCost.benefit.cost.qualifiers | InsurancePlan.plan.specificCost.benefit.cost.qualifiers | Equivalent | R4B `InsurancePlan.plan.specificCost.benefit.cost.qualifiers` maps as Equivalent to R5 `InsurancePlan.plan.specificCost.benefit.cost.qualifiers` |
| InsurancePlan.plan.specificCost.benefit.cost.type | InsurancePlan.plan.specificCost.benefit.cost.type | Equivalent | R4B `InsurancePlan.plan.specificCost.benefit.cost.type` maps as Equivalent to R5 `InsurancePlan.plan.specificCost.benefit.cost.type` |
| InsurancePlan.plan.specificCost.benefit.cost.value | InsurancePlan.plan.specificCost.benefit.cost.value | Equivalent | R4B `InsurancePlan.plan.specificCost.benefit.cost.value` maps as Equivalent to R5 `InsurancePlan.plan.specificCost.benefit.cost.value` |
| InsurancePlan.plan.specificCost.benefit.extension | InsurancePlan.plan.specificCost.benefit.extension | RelatedTo | R4B `InsurancePlan.plan.specificCost.benefit.extension` maps as RelatedTo to R5 `InsurancePlan.plan.specificCost.benefit.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| InsurancePlan.plan.specificCost.benefit.id | InsurancePlan.plan.specificCost.benefit.id | Equivalent | R4B `InsurancePlan.plan.specificCost.benefit.id` maps as Equivalent to R5 `InsurancePlan.plan.specificCost.benefit.id` |
| InsurancePlan.plan.specificCost.benefit.modifierExtension | InsurancePlan.plan.specificCost.benefit.modifierExtension | RelatedTo | R4B `InsurancePlan.plan.specificCost.benefit.modifierExtension` maps as RelatedTo to R5 `InsurancePlan.plan.specificCost.benefit.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| InsurancePlan.plan.specificCost.benefit.type | InsurancePlan.plan.specificCost.benefit.type | Equivalent | R4B `InsurancePlan.plan.specificCost.benefit.type` maps as Equivalent to R5 `InsurancePlan.plan.specificCost.benefit.type` |
| InsurancePlan.plan.specificCost.category | InsurancePlan.plan.specificCost.category | Equivalent | R4B `InsurancePlan.plan.specificCost.category` maps as Equivalent to R5 `InsurancePlan.plan.specificCost.category` |
| InsurancePlan.plan.specificCost.extension | InsurancePlan.plan.specificCost.extension | RelatedTo | R4B `InsurancePlan.plan.specificCost.extension` maps as RelatedTo to R5 `InsurancePlan.plan.specificCost.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| InsurancePlan.plan.specificCost.id | InsurancePlan.plan.specificCost.id | Equivalent | R4B `InsurancePlan.plan.specificCost.id` maps as Equivalent to R5 `InsurancePlan.plan.specificCost.id` |
| InsurancePlan.plan.specificCost.modifierExtension | InsurancePlan.plan.specificCost.modifierExtension | RelatedTo | R4B `InsurancePlan.plan.specificCost.modifierExtension` maps as RelatedTo to R5 `InsurancePlan.plan.specificCost.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| InsurancePlan.plan.type | InsurancePlan.plan.type | Equivalent | R4B `InsurancePlan.plan.type` maps as Equivalent to R5 `InsurancePlan.plan.type` |
| InsurancePlan.status | InsurancePlan.status | Equivalent | R4B `InsurancePlan.status` maps as Equivalent to R5 `InsurancePlan.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|4.3.0 and http://hl7.org/fhir/ValueSet/publication-status|5.0.0 (Equivalent) |
| InsurancePlan.text | InsurancePlan.text | Equivalent | R4B `InsurancePlan.text` maps as Equivalent to R5 `InsurancePlan.text` |
| InsurancePlan.type | InsurancePlan.type | Equivalent | R4B `InsurancePlan.type` maps as Equivalent to R5 `InsurancePlan.type` |

