Comparison of 
Generated at Thursday, April 3, 2025 8:18:05 AM

### CommunicationStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | CommunicationStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/communication-status` |
| Version | 1.0.2 |
| Description | The status of the communication. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `57` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Communication` | `Communication.status` | `http://hl7.org/fhir/ValueSet/communication-status` | `Required` | in-progress \| completed \| suspended \| rejected \| failed |

### Referenced Systems

* `http://hl7.org/fhir/communication-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [CommunicationStatus](/docs/R2/ValueSets/CommunicationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/communication-status\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `31`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `190`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EventStatus](/docs/R3/ValueSets/EventStatus.md)<br/> `http://hl7.org/fhir/ValueSet/event-status\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `358`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `581`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EventStatus](/docs/R4/ValueSets/EventStatus.md)<br/> `http://hl7.org/fhir/ValueSet/event-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1499`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1500`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EventStatus](/docs/R4B/ValueSets/EventStatus.md)<br/> `http://hl7.org/fhir/ValueSet/event-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `801`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1062`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EventStatus](/docs/R5/ValueSets/EventStatus.md)<br/> `http://hl7.org/fhir/ValueSet/event-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set CommunicationStatus from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 CommunicationStatus| Relationship | [R3 EventStatus](/docs/R3/ValueSets/EventStatus.md)| Relationship | [R4 EventStatus](/docs/R4/ValueSets/EventStatus.md)| Relationship | [R4B EventStatus](/docs/R4B/ValueSets/EventStatus.md)| Relationship | [R5 EventStatus](/docs/R5/ValueSets/EventStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/communication-status`
| **`in-progress`**| _Equivalent_ <br/>(156/1521)| `in-progress`| _Equivalent_ <br/>(3058/5263)| `in-progress`| _Equivalent_ <br/>(15902/15903)| `in-progress`| _Equivalent_ <br/>(7573/9843)| `in-progress`
| **`completed`**| _Equivalent_ <br/>(154/1519)| `completed`| _Equivalent_ <br/>(3056/5261)| `completed`| _Equivalent_ <br/>(15910/15911)| `completed`| _Equivalent_ <br/>(7570/9840)| `completed`
| **`suspended`**| _Equivalent_ <br/>(158/1523)| `suspended`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(3060)<hr/>←←←← _Equivalent_ ←←←← <br/>(5265) | `on-hold`| _Equivalent_ <br/>(15906/15907)| `on-hold`| _Equivalent_ <br/>(7574/9844)| `on-hold`
| **`suspended`**| _Equivalent_ <br/>(158/1523)| `suspended`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(3060)<hr/>←←←← _Equivalent_ ←←←← <br/>(5265) | `on-hold`| _Equivalent_ <br/>(15906/15907)| `on-hold`| _Equivalent_ <br/>(7574/9844)| `on-hold`
| **`rejected`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(157)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1518) | `aborted`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(3055)<hr/>←←←← _Equivalent_ ←←←← <br/>(5267) | `not-done`| _Equivalent_ <br/>(15904/15905)| `not-done`| _Equivalent_ <br/>(7571/9841)| `not-done`
| **`rejected`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(157)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1518) | `aborted`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(3055)<hr/>←←←← _Equivalent_ ←←←← <br/>(5267) | `stopped`| _Equivalent_ <br/>(15908/15909)| `stopped`| _Equivalent_ <br/>(7569/9839)| `stopped`
| **`rejected`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(157)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1518) | `aborted`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(3055)<hr/>←←←← _Equivalent_ ←←←← <br/>(5267) | `stopped`| _Equivalent_ <br/>(15908/15909)| `stopped`| _Equivalent_ <br/>(7569/9839)| `stopped`
| **`failed`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(155)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1517) | `aborted`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(3055)<hr/>←←←← _Equivalent_ ←←←← <br/>(5267) | `not-done`| _Equivalent_ <br/>(15904/15905)| `not-done`| _Equivalent_ <br/>(7571/9841)| `not-done`
| **`failed`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(155)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1517) | `aborted`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(3055)<hr/>←←←← _Equivalent_ ←←←← <br/>(5267) | `stopped`| _Equivalent_ <br/>(15908/15909)| `stopped`| _Equivalent_ <br/>(7569/9839)| `stopped`
| **`failed`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(155)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1517) | `aborted`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(3055)<hr/>←←←← _Equivalent_ ←←←← <br/>(5267) | `stopped`| _Equivalent_ <br/>(15908/15909)| `stopped`| _Equivalent_ <br/>(7569/9839)| `stopped`
| *5 of 5 codes used* | | *4 of 7 codes used* <br/>remaining codes:<br/>`entered-in-error`, `preparation`, `unknown`| | *5 of 8 codes used* <br/>remaining codes:<br/>`entered-in-error`, `preparation`, `unknown`| | *5 of 8 codes used* <br/>remaining codes:<br/>`entered-in-error`, `preparation`, `unknown`| | *5 of 8 codes used* <br/>remaining codes:<br/>`entered-in-error`, `preparation`, `unknown`

