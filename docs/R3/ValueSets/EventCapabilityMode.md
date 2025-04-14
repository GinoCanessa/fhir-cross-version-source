Comparison of 
Generated at Monday, April 14, 2025 6:17:20 PM

### EventCapabilityMode

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | EventCapabilityMode |
| Canonical URL | `http://hl7.org/fhir/ValueSet/event-capability-mode` |
| Version | 3.0.2 |
| Description | The mode of a message capability statement. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1222` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/CapabilityStatement` | `CapabilityStatement.messaging.supportedMessage.mode` | `http://hl7.org/fhir/ValueSet/event-capability-mode` | `Required` | sender \| receiver |
| `http://hl7.org/fhir/StructureDefinition/CapabilityStatement` | `CapabilityStatement.messaging.event.mode` | `http://hl7.org/fhir/ValueSet/event-capability-mode` | `Required` | sender \| receiver |

### Referenced Systems

* `http://hl7.org/fhir/event-capability-mode`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ConformanceEventMode](/docs/R2/ValueSets/ConformanceEventMode.md)<br/> `http://hl7.org/fhir/ValueSet/message-conformance-event-mode\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `38`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `197`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [EventCapabilityMode](/docs/R3/ValueSets/EventCapabilityMode.md)<br/> `http://hl7.org/fhir/ValueSet/event-capability-mode\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `364`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `587`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [EventCapabilityMode](/docs/R4/ValueSets/EventCapabilityMode.md)<br/> `http://hl7.org/fhir/ValueSet/event-capability-mode\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1497`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1498`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [EventCapabilityMode](/docs/R4B/ValueSets/EventCapabilityMode.md)<br/> `http://hl7.org/fhir/ValueSet/event-capability-mode\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `811`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1072`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [EventCapabilityMode](/docs/R5/ValueSets/EventCapabilityMode.md)<br/> `http://hl7.org/fhir/ValueSet/event-capability-mode\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set EventCapabilityMode from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 ConformanceEventMode](/docs/R2/ValueSets/ConformanceEventMode.md)| Relationship | R3 EventCapabilityMode| Relationship | [R4 EventCapabilityMode](/docs/R4/ValueSets/EventCapabilityMode.md)| Relationship | [R4B EventCapabilityMode](/docs/R4B/ValueSets/EventCapabilityMode.md)| Relationship | [R5 EventCapabilityMode](/docs/R5/ValueSets/EventCapabilityMode.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/event-capability-mode`
| `sender`| _Equivalent_ <br/>(181/1547)| **`sender`**| _Equivalent_ <br/>(3083/5290)| `sender`| _Equivalent_ <br/>(15896/15897)| `sender`| _Equivalent_ <br/>(7653/9953)| `sender`
| `receiver`| _Equivalent_ <br/>(180/1546)| **`receiver`**| _Equivalent_ <br/>(3082/5289)| `receiver`| _Equivalent_ <br/>(15898/15899)| `receiver`| _Equivalent_ <br/>(7652/9952)| `receiver`
| *2 of 2 codes used* | | *2 of 2 codes used* | | *2 of 2 codes used* | | *2 of 2 codes used* | | *2 of 2 codes used* 

