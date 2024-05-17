Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | ChargeItem |  | The resource ChargeItem describes the provision of healthcare provider products for a certain patient, therefore referring not only to the product, but containing in addition details of the provision, like date, time, amounts and participating organizations and persons. Main Usage of the ChargeItem is to enable the billing process and internal cost allocation. | 40 | 29 |
| Target | ChargeItem |  | The resource ChargeItem describes the provision of healthcare provider products for a certain patient, therefore referring not only to the product, but containing in addition details of the provision, like date, time, amounts and participating organizations and persons. Main Usage of the ChargeItem is to enable the billing process and internal cost allocation. | 40 | 29 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 4 |
Equivalent | 4 |
RelatedTo | 32 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| ChargeItem | ChargeItem | Equivalent | R4B `ChargeItem` maps as Equivalent to R5 `ChargeItem` |
| ChargeItem.account | ChargeItem.account | Equivalent | R4B `ChargeItem.account` maps as Equivalent to R5 `ChargeItem.account` |
| ChargeItem.bodysite | ChargeItem.bodysite | Equivalent | R4B `ChargeItem.bodysite` maps as Equivalent to R5 `ChargeItem.bodysite` |
| ChargeItem.code | ChargeItem.code | Equivalent | R4B `ChargeItem.code` maps as Equivalent to R5 `ChargeItem.code` |
| ChargeItem.contained | ChargeItem.contained | Equivalent | R4B `ChargeItem.contained` maps as Equivalent to R5 `ChargeItem.contained` |
| ChargeItem.context | - | DoesNotExistInTarget | R4B `ChargeItem.context` does not appear in the target and has no mapping for `ChargeItem`. |
| ChargeItem.costCenter | ChargeItem.costCenter | Equivalent | R4B `ChargeItem.costCenter` maps as Equivalent to R5 `ChargeItem.costCenter` |
| ChargeItem.definitionCanonical | ChargeItem.definitionCanonical | Equivalent | R4B `ChargeItem.definitionCanonical` maps as Equivalent to R5 `ChargeItem.definitionCanonical` |
| ChargeItem.definitionUri | ChargeItem.definitionUri | Equivalent | R4B `ChargeItem.definitionUri` maps as Equivalent to R5 `ChargeItem.definitionUri` |
| ChargeItem.enteredDate | ChargeItem.enteredDate | Equivalent | R4B `ChargeItem.enteredDate` maps as Equivalent to R5 `ChargeItem.enteredDate` |
| ChargeItem.enterer | ChargeItem.enterer | Equivalent | R4B `ChargeItem.enterer` maps as Equivalent to R5 `ChargeItem.enterer` |
| ChargeItem.extension | ChargeItem.extension | RelatedTo | R4B `ChargeItem.extension` maps as RelatedTo to R5 `ChargeItem.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ChargeItem.factorOverride | - | DoesNotExistInTarget | R4B `ChargeItem.factorOverride` does not appear in the target and has no mapping for `ChargeItem`. |
| ChargeItem.id | ChargeItem.id | Equivalent | R4B `ChargeItem.id` maps as Equivalent to R5 `ChargeItem.id` |
| ChargeItem.identifier | ChargeItem.identifier | Equivalent | R4B `ChargeItem.identifier` maps as Equivalent to R5 `ChargeItem.identifier` |
| ChargeItem.implicitRules | ChargeItem.implicitRules | Equivalent | R4B `ChargeItem.implicitRules` maps as Equivalent to R5 `ChargeItem.implicitRules` |
| ChargeItem.language | ChargeItem.language | RelatedTo | R4B `ChargeItem.language` maps as RelatedTo to R5 `ChargeItem.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| ChargeItem.meta | ChargeItem.meta | Equivalent | R4B `ChargeItem.meta` maps as Equivalent to R5 `ChargeItem.meta` |
| ChargeItem.modifierExtension | ChargeItem.modifierExtension | RelatedTo | R4B `ChargeItem.modifierExtension` maps as RelatedTo to R5 `ChargeItem.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ChargeItem.note | ChargeItem.note | SourceIsNarrowerThanTarget | R4B `ChargeItem.note` maps as SourceIsNarrowerThanTarget to R5 `ChargeItem.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| ChargeItem.occurrence[x] | ChargeItem.occurrence[x] | Equivalent | R4B `ChargeItem.occurrence[x]` maps as Equivalent to R5 `ChargeItem.occurrence[x]` |
| ChargeItem.overrideReason | ChargeItem.overrideReason | RelatedTo | R4B `ChargeItem.overrideReason` maps as RelatedTo to R5 `ChargeItem.overrideReason` - overrideReason added a binding requirement - Example ; overrideReason has change due to type change: R4B overrideReason string has no equivalent or mapped type in R5 overrideReason |
| ChargeItem.partOf | ChargeItem.partOf | Equivalent | R4B `ChargeItem.partOf` maps as Equivalent to R5 `ChargeItem.partOf` |
| ChargeItem.performer | ChargeItem.performer | Equivalent | R4B `ChargeItem.performer` maps as Equivalent to R5 `ChargeItem.performer` |
| ChargeItem.performer.actor | ChargeItem.performer.actor | SourceIsNarrowerThanTarget | R4B `ChargeItem.performer.actor` maps as SourceIsNarrowerThanTarget to R5 `ChargeItem.performer.actor` - actor has change due to type change: R4B `actor` `Reference` maps as SourceIsNarrowerThanTarget for R5 `actor` |
| ChargeItem.performer.extension | ChargeItem.performer.extension | RelatedTo | R4B `ChargeItem.performer.extension` maps as RelatedTo to R5 `ChargeItem.performer.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ChargeItem.performer.function | ChargeItem.performer.function | Equivalent | R4B `ChargeItem.performer.function` maps as Equivalent to R5 `ChargeItem.performer.function` |
| ChargeItem.performer.id | ChargeItem.performer.id | Equivalent | R4B `ChargeItem.performer.id` maps as Equivalent to R5 `ChargeItem.performer.id` |
| ChargeItem.performer.modifierExtension | ChargeItem.performer.modifierExtension | RelatedTo | R4B `ChargeItem.performer.modifierExtension` maps as RelatedTo to R5 `ChargeItem.performer.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ChargeItem.performingOrganization | ChargeItem.performingOrganization | Equivalent | R4B `ChargeItem.performingOrganization` maps as Equivalent to R5 `ChargeItem.performingOrganization` |
| ChargeItem.priceOverride | - | DoesNotExistInTarget | R4B `ChargeItem.priceOverride` does not appear in the target and has no mapping for `ChargeItem`. |
| ChargeItem.product[x] | - | DoesNotExistInTarget | R4B `ChargeItem.product[x]` does not appear in the target and has no mapping for `ChargeItem`. |
| ChargeItem.quantity | ChargeItem.quantity | Equivalent | R4B `ChargeItem.quantity` maps as Equivalent to R5 `ChargeItem.quantity` |
| ChargeItem.reason | ChargeItem.reason | Equivalent | R4B `ChargeItem.reason` maps as Equivalent to R5 `ChargeItem.reason` |
| ChargeItem.requestingOrganization | ChargeItem.requestingOrganization | Equivalent | R4B `ChargeItem.requestingOrganization` maps as Equivalent to R5 `ChargeItem.requestingOrganization` |
| ChargeItem.service | ChargeItem.service | SourceIsBroaderThanTarget | R4B `ChargeItem.service` maps as SourceIsBroaderThanTarget to R5 `ChargeItem.service` - service has change due to type change: R4B service Reference has no equivalent or mapped type in R5 service |
| ChargeItem.status | ChargeItem.status | Equivalent | R4B `ChargeItem.status` maps as Equivalent to R5 `ChargeItem.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/chargeitem-status|4.3.0 and http://hl7.org/fhir/ValueSet/chargeitem-status|5.0.0 (Equivalent) |
| ChargeItem.subject | ChargeItem.subject | Equivalent | R4B `ChargeItem.subject` maps as Equivalent to R5 `ChargeItem.subject` |
| ChargeItem.supportingInformation | ChargeItem.supportingInformation | Equivalent | R4B `ChargeItem.supportingInformation` maps as Equivalent to R5 `ChargeItem.supportingInformation` |
| ChargeItem.text | ChargeItem.text | Equivalent | R4B `ChargeItem.text` maps as Equivalent to R5 `ChargeItem.text` |

