Comparison of 
Generated at Thursday, April 3, 2025 8:18:10 AM

### GoalStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | GoalStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/goal-status` |
| Version | 3.0.2 |
| Description | Indicates whether the goal has been met and is still being targeted |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1256` |
| Database Concept Count | `13` |
| Database Active Concept Count | `13` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Goal` | `Goal.status` | `http://hl7.org/fhir/ValueSet/goal-status` | `Required` | proposed \| accepted \| planned \| in-progress \| on-target \| ahead-of-target \| behind-target \| sustaining \| achieved \| on-hold \| cancelled \| entered-in-error \| rejected |

### Referenced Systems

* `http://hl7.org/fhir/goal-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [GoalStatus](/docs/R2/ValueSets/GoalStatus.md)<br/> `http://hl7.org/fhir/ValueSet/goal-status\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `80`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `236`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [GoalStatus](/docs/R3/ValueSets/GoalStatus.md)<br/> `http://hl7.org/fhir/ValueSet/goal-status\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `420`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `642`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [GoalLifecycleStatus](/docs/R4/ValueSets/GoalLifecycleStatus.md)<br/> `http://hl7.org/fhir/ValueSet/goal-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1517`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1518`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [GoalLifecycleStatus](/docs/R4B/ValueSets/GoalLifecycleStatus.md)<br/> `http://hl7.org/fhir/ValueSet/goal-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `893`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1154`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [GoalLifecycleStatus](/docs/R5/ValueSets/GoalLifecycleStatus.md)<br/> `http://hl7.org/fhir/ValueSet/goal-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set GoalStatus from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 GoalStatus](/docs/R2/ValueSets/GoalStatus.md)| Relationship | R3 GoalStatus| Relationship | [R4 GoalLifecycleStatus](/docs/R4/ValueSets/GoalLifecycleStatus.md)| Relationship | [R4B GoalLifecycleStatus](/docs/R4B/ValueSets/GoalLifecycleStatus.md)| Relationship | [R5 GoalLifecycleStatus](/docs/R5/ValueSets/GoalLifecycleStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/goal-status`
| `proposed`| _Equivalent_ <br/>(563/1929)| **`proposed`**| _Equivalent_ <br/>(3724/5999)| `proposed`| _Equivalent_ <br/>(16062/16063)| `proposed`| _Equivalent_ <br/>(8299/10604)| `proposed`
| `accepted`| _Equivalent_ <br/>(565/1919)| **`accepted`**| _Equivalent_ <br/>(3714/6001)| `accepted`| _Equivalent_ <br/>(16066/16067)| `accepted`| _Equivalent_ <br/>(8301/10606)| `accepted`
| `planned`| _Equivalent_ <br/>(568/1928)| **`planned`**| _Equivalent_ <br/>(3723/6007)| `planned`| _Equivalent_ <br/>(16064/16065)| `planned`| _Equivalent_ <br/>(8304/10609)| `planned`
| `in-progress`| _Equivalent_ <br/>(569/1925)| **`in-progress`**| →→→→ _Equivalent_ →→→→ <br/>(3720)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6004) | `active`| _Equivalent_ <br/>(16068/16069)| `active`| _Equivalent_ <br/>(8302/10607)| `active`
| | | **`on-target`**| | | | | | | 
| | | **`ahead-of-target`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3716)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6002) | `active`| _Equivalent_ <br/>(16068/16069)| `active`| _Equivalent_ <br/>(8302/10607)| `active`
| | | **`behind-target`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3717)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6003) | `active`| _Equivalent_ <br/>(16068/16069)| `active`| _Equivalent_ <br/>(8302/10607)| `active`
| `sustaining`| _Equivalent_ <br/>(562/1931)| **`sustaining`**| →→→→ _Equivalent_ →→→→ <br/>(3726)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6005) | `active`| _Equivalent_ <br/>(16068/16069)| `active`| _Equivalent_ <br/>(8302/10607)| `active`
| `achieved`| _Equivalent_ <br/>(566/1920)| **`achieved`**| _Equivalent_ <br/>(3715/6008)| `completed`| _Equivalent_ <br/>(16072/16073)| `completed`| _Equivalent_ <br/>(8305/10610)| `completed`
| `on-hold`| _Equivalent_ <br/>(570/1926)| **`on-hold`**| _Equivalent_ <br/>(3721/6010)| `on-hold`| _Equivalent_ <br/>(16070/16071)| `on-hold`| _Equivalent_ <br/>(8307/10612)| `on-hold`
| `cancelled`| _Equivalent_ <br/>(567/1923)| **`cancelled`**| _Equivalent_ <br/>(3718/6006)| `cancelled`| _Equivalent_ <br/>(16074/16075)| `cancelled`| _Equivalent_ <br/>(8303/10608)| `cancelled`
| | | **`entered-in-error`**| _Equivalent_ <br/>(3719/6009)| `entered-in-error`| _Equivalent_ <br/>(16076/16077)| `entered-in-error`| _Equivalent_ <br/>(8306/10611)| `entered-in-error`
| `rejected`| _Equivalent_ <br/>(564/1930)| **`rejected`**| _Equivalent_ <br/>(3725/6000)| `rejected`| _Equivalent_ <br/>(16078/16079)| `rejected`| _Equivalent_ <br/>(8300/10605)| `rejected`
| *9 of 9 codes used* | | *13 of 13 codes used* | | *9 of 9 codes used* | | *9 of 9 codes used* | | *9 of 9 codes used* 

