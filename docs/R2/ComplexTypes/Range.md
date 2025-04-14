Comparison of 
Generated at Monday, April 14, 2025 6:17:16 PM

### Range

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | Range |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Range` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for Range Type |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `35` |
| Database Snapshot Count | `5` |
| Database Differential Count | `3` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Range` | `Range` | `Range` | Range | Set of values bounded by low and high | 0..* | Range |  |  |
| `Range.extension` | `Range.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Range.high` | `Range.high` | `high` |  | High limit | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
| `Range.id` | `Range.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Range.low` | `Range.low` | `low` |  | Low limit | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Range](/docs/R2/ComplexTypes/Range.md)<br/> `http://hl7.org/fhir/StructureDefinition/Range\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `66`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `232`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Range](/docs/R3/ComplexTypes/Range.md)<br/> `http://hl7.org/fhir/StructureDefinition/Range\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `406`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `602`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Range](/docs/R4/ComplexTypes/Range.md)<br/> `http://hl7.org/fhir/StructureDefinition/Range\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1369`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1370`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Range](/docs/R4B/ComplexTypes/Range.md)<br/> `http://hl7.org/fhir/StructureDefinition/Range\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `916`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1145`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Range](/docs/R5/ComplexTypes/Range.md)<br/> `http://hl7.org/fhir/StructureDefinition/Range\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Range from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 Range| Relationship | [R3 Range](/docs/R3/ComplexTypes/Range.md)| Relationship | [R4 Range](/docs/R4/ComplexTypes/Range.md)| Relationship | [R4B Range](/docs/R4B/ComplexTypes/Range.md)| Relationship | [R5 Range](/docs/R5/ComplexTypes/Range.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`Range`**| _Equivalent_<br/>(2795/2796)| `Range`| _Equivalent_<br/>(9727/9728)| `Range`| _Equivalent_<br/>(21193/21194)| `Range`| _Equivalent_<br/>(36253/36254)| `Range`
| **`Range.id`**| _Equivalent_<br/>(2797/2798)| `Range.id`| _Equivalent_<br/>(9729/9730)| `Range.id`| _Equivalent_<br/>(21195/21196)| `Range.id`| _Equivalent_<br/>(36255/36256)| `Range.id`
| **`Range.extension`**| _Equivalent_<br/>(2799/2800)| `Range.extension`| _Equivalent_<br/>(9731/9732)| `Range.extension`| _Equivalent_<br/>(21197/21198)| `Range.extension`| _Equivalent_<br/>(36257/36258)| `Range.extension`
| **`Range.low`**| _Equivalent_<br/>(2801/2802)| `Range.low`| _Equivalent_<br/>(9733/9734)| `Range.low`| _Equivalent_<br/>(21199/21200)| `Range.low`| _Equivalent_<br/>(36259/36260)| `Range.low`
| **`Range.high`**| _Equivalent_<br/>(2803/2804)| `Range.high`| _Equivalent_<br/>(9735/9736)| `Range.high`| _Equivalent_<br/>(21201/21202)| `Range.high`| _Equivalent_<br/>(36261/36262)| `Range.high`
| *5 of 5 elements used* | | *5 of 5 elements used* | | *5 of 5 elements used* | | *5 of 5 elements used* | | *5 of 5 elements used* 

