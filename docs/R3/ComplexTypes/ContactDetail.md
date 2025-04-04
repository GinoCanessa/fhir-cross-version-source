Comparison of 
Generated at Friday, April 4, 2025 2:58:38 PM

### ContactDetail

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | ContactDetail |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ContactDetail` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for ContactDetail Type |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `447` |
| Database Snapshot Count | `5` |
| Database Differential Count | `3` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ContactDetail` | `ContactDetail` | `ContactDetail` | ContactDetail | Contact information | 0..* | ContactDetail |  |  |
| `ContactDetail.extension` | `ContactDetail.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ContactDetail.id` | `ContactDetail.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `ContactDetail.name` | `ContactDetail.name` | `name` |  | Name of an individual to contact | 0..1 | string |  |  |
| `ContactDetail.telecom` | `ContactDetail.telecom` | `telecom` |  | Contact details for individual or organization | 0..* | ContactPoint |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [ContactDetail](/docs/R3/ComplexTypes/ContactDetail.md)<br/> `http://hl7.org/fhir/StructureDefinition/ContactDetail\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `388`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `584`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ContactDetail](/docs/R4/ComplexTypes/ContactDetail.md)<br/> `http://hl7.org/fhir/StructureDefinition/ContactDetail\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1321`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1322`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ContactDetail](/docs/R4B/ComplexTypes/ContactDetail.md)<br/> `http://hl7.org/fhir/StructureDefinition/ContactDetail\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `896`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1125`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ContactDetail](/docs/R5/ComplexTypes/ContactDetail.md)<br/> `http://hl7.org/fhir/StructureDefinition/ContactDetail\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition ContactDetail from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | R3 ContactDetail| Relationship | [R4 ContactDetail](/docs/R4/ComplexTypes/ContactDetail.md)| Relationship | [R4B ContactDetail](/docs/R4B/ComplexTypes/ContactDetail.md)| Relationship | [R5 ContactDetail](/docs/R5/ComplexTypes/ContactDetail.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | **`ContactDetail`**| _Equivalent_<br/>(9238/9239)| `ContactDetail`| _Equivalent_<br/>(20588/20589)| `ContactDetail`| _Equivalent_<br/>(35715/35716)| `ContactDetail`
| | | **`ContactDetail.id`**| _Equivalent_<br/>(9240/9241)| `ContactDetail.id`| _Equivalent_<br/>(20590/20591)| `ContactDetail.id`| _Equivalent_<br/>(35717/35718)| `ContactDetail.id`
| | | **`ContactDetail.extension`**| _Equivalent_<br/>(9242/9243)| `ContactDetail.extension`| _Equivalent_<br/>(20592/20593)| `ContactDetail.extension`| _Equivalent_<br/>(35719/35720)| `ContactDetail.extension`
| | | **`ContactDetail.name`**| _Equivalent_<br/>(9244/9245)| `ContactDetail.name`| _Equivalent_<br/>(20594/20595)| `ContactDetail.name`| _Equivalent_<br/>(35721/35722)| `ContactDetail.name`
| | | **`ContactDetail.telecom`**| _Equivalent_<br/>(9246/9247)| `ContactDetail.telecom`| _Equivalent_<br/>(20596/20597)| `ContactDetail.telecom`| _Equivalent_<br/>(35723/35724)| `ContactDetail.telecom`
| | | *5 of 5 elements used* | | *5 of 5 elements used* | | *5 of 5 elements used* | | *5 of 5 elements used* 

