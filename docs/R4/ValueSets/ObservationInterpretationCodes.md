Comparison of 
Generated at Monday, April 14, 2025 6:17:28 PM

### ObservationInterpretationCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | ObservationInterpretationCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/observation-interpretation` |
| Version | 4.0.1 |
| Description | A categorical assessment, providing a rough qualitative interpretation of the observation value,    such as “normal”/ “abnormal”,”low” / “high”, “better” / “worse”, “susceptible” / “resistant”, “expected”/ “not expected”.    The value set is intended to be for ANY use where coded representation of an interpretation is needed.   <br/><br/>   <br/><br/>   Notes:<br/><br/>   <br/><br/>   This is being communicated in v2.x in OBX-8 (Observation Interpretation), in v3 in ObservationInterpretation (CWE) in R1 (Representative Realm) and in FHIR in    Observation.interpretation. Historically these values come from the laboratory domain, and these codes are extensively    used. The value set binding is extensible, so codes outside the value set that are needed for interpretation concepts    (i.e. particular meanings) that are not included in the value set can be used, and these new codes may also be added to    the value set and published in a future version. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `2617` |
| Database Concept Count | `39` |
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
| [Observation Interpretation Codes](/docs/R2/ValueSets/ObservationInterpretationCodes.md)<br/> `http://hl7.org/fhir/ValueSet/observation-interpretation\|1.0.2` | →→→→→→→<br/>``<br/>- DBKey: `106`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `262`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Observation Interpretation Codes](/docs/R3/ValueSets/ObservationInterpretationCodes.md)<br/> `http://hl7.org/fhir/ValueSet/observation-interpretation\|3.0.2` | →→→→→→→<br/>``<br/>- DBKey: `457`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `681`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ObservationInterpretationCodes](/docs/R4/ValueSets/ObservationInterpretationCodes.md)<br/> `http://hl7.org/fhir/ValueSet/observation-interpretation\|4.0.1` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set ObservationInterpretationCodes from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 Observation Interpretation Codes](/docs/R2/ValueSets/ObservationInterpretationCodes.md)| Relationship | [R3 Observation Interpretation Codes](/docs/R3/ValueSets/ObservationInterpretationCodes.md)| Relationship | R4 ObservationInterpretationCodes| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://terminology.hl7.org/CodeSystem/v3-ObservationInterpretation`
| | | | | **`CAR`**| | | | | 
| `B`| _Equivalent_ <br/>(860/2228)| `B`| _Equivalent_ <br/>(4054/6390)| **`B`**| | | | | 
| `D`| _Equivalent_ <br/>(861/2229)| `D`| _Equivalent_ <br/>(4055/6392)| **`D`**| | | | | 
| `U`| _Equivalent_ <br/>(875/2243)| `U`| _Equivalent_ <br/>(4078/6421)| **`U`**| | | | | 
| `W`| _Equivalent_ <br/>(877/2245)| `W`| _Equivalent_ <br/>(4079/6423)| **`W`**| | | | | 
| `<`| _Equivalent_ <br/>(889/2257)| `<`| _Equivalent_ <br/>(4050/6386)| **`<`**| | | | | 
| `>`| _Equivalent_ <br/>(892/2260)| `>`| _Equivalent_ <br/>(4051/6387)| **`>`**| | | | | 
| `IE`| _Equivalent_ <br/>(879/2247)| `IE`| _Equivalent_ <br/>(4061/6402)| **`IE`**| | | | | 
| `A`| _Equivalent_ <br/>(859/2227)| `A`| _Equivalent_ <br/>(4052/6388)| **`A`**| | | | | 
| `AA`| _Equivalent_ <br/>(880/2248)| `AA`| _Equivalent_ <br/>(4053/6389)| **`AA`**| | | | | 
| `HH`| _Equivalent_ <br/>(856/2224)| `HH`| _Equivalent_ <br/>(4058/6398)| **`HH`**| | | | | 
| `LL`| _Equivalent_ <br/>(857/2225)| `LL`| _Equivalent_ <br/>(4064/6405)| **`LL`**| | | | | 
| `H`| _Equivalent_ <br/>(865/2233)| `H`| _Equivalent_ <br/>(4057/6397)| **`H`**| | | | | 
| `HU`| _Equivalent_ <br/>(869/2237)| `HU`| _Equivalent_ <br/>(4059/6399)| **`HU`**| | | | | 
| `L`| _Equivalent_ <br/>(868/2236)| `L`| _Equivalent_ <br/>(4063/6404)| **`L`**| | | | | 
| `LU`| _Equivalent_ <br/>(867/2235)| `LU`| _Equivalent_ <br/>(4065/6406)| **`LU`**| | | | | 
| `N`| _Equivalent_ <br/>(870/2238)| `N`| _Equivalent_ <br/>(4066/6408)| **`N`**| | | | | 
| `I`| _Equivalent_ <br/>(866/2234)| `I`| _Equivalent_ <br/>(4060/6401)| **`I`**| | | | | 
| | | | | **`NCL`**| | | | | 
| `NS`| _Equivalent_ <br/>(864/2232)| `NS`| _Equivalent_ <br/>(4070/6413)| **`NS`**| | | | | 
| `R`| _Equivalent_ <br/>(871/2239)| `R`| _Equivalent_ <br/>(4072/6415)| **`R`**| | | | | 
| `SYN-R`| _Equivalent_ <br/>(876/2244)| `SYN-R`| _Equivalent_ <br/>(4076/6419)| **`SYN-R`**| | | | | 
| `S`| _Equivalent_ <br/>(873/2241)| `S`| _Equivalent_ <br/>(4074/6417)| **`S`**| | | | | 
| `SDD`| _Equivalent_ <br/>(872/2240)| `SDD`| _Equivalent_ <br/>(4075/6418)| **`SDD`**| | | | | 
| `SYN-S`| _Equivalent_ <br/>(874/2242)| `SYN-S`| _Equivalent_ <br/>(4077/6420)| **`SYN-S`**| | | | | 
| | | | | **`EX`**| | | | | 
| | | | | **`HX`**| | | | | 
| | | | | **`LX`**| | | | | 
| `IND`| _Equivalent_ <br/>(893/2261)| `IND`| _Equivalent_ <br/>(4062/6403)| **`IND`**| | | | | 
| | | | | **`E`**| | | | | 
| `NEG`| _Equivalent_ <br/>(884/2252)| `NEG`| _Equivalent_ <br/>(4068/6411)| **`NEG`**| | | | | 
| `ND`| _Equivalent_ <br/>(888/2256)| `ND`| _Equivalent_ <br/>(4067/6410)| **`ND`**| | | | | 
| `POS`| _Equivalent_ <br/>(886/2254)| `POS`| _Equivalent_ <br/>(4071/6414)| **`POS`**| | | | | 
| `DET`| _Equivalent_ <br/>(885/2253)| `DET`| _Equivalent_ <br/>(4056/6393)| **`DET`**| | | | | 
| | | | | **`EXP`**| | | | | 
| | | | | **`UNE`**| | | | | 
| `NR`| _Equivalent_ <br/>(862/2230)| `NR`| _Equivalent_ <br/>(4069/6412)| **`NR`**| | | | | 
| `RR`| _Equivalent_ <br/>(858/2226)| `RR`| _Equivalent_ <br/>(4073/6416)| **`RR`**| | | | | 
| `WR`| _Equivalent_ <br/>(878/2246)| `WR`| _Equivalent_ <br/>(4080/6424)| **`WR`**| | | | | 
| *31 of 39 codes used* <br/>remaining codes:<br/>`AC`, `HM`, `MS`, `OBX`, `QCF`, `TOX`, `VS`, `null`| | *31 of 39 codes used* <br/>remaining codes:<br/>`AC`, `HM`, `MS`, `OBX`, `QCF`, `TOX`, `VS`, `null`| | *39 of 39 codes used* | | | | 

