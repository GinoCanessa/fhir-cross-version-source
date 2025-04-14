Comparison of 
Generated at Monday, April 14, 2025 6:17:16 PM

### DocumentManifest

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | DocumentManifest |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/DocumentManifest` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for DocumentManifest Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `71` |
| Database Snapshot Count | `30` |
| Database Differential Count | `16` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `DocumentManifest` | `DocumentManifest` | `DocumentManifest` | DocumentManifest | A manifest that defines a set of documents | 0..* | DocumentManifest |  |  |
| `DocumentManifest.author` | `DocumentManifest.author` | `author` |  | Who and/or what authored the manifest | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `DocumentManifest.contained` | `DocumentManifest.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `DocumentManifest.content` | `DocumentManifest.content` | `content` |  | The items included | 1..* | BackboneElement |  |  |
| `DocumentManifest.content.extension` | `DocumentManifest.content.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `DocumentManifest.content.id` | `DocumentManifest.content.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `DocumentManifest.content.modifierExtension` | `DocumentManifest.content.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `DocumentManifest.content.p[x]` | `DocumentManifest.content.p[x]` | `p[x]` |  | Contents of this set of documents | 1..1 | Attachment, Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `DocumentManifest.created` | `DocumentManifest.created` | `created` |  | When this document manifest created | 0..1 | dateTime |  |  |
| `DocumentManifest.description` | `DocumentManifest.description` | `description` |  | Human-readable description (title) | 0..1 | string |  |  |
| `DocumentManifest.extension` | `DocumentManifest.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `DocumentManifest.id` | `DocumentManifest.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `DocumentManifest.identifier` | `DocumentManifest.identifier` | `identifier` |  | Other identifiers for the manifest | 0..* | Identifier |  |  |
| `DocumentManifest.implicitRules` | `DocumentManifest.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `DocumentManifest.language` | `DocumentManifest.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `DocumentManifest.masterIdentifier` | `DocumentManifest.masterIdentifier` | `masterIdentifier` |  | Unique Identifier for the set of documents | 0..1 | Identifier |  |  |
| `DocumentManifest.meta` | `DocumentManifest.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `DocumentManifest.modifierExtension` | `DocumentManifest.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `DocumentManifest.recipient` | `DocumentManifest.recipient` | `recipient` |  | Intended to get notified about this set of documents | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `DocumentManifest.related` | `DocumentManifest.related` | `related` |  | Related things | 0..* | BackboneElement |  |  |
| `DocumentManifest.related.extension` | `DocumentManifest.related.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `DocumentManifest.related.id` | `DocumentManifest.related.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `DocumentManifest.related.identifier` | `DocumentManifest.related.identifier` | `identifier` |  | Identifiers of things that are related | 0..1 | Identifier |  |  |
| `DocumentManifest.related.modifierExtension` | `DocumentManifest.related.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `DocumentManifest.related.ref` | `DocumentManifest.related.ref` | `ref` |  | Related Resource | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `DocumentManifest.source` | `DocumentManifest.source` | `source` |  | The source system/application/software | 0..1 | uri |  |  |
| `DocumentManifest.status` | `DocumentManifest.status` | `status` |  | current \| superseded \| entered-in-error | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/document-reference-status` |
| `DocumentManifest.subject` | `DocumentManifest.subject` | `subject` |  | The subject of the set of documents | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
| `DocumentManifest.text` | `DocumentManifest.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `DocumentManifest.type` | `DocumentManifest.type` | `type` |  | Kind of document set | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/c80-doc-typecodes` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [DocumentManifest](/docs/R2/Resources/DocumentManifest.md)<br/> `http://hl7.org/fhir/StructureDefinition/DocumentManifest\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `104`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `270`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [DocumentManifest](/docs/R3/Resources/DocumentManifest.md)<br/> `http://hl7.org/fhir/StructureDefinition/DocumentManifest\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `452`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `647`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [DocumentManifest](/docs/R4/Resources/DocumentManifest.md)<br/> `http://hl7.org/fhir/StructureDefinition/DocumentManifest\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1467`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1468`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [DocumentManifest](/docs/R4B/Resources/DocumentManifest.md)<br/> `http://hl7.org/fhir/StructureDefinition/DocumentManifest\|4.3.0` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | 
### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition DocumentManifest from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 DocumentManifest| Relationship | [R3 DocumentManifest](/docs/R3/Resources/DocumentManifest.md)| Relationship | [R4 DocumentManifest](/docs/R4/Resources/DocumentManifest.md)| Relationship | [R4B DocumentManifest](/docs/R4B/Resources/DocumentManifest.md)| Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`DocumentManifest`**| _Equivalent_<br/>(4764/4765)| `DocumentManifest`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(13162)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(13163)| `DocumentManifest`| _Equivalent_<br/>(25986/25987)| `DocumentManifest`| | | 
| **`DocumentManifest.id`**| _Equivalent_<br/>(4766/4767)| `DocumentManifest.id`| _Equivalent_<br/>(13164/13165)| `DocumentManifest.id`| _Equivalent_<br/>(25988/25989)| `DocumentManifest.id`| | | 
| **`DocumentManifest.meta`**| _Equivalent_<br/>(4768/4769)| `DocumentManifest.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13166)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13167)| `DocumentManifest.meta`| _Equivalent_<br/>(25990/25991)| `DocumentManifest.meta`| | | 
| **`DocumentManifest.implicitRules`**| _Equivalent_<br/>(4770/4771)| `DocumentManifest.implicitRules`| _Equivalent_<br/>(13168/13169)| `DocumentManifest.implicitRules`| _Equivalent_<br/>(25992/25993)| `DocumentManifest.implicitRules`| | | 
| **`DocumentManifest.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4772)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(4773)| `DocumentManifest.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13170)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(13171)| `DocumentManifest.language`| _Equivalent_<br/>(25994/25995)| `DocumentManifest.language`| | | 
| **`DocumentManifest.text`**| _Equivalent_<br/>(4774/4775)| `DocumentManifest.text`| _Equivalent_<br/>(13172/13173)| `DocumentManifest.text`| _Equivalent_<br/>(25996/25997)| `DocumentManifest.text`| | | 
| **`DocumentManifest.contained`**| _Equivalent_<br/>(4776/4777)| `DocumentManifest.contained`| _Equivalent_<br/>(13174/13175)| `DocumentManifest.contained`| _Equivalent_<br/>(25998/25999)| `DocumentManifest.contained`| | | 
| **`DocumentManifest.extension`**| _Equivalent_<br/>(4778/4779)| `DocumentManifest.extension`| _Equivalent_<br/>(13176/13177)| `DocumentManifest.extension`| _Equivalent_<br/>(26000/26001)| `DocumentManifest.extension`| | | 
| **`DocumentManifest.modifierExtension`**| _Equivalent_<br/>(4780/4781)| `DocumentManifest.modifierExtension`| _Equivalent_<br/>(13178/13179)| `DocumentManifest.modifierExtension`| _Equivalent_<br/>(26002/26003)| `DocumentManifest.modifierExtension`| | | 
| **`DocumentManifest.masterIdentifier`**| _Equivalent_<br/>(4782/4783)| `DocumentManifest.masterIdentifier`| _Equivalent_<br/>(13180/13181)| `DocumentManifest.masterIdentifier`| _Equivalent_<br/>(26004/26005)| `DocumentManifest.masterIdentifier`| | | 
| **`DocumentManifest.identifier`**| _Equivalent_<br/>(4784/4785)| `DocumentManifest.identifier`| _Equivalent_<br/>(13182/13183)| `DocumentManifest.identifier`| _Equivalent_<br/>(26006/26007)| `DocumentManifest.identifier`| | | 
| **`DocumentManifest.subject`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4786)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4787)| `DocumentManifest.subject`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13188)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13189)| `DocumentManifest.subject`| _Equivalent_<br/>(26012/26013)| `DocumentManifest.subject`| | | 
| **`DocumentManifest.recipient`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4788)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4789)| `DocumentManifest.recipient`| →→→→ _RelatedTo_ →→→→ <br/>(13194)<hr/>←←←← _RelatedTo_ ←←←← <br/>(13195)| `DocumentManifest.recipient`| _Equivalent_<br/>(26018/26019)| `DocumentManifest.recipient`| | | 
| **`DocumentManifest.type`**| _Equivalent_<br/>(4790/4791)| `DocumentManifest.type`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13186)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13187)| `DocumentManifest.type`| _Equivalent_<br/>(26010/26011)| `DocumentManifest.type`| | | 
| **`DocumentManifest.author`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4792)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4793)| `DocumentManifest.author`| →→→→ _RelatedTo_ →→→→ <br/>(13192)<hr/>←←←← _RelatedTo_ ←←←← <br/>(13193)| `DocumentManifest.author`| _Equivalent_<br/>(26016/26017)| `DocumentManifest.author`| | | 
| **`DocumentManifest.created`**| _Equivalent_<br/>(4794/4795)| `DocumentManifest.created`| _Equivalent_<br/>(13190/13191)| `DocumentManifest.created`| _Equivalent_<br/>(26014/26015)| `DocumentManifest.created`| | | 
| **`DocumentManifest.source`**| _Equivalent_<br/>(4796/4797)| `DocumentManifest.source`| _Equivalent_<br/>(13196/13197)| `DocumentManifest.source`| _Equivalent_<br/>(26020/26021)| `DocumentManifest.source`| | | 
| **`DocumentManifest.status`**| _Equivalent_<br/>(4798/4799)| `DocumentManifest.status`| _Equivalent_<br/>(13184/13185)| `DocumentManifest.status`| _Equivalent_<br/>(26008/26009)| `DocumentManifest.status`| | | 
| **`DocumentManifest.description`**| _Equivalent_<br/>(4800/4801)| `DocumentManifest.description`| _Equivalent_<br/>(13198/13199)| `DocumentManifest.description`| _Equivalent_<br/>(26022/26023)| `DocumentManifest.description`| | | 
| **`DocumentManifest.content`**| _Equivalent_<br/>(4802/4803)| `DocumentManifest.content`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(13200)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13201)| `DocumentManifest.content`| _Equivalent_<br/>(26024/26025)| `DocumentManifest.content`| | | 
| **`DocumentManifest.content.id`**| _Equivalent_<br/>(4804/4805)| `DocumentManifest.content.id`| | | | | | | 
| **`DocumentManifest.content.extension`**| _Equivalent_<br/>(4806/4807)| `DocumentManifest.content.extension`| | | | | | | 
| **`DocumentManifest.content.modifierExtension`**| _Equivalent_<br/>(4808/4809)| `DocumentManifest.content.modifierExtension`| | | | | | | 
| **`DocumentManifest.content.p[x]`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4810)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4811)| `DocumentManifest.content.p[x]`| →→→→ _RelatedTo_ →→→→ <br/>(1008)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1491)| `DocumentManifest.content`| _Equivalent_<br/>(26024/26025)| `DocumentManifest.content`| | | 
| **`DocumentManifest.related`**| _Equivalent_<br/>(4812/4813)| `DocumentManifest.related`| _Equivalent_<br/>(13205/13206)| `DocumentManifest.related`| _Equivalent_<br/>(26026/26027)| `DocumentManifest.related`| | | 
| **`DocumentManifest.related.id`**| _Equivalent_<br/>(4814/4815)| `DocumentManifest.related.id`| _Equivalent_<br/>(13207/13208)| `DocumentManifest.related.id`| _Equivalent_<br/>(26028/26029)| `DocumentManifest.related.id`| | | 
| **`DocumentManifest.related.extension`**| _Equivalent_<br/>(4816/4817)| `DocumentManifest.related.extension`| _Equivalent_<br/>(13209/13210)| `DocumentManifest.related.extension`| _Equivalent_<br/>(26030/26031)| `DocumentManifest.related.extension`| | | 
| **`DocumentManifest.related.modifierExtension`**| _Equivalent_<br/>(4818/4819)| `DocumentManifest.related.modifierExtension`| _Equivalent_<br/>(13211/13212)| `DocumentManifest.related.modifierExtension`| _Equivalent_<br/>(26032/26033)| `DocumentManifest.related.modifierExtension`| | | 
| **`DocumentManifest.related.identifier`**| _Equivalent_<br/>(4820/4821)| `DocumentManifest.related.identifier`| _Equivalent_<br/>(13213/13214)| `DocumentManifest.related.identifier`| _Equivalent_<br/>(26034/26035)| `DocumentManifest.related.identifier`| | | 
| **`DocumentManifest.related.ref`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4822)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4823)| `DocumentManifest.related.ref`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13215)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13216)| `DocumentManifest.related.ref`| _Equivalent_<br/>(26036/26037)| `DocumentManifest.related.ref`| | | 
| *30 of 30 elements used* | | *30 of 30 elements used* | | *26 of 26 elements used* | | *26 of 26 elements used* | | 

