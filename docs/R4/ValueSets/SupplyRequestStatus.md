Comparison of 
Generated at Monday, April 14, 2025 6:17:26 PM

### SupplyRequestStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | SupplyRequestStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/supplyrequest-status` |
| Version | 4.0.1 |
| Description | Status of the supply request. |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `2792` |
| Database Concept Count | `7` |
| Database Active Concept Count | `7` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/SupplyRequest` | `SupplyRequest.status` | `http://hl7.org/fhir/ValueSet/supplyrequest-status\|4.0.1` | `Required` | draft \| active \| suspended + |

### Referenced Systems

* `http://hl7.org/fhir/supplyrequest-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [SupplyRequestStatus](/docs/R2/ValueSets/SupplyRequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/supplyrequest-status\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `150`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `308`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [SupplyRequestStatus](/docs/R3/ValueSets/SupplyRequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/supplyrequest-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `521`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `742`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [SupplyRequestStatus](/docs/R4/ValueSets/SupplyRequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/supplyrequest-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1759`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1760`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [SupplyRequestStatus](/docs/R4B/ValueSets/SupplyRequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/supplyrequest-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1001`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1262`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [SupplyRequestStatus](/docs/R5/ValueSets/SupplyRequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/supplyrequest-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set SupplyRequestStatus from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 SupplyRequestStatus](/docs/R2/ValueSets/SupplyRequestStatus.md)| Relationship | [R3 SupplyRequestStatus](/docs/R3/ValueSets/SupplyRequestStatus.md)| Relationship | R4 SupplyRequestStatus| Relationship | [R4B SupplyRequestStatus](/docs/R4B/ValueSets/SupplyRequestStatus.md)| Relationship | [R5 SupplyRequestStatus](/docs/R5/ValueSets/SupplyRequestStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://hl7.org/fhir/supplyrequest-status`
| `requested`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1297)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2745) | `draft`| _Equivalent_ <br/>(4863/7186)| **`draft`**| _Equivalent_ <br/>(18272/18273)| `draft`| _Equivalent_ <br/>(9441/11778)| `draft`
| | | `active`| _Equivalent_ <br/>(4864/7187)| **`active`**| _Equivalent_ <br/>(18274/18275)| `active`| _Equivalent_ <br/>(9442/11779)| `active`
| | | `suspended`| _Equivalent_ <br/>(4868/7191)| **`suspended`**| _Equivalent_ <br/>(18276/18277)| `suspended`| _Equivalent_ <br/>(9446/11783)| `suspended`
| `failed`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1296)<hr/>←←←← __ ←←←← <br/>() | `cancelled`| _Equivalent_ <br/>(4865/7188)| **`cancelled`**| _Equivalent_ <br/>(18278/18279)| `cancelled`| _Equivalent_ <br/>(9443/11780)| `cancelled`
| `cancelled`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1294)<hr/>←←←← __ ←←←← <br/>() | `cancelled`| _Equivalent_ <br/>(4865/7188)| **`cancelled`**| _Equivalent_ <br/>(18278/18279)| `cancelled`| _Equivalent_ <br/>(9443/11780)| `cancelled`
| `completed`| _Equivalent_ <br/>(1295/2744)| `completed`| _Equivalent_ <br/>(4866/7189)| **`completed`**| _Equivalent_ <br/>(18280/18281)| `completed`| _Equivalent_ <br/>(9444/11781)| `completed`
| | | `entered-in-error`| _Equivalent_ <br/>(4867/7190)| **`entered-in-error`**| _Equivalent_ <br/>(18282/18283)| `entered-in-error`| _Equivalent_ <br/>(9445/11782)| `entered-in-error`
| | | `unknown`| _Equivalent_ <br/>(4869/7192)| **`unknown`**| _Equivalent_ <br/>(18284/18285)| `unknown`| _Equivalent_ <br/>(9447/11784)| `unknown`
| *4 of 4 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* 

