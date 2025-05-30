Comparison of 
Generated at Monday, April 14, 2025 6:17:29 PM

### ContactDetail

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | ContactDetail |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ContactDetail` |
| Version | 4.0.1 |
| Description | Base StructureDefinition for ContactDetail Type: Specifies contact information for a person or organization. |
| Status | `Active` |
| Artifact Class | `ComplexType` |
| Database Key | `997` |
| Database Snapshot Count | `5` |
| Database Differential Count | `3` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ContactDetail` | `ContactDetail` | `ContactDetail` | ContactDetail | Contact information | 0..* | ContactDetail |  |  |
| `ContactDetail.extension` | `ContactDetail.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ContactDetail.id` | `ContactDetail.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ContactDetail.name` | `ContactDetail.name` | `name` | ContactDetail.name | Name of an individual to contact | 0..1 | string |  |  |
| `ContactDetail.telecom` | `ContactDetail.telecom` | `telecom` | ContactDetail.telecom | Contact details for individual or organization | 0..* | ContactPoint |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [ContactDetail](/docs/R3/ComplexTypes/ContactDetail.md)<br/> `http://hl7.org/fhir/StructureDefinition/ContactDetail\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `388`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `584`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ContactDetail](/docs/R4/ComplexTypes/ContactDetail.md)<br/> `http://hl7.org/fhir/StructureDefinition/ContactDetail\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1321`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1322`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ContactDetail](/docs/R4B/ComplexTypes/ContactDetail.md)<br/> `http://hl7.org/fhir/StructureDefinition/ContactDetail\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `896`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1125`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ContactDetail](/docs/R5/ComplexTypes/ContactDetail.md)<br/> `http://hl7.org/fhir/StructureDefinition/ContactDetail\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition ContactDetail from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | [R3 ContactDetail](/docs/R3/ComplexTypes/ContactDetail.md)| Relationship | R4 ContactDetail| Relationship | [R4B ContactDetail](/docs/R4B/ComplexTypes/ContactDetail.md)| Relationship | [R5 ContactDetail](/docs/R5/ComplexTypes/ContactDetail.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | `ContactDetail`| _Equivalent_<br/>(9238/9239)| **`ContactDetail`**| _Equivalent_<br/>(20588/20589)| `ContactDetail`| _Equivalent_<br/>(35715/35716)| `ContactDetail`
| | | `ContactDetail.id`| _Equivalent_<br/>(9240/9241)| **`ContactDetail.id`**| _Equivalent_<br/>(20590/20591)| `ContactDetail.id`| _Equivalent_<br/>(35717/35718)| `ContactDetail.id`
| | | `ContactDetail.extension`| _Equivalent_<br/>(9242/9243)| **`ContactDetail.extension`**| _Equivalent_<br/>(20592/20593)| `ContactDetail.extension`| _Equivalent_<br/>(35719/35720)| `ContactDetail.extension`
| | | `ContactDetail.name`| _Equivalent_<br/>(9244/9245)| **`ContactDetail.name`**| _Equivalent_<br/>(20594/20595)| `ContactDetail.name`| _Equivalent_<br/>(35721/35722)| `ContactDetail.name`
| | | `ContactDetail.telecom`| _Equivalent_<br/>(9246/9247)| **`ContactDetail.telecom`**| _Equivalent_<br/>(20596/20597)| `ContactDetail.telecom`| _Equivalent_<br/>(35723/35724)| `ContactDetail.telecom`
| | | *5 of 5 elements used* | | *5 of 5 elements used* | | *5 of 5 elements used* | | *5 of 5 elements used* 

