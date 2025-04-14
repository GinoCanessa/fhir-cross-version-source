Comparison of 
Generated at Monday, April 14, 2025 6:17:21 PM

### Period

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | Period |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Period` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for Period Type |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `464` |
| Database Snapshot Count | `5` |
| Database Differential Count | `3` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Period` | `Period` | `Period` | Period | Time range defined by start and end date/time | 0..* | Period |  |  |
| `Period.end` | `Period.end` | `end` |  | End time with inclusive boundary, if not ongoing | 0..1 | dateTime |  |  |
| `Period.extension` | `Period.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Period.id` | `Period.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Period.start` | `Period.start` | `start` |  | Starting time with inclusive boundary | 0..1 | dateTime |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Period](/docs/R2/ComplexTypes/Period.md)<br/> `http://hl7.org/fhir/StructureDefinition/Period\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `59`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `230`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Period](/docs/R3/ComplexTypes/Period.md)<br/> `http://hl7.org/fhir/StructureDefinition/Period\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `404`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `600`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Period](/docs/R4/ComplexTypes/Period.md)<br/> `http://hl7.org/fhir/StructureDefinition/Period\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1359`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1360`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Period](/docs/R4B/ComplexTypes/Period.md)<br/> `http://hl7.org/fhir/StructureDefinition/Period\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `913`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1142`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Period](/docs/R5/ComplexTypes/Period.md)<br/> `http://hl7.org/fhir/StructureDefinition/Period\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Period from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Period](/docs/R2/ComplexTypes/Period.md)| Relationship | R3 Period| Relationship | [R4 Period](/docs/R4/ComplexTypes/Period.md)| Relationship | [R4B Period](/docs/R4B/ComplexTypes/Period.md)| Relationship | [R5 Period](/docs/R5/ComplexTypes/Period.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `Period`| _Equivalent_<br/>(2729/2730)| **`Period`**| _Equivalent_<br/>(9701/9702)| `Period`| _Equivalent_<br/>(21105/21106)| `Period`| _Equivalent_<br/>(36214/36215)| `Period`
| `Period.id`| _Equivalent_<br/>(2731/2732)| **`Period.id`**| _Equivalent_<br/>(9703/9704)| `Period.id`| _Equivalent_<br/>(21107/21108)| `Period.id`| _Equivalent_<br/>(36216/36217)| `Period.id`
| `Period.extension`| _Equivalent_<br/>(2733/2734)| **`Period.extension`**| _Equivalent_<br/>(9705/9706)| `Period.extension`| _Equivalent_<br/>(21109/21110)| `Period.extension`| _Equivalent_<br/>(36218/36219)| `Period.extension`
| `Period.start`| _Equivalent_<br/>(2735/2736)| **`Period.start`**| _Equivalent_<br/>(9707/9708)| `Period.start`| _Equivalent_<br/>(21111/21112)| `Period.start`| _Equivalent_<br/>(36220/36221)| `Period.start`
| `Period.end`| _Equivalent_<br/>(2737/2738)| **`Period.end`**| _Equivalent_<br/>(9709/9710)| `Period.end`| _Equivalent_<br/>(21113/21114)| `Period.end`| _Equivalent_<br/>(36222/36223)| `Period.end`
| *5 of 5 elements used* | | *5 of 5 elements used* | | *5 of 5 elements used* | | *5 of 5 elements used* | | *5 of 5 elements used* 

