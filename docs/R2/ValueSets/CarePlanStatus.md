Comparison of 
Generated at Friday, April 4, 2025 2:58:31 PM

### CarePlanStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | CarePlanStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/care-plan-status` |
| Version | 1.0.2 |
| Description | Indicates whether the plan is currently being acted upon, represents future intentions or is now a historical record. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `47` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/CarePlan` | `CarePlan.status` | `http://hl7.org/fhir/ValueSet/care-plan-status` | `Required` | proposed \| draft \| active \| completed \| cancelled |

### Referenced Systems

* `http://hl7.org/fhir/care-plan-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [CarePlanStatus](/docs/R2/ValueSets/CarePlanStatus.md)<br/> `http://hl7.org/fhir/ValueSet/care-plan-status\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `47`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `206`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CarePlanStatus](/docs/R3/ValueSets/CarePlanStatus.md)<br/> `http://hl7.org/fhir/ValueSet/care-plan-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `377`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `600`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R4/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1703`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1704`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R4B/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `800`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1061`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestStatus](/docs/R5/ValueSets/RequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/request-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set CarePlanStatus from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 CarePlanStatus| Relationship | [R3 CarePlanStatus](/docs/R3/ValueSets/CarePlanStatus.md)| Relationship | [R4 RequestStatus](/docs/R4/ValueSets/RequestStatus.md)| Relationship | [R4B RequestStatus](/docs/R4B/ValueSets/RequestStatus.md)| Relationship | [R5 RequestStatus](/docs/R5/ValueSets/RequestStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/care-plan-status`
| **`proposed`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(226)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1593) | `draft`| _Equivalent_ <br/>(3147/5354)| `draft`| _Equivalent_ <br/>(17008/17009)| `draft`| _Equivalent_ <br/>(7562/9832)| `draft`
| **`draft`**| →→→→ _Equivalent_ →→→→ <br/>(225)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1594) | `draft`| _Equivalent_ <br/>(3147/5354)| `draft`| _Equivalent_ <br/>(17008/17009)| `draft`| _Equivalent_ <br/>(7562/9832)| `draft`
| **`active`**| _Equivalent_ <br/>(222/1590)| `active`| _Equivalent_ <br/>(3144/5355)| `active`| _Equivalent_ <br/>(17010/17011)| `active`| _Equivalent_ <br/>(7563/9833)| `active`
| **`completed`**| _Equivalent_ <br/>(224/1592)| `completed`| _Equivalent_ <br/>(3146/5356)| `completed`| _Equivalent_ <br/>(17016/17017)| `completed`| _Equivalent_ <br/>(7564/9834)| `completed`
| **`cancelled`**| _Equivalent_ <br/>(223/1591)| `cancelled`| _Equivalent_ <br/>(3145/5357)| `revoked`| _Equivalent_ <br/>(17014/17015)| `revoked`| _Equivalent_ <br/>(7565/9835)| `revoked`
| *5 of 5 codes used* | | *4 of 7 codes used* <br/>remaining codes:<br/>`entered-in-error`, `suspended`, `unknown`| | *4 of 7 codes used* <br/>remaining codes:<br/>`entered-in-error`, `on-hold`, `unknown`| | *4 of 7 codes used* <br/>remaining codes:<br/>`entered-in-error`, `on-hold`, `unknown`| | *4 of 7 codes used* <br/>remaining codes:<br/>`entered-in-error`, `on-hold`, `unknown`

