Comparison of 
Generated at Thursday, April 3, 2025 8:18:05 AM

### SearchParamType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | SearchParamType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/search-param-type` |
| Version | 1.0.2 |
| Description | Data types allowed to be used for search parameters. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `357` |
| Database Concept Count | `8` |
| Database Active Concept Count | `8` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Conformance` | `Conformance.rest.resource.searchParam.type` | `http://hl7.org/fhir/ValueSet/search-param-type` | `Required` | number \| date \| string \| token \| reference \| composite \| quantity \| uri |
| `http://hl7.org/fhir/StructureDefinition/SearchParameter` | `SearchParameter.type` | `http://hl7.org/fhir/ValueSet/search-param-type` | `Required` | number \| date \| string \| token \| reference \| composite \| quantity \| uri |

### Referenced Systems

* `http://hl7.org/fhir/search-param-type`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [SearchParamType](/docs/R2/ValueSets/SearchParamType.md)<br/> `http://hl7.org/fhir/ValueSet/search-param-type\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `43`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `202`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SearchParamType](/docs/R3/ValueSets/SearchParamType.md)<br/> `http://hl7.org/fhir/ValueSet/search-param-type\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `371`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `594`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SearchParamType](/docs/R4/ValueSets/SearchParamType.md)<br/> `http://hl7.org/fhir/ValueSet/search-param-type\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1727`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1728`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SearchParamType](/docs/R4B/ValueSets/SearchParamType.md)<br/> `http://hl7.org/fhir/ValueSet/search-param-type\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `818`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1079`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SearchParamType](/docs/R5/ValueSets/SearchParamType.md)<br/> `http://hl7.org/fhir/ValueSet/search-param-type\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set SearchParamType from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 SearchParamType| Relationship | [R3 SearchParamType](/docs/R3/ValueSets/SearchParamType.md)| Relationship | [R4 SearchParamType](/docs/R4/ValueSets/SearchParamType.md)| Relationship | [R4B SearchParamType](/docs/R4B/ValueSets/SearchParamType.md)| Relationship | [R5 SearchParamType](/docs/R5/ValueSets/SearchParamType.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/search-param-type`
| **`number`**| _Equivalent_ <br/>(201/1568)| `number`| _Equivalent_ <br/>(3113/5320)| `number`| _Equivalent_ <br/>(17466/17467)| `number`| _Equivalent_ <br/>(7684/9984)| `number`
| **`date`**| _Equivalent_ <br/>(199/1566)| `date`| _Equivalent_ <br/>(3111/5319)| `date`| _Equivalent_ <br/>(17468/17469)| `date`| _Equivalent_ <br/>(7681/9981)| `date`
| **`string`**| _Equivalent_ <br/>(203/1570)| `string`| _Equivalent_ <br/>(3115/5324)| `string`| _Equivalent_ <br/>(17470/17471)| `string`| _Equivalent_ <br/>(7686/9986)| `string`
| **`token`**| _Equivalent_ <br/>(206/1573)| `token`| _Equivalent_ <br/>(3118/5325)| `token`| _Equivalent_ <br/>(17472/17473)| `token`| _Equivalent_ <br/>(7689/9989)| `token`
| **`reference`**| _Equivalent_ <br/>(200/1567)| `reference`| _Equivalent_ <br/>(3112/5322)| `reference`| _Equivalent_ <br/>(17474/17475)| `reference`| _Equivalent_ <br/>(7682/9982)| `reference`
| **`composite`**| _Equivalent_ <br/>(204/1571)| `composite`| _Equivalent_ <br/>(3116/5318)| `composite`| _Equivalent_ <br/>(17476/17477)| `composite`| _Equivalent_ <br/>(7687/9987)| `composite`
| **`quantity`**| _Equivalent_ <br/>(202/1569)| `quantity`| _Equivalent_ <br/>(3114/5321)| `quantity`| _Equivalent_ <br/>(17478/17479)| `quantity`| _Equivalent_ <br/>(7685/9985)| `quantity`
| **`uri`**| _Equivalent_ <br/>(205/1572)| `uri`| _Equivalent_ <br/>(3117/5326)| `uri`| _Equivalent_ <br/>(17480/17481)| `uri`| _Equivalent_ <br/>(7688/9988)| `uri`
| *8 of 8 codes used* | | *8 of 8 codes used* | | *8 of 9 codes used* <br/>remaining codes:<br/>`special`| | *8 of 9 codes used* <br/>remaining codes:<br/>`special`| | *8 of 9 codes used* <br/>remaining codes:<br/>`special`

