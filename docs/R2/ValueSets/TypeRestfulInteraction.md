Comparison of 
Generated at Monday, April 14, 2025 6:17:15 PM

### TypeRestfulInteraction

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | TypeRestfulInteraction |
| Canonical URL | `http://hl7.org/fhir/ValueSet/type-restful-interaction` |
| Version | 1.0.2 |
| Description | Operations supported by REST at the type or instance level. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `399` |
| Database Concept Count | `9` |
| Database Active Concept Count | `9` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Conformance` | `Conformance.rest.resource.interaction.code` | `http://hl7.org/fhir/ValueSet/type-restful-interaction` | `Required` | read \| vread \| update \| delete \| history-instance \| validate \| history-type \| create \| search-type |

### Referenced Systems

* `http://hl7.org/fhir/restful-interaction`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [TypeRestfulInteraction](/docs/R2/ValueSets/TypeRestfulInteraction.md)<br/> `http://hl7.org/fhir/ValueSet/type-restful-interaction\|1.0.2` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `42`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `201`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [TypeRestfulInteraction](/docs/R3/ValueSets/TypeRestfulInteraction.md)<br/> `http://hl7.org/fhir/ValueSet/type-restful-interaction\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `369`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `592`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [TypeRestfulInteraction](/docs/R4/ValueSets/TypeRestfulInteraction.md)<br/> `http://hl7.org/fhir/ValueSet/type-restful-interaction\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1771`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1772`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [TypeRestfulInteraction](/docs/R4B/ValueSets/TypeRestfulInteraction.md)<br/> `http://hl7.org/fhir/ValueSet/type-restful-interaction\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `816`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1077`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [TypeRestfulInteraction](/docs/R5/ValueSets/TypeRestfulInteraction.md)<br/> `http://hl7.org/fhir/ValueSet/type-restful-interaction\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set TypeRestfulInteraction from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 TypeRestfulInteraction| Relationship | [R3 TypeRestfulInteraction](/docs/R3/ValueSets/TypeRestfulInteraction.md)| Relationship | [R4 TypeRestfulInteraction](/docs/R4/ValueSets/TypeRestfulInteraction.md)| Relationship | [R4B TypeRestfulInteraction](/docs/R4B/ValueSets/TypeRestfulInteraction.md)| Relationship | [R5 TypeRestfulInteraction](/docs/R5/ValueSets/TypeRestfulInteraction.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/restful-interaction`
| **`read`**| _Equivalent_ <br/>(194/1562)| `read`| _Equivalent_ <br/>(3097/5304)| `read`| _Equivalent_ <br/>(18356/18357)| `read`| _Equivalent_ <br/>(7667/9967)| `read`
| **`vread`**| _Equivalent_ <br/>(198/1565)| `vread`| _Equivalent_ <br/>(3102/5309)| `vread`| _Equivalent_ <br/>(18358/18359)| `vread`| _Equivalent_ <br/>(7672/9972)| `vread`
| **`update`**| _Equivalent_ <br/>(196/1564)| `update`| _Equivalent_ <br/>(3099/5306)| `update`| _Equivalent_ <br/>(18360/18361)| `update`| _Equivalent_ <br/>(7669/9969)| `update`
| **`delete`**| _Equivalent_ <br/>(191/1558)| `delete`| _Equivalent_ <br/>(3100/5307)| `delete`| _Equivalent_ <br/>(18364/18365)| `delete`| _Equivalent_ <br/>(7670/9970)| `delete`
| **`history-instance`**| _Equivalent_ <br/>(192/1559)| `history-instance`| _Equivalent_ <br/>(3104/5311)| `history-instance`| _Equivalent_ <br/>(18366/18367)| `history-instance`| _Equivalent_ <br/>(7674/9974)| `history-instance`
| **`validate`**| | | | | | | | | 
| **`history-type`**| _Equivalent_ <br/>(193/1560)| `history-type`| _Equivalent_ <br/>(3105/5312)| `history-type`| _Equivalent_ <br/>(18368/18369)| `history-type`| _Equivalent_ <br/>(7675/9975)| `history-type`
| **`create`**| _Equivalent_ <br/>(190/1557)| `create`| _Equivalent_ <br/>(3103/5310)| `create`| _Equivalent_ <br/>(18370/18371)| `create`| _Equivalent_ <br/>(7673/9973)| `create`
| **`search-type`**| _Equivalent_ <br/>(195/1563)| `search-type`| _Equivalent_ <br/>(3098/5305)| `search-type`| _Equivalent_ <br/>(18372/18373)| `search-type`| _Equivalent_ <br/>(7668/9968)| `search-type`
| *9 of 9 codes used* | | *8 of 9 codes used* <br/>remaining codes:<br/>`patch`| | *8 of 9 codes used* <br/>remaining codes:<br/>`patch`| | *8 of 9 codes used* <br/>remaining codes:<br/>`patch`| | *8 of 9 codes used* <br/>remaining codes:<br/>`patch`

