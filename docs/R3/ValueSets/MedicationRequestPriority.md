Comparison of 
Generated at Monday, April 14, 2025 6:17:21 PM

### MedicationRequestPriority

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | MedicationRequestPriority |
| Canonical URL | `http://hl7.org/fhir/ValueSet/medication-request-priority` |
| Version | 3.0.2 |
| Description | Identifies the level of importance to be assigned to actioning the request |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1334` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/MedicationRequest` | `MedicationRequest.priority` | `http://hl7.org/fhir/ValueSet/medication-request-priority` | `Required` | routine \| urgent \| stat \| asap |

### Referenced Systems

* `http://hl7.org/fhir/medication-request-priority`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [MedicationRequestPriority](/docs/R3/ValueSets/MedicationRequestPriority.md)<br/> `http://hl7.org/fhir/ValueSet/medication-request-priority\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `444`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `666`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [RequestPriority](/docs/R4/ValueSets/RequestPriority.md)<br/> `http://hl7.org/fhir/ValueSet/request-priority\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1699`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1700`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [RequestPriority](/docs/R4B/ValueSets/RequestPriority.md)<br/> `http://hl7.org/fhir/ValueSet/request-priority\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `770`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1031`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [RequestPriority](/docs/R5/ValueSets/RequestPriority.md)<br/> `http://hl7.org/fhir/ValueSet/request-priority\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set MedicationRequestPriority from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | R3 MedicationRequestPriority| Relationship | [R4 RequestPriority](/docs/R4/ValueSets/RequestPriority.md)| Relationship | [R4B RequestPriority](/docs/R4B/ValueSets/RequestPriority.md)| Relationship | [R5 RequestPriority](/docs/R5/ValueSets/RequestPriority.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/medication-request-priority`
| | | **`routine`**| _Equivalent_ <br/>(3976/6300)| `routine`| _Equivalent_ <br/>(16970/16971)| `routine`| _Equivalent_ <br/>(7426/9691)| `routine`
| | | **`urgent`**| _Equivalent_ <br/>(3977/6301)| `urgent`| _Equivalent_ <br/>(16972/16973)| `urgent`| _Equivalent_ <br/>(7427/9692)| `urgent`
| | | **`stat`**| _Equivalent_ <br/>(3975/6299)| `stat`| _Equivalent_ <br/>(16976/16977)| `stat`| _Equivalent_ <br/>(7425/9690)| `stat`
| | | **`asap`**| _Equivalent_ <br/>(3978/6302)| `asap`| _Equivalent_ <br/>(16974/16975)| `asap`| _Equivalent_ <br/>(7428/9693)| `asap`
| | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* 

