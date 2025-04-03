Comparison of 
Generated at Thursday, April 3, 2025 8:18:34 AM

### Binary

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | Binary |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Binary` |
| Version | 5.0.0 |
| Description | A resource that represents the data of a single raw artifact as digital content accessible in its native format.  A Binary resource can contain any content, whether text, image, pdf, zip archive, etc. |
| Status | `Active` |
| Artifact Class | `Resource` |
| Database Key | `2259` |
| Database Snapshot Count | `8` |
| Database Differential Count | `4` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Binary` | `Binary` | `Binary` | Binary | Pure binary content defined by a format other than FHIR | 0..* | Binary |  |  |
| `Binary.contentType` | `Binary.contentType` | `contentType` | Binary.contentType | MimeType of the binary content | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/mimetypes|5.0.0` |
| `Binary.data` | `Binary.data` | `data` | Binary.data | The actual content | 0..1 | base64Binary |  |  |
| `Binary.id` | `Binary.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Binary.implicitRules` | `Binary.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Binary.language` | `Binary.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `Binary.meta` | `Binary.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Binary.securityContext` | `Binary.securityContext` | `securityContext` | Binary.securityContext | Identifies another resource to use as proxy when enforcing access control | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Binary](/docs/R2/Resources/Binary.md)<br/> `http://hl7.org/fhir/StructureDefinition/Binary\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `78`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `244`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Binary](/docs/R3/Resources/Binary.md)<br/> `http://hl7.org/fhir/StructureDefinition/Binary\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `423`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `619`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Binary](/docs/R4/Resources/Binary.md)<br/> `http://hl7.org/fhir/StructureDefinition/Binary\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1403`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1404`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Binary](/docs/R4B/Resources/Binary.md)<br/> `http://hl7.org/fhir/StructureDefinition/Binary\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `926`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1155`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Binary](/docs/R5/Resources/Binary.md)<br/> `http://hl7.org/fhir/StructureDefinition/Binary\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Binary from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Binary](/docs/R2/Resources/Binary.md)| Relationship | [R3 Binary](/docs/R3/Resources/Binary.md)| Relationship | [R4 Binary](/docs/R4/Resources/Binary.md)| Relationship | [R4B Binary](/docs/R4B/Resources/Binary.md)| Relationship | R5 Binary
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `Binary`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3146)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3147)| `Binary`| _Equivalent_<br/>(10437/10438)| `Binary`| _Equivalent_<br/>(22002/22003)| `Binary`| _Equivalent_<br/>(37079/37080)| **`Binary`**
| `Binary.id`| _Equivalent_<br/>(3148/3149)| `Binary.id`| _Equivalent_<br/>(10439/10440)| `Binary.id`| _Equivalent_<br/>(22004/22005)| `Binary.id`| _Equivalent_<br/>(37081/37082)| **`Binary.id`**
| `Binary.meta`| _Equivalent_<br/>(3150/3151)| `Binary.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10441)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10442)| `Binary.meta`| _Equivalent_<br/>(22006/22007)| `Binary.meta`| _Equivalent_<br/>(37083/37084)| **`Binary.meta`**
| `Binary.implicitRules`| _Equivalent_<br/>(3152/3153)| `Binary.implicitRules`| _Equivalent_<br/>(10443/10444)| `Binary.implicitRules`| _Equivalent_<br/>(22008/22009)| `Binary.implicitRules`| _Equivalent_<br/>(37085/37086)| **`Binary.implicitRules`**
| `Binary.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3154)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(3155)| `Binary.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10445)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(10446)| `Binary.language`| _Equivalent_<br/>(22010/22011)| `Binary.language`| _Equivalent_<br/>(37087/37088)| **`Binary.language`**
| `Binary.contentType`| _Equivalent_<br/>(3156/3157)| `Binary.contentType`| _Equivalent_<br/>(10447/10448)| `Binary.contentType`| _Equivalent_<br/>(22012/22013)| `Binary.contentType`| _Equivalent_<br/>(37089/37090)| **`Binary.contentType`**
| | | `Binary.securityContext`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10449)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10450)| `Binary.securityContext`| _Equivalent_<br/>(22014/22015)| `Binary.securityContext`| _Equivalent_<br/>(37091/37092)| **`Binary.securityContext`**
| `Binary.content`| _Equivalent_<br/>(3158/3159)| `Binary.content`| →→→→ _Equivalent_ →→→→ <br/>(820)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1358)| `Binary.data`| _Equivalent_<br/>(22016/22017)| `Binary.data`| _Equivalent_<br/>(37093/37094)| **`Binary.data`**
| *7 of 7 elements used* | | *8 of 8 elements used* | | *8 of 8 elements used* | | *8 of 8 elements used* | | *8 of 8 elements used* 

