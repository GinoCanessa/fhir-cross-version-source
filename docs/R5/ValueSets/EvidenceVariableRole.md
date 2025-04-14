Comparison of 
Generated at Monday, April 14, 2025 6:17:42 PM

### EvidenceVariableRole

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | EvidenceVariableRole |
| Canonical URL | `http://hl7.org/fhir/ValueSet/variable-role` |
| Version | 5.0.0 |
| Description | The role that the assertion variable plays. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `5001` |
| Database Concept Count | `6` |
| Database Active Concept Count | `6` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Evidence` | `Evidence.variableDefinition.variableRole` | `http://hl7.org/fhir/ValueSet/variable-role` | `Extensible` | population \| subpopulation \| exposure \| referenceExposure \| measuredVariable \| confounder |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/variable-role`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [EvidenceVariableRole](/docs/R4B/ValueSets/EvidenceVariableRole.md)<br/> `http://hl7.org/fhir/ValueSet/variable-role\|4.3.0` | →→→→→→→<br/>``<br/>- DBKey: `884`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `1145`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [EvidenceVariableRole](/docs/R5/ValueSets/EvidenceVariableRole.md)<br/> `http://hl7.org/fhir/ValueSet/variable-role\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set EvidenceVariableRole from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | [R4B EvidenceVariableRole](/docs/R4B/ValueSets/EvidenceVariableRole.md)| Relationship | R5 EvidenceVariableRole
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://terminology.hl7.org/CodeSystem/variable-role`
| | | | | | | `population`| _Equivalent_ <br/>(8208/10513)| **`population`**
| | | | | | | `subpopulation`| _Equivalent_ <br/>(8210/10515)| **`subpopulation`**
| | | | | | | `exposure`| _Equivalent_ <br/>(8206/10511)| **`exposure`**
| | | | | | | `referenceExposure`| _Equivalent_ <br/>(8209/10514)| **`referenceExposure`**
| | | | | | | `measuredVariable`| _Equivalent_ <br/>(8207/10512)| **`measuredVariable`**
| | | | | | | `confounder`| _Equivalent_ <br/>(8205/10510)| **`confounder`**
| | | | | | | *6 of 6 codes used* | | *6 of 6 codes used* 

