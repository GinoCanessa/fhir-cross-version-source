Comparison of 
Generated at Friday, April 4, 2025 2:58:58 PM

### ClaimProcessingCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | ClaimProcessingCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/claim-outcome` |
| Version | 5.0.0 |
| Description | This value set includes Claim Processing Outcome codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4364` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.outcome` | `http://hl7.org/fhir/ValueSet/claim-outcome\|5.0.0` | `Required` | queued \| complete \| error \| partial |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.outcome` | `http://hl7.org/fhir/ValueSet/claim-outcome\|5.0.0` | `Required` | queued \| complete \| error \| partial |

### Referenced Systems

* `http://hl7.org/fhir/claim-outcome`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [RemittanceOutcome](/docs/R2/ValueSets/RemittanceOutcome.md)<br/> `http://hl7.org/fhir/ValueSet/remittance-outcome\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `73`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `229`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Claim Processing Codes](/docs/R3/ValueSets/ClaimProcessingCodes.md)<br/> `http://hl7.org/fhir/ValueSet/remittance-outcome\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `409`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `565`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ClaimProcessingCodes](/docs/R4/ValueSets/ClaimProcessingCodes.md)<br/> `http://hl7.org/fhir/ValueSet/remittance-outcome\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1685`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1686`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RemittanceOutcome](/docs/R4B/ValueSets/RemittanceOutcome.md)<br/> `http://hl7.org/fhir/ValueSet/remittance-outcome\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `795`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1056`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ClaimProcessingCodes](/docs/R5/ValueSets/ClaimProcessingCodes.md)<br/> `http://hl7.org/fhir/ValueSet/claim-outcome\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set ClaimProcessingCodes from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 RemittanceOutcome](/docs/R2/ValueSets/RemittanceOutcome.md)| Relationship | [R3 Claim Processing Codes](/docs/R3/ValueSets/ClaimProcessingCodes.md)| Relationship | [R4 ClaimProcessingCodes](/docs/R4/ValueSets/ClaimProcessingCodes.md)| Relationship | [R4B RemittanceOutcome](/docs/R4B/ValueSets/RemittanceOutcome.md)| Relationship | R5 ClaimProcessingCodes
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/claim-outcome`
| | | | | `queued`| _Equivalent_ <br/>(16902/16903)| `queued`| _Equivalent_ <br/>(7537/9806)| **`queued`**
| `complete`| _Equivalent_ <br/>(527/1877)| `complete`| _Equivalent_ <br/>(3645/5187)| `complete`| _Equivalent_ <br/>(16904/16905)| `complete`| _Equivalent_ <br/>(7538/9807)| **`complete`**
| `error`| _Equivalent_ <br/>(528/1878)| `error`| _Equivalent_ <br/>(3646/5188)| `error`| _Equivalent_ <br/>(16906/16907)| `error`| _Equivalent_ <br/>(7539/9808)| **`error`**
| | | `partial`| _Equivalent_ <br/>(3647/5189)| `partial`| _Equivalent_ <br/>(16908/16909)| `partial`| _Equivalent_ <br/>(7540/9809)| **`partial`**
| *2 of 2 codes used* | | *3 of 3 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* 

