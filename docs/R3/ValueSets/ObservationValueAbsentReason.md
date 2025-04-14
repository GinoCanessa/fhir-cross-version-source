Comparison of 
Generated at Monday, April 14, 2025 6:17:20 PM

### Observation Value Absent Reason

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Observation Value Absent Reason |
| Canonical URL | `http://hl7.org/fhir/ValueSet/observation-valueabsentreason` |
| Version | 3.0.2 |
| Description | This value set defines the set of codes for identifying the reason why the expected result in Observation.value[x] is missing. |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `1374` |
| Database Concept Count | `10` |
| Database Active Concept Count | `10` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Observation` | `Observation.dataAbsentReason` | `http://hl7.org/fhir/ValueSet/observation-valueabsentreason` | `Extensible` | Why the result is missing |
| `http://hl7.org/fhir/StructureDefinition/Observation` | `Observation.component.dataAbsentReason` | `http://hl7.org/fhir/ValueSet/observation-valueabsentreason` | `Extensible` | Why the component result is missing |

### Referenced Systems

* `http://hl7.org/fhir/data-absent-reason`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Observation Value Absent Reason](/docs/R2/ValueSets/ObservationValueAbsentReason.md)<br/> `http://hl7.org/fhir/ValueSet/observation-valueabsentreason\|1.0.2` | →→→→→→→<br/>``<br/>- DBKey: `105`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `261`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Observation Value Absent Reason](/docs/R3/ValueSets/ObservationValueAbsentReason.md)<br/> `http://hl7.org/fhir/ValueSet/observation-valueabsentreason\|3.0.2` | →→→→→→→<br/>``<br/>- DBKey: `456`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `680`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [DataAbsentReason](/docs/R4/ValueSets/DataAbsentReason.md)<br/> `http://hl7.org/fhir/ValueSet/data-absent-reason\|4.0.1` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set Observation Value Absent Reason from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 Observation Value Absent Reason](/docs/R2/ValueSets/ObservationValueAbsentReason.md)| Relationship | R3 Observation Value Absent Reason| Relationship | [R4 DataAbsentReason](/docs/R4/ValueSets/DataAbsentReason.md)| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/data-absent-reason`
| `unknown`| _Equivalent_ <br/>(854/2222)| **`unknown`**| _Equivalent_ <br/>(4048/6378)| `unknown`| | | | | 
| `asked`| _Equivalent_ <br/>(849/2215)| **`asked`**| _Equivalent_ <br/>(4041/6373)| `asked-unknown`| | | | | 
| `asked`| _Equivalent_ <br/>(849/2215)| **`asked`**| _Equivalent_ <br/>(4040/6381)| `asked-declined`| | | | | 
| `temp`| _Equivalent_ <br/>(847/2221)| **`temp`**| _Equivalent_ <br/>(4047/6383)| `temp-unknown`| | | | | 
| `not-asked`| _Equivalent_ <br/>(853/2219)| **`not-asked`**| _Equivalent_ <br/>(4045/6375)| `not-asked`| | | | | 
| `masked`| _Equivalent_ <br/>(850/2218)| **`masked`**| _Equivalent_ <br/>(4044/6372)| `masked`| | | | | 
| `unsupported`| _Equivalent_ <br/>(848/2223)| **`unsupported`**| _Equivalent_ <br/>(4049/6379)| `unsupported`| | | | | 
| `astext`| _Equivalent_ <br/>(855/2216)| **`astext`**| _Equivalent_ <br/>(4042/6371)| `as-text`| | | | | 
| `error`| _Equivalent_ <br/>(852/2217)| **`error`**| _Equivalent_ <br/>(4043/6374)| `error`| | | | | 
| `NaN`| _Equivalent_ <br/>(851/2214)| **`NaN`**| _Equivalent_ <br/>(4038/6385)| `not-a-number`| | | | | 
| `NaN`| _Equivalent_ <br/>(851/2214)| **`NaN`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4037)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(6380) | `negative-infinity`| | | | | 
| `NaN`| _Equivalent_ <br/>(851/2214)| **`NaN`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4039)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(6377) | `positive-infinity`| | | | | 
| | | **`not-performed`**| _Equivalent_ <br/>(4046/6376)| `not-performed`| | | | | 
| *9 of 9 codes used* | | *10 of 10 codes used* | | *13 of 15 codes used* <br/>remaining codes:<br/>`not-applicable`, `not-permitted`| | | | 

