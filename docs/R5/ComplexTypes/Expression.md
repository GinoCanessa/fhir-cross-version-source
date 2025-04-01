Comparison of 
Generated at Tuesday, April 1, 2025 1:39:35 PM

### Expression

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | Expression |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Expression` |
| Version | 5.0.0 |
| Description | Expression Type: A expression that is evaluated in a specified context and returns a value. The context of use of the expression must specify the context in which the expression is evaluated, and how the result of the expression is used. |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `2222` |
| Database Snapshot Count | `8` |
| Database Differential Count | `6` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Expression` | `Expression` | `Expression` | Expression | An expression that can be used to generate a value | 0..* | Expression |  |  |
| `Expression.description` | `Expression.description` | `description` | Expression.description | Natural language description of the condition | 0..1 | string |  |  |
| `Expression.expression` | `Expression.expression` | `expression` | Expression.expression | Expression in specified language | 0..1 | string |  |  |
| `Expression.extension` | `Expression.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Expression.id` | `Expression.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Expression.language` | `Expression.language` | `language` | Expression.language | text/cql \| text/fhirpath \| application/x-fhir-query \| etc. | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/mimetypes` |
| `Expression.name` | `Expression.name` | `name` | Expression.name | Short name assigned to expression for reuse | 0..1 | code |  |  |
| `Expression.reference` | `Expression.reference` | `reference` | Expression.reference | Where the expression is found | 0..1 | uri |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [Expression](/docs/R4/ComplexTypes/Expression.md)<br/> `http://hl7.org/fhir/StructureDefinition/Expression\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1341`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1342`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Expression](/docs/R4B/ComplexTypes/Expression.md)<br/> `http://hl7.org/fhir/StructureDefinition/Expression\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `905`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1134`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Expression](/docs/R5/ComplexTypes/Expression.md)<br/> `http://hl7.org/fhir/StructureDefinition/Expression\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Expression from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | [R4 Expression](/docs/R4/ComplexTypes/Expression.md)| Relationship | [R4B Expression](/docs/R4B/ComplexTypes/Expression.md)| Relationship | R5 Expression
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | `Expression`| _Equivalent_<br/>(20963/20964)| `Expression`| _Equivalent_<br/>(36074/36075)| **`Expression`**
| | | | | `Expression.id`| _Equivalent_<br/>(20965/20966)| `Expression.id`| _Equivalent_<br/>(36076/36077)| **`Expression.id`**
| | | | | `Expression.extension`| _Equivalent_<br/>(20967/20968)| `Expression.extension`| _Equivalent_<br/>(36078/36079)| **`Expression.extension`**
| | | | | `Expression.description`| _Equivalent_<br/>(20969/20970)| `Expression.description`| _Equivalent_<br/>(36080/36081)| **`Expression.description`**
| | | | | `Expression.name`| _Equivalent_<br/>(20971/20972)| `Expression.name`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36082)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(36083)| **`Expression.name`**
| | | | | `Expression.language`| _Equivalent_<br/>(20973/20974)| `Expression.language`| →→→→ _Equivalent_ →→→→ <br/>(36084)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(36085)| **`Expression.language`**
| | | | | `Expression.expression`| _Equivalent_<br/>(20975/20976)| `Expression.expression`| _Equivalent_<br/>(36086/36087)| **`Expression.expression`**
| | | | | `Expression.reference`| _Equivalent_<br/>(20977/20978)| `Expression.reference`| _Equivalent_<br/>(36088/36089)| **`Expression.reference`**
| | | | | *8 of 8 elements used* | | *8 of 8 elements used* | | *8 of 8 elements used* 

