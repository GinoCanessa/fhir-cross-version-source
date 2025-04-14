Comparison of 
Generated at Monday, April 14, 2025 6:17:15 PM

### ReferralStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | ReferralStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/referralstatus` |
| Version | 1.0.2 |
| Description | The status of the referral. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `336` |
| Database Concept Count | `7` |
| Database Active Concept Count | `7` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ReferralRequest` | `ReferralRequest.status` | `http://hl7.org/fhir/ValueSet/referralstatus` | `Required` | draft \| requested \| active \| cancelled \| accepted \| rejected \| completed |

### Referenced Systems

* `http://hl7.org/fhir/referralstatus`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ReferralStatus](/docs/R2/ValueSets/ReferralStatus.md)<br/> `http://hl7.org/fhir/ValueSet/referralstatus\|1.0.2` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `129`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `287`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [RequestStatus](/docs/R3/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `357`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `580`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [RequestStatus](/docs/R4/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1703`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1704`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [RequestStatus](/docs/R4B/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `800`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1061`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [RequestStatus](/docs/R5/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set ReferralStatus from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 ReferralStatus| Relationship | [R3 RequestStatus](/docs/R3/ValueSets/RequestStatus.md)| Relationship | [R4 RequestStatus](/docs/R4/ValueSets/RequestStatus.md)| Relationship | [R4B RequestStatus](/docs/R4B/ValueSets/RequestStatus.md)| Relationship | [R5 RequestStatus](/docs/R5/ValueSets/RequestStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/referralstatus`
| **`draft`**| _Equivalent_ <br/>(1092/2511)| `draft`| _Equivalent_ <br/>(3046/5256)| `draft`| _Equivalent_ <br/>(17008/17009)| `draft`| _Equivalent_ <br/>(7562/9832)| `draft`
| **`requested`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1094)<hr/>←←←← _Equivalent_ ←←←← <br/>(2507) | `active`| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| **`active`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1089)<hr/>←←←← _Equivalent_ ←←←← <br/>(2506) | `active`| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| **`cancelled`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1090)<hr/>←←←← _Equivalent_ ←←←← <br/>(2508) | `cancelled`| _Equivalent_ <br/>(3048/5259)| `revoked`| _Equivalent_ <br/>(17014/17015)| `revoked`| _Equivalent_ <br/>(7565/9835)| `revoked`
| **`accepted`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1088)<hr/>←←←← _Equivalent_ ←←←← <br/>(2505) | `active`| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| **`rejected`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1093)<hr/>←←←← _Equivalent_ ←←←← <br/>(2509) | `cancelled`| _Equivalent_ <br/>(3048/5259)| `revoked`| _Equivalent_ <br/>(17014/17015)| `revoked`| _Equivalent_ <br/>(7565/9835)| `revoked`
| **`completed`**| _Equivalent_ <br/>(1091/2510)| `completed`| _Equivalent_ <br/>(3049/5255)| `completed`| _Equivalent_ <br/>(17016/17017)| `completed`| _Equivalent_ <br/>(7564/9834)| `completed`
| *7 of 7 codes used* | | *4 of 7 codes used* <br/>remaining codes:<br/>`entered-in-error`, `suspended`, `unknown`| | *4 of 7 codes used* <br/>remaining codes:<br/>`entered-in-error`, `on-hold`, `unknown`| | *4 of 7 codes used* <br/>remaining codes:<br/>`entered-in-error`, `on-hold`, `unknown`| | *4 of 7 codes used* <br/>remaining codes:<br/>`entered-in-error`, `on-hold`, `unknown`

