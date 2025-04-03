Comparison of 
Generated at Thursday, April 3, 2025 8:18:33 AM

### Annotation

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | Annotation |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Annotation` |
| Version | 5.0.0 |
| Description | Annotation Type: A  text note which also  contains information about who made the statement and when. |
| Status | `Active` |
| Artifact Class | `ComplexType` |
| Database Key | `2202` |
| Database Snapshot Count | `6` |
| Database Differential Count | `4` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Annotation` | `Annotation` | `Annotation` | Annotation | Text node with attribution | 0..* | Annotation |  |  |
| `Annotation.author[x]` | `Annotation.author[x]` | `author[x]` | Annotation.author[x] | Individual responsible for the annotation | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson), string |  |  |
| `Annotation.extension` | `Annotation.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Annotation.id` | `Annotation.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Annotation.text` | `Annotation.text` | `text` | Annotation.text | The annotation  - text content (as markdown) | 1..1 | markdown |  |  |
| `Annotation.time` | `Annotation.time` | `time` | Annotation.time | When the annotation was made | 0..1 | dateTime |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Annotation](/docs/R2/ComplexTypes/Annotation.md)<br/> `http://hl7.org/fhir/StructureDefinition/Annotation\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `48`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `215`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Annotation](/docs/R3/ComplexTypes/Annotation.md)<br/> `http://hl7.org/fhir/StructureDefinition/Annotation\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `384`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `580`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Annotation](/docs/R4/ComplexTypes/Annotation.md)<br/> `http://hl7.org/fhir/StructureDefinition/Annotation\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1311`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1312`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Annotation](/docs/R4B/ComplexTypes/Annotation.md)<br/> `http://hl7.org/fhir/StructureDefinition/Annotation\|4.3.0` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `891`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1120`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Annotation](/docs/R5/ComplexTypes/Annotation.md)<br/> `http://hl7.org/fhir/StructureDefinition/Annotation\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Annotation from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Annotation](/docs/R2/ComplexTypes/Annotation.md)| Relationship | [R3 Annotation](/docs/R3/ComplexTypes/Annotation.md)| Relationship | [R4 Annotation](/docs/R4/ComplexTypes/Annotation.md)| Relationship | [R4B Annotation](/docs/R4B/ComplexTypes/Annotation.md)| Relationship | R5 Annotation
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `Annotation`| _Equivalent_<br/>(2441/2442)| `Annotation`| _Equivalent_<br/>(9170/9171)| `Annotation`| _Equivalent_<br/>(20520/20521)| `Annotation`| _Equivalent_<br/>(35637/35638)| **`Annotation`**
| `Annotation.id`| _Equivalent_<br/>(2443/2444)| `Annotation.id`| _Equivalent_<br/>(9172/9173)| `Annotation.id`| _Equivalent_<br/>(20522/20523)| `Annotation.id`| _Equivalent_<br/>(35639/35640)| **`Annotation.id`**
| `Annotation.extension`| _Equivalent_<br/>(2445/2446)| `Annotation.extension`| _Equivalent_<br/>(9174/9175)| `Annotation.extension`| _Equivalent_<br/>(20524/20525)| `Annotation.extension`| _Equivalent_<br/>(35641/35642)| **`Annotation.extension`**
| `Annotation.author[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(2447)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2448)| `Annotation.author[x]`| →→→→ _RelatedTo_ →→→→ <br/>(9176)<hr/>←←←← _RelatedTo_ ←←←← <br/>(9177)| `Annotation.author[x]`| _Equivalent_<br/>(20526/20527)| `Annotation.author[x]`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(35643)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(35644)| **`Annotation.author[x]`**
| `Annotation.time`| _Equivalent_<br/>(2449/2450)| `Annotation.time`| _Equivalent_<br/>(9178/9179)| `Annotation.time`| _Equivalent_<br/>(20528/20529)| `Annotation.time`| _Equivalent_<br/>(35645/35646)| **`Annotation.time`**
| `Annotation.text`| _Equivalent_<br/>(2451/2452)| `Annotation.text`| _Equivalent_<br/>(9180/9181)| `Annotation.text`| _Equivalent_<br/>(20530/20531)| `Annotation.text`| _Equivalent_<br/>(35647/35648)| **`Annotation.text`**
| *6 of 6 elements used* | | *6 of 6 elements used* | | *6 of 6 elements used* | | *6 of 6 elements used* | | *6 of 6 elements used* 

