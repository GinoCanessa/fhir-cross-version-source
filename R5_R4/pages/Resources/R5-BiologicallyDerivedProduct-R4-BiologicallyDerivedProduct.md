Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | BiologicallyDerivedProduct |  | A biological material originating from a biological entity intended to be transplanted or infused into another (possibly the same) biological entity. | 33 | 19 |
| Target | BiologicallyDerivedProduct |  | A material substance originating from a biological entity intended to be transplanted or infused<br/>into another (possibly the same) biological entity. | 45 | 25 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 11 |
Equivalent | 15 |
RelatedTo | 2 |
SourceIsBroaderThanTarget | 4 |
SourceIsNarrowerThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| BiologicallyDerivedProduct | BiologicallyDerivedProduct | Equivalent | R5 `BiologicallyDerivedProduct` maps as Equivalent to R4 `BiologicallyDerivedProduct` |
| BiologicallyDerivedProduct.biologicalSourceEvent | - | DoesNotExistInTarget | R5 `BiologicallyDerivedProduct.biologicalSourceEvent` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.collection | BiologicallyDerivedProduct.collection | Equivalent | R5 `BiologicallyDerivedProduct.collection` maps as Equivalent to R4 `BiologicallyDerivedProduct.collection` |
| BiologicallyDerivedProduct.collection.collected[x] | BiologicallyDerivedProduct.collection.collected[x] | Equivalent | R5 `BiologicallyDerivedProduct.collection.collected[x]` maps as Equivalent to R4 `BiologicallyDerivedProduct.collection.collected[x]` |
| BiologicallyDerivedProduct.collection.collector | BiologicallyDerivedProduct.collection.collector | Equivalent | R5 `BiologicallyDerivedProduct.collection.collector` maps as Equivalent to R4 `BiologicallyDerivedProduct.collection.collector` |
| BiologicallyDerivedProduct.collection.extension | BiologicallyDerivedProduct.collection.extension | SourceIsBroaderThanTarget | R5 `BiologicallyDerivedProduct.collection.extension` maps as SourceIsBroaderThanTarget to R4 `BiologicallyDerivedProduct.collection.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| BiologicallyDerivedProduct.collection.id | BiologicallyDerivedProduct.collection.id | Equivalent | R5 `BiologicallyDerivedProduct.collection.id` maps as Equivalent to R4 `BiologicallyDerivedProduct.collection.id` |
| BiologicallyDerivedProduct.collection.modifierExtension | BiologicallyDerivedProduct.collection.modifierExtension | SourceIsBroaderThanTarget | R5 `BiologicallyDerivedProduct.collection.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `BiologicallyDerivedProduct.collection.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| BiologicallyDerivedProduct.collection.source | BiologicallyDerivedProduct.collection.source | Equivalent | R5 `BiologicallyDerivedProduct.collection.source` maps as Equivalent to R4 `BiologicallyDerivedProduct.collection.source` |
| BiologicallyDerivedProduct.contained | BiologicallyDerivedProduct.contained | Equivalent | R5 `BiologicallyDerivedProduct.contained` maps as Equivalent to R4 `BiologicallyDerivedProduct.contained` |
| BiologicallyDerivedProduct.division | - | DoesNotExistInTarget | R5 `BiologicallyDerivedProduct.division` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.expirationDate | - | DoesNotExistInTarget | R5 `BiologicallyDerivedProduct.expirationDate` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.extension | BiologicallyDerivedProduct.extension | SourceIsBroaderThanTarget | R5 `BiologicallyDerivedProduct.extension` maps as SourceIsBroaderThanTarget to R4 `BiologicallyDerivedProduct.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| BiologicallyDerivedProduct.id | BiologicallyDerivedProduct.id | Equivalent | R5 `BiologicallyDerivedProduct.id` maps as Equivalent to R4 `BiologicallyDerivedProduct.id` |
| BiologicallyDerivedProduct.identifier | BiologicallyDerivedProduct.identifier | Equivalent | R5 `BiologicallyDerivedProduct.identifier` maps as Equivalent to R4 `BiologicallyDerivedProduct.identifier` |
| BiologicallyDerivedProduct.implicitRules | BiologicallyDerivedProduct.implicitRules | Equivalent | R5 `BiologicallyDerivedProduct.implicitRules` maps as Equivalent to R4 `BiologicallyDerivedProduct.implicitRules` |
| BiologicallyDerivedProduct.language | BiologicallyDerivedProduct.language | SourceIsNarrowerThanTarget | R5 `BiologicallyDerivedProduct.language` maps as SourceIsNarrowerThanTarget to R4 `BiologicallyDerivedProduct.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| BiologicallyDerivedProduct.meta | BiologicallyDerivedProduct.meta | Equivalent | R5 `BiologicallyDerivedProduct.meta` maps as Equivalent to R4 `BiologicallyDerivedProduct.meta` |
| BiologicallyDerivedProduct.modifierExtension | BiologicallyDerivedProduct.modifierExtension | SourceIsBroaderThanTarget | R5 `BiologicallyDerivedProduct.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `BiologicallyDerivedProduct.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| BiologicallyDerivedProduct.parent | BiologicallyDerivedProduct.parent | Equivalent | R5 `BiologicallyDerivedProduct.parent` maps as Equivalent to R4 `BiologicallyDerivedProduct.parent` |
| BiologicallyDerivedProduct.processingFacility | - | DoesNotExistInTarget | R5 `BiologicallyDerivedProduct.processingFacility` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.productCategory | BiologicallyDerivedProduct.productCategory | RelatedTo | R5 `BiologicallyDerivedProduct.productCategory` maps as RelatedTo to R4 `BiologicallyDerivedProduct.productCategory` - productCategory made the binding required (from Example) for http://hl7.org/fhir/ValueSet/product-category|4.0.1; productCategory has change due to type change: R5 productCategory Coding has no equivalent or mapped type in R4 productCategory |
| BiologicallyDerivedProduct.productCode | BiologicallyDerivedProduct.productCode | Equivalent | R5 `BiologicallyDerivedProduct.productCode` maps as Equivalent to R4 `BiologicallyDerivedProduct.productCode` |
| BiologicallyDerivedProduct.productStatus | BiologicallyDerivedProduct.status | RelatedTo | R5 `BiologicallyDerivedProduct.productStatus` maps as RelatedTo to R4 `BiologicallyDerivedProduct.status` - status made the binding required (from Example) for http://hl7.org/fhir/ValueSet/product-status|4.0.1; status has change due to type change: R5 productStatus Coding has no equivalent or mapped type in R4 status |
| BiologicallyDerivedProduct.property | - | DoesNotExistInTarget | R5 `BiologicallyDerivedProduct.property` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.property.extension | - | DoesNotExistInTarget | R5 `BiologicallyDerivedProduct.property.extension` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.property.id | - | DoesNotExistInTarget | R5 `BiologicallyDerivedProduct.property.id` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.property.modifierExtension | - | DoesNotExistInTarget | R5 `BiologicallyDerivedProduct.property.modifierExtension` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.property.type | - | DoesNotExistInTarget | R5 `BiologicallyDerivedProduct.property.type` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.property.value[x] | - | DoesNotExistInTarget | R5 `BiologicallyDerivedProduct.property.value[x]` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.request | BiologicallyDerivedProduct.request | Equivalent | R5 `BiologicallyDerivedProduct.request` maps as Equivalent to R4 `BiologicallyDerivedProduct.request` |
| BiologicallyDerivedProduct.storageTempRequirements | - | DoesNotExistInTarget | R5 `BiologicallyDerivedProduct.storageTempRequirements` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.text | BiologicallyDerivedProduct.text | Equivalent | R5 `BiologicallyDerivedProduct.text` maps as Equivalent to R4 `BiologicallyDerivedProduct.text` |

