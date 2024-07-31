Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | MarketingStatus |  | MarketingStatus Type: The marketing status describes the date when a medicinal product is actually put on the market or the date as of which it is no longer available. | 9 | 6 |
| Target | MarketingStatus |  | Base StructureDefinition for MarketingStatus Type: The marketing status describes the date when a medicinal product is actually put on the market or the date as of which it is no longer available. | 9 | 6 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 7 |
RelatedTo | 2 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| MarketingStatus | MarketingStatus | Equivalent | R5 `MarketingStatus` maps as Equivalent to R4 `MarketingStatus` |
| MarketingStatus.country | MarketingStatus.country | RelatedTo | R5 `MarketingStatus.country` maps as RelatedTo to R4 `MarketingStatus.country` - country made the element mandatory; country increased the minimum cardinality from 0 to 1 |
| MarketingStatus.dateRange | MarketingStatus.dateRange | RelatedTo | R5 `MarketingStatus.dateRange` maps as RelatedTo to R4 `MarketingStatus.dateRange` - dateRange made the element mandatory; dateRange increased the minimum cardinality from 0 to 1 |
| MarketingStatus.extension | MarketingStatus.extension | Equivalent | R5 `MarketingStatus.extension` maps as Equivalent to R4 `MarketingStatus.extension` |
| MarketingStatus.id | MarketingStatus.id | Equivalent | R5 `MarketingStatus.id` maps as Equivalent to R4 `MarketingStatus.id` |
| MarketingStatus.jurisdiction | MarketingStatus.jurisdiction | Equivalent | R5 `MarketingStatus.jurisdiction` maps as Equivalent to R4 `MarketingStatus.jurisdiction` |
| MarketingStatus.modifierExtension | MarketingStatus.modifierExtension | Equivalent | R5 `MarketingStatus.modifierExtension` maps as Equivalent to R4 `MarketingStatus.modifierExtension` |
| MarketingStatus.restoreDate | MarketingStatus.restoreDate | Equivalent | R5 `MarketingStatus.restoreDate` maps as Equivalent to R4 `MarketingStatus.restoreDate` |
| MarketingStatus.status | MarketingStatus.status | Equivalent | R5 `MarketingStatus.status` maps as Equivalent to R4 `MarketingStatus.status` |

