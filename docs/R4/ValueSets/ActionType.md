Comparison of 
Generated at Monday, April 14, 2025 6:17:27 PM

### ActionType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | ActionType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/action-type` |
| Version | 4.0.1 |
| Description | The type of action to be performed. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2184` |
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
| | | [ActionType](/docs/R3/ValueSets/ActionType.md)<br/> `http://hl7.org/fhir/ValueSet/action-type\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `473`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `697`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ActionType](/docs/R4/ValueSets/ActionType.md)<br/> `http://hl7.org/fhir/ValueSet/action-type\|4.0.1` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set ActionType from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | [R3 ActionType](/docs/R3/ValueSets/ActionType.md)| Relationship | R4 ActionType| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://terminology.hl7.org/CodeSystem/action-type`
| | | `create`| _Equivalent_ <br/>(4187/6532)| **`create`**| | | | | 
| | | `update`| _Equivalent_ <br/>(4188/6533)| **`update`**| | | | | 
| | | `remove`| _Equivalent_ <br/>(4189/6534)| **`remove`**| | | | | 
| | | `fire-event`| _Equivalent_ <br/>(4186/6531)| **`fire-event`**| | | | | 
| | | *4 of 4 codes used* | | *4 of 4 codes used* | | | | 

