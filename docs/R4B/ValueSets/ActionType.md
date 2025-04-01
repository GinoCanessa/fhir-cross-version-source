Comparison of 
Generated at Tuesday, April 1, 2025 1:39:26 PM

### ActionType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | ActionType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/action-type` |
| Version | 4.3.0 |
| Description | The type of action to be performed. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `3501` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/PlanDefinition` | `PlanDefinition.action.type` | `http://hl7.org/fhir/ValueSet/action-type` | `Extensible` | create \| update \| remove \| fire-event |
| `http://hl7.org/fhir/StructureDefinition/RequestGroup` | `RequestGroup.action.type` | `http://hl7.org/fhir/ValueSet/action-type` | `Extensible` | create \| update \| remove \| fire-event |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/action-type`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [ActionType](/docs/R4B/ValueSets/ActionType.md)<br/> `http://hl7.org/fhir/ValueSet/action-type\|4.3.0` | →→→→→→→<br/>``<br/>- DBKey: `958`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `1219`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ActionType](/docs/R5/ValueSets/ActionType.md)<br/> `http://hl7.org/fhir/ValueSet/action-type\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set ActionType from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | R4B ActionType| Relationship | [R5 ActionType](/docs/R5/ValueSets/ActionType.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://terminology.hl7.org/CodeSystem/action-type`
| | | | | | | **`create`**| _Equivalent_ <br/>(9205/11519)| `create`
| | | | | | | **`update`**| _Equivalent_ <br/>(9208/11522)| `update`
| | | | | | | **`remove`**| _Equivalent_ <br/>(9207/11521)| `remove`
| | | | | | | **`fire-event`**| _Equivalent_ <br/>(9206/11520)| `fire-event`
| | | | | | | *4 of 4 codes used* | | *4 of 4 codes used* 

