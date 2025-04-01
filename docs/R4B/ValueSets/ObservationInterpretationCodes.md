Comparison of 
Generated at Tuesday, April 1, 2025 1:39:26 PM

### ObservationInterpretationCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | ObservationInterpretationCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/observation-interpretation` |
| Version | 4.3.0 |
| Description | A categorical assessment, providing a rough qualitative interpretation of the observation value,    such as “normal”/ “abnormal”,”low” / “high”, “better” / “worse”, “susceptible” / “resistant”, “expected”/ “not expected”.    The value set is intended to be for ANY use where coded representation of an interpretation is needed.   <br/><br/>   <br/><br/>   Notes:<br/><br/>   <br/><br/>   This is being communicated in v2.x in OBX-8 (Observation Interpretation), in v3 in ObservationInterpretation (CWE) in R1 (Representative Realm) and in FHIR in    Observation.interpretation. Historically these values come from the laboratory domain, and these codes are extensively    used. The value set binding is extensible, so codes outside the value set that are needed for interpretation concepts    (i.e. particular meanings) that are not included in the value set can be used, and these new codes may also be added to    the value set and published in a future version. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `3962` |
| Database Concept Count | `47` |
| Database Active Concept Count | `39` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Observation` | `Observation.interpretation` | `http://hl7.org/fhir/ValueSet/observation-interpretation` | `Extensible` | High, low, normal, etc. |
| `http://hl7.org/fhir/StructureDefinition/Observation` | `Observation.component.interpretation` | `http://hl7.org/fhir/ValueSet/observation-interpretation` | `Extensible` | High, low, normal, etc. |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/v3-ObservationInterpretation`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [ObservationInterpretationCodes](/docs/R4B/ValueSets/ObservationInterpretationCodes.md)<br/> `http://hl7.org/fhir/ValueSet/observation-interpretation\|4.3.0` | →→→→→→→<br/>``<br/>- DBKey: `942`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `1203`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ObservationInterpretationCodes](/docs/R5/ValueSets/ObservationInterpretationCodes.md)<br/> `http://hl7.org/fhir/ValueSet/observation-interpretation\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set ObservationInterpretationCodes from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | R4B ObservationInterpretationCodes| Relationship | [R5 ObservationInterpretationCodes](/docs/R5/ValueSets/ObservationInterpretationCodes.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://terminology.hl7.org/CodeSystem/v3-ObservationInterpretation`
| | | | | | | **`CAR`**| _Equivalent_ <br/>(9070/11381)| `CAR`
| | | | | | | **`B`**| _Equivalent_ <br/>(9069/11380)| `B`
| | | | | | | **`D`**| _Equivalent_ <br/>(9071/11382)| `D`
| | | | | | | **`U`**| _Equivalent_ <br/>(9100/11411)| `U`
| | | | | | | **`W`**| _Equivalent_ <br/>(9102/11413)| `W`
| | | | | | | **`<`**| _Equivalent_ <br/>(9065/11376)| `<`
| | | | | | | **`>`**| _Equivalent_ <br/>(9066/11377)| `>`
| | | | | | | **`IE`**| _Equivalent_ <br/>(9081/11392)| `IE`
| | | | | | | **`A`**| _Equivalent_ <br/>(9067/11378)| `A`
| | | | | | | **`AA`**| _Equivalent_ <br/>(9068/11379)| `AA`
| | | | | | | **`HH`**| _Equivalent_ <br/>(9077/11388)| `HH`
| | | | | | | **`LL`**| _Equivalent_ <br/>(9084/11395)| `LL`
| | | | | | | **`H`**| _Equivalent_ <br/>(9076/11387)| `H`
| | | | | | | **`HU`**| _Equivalent_ <br/>(9078/11389)| `HU`
| | | | | | | **`L`**| _Equivalent_ <br/>(9083/11394)| `L`
| | | | | | | **`LU`**| _Equivalent_ <br/>(9085/11396)| `LU`
| | | | | | | **`N`**| _Equivalent_ <br/>(9087/11398)| `N`
| | | | | | | **`I`**| _Equivalent_ <br/>(9080/11391)| `I`
| | | | | | | **`NCL`**| _Equivalent_ <br/>(9088/11399)| `NCL`
| | | | | | | **`NS`**| _Equivalent_ <br/>(9092/11403)| `NS`
| | | | | | | **`R`**| _Equivalent_ <br/>(9094/11405)| `R`
| | | | | | | **`SYN-R`**| _Equivalent_ <br/>(9098/11409)| `SYN-R`
| | | | | | | **`S`**| _Equivalent_ <br/>(9096/11407)| `S`
| | | | | | | **`SDD`**| _Equivalent_ <br/>(9097/11408)| `SDD`
| | | | | | | **`SYN-S`**| _Equivalent_ <br/>(9099/11410)| `SYN-S`
| | | | | | | **`EX`**| _Equivalent_ <br/>(9074/11385)| `EX`
| | | | | | | **`HX`**| _Equivalent_ <br/>(9079/11390)| `HX`
| | | | | | | **`LX`**| _Equivalent_ <br/>(9086/11397)| `LX`
| | | | | | | **`IND`**| _Equivalent_ <br/>(9082/11393)| `IND`
| | | | | | | **`E`**| _Equivalent_ <br/>(9073/11384)| `E`
| | | | | | | **`NEG`**| _Equivalent_ <br/>(9090/11401)| `NEG`
| | | | | | | **`ND`**| _Equivalent_ <br/>(9089/11400)| `ND`
| | | | | | | **`POS`**| _Equivalent_ <br/>(9093/11404)| `POS`
| | | | | | | **`DET`**| _Equivalent_ <br/>(9072/11383)| `DET`
| | | | | | | **`EXP`**| _Equivalent_ <br/>(9075/11386)| `EXP`
| | | | | | | **`UNE`**| _Equivalent_ <br/>(9101/11412)| `UNE`
| | | | | | | **`NR`**| _Equivalent_ <br/>(9091/11402)| `NR`
| | | | | | | **`RR`**| _Equivalent_ <br/>(9095/11406)| `RR`
| | | | | | | **`WR`**| _Equivalent_ <br/>(9103/11414)| `WR`
| | | | | | | **`_GeneticObservationInterpretation`**| | | 
| | | | | | | **`_ObservationInterpretationChange`**| | | 
| | | | | | | **`_ObservationInterpretationExceptions`**| | | 
| | | | | | | **`_ObservationInterpretationNormality`**| | | 
| | | | | | | **`_ObservationInterpretationSusceptibility`**| | | 
| | | | | | | **`ObservationInterpretationDetection`**| | | 
| | | | | | | **`ObservationInterpretationExpectation`**| | | 
| | | | | | | **`ReactivityObservationInterpretation`**| | | 
| | | | | | | *47 of 47 codes used* | | *39 of 57 codes used* 

