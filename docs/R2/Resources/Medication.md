Comparison of 
Generated at Tuesday, April 1, 2025 1:39:09 PM

### Medication

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | Medication |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Medication` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for Medication Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `94` |
| Database Snapshot Count | `40` |
| Database Differential Count | `17` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Medication` | `Medication` | `Medication` | Medication | Definition of a Medication | 0..* | Medication |  |  |
| `Medication.code` | `Medication.code` | `code` |  | Codes that identify this medication | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/medication-codes` |
| `Medication.contained` | `Medication.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Medication.extension` | `Medication.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Medication.id` | `Medication.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Medication.implicitRules` | `Medication.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Medication.isBrand` | `Medication.isBrand` | `isBrand` |  | True if a brand | 0..1 | boolean |  |  |
| `Medication.language` | `Medication.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `Medication.manufacturer` | `Medication.manufacturer` | `manufacturer` |  | Manufacturer of the item | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `Medication.meta` | `Medication.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Medication.modifierExtension` | `Medication.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Medication.package` | `Medication.package` | `package` |  | Details about packaged medications | 0..1 | BackboneElement |  |  |
| `Medication.package.container` | `Medication.package.container` | `container` |  | E.g. box, vial, blister-pack | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/medication-package-form-codes` |
| `Medication.package.content` | `Medication.package.content` | `content` |  | What is  in the package | 0..* | BackboneElement |  |  |
| `Medication.package.content.amount` | `Medication.package.content.amount` | `amount` |  | Quantity present in the package | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
| `Medication.package.content.extension` | `Medication.package.content.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Medication.package.content.id` | `Medication.package.content.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Medication.package.content.item` | `Medication.package.content.item` | `item` |  | A product in the package | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Medication) |  |  |
| `Medication.package.content.modifierExtension` | `Medication.package.content.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Medication.package.extension` | `Medication.package.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Medication.package.id` | `Medication.package.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Medication.package.modifierExtension` | `Medication.package.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Medication.product` | `Medication.product` | `product` |  | Administrable medication details | 0..1 | BackboneElement |  |  |
| `Medication.product.batch` | `Medication.product.batch` | `batch` |  |  | 0..* | BackboneElement |  |  |
| `Medication.product.batch.expirationDate` | `Medication.product.batch.expirationDate` | `expirationDate` |  |  | 0..1 | dateTime |  |  |
| `Medication.product.batch.extension` | `Medication.product.batch.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Medication.product.batch.id` | `Medication.product.batch.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Medication.product.batch.lotNumber` | `Medication.product.batch.lotNumber` | `lotNumber` |  |  | 0..1 | string |  |  |
| `Medication.product.batch.modifierExtension` | `Medication.product.batch.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Medication.product.extension` | `Medication.product.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Medication.product.form` | `Medication.product.form` | `form` |  | powder \| tablets \| carton + | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/medication-form-codes` |
| `Medication.product.id` | `Medication.product.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Medication.product.ingredient` | `Medication.product.ingredient` | `ingredient` |  | Active or inactive ingredient | 0..* | BackboneElement |  |  |
| `Medication.product.ingredient.amount` | `Medication.product.ingredient.amount` | `amount` |  | Quantity of ingredient present | 0..1 | Ratio |  |  |
| `Medication.product.ingredient.extension` | `Medication.product.ingredient.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Medication.product.ingredient.id` | `Medication.product.ingredient.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Medication.product.ingredient.item` | `Medication.product.ingredient.item` | `item` |  | The product contained | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Medication), Reference(http://hl7.org/fhir/StructureDefinition/Substance) |  |  |
| `Medication.product.ingredient.modifierExtension` | `Medication.product.ingredient.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Medication.product.modifierExtension` | `Medication.product.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Medication.text` | `Medication.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Medication](/docs/R2/Resources/Medication.md)<br/> `http://hl7.org/fhir/StructureDefinition/Medication\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `124`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `290`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Medication](/docs/R3/Resources/Medication.md)<br/> `http://hl7.org/fhir/StructureDefinition/Medication\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `479`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `673`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Medication](/docs/R4/Resources/Medication.md)<br/> `http://hl7.org/fhir/StructureDefinition/Medication\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1535`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1536`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Medication](/docs/R4B/Resources/Medication.md)<br/> `http://hl7.org/fhir/StructureDefinition/Medication\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1002`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1231`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Medication](/docs/R5/Resources/Medication.md)<br/> `http://hl7.org/fhir/StructureDefinition/Medication\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Medication from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 Medication| Relationship | [R3 Medication](/docs/R3/Resources/Medication.md)| Relationship | [R4 Medication](/docs/R4/Resources/Medication.md)| Relationship | [R4B Medication](/docs/R4B/Resources/Medication.md)| Relationship | [R5 Medication](/docs/R5/Resources/Medication.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`Medication`**| →→→→ _Equivalent_ →→→→ <br/>(6089)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6090)| `Medication`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(15682)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(15683)| `Medication`| _Equivalent_<br/>(29443/29444)| `Medication`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(44224)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(44225)| `Medication`
| **`Medication.id`**| _Equivalent_<br/>(6091/6092)| `Medication.id`| _Equivalent_<br/>(15684/15685)| `Medication.id`| _Equivalent_<br/>(29445/29446)| `Medication.id`| _Equivalent_<br/>(44226/44227)| `Medication.id`
| **`Medication.meta`**| _Equivalent_<br/>(6093/6094)| `Medication.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15686)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15687)| `Medication.meta`| _Equivalent_<br/>(29447/29448)| `Medication.meta`| _Equivalent_<br/>(44228/44229)| `Medication.meta`
| **`Medication.implicitRules`**| _Equivalent_<br/>(6095/6096)| `Medication.implicitRules`| _Equivalent_<br/>(15688/15689)| `Medication.implicitRules`| _Equivalent_<br/>(29449/29450)| `Medication.implicitRules`| _Equivalent_<br/>(44230/44231)| `Medication.implicitRules`
| **`Medication.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(6097)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(6098)| `Medication.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15690)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(15691)| `Medication.language`| _Equivalent_<br/>(29451/29452)| `Medication.language`| _Equivalent_<br/>(44232/44233)| `Medication.language`
| **`Medication.text`**| _Equivalent_<br/>(6099/6100)| `Medication.text`| _Equivalent_<br/>(15692/15693)| `Medication.text`| _Equivalent_<br/>(29453/29454)| `Medication.text`| _Equivalent_<br/>(44234/44235)| `Medication.text`
| **`Medication.contained`**| _Equivalent_<br/>(6101/6102)| `Medication.contained`| _Equivalent_<br/>(15694/15695)| `Medication.contained`| _Equivalent_<br/>(29455/29456)| `Medication.contained`| _Equivalent_<br/>(44236/44237)| `Medication.contained`
| **`Medication.extension`**| _Equivalent_<br/>(6103/6104)| `Medication.extension`| →→→→ _Equivalent_ →→→→ <br/>(15696)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15697)| `Medication.extension`| _Equivalent_<br/>(29457/29458)| `Medication.extension`| _Equivalent_<br/>(44238/44239)| `Medication.extension`
| **`Medication.modifierExtension`**| _Equivalent_<br/>(6105/6106)| `Medication.modifierExtension`| _Equivalent_<br/>(15698/15699)| `Medication.modifierExtension`| _Equivalent_<br/>(29459/29460)| `Medication.modifierExtension`| _Equivalent_<br/>(44240/44241)| `Medication.modifierExtension`
| **`Medication.code`**| _Equivalent_<br/>(6107/6108)| `Medication.code`| _Equivalent_<br/>(15700/15701)| `Medication.code`| _Equivalent_<br/>(29463/29464)| `Medication.code`| _Equivalent_<br/>(44244/44245)| `Medication.code`
| **`Medication.isBrand`**| _Equivalent_<br/>(6109/6110)| `Medication.isBrand`| | | | | | | 
| **`Medication.manufacturer`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(6111)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6112)| `Medication.manufacturer`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15703)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15704)| `Medication.manufacturer`| _Equivalent_<br/>(29467/29468)| `Medication.manufacturer`| _Equivalent_<br/>(1821/2064)| `Medication.marketingAuthorizationHolder`
| **`Medication.product`**| →→→→ _RelatedTo_ →→→→ <br/>(264)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(644)| `Medication`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(15682)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(15683)| `Medication`| _Equivalent_<br/>(29443/29444)| `Medication`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(44224)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(44225)| `Medication`
| **`Medication.product.id`**| | | | | | | | | 
| **`Medication.product.extension`**| | | | | | | | | 
| **`Medication.product.modifierExtension`**| | | | | | | | | 
| **`Medication.product.form`**| _Equivalent_<br/>(268/645)| `Medication.form`| _Equivalent_<br/>(15705/15706)| `Medication.form`| _Equivalent_<br/>(29469/29470)| `Medication.form`| _Equivalent_<br/>(1822/2065)| `Medication.doseForm`
| **`Medication.product.ingredient`**| _Equivalent_<br/>(269/646)| `Medication.ingredient`| _Equivalent_<br/>(15707/15708)| `Medication.ingredient`| _Equivalent_<br/>(29473/29474)| `Medication.ingredient`| _Equivalent_<br/>(44249/44250)| `Medication.ingredient`
| **`Medication.product.ingredient.id`**| | | | | | | | | 
| **`Medication.product.ingredient.extension`**| | | | | | | | | 
| **`Medication.product.ingredient.modifierExtension`**| | | | | | | | | 
| **`Medication.product.ingredient.item`**| | | | | | | | | 
| **`Medication.product.ingredient.amount`**| _Equivalent_<br/>(270/647)| `Medication.ingredient.amount`| _Equivalent_<br/>(1171/1599)| `Medication.ingredient.strength`| _Equivalent_<br/>(29485/29486)| `Medication.ingredient.strength`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1820)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2063)| `Medication.ingredient.strength[x]`
| **`Medication.product.batch`**| _Equivalent_<br/>(265/648)| `Medication.package.batch`| | | | | | | 
| **`Medication.product.batch.id`**| | | | | | | | | 
| **`Medication.product.batch.extension`**| | | | | | | | | 
| **`Medication.product.batch.modifierExtension`**| | | | | | | | | 
| **`Medication.product.batch.lotNumber`**| _Equivalent_<br/>(267/650)| `Medication.package.batch.lotNumber`| | | | | | | 
| **`Medication.product.batch.expirationDate`**| _Equivalent_<br/>(266/649)| `Medication.package.batch.expirationDate`| | | | | | | 
| **`Medication.package`**| _Equivalent_<br/>(6123/6124)| `Medication.package`| | | | | | | 
| **`Medication.package.id`**| _Equivalent_<br/>(6125/6126)| `Medication.package.id`| | | | | | | 
| **`Medication.package.extension`**| _Equivalent_<br/>(6127/6128)| `Medication.package.extension`| | | | | | | 
| **`Medication.package.modifierExtension`**| _Equivalent_<br/>(6129/6130)| `Medication.package.modifierExtension`| | | | | | | 
| **`Medication.package.container`**| _Equivalent_<br/>(6131/6132)| `Medication.package.container`| | | | | | | 
| **`Medication.package.content`**| _Equivalent_<br/>(6133/6134)| `Medication.package.content`| | | | | | | 
| **`Medication.package.content.id`**| _Equivalent_<br/>(6135/6136)| `Medication.package.content.id`| | | | | | | 
| **`Medication.package.content.extension`**| _Equivalent_<br/>(6137/6138)| `Medication.package.content.extension`| | | | | | | 
| **`Medication.package.content.modifierExtension`**| _Equivalent_<br/>(6139/6140)| `Medication.package.content.modifierExtension`| | | | | | | 
| **`Medication.package.content.item`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(263)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(651)| `Medication.package.content.item[x]`| | | | | | | 
| **`Medication.package.content.amount`**| _Equivalent_<br/>(6141/6142)| `Medication.package.content.amount`| | | | | | | 
| *40 of 40 elements used* | | *29 of 40 elements used* | | *14 of 28 elements used* | | *14 of 28 elements used* | | *14 of 29 elements used* 

