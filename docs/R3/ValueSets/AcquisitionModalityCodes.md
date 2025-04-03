Comparison of 
Generated at Thursday, April 3, 2025 8:18:10 AM

### Acquisition Modality Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Acquisition Modality Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/dicom-cid29` |
| Version | 20121129 |
| Description | This Value Set includes codes that may be used to identify an image or waveform acquisition modality, as used in the ImagingStudy resource, Dicom  Attribute Modality (0008,0060) or HL7 v2 Table 0259 (see HL7 v2.6 Chapter 8 Section 8.8.8.47). It generally corresponds to a class of diagnostic equipment, or to a specific acquisition function or technique in a device. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `1193` |
| Database Concept Count | `37` |
| Database Active Concept Count | `37` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ImagingStudy` | `ImagingStudy.modalityList` | `http://hl7.org/fhir/ValueSet/dicom-cid29` | `Extensible` | All series modality if actual acquisition modalities |
| `http://hl7.org/fhir/StructureDefinition/ImagingStudy` | `ImagingStudy.series.modality` | `http://hl7.org/fhir/ValueSet/dicom-cid29` | `Extensible` | The modality of the instances in the series |

### Referenced Systems

* `http://dicom.nema.org/resources/ontology/DCM`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Acquisition Modality Codes](/docs/R2/ValueSets/AcquisitionModalityCodes.md)<br/> `http://hl7.org/fhir/ValueSet/dicom-cid29\|20121129` | →→→→→→→<br/>``<br/>- DBKey: `89`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `245`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Acquisition Modality Codes](/docs/R3/ValueSets/AcquisitionModalityCodes.md)<br/> `http://hl7.org/fhir/ValueSet/dicom-cid29\|20121129` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set Acquisition Modality Codes from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 Acquisition Modality Codes](/docs/R2/ValueSets/AcquisitionModalityCodes.md)| Relationship | R3 Acquisition Modality Codes| Relationship | *No Map* | Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://dicom.nema.org/resources/ontology/DCM`
| `AR`| _Equivalent_ <br/>(627/1982)| **`AR`**| | | | | | | 
| `BMD`| _Equivalent_ <br/>(623/1984)| **`BMD`**| | | | | | | 
| `BDUS`| _Equivalent_ <br/>(644/1983)| **`BDUS`**| | | | | | | 
| `EPS`| _Equivalent_ <br/>(650/1989)| **`EPS`**| | | | | | | 
| `CR`| _Equivalent_ <br/>(628/1985)| **`CR`**| | | | | | | 
| `CT`| _Equivalent_ <br/>(629/1986)| **`CT`**| | | | | | | 
| `DX`| _Equivalent_ <br/>(630/1987)| **`DX`**| | | | | | | 
| `ECG`| _Equivalent_ <br/>(649/1988)| **`ECG`**| | | | | | | 
| `ES`| _Equivalent_ <br/>(631/1990)| **`ES`**| | | | | | | 
| `XC`| _Equivalent_ <br/>(648/2018)| **`XC`**| | | | | | | 
| `GM`| _Equivalent_ <br/>(632/1991)| **`GM`**| | | | | | | 
| `HD`| _Equivalent_ <br/>(633/1992)| **`HD`**| | | | | | | 
| `IO`| _Equivalent_ <br/>(634/1993)| **`IO`**| | | | | | | 
| | | **`IVOCT`**| | | | | | | 
| `IVUS`| _Equivalent_ <br/>(657/1995)| **`IVUS`**| | | | | | | 
| `KER`| _Equivalent_ <br/>(625/1996)| **`KER`**| | | | | | | 
| `LEN`| _Equivalent_ <br/>(626/1997)| **`LEN`**| | | | | | | 
| `MR`| _Equivalent_ <br/>(636/1999)| **`MR`**| | | | | | | 
| `MG`| _Equivalent_ <br/>(635/1998)| **`MG`**| | | | | | | 
| `NM`| _Equivalent_ <br/>(637/2000)| **`NM`**| | | | | | | 
| `OAM`| _Equivalent_ <br/>(651/2001)| **`OAM`**| | | | | | | 
| `OCT`| _Equivalent_ <br/>(652/2002)| **`OCT`**| | | | | | | 
| `OPM`| _Equivalent_ <br/>(653/2004)| **`OPM`**| | | | | | | 
| `OP`| _Equivalent_ <br/>(638/2003)| **`OP`**| | | | | | | 
| `OPR`| _Equivalent_ <br/>(654/2005)| **`OPR`**| | | | | | | 
| `OPT`| _Equivalent_ <br/>(655/2006)| **`OPT`**| | | | | | | 
| `OPV`| _Equivalent_ <br/>(656/2007)| **`OPV`**| | | | | | | 
| | | **`OSS`**| | | | | | | 
| `PX`| _Equivalent_ <br/>(640/2010)| **`PX`**| | | | | | | 
| `PT`| _Equivalent_ <br/>(639/2009)| **`PT`**| | | | | | | 
| `RF`| _Equivalent_ <br/>(641/2011)| **`RF`**| | | | | | | 
| `RG`| _Equivalent_ <br/>(642/2012)| **`RG`**| | | | | | | 
| `SM`| _Equivalent_ <br/>(643/2013)| **`SM`**| | | | | | | 
| `SRF`| _Equivalent_ <br/>(624/2014)| **`SRF`**| | | | | | | 
| `US`| _Equivalent_ <br/>(645/2015)| **`US`**| | | | | | | 
| `VA`| _Equivalent_ <br/>(646/2016)| **`VA`**| | | | | | | 
| `XA`| _Equivalent_ <br/>(647/2017)| **`XA`**| | | | | | | 
| *35 of 37 codes used* <br/>remaining codes:<br/>`IVOCT`, `OSS`| | *37 of 37 codes used* | | | | | | 

