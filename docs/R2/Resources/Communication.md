Comparison of 
Generated at Friday, April 4, 2025 2:58:34 PM

### Communication

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | Communication |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Communication` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for Communication Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `54` |
| Database Snapshot Count | `26` |
| Database Differential Count | `15` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Communication` | `Communication` | `Communication` | Communication | A record of information transmitted from a sender to a receiver | 0..* | Communication |  |  |
| `Communication.category` | `Communication.category` | `category` |  | Message category | 0..1 | CodeableConcept | `Example` |  |
| `Communication.contained` | `Communication.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Communication.encounter` | `Communication.encounter` | `encounter` |  | Encounter leading to message | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Encounter) |  |  |
| `Communication.extension` | `Communication.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Communication.id` | `Communication.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Communication.identifier` | `Communication.identifier` | `identifier` |  | Unique identifier | 0..* | Identifier |  |  |
| `Communication.implicitRules` | `Communication.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Communication.language` | `Communication.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `Communication.medium` | `Communication.medium` | `medium` |  | A channel of communication | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/v3-ParticipationMode` |
| `Communication.meta` | `Communication.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Communication.modifierExtension` | `Communication.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Communication.payload` | `Communication.payload` | `payload` |  | Message payload | 0..* | BackboneElement |  |  |
| `Communication.payload.content[x]` | `Communication.payload.content[x]` | `content[x]` |  | Message part content | 1..1 | Attachment, Reference(http://hl7.org/fhir/StructureDefinition/Resource), string |  |  |
| `Communication.payload.extension` | `Communication.payload.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Communication.payload.id` | `Communication.payload.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Communication.payload.modifierExtension` | `Communication.payload.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Communication.reason` | `Communication.reason` | `reason` |  | Indication for message | 0..* | CodeableConcept | `Example` |  |
| `Communication.received` | `Communication.received` | `received` |  | When received | 0..1 | dateTime |  |  |
| `Communication.recipient` | `Communication.recipient` | `recipient` |  | Message recipient | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `Communication.requestDetail` | `Communication.requestDetail` | `requestDetail` |  | CommunicationRequest producing this message | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/CommunicationRequest) |  |  |
| `Communication.sender` | `Communication.sender` | `sender` |  | Message sender | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `Communication.sent` | `Communication.sent` | `sent` |  | When sent | 0..1 | dateTime |  |  |
| `Communication.status` | `Communication.status` | `status` |  | in-progress \| completed \| suspended \| rejected \| failed | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/communication-status` |
| `Communication.subject` | `Communication.subject` | `subject` |  | Focus of message | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `Communication.text` | `Communication.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Communication](/docs/R2/Resources/Communication.md)<br/> `http://hl7.org/fhir/StructureDefinition/Communication\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `86`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `253`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Communication](/docs/R3/Resources/Communication.md)<br/> `http://hl7.org/fhir/StructureDefinition/Communication\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `434`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `630`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Communication](/docs/R4/Resources/Communication.md)<br/> `http://hl7.org/fhir/StructureDefinition/Communication\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1431`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1432`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Communication](/docs/R4B/Resources/Communication.md)<br/> `http://hl7.org/fhir/StructureDefinition/Communication\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `950`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1179`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Communication](/docs/R5/Resources/Communication.md)<br/> `http://hl7.org/fhir/StructureDefinition/Communication\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Communication from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 Communication| Relationship | [R3 Communication](/docs/R3/Resources/Communication.md)| Relationship | [R4 Communication](/docs/R4/Resources/Communication.md)| Relationship | [R4B Communication](/docs/R4B/Resources/Communication.md)| Relationship | [R5 Communication](/docs/R5/Resources/Communication.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`Communication`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3740)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3741)| `Communication`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12002)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12003)| `Communication`| _Equivalent_<br/>(23811/23812)| `Communication`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(39131)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(39132)| `Communication`
| **`Communication.id`**| _Equivalent_<br/>(3742/3743)| `Communication.id`| _Equivalent_<br/>(12004/12005)| `Communication.id`| _Equivalent_<br/>(23813/23814)| `Communication.id`| _Equivalent_<br/>(39133/39134)| `Communication.id`
| **`Communication.meta`**| _Equivalent_<br/>(3744/3745)| `Communication.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12006)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12007)| `Communication.meta`| _Equivalent_<br/>(23815/23816)| `Communication.meta`| _Equivalent_<br/>(39135/39136)| `Communication.meta`
| **`Communication.implicitRules`**| _Equivalent_<br/>(3746/3747)| `Communication.implicitRules`| _Equivalent_<br/>(12008/12009)| `Communication.implicitRules`| _Equivalent_<br/>(23817/23818)| `Communication.implicitRules`| _Equivalent_<br/>(39137/39138)| `Communication.implicitRules`
| **`Communication.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3748)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(3749)| `Communication.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12010)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(12011)| `Communication.language`| _Equivalent_<br/>(23819/23820)| `Communication.language`| _Equivalent_<br/>(39139/39140)| `Communication.language`
| **`Communication.text`**| _Equivalent_<br/>(3750/3751)| `Communication.text`| _Equivalent_<br/>(12012/12013)| `Communication.text`| _Equivalent_<br/>(23821/23822)| `Communication.text`| _Equivalent_<br/>(39141/39142)| `Communication.text`
| **`Communication.contained`**| _Equivalent_<br/>(3752/3753)| `Communication.contained`| _Equivalent_<br/>(12014/12015)| `Communication.contained`| _Equivalent_<br/>(23823/23824)| `Communication.contained`| _Equivalent_<br/>(39143/39144)| `Communication.contained`
| **`Communication.extension`**| _Equivalent_<br/>(3754/3755)| `Communication.extension`| →→→→ _Equivalent_ →→→→ <br/>(12016)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12017)| `Communication.extension`| _Equivalent_<br/>(23825/23826)| `Communication.extension`| _Equivalent_<br/>(39145/39146)| `Communication.extension`
| **`Communication.modifierExtension`**| _Equivalent_<br/>(3756/3757)| `Communication.modifierExtension`| _Equivalent_<br/>(12018/12019)| `Communication.modifierExtension`| _Equivalent_<br/>(23827/23828)| `Communication.modifierExtension`| _Equivalent_<br/>(39147/39148)| `Communication.modifierExtension`
| **`Communication.identifier`**| _Equivalent_<br/>(3758/3759)| `Communication.identifier`| _Equivalent_<br/>(12020/12021)| `Communication.identifier`| _Equivalent_<br/>(23829/23830)| `Communication.identifier`| _Equivalent_<br/>(39149/39150)| `Communication.identifier`
| **`Communication.category`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3760)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3761)| `Communication.category`| _Equivalent_<br/>(12028/12029)| `Communication.category`| _Equivalent_<br/>(23845/23846)| `Communication.category`| _Equivalent_<br/>(39165/39166)| `Communication.category`
| **`Communication.sender`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3762)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3763)| `Communication.sender`| →→→→ _RelatedTo_ →→→→ <br/>(12041)<hr/>←←←← _RelatedTo_ ←←←← <br/>(12042)| `Communication.sender`| _Equivalent_<br/>(23865/23866)| `Communication.sender`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(39185)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(39186)| `Communication.sender`
| **`Communication.recipient`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3764)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3765)| `Communication.recipient`| →→→→ _RelatedTo_ →→→→ <br/>(12034)<hr/>←←←← _RelatedTo_ ←←←← <br/>(12035)| `Communication.recipient`| _Equivalent_<br/>(23863/23864)| `Communication.recipient`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(39183)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(39184)| `Communication.recipient`
| **`Communication.payload`**| _Equivalent_<br/>(3766/3767)| `Communication.payload`| _Equivalent_<br/>(12047/12048)| `Communication.payload`| _Equivalent_<br/>(23871/23872)| `Communication.payload`| _Equivalent_<br/>(39187/39188)| `Communication.payload`
| **`Communication.payload.id`**| _Equivalent_<br/>(3768/3769)| `Communication.payload.id`| _Equivalent_<br/>(12049/12050)| `Communication.payload.id`| _Equivalent_<br/>(23873/23874)| `Communication.payload.id`| _Equivalent_<br/>(39189/39190)| `Communication.payload.id`
| **`Communication.payload.extension`**| _Equivalent_<br/>(3770/3771)| `Communication.payload.extension`| _Equivalent_<br/>(12051/12052)| `Communication.payload.extension`| _Equivalent_<br/>(23875/23876)| `Communication.payload.extension`| _Equivalent_<br/>(39191/39192)| `Communication.payload.extension`
| **`Communication.payload.modifierExtension`**| _Equivalent_<br/>(3772/3773)| `Communication.payload.modifierExtension`| _Equivalent_<br/>(12053/12054)| `Communication.payload.modifierExtension`| _Equivalent_<br/>(23877/23878)| `Communication.payload.modifierExtension`| _Equivalent_<br/>(39193/39194)| `Communication.payload.modifierExtension`
| **`Communication.payload.content[x]`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3774)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3775)| `Communication.payload.content[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12055)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12056)| `Communication.payload.content[x]`| _Equivalent_<br/>(23879/23880)| `Communication.payload.content[x]`| →→→→ _RelatedTo_ →→→→ <br/>(39195)<hr/>←←←← _RelatedTo_ ←←←← <br/>(39196)| `Communication.payload.content[x]`
| **`Communication.medium`**| _Equivalent_<br/>(3776/3777)| `Communication.medium`| _Equivalent_<br/>(12030/12031)| `Communication.medium`| _Equivalent_<br/>(23849/23850)| `Communication.medium`| _Equivalent_<br/>(39169/39170)| `Communication.medium`
| **`Communication.status`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3778)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3779)| `Communication.status`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12026)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12027)| `Communication.status`| _Equivalent_<br/>(23841/23842)| `Communication.status`| _Equivalent_<br/>(39161/39162)| `Communication.status`
| **`Communication.encounter`**| →→→→ _RelatedTo_ →→→→ <br/>(135)<hr/>←←←← _RelatedTo_ ←←←← <br/>(555)| `Communication.context`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(893)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1409)| `Communication.encounter`| _Equivalent_<br/>(23857/23858)| `Communication.encounter`| _Equivalent_<br/>(39177/39178)| `Communication.encounter`
| **`Communication.sent`**| _Equivalent_<br/>(3780/3781)| `Communication.sent`| _Equivalent_<br/>(12037/12038)| `Communication.sent`| _Equivalent_<br/>(23859/23860)| `Communication.sent`| _Equivalent_<br/>(39179/39180)| `Communication.sent`
| **`Communication.received`**| _Equivalent_<br/>(3782/3783)| `Communication.received`| _Equivalent_<br/>(12039/12040)| `Communication.received`| _Equivalent_<br/>(23861/23862)| `Communication.received`| _Equivalent_<br/>(39181/39182)| `Communication.received`
| **`Communication.reason`**| _Equivalent_<br/>(136/556)| `Communication.reasonCode`| _Equivalent_<br/>(12043/12044)| `Communication.reasonCode`| _Equivalent_<br/>(23867/23868)| `Communication.reasonCode`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1866)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2108)| `Communication.reason`
| **`Communication.subject`**| →→→→ _RelatedTo_ →→→→ <br/>(3784)<hr/>←←←← _RelatedTo_ ←←←← <br/>(3785)| `Communication.subject`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12032)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12033)| `Communication.subject`| _Equivalent_<br/>(23851/23852)| `Communication.subject`| _Equivalent_<br/>(39171/39172)| `Communication.subject`
| **`Communication.requestDetail`**| →→→→ _RelatedTo_ →→→→ <br/>(137)<hr/>←←←← _RelatedTo_ ←←←← <br/>(554)| `Communication.basedOn`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12022)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12023)| `Communication.basedOn`| _Equivalent_<br/>(23835/23836)| `Communication.basedOn`| _Equivalent_<br/>(39155/39156)| `Communication.basedOn`
| *26 of 26 elements used* | | *26 of 33 elements used* <br/>remaining elements:<br/>`Communication.definition`, `Communication.notDone`, `Communication.notDoneReason`, `Communication.note`, `Communication.partOf`, `Communication.reasonReference`, `Communication.topic`| | *26 of 36 elements used* <br/>remaining elements:<br/>`Communication.about`, `Communication.inResponseTo`, `Communication.instantiatesCanonical`, `Communication.instantiatesUri`, `Communication.note`, `Communication.partOf`, `Communication.priority`, `Communication.reasonReference`, `Communication.statusReason`, `Communication.topic`| | *26 of 36 elements used* <br/>remaining elements:<br/>`Communication.about`, `Communication.inResponseTo`, `Communication.instantiatesCanonical`, `Communication.instantiatesUri`, `Communication.note`, `Communication.partOf`, `Communication.priority`, `Communication.reasonReference`, `Communication.statusReason`, `Communication.topic`| | *26 of 35 elements used* <br/>remaining elements:<br/>`Communication.about`, `Communication.inResponseTo`, `Communication.instantiatesCanonical`, `Communication.instantiatesUri`, `Communication.note`, `Communication.partOf`, `Communication.priority`, `Communication.statusReason`, `Communication.topic`

