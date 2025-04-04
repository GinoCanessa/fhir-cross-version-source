Comparison of 
Generated at Friday, April 4, 2025 2:58:37 PM

### Financial Resource Status Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Financial Resource Status Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/fm-status` |
| Version | 3.0.2 |
| Description | This value set includes Status codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1245` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.status` | `http://hl7.org/fhir/ValueSet/fm-status` | `Required` | active \| cancelled \| draft \| entered-in-error |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.status` | `http://hl7.org/fhir/ValueSet/fm-status` | `Required` | active \| cancelled \| draft \| entered-in-error |
| `http://hl7.org/fhir/StructureDefinition/Coverage` | `Coverage.status` | `http://hl7.org/fhir/ValueSet/fm-status` | `Required` | active \| cancelled \| draft \| entered-in-error |
| `http://hl7.org/fhir/StructureDefinition/EligibilityRequest` | `EligibilityRequest.status` | `http://hl7.org/fhir/ValueSet/fm-status` | `Required` | active \| cancelled \| draft \| entered-in-error |
| `http://hl7.org/fhir/StructureDefinition/EligibilityResponse` | `EligibilityResponse.status` | `http://hl7.org/fhir/ValueSet/fm-status` | `Required` | active \| cancelled \| draft \| entered-in-error |
| `http://hl7.org/fhir/StructureDefinition/EnrollmentRequest` | `EnrollmentRequest.status` | `http://hl7.org/fhir/ValueSet/fm-status` | `Required` | active \| cancelled \| draft \| entered-in-error |
| `http://hl7.org/fhir/StructureDefinition/EnrollmentResponse` | `EnrollmentResponse.status` | `http://hl7.org/fhir/ValueSet/fm-status` | `Required` | active \| cancelled \| draft \| entered-in-error |
| `http://hl7.org/fhir/StructureDefinition/PaymentNotice` | `PaymentNotice.status` | `http://hl7.org/fhir/ValueSet/fm-status` | `Required` | active \| cancelled \| draft \| entered-in-error |
| `http://hl7.org/fhir/StructureDefinition/PaymentReconciliation` | `PaymentReconciliation.status` | `http://hl7.org/fhir/ValueSet/fm-status` | `Required` | active \| cancelled \| draft \| entered-in-error |
| `http://hl7.org/fhir/StructureDefinition/ProcessRequest` | `ProcessRequest.status` | `http://hl7.org/fhir/ValueSet/fm-status` | `Required` | active \| cancelled \| draft \| entered-in-error |
| `http://hl7.org/fhir/StructureDefinition/ProcessResponse` | `ProcessResponse.status` | `http://hl7.org/fhir/ValueSet/fm-status` | `Required` | active \| cancelled \| draft \| entered-in-error |
| `http://hl7.org/fhir/StructureDefinition/VisionPrescription` | `VisionPrescription.status` | `http://hl7.org/fhir/ValueSet/fm-status` | `Required` | active \| cancelled \| draft \| entered-in-error |

### Referenced Systems

* `http://hl7.org/fhir/fm-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [Financial Resource Status Codes](/docs/R3/ValueSets/FinancialResourceStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/fm-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `345`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `564`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [FinancialResourceStatusCodes](/docs/R4/ValueSets/FinancialResourceStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/fm-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1515`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1516`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [FinancialResourceStatusCodes](/docs/R4B/ValueSets/FinancialResourceStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/fm-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `788`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1049`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [FinancialResourceStatusCodes](/docs/R5/ValueSets/FinancialResourceStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/fm-status\|5.0.0` 
| | | [Financial Resource Status Codes](/docs/R3/ValueSets/FinancialResourceStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/fm-status\|3.0.2` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `480`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`RelatedTo`<br/>- DBKey: `748`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TaskStatus](/docs/R4/ValueSets/TaskStatus.md)<br/> `http://hl7.org/fhir/ValueSet/task-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1765`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1766`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TaskStatus](/docs/R4B/ValueSets/TaskStatus.md)<br/> `http://hl7.org/fhir/ValueSet/task-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1009`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1270`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TaskStatus](/docs/R5/ValueSets/TaskStatus.md)<br/> `http://hl7.org/fhir/ValueSet/task-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set Financial Resource Status Codes from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | R3 Financial Resource Status Codes| Relationship | [R4 FinancialResourceStatusCodes](/docs/R4/ValueSets/FinancialResourceStatusCodes.md)| Relationship | [R4B FinancialResourceStatusCodes](/docs/R4B/ValueSets/FinancialResourceStatusCodes.md)| Relationship | [R5 FinancialResourceStatusCodes](/docs/R5/ValueSets/FinancialResourceStatusCodes.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/fm-status`
| | | **`active`**| _Equivalent_ <br/>(2993/5184)| `active`| _Equivalent_ <br/>(16054/16055)| `active`| _Equivalent_ <br/>(7508/9772)| `active`
| | | **`cancelled`**| _Equivalent_ <br/>(2994/5185)| `cancelled`| _Equivalent_ <br/>(16056/16057)| `cancelled`| _Equivalent_ <br/>(7509/9773)| `cancelled`
| | | **`draft`**| _Equivalent_ <br/>(2992/5183)| `draft`| _Equivalent_ <br/>(16058/16059)| `draft`| _Equivalent_ <br/>(7507/9771)| `draft`
| | | **`entered-in-error`**| _Equivalent_ <br/>(2995/5186)| `entered-in-error`| _Equivalent_ <br/>(16060/16061)| `entered-in-error`| _Equivalent_ <br/>(7510/9774)| `entered-in-error`
| | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* 


#### Map Group 1

This group is centered on the Value Set Financial Resource Status Codes from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | R3 Financial Resource Status Codes| Relationship | [R4 TaskStatus](/docs/R4/ValueSets/TaskStatus.md)| Relationship | [R4B TaskStatus](/docs/R4B/ValueSets/TaskStatus.md)| Relationship | [R5 TaskStatus](/docs/R5/ValueSets/TaskStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/fm-status`
| | | **`active`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4385)<hr/>←←←← _Equivalent_ ←←←← <br/>(7278) | `received`| _Equivalent_ <br/>(18316/18317)| `received`| _Equivalent_ <br/>(9515/11854)| `received`
| | | **`active`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4382)<hr/>←←←← _Equivalent_ ←←←← <br/>(7269) | `accepted`| _Equivalent_ <br/>(18318/18319)| `accepted`| _Equivalent_ <br/>(9513/11852)| `accepted`
| | | **`active`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4384)<hr/>←←←← _Equivalent_ ←←←← <br/>(7277) | `ready`| _Equivalent_ <br/>(18322/18323)| `ready`| _Equivalent_ <br/>(9511/11850)| `ready`
| | | **`active`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4383)<hr/>←←←← _Equivalent_ ←←←← <br/>(7275) | `in-progress`| _Equivalent_ <br/>(18326/18327)| `in-progress`| _Equivalent_ <br/>(9519/11858)| `in-progress`
| | | **`cancelled`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4389)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7279) | `rejected`| _Equivalent_ <br/>(18320/18321)| `rejected`| _Equivalent_ <br/>(9510/11849)| `rejected`
| | | **`cancelled`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4386)<hr/>←←←← _Equivalent_ ←←←← <br/>(7270) | `cancelled`| _Equivalent_ <br/>(18324/18325)| `cancelled`| _Equivalent_ <br/>(9514/11853)| `cancelled`
| | | **`cancelled`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4388)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7274) | `failed`| _Equivalent_ <br/>(18330/18331)| `failed`| _Equivalent_ <br/>(9516/11855)| `failed`
| | | **`cancelled`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4387)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7271) | `completed`| _Equivalent_ <br/>(18332/18333)| `completed`| _Equivalent_ <br/>(9517/11856)| `completed`
| | | **`draft`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4380)<hr/>←←←← _Equivalent_ ←←←← <br/>(7272) | `draft`| _Equivalent_ <br/>(18312/18313)| `draft`| _Equivalent_ <br/>(9512/11851)| `draft`
| | | **`draft`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4381)<hr/>←←←← _Equivalent_ ←←←← <br/>(7280) | `requested`| _Equivalent_ <br/>(18314/18315)| `requested`| _Equivalent_ <br/>(9509/11848)| `requested`
| | | **`entered-in-error`**| _Equivalent_ <br/>(4390/7273)| `entered-in-error`| _Equivalent_ <br/>(18334/18335)| `entered-in-error`| _Equivalent_ <br/>(9518/11857)| `entered-in-error`
| | | *4 of 4 codes used* | | *11 of 12 codes used* <br/>remaining codes:<br/>`on-hold`| | *11 of 12 codes used* <br/>remaining codes:<br/>`on-hold`| | *11 of 12 codes used* <br/>remaining codes:<br/>`on-hold`

