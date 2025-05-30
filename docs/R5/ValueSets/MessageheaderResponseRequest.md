Comparison of 
Generated at Monday, April 14, 2025 6:17:42 PM

### MessageheaderResponseRequest

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | MessageheaderResponseRequest |
| Canonical URL | `http://hl7.org/fhir/ValueSet/messageheader-response-request` |
| Version | 5.0.0 |
| Description | HL7-defined table of codes which identify conditions under which acknowledgments are required to be returned in response to a message. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4737` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/MessageDefinition` | `MessageDefinition.responseRequired` | `http://hl7.org/fhir/ValueSet/messageheader-response-request\|5.0.0` | `Required` | always \| on-error \| never \| on-success |

### Referenced Systems

* `http://hl7.org/fhir/messageheader-response-request`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [messageheader-response-request](/docs/R3/ValueSets/MessageheaderResponseRequest.md)<br/> `http://hl7.org/fhir/ValueSet/messageheader-response-request\|3.0.2` | →→→→→→→<br/>``<br/>- DBKey: `1610`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `1609`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [messageheader-response-request](/docs/R4/ValueSets/MessageheaderResponseRequest.md)<br/> `http://hl7.org/fhir/ValueSet/messageheader-response-request\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1611`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1612`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [messageheader-response-request](/docs/R4B/ValueSets/MessageheaderResponseRequest.md)<br/> `http://hl7.org/fhir/ValueSet/messageheader-response-request\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `929`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1190`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [MessageheaderResponseRequest](/docs/R5/ValueSets/MessageheaderResponseRequest.md)<br/> `http://hl7.org/fhir/ValueSet/messageheader-response-request\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set MessageheaderResponseRequest from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | [R3 messageheader-response-request](/docs/R3/ValueSets/MessageheaderResponseRequest.md)| Relationship | [R4 messageheader-response-request](/docs/R4/ValueSets/MessageheaderResponseRequest.md)| Relationship | [R4B messageheader-response-request](/docs/R4B/ValueSets/MessageheaderResponseRequest.md)| Relationship | R5 MessageheaderResponseRequest
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/messageheader-response-request`
| | | `always`| _Equivalent_ <br/>(16585/16584)| `always`| _Equivalent_ <br/>(16592/16593)| `always`| _Equivalent_ <br/>(8997/11306)| **`always`**
| | | `on-error`| _Equivalent_ <br/>(16587/16586)| `on-error`| _Equivalent_ <br/>(16594/16595)| `on-error`| _Equivalent_ <br/>(8999/11308)| **`on-error`**
| | | `never`| _Equivalent_ <br/>(16589/16588)| `never`| _Equivalent_ <br/>(16596/16597)| `never`| _Equivalent_ <br/>(8998/11307)| **`never`**
| | | `on-success`| _Equivalent_ <br/>(16591/16590)| `on-success`| _Equivalent_ <br/>(16598/16599)| `on-success`| _Equivalent_ <br/>(9000/11309)| **`on-success`**
| | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* 

