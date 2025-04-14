Comparison of 
Generated at Monday, April 14, 2025 6:17:36 PM

### RequestPriority

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | RequestPriority |
| Canonical URL | `http://hl7.org/fhir/ValueSet/request-priority` |
| Version | 4.3.0 |
| Description | Identifies the level of importance to be assigned to actioning the request. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4056` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ActivityDefinition` | `ActivityDefinition.priority` | `http://hl7.org/fhir/ValueSet/request-priority\|4.3.0` | `Required` | routine \| urgent \| asap \| stat |
| `http://hl7.org/fhir/StructureDefinition/Communication` | `Communication.priority` | `http://hl7.org/fhir/ValueSet/request-priority\|4.3.0` | `Required` | routine \| urgent \| asap \| stat |
| `http://hl7.org/fhir/StructureDefinition/CommunicationRequest` | `CommunicationRequest.priority` | `http://hl7.org/fhir/ValueSet/request-priority\|4.3.0` | `Required` | routine \| urgent \| asap \| stat |
| `http://hl7.org/fhir/StructureDefinition/DeviceRequest` | `DeviceRequest.priority` | `http://hl7.org/fhir/ValueSet/request-priority\|4.3.0` | `Required` | routine \| urgent \| asap \| stat |
| `http://hl7.org/fhir/StructureDefinition/MedicationRequest` | `MedicationRequest.priority` | `http://hl7.org/fhir/ValueSet/request-priority\|4.3.0` | `Required` | routine \| urgent \| asap \| stat |
| `http://hl7.org/fhir/StructureDefinition/PlanDefinition` | `PlanDefinition.action.priority` | `http://hl7.org/fhir/ValueSet/request-priority\|4.3.0` | `Required` | routine \| urgent \| asap \| stat |
| `http://hl7.org/fhir/StructureDefinition/RequestGroup` | `RequestGroup.priority` | `http://hl7.org/fhir/ValueSet/request-priority\|4.3.0` | `Required` | routine \| urgent \| asap \| stat |
| `http://hl7.org/fhir/StructureDefinition/RequestGroup` | `RequestGroup.action.priority` | `http://hl7.org/fhir/ValueSet/request-priority\|4.3.0` | `Required` | routine \| urgent \| asap \| stat |
| `http://hl7.org/fhir/StructureDefinition/ServiceRequest` | `ServiceRequest.priority` | `http://hl7.org/fhir/ValueSet/request-priority\|4.3.0` | `Required` | routine \| urgent \| asap \| stat |
| `http://hl7.org/fhir/StructureDefinition/SupplyRequest` | `SupplyRequest.priority` | `http://hl7.org/fhir/ValueSet/request-priority\|4.3.0` | `Required` | routine \| urgent \| asap \| stat |
| `http://hl7.org/fhir/StructureDefinition/Task` | `Task.priority` | `http://hl7.org/fhir/ValueSet/request-priority\|4.3.0` | `Required` | routine \| urgent \| asap \| stat |

### Referenced Systems

* `http://hl7.org/fhir/request-priority`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [MedicationRequestPriority](/docs/R3/ValueSets/MedicationRequestPriority.md)<br/> `http://hl7.org/fhir/ValueSet/medication-request-priority\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `444`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>*no map*<br/>←←←←←←←| [RequestPriority](/docs/R4/ValueSets/RequestPriority.md)<br/> `http://hl7.org/fhir/ValueSet/request-priority\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1699`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1700`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [RequestPriority](/docs/R4B/ValueSets/RequestPriority.md)<br/> `http://hl7.org/fhir/ValueSet/request-priority\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `770`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1031`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [RequestPriority](/docs/R5/ValueSets/RequestPriority.md)<br/> `http://hl7.org/fhir/ValueSet/request-priority\|5.0.0` 
| [DeviceUseRequestPriority](/docs/R2/ValueSets/DeviceUseRequestPriority.md)<br/> `http://hl7.org/fhir/ValueSet/device-use-request-priority\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `60`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>*no map*<br/>←←←←←←←| [RequestPriority](/docs/R3/ValueSets/RequestPriority.md)<br/> `http://hl7.org/fhir/ValueSet/request-priority\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `356`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>*no map*<br/>←←←←←←←| [RequestPriority](/docs/R4/ValueSets/RequestPriority.md)<br/> `http://hl7.org/fhir/ValueSet/request-priority\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1699`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1700`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [RequestPriority](/docs/R4B/ValueSets/RequestPriority.md)<br/> `http://hl7.org/fhir/ValueSet/request-priority\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `770`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1031`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [RequestPriority](/docs/R5/ValueSets/RequestPriority.md)<br/> `http://hl7.org/fhir/ValueSet/request-priority\|5.0.0` 
| [DiagnosticOrderPriority](/docs/R2/ValueSets/DiagnosticOrderPriority.md)<br/> `http://hl7.org/fhir/ValueSet/diagnostic-order-priority\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `55`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>*no map*<br/>←←←←←←←| [RequestPriority](/docs/R3/ValueSets/RequestPriority.md)<br/> `http://hl7.org/fhir/ValueSet/request-priority\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `356`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>*no map*<br/>←←←←←←←| [RequestPriority](/docs/R4/ValueSets/RequestPriority.md)<br/> `http://hl7.org/fhir/ValueSet/request-priority\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1699`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1700`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [RequestPriority](/docs/R4B/ValueSets/RequestPriority.md)<br/> `http://hl7.org/fhir/ValueSet/request-priority\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `770`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1031`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [RequestPriority](/docs/R5/ValueSets/RequestPriority.md)<br/> `http://hl7.org/fhir/ValueSet/request-priority\|5.0.0` 
| [ProcedureRequestPriority](/docs/R2/ValueSets/ProcedureRequestPriority.md)<br/> `http://hl7.org/fhir/ValueSet/procedure-request-priority\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `117`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>*no map*<br/>←←←←←←←| [RequestPriority](/docs/R3/ValueSets/RequestPriority.md)<br/> `http://hl7.org/fhir/ValueSet/request-priority\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `356`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>*no map*<br/>←←←←←←←| [RequestPriority](/docs/R4/ValueSets/RequestPriority.md)<br/> `http://hl7.org/fhir/ValueSet/request-priority\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1699`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1700`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [RequestPriority](/docs/R4B/ValueSets/RequestPriority.md)<br/> `http://hl7.org/fhir/ValueSet/request-priority\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `770`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1031`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [RequestPriority](/docs/R5/ValueSets/RequestPriority.md)<br/> `http://hl7.org/fhir/ValueSet/request-priority\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set RequestPriority from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | [R3 MedicationRequestPriority](/docs/R3/ValueSets/MedicationRequestPriority.md)| Relationship | [R4 RequestPriority](/docs/R4/ValueSets/RequestPriority.md)| Relationship | R4B RequestPriority| Relationship | [R5 RequestPriority](/docs/R5/ValueSets/RequestPriority.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://hl7.org/fhir/request-priority`
| | | `routine`| _Equivalent_ <br/>(3976/6300)| `routine`| _Equivalent_ <br/>(16970/16971)| **`routine`**| _Equivalent_ <br/>(7426/9691)| `routine`
| | | `urgent`| _Equivalent_ <br/>(3977/6301)| `urgent`| _Equivalent_ <br/>(16972/16973)| **`urgent`**| _Equivalent_ <br/>(7427/9692)| `urgent`
| | | `asap`| _Equivalent_ <br/>(3978/6302)| `asap`| _Equivalent_ <br/>(16974/16975)| **`asap`**| _Equivalent_ <br/>(7428/9693)| `asap`
| | | `stat`| _Equivalent_ <br/>(3975/6299)| `stat`| _Equivalent_ <br/>(16976/16977)| **`stat`**| _Equivalent_ <br/>(7425/9690)| `stat`
| | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* 


#### Map Group 1

This group is centered on the Value Set RequestPriority from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 DeviceUseRequestPriority](/docs/R2/ValueSets/DeviceUseRequestPriority.md)| Relationship | [R3 RequestPriority](/docs/R3/ValueSets/RequestPriority.md)| Relationship | [R4 RequestPriority](/docs/R4/ValueSets/RequestPriority.md)| Relationship | R4B RequestPriority| Relationship | [R5 RequestPriority](/docs/R5/ValueSets/RequestPriority.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://hl7.org/fhir/request-priority`
| `routine`| _Equivalent_ <br/>(467/1810)| `routine`| _Equivalent_ <br/>(3043/5251)| `routine`| _Equivalent_ <br/>(16970/16971)| **`routine`**| _Equivalent_ <br/>(7426/9691)| `routine`
| `urgent`| _Equivalent_ <br/>(468/1811)| `urgent`| _Equivalent_ <br/>(3044/5252)| `urgent`| _Equivalent_ <br/>(16972/16973)| **`urgent`**| _Equivalent_ <br/>(7427/9692)| `urgent`
| `asap`| _Equivalent_ <br/>(469/1812)| `asap`| _Equivalent_ <br/>(3045/5253)| `asap`| _Equivalent_ <br/>(16974/16975)| **`asap`**| _Equivalent_ <br/>(7428/9693)| `asap`
| `stat`| _Equivalent_ <br/>(466/1809)| `stat`| _Equivalent_ <br/>(3042/5250)| `stat`| _Equivalent_ <br/>(16976/16977)| **`stat`**| _Equivalent_ <br/>(7425/9690)| `stat`
| *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* 


#### Map Group 2

This group is centered on the Value Set RequestPriority from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 DiagnosticOrderPriority](/docs/R2/ValueSets/DiagnosticOrderPriority.md)| Relationship | [R3 RequestPriority](/docs/R3/ValueSets/RequestPriority.md)| Relationship | [R4 RequestPriority](/docs/R4/ValueSets/RequestPriority.md)| Relationship | R4B RequestPriority| Relationship | [R5 RequestPriority](/docs/R5/ValueSets/RequestPriority.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://hl7.org/fhir/request-priority`
| `routine`| _Equivalent_ <br/>(426/2363)| `routine`| _Equivalent_ <br/>(3043/5251)| `routine`| _Equivalent_ <br/>(16970/16971)| **`routine`**| _Equivalent_ <br/>(7426/9691)| `routine`
| `urgent`| _Equivalent_ <br/>(427/2364)| `urgent`| _Equivalent_ <br/>(3044/5252)| `urgent`| _Equivalent_ <br/>(16972/16973)| **`urgent`**| _Equivalent_ <br/>(7427/9692)| `urgent`
| `asap`| _Equivalent_ <br/>(428/2365)| `asap`| _Equivalent_ <br/>(3045/5253)| `asap`| _Equivalent_ <br/>(16974/16975)| **`asap`**| _Equivalent_ <br/>(7428/9693)| `asap`
| `stat`| _Equivalent_ <br/>(425/2362)| `stat`| _Equivalent_ <br/>(3042/5250)| `stat`| _Equivalent_ <br/>(16976/16977)| **`stat`**| _Equivalent_ <br/>(7425/9690)| `stat`
| *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* 


#### Map Group 3

This group is centered on the Value Set RequestPriority from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 ProcedureRequestPriority](/docs/R2/ValueSets/ProcedureRequestPriority.md)| Relationship | [R3 RequestPriority](/docs/R3/ValueSets/RequestPriority.md)| Relationship | [R4 RequestPriority](/docs/R4/ValueSets/RequestPriority.md)| Relationship | R4B RequestPriority| Relationship | [R5 RequestPriority](/docs/R5/ValueSets/RequestPriority.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://hl7.org/fhir/request-priority`
| `routine`| _Equivalent_ <br/>(978/2359)| `routine`| _Equivalent_ <br/>(3043/5251)| `routine`| _Equivalent_ <br/>(16970/16971)| **`routine`**| _Equivalent_ <br/>(7426/9691)| `routine`
| `urgent`| _Equivalent_ <br/>(979/2360)| `urgent`| _Equivalent_ <br/>(3044/5252)| `urgent`| _Equivalent_ <br/>(16972/16973)| **`urgent`**| _Equivalent_ <br/>(7427/9692)| `urgent`
| `asap`| _Equivalent_ <br/>(980/2361)| `asap`| _Equivalent_ <br/>(3045/5253)| `asap`| _Equivalent_ <br/>(16974/16975)| **`asap`**| _Equivalent_ <br/>(7428/9693)| `asap`
| `stat`| _Equivalent_ <br/>(977/2358)| `stat`| _Equivalent_ <br/>(3042/5250)| `stat`| _Equivalent_ <br/>(16976/16977)| **`stat`**| _Equivalent_ <br/>(7425/9690)| `stat`
| *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* 

