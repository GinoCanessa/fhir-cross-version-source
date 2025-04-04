Comparison of 
Generated at Friday, April 4, 2025 2:59:00 PM

### RatioRange

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | RatioRange |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/RatioRange` |
| Version | 5.0.0 |
| Description | RatioRange Type: A range of ratios expressed as a low and high numerator and a denominator. |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `2239` |
| Database Snapshot Count | `6` |
| Database Differential Count | `4` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `RatioRange` | `RatioRange` | `RatioRange` | RatioRange | Range of ratio values | 0..* | RatioRange |  |  |
| `RatioRange.denominator` | `RatioRange.denominator` | `denominator` | RatioRange.denominator | Denominator value | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
| `RatioRange.extension` | `RatioRange.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `RatioRange.highNumerator` | `RatioRange.highNumerator` | `highNumerator` | RatioRange.highNumerator | High Numerator limit | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
| `RatioRange.id` | `RatioRange.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `RatioRange.lowNumerator` | `RatioRange.lowNumerator` | `lowNumerator` | RatioRange.lowNumerator | Low Numerator limit | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [RatioRange](/docs/R4B/ComplexTypes/RatioRange.md)<br/> `http://hl7.org/fhir/StructureDefinition/RatioRange\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `918`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1147`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RatioRange](/docs/R5/ComplexTypes/RatioRange.md)<br/> `http://hl7.org/fhir/StructureDefinition/RatioRange\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition RatioRange from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | [R4B RatioRange](/docs/R4B/ComplexTypes/RatioRange.md)| Relationship | R5 RatioRange
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | `RatioRange`| _Equivalent_<br/>(36273/36274)| **`RatioRange`**
| | | | | | | `RatioRange.id`| _Equivalent_<br/>(36275/36276)| **`RatioRange.id`**
| | | | | | | `RatioRange.extension`| _Equivalent_<br/>(36277/36278)| **`RatioRange.extension`**
| | | | | | | `RatioRange.lowNumerator`| _Equivalent_<br/>(36279/36280)| **`RatioRange.lowNumerator`**
| | | | | | | `RatioRange.highNumerator`| _Equivalent_<br/>(36281/36282)| **`RatioRange.highNumerator`**
| | | | | | | `RatioRange.denominator`| _Equivalent_<br/>(36283/36284)| **`RatioRange.denominator`**
| | | | | | | *6 of 6 elements used* | | *6 of 6 elements used* 

