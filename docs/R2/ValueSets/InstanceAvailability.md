Comparison of 
Generated at Friday, April 4, 2025 2:58:31 PM

### InstanceAvailability

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | InstanceAvailability |
| Canonical URL | `http://hl7.org/fhir/ValueSet/instance-availability` |
| Version | 1.0.2 |
| Description | Availability of the resource |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `198` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ImagingStudy` | `ImagingStudy.availability` | `http://hl7.org/fhir/ValueSet/instance-availability` | `Required` | ONLINE \| OFFLINE \| NEARLINE \| UNAVAILABLE (0008,0056) |
| `http://hl7.org/fhir/StructureDefinition/ImagingStudy` | `ImagingStudy.series.availability` | `http://hl7.org/fhir/ValueSet/instance-availability` | `Required` | ONLINE \| OFFLINE \| NEARLINE \| UNAVAILABLE |

### Referenced Systems

* `http://nema.org/dicom/dicm`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [InstanceAvailability](/docs/R2/ValueSets/InstanceAvailability.md)<br/> `http://hl7.org/fhir/ValueSet/instance-availability\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `88`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `244`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [InstanceAvailability](/docs/R3/ValueSets/InstanceAvailability.md)<br/> `http://hl7.org/fhir/ValueSet/instance-availability\|3.0.2` | →→→→→→→<br/>``<br/>- DBKey: `1325`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `1326`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [InstanceAvailability](/docs/R4/ValueSets/InstanceAvailability.md)<br/> `http://hl7.org/fhir/ValueSet/instance-availability\|4.0.1` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set InstanceAvailability from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 InstanceAvailability| Relationship | [R3 InstanceAvailability](/docs/R3/ValueSets/InstanceAvailability.md)| Relationship | [R4 InstanceAvailability](/docs/R4/ValueSets/InstanceAvailability.md)| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://nema.org/dicom/dicm`
| **`ONLINE`**| _Equivalent_ <br/>(619/1980)| `ONLINE`| _Equivalent_ <br/>(13537/13538)| `ONLINE`| | | | | 
| **`OFFLINE`**| _Equivalent_ <br/>(622/1979)| `OFFLINE`| _Equivalent_ <br/>(13539/13540)| `OFFLINE`| | | | | 
| **`NEARLINE`**| _Equivalent_ <br/>(620/1978)| `NEARLINE`| _Equivalent_ <br/>(13541/13542)| `NEARLINE`| | | | | 
| **`UNAVAILABLE`**| _Equivalent_ <br/>(621/1981)| `UNAVAILABLE`| _Equivalent_ <br/>(13543/13544)| `UNAVAILABLE`| | | | | 
| *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | | | 

