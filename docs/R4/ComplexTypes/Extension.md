Comparison of 
Generated at Tuesday, April 1, 2025 1:39:20 PM

### Extension

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | Extension |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Extension` |
| Version | 4.0.1 |
| Description | Base StructureDefinition for Extension Type: Optional Extension Element - found in all resources. |
| Status | `Active` |
| Artifact Class | `ComplexType` |
| Database Key | `1008` |
| Database Snapshot Count | `5` |
| Database Differential Count | `3` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Extension` | `Extension` | `Extension` | Extension | Optional Extensions Element | 0..* | Extension |  |  |
| `Extension.extension` | `Extension.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Extension.id` | `Extension.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Extension.url` | `Extension.url` | `url` | Extension.url | identifies the meaning of the extension | 1..1 | uri |  |  |
| `Extension.value[x]` | `Extension.value[x]` | `value[x]` | Extension.value[x] | Value of extension | 0..1 | Address, Age, Annotation, Attachment, base64Binary, boolean, canonical, code, CodeableConcept, Coding, ContactDetail, ContactPoint, Contributor, Count, DataRequirement, date, dateTime, decimal, Distance, Dosage, Duration, Expression, HumanName, id, Identifier, instant, integer, markdown, Meta, Money, oid, ParameterDefinition, Period, positiveInt, Quantity, Range, Ratio, Reference, RelatedArtifact, SampledData, Signature, string, time, Timing, TriggerDefinition, unsignedInt, uri, url, UsageContext, uuid |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Extension](/docs/R2/ComplexTypes/Extension.md)<br/> `http://hl7.org/fhir/StructureDefinition/Extension\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `54`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `224`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Extension](/docs/R3/ComplexTypes/Extension.md)<br/> `http://hl7.org/fhir/StructureDefinition/Extension\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `397`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `593`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Extension](/docs/R4/ComplexTypes/Extension.md)<br/> `http://hl7.org/fhir/StructureDefinition/Extension\|4.0.1` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1343`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1344`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Extension](/docs/R4B/ComplexTypes/Extension.md)<br/> `http://hl7.org/fhir/StructureDefinition/Extension\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `906`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1135`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Extension](/docs/R5/ComplexTypes/Extension.md)<br/> `http://hl7.org/fhir/StructureDefinition/Extension\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Extension from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Extension](/docs/R2/ComplexTypes/Extension.md)| Relationship | [R3 Extension](/docs/R3/ComplexTypes/Extension.md)| Relationship | R4 Extension| Relationship | [R4B Extension](/docs/R4B/ComplexTypes/Extension.md)| Relationship | [R5 Extension](/docs/R5/ComplexTypes/Extension.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `Extension`| _Equivalent_<br/>(2657/2658)| `Extension`| _Equivalent_<br/>(9586/9587)| **`Extension`**| _Equivalent_<br/>(20979/20980)| `Extension`| _Equivalent_<br/>(36090/36091)| `Extension`
| `Extension.id`| _Equivalent_<br/>(2659/2660)| `Extension.id`| _Equivalent_<br/>(9588/9589)| **`Extension.id`**| _Equivalent_<br/>(20981/20982)| `Extension.id`| _Equivalent_<br/>(36092/36093)| `Extension.id`
| `Extension.extension`| _Equivalent_<br/>(2661/2662)| `Extension.extension`| _Equivalent_<br/>(9590/9591)| **`Extension.extension`**| _Equivalent_<br/>(20983/20984)| `Extension.extension`| _Equivalent_<br/>(36094/36095)| `Extension.extension`
| `Extension.url`| _Equivalent_<br/>(2663/2664)| `Extension.url`| _Equivalent_<br/>(9592/9593)| **`Extension.url`**| _Equivalent_<br/>(20985/20986)| `Extension.url`| _Equivalent_<br/>(36096/36097)| `Extension.url`
| `Extension.value[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(2665)<hr/>←←←← _RelatedTo_ ←←←← <br/>(2666)| `Extension.value[x]`| →→→→ _RelatedTo_ →→→→ <br/>(9594)<hr/>←←←← _RelatedTo_ ←←←← <br/>(9595)| **`Extension.value[x]`**| →→→→ _RelatedTo_ →→→→ <br/>(20987)<hr/>←←←← _RelatedTo_ ←←←← <br/>(20988)| `Extension.value[x]`| →→→→ _RelatedTo_ →→→→ <br/>(36098)<hr/>←←←← _RelatedTo_ ←←←← <br/>(36099)| `Extension.value[x]`
| *5 of 5 elements used* | | *5 of 5 elements used* | | *5 of 5 elements used* | | *5 of 5 elements used* | | *5 of 5 elements used* 

