Comparison of 
Generated at Monday, April 14, 2025 6:17:14 PM

### SubscriptionStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | SubscriptionStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/subscription-status` |
| Version | 1.0.2 |
| Description | The status of a subscription. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `375` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Subscription` | `Subscription.status` | `http://hl7.org/fhir/ValueSet/subscription-status` | `Required` | requested \| active \| error \| off |

### Referenced Systems

* `http://hl7.org/fhir/subscription-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [SubscriptionStatus](/docs/R2/ValueSets/SubscriptionStatus.md)<br/> `http://hl7.org/fhir/ValueSet/subscription-status\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `131`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `289`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [SubscriptionStatus](/docs/R3/ValueSets/SubscriptionStatus.md)<br/> `http://hl7.org/fhir/ValueSet/subscription-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `491`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `714`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [SubscriptionStatus](/docs/R4/ValueSets/SubscriptionStatus.md)<br/> `http://hl7.org/fhir/ValueSet/subscription-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1751`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1752`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [SubscriptionStatusCodes](/docs/R4B/ValueSets/SubscriptionStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/subscription-status\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `974`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1235`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [SubscriptionStatusCodes](/docs/R5/ValueSets/SubscriptionStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/subscription-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set SubscriptionStatus from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 SubscriptionStatus| Relationship | [R3 SubscriptionStatus](/docs/R3/ValueSets/SubscriptionStatus.md)| Relationship | [R4 SubscriptionStatus](/docs/R4/ValueSets/SubscriptionStatus.md)| Relationship | [R4B SubscriptionStatusCodes](/docs/R4B/ValueSets/SubscriptionStatusCodes.md)| Relationship | [R5 SubscriptionStatusCodes](/docs/R5/ValueSets/SubscriptionStatusCodes.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/subscription-status`
| **`requested`**| _Equivalent_ <br/>(1100/2520)| `requested`| _Equivalent_ <br/>(4590/6902)| `requested`| _Equivalent_ <br/>(18246/18247)| `requested`| _Equivalent_ <br/>(9302/11643)| `requested`
| **`active`**| _Equivalent_ <br/>(1101/2521)| `active`| _Equivalent_ <br/>(4591/6903)| `active`| _Equivalent_ <br/>(18248/18249)| `active`| _Equivalent_ <br/>(9303/11639)| `active`
| **`error`**| _Equivalent_ <br/>(1102/2522)| `error`| _Equivalent_ <br/>(4592/6904)| `error`| _Equivalent_ <br/>(18250/18251)| `error`| _Equivalent_ <br/>(9304/11641)| `error`
| **`off`**| _Equivalent_ <br/>(1103/2523)| `off`| _Equivalent_ <br/>(4593/6905)| `off`| _Equivalent_ <br/>(18252/18253)| `off`| _Equivalent_ <br/>(9305/11642)| `off`
| *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 5 codes used* <br/>remaining codes:<br/>`entered-in-error`

