Comparison of 
Generated at Tuesday, April 1, 2025 1:39:17 PM

### RequestIntent

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | RequestIntent |
| Canonical URL | `http://hl7.org/fhir/ValueSet/request-intent` |
| Version | 4.0.1 |
| Description | Codes indicating the degree of authority/intentionality associated with a request. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2710` |
| Database Concept Count | `9` |
| Database Active Concept Count | `9` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ActivityDefinition` | `ActivityDefinition.intent` | `http://hl7.org/fhir/ValueSet/request-intent\|4.0.1` | `Required` | proposal \| plan \| directive \| order \| original-order \| reflex-order \| filler-order \| instance-order \| option |
| `http://hl7.org/fhir/StructureDefinition/DeviceRequest` | `DeviceRequest.intent` | `http://hl7.org/fhir/ValueSet/request-intent\|4.0.1` | `Required` | proposal \| plan \| directive \| order \| original-order \| reflex-order \| filler-order \| instance-order \| option |
| `http://hl7.org/fhir/StructureDefinition/NutritionOrder` | `NutritionOrder.intent` | `http://hl7.org/fhir/ValueSet/request-intent\|4.0.1` | `Required` | proposal \| plan \| directive \| order \| original-order \| reflex-order \| filler-order \| instance-order \| option |
| `http://hl7.org/fhir/StructureDefinition/RequestGroup` | `RequestGroup.intent` | `http://hl7.org/fhir/ValueSet/request-intent\|4.0.1` | `Required` | proposal \| plan \| directive \| order \| original-order \| reflex-order \| filler-order \| instance-order \| option |
| `http://hl7.org/fhir/StructureDefinition/ServiceRequest` | `ServiceRequest.intent` | `http://hl7.org/fhir/ValueSet/request-intent\|4.0.1` | `Required` | proposal \| plan \| directive \| order \| original-order \| reflex-order \| filler-order \| instance-order \| option |

### Referenced Systems

* `http://hl7.org/fhir/request-intent`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [DiagnosticOrderStatus](/docs/R2/ValueSets/DiagnosticOrderStatus.md)<br/> `http://hl7.org/fhir/ValueSet/diagnostic-order-status\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `56`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1294`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestIntent](/docs/R3/ValueSets/RequestIntent.md)<br/> `http://hl7.org/fhir/ValueSet/request-intent\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `395`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `618`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestIntent](/docs/R4/ValueSets/RequestIntent.md)<br/> `http://hl7.org/fhir/ValueSet/request-intent\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1697`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1698`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestIntent](/docs/R4B/ValueSets/RequestIntent.md)<br/> `http://hl7.org/fhir/ValueSet/request-intent\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `767`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1028`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestIntent](/docs/R5/ValueSets/RequestIntent.md)<br/> `http://hl7.org/fhir/ValueSet/request-intent\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set RequestIntent from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 DiagnosticOrderStatus](/docs/R2/ValueSets/DiagnosticOrderStatus.md)| Relationship | [R3 RequestIntent](/docs/R3/ValueSets/RequestIntent.md)| Relationship | R4 RequestIntent| Relationship | [R4B RequestIntent](/docs/R4B/ValueSets/RequestIntent.md)| Relationship | [R5 RequestIntent](/docs/R5/ValueSets/RequestIntent.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://hl7.org/fhir/request-intent`
| `proposed`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(438)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12276) | `proposal`| _Equivalent_ <br/>(3582/5875)| **`proposal`**| _Equivalent_ <br/>(16952/16953)| `proposal`| _Equivalent_ <br/>(7412/9671)| `proposal`
| `planned`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(432)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12276) | `proposal`| _Equivalent_ <br/>(3582/5875)| **`proposal`**| _Equivalent_ <br/>(16952/16953)| `proposal`| _Equivalent_ <br/>(7412/9671)| `proposal`
| `requested`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(437)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12276) | `proposal`| _Equivalent_ <br/>(3582/5875)| **`proposal`**| _Equivalent_ <br/>(16952/16953)| `proposal`| _Equivalent_ <br/>(7412/9671)| `proposal`
| `received`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(431)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12276) | `proposal`| _Equivalent_ <br/>(3582/5875)| **`proposal`**| _Equivalent_ <br/>(16952/16953)| `proposal`| _Equivalent_ <br/>(7412/9671)| `proposal`
| | | `plan`| _Equivalent_ <br/>(3587/5874)| **`plan`**| _Equivalent_ <br/>(16954/16955)| `plan`| _Equivalent_ <br/>(7417/9676)| `plan`
| | | | | **`directive`**| _Equivalent_ <br/>(16956/16957)| `directive`| _Equivalent_ <br/>(7418/9677)| `directive`
| | | `order`| _Equivalent_ <br/>(3588/5872)| **`order`**| _Equivalent_ <br/>(16958/16959)| `order`| _Equivalent_ <br/>(7419/9678)| `order`
| | | `original-order`| _Equivalent_ <br/>(3585/5873)| **`original-order`**| _Equivalent_ <br/>(16960/16961)| `original-order`| _Equivalent_ <br/>(7415/9674)| `original-order`
| | | `reflex-order`| _Equivalent_ <br/>(3586/5876)| **`reflex-order`**| _Equivalent_ <br/>(16962/16963)| `reflex-order`| _Equivalent_ <br/>(7416/9675)| `reflex-order`
| | | `filler-order`| _Equivalent_ <br/>(3584/5869)| **`filler-order`**| _Equivalent_ <br/>(16964/16965)| `filler-order`| _Equivalent_ <br/>(7414/9673)| `filler-order`
| `accepted`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(430)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12279) | `instance-order`| _Equivalent_ <br/>(3583/5870)| **`instance-order`**| _Equivalent_ <br/>(16966/16967)| `instance-order`| _Equivalent_ <br/>(7413/9672)| `instance-order`
| `in-progress`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(435)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12279) | `instance-order`| _Equivalent_ <br/>(3583/5870)| **`instance-order`**| _Equivalent_ <br/>(16966/16967)| `instance-order`| _Equivalent_ <br/>(7413/9672)| `instance-order`
| `completed`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(433)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12279) | `instance-order`| _Equivalent_ <br/>(3583/5870)| **`instance-order`**| _Equivalent_ <br/>(16966/16967)| `instance-order`| _Equivalent_ <br/>(7413/9672)| `instance-order`
| | | `option`| _Equivalent_ <br/>(3589/5871)| **`option`**| _Equivalent_ <br/>(16968/16969)| `option`| _Equivalent_ <br/>(7420/9679)| `option`
| *7 of 13 codes used* | | *8 of 8 codes used* | | *9 of 9 codes used* | | *9 of 9 codes used* | | *9 of 9 codes used* 

