Comparison of 
Generated at Thursday, April 3, 2025 8:18:16 AM

### ClaimTypeCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | ClaimTypeCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/claim-type` |
| Version | 4.0.1 |
| Description | This value set includes Claim Type codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2267` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.type` | `http://hl7.org/fhir/ValueSet/claim-type` | `Extensible` | Category or discipline |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.type` | `http://hl7.org/fhir/ValueSet/claim-type` | `Extensible` | More granular claim type |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.type` | `http://hl7.org/fhir/ValueSet/claim-type` | `Extensible` | Category or discipline |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/claim-type`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ClaimType](/docs/R2/ValueSets/ClaimType.md)<br/> `http://hl7.org/fhir/ValueSet/claim-type-link\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `20`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `179`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Example Claim Type Codes](/docs/R3/ValueSets/ExampleClaimTypeCodes.md)<br/> `http://hl7.org/fhir/ValueSet/claim-type\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `346`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `569`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ClaimTypeCodes](/docs/R4/ValueSets/ClaimTypeCodes.md)<br/> `http://hl7.org/fhir/ValueSet/claim-type\|4.0.1` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set ClaimTypeCodes from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 ClaimType](/docs/R2/ValueSets/ClaimType.md)| Relationship | [R3 Example Claim Type Codes](/docs/R3/ValueSets/ExampleClaimTypeCodes.md)| Relationship | R4 ClaimTypeCodes| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://terminology.hl7.org/CodeSystem/claim-type`
| `institutional`| _Equivalent_ <br/>(93/1463)| `institutional`| _Equivalent_ <br/>(2997/5206)| **`institutional`**| | | | | 
| `oral`| _Equivalent_ <br/>(95/1465)| `oral`| _Equivalent_ <br/>(2999/5208)| **`oral`**| | | | | 
| `pharmacy`| _Equivalent_ <br/>(94/1464)| `pharmacy`| _Equivalent_ <br/>(2998/5207)| **`pharmacy`**| | | | | 
| `professional`| _Equivalent_ <br/>(96/1466)| `professional`| _Equivalent_ <br/>(3000/5209)| **`professional`**| | | | | 
| `vision`| _Equivalent_ <br/>(92/1462)| `vision`| _Equivalent_ <br/>(2996/5205)| **`vision`**| | | | | 
| *5 of 5 codes used* | | *5 of 5 codes used* | | *5 of 5 codes used* | | | | 

