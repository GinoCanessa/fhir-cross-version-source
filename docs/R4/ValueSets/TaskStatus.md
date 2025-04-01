Comparison of 
Generated at Tuesday, April 1, 2025 1:39:18 PM

### TaskStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | TaskStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/task-status` |
| Version | 4.0.1 |
| Description | The current status of the task. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2798` |
| Database Concept Count | `12` |
| Database Active Concept Count | `12` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Task` | `Task.status` | `http://hl7.org/fhir/ValueSet/task-status\|4.0.1` | `Required` | draft \| requested \| received \| accepted \| + |

### Referenced Systems

* `http://hl7.org/fhir/task-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [Financial Resource Status Codes](/docs/R3/ValueSets/FinancialResourceStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/fm-status\|3.0.2` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `480`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `747`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TaskStatus](/docs/R4/ValueSets/TaskStatus.md)<br/> `http://hl7.org/fhir/ValueSet/task-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1765`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1766`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TaskStatus](/docs/R4B/ValueSets/TaskStatus.md)<br/> `http://hl7.org/fhir/ValueSet/task-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1009`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1270`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TaskStatus](/docs/R5/ValueSets/TaskStatus.md)<br/> `http://hl7.org/fhir/ValueSet/task-status\|5.0.0` 
| | | [TaskStatus](/docs/R3/ValueSets/TaskStatus.md)<br/> `http://hl7.org/fhir/ValueSet/task-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `526`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `747`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TaskStatus](/docs/R4/ValueSets/TaskStatus.md)<br/> `http://hl7.org/fhir/ValueSet/task-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1765`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1766`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TaskStatus](/docs/R4B/ValueSets/TaskStatus.md)<br/> `http://hl7.org/fhir/ValueSet/task-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1009`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1270`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TaskStatus](/docs/R5/ValueSets/TaskStatus.md)<br/> `http://hl7.org/fhir/ValueSet/task-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set TaskStatus from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | [R3 Financial Resource Status Codes](/docs/R3/ValueSets/FinancialResourceStatusCodes.md)| Relationship | R4 TaskStatus| Relationship | [R4B TaskStatus](/docs/R4B/ValueSets/TaskStatus.md)| Relationship | [R5 TaskStatus](/docs/R5/ValueSets/TaskStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://hl7.org/fhir/task-status`
| | | `draft`| _Equivalent_ <br/>(4928/7260)| **`draft`**| _Equivalent_ <br/>(18312/18313)| `draft`| _Equivalent_ <br/>(9512/11851)| `draft`
| | | `requested`| _Equivalent_ <br/>(4925/7257)| **`requested`**| _Equivalent_ <br/>(18314/18315)| `requested`| _Equivalent_ <br/>(9509/11848)| `requested`
| | | `received`| _Equivalent_ <br/>(4931/7263)| **`received`**| _Equivalent_ <br/>(18316/18317)| `received`| _Equivalent_ <br/>(9515/11854)| `received`
| | | `accepted`| _Equivalent_ <br/>(4929/7261)| **`accepted`**| _Equivalent_ <br/>(18318/18319)| `accepted`| _Equivalent_ <br/>(9513/11852)| `accepted`
| | | `rejected`| _Equivalent_ <br/>(4926/7258)| **`rejected`**| _Equivalent_ <br/>(18320/18321)| `rejected`| _Equivalent_ <br/>(9510/11849)| `rejected`
| | | `ready`| _Equivalent_ <br/>(4927/7259)| **`ready`**| _Equivalent_ <br/>(18322/18323)| `ready`| _Equivalent_ <br/>(9511/11850)| `ready`
| | | `cancelled`| _Equivalent_ <br/>(4930/7262)| **`cancelled`**| _Equivalent_ <br/>(18324/18325)| `cancelled`| _Equivalent_ <br/>(9514/11853)| `cancelled`
| | | `in-progress`| _Equivalent_ <br/>(4935/7267)| **`in-progress`**| _Equivalent_ <br/>(18326/18327)| `in-progress`| _Equivalent_ <br/>(9519/11858)| `in-progress`
| | | `on-hold`| _Equivalent_ <br/>(4936/7268)| **`on-hold`**| _Equivalent_ <br/>(18328/18329)| `on-hold`| _Equivalent_ <br/>(9520/11859)| `on-hold`
| | | `failed`| _Equivalent_ <br/>(4932/7264)| **`failed`**| _Equivalent_ <br/>(18330/18331)| `failed`| _Equivalent_ <br/>(9516/11855)| `failed`
| | | `completed`| _Equivalent_ <br/>(4933/7265)| **`completed`**| _Equivalent_ <br/>(18332/18333)| `completed`| _Equivalent_ <br/>(9517/11856)| `completed`
| | | `entered-in-error`| _Equivalent_ <br/>(4934/7266)| **`entered-in-error`**| _Equivalent_ <br/>(18334/18335)| `entered-in-error`| _Equivalent_ <br/>(9518/11857)| `entered-in-error`
| | | *12 of 4 codes used* | | *12 of 12 codes used* | | *12 of 12 codes used* | | *12 of 12 codes used* 


#### Map Group 1

This group is centered on the Value Set TaskStatus from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | [R3 TaskStatus](/docs/R3/ValueSets/TaskStatus.md)| Relationship | R4 TaskStatus| Relationship | [R4B TaskStatus](/docs/R4B/ValueSets/TaskStatus.md)| Relationship | [R5 TaskStatus](/docs/R5/ValueSets/TaskStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://hl7.org/fhir/task-status`
| | | `draft`| _Equivalent_ <br/>(4928/7260)| **`draft`**| _Equivalent_ <br/>(18312/18313)| `draft`| _Equivalent_ <br/>(9512/11851)| `draft`
| | | `requested`| _Equivalent_ <br/>(4925/7257)| **`requested`**| _Equivalent_ <br/>(18314/18315)| `requested`| _Equivalent_ <br/>(9509/11848)| `requested`
| | | `received`| _Equivalent_ <br/>(4931/7263)| **`received`**| _Equivalent_ <br/>(18316/18317)| `received`| _Equivalent_ <br/>(9515/11854)| `received`
| | | `accepted`| _Equivalent_ <br/>(4929/7261)| **`accepted`**| _Equivalent_ <br/>(18318/18319)| `accepted`| _Equivalent_ <br/>(9513/11852)| `accepted`
| | | `rejected`| _Equivalent_ <br/>(4926/7258)| **`rejected`**| _Equivalent_ <br/>(18320/18321)| `rejected`| _Equivalent_ <br/>(9510/11849)| `rejected`
| | | `ready`| _Equivalent_ <br/>(4927/7259)| **`ready`**| _Equivalent_ <br/>(18322/18323)| `ready`| _Equivalent_ <br/>(9511/11850)| `ready`
| | | `cancelled`| _Equivalent_ <br/>(4930/7262)| **`cancelled`**| _Equivalent_ <br/>(18324/18325)| `cancelled`| _Equivalent_ <br/>(9514/11853)| `cancelled`
| | | `in-progress`| _Equivalent_ <br/>(4935/7267)| **`in-progress`**| _Equivalent_ <br/>(18326/18327)| `in-progress`| _Equivalent_ <br/>(9519/11858)| `in-progress`
| | | `on-hold`| _Equivalent_ <br/>(4936/7268)| **`on-hold`**| _Equivalent_ <br/>(18328/18329)| `on-hold`| _Equivalent_ <br/>(9520/11859)| `on-hold`
| | | `failed`| _Equivalent_ <br/>(4932/7264)| **`failed`**| _Equivalent_ <br/>(18330/18331)| `failed`| _Equivalent_ <br/>(9516/11855)| `failed`
| | | `completed`| _Equivalent_ <br/>(4933/7265)| **`completed`**| _Equivalent_ <br/>(18332/18333)| `completed`| _Equivalent_ <br/>(9517/11856)| `completed`
| | | `entered-in-error`| _Equivalent_ <br/>(4934/7266)| **`entered-in-error`**| _Equivalent_ <br/>(18334/18335)| `entered-in-error`| _Equivalent_ <br/>(9518/11857)| `entered-in-error`
| | | *12 of 12 codes used* | | *12 of 12 codes used* | | *12 of 12 codes used* | | *12 of 12 codes used* 

