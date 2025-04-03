Comparison of 
Generated at Thursday, April 3, 2025 8:18:33 AM

### Contributor

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | Contributor |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Contributor` |
| Version | 5.0.0 |
| Description | Contributor Type: A contributor to the content of a knowledge asset, including authors, editors, reviewers, and endorsers. |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `2213` |
| Database Snapshot Count | `6` |
| Database Differential Count | `4` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Contributor` | `Contributor` | `Contributor` | Contributor | Contributor information | 0..* | Contributor |  |  |
| `Contributor.contact` | `Contributor.contact` | `contact` | Contributor.contact | Contact details of the contributor | 0..* | ContactDetail |  |  |
| `Contributor.extension` | `Contributor.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Contributor.id` | `Contributor.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Contributor.name` | `Contributor.name` | `name` | Contributor.name | Who contributed the content | 1..1 | string |  |  |
| `Contributor.type` | `Contributor.type` | `type` | Contributor.type | author \| editor \| reviewer \| endorser | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/contributor-type|5.0.0` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [Contributor](/docs/R3/ComplexTypes/Contributor.md)<br/> `http://hl7.org/fhir/StructureDefinition/Contributor\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `390`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `586`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Contributor](/docs/R4/ComplexTypes/Contributor.md)<br/> `http://hl7.org/fhir/StructureDefinition/Contributor\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1325`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1326`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Contributor](/docs/R4B/ComplexTypes/Contributor.md)<br/> `http://hl7.org/fhir/StructureDefinition/Contributor\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `898`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1127`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Contributor](/docs/R5/ComplexTypes/Contributor.md)<br/> `http://hl7.org/fhir/StructureDefinition/Contributor\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Contributor from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | [R3 Contributor](/docs/R3/ComplexTypes/Contributor.md)| Relationship | [R4 Contributor](/docs/R4/ComplexTypes/Contributor.md)| Relationship | [R4B Contributor](/docs/R4B/ComplexTypes/Contributor.md)| Relationship | R5 Contributor
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | `Contributor`| _Equivalent_<br/>(9264/9265)| `Contributor`| _Equivalent_<br/>(20616/20617)| `Contributor`| _Equivalent_<br/>(35741/35742)| **`Contributor`**
| | | `Contributor.id`| _Equivalent_<br/>(9266/9267)| `Contributor.id`| _Equivalent_<br/>(20618/20619)| `Contributor.id`| _Equivalent_<br/>(35743/35744)| **`Contributor.id`**
| | | `Contributor.extension`| →→→→ _Equivalent_ →→→→ <br/>(9268)<hr/>←←←← _RelatedTo_ ←←←← <br/>(9272)| `Contributor.extension`| _Equivalent_<br/>(20620/20621)| `Contributor.extension`| _Equivalent_<br/>(35745/35746)| **`Contributor.extension`**
| | | `Contributor.name`| →→→→ _RelatedTo_ →→→→ <br/>(1333)<hr/>←←←← _RelatedTo_ ←←←← <br/>(9272)| `Contributor.extension`| _Equivalent_<br/>(20620/20621)| `Contributor.extension`| _Equivalent_<br/>(35745/35746)| **`Contributor.extension`**
| | | `Contributor.type`| _Equivalent_<br/>(9270/9271)| `Contributor.type`| _Equivalent_<br/>(20622/20623)| `Contributor.type`| _Equivalent_<br/>(35747/35748)| **`Contributor.type`**
| | | `Contributor.name`| _Equivalent_<br/>(20615/20614)| `Contributor.name`| _Equivalent_<br/>(20624/20625)| `Contributor.name`| _Equivalent_<br/>(35749/35750)| **`Contributor.name`**
| | | `Contributor.contact`| _Equivalent_<br/>(9273/9274)| `Contributor.contact`| _Equivalent_<br/>(20626/20627)| `Contributor.contact`| _Equivalent_<br/>(35751/35752)| **`Contributor.contact`**
| | | *6 of 6 elements used* | | *6 of 6 elements used* | | *6 of 6 elements used* | | *6 of 6 elements used* 

