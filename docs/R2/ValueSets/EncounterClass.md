Comparison of 
Generated at Monday, April 14, 2025 6:17:15 PM

### EncounterClass

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | EncounterClass |
| Canonical URL | `http://hl7.org/fhir/ValueSet/encounter-class` |
| Version | 1.0.2 |
| Description | Classification of the encounter |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `143` |
| Database Concept Count | `9` |
| Database Active Concept Count | `9` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Encounter` | `Encounter.class` | `http://hl7.org/fhir/ValueSet/encounter-class` | `Required` | inpatient \| outpatient \| ambulatory \| emergency + |

### Referenced Systems

* `http://hl7.org/fhir/encounter-class`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [EncounterClass](/docs/R2/ValueSets/EncounterClass.md)<br/> `http://hl7.org/fhir/ValueSet/encounter-class\|1.0.2` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `74`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `230`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ActEncounterCode](/docs/R3/ValueSets/ActEncounterCode.md)<br/> `http://hl7.org/fhir/ValueSet/v3-ActEncounterCode\|2014-03-26` | →→→→→→→<br/>``<br/>- DBKey: `410`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `632`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [v3.ActEncounterCode](/docs/R4/ValueSets/V3ActEncounterCode.md)<br/> `http://terminology.hl7.org/ValueSet/v3-ActEncounterCode\|2014-03-26` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set EncounterClass from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 EncounterClass| Relationship | [R3 ActEncounterCode](/docs/R3/ValueSets/ActEncounterCode.md)| Relationship | [R4 v3.ActEncounterCode](/docs/R4/ValueSets/V3ActEncounterCode.md)| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/encounter-class`
| **`inpatient`**| _Equivalent_ <br/>(529/1886)| `IMP`| _Equivalent_ <br/>(3653/5937)| `IMP`| | | | | 
| **`outpatient`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(530)<hr/>←←←← _Equivalent_ ←←←← <br/>(1881) | `AMB`| _Equivalent_ <br/>(3649/5933)| `AMB`| | | | | 
| **`ambulatory`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(531)<hr/>←←←← _Equivalent_ ←←←← <br/>(1882) | `AMB`| _Equivalent_ <br/>(3649/5933)| `AMB`| | | | | 
| **`emergency`**| _Equivalent_ <br/>(532/1883)| `EMER`| _Equivalent_ <br/>(3650/5934)| `EMER`| | | | | 
| **`home`**| _Equivalent_ <br/>(533/1885)| `HH`| _Equivalent_ <br/>(3652/5936)| `HH`| | | | | 
| **`field`**| _Equivalent_ <br/>(534/1884)| `FLD`| _Equivalent_ <br/>(3651/5935)| `FLD`| | | | | 
| **`daytime`**| _Equivalent_ <br/>(535/1889)| `SS`| _Equivalent_ <br/>(3656/5941)| `SS`| | | | | 
| **`virtual`**| _Equivalent_ <br/>(536/1890)| `VR`| _Equivalent_ <br/>(3657/5942)| `VR`| | | | | 
| **`other`**| | | | | | | | | 
| *9 of 9 codes used* | | *7 of 10 codes used* <br/>remaining codes:<br/>`ACUTE`, `NONAC`, `PRENC`| | *7 of 11 codes used* <br/>remaining codes:<br/>`ACUTE`, `NONAC`, `OBSENC`, `PRENC`| | | | 

