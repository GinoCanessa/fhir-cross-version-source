Comparison of 
Generated at Friday, April 4, 2025 2:58:33 PM

### Narrative

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | Narrative |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Narrative` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for Narrative Type |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `32` |
| Database Snapshot Count | `5` |
| Database Differential Count | `3` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Narrative` | `Narrative` | `Narrative` | Narrative | A human-readable formatted text, including images | 0..* | Narrative |  |  |
| `Narrative.div` | `Narrative.div` | `div` |  | Limited xhtml content | 1..1 | xhtml |  |  |
| `Narrative.extension` | `Narrative.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Narrative.id` | `Narrative.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Narrative.status` | `Narrative.status` | `status` |  | generated \| extensions \| additional \| empty | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/narrative-status` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Narrative](/docs/R2/ComplexTypes/Narrative.md)<br/> `http://hl7.org/fhir/StructureDefinition/Narrative\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `58`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `229`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Narrative](/docs/R3/ComplexTypes/Narrative.md)<br/> `http://hl7.org/fhir/StructureDefinition/Narrative\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `402`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `598`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Narrative](/docs/R4/ComplexTypes/Narrative.md)<br/> `http://hl7.org/fhir/StructureDefinition/Narrative\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1355`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1356`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Narrative](/docs/R4B/ComplexTypes/Narrative.md)<br/> `http://hl7.org/fhir/StructureDefinition/Narrative\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `911`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1140`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Narrative](/docs/R5/ComplexTypes/Narrative.md)<br/> `http://hl7.org/fhir/StructureDefinition/Narrative\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Narrative from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 Narrative| Relationship | [R3 Narrative](/docs/R3/ComplexTypes/Narrative.md)| Relationship | [R4 Narrative](/docs/R4/ComplexTypes/Narrative.md)| Relationship | [R4B Narrative](/docs/R4B/ComplexTypes/Narrative.md)| Relationship | [R5 Narrative](/docs/R5/ComplexTypes/Narrative.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`Narrative`**| _Equivalent_<br/>(2719/2720)| `Narrative`| _Equivalent_<br/>(9671/9672)| `Narrative`| _Equivalent_<br/>(21075/21076)| `Narrative`| _Equivalent_<br/>(36184/36185)| `Narrative`
| **`Narrative.id`**| _Equivalent_<br/>(2721/2722)| `Narrative.id`| _Equivalent_<br/>(9673/9674)| `Narrative.id`| _Equivalent_<br/>(21077/21078)| `Narrative.id`| _Equivalent_<br/>(36186/36187)| `Narrative.id`
| **`Narrative.extension`**| _Equivalent_<br/>(2723/2724)| `Narrative.extension`| _Equivalent_<br/>(9675/9676)| `Narrative.extension`| _Equivalent_<br/>(21079/21080)| `Narrative.extension`| _Equivalent_<br/>(36188/36189)| `Narrative.extension`
| **`Narrative.status`**| _Equivalent_<br/>(2725/2726)| `Narrative.status`| _Equivalent_<br/>(9677/9678)| `Narrative.status`| _Equivalent_<br/>(21081/21082)| `Narrative.status`| _Equivalent_<br/>(36190/36191)| `Narrative.status`
| **`Narrative.div`**| _Equivalent_<br/>(2727/2728)| `Narrative.div`| _Equivalent_<br/>(9679/9680)| `Narrative.div`| _Equivalent_<br/>(21083/21084)| `Narrative.div`| _Equivalent_<br/>(36192/36193)| `Narrative.div`
| *5 of 5 elements used* | | *5 of 5 elements used* | | *5 of 5 elements used* | | *5 of 5 elements used* | | *5 of 5 elements used* 

