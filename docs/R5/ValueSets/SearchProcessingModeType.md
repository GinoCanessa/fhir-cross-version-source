Comparison of 
Generated at Monday, April 14, 2025 6:17:43 PM

### SearchProcessingModeType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | SearchProcessingModeType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/search-processingmode` |
| Version | 5.0.0 |
| Description | How a search parameter relates to the set of elements returned by evaluating its expression query. |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `4885` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/SearchParameter` | `SearchParameter.processingMode` | `http://hl7.org/fhir/ValueSet/search-processingmode\|5.0.0` | `Required` | normal \| phonetic \| other |

### Referenced Systems

* `http://hl7.org/fhir/search-processingmode`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [XPathUsageType](/docs/R2/ValueSets/XPathUsageType.md)<br/> `http://hl7.org/fhir/ValueSet/search-xpath-usage\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `145`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `303`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [XPathUsageType](/docs/R3/ValueSets/XPathUsageType.md)<br/> `http://hl7.org/fhir/ValueSet/search-xpath-usage\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `515`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `736`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [XPathUsageType](/docs/R4/ValueSets/XPathUsageType.md)<br/> `http://hl7.org/fhir/ValueSet/search-xpath-usage\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1729`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1730`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [XPathUsageType](/docs/R4B/ValueSets/XPathUsageType.md)<br/> `http://hl7.org/fhir/ValueSet/search-xpath-usage\|4.3.0` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `993`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1254`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [SearchProcessingModeType](/docs/R5/ValueSets/SearchProcessingModeType.md)<br/> `http://hl7.org/fhir/ValueSet/search-processingmode\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set SearchProcessingModeType from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 XPathUsageType](/docs/R2/ValueSets/XPathUsageType.md)| Relationship | [R3 XPathUsageType](/docs/R3/ValueSets/XPathUsageType.md)| Relationship | [R4 XPathUsageType](/docs/R4/ValueSets/XPathUsageType.md)| Relationship | [R4B XPathUsageType](/docs/R4B/ValueSets/XPathUsageType.md)| Relationship | R5 SearchProcessingModeType
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/search-processingmode`
| `normal`| _Equivalent_ <br/>(1273/2719)| `normal`| _Equivalent_ <br/>(4838/7161)| `normal`| _Equivalent_ <br/>(17484/17485)| `normal`| _Equivalent_ <br/>(9416/11752)| **`normal`**
| `phonetic`| _Equivalent_ <br/>(1275/2721)| `phonetic`| _Equivalent_ <br/>(4840/7163)| `phonetic`| _Equivalent_ <br/>(17486/17487)| `phonetic`| _Equivalent_ <br/>(9418/11754)| **`phonetic`**
| `other`| _Equivalent_ <br/>(1274/2720)| `other`| _Equivalent_ <br/>(4839/7162)| `other`| _Equivalent_ <br/>(17492/17493)| `other`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9417)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11753) | **`other`**
| *3 of 5 codes used* <br/>remaining codes:<br/>`distance`, `nearby`| | *3 of 5 codes used* <br/>remaining codes:<br/>`distance`, `nearby`| | *3 of 5 codes used* <br/>remaining codes:<br/>`distance`, `nearby`| | *3 of 5 codes used* <br/>remaining codes:<br/>`distance`, `nearby`| | *3 of 3 codes used* 

