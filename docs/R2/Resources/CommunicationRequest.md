Comparison of 
Generated at Tuesday, April 1, 2025 1:39:09 PM

### CommunicationRequest

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | CommunicationRequest |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/CommunicationRequest` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for CommunicationRequest Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `55` |
| Database Snapshot Count | `27` |
| Database Differential Count | `16` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `CommunicationRequest` | `CommunicationRequest` | `CommunicationRequest` | CommunicationRequest | A request for information to be sent to a receiver | 0..* | CommunicationRequest |  |  |
| `CommunicationRequest.category` | `CommunicationRequest.category` | `category` |  | Message category | 0..1 | CodeableConcept | `Example` |  |
| `CommunicationRequest.contained` | `CommunicationRequest.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `CommunicationRequest.encounter` | `CommunicationRequest.encounter` | `encounter` |  | Encounter leading to message | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Encounter) |  |  |
| `CommunicationRequest.extension` | `CommunicationRequest.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `CommunicationRequest.id` | `CommunicationRequest.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `CommunicationRequest.identifier` | `CommunicationRequest.identifier` | `identifier` |  | Unique identifier | 0..* | Identifier |  |  |
| `CommunicationRequest.implicitRules` | `CommunicationRequest.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `CommunicationRequest.language` | `CommunicationRequest.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `CommunicationRequest.medium` | `CommunicationRequest.medium` | `medium` |  | A channel of communication | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/v3-ParticipationMode` |
| `CommunicationRequest.meta` | `CommunicationRequest.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `CommunicationRequest.modifierExtension` | `CommunicationRequest.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `CommunicationRequest.payload` | `CommunicationRequest.payload` | `payload` |  | Message payload | 0..* | BackboneElement |  |  |
| `CommunicationRequest.payload.content[x]` | `CommunicationRequest.payload.content[x]` | `content[x]` |  | Message part content | 1..1 | Attachment, Reference(http://hl7.org/fhir/StructureDefinition/Resource), string |  |  |
| `CommunicationRequest.payload.extension` | `CommunicationRequest.payload.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `CommunicationRequest.payload.id` | `CommunicationRequest.payload.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `CommunicationRequest.payload.modifierExtension` | `CommunicationRequest.payload.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `CommunicationRequest.priority` | `CommunicationRequest.priority` | `priority` |  | Message urgency | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/diagnostic-order-priority` |
| `CommunicationRequest.reason` | `CommunicationRequest.reason` | `reason` |  | Indication for message | 0..* | CodeableConcept | `Example` |  |
| `CommunicationRequest.recipient` | `CommunicationRequest.recipient` | `recipient` |  | Message recipient | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `CommunicationRequest.requestedOn` | `CommunicationRequest.requestedOn` | `requestedOn` |  | When ordered or proposed | 0..1 | dateTime |  |  |
| `CommunicationRequest.requester` | `CommunicationRequest.requester` | `requester` |  | An individual who requested a communication | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `CommunicationRequest.scheduled[x]` | `CommunicationRequest.scheduled[x]` | `scheduled[x]` |  | When scheduled | 0..1 | dateTime, Period |  |  |
| `CommunicationRequest.sender` | `CommunicationRequest.sender` | `sender` |  | Message sender | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `CommunicationRequest.status` | `CommunicationRequest.status` | `status` |  | proposed \| planned \| requested \| received \| accepted \| in-progress \| completed \| suspended \| rejected \| failed | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/communication-request-status` |
| `CommunicationRequest.subject` | `CommunicationRequest.subject` | `subject` |  | Focus of message | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `CommunicationRequest.text` | `CommunicationRequest.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [CommunicationRequest](/docs/R2/Resources/CommunicationRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/CommunicationRequest\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `87`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `254`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CommunicationRequest](/docs/R3/Resources/CommunicationRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/CommunicationRequest\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `435`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `631`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CommunicationRequest](/docs/R4/Resources/CommunicationRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/CommunicationRequest\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1433`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1434`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CommunicationRequest](/docs/R4B/Resources/CommunicationRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/CommunicationRequest\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `951`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1180`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CommunicationRequest](/docs/R5/Resources/CommunicationRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/CommunicationRequest\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition CommunicationRequest from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 CommunicationRequest| Relationship | [R3 CommunicationRequest](/docs/R3/Resources/CommunicationRequest.md)| Relationship | [R4 CommunicationRequest](/docs/R4/Resources/CommunicationRequest.md)| Relationship | [R4B CommunicationRequest](/docs/R4B/Resources/CommunicationRequest.md)| Relationship | [R5 CommunicationRequest](/docs/R5/Resources/CommunicationRequest.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`CommunicationRequest`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3786)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3787)| `CommunicationRequest`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(12070)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(12071)| `CommunicationRequest`| _Equivalent_<br/>(23886/23887)| `CommunicationRequest`| _Equivalent_<br/>(39199/39200)| `CommunicationRequest`
| **`CommunicationRequest.id`**| _Equivalent_<br/>(3788/3789)| `CommunicationRequest.id`| _Equivalent_<br/>(12072/12073)| `CommunicationRequest.id`| _Equivalent_<br/>(23888/23889)| `CommunicationRequest.id`| _Equivalent_<br/>(39201/39202)| `CommunicationRequest.id`
| **`CommunicationRequest.meta`**| _Equivalent_<br/>(3790/3791)| `CommunicationRequest.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12074)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12075)| `CommunicationRequest.meta`| _Equivalent_<br/>(23890/23891)| `CommunicationRequest.meta`| _Equivalent_<br/>(39203/39204)| `CommunicationRequest.meta`
| **`CommunicationRequest.implicitRules`**| _Equivalent_<br/>(3792/3793)| `CommunicationRequest.implicitRules`| _Equivalent_<br/>(12076/12077)| `CommunicationRequest.implicitRules`| _Equivalent_<br/>(23892/23893)| `CommunicationRequest.implicitRules`| _Equivalent_<br/>(39205/39206)| `CommunicationRequest.implicitRules`
| **`CommunicationRequest.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3794)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(3795)| `CommunicationRequest.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12078)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(12079)| `CommunicationRequest.language`| _Equivalent_<br/>(23894/23895)| `CommunicationRequest.language`| _Equivalent_<br/>(39207/39208)| `CommunicationRequest.language`
| **`CommunicationRequest.text`**| _Equivalent_<br/>(3796/3797)| `CommunicationRequest.text`| _Equivalent_<br/>(12080/12081)| `CommunicationRequest.text`| _Equivalent_<br/>(23896/23897)| `CommunicationRequest.text`| _Equivalent_<br/>(39209/39210)| `CommunicationRequest.text`
| **`CommunicationRequest.contained`**| _Equivalent_<br/>(3798/3799)| `CommunicationRequest.contained`| _Equivalent_<br/>(12082/12083)| `CommunicationRequest.contained`| _Equivalent_<br/>(23898/23899)| `CommunicationRequest.contained`| _Equivalent_<br/>(39211/39212)| `CommunicationRequest.contained`
| **`CommunicationRequest.extension`**| _Equivalent_<br/>(3800/3801)| `CommunicationRequest.extension`| _Equivalent_<br/>(12084/12085)| `CommunicationRequest.extension`| _Equivalent_<br/>(23900/23901)| `CommunicationRequest.extension`| _Equivalent_<br/>(39213/39214)| `CommunicationRequest.extension`
| **`CommunicationRequest.modifierExtension`**| _Equivalent_<br/>(3802/3803)| `CommunicationRequest.modifierExtension`| _Equivalent_<br/>(12086/12087)| `CommunicationRequest.modifierExtension`| _Equivalent_<br/>(23902/23903)| `CommunicationRequest.modifierExtension`| _Equivalent_<br/>(39215/39216)| `CommunicationRequest.modifierExtension`
| **`CommunicationRequest.identifier`**| _Equivalent_<br/>(3804/3805)| `CommunicationRequest.identifier`| _Equivalent_<br/>(12088/12089)| `CommunicationRequest.identifier`| _Equivalent_<br/>(23904/23905)| `CommunicationRequest.identifier`| _Equivalent_<br/>(39217/39218)| `CommunicationRequest.identifier`
| **`CommunicationRequest.category`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3806)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3807)| `CommunicationRequest.category`| _Equivalent_<br/>(12098/12099)| `CommunicationRequest.category`| _Equivalent_<br/>(23916/23917)| `CommunicationRequest.category`| _Equivalent_<br/>(39229/39230)| `CommunicationRequest.category`
| **`CommunicationRequest.sender`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3808)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3809)| `CommunicationRequest.sender`| →→→→ _RelatedTo_ →→→→ <br/>(12122)<hr/>←←←← _RelatedTo_ ←←←← <br/>(12123)| `CommunicationRequest.sender`| _Equivalent_<br/>(23948/23949)| `CommunicationRequest.sender`| →→→→ _RelatedTo_ →→→→ <br/>(1739)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1983)| `CommunicationRequest.informationProvider`
| **`CommunicationRequest.recipient`**| →→→→ _RelatedTo_ →→→→ <br/>(3810)<hr/>←←←← _RelatedTo_ ←←←← <br/>(3811)| `CommunicationRequest.recipient`| →→→→ _RelatedTo_ →→→→ <br/>(12106)<hr/>←←←← _RelatedTo_ ←←←← <br/>(12107)| `CommunicationRequest.recipient`| _Equivalent_<br/>(23946/23947)| `CommunicationRequest.recipient`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(39259)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(39260)| `CommunicationRequest.recipient`
| **`CommunicationRequest.payload`**| _Equivalent_<br/>(3812/3813)| `CommunicationRequest.payload`| _Equivalent_<br/>(12108/12109)| `CommunicationRequest.payload`| _Equivalent_<br/>(23930/23931)| `CommunicationRequest.payload`| _Equivalent_<br/>(39243/39244)| `CommunicationRequest.payload`
| **`CommunicationRequest.payload.id`**| _Equivalent_<br/>(3814/3815)| `CommunicationRequest.payload.id`| _Equivalent_<br/>(12110/12111)| `CommunicationRequest.payload.id`| _Equivalent_<br/>(23932/23933)| `CommunicationRequest.payload.id`| _Equivalent_<br/>(39245/39246)| `CommunicationRequest.payload.id`
| **`CommunicationRequest.payload.extension`**| _Equivalent_<br/>(3816/3817)| `CommunicationRequest.payload.extension`| _Equivalent_<br/>(12112/12113)| `CommunicationRequest.payload.extension`| _Equivalent_<br/>(23934/23935)| `CommunicationRequest.payload.extension`| _Equivalent_<br/>(39247/39248)| `CommunicationRequest.payload.extension`
| **`CommunicationRequest.payload.modifierExtension`**| _Equivalent_<br/>(3818/3819)| `CommunicationRequest.payload.modifierExtension`| _Equivalent_<br/>(12114/12115)| `CommunicationRequest.payload.modifierExtension`| _Equivalent_<br/>(23936/23937)| `CommunicationRequest.payload.modifierExtension`| _Equivalent_<br/>(39249/39250)| `CommunicationRequest.payload.modifierExtension`
| **`CommunicationRequest.payload.content[x]`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3820)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3821)| `CommunicationRequest.payload.content[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12116)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12117)| `CommunicationRequest.payload.content[x]`| _Equivalent_<br/>(23938/23939)| `CommunicationRequest.payload.content[x]`| →→→→ _RelatedTo_ →→→→ <br/>(39251)<hr/>←←←← _RelatedTo_ ←←←← <br/>(39252)| `CommunicationRequest.payload.content[x]`
| **`CommunicationRequest.medium`**| _Equivalent_<br/>(3822/3823)| `CommunicationRequest.medium`| _Equivalent_<br/>(12102/12103)| `CommunicationRequest.medium`| _Equivalent_<br/>(23922/23923)| `CommunicationRequest.medium`| _Equivalent_<br/>(39235/39236)| `CommunicationRequest.medium`
| **`CommunicationRequest.requester`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(3824)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3825)| `CommunicationRequest.requester`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(12124)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12125)| `CommunicationRequest.requester`| _Equivalent_<br/>(23944/23945)| `CommunicationRequest.requester`| _Equivalent_<br/>(39257/39258)| `CommunicationRequest.requester`
| **`CommunicationRequest.status`**| →→→→ _RelatedTo_ →→→→ <br/>(3826)<hr/>←←←← _RelatedTo_ ←←←← <br/>(3827)| `CommunicationRequest.status`| _Equivalent_<br/>(12096/12097)| `CommunicationRequest.status`| _Equivalent_<br/>(23912/23913)| `CommunicationRequest.status`| _Equivalent_<br/>(39225/39226)| `CommunicationRequest.status`
| **`CommunicationRequest.encounter`**| →→→→ _RelatedTo_ →→→→ <br/>(138)<hr/>←←←← _RelatedTo_ ←←←← <br/>(558)| `CommunicationRequest.context`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(898)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1413)| `CommunicationRequest.encounter`| _Equivalent_<br/>(23928/23929)| `CommunicationRequest.encounter`| _Equivalent_<br/>(39241/39242)| `CommunicationRequest.encounter`
| **`CommunicationRequest.scheduled[x]`**| _Equivalent_<br/>(141/559)| `CommunicationRequest.occurrence[x]`| _Equivalent_<br/>(12118/12119)| `CommunicationRequest.occurrence[x]`| _Equivalent_<br/>(23940/23941)| `CommunicationRequest.occurrence[x]`| _Equivalent_<br/>(39253/39254)| `CommunicationRequest.occurrence[x]`
| **`CommunicationRequest.reason`**| _Equivalent_<br/>(139/560)| `CommunicationRequest.reasonCode`| _Equivalent_<br/>(12129/12130)| `CommunicationRequest.reasonCode`| _Equivalent_<br/>(23950/23951)| `CommunicationRequest.reasonCode`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1740)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1984)| `CommunicationRequest.reason`
| **`CommunicationRequest.requestedOn`**| _Equivalent_<br/>(140/557)| `CommunicationRequest.authoredOn`| _Equivalent_<br/>(12120/12121)| `CommunicationRequest.authoredOn`| _Equivalent_<br/>(23942/23943)| `CommunicationRequest.authoredOn`| _Equivalent_<br/>(39255/39256)| `CommunicationRequest.authoredOn`
| **`CommunicationRequest.subject`**| →→→→ _RelatedTo_ →→→→ <br/>(3828)<hr/>←←←← _RelatedTo_ ←←←← <br/>(3829)| `CommunicationRequest.subject`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12104)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12105)| `CommunicationRequest.subject`| _Equivalent_<br/>(23924/23925)| `CommunicationRequest.subject`| _Equivalent_<br/>(39237/39238)| `CommunicationRequest.subject`
| **`CommunicationRequest.priority`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3830)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(3831)| `CommunicationRequest.priority`| _Equivalent_<br/>(12100/12101)| `CommunicationRequest.priority`| _Equivalent_<br/>(23918/23919)| `CommunicationRequest.priority`| _Equivalent_<br/>(39231/39232)| `CommunicationRequest.priority`
| *27 of 27 elements used* | | *27 of 38 elements used* | | *27 of 35 elements used* | | *27 of 35 elements used* | | *27 of 35 elements used* 

