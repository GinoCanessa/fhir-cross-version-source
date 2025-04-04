Comparison of 
Generated at Friday, April 4, 2025 2:58:53 PM

### BiologicallyDerivedProduct

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| Stucture Name | BiologicallyDerivedProduct |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/BiologicallyDerivedProduct` |
| Version | 4.3.0 |
| Description | A material substance originating from a biological entity intended to be transplanted or infused<br/>into another (possibly the same) biological entity. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1648` |
| Database Snapshot Count | `45` |
| Database Differential Count | `25` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `BiologicallyDerivedProduct` | `BiologicallyDerivedProduct` | `BiologicallyDerivedProduct` | BiologicallyDerivedProduct | A material substance originating from a biological entity | 0..* | BiologicallyDerivedProduct |  |  |
| `BiologicallyDerivedProduct.collection` | `BiologicallyDerivedProduct.collection` | `collection` | BiologicallyDerivedProduct.collection | How this product was collected | 0..1 | BackboneElement |  |  |
| `BiologicallyDerivedProduct.collection.collected[x]` | `BiologicallyDerivedProduct.collection.collected[x]` | `collected[x]` | BiologicallyDerivedProduct.collection.collected[x] | Time of product collection | 0..1 | dateTime, Period |  |  |
| `BiologicallyDerivedProduct.collection.collector` | `BiologicallyDerivedProduct.collection.collector` | `collector` | BiologicallyDerivedProduct.collection.collector | Individual performing collection | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole) |  |  |
| `BiologicallyDerivedProduct.collection.extension` | `BiologicallyDerivedProduct.collection.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `BiologicallyDerivedProduct.collection.id` | `BiologicallyDerivedProduct.collection.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `BiologicallyDerivedProduct.collection.modifierExtension` | `BiologicallyDerivedProduct.collection.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `BiologicallyDerivedProduct.collection.source` | `BiologicallyDerivedProduct.collection.source` | `source` | BiologicallyDerivedProduct.collection.source | Who is product from | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `BiologicallyDerivedProduct.contained` | `BiologicallyDerivedProduct.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `BiologicallyDerivedProduct.extension` | `BiologicallyDerivedProduct.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `BiologicallyDerivedProduct.id` | `BiologicallyDerivedProduct.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `BiologicallyDerivedProduct.identifier` | `BiologicallyDerivedProduct.identifier` | `identifier` | BiologicallyDerivedProduct.identifier | External ids for this item | 0..* | Identifier |  |  |
| `BiologicallyDerivedProduct.implicitRules` | `BiologicallyDerivedProduct.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `BiologicallyDerivedProduct.language` | `BiologicallyDerivedProduct.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `BiologicallyDerivedProduct.manipulation` | `BiologicallyDerivedProduct.manipulation` | `manipulation` | BiologicallyDerivedProduct.manipulation | Any manipulation of product post-collection | 0..1 | BackboneElement |  |  |
| `BiologicallyDerivedProduct.manipulation.description` | `BiologicallyDerivedProduct.manipulation.description` | `description` | BiologicallyDerivedProduct.manipulation.description | Description of manipulation | 0..1 | string |  |  |
| `BiologicallyDerivedProduct.manipulation.extension` | `BiologicallyDerivedProduct.manipulation.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `BiologicallyDerivedProduct.manipulation.id` | `BiologicallyDerivedProduct.manipulation.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `BiologicallyDerivedProduct.manipulation.modifierExtension` | `BiologicallyDerivedProduct.manipulation.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `BiologicallyDerivedProduct.manipulation.time[x]` | `BiologicallyDerivedProduct.manipulation.time[x]` | `time[x]` | BiologicallyDerivedProduct.manipulation.time[x] | Time of manipulation | 0..1 | dateTime, Period |  |  |
| `BiologicallyDerivedProduct.meta` | `BiologicallyDerivedProduct.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `BiologicallyDerivedProduct.modifierExtension` | `BiologicallyDerivedProduct.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `BiologicallyDerivedProduct.parent` | `BiologicallyDerivedProduct.parent` | `parent` | BiologicallyDerivedProduct.parent | BiologicallyDerivedProduct parent | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/BiologicallyDerivedProduct) |  |  |
| `BiologicallyDerivedProduct.processing` | `BiologicallyDerivedProduct.processing` | `processing` | BiologicallyDerivedProduct.processing | Any processing of the product during collection | 0..* | BackboneElement |  |  |
| `BiologicallyDerivedProduct.processing.additive` | `BiologicallyDerivedProduct.processing.additive` | `additive` | BiologicallyDerivedProduct.processing.additive | Substance added during processing | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Substance) |  |  |
| `BiologicallyDerivedProduct.processing.description` | `BiologicallyDerivedProduct.processing.description` | `description` | BiologicallyDerivedProduct.processing.description | Description of of processing | 0..1 | string |  |  |
| `BiologicallyDerivedProduct.processing.extension` | `BiologicallyDerivedProduct.processing.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `BiologicallyDerivedProduct.processing.id` | `BiologicallyDerivedProduct.processing.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `BiologicallyDerivedProduct.processing.modifierExtension` | `BiologicallyDerivedProduct.processing.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `BiologicallyDerivedProduct.processing.procedure` | `BiologicallyDerivedProduct.processing.procedure` | `procedure` | BiologicallyDerivedProduct.processing.procedure | Procesing code | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/procedure-code` |
| `BiologicallyDerivedProduct.processing.time[x]` | `BiologicallyDerivedProduct.processing.time[x]` | `time[x]` | BiologicallyDerivedProduct.processing.time[x] | Time of processing | 0..1 | dateTime, Period |  |  |
| `BiologicallyDerivedProduct.productCategory` | `BiologicallyDerivedProduct.productCategory` | `productCategory` | BiologicallyDerivedProduct.productCategory | organ \| tissue \| fluid \| cells \| biologicalAgent | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/product-category|4.3.0` |
| `BiologicallyDerivedProduct.productCode` | `BiologicallyDerivedProduct.productCode` | `productCode` | BiologicallyDerivedProduct.productCode | What this biologically derived product is | 0..1 | CodeableConcept | `Example` |  |
| `BiologicallyDerivedProduct.quantity` | `BiologicallyDerivedProduct.quantity` | `quantity` | BiologicallyDerivedProduct.quantity | The amount of this biologically derived product | 0..1 | integer |  |  |
| `BiologicallyDerivedProduct.request` | `BiologicallyDerivedProduct.request` | `request` | BiologicallyDerivedProduct.request | Procedure request | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/ServiceRequest) |  |  |
| `BiologicallyDerivedProduct.status` | `BiologicallyDerivedProduct.status` | `status` | BiologicallyDerivedProduct.status | available \| unavailable | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/product-status|4.3.0` |
| `BiologicallyDerivedProduct.storage` | `BiologicallyDerivedProduct.storage` | `storage` | BiologicallyDerivedProduct.storage | Product storage | 0..* | BackboneElement |  |  |
| `BiologicallyDerivedProduct.storage.description` | `BiologicallyDerivedProduct.storage.description` | `description` | BiologicallyDerivedProduct.storage.description | Description of storage | 0..1 | string |  |  |
| `BiologicallyDerivedProduct.storage.duration` | `BiologicallyDerivedProduct.storage.duration` | `duration` | BiologicallyDerivedProduct.storage.duration | Storage timeperiod | 0..1 | Period |  |  |
| `BiologicallyDerivedProduct.storage.extension` | `BiologicallyDerivedProduct.storage.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `BiologicallyDerivedProduct.storage.id` | `BiologicallyDerivedProduct.storage.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `BiologicallyDerivedProduct.storage.modifierExtension` | `BiologicallyDerivedProduct.storage.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `BiologicallyDerivedProduct.storage.scale` | `BiologicallyDerivedProduct.storage.scale` | `scale` | BiologicallyDerivedProduct.storage.scale | farenheit \| celsius \| kelvin | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/product-storage-scale|4.3.0` |
| `BiologicallyDerivedProduct.storage.temperature` | `BiologicallyDerivedProduct.storage.temperature` | `temperature` | BiologicallyDerivedProduct.storage.temperature | Storage temperature | 0..1 | decimal |  |  |
| `BiologicallyDerivedProduct.text` | `BiologicallyDerivedProduct.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [BiologicallyDerivedProduct](/docs/R4/Resources/BiologicallyDerivedProduct.md)<br/> `http://hl7.org/fhir/StructureDefinition/BiologicallyDerivedProduct\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1405`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1406`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [BiologicallyDerivedProduct](/docs/R4B/Resources/BiologicallyDerivedProduct.md)<br/> `http://hl7.org/fhir/StructureDefinition/BiologicallyDerivedProduct\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `937`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1166`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [BiologicallyDerivedProduct](/docs/R5/Resources/BiologicallyDerivedProduct.md)<br/> `http://hl7.org/fhir/StructureDefinition/BiologicallyDerivedProduct\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition BiologicallyDerivedProduct from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | [R4 BiologicallyDerivedProduct](/docs/R4/Resources/BiologicallyDerivedProduct.md)| Relationship | R4B BiologicallyDerivedProduct| Relationship | [R5 BiologicallyDerivedProduct](/docs/R5/Resources/BiologicallyDerivedProduct.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | `BiologicallyDerivedProduct`| _Equivalent_<br/>(22018/22019)| **`BiologicallyDerivedProduct`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(37095)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(37096)| `BiologicallyDerivedProduct`
| | | | | `BiologicallyDerivedProduct.id`| _Equivalent_<br/>(22020/22021)| **`BiologicallyDerivedProduct.id`**| _Equivalent_<br/>(37097/37098)| `BiologicallyDerivedProduct.id`
| | | | | `BiologicallyDerivedProduct.meta`| _Equivalent_<br/>(22022/22023)| **`BiologicallyDerivedProduct.meta`**| _Equivalent_<br/>(37099/37100)| `BiologicallyDerivedProduct.meta`
| | | | | `BiologicallyDerivedProduct.implicitRules`| _Equivalent_<br/>(22024/22025)| **`BiologicallyDerivedProduct.implicitRules`**| _Equivalent_<br/>(37101/37102)| `BiologicallyDerivedProduct.implicitRules`
| | | | | `BiologicallyDerivedProduct.language`| _Equivalent_<br/>(22026/22027)| **`BiologicallyDerivedProduct.language`**| _Equivalent_<br/>(37103/37104)| `BiologicallyDerivedProduct.language`
| | | | | `BiologicallyDerivedProduct.text`| _Equivalent_<br/>(22028/22029)| **`BiologicallyDerivedProduct.text`**| _Equivalent_<br/>(37105/37106)| `BiologicallyDerivedProduct.text`
| | | | | `BiologicallyDerivedProduct.contained`| _Equivalent_<br/>(22030/22031)| **`BiologicallyDerivedProduct.contained`**| _Equivalent_<br/>(37107/37108)| `BiologicallyDerivedProduct.contained`
| | | | | `BiologicallyDerivedProduct.extension`| _Equivalent_<br/>(22032/22033)| **`BiologicallyDerivedProduct.extension`**| _Equivalent_<br/>(37109/37110)| `BiologicallyDerivedProduct.extension`
| | | | | `BiologicallyDerivedProduct.modifierExtension`| _Equivalent_<br/>(22034/22035)| **`BiologicallyDerivedProduct.modifierExtension`**| _Equivalent_<br/>(37111/37112)| `BiologicallyDerivedProduct.modifierExtension`
| | | | | `BiologicallyDerivedProduct.identifier`| _Equivalent_<br/>(22036/22037)| **`BiologicallyDerivedProduct.identifier`**| _Equivalent_<br/>(37113/37114)| `BiologicallyDerivedProduct.identifier`
| | | | | `BiologicallyDerivedProduct.productCategory`| _Equivalent_<br/>(22038/22039)| **`BiologicallyDerivedProduct.productCategory`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(37115)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(37116)| `BiologicallyDerivedProduct.productCategory`
| | | | | `BiologicallyDerivedProduct.productCode`| _Equivalent_<br/>(22040/22041)| **`BiologicallyDerivedProduct.productCode`**| _Equivalent_<br/>(37117/37118)| `BiologicallyDerivedProduct.productCode`
| | | | | `BiologicallyDerivedProduct.status`| _Equivalent_<br/>(22042/22043)| **`BiologicallyDerivedProduct.status`**| | | 
| | | | | `BiologicallyDerivedProduct.request`| _Equivalent_<br/>(22044/22045)| **`BiologicallyDerivedProduct.request`**| _Equivalent_<br/>(37120/37121)| `BiologicallyDerivedProduct.request`
| | | | | `BiologicallyDerivedProduct.quantity`| _Equivalent_<br/>(22046/22047)| **`BiologicallyDerivedProduct.quantity`**| | | 
| | | | | `BiologicallyDerivedProduct.parent`| _Equivalent_<br/>(22048/22049)| **`BiologicallyDerivedProduct.parent`**| _Equivalent_<br/>(37123/37124)| `BiologicallyDerivedProduct.parent`
| | | | | `BiologicallyDerivedProduct.collection`| _Equivalent_<br/>(22050/22051)| **`BiologicallyDerivedProduct.collection`**| _Equivalent_<br/>(37125/37126)| `BiologicallyDerivedProduct.collection`
| | | | | `BiologicallyDerivedProduct.collection.id`| _Equivalent_<br/>(22052/22053)| **`BiologicallyDerivedProduct.collection.id`**| _Equivalent_<br/>(37127/37128)| `BiologicallyDerivedProduct.collection.id`
| | | | | `BiologicallyDerivedProduct.collection.extension`| _Equivalent_<br/>(22054/22055)| **`BiologicallyDerivedProduct.collection.extension`**| _Equivalent_<br/>(37129/37130)| `BiologicallyDerivedProduct.collection.extension`
| | | | | `BiologicallyDerivedProduct.collection.modifierExtension`| _Equivalent_<br/>(22056/22057)| **`BiologicallyDerivedProduct.collection.modifierExtension`**| _Equivalent_<br/>(37131/37132)| `BiologicallyDerivedProduct.collection.modifierExtension`
| | | | | `BiologicallyDerivedProduct.collection.collector`| _Equivalent_<br/>(22058/22059)| **`BiologicallyDerivedProduct.collection.collector`**| _Equivalent_<br/>(37133/37134)| `BiologicallyDerivedProduct.collection.collector`
| | | | | `BiologicallyDerivedProduct.collection.source`| _Equivalent_<br/>(22060/22061)| **`BiologicallyDerivedProduct.collection.source`**| _Equivalent_<br/>(37135/37136)| `BiologicallyDerivedProduct.collection.source`
| | | | | `BiologicallyDerivedProduct.collection.collected[x]`| _Equivalent_<br/>(22062/22063)| **`BiologicallyDerivedProduct.collection.collected[x]`**| _Equivalent_<br/>(37137/37138)| `BiologicallyDerivedProduct.collection.collected[x]`
| | | | | `BiologicallyDerivedProduct.processing`| _Equivalent_<br/>(22064/22065)| **`BiologicallyDerivedProduct.processing`**| | | 
| | | | | `BiologicallyDerivedProduct.processing.id`| _Equivalent_<br/>(22066/22067)| **`BiologicallyDerivedProduct.processing.id`**| | | 
| | | | | `BiologicallyDerivedProduct.processing.extension`| _Equivalent_<br/>(22068/22069)| **`BiologicallyDerivedProduct.processing.extension`**| | | 
| | | | | `BiologicallyDerivedProduct.processing.modifierExtension`| _Equivalent_<br/>(22070/22071)| **`BiologicallyDerivedProduct.processing.modifierExtension`**| | | 
| | | | | `BiologicallyDerivedProduct.processing.description`| _Equivalent_<br/>(22072/22073)| **`BiologicallyDerivedProduct.processing.description`**| | | 
| | | | | `BiologicallyDerivedProduct.processing.procedure`| _Equivalent_<br/>(22074/22075)| **`BiologicallyDerivedProduct.processing.procedure`**| | | 
| | | | | `BiologicallyDerivedProduct.processing.additive`| _Equivalent_<br/>(22076/22077)| **`BiologicallyDerivedProduct.processing.additive`**| | | 
| | | | | `BiologicallyDerivedProduct.processing.time[x]`| _Equivalent_<br/>(22078/22079)| **`BiologicallyDerivedProduct.processing.time[x]`**| | | 
| | | | | `BiologicallyDerivedProduct.manipulation`| _Equivalent_<br/>(22080/22081)| **`BiologicallyDerivedProduct.manipulation`**| | | 
| | | | | `BiologicallyDerivedProduct.manipulation.id`| _Equivalent_<br/>(22082/22083)| **`BiologicallyDerivedProduct.manipulation.id`**| | | 
| | | | | `BiologicallyDerivedProduct.manipulation.extension`| _Equivalent_<br/>(22084/22085)| **`BiologicallyDerivedProduct.manipulation.extension`**| | | 
| | | | | `BiologicallyDerivedProduct.manipulation.modifierExtension`| _Equivalent_<br/>(22086/22087)| **`BiologicallyDerivedProduct.manipulation.modifierExtension`**| | | 
| | | | | `BiologicallyDerivedProduct.manipulation.description`| _Equivalent_<br/>(22088/22089)| **`BiologicallyDerivedProduct.manipulation.description`**| | | 
| | | | | `BiologicallyDerivedProduct.manipulation.time[x]`| _Equivalent_<br/>(22090/22091)| **`BiologicallyDerivedProduct.manipulation.time[x]`**| | | 
| | | | | `BiologicallyDerivedProduct.storage`| _Equivalent_<br/>(22092/22093)| **`BiologicallyDerivedProduct.storage`**| | | 
| | | | | `BiologicallyDerivedProduct.storage.id`| _Equivalent_<br/>(22094/22095)| **`BiologicallyDerivedProduct.storage.id`**| | | 
| | | | | `BiologicallyDerivedProduct.storage.extension`| _Equivalent_<br/>(22096/22097)| **`BiologicallyDerivedProduct.storage.extension`**| | | 
| | | | | `BiologicallyDerivedProduct.storage.modifierExtension`| _Equivalent_<br/>(22098/22099)| **`BiologicallyDerivedProduct.storage.modifierExtension`**| | | 
| | | | | `BiologicallyDerivedProduct.storage.description`| _Equivalent_<br/>(22100/22101)| **`BiologicallyDerivedProduct.storage.description`**| | | 
| | | | | `BiologicallyDerivedProduct.storage.temperature`| _Equivalent_<br/>(22102/22103)| **`BiologicallyDerivedProduct.storage.temperature`**| | | 
| | | | | `BiologicallyDerivedProduct.storage.scale`| _Equivalent_<br/>(22104/22105)| **`BiologicallyDerivedProduct.storage.scale`**| | | 
| | | | | `BiologicallyDerivedProduct.storage.duration`| _Equivalent_<br/>(22106/22107)| **`BiologicallyDerivedProduct.storage.duration`**| | | 
| | | | | *45 of 45 elements used* | | *45 of 45 elements used* | | *21 of 33 elements used* <br/>remaining elements:<br/>`BiologicallyDerivedProduct.biologicalSourceEvent`, `BiologicallyDerivedProduct.division`, `BiologicallyDerivedProduct.expirationDate`, `BiologicallyDerivedProduct.processingFacility`, `BiologicallyDerivedProduct.productStatus`, `BiologicallyDerivedProduct.property`, `BiologicallyDerivedProduct.property.extension`, `BiologicallyDerivedProduct.property.id`, `BiologicallyDerivedProduct.property.modifierExtension`, `BiologicallyDerivedProduct.property.type`, `BiologicallyDerivedProduct.property.value[x]`, `BiologicallyDerivedProduct.storageTempRequirements`

