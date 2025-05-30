Comparison of 
Generated at Monday, April 14, 2025 6:17:20 PM

### SystemRestfulInteraction

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | SystemRestfulInteraction |
| Canonical URL | `http://hl7.org/fhir/ValueSet/system-restful-interaction` |
| Version | 3.0.2 |
| Description | Operations supported by REST at the system level. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1506` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/CapabilityStatement` | `CapabilityStatement.rest.interaction.code` | `http://hl7.org/fhir/ValueSet/system-restful-interaction` | `Required` | transaction \| batch \| search-system \| history-system |

### Referenced Systems

* `http://hl7.org/fhir/restful-interaction`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [SystemRestfulInteraction](/docs/R2/ValueSets/SystemRestfulInteraction.md)<br/> `http://hl7.org/fhir/ValueSet/system-restful-interaction\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `39`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `198`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [SystemRestfulInteraction](/docs/R3/ValueSets/SystemRestfulInteraction.md)<br/> `http://hl7.org/fhir/ValueSet/system-restful-interaction\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `365`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `588`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [SystemRestfulInteraction](/docs/R4/ValueSets/SystemRestfulInteraction.md)<br/> `http://hl7.org/fhir/ValueSet/system-restful-interaction\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1761`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1762`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [SystemRestfulInteraction](/docs/R4B/ValueSets/SystemRestfulInteraction.md)<br/> `http://hl7.org/fhir/ValueSet/system-restful-interaction\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `812`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1073`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [SystemRestfulInteraction](/docs/R5/ValueSets/SystemRestfulInteraction.md)<br/> `http://hl7.org/fhir/ValueSet/system-restful-interaction\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set SystemRestfulInteraction from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 SystemRestfulInteraction](/docs/R2/ValueSets/SystemRestfulInteraction.md)| Relationship | R3 SystemRestfulInteraction| Relationship | [R4 SystemRestfulInteraction](/docs/R4/ValueSets/SystemRestfulInteraction.md)| Relationship | [R4B SystemRestfulInteraction](/docs/R4B/ValueSets/SystemRestfulInteraction.md)| Relationship | [R5 SystemRestfulInteraction](/docs/R5/ValueSets/SystemRestfulInteraction.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/restful-interaction`
| `transaction`| _Equivalent_ <br/>(184/1551)| **`transaction`**| _Equivalent_ <br/>(3087/5294)| `transaction`| _Equivalent_ <br/>(18286/18287)| `transaction`| _Equivalent_ <br/>(7657/9957)| `transaction`
| | | **`batch`**| _Equivalent_ <br/>(3085/5292)| `batch`| _Equivalent_ <br/>(18288/18289)| `batch`| _Equivalent_ <br/>(7655/9954)| `batch`
| `search-system`| _Equivalent_ <br/>(183/1550)| **`search-system`**| _Equivalent_ <br/>(3084/5291)| `search-system`| _Equivalent_ <br/>(18290/18291)| `search-system`| _Equivalent_ <br/>(7654/9956)| `search-system`
| `history-system`| _Equivalent_ <br/>(182/1549)| **`history-system`**| _Equivalent_ <br/>(3086/5293)| `history-system`| _Equivalent_ <br/>(18292/18293)| `history-system`| _Equivalent_ <br/>(7656/9955)| `history-system`
| *3 of 3 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* 

