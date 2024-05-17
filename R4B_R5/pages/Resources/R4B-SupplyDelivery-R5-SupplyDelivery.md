Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

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
| SupplyDelivery | SupplyDelivery | Equivalent | R4B `SupplyDelivery` maps as Equivalent to R5 `SupplyDelivery` |
| SupplyDelivery.basedOn | SupplyDelivery.basedOn | Equivalent | R4B `SupplyDelivery.basedOn` maps as Equivalent to R5 `SupplyDelivery.basedOn` |
| SupplyDelivery.contained | SupplyDelivery.contained | Equivalent | R4B `SupplyDelivery.contained` maps as Equivalent to R5 `SupplyDelivery.contained` |
| SupplyDelivery.destination | SupplyDelivery.destination | Equivalent | R4B `SupplyDelivery.destination` maps as Equivalent to R5 `SupplyDelivery.destination` |
| SupplyDelivery.extension | SupplyDelivery.extension | RelatedTo | R4B `SupplyDelivery.extension` maps as RelatedTo to R5 `SupplyDelivery.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| SupplyDelivery.id | SupplyDelivery.id | Equivalent | R4B `SupplyDelivery.id` maps as Equivalent to R5 `SupplyDelivery.id` |
| SupplyDelivery.identifier | SupplyDelivery.identifier | Equivalent | R4B `SupplyDelivery.identifier` maps as Equivalent to R5 `SupplyDelivery.identifier` |
| SupplyDelivery.implicitRules | SupplyDelivery.implicitRules | Equivalent | R4B `SupplyDelivery.implicitRules` maps as Equivalent to R5 `SupplyDelivery.implicitRules` |
| SupplyDelivery.language | SupplyDelivery.language | RelatedTo | R4B `SupplyDelivery.language` maps as RelatedTo to R5 `SupplyDelivery.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| SupplyDelivery.meta | SupplyDelivery.meta | Equivalent | R4B `SupplyDelivery.meta` maps as Equivalent to R5 `SupplyDelivery.meta` |
| SupplyDelivery.modifierExtension | SupplyDelivery.modifierExtension | RelatedTo | R4B `SupplyDelivery.modifierExtension` maps as RelatedTo to R5 `SupplyDelivery.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| SupplyDelivery.occurrence[x] | SupplyDelivery.occurrence[x] | Equivalent | R4B `SupplyDelivery.occurrence[x]` maps as Equivalent to R5 `SupplyDelivery.occurrence[x]` |
| SupplyDelivery.partOf | SupplyDelivery.partOf | Equivalent | R4B `SupplyDelivery.partOf` maps as Equivalent to R5 `SupplyDelivery.partOf` |
| SupplyDelivery.patient | SupplyDelivery.patient | Equivalent | R4B `SupplyDelivery.patient` maps as Equivalent to R5 `SupplyDelivery.patient` |
| SupplyDelivery.receiver | SupplyDelivery.receiver | SourceIsNarrowerThanTarget | R4B `SupplyDelivery.receiver` maps as SourceIsNarrowerThanTarget to R5 `SupplyDelivery.receiver` - receiver has change due to type change: R4B `receiver` `Reference` maps as SourceIsNarrowerThanTarget for R5 `receiver` |
| SupplyDelivery.status | SupplyDelivery.status | Equivalent | R4B `SupplyDelivery.status` maps as Equivalent to R5 `SupplyDelivery.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/supplydelivery-status|4.3.0 and http://hl7.org/fhir/ValueSet/supplydelivery-status|5.0.0 (Equivalent) |
| SupplyDelivery.suppliedItem | SupplyDelivery.suppliedItem | RelatedTo | R4B `SupplyDelivery.suppliedItem` maps as RelatedTo to R5 `SupplyDelivery.suppliedItem` - suppliedItem changed from scalar to array (max cardinality from 1 to *) |
| SupplyDelivery.suppliedItem.extension | SupplyDelivery.suppliedItem.extension | RelatedTo | R4B `SupplyDelivery.suppliedItem.extension` maps as RelatedTo to R5 `SupplyDelivery.suppliedItem.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| SupplyDelivery.suppliedItem.id | SupplyDelivery.suppliedItem.id | Equivalent | R4B `SupplyDelivery.suppliedItem.id` maps as Equivalent to R5 `SupplyDelivery.suppliedItem.id` |
| SupplyDelivery.suppliedItem.item[x] | SupplyDelivery.suppliedItem.item[x] | SourceIsNarrowerThanTarget | R4B `SupplyDelivery.suppliedItem.item[x]` maps as SourceIsNarrowerThanTarget to R5 `SupplyDelivery.suppliedItem.item[x]` - item[x] has change due to type change: R4B `item[x]` `Reference` maps as SourceIsNarrowerThanTarget for R5 `item[x]` |
| SupplyDelivery.suppliedItem.modifierExtension | SupplyDelivery.suppliedItem.modifierExtension | RelatedTo | R4B `SupplyDelivery.suppliedItem.modifierExtension` maps as RelatedTo to R5 `SupplyDelivery.suppliedItem.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| SupplyDelivery.suppliedItem.quantity | SupplyDelivery.suppliedItem.quantity | Equivalent | R4B `SupplyDelivery.suppliedItem.quantity` maps as Equivalent to R5 `SupplyDelivery.suppliedItem.quantity` |
| SupplyDelivery.supplier | SupplyDelivery.supplier | Equivalent | R4B `SupplyDelivery.supplier` maps as Equivalent to R5 `SupplyDelivery.supplier` |
| SupplyDelivery.text | SupplyDelivery.text | Equivalent | R4B `SupplyDelivery.text` maps as Equivalent to R5 `SupplyDelivery.text` |
| SupplyDelivery.type | SupplyDelivery.type | Equivalent | R4B `SupplyDelivery.type` maps as Equivalent to R5 `SupplyDelivery.type` - type has compatible required binding for non-code type: http://hl7.org/fhir/ValueSet/supplydelivery-type|4.3.0 and http://hl7.org/fhir/ValueSet/supplydelivery-supplyitemtype|5.0.0 (Equivalent) |

