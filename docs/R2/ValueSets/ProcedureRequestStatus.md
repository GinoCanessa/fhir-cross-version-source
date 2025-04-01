Comparison of 
Generated at Tuesday, April 1, 2025 1:39:06 PM

### ProcedureRequestStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | ProcedureRequestStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/procedure-request-status` |
| Version | 1.0.2 |
| Description | The status of the request. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `291` |
| Database Concept Count | `10` |
| Database Active Concept Count | `10` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ProcedureRequest` | `ProcedureRequest.status` | `http://hl7.org/fhir/ValueSet/procedure-request-status` | `Required` | proposed \| draft \| requested \| received \| accepted \| in-progress \| completed \| suspended \| rejected \| aborted |

### Referenced Systems

* `http://hl7.org/fhir/procedure-request-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ProcedureRequestStatus](/docs/R2/ValueSets/ProcedureRequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/procedure-request-status\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `118`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `275`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R3/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `357`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `580`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R4/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1703`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1704`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R4B/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `800`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1061`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R5/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set ProcedureRequestStatus from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 ProcedureRequestStatus| Relationship | [R3 RequestStatus](/docs/R3/ValueSets/RequestStatus.md)| Relationship | [R4 RequestStatus](/docs/R4/ValueSets/RequestStatus.md)| Relationship | [R4B RequestStatus](/docs/R4B/ValueSets/RequestStatus.md)| Relationship | [R5 RequestStatus](/docs/R5/ValueSets/RequestStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/procedure-request-status`
| **`proposed`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(986)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2374) | `draft`| →→→→ _Equivalent_ →→→→ <br/>(3046)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5256) | `draft`| _Equivalent_ <br/>(17008/17009)| `draft`| _Equivalent_ <br/>(7562/9832)| `draft`
| **`draft`**| →→→→ _Equivalent_ →→→→ <br/>(984)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2373) | `draft`| →→→→ _Equivalent_ →→→→ <br/>(3046)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5256) | `draft`| _Equivalent_ <br/>(17008/17009)| `draft`| _Equivalent_ <br/>(7562/9832)| `draft`
| **`requested`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(989)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2368) | `draft`| →→→→ _Equivalent_ →→→→ <br/>(3046)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5256) | `draft`| _Equivalent_ <br/>(17008/17009)| `draft`| _Equivalent_ <br/>(7562/9832)| `draft`
| **`requested`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(989)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2368) | `active`| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| **`received`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(987)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2372) | `completed`| _Equivalent_ <br/>(3049/5255)| `completed`| _Equivalent_ <br/>(17016/17017)| `completed`| _Equivalent_ <br/>(7564/9834)| `completed`
| **`accepted`**| →→→→ _Equivalent_ →→→→ <br/>(982)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2366) | `active`| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| **`in-progress`**| →→→→ _Equivalent_ →→→→ <br/>(985)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2367) | `active`| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| **`completed`**| →→→→ _Equivalent_ →→→→ <br/>(983)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2371) | `completed`| _Equivalent_ <br/>(3049/5255)| `completed`| _Equivalent_ <br/>(17016/17017)| `completed`| _Equivalent_ <br/>(7564/9834)| `completed`
| **`suspended`**| _Equivalent_ <br/>(991/2377)| `suspended`| _Equivalent_ <br/>(3051/5258)| `on-hold`| _Equivalent_ <br/>(17012/17013)| `on-hold`| _Equivalent_ <br/>(7567/9837)| `on-hold`
| **`rejected`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(988)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2369) | `cancelled`| _Equivalent_ <br/>(3048/5259)| `revoked`| _Equivalent_ <br/>(17014/17015)| `revoked`| _Equivalent_ <br/>(7565/9835)| `revoked`
| **`aborted`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(981)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2370) | `cancelled`| _Equivalent_ <br/>(3048/5259)| `revoked`| _Equivalent_ <br/>(17014/17015)| `revoked`| _Equivalent_ <br/>(7565/9835)| `revoked`
| *10 of 10 codes used* | | *5 of 7 codes used* | | *5 of 7 codes used* | | *5 of 7 codes used* | | *5 of 7 codes used* 

