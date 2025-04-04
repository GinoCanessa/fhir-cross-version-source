Comparison of 
Generated at Friday, April 4, 2025 2:59:01 PM

### BiologicallyDerivedProduct

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | BiologicallyDerivedProduct |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/BiologicallyDerivedProduct` |
| Version | 5.0.0 |
| Description | A biological material originating from a biological entity intended to be transplanted or infused into another (possibly the same) biological entity. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2260` |
| Database Snapshot Count | `33` |
| Database Differential Count | `19` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `BiologicallyDerivedProduct` | `BiologicallyDerivedProduct` | `BiologicallyDerivedProduct` | BiologicallyDerivedProduct | This resource reflects an instance of a biologically derived product | 0..* | BiologicallyDerivedProduct |  |  |
| `BiologicallyDerivedProduct.biologicalSourceEvent` | `BiologicallyDerivedProduct.biologicalSourceEvent` | `biologicalSourceEvent` | BiologicallyDerivedProduct.biologicalSourceEvent | An identifier that supports traceability to the event during which material in this product from one or more biological entities was obtained or pooled | 0..1 | Identifier |  |  |
| `BiologicallyDerivedProduct.collection` | `BiologicallyDerivedProduct.collection` | `collection` | BiologicallyDerivedProduct.collection | How this product was collected | 0..1 | BackboneElement |  |  |
| `BiologicallyDerivedProduct.collection.collected[x]` | `BiologicallyDerivedProduct.collection.collected[x]` | `collected[x]` | BiologicallyDerivedProduct.collection.collected[x] | Time of product collection | 0..1 | dateTime, Period |  |  |
| `BiologicallyDerivedProduct.collection.collector` | `BiologicallyDerivedProduct.collection.collector` | `collector` | BiologicallyDerivedProduct.collection.collector | Individual performing collection | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole) |  |  |
| `BiologicallyDerivedProduct.collection.extension` | `BiologicallyDerivedProduct.collection.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `BiologicallyDerivedProduct.collection.id` | `BiologicallyDerivedProduct.collection.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `BiologicallyDerivedProduct.collection.modifierExtension` | `BiologicallyDerivedProduct.collection.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `BiologicallyDerivedProduct.collection.source` | `BiologicallyDerivedProduct.collection.source` | `source` | BiologicallyDerivedProduct.collection.source | The patient who underwent the medical procedure to collect the product or the organization that facilitated the collection | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `BiologicallyDerivedProduct.contained` | `BiologicallyDerivedProduct.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `BiologicallyDerivedProduct.division` | `BiologicallyDerivedProduct.division` | `division` | BiologicallyDerivedProduct.division | A unique identifier for an aliquot of a product | 0..1 | string |  |  |
| `BiologicallyDerivedProduct.expirationDate` | `BiologicallyDerivedProduct.expirationDate` | `expirationDate` | BiologicallyDerivedProduct.expirationDate | Date, and where relevant time, of expiration | 0..1 | dateTime |  |  |
| `BiologicallyDerivedProduct.extension` | `BiologicallyDerivedProduct.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `BiologicallyDerivedProduct.id` | `BiologicallyDerivedProduct.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `BiologicallyDerivedProduct.identifier` | `BiologicallyDerivedProduct.identifier` | `identifier` | BiologicallyDerivedProduct.identifier | Instance identifier | 0..* | Identifier |  |  |
| `BiologicallyDerivedProduct.implicitRules` | `BiologicallyDerivedProduct.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `BiologicallyDerivedProduct.language` | `BiologicallyDerivedProduct.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `BiologicallyDerivedProduct.meta` | `BiologicallyDerivedProduct.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `BiologicallyDerivedProduct.modifierExtension` | `BiologicallyDerivedProduct.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `BiologicallyDerivedProduct.parent` | `BiologicallyDerivedProduct.parent` | `parent` | BiologicallyDerivedProduct.parent | The parent biologically-derived product | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/BiologicallyDerivedProduct) |  |  |
| `BiologicallyDerivedProduct.processingFacility` | `BiologicallyDerivedProduct.processingFacility` | `processingFacility` | BiologicallyDerivedProduct.processingFacility | Processing facilities responsible for the labeling and distribution of this biologically derived product | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `BiologicallyDerivedProduct.productCategory` | `BiologicallyDerivedProduct.productCategory` | `productCategory` | BiologicallyDerivedProduct.productCategory | organ \| tissue \| fluid \| cells \| biologicalAgent | 0..1 | Coding | `Example` | `http://hl7.org/fhir/ValueSet/product-category` |
| `BiologicallyDerivedProduct.productCode` | `BiologicallyDerivedProduct.productCode` | `productCode` | BiologicallyDerivedProduct.productCode | A code that identifies the kind of this biologically derived product | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/biologicallyderived-productcodes` |
| `BiologicallyDerivedProduct.productStatus` | `BiologicallyDerivedProduct.productStatus` | `productStatus` | BiologicallyDerivedProduct.productStatus | available \| unavailable | 0..1 | Coding | `Example` | `http://hl7.org/fhir/ValueSet/biologicallyderived-product-status` |
| `BiologicallyDerivedProduct.property` | `BiologicallyDerivedProduct.property` | `property` | BiologicallyDerivedProduct.property | A property that is specific to this BiologicallyDerviedProduct instance | 0..* | BackboneElement |  |  |
| `BiologicallyDerivedProduct.property.extension` | `BiologicallyDerivedProduct.property.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `BiologicallyDerivedProduct.property.id` | `BiologicallyDerivedProduct.property.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `BiologicallyDerivedProduct.property.modifierExtension` | `BiologicallyDerivedProduct.property.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `BiologicallyDerivedProduct.property.type` | `BiologicallyDerivedProduct.property.type` | `type` | BiologicallyDerivedProduct.property.type | Code that specifies the property | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/biologicallyderived-product-property-type-codes` |
| `BiologicallyDerivedProduct.property.value[x]` | `BiologicallyDerivedProduct.property.value[x]` | `value[x]` | BiologicallyDerivedProduct.property.value[x] | Property values | 1..1 | Attachment, boolean, CodeableConcept, integer, Period, Quantity, Range, Ratio, string |  |  |
| `BiologicallyDerivedProduct.request` | `BiologicallyDerivedProduct.request` | `request` | BiologicallyDerivedProduct.request | Request to obtain and/or infuse this product | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/ServiceRequest) |  |  |
| `BiologicallyDerivedProduct.storageTempRequirements` | `BiologicallyDerivedProduct.storageTempRequirements` | `storageTempRequirements` | BiologicallyDerivedProduct.storageTempRequirements | Product storage temperature requirements | 0..1 | Range |  |  |
| `BiologicallyDerivedProduct.text` | `BiologicallyDerivedProduct.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [BiologicallyDerivedProduct](/docs/R4/Resources/BiologicallyDerivedProduct.md)<br/> `http://hl7.org/fhir/StructureDefinition/BiologicallyDerivedProduct\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1405`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1406`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [BiologicallyDerivedProduct](/docs/R4B/Resources/BiologicallyDerivedProduct.md)<br/> `http://hl7.org/fhir/StructureDefinition/BiologicallyDerivedProduct\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `937`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1166`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [BiologicallyDerivedProduct](/docs/R5/Resources/BiologicallyDerivedProduct.md)<br/> `http://hl7.org/fhir/StructureDefinition/BiologicallyDerivedProduct\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition BiologicallyDerivedProduct from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | [R4 BiologicallyDerivedProduct](/docs/R4/Resources/BiologicallyDerivedProduct.md)| Relationship | [R4B BiologicallyDerivedProduct](/docs/R4B/Resources/BiologicallyDerivedProduct.md)| Relationship | R5 BiologicallyDerivedProduct
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | `BiologicallyDerivedProduct`| _Equivalent_<br/>(22018/22019)| `BiologicallyDerivedProduct`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(37095)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(37096)| **`BiologicallyDerivedProduct`**
| | | | | `BiologicallyDerivedProduct.id`| _Equivalent_<br/>(22020/22021)| `BiologicallyDerivedProduct.id`| _Equivalent_<br/>(37097/37098)| **`BiologicallyDerivedProduct.id`**
| | | | | `BiologicallyDerivedProduct.meta`| _Equivalent_<br/>(22022/22023)| `BiologicallyDerivedProduct.meta`| _Equivalent_<br/>(37099/37100)| **`BiologicallyDerivedProduct.meta`**
| | | | | `BiologicallyDerivedProduct.implicitRules`| _Equivalent_<br/>(22024/22025)| `BiologicallyDerivedProduct.implicitRules`| _Equivalent_<br/>(37101/37102)| **`BiologicallyDerivedProduct.implicitRules`**
| | | | | `BiologicallyDerivedProduct.language`| _Equivalent_<br/>(22026/22027)| `BiologicallyDerivedProduct.language`| _Equivalent_<br/>(37103/37104)| **`BiologicallyDerivedProduct.language`**
| | | | | `BiologicallyDerivedProduct.text`| _Equivalent_<br/>(22028/22029)| `BiologicallyDerivedProduct.text`| _Equivalent_<br/>(37105/37106)| **`BiologicallyDerivedProduct.text`**
| | | | | `BiologicallyDerivedProduct.contained`| _Equivalent_<br/>(22030/22031)| `BiologicallyDerivedProduct.contained`| _Equivalent_<br/>(37107/37108)| **`BiologicallyDerivedProduct.contained`**
| | | | | `BiologicallyDerivedProduct.extension`| _Equivalent_<br/>(22032/22033)| `BiologicallyDerivedProduct.extension`| _Equivalent_<br/>(37109/37110)| **`BiologicallyDerivedProduct.extension`**
| | | | | `BiologicallyDerivedProduct.modifierExtension`| _Equivalent_<br/>(22034/22035)| `BiologicallyDerivedProduct.modifierExtension`| _Equivalent_<br/>(37111/37112)| **`BiologicallyDerivedProduct.modifierExtension`**
| | | | | `BiologicallyDerivedProduct.productCategory`| _Equivalent_<br/>(22038/22039)| `BiologicallyDerivedProduct.productCategory`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(37115)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(37116)| **`BiologicallyDerivedProduct.productCategory`**
| | | | | `BiologicallyDerivedProduct.productCode`| _Equivalent_<br/>(22040/22041)| `BiologicallyDerivedProduct.productCode`| _Equivalent_<br/>(37117/37118)| **`BiologicallyDerivedProduct.productCode`**
| | | | | `BiologicallyDerivedProduct.parent`| _Equivalent_<br/>(22048/22049)| `BiologicallyDerivedProduct.parent`| _Equivalent_<br/>(37123/37124)| **`BiologicallyDerivedProduct.parent`**
| | | | | `BiologicallyDerivedProduct.request`| _Equivalent_<br/>(22044/22045)| `BiologicallyDerivedProduct.request`| _Equivalent_<br/>(37120/37121)| **`BiologicallyDerivedProduct.request`**
| | | | | `BiologicallyDerivedProduct.identifier`| _Equivalent_<br/>(22036/22037)| `BiologicallyDerivedProduct.identifier`| _Equivalent_<br/>(37113/37114)| **`BiologicallyDerivedProduct.identifier`**
| | | | | | | | | **`BiologicallyDerivedProduct.biologicalSourceEvent`**
| | | | | | | | | **`BiologicallyDerivedProduct.processingFacility`**
| | | | | | | | | **`BiologicallyDerivedProduct.division`**
| | | | | | | | | **`BiologicallyDerivedProduct.productStatus`**
| | | | | | | | | **`BiologicallyDerivedProduct.expirationDate`**
| | | | | `BiologicallyDerivedProduct.collection`| _Equivalent_<br/>(22050/22051)| `BiologicallyDerivedProduct.collection`| _Equivalent_<br/>(37125/37126)| **`BiologicallyDerivedProduct.collection`**
| | | | | `BiologicallyDerivedProduct.collection.id`| _Equivalent_<br/>(22052/22053)| `BiologicallyDerivedProduct.collection.id`| _Equivalent_<br/>(37127/37128)| **`BiologicallyDerivedProduct.collection.id`**
| | | | | `BiologicallyDerivedProduct.collection.extension`| _Equivalent_<br/>(22054/22055)| `BiologicallyDerivedProduct.collection.extension`| _Equivalent_<br/>(37129/37130)| **`BiologicallyDerivedProduct.collection.extension`**
| | | | | `BiologicallyDerivedProduct.collection.modifierExtension`| _Equivalent_<br/>(22056/22057)| `BiologicallyDerivedProduct.collection.modifierExtension`| _Equivalent_<br/>(37131/37132)| **`BiologicallyDerivedProduct.collection.modifierExtension`**
| | | | | `BiologicallyDerivedProduct.collection.collector`| _Equivalent_<br/>(22058/22059)| `BiologicallyDerivedProduct.collection.collector`| _Equivalent_<br/>(37133/37134)| **`BiologicallyDerivedProduct.collection.collector`**
| | | | | `BiologicallyDerivedProduct.collection.source`| _Equivalent_<br/>(22060/22061)| `BiologicallyDerivedProduct.collection.source`| _Equivalent_<br/>(37135/37136)| **`BiologicallyDerivedProduct.collection.source`**
| | | | | `BiologicallyDerivedProduct.collection.collected[x]`| _Equivalent_<br/>(22062/22063)| `BiologicallyDerivedProduct.collection.collected[x]`| _Equivalent_<br/>(37137/37138)| **`BiologicallyDerivedProduct.collection.collected[x]`**
| | | | | | | | | **`BiologicallyDerivedProduct.storageTempRequirements`**
| | | | | | | | | **`BiologicallyDerivedProduct.property`**
| | | | | | | | | **`BiologicallyDerivedProduct.property.id`**
| | | | | | | | | **`BiologicallyDerivedProduct.property.extension`**
| | | | | | | | | **`BiologicallyDerivedProduct.property.modifierExtension`**
| | | | | | | | | **`BiologicallyDerivedProduct.property.type`**
| | | | | | | | | **`BiologicallyDerivedProduct.property.value[x]`**
| | | | | *21 of 45 elements used* <br/>remaining elements:<br/>`BiologicallyDerivedProduct.manipulation`, `BiologicallyDerivedProduct.manipulation.description`, `BiologicallyDerivedProduct.manipulation.extension`, `BiologicallyDerivedProduct.manipulation.id`, `BiologicallyDerivedProduct.manipulation.modifierExtension`, `BiologicallyDerivedProduct.manipulation.time[x]`, `BiologicallyDerivedProduct.processing`, `BiologicallyDerivedProduct.processing.additive`, `BiologicallyDerivedProduct.processing.description`, `BiologicallyDerivedProduct.processing.extension`, `BiologicallyDerivedProduct.processing.id`, `BiologicallyDerivedProduct.processing.modifierExtension`, `BiologicallyDerivedProduct.processing.procedure`, `BiologicallyDerivedProduct.processing.time[x]`, `BiologicallyDerivedProduct.quantity`, `BiologicallyDerivedProduct.status`, `BiologicallyDerivedProduct.storage`, `BiologicallyDerivedProduct.storage.description`, `BiologicallyDerivedProduct.storage.duration`, `BiologicallyDerivedProduct.storage.extension`, `BiologicallyDerivedProduct.storage.id`, `BiologicallyDerivedProduct.storage.modifierExtension`, `BiologicallyDerivedProduct.storage.scale`, `BiologicallyDerivedProduct.storage.temperature`| | *21 of 45 elements used* <br/>remaining elements:<br/>`BiologicallyDerivedProduct.manipulation`, `BiologicallyDerivedProduct.manipulation.description`, `BiologicallyDerivedProduct.manipulation.extension`, `BiologicallyDerivedProduct.manipulation.id`, `BiologicallyDerivedProduct.manipulation.modifierExtension`, `BiologicallyDerivedProduct.manipulation.time[x]`, `BiologicallyDerivedProduct.processing`, `BiologicallyDerivedProduct.processing.additive`, `BiologicallyDerivedProduct.processing.description`, `BiologicallyDerivedProduct.processing.extension`, `BiologicallyDerivedProduct.processing.id`, `BiologicallyDerivedProduct.processing.modifierExtension`, `BiologicallyDerivedProduct.processing.procedure`, `BiologicallyDerivedProduct.processing.time[x]`, `BiologicallyDerivedProduct.quantity`, `BiologicallyDerivedProduct.status`, `BiologicallyDerivedProduct.storage`, `BiologicallyDerivedProduct.storage.description`, `BiologicallyDerivedProduct.storage.duration`, `BiologicallyDerivedProduct.storage.extension`, `BiologicallyDerivedProduct.storage.id`, `BiologicallyDerivedProduct.storage.modifierExtension`, `BiologicallyDerivedProduct.storage.scale`, `BiologicallyDerivedProduct.storage.temperature`| | *33 of 33 elements used* 

