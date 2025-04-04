Comparison of 
Generated at Friday, April 4, 2025 2:59:00 PM

### RelatedArtifact

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | RelatedArtifact |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/RelatedArtifact` |
| Version | 5.0.0 |
| Description | RelatedArtifact Type: Related artifacts such as additional documentation, justification, or bibliographic references. |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `2241` |
| Database Snapshot Count | `13` |
| Database Differential Count | `11` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `RelatedArtifact` | `RelatedArtifact` | `RelatedArtifact` | RelatedArtifact | Related artifacts for a knowledge resource | 0..* | RelatedArtifact |  |  |
| `RelatedArtifact.citation` | `RelatedArtifact.citation` | `citation` | RelatedArtifact.citation | Bibliographic citation for the artifact | 0..1 | markdown |  |  |
| `RelatedArtifact.classifier` | `RelatedArtifact.classifier` | `classifier` | RelatedArtifact.classifier | Additional classifiers | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/citation-artifact-classifier` |
| `RelatedArtifact.display` | `RelatedArtifact.display` | `display` | RelatedArtifact.display | Brief description of the related artifact | 0..1 | string |  |  |
| `RelatedArtifact.document` | `RelatedArtifact.document` | `document` | RelatedArtifact.document | What document is being referenced | 0..1 | Attachment |  |  |
| `RelatedArtifact.extension` | `RelatedArtifact.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `RelatedArtifact.id` | `RelatedArtifact.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `RelatedArtifact.label` | `RelatedArtifact.label` | `label` | RelatedArtifact.label | Short label | 0..1 | string |  |  |
| `RelatedArtifact.publicationDate` | `RelatedArtifact.publicationDate` | `publicationDate` | RelatedArtifact.publicationDate | Date of publication of the artifact being referred to | 0..1 | date |  |  |
| `RelatedArtifact.publicationStatus` | `RelatedArtifact.publicationStatus` | `publicationStatus` | RelatedArtifact.publicationStatus | draft \| active \| retired \| unknown | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status|5.0.0` |
| `RelatedArtifact.resource` | `RelatedArtifact.resource` | `resource` | RelatedArtifact.resource | What artifact is being referenced | 0..1 | canonical(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `RelatedArtifact.resourceReference` | `RelatedArtifact.resourceReference` | `resourceReference` | RelatedArtifact.resourceReference | What artifact, if not a conformance resource | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `RelatedArtifact.type` | `RelatedArtifact.type` | `type` | RelatedArtifact.type | documentation \| justification \| citation \| predecessor \| successor \| derived-from \| depends-on \| composed-of \| part-of \| amends \| amended-with \| appends \| appended-with \| cites \| cited-by \| comments-on \| comment-in \| contains \| contained-in \| corrects \| correction-in \| replaces \| replaced-with \| retracts \| retracted-by \| signs \| similar-to \| supports \| supported-with \| transforms \| transformed-into \| transformed-with \| documents \| specification-of \| created-with \| cite-as | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/related-artifact-type|5.0.0` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [RelatedArtifact](/docs/R3/ComplexTypes/RelatedArtifact.md)<br/> `http://hl7.org/fhir/StructureDefinition/RelatedArtifact\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `409`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `605`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RelatedArtifact](/docs/R4/ComplexTypes/RelatedArtifact.md)<br/> `http://hl7.org/fhir/StructureDefinition/RelatedArtifact\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1375`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1376`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RelatedArtifact](/docs/R4B/ComplexTypes/RelatedArtifact.md)<br/> `http://hl7.org/fhir/StructureDefinition/RelatedArtifact\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `920`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1149`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RelatedArtifact](/docs/R5/ComplexTypes/RelatedArtifact.md)<br/> `http://hl7.org/fhir/StructureDefinition/RelatedArtifact\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition RelatedArtifact from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | [R3 RelatedArtifact](/docs/R3/ComplexTypes/RelatedArtifact.md)| Relationship | [R4 RelatedArtifact](/docs/R4/ComplexTypes/RelatedArtifact.md)| Relationship | [R4B RelatedArtifact](/docs/R4B/ComplexTypes/RelatedArtifact.md)| Relationship | R5 RelatedArtifact
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | `RelatedArtifact`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9760)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(9761)| `RelatedArtifact`| _Equivalent_<br/>(21229/21230)| `RelatedArtifact`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36299)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(36300)| **`RelatedArtifact`**
| | | `RelatedArtifact.id`| _Equivalent_<br/>(9762/9763)| `RelatedArtifact.id`| _Equivalent_<br/>(21231/21232)| `RelatedArtifact.id`| _Equivalent_<br/>(36301/36302)| **`RelatedArtifact.id`**
| | | `RelatedArtifact.extension`| _Equivalent_<br/>(9764/9765)| `RelatedArtifact.extension`| _Equivalent_<br/>(21233/21234)| `RelatedArtifact.extension`| _Equivalent_<br/>(36303/36304)| **`RelatedArtifact.extension`**
| | | `RelatedArtifact.type`| _Equivalent_<br/>(9766/9767)| `RelatedArtifact.type`| _Equivalent_<br/>(21235/21236)| `RelatedArtifact.type`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36305)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(36306)| **`RelatedArtifact.type`**
| | | | | | | | | **`RelatedArtifact.classifier`**
| | | | | `RelatedArtifact.label`| _Equivalent_<br/>(21237/21238)| `RelatedArtifact.label`| _Equivalent_<br/>(36307/36308)| **`RelatedArtifact.label`**
| | | `RelatedArtifact.display`| _Equivalent_<br/>(9768/9769)| `RelatedArtifact.display`| _Equivalent_<br/>(21239/21240)| `RelatedArtifact.display`| _Equivalent_<br/>(36309/36310)| **`RelatedArtifact.display`**
| | | `RelatedArtifact.citation`| _Equivalent_<br/>(9770/9771)| `RelatedArtifact.citation`| _Equivalent_<br/>(21241/21242)| `RelatedArtifact.citation`| _Equivalent_<br/>(36311/36312)| **`RelatedArtifact.citation`**
| | | `RelatedArtifact.document`| _Equivalent_<br/>(9774/9775)| `RelatedArtifact.document`| _Equivalent_<br/>(21245/21246)| `RelatedArtifact.document`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36314)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(36315)| **`RelatedArtifact.document`**
| | | `RelatedArtifact.resource`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9776)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(9777)| `RelatedArtifact.resource`| _Equivalent_<br/>(21247/21248)| `RelatedArtifact.resource`| _Equivalent_<br/>(36316/36317)| **`RelatedArtifact.resource`**
| | | | | | | | | **`RelatedArtifact.resourceReference`**
| | | | | | | | | **`RelatedArtifact.publicationStatus`**
| | | | | | | | | **`RelatedArtifact.publicationDate`**
| | | *8 of 9 elements used* <br/>remaining elements:<br/>`RelatedArtifact.url`| | *9 of 10 elements used* <br/>remaining elements:<br/>`RelatedArtifact.url`| | *9 of 10 elements used* <br/>remaining elements:<br/>`RelatedArtifact.url`| | *13 of 13 elements used* 

