Comparison of 
Generated at Monday, April 14, 2025 6:17:15 PM

### CommunicationRequestStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | CommunicationRequestStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/communication-request-status` |
| Version | 1.0.2 |
| Description | The status of the communication. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `56` |
| Database Concept Count | `10` |
| Database Active Concept Count | `10` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/CommunicationRequest` | `CommunicationRequest.status` | `http://hl7.org/fhir/ValueSet/communication-request-status` | `Required` | proposed \| planned \| requested \| received \| accepted \| in-progress \| completed \| suspended \| rejected \| failed |

### Referenced Systems

* `http://hl7.org/fhir/communication-request-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [CommunicationRequestStatus](/docs/R2/ValueSets/CommunicationRequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/communication-request-status\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `30`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`RelatedTo`<br/>- DBKey: `189`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [RequestStatus](/docs/R3/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `357`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `580`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [RequestStatus](/docs/R4/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1703`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1704`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [RequestStatus](/docs/R4B/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `800`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1061`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [RequestStatus](/docs/R5/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set CommunicationRequestStatus from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 CommunicationRequestStatus| Relationship | [R3 RequestStatus](/docs/R3/ValueSets/RequestStatus.md)| Relationship | [R4 RequestStatus](/docs/R4/ValueSets/RequestStatus.md)| Relationship | [R4B RequestStatus](/docs/R4B/ValueSets/RequestStatus.md)| Relationship | [R5 RequestStatus](/docs/R5/ValueSets/RequestStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/communication-request-status`
| **`proposed`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(149)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1512) | `draft`| _Equivalent_ <br/>(3046/5256)| `draft`| _Equivalent_ <br/>(17008/17009)| `draft`| _Equivalent_ <br/>(7562/9832)| `draft`
| **`planned`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(148)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1511) | `draft`| _Equivalent_ <br/>(3046/5256)| `draft`| _Equivalent_ <br/>(17008/17009)| `draft`| _Equivalent_ <br/>(7562/9832)| `draft`
| **`requested`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(152)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1513) | `draft`| _Equivalent_ <br/>(3046/5256)| `draft`| _Equivalent_ <br/>(17008/17009)| `draft`| _Equivalent_ <br/>(7562/9832)| `draft`
| **`received`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(150)<hr/>←←←← _Equivalent_ ←←←← <br/>(1507) | `active`| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| **`accepted`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(143)<hr/>←←←← _Equivalent_ ←←←← <br/>(1505) | `active`| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| **`in-progress`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(147)<hr/>←←←← _Equivalent_ ←←←← <br/>(1506) | `active`| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| **`completed`**| _Equivalent_ <br/>(144/1510)| `completed`| _Equivalent_ <br/>(3049/5255)| `completed`| _Equivalent_ <br/>(17016/17017)| `completed`| _Equivalent_ <br/>(7564/9834)| `completed`
| **`suspended`**| _Equivalent_ <br/>(153/1515)| `suspended`| _Equivalent_ <br/>(3051/5258)| `on-hold`| _Equivalent_ <br/>(17012/17013)| `on-hold`| _Equivalent_ <br/>(7567/9837)| `on-hold`
| **`rejected`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(151)<hr/>←←←← _Equivalent_ ←←←← <br/>(1509) | `cancelled`| _Equivalent_ <br/>(3048/5259)| `revoked`| _Equivalent_ <br/>(17014/17015)| `revoked`| _Equivalent_ <br/>(7565/9835)| `revoked`
| **`failed`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(145)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1508) | `cancelled`| _Equivalent_ <br/>(3048/5259)| `revoked`| _Equivalent_ <br/>(17014/17015)| `revoked`| _Equivalent_ <br/>(7565/9835)| `revoked`
| **`failed`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(146)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1514) | `entered-in-error`| _Equivalent_ <br/>(3050/5257)| `entered-in-error`| _Equivalent_ <br/>(17018/17019)| `entered-in-error`| _Equivalent_ <br/>(7566/9836)| `entered-in-error`
| *10 of 10 codes used* | | *6 of 7 codes used* <br/>remaining codes:<br/>`unknown`| | *6 of 7 codes used* <br/>remaining codes:<br/>`unknown`| | *6 of 7 codes used* <br/>remaining codes:<br/>`unknown`| | *6 of 7 codes used* <br/>remaining codes:<br/>`unknown`

