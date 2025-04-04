Comparison of 
Generated at Friday, April 4, 2025 2:59:00 PM

### Ratio

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | Ratio |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Ratio` |
| Version | 5.0.0 |
| Description | Ratio Type: A relationship of two Quantity values - expressed as a numerator and a denominator. |
| Status | `Active` |
| Artifact Class | `ComplexType` |
| Database Key | `2238` |
| Database Snapshot Count | `5` |
| Database Differential Count | `3` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Ratio` | `Ratio` | `Ratio` | Ratio | A ratio of two Quantity values - a numerator and a denominator | 0..* | Ratio |  |  |
| `Ratio.denominator` | `Ratio.denominator` | `denominator` | Ratio.denominator | Denominator value | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
| `Ratio.extension` | `Ratio.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Ratio.id` | `Ratio.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Ratio.numerator` | `Ratio.numerator` | `numerator` | Ratio.numerator | Numerator value | 0..1 | Quantity |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Ratio](/docs/R2/ComplexTypes/Ratio.md)<br/> `http://hl7.org/fhir/StructureDefinition/Ratio\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `67`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `233`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Ratio](/docs/R3/ComplexTypes/Ratio.md)<br/> `http://hl7.org/fhir/StructureDefinition/Ratio\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `407`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `603`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Ratio](/docs/R4/ComplexTypes/Ratio.md)<br/> `http://hl7.org/fhir/StructureDefinition/Ratio\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1371`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1372`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Ratio](/docs/R4B/ComplexTypes/Ratio.md)<br/> `http://hl7.org/fhir/StructureDefinition/Ratio\|4.3.0` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `917`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1146`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Ratio](/docs/R5/ComplexTypes/Ratio.md)<br/> `http://hl7.org/fhir/StructureDefinition/Ratio\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Ratio from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Ratio](/docs/R2/ComplexTypes/Ratio.md)| Relationship | [R3 Ratio](/docs/R3/ComplexTypes/Ratio.md)| Relationship | [R4 Ratio](/docs/R4/ComplexTypes/Ratio.md)| Relationship | [R4B Ratio](/docs/R4B/ComplexTypes/Ratio.md)| Relationship | R5 Ratio
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `Ratio`| _Equivalent_<br/>(2805/2806)| `Ratio`| _Equivalent_<br/>(9737/9738)| `Ratio`| _Equivalent_<br/>(21203/21204)| `Ratio`| _Equivalent_<br/>(36263/36264)| **`Ratio`**
| `Ratio.id`| _Equivalent_<br/>(2807/2808)| `Ratio.id`| _Equivalent_<br/>(9739/9740)| `Ratio.id`| _Equivalent_<br/>(21205/21206)| `Ratio.id`| _Equivalent_<br/>(36265/36266)| **`Ratio.id`**
| `Ratio.extension`| _Equivalent_<br/>(2809/2810)| `Ratio.extension`| _Equivalent_<br/>(9741/9742)| `Ratio.extension`| _Equivalent_<br/>(21207/21208)| `Ratio.extension`| _Equivalent_<br/>(36267/36268)| **`Ratio.extension`**
| `Ratio.numerator`| _Equivalent_<br/>(2811/2812)| `Ratio.numerator`| _Equivalent_<br/>(9743/9744)| `Ratio.numerator`| _Equivalent_<br/>(21209/21210)| `Ratio.numerator`| _Equivalent_<br/>(36269/36270)| **`Ratio.numerator`**
| `Ratio.denominator`| _Equivalent_<br/>(2813/2814)| `Ratio.denominator`| _Equivalent_<br/>(9745/9746)| `Ratio.denominator`| _Equivalent_<br/>(21211/21212)| `Ratio.denominator`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(36271)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(36272)| **`Ratio.denominator`**
| *5 of 5 elements used* | | *5 of 5 elements used* | | *5 of 5 elements used* | | *5 of 5 elements used* | | *5 of 5 elements used* 

