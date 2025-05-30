Comparison of 
Generated at Monday, April 14, 2025 6:17:15 PM

### AuditEventOutcome

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | AuditEventOutcome |
| Canonical URL | `http://hl7.org/fhir/ValueSet/audit-event-outcome` |
| Version | 1.0.2 |
| Description | Indicates whether the event succeeded or failed |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `28` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/AuditEvent` | `AuditEvent.event.outcome` | `http://hl7.org/fhir/ValueSet/audit-event-outcome` | `Required` | Whether the event succeeded or failed |

### Referenced Systems

* `http://hl7.org/fhir/audit-event-outcome`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [AuditEventOutcome](/docs/R2/ValueSets/AuditEventOutcome.md)<br/> `http://hl7.org/fhir/ValueSet/audit-event-outcome\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `135`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `298`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [AuditEventOutcome](/docs/R3/ValueSets/AuditEventOutcome.md)<br/> `http://hl7.org/fhir/ValueSet/audit-event-outcome\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `501`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `722`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [AuditEventOutcome](/docs/R4/ValueSets/AuditEventOutcome.md)<br/> `http://hl7.org/fhir/ValueSet/audit-event-outcome\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1395`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1396`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [AuditEventOutcome](/docs/R4B/ValueSets/AuditEventOutcome.md)<br/> `http://hl7.org/fhir/ValueSet/audit-event-outcome\|4.3.0` | →→→→→→→<br/>``<br/>- DBKey: `1797`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `1798`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [AuditEventOutcome](/docs/R5/ValueSets/AuditEventOutcome.md)<br/> `http://hl7.org/fhir/ValueSet/audit-event-outcome\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set AuditEventOutcome from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 AuditEventOutcome| Relationship | [R3 AuditEventOutcome](/docs/R3/ValueSets/AuditEventOutcome.md)| Relationship | [R4 AuditEventOutcome](/docs/R4/ValueSets/AuditEventOutcome.md)| Relationship | [R4B AuditEventOutcome](/docs/R4B/ValueSets/AuditEventOutcome.md)| Relationship | [R5 AuditEventOutcome](/docs/R5/ValueSets/AuditEventOutcome.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/audit-event-outcome`
| **`0`**| _Equivalent_ <br/>(1117/2645)| `0`| _Equivalent_ <br/>(4707/7028)| `0`| _Equivalent_ <br/>(14546/14547)| `0`| | | 
| **`4`**| _Equivalent_ <br/>(1119/2647)| `4`| _Equivalent_ <br/>(4709/7030)| `4`| _Equivalent_ <br/>(14548/14549)| `4`| | | 
| **`8`**| _Equivalent_ <br/>(1120/2648)| `8`| _Equivalent_ <br/>(4710/7031)| `8`| _Equivalent_ <br/>(14550/14551)| `8`| | | 
| **`12`**| _Equivalent_ <br/>(1118/2646)| `12`| _Equivalent_ <br/>(4708/7029)| `12`| _Equivalent_ <br/>(14552/14553)| `12`| | | 
| *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *0 of 5 codes used* <br/>remaining codes:<br/>`error`, `fatal`, `information`, `success`, `warning`

