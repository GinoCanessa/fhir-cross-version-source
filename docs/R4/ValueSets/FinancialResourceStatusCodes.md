Comparison of 
Generated at Monday, April 14, 2025 6:17:26 PM

### FinancialResourceStatusCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | FinancialResourceStatusCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/fm-status` |
| Version | 4.0.1 |
| Description | This value set includes Status codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2462` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.status` | `http://hl7.org/fhir/ValueSet/fm-status\|4.0.1` | `Required` | active \| cancelled \| draft \| entered-in-error |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.status` | `http://hl7.org/fhir/ValueSet/fm-status\|4.0.1` | `Required` | active \| cancelled \| draft \| entered-in-error |
| `http://hl7.org/fhir/StructureDefinition/Coverage` | `Coverage.status` | `http://hl7.org/fhir/ValueSet/fm-status\|4.0.1` | `Required` | active \| cancelled \| draft \| entered-in-error |
| `http://hl7.org/fhir/StructureDefinition/CoverageEligibilityRequest` | `CoverageEligibilityRequest.status` | `http://hl7.org/fhir/ValueSet/fm-status\|4.0.1` | `Required` | active \| cancelled \| draft \| entered-in-error |
| `http://hl7.org/fhir/StructureDefinition/CoverageEligibilityResponse` | `CoverageEligibilityResponse.status` | `http://hl7.org/fhir/ValueSet/fm-status\|4.0.1` | `Required` | active \| cancelled \| draft \| entered-in-error |
| `http://hl7.org/fhir/StructureDefinition/EnrollmentRequest` | `EnrollmentRequest.status` | `http://hl7.org/fhir/ValueSet/fm-status\|4.0.1` | `Required` | active \| cancelled \| draft \| entered-in-error |
| `http://hl7.org/fhir/StructureDefinition/EnrollmentResponse` | `EnrollmentResponse.status` | `http://hl7.org/fhir/ValueSet/fm-status\|4.0.1` | `Required` | active \| cancelled \| draft \| entered-in-error |
| `http://hl7.org/fhir/StructureDefinition/PaymentNotice` | `PaymentNotice.status` | `http://hl7.org/fhir/ValueSet/fm-status\|4.0.1` | `Required` | active \| cancelled \| draft \| entered-in-error |
| `http://hl7.org/fhir/StructureDefinition/PaymentReconciliation` | `PaymentReconciliation.status` | `http://hl7.org/fhir/ValueSet/fm-status\|4.0.1` | `Required` | active \| cancelled \| draft \| entered-in-error |
| `http://hl7.org/fhir/StructureDefinition/VisionPrescription` | `VisionPrescription.status` | `http://hl7.org/fhir/ValueSet/fm-status\|4.0.1` | `Required` | active \| cancelled \| draft \| entered-in-error |

### Referenced Systems

* `http://hl7.org/fhir/fm-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [Financial Resource Status Codes](/docs/R3/ValueSets/FinancialResourceStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/fm-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `345`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `564`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [FinancialResourceStatusCodes](/docs/R4/ValueSets/FinancialResourceStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/fm-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1515`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1516`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [FinancialResourceStatusCodes](/docs/R4B/ValueSets/FinancialResourceStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/fm-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `788`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1049`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [FinancialResourceStatusCodes](/docs/R5/ValueSets/FinancialResourceStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/fm-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set FinancialResourceStatusCodes from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | [R3 Financial Resource Status Codes](/docs/R3/ValueSets/FinancialResourceStatusCodes.md)| Relationship | R4 FinancialResourceStatusCodes| Relationship | [R4B FinancialResourceStatusCodes](/docs/R4B/ValueSets/FinancialResourceStatusCodes.md)| Relationship | [R5 FinancialResourceStatusCodes](/docs/R5/ValueSets/FinancialResourceStatusCodes.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://hl7.org/fhir/fm-status`
| | | `active`| _Equivalent_ <br/>(2993/5184)| **`active`**| _Equivalent_ <br/>(16054/16055)| `active`| _Equivalent_ <br/>(7508/9772)| `active`
| | | `cancelled`| _Equivalent_ <br/>(2994/5185)| **`cancelled`**| _Equivalent_ <br/>(16056/16057)| `cancelled`| _Equivalent_ <br/>(7509/9773)| `cancelled`
| | | `draft`| _Equivalent_ <br/>(2992/5183)| **`draft`**| _Equivalent_ <br/>(16058/16059)| `draft`| _Equivalent_ <br/>(7507/9771)| `draft`
| | | `entered-in-error`| _Equivalent_ <br/>(2995/5186)| **`entered-in-error`**| _Equivalent_ <br/>(16060/16061)| `entered-in-error`| _Equivalent_ <br/>(7510/9774)| `entered-in-error`
| | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* 

