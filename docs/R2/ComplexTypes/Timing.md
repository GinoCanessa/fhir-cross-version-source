Comparison of 
Generated at Tuesday, April 1, 2025 1:39:07 PM

### Timing

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | Timing |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Timing` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for Timing Type |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `40` |
| Database Snapshot Count | `19` |
| Database Differential Count | `15` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Timing` | `Timing` | `Timing` | Timing | A timing schedule that specifies an event that may occur multiple times | 0..* | Timing |  |  |
| `Timing.code` | `Timing.code` | `code` |  | QD \| QOD \| Q4H \| Q6H \| BID \| TID \| QID \| AM \| PM + | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/timing-abbreviation` |
| `Timing.event` | `Timing.event` | `event` |  | When the event occurs | 0..* | dateTime |  |  |
| `Timing.extension` | `Timing.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Timing.id` | `Timing.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Timing.repeat` | `Timing.repeat` | `repeat` |  | When the event is to occur | 0..1 | Element |  |  |
| `Timing.repeat.bounds[x]` | `Timing.repeat.bounds[x]` | `bounds[x]` |  | Length/Range of lengths, or (Start and/or end) limits | 0..1 | Period, Quantity[http://hl7.org/fhir/StructureDefinition/Duration], Range |  |  |
| `Timing.repeat.count` | `Timing.repeat.count` | `count` |  | Number of times to repeat | 0..1 | integer |  |  |
| `Timing.repeat.duration` | `Timing.repeat.duration` | `duration` |  | How long when it happens | 0..1 | decimal |  |  |
| `Timing.repeat.durationMax` | `Timing.repeat.durationMax` | `durationMax` |  | How long when it happens (Max) | 0..1 | decimal |  |  |
| `Timing.repeat.durationUnits` | `Timing.repeat.durationUnits` | `durationUnits` |  | s \| min \| h \| d \| wk \| mo \| a - unit of time (UCUM) | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/units-of-time` |
| `Timing.repeat.extension` | `Timing.repeat.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Timing.repeat.frequency` | `Timing.repeat.frequency` | `frequency` |  | Event occurs frequency times per period | 0..1 | integer |  |  |
| `Timing.repeat.frequencyMax` | `Timing.repeat.frequencyMax` | `frequencyMax` |  | Event occurs up to frequencyMax times per period | 0..1 | integer |  |  |
| `Timing.repeat.id` | `Timing.repeat.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Timing.repeat.period` | `Timing.repeat.period` | `period` |  | Event occurs frequency times per period | 0..1 | decimal |  |  |
| `Timing.repeat.periodMax` | `Timing.repeat.periodMax` | `periodMax` |  | Upper limit of period (3-4 hours) | 0..1 | decimal |  |  |
| `Timing.repeat.periodUnits` | `Timing.repeat.periodUnits` | `periodUnits` |  | s \| min \| h \| d \| wk \| mo \| a - unit of time (UCUM) | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/units-of-time` |
| `Timing.repeat.when` | `Timing.repeat.when` | `when` |  | Regular life events the event is tied to | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/event-timing` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Timing](/docs/R2/ComplexTypes/Timing.md)<br/> `http://hl7.org/fhir/StructureDefinition/Timing\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `71`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `237`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Timing](/docs/R3/ComplexTypes/Timing.md)<br/> `http://hl7.org/fhir/StructureDefinition/Timing\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `412`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `608`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Timing](/docs/R4/ComplexTypes/Timing.md)<br/> `http://hl7.org/fhir/StructureDefinition/Timing\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1381`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1382`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Timing](/docs/R4B/ComplexTypes/Timing.md)<br/> `http://hl7.org/fhir/StructureDefinition/Timing\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `923`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1152`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Timing](/docs/R5/ComplexTypes/Timing.md)<br/> `http://hl7.org/fhir/StructureDefinition/Timing\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Timing from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 Timing| Relationship | [R3 Timing](/docs/R3/ComplexTypes/Timing.md)| Relationship | [R4 Timing](/docs/R4/ComplexTypes/Timing.md)| Relationship | [R4B Timing](/docs/R4B/ComplexTypes/Timing.md)| Relationship | [R5 Timing](/docs/R5/ComplexTypes/Timing.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`Timing`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(2861)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2862)| `Timing`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9813)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(9814)| `Timing`| _Equivalent_<br/>(21291/21292)| `Timing`| _Equivalent_<br/>(36357/36358)| `Timing`
| **`Timing.id`**| _Equivalent_<br/>(2863/2864)| `Timing.id`| _Equivalent_<br/>(9815/9816)| `Timing.id`| _Equivalent_<br/>(21293/21294)| `Timing.id`| _Equivalent_<br/>(36359/36360)| `Timing.id`
| **`Timing.extension`**| _Equivalent_<br/>(2865/2866)| `Timing.extension`| _Equivalent_<br/>(9817/9818)| `Timing.extension`| _Equivalent_<br/>(21295/21296)| `Timing.extension`| _Equivalent_<br/>(36361/36362)| `Timing.extension`
| **`Timing.event`**| _Equivalent_<br/>(2867/2868)| `Timing.event`| _Equivalent_<br/>(9819/9820)| `Timing.event`| _Equivalent_<br/>(21299/21300)| `Timing.event`| _Equivalent_<br/>(36365/36366)| `Timing.event`
| **`Timing.repeat`**| _Equivalent_<br/>(2869/2870)| `Timing.repeat`| _Equivalent_<br/>(9821/9822)| `Timing.repeat`| _Equivalent_<br/>(21301/21302)| `Timing.repeat`| _Equivalent_<br/>(36367/36368)| `Timing.repeat`
| **`Timing.repeat.id`**| _Equivalent_<br/>(2871/2872)| `Timing.repeat.id`| _Equivalent_<br/>(9823/9824)| `Timing.repeat.id`| _Equivalent_<br/>(21303/21304)| `Timing.repeat.id`| _Equivalent_<br/>(36369/36370)| `Timing.repeat.id`
| **`Timing.repeat.extension`**| _Equivalent_<br/>(2873/2874)| `Timing.repeat.extension`| _Equivalent_<br/>(9825/9826)| `Timing.repeat.extension`| _Equivalent_<br/>(21305/21306)| `Timing.repeat.extension`| _Equivalent_<br/>(36371/36372)| `Timing.repeat.extension`
| **`Timing.repeat.bounds[x]`**| →→→→ _RelatedTo_ →→→→ <br/>(2875)<hr/>←←←← _RelatedTo_ ←←←← <br/>(2876)| `Timing.repeat.bounds[x]`| _Equivalent_<br/>(9827/9828)| `Timing.repeat.bounds[x]`| _Equivalent_<br/>(21307/21308)| `Timing.repeat.bounds[x]`| _Equivalent_<br/>(36373/36374)| `Timing.repeat.bounds[x]`
| **`Timing.repeat.count`**| _Equivalent_<br/>(2877/2878)| `Timing.repeat.count`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9829)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(9830)| `Timing.repeat.count`| _Equivalent_<br/>(21309/21310)| `Timing.repeat.count`| _Equivalent_<br/>(36375/36376)| `Timing.repeat.count`
| **`Timing.repeat.duration`**| _Equivalent_<br/>(2879/2880)| `Timing.repeat.duration`| _Equivalent_<br/>(9833/9834)| `Timing.repeat.duration`| _Equivalent_<br/>(21313/21314)| `Timing.repeat.duration`| _Equivalent_<br/>(36379/36380)| `Timing.repeat.duration`
| **`Timing.repeat.durationMax`**| _Equivalent_<br/>(2881/2882)| `Timing.repeat.durationMax`| _Equivalent_<br/>(9835/9836)| `Timing.repeat.durationMax`| _Equivalent_<br/>(21315/21316)| `Timing.repeat.durationMax`| _Equivalent_<br/>(36381/36382)| `Timing.repeat.durationMax`
| **`Timing.repeat.durationUnits`**| _Equivalent_<br/>(438/782)| `Timing.repeat.durationUnit`| _Equivalent_<br/>(9837/9838)| `Timing.repeat.durationUnit`| _Equivalent_<br/>(21317/21318)| `Timing.repeat.durationUnit`| _Equivalent_<br/>(36383/36384)| `Timing.repeat.durationUnit`
| **`Timing.repeat.frequency`**| _Equivalent_<br/>(2883/2884)| `Timing.repeat.frequency`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9839)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(9840)| `Timing.repeat.frequency`| _Equivalent_<br/>(21319/21320)| `Timing.repeat.frequency`| _Equivalent_<br/>(36385/36386)| `Timing.repeat.frequency`
| **`Timing.repeat.frequencyMax`**| _Equivalent_<br/>(2885/2886)| `Timing.repeat.frequencyMax`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9841)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(9842)| `Timing.repeat.frequencyMax`| _Equivalent_<br/>(21321/21322)| `Timing.repeat.frequencyMax`| _Equivalent_<br/>(36387/36388)| `Timing.repeat.frequencyMax`
| **`Timing.repeat.period`**| _Equivalent_<br/>(2887/2888)| `Timing.repeat.period`| _Equivalent_<br/>(9843/9844)| `Timing.repeat.period`| _Equivalent_<br/>(21323/21324)| `Timing.repeat.period`| _Equivalent_<br/>(36389/36390)| `Timing.repeat.period`
| **`Timing.repeat.periodMax`**| _Equivalent_<br/>(2889/2890)| `Timing.repeat.periodMax`| _Equivalent_<br/>(9845/9846)| `Timing.repeat.periodMax`| _Equivalent_<br/>(21325/21326)| `Timing.repeat.periodMax`| _Equivalent_<br/>(36391/36392)| `Timing.repeat.periodMax`
| **`Timing.repeat.periodUnits`**| _Equivalent_<br/>(439/783)| `Timing.repeat.periodUnit`| _Equivalent_<br/>(9847/9848)| `Timing.repeat.periodUnit`| _Equivalent_<br/>(21327/21328)| `Timing.repeat.periodUnit`| _Equivalent_<br/>(36393/36394)| `Timing.repeat.periodUnit`
| **`Timing.repeat.when`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(2891)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2892)| `Timing.repeat.when`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9853)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(9854)| `Timing.repeat.when`| _Equivalent_<br/>(21333/21334)| `Timing.repeat.when`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36399)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(36400)| `Timing.repeat.when`
| **`Timing.code`**| _Equivalent_<br/>(2893/2894)| `Timing.code`| _Equivalent_<br/>(9857/9858)| `Timing.code`| _Equivalent_<br/>(21337/21338)| `Timing.code`| _Equivalent_<br/>(36403/36404)| `Timing.code`
| *19 of 19 elements used* | | *19 of 23 elements used* | | *19 of 24 elements used* | | *19 of 24 elements used* | | *19 of 24 elements used* 

