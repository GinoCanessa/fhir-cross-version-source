Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

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
| ChargeItem | ChargeItem | Equivalent | R5 `ChargeItem` maps as Equivalent to R4 `ChargeItem` |
| ChargeItem.account | ChargeItem.account | Equivalent | R5 `ChargeItem.account` maps as Equivalent to R4 `ChargeItem.account` |
| ChargeItem.bodysite | ChargeItem.bodysite | Equivalent | R5 `ChargeItem.bodysite` maps as Equivalent to R4 `ChargeItem.bodysite` |
| ChargeItem.code | ChargeItem.code | Equivalent | R5 `ChargeItem.code` maps as Equivalent to R4 `ChargeItem.code` |
| ChargeItem.contained | ChargeItem.contained | Equivalent | R5 `ChargeItem.contained` maps as Equivalent to R4 `ChargeItem.contained` |
| ChargeItem.costCenter | ChargeItem.costCenter | Equivalent | R5 `ChargeItem.costCenter` maps as Equivalent to R4 `ChargeItem.costCenter` |
| ChargeItem.definitionCanonical | ChargeItem.definitionCanonical | Equivalent | R5 `ChargeItem.definitionCanonical` maps as Equivalent to R4 `ChargeItem.definitionCanonical` |
| ChargeItem.definitionUri | ChargeItem.definitionUri | Equivalent | R5 `ChargeItem.definitionUri` maps as Equivalent to R4 `ChargeItem.definitionUri` |
| ChargeItem.encounter | - | DoesNotExistInTarget | R5 `ChargeItem.encounter` does not appear in the target and has no mapping for `ChargeItem`. |
| ChargeItem.enteredDate | ChargeItem.enteredDate | Equivalent | R5 `ChargeItem.enteredDate` maps as Equivalent to R4 `ChargeItem.enteredDate` |
| ChargeItem.enterer | ChargeItem.enterer | Equivalent | R5 `ChargeItem.enterer` maps as Equivalent to R4 `ChargeItem.enterer` |
| ChargeItem.extension | ChargeItem.extension | SourceIsBroaderThanTarget | R5 `ChargeItem.extension` maps as SourceIsBroaderThanTarget to R4 `ChargeItem.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ChargeItem.id | ChargeItem.id | Equivalent | R5 `ChargeItem.id` maps as Equivalent to R4 `ChargeItem.id` |
| ChargeItem.identifier | ChargeItem.identifier | Equivalent | R5 `ChargeItem.identifier` maps as Equivalent to R4 `ChargeItem.identifier` |
| ChargeItem.implicitRules | ChargeItem.implicitRules | Equivalent | R5 `ChargeItem.implicitRules` maps as Equivalent to R4 `ChargeItem.implicitRules` |
| ChargeItem.language | ChargeItem.language | RelatedTo | R5 `ChargeItem.language` maps as RelatedTo to R4 `ChargeItem.language` - language changed the binding strength from Required to Preferred |
| ChargeItem.meta | ChargeItem.meta | Equivalent | R5 `ChargeItem.meta` maps as Equivalent to R4 `ChargeItem.meta` |
| ChargeItem.modifierExtension | ChargeItem.modifierExtension | SourceIsBroaderThanTarget | R5 `ChargeItem.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ChargeItem.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ChargeItem.note | ChargeItem.note | SourceIsBroaderThanTarget | R5 `ChargeItem.note` maps as SourceIsBroaderThanTarget to R4 `ChargeItem.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4 `note` |
| ChargeItem.occurrence[x] | ChargeItem.occurrence[x] | Equivalent | R5 `ChargeItem.occurrence[x]` maps as Equivalent to R4 `ChargeItem.occurrence[x]` |
| ChargeItem.overrideReason | ChargeItem.overrideReason | RelatedTo | R5 `ChargeItem.overrideReason` maps as RelatedTo to R4 `ChargeItem.overrideReason` - overrideReason removed a binding requirement - Example ; overrideReason has change due to type change: R5 overrideReason CodeableConcept has no equivalent or mapped type in R4 overrideReason |
| ChargeItem.partOf | ChargeItem.partOf | Equivalent | R5 `ChargeItem.partOf` maps as Equivalent to R4 `ChargeItem.partOf` |
| ChargeItem.performer | ChargeItem.performer | Equivalent | R5 `ChargeItem.performer` maps as Equivalent to R4 `ChargeItem.performer` |
| ChargeItem.performer.actor | ChargeItem.performer.actor | SourceIsBroaderThanTarget | R5 `ChargeItem.performer.actor` maps as SourceIsBroaderThanTarget to R4 `ChargeItem.performer.actor` - actor has change due to type change: R5 `actor` `Reference` maps as SourceIsBroaderThanTarget for R4 `actor` |
| ChargeItem.performer.extension | ChargeItem.performer.extension | SourceIsBroaderThanTarget | R5 `ChargeItem.performer.extension` maps as SourceIsBroaderThanTarget to R4 `ChargeItem.performer.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ChargeItem.performer.function | ChargeItem.performer.function | Equivalent | R5 `ChargeItem.performer.function` maps as Equivalent to R4 `ChargeItem.performer.function` |
| ChargeItem.performer.id | ChargeItem.performer.id | Equivalent | R5 `ChargeItem.performer.id` maps as Equivalent to R4 `ChargeItem.performer.id` |
| ChargeItem.performer.modifierExtension | ChargeItem.performer.modifierExtension | SourceIsBroaderThanTarget | R5 `ChargeItem.performer.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ChargeItem.performer.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ChargeItem.performingOrganization | ChargeItem.performingOrganization | Equivalent | R5 `ChargeItem.performingOrganization` maps as Equivalent to R4 `ChargeItem.performingOrganization` |
| ChargeItem.product | - | DoesNotExistInTarget | R5 `ChargeItem.product` does not appear in the target and has no mapping for `ChargeItem`. |
| ChargeItem.quantity | ChargeItem.quantity | Equivalent | R5 `ChargeItem.quantity` maps as Equivalent to R4 `ChargeItem.quantity` |
| ChargeItem.reason | ChargeItem.reason | Equivalent | R5 `ChargeItem.reason` maps as Equivalent to R4 `ChargeItem.reason` |
| ChargeItem.requestingOrganization | ChargeItem.requestingOrganization | Equivalent | R5 `ChargeItem.requestingOrganization` maps as Equivalent to R4 `ChargeItem.requestingOrganization` |
| ChargeItem.service | ChargeItem.service | SourceIsBroaderThanTarget | R5 `ChargeItem.service` maps as SourceIsBroaderThanTarget to R4 `ChargeItem.service` - service has change due to type change: R5 service CodeableReference has no equivalent or mapped type in R4 service |
| ChargeItem.status | ChargeItem.status | Equivalent | R5 `ChargeItem.status` maps as Equivalent to R4 `ChargeItem.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/chargeitem-status|5.0.0 and http://hl7.org/fhir/ValueSet/chargeitem-status|4.0.1 (Equivalent) |
| ChargeItem.subject | ChargeItem.subject | Equivalent | R5 `ChargeItem.subject` maps as Equivalent to R4 `ChargeItem.subject` |
| ChargeItem.supportingInformation | ChargeItem.supportingInformation | Equivalent | R5 `ChargeItem.supportingInformation` maps as Equivalent to R4 `ChargeItem.supportingInformation` |
| ChargeItem.text | ChargeItem.text | Equivalent | R5 `ChargeItem.text` maps as Equivalent to R4 `ChargeItem.text` |
| ChargeItem.totalPriceComponent | - | DoesNotExistInTarget | R5 `ChargeItem.totalPriceComponent` does not appear in the target and has no mapping for `ChargeItem`. |
| ChargeItem.unitPriceComponent | - | DoesNotExistInTarget | R5 `ChargeItem.unitPriceComponent` does not appear in the target and has no mapping for `ChargeItem`. |

