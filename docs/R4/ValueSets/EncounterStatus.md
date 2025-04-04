Comparison of 
Generated at Friday, April 4, 2025 2:58:44 PM

### EncounterStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | EncounterStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/encounter-status` |
| Version | 4.0.1 |
| Description | Current state of the encounter. |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `2411` |
| Database Concept Count | `9` |
| Database Active Concept Count | `9` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Encounter` | `Encounter.status` | `http://hl7.org/fhir/ValueSet/encounter-status\|4.0.1` | `Required` | planned \| arrived \| triaged \| in-progress \| onleave \| finished \| cancelled + |
| `http://hl7.org/fhir/StructureDefinition/Encounter` | `Encounter.statusHistory.status` | `http://hl7.org/fhir/ValueSet/encounter-status\|4.0.1` | `Required` | planned \| arrived \| triaged \| in-progress \| onleave \| finished \| cancelled + |

### Referenced Systems

* `http://hl7.org/fhir/encounter-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [EncounterState](/docs/R2/ValueSets/EncounterState.md)<br/> `http://hl7.org/fhir/ValueSet/encounter-state\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `76`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `232`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EncounterStatus](/docs/R3/ValueSets/EncounterStatus.md)<br/> `http://hl7.org/fhir/ValueSet/encounter-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `412`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `634`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EncounterStatus](/docs/R4/ValueSets/EncounterStatus.md)<br/> `http://hl7.org/fhir/ValueSet/encounter-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1491`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1492`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EncounterStatus](/docs/R4B/ValueSets/EncounterStatus.md)<br/> `http://hl7.org/fhir/ValueSet/encounter-status\|4.3.0` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `873`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1134`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EncounterStatus](/docs/R5/ValueSets/EncounterStatus.md)<br/> `http://hl7.org/fhir/ValueSet/encounter-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set EncounterStatus from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 EncounterState](/docs/R2/ValueSets/EncounterState.md)| Relationship | [R3 EncounterStatus](/docs/R3/ValueSets/EncounterStatus.md)| Relationship | R4 EncounterStatus| Relationship | [R4B EncounterStatus](/docs/R4B/ValueSets/EncounterStatus.md)| Relationship | [R5 EncounterStatus](/docs/R5/ValueSets/EncounterStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://hl7.org/fhir/encounter-status`
| `planned`| _Equivalent_ <br/>(546/1901)| `planned`| _Equivalent_ <br/>(3667/5952)| **`planned`**| _Equivalent_ <br/>(15852/15853)| `planned`| →→→→ _Equivalent_ →→→→ <br/>(8040)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10340) | `planned`
| `arrived`| _Equivalent_ <br/>(542/1895)| `arrived`| _Equivalent_ <br/>(3663/5948)| **`arrived`**| _Equivalent_ <br/>(15854/15855)| `arrived`| →→→→ _Equivalent_ →→→→ <br/>(8033)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10341) | `planned`
| | | `triaged`| _Equivalent_ <br/>(3662/5947)| **`triaged`**| _Equivalent_ <br/>(15856/15857)| `triaged`| →→→→ _Equivalent_ →→→→ <br/>(8041)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10346) | `in-progress`
| `in-progress`| _Equivalent_ <br/>(547/1899)| `in-progress`| _Equivalent_ <br/>(3669/5954)| **`in-progress`**| _Equivalent_ <br/>(15858/15859)| `in-progress`| →→→→ _Equivalent_ →→→→ <br/>(8038)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10345) | `in-progress`
| `onleave`| _Equivalent_ <br/>(543/1900)| `onleave`| _Equivalent_ <br/>(3664/5949)| **`onleave`**| _Equivalent_ <br/>(15860/15861)| `onleave`| _Equivalent_ <br/>(8039/10347)| `on-hold`
| `finished`| _Equivalent_ <br/>(545/1898)| `finished`| _Equivalent_ <br/>(3666/5951)| **`finished`**| _Equivalent_ <br/>(15862/15863)| `finished`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(8037)<hr/>←←←← _Equivalent_ ←←←← <br/>(10338) | `discharged`
| `finished`| _Equivalent_ <br/>(545/1898)| `finished`| _Equivalent_ <br/>(3666/5951)| **`finished`**| _Equivalent_ <br/>(15862/15863)| `finished`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(8036)<hr/>←←←← _Equivalent_ ←←←← <br/>(10342) | `completed`
| `cancelled`| _Equivalent_ <br/>(544/1896)| `cancelled`| _Equivalent_ <br/>(3665/5950)| **`cancelled`**| _Equivalent_ <br/>(15864/15865)| `cancelled`| _Equivalent_ <br/>(8034/10339)| `cancelled`
| | | `entered-in-error`| _Equivalent_ <br/>(3668/5953)| **`entered-in-error`**| _Equivalent_ <br/>(15866/15867)| `entered-in-error`| _Equivalent_ <br/>(8035/10344)| `entered-in-error`
| | | `unknown`| _Equivalent_ <br/>(3670/5955)| **`unknown`**| _Equivalent_ <br/>(15868/15869)| `unknown`| _Equivalent_ <br/>(8042/10348)| `unknown`
| *6 of 6 codes used* | | *9 of 9 codes used* | | *9 of 9 codes used* | | *9 of 9 codes used* | | *8 of 9 codes used* <br/>remaining codes:<br/>`discontinued`

