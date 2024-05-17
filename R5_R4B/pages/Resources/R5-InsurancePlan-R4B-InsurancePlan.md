Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | InsurancePlan |  | Details of a Health Insurance product/plan provided by an organization. | 73 | 41 |
| Target | InsurancePlan |  | Details of a Health Insurance product/plan provided by an organization. | 80 | 45 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 69 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| InsurancePlan | InsurancePlan | Equivalent | R5 `InsurancePlan` maps as Equivalent to R4B `InsurancePlan` |
| InsurancePlan.administeredBy | InsurancePlan.administeredBy | Equivalent | R5 `InsurancePlan.administeredBy` maps as Equivalent to R4B `InsurancePlan.administeredBy` |
| InsurancePlan.alias | InsurancePlan.alias | Equivalent | R5 `InsurancePlan.alias` maps as Equivalent to R4B `InsurancePlan.alias` |
| InsurancePlan.contact | InsurancePlan.contact | SourceIsBroaderThanTarget | R5 `InsurancePlan.contact` maps as SourceIsBroaderThanTarget to R4B `InsurancePlan.contact` - contact has change due to type change: R5 type ExtendedContactDetail does not exist in R4B |
| InsurancePlan.contained | InsurancePlan.contained | Equivalent | R5 `InsurancePlan.contained` maps as Equivalent to R4B `InsurancePlan.contained` |
| InsurancePlan.coverage | InsurancePlan.coverage | Equivalent | R5 `InsurancePlan.coverage` maps as Equivalent to R4B `InsurancePlan.coverage` |
| InsurancePlan.coverage.benefit | InsurancePlan.coverage.benefit | Equivalent | R5 `InsurancePlan.coverage.benefit` maps as Equivalent to R4B `InsurancePlan.coverage.benefit` |
| InsurancePlan.coverage.benefit.extension | InsurancePlan.coverage.benefit.extension | SourceIsBroaderThanTarget | R5 `InsurancePlan.coverage.benefit.extension` maps as SourceIsBroaderThanTarget to R4B `InsurancePlan.coverage.benefit.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| InsurancePlan.coverage.benefit.id | InsurancePlan.coverage.benefit.id | Equivalent | R5 `InsurancePlan.coverage.benefit.id` maps as Equivalent to R4B `InsurancePlan.coverage.benefit.id` |
| InsurancePlan.coverage.benefit.limit | InsurancePlan.coverage.benefit.limit | Equivalent | R5 `InsurancePlan.coverage.benefit.limit` maps as Equivalent to R4B `InsurancePlan.coverage.benefit.limit` |
| InsurancePlan.coverage.benefit.limit.code | InsurancePlan.coverage.benefit.limit.code | Equivalent | R5 `InsurancePlan.coverage.benefit.limit.code` maps as Equivalent to R4B `InsurancePlan.coverage.benefit.limit.code` |
| InsurancePlan.coverage.benefit.limit.extension | InsurancePlan.coverage.benefit.limit.extension | SourceIsBroaderThanTarget | R5 `InsurancePlan.coverage.benefit.limit.extension` maps as SourceIsBroaderThanTarget to R4B `InsurancePlan.coverage.benefit.limit.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| InsurancePlan.coverage.benefit.limit.id | InsurancePlan.coverage.benefit.limit.id | Equivalent | R5 `InsurancePlan.coverage.benefit.limit.id` maps as Equivalent to R4B `InsurancePlan.coverage.benefit.limit.id` |
| InsurancePlan.coverage.benefit.limit.modifierExtension | InsurancePlan.coverage.benefit.limit.modifierExtension | SourceIsBroaderThanTarget | R5 `InsurancePlan.coverage.benefit.limit.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `InsurancePlan.coverage.benefit.limit.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| InsurancePlan.coverage.benefit.limit.value | InsurancePlan.coverage.benefit.limit.value | Equivalent | R5 `InsurancePlan.coverage.benefit.limit.value` maps as Equivalent to R4B `InsurancePlan.coverage.benefit.limit.value` |
| InsurancePlan.coverage.benefit.modifierExtension | InsurancePlan.coverage.benefit.modifierExtension | SourceIsBroaderThanTarget | R5 `InsurancePlan.coverage.benefit.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `InsurancePlan.coverage.benefit.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| InsurancePlan.coverage.benefit.requirement | InsurancePlan.coverage.benefit.requirement | Equivalent | R5 `InsurancePlan.coverage.benefit.requirement` maps as Equivalent to R4B `InsurancePlan.coverage.benefit.requirement` |
| InsurancePlan.coverage.benefit.type | InsurancePlan.coverage.benefit.type | Equivalent | R5 `InsurancePlan.coverage.benefit.type` maps as Equivalent to R4B `InsurancePlan.coverage.benefit.type` |
| InsurancePlan.coverage.extension | InsurancePlan.coverage.extension | SourceIsBroaderThanTarget | R5 `InsurancePlan.coverage.extension` maps as SourceIsBroaderThanTarget to R4B `InsurancePlan.coverage.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| InsurancePlan.coverage.id | InsurancePlan.coverage.id | Equivalent | R5 `InsurancePlan.coverage.id` maps as Equivalent to R4B `InsurancePlan.coverage.id` |
| InsurancePlan.coverage.modifierExtension | InsurancePlan.coverage.modifierExtension | SourceIsBroaderThanTarget | R5 `InsurancePlan.coverage.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `InsurancePlan.coverage.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| InsurancePlan.coverage.network | InsurancePlan.coverage.network | Equivalent | R5 `InsurancePlan.coverage.network` maps as Equivalent to R4B `InsurancePlan.coverage.network` |
| InsurancePlan.coverage.type | InsurancePlan.coverage.type | Equivalent | R5 `InsurancePlan.coverage.type` maps as Equivalent to R4B `InsurancePlan.coverage.type` |
| InsurancePlan.coverageArea | InsurancePlan.coverageArea | Equivalent | R5 `InsurancePlan.coverageArea` maps as Equivalent to R4B `InsurancePlan.coverageArea` |
| InsurancePlan.endpoint | InsurancePlan.endpoint | Equivalent | R5 `InsurancePlan.endpoint` maps as Equivalent to R4B `InsurancePlan.endpoint` |
| InsurancePlan.extension | InsurancePlan.extension | SourceIsBroaderThanTarget | R5 `InsurancePlan.extension` maps as SourceIsBroaderThanTarget to R4B `InsurancePlan.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| InsurancePlan.id | InsurancePlan.id | Equivalent | R5 `InsurancePlan.id` maps as Equivalent to R4B `InsurancePlan.id` |
| InsurancePlan.identifier | InsurancePlan.identifier | Equivalent | R5 `InsurancePlan.identifier` maps as Equivalent to R4B `InsurancePlan.identifier` |
| InsurancePlan.implicitRules | InsurancePlan.implicitRules | Equivalent | R5 `InsurancePlan.implicitRules` maps as Equivalent to R4B `InsurancePlan.implicitRules` |
| InsurancePlan.language | InsurancePlan.language | RelatedTo | R5 `InsurancePlan.language` maps as RelatedTo to R4B `InsurancePlan.language` - language changed the binding strength from Required to Preferred |
| InsurancePlan.meta | InsurancePlan.meta | Equivalent | R5 `InsurancePlan.meta` maps as Equivalent to R4B `InsurancePlan.meta` |
| InsurancePlan.modifierExtension | InsurancePlan.modifierExtension | SourceIsBroaderThanTarget | R5 `InsurancePlan.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `InsurancePlan.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| InsurancePlan.name | InsurancePlan.name | Equivalent | R5 `InsurancePlan.name` maps as Equivalent to R4B `InsurancePlan.name` |
| InsurancePlan.network | InsurancePlan.network | Equivalent | R5 `InsurancePlan.network` maps as Equivalent to R4B `InsurancePlan.network` |
| InsurancePlan.ownedBy | InsurancePlan.ownedBy | Equivalent | R5 `InsurancePlan.ownedBy` maps as Equivalent to R4B `InsurancePlan.ownedBy` |
| InsurancePlan.period | InsurancePlan.period | Equivalent | R5 `InsurancePlan.period` maps as Equivalent to R4B `InsurancePlan.period` |
| InsurancePlan.plan | InsurancePlan.plan | Equivalent | R5 `InsurancePlan.plan` maps as Equivalent to R4B `InsurancePlan.plan` |
| InsurancePlan.plan.coverageArea | InsurancePlan.plan.coverageArea | Equivalent | R5 `InsurancePlan.plan.coverageArea` maps as Equivalent to R4B `InsurancePlan.plan.coverageArea` |
| InsurancePlan.plan.extension | InsurancePlan.plan.extension | SourceIsBroaderThanTarget | R5 `InsurancePlan.plan.extension` maps as SourceIsBroaderThanTarget to R4B `InsurancePlan.plan.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| InsurancePlan.plan.generalCost | InsurancePlan.plan.generalCost | Equivalent | R5 `InsurancePlan.plan.generalCost` maps as Equivalent to R4B `InsurancePlan.plan.generalCost` |
| InsurancePlan.plan.generalCost.comment | InsurancePlan.plan.generalCost.comment | Equivalent | R5 `InsurancePlan.plan.generalCost.comment` maps as Equivalent to R4B `InsurancePlan.plan.generalCost.comment` |
| InsurancePlan.plan.generalCost.cost | InsurancePlan.plan.generalCost.cost | RelatedTo | R5 `InsurancePlan.plan.generalCost.cost` maps as RelatedTo to R4B `InsurancePlan.plan.generalCost.cost` - cost has change due to type change: R5 `cost` `Money` maps as RelatedTo for R4B `cost` |
| InsurancePlan.plan.generalCost.extension | InsurancePlan.plan.generalCost.extension | SourceIsBroaderThanTarget | R5 `InsurancePlan.plan.generalCost.extension` maps as SourceIsBroaderThanTarget to R4B `InsurancePlan.plan.generalCost.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| InsurancePlan.plan.generalCost.groupSize | InsurancePlan.plan.generalCost.groupSize | Equivalent | R5 `InsurancePlan.plan.generalCost.groupSize` maps as Equivalent to R4B `InsurancePlan.plan.generalCost.groupSize` |
| InsurancePlan.plan.generalCost.id | InsurancePlan.plan.generalCost.id | Equivalent | R5 `InsurancePlan.plan.generalCost.id` maps as Equivalent to R4B `InsurancePlan.plan.generalCost.id` |
| InsurancePlan.plan.generalCost.modifierExtension | InsurancePlan.plan.generalCost.modifierExtension | SourceIsBroaderThanTarget | R5 `InsurancePlan.plan.generalCost.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `InsurancePlan.plan.generalCost.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| InsurancePlan.plan.generalCost.type | InsurancePlan.plan.generalCost.type | Equivalent | R5 `InsurancePlan.plan.generalCost.type` maps as Equivalent to R4B `InsurancePlan.plan.generalCost.type` |
| InsurancePlan.plan.id | InsurancePlan.plan.id | Equivalent | R5 `InsurancePlan.plan.id` maps as Equivalent to R4B `InsurancePlan.plan.id` |
| InsurancePlan.plan.identifier | InsurancePlan.plan.identifier | Equivalent | R5 `InsurancePlan.plan.identifier` maps as Equivalent to R4B `InsurancePlan.plan.identifier` |
| InsurancePlan.plan.modifierExtension | InsurancePlan.plan.modifierExtension | SourceIsBroaderThanTarget | R5 `InsurancePlan.plan.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `InsurancePlan.plan.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| InsurancePlan.plan.network | InsurancePlan.plan.network | Equivalent | R5 `InsurancePlan.plan.network` maps as Equivalent to R4B `InsurancePlan.plan.network` |
| InsurancePlan.plan.specificCost | InsurancePlan.plan.specificCost | Equivalent | R5 `InsurancePlan.plan.specificCost` maps as Equivalent to R4B `InsurancePlan.plan.specificCost` |
| InsurancePlan.plan.specificCost.benefit | InsurancePlan.plan.specificCost.benefit | Equivalent | R5 `InsurancePlan.plan.specificCost.benefit` maps as Equivalent to R4B `InsurancePlan.plan.specificCost.benefit` |
| InsurancePlan.plan.specificCost.benefit.cost | InsurancePlan.plan.specificCost.benefit.cost | Equivalent | R5 `InsurancePlan.plan.specificCost.benefit.cost` maps as Equivalent to R4B `InsurancePlan.plan.specificCost.benefit.cost` |
| InsurancePlan.plan.specificCost.benefit.cost.applicability | InsurancePlan.plan.specificCost.benefit.cost.applicability | Equivalent | R5 `InsurancePlan.plan.specificCost.benefit.cost.applicability` maps as Equivalent to R4B `InsurancePlan.plan.specificCost.benefit.cost.applicability` - applicability has compatible required binding for non-code type: http://hl7.org/fhir/ValueSet/insuranceplan-applicability|5.0.0 and http://hl7.org/fhir/ValueSet/insuranceplan-applicability|4.3.0 (Equivalent) |
| InsurancePlan.plan.specificCost.benefit.cost.extension | InsurancePlan.plan.specificCost.benefit.cost.extension | SourceIsBroaderThanTarget | R5 `InsurancePlan.plan.specificCost.benefit.cost.extension` maps as SourceIsBroaderThanTarget to R4B `InsurancePlan.plan.specificCost.benefit.cost.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| InsurancePlan.plan.specificCost.benefit.cost.id | InsurancePlan.plan.specificCost.benefit.cost.id | Equivalent | R5 `InsurancePlan.plan.specificCost.benefit.cost.id` maps as Equivalent to R4B `InsurancePlan.plan.specificCost.benefit.cost.id` |
| InsurancePlan.plan.specificCost.benefit.cost.modifierExtension | InsurancePlan.plan.specificCost.benefit.cost.modifierExtension | SourceIsBroaderThanTarget | R5 `InsurancePlan.plan.specificCost.benefit.cost.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `InsurancePlan.plan.specificCost.benefit.cost.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| InsurancePlan.plan.specificCost.benefit.cost.qualifiers | InsurancePlan.plan.specificCost.benefit.cost.qualifiers | Equivalent | R5 `InsurancePlan.plan.specificCost.benefit.cost.qualifiers` maps as Equivalent to R4B `InsurancePlan.plan.specificCost.benefit.cost.qualifiers` |
| InsurancePlan.plan.specificCost.benefit.cost.type | InsurancePlan.plan.specificCost.benefit.cost.type | Equivalent | R5 `InsurancePlan.plan.specificCost.benefit.cost.type` maps as Equivalent to R4B `InsurancePlan.plan.specificCost.benefit.cost.type` |
| InsurancePlan.plan.specificCost.benefit.cost.value | InsurancePlan.plan.specificCost.benefit.cost.value | Equivalent | R5 `InsurancePlan.plan.specificCost.benefit.cost.value` maps as Equivalent to R4B `InsurancePlan.plan.specificCost.benefit.cost.value` |
| InsurancePlan.plan.specificCost.benefit.extension | InsurancePlan.plan.specificCost.benefit.extension | SourceIsBroaderThanTarget | R5 `InsurancePlan.plan.specificCost.benefit.extension` maps as SourceIsBroaderThanTarget to R4B `InsurancePlan.plan.specificCost.benefit.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| InsurancePlan.plan.specificCost.benefit.id | InsurancePlan.plan.specificCost.benefit.id | Equivalent | R5 `InsurancePlan.plan.specificCost.benefit.id` maps as Equivalent to R4B `InsurancePlan.plan.specificCost.benefit.id` |
| InsurancePlan.plan.specificCost.benefit.modifierExtension | InsurancePlan.plan.specificCost.benefit.modifierExtension | SourceIsBroaderThanTarget | R5 `InsurancePlan.plan.specificCost.benefit.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `InsurancePlan.plan.specificCost.benefit.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| InsurancePlan.plan.specificCost.benefit.type | InsurancePlan.plan.specificCost.benefit.type | Equivalent | R5 `InsurancePlan.plan.specificCost.benefit.type` maps as Equivalent to R4B `InsurancePlan.plan.specificCost.benefit.type` |
| InsurancePlan.plan.specificCost.category | InsurancePlan.plan.specificCost.category | Equivalent | R5 `InsurancePlan.plan.specificCost.category` maps as Equivalent to R4B `InsurancePlan.plan.specificCost.category` |
| InsurancePlan.plan.specificCost.extension | InsurancePlan.plan.specificCost.extension | SourceIsBroaderThanTarget | R5 `InsurancePlan.plan.specificCost.extension` maps as SourceIsBroaderThanTarget to R4B `InsurancePlan.plan.specificCost.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| InsurancePlan.plan.specificCost.id | InsurancePlan.plan.specificCost.id | Equivalent | R5 `InsurancePlan.plan.specificCost.id` maps as Equivalent to R4B `InsurancePlan.plan.specificCost.id` |
| InsurancePlan.plan.specificCost.modifierExtension | InsurancePlan.plan.specificCost.modifierExtension | SourceIsBroaderThanTarget | R5 `InsurancePlan.plan.specificCost.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `InsurancePlan.plan.specificCost.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| InsurancePlan.plan.type | InsurancePlan.plan.type | Equivalent | R5 `InsurancePlan.plan.type` maps as Equivalent to R4B `InsurancePlan.plan.type` |
| InsurancePlan.status | InsurancePlan.status | Equivalent | R5 `InsurancePlan.status` maps as Equivalent to R4B `InsurancePlan.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|5.0.0 and http://hl7.org/fhir/ValueSet/publication-status|4.3.0 (Equivalent) |
| InsurancePlan.text | InsurancePlan.text | Equivalent | R5 `InsurancePlan.text` maps as Equivalent to R4B `InsurancePlan.text` |
| InsurancePlan.type | InsurancePlan.type | Equivalent | R5 `InsurancePlan.type` maps as Equivalent to R4B `InsurancePlan.type` |

