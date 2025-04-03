Comparison of 
Generated at Thursday, April 3, 2025 8:18:05 AM

### SupplyRequestStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | SupplyRequestStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/supplyrequest-status` |
| Version | 1.0.2 |
| Description | Status of the supply request |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `388` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/SupplyRequest` | `SupplyRequest.status` | `http://hl7.org/fhir/ValueSet/supplyrequest-status` | `Required` | requested \| completed \| failed \| cancelled |

### Referenced Systems

* `http://hl7.org/fhir/supplyrequest-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [SupplyRequestStatus](/docs/R2/ValueSets/SupplyRequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/supplyrequest-status\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `150`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `308`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SupplyRequestStatus](/docs/R3/ValueSets/SupplyRequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/supplyrequest-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `521`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `742`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SupplyRequestStatus](/docs/R4/ValueSets/SupplyRequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/supplyrequest-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1759`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1760`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SupplyRequestStatus](/docs/R4B/ValueSets/SupplyRequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/supplyrequest-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1001`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1262`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SupplyRequestStatus](/docs/R5/ValueSets/SupplyRequestStatus.md)<br/> `http://hl7.org/fhir/ValueSet/supplyrequest-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set SupplyRequestStatus from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 SupplyRequestStatus| Relationship | [R3 SupplyRequestStatus](/docs/R3/ValueSets/SupplyRequestStatus.md)| Relationship | [R4 SupplyRequestStatus](/docs/R4/ValueSets/SupplyRequestStatus.md)| Relationship | [R4B SupplyRequestStatus](/docs/R4B/ValueSets/SupplyRequestStatus.md)| Relationship | [R5 SupplyRequestStatus](/docs/R5/ValueSets/SupplyRequestStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/supplyrequest-status`
| **`requested`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1297)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2745) | `draft`| _Equivalent_ <br/>(4863/7186)| `draft`| _Equivalent_ <br/>(18272/18273)| `draft`| _Equivalent_ <br/>(9441/11778)| `draft`
| **`completed`**| _Equivalent_ <br/>(1295/2744)| `completed`| _Equivalent_ <br/>(4866/7189)| `completed`| _Equivalent_ <br/>(18280/18281)| `completed`| _Equivalent_ <br/>(9444/11781)| `completed`
| **`failed`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1296)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2743) | `cancelled`| _Equivalent_ <br/>(4865/7188)| `cancelled`| _Equivalent_ <br/>(18278/18279)| `cancelled`| _Equivalent_ <br/>(9443/11780)| `cancelled`
| **`cancelled`**| →→→→ _Equivalent_ →→→→ <br/>(1294)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2742) | `cancelled`| _Equivalent_ <br/>(4865/7188)| `cancelled`| _Equivalent_ <br/>(18278/18279)| `cancelled`| _Equivalent_ <br/>(9443/11780)| `cancelled`
| *4 of 4 codes used* | | *3 of 7 codes used* <br/>remaining codes:<br/>`active`, `entered-in-error`, `suspended`, `unknown`| | *3 of 7 codes used* <br/>remaining codes:<br/>`active`, `entered-in-error`, `suspended`, `unknown`| | *3 of 7 codes used* <br/>remaining codes:<br/>`active`, `entered-in-error`, `suspended`, `unknown`| | *3 of 7 codes used* <br/>remaining codes:<br/>`active`, `entered-in-error`, `suspended`, `unknown`

