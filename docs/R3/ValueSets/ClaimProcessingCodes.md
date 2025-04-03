Comparison of 
Generated at Thursday, April 3, 2025 8:18:10 AM

### Claim Processing Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Claim Processing Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/remittance-outcome` |
| Version | 3.0.2 |
| Description | This value set includes a Claim Processing Outcome codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1438` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.outcome` | `http://hl7.org/fhir/ValueSet/remittance-outcome` | `Example` | complete \| error \| partial |
| `http://hl7.org/fhir/StructureDefinition/EligibilityResponse` | `EligibilityResponse.outcome` | `http://hl7.org/fhir/ValueSet/remittance-outcome` | `Required` | complete \| error \| partial |
| `http://hl7.org/fhir/StructureDefinition/EnrollmentResponse` | `EnrollmentResponse.outcome` | `http://hl7.org/fhir/ValueSet/remittance-outcome` | `Required` | complete \| error \| partial |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.outcome` | `http://hl7.org/fhir/ValueSet/remittance-outcome` | `Example` | complete \| error \| partial |
| `http://hl7.org/fhir/StructureDefinition/PaymentReconciliation` | `PaymentReconciliation.outcome` | `http://hl7.org/fhir/ValueSet/remittance-outcome` | `Required` | complete \| error \| partial |

### Referenced Systems

* `http://hl7.org/fhir/remittance-outcome`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [RemittanceOutcome](/docs/R2/ValueSets/RemittanceOutcome.md)<br/> `http://hl7.org/fhir/ValueSet/remittance-outcome\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `73`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `229`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Claim Processing Codes](/docs/R3/ValueSets/ClaimProcessingCodes.md)<br/> `http://hl7.org/fhir/ValueSet/remittance-outcome\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `409`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `565`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ClaimProcessingCodes](/docs/R4/ValueSets/ClaimProcessingCodes.md)<br/> `http://hl7.org/fhir/ValueSet/remittance-outcome\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1685`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1686`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RemittanceOutcome](/docs/R4B/ValueSets/RemittanceOutcome.md)<br/> `http://hl7.org/fhir/ValueSet/remittance-outcome\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `960`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1221`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ClaimProcessingCodes](/docs/R5/ValueSets/ClaimProcessingCodes.md)<br/> `http://hl7.org/fhir/ValueSet/claim-outcome\|5.0.0` 
| [RemittanceOutcome](/docs/R2/ValueSets/RemittanceOutcome.md)<br/> `http://hl7.org/fhir/ValueSet/remittance-outcome\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `73`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `229`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Claim Processing Codes](/docs/R3/ValueSets/ClaimProcessingCodes.md)<br/> `http://hl7.org/fhir/ValueSet/remittance-outcome\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `409`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `565`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ClaimProcessingCodes](/docs/R4/ValueSets/ClaimProcessingCodes.md)<br/> `http://hl7.org/fhir/ValueSet/remittance-outcome\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1685`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1686`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RemittanceOutcome](/docs/R4B/ValueSets/RemittanceOutcome.md)<br/> `http://hl7.org/fhir/ValueSet/remittance-outcome\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `960`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1221`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EligibilityOutcome](/docs/R5/ValueSets/EligibilityOutcome.md)<br/> `http://hl7.org/fhir/ValueSet/eligibility-outcome\|5.0.0` 
| [RemittanceOutcome](/docs/R2/ValueSets/RemittanceOutcome.md)<br/> `http://hl7.org/fhir/ValueSet/remittance-outcome\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `73`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `229`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Claim Processing Codes](/docs/R3/ValueSets/ClaimProcessingCodes.md)<br/> `http://hl7.org/fhir/ValueSet/remittance-outcome\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `409`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `565`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ClaimProcessingCodes](/docs/R4/ValueSets/ClaimProcessingCodes.md)<br/> `http://hl7.org/fhir/ValueSet/remittance-outcome\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1685`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1686`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RemittanceOutcome](/docs/R4B/ValueSets/RemittanceOutcome.md)<br/> `http://hl7.org/fhir/ValueSet/remittance-outcome\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `960`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1221`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EnrollmentOutcome](/docs/R5/ValueSets/EnrollmentOutcome.md)<br/> `http://hl7.org/fhir/ValueSet/enrollment-outcome\|5.0.0` 
| [RemittanceOutcome](/docs/R2/ValueSets/RemittanceOutcome.md)<br/> `http://hl7.org/fhir/ValueSet/remittance-outcome\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `73`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `229`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Claim Processing Codes](/docs/R3/ValueSets/ClaimProcessingCodes.md)<br/> `http://hl7.org/fhir/ValueSet/remittance-outcome\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `409`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `565`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ClaimProcessingCodes](/docs/R4/ValueSets/ClaimProcessingCodes.md)<br/> `http://hl7.org/fhir/ValueSet/remittance-outcome\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1685`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1686`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RemittanceOutcome](/docs/R4B/ValueSets/RemittanceOutcome.md)<br/> `http://hl7.org/fhir/ValueSet/remittance-outcome\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `960`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1221`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [PaymentOutcome](/docs/R5/ValueSets/PaymentOutcome.md)<br/> `http://hl7.org/fhir/ValueSet/payment-outcome\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set Claim Processing Codes from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 RemittanceOutcome](/docs/R2/ValueSets/RemittanceOutcome.md)| Relationship | R3 Claim Processing Codes| Relationship | [R4 ClaimProcessingCodes](/docs/R4/ValueSets/ClaimProcessingCodes.md)| Relationship | [R4B RemittanceOutcome](/docs/R4B/ValueSets/RemittanceOutcome.md)| Relationship | [R5 ClaimProcessingCodes](/docs/R5/ValueSets/ClaimProcessingCodes.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/remittance-outcome`
| `complete`| _Equivalent_ <br/>(527/1877)| **`complete`**| _Equivalent_ <br/>(3645/5187)| `complete`| _Equivalent_ <br/>(16904/16905)| `complete`| _Equivalent_ <br/>(9214/11528)| `complete`
| `error`| _Equivalent_ <br/>(528/1878)| **`error`**| _Equivalent_ <br/>(3646/5188)| `error`| _Equivalent_ <br/>(16906/16907)| `error`| _Equivalent_ <br/>(9215/11529)| `error`
| | | **`partial`**| _Equivalent_ <br/>(3647/5189)| `partial`| _Equivalent_ <br/>(16908/16909)| `partial`| _Equivalent_ <br/>(9216/11530)| `partial`
| *2 of 2 codes used* | | *3 of 3 codes used* | | *3 of 4 codes used* <br/>remaining codes:<br/>`queued`| | *3 of 4 codes used* <br/>remaining codes:<br/>`queued`| | *3 of 4 codes used* <br/>remaining codes:<br/>`complete`, `error`, `partial`, `queued`


#### Map Group 1

This group is centered on the Value Set Claim Processing Codes from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 RemittanceOutcome](/docs/R2/ValueSets/RemittanceOutcome.md)| Relationship | R3 Claim Processing Codes| Relationship | [R4 ClaimProcessingCodes](/docs/R4/ValueSets/ClaimProcessingCodes.md)| Relationship | [R4B RemittanceOutcome](/docs/R4B/ValueSets/RemittanceOutcome.md)| Relationship | [R5 EligibilityOutcome](/docs/R5/ValueSets/EligibilityOutcome.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/remittance-outcome`
| `complete`| _Equivalent_ <br/>(527/1877)| **`complete`**| _Equivalent_ <br/>(3645/5187)| `complete`| _Equivalent_ <br/>(16904/16905)| `complete`| _Equivalent_ <br/>(9214/11528)| `complete`
| `error`| _Equivalent_ <br/>(528/1878)| **`error`**| _Equivalent_ <br/>(3646/5188)| `error`| _Equivalent_ <br/>(16906/16907)| `error`| _Equivalent_ <br/>(9215/11529)| `error`
| | | **`partial`**| _Equivalent_ <br/>(3647/5189)| `partial`| _Equivalent_ <br/>(16908/16909)| `partial`| _Equivalent_ <br/>(9216/11530)| `partial`
| *2 of 2 codes used* | | *3 of 3 codes used* | | *3 of 4 codes used* <br/>remaining codes:<br/>`queued`| | *3 of 4 codes used* <br/>remaining codes:<br/>`queued`| | *3 of 4 codes used* <br/>remaining codes:<br/>`complete`, `error`, `partial`, `queued`


#### Map Group 2

This group is centered on the Value Set Claim Processing Codes from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 RemittanceOutcome](/docs/R2/ValueSets/RemittanceOutcome.md)| Relationship | R3 Claim Processing Codes| Relationship | [R4 ClaimProcessingCodes](/docs/R4/ValueSets/ClaimProcessingCodes.md)| Relationship | [R4B RemittanceOutcome](/docs/R4B/ValueSets/RemittanceOutcome.md)| Relationship | [R5 EnrollmentOutcome](/docs/R5/ValueSets/EnrollmentOutcome.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/remittance-outcome`
| `complete`| _Equivalent_ <br/>(527/1877)| **`complete`**| _Equivalent_ <br/>(3645/5187)| `complete`| _Equivalent_ <br/>(16904/16905)| `complete`| _Equivalent_ <br/>(9214/11528)| `complete`
| `error`| _Equivalent_ <br/>(528/1878)| **`error`**| _Equivalent_ <br/>(3646/5188)| `error`| _Equivalent_ <br/>(16906/16907)| `error`| _Equivalent_ <br/>(9215/11529)| `error`
| | | **`partial`**| _Equivalent_ <br/>(3647/5189)| `partial`| _Equivalent_ <br/>(16908/16909)| `partial`| _Equivalent_ <br/>(9216/11530)| `partial`
| *2 of 2 codes used* | | *3 of 3 codes used* | | *3 of 4 codes used* <br/>remaining codes:<br/>`queued`| | *3 of 4 codes used* <br/>remaining codes:<br/>`queued`| | *3 of 4 codes used* <br/>remaining codes:<br/>`complete`, `error`, `partial`, `queued`


#### Map Group 3

This group is centered on the Value Set Claim Processing Codes from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 RemittanceOutcome](/docs/R2/ValueSets/RemittanceOutcome.md)| Relationship | R3 Claim Processing Codes| Relationship | [R4 ClaimProcessingCodes](/docs/R4/ValueSets/ClaimProcessingCodes.md)| Relationship | [R4B RemittanceOutcome](/docs/R4B/ValueSets/RemittanceOutcome.md)| Relationship | [R5 PaymentOutcome](/docs/R5/ValueSets/PaymentOutcome.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/remittance-outcome`
| `complete`| _Equivalent_ <br/>(527/1877)| **`complete`**| _Equivalent_ <br/>(3645/5187)| `complete`| _Equivalent_ <br/>(16904/16905)| `complete`| _Equivalent_ <br/>(9214/11528)| `complete`
| `error`| _Equivalent_ <br/>(528/1878)| **`error`**| _Equivalent_ <br/>(3646/5188)| `error`| _Equivalent_ <br/>(16906/16907)| `error`| _Equivalent_ <br/>(9215/11529)| `error`
| | | **`partial`**| _Equivalent_ <br/>(3647/5189)| `partial`| _Equivalent_ <br/>(16908/16909)| `partial`| _Equivalent_ <br/>(9216/11530)| `partial`
| *2 of 2 codes used* | | *3 of 3 codes used* | | *3 of 4 codes used* <br/>remaining codes:<br/>`queued`| | *3 of 4 codes used* <br/>remaining codes:<br/>`queued`| | *3 of 4 codes used* <br/>remaining codes:<br/>`queued`

