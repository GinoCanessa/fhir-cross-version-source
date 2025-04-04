Comparison of 
Generated at Friday, April 4, 2025 2:58:33 PM

### Identifier

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | Identifier |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Identifier` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for Identifier Type |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `30` |
| Database Snapshot Count | `9` |
| Database Differential Count | `7` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Identifier` | `Identifier` | `Identifier` | Identifier | An identifier intended for computation | 0..* | Identifier |  |  |
| `Identifier.assigner` | `Identifier.assigner` | `assigner` |  | Organization that issued id (may be just text) | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `Identifier.extension` | `Identifier.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Identifier.id` | `Identifier.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Identifier.period` | `Identifier.period` | `period` |  | Time period when id is/was valid for use | 0..1 | Period |  |  |
| `Identifier.system` | `Identifier.system` | `system` |  | The namespace for the identifier | 0..1 | uri |  |  |
| `Identifier.type` | `Identifier.type` | `type` |  | Description of identifier | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/identifier-type` |
| `Identifier.use` | `Identifier.use` | `use` |  | usual \| official \| temp \| secondary (If known) | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/identifier-use` |
| `Identifier.value` | `Identifier.value` | `value` |  | The value that is unique | 0..1 | string |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Identifier](/docs/R2/ComplexTypes/Identifier.md)<br/> `http://hl7.org/fhir/StructureDefinition/Identifier\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `56`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `226`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Identifier](/docs/R3/ComplexTypes/Identifier.md)<br/> `http://hl7.org/fhir/StructureDefinition/Identifier\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `399`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `595`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Identifier](/docs/R4/ComplexTypes/Identifier.md)<br/> `http://hl7.org/fhir/StructureDefinition/Identifier\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1347`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1348`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Identifier](/docs/R4B/ComplexTypes/Identifier.md)<br/> `http://hl7.org/fhir/StructureDefinition/Identifier\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `908`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1137`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Identifier](/docs/R5/ComplexTypes/Identifier.md)<br/> `http://hl7.org/fhir/StructureDefinition/Identifier\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Identifier from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 Identifier| Relationship | [R3 Identifier](/docs/R3/ComplexTypes/Identifier.md)| Relationship | [R4 Identifier](/docs/R4/ComplexTypes/Identifier.md)| Relationship | [R4B Identifier](/docs/R4B/ComplexTypes/Identifier.md)| Relationship | [R5 Identifier](/docs/R5/ComplexTypes/Identifier.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`Identifier`**| _Equivalent_<br/>(2685/2686)| `Identifier`| _Equivalent_<br/>(9618/9619)| `Identifier`| _Equivalent_<br/>(21009/21010)| `Identifier`| _Equivalent_<br/>(36120/36121)| `Identifier`
| **`Identifier.id`**| _Equivalent_<br/>(2687/2688)| `Identifier.id`| _Equivalent_<br/>(9620/9621)| `Identifier.id`| _Equivalent_<br/>(21011/21012)| `Identifier.id`| _Equivalent_<br/>(36122/36123)| `Identifier.id`
| **`Identifier.extension`**| _Equivalent_<br/>(2689/2690)| `Identifier.extension`| _Equivalent_<br/>(9622/9623)| `Identifier.extension`| _Equivalent_<br/>(21013/21014)| `Identifier.extension`| _Equivalent_<br/>(36124/36125)| `Identifier.extension`
| **`Identifier.use`**| _Equivalent_<br/>(2691/2692)| `Identifier.use`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9624)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(9625)| `Identifier.use`| _Equivalent_<br/>(21015/21016)| `Identifier.use`| _Equivalent_<br/>(36126/36127)| `Identifier.use`
| **`Identifier.type`**| _Equivalent_<br/>(2693/2694)| `Identifier.type`| _Equivalent_<br/>(9626/9627)| `Identifier.type`| _Equivalent_<br/>(21017/21018)| `Identifier.type`| _Equivalent_<br/>(36128/36129)| `Identifier.type`
| **`Identifier.system`**| _Equivalent_<br/>(2695/2696)| `Identifier.system`| _Equivalent_<br/>(9628/9629)| `Identifier.system`| _Equivalent_<br/>(21019/21020)| `Identifier.system`| _Equivalent_<br/>(36130/36131)| `Identifier.system`
| **`Identifier.value`**| _Equivalent_<br/>(2697/2698)| `Identifier.value`| _Equivalent_<br/>(9630/9631)| `Identifier.value`| _Equivalent_<br/>(21021/21022)| `Identifier.value`| _Equivalent_<br/>(36132/36133)| `Identifier.value`
| **`Identifier.period`**| _Equivalent_<br/>(2699/2700)| `Identifier.period`| _Equivalent_<br/>(9632/9633)| `Identifier.period`| _Equivalent_<br/>(21023/21024)| `Identifier.period`| _Equivalent_<br/>(36134/36135)| `Identifier.period`
| **`Identifier.assigner`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(2701)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2702)| `Identifier.assigner`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9634)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(9635)| `Identifier.assigner`| _Equivalent_<br/>(21025/21026)| `Identifier.assigner`| _Equivalent_<br/>(36136/36137)| `Identifier.assigner`
| *9 of 9 elements used* | | *9 of 9 elements used* | | *9 of 9 elements used* | | *9 of 9 elements used* | | *9 of 9 elements used* 

