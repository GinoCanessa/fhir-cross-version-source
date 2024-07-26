Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1
Generated at Thursday, July 25, 2024 3:56:51 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | SupplyDelivery |  | Record of delivery of what is supplied. | 25 | 14 |
| Target | SupplyDelivery |  | Record of delivery of what is supplied. | 25 | 14 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 21 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| SupplyDelivery | SupplyDelivery | Equivalent | R5 `SupplyDelivery` maps as Equivalent to R4 `SupplyDelivery` |
| SupplyDelivery.basedOn | SupplyDelivery.basedOn | Equivalent | R5 `SupplyDelivery.basedOn` maps as Equivalent to R4 `SupplyDelivery.basedOn` |
| SupplyDelivery.contained | SupplyDelivery.contained | Equivalent | R5 `SupplyDelivery.contained` maps as Equivalent to R4 `SupplyDelivery.contained` |
| SupplyDelivery.destination | SupplyDelivery.destination | Equivalent | R5 `SupplyDelivery.destination` maps as Equivalent to R4 `SupplyDelivery.destination` |
| SupplyDelivery.extension | SupplyDelivery.extension | SourceIsBroaderThanTarget | R5 `SupplyDelivery.extension` maps as SourceIsBroaderThanTarget to R4 `SupplyDelivery.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| SupplyDelivery.id | SupplyDelivery.id | Equivalent | R5 `SupplyDelivery.id` maps as Equivalent to R4 `SupplyDelivery.id` |
| SupplyDelivery.identifier | SupplyDelivery.identifier | Equivalent | R5 `SupplyDelivery.identifier` maps as Equivalent to R4 `SupplyDelivery.identifier` |
| SupplyDelivery.implicitRules | SupplyDelivery.implicitRules | Equivalent | R5 `SupplyDelivery.implicitRules` maps as Equivalent to R4 `SupplyDelivery.implicitRules` |
| SupplyDelivery.language | SupplyDelivery.language | RelatedTo | R5 `SupplyDelivery.language` maps as RelatedTo to R4 `SupplyDelivery.language` - language changed the binding strength from Required to Preferred |
| SupplyDelivery.meta | SupplyDelivery.meta | Equivalent | R5 `SupplyDelivery.meta` maps as Equivalent to R4 `SupplyDelivery.meta` |
| SupplyDelivery.modifierExtension | SupplyDelivery.modifierExtension | SourceIsBroaderThanTarget | R5 `SupplyDelivery.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `SupplyDelivery.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| SupplyDelivery.occurrence[x] | SupplyDelivery.occurrence[x] | Equivalent | R5 `SupplyDelivery.occurrence[x]` maps as Equivalent to R4 `SupplyDelivery.occurrence[x]` |
| SupplyDelivery.partOf | SupplyDelivery.partOf | Equivalent | R5 `SupplyDelivery.partOf` maps as Equivalent to R4 `SupplyDelivery.partOf` |
| SupplyDelivery.patient | SupplyDelivery.patient | Equivalent | R5 `SupplyDelivery.patient` maps as Equivalent to R4 `SupplyDelivery.patient` |
| SupplyDelivery.receiver | SupplyDelivery.receiver | SourceIsBroaderThanTarget | R5 `SupplyDelivery.receiver` maps as SourceIsBroaderThanTarget to R4 `SupplyDelivery.receiver` - receiver has change due to type change: R5 `receiver` `Reference` maps as SourceIsBroaderThanTarget for R4 `receiver` |
| SupplyDelivery.status | SupplyDelivery.status | Equivalent | R5 `SupplyDelivery.status` maps as Equivalent to R4 `SupplyDelivery.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/supplydelivery-status|5.0.0 and http://hl7.org/fhir/ValueSet/supplydelivery-status|4.0.1 (Equivalent) |
| SupplyDelivery.suppliedItem | SupplyDelivery.suppliedItem | RelatedTo | R5 `SupplyDelivery.suppliedItem` maps as RelatedTo to R4 `SupplyDelivery.suppliedItem` - suppliedItem changed from array to scalar (max cardinality from * to 1) |
| SupplyDelivery.suppliedItem.extension | SupplyDelivery.suppliedItem.extension | SourceIsBroaderThanTarget | R5 `SupplyDelivery.suppliedItem.extension` maps as SourceIsBroaderThanTarget to R4 `SupplyDelivery.suppliedItem.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| SupplyDelivery.suppliedItem.id | SupplyDelivery.suppliedItem.id | Equivalent | R5 `SupplyDelivery.suppliedItem.id` maps as Equivalent to R4 `SupplyDelivery.suppliedItem.id` |
| SupplyDelivery.suppliedItem.item[x] | SupplyDelivery.suppliedItem.item[x] | SourceIsBroaderThanTarget | R5 `SupplyDelivery.suppliedItem.item[x]` maps as SourceIsBroaderThanTarget to R4 `SupplyDelivery.suppliedItem.item[x]` - item[x] has change due to type change: R5 `item[x]` `Reference` maps as SourceIsBroaderThanTarget for R4 `item[x]` |
| SupplyDelivery.suppliedItem.modifierExtension | SupplyDelivery.suppliedItem.modifierExtension | SourceIsBroaderThanTarget | R5 `SupplyDelivery.suppliedItem.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `SupplyDelivery.suppliedItem.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| SupplyDelivery.suppliedItem.quantity | SupplyDelivery.suppliedItem.quantity | Equivalent | R5 `SupplyDelivery.suppliedItem.quantity` maps as Equivalent to R4 `SupplyDelivery.suppliedItem.quantity` |
| SupplyDelivery.supplier | SupplyDelivery.supplier | Equivalent | R5 `SupplyDelivery.supplier` maps as Equivalent to R4 `SupplyDelivery.supplier` |
| SupplyDelivery.text | SupplyDelivery.text | Equivalent | R5 `SupplyDelivery.text` maps as Equivalent to R4 `SupplyDelivery.text` |
| SupplyDelivery.type | SupplyDelivery.type | Equivalent | R5 `SupplyDelivery.type` maps as Equivalent to R4 `SupplyDelivery.type` - type has compatible required binding for non-code type: http://hl7.org/fhir/ValueSet/supplydelivery-supplyitemtype|5.0.0 and http://hl7.org/fhir/ValueSet/supplydelivery-type|4.0.1 (Equivalent) |

