Comparison of 
Generated at Friday, April 4, 2025 2:58:43 PM

### v3.ActEncounterCode

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | v3.ActEncounterCode |
| Canonical URL | `http://terminology.hl7.org/ValueSet/v3-ActEncounterCode` |
| Version | 2014-03-26 |
| Description | Domain provides codes that qualify the ActEncounterClass (ENC) |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `3288` |
| Database Concept Count | `11` |
| Database Active Concept Count | `11` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Encounter` | `Encounter.class` | `http://terminology.hl7.org/ValueSet/v3-ActEncounterCode` | `Extensible` | Classification of patient encounter |
| `http://hl7.org/fhir/StructureDefinition/Encounter` | `Encounter.classHistory.class` | `http://terminology.hl7.org/ValueSet/v3-ActEncounterCode` | `Extensible` | inpatient \| outpatient \| ambulatory \| emergency + |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/v3-ActCode`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [EncounterClass](/docs/R2/ValueSets/EncounterClass.md)<br/> `http://hl7.org/fhir/ValueSet/encounter-class\|1.0.2` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `74`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `230`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ActEncounterCode](/docs/R3/ValueSets/ActEncounterCode.md)<br/> `http://hl7.org/fhir/ValueSet/v3-ActEncounterCode\|2014-03-26` | →→→→→→→<br/>``<br/>- DBKey: `410`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `632`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [v3.ActEncounterCode](/docs/R4/ValueSets/V3ActEncounterCode.md)<br/> `http://terminology.hl7.org/ValueSet/v3-ActEncounterCode\|2014-03-26` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set v3.ActEncounterCode from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 EncounterClass](/docs/R2/ValueSets/EncounterClass.md)| Relationship | [R3 ActEncounterCode](/docs/R3/ValueSets/ActEncounterCode.md)| Relationship | R4 v3.ActEncounterCode| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://terminology.hl7.org/CodeSystem/v3-ActCode`
| `outpatient`| →→→→ _Equivalent_ →→→→ <br/>(530)<hr/>←←←← __ ←←←← <br/>() | `AMB`| _Equivalent_ <br/>(3649/5933)| **`AMB`**| | | | | 
| `ambulatory`| →→→→ _Equivalent_ →→→→ <br/>(531)<hr/>←←←← __ ←←←← <br/>() | `AMB`| _Equivalent_ <br/>(3649/5933)| **`AMB`**| | | | | 
| `emergency`| _Equivalent_ <br/>(532/1883)| `EMER`| _Equivalent_ <br/>(3650/5934)| **`EMER`**| | | | | 
| `field`| _Equivalent_ <br/>(534/1884)| `FLD`| _Equivalent_ <br/>(3651/5935)| **`FLD`**| | | | | 
| `home`| _Equivalent_ <br/>(533/1885)| `HH`| _Equivalent_ <br/>(3652/5936)| **`HH`**| | | | | 
| `inpatient`| _Equivalent_ <br/>(529/1886)| `IMP`| _Equivalent_ <br/>(3653/5937)| **`IMP`**| | | | | 
| | | `ACUTE`| _Equivalent_ <br/>(3648/5932)| **`ACUTE`**| | | | | 
| | | `NONAC`| _Equivalent_ <br/>(3654/5938)| **`NONAC`**| | | | | 
| | | | | **`OBSENC`**| | | | | 
| | | `PRENC`| _Equivalent_ <br/>(3655/5940)| **`PRENC`**| | | | | 
| `daytime`| _Equivalent_ <br/>(535/1889)| `SS`| _Equivalent_ <br/>(3656/5941)| **`SS`**| | | | | 
| `virtual`| _Equivalent_ <br/>(536/1890)| `VR`| _Equivalent_ <br/>(3657/5942)| **`VR`**| | | | | 
| *8 of 9 codes used* <br/>remaining codes:<br/>`other`| | *10 of 10 codes used* | | *11 of 11 codes used* | | | | 

