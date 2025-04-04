Comparison of 
Generated at Friday, April 4, 2025 2:58:59 PM

### TaskIntent

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | TaskIntent |
| Canonical URL | `http://hl7.org/fhir/ValueSet/task-intent` |
| Version | 5.0.0 |
| Description | Distinguishes whether the task is a proposal, plan or full order. |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `4962` |
| Database Concept Count | `9` |
| Database Active Concept Count | `9` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Task` | `Task.intent` | `http://hl7.org/fhir/ValueSet/task-intent\|5.0.0` | `Required` | unknown \| proposal \| plan \| order \| original-order \| reflex-order \| filler-order \| instance-order \| option |

### Referenced Systems

* `http://hl7.org/fhir/task-intent`
* `http://hl7.org/fhir/request-intent`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [DiagnosticOrderStatus](/docs/R2/ValueSets/DiagnosticOrderStatus.md)<br/> `http://hl7.org/fhir/ValueSet/diagnostic-order-status\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `56`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1294`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestIntent](/docs/R3/ValueSets/RequestIntent.md)<br/> `http://hl7.org/fhir/ValueSet/request-intent\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `525`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `746`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TaskIntent](/docs/R4/ValueSets/TaskIntent.md)<br/> `http://hl7.org/fhir/ValueSet/task-intent\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1763`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1764`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TaskIntent](/docs/R4B/ValueSets/TaskIntent.md)<br/> `http://hl7.org/fhir/ValueSet/task-intent\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1008`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1269`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TaskIntent](/docs/R5/ValueSets/TaskIntent.md)<br/> `http://hl7.org/fhir/ValueSet/task-intent\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set TaskIntent from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 DiagnosticOrderStatus](/docs/R2/ValueSets/DiagnosticOrderStatus.md)| Relationship | [R3 RequestIntent](/docs/R3/ValueSets/RequestIntent.md)| Relationship | [R4 TaskIntent](/docs/R4/ValueSets/TaskIntent.md)| Relationship | [R4B TaskIntent](/docs/R4B/ValueSets/TaskIntent.md)| Relationship | R5 TaskIntent
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/task-intent`
| | | | | `unknown`| _Equivalent_ <br/>(18294/18295)| `unknown`| _Equivalent_ <br/>(9508/11847)| **`unknown`**
| <td colspan="8">**R5** System: `http://hl7.org/fhir/request-intent`
| `proposed`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(438)<hr/>←←←← __ ←←←← <br/>() | `proposal`| _Equivalent_ <br/>(4923/7254)| `proposal`| _Equivalent_ <br/>(18296/18297)| `proposal`| _Equivalent_ <br/>(9506/11845)| **`proposal`**
| `planned`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(432)<hr/>←←←← __ ←←←← <br/>() | `proposal`| _Equivalent_ <br/>(4923/7254)| `proposal`| _Equivalent_ <br/>(18296/18297)| `proposal`| _Equivalent_ <br/>(9506/11845)| **`proposal`**
| `requested`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(437)<hr/>←←←← __ ←←←← <br/>() | `proposal`| _Equivalent_ <br/>(4923/7254)| `proposal`| _Equivalent_ <br/>(18296/18297)| `proposal`| _Equivalent_ <br/>(9506/11845)| **`proposal`**
| `received`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(431)<hr/>←←←← __ ←←←← <br/>() | `proposal`| _Equivalent_ <br/>(4923/7254)| `proposal`| _Equivalent_ <br/>(18296/18297)| `proposal`| _Equivalent_ <br/>(9506/11845)| **`proposal`**
| | | `plan`| _Equivalent_ <br/>(4922/7253)| `plan`| _Equivalent_ <br/>(18298/18299)| `plan`| _Equivalent_ <br/>(9505/11844)| **`plan`**
| | | `order`| _Equivalent_ <br/>(4920/7251)| `order`| _Equivalent_ <br/>(18300/18301)| `order`| _Equivalent_ <br/>(9503/11842)| **`order`**
| | | `original-order`| _Equivalent_ <br/>(4921/7252)| `original-order`| _Equivalent_ <br/>(18302/18303)| `original-order`| _Equivalent_ <br/>(9504/11843)| **`original-order`**
| | | `reflex-order`| _Equivalent_ <br/>(4924/7255)| `reflex-order`| _Equivalent_ <br/>(18304/18305)| `reflex-order`| _Equivalent_ <br/>(9507/11846)| **`reflex-order`**
| | | `filler-order`| _Equivalent_ <br/>(4917/7248)| `filler-order`| _Equivalent_ <br/>(18306/18307)| `filler-order`| _Equivalent_ <br/>(9500/11839)| **`filler-order`**
| `accepted`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(430)<hr/>←←←← __ ←←←← <br/>() | `instance-order`| _Equivalent_ <br/>(4918/7249)| `instance-order`| _Equivalent_ <br/>(18308/18309)| `instance-order`| _Equivalent_ <br/>(9501/11840)| **`instance-order`**
| `in-progress`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(435)<hr/>←←←← __ ←←←← <br/>() | `instance-order`| _Equivalent_ <br/>(4918/7249)| `instance-order`| _Equivalent_ <br/>(18308/18309)| `instance-order`| _Equivalent_ <br/>(9501/11840)| **`instance-order`**
| `completed`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(433)<hr/>←←←← __ ←←←← <br/>() | `instance-order`| _Equivalent_ <br/>(4918/7249)| `instance-order`| _Equivalent_ <br/>(18308/18309)| `instance-order`| _Equivalent_ <br/>(9501/11840)| **`instance-order`**
| | | `option`| _Equivalent_ <br/>(4919/7250)| `option`| _Equivalent_ <br/>(18310/18311)| `option`| _Equivalent_ <br/>(9502/11841)| **`option`**
| *7 of 13 codes used* <br/>remaining codes:<br/>`cancelled`, `draft`, `failed`, `rejected`, `review`, `suspended`| | *8 of 8 codes used* | | *9 of 9 codes used* | | *9 of 9 codes used* | | *9 of 9 codes used* 

