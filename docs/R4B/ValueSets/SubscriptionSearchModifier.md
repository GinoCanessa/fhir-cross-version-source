Comparison of 
Generated at Monday, April 14, 2025 6:17:35 PM

### SubscriptionSearchModifier

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | SubscriptionSearchModifier |
| Canonical URL | `http://hl7.org/fhir/ValueSet/subscription-search-modifier` |
| Version | 4.3.0 |
| Description | FHIR search modifiers allowed for use in Subscriptions and SubscriptionTopics. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `4123` |
| Database Concept Count | `15` |
| Database Active Concept Count | `15` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/SubscriptionTopic` | `SubscriptionTopic.canFilterBy.modifier` | `http://hl7.org/fhir/ValueSet/subscription-search-modifier\|4.3.0` | `Required` | = \| eq \| ne \| gt \| lt \| ge \| le \| sa \| eb \| ap \| above \| below \| in \| not-in \| of-type |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/subscription-search-modifier`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [SubscriptionSearchModifier](/docs/R4B/ValueSets/SubscriptionSearchModifier.md)<br/> `http://hl7.org/fhir/ValueSet/subscription-search-modifier\|4.3.0` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `976`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1237`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [SearchModifierCode](/docs/R5/ValueSets/SearchModifierCode.md)<br/> `http://hl7.org/fhir/ValueSet/search-modifier-code\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set SubscriptionSearchModifier from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | R4B SubscriptionSearchModifier| Relationship | [R5 SearchModifierCode](/docs/R5/ValueSets/SearchModifierCode.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://terminology.hl7.org/CodeSystem/subscription-search-modifier`
| | | | | | | **`=`**| | | 
| | | | | | | **`eq`**| | | 
| | | | | | | **`ne`**| | | 
| | | | | | | **`gt`**| | | 
| | | | | | | **`lt`**| | | 
| | | | | | | **`ge`**| | | 
| | | | | | | **`le`**| | | 
| | | | | | | **`sa`**| | | 
| | | | | | | **`eb`**| | | 
| | | | | | | **`ap`**| | | 
| | | | | | | **`above`**| _Equivalent_ <br/>(9320/11658)| `above`
| | | | | | | **`below`**| _Equivalent_ <br/>(9312/11652)| `below`
| | | | | | | **`in`**| _Equivalent_ <br/>(9313/11651)| `in`
| | | | | | | **`not-in`**| _Equivalent_ <br/>(9322/11659)| `not-in`
| | | | | | | **`of-type`**| _Equivalent_ <br/>(9311/11650)| `of-type`
| | | | | | | *15 of 15 codes used* | | *5 of 15 codes used* <br/>remaining codes:<br/>`code-text`, `contains`, `exact`, `identifier`, `iterate`, `missing`, `not`, `text`, `text-advanced`, `type`

