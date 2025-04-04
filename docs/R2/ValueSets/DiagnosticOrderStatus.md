Comparison of 
Generated at Friday, April 4, 2025 2:58:31 PM

### DiagnosticOrderStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | DiagnosticOrderStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/diagnostic-order-status` |
| Version | 1.0.2 |
| Description | The status of a diagnostic order. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `125` |
| Database Concept Count | `13` |
| Database Active Concept Count | `13` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/DiagnosticOrder` | `DiagnosticOrder.status` | `http://hl7.org/fhir/ValueSet/diagnostic-order-status` | `Required` | proposed \| draft \| planned \| requested \| received \| accepted \| in-progress \| review \| completed \| cancelled \| suspended \| rejected \| failed |
| `http://hl7.org/fhir/StructureDefinition/DiagnosticOrder` | `DiagnosticOrder.event.status` | `http://hl7.org/fhir/ValueSet/diagnostic-order-status` | `Required` | proposed \| draft \| planned \| requested \| received \| accepted \| in-progress \| review \| completed \| cancelled \| suspended \| rejected \| failed |
| `http://hl7.org/fhir/StructureDefinition/DiagnosticOrder` | `DiagnosticOrder.item.status` | `http://hl7.org/fhir/ValueSet/diagnostic-order-status` | `Required` | proposed \| draft \| planned \| requested \| received \| accepted \| in-progress \| review \| completed \| cancelled \| suspended \| rejected \| failed |

### Referenced Systems

* `http://hl7.org/fhir/diagnostic-order-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [DiagnosticOrderStatus](/docs/R2/ValueSets/DiagnosticOrderStatus.md)<br/> `http://hl7.org/fhir/ValueSet/diagnostic-order-status\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `56`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1294`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestIntent](/docs/R3/ValueSets/RequestIntent.md)<br/> `http://hl7.org/fhir/ValueSet/request-intent\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `395`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `618`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestIntent](/docs/R4/ValueSets/RequestIntent.md)<br/> `http://hl7.org/fhir/ValueSet/request-intent\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1697`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1698`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestIntent](/docs/R4B/ValueSets/RequestIntent.md)<br/> `http://hl7.org/fhir/ValueSet/request-intent\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `767`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1028`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestIntent](/docs/R5/ValueSets/RequestIntent.md)<br/> `http://hl7.org/fhir/ValueSet/request-intent\|5.0.0` 
| [DiagnosticOrderStatus](/docs/R2/ValueSets/DiagnosticOrderStatus.md)<br/> `http://hl7.org/fhir/ValueSet/diagnostic-order-status\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `56`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1294`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestIntent](/docs/R3/ValueSets/RequestIntent.md)<br/> `http://hl7.org/fhir/ValueSet/request-intent\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `525`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `746`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TaskIntent](/docs/R4/ValueSets/TaskIntent.md)<br/> `http://hl7.org/fhir/ValueSet/task-intent\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1763`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1764`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TaskIntent](/docs/R4B/ValueSets/TaskIntent.md)<br/> `http://hl7.org/fhir/ValueSet/task-intent\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1008`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1269`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TaskIntent](/docs/R5/ValueSets/TaskIntent.md)<br/> `http://hl7.org/fhir/ValueSet/task-intent\|5.0.0` 
| [DiagnosticOrderStatus](/docs/R2/ValueSets/DiagnosticOrderStatus.md)<br/> `http://hl7.org/fhir/ValueSet/diagnostic-order-status\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `57`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `276`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R3/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `357`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `580`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R4/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1703`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1704`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R4B/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `800`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1061`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R5/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set DiagnosticOrderStatus from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 DiagnosticOrderStatus| Relationship | [R3 RequestIntent](/docs/R3/ValueSets/RequestIntent.md)| Relationship | [R4 RequestIntent](/docs/R4/ValueSets/RequestIntent.md)| Relationship | [R4B RequestIntent](/docs/R4B/ValueSets/RequestIntent.md)| Relationship | [R5 RequestIntent](/docs/R5/ValueSets/RequestIntent.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/diagnostic-order-status`
| **`proposed`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(438)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12273) | `proposal`| _Equivalent_ <br/>(3582/5875)| `proposal`| _Equivalent_ <br/>(16952/16953)| `proposal`| _Equivalent_ <br/>(7412/9671)| `proposal`
| **`draft`**| | | | | | | | | 
| **`planned`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(432)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12274) | `proposal`| _Equivalent_ <br/>(3582/5875)| `proposal`| _Equivalent_ <br/>(16952/16953)| `proposal`| _Equivalent_ <br/>(7412/9671)| `proposal`
| **`requested`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(437)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12275) | `proposal`| _Equivalent_ <br/>(3582/5875)| `proposal`| _Equivalent_ <br/>(16952/16953)| `proposal`| _Equivalent_ <br/>(7412/9671)| `proposal`
| **`received`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(431)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12276) | `proposal`| _Equivalent_ <br/>(3582/5875)| `proposal`| _Equivalent_ <br/>(16952/16953)| `proposal`| _Equivalent_ <br/>(7412/9671)| `proposal`
| **`accepted`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(430)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12277) | `instance-order`| _Equivalent_ <br/>(3583/5870)| `instance-order`| _Equivalent_ <br/>(16966/16967)| `instance-order`| _Equivalent_ <br/>(7413/9672)| `instance-order`
| **`in-progress`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(435)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12278) | `instance-order`| _Equivalent_ <br/>(3583/5870)| `instance-order`| _Equivalent_ <br/>(16966/16967)| `instance-order`| _Equivalent_ <br/>(7413/9672)| `instance-order`
| **`review`**| | | | | | | | | 
| **`completed`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(433)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12279) | `instance-order`| _Equivalent_ <br/>(3583/5870)| `instance-order`| _Equivalent_ <br/>(16966/16967)| `instance-order`| _Equivalent_ <br/>(7413/9672)| `instance-order`
| **`cancelled`**| | | | | | | | | 
| **`suspended`**| | | | | | | | | 
| **`rejected`**| | | | | | | | | 
| **`failed`**| | | | | | | | | 
| *13 of 13 codes used* | | *2 of 8 codes used* <br/>remaining codes:<br/>`filler-order`, `option`, `order`, `original-order`, `plan`, `reflex-order`| | *2 of 9 codes used* <br/>remaining codes:<br/>`directive`, `filler-order`, `option`, `order`, `original-order`, `plan`, `reflex-order`| | *2 of 9 codes used* <br/>remaining codes:<br/>`directive`, `filler-order`, `option`, `order`, `original-order`, `plan`, `reflex-order`| | *2 of 9 codes used* <br/>remaining codes:<br/>`directive`, `filler-order`, `option`, `order`, `original-order`, `plan`, `reflex-order`


#### Map Group 1

This group is centered on the Value Set DiagnosticOrderStatus from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 DiagnosticOrderStatus| Relationship | [R3 RequestIntent](/docs/R3/ValueSets/RequestIntent.md)| Relationship | [R4 TaskIntent](/docs/R4/ValueSets/TaskIntent.md)| Relationship | [R4B TaskIntent](/docs/R4B/ValueSets/TaskIntent.md)| Relationship | [R5 TaskIntent](/docs/R5/ValueSets/TaskIntent.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/diagnostic-order-status`
| **`proposed`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(438)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12273) | `proposal`| _Equivalent_ <br/>(4923/7254)| `proposal`| _Equivalent_ <br/>(18296/18297)| `proposal`| _Equivalent_ <br/>(9506/11845)| `proposal`
| **`draft`**| | | | | | | | | 
| **`planned`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(432)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12274) | `proposal`| _Equivalent_ <br/>(4923/7254)| `proposal`| _Equivalent_ <br/>(18296/18297)| `proposal`| _Equivalent_ <br/>(9506/11845)| `proposal`
| **`requested`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(437)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12275) | `proposal`| _Equivalent_ <br/>(4923/7254)| `proposal`| _Equivalent_ <br/>(18296/18297)| `proposal`| _Equivalent_ <br/>(9506/11845)| `proposal`
| **`received`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(431)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12276) | `proposal`| _Equivalent_ <br/>(4923/7254)| `proposal`| _Equivalent_ <br/>(18296/18297)| `proposal`| _Equivalent_ <br/>(9506/11845)| `proposal`
| **`accepted`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(430)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12277) | `instance-order`| _Equivalent_ <br/>(4918/7249)| `instance-order`| _Equivalent_ <br/>(18308/18309)| `instance-order`| _Equivalent_ <br/>(9501/11840)| `instance-order`
| **`in-progress`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(435)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12278) | `instance-order`| _Equivalent_ <br/>(4918/7249)| `instance-order`| _Equivalent_ <br/>(18308/18309)| `instance-order`| _Equivalent_ <br/>(9501/11840)| `instance-order`
| **`review`**| | | | | | | | | 
| **`completed`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(433)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12279) | `instance-order`| _Equivalent_ <br/>(4918/7249)| `instance-order`| _Equivalent_ <br/>(18308/18309)| `instance-order`| _Equivalent_ <br/>(9501/11840)| `instance-order`
| **`cancelled`**| | | | | | | | | 
| **`suspended`**| | | | | | | | | 
| **`rejected`**| | | | | | | | | 
| **`failed`**| | | | | | | | | 
| *13 of 13 codes used* | | *2 of 8 codes used* <br/>remaining codes:<br/>`filler-order`, `option`, `order`, `original-order`, `plan`, `reflex-order`| | *2 of 9 codes used* <br/>remaining codes:<br/>`filler-order`, `option`, `order`, `original-order`, `plan`, `reflex-order`, `unknown`| | *2 of 9 codes used* <br/>remaining codes:<br/>`filler-order`, `option`, `order`, `original-order`, `plan`, `reflex-order`, `unknown`| | *2 of 9 codes used* <br/>remaining codes:<br/>`filler-order`, `option`, `order`, `original-order`, `plan`, `reflex-order`, `unknown`


#### Map Group 2

This group is centered on the Value Set DiagnosticOrderStatus from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 DiagnosticOrderStatus| Relationship | [R3 RequestStatus](/docs/R3/ValueSets/RequestStatus.md)| Relationship | [R4 RequestStatus](/docs/R4/ValueSets/RequestStatus.md)| Relationship | [R4B RequestStatus](/docs/R4B/ValueSets/RequestStatus.md)| Relationship | [R5 RequestStatus](/docs/R5/ValueSets/RequestStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/diagnostic-order-status`
| **`proposed`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(451)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2389) | `draft`| →→→→ _Equivalent_ →→→→ <br/>(3046)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5256) | `draft`| _Equivalent_ <br/>(17008/17009)| `draft`| _Equivalent_ <br/>(7562/9832)| `draft`
| **`draft`**| →→→→ _Equivalent_ →→→→ <br/>(453)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2387) | `draft`| →→→→ _Equivalent_ →→→→ <br/>(3046)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5256) | `draft`| _Equivalent_ <br/>(17008/17009)| `draft`| _Equivalent_ <br/>(7562/9832)| `draft`
| **`planned`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(445)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2388) | `draft`| →→→→ _Equivalent_ →→→→ <br/>(3046)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5256) | `draft`| _Equivalent_ <br/>(17008/17009)| `draft`| _Equivalent_ <br/>(7562/9832)| `draft`
| **`requested`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(450)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2382) | `active`| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| **`received`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(444)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2381) | `active`| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| **`accepted`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(443)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2379) | `active`| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| **`in-progress`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(448)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2380) | `active`| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| **`review`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(452)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2383) | `active`| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| **`completed`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(446)<hr/>←←←← _Equivalent_ ←←←← <br/>(2386) | `completed`| _Equivalent_ <br/>(3049/5255)| `completed`| _Equivalent_ <br/>(17016/17017)| `completed`| _Equivalent_ <br/>(7564/9834)| `completed`
| **`cancelled`**| →→→→ _Equivalent_ →→→→ <br/>(454)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2384) | `cancelled`| _Equivalent_ <br/>(3048/5259)| `revoked`| _Equivalent_ <br/>(17014/17015)| `revoked`| _Equivalent_ <br/>(7565/9835)| `revoked`
| **`suspended`**| _Equivalent_ <br/>(449/2391)| `suspended`| _Equivalent_ <br/>(3051/5258)| `on-hold`| _Equivalent_ <br/>(17012/17013)| `on-hold`| _Equivalent_ <br/>(7567/9837)| `on-hold`
| **`rejected`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(442)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2385) | `cancelled`| _Equivalent_ <br/>(3048/5259)| `revoked`| _Equivalent_ <br/>(17014/17015)| `revoked`| _Equivalent_ <br/>(7565/9835)| `revoked`
| **`failed`**| | | | | | | | | 
| *13 of 13 codes used* | | *5 of 7 codes used* <br/>remaining codes:<br/>`entered-in-error`, `unknown`| | *5 of 7 codes used* <br/>remaining codes:<br/>`entered-in-error`, `unknown`| | *5 of 7 codes used* <br/>remaining codes:<br/>`entered-in-error`, `unknown`| | *5 of 7 codes used* <br/>remaining codes:<br/>`entered-in-error`, `unknown`

