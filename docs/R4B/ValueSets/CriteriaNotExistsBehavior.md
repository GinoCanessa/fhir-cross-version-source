Comparison of 
Generated at Friday, April 4, 2025 2:58:52 PM

### CriteriaNotExistsBehavior

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | CriteriaNotExistsBehavior |
| Canonical URL | `http://hl7.org/fhir/ValueSet/subscriptiontopic-cr-behavior` |
| Version | 4.3.0 |
| Description | Behavior a server can exhibit when a criteria state does not exist (e.g., state prior to a create or after a delete). |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4125` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/SubscriptionTopic` | `SubscriptionTopic.resourceTrigger.queryCriteria.resultForCreate` | `http://hl7.org/fhir/ValueSet/subscriptiontopic-cr-behavior\|4.3.0` | `Required` | test-passes \| test-fails |
| `http://hl7.org/fhir/StructureDefinition/SubscriptionTopic` | `SubscriptionTopic.resourceTrigger.queryCriteria.resultForDelete` | `http://hl7.org/fhir/ValueSet/subscriptiontopic-cr-behavior\|4.3.0` | `Required` | test-passes \| test-fails |

### Referenced Systems

* `http://hl7.org/fhir/subscriptiontopic-cr-behavior`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [CriteriaNotExistsBehavior](/docs/R4B/ValueSets/CriteriaNotExistsBehavior.md)<br/> `http://hl7.org/fhir/ValueSet/subscriptiontopic-cr-behavior\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `977`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1238`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CriteriaNotExistsBehavior](/docs/R5/ValueSets/CriteriaNotExistsBehavior.md)<br/> `http://hl7.org/fhir/ValueSet/subscriptiontopic-cr-behavior\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set CriteriaNotExistsBehavior from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | R4B CriteriaNotExistsBehavior| Relationship | [R5 CriteriaNotExistsBehavior](/docs/R5/ValueSets/CriteriaNotExistsBehavior.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://hl7.org/fhir/subscriptiontopic-cr-behavior`
| | | | | | | **`test-passes`**| _Equivalent_ <br/>(9327/11665)| `test-passes`
| | | | | | | **`test-fails`**| _Equivalent_ <br/>(9326/11664)| `test-fails`
| | | | | | | *2 of 2 codes used* | | *2 of 2 codes used* 

