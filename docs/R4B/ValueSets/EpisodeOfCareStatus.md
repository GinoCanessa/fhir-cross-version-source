Comparison of 
Generated at Thursday, April 3, 2025 8:18:24 AM

### EpisodeOfCareStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | EpisodeOfCareStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/episode-of-care-status` |
| Version | 4.3.0 |
| Description | The status of the episode of care. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `3748` |
| Database Concept Count | `7` |
| Database Active Concept Count | `7` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/EpisodeOfCare` | `EpisodeOfCare.status` | `http://hl7.org/fhir/ValueSet/episode-of-care-status\|4.3.0` | `Required` | planned \| waitlist \| active \| onhold \| finished \| cancelled \| entered-in-error |
| `http://hl7.org/fhir/StructureDefinition/EpisodeOfCare` | `EpisodeOfCare.statusHistory.status` | `http://hl7.org/fhir/ValueSet/episode-of-care-status\|4.3.0` | `Required` | planned \| waitlist \| active \| onhold \| finished \| cancelled \| entered-in-error |

### Referenced Systems

* `http://hl7.org/fhir/episode-of-care-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [EpisodeOfCareStatus](/docs/R2/ValueSets/EpisodeOfCareStatus.md)<br/> `http://hl7.org/fhir/ValueSet/episode-of-care-status\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `77`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `233`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EpisodeOfCareStatus](/docs/R3/ValueSets/EpisodeOfCareStatus.md)<br/> `http://hl7.org/fhir/ValueSet/episode-of-care-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `416`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `638`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EpisodeOfCareStatus](/docs/R4/ValueSets/EpisodeOfCareStatus.md)<br/> `http://hl7.org/fhir/ValueSet/episode-of-care-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1495`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1496`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EpisodeOfCareStatus](/docs/R4B/ValueSets/EpisodeOfCareStatus.md)<br/> `http://hl7.org/fhir/ValueSet/episode-of-care-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `877`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1138`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EpisodeOfCareStatus](/docs/R5/ValueSets/EpisodeOfCareStatus.md)<br/> `http://hl7.org/fhir/ValueSet/episode-of-care-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set EpisodeOfCareStatus from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 EpisodeOfCareStatus](/docs/R2/ValueSets/EpisodeOfCareStatus.md)| Relationship | [R3 EpisodeOfCareStatus](/docs/R3/ValueSets/EpisodeOfCareStatus.md)| Relationship | [R4 EpisodeOfCareStatus](/docs/R4/ValueSets/EpisodeOfCareStatus.md)| Relationship | R4B EpisodeOfCareStatus| Relationship | [R5 EpisodeOfCareStatus](/docs/R5/ValueSets/EpisodeOfCareStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://hl7.org/fhir/episode-of-care-status`
| `planned`| _Equivalent_ <br/>(553/1909)| `planned`| _Equivalent_ <br/>(3700/5985)| `planned`| _Equivalent_ <br/>(15882/15883)| **`planned`**| _Equivalent_ <br/>(8062/10367)| `planned`
| `waitlist`| _Equivalent_ <br/>(549/1910)| `waitlist`| _Equivalent_ <br/>(3696/5981)| `waitlist`| _Equivalent_ <br/>(15884/15885)| **`waitlist`**| _Equivalent_ <br/>(8058/10363)| `waitlist`
| `active`| _Equivalent_ <br/>(550/1904)| `active`| _Equivalent_ <br/>(3697/5982)| `active`| _Equivalent_ <br/>(15886/15887)| **`active`**| _Equivalent_ <br/>(8059/10364)| `active`
| `onhold`| _Equivalent_ <br/>(548/1908)| `onhold`| _Equivalent_ <br/>(3695/5980)| `onhold`| _Equivalent_ <br/>(15888/15889)| **`onhold`**| _Equivalent_ <br/>(8057/10362)| `onhold`
| `finished`| _Equivalent_ <br/>(552/1907)| `finished`| _Equivalent_ <br/>(3699/5984)| `finished`| _Equivalent_ <br/>(15890/15891)| **`finished`**| _Equivalent_ <br/>(8061/10366)| `finished`
| `cancelled`| _Equivalent_ <br/>(551/1905)| `cancelled`| _Equivalent_ <br/>(3698/5983)| `cancelled`| _Equivalent_ <br/>(15892/15893)| **`cancelled`**| _Equivalent_ <br/>(8060/10365)| `cancelled`
| | | `entered-in-error`| _Equivalent_ <br/>(3701/5986)| `entered-in-error`| _Equivalent_ <br/>(15894/15895)| **`entered-in-error`**| _Equivalent_ <br/>(8063/10368)| `entered-in-error`
| *6 of 6 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* 

