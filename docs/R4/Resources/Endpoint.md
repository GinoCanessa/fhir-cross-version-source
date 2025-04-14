Comparison of 
Generated at Monday, April 14, 2025 6:17:31 PM

### Endpoint

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | Endpoint |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Endpoint` |
| Version | 4.0.1 |
| Description | The technical details of an endpoint that can be used for electronic services, such as for web services providing XDS.b or a REST endpoint for another FHIR server. This may include any security context information. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1076` |
| Database Snapshot Count | `20` |
| Database Differential Count | `12` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Endpoint` | `Endpoint` | `Endpoint` | Endpoint | The technical details of an endpoint that can be used for electronic services | 0..* | Endpoint |  |  |
| `Endpoint.address` | `Endpoint.address` | `address` | Endpoint.address | The technical base address for connecting to this endpoint | 1..1 | url |  |  |
| `Endpoint.connectionType` | `Endpoint.connectionType` | `connectionType` | Endpoint.connectionType | Protocol/Profile/Standard to be used with this endpoint connection | 1..1 | Coding | `Extensible` | `http://hl7.org/fhir/ValueSet/endpoint-connection-type` |
| `Endpoint.contact` | `Endpoint.contact` | `contact` | Endpoint.contact | Contact details for source (e.g. troubleshooting) | 0..* | ContactPoint |  |  |
| `Endpoint.contained` | `Endpoint.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Endpoint.extension` | `Endpoint.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Endpoint.header` | `Endpoint.header` | `header` | Endpoint.header | Usage depends on the channel type | 0..* | string |  |  |
| `Endpoint.id` | `Endpoint.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Endpoint.identifier` | `Endpoint.identifier` | `identifier` | Endpoint.identifier | Identifies this endpoint across multiple systems | 0..* | Identifier |  |  |
| `Endpoint.implicitRules` | `Endpoint.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Endpoint.language` | `Endpoint.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `Endpoint.managingOrganization` | `Endpoint.managingOrganization` | `managingOrganization` | Endpoint.managingOrganization | Organization that manages this endpoint (might not be the organization that exposes the endpoint) | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `Endpoint.meta` | `Endpoint.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Endpoint.modifierExtension` | `Endpoint.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Endpoint.name` | `Endpoint.name` | `name` | Endpoint.name | A name that this endpoint can be identified by | 0..1 | string |  |  |
| `Endpoint.payloadMimeType` | `Endpoint.payloadMimeType` | `payloadMimeType` | Endpoint.payloadMimeType | Mimetype to send. If not specified, the content could be anything (including no payload, if the connectionType defined this) | 0..* | code | `Required` | `http://hl7.org/fhir/ValueSet/mimetypes|4.0.1` |
| `Endpoint.payloadType` | `Endpoint.payloadType` | `payloadType` | Endpoint.payloadType | The type of content that may be used at this endpoint (e.g. XDS Discharge summaries) | 1..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/endpoint-payload-type` |
| `Endpoint.period` | `Endpoint.period` | `period` | Endpoint.period | Interval the endpoint is expected to be operational | 0..1 | Period |  |  |
| `Endpoint.status` | `Endpoint.status` | `status` | Endpoint.status | active \| suspended \| error \| off \| entered-in-error \| test | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/endpoint-status|4.0.1` |
| `Endpoint.text` | `Endpoint.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [Endpoint](/docs/R3/Resources/Endpoint.md)<br/> `http://hl7.org/fhir/StructureDefinition/Endpoint\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `455`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `650`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Endpoint](/docs/R4/Resources/Endpoint.md)<br/> `http://hl7.org/fhir/StructureDefinition/Endpoint\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1475`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1476`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Endpoint](/docs/R4B/Resources/Endpoint.md)<br/> `http://hl7.org/fhir/StructureDefinition/Endpoint\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `970`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1199`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Endpoint](/docs/R5/Resources/Endpoint.md)<br/> `http://hl7.org/fhir/StructureDefinition/Endpoint\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Endpoint from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | [R3 Endpoint](/docs/R3/Resources/Endpoint.md)| Relationship | R4 Endpoint| Relationship | [R4B Endpoint](/docs/R4B/Resources/Endpoint.md)| Relationship | [R5 Endpoint](/docs/R5/Resources/Endpoint.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | `Endpoint`| _Equivalent_<br/>(13568/13569)| **`Endpoint`**| _Equivalent_<br/>(26296/26297)| `Endpoint`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(41034)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(41035)| `Endpoint`
| | | `Endpoint.id`| _Equivalent_<br/>(13570/13571)| **`Endpoint.id`**| _Equivalent_<br/>(26298/26299)| `Endpoint.id`| _Equivalent_<br/>(41036/41037)| `Endpoint.id`
| | | `Endpoint.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13572)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13573)| **`Endpoint.meta`**| _Equivalent_<br/>(26300/26301)| `Endpoint.meta`| _Equivalent_<br/>(41038/41039)| `Endpoint.meta`
| | | `Endpoint.implicitRules`| _Equivalent_<br/>(13574/13575)| **`Endpoint.implicitRules`**| _Equivalent_<br/>(26302/26303)| `Endpoint.implicitRules`| _Equivalent_<br/>(41040/41041)| `Endpoint.implicitRules`
| | | `Endpoint.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13576)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(13577)| **`Endpoint.language`**| _Equivalent_<br/>(26304/26305)| `Endpoint.language`| _Equivalent_<br/>(41042/41043)| `Endpoint.language`
| | | `Endpoint.text`| _Equivalent_<br/>(13578/13579)| **`Endpoint.text`**| _Equivalent_<br/>(26306/26307)| `Endpoint.text`| _Equivalent_<br/>(41044/41045)| `Endpoint.text`
| | | `Endpoint.contained`| _Equivalent_<br/>(13580/13581)| **`Endpoint.contained`**| _Equivalent_<br/>(26308/26309)| `Endpoint.contained`| _Equivalent_<br/>(41046/41047)| `Endpoint.contained`
| | | `Endpoint.extension`| _Equivalent_<br/>(13582/13583)| **`Endpoint.extension`**| _Equivalent_<br/>(26310/26311)| `Endpoint.extension`| _Equivalent_<br/>(41048/41049)| `Endpoint.extension`
| | | `Endpoint.modifierExtension`| _Equivalent_<br/>(13584/13585)| **`Endpoint.modifierExtension`**| _Equivalent_<br/>(26312/26313)| `Endpoint.modifierExtension`| _Equivalent_<br/>(41050/41051)| `Endpoint.modifierExtension`
| | | `Endpoint.identifier`| _Equivalent_<br/>(13586/13587)| **`Endpoint.identifier`**| _Equivalent_<br/>(26314/26315)| `Endpoint.identifier`| _Equivalent_<br/>(41052/41053)| `Endpoint.identifier`
| | | `Endpoint.status`| _Equivalent_<br/>(13588/13589)| **`Endpoint.status`**| _Equivalent_<br/>(26316/26317)| `Endpoint.status`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(41054)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(41055)| `Endpoint.status`
| | | `Endpoint.connectionType`| _Equivalent_<br/>(13590/13591)| **`Endpoint.connectionType`**| _Equivalent_<br/>(26318/26319)| `Endpoint.connectionType`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(41056)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(41057)| `Endpoint.connectionType`
| | | `Endpoint.name`| _Equivalent_<br/>(13592/13593)| **`Endpoint.name`**| _Equivalent_<br/>(26320/26321)| `Endpoint.name`| _Equivalent_<br/>(41058/41059)| `Endpoint.name`
| | | `Endpoint.managingOrganization`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13594)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13595)| **`Endpoint.managingOrganization`**| _Equivalent_<br/>(26322/26323)| `Endpoint.managingOrganization`| _Equivalent_<br/>(41060/41061)| `Endpoint.managingOrganization`
| | | `Endpoint.contact`| _Equivalent_<br/>(13596/13597)| **`Endpoint.contact`**| _Equivalent_<br/>(26324/26325)| `Endpoint.contact`| _Equivalent_<br/>(41062/41063)| `Endpoint.contact`
| | | `Endpoint.period`| _Equivalent_<br/>(13598/13599)| **`Endpoint.period`**| _Equivalent_<br/>(26326/26327)| `Endpoint.period`| _Equivalent_<br/>(41064/41065)| `Endpoint.period`
| | | `Endpoint.payloadType`| _Equivalent_<br/>(13600/13601)| **`Endpoint.payloadType`**| _Equivalent_<br/>(26328/26329)| `Endpoint.payloadType`| | | 
| | | `Endpoint.payloadMimeType`| _Equivalent_<br/>(13602/13603)| **`Endpoint.payloadMimeType`**| _Equivalent_<br/>(26330/26331)| `Endpoint.payloadMimeType`| | | 
| | | `Endpoint.address`| _Equivalent_<br/>(13604/13605)| **`Endpoint.address`**| _Equivalent_<br/>(26332/26333)| `Endpoint.address`| _Equivalent_<br/>(41068/41069)| `Endpoint.address`
| | | `Endpoint.header`| _Equivalent_<br/>(13606/13607)| **`Endpoint.header`**| _Equivalent_<br/>(26334/26335)| `Endpoint.header`| _Equivalent_<br/>(41070/41071)| `Endpoint.header`
| | | *20 of 20 elements used* | | *20 of 20 elements used* | | *20 of 20 elements used* | | *18 of 26 elements used* <br/>remaining elements:<br/>`Endpoint.description`, `Endpoint.environmentType`, `Endpoint.payload`, `Endpoint.payload.extension`, `Endpoint.payload.id`, `Endpoint.payload.mimeType`, `Endpoint.payload.modifierExtension`, `Endpoint.payload.type`

