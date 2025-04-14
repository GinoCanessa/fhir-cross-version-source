Comparison of 
Generated at Monday, April 14, 2025 6:17:36 PM

### Population

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| Stucture Name | Population |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Population` |
| Version | 4.3.0 |
| Description | Base StructureDefinition for Population Type: A populatioof people with some set of grouping criteria. |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `1624` |
| Database Snapshot Count | `8` |
| Database Differential Count | `5` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Population` | `Population` | `Population` | Population | A definition of a set of people that apply to some clinically related context, for example people contraindicated for a certain medication | 0..* | Population |  |  |
| `Population.age[x]` | `Population.age[x]` | `age[x]` | Population.age[x] | The age of the specific population | 0..1 | CodeableConcept, Range |  |  |
| `Population.extension` | `Population.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Population.gender` | `Population.gender` | `gender` | Population.gender | The gender of the specific population | 0..1 | CodeableConcept |  |  |
| `Population.id` | `Population.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Population.modifierExtension` | `Population.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Population.physiologicalCondition` | `Population.physiologicalCondition` | `physiologicalCondition` | Population.physiologicalCondition | The existing physiological conditions of the specific population to which this applies | 0..1 | CodeableConcept |  |  |
| `Population.race` | `Population.race` | `race` | Population.race | Race of the specific population | 0..1 | CodeableConcept |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [Population](/docs/R4/ComplexTypes/Population.md)<br/> `http://hl7.org/fhir/StructureDefinition/Population\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1361`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1362`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Population](/docs/R4B/ComplexTypes/Population.md)<br/> `http://hl7.org/fhir/StructureDefinition/Population\|4.3.0` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | 
### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Population from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | [R4 Population](/docs/R4/ComplexTypes/Population.md)| Relationship | R4B Population| Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | `Population`| _Equivalent_<br/>(21115/21116)| **`Population`**| | | 
| | | | | `Population.id`| _Equivalent_<br/>(21117/21118)| **`Population.id`**| | | 
| | | | | `Population.extension`| _Equivalent_<br/>(21119/21120)| **`Population.extension`**| | | 
| | | | | `Population.modifierExtension`| _Equivalent_<br/>(21121/21122)| **`Population.modifierExtension`**| | | 
| | | | | `Population.age[x]`| _Equivalent_<br/>(21123/21124)| **`Population.age[x]`**| | | 
| | | | | `Population.gender`| _Equivalent_<br/>(21125/21126)| **`Population.gender`**| | | 
| | | | | `Population.race`| _Equivalent_<br/>(21127/21128)| **`Population.race`**| | | 
| | | | | `Population.physiologicalCondition`| _Equivalent_<br/>(21129/21130)| **`Population.physiologicalCondition`**| | | 
| | | | | *8 of 8 elements used* | | *8 of 8 elements used* | | 

