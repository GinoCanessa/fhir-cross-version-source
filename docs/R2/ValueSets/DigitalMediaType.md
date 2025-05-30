Comparison of 
Generated at Monday, April 14, 2025 6:17:15 PM

### DigitalMediaType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | DigitalMediaType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/digital-media-type` |
| Version | 1.0.2 |
| Description | Whether the Media is a photo, video, or audio |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `135` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Media` | `Media.type` | `http://hl7.org/fhir/ValueSet/digital-media-type` | `Required` | photo \| video \| audio |

### Referenced Systems

* `http://hl7.org/fhir/digital-media-type`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [DigitalMediaType](/docs/R2/ValueSets/DigitalMediaType.md)<br/> `http://hl7.org/fhir/ValueSet/digital-media-type\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `95`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `251`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [DigitalMediaType](/docs/R3/ValueSets/DigitalMediaType.md)<br/> `http://hl7.org/fhir/ValueSet/digital-media-type\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `435`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `657`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [MediaType](/docs/R4/ValueSets/MediaType.md)<br/> `http://hl7.org/fhir/ValueSet/media-type\|4.0.1` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set DigitalMediaType from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 DigitalMediaType| Relationship | [R3 DigitalMediaType](/docs/R3/ValueSets/DigitalMediaType.md)| Relationship | [R4 MediaType](/docs/R4/ValueSets/MediaType.md)| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/digital-media-type`
| **`photo`**| _Equivalent_ <br/>(794/2156)| `photo`| _Equivalent_ <br/>(3934/6252)| `image`| | | | | 
| **`video`**| _Equivalent_ <br/>(795/2157)| `video`| _Equivalent_ <br/>(3935/6253)| `video`| | | | | 
| **`audio`**| _Equivalent_ <br/>(796/2158)| `audio`| _Equivalent_ <br/>(3933/6254)| `audio`| | | | | 
| *3 of 3 codes used* | | *3 of 3 codes used* | | *3 of 3 codes used* | | | | 

