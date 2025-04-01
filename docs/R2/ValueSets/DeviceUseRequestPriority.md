Comparison of 
Generated at Tuesday, April 1, 2025 1:39:07 PM

### DeviceUseRequestPriority

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | DeviceUseRequestPriority |
| Canonical URL | `http://hl7.org/fhir/ValueSet/device-use-request-priority` |
| Version | 1.0.2 |
| Description | Codes representing the priority of the request. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `120` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/DeviceUseRequest` | `DeviceUseRequest.priority` | `http://hl7.org/fhir/ValueSet/device-use-request-priority` | `Required` | routine \| urgent \| stat \| asap |

### Referenced Systems

* `http://hl7.org/fhir/device-use-request-priority`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [DeviceUseRequestPriority](/docs/R2/ValueSets/DeviceUseRequestPriority.md)<br/> `http://hl7.org/fhir/ValueSet/device-use-request-priority\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `60`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `216`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestPriority](/docs/R3/ValueSets/RequestPriority.md)<br/> `http://hl7.org/fhir/ValueSet/request-priority\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `356`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `579`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestPriority](/docs/R4/ValueSets/RequestPriority.md)<br/> `http://hl7.org/fhir/ValueSet/request-priority\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1699`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1700`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestPriority](/docs/R4B/ValueSets/RequestPriority.md)<br/> `http://hl7.org/fhir/ValueSet/request-priority\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `770`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1031`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestPriority](/docs/R5/ValueSets/RequestPriority.md)<br/> `http://hl7.org/fhir/ValueSet/request-priority\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set DeviceUseRequestPriority from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 DeviceUseRequestPriority| Relationship | [R3 RequestPriority](/docs/R3/ValueSets/RequestPriority.md)| Relationship | [R4 RequestPriority](/docs/R4/ValueSets/RequestPriority.md)| Relationship | [R4B RequestPriority](/docs/R4B/ValueSets/RequestPriority.md)| Relationship | [R5 RequestPriority](/docs/R5/ValueSets/RequestPriority.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/device-use-request-priority`
| **`routine`**| _Equivalent_ <br/>(467/1810)| `routine`| _Equivalent_ <br/>(3043/5251)| `routine`| _Equivalent_ <br/>(16970/16971)| `routine`| _Equivalent_ <br/>(7426/9691)| `routine`
| **`urgent`**| _Equivalent_ <br/>(468/1811)| `urgent`| _Equivalent_ <br/>(3044/5252)| `urgent`| _Equivalent_ <br/>(16972/16973)| `urgent`| _Equivalent_ <br/>(7427/9692)| `urgent`
| **`stat`**| _Equivalent_ <br/>(466/1809)| `stat`| _Equivalent_ <br/>(3042/5250)| `stat`| _Equivalent_ <br/>(16976/16977)| `stat`| _Equivalent_ <br/>(7425/9690)| `stat`
| **`asap`**| _Equivalent_ <br/>(469/1812)| `asap`| _Equivalent_ <br/>(3045/5253)| `asap`| _Equivalent_ <br/>(16974/16975)| `asap`| _Equivalent_ <br/>(7428/9693)| `asap`
| *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* 

