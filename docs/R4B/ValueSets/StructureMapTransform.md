Comparison of 
Generated at Thursday, April 3, 2025 8:18:24 AM

### StructureMapTransform

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | StructureMapTransform |
| Canonical URL | `http://hl7.org/fhir/ValueSet/map-transform` |
| Version | 4.3.0 |
| Description | How data is copied/created. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `3882` |
| Database Concept Count | `17` |
| Database Active Concept Count | `17` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/StructureMap` | `StructureMap.group.rule.target.transform` | `http://hl7.org/fhir/ValueSet/map-transform\|4.3.0` | `Required` | create \| copy + |

### Referenced Systems

* `http://hl7.org/fhir/map-transform`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [StructureMapTransform](/docs/R3/ValueSets/StructureMapTransform.md)<br/> `http://hl7.org/fhir/ValueSet/map-transform\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `510`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `731`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [StructureMapTransform](/docs/R4/ValueSets/StructureMapTransform.md)<br/> `http://hl7.org/fhir/ValueSet/map-transform\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1585`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1586`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [StructureMapTransform](/docs/R4B/ValueSets/StructureMapTransform.md)<br/> `http://hl7.org/fhir/ValueSet/map-transform\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `988`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1249`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [StructureMapTransform](/docs/R5/ValueSets/StructureMapTransform.md)<br/> `http://hl7.org/fhir/ValueSet/map-transform\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set StructureMapTransform from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | [R3 StructureMapTransform](/docs/R3/ValueSets/StructureMapTransform.md)| Relationship | [R4 StructureMapTransform](/docs/R4/ValueSets/StructureMapTransform.md)| Relationship | R4B StructureMapTransform| Relationship | [R5 StructureMapTransform](/docs/R5/ValueSets/StructureMapTransform.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://hl7.org/fhir/map-transform`
| | | `create`| _Equivalent_ <br/>(4805/7126)| `create`| _Equivalent_ <br/>(16434/16435)| **`create`**| _Equivalent_ <br/>(9377/11715)| `create`
| | | `copy`| _Equivalent_ <br/>(4806/7127)| `copy`| _Equivalent_ <br/>(16436/16437)| **`copy`**| _Equivalent_ <br/>(9378/11716)| `copy`
| | | `truncate`| _Equivalent_ <br/>(4803/7124)| `truncate`| _Equivalent_ <br/>(16438/16439)| **`truncate`**| _Equivalent_ <br/>(9375/11713)| `truncate`
| | | `escape`| _Equivalent_ <br/>(4808/7129)| `escape`| _Equivalent_ <br/>(16440/16441)| **`escape`**| _Equivalent_ <br/>(9380/11718)| `escape`
| | | `cast`| _Equivalent_ <br/>(4802/7123)| `cast`| _Equivalent_ <br/>(16442/16443)| **`cast`**| _Equivalent_ <br/>(9374/11712)| `cast`
| | | `append`| _Equivalent_ <br/>(4810/7131)| `append`| _Equivalent_ <br/>(16444/16445)| **`append`**| _Equivalent_ <br/>(9382/11720)| `append`
| | | `translate`| _Equivalent_ <br/>(4800/7121)| `translate`| _Equivalent_ <br/>(16446/16447)| **`translate`**| _Equivalent_ <br/>(9372/11710)| `translate`
| | | `reference`| _Equivalent_ <br/>(4801/7122)| `reference`| _Equivalent_ <br/>(16448/16449)| **`reference`**| _Equivalent_ <br/>(9373/11711)| `reference`
| | | `dateOp`| _Equivalent_ <br/>(4811/7132)| `dateOp`| _Equivalent_ <br/>(16450/16451)| **`dateOp`**| _Equivalent_ <br/>(9383/11721)| `dateOp`
| | | `uuid`| _Equivalent_ <br/>(4798/7119)| `uuid`| _Equivalent_ <br/>(16452/16453)| **`uuid`**| _Equivalent_ <br/>(9370/11708)| `uuid`
| | | `pointer`| _Equivalent_ <br/>(4796/7117)| `pointer`| _Equivalent_ <br/>(16454/16455)| **`pointer`**| _Equivalent_ <br/>(9368/11706)| `pointer`
| | | `evaluate`| _Equivalent_ <br/>(4809/7130)| `evaluate`| _Equivalent_ <br/>(16456/16457)| **`evaluate`**| _Equivalent_ <br/>(9381/11719)| `evaluate`
| | | `cc`| _Equivalent_ <br/>(4795/7116)| `cc`| _Equivalent_ <br/>(16458/16459)| **`cc`**| _Equivalent_ <br/>(9367/11705)| `cc`
| | | `c`| _Equivalent_ <br/>(4797/7118)| `c`| _Equivalent_ <br/>(16460/16461)| **`c`**| _Equivalent_ <br/>(9369/11707)| `c`
| | | `qty`| _Equivalent_ <br/>(4804/7125)| `qty`| _Equivalent_ <br/>(16462/16463)| **`qty`**| _Equivalent_ <br/>(9376/11714)| `qty`
| | | `id`| _Equivalent_ <br/>(4807/7128)| `id`| _Equivalent_ <br/>(16464/16465)| **`id`**| _Equivalent_ <br/>(9379/11717)| `id`
| | | `cp`| _Equivalent_ <br/>(4799/7120)| `cp`| _Equivalent_ <br/>(16466/16467)| **`cp`**| _Equivalent_ <br/>(9371/11709)| `cp`
| | | *17 of 17 codes used* | | *17 of 17 codes used* | | *17 of 17 codes used* | | *17 of 17 codes used* 

