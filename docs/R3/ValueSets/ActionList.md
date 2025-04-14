Comparison of 
Generated at Monday, April 14, 2025 6:17:19 PM

### ActionList

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | ActionList |
| Canonical URL | `http://hl7.org/fhir/ValueSet/actionlist` |
| Version | 3.0.2 |
| Description | List of allowable action which this resource can request. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1030` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ProcessRequest` | `ProcessRequest.action` | `http://hl7.org/fhir/ValueSet/actionlist` | `Required` | cancel \| poll \| reprocess \| status |

### Referenced Systems

* `http://hl7.org/fhir/actionlist`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ActionList](/docs/R2/ValueSets/ActionList.md)<br/> `http://hl7.org/fhir/ValueSet/actionlist\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `120`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `278`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [ActionList](/docs/R3/ValueSets/ActionList.md)<br/> `http://hl7.org/fhir/ValueSet/actionlist\|3.0.2` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set ActionList from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 ActionList](/docs/R2/ValueSets/ActionList.md)| Relationship | R3 ActionList| Relationship | *No Map* | Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/actionlist`
| `cancel`| _Equivalent_ <br/>(996/2400)| **`cancel`**| | | | | | | 
| `poll`| _Equivalent_ <br/>(998/2402)| **`poll`**| | | | | | | 
| `reprocess`| _Equivalent_ <br/>(997/2401)| **`reprocess`**| | | | | | | 
| `status`| _Equivalent_ <br/>(999/2403)| **`status`**| | | | | | | 
| *4 of 4 codes used* | | *4 of 4 codes used* | | | | | | 

