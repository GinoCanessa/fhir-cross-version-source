Comparison of 
Generated at Friday, April 4, 2025 2:58:45 PM

### Signature

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | Signature |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Signature` |
| Version | 4.0.1 |
| Description | Base StructureDefinition for Signature Type: A signature along with supporting context. The signature may be a digital signature that is cryptographic in nature, or some other signature acceptable to the domain. This other signature may be as simple as a graphical image representing a hand-written signature, or a signature ceremony Different signature approaches have different utilities. |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `1026` |
| Database Snapshot Count | `10` |
| Database Differential Count | `8` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Signature` | `Signature` | `Signature` | Signature | A Signature - XML DigSig, JWS, Graphical image of signature, etc. | 0..* | Signature |  |  |
| `Signature.data` | `Signature.data` | `data` | Signature.data | The actual signature content (XML DigSig. JWS, picture, etc.) | 0..1 | base64Binary |  |  |
| `Signature.extension` | `Signature.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Signature.id` | `Signature.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Signature.onBehalfOf` | `Signature.onBehalfOf` | `onBehalfOf` | Signature.onBehalfOf | The party represented | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `Signature.sigFormat` | `Signature.sigFormat` | `sigFormat` | Signature.sigFormat | The technical format of the signature | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/mimetypes|4.0.1` |
| `Signature.targetFormat` | `Signature.targetFormat` | `targetFormat` | Signature.targetFormat | The technical format of the signed resources | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/mimetypes|4.0.1` |
| `Signature.type` | `Signature.type` | `type` | Signature.type | Indication of the reason the entity signed the object(s) | 1..* | Coding | `Preferred` | `http://hl7.org/fhir/ValueSet/signature-type` |
| `Signature.when` | `Signature.when` | `when` | Signature.when | When the signature was created | 1..1 | instant |  |  |
| `Signature.who` | `Signature.who` | `who` | Signature.who | Who signed | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Signature](/docs/R2/ComplexTypes/Signature.md)<br/> `http://hl7.org/fhir/StructureDefinition/Signature\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `70`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `236`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Signature](/docs/R3/ComplexTypes/Signature.md)<br/> `http://hl7.org/fhir/StructureDefinition/Signature\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `411`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `607`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Signature](/docs/R4/ComplexTypes/Signature.md)<br/> `http://hl7.org/fhir/StructureDefinition/Signature\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1379`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1380`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Signature](/docs/R4B/ComplexTypes/Signature.md)<br/> `http://hl7.org/fhir/StructureDefinition/Signature\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `922`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1151`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Signature](/docs/R5/ComplexTypes/Signature.md)<br/> `http://hl7.org/fhir/StructureDefinition/Signature\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Signature from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Signature](/docs/R2/ComplexTypes/Signature.md)| Relationship | [R3 Signature](/docs/R3/ComplexTypes/Signature.md)| Relationship | R4 Signature| Relationship | [R4B Signature](/docs/R4B/ComplexTypes/Signature.md)| Relationship | [R5 Signature](/docs/R5/ComplexTypes/Signature.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `Signature`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(2845)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2846)| `Signature`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9799)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(9800)| **`Signature`**| _Equivalent_<br/>(21270/21271)| `Signature`| _Equivalent_<br/>(36337/36338)| `Signature`
| `Signature.id`| _Equivalent_<br/>(2847/2848)| `Signature.id`| _Equivalent_<br/>(9801/9802)| **`Signature.id`**| _Equivalent_<br/>(21272/21273)| `Signature.id`| _Equivalent_<br/>(36339/36340)| `Signature.id`
| `Signature.extension`| _Equivalent_<br/>(2849/2850)| `Signature.extension`| _Equivalent_<br/>(9803/9804)| **`Signature.extension`**| _Equivalent_<br/>(21274/21275)| `Signature.extension`| _Equivalent_<br/>(36341/36342)| `Signature.extension`
| `Signature.type`| _Equivalent_<br/>(2851/2852)| `Signature.type`| _Equivalent_<br/>(9805/9806)| **`Signature.type`**| _Equivalent_<br/>(21276/21277)| `Signature.type`| →→→→ _Equivalent_ →→→→ <br/>(36343)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(36344)| `Signature.type`
| `Signature.when`| _Equivalent_<br/>(2853/2854)| `Signature.when`| _Equivalent_<br/>(9807/9808)| **`Signature.when`**| _Equivalent_<br/>(21278/21279)| `Signature.when`| →→→→ _Equivalent_ →→→→ <br/>(36345)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(36346)| `Signature.when`
| `Signature.who[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(2855)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2856)| `Signature.who[x]`| →→→→ _RelatedTo_ →→→→ <br/>(1283)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1673)| **`Signature.who`**| _Equivalent_<br/>(21280/21281)| `Signature.who`| →→→→ _Equivalent_ →→→→ <br/>(36347)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(36348)| `Signature.who`
| | | `Signature.onBehalfOf[x]`| →→→→ _RelatedTo_ →→→→ <br/>(1282)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1671)| **`Signature.onBehalfOf`**| _Equivalent_<br/>(21282/21283)| `Signature.onBehalfOf`| _Equivalent_<br/>(36349/36350)| `Signature.onBehalfOf`
| | | | | **`Signature.targetFormat`**| _Equivalent_<br/>(21284/21285)| `Signature.targetFormat`| _Equivalent_<br/>(36351/36352)| `Signature.targetFormat`
| `Signature.contentType`| →→→→ _Equivalent_ →→→→ <br/>(2857)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2858)| `Signature.contentType`| _Equivalent_<br/>(1281/1672)| **`Signature.sigFormat`**| _Equivalent_<br/>(21286/21287)| `Signature.sigFormat`| _Equivalent_<br/>(36353/36354)| `Signature.sigFormat`
| `Signature.blob`| →→→→ _Equivalent_ →→→→ <br/>(2859)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2860)| `Signature.blob`| _Equivalent_<br/>(1280/1670)| **`Signature.data`**| _Equivalent_<br/>(21288/21289)| `Signature.data`| _Equivalent_<br/>(36355/36356)| `Signature.data`
| *8 of 8 elements used* | | *9 of 9 elements used* | | *10 of 10 elements used* | | *10 of 10 elements used* | | *10 of 10 elements used* 

