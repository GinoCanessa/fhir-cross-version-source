Comparison of 
Generated at Thursday, April 3, 2025 8:18:09 AM

### AdverseEventCategory

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | AdverseEventCategory |
| Canonical URL | `http://hl7.org/fhir/ValueSet/adverse-event-category` |
| Version | 3.0.2 |
| Description | Overall categorization of the event, e.g. real or potential |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1042` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/AdverseEvent` | `AdverseEvent.category` | `http://hl7.org/fhir/ValueSet/adverse-event-category` | `Required` | AE \| PAE <br/>An adverse event is an event that caused harm to a patient,  an adverse reaction is a something that is a subject-specific event that is a result of an exposure to a medication, food, device or environmental substance, a potential adverse event is something that occurred and that could have caused harm to a patient but did not |

### Referenced Systems

* `http://hl7.org/fhir/adverse-event-category`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [AdverseEventCategory](/docs/R3/ValueSets/AdverseEventCategory.md)<br/> `http://hl7.org/fhir/ValueSet/adverse-event-category\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `326`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `548`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AdverseEventCategory](/docs/R4/ValueSets/AdverseEventCategory.md)<br/> `http://hl7.org/fhir/ValueSet/adverse-event-category\|4.0.1` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set AdverseEventCategory from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | R3 AdverseEventCategory| Relationship | [R4 AdverseEventCategory](/docs/R4/ValueSets/AdverseEventCategory.md)| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/adverse-event-category`
| | | **`AE`**| | | | | | | 
| | | **`PAE`**| | | | | | | 
| | | *2 of 2 codes used* | | *0 of 14 codes used* <br/>remaining codes:<br/>`expired-drug`, `incorrect-prescribing-information`, `medical-device-use-error`, `problem-different-manufacturer`, `product-problem`, `product-quality`, `product-use-error`, `unsafe-physical-environment`, `wrong-dose`, `wrong-duration`, `wrong-rate`, `wrong-route-of-administration`, `wrong-technique`, `wrong-time`| | | | 

