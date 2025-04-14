Comparison of 
Generated at Monday, April 14, 2025 6:17:35 PM

### ClaimTypeCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | ClaimTypeCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/claim-type` |
| Version | 4.3.0 |
| Description | This value set includes Claim Type codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `3599` |
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
| | | | | | | [ClaimTypeCodes](/docs/R4B/ValueSets/ClaimTypeCodes.md)<br/> `http://hl7.org/fhir/ValueSet/claim-type\|4.3.0` | →→→→→→→<br/>``<br/>- DBKey: `793`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `1054`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ClaimTypeCodes](/docs/R5/ValueSets/ClaimTypeCodes.md)<br/> `http://hl7.org/fhir/ValueSet/claim-type\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set ClaimTypeCodes from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | R4B ClaimTypeCodes| Relationship | [R5 ClaimTypeCodes](/docs/R5/ValueSets/ClaimTypeCodes.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://terminology.hl7.org/CodeSystem/claim-type`
| | | | | | | **`institutional`**| _Equivalent_ <br/>(7529/9798)| `institutional`
| | | | | | | **`oral`**| _Equivalent_ <br/>(7530/9799)| `oral`
| | | | | | | **`pharmacy`**| _Equivalent_ <br/>(7531/9800)| `pharmacy`
| | | | | | | **`professional`**| _Equivalent_ <br/>(7532/9801)| `professional`
| | | | | | | **`vision`**| _Equivalent_ <br/>(7533/9802)| `vision`
| | | | | | | *5 of 5 codes used* | | *5 of 5 codes used* 

