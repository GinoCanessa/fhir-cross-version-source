Comparison of 
Generated at Thursday, April 3, 2025 8:18:06 AM

### Binary

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | Binary |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Binary` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for Binary Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `47` |
| Database Snapshot Count | `7` |
| Database Differential Count | `3` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Binary` | `Binary` | `Binary` | Binary | Pure binary content defined by some other format than FHIR | 0..* | Binary |  |  |
| `Binary.content` | `Binary.content` | `content` |  | The actual content | 1..1 | base64Binary |  |  |
| `Binary.contentType` | `Binary.contentType` | `contentType` |  | MimeType of the binary content | 1..1 | code | `Required` | `http://www.rfc-editor.org/bcp/bcp13.txt` |
| `Binary.id` | `Binary.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Binary.implicitRules` | `Binary.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Binary.language` | `Binary.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `Binary.meta` | `Binary.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Binary](/docs/R2/Resources/Binary.md)<br/> `http://hl7.org/fhir/StructureDefinition/Binary\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `78`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `244`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Binary](/docs/R3/Resources/Binary.md)<br/> `http://hl7.org/fhir/StructureDefinition/Binary\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `423`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `619`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Binary](/docs/R4/Resources/Binary.md)<br/> `http://hl7.org/fhir/StructureDefinition/Binary\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1403`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1404`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Binary](/docs/R4B/Resources/Binary.md)<br/> `http://hl7.org/fhir/StructureDefinition/Binary\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `926`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1155`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Binary](/docs/R5/Resources/Binary.md)<br/> `http://hl7.org/fhir/StructureDefinition/Binary\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Binary from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 Binary| Relationship | [R3 Binary](/docs/R3/Resources/Binary.md)| Relationship | [R4 Binary](/docs/R4/Resources/Binary.md)| Relationship | [R4B Binary](/docs/R4B/Resources/Binary.md)| Relationship | [R5 Binary](/docs/R5/Resources/Binary.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`Binary`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3146)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3147)| `Binary`| _Equivalent_<br/>(10437/10438)| `Binary`| _Equivalent_<br/>(22002/22003)| `Binary`| _Equivalent_<br/>(37079/37080)| `Binary`
| **`Binary.id`**| _Equivalent_<br/>(3148/3149)| `Binary.id`| _Equivalent_<br/>(10439/10440)| `Binary.id`| _Equivalent_<br/>(22004/22005)| `Binary.id`| _Equivalent_<br/>(37081/37082)| `Binary.id`
| **`Binary.meta`**| _Equivalent_<br/>(3150/3151)| `Binary.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10441)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10442)| `Binary.meta`| _Equivalent_<br/>(22006/22007)| `Binary.meta`| _Equivalent_<br/>(37083/37084)| `Binary.meta`
| **`Binary.implicitRules`**| _Equivalent_<br/>(3152/3153)| `Binary.implicitRules`| _Equivalent_<br/>(10443/10444)| `Binary.implicitRules`| _Equivalent_<br/>(22008/22009)| `Binary.implicitRules`| _Equivalent_<br/>(37085/37086)| `Binary.implicitRules`
| **`Binary.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3154)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(3155)| `Binary.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10445)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(10446)| `Binary.language`| _Equivalent_<br/>(22010/22011)| `Binary.language`| _Equivalent_<br/>(37087/37088)| `Binary.language`
| **`Binary.contentType`**| _Equivalent_<br/>(3156/3157)| `Binary.contentType`| _Equivalent_<br/>(10447/10448)| `Binary.contentType`| _Equivalent_<br/>(22012/22013)| `Binary.contentType`| _Equivalent_<br/>(37089/37090)| `Binary.contentType`
| **`Binary.content`**| _Equivalent_<br/>(3158/3159)| `Binary.content`| →→→→ _Equivalent_ →→→→ <br/>(820)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1358)| `Binary.data`| _Equivalent_<br/>(22016/22017)| `Binary.data`| _Equivalent_<br/>(37093/37094)| `Binary.data`
| *7 of 7 elements used* | | *7 of 8 elements used* <br/>remaining elements:<br/>`Binary.securityContext`| | *7 of 8 elements used* <br/>remaining elements:<br/>`Binary.securityContext`| | *7 of 8 elements used* <br/>remaining elements:<br/>`Binary.securityContext`| | *7 of 8 elements used* <br/>remaining elements:<br/>`Binary.securityContext`

