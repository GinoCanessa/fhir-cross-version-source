Comparison of 
Generated at Monday, April 14, 2025 6:17:29 PM

### ParameterDefinition

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | ParameterDefinition |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ParameterDefinition` |
| Version | 4.0.1 |
| Description | Base StructureDefinition for ParameterDefinition Type: The parameters to the module. This collection specifies both the input and output parameters. Input parameters are provided by the caller as part of the $evaluate operation. Output parameters are included in the GuidanceResponse. |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `1015` |
| Database Snapshot Count | `10` |
| Database Differential Count | `8` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ParameterDefinition` | `ParameterDefinition` | `ParameterDefinition` | ParameterDefinition | Definition of a parameter to a module | 0..* | ParameterDefinition |  |  |
| `ParameterDefinition.documentation` | `ParameterDefinition.documentation` | `documentation` | ParameterDefinition.documentation | A brief description of the parameter | 0..1 | string |  |  |
| `ParameterDefinition.extension` | `ParameterDefinition.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ParameterDefinition.id` | `ParameterDefinition.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ParameterDefinition.max` | `ParameterDefinition.max` | `max` | ParameterDefinition.max | Maximum cardinality (a number of *) | 0..1 | string |  |  |
| `ParameterDefinition.min` | `ParameterDefinition.min` | `min` | ParameterDefinition.min | Minimum cardinality | 0..1 | integer |  |  |
| `ParameterDefinition.name` | `ParameterDefinition.name` | `name` | ParameterDefinition.name | Name used to access the parameter value | 0..1 | code |  |  |
| `ParameterDefinition.profile` | `ParameterDefinition.profile` | `profile` | ParameterDefinition.profile | What profile the value is expected to be | 0..1 | canonical(http://hl7.org/fhir/StructureDefinition/StructureDefinition) |  |  |
| `ParameterDefinition.type` | `ParameterDefinition.type` | `type` | ParameterDefinition.type | What type of value | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-types|4.0.1` |
| `ParameterDefinition.use` | `ParameterDefinition.use` | `use` | ParameterDefinition.use | in \| out | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/operation-parameter-use|4.0.1` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [ParameterDefinition](/docs/R3/ComplexTypes/ParameterDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/ParameterDefinition\|3.0.2` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `403`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `599`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ParameterDefinition](/docs/R4/ComplexTypes/ParameterDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/ParameterDefinition\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1357`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1358`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ParameterDefinition](/docs/R4B/ComplexTypes/ParameterDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/ParameterDefinition\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `912`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1141`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ParameterDefinition](/docs/R5/ComplexTypes/ParameterDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/ParameterDefinition\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition ParameterDefinition from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | [R3 ParameterDefinition](/docs/R3/ComplexTypes/ParameterDefinition.md)| Relationship | R4 ParameterDefinition| Relationship | [R4B ParameterDefinition](/docs/R4B/ComplexTypes/ParameterDefinition.md)| Relationship | [R5 ParameterDefinition](/docs/R5/ComplexTypes/ParameterDefinition.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | `ParameterDefinition`| _Equivalent_<br/>(9681/9682)| **`ParameterDefinition`**| _Equivalent_<br/>(21085/21086)| `ParameterDefinition`| _Equivalent_<br/>(36194/36195)| `ParameterDefinition`
| | | `ParameterDefinition.id`| _Equivalent_<br/>(9683/9684)| **`ParameterDefinition.id`**| _Equivalent_<br/>(21087/21088)| `ParameterDefinition.id`| _Equivalent_<br/>(36196/36197)| `ParameterDefinition.id`
| | | `ParameterDefinition.extension`| _Equivalent_<br/>(9685/9686)| **`ParameterDefinition.extension`**| _Equivalent_<br/>(21089/21090)| `ParameterDefinition.extension`| _Equivalent_<br/>(36198/36199)| `ParameterDefinition.extension`
| | | `ParameterDefinition.name`| _Equivalent_<br/>(9687/9688)| **`ParameterDefinition.name`**| _Equivalent_<br/>(21091/21092)| `ParameterDefinition.name`| _Equivalent_<br/>(36200/36201)| `ParameterDefinition.name`
| | | `ParameterDefinition.use`| _Equivalent_<br/>(9689/9690)| **`ParameterDefinition.use`**| _Equivalent_<br/>(21093/21094)| `ParameterDefinition.use`| _Equivalent_<br/>(36202/36203)| `ParameterDefinition.use`
| | | `ParameterDefinition.min`| _Equivalent_<br/>(9691/9692)| **`ParameterDefinition.min`**| _Equivalent_<br/>(21095/21096)| `ParameterDefinition.min`| _Equivalent_<br/>(36204/36205)| `ParameterDefinition.min`
| | | `ParameterDefinition.max`| _Equivalent_<br/>(9693/9694)| **`ParameterDefinition.max`**| _Equivalent_<br/>(21097/21098)| `ParameterDefinition.max`| _Equivalent_<br/>(36206/36207)| `ParameterDefinition.max`
| | | `ParameterDefinition.documentation`| _Equivalent_<br/>(9695/9696)| **`ParameterDefinition.documentation`**| _Equivalent_<br/>(21099/21100)| `ParameterDefinition.documentation`| _Equivalent_<br/>(36208/36209)| `ParameterDefinition.documentation`
| | | `ParameterDefinition.type`| →→→→ _Equivalent_ →→→→ <br/>(9697)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(9698)| **`ParameterDefinition.type`**| →→→→ _Equivalent_ →→→→ <br/>(21101)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(21102)| `ParameterDefinition.type`| _Equivalent_<br/>(36210/36211)| `ParameterDefinition.type`
| | | `ParameterDefinition.profile`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9699)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(9700)| **`ParameterDefinition.profile`**| _Equivalent_<br/>(21103/21104)| `ParameterDefinition.profile`| _Equivalent_<br/>(36212/36213)| `ParameterDefinition.profile`
| | | *10 of 10 elements used* | | *10 of 10 elements used* | | *10 of 10 elements used* | | *10 of 10 elements used* 

