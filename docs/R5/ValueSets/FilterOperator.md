Comparison of 
Generated at Monday, April 14, 2025 6:17:44 PM

### FilterOperator

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | FilterOperator |
| Canonical URL | `http://hl7.org/fhir/ValueSet/filter-operator` |
| Version | 5.0.0 |
| Description | The kind of operation to perform as a part of a property based filter. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `4572` |
| Database Concept Count | `11` |
| Database Active Concept Count | `11` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/CodeSystem` | `CodeSystem.filter.operator` | `http://hl7.org/fhir/ValueSet/filter-operator\|5.0.0` | `Required` | = \| is-a \| descendent-of \| is-not-a \| regex \| in \| not-in \| generalizes \| child-of \| descendent-leaf \| exists |
| `http://hl7.org/fhir/StructureDefinition/ValueSet` | `ValueSet.compose.include.filter.op` | `http://hl7.org/fhir/ValueSet/filter-operator\|5.0.0` | `Required` | = \| is-a \| descendent-of \| is-not-a \| regex \| in \| not-in \| generalizes \| child-of \| descendent-leaf \| exists |

### Referenced Systems

* `http://hl7.org/fhir/filter-operator`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [FilterOperator](/docs/R2/ValueSets/FilterOperator.md)<br/> `http://hl7.org/fhir/ValueSet/filter-operator\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `161`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `319`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [FilterOperator](/docs/R3/ValueSets/FilterOperator.md)<br/> `http://hl7.org/fhir/ValueSet/filter-operator\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `382`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `605`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [FilterOperator](/docs/R4/ValueSets/FilterOperator.md)<br/> `http://hl7.org/fhir/ValueSet/filter-operator\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1511`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1512`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [FilterOperator](/docs/R4B/ValueSets/FilterOperator.md)<br/> `http://hl7.org/fhir/ValueSet/filter-operator\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `827`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1088`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [FilterOperator](/docs/R5/ValueSets/FilterOperator.md)<br/> `http://hl7.org/fhir/ValueSet/filter-operator\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set FilterOperator from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 FilterOperator](/docs/R2/ValueSets/FilterOperator.md)| Relationship | [R3 FilterOperator](/docs/R3/ValueSets/FilterOperator.md)| Relationship | [R4 FilterOperator](/docs/R4/ValueSets/FilterOperator.md)| Relationship | [R4B FilterOperator](/docs/R4B/ValueSets/FilterOperator.md)| Relationship | R5 FilterOperator
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/filter-operator`
| `=`| _Equivalent_ <br/>(1383/2867)| `=`| _Equivalent_ <br/>(3174/5385)| `=`| _Equivalent_ <br/>(16030/16031)| `=`| _Equivalent_ <br/>(7732/10027)| **`=`**
| `is-a`| _Equivalent_ <br/>(1384/2872)| `is-a`| _Equivalent_ <br/>(3175/5386)| `is-a`| _Equivalent_ <br/>(16032/16033)| `is-a`| _Equivalent_ <br/>(7733/10034)| **`is-a`**
| | | `descendent-of`| _Equivalent_ <br/>(3170/5381)| `descendent-of`| _Equivalent_ <br/>(16034/16035)| `descendent-of`| _Equivalent_ <br/>(7728/10030)| **`descendent-of`**
| `is-not-a`| _Equivalent_ <br/>(1379/2873)| `is-not-a`| _Equivalent_ <br/>(3167/5378)| `is-not-a`| _Equivalent_ <br/>(16036/16037)| `is-not-a`| _Equivalent_ <br/>(7725/10035)| **`is-not-a`**
| `regex`| _Equivalent_ <br/>(1380/2875)| `regex`| _Equivalent_ <br/>(3168/5379)| `regex`| _Equivalent_ <br/>(16038/16039)| `regex`| _Equivalent_ <br/>(7726/10037)| **`regex`**
| `in`| _Equivalent_ <br/>(1381/2871)| `in`| _Equivalent_ <br/>(3169/5380)| `in`| _Equivalent_ <br/>(16040/16041)| `in`| _Equivalent_ <br/>(7727/10033)| **`in`**
| `not-in`| _Equivalent_ <br/>(1382/2874)| `not-in`| _Equivalent_ <br/>(3171/5382)| `not-in`| _Equivalent_ <br/>(16042/16043)| `not-in`| _Equivalent_ <br/>(7729/10036)| **`not-in`**
| | | `generalizes`| _Equivalent_ <br/>(3173/5384)| `generalizes`| _Equivalent_ <br/>(16044/16045)| `generalizes`| _Equivalent_ <br/>(7731/10032)| **`generalizes`**
| | | | | | | | | **`child-of`**
| | | | | | | | | **`descendent-leaf`**
| | | `exists`| _Equivalent_ <br/>(3172/5383)| `exists`| _Equivalent_ <br/>(16046/16047)| `exists`| _Equivalent_ <br/>(7730/10031)| **`exists`**
| *6 of 6 codes used* | | *9 of 9 codes used* | | *9 of 9 codes used* | | *9 of 9 codes used* | | *11 of 11 codes used* 

