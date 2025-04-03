Comparison of 
Generated at Thursday, April 3, 2025 8:18:16 AM

### MessageTransport

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | MessageTransport |
| Canonical URL | `http://hl7.org/fhir/ValueSet/message-transport` |
| Version | 4.0.1 |
| Description | The protocol used for message transport. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `2592` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/CapabilityStatement` | `CapabilityStatement.messaging.endpoint.protocol` | `http://hl7.org/fhir/ValueSet/message-transport` | `Extensible` | http \| ftp \| mllp + |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/message-transport`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [MessageTransport](/docs/R2/ValueSets/MessageTransport.md)<br/> `http://hl7.org/fhir/ValueSet/message-transport\|1.0.2` | →→→→→→→<br/>``<br/>- DBKey: `36`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `195`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MessageTransport](/docs/R3/ValueSets/MessageTransport.md)<br/> `http://hl7.org/fhir/ValueSet/message-transport\|3.0.2` | →→→→→→→<br/>``<br/>- DBKey: `363`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `586`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MessageTransport](/docs/R4/ValueSets/MessageTransport.md)<br/> `http://hl7.org/fhir/ValueSet/message-transport\|4.0.1` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set MessageTransport from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 MessageTransport](/docs/R2/ValueSets/MessageTransport.md)| Relationship | [R3 MessageTransport](/docs/R3/ValueSets/MessageTransport.md)| Relationship | R4 MessageTransport| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://terminology.hl7.org/CodeSystem/message-transport`
| `http`| _Equivalent_ <br/>(176/1542)| `http`| _Equivalent_ <br/>(3081/5288)| **`http`**| | | | | 
| `ftp`| _Equivalent_ <br/>(175/1541)| `ftp`| _Equivalent_ <br/>(3080/5287)| **`ftp`**| | | | | 
| `mllp`| _Equivalent_ <br/>(174/1540)| `mllp`| _Equivalent_ <br/>(3079/5286)| **`mllp`**| | | | | 
| *3 of 3 codes used* | | *3 of 3 codes used* | | *3 of 3 codes used* | | | | 

