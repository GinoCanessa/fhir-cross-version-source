Comparison of 
Generated at Tuesday, April 1, 2025 1:39:27 PM

### CodeableReference

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| Stucture Name | CodeableReference |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/CodeableReference` |
| Version | 4.3.0 |
| Description | Base StructureDefinition for CodeableReference Type: A reference to a resource (by instance), or instead, a reference to a concept defined in a terminology or ontology (by class). |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `1601` |
| Database Snapshot Count | `5` |
| Database Differential Count | `3` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `CodeableReference` | `CodeableReference` | `CodeableReference` | CodeableReference | Reference to a resource or a concept | 0..* | CodeableReference |  |  |
| `CodeableReference.concept` | `CodeableReference.concept` | `concept` | CodeableReference.concept | Reference to a concept (by class) | 0..1 | CodeableConcept |  |  |
| `CodeableReference.extension` | `CodeableReference.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `CodeableReference.id` | `CodeableReference.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `CodeableReference.reference` | `CodeableReference.reference` | `reference` | CodeableReference.reference | Reference to a resource (by instance) | 0..1 | Reference |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [CodeableReference](/docs/R4B/ComplexTypes/CodeableReference.md)<br/> `http://hl7.org/fhir/StructureDefinition/CodeableReference\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `894`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1123`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CodeableReference](/docs/R5/ComplexTypes/CodeableReference.md)<br/> `http://hl7.org/fhir/StructureDefinition/CodeableReference\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition CodeableReference from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | R4B CodeableReference| Relationship | [R5 CodeableReference](/docs/R5/ComplexTypes/CodeableReference.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | **`CodeableReference`**| _Equivalent_<br/>(35689/35690)| `CodeableReference`
| | | | | | | **`CodeableReference.id`**| _Equivalent_<br/>(35691/35692)| `CodeableReference.id`
| | | | | | | **`CodeableReference.extension`**| _Equivalent_<br/>(35693/35694)| `CodeableReference.extension`
| | | | | | | **`CodeableReference.concept`**| _Equivalent_<br/>(35695/35696)| `CodeableReference.concept`
| | | | | | | **`CodeableReference.reference`**| _Equivalent_<br/>(35697/35698)| `CodeableReference.reference`
| | | | | | | *5 of 5 elements used* | | *5 of 5 elements used* 

