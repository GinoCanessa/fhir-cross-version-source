Comparison of 
Generated at Thursday, April 3, 2025 8:18:05 AM

### DeviceUseRequestStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | DeviceUseRequestStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/device-use-request-status` |
| Version | 1.0.2 |
| Description | Codes representing the status of the request. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `121` |
| Database Concept Count | `10` |
| Database Active Concept Count | `10` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/DeviceUseRequest` | `DeviceUseRequest.status` | `http://hl7.org/fhir/ValueSet/device-use-request-status` | `Required` | proposed \| planned \| requested \| received \| accepted \| in-progress \| completed \| suspended \| rejected \| aborted |

### Referenced Systems

* `http://hl7.org/fhir/device-use-request-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [DeviceUseRequestStatus](/docs/R2/ValueSets/DeviceUseRequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/device-use-request-status\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `61`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `217`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R3/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `357`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `580`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R4/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1703`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1704`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R4B/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `800`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1061`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R5/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set DeviceUseRequestStatus from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 DeviceUseRequestStatus| Relationship | [R3 RequestStatus](/docs/R3/ValueSets/RequestStatus.md)| Relationship | [R4 RequestStatus](/docs/R4/ValueSets/RequestStatus.md)| Relationship | [R4B RequestStatus](/docs/R4B/ValueSets/RequestStatus.md)| Relationship | [R5 RequestStatus](/docs/R5/ValueSets/RequestStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/device-use-request-status`
| **`proposed`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(475)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1820) | `draft`| →→→→ _Equivalent_ →→→→ <br/>(3046)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5256) | `draft`| _Equivalent_ <br/>(17008/17009)| `draft`| _Equivalent_ <br/>(7562/9832)| `draft`
| **`planned`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(474)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1819) | `draft`| →→→→ _Equivalent_ →→→→ <br/>(3046)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5256) | `draft`| _Equivalent_ <br/>(17008/17009)| `draft`| _Equivalent_ <br/>(7562/9832)| `draft`
| **`requested`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(478)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1821) | `draft`| →→→→ _Equivalent_ →→→→ <br/>(3046)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5256) | `draft`| _Equivalent_ <br/>(17008/17009)| `draft`| _Equivalent_ <br/>(7562/9832)| `draft`
| **`received`**| →→→→ _Equivalent_ →→→→ <br/>(476)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1815) | `active`| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| **`accepted`**| →→→→ _Equivalent_ →→→→ <br/>(471)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1813) | `active`| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| **`in-progress`**| →→→→ _Equivalent_ →→→→ <br/>(473)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1814) | `active`| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| **`completed`**| _Equivalent_ <br/>(472/1818)| `completed`| _Equivalent_ <br/>(3049/5255)| `completed`| _Equivalent_ <br/>(17016/17017)| `completed`| _Equivalent_ <br/>(7564/9834)| `completed`
| **`suspended`**| _Equivalent_ <br/>(479/1823)| `suspended`| _Equivalent_ <br/>(3051/5258)| `on-hold`| _Equivalent_ <br/>(17012/17013)| `on-hold`| _Equivalent_ <br/>(7567/9837)| `on-hold`
| **`rejected`**| →→→→ _Equivalent_ →→→→ <br/>(477)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1817) | `cancelled`| _Equivalent_ <br/>(3048/5259)| `revoked`| _Equivalent_ <br/>(17014/17015)| `revoked`| _Equivalent_ <br/>(7565/9835)| `revoked`
| **`aborted`**| →→→→ _Equivalent_ →→→→ <br/>(470)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1816) | `cancelled`| _Equivalent_ <br/>(3048/5259)| `revoked`| _Equivalent_ <br/>(17014/17015)| `revoked`| _Equivalent_ <br/>(7565/9835)| `revoked`
| *10 of 10 codes used* | | *5 of 7 codes used* <br/>remaining codes:<br/>`entered-in-error`, `unknown`| | *5 of 7 codes used* <br/>remaining codes:<br/>`entered-in-error`, `unknown`| | *5 of 7 codes used* <br/>remaining codes:<br/>`entered-in-error`, `unknown`| | *5 of 7 codes used* <br/>remaining codes:<br/>`entered-in-error`, `unknown`

