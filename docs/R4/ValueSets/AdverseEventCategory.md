Comparison of 
Generated at Thursday, April 3, 2025 8:18:16 AM

### AdverseEventCategory

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | AdverseEventCategory |
| Canonical URL | `http://hl7.org/fhir/ValueSet/adverse-event-category` |
| Version | 4.0.1 |
| Description | Overall categorization of the event, e.g. product-related or situational. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2196` |
| Database Concept Count | `14` |
| Database Active Concept Count | `14` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/AdverseEvent` | `AdverseEvent.category` | `http://hl7.org/fhir/ValueSet/adverse-event-category` | `Extensible` | product-problem \| product-quality \| product-use-error \| wrong-dose \| incorrect-prescribing-information \| wrong-technique \| wrong-route-of-administration \| wrong-rate \| wrong-duration \| wrong-time \| expired-drug \| medical-device-use-error \| problem-different-manufacturer \| unsafe-physical-environment |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/adverse-event-category`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [AdverseEventCategory](/docs/R3/ValueSets/AdverseEventCategory.md)<br/> `http://hl7.org/fhir/ValueSet/adverse-event-category\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `326`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `548`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AdverseEventCategory](/docs/R4/ValueSets/AdverseEventCategory.md)<br/> `http://hl7.org/fhir/ValueSet/adverse-event-category\|4.0.1` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set AdverseEventCategory from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | [R3 AdverseEventCategory](/docs/R3/ValueSets/AdverseEventCategory.md)| Relationship | R4 AdverseEventCategory| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://terminology.hl7.org/CodeSystem/adverse-event-category`
| | | | | **`product-problem`**| | | | | 
| | | | | **`product-quality`**| | | | | 
| | | | | **`product-use-error`**| | | | | 
| | | | | **`wrong-dose`**| | | | | 
| | | | | **`incorrect-prescribing-information`**| | | | | 
| | | | | **`wrong-technique`**| | | | | 
| | | | | **`wrong-route-of-administration`**| | | | | 
| | | | | **`wrong-rate`**| | | | | 
| | | | | **`wrong-duration`**| | | | | 
| | | | | **`wrong-time`**| | | | | 
| | | | | **`expired-drug`**| | | | | 
| | | | | **`medical-device-use-error`**| | | | | 
| | | | | **`problem-different-manufacturer`**| | | | | 
| | | | | **`unsafe-physical-environment`**| | | | | 
| | | *0 of 2 codes used* <br/>remaining codes:<br/>`AE`, `PAE`| | *14 of 14 codes used* | | | | 

