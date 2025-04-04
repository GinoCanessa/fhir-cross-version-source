Comparison of 
Generated at Friday, April 4, 2025 2:58:59 PM

### DataAbsentReason

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | DataAbsentReason |
| Canonical URL | `http://hl7.org/fhir/ValueSet/data-absent-reason` |
| Version | 5.0.0 |
| Description | Used to specify why the normally expected content of the data element is missing. |
| Status | `Active` |
| Has Escape Valve Code | `True` |
| Database Key | `4461` |
| Database Concept Count | `15` |
| Database Active Concept Count | `15` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Observation` | `Observation.dataAbsentReason` | `http://hl7.org/fhir/ValueSet/data-absent-reason` | `Extensible` | Why the result is missing |
| `http://hl7.org/fhir/StructureDefinition/Observation` | `Observation.component.dataAbsentReason` | `http://hl7.org/fhir/ValueSet/data-absent-reason` | `Extensible` | Why the component result is missing |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/data-absent-reason`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [DataAbsentReason](/docs/R4B/ValueSets/DataAbsentReason.md)<br/> `http://hl7.org/fhir/ValueSet/data-absent-reason\|4.3.0` | →→→→→→→<br/>``<br/>- DBKey: `941`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `1202`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DataAbsentReason](/docs/R5/ValueSets/DataAbsentReason.md)<br/> `http://hl7.org/fhir/ValueSet/data-absent-reason\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set DataAbsentReason from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | [R4B DataAbsentReason](/docs/R4B/ValueSets/DataAbsentReason.md)| Relationship | R5 DataAbsentReason
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://terminology.hl7.org/CodeSystem/data-absent-reason`
| | | | | | | `unknown`| _Equivalent_ <br/>(9063/11374)| **`unknown`**
| | | | | | | `asked-unknown`| _Equivalent_ <br/>(9052/11363)| **`asked-unknown`**
| | | | | | | `temp-unknown`| _Equivalent_ <br/>(9062/11373)| **`temp-unknown`**
| | | | | | | `not-asked`| _Equivalent_ <br/>(9058/11369)| **`not-asked`**
| | | | | | | `asked-declined`| _Equivalent_ <br/>(9051/11362)| **`asked-declined`**
| | | | | | | `masked`| _Equivalent_ <br/>(9054/11365)| **`masked`**
| | | | | | | `not-applicable`| _Equivalent_ <br/>(9057/11368)| **`not-applicable`**
| | | | | | | `unsupported`| _Equivalent_ <br/>(9064/11375)| **`unsupported`**
| | | | | | | `as-text`| _Equivalent_ <br/>(9050/11361)| **`as-text`**
| | | | | | | `error`| _Equivalent_ <br/>(9053/11364)| **`error`**
| | | | | | | `not-a-number`| _Equivalent_ <br/>(9056/11367)| **`not-a-number`**
| | | | | | | `negative-infinity`| _Equivalent_ <br/>(9055/11366)| **`negative-infinity`**
| | | | | | | `positive-infinity`| _Equivalent_ <br/>(9061/11372)| **`positive-infinity`**
| | | | | | | `not-performed`| _Equivalent_ <br/>(9059/11370)| **`not-performed`**
| | | | | | | `not-permitted`| _Equivalent_ <br/>(9060/11371)| **`not-permitted`**
| | | | | | | *15 of 15 codes used* | | *15 of 15 codes used* 

