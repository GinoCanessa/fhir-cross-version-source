Comparison of 
Generated at Friday, April 4, 2025 2:58:37 PM

### UDIEntryType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | UDIEntryType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/udi-entry-type` |
| Version | 3.0.2 |
| Description | Codes to identify how UDI data was entered |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `1529` |
| Database Concept Count | `6` |
| Database Active Concept Count | `6` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Device` | `Device.udi.entryType` | `http://hl7.org/fhir/ValueSet/udi-entry-type` | `Required` | barcode \| rfid \| manual + |

### Referenced Systems

* `http://hl7.org/fhir/udi-entry-type`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [UDIEntryType](/docs/R3/ValueSets/UDIEntryType.md)<br/> `http://hl7.org/fhir/ValueSet/udi-entry-type\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `391`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `614`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [UDIEntryType](/docs/R4/ValueSets/UDIEntryType.md)<br/> `http://hl7.org/fhir/ValueSet/udi-entry-type\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1777`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1778`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [UDIEntryType](/docs/R4B/ValueSets/UDIEntryType.md)<br/> `http://hl7.org/fhir/ValueSet/udi-entry-type\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `854`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1115`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [UDIEntryType](/docs/R5/ValueSets/UDIEntryType.md)<br/> `http://hl7.org/fhir/ValueSet/udi-entry-type\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set UDIEntryType from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | R3 UDIEntryType| Relationship | [R4 UDIEntryType](/docs/R4/ValueSets/UDIEntryType.md)| Relationship | [R4B UDIEntryType](/docs/R4B/ValueSets/UDIEntryType.md)| Relationship | [R5 UDIEntryType](/docs/R5/ValueSets/UDIEntryType.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/udi-entry-type`
| | | **`barcode`**| _Equivalent_ <br/>(3558/5844)| `barcode`| _Equivalent_ <br/>(18374/18375)| `barcode`| _Equivalent_ <br/>(7955/10258)| `barcode`
| | | **`rfid`**| _Equivalent_ <br/>(3556/5842)| `rfid`| _Equivalent_ <br/>(18376/18377)| `rfid`| _Equivalent_ <br/>(7953/10262)| `rfid`
| | | **`manual`**| _Equivalent_ <br/>(3557/5843)| `manual`| _Equivalent_ <br/>(18378/18379)| `manual`| _Equivalent_ <br/>(7954/10261)| `manual`
| | | **`card`**| _Equivalent_ <br/>(3559/5845)| `card`| _Equivalent_ <br/>(18380/18381)| `card`| _Equivalent_ <br/>(7956/10259)| `card`
| | | **`self-reported`**| _Equivalent_ <br/>(3555/5841)| `self-reported`| _Equivalent_ <br/>(18382/18383)| `self-reported`| _Equivalent_ <br/>(7952/10263)| `self-reported`
| | | **`unknown`**| _Equivalent_ <br/>(3560/5846)| `unknown`| _Equivalent_ <br/>(18384/18385)| `unknown`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7957)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10264) | `unknown`
| | | *6 of 6 codes used* | | *6 of 6 codes used* | | *6 of 6 codes used* | | *6 of 7 codes used* <br/>remaining codes:<br/>`electronic-transmission`

