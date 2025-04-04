Comparison of 
Generated at Friday, April 4, 2025 2:58:44 PM

### CarePlanActivityStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | CarePlanActivityStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/care-plan-activity-status` |
| Version | 4.0.1 |
| Description | Codes that reflect the current state of a care plan activity within its overall life cycle. |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `2249` |
| Database Concept Count | `9` |
| Database Active Concept Count | `9` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/CarePlan` | `CarePlan.activity.detail.status` | `http://hl7.org/fhir/ValueSet/care-plan-activity-status\|4.0.1` | `Required` | not-started \| scheduled \| in-progress \| on-hold \| completed \| cancelled \| stopped \| unknown \| entered-in-error |

### Referenced Systems

* `http://hl7.org/fhir/care-plan-activity-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [CarePlanActivityStatus](/docs/R2/ValueSets/CarePlanActivityStatus.md)<br/> `http://hl7.org/fhir/ValueSet/care-plan-activity-status\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `46`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `205`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CarePlanActivityStatus](/docs/R3/ValueSets/CarePlanActivityStatus.md)<br/> `http://hl7.org/fhir/ValueSet/care-plan-activity-status\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `375`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `598`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CarePlanActivityStatus](/docs/R4/ValueSets/CarePlanActivityStatus.md)<br/> `http://hl7.org/fhir/ValueSet/care-plan-activity-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1405`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1406`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CarePlanActivityStatus](/docs/R4B/ValueSets/CarePlanActivityStatus.md)<br/> `http://hl7.org/fhir/ValueSet/care-plan-activity-status\|4.3.0` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set CarePlanActivityStatus from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 CarePlanActivityStatus](/docs/R2/ValueSets/CarePlanActivityStatus.md)| Relationship | [R3 CarePlanActivityStatus](/docs/R3/ValueSets/CarePlanActivityStatus.md)| Relationship | R4 CarePlanActivityStatus| Relationship | [R4B CarePlanActivityStatus](/docs/R4B/ValueSets/CarePlanActivityStatus.md)| Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://hl7.org/fhir/care-plan-activity-status`
| `not-started`| _Equivalent_ <br/>(217/1586)| `not-started`| _Equivalent_ <br/>(3134/5345)| **`not-started`**| _Equivalent_ <br/>(14602/14603)| `not-started`| | | 
| `scheduled`| _Equivalent_ <br/>(216/1588)| `scheduled`| _Equivalent_ <br/>(3133/5347)| **`scheduled`**| _Equivalent_ <br/>(14604/14605)| `scheduled`| | | 
| `in-progress`| _Equivalent_ <br/>(220/1585)| `in-progress`| _Equivalent_ <br/>(3137/5344)| **`in-progress`**| _Equivalent_ <br/>(14606/14607)| `in-progress`| | | 
| `on-hold`| _Equivalent_ <br/>(221/1587)| `on-hold`| _Equivalent_ <br/>(3138/5346)| **`on-hold`**| _Equivalent_ <br/>(14608/14609)| `on-hold`| | | 
| `completed`| _Equivalent_ <br/>(219/1584)| `completed`| _Equivalent_ <br/>(3136/5342)| **`completed`**| _Equivalent_ <br/>(14610/14611)| `completed`| | | 
| `cancelled`| _Equivalent_ <br/>(218/1583)| `cancelled`| _Equivalent_ <br/>(3135/5341)| **`cancelled`**| _Equivalent_ <br/>(14612/14613)| `cancelled`| | | 
| | | | | **`stopped`**| _Equivalent_ <br/>(14614/14615)| `stopped`| | | 
| | | `unknown`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3139)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5349) | **`unknown`**| _Equivalent_ <br/>(14616/14617)| `unknown`| | | 
| | | | | **`entered-in-error`**| _Equivalent_ <br/>(14618/14619)| `entered-in-error`| | | 
| *6 of 6 codes used* | | *7 of 7 codes used* | | *9 of 9 codes used* | | *9 of 9 codes used* | | 

