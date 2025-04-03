Comparison of 
Generated at Thursday, April 3, 2025 8:18:24 AM

### EndpointStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | EndpointStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/endpoint-status` |
| Version | 4.3.0 |
| Description | The status of the endpoint. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `3744` |
| Database Concept Count | `6` |
| Database Active Concept Count | `6` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Endpoint` | `Endpoint.status` | `http://hl7.org/fhir/ValueSet/endpoint-status\|4.3.0` | `Required` | active \| suspended \| error \| off \| entered-in-error \| test |

### Referenced Systems

* `http://hl7.org/fhir/endpoint-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [EndpointStatus](/docs/R3/ValueSets/EndpointStatus.md)<br/> `http://hl7.org/fhir/ValueSet/endpoint-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `414`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `636`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EndpointStatus](/docs/R4/ValueSets/EndpointStatus.md)<br/> `http://hl7.org/fhir/ValueSet/endpoint-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1493`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1494`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EndpointStatus](/docs/R4B/ValueSets/EndpointStatus.md)<br/> `http://hl7.org/fhir/ValueSet/endpoint-status\|4.3.0` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `874`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1135`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EndpointStatus](/docs/R5/ValueSets/EndpointStatus.md)<br/> `http://hl7.org/fhir/ValueSet/endpoint-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set EndpointStatus from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | [R3 EndpointStatus](/docs/R3/ValueSets/EndpointStatus.md)| Relationship | [R4 EndpointStatus](/docs/R4/ValueSets/EndpointStatus.md)| Relationship | R4B EndpointStatus| Relationship | [R5 EndpointStatus](/docs/R5/ValueSets/EndpointStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://hl7.org/fhir/endpoint-status`
| | | `active`| _Equivalent_ <br/>(3686/5971)| `active`| _Equivalent_ <br/>(15870/15871)| **`active`**| _Equivalent_ <br/>(8043/10349)| `active`
| | | `suspended`| _Equivalent_ <br/>(3689/5974)| `suspended`| _Equivalent_ <br/>(15872/15873)| **`suspended`**| _Equivalent_ <br/>(8047/10352)| `suspended`
| | | `error`| _Equivalent_ <br/>(3687/5972)| `error`| _Equivalent_ <br/>(15874/15875)| **`error`**| _Equivalent_ <br/>(8045/10350)| `error`
| | | `off`| _Equivalent_ <br/>(3690/5975)| `off`| _Equivalent_ <br/>(15876/15877)| **`off`**| _Equivalent_ <br/>(8046/10353)| `off`
| | | `entered-in-error`| _Equivalent_ <br/>(3688/5973)| `entered-in-error`| _Equivalent_ <br/>(15878/15879)| **`entered-in-error`**| _Equivalent_ <br/>(8044/10351)| `entered-in-error`
| | | `test`| _Equivalent_ <br/>(3685/5970)| `test`| _Equivalent_ <br/>(15880/15881)| **`test`**| | | 
| | | *6 of 6 codes used* | | *6 of 6 codes used* | | *6 of 6 codes used* | | *5 of 5 codes used* 

