Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | BiologicallyDerivedProduct |  | A material substance originating from a biological entity intended to be transplanted or infused<br/>into another (possibly the same) biological entity. | 45 | 25 |
| Target | BiologicallyDerivedProduct |  | A biological material originating from a biological entity intended to be transplanted or infused into another (possibly the same) biological entity. | 33 | 19 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 24 |
Equivalent | 4 |
RelatedTo | 17 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| BiologicallyDerivedProduct | BiologicallyDerivedProduct | Equivalent | R4B `BiologicallyDerivedProduct` maps as Equivalent to R5 `BiologicallyDerivedProduct` |
| BiologicallyDerivedProduct.collection | BiologicallyDerivedProduct.collection | Equivalent | R4B `BiologicallyDerivedProduct.collection` maps as Equivalent to R5 `BiologicallyDerivedProduct.collection` |
| BiologicallyDerivedProduct.collection.collected[x] | BiologicallyDerivedProduct.collection.collected[x] | Equivalent | R4B `BiologicallyDerivedProduct.collection.collected[x]` maps as Equivalent to R5 `BiologicallyDerivedProduct.collection.collected[x]` |
| BiologicallyDerivedProduct.collection.collector | BiologicallyDerivedProduct.collection.collector | Equivalent | R4B `BiologicallyDerivedProduct.collection.collector` maps as Equivalent to R5 `BiologicallyDerivedProduct.collection.collector` |
| BiologicallyDerivedProduct.collection.extension | BiologicallyDerivedProduct.collection.extension | RelatedTo | R4B `BiologicallyDerivedProduct.collection.extension` maps as RelatedTo to R5 `BiologicallyDerivedProduct.collection.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| BiologicallyDerivedProduct.collection.id | BiologicallyDerivedProduct.collection.id | Equivalent | R4B `BiologicallyDerivedProduct.collection.id` maps as Equivalent to R5 `BiologicallyDerivedProduct.collection.id` |
| BiologicallyDerivedProduct.collection.modifierExtension | BiologicallyDerivedProduct.collection.modifierExtension | RelatedTo | R4B `BiologicallyDerivedProduct.collection.modifierExtension` maps as RelatedTo to R5 `BiologicallyDerivedProduct.collection.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| BiologicallyDerivedProduct.collection.source | BiologicallyDerivedProduct.collection.source | Equivalent | R4B `BiologicallyDerivedProduct.collection.source` maps as Equivalent to R5 `BiologicallyDerivedProduct.collection.source` |
| BiologicallyDerivedProduct.contained | BiologicallyDerivedProduct.contained | Equivalent | R4B `BiologicallyDerivedProduct.contained` maps as Equivalent to R5 `BiologicallyDerivedProduct.contained` |
| BiologicallyDerivedProduct.extension | BiologicallyDerivedProduct.extension | RelatedTo | R4B `BiologicallyDerivedProduct.extension` maps as RelatedTo to R5 `BiologicallyDerivedProduct.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| BiologicallyDerivedProduct.id | BiologicallyDerivedProduct.id | Equivalent | R4B `BiologicallyDerivedProduct.id` maps as Equivalent to R5 `BiologicallyDerivedProduct.id` |
| BiologicallyDerivedProduct.identifier | BiologicallyDerivedProduct.identifier | Equivalent | R4B `BiologicallyDerivedProduct.identifier` maps as Equivalent to R5 `BiologicallyDerivedProduct.identifier` |
| BiologicallyDerivedProduct.implicitRules | BiologicallyDerivedProduct.implicitRules | Equivalent | R4B `BiologicallyDerivedProduct.implicitRules` maps as Equivalent to R5 `BiologicallyDerivedProduct.implicitRules` |
| BiologicallyDerivedProduct.language | BiologicallyDerivedProduct.language | RelatedTo | R4B `BiologicallyDerivedProduct.language` maps as RelatedTo to R5 `BiologicallyDerivedProduct.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| BiologicallyDerivedProduct.manipulation | - | DoesNotExistInTarget | R4B `BiologicallyDerivedProduct.manipulation` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.manipulation.description | - | DoesNotExistInTarget | R4B `BiologicallyDerivedProduct.manipulation.description` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.manipulation.extension | - | DoesNotExistInTarget | R4B `BiologicallyDerivedProduct.manipulation.extension` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.manipulation.id | - | DoesNotExistInTarget | R4B `BiologicallyDerivedProduct.manipulation.id` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.manipulation.modifierExtension | - | DoesNotExistInTarget | R4B `BiologicallyDerivedProduct.manipulation.modifierExtension` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.manipulation.time[x] | - | DoesNotExistInTarget | R4B `BiologicallyDerivedProduct.manipulation.time[x]` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.meta | BiologicallyDerivedProduct.meta | Equivalent | R4B `BiologicallyDerivedProduct.meta` maps as Equivalent to R5 `BiologicallyDerivedProduct.meta` |
| BiologicallyDerivedProduct.modifierExtension | BiologicallyDerivedProduct.modifierExtension | RelatedTo | R4B `BiologicallyDerivedProduct.modifierExtension` maps as RelatedTo to R5 `BiologicallyDerivedProduct.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| BiologicallyDerivedProduct.parent | BiologicallyDerivedProduct.parent | Equivalent | R4B `BiologicallyDerivedProduct.parent` maps as Equivalent to R5 `BiologicallyDerivedProduct.parent` |
| BiologicallyDerivedProduct.processing | - | DoesNotExistInTarget | R4B `BiologicallyDerivedProduct.processing` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.processing.additive | - | DoesNotExistInTarget | R4B `BiologicallyDerivedProduct.processing.additive` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.processing.description | - | DoesNotExistInTarget | R4B `BiologicallyDerivedProduct.processing.description` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.processing.extension | - | DoesNotExistInTarget | R4B `BiologicallyDerivedProduct.processing.extension` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.processing.id | - | DoesNotExistInTarget | R4B `BiologicallyDerivedProduct.processing.id` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.processing.modifierExtension | - | DoesNotExistInTarget | R4B `BiologicallyDerivedProduct.processing.modifierExtension` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.processing.procedure | - | DoesNotExistInTarget | R4B `BiologicallyDerivedProduct.processing.procedure` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.processing.time[x] | - | DoesNotExistInTarget | R4B `BiologicallyDerivedProduct.processing.time[x]` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.productCategory | BiologicallyDerivedProduct.productCategory | RelatedTo | R4B `BiologicallyDerivedProduct.productCategory` maps as RelatedTo to R5 `BiologicallyDerivedProduct.productCategory` - productCategory changed the binding strength from Required to Example; productCategory has change due to type change: R4B productCategory code has no equivalent or mapped type in R5 productCategory |
| BiologicallyDerivedProduct.productCode | BiologicallyDerivedProduct.productCode | Equivalent | R4B `BiologicallyDerivedProduct.productCode` maps as Equivalent to R5 `BiologicallyDerivedProduct.productCode` |
| BiologicallyDerivedProduct.quantity | - | DoesNotExistInTarget | R4B `BiologicallyDerivedProduct.quantity` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.request | BiologicallyDerivedProduct.request | Equivalent | R4B `BiologicallyDerivedProduct.request` maps as Equivalent to R5 `BiologicallyDerivedProduct.request` |
| BiologicallyDerivedProduct.status | - | DoesNotExistInTarget | R4B `BiologicallyDerivedProduct.status` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.storage | - | DoesNotExistInTarget | R4B `BiologicallyDerivedProduct.storage` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.storage.description | - | DoesNotExistInTarget | R4B `BiologicallyDerivedProduct.storage.description` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.storage.duration | - | DoesNotExistInTarget | R4B `BiologicallyDerivedProduct.storage.duration` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.storage.extension | - | DoesNotExistInTarget | R4B `BiologicallyDerivedProduct.storage.extension` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.storage.id | - | DoesNotExistInTarget | R4B `BiologicallyDerivedProduct.storage.id` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.storage.modifierExtension | - | DoesNotExistInTarget | R4B `BiologicallyDerivedProduct.storage.modifierExtension` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.storage.scale | - | DoesNotExistInTarget | R4B `BiologicallyDerivedProduct.storage.scale` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.storage.temperature | - | DoesNotExistInTarget | R4B `BiologicallyDerivedProduct.storage.temperature` does not appear in the target and has no mapping for `BiologicallyDerivedProduct`. |
| BiologicallyDerivedProduct.text | BiologicallyDerivedProduct.text | Equivalent | R4B `BiologicallyDerivedProduct.text` maps as Equivalent to R5 `BiologicallyDerivedProduct.text` |

