Comparison of 
Generated at Friday, April 4, 2025 2:58:31 PM

### NutritionOrderStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | NutritionOrderStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/nutrition-order-status` |
| Version | 1.0.2 |
| Description | Codes specifying the state of the request. Describes the lifecycle of the nutrition order. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `249` |
| Database Concept Count | `8` |
| Database Active Concept Count | `8` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/NutritionOrder` | `NutritionOrder.status` | `http://hl7.org/fhir/ValueSet/nutrition-order-status` | `Required` | proposed \| draft \| planned \| requested \| active \| on-hold \| completed \| cancelled |

### Referenced Systems

* `http://hl7.org/fhir/nutrition-order-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [NutritionOrderStatus](/docs/R2/ValueSets/NutritionOrderStatus.md)<br/> `http://hl7.org/fhir/ValueSet/nutrition-order-status\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `102`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `258`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [NutritionOrderStatus](/docs/R3/ValueSets/NutritionOrderStatus.md)<br/> `http://hl7.org/fhir/ValueSet/nutrition-request-status\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `453`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `677`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R4/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1703`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1704`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R4B/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `800`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1061`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R5/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set NutritionOrderStatus from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 NutritionOrderStatus| Relationship | [R3 NutritionOrderStatus](/docs/R3/ValueSets/NutritionOrderStatus.md)| Relationship | [R4 RequestStatus](/docs/R4/ValueSets/RequestStatus.md)| Relationship | [R4B RequestStatus](/docs/R4B/ValueSets/RequestStatus.md)| Relationship | [R5 RequestStatus](/docs/R5/ValueSets/RequestStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/nutrition-order-status`
| **`proposed`**| _Equivalent_ <br/>(833/2205)| `proposed`| | | | | | | 
| **`draft`**| _Equivalent_ <br/>(834/2201)| `draft`| →→→→ _Equivalent_ →→→→ <br/>(4024)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6358) | `draft`| _Equivalent_ <br/>(17008/17009)| `draft`| _Equivalent_ <br/>(7562/9832)| `draft`
| **`planned`**| _Equivalent_ <br/>(837/2204)| `planned`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4027)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6359) | `draft`| _Equivalent_ <br/>(17008/17009)| `draft`| _Equivalent_ <br/>(7562/9832)| `draft`
| **`requested`**| _Equivalent_ <br/>(832/2206)| `requested`| | | | | | | 
| **`active`**| _Equivalent_ <br/>(835/2198)| `active`| _Equivalent_ <br/>(4021/6356)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| **`on-hold`**| _Equivalent_ <br/>(839/2203)| `on-hold`| _Equivalent_ <br/>(4026/6361)| `on-hold`| _Equivalent_ <br/>(17012/17013)| `on-hold`| _Equivalent_ <br/>(7567/9837)| `on-hold`
| **`completed`**| _Equivalent_ <br/>(838/2200)| `completed`| _Equivalent_ <br/>(4023/6357)| `completed`| _Equivalent_ <br/>(17016/17017)| `completed`| _Equivalent_ <br/>(7564/9834)| `completed`
| **`cancelled`**| _Equivalent_ <br/>(836/2199)| `cancelled`| _Equivalent_ <br/>(4022/6362)| `revoked`| _Equivalent_ <br/>(17014/17015)| `revoked`| _Equivalent_ <br/>(7565/9835)| `revoked`
| *8 of 8 codes used* | | *8 of 9 codes used* <br/>remaining codes:<br/>`entered-in-error`| | *5 of 7 codes used* <br/>remaining codes:<br/>`entered-in-error`, `unknown`| | *5 of 7 codes used* <br/>remaining codes:<br/>`entered-in-error`, `unknown`| | *5 of 7 codes used* <br/>remaining codes:<br/>`entered-in-error`, `unknown`

