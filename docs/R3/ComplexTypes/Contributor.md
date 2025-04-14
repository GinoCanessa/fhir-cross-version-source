Comparison of 
Generated at Monday, April 14, 2025 6:17:21 PM

### Contributor

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | Contributor |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Contributor` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for Contributor Type |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `449` |
| Database Snapshot Count | `6` |
| Database Differential Count | `4` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Contributor` | `Contributor` | `Contributor` | Contributor | Contributor information | 0..* | Contributor |  |  |
| `Contributor.contact` | `Contributor.contact` | `contact` |  | Contact details of the contributor | 0..* | ContactDetail |  |  |
| `Contributor.extension` | `Contributor.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Contributor.id` | `Contributor.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Contributor.name` | `Contributor.name` | `name` |  | Who contributed the content | 1..1 | string |  |  |
| `Contributor.type` | `Contributor.type` | `type` |  | author \| editor \| reviewer \| endorser | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/contributor-type` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [Contributor](/docs/R3/ComplexTypes/Contributor.md)<br/> `http://hl7.org/fhir/StructureDefinition/Contributor\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `390`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `586`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Contributor](/docs/R4/ComplexTypes/Contributor.md)<br/> `http://hl7.org/fhir/StructureDefinition/Contributor\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1325`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1326`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Contributor](/docs/R4B/ComplexTypes/Contributor.md)<br/> `http://hl7.org/fhir/StructureDefinition/Contributor\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `898`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1127`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Contributor](/docs/R5/ComplexTypes/Contributor.md)<br/> `http://hl7.org/fhir/StructureDefinition/Contributor\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Contributor from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | R3 Contributor| Relationship | [R4 Contributor](/docs/R4/ComplexTypes/Contributor.md)| Relationship | [R4B Contributor](/docs/R4B/ComplexTypes/Contributor.md)| Relationship | [R5 Contributor](/docs/R5/ComplexTypes/Contributor.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | **`Contributor`**| _Equivalent_<br/>(9264/9265)| `Contributor`| _Equivalent_<br/>(20616/20617)| `Contributor`| _Equivalent_<br/>(35741/35742)| `Contributor`
| | | **`Contributor.id`**| _Equivalent_<br/>(9266/9267)| `Contributor.id`| _Equivalent_<br/>(20618/20619)| `Contributor.id`| _Equivalent_<br/>(35743/35744)| `Contributor.id`
| | | **`Contributor.extension`**| →→→→ _Equivalent_ →→→→ <br/>(9268)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(9269)| `Contributor.extension`| _Equivalent_<br/>(20620/20621)| `Contributor.extension`| _Equivalent_<br/>(35745/35746)| `Contributor.extension`
| | | **`Contributor.type`**| _Equivalent_<br/>(9270/9271)| `Contributor.type`| _Equivalent_<br/>(20622/20623)| `Contributor.type`| _Equivalent_<br/>(35747/35748)| `Contributor.type`
| | | **`Contributor.name`**| →→→→ _RelatedTo_ →→→→ <br/>(1333)<hr/>←←←← _RelatedTo_ ←←←← <br/>(9272)| `Contributor.extension`| _Equivalent_<br/>(20620/20621)| `Contributor.extension`| _Equivalent_<br/>(35745/35746)| `Contributor.extension`
| | | **`Contributor.name`**| _Equivalent_<br/>(20615/20614)| `Contributor.name`| _Equivalent_<br/>(20624/20625)| `Contributor.name`| _Equivalent_<br/>(35749/35750)| `Contributor.name`
| | | **`Contributor.contact`**| _Equivalent_<br/>(9273/9274)| `Contributor.contact`| _Equivalent_<br/>(20626/20627)| `Contributor.contact`| _Equivalent_<br/>(35751/35752)| `Contributor.contact`
| | | *6 of 6 elements used* | | *6 of 6 elements used* | | *6 of 6 elements used* | | *6 of 6 elements used* 

