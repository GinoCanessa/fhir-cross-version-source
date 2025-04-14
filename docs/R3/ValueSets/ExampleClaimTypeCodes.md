Comparison of 
Generated at Monday, April 14, 2025 6:17:20 PM

### Example Claim Type Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Example Claim Type Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/claim-type` |
| Version | 3.0.2 |
| Description | This value set includes sample Claim Type codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1109` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.type` | `http://hl7.org/fhir/ValueSet/claim-type` | `Required` | Type or discipline |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.type` | `http://hl7.org/fhir/ValueSet/claim-type` | `Required` | Type or discipline |

### Referenced Systems

* `http://hl7.org/fhir/ex-claimtype`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ClaimType](/docs/R2/ValueSets/ClaimType.md)<br/> `http://hl7.org/fhir/ValueSet/claim-type-link\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `20`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `179`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Example Claim Type Codes](/docs/R3/ValueSets/ExampleClaimTypeCodes.md)<br/> `http://hl7.org/fhir/ValueSet/claim-type\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `346`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `569`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ClaimTypeCodes](/docs/R4/ValueSets/ClaimTypeCodes.md)<br/> `http://hl7.org/fhir/ValueSet/claim-type\|4.0.1` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set Example Claim Type Codes from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 ClaimType](/docs/R2/ValueSets/ClaimType.md)| Relationship | R3 Example Claim Type Codes| Relationship | [R4 ClaimTypeCodes](/docs/R4/ValueSets/ClaimTypeCodes.md)| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/ex-claimtype`
| `institutional`| _Equivalent_ <br/>(93/1463)| **`institutional`**| _Equivalent_ <br/>(2997/5206)| `institutional`| | | | | 
| `oral`| _Equivalent_ <br/>(95/1465)| **`oral`**| _Equivalent_ <br/>(2999/5208)| `oral`| | | | | 
| `pharmacy`| _Equivalent_ <br/>(94/1464)| **`pharmacy`**| _Equivalent_ <br/>(2998/5207)| `pharmacy`| | | | | 
| `professional`| _Equivalent_ <br/>(96/1466)| **`professional`**| _Equivalent_ <br/>(3000/5209)| `professional`| | | | | 
| `vision`| _Equivalent_ <br/>(92/1462)| **`vision`**| _Equivalent_ <br/>(2996/5205)| `vision`| | | | | 
| *5 of 5 codes used* | | *5 of 5 codes used* | | *5 of 5 codes used* | | | | 

