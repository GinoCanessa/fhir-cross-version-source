Comparison of 
Generated at Monday, April 14, 2025 6:17:29 PM

### Address

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | Address |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Address` |
| Version | 4.0.1 |
| Description | Base StructureDefinition for Address Type: An address expressed using postal conventions (as opposed to GPS or other location definition formats).  This data type may be used to convey addresses for use in delivering mail as well as for visiting locations which might not be valid for mail delivery.  There are a variety of postal address formats defined around the world. |
| Status | `Active` |
| Artifact Class | `ComplexType` |
| Database Key | `990` |
| Database Snapshot Count | `13` |
| Database Differential Count | `11` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Address` | `Address` | `Address` | Address | An address expressed using postal conventions (as opposed to GPS or other location definition formats) | 0..* | Address |  |  |
| `Address.city` | `Address.city` | `city` | Address.city | Name of city, town etc. | 0..1 | string |  |  |
| `Address.country` | `Address.country` | `country` | Address.country | Country (e.g. can be ISO 3166 2 or 3 letter code) | 0..1 | string |  |  |
| `Address.district` | `Address.district` | `district` | Address.district | District name (aka county) | 0..1 | string |  |  |
| `Address.extension` | `Address.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Address.id` | `Address.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Address.line` | `Address.line` | `line` | Address.line | Street name, number, direction & P.O. Box etc. | 0..* | string |  |  |
| `Address.period` | `Address.period` | `period` | Address.period | Time period when address was/is in use | 0..1 | Period |  |  |
| `Address.postalCode` | `Address.postalCode` | `postalCode` | Address.postalCode | Postal code for area | 0..1 | string |  |  |
| `Address.state` | `Address.state` | `state` | Address.state | Sub-unit of country (abbreviations ok) | 0..1 | string |  |  |
| `Address.text` | `Address.text` | `text` | Address.text | Text representation of the address | 0..1 | string |  |  |
| `Address.type` | `Address.type` | `type` | Address.type | postal \| physical \| both | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/address-type|4.0.1` |
| `Address.use` | `Address.use` | `use` | Address.use | home \| work \| temp \| old \| billing - purpose of this address | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/address-use|4.0.1` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Address](/docs/R2/ComplexTypes/Address.md)<br/> `http://hl7.org/fhir/StructureDefinition/Address\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `47`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `213`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Address](/docs/R3/ComplexTypes/Address.md)<br/> `http://hl7.org/fhir/StructureDefinition/Address\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `382`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `578`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Address](/docs/R4/ComplexTypes/Address.md)<br/> `http://hl7.org/fhir/StructureDefinition/Address\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1307`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1308`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Address](/docs/R4B/ComplexTypes/Address.md)<br/> `http://hl7.org/fhir/StructureDefinition/Address\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `889`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1118`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Address](/docs/R5/ComplexTypes/Address.md)<br/> `http://hl7.org/fhir/StructureDefinition/Address\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Address from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Address](/docs/R2/ComplexTypes/Address.md)| Relationship | [R3 Address](/docs/R3/ComplexTypes/Address.md)| Relationship | R4 Address| Relationship | [R4B Address](/docs/R4B/ComplexTypes/Address.md)| Relationship | [R5 Address](/docs/R5/ComplexTypes/Address.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `Address`| _Equivalent_<br/>(2415/2416)| `Address`| _Equivalent_<br/>(9120/9121)| **`Address`**| _Equivalent_<br/>(20478/20479)| `Address`| _Equivalent_<br/>(35595/35596)| `Address`
| `Address.id`| _Equivalent_<br/>(2417/2418)| `Address.id`| _Equivalent_<br/>(9122/9123)| **`Address.id`**| _Equivalent_<br/>(20480/20481)| `Address.id`| _Equivalent_<br/>(35597/35598)| `Address.id`
| `Address.extension`| _Equivalent_<br/>(2419/2420)| `Address.extension`| _Equivalent_<br/>(9124/9125)| **`Address.extension`**| _Equivalent_<br/>(20482/20483)| `Address.extension`| _Equivalent_<br/>(35599/35600)| `Address.extension`
| `Address.use`| _Equivalent_<br/>(2421/2422)| `Address.use`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9126)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(9127)| **`Address.use`**| _Equivalent_<br/>(20484/20485)| `Address.use`| _Equivalent_<br/>(35601/35602)| `Address.use`
| `Address.type`| _Equivalent_<br/>(2423/2424)| `Address.type`| _Equivalent_<br/>(9128/9129)| **`Address.type`**| _Equivalent_<br/>(20486/20487)| `Address.type`| _Equivalent_<br/>(35603/35604)| `Address.type`
| `Address.text`| _Equivalent_<br/>(2425/2426)| `Address.text`| _Equivalent_<br/>(9130/9131)| **`Address.text`**| _Equivalent_<br/>(20488/20489)| `Address.text`| _Equivalent_<br/>(35605/35606)| `Address.text`
| `Address.line`| _Equivalent_<br/>(2427/2428)| `Address.line`| _Equivalent_<br/>(9132/9133)| **`Address.line`**| _Equivalent_<br/>(20490/20491)| `Address.line`| _Equivalent_<br/>(35607/35608)| `Address.line`
| `Address.city`| _Equivalent_<br/>(2429/2430)| `Address.city`| _Equivalent_<br/>(9134/9135)| **`Address.city`**| _Equivalent_<br/>(20492/20493)| `Address.city`| _Equivalent_<br/>(35609/35610)| `Address.city`
| `Address.district`| _Equivalent_<br/>(2431/2432)| `Address.district`| _Equivalent_<br/>(9136/9137)| **`Address.district`**| _Equivalent_<br/>(20494/20495)| `Address.district`| _Equivalent_<br/>(35611/35612)| `Address.district`
| `Address.state`| _Equivalent_<br/>(2433/2434)| `Address.state`| _Equivalent_<br/>(9138/9139)| **`Address.state`**| _Equivalent_<br/>(20496/20497)| `Address.state`| _Equivalent_<br/>(35613/35614)| `Address.state`
| `Address.postalCode`| _Equivalent_<br/>(2435/2436)| `Address.postalCode`| _Equivalent_<br/>(9140/9141)| **`Address.postalCode`**| _Equivalent_<br/>(20498/20499)| `Address.postalCode`| _Equivalent_<br/>(35615/35616)| `Address.postalCode`
| `Address.country`| _Equivalent_<br/>(2437/2438)| `Address.country`| _Equivalent_<br/>(9142/9143)| **`Address.country`**| _Equivalent_<br/>(20500/20501)| `Address.country`| _Equivalent_<br/>(35617/35618)| `Address.country`
| `Address.period`| _Equivalent_<br/>(2439/2440)| `Address.period`| _Equivalent_<br/>(9144/9145)| **`Address.period`**| _Equivalent_<br/>(20502/20503)| `Address.period`| _Equivalent_<br/>(35619/35620)| `Address.period`
| *13 of 13 elements used* | | *13 of 13 elements used* | | *13 of 13 elements used* | | *13 of 13 elements used* | | *13 of 13 elements used* 

