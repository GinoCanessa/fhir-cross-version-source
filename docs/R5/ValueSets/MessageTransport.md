Comparison of 
Generated at Monday, April 14, 2025 6:17:42 PM

### MessageTransport

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | MessageTransport |
| Canonical URL | `http://hl7.org/fhir/ValueSet/message-transport` |
| Version | 5.0.0 |
| Description | The protocol used for message transport. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `4736` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/CapabilityStatement` | `CapabilityStatement.messaging.endpoint.protocol` | `http://hl7.org/fhir/ValueSet/message-transport` | `Extensible` | http \| ftp \| mllp + |

### Referenced Systems

* `http://hl7.org/fhir/message-transport`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [MessageTransport](/docs/R4B/ValueSets/MessageTransport.md)<br/> `http://hl7.org/fhir/ValueSet/message-transport\|4.3.0` | →→→→→→→<br/>``<br/>- DBKey: `810`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `1071`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [MessageTransport](/docs/R5/ValueSets/MessageTransport.md)<br/> `http://hl7.org/fhir/ValueSet/message-transport\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set MessageTransport from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | [R4B MessageTransport](/docs/R4B/ValueSets/MessageTransport.md)| Relationship | R5 MessageTransport
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/message-transport`
| | | | | | | `http`| _Equivalent_ <br/>(7651/9951)| **`http`**
| | | | | | | `ftp`| _Equivalent_ <br/>(7650/9950)| **`ftp`**
| | | | | | | `mllp`| _Equivalent_ <br/>(7649/9949)| **`mllp`**
| | | | | | | *3 of 3 codes used* | | *3 of 3 codes used* 

