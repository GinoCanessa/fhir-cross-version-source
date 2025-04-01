Comparison of 
Generated at Tuesday, April 1, 2025 1:39:12 PM

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
| [CommunicationRequestStatus](/docs/R2/ValueSets/CommunicationRequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/communication-request-status\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `30`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `287`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R3/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `357`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `580`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R4/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1703`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1704`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R4B/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `800`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1061`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R5/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|5.0.0` 
| [DeviceUseRequestStatus](/docs/R2/ValueSets/DeviceUseRequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/device-use-request-status\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `61`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `287`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R3/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `357`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `580`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R4/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1703`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1704`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R4B/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `800`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1061`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R5/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|5.0.0` 
| [DiagnosticOrderStatus](/docs/R2/ValueSets/DiagnosticOrderStatus.md)<br/> `http://hl7.org/fhir/ValueSet/diagnostic-order-status\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `57`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `287`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R3/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `357`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `580`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R4/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1703`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1704`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R4B/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `800`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1061`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R5/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|5.0.0` 
| [ProcedureRequestStatus](/docs/R2/ValueSets/ProcedureRequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/procedure-request-status\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `118`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `287`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R3/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `357`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `580`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R4/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1703`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1704`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R4B/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `800`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1061`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R5/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|5.0.0` 
| [ReferralStatus](/docs/R2/ValueSets/ReferralStatus.md)<br/> `http://hl7.org/fhir/ValueSet/referralstatus\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `129`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `287`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R3/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `357`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `580`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R4/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1703`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1704`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R4B/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `800`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1061`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R5/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set RequestStatus from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 CommunicationRequestStatus](/docs/R2/ValueSets/CommunicationRequestStatus.md)| Relationship | R3 RequestStatus| Relationship | [R4 RequestStatus](/docs/R4/ValueSets/RequestStatus.md)| Relationship | [R4B RequestStatus](/docs/R4B/ValueSets/RequestStatus.md)| Relationship | [R5 RequestStatus](/docs/R5/ValueSets/RequestStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/request-status`
| `draft`| →→→→ _Equivalent_ →→→→ <br/>(1092)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2511) | **`draft`**| →→→→ _Equivalent_ →→→→ <br/>(3046)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5256) | `draft`| _Equivalent_ <br/>(17008/17009)| `draft`| _Equivalent_ <br/>(7562/9832)| `draft`
| `requested`| →→→→ _Equivalent_ →→→→ <br/>(1094)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2505) | **`active`**| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| `active`| →→→→ _Equivalent_ →→→→ <br/>(1089)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2505) | **`active`**| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| `accepted`| →→→→ _Equivalent_ →→→→ <br/>(1088)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2505) | **`active`**| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| | | **`suspended`**| _Equivalent_ <br/>(3051/5258)| `on-hold`| _Equivalent_ <br/>(17012/17013)| `on-hold`| _Equivalent_ <br/>(7567/9837)| `on-hold`
| `cancelled`| →→→→ _Equivalent_ →→→→ <br/>(1090)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2509) | **`cancelled`**| _Equivalent_ <br/>(3048/5259)| `revoked`| _Equivalent_ <br/>(17014/17015)| `revoked`| _Equivalent_ <br/>(7565/9835)| `revoked`
| `rejected`| →→→→ _Equivalent_ →→→→ <br/>(1093)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2509) | **`cancelled`**| _Equivalent_ <br/>(3048/5259)| `revoked`| _Equivalent_ <br/>(17014/17015)| `revoked`| _Equivalent_ <br/>(7565/9835)| `revoked`
| `completed`| →→→→ _Equivalent_ →→→→ <br/>(1091)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2510) | **`completed`**| _Equivalent_ <br/>(3049/5255)| `completed`| _Equivalent_ <br/>(17016/17017)| `completed`| _Equivalent_ <br/>(7564/9834)| `completed`
| | | **`entered-in-error`**| _Equivalent_ <br/>(3050/5257)| `entered-in-error`| _Equivalent_ <br/>(17018/17019)| `entered-in-error`| _Equivalent_ <br/>(7566/9836)| `entered-in-error`
| | | **`unknown`**| _Equivalent_ <br/>(3052/5260)| `unknown`| _Equivalent_ <br/>(17020/17021)| `unknown`| _Equivalent_ <br/>(7568/9838)| `unknown`
| *7 of 10 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* 


#### Map Group 1

This group is centered on the Value Set RequestStatus from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 DeviceUseRequestStatus](/docs/R2/ValueSets/DeviceUseRequestStatus.md)| Relationship | R3 RequestStatus| Relationship | [R4 RequestStatus](/docs/R4/ValueSets/RequestStatus.md)| Relationship | [R4B RequestStatus](/docs/R4B/ValueSets/RequestStatus.md)| Relationship | [R5 RequestStatus](/docs/R5/ValueSets/RequestStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/request-status`
| `draft`| →→→→ _Equivalent_ →→→→ <br/>(1092)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2511) | **`draft`**| →→→→ _Equivalent_ →→→→ <br/>(3046)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5256) | `draft`| _Equivalent_ <br/>(17008/17009)| `draft`| _Equivalent_ <br/>(7562/9832)| `draft`
| `requested`| →→→→ _Equivalent_ →→→→ <br/>(1094)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2505) | **`active`**| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| `active`| →→→→ _Equivalent_ →→→→ <br/>(1089)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2505) | **`active`**| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| `accepted`| →→→→ _Equivalent_ →→→→ <br/>(1088)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2505) | **`active`**| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| | | **`suspended`**| _Equivalent_ <br/>(3051/5258)| `on-hold`| _Equivalent_ <br/>(17012/17013)| `on-hold`| _Equivalent_ <br/>(7567/9837)| `on-hold`
| `cancelled`| →→→→ _Equivalent_ →→→→ <br/>(1090)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2509) | **`cancelled`**| _Equivalent_ <br/>(3048/5259)| `revoked`| _Equivalent_ <br/>(17014/17015)| `revoked`| _Equivalent_ <br/>(7565/9835)| `revoked`
| `rejected`| →→→→ _Equivalent_ →→→→ <br/>(1093)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2509) | **`cancelled`**| _Equivalent_ <br/>(3048/5259)| `revoked`| _Equivalent_ <br/>(17014/17015)| `revoked`| _Equivalent_ <br/>(7565/9835)| `revoked`
| `completed`| →→→→ _Equivalent_ →→→→ <br/>(1091)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2510) | **`completed`**| _Equivalent_ <br/>(3049/5255)| `completed`| _Equivalent_ <br/>(17016/17017)| `completed`| _Equivalent_ <br/>(7564/9834)| `completed`
| | | **`entered-in-error`**| _Equivalent_ <br/>(3050/5257)| `entered-in-error`| _Equivalent_ <br/>(17018/17019)| `entered-in-error`| _Equivalent_ <br/>(7566/9836)| `entered-in-error`
| | | **`unknown`**| _Equivalent_ <br/>(3052/5260)| `unknown`| _Equivalent_ <br/>(17020/17021)| `unknown`| _Equivalent_ <br/>(7568/9838)| `unknown`
| *7 of 10 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* 


#### Map Group 2

This group is centered on the Value Set RequestStatus from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 DiagnosticOrderStatus](/docs/R2/ValueSets/DiagnosticOrderStatus.md)| Relationship | R3 RequestStatus| Relationship | [R4 RequestStatus](/docs/R4/ValueSets/RequestStatus.md)| Relationship | [R4B RequestStatus](/docs/R4B/ValueSets/RequestStatus.md)| Relationship | [R5 RequestStatus](/docs/R5/ValueSets/RequestStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/request-status`
| `draft`| →→→→ _Equivalent_ →→→→ <br/>(1092)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2511) | **`draft`**| →→→→ _Equivalent_ →→→→ <br/>(3046)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5256) | `draft`| _Equivalent_ <br/>(17008/17009)| `draft`| _Equivalent_ <br/>(7562/9832)| `draft`
| `requested`| →→→→ _Equivalent_ →→→→ <br/>(1094)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2505) | **`active`**| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| `active`| →→→→ _Equivalent_ →→→→ <br/>(1089)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2505) | **`active`**| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| `accepted`| →→→→ _Equivalent_ →→→→ <br/>(1088)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2505) | **`active`**| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| | | **`suspended`**| _Equivalent_ <br/>(3051/5258)| `on-hold`| _Equivalent_ <br/>(17012/17013)| `on-hold`| _Equivalent_ <br/>(7567/9837)| `on-hold`
| `cancelled`| →→→→ _Equivalent_ →→→→ <br/>(1090)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2509) | **`cancelled`**| _Equivalent_ <br/>(3048/5259)| `revoked`| _Equivalent_ <br/>(17014/17015)| `revoked`| _Equivalent_ <br/>(7565/9835)| `revoked`
| `rejected`| →→→→ _Equivalent_ →→→→ <br/>(1093)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2509) | **`cancelled`**| _Equivalent_ <br/>(3048/5259)| `revoked`| _Equivalent_ <br/>(17014/17015)| `revoked`| _Equivalent_ <br/>(7565/9835)| `revoked`
| `completed`| →→→→ _Equivalent_ →→→→ <br/>(1091)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2510) | **`completed`**| _Equivalent_ <br/>(3049/5255)| `completed`| _Equivalent_ <br/>(17016/17017)| `completed`| _Equivalent_ <br/>(7564/9834)| `completed`
| | | **`entered-in-error`**| _Equivalent_ <br/>(3050/5257)| `entered-in-error`| _Equivalent_ <br/>(17018/17019)| `entered-in-error`| _Equivalent_ <br/>(7566/9836)| `entered-in-error`
| | | **`unknown`**| _Equivalent_ <br/>(3052/5260)| `unknown`| _Equivalent_ <br/>(17020/17021)| `unknown`| _Equivalent_ <br/>(7568/9838)| `unknown`
| *7 of 13 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* 


#### Map Group 3

This group is centered on the Value Set RequestStatus from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 ProcedureRequestStatus](/docs/R2/ValueSets/ProcedureRequestStatus.md)| Relationship | R3 RequestStatus| Relationship | [R4 RequestStatus](/docs/R4/ValueSets/RequestStatus.md)| Relationship | [R4B RequestStatus](/docs/R4B/ValueSets/RequestStatus.md)| Relationship | [R5 RequestStatus](/docs/R5/ValueSets/RequestStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/request-status`
| `draft`| →→→→ _Equivalent_ →→→→ <br/>(1092)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2511) | **`draft`**| →→→→ _Equivalent_ →→→→ <br/>(3046)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5256) | `draft`| _Equivalent_ <br/>(17008/17009)| `draft`| _Equivalent_ <br/>(7562/9832)| `draft`
| `requested`| →→→→ _Equivalent_ →→→→ <br/>(1094)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2505) | **`active`**| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| `active`| →→→→ _Equivalent_ →→→→ <br/>(1089)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2505) | **`active`**| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| `accepted`| →→→→ _Equivalent_ →→→→ <br/>(1088)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2505) | **`active`**| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| | | **`suspended`**| _Equivalent_ <br/>(3051/5258)| `on-hold`| _Equivalent_ <br/>(17012/17013)| `on-hold`| _Equivalent_ <br/>(7567/9837)| `on-hold`
| `cancelled`| →→→→ _Equivalent_ →→→→ <br/>(1090)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2509) | **`cancelled`**| _Equivalent_ <br/>(3048/5259)| `revoked`| _Equivalent_ <br/>(17014/17015)| `revoked`| _Equivalent_ <br/>(7565/9835)| `revoked`
| `rejected`| →→→→ _Equivalent_ →→→→ <br/>(1093)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2509) | **`cancelled`**| _Equivalent_ <br/>(3048/5259)| `revoked`| _Equivalent_ <br/>(17014/17015)| `revoked`| _Equivalent_ <br/>(7565/9835)| `revoked`
| `completed`| →→→→ _Equivalent_ →→→→ <br/>(1091)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2510) | **`completed`**| _Equivalent_ <br/>(3049/5255)| `completed`| _Equivalent_ <br/>(17016/17017)| `completed`| _Equivalent_ <br/>(7564/9834)| `completed`
| | | **`entered-in-error`**| _Equivalent_ <br/>(3050/5257)| `entered-in-error`| _Equivalent_ <br/>(17018/17019)| `entered-in-error`| _Equivalent_ <br/>(7566/9836)| `entered-in-error`
| | | **`unknown`**| _Equivalent_ <br/>(3052/5260)| `unknown`| _Equivalent_ <br/>(17020/17021)| `unknown`| _Equivalent_ <br/>(7568/9838)| `unknown`
| *7 of 10 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* 


#### Map Group 4

This group is centered on the Value Set RequestStatus from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 ReferralStatus](/docs/R2/ValueSets/ReferralStatus.md)| Relationship | R3 RequestStatus| Relationship | [R4 RequestStatus](/docs/R4/ValueSets/RequestStatus.md)| Relationship | [R4B RequestStatus](/docs/R4B/ValueSets/RequestStatus.md)| Relationship | [R5 RequestStatus](/docs/R5/ValueSets/RequestStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/request-status`
| `draft`| →→→→ _Equivalent_ →→→→ <br/>(1092)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2511) | **`draft`**| →→→→ _Equivalent_ →→→→ <br/>(3046)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5256) | `draft`| _Equivalent_ <br/>(17008/17009)| `draft`| _Equivalent_ <br/>(7562/9832)| `draft`
| `requested`| →→→→ _Equivalent_ →→→→ <br/>(1094)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2505) | **`active`**| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| `active`| →→→→ _Equivalent_ →→→→ <br/>(1089)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2505) | **`active`**| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| `accepted`| →→→→ _Equivalent_ →→→→ <br/>(1088)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2505) | **`active`**| _Equivalent_ <br/>(3047/5254)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| | | **`suspended`**| _Equivalent_ <br/>(3051/5258)| `on-hold`| _Equivalent_ <br/>(17012/17013)| `on-hold`| _Equivalent_ <br/>(7567/9837)| `on-hold`
| `cancelled`| →→→→ _Equivalent_ →→→→ <br/>(1090)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2509) | **`cancelled`**| _Equivalent_ <br/>(3048/5259)| `revoked`| _Equivalent_ <br/>(17014/17015)| `revoked`| _Equivalent_ <br/>(7565/9835)| `revoked`
| `rejected`| →→→→ _Equivalent_ →→→→ <br/>(1093)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2509) | **`cancelled`**| _Equivalent_ <br/>(3048/5259)| `revoked`| _Equivalent_ <br/>(17014/17015)| `revoked`| _Equivalent_ <br/>(7565/9835)| `revoked`
| `completed`| →→→→ _Equivalent_ →→→→ <br/>(1091)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2510) | **`completed`**| _Equivalent_ <br/>(3049/5255)| `completed`| _Equivalent_ <br/>(17016/17017)| `completed`| _Equivalent_ <br/>(7564/9834)| `completed`
| | | **`entered-in-error`**| _Equivalent_ <br/>(3050/5257)| `entered-in-error`| _Equivalent_ <br/>(17018/17019)| `entered-in-error`| _Equivalent_ <br/>(7566/9836)| `entered-in-error`
| | | **`unknown`**| _Equivalent_ <br/>(3052/5260)| `unknown`| _Equivalent_ <br/>(17020/17021)| `unknown`| _Equivalent_ <br/>(7568/9838)| `unknown`
| *7 of 7 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* 

