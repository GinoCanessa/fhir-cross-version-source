Comparison of 
Generated at Monday, April 14, 2025 6:17:14 PM

### Adjudication Error Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | Adjudication Error Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/adjudication-error` |
| Version | 1.0.2 |
| Description | This value set includes a smattering of adjudication codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `8` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.error.code` | `http://hl7.org/fhir/ValueSet/adjudication-error` | `Required` | Error code detailing processing issues |
| `http://hl7.org/fhir/StructureDefinition/ProcessResponse` | `ProcessResponse.error` | `http://hl7.org/fhir/ValueSet/adjudication-error` | `Required` | Error code |

### Referenced Systems

* `http://hl7.org/fhir/adjudication-error`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Adjudication Error Codes](/docs/R2/ValueSets/AdjudicationErrorCodes.md)<br/> `http://hl7.org/fhir/ValueSet/adjudication-error\|1.0.2` | →→→→→→→<br/>``<br/>- DBKey: `1286`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `1287`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Adjudication Error Codes](/docs/R3/ValueSets/AdjudicationErrorCodes.md)<br/> `http://hl7.org/fhir/ValueSet/adjudication-error\|3.0.2` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set Adjudication Error Codes from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 Adjudication Error Codes| Relationship | [R3 Adjudication Error Codes](/docs/R3/ValueSets/AdjudicationErrorCodes.md)| Relationship | *No Map* | Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/adjudication-error`
| **`A001`**| | | | | | | | | 
| **`A002`**| | | | | | | | | 
| *2 of 2 codes used* | | *0 of 2 codes used* <br/>remaining codes:<br/>`a001`, `a002`| | | | | | 

