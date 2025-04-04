Comparison of 
Generated at Friday, April 4, 2025 2:58:31 PM

### EventTiming

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | EventTiming |
| Canonical URL | `http://hl7.org/fhir/ValueSet/event-timing` |
| Version | 1.0.2 |
| Description | Real world event that the relating to the schedule. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `158` |
| Database Concept Count | `14` |
| Database Active Concept Count | `14` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Timing` | `Timing.repeat.when` | `http://hl7.org/fhir/ValueSet/event-timing` | `Required` | Regular life events the event is tied to |

### Referenced Systems

* `http://hl7.org/fhir/v3/TimingEvent`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [EventTiming](/docs/R2/ValueSets/EventTiming.md)<br/> `http://hl7.org/fhir/ValueSet/event-timing\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `152`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `310`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EventTiming](/docs/R3/ValueSets/EventTiming.md)<br/> `http://hl7.org/fhir/ValueSet/event-timing\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `523`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `744`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EventTiming](/docs/R4/ValueSets/EventTiming.md)<br/> `http://hl7.org/fhir/ValueSet/event-timing\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1501`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1502`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EventTiming](/docs/R4B/ValueSets/EventTiming.md)<br/> `http://hl7.org/fhir/ValueSet/event-timing\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1005`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1266`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EventTiming](/docs/R5/ValueSets/EventTiming.md)<br/> `http://hl7.org/fhir/ValueSet/event-timing\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set EventTiming from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 EventTiming| Relationship | [R3 EventTiming](/docs/R3/ValueSets/EventTiming.md)| Relationship | [R4 EventTiming](/docs/R4/ValueSets/EventTiming.md)| Relationship | [R4B EventTiming](/docs/R4B/ValueSets/EventTiming.md)| Relationship | [R5 EventTiming](/docs/R5/ValueSets/EventTiming.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/v3/TimingEvent`
| **`HS`**| _Equivalent_ <br/>(1313/2764)| `HS`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4883)<hr/>←←←← __ ←←←← <br/>() | `HS`| _Equivalent_ <br/>(15940/15941)| `HS`| _Equivalent_ <br/>(9484/11823)| `HS`
| **`HS`**| _Equivalent_ <br/>(1313/2764)| `HS`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4909)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7227) | `HS`| _Equivalent_ <br/>(15940/15941)| `HS`| _Equivalent_ <br/>(9484/11823)| `HS`
| **`WAKE`**| _Equivalent_ <br/>(1318/2769)| `WAKE`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4892)<hr/>←←←← __ ←←←← <br/>() | `WAKE`| _Equivalent_ <br/>(15942/15943)| `WAKE`| _Equivalent_ <br/>(9489/11828)| `WAKE`
| **`WAKE`**| _Equivalent_ <br/>(1318/2769)| `WAKE`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4897)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7236) | `WAKE`| _Equivalent_ <br/>(15942/15943)| `WAKE`| _Equivalent_ <br/>(9489/11828)| `WAKE`
| **`C`**| _Equivalent_ <br/>(1309/2760)| `C`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4895)<hr/>←←←← __ ←←←← <br/>() | `C`| _Equivalent_ <br/>(15944/15945)| `C`| _Equivalent_ <br/>(9480/11819)| `C`
| **`C`**| _Equivalent_ <br/>(1309/2760)| `C`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4896)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7239) | `C`| _Equivalent_ <br/>(15944/15945)| `C`| _Equivalent_ <br/>(9480/11819)| `C`
| **`CM`**| _Equivalent_ <br/>(1311/2762)| `CM`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4889)<hr/>←←←← __ ←←←← <br/>() | `CM`| _Equivalent_ <br/>(15946/15947)| `CM`| _Equivalent_ <br/>(9482/11821)| `CM`
| **`CM`**| _Equivalent_ <br/>(1311/2762)| `CM`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4908)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7233) | `CM`| _Equivalent_ <br/>(15946/15947)| `CM`| _Equivalent_ <br/>(9482/11821)| `CM`
| **`CD`**| _Equivalent_ <br/>(1310/2761)| `CD`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4882)<hr/>←←←← __ ←←←← <br/>() | `CD`| _Equivalent_ <br/>(15948/15949)| `CD`| _Equivalent_ <br/>(9481/11820)| `CD`
| **`CD`**| _Equivalent_ <br/>(1310/2761)| `CD`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4904)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7226) | `CD`| _Equivalent_ <br/>(15948/15949)| `CD`| _Equivalent_ <br/>(9481/11820)| `CD`
| **`CV`**| _Equivalent_ <br/>(1312/2763)| `CV`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4893)<hr/>←←←← __ ←←←← <br/>() | `CV`| _Equivalent_ <br/>(15950/15951)| `CV`| _Equivalent_ <br/>(9483/11822)| `CV`
| **`CV`**| _Equivalent_ <br/>(1312/2763)| `CV`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4899)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7237) | `CV`| _Equivalent_ <br/>(15950/15951)| `CV`| _Equivalent_ <br/>(9483/11822)| `CV`
| **`AC`**| _Equivalent_ <br/>(1305/2756)| `AC`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4890)<hr/>←←←← __ ←←←← <br/>() | `AC`| _Equivalent_ <br/>(15952/15953)| `AC`| _Equivalent_ <br/>(9476/11815)| `AC`
| **`AC`**| _Equivalent_ <br/>(1305/2756)| `AC`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4907)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7234) | `AC`| _Equivalent_ <br/>(15952/15953)| `AC`| _Equivalent_ <br/>(9476/11815)| `AC`
| **`ACM`**| _Equivalent_ <br/>(1307/2758)| `ACM`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4888)<hr/>←←←← __ ←←←← <br/>() | `ACM`| _Equivalent_ <br/>(15954/15955)| `ACM`| _Equivalent_ <br/>(9478/11817)| `ACM`
| **`ACM`**| _Equivalent_ <br/>(1307/2758)| `ACM`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4903)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7232) | `ACM`| _Equivalent_ <br/>(15954/15955)| `ACM`| _Equivalent_ <br/>(9478/11817)| `ACM`
| **`ACD`**| _Equivalent_ <br/>(1306/2757)| `ACD`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4891)<hr/>←←←← __ ←←←← <br/>() | `ACD`| _Equivalent_ <br/>(15956/15957)| `ACD`| _Equivalent_ <br/>(9477/11816)| `ACD`
| **`ACD`**| _Equivalent_ <br/>(1306/2757)| `ACD`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4898)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7235) | `ACD`| _Equivalent_ <br/>(15956/15957)| `ACD`| _Equivalent_ <br/>(9477/11816)| `ACD`
| **`ACV`**| _Equivalent_ <br/>(1308/2759)| `ACV`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4884)<hr/>←←←← __ ←←←← <br/>() | `ACV`| _Equivalent_ <br/>(15958/15959)| `ACV`| _Equivalent_ <br/>(9479/11818)| `ACV`
| **`ACV`**| _Equivalent_ <br/>(1308/2759)| `ACV`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4901)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7228) | `ACV`| _Equivalent_ <br/>(15958/15959)| `ACV`| _Equivalent_ <br/>(9479/11818)| `ACV`
| **`PC`**| _Equivalent_ <br/>(1314/2765)| `PC`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4894)<hr/>←←←← __ ←←←← <br/>() | `PC`| _Equivalent_ <br/>(15960/15961)| `PC`| _Equivalent_ <br/>(9485/11824)| `PC`
| **`PC`**| _Equivalent_ <br/>(1314/2765)| `PC`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4902)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7238) | `PC`| _Equivalent_ <br/>(15960/15961)| `PC`| _Equivalent_ <br/>(9485/11824)| `PC`
| **`PCM`**| _Equivalent_ <br/>(1316/2767)| `PCM`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4887)<hr/>←←←← __ ←←←← <br/>() | `PCM`| _Equivalent_ <br/>(15962/15963)| `PCM`| _Equivalent_ <br/>(9487/11826)| `PCM`
| **`PCM`**| _Equivalent_ <br/>(1316/2767)| `PCM`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4906)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7231) | `PCM`| _Equivalent_ <br/>(15962/15963)| `PCM`| _Equivalent_ <br/>(9487/11826)| `PCM`
| **`PCD`**| _Equivalent_ <br/>(1315/2766)| `PCD`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4885)<hr/>←←←← __ ←←←← <br/>() | `PCD`| _Equivalent_ <br/>(15964/15965)| `PCD`| _Equivalent_ <br/>(9486/11825)| `PCD`
| **`PCD`**| _Equivalent_ <br/>(1315/2766)| `PCD`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4900)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7229) | `PCD`| _Equivalent_ <br/>(15964/15965)| `PCD`| _Equivalent_ <br/>(9486/11825)| `PCD`
| **`PCV`**| _Equivalent_ <br/>(1317/2768)| `PCV`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4886)<hr/>←←←← __ ←←←← <br/>() | `PCV`| _Equivalent_ <br/>(15966/15967)| `PCV`| _Equivalent_ <br/>(9488/11827)| `PCV`
| **`PCV`**| _Equivalent_ <br/>(1317/2768)| `PCV`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4905)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7230) | `PCV`| _Equivalent_ <br/>(15966/15967)| `PCV`| _Equivalent_ <br/>(9488/11827)| `PCV`
| *14 of 14 codes used* | | *14 of 19 codes used* <br/>remaining codes:<br/>`AFT`, `EVE`, `MORN`, `NIGHT`, `PHS`| | *14 of 26 codes used* <br/>remaining codes:<br/>`AFT`, `AFT.early`, `AFT.late`, `EVE`, `EVE.early`, `EVE.late`, `MORN`, `MORN.early`, `MORN.late`, `NIGHT`, `NOON`, `PHS`| | *14 of 26 codes used* <br/>remaining codes:<br/>`AFT`, `AFT.early`, `AFT.late`, `EVE`, `EVE.early`, `EVE.late`, `MORN`, `MORN.early`, `MORN.late`, `NIGHT`, `NOON`, `PHS`| | *14 of 27 codes used* <br/>remaining codes:<br/>`AFT`, `AFT.early`, `AFT.late`, `EVE`, `EVE.early`, `EVE.late`, `IMD`, `MORN`, `MORN.early`, `MORN.late`, `NIGHT`, `NOON`, `PHS`

