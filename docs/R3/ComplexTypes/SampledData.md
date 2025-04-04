Comparison of 
Generated at Friday, April 4, 2025 2:58:38 PM

### SampledData

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | SampledData |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/SampledData` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for SampledData Type |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `470` |
| Database Snapshot Count | `10` |
| Database Differential Count | `8` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `SampledData` | `SampledData` | `SampledData` | SampledData | A series of measurements taken by a device | 0..* | SampledData |  |  |
| `SampledData.data` | `SampledData.data` | `data` |  | Decimal values with spaces, or "E" \| "U" \| "L" | 1..1 | string |  |  |
| `SampledData.dimensions` | `SampledData.dimensions` | `dimensions` |  | Number of sample points at each time point | 1..1 | positiveInt |  |  |
| `SampledData.extension` | `SampledData.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `SampledData.factor` | `SampledData.factor` | `factor` |  | Multiply data by this before adding to origin | 0..1 | decimal |  |  |
| `SampledData.id` | `SampledData.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `SampledData.lowerLimit` | `SampledData.lowerLimit` | `lowerLimit` |  | Lower limit of detection | 0..1 | decimal |  |  |
| `SampledData.origin` | `SampledData.origin` | `origin` |  | Zero value and units | 1..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
| `SampledData.period` | `SampledData.period` | `period` |  | Number of milliseconds between samples | 1..1 | decimal |  |  |
| `SampledData.upperLimit` | `SampledData.upperLimit` | `upperLimit` |  | Upper limit of detection | 0..1 | decimal |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [SampledData](/docs/R2/ComplexTypes/SampledData.md)<br/> `http://hl7.org/fhir/StructureDefinition/SampledData\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `69`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `235`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SampledData](/docs/R3/ComplexTypes/SampledData.md)<br/> `http://hl7.org/fhir/StructureDefinition/SampledData\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `410`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `606`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SampledData](/docs/R4/ComplexTypes/SampledData.md)<br/> `http://hl7.org/fhir/StructureDefinition/SampledData\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1377`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1378`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SampledData](/docs/R4B/ComplexTypes/SampledData.md)<br/> `http://hl7.org/fhir/StructureDefinition/SampledData\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `921`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1150`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SampledData](/docs/R5/ComplexTypes/SampledData.md)<br/> `http://hl7.org/fhir/StructureDefinition/SampledData\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition SampledData from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 SampledData](/docs/R2/ComplexTypes/SampledData.md)| Relationship | R3 SampledData| Relationship | [R4 SampledData](/docs/R4/ComplexTypes/SampledData.md)| Relationship | [R4B SampledData](/docs/R4B/ComplexTypes/SampledData.md)| Relationship | [R5 SampledData](/docs/R5/ComplexTypes/SampledData.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `SampledData`| _Equivalent_<br/>(2825/2826)| **`SampledData`**| _Equivalent_<br/>(9778/9779)| `SampledData`| _Equivalent_<br/>(21249/21250)| `SampledData`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36318)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(36319)| `SampledData`
| `SampledData.id`| _Equivalent_<br/>(2827/2828)| **`SampledData.id`**| _Equivalent_<br/>(9780/9781)| `SampledData.id`| _Equivalent_<br/>(21251/21252)| `SampledData.id`| _Equivalent_<br/>(36320/36321)| `SampledData.id`
| `SampledData.extension`| _Equivalent_<br/>(2829/2830)| **`SampledData.extension`**| _Equivalent_<br/>(9782/9783)| `SampledData.extension`| _Equivalent_<br/>(21253/21254)| `SampledData.extension`| _Equivalent_<br/>(36322/36323)| `SampledData.extension`
| `SampledData.origin`| _Equivalent_<br/>(2831/2832)| **`SampledData.origin`**| _Equivalent_<br/>(9784/9785)| `SampledData.origin`| _Equivalent_<br/>(21255/21256)| `SampledData.origin`| _Equivalent_<br/>(36324/36325)| `SampledData.origin`
| `SampledData.period`| _Equivalent_<br/>(2833/2834)| **`SampledData.period`**| _Equivalent_<br/>(9786/9787)| `SampledData.period`| _Equivalent_<br/>(21257/21258)| `SampledData.period`| →→→→ _RelatedTo_ →→→→ <br/>(1948)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(36326)| `SampledData.interval`
| `SampledData.period`| _Equivalent_<br/>(2833/2834)| **`SampledData.period`**| _Equivalent_<br/>(9786/9787)| `SampledData.period`| _Equivalent_<br/>(21257/21258)| `SampledData.period`| →→→→ _RelatedTo_ →→→→ <br/>(1948)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(36326)| `SampledData.intervalUnit`
| `SampledData.factor`| _Equivalent_<br/>(2835/2836)| **`SampledData.factor`**| _Equivalent_<br/>(9788/9789)| `SampledData.factor`| _Equivalent_<br/>(21259/21260)| `SampledData.factor`| _Equivalent_<br/>(36327/36328)| `SampledData.factor`
| `SampledData.lowerLimit`| _Equivalent_<br/>(2837/2838)| **`SampledData.lowerLimit`**| _Equivalent_<br/>(9790/9791)| `SampledData.lowerLimit`| _Equivalent_<br/>(21261/21262)| `SampledData.lowerLimit`| _Equivalent_<br/>(36329/36330)| `SampledData.lowerLimit`
| `SampledData.upperLimit`| _Equivalent_<br/>(2839/2840)| **`SampledData.upperLimit`**| _Equivalent_<br/>(9792/9793)| `SampledData.upperLimit`| _Equivalent_<br/>(21263/21264)| `SampledData.upperLimit`| _Equivalent_<br/>(36331/36332)| `SampledData.upperLimit`
| `SampledData.dimensions`| _Equivalent_<br/>(2841/2842)| **`SampledData.dimensions`**| _Equivalent_<br/>(9794/9795)| `SampledData.dimensions`| _Equivalent_<br/>(21265/21266)| `SampledData.dimensions`| _Equivalent_<br/>(36333/36334)| `SampledData.dimensions`
| `SampledData.data`| _Equivalent_<br/>(2843/2844)| **`SampledData.data`**| →→→→ _Equivalent_ →→→→ <br/>(9796)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(9797)| `SampledData.data`| _Equivalent_<br/>(21267/21268)| `SampledData.data`| _Equivalent_<br/>(36335/36336)| `SampledData.data`
| *10 of 10 elements used* | | *10 of 10 elements used* | | *10 of 10 elements used* | | *10 of 10 elements used* | | *11 of 13 elements used* <br/>remaining elements:<br/>`SampledData.codeMap`, `SampledData.offsets`

