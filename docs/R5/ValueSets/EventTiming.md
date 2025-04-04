Comparison of 
Generated at Friday, April 4, 2025 2:58:59 PM

### EventTiming

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | EventTiming |
| Canonical URL | `http://hl7.org/fhir/ValueSet/event-timing` |
| Version | 5.0.0 |
| Description | Real-world event relating to the schedule. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `4544` |
| Database Concept Count | `27` |
| Database Active Concept Count | `27` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Timing` | `Timing.repeat.when` | `http://hl7.org/fhir/ValueSet/event-timing\|5.0.0` | `Required` | Code for time period of occurrence |

### Referenced Systems

* `http://hl7.org/fhir/event-timing`
* `http://terminology.hl7.org/CodeSystem/v3-TimingEvent`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [EventTiming](/docs/R2/ValueSets/EventTiming.md)<br/> `http://hl7.org/fhir/ValueSet/event-timing\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `152`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `310`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EventTiming](/docs/R3/ValueSets/EventTiming.md)<br/> `http://hl7.org/fhir/ValueSet/event-timing\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `523`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `744`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EventTiming](/docs/R4/ValueSets/EventTiming.md)<br/> `http://hl7.org/fhir/ValueSet/event-timing\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1501`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1502`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EventTiming](/docs/R4B/ValueSets/EventTiming.md)<br/> `http://hl7.org/fhir/ValueSet/event-timing\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1005`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1266`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EventTiming](/docs/R5/ValueSets/EventTiming.md)<br/> `http://hl7.org/fhir/ValueSet/event-timing\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set EventTiming from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 EventTiming](/docs/R2/ValueSets/EventTiming.md)| Relationship | [R3 EventTiming](/docs/R3/ValueSets/EventTiming.md)| Relationship | [R4 EventTiming](/docs/R4/ValueSets/EventTiming.md)| Relationship | [R4B EventTiming](/docs/R4B/ValueSets/EventTiming.md)| Relationship | R5 EventTiming
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/event-timing`
| | | `MORN`| _Equivalent_ <br/>(4879/7206)| `MORN`| _Equivalent_ <br/>(15916/15917)| `MORN`| _Equivalent_ <br/>(9470/11809)| **`MORN`**
| | | | | `MORN.early`| _Equivalent_ <br/>(15918/15919)| `MORN.early`| _Equivalent_ <br/>(9471/11810)| **`MORN.early`**
| | | | | `MORN.late`| _Equivalent_ <br/>(15920/15921)| `MORN.late`| _Equivalent_ <br/>(9472/11811)| **`MORN.late`**
| | | | | `NOON`| _Equivalent_ <br/>(15922/15923)| `NOON`| _Equivalent_ <br/>(9474/11813)| **`NOON`**
| | | `AFT`| _Equivalent_ <br/>(4877/7200)| `AFT`| _Equivalent_ <br/>(15924/15925)| `AFT`| _Equivalent_ <br/>(9464/11802)| **`AFT`**
| | | | | `AFT.early`| _Equivalent_ <br/>(15926/15927)| `AFT.early`| _Equivalent_ <br/>(9465/11803)| **`AFT.early`**
| | | | | `AFT.late`| _Equivalent_ <br/>(15928/15929)| `AFT.late`| _Equivalent_ <br/>(9466/11804)| **`AFT.late`**
| | | `EVE`| _Equivalent_ <br/>(4878/7203)| `EVE`| _Equivalent_ <br/>(15930/15931)| `EVE`| _Equivalent_ <br/>(9467/11805)| **`EVE`**
| | | | | `EVE.early`| _Equivalent_ <br/>(15932/15933)| `EVE.early`| _Equivalent_ <br/>(9468/11806)| **`EVE.early`**
| | | | | `EVE.late`| _Equivalent_ <br/>(15934/15935)| `EVE.late`| _Equivalent_ <br/>(9469/11807)| **`EVE.late`**
| | | `NIGHT`| _Equivalent_ <br/>(4880/7209)| `NIGHT`| _Equivalent_ <br/>(15936/15937)| `NIGHT`| _Equivalent_ <br/>(9473/11812)| **`NIGHT`**
| | | `PHS`| _Equivalent_ <br/>(4881/7211)| `PHS`| _Equivalent_ <br/>(15938/15939)| `PHS`| _Equivalent_ <br/>(9475/11814)| **`PHS`**
| | | | | | | | | **`IMD`**
| <td colspan="8">**R5** System: `http://terminology.hl7.org/CodeSystem/v3-TimingEvent`
| `HS`| _Equivalent_ <br/>(1313/2764)| `HS`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4909)<hr/>←←←← __ ←←←← <br/>() | `HS`| _Equivalent_ <br/>(15940/15941)| `HS`| _Equivalent_ <br/>(9484/11823)| **`HS`**
| `HS`| _Equivalent_ <br/>(1313/2764)| `HS`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4909)<hr/>←←←← __ ←←←← <br/>() | `HS`| _Equivalent_ <br/>(15940/15941)| `HS`| _Equivalent_ <br/>(9484/11823)| **`HS`**
| `WAKE`| _Equivalent_ <br/>(1318/2769)| `WAKE`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4897)<hr/>←←←← __ ←←←← <br/>() | `WAKE`| _Equivalent_ <br/>(15942/15943)| `WAKE`| _Equivalent_ <br/>(9489/11828)| **`WAKE`**
| `WAKE`| _Equivalent_ <br/>(1318/2769)| `WAKE`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4897)<hr/>←←←← __ ←←←← <br/>() | `WAKE`| _Equivalent_ <br/>(15942/15943)| `WAKE`| _Equivalent_ <br/>(9489/11828)| **`WAKE`**
| `C`| _Equivalent_ <br/>(1309/2760)| `C`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4896)<hr/>←←←← __ ←←←← <br/>() | `C`| _Equivalent_ <br/>(15944/15945)| `C`| _Equivalent_ <br/>(9480/11819)| **`C`**
| `C`| _Equivalent_ <br/>(1309/2760)| `C`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4896)<hr/>←←←← __ ←←←← <br/>() | `C`| _Equivalent_ <br/>(15944/15945)| `C`| _Equivalent_ <br/>(9480/11819)| **`C`**
| `CM`| _Equivalent_ <br/>(1311/2762)| `CM`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4908)<hr/>←←←← __ ←←←← <br/>() | `CM`| _Equivalent_ <br/>(15946/15947)| `CM`| _Equivalent_ <br/>(9482/11821)| **`CM`**
| `CM`| _Equivalent_ <br/>(1311/2762)| `CM`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4908)<hr/>←←←← __ ←←←← <br/>() | `CM`| _Equivalent_ <br/>(15946/15947)| `CM`| _Equivalent_ <br/>(9482/11821)| **`CM`**
| `CD`| _Equivalent_ <br/>(1310/2761)| `CD`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4904)<hr/>←←←← __ ←←←← <br/>() | `CD`| _Equivalent_ <br/>(15948/15949)| `CD`| _Equivalent_ <br/>(9481/11820)| **`CD`**
| `CD`| _Equivalent_ <br/>(1310/2761)| `CD`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4904)<hr/>←←←← __ ←←←← <br/>() | `CD`| _Equivalent_ <br/>(15948/15949)| `CD`| _Equivalent_ <br/>(9481/11820)| **`CD`**
| `CV`| _Equivalent_ <br/>(1312/2763)| `CV`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4899)<hr/>←←←← __ ←←←← <br/>() | `CV`| _Equivalent_ <br/>(15950/15951)| `CV`| _Equivalent_ <br/>(9483/11822)| **`CV`**
| `CV`| _Equivalent_ <br/>(1312/2763)| `CV`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4899)<hr/>←←←← __ ←←←← <br/>() | `CV`| _Equivalent_ <br/>(15950/15951)| `CV`| _Equivalent_ <br/>(9483/11822)| **`CV`**
| `AC`| _Equivalent_ <br/>(1305/2756)| `AC`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4907)<hr/>←←←← __ ←←←← <br/>() | `AC`| _Equivalent_ <br/>(15952/15953)| `AC`| _Equivalent_ <br/>(9476/11815)| **`AC`**
| `AC`| _Equivalent_ <br/>(1305/2756)| `AC`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4907)<hr/>←←←← __ ←←←← <br/>() | `AC`| _Equivalent_ <br/>(15952/15953)| `AC`| _Equivalent_ <br/>(9476/11815)| **`AC`**
| `ACM`| _Equivalent_ <br/>(1307/2758)| `ACM`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4903)<hr/>←←←← __ ←←←← <br/>() | `ACM`| _Equivalent_ <br/>(15954/15955)| `ACM`| _Equivalent_ <br/>(9478/11817)| **`ACM`**
| `ACM`| _Equivalent_ <br/>(1307/2758)| `ACM`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4903)<hr/>←←←← __ ←←←← <br/>() | `ACM`| _Equivalent_ <br/>(15954/15955)| `ACM`| _Equivalent_ <br/>(9478/11817)| **`ACM`**
| `ACD`| _Equivalent_ <br/>(1306/2757)| `ACD`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4898)<hr/>←←←← __ ←←←← <br/>() | `ACD`| _Equivalent_ <br/>(15956/15957)| `ACD`| _Equivalent_ <br/>(9477/11816)| **`ACD`**
| `ACD`| _Equivalent_ <br/>(1306/2757)| `ACD`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4898)<hr/>←←←← __ ←←←← <br/>() | `ACD`| _Equivalent_ <br/>(15956/15957)| `ACD`| _Equivalent_ <br/>(9477/11816)| **`ACD`**
| `ACV`| _Equivalent_ <br/>(1308/2759)| `ACV`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4901)<hr/>←←←← __ ←←←← <br/>() | `ACV`| _Equivalent_ <br/>(15958/15959)| `ACV`| _Equivalent_ <br/>(9479/11818)| **`ACV`**
| `ACV`| _Equivalent_ <br/>(1308/2759)| `ACV`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4901)<hr/>←←←← __ ←←←← <br/>() | `ACV`| _Equivalent_ <br/>(15958/15959)| `ACV`| _Equivalent_ <br/>(9479/11818)| **`ACV`**
| `PC`| _Equivalent_ <br/>(1314/2765)| `PC`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4902)<hr/>←←←← __ ←←←← <br/>() | `PC`| _Equivalent_ <br/>(15960/15961)| `PC`| _Equivalent_ <br/>(9485/11824)| **`PC`**
| `PC`| _Equivalent_ <br/>(1314/2765)| `PC`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4902)<hr/>←←←← __ ←←←← <br/>() | `PC`| _Equivalent_ <br/>(15960/15961)| `PC`| _Equivalent_ <br/>(9485/11824)| **`PC`**
| `PCM`| _Equivalent_ <br/>(1316/2767)| `PCM`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4906)<hr/>←←←← __ ←←←← <br/>() | `PCM`| _Equivalent_ <br/>(15962/15963)| `PCM`| _Equivalent_ <br/>(9487/11826)| **`PCM`**
| `PCM`| _Equivalent_ <br/>(1316/2767)| `PCM`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4906)<hr/>←←←← __ ←←←← <br/>() | `PCM`| _Equivalent_ <br/>(15962/15963)| `PCM`| _Equivalent_ <br/>(9487/11826)| **`PCM`**
| `PCD`| _Equivalent_ <br/>(1315/2766)| `PCD`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4900)<hr/>←←←← __ ←←←← <br/>() | `PCD`| _Equivalent_ <br/>(15964/15965)| `PCD`| _Equivalent_ <br/>(9486/11825)| **`PCD`**
| `PCD`| _Equivalent_ <br/>(1315/2766)| `PCD`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4900)<hr/>←←←← __ ←←←← <br/>() | `PCD`| _Equivalent_ <br/>(15964/15965)| `PCD`| _Equivalent_ <br/>(9486/11825)| **`PCD`**
| `PCV`| _Equivalent_ <br/>(1317/2768)| `PCV`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4905)<hr/>←←←← __ ←←←← <br/>() | `PCV`| _Equivalent_ <br/>(15966/15967)| `PCV`| _Equivalent_ <br/>(9488/11827)| **`PCV`**
| `PCV`| _Equivalent_ <br/>(1317/2768)| `PCV`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4905)<hr/>←←←← __ ←←←← <br/>() | `PCV`| _Equivalent_ <br/>(15966/15967)| `PCV`| _Equivalent_ <br/>(9488/11827)| **`PCV`**
| *14 of 14 codes used* | | *19 of 19 codes used* | | *26 of 26 codes used* | | *26 of 26 codes used* | | *27 of 27 codes used* 

