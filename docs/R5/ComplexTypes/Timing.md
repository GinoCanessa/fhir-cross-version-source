Comparison of 
Generated at Thursday, April 3, 2025 8:18:33 AM

### Timing

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | Timing |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Timing` |
| Version | 5.0.0 |
| Description | Timing Type: Specifies an event that may occur multiple times. Timing schedules are used to record when things are planned, expected or requested to occur. The most common usage is in dosage instructions for medications. They are also used when planning care of various kinds, and may be used for reporting the schedule to which past regular activities were carried out. |
| Status | `Active` |
| Artifact Class | `ComplexType` |
| Database Key | `2244` |
| Database Snapshot Count | `24` |
| Database Differential Count | `19` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Timing` | `Timing` | `Timing` | Timing | A timing schedule that specifies an event that may occur multiple times | 0..* | Timing |  |  |
| `Timing.code` | `Timing.code` | `code` | Timing.code | C \| BID \| TID \| QID \| AM \| PM \| QD \| QOD \| + | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/timing-abbreviation` |
| `Timing.event` | `Timing.event` | `event` | Timing.event | When the event occurs | 0..* | dateTime |  |  |
| `Timing.extension` | `Timing.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Timing.id` | `Timing.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Timing.modifierExtension` | `Timing.modifierExtension` | `modifierExtension` | BackboneType.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Timing.repeat` | `Timing.repeat` | `repeat` | Timing.repeat | When the event is to occur | 0..1 | Element |  |  |
| `Timing.repeat.bounds[x]` | `Timing.repeat.bounds[x]` | `bounds[x]` | Timing.repeat.bounds[x] | Length/Range of lengths, or (Start and/or end) limits | 0..1 | Duration, Period, Range |  |  |
| `Timing.repeat.count` | `Timing.repeat.count` | `count` | Timing.repeat.count | Number of times to repeat | 0..1 | positiveInt |  |  |
| `Timing.repeat.countMax` | `Timing.repeat.countMax` | `countMax` | Timing.repeat.countMax | Maximum number of times to repeat | 0..1 | positiveInt |  |  |
| `Timing.repeat.dayOfWeek` | `Timing.repeat.dayOfWeek` | `dayOfWeek` | Timing.repeat.dayOfWeek | mon \| tue \| wed \| thu \| fri \| sat \| sun | 0..* | code | `Required` | `http://hl7.org/fhir/ValueSet/days-of-week|5.0.0` |
| `Timing.repeat.duration` | `Timing.repeat.duration` | `duration` | Timing.repeat.duration | How long when it happens | 0..1 | decimal |  |  |
| `Timing.repeat.durationMax` | `Timing.repeat.durationMax` | `durationMax` | Timing.repeat.durationMax | How long when it happens (Max) | 0..1 | decimal |  |  |
| `Timing.repeat.durationUnit` | `Timing.repeat.durationUnit` | `durationUnit` | Timing.repeat.durationUnit | s \| min \| h \| d \| wk \| mo \| a - unit of time (UCUM) | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/units-of-time|5.0.0` |
| `Timing.repeat.extension` | `Timing.repeat.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Timing.repeat.frequency` | `Timing.repeat.frequency` | `frequency` | Timing.repeat.frequency | Indicates the number of repetitions that should occur within a period. I.e. Event occurs frequency times per period | 0..1 | positiveInt |  |  |
| `Timing.repeat.frequencyMax` | `Timing.repeat.frequencyMax` | `frequencyMax` | Timing.repeat.frequencyMax | Event occurs up to frequencyMax times per period | 0..1 | positiveInt |  |  |
| `Timing.repeat.id` | `Timing.repeat.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Timing.repeat.offset` | `Timing.repeat.offset` | `offset` | Timing.repeat.offset | Minutes from event (before or after) | 0..1 | unsignedInt |  |  |
| `Timing.repeat.period` | `Timing.repeat.period` | `period` | Timing.repeat.period | The duration to which the frequency applies. I.e. Event occurs frequency times per period | 0..1 | decimal |  |  |
| `Timing.repeat.periodMax` | `Timing.repeat.periodMax` | `periodMax` | Timing.repeat.periodMax | Upper limit of period (3-4 hours) | 0..1 | decimal |  |  |
| `Timing.repeat.periodUnit` | `Timing.repeat.periodUnit` | `periodUnit` | Timing.repeat.periodUnit | s \| min \| h \| d \| wk \| mo \| a - unit of time (UCUM) | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/units-of-time|5.0.0` |
| `Timing.repeat.timeOfDay` | `Timing.repeat.timeOfDay` | `timeOfDay` | Timing.repeat.timeOfDay | Time of day for action | 0..* | time |  |  |
| `Timing.repeat.when` | `Timing.repeat.when` | `when` | Timing.repeat.when | Code for time period of occurrence | 0..* | code | `Required` | `http://hl7.org/fhir/ValueSet/event-timing|5.0.0` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Timing](/docs/R2/ComplexTypes/Timing.md)<br/> `http://hl7.org/fhir/StructureDefinition/Timing\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `71`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `237`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Timing](/docs/R3/ComplexTypes/Timing.md)<br/> `http://hl7.org/fhir/StructureDefinition/Timing\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `412`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `608`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Timing](/docs/R4/ComplexTypes/Timing.md)<br/> `http://hl7.org/fhir/StructureDefinition/Timing\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1381`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1382`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Timing](/docs/R4B/ComplexTypes/Timing.md)<br/> `http://hl7.org/fhir/StructureDefinition/Timing\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `923`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1152`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Timing](/docs/R5/ComplexTypes/Timing.md)<br/> `http://hl7.org/fhir/StructureDefinition/Timing\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Timing from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Timing](/docs/R2/ComplexTypes/Timing.md)| Relationship | [R3 Timing](/docs/R3/ComplexTypes/Timing.md)| Relationship | [R4 Timing](/docs/R4/ComplexTypes/Timing.md)| Relationship | [R4B Timing](/docs/R4B/ComplexTypes/Timing.md)| Relationship | R5 Timing
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `Timing`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(2861)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2862)| `Timing`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9813)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(9814)| `Timing`| _Equivalent_<br/>(21291/21292)| `Timing`| _Equivalent_<br/>(36357/36358)| **`Timing`**
| `Timing.id`| _Equivalent_<br/>(2863/2864)| `Timing.id`| _Equivalent_<br/>(9815/9816)| `Timing.id`| _Equivalent_<br/>(21293/21294)| `Timing.id`| _Equivalent_<br/>(36359/36360)| **`Timing.id`**
| `Timing.extension`| _Equivalent_<br/>(2865/2866)| `Timing.extension`| _Equivalent_<br/>(9817/9818)| `Timing.extension`| _Equivalent_<br/>(21295/21296)| `Timing.extension`| _Equivalent_<br/>(36361/36362)| **`Timing.extension`**
| | | | | `Timing.modifierExtension`| _Equivalent_<br/>(21297/21298)| `Timing.modifierExtension`| _Equivalent_<br/>(36363/36364)| **`Timing.modifierExtension`**
| `Timing.event`| _Equivalent_<br/>(2867/2868)| `Timing.event`| _Equivalent_<br/>(9819/9820)| `Timing.event`| _Equivalent_<br/>(21299/21300)| `Timing.event`| _Equivalent_<br/>(36365/36366)| **`Timing.event`**
| `Timing.repeat`| _Equivalent_<br/>(2869/2870)| `Timing.repeat`| _Equivalent_<br/>(9821/9822)| `Timing.repeat`| _Equivalent_<br/>(21301/21302)| `Timing.repeat`| _Equivalent_<br/>(36367/36368)| **`Timing.repeat`**
| `Timing.repeat.id`| _Equivalent_<br/>(2871/2872)| `Timing.repeat.id`| _Equivalent_<br/>(9823/9824)| `Timing.repeat.id`| _Equivalent_<br/>(21303/21304)| `Timing.repeat.id`| _Equivalent_<br/>(36369/36370)| **`Timing.repeat.id`**
| `Timing.repeat.extension`| _Equivalent_<br/>(2873/2874)| `Timing.repeat.extension`| _Equivalent_<br/>(9825/9826)| `Timing.repeat.extension`| _Equivalent_<br/>(21305/21306)| `Timing.repeat.extension`| _Equivalent_<br/>(36371/36372)| **`Timing.repeat.extension`**
| `Timing.repeat.bounds[x]`| →→→→ _RelatedTo_ →→→→ <br/>(2875)<hr/>←←←← _RelatedTo_ ←←←← <br/>(2876)| `Timing.repeat.bounds[x]`| _Equivalent_<br/>(9827/9828)| `Timing.repeat.bounds[x]`| _Equivalent_<br/>(21307/21308)| `Timing.repeat.bounds[x]`| _Equivalent_<br/>(36373/36374)| **`Timing.repeat.bounds[x]`**
| `Timing.repeat.count`| _Equivalent_<br/>(2877/2878)| `Timing.repeat.count`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9829)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(9830)| `Timing.repeat.count`| _Equivalent_<br/>(21309/21310)| `Timing.repeat.count`| _Equivalent_<br/>(36375/36376)| **`Timing.repeat.count`**
| | | `Timing.repeat.countMax`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9831)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(9832)| `Timing.repeat.countMax`| _Equivalent_<br/>(21311/21312)| `Timing.repeat.countMax`| _Equivalent_<br/>(36377/36378)| **`Timing.repeat.countMax`**
| `Timing.repeat.duration`| _Equivalent_<br/>(2879/2880)| `Timing.repeat.duration`| _Equivalent_<br/>(9833/9834)| `Timing.repeat.duration`| _Equivalent_<br/>(21313/21314)| `Timing.repeat.duration`| _Equivalent_<br/>(36379/36380)| **`Timing.repeat.duration`**
| `Timing.repeat.durationMax`| _Equivalent_<br/>(2881/2882)| `Timing.repeat.durationMax`| _Equivalent_<br/>(9835/9836)| `Timing.repeat.durationMax`| _Equivalent_<br/>(21315/21316)| `Timing.repeat.durationMax`| _Equivalent_<br/>(36381/36382)| **`Timing.repeat.durationMax`**
| `Timing.repeat.durationUnits`| _Equivalent_<br/>(438/782)| `Timing.repeat.durationUnit`| _Equivalent_<br/>(9837/9838)| `Timing.repeat.durationUnit`| _Equivalent_<br/>(21317/21318)| `Timing.repeat.durationUnit`| _Equivalent_<br/>(36383/36384)| **`Timing.repeat.durationUnit`**
| `Timing.repeat.frequency`| _Equivalent_<br/>(2883/2884)| `Timing.repeat.frequency`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9839)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(9840)| `Timing.repeat.frequency`| _Equivalent_<br/>(21319/21320)| `Timing.repeat.frequency`| _Equivalent_<br/>(36385/36386)| **`Timing.repeat.frequency`**
| `Timing.repeat.frequencyMax`| _Equivalent_<br/>(2885/2886)| `Timing.repeat.frequencyMax`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9841)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(9842)| `Timing.repeat.frequencyMax`| _Equivalent_<br/>(21321/21322)| `Timing.repeat.frequencyMax`| _Equivalent_<br/>(36387/36388)| **`Timing.repeat.frequencyMax`**
| `Timing.repeat.period`| _Equivalent_<br/>(2887/2888)| `Timing.repeat.period`| _Equivalent_<br/>(9843/9844)| `Timing.repeat.period`| _Equivalent_<br/>(21323/21324)| `Timing.repeat.period`| _Equivalent_<br/>(36389/36390)| **`Timing.repeat.period`**
| `Timing.repeat.periodMax`| _Equivalent_<br/>(2889/2890)| `Timing.repeat.periodMax`| _Equivalent_<br/>(9845/9846)| `Timing.repeat.periodMax`| _Equivalent_<br/>(21325/21326)| `Timing.repeat.periodMax`| _Equivalent_<br/>(36391/36392)| **`Timing.repeat.periodMax`**
| `Timing.repeat.periodUnits`| _Equivalent_<br/>(439/783)| `Timing.repeat.periodUnit`| _Equivalent_<br/>(9847/9848)| `Timing.repeat.periodUnit`| _Equivalent_<br/>(21327/21328)| `Timing.repeat.periodUnit`| _Equivalent_<br/>(36393/36394)| **`Timing.repeat.periodUnit`**
| | | `Timing.repeat.dayOfWeek`| _Equivalent_<br/>(9849/9850)| `Timing.repeat.dayOfWeek`| _Equivalent_<br/>(21329/21330)| `Timing.repeat.dayOfWeek`| _Equivalent_<br/>(36395/36396)| **`Timing.repeat.dayOfWeek`**
| | | `Timing.repeat.timeOfDay`| _Equivalent_<br/>(9851/9852)| `Timing.repeat.timeOfDay`| _Equivalent_<br/>(21331/21332)| `Timing.repeat.timeOfDay`| _Equivalent_<br/>(36397/36398)| **`Timing.repeat.timeOfDay`**
| `Timing.repeat.when`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(2891)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2892)| `Timing.repeat.when`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9853)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(9854)| `Timing.repeat.when`| _Equivalent_<br/>(21333/21334)| `Timing.repeat.when`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36399)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(36400)| **`Timing.repeat.when`**
| | | `Timing.repeat.offset`| _Equivalent_<br/>(9855/9856)| `Timing.repeat.offset`| _Equivalent_<br/>(21335/21336)| `Timing.repeat.offset`| _Equivalent_<br/>(36401/36402)| **`Timing.repeat.offset`**
| `Timing.code`| _Equivalent_<br/>(2893/2894)| `Timing.code`| _Equivalent_<br/>(9857/9858)| `Timing.code`| _Equivalent_<br/>(21337/21338)| `Timing.code`| _Equivalent_<br/>(36403/36404)| **`Timing.code`**
| *19 of 19 elements used* | | *23 of 23 elements used* | | *24 of 24 elements used* | | *24 of 24 elements used* | | *24 of 24 elements used* 

