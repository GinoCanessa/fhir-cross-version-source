Comparison of 
Generated at Monday, April 14, 2025 6:17:21 PM

### RequestStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | RequestStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/request-status` |
| Version | 3.0.2 |
| Description | Codes identifying the stage lifecycle stage of a request |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `1447` |
| Database Concept Count | `7` |
| Database Active Concept Count | `7` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/CommunicationRequest` | `CommunicationRequest.status` | `http://hl7.org/fhir/ValueSet/request-status` | `Required` | draft \| active \| suspended \| cancelled \| completed \| entered-in-error \| unknown |
| `http://hl7.org/fhir/StructureDefinition/DeviceRequest` | `DeviceRequest.status` | `http://hl7.org/fhir/ValueSet/request-status` | `Required` | draft \| active \| suspended \| completed \| entered-in-error \| cancelled |
| `http://hl7.org/fhir/StructureDefinition/ProcedureRequest` | `ProcedureRequest.status` | `http://hl7.org/fhir/ValueSet/request-status` | `Required` | draft \| active \| suspended \| completed \| entered-in-error \| cancelled |
| `http://hl7.org/fhir/StructureDefinition/ReferralRequest` | `ReferralRequest.status` | `http://hl7.org/fhir/ValueSet/request-status` | `Required` | draft \| active \| suspended \| cancelled \| completed \| entered-in-error \| unknown |
| `http://hl7.org/fhir/StructureDefinition/RequestGroup` | `RequestGroup.status` | `http://hl7.org/fhir/ValueSet/request-status` | `Required` | draft \| active \| suspended \| cancelled \| completed \| entered-in-error \| unknown |

### Referenced Systems

* `http://hl7.org/fhir/request-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [CommunicationRequestStatus](/docs/R2/ValueSets/CommunicationRequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/communication-request-status\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `30`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>*no map*<br/>←←←←←←←| [RequestStatus](/docs/R3/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `357`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `580`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [RequestStatus](/docs/R4/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1703`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1704`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [RequestStatus](/docs/R4B/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `800`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1061`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [RequestStatus](/docs/R5/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|5.0.0` 
| [DeviceUseRequestStatus](/docs/R2/ValueSets/DeviceUseRequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/device-use-request-status\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `61`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>*no map*<br/>←←←←←←←| [RequestStatus](/docs/R3/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `357`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `580`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [RequestStatus](/docs/R4/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1703`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1704`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [RequestStatus](/docs/R4B/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `800`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1061`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [RequestStatus](/docs/R5/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|5.0.0` 
| [DiagnosticOrderStatus](/docs/R2/ValueSets/DiagnosticOrderStatus.md)<br/> `http://hl7.org/fhir/ValueSet/diagnostic-order-status\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `57`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>*no map*<br/>←←←←←←←| [RequestStatus](/docs/R3/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `357`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `580`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [RequestStatus](/docs/R4/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1703`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1704`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [RequestStatus](/docs/R4B/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `800`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1061`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [RequestStatus](/docs/R5/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|5.0.0` 
| [ProcedureRequestStatus](/docs/R2/ValueSets/ProcedureRequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/procedure-request-status\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `118`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>*no map*<br/>←←←←←←←| [RequestStatus](/docs/R3/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `357`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `580`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [RequestStatus](/docs/R4/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1703`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1704`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [RequestStatus](/docs/R4B/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `800`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1061`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [RequestStatus](/docs/R5/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|5.0.0` 
| [ReferralStatus](/docs/R2/ValueSets/ReferralStatus.md)<br/> `http://hl7.org/fhir/ValueSet/referralstatus\|1.0.2` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `129`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>*no map*<br/>←←←←←←←| [RequestStatus](/docs/R3/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `357`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `580`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [RequestStatus](/docs/R4/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1703`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1704`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [RequestStatus](/docs/R4B/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `800`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1061`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [RequestStatus](/docs/R5/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set RequestStatus from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 CommunicationRequestStatus](/docs/R2/ValueSets/CommunicationRequestStatus.md)| Relationship | R3 RequestStatus| Relationship | [R4 RequestStatus](/docs/R4/ValueSets/RequestStatus.md)| Relationship | [R4B RequestStatus](/docs/R4B/ValueSets/RequestStatus.md)| Relationship | [R5 RequestStatus](/docs/R5/ValueSets/RequestStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/request-status`
| `proposed`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(149)<hr/>←←←← __ ←←←← <br/>() | **`draft`**| _Equivalent_ <br/>(3046/5256)| `draft`| _Equivalent_ <br/>(17008/17009)| `draft`| _Equivalent_ <br/>(7562/9832)| `draft`
| `planned`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(148)<hr/>←←←← __ ←←←← <br/>() | **`draft`**| _Equivalent_ <br/>(3046/5256)| `draft`| _Equivalent_ <br/>(17008/17009)| `draft`| _Equivalent_ <br/>(7562/9832)| `draft`
| `requested`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(152)<hr/>←←←← __ ←←←← <br/>() | **`draft`**| _Equivalent_ <br/>(3046/5256)| `draft`| _Equivalent_ <br/>(17008/17009)| `draft`| _Equivalent_ <br/>(7562/9832)| `draft`
| `received`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(150)<hr/>←←←← __ ←←←← <br/>() | **`active`**| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| `accepted`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(143)<hr/>←←←← __ ←←←← <br/>() | **`active`**| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| `in-progress`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(147)<hr/>←←←← __ ←←←← <br/>() | **`active`**| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| `suspended`| _Equivalent_ <br/>(153/1515)| **`suspended`**| _Equivalent_ <br/>(3051/5258)| `on-hold`| _Equivalent_ <br/>(17012/17013)| `on-hold`| _Equivalent_ <br/>(7567/9837)| `on-hold`
| `rejected`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(151)<hr/>←←←← __ ←←←← <br/>() | **`cancelled`**| _Equivalent_ <br/>(3048/5259)| `revoked`| _Equivalent_ <br/>(17014/17015)| `revoked`| _Equivalent_ <br/>(7565/9835)| `revoked`
| `failed`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(145)<hr/>←←←← __ ←←←← <br/>() | **`cancelled`**| _Equivalent_ <br/>(3048/5259)| `revoked`| _Equivalent_ <br/>(17014/17015)| `revoked`| _Equivalent_ <br/>(7565/9835)| `revoked`
| `completed`| _Equivalent_ <br/>(144/1510)| **`completed`**| _Equivalent_ <br/>(3049/5255)| `completed`| _Equivalent_ <br/>(17016/17017)| `completed`| _Equivalent_ <br/>(7564/9834)| `completed`
| `failed`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(146)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1514) | **`entered-in-error`**| _Equivalent_ <br/>(3050/5257)| `entered-in-error`| _Equivalent_ <br/>(17018/17019)| `entered-in-error`| _Equivalent_ <br/>(7566/9836)| `entered-in-error`
| | | **`unknown`**| _Equivalent_ <br/>(3052/5260)| `unknown`| _Equivalent_ <br/>(17020/17021)| `unknown`| _Equivalent_ <br/>(7568/9838)| `unknown`
| *10 of 10 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* 


#### Map Group 1

This group is centered on the Value Set RequestStatus from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 DeviceUseRequestStatus](/docs/R2/ValueSets/DeviceUseRequestStatus.md)| Relationship | R3 RequestStatus| Relationship | [R4 RequestStatus](/docs/R4/ValueSets/RequestStatus.md)| Relationship | [R4B RequestStatus](/docs/R4B/ValueSets/RequestStatus.md)| Relationship | [R5 RequestStatus](/docs/R5/ValueSets/RequestStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/request-status`
| `proposed`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(475)<hr/>←←←← __ ←←←← <br/>() | **`draft`**| _Equivalent_ <br/>(3046/5256)| `draft`| _Equivalent_ <br/>(17008/17009)| `draft`| _Equivalent_ <br/>(7562/9832)| `draft`
| `planned`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(474)<hr/>←←←← __ ←←←← <br/>() | **`draft`**| _Equivalent_ <br/>(3046/5256)| `draft`| _Equivalent_ <br/>(17008/17009)| `draft`| _Equivalent_ <br/>(7562/9832)| `draft`
| `requested`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(478)<hr/>←←←← __ ←←←← <br/>() | **`draft`**| _Equivalent_ <br/>(3046/5256)| `draft`| _Equivalent_ <br/>(17008/17009)| `draft`| _Equivalent_ <br/>(7562/9832)| `draft`
| `received`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(476)<hr/>←←←← __ ←←←← <br/>() | **`active`**| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| `accepted`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(471)<hr/>←←←← __ ←←←← <br/>() | **`active`**| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| `in-progress`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(473)<hr/>←←←← __ ←←←← <br/>() | **`active`**| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| `suspended`| _Equivalent_ <br/>(479/1823)| **`suspended`**| _Equivalent_ <br/>(3051/5258)| `on-hold`| _Equivalent_ <br/>(17012/17013)| `on-hold`| _Equivalent_ <br/>(7567/9837)| `on-hold`
| `rejected`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(477)<hr/>←←←← __ ←←←← <br/>() | **`cancelled`**| _Equivalent_ <br/>(3048/5259)| `revoked`| _Equivalent_ <br/>(17014/17015)| `revoked`| _Equivalent_ <br/>(7565/9835)| `revoked`
| `aborted`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(470)<hr/>←←←← __ ←←←← <br/>() | **`cancelled`**| _Equivalent_ <br/>(3048/5259)| `revoked`| _Equivalent_ <br/>(17014/17015)| `revoked`| _Equivalent_ <br/>(7565/9835)| `revoked`
| `completed`| _Equivalent_ <br/>(472/1818)| **`completed`**| _Equivalent_ <br/>(3049/5255)| `completed`| _Equivalent_ <br/>(17016/17017)| `completed`| _Equivalent_ <br/>(7564/9834)| `completed`
| | | **`entered-in-error`**| _Equivalent_ <br/>(3050/5257)| `entered-in-error`| _Equivalent_ <br/>(17018/17019)| `entered-in-error`| _Equivalent_ <br/>(7566/9836)| `entered-in-error`
| | | **`unknown`**| _Equivalent_ <br/>(3052/5260)| `unknown`| _Equivalent_ <br/>(17020/17021)| `unknown`| _Equivalent_ <br/>(7568/9838)| `unknown`
| *10 of 10 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* 


#### Map Group 2

This group is centered on the Value Set RequestStatus from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 DiagnosticOrderStatus](/docs/R2/ValueSets/DiagnosticOrderStatus.md)| Relationship | R3 RequestStatus| Relationship | [R4 RequestStatus](/docs/R4/ValueSets/RequestStatus.md)| Relationship | [R4B RequestStatus](/docs/R4B/ValueSets/RequestStatus.md)| Relationship | [R5 RequestStatus](/docs/R5/ValueSets/RequestStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/request-status`
| `proposed`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(451)<hr/>←←←← __ ←←←← <br/>() | **`draft`**| _Equivalent_ <br/>(3046/5256)| `draft`| _Equivalent_ <br/>(17008/17009)| `draft`| _Equivalent_ <br/>(7562/9832)| `draft`
| `draft`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(453)<hr/>←←←← __ ←←←← <br/>() | **`draft`**| _Equivalent_ <br/>(3046/5256)| `draft`| _Equivalent_ <br/>(17008/17009)| `draft`| _Equivalent_ <br/>(7562/9832)| `draft`
| `planned`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(445)<hr/>←←←← __ ←←←← <br/>() | **`draft`**| _Equivalent_ <br/>(3046/5256)| `draft`| _Equivalent_ <br/>(17008/17009)| `draft`| _Equivalent_ <br/>(7562/9832)| `draft`
| `requested`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(450)<hr/>←←←← __ ←←←← <br/>() | **`active`**| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| `received`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(444)<hr/>←←←← __ ←←←← <br/>() | **`active`**| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| `accepted`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(443)<hr/>←←←← __ ←←←← <br/>() | **`active`**| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| `in-progress`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(448)<hr/>←←←← __ ←←←← <br/>() | **`active`**| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| `review`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(452)<hr/>←←←← __ ←←←← <br/>() | **`active`**| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| `suspended`| _Equivalent_ <br/>(449/2391)| **`suspended`**| _Equivalent_ <br/>(3051/5258)| `on-hold`| _Equivalent_ <br/>(17012/17013)| `on-hold`| _Equivalent_ <br/>(7567/9837)| `on-hold`
| `cancelled`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(454)<hr/>←←←← __ ←←←← <br/>() | **`cancelled`**| _Equivalent_ <br/>(3048/5259)| `revoked`| _Equivalent_ <br/>(17014/17015)| `revoked`| _Equivalent_ <br/>(7565/9835)| `revoked`
| `rejected`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(442)<hr/>←←←← __ ←←←← <br/>() | **`cancelled`**| _Equivalent_ <br/>(3048/5259)| `revoked`| _Equivalent_ <br/>(17014/17015)| `revoked`| _Equivalent_ <br/>(7565/9835)| `revoked`
| `completed`| _Equivalent_ <br/>(446/2386)| **`completed`**| _Equivalent_ <br/>(3049/5255)| `completed`| _Equivalent_ <br/>(17016/17017)| `completed`| _Equivalent_ <br/>(7564/9834)| `completed`
| | | **`entered-in-error`**| _Equivalent_ <br/>(3050/5257)| `entered-in-error`| _Equivalent_ <br/>(17018/17019)| `entered-in-error`| _Equivalent_ <br/>(7566/9836)| `entered-in-error`
| | | **`unknown`**| _Equivalent_ <br/>(3052/5260)| `unknown`| _Equivalent_ <br/>(17020/17021)| `unknown`| _Equivalent_ <br/>(7568/9838)| `unknown`
| *12 of 13 codes used* <br/>remaining codes:<br/>`failed`| | *7 of 7 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* 


#### Map Group 3

This group is centered on the Value Set RequestStatus from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 ProcedureRequestStatus](/docs/R2/ValueSets/ProcedureRequestStatus.md)| Relationship | R3 RequestStatus| Relationship | [R4 RequestStatus](/docs/R4/ValueSets/RequestStatus.md)| Relationship | [R4B RequestStatus](/docs/R4B/ValueSets/RequestStatus.md)| Relationship | [R5 RequestStatus](/docs/R5/ValueSets/RequestStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/request-status`
| `proposed`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(986)<hr/>←←←← __ ←←←← <br/>() | **`draft`**| _Equivalent_ <br/>(3046/5256)| `draft`| _Equivalent_ <br/>(17008/17009)| `draft`| _Equivalent_ <br/>(7562/9832)| `draft`
| `draft`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(984)<hr/>←←←← __ ←←←← <br/>() | **`draft`**| _Equivalent_ <br/>(3046/5256)| `draft`| _Equivalent_ <br/>(17008/17009)| `draft`| _Equivalent_ <br/>(7562/9832)| `draft`
| `requested`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(990)<hr/>←←←← __ ←←←← <br/>() | **`draft`**| _Equivalent_ <br/>(3046/5256)| `draft`| _Equivalent_ <br/>(17008/17009)| `draft`| _Equivalent_ <br/>(7562/9832)| `draft`
| `requested`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(989)<hr/>←←←← __ ←←←← <br/>() | **`active`**| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| `accepted`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(982)<hr/>←←←← __ ←←←← <br/>() | **`active`**| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| `in-progress`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(985)<hr/>←←←← __ ←←←← <br/>() | **`active`**| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| `suspended`| _Equivalent_ <br/>(991/2377)| **`suspended`**| _Equivalent_ <br/>(3051/5258)| `on-hold`| _Equivalent_ <br/>(17012/17013)| `on-hold`| _Equivalent_ <br/>(7567/9837)| `on-hold`
| `rejected`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(988)<hr/>←←←← __ ←←←← <br/>() | **`cancelled`**| _Equivalent_ <br/>(3048/5259)| `revoked`| _Equivalent_ <br/>(17014/17015)| `revoked`| _Equivalent_ <br/>(7565/9835)| `revoked`
| `aborted`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(981)<hr/>←←←← __ ←←←← <br/>() | **`cancelled`**| _Equivalent_ <br/>(3048/5259)| `revoked`| _Equivalent_ <br/>(17014/17015)| `revoked`| _Equivalent_ <br/>(7565/9835)| `revoked`
| `received`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(987)<hr/>←←←← __ ←←←← <br/>() | **`completed`**| _Equivalent_ <br/>(3049/5255)| `completed`| _Equivalent_ <br/>(17016/17017)| `completed`| _Equivalent_ <br/>(7564/9834)| `completed`
| `completed`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(983)<hr/>←←←← __ ←←←← <br/>() | **`completed`**| _Equivalent_ <br/>(3049/5255)| `completed`| _Equivalent_ <br/>(17016/17017)| `completed`| _Equivalent_ <br/>(7564/9834)| `completed`
| | | **`entered-in-error`**| _Equivalent_ <br/>(3050/5257)| `entered-in-error`| _Equivalent_ <br/>(17018/17019)| `entered-in-error`| _Equivalent_ <br/>(7566/9836)| `entered-in-error`
| | | **`unknown`**| _Equivalent_ <br/>(3052/5260)| `unknown`| _Equivalent_ <br/>(17020/17021)| `unknown`| _Equivalent_ <br/>(7568/9838)| `unknown`
| *10 of 10 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* 


#### Map Group 4

This group is centered on the Value Set RequestStatus from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 ReferralStatus](/docs/R2/ValueSets/ReferralStatus.md)| Relationship | R3 RequestStatus| Relationship | [R4 RequestStatus](/docs/R4/ValueSets/RequestStatus.md)| Relationship | [R4B RequestStatus](/docs/R4B/ValueSets/RequestStatus.md)| Relationship | [R5 RequestStatus](/docs/R5/ValueSets/RequestStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/request-status`
| `draft`| _Equivalent_ <br/>(1092/2511)| **`draft`**| _Equivalent_ <br/>(3046/5256)| `draft`| _Equivalent_ <br/>(17008/17009)| `draft`| _Equivalent_ <br/>(7562/9832)| `draft`
| `requested`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1094)<hr/>←←←← __ ←←←← <br/>() | **`active`**| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| `active`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1089)<hr/>←←←← __ ←←←← <br/>() | **`active`**| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| `accepted`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1088)<hr/>←←←← __ ←←←← <br/>() | **`active`**| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| | | **`suspended`**| _Equivalent_ <br/>(3051/5258)| `on-hold`| _Equivalent_ <br/>(17012/17013)| `on-hold`| _Equivalent_ <br/>(7567/9837)| `on-hold`
| `cancelled`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1090)<hr/>←←←← __ ←←←← <br/>() | **`cancelled`**| _Equivalent_ <br/>(3048/5259)| `revoked`| _Equivalent_ <br/>(17014/17015)| `revoked`| _Equivalent_ <br/>(7565/9835)| `revoked`
| `rejected`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1093)<hr/>←←←← __ ←←←← <br/>() | **`cancelled`**| _Equivalent_ <br/>(3048/5259)| `revoked`| _Equivalent_ <br/>(17014/17015)| `revoked`| _Equivalent_ <br/>(7565/9835)| `revoked`
| `completed`| _Equivalent_ <br/>(1091/2510)| **`completed`**| _Equivalent_ <br/>(3049/5255)| `completed`| _Equivalent_ <br/>(17016/17017)| `completed`| _Equivalent_ <br/>(7564/9834)| `completed`
| | | **`entered-in-error`**| _Equivalent_ <br/>(3050/5257)| `entered-in-error`| _Equivalent_ <br/>(17018/17019)| `entered-in-error`| _Equivalent_ <br/>(7566/9836)| `entered-in-error`
| | | **`unknown`**| _Equivalent_ <br/>(3052/5260)| `unknown`| _Equivalent_ <br/>(17020/17021)| `unknown`| _Equivalent_ <br/>(7568/9838)| `unknown`
| *7 of 7 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* 

