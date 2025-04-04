Comparison of 
Generated at Friday, April 4, 2025 2:58:36 PM

### Adjudication Error Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Adjudication Error Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/adjudication-error` |
| Version | 3.0.2 |
| Description | This value set includes a smattering of adjudication codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1038` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.error.code` | `http://hl7.org/fhir/ValueSet/adjudication-error` | `Example` | Error code detailing processing issues |
| `http://hl7.org/fhir/StructureDefinition/EligibilityResponse` | `EligibilityResponse.error.code` | `http://hl7.org/fhir/ValueSet/adjudication-error` | `Example` | Error code detailing processing issues |
| `http://hl7.org/fhir/StructureDefinition/ProcessResponse` | `ProcessResponse.error` | `http://hl7.org/fhir/ValueSet/adjudication-error` | `Example` | Error code |

### Referenced Systems

* `http://hl7.org/fhir/adjudication-error`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Adjudication Error Codes](/docs/R2/ValueSets/AdjudicationErrorCodes.md)<br/> `http://hl7.org/fhir/ValueSet/adjudication-error\|1.0.2` | →→→→→→→<br/>``<br/>- DBKey: `1286`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `1287`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Adjudication Error Codes](/docs/R3/ValueSets/AdjudicationErrorCodes.md)<br/> `http://hl7.org/fhir/ValueSet/adjudication-error\|3.0.2` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set Adjudication Error Codes from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 Adjudication Error Codes](/docs/R2/ValueSets/AdjudicationErrorCodes.md)| Relationship | R3 Adjudication Error Codes| Relationship | *No Map* | Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/adjudication-error`
| | | **`a001`**| | | | | | | 
| | | **`a002`**| | | | | | | 
| *0 of 2 codes used* <br/>remaining codes:<br/>`A001`, `A002`| | *2 of 2 codes used* | | | | | | 

