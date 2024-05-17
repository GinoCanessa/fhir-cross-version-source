Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | BiologicallyDerivedProduct |  | A biological material originating from a biological entity intended to be transplanted or infused into another (possibly the same) biological entity. | 33 | 19 |
| Target | BiologicallyDerivedProduct |  | A material substance originating from a biological entity intended to be transplanted or infused<br/>into another (possibly the same) biological entity. | 45 | 25 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 12 |
Equivalent | 4 |
RelatedTo | 17 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| BiologicallyDerivedProduct | BiologicallyDerivedProduct | Equivalent | R5 `BiologicallyDerivedProduct` maps as Equivalent to R4B `BiologicallyDerivedProduct` |
| BiologicallyDerivedProduct.biologicalSourceEvent | - | DoesNotExistInTarget | R5 `BiologicallyDerivedProduct.biologicalSourceEvent` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.collection | BiologicallyDerivedProduct.collection | Equivalent | R5 `BiologicallyDerivedProduct.collection` maps as Equivalent to R4B `BiologicallyDerivedProduct.collection` |
| BiologicallyDerivedProduct.collection.collected[x] | BiologicallyDerivedProduct.collection.collected[x] | Equivalent | R5 `BiologicallyDerivedProduct.collection.collected[x]` maps as Equivalent to R4B `BiologicallyDerivedProduct.collection.collected[x]` |
| BiologicallyDerivedProduct.collection.collector | BiologicallyDerivedProduct.collection.collector | Equivalent | R5 `BiologicallyDerivedProduct.collection.collector` maps as Equivalent to R4B `BiologicallyDerivedProduct.collection.collector` |
| BiologicallyDerivedProduct.collection.extension | BiologicallyDerivedProduct.collection.extension | SourceIsBroaderThanTarget | R5 `BiologicallyDerivedProduct.collection.extension` maps as SourceIsBroaderThanTarget to R4B `BiologicallyDerivedProduct.collection.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| BiologicallyDerivedProduct.collection.id | BiologicallyDerivedProduct.collection.id | Equivalent | R5 `BiologicallyDerivedProduct.collection.id` maps as Equivalent to R4B `BiologicallyDerivedProduct.collection.id` |
| BiologicallyDerivedProduct.collection.modifierExtension | BiologicallyDerivedProduct.collection.modifierExtension | SourceIsBroaderThanTarget | R5 `BiologicallyDerivedProduct.collection.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `BiologicallyDerivedProduct.collection.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| BiologicallyDerivedProduct.collection.source | BiologicallyDerivedProduct.collection.source | Equivalent | R5 `BiologicallyDerivedProduct.collection.source` maps as Equivalent to R4B `BiologicallyDerivedProduct.collection.source` |
| BiologicallyDerivedProduct.contained | BiologicallyDerivedProduct.contained | Equivalent | R5 `BiologicallyDerivedProduct.contained` maps as Equivalent to R4B `BiologicallyDerivedProduct.contained` |
| BiologicallyDerivedProduct.division | - | DoesNotExistInTarget | R5 `BiologicallyDerivedProduct.division` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.expirationDate | - | DoesNotExistInTarget | R5 `BiologicallyDerivedProduct.expirationDate` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.extension | BiologicallyDerivedProduct.extension | SourceIsBroaderThanTarget | R5 `BiologicallyDerivedProduct.extension` maps as SourceIsBroaderThanTarget to R4B `BiologicallyDerivedProduct.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| BiologicallyDerivedProduct.id | BiologicallyDerivedProduct.id | Equivalent | R5 `BiologicallyDerivedProduct.id` maps as Equivalent to R4B `BiologicallyDerivedProduct.id` |
| BiologicallyDerivedProduct.identifier | BiologicallyDerivedProduct.identifier | Equivalent | R5 `BiologicallyDerivedProduct.identifier` maps as Equivalent to R4B `BiologicallyDerivedProduct.identifier` |
| BiologicallyDerivedProduct.implicitRules | BiologicallyDerivedProduct.implicitRules | Equivalent | R5 `BiologicallyDerivedProduct.implicitRules` maps as Equivalent to R4B `BiologicallyDerivedProduct.implicitRules` |
| BiologicallyDerivedProduct.language | BiologicallyDerivedProduct.language | RelatedTo | R5 `BiologicallyDerivedProduct.language` maps as RelatedTo to R4B `BiologicallyDerivedProduct.language` - language changed the binding strength from Required to Preferred |
| BiologicallyDerivedProduct.meta | BiologicallyDerivedProduct.meta | Equivalent | R5 `BiologicallyDerivedProduct.meta` maps as Equivalent to R4B `BiologicallyDerivedProduct.meta` |
| BiologicallyDerivedProduct.modifierExtension | BiologicallyDerivedProduct.modifierExtension | SourceIsBroaderThanTarget | R5 `BiologicallyDerivedProduct.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `BiologicallyDerivedProduct.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| BiologicallyDerivedProduct.parent | BiologicallyDerivedProduct.parent | Equivalent | R5 `BiologicallyDerivedProduct.parent` maps as Equivalent to R4B `BiologicallyDerivedProduct.parent` |
| BiologicallyDerivedProduct.processingFacility | - | DoesNotExistInTarget | R5 `BiologicallyDerivedProduct.processingFacility` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.productCategory | BiologicallyDerivedProduct.productCategory | RelatedTo | R5 `BiologicallyDerivedProduct.productCategory` maps as RelatedTo to R4B `BiologicallyDerivedProduct.productCategory` - productCategory made the binding required (from Example) for http://hl7.org/fhir/ValueSet/product-category|4.3.0; productCategory has change due to type change: R5 productCategory Coding has no equivalent or mapped type in R4B productCategory |
| BiologicallyDerivedProduct.productCode | BiologicallyDerivedProduct.productCode | Equivalent | R5 `BiologicallyDerivedProduct.productCode` maps as Equivalent to R4B `BiologicallyDerivedProduct.productCode` |
| BiologicallyDerivedProduct.productStatus | - | DoesNotExistInTarget | R5 `BiologicallyDerivedProduct.productStatus` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.property | - | DoesNotExistInTarget | R5 `BiologicallyDerivedProduct.property` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.property.extension | - | DoesNotExistInTarget | R5 `BiologicallyDerivedProduct.property.extension` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.property.id | - | DoesNotExistInTarget | R5 `BiologicallyDerivedProduct.property.id` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.property.modifierExtension | - | DoesNotExistInTarget | R5 `BiologicallyDerivedProduct.property.modifierExtension` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.property.type | - | DoesNotExistInTarget | R5 `BiologicallyDerivedProduct.property.type` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.property.value[x] | - | DoesNotExistInTarget | R5 `BiologicallyDerivedProduct.property.value[x]` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.request | BiologicallyDerivedProduct.request | Equivalent | R5 `BiologicallyDerivedProduct.request` maps as Equivalent to R4B `BiologicallyDerivedProduct.request` |
| BiologicallyDerivedProduct.storageTempRequirements | - | DoesNotExistInTarget | R5 `BiologicallyDerivedProduct.storageTempRequirements` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.text | BiologicallyDerivedProduct.text | Equivalent | R5 `BiologicallyDerivedProduct.text` maps as Equivalent to R4B `BiologicallyDerivedProduct.text` |

