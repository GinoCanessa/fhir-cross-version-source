Comparison of 
Generated at Tuesday, April 1, 2025 1:39:33 PM

### InteractionTrigger

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | InteractionTrigger |
| Canonical URL | `http://hl7.org/fhir/ValueSet/interaction-trigger` |
| Version | 5.0.0 |
| Description | FHIR RESTful interaction codes used for SubscriptionTopic trigger. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `4643` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/SubscriptionTopic` | `SubscriptionTopic.resourceTrigger.supportedInteraction` | `http://hl7.org/fhir/ValueSet/interaction-trigger\|5.0.0` | `Required` | create \| update \| delete |

### Referenced Systems

* `http://hl7.org/fhir/restful-interaction`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [InteractionTrigger](/docs/R4B/ValueSets/InteractionTrigger.md)<br/> `http://hl7.org/fhir/ValueSet/interaction-trigger\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `978`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1239`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [InteractionTrigger](/docs/R5/ValueSets/InteractionTrigger.md)<br/> `http://hl7.org/fhir/ValueSet/interaction-trigger\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set InteractionTrigger from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | [R4B InteractionTrigger](/docs/R4B/ValueSets/InteractionTrigger.md)| Relationship | R5 InteractionTrigger
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/restful-interaction`
| | | | | | | `create`| _Equivalent_ <br/>(9330/11668)| **`create`**
| | | | | | | `update`| _Equivalent_ <br/>(9328/11666)| **`update`**
| | | | | | | `delete`| _Equivalent_ <br/>(9329/11667)| **`delete`**
| | | | | | | *3 of 3 codes used* | | *3 of 3 codes used* 

