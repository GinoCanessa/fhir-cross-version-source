Comparison of 
Generated at Monday, April 14, 2025 6:17:28 PM

### SearchEntryMode

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | SearchEntryMode |
| Canonical URL | `http://hl7.org/fhir/ValueSet/search-entry-mode` |
| Version | 4.0.1 |
| Description | Why an entry is in the result set - whether it's included as a match or because of an _include requirement, or to convey information or warning information about the search process. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `2735` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Bundle` | `Bundle.entry.search.mode` | `http://hl7.org/fhir/ValueSet/search-entry-mode\|4.0.1` | `Required` | match \| include \| outcome - why this is in the result set |

### Referenced Systems

* `http://hl7.org/fhir/search-entry-mode`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [SearchEntryMode](/docs/R2/ValueSets/SearchEntryMode.md)<br/> `http://hl7.org/fhir/ValueSet/search-entry-mode\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `16`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `175`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [SearchEntryMode](/docs/R3/ValueSets/SearchEntryMode.md)<br/> `http://hl7.org/fhir/ValueSet/search-entry-mode\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `340`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `562`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [SearchEntryMode](/docs/R4/ValueSets/SearchEntryMode.md)<br/> `http://hl7.org/fhir/ValueSet/search-entry-mode\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1723`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1724`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [SearchEntryMode](/docs/R4B/ValueSets/SearchEntryMode.md)<br/> `http://hl7.org/fhir/ValueSet/search-entry-mode\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `785`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1046`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [SearchEntryMode](/docs/R5/ValueSets/SearchEntryMode.md)<br/> `http://hl7.org/fhir/ValueSet/search-entry-mode\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set SearchEntryMode from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 SearchEntryMode](/docs/R2/ValueSets/SearchEntryMode.md)| Relationship | [R3 SearchEntryMode](/docs/R3/ValueSets/SearchEntryMode.md)| Relationship | R4 SearchEntryMode| Relationship | [R4B SearchEntryMode](/docs/R4B/ValueSets/SearchEntryMode.md)| Relationship | [R5 SearchEntryMode](/docs/R5/ValueSets/SearchEntryMode.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://hl7.org/fhir/search-entry-mode`
| `match`| _Equivalent_ <br/>(74/1444)| `match`| _Equivalent_ <br/>(2967/5172)| **`match`**| _Equivalent_ <br/>(17436/17437)| `match`| _Equivalent_ <br/>(7492/9755)| `match`
| `include`| _Equivalent_ <br/>(73/1443)| `include`| _Equivalent_ <br/>(2966/5171)| **`include`**| _Equivalent_ <br/>(17438/17439)| `include`| _Equivalent_ <br/>(7491/9754)| `include`
| `outcome`| _Equivalent_ <br/>(75/1445)| `outcome`| _Equivalent_ <br/>(2968/5173)| **`outcome`**| _Equivalent_ <br/>(17440/17441)| `outcome`| _Equivalent_ <br/>(7493/9756)| `outcome`
| *3 of 3 codes used* | | *3 of 3 codes used* | | *3 of 3 codes used* | | *3 of 3 codes used* | | *3 of 3 codes used* 

