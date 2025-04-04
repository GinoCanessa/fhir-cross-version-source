Comparison of 
Generated at Friday, April 4, 2025 2:58:52 PM

### Reference

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| Stucture Name | Reference |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Reference` |
| Version | 4.3.0 |
| Description | Base StructureDefinition for Reference Type: A reference from one resource to another. |
| Status | `Active` |
| Artifact Class | `ComplexType` |
| Database Key | `1631` |
| Database Snapshot Count | `7` |
| Database Differential Count | `5` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Reference` | `Reference` | `Reference` | Reference | A reference from one resource to another | 0..* | Reference |  |  |
| `Reference.display` | `Reference.display` | `display` | Reference.display | Text alternative for the resource | 0..1 | string |  |  |
| `Reference.extension` | `Reference.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Reference.id` | `Reference.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Reference.identifier` | `Reference.identifier` | `identifier` | Reference.identifier | Logical reference, when literal reference is not known | 0..1 | Identifier |  |  |
| `Reference.reference` | `Reference.reference` | `reference` | Reference.reference | Literal reference, Relative, internal or absolute URL | 0..1 | string |  |  |
| `Reference.type` | `Reference.type` | `type` | Reference.type | Type the reference refers to (e.g. "Patient") | 0..1 | uri | `Extensible` | `http://hl7.org/fhir/ValueSet/resource-types` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Reference](/docs/R2/ComplexTypes/Reference.md)<br/> `http://hl7.org/fhir/StructureDefinition/Reference\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `68`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `234`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Reference](/docs/R3/ComplexTypes/Reference.md)<br/> `http://hl7.org/fhir/StructureDefinition/Reference\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `408`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `604`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Reference](/docs/R4/ComplexTypes/Reference.md)<br/> `http://hl7.org/fhir/StructureDefinition/Reference\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1373`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1374`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Reference](/docs/R4B/ComplexTypes/Reference.md)<br/> `http://hl7.org/fhir/StructureDefinition/Reference\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `919`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1148`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Reference](/docs/R5/ComplexTypes/Reference.md)<br/> `http://hl7.org/fhir/StructureDefinition/Reference\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Reference from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Reference](/docs/R2/ComplexTypes/Reference.md)| Relationship | [R3 Reference](/docs/R3/ComplexTypes/Reference.md)| Relationship | [R4 Reference](/docs/R4/ComplexTypes/Reference.md)| Relationship | R4B Reference| Relationship | [R5 Reference](/docs/R5/ComplexTypes/Reference.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `Reference`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(2815)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2816)| `Reference`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9748)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(9749)| `Reference`| _Equivalent_<br/>(21214/21215)| **`Reference`**| _Equivalent_<br/>(36285/36286)| `Reference`
| `Reference.id`| _Equivalent_<br/>(2817/2818)| `Reference.id`| _Equivalent_<br/>(9750/9751)| `Reference.id`| _Equivalent_<br/>(21216/21217)| **`Reference.id`**| _Equivalent_<br/>(36287/36288)| `Reference.id`
| `Reference.extension`| _Equivalent_<br/>(2819/2820)| `Reference.extension`| _Equivalent_<br/>(9752/9753)| `Reference.extension`| _Equivalent_<br/>(21218/21219)| **`Reference.extension`**| _Equivalent_<br/>(36289/36290)| `Reference.extension`
| `Reference.reference`| _Equivalent_<br/>(2821/2822)| `Reference.reference`| _Equivalent_<br/>(9754/9755)| `Reference.reference`| _Equivalent_<br/>(21220/21221)| **`Reference.reference`**| _Equivalent_<br/>(36291/36292)| `Reference.reference`
| | | | | `Reference.type`| _Equivalent_<br/>(21222/21223)| **`Reference.type`**| _Equivalent_<br/>(36293/36294)| `Reference.type`
| | | `Reference.identifier`| _Equivalent_<br/>(9756/9757)| `Reference.identifier`| _Equivalent_<br/>(21224/21225)| **`Reference.identifier`**| _Equivalent_<br/>(36295/36296)| `Reference.identifier`
| `Reference.display`| _Equivalent_<br/>(2823/2824)| `Reference.display`| _Equivalent_<br/>(9758/9759)| `Reference.display`| _Equivalent_<br/>(21226/21227)| **`Reference.display`**| _Equivalent_<br/>(36297/36298)| `Reference.display`
| *5 of 5 elements used* | | *6 of 6 elements used* | | *7 of 7 elements used* | | *7 of 7 elements used* | | *7 of 7 elements used* 

