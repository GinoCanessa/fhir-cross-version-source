Comparison of 
Generated at Friday, April 4, 2025 2:58:32 PM

### RemittanceOutcome

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | RemittanceOutcome |
| Canonical URL | `http://hl7.org/fhir/ValueSet/remittance-outcome` |
| Version | 1.0.2 |
| Description | The outcome of the processing. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `339` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.outcome` | `http://hl7.org/fhir/ValueSet/remittance-outcome` | `Required` | complete \| error |
| `http://hl7.org/fhir/StructureDefinition/EligibilityResponse` | `EligibilityResponse.outcome` | `http://hl7.org/fhir/ValueSet/remittance-outcome` | `Required` | complete \| error |
| `http://hl7.org/fhir/StructureDefinition/EnrollmentResponse` | `EnrollmentResponse.outcome` | `http://hl7.org/fhir/ValueSet/remittance-outcome` | `Required` | complete \| error |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.outcome` | `http://hl7.org/fhir/ValueSet/remittance-outcome` | `Required` | complete \| error |
| `http://hl7.org/fhir/StructureDefinition/PaymentReconciliation` | `PaymentReconciliation.outcome` | `http://hl7.org/fhir/ValueSet/remittance-outcome` | `Required` | complete \| error |

### Referenced Systems

* `http://hl7.org/fhir/remittance-outcome`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [RemittanceOutcome](/docs/R2/ValueSets/RemittanceOutcome.md)<br/> `http://hl7.org/fhir/ValueSet/remittance-outcome\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `73`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `229`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Claim Processing Codes](/docs/R3/ValueSets/ClaimProcessingCodes.md)<br/> `http://hl7.org/fhir/ValueSet/remittance-outcome\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `409`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `565`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ClaimProcessingCodes](/docs/R4/ValueSets/ClaimProcessingCodes.md)<br/> `http://hl7.org/fhir/ValueSet/remittance-outcome\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1685`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1686`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RemittanceOutcome](/docs/R4B/ValueSets/RemittanceOutcome.md)<br/> `http://hl7.org/fhir/ValueSet/remittance-outcome\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `795`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1056`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ClaimProcessingCodes](/docs/R5/ValueSets/ClaimProcessingCodes.md)<br/> `http://hl7.org/fhir/ValueSet/claim-outcome\|5.0.0` 
| [RemittanceOutcome](/docs/R2/ValueSets/RemittanceOutcome.md)<br/> `http://hl7.org/fhir/ValueSet/remittance-outcome\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `73`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `229`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Claim Processing Codes](/docs/R3/ValueSets/ClaimProcessingCodes.md)<br/> `http://hl7.org/fhir/ValueSet/remittance-outcome\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `409`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `565`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ClaimProcessingCodes](/docs/R4/ValueSets/ClaimProcessingCodes.md)<br/> `http://hl7.org/fhir/ValueSet/remittance-outcome\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1685`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1686`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RemittanceOutcome](/docs/R4B/ValueSets/RemittanceOutcome.md)<br/> `http://hl7.org/fhir/ValueSet/remittance-outcome\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `789`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1050`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EligibilityOutcome](/docs/R5/ValueSets/EligibilityOutcome.md)<br/> `http://hl7.org/fhir/ValueSet/eligibility-outcome\|5.0.0` 
| [RemittanceOutcome](/docs/R2/ValueSets/RemittanceOutcome.md)<br/> `http://hl7.org/fhir/ValueSet/remittance-outcome\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `73`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `229`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Claim Processing Codes](/docs/R3/ValueSets/ClaimProcessingCodes.md)<br/> `http://hl7.org/fhir/ValueSet/remittance-outcome\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `409`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `565`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ClaimProcessingCodes](/docs/R4/ValueSets/ClaimProcessingCodes.md)<br/> `http://hl7.org/fhir/ValueSet/remittance-outcome\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1685`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1686`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RemittanceOutcome](/docs/R4B/ValueSets/RemittanceOutcome.md)<br/> `http://hl7.org/fhir/ValueSet/remittance-outcome\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `875`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1136`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EnrollmentOutcome](/docs/R5/ValueSets/EnrollmentOutcome.md)<br/> `http://hl7.org/fhir/ValueSet/enrollment-outcome\|5.0.0` 
| [RemittanceOutcome](/docs/R2/ValueSets/RemittanceOutcome.md)<br/> `http://hl7.org/fhir/ValueSet/remittance-outcome\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `73`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `229`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Claim Processing Codes](/docs/R3/ValueSets/ClaimProcessingCodes.md)<br/> `http://hl7.org/fhir/ValueSet/remittance-outcome\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `409`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `565`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ClaimProcessingCodes](/docs/R4/ValueSets/ClaimProcessingCodes.md)<br/> `http://hl7.org/fhir/ValueSet/remittance-outcome\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1685`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1686`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RemittanceOutcome](/docs/R4B/ValueSets/RemittanceOutcome.md)<br/> `http://hl7.org/fhir/ValueSet/remittance-outcome\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `960`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1221`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [PaymentOutcome](/docs/R5/ValueSets/PaymentOutcome.md)<br/> `http://hl7.org/fhir/ValueSet/payment-outcome\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set RemittanceOutcome from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 RemittanceOutcome| Relationship | [R3 Claim Processing Codes](/docs/R3/ValueSets/ClaimProcessingCodes.md)| Relationship | [R4 ClaimProcessingCodes](/docs/R4/ValueSets/ClaimProcessingCodes.md)| Relationship | [R4B RemittanceOutcome](/docs/R4B/ValueSets/RemittanceOutcome.md)| Relationship | [R5 ClaimProcessingCodes](/docs/R5/ValueSets/ClaimProcessingCodes.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/remittance-outcome`
| **`complete`**| _Equivalent_ <br/>(527/1877)| `complete`| _Equivalent_ <br/>(3645/5187)| `complete`| _Equivalent_ <br/>(16904/16905)| `complete`| _Equivalent_ <br/>(7538/9807)| `complete`
| **`error`**| _Equivalent_ <br/>(528/1878)| `error`| _Equivalent_ <br/>(3646/5188)| `error`| _Equivalent_ <br/>(16906/16907)| `error`| _Equivalent_ <br/>(7539/9808)| `error`
| *2 of 2 codes used* | | *2 of 3 codes used* <br/>remaining codes:<br/>`partial`| | *2 of 4 codes used* <br/>remaining codes:<br/>`partial`, `queued`| | *2 of 4 codes used* <br/>remaining codes:<br/>`partial`, `queued`| | *2 of 4 codes used* <br/>remaining codes:<br/>`partial`, `queued`


#### Map Group 1

This group is centered on the Value Set RemittanceOutcome from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 RemittanceOutcome| Relationship | [R3 Claim Processing Codes](/docs/R3/ValueSets/ClaimProcessingCodes.md)| Relationship | [R4 ClaimProcessingCodes](/docs/R4/ValueSets/ClaimProcessingCodes.md)| Relationship | [R4B RemittanceOutcome](/docs/R4B/ValueSets/RemittanceOutcome.md)| Relationship | [R5 EligibilityOutcome](/docs/R5/ValueSets/EligibilityOutcome.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/remittance-outcome`
| **`complete`**| _Equivalent_ <br/>(527/1877)| `complete`| _Equivalent_ <br/>(3645/5187)| `complete`| _Equivalent_ <br/>(16904/16905)| `complete`| _Equivalent_ <br/>(7512/9776)| `complete`
| **`error`**| _Equivalent_ <br/>(528/1878)| `error`| _Equivalent_ <br/>(3646/5188)| `error`| _Equivalent_ <br/>(16906/16907)| `error`| _Equivalent_ <br/>(7513/9777)| `error`
| *2 of 2 codes used* | | *2 of 3 codes used* <br/>remaining codes:<br/>`partial`| | *2 of 4 codes used* <br/>remaining codes:<br/>`partial`, `queued`| | *2 of 4 codes used* <br/>remaining codes:<br/>`partial`, `queued`| | *2 of 4 codes used* <br/>remaining codes:<br/>`partial`, `queued`


#### Map Group 2

This group is centered on the Value Set RemittanceOutcome from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 RemittanceOutcome| Relationship | [R3 Claim Processing Codes](/docs/R3/ValueSets/ClaimProcessingCodes.md)| Relationship | [R4 ClaimProcessingCodes](/docs/R4/ValueSets/ClaimProcessingCodes.md)| Relationship | [R4B RemittanceOutcome](/docs/R4B/ValueSets/RemittanceOutcome.md)| Relationship | [R5 EnrollmentOutcome](/docs/R5/ValueSets/EnrollmentOutcome.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/remittance-outcome`
| **`complete`**| _Equivalent_ <br/>(527/1877)| `complete`| _Equivalent_ <br/>(3645/5187)| `complete`| _Equivalent_ <br/>(16904/16905)| `complete`| _Equivalent_ <br/>(8050/10355)| `complete`
| **`error`**| _Equivalent_ <br/>(528/1878)| `error`| _Equivalent_ <br/>(3646/5188)| `error`| _Equivalent_ <br/>(16906/16907)| `error`| _Equivalent_ <br/>(8051/10356)| `error`
| *2 of 2 codes used* | | *2 of 3 codes used* <br/>remaining codes:<br/>`partial`| | *2 of 4 codes used* <br/>remaining codes:<br/>`partial`, `queued`| | *2 of 4 codes used* <br/>remaining codes:<br/>`partial`, `queued`| | *2 of 4 codes used* <br/>remaining codes:<br/>`partial`, `queued`


#### Map Group 3

This group is centered on the Value Set RemittanceOutcome from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 RemittanceOutcome| Relationship | [R3 Claim Processing Codes](/docs/R3/ValueSets/ClaimProcessingCodes.md)| Relationship | [R4 ClaimProcessingCodes](/docs/R4/ValueSets/ClaimProcessingCodes.md)| Relationship | [R4B RemittanceOutcome](/docs/R4B/ValueSets/RemittanceOutcome.md)| Relationship | [R5 PaymentOutcome](/docs/R5/ValueSets/PaymentOutcome.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/remittance-outcome`
| **`complete`**| _Equivalent_ <br/>(527/1877)| `complete`| _Equivalent_ <br/>(3645/5187)| `complete`| _Equivalent_ <br/>(16904/16905)| `complete`| _Equivalent_ <br/>(9214/11528)| `complete`
| **`error`**| _Equivalent_ <br/>(528/1878)| `error`| _Equivalent_ <br/>(3646/5188)| `error`| _Equivalent_ <br/>(16906/16907)| `error`| _Equivalent_ <br/>(9215/11529)| `error`
| *2 of 2 codes used* | | *2 of 3 codes used* <br/>remaining codes:<br/>`partial`| | *2 of 4 codes used* <br/>remaining codes:<br/>`partial`, `queued`| | *2 of 4 codes used* <br/>remaining codes:<br/>`partial`, `queued`| | *2 of 4 codes used* <br/>remaining codes:<br/>`partial`, `queued`

