Comparison of 
Generated at Tuesday, April 1, 2025 1:39:26 PM

### SubscriberRelationshipCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | SubscriberRelationshipCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/subscriber-relationship` |
| Version | 4.3.0 |
| Description | This value set includes codes for the relationship between the Subscriber and the Beneficiary (insured/covered party/patient). |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `4119` |
| Database Concept Count | `7` |
| Database Active Concept Count | `7` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Coverage` | `Coverage.relationship` | `http://hl7.org/fhir/ValueSet/subscriber-relationship` | `Extensible` | Beneficiary relationship to the subscriber |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/subscriber-relationship`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [SubscriberRelationshipCodes](/docs/R4B/ValueSets/SubscriberRelationshipCodes.md)<br/> `http://hl7.org/fhir/ValueSet/subscriber-relationship\|4.3.0` | →→→→→→→<br/>``<br/>- DBKey: `806`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `1067`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SubscriberRelationshipCodes](/docs/R5/ValueSets/SubscriberRelationshipCodes.md)<br/> `http://hl7.org/fhir/ValueSet/subscriber-relationship\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set SubscriberRelationshipCodes from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | R4B SubscriberRelationshipCodes| Relationship | [R5 SubscriberRelationshipCodes](/docs/R5/ValueSets/SubscriberRelationshipCodes.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://terminology.hl7.org/CodeSystem/subscriber-relationship`
| | | | | | | **`child`**| _Equivalent_ <br/>(7610/9880)| `child`
| | | | | | | **`parent`**| _Equivalent_ <br/>(7614/9884)| `parent`
| | | | | | | **`spouse`**| _Equivalent_ <br/>(7616/9886)| `spouse`
| | | | | | | **`common`**| _Equivalent_ <br/>(7611/9881)| `common`
| | | | | | | **`other`**| _Equivalent_ <br/>(7613/9883)| `other`
| | | | | | | **`self`**| _Equivalent_ <br/>(7615/9885)| `self`
| | | | | | | **`injured`**| _Equivalent_ <br/>(7612/9882)| `injured`
| | | | | | | *7 of 7 codes used* | | *7 of 7 codes used* 

