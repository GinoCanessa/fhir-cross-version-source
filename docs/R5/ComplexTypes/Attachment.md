Comparison of 
Generated at Thursday, April 3, 2025 8:18:33 AM

### Attachment

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | Attachment |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Attachment` |
| Version | 5.0.0 |
| Description | Attachment Type: For referring to data content defined in other formats. |
| Status | `Active` |
| Artifact Class | `ComplexType` |
| Database Key | `2203` |
| Database Snapshot Count | `16` |
| Database Differential Count | `14` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Attachment` | `Attachment` | `Attachment` | Attachment | Content in a format defined elsewhere | 0..* | Attachment |  |  |
| `Attachment.contentType` | `Attachment.contentType` | `contentType` | Attachment.contentType | Mime type of the content, with charset etc. | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/mimetypes|5.0.0` |
| `Attachment.creation` | `Attachment.creation` | `creation` | Attachment.creation | Date attachment was first created | 0..1 | dateTime |  |  |
| `Attachment.data` | `Attachment.data` | `data` | Attachment.data | Data inline, base64ed | 0..1 | base64Binary |  |  |
| `Attachment.duration` | `Attachment.duration` | `duration` | Attachment.duration | Length in seconds (audio / video) | 0..1 | decimal |  |  |
| `Attachment.extension` | `Attachment.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Attachment.frames` | `Attachment.frames` | `frames` | Attachment.frames | Number of frames if > 1 (photo) | 0..1 | positiveInt |  |  |
| `Attachment.hash` | `Attachment.hash` | `hash` | Attachment.hash | Hash of the data (sha-1, base64ed) | 0..1 | base64Binary |  |  |
| `Attachment.height` | `Attachment.height` | `height` | Attachment.height | Height of the image in pixels (photo/video) | 0..1 | positiveInt |  |  |
| `Attachment.id` | `Attachment.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Attachment.language` | `Attachment.language` | `language` | Attachment.language | Human language of the content (BCP-47) | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `Attachment.pages` | `Attachment.pages` | `pages` | Attachment.pages | Number of printed pages | 0..1 | positiveInt |  |  |
| `Attachment.size` | `Attachment.size` | `size` | Attachment.size | Number of bytes of content (if url provided) | 0..1 | integer64 |  |  |
| `Attachment.title` | `Attachment.title` | `title` | Attachment.title | Label to display in place of the data | 0..1 | string |  |  |
| `Attachment.url` | `Attachment.url` | `url` | Attachment.url | Uri where the data can be found | 0..1 | url |  |  |
| `Attachment.width` | `Attachment.width` | `width` | Attachment.width | Width of the image in pixels (photo/video) | 0..1 | positiveInt |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Attachment](/docs/R2/ComplexTypes/Attachment.md)<br/> `http://hl7.org/fhir/StructureDefinition/Attachment\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `49`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `216`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Attachment](/docs/R3/ComplexTypes/Attachment.md)<br/> `http://hl7.org/fhir/StructureDefinition/Attachment\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `385`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `581`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Attachment](/docs/R4/ComplexTypes/Attachment.md)<br/> `http://hl7.org/fhir/StructureDefinition/Attachment\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1313`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1314`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Attachment](/docs/R4B/ComplexTypes/Attachment.md)<br/> `http://hl7.org/fhir/StructureDefinition/Attachment\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `892`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1121`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Attachment](/docs/R5/ComplexTypes/Attachment.md)<br/> `http://hl7.org/fhir/StructureDefinition/Attachment\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Attachment from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Attachment](/docs/R2/ComplexTypes/Attachment.md)| Relationship | [R3 Attachment](/docs/R3/ComplexTypes/Attachment.md)| Relationship | [R4 Attachment](/docs/R4/ComplexTypes/Attachment.md)| Relationship | [R4B Attachment](/docs/R4B/ComplexTypes/Attachment.md)| Relationship | R5 Attachment
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `Attachment`| _Equivalent_<br/>(2453/2454)| `Attachment`| _Equivalent_<br/>(9182/9183)| `Attachment`| _Equivalent_<br/>(20532/20533)| `Attachment`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(35649)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(35650)| **`Attachment`**
| `Attachment.id`| _Equivalent_<br/>(2455/2456)| `Attachment.id`| _Equivalent_<br/>(9184/9185)| `Attachment.id`| _Equivalent_<br/>(20534/20535)| `Attachment.id`| _Equivalent_<br/>(35651/35652)| **`Attachment.id`**
| `Attachment.extension`| _Equivalent_<br/>(2457/2458)| `Attachment.extension`| _Equivalent_<br/>(9186/9187)| `Attachment.extension`| _Equivalent_<br/>(20536/20537)| `Attachment.extension`| _Equivalent_<br/>(35653/35654)| **`Attachment.extension`**
| `Attachment.contentType`| _Equivalent_<br/>(2459/2460)| `Attachment.contentType`| _Equivalent_<br/>(9188/9189)| `Attachment.contentType`| _Equivalent_<br/>(20538/20539)| `Attachment.contentType`| _Equivalent_<br/>(35655/35656)| **`Attachment.contentType`**
| `Attachment.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(2461)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2462)| `Attachment.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9190)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(9191)| `Attachment.language`| _Equivalent_<br/>(20540/20541)| `Attachment.language`| _Equivalent_<br/>(35657/35658)| **`Attachment.language`**
| `Attachment.data`| _Equivalent_<br/>(2463/2464)| `Attachment.data`| _Equivalent_<br/>(9192/9193)| `Attachment.data`| _Equivalent_<br/>(20542/20543)| `Attachment.data`| _Equivalent_<br/>(35659/35660)| **`Attachment.data`**
| `Attachment.url`| _Equivalent_<br/>(2465/2466)| `Attachment.url`| _Equivalent_<br/>(9194/9195)| `Attachment.url`| _Equivalent_<br/>(20544/20545)| `Attachment.url`| _Equivalent_<br/>(35661/35662)| **`Attachment.url`**
| `Attachment.size`| _Equivalent_<br/>(2467/2468)| `Attachment.size`| _Equivalent_<br/>(9196/9197)| `Attachment.size`| _Equivalent_<br/>(20546/20547)| `Attachment.size`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(35663)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(35664)| **`Attachment.size`**
| `Attachment.hash`| _Equivalent_<br/>(2469/2470)| `Attachment.hash`| _Equivalent_<br/>(9198/9199)| `Attachment.hash`| _Equivalent_<br/>(20548/20549)| `Attachment.hash`| _Equivalent_<br/>(35665/35666)| **`Attachment.hash`**
| `Attachment.title`| _Equivalent_<br/>(2471/2472)| `Attachment.title`| _Equivalent_<br/>(9200/9201)| `Attachment.title`| _Equivalent_<br/>(20550/20551)| `Attachment.title`| _Equivalent_<br/>(35667/35668)| **`Attachment.title`**
| `Attachment.creation`| _Equivalent_<br/>(2473/2474)| `Attachment.creation`| _Equivalent_<br/>(9202/9203)| `Attachment.creation`| _Equivalent_<br/>(20552/20553)| `Attachment.creation`| _Equivalent_<br/>(35669/35670)| **`Attachment.creation`**
| | | | | | | | | **`Attachment.height`**
| | | | | | | | | **`Attachment.width`**
| | | | | | | | | **`Attachment.frames`**
| | | | | | | | | **`Attachment.duration`**
| | | | | | | | | **`Attachment.pages`**
| *11 of 11 elements used* | | *11 of 11 elements used* | | *11 of 11 elements used* | | *11 of 11 elements used* | | *16 of 16 elements used* 

