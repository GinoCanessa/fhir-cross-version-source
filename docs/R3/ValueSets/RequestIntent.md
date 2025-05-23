Comparison of 
Generated at Monday, April 14, 2025 6:17:20 PM

### RequestIntent

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | RequestIntent |
| Canonical URL | `http://hl7.org/fhir/ValueSet/request-intent` |
| Version | 3.0.2 |
| Description | Codes indicating the degree of authority/intentionality associated with a request |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1445` |
| Database Concept Count | `8` |
| Database Active Concept Count | `8` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/DeviceRequest` | `DeviceRequest.intent` | `http://hl7.org/fhir/ValueSet/request-intent` | `Required` | proposal \| plan \| original-order \| encoded \| reflex-order |
| `http://hl7.org/fhir/StructureDefinition/ProcedureRequest` | `ProcedureRequest.intent` | `http://hl7.org/fhir/ValueSet/request-intent` | `Required` | proposal \| plan \| order + |
| `http://hl7.org/fhir/StructureDefinition/ReferralRequest` | `ReferralRequest.intent` | `http://hl7.org/fhir/ValueSet/request-intent` | `Required` | proposal \| plan \| order |
| `http://hl7.org/fhir/StructureDefinition/RequestGroup` | `RequestGroup.intent` | `http://hl7.org/fhir/ValueSet/request-intent` | `Required` | proposal \| plan \| order |
| `http://hl7.org/fhir/StructureDefinition/Task` | `Task.intent` | `http://hl7.org/fhir/ValueSet/request-intent` | `Required` | proposal \| plan \| order + |

### Referenced Systems

* `http://hl7.org/fhir/request-intent`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [DiagnosticOrderStatus](/docs/R2/ValueSets/DiagnosticOrderStatus.md)<br/> `http://hl7.org/fhir/ValueSet/diagnostic-order-status\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `56`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1294`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [RequestIntent](/docs/R3/ValueSets/RequestIntent.md)<br/> `http://hl7.org/fhir/ValueSet/request-intent\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `395`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `618`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [RequestIntent](/docs/R4/ValueSets/RequestIntent.md)<br/> `http://hl7.org/fhir/ValueSet/request-intent\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1697`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1698`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [RequestIntent](/docs/R4B/ValueSets/RequestIntent.md)<br/> `http://hl7.org/fhir/ValueSet/request-intent\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `767`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1028`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [RequestIntent](/docs/R5/ValueSets/RequestIntent.md)<br/> `http://hl7.org/fhir/ValueSet/request-intent\|5.0.0` 
| [DiagnosticOrderStatus](/docs/R2/ValueSets/DiagnosticOrderStatus.md)<br/> `http://hl7.org/fhir/ValueSet/diagnostic-order-status\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `56`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1294`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [RequestIntent](/docs/R3/ValueSets/RequestIntent.md)<br/> `http://hl7.org/fhir/ValueSet/request-intent\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `525`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `746`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [TaskIntent](/docs/R4/ValueSets/TaskIntent.md)<br/> `http://hl7.org/fhir/ValueSet/task-intent\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1763`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1764`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [TaskIntent](/docs/R4B/ValueSets/TaskIntent.md)<br/> `http://hl7.org/fhir/ValueSet/task-intent\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1008`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1269`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [TaskIntent](/docs/R5/ValueSets/TaskIntent.md)<br/> `http://hl7.org/fhir/ValueSet/task-intent\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set RequestIntent from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 DiagnosticOrderStatus](/docs/R2/ValueSets/DiagnosticOrderStatus.md)| Relationship | R3 RequestIntent| Relationship | [R4 RequestIntent](/docs/R4/ValueSets/RequestIntent.md)| Relationship | [R4B RequestIntent](/docs/R4B/ValueSets/RequestIntent.md)| Relationship | [R5 RequestIntent](/docs/R5/ValueSets/RequestIntent.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/request-intent`
| `proposed`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(438)<hr/>←←←← __ ←←←← <br/>() | **`proposal`**| _Equivalent_ <br/>(3582/5875)| `proposal`| _Equivalent_ <br/>(16952/16953)| `proposal`| _Equivalent_ <br/>(7412/9671)| `proposal`
| `planned`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(432)<hr/>←←←← __ ←←←← <br/>() | **`proposal`**| _Equivalent_ <br/>(3582/5875)| `proposal`| _Equivalent_ <br/>(16952/16953)| `proposal`| _Equivalent_ <br/>(7412/9671)| `proposal`
| `requested`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(437)<hr/>←←←← __ ←←←← <br/>() | **`proposal`**| _Equivalent_ <br/>(3582/5875)| `proposal`| _Equivalent_ <br/>(16952/16953)| `proposal`| _Equivalent_ <br/>(7412/9671)| `proposal`
| `received`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(431)<hr/>←←←← __ ←←←← <br/>() | **`proposal`**| _Equivalent_ <br/>(3582/5875)| `proposal`| _Equivalent_ <br/>(16952/16953)| `proposal`| _Equivalent_ <br/>(7412/9671)| `proposal`
| | | **`plan`**| _Equivalent_ <br/>(3587/5874)| `plan`| _Equivalent_ <br/>(16954/16955)| `plan`| _Equivalent_ <br/>(7417/9676)| `plan`
| | | **`order`**| _Equivalent_ <br/>(3588/5872)| `order`| _Equivalent_ <br/>(16958/16959)| `order`| _Equivalent_ <br/>(7419/9678)| `order`
| | | **`original-order`**| _Equivalent_ <br/>(3585/5873)| `original-order`| _Equivalent_ <br/>(16960/16961)| `original-order`| _Equivalent_ <br/>(7415/9674)| `original-order`
| | | **`reflex-order`**| _Equivalent_ <br/>(3586/5876)| `reflex-order`| _Equivalent_ <br/>(16962/16963)| `reflex-order`| _Equivalent_ <br/>(7416/9675)| `reflex-order`
| | | **`filler-order`**| _Equivalent_ <br/>(3584/5869)| `filler-order`| _Equivalent_ <br/>(16964/16965)| `filler-order`| _Equivalent_ <br/>(7414/9673)| `filler-order`
| `accepted`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(430)<hr/>←←←← __ ←←←← <br/>() | **`instance-order`**| _Equivalent_ <br/>(3583/5870)| `instance-order`| _Equivalent_ <br/>(16966/16967)| `instance-order`| _Equivalent_ <br/>(7413/9672)| `instance-order`
| `in-progress`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(435)<hr/>←←←← __ ←←←← <br/>() | **`instance-order`**| _Equivalent_ <br/>(3583/5870)| `instance-order`| _Equivalent_ <br/>(16966/16967)| `instance-order`| _Equivalent_ <br/>(7413/9672)| `instance-order`
| `completed`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(433)<hr/>←←←← __ ←←←← <br/>() | **`instance-order`**| _Equivalent_ <br/>(3583/5870)| `instance-order`| _Equivalent_ <br/>(16966/16967)| `instance-order`| _Equivalent_ <br/>(7413/9672)| `instance-order`
| | | **`option`**| _Equivalent_ <br/>(3589/5871)| `option`| _Equivalent_ <br/>(16968/16969)| `option`| _Equivalent_ <br/>(7420/9679)| `option`
| *7 of 13 codes used* <br/>remaining codes:<br/>`cancelled`, `draft`, `failed`, `rejected`, `review`, `suspended`| | *8 of 8 codes used* | | *8 of 9 codes used* <br/>remaining codes:<br/>`directive`| | *8 of 9 codes used* <br/>remaining codes:<br/>`directive`| | *8 of 9 codes used* <br/>remaining codes:<br/>`directive`


#### Map Group 1

This group is centered on the Value Set RequestIntent from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 DiagnosticOrderStatus](/docs/R2/ValueSets/DiagnosticOrderStatus.md)| Relationship | R3 RequestIntent| Relationship | [R4 TaskIntent](/docs/R4/ValueSets/TaskIntent.md)| Relationship | [R4B TaskIntent](/docs/R4B/ValueSets/TaskIntent.md)| Relationship | [R5 TaskIntent](/docs/R5/ValueSets/TaskIntent.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/request-intent`
| `proposed`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(438)<hr/>←←←← __ ←←←← <br/>() | **`proposal`**| _Equivalent_ <br/>(4923/7254)| `proposal`| _Equivalent_ <br/>(18296/18297)| `proposal`| _Equivalent_ <br/>(9506/11845)| `proposal`
| `planned`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(432)<hr/>←←←← __ ←←←← <br/>() | **`proposal`**| _Equivalent_ <br/>(4923/7254)| `proposal`| _Equivalent_ <br/>(18296/18297)| `proposal`| _Equivalent_ <br/>(9506/11845)| `proposal`
| `requested`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(437)<hr/>←←←← __ ←←←← <br/>() | **`proposal`**| _Equivalent_ <br/>(4923/7254)| `proposal`| _Equivalent_ <br/>(18296/18297)| `proposal`| _Equivalent_ <br/>(9506/11845)| `proposal`
| `received`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(431)<hr/>←←←← __ ←←←← <br/>() | **`proposal`**| _Equivalent_ <br/>(4923/7254)| `proposal`| _Equivalent_ <br/>(18296/18297)| `proposal`| _Equivalent_ <br/>(9506/11845)| `proposal`
| | | **`plan`**| _Equivalent_ <br/>(4922/7253)| `plan`| _Equivalent_ <br/>(18298/18299)| `plan`| _Equivalent_ <br/>(9505/11844)| `plan`
| | | **`order`**| _Equivalent_ <br/>(4920/7251)| `order`| _Equivalent_ <br/>(18300/18301)| `order`| _Equivalent_ <br/>(9503/11842)| `order`
| | | **`original-order`**| _Equivalent_ <br/>(4921/7252)| `original-order`| _Equivalent_ <br/>(18302/18303)| `original-order`| _Equivalent_ <br/>(9504/11843)| `original-order`
| | | **`reflex-order`**| _Equivalent_ <br/>(4924/7255)| `reflex-order`| _Equivalent_ <br/>(18304/18305)| `reflex-order`| _Equivalent_ <br/>(9507/11846)| `reflex-order`
| | | **`filler-order`**| _Equivalent_ <br/>(4917/7248)| `filler-order`| _Equivalent_ <br/>(18306/18307)| `filler-order`| _Equivalent_ <br/>(9500/11839)| `filler-order`
| `accepted`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(430)<hr/>←←←← __ ←←←← <br/>() | **`instance-order`**| _Equivalent_ <br/>(4918/7249)| `instance-order`| _Equivalent_ <br/>(18308/18309)| `instance-order`| _Equivalent_ <br/>(9501/11840)| `instance-order`
| `in-progress`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(435)<hr/>←←←← __ ←←←← <br/>() | **`instance-order`**| _Equivalent_ <br/>(4918/7249)| `instance-order`| _Equivalent_ <br/>(18308/18309)| `instance-order`| _Equivalent_ <br/>(9501/11840)| `instance-order`
| `completed`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(433)<hr/>←←←← __ ←←←← <br/>() | **`instance-order`**| _Equivalent_ <br/>(4918/7249)| `instance-order`| _Equivalent_ <br/>(18308/18309)| `instance-order`| _Equivalent_ <br/>(9501/11840)| `instance-order`
| | | **`option`**| _Equivalent_ <br/>(4919/7250)| `option`| _Equivalent_ <br/>(18310/18311)| `option`| _Equivalent_ <br/>(9502/11841)| `option`
| *7 of 13 codes used* <br/>remaining codes:<br/>`cancelled`, `draft`, `failed`, `rejected`, `review`, `suspended`| | *8 of 8 codes used* | | *8 of 9 codes used* <br/>remaining codes:<br/>`unknown`| | *8 of 9 codes used* <br/>remaining codes:<br/>`unknown`| | *8 of 9 codes used* <br/>remaining codes:<br/>`unknown`

