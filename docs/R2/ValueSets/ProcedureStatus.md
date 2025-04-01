Comparison of 
Generated at Tuesday, April 1, 2025 1:39:06 PM

### ProcedureStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | ProcedureStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/procedure-status` |
| Version | 1.0.2 |
| Description | A code specifying the state of the procedure. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `292` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Procedure` | `Procedure.status` | `http://hl7.org/fhir/ValueSet/procedure-status` | `Required` | in-progress \| aborted \| completed \| entered-in-error |

### Referenced Systems

* `http://hl7.org/fhir/procedure-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ProcedureStatus](/docs/R2/ValueSets/ProcedureStatus.md)<br/> `http://hl7.org/fhir/ValueSet/procedure-status\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `119`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `277`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EventStatus](/docs/R3/ValueSets/EventStatus.md)<br/> `http://hl7.org/fhir/ValueSet/event-status\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `358`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `581`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EventStatus](/docs/R4/ValueSets/EventStatus.md)<br/> `http://hl7.org/fhir/ValueSet/event-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1499`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1500`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EventStatus](/docs/R4B/ValueSets/EventStatus.md)<br/> `http://hl7.org/fhir/ValueSet/event-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `801`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1062`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EventStatus](/docs/R5/ValueSets/EventStatus.md)<br/> `http://hl7.org/fhir/ValueSet/event-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set ProcedureStatus from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 ProcedureStatus| Relationship | [R3 EventStatus](/docs/R3/ValueSets/EventStatus.md)| Relationship | [R4 EventStatus](/docs/R4/ValueSets/EventStatus.md)| Relationship | [R4B EventStatus](/docs/R4B/ValueSets/EventStatus.md)| Relationship | [R5 EventStatus](/docs/R5/ValueSets/EventStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/procedure-status`
| **`in-progress`**| _Equivalent_ <br/>(995/2396)| `in-progress`| _Equivalent_ <br/>(3058/5263)| `in-progress`| _Equivalent_ <br/>(15902/15903)| `in-progress`| _Equivalent_ <br/>(7573/9843)| `in-progress`
| **`aborted`**| _Equivalent_ <br/>(992/2393)| `aborted`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(3055)<hr/>←←←← _Equivalent_ ←←←← <br/>(5267) | `not-done`| _Equivalent_ <br/>(15904/15905)| `not-done`| _Equivalent_ <br/>(7571/9841)| `not-done`
| **`aborted`**| _Equivalent_ <br/>(992/2393)| `aborted`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(3055)<hr/>←←←← _Equivalent_ ←←←← <br/>(5267) | `stopped`| _Equivalent_ <br/>(15908/15909)| `stopped`| _Equivalent_ <br/>(7569/9839)| `stopped`
| **`aborted`**| _Equivalent_ <br/>(992/2393)| `aborted`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(3055)<hr/>←←←← _Equivalent_ ←←←← <br/>(5267) | `stopped`| _Equivalent_ <br/>(15908/15909)| `stopped`| _Equivalent_ <br/>(7569/9839)| `stopped`
| **`completed`**| _Equivalent_ <br/>(993/2394)| `completed`| _Equivalent_ <br/>(3056/5261)| `completed`| _Equivalent_ <br/>(15910/15911)| `completed`| _Equivalent_ <br/>(7570/9840)| `completed`
| **`entered-in-error`**| _Equivalent_ <br/>(994/2395)| `entered-in-error`| _Equivalent_ <br/>(3057/5262)| `entered-in-error`| _Equivalent_ <br/>(15912/15913)| `entered-in-error`| _Equivalent_ <br/>(7572/9842)| `entered-in-error`
| *4 of 4 codes used* | | *4 of 7 codes used* | | *5 of 8 codes used* | | *5 of 8 codes used* | | *5 of 8 codes used* 

