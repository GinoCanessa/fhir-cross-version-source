Comparison of 
Generated at Friday, April 4, 2025 2:58:58 PM

### TriggerType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | TriggerType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/trigger-type` |
| Version | 5.0.0 |
| Description | The type of trigger. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4981` |
| Database Concept Count | `8` |
| Database Active Concept Count | `8` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/TriggerDefinition` | `TriggerDefinition.type` | `http://hl7.org/fhir/ValueSet/trigger-type\|5.0.0` | `Required` | named-event \| periodic \| data-changed \| data-added \| data-modified \| data-removed \| data-accessed \| data-access-ended |

### Referenced Systems

* `http://hl7.org/fhir/trigger-type`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [TriggerType](/docs/R3/ValueSets/TriggerType.md)<br/> `http://hl7.org/fhir/ValueSet/trigger-type\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `524`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `745`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TriggerType](/docs/R4/ValueSets/TriggerType.md)<br/> `http://hl7.org/fhir/ValueSet/trigger-type\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1767`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1768`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TriggerType](/docs/R4B/ValueSets/TriggerType.md)<br/> `http://hl7.org/fhir/ValueSet/trigger-type\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1007`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1268`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TriggerType](/docs/R5/ValueSets/TriggerType.md)<br/> `http://hl7.org/fhir/ValueSet/trigger-type\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set TriggerType from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | [R3 TriggerType](/docs/R3/ValueSets/TriggerType.md)| Relationship | [R4 TriggerType](/docs/R4/ValueSets/TriggerType.md)| Relationship | [R4B TriggerType](/docs/R4B/ValueSets/TriggerType.md)| Relationship | R5 TriggerType
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/trigger-type`
| | | `named-event`| _Equivalent_ <br/>(4911/7246)| `named-event`| _Equivalent_ <br/>(18336/18337)| `named-event`| _Equivalent_ <br/>(9494/11833)| **`named-event`**
| | | `periodic`| _Equivalent_ <br/>(4912/7247)| `periodic`| _Equivalent_ <br/>(18338/18339)| `periodic`| _Equivalent_ <br/>(9495/11834)| **`periodic`**
| | | | | `data-changed`| _Equivalent_ <br/>(18340/18341)| `data-changed`| _Equivalent_ <br/>(9492/11831)| **`data-changed`**
| | | `data-added`| _Equivalent_ <br/>(4916/7242)| `data-added`| _Equivalent_ <br/>(18342/18343)| `data-added`| _Equivalent_ <br/>(9499/11838)| **`data-added`**
| | | `data-modified`| _Equivalent_ <br/>(4913/7244)| `data-modified`| _Equivalent_ <br/>(18344/18345)| `data-modified`| _Equivalent_ <br/>(9496/11835)| **`data-modified`**
| | | `data-removed`| _Equivalent_ <br/>(4914/7245)| `data-removed`| _Equivalent_ <br/>(18346/18347)| `data-removed`| _Equivalent_ <br/>(9497/11836)| **`data-removed`**
| | | `data-accessed`| _Equivalent_ <br/>(4915/7241)| `data-accessed`| _Equivalent_ <br/>(18348/18349)| `data-accessed`| _Equivalent_ <br/>(9498/11837)| **`data-accessed`**
| | | `data-access-ended`| _Equivalent_ <br/>(4910/7240)| `data-access-ended`| _Equivalent_ <br/>(18350/18351)| `data-access-ended`| _Equivalent_ <br/>(9493/11832)| **`data-access-ended`**
| | | *7 of 7 codes used* | | *8 of 8 codes used* | | *8 of 8 codes used* | | *8 of 8 codes used* 

