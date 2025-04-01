Comparison of 
Generated at Tuesday, April 1, 2025 1:39:06 PM

### ContentType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | ContentType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/content-type` |
| Version | 1.0.2 |
| Description | The content or mime type.  The content type or mime type to be specified in Accept or Content-Type header. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `80` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/TestScript` | `TestScript.setup.action.operation.accept` | `http://hl7.org/fhir/ValueSet/content-type` | `Required` | xml \| json |
| `http://hl7.org/fhir/StructureDefinition/TestScript` | `TestScript.setup.action.operation.contentType` | `http://hl7.org/fhir/ValueSet/content-type` | `Required` | xml \| json |
| `http://hl7.org/fhir/StructureDefinition/TestScript` | `TestScript.setup.action.assert.contentType` | `http://hl7.org/fhir/ValueSet/content-type` | `Required` | xml \| json |

### Referenced Systems

* `http://hl7.org/fhir/content-type`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ContentType](/docs/R2/ValueSets/ContentType.md)<br/> `http://hl7.org/fhir/ValueSet/content-type\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `153`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `311`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ContentType](/docs/R3/ValueSets/ContentType.md)<br/> `http://hl7.org/fhir/ValueSet/content-type\|3.0.2` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set ContentType from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 ContentType| Relationship | [R3 ContentType](/docs/R3/ValueSets/ContentType.md)| Relationship | *No Map* | Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/content-type`
| **`xml`**| _Equivalent_ <br/>(1319/2778)| `xml`| | | | | | | 
| **`json`**| _Equivalent_ <br/>(1320/2775)| `json`| | | | | | | 
| *2 of 2 codes used* | | *2 of 4 codes used* | | | | | | 

