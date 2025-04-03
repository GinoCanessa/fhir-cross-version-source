Comparison of 
Generated at Thursday, April 3, 2025 8:18:08 AM

### NamingSystem

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | NamingSystem |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/NamingSystem` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for NamingSystem Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `100` |
| Database Snapshot Count | `34` |
| Database Differential Count | `20` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `NamingSystem` | `NamingSystem` | `NamingSystem` | NamingSystem | System of unique identification | 0..* | NamingSystem |  |  |
| `NamingSystem.contact` | `NamingSystem.contact` | `contact` |  | Contact details of the publisher | 0..* | BackboneElement |  |  |
| `NamingSystem.contact.extension` | `NamingSystem.contact.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `NamingSystem.contact.id` | `NamingSystem.contact.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `NamingSystem.contact.modifierExtension` | `NamingSystem.contact.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `NamingSystem.contact.name` | `NamingSystem.contact.name` | `name` |  | Name of a individual to contact | 0..1 | string |  |  |
| `NamingSystem.contact.telecom` | `NamingSystem.contact.telecom` | `telecom` |  | Contact details for individual or publisher | 0..* | ContactPoint |  |  |
| `NamingSystem.contained` | `NamingSystem.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `NamingSystem.date` | `NamingSystem.date` | `date` |  | Publication Date(/time) | 1..1 | dateTime |  |  |
| `NamingSystem.description` | `NamingSystem.description` | `description` |  | What does naming system identify? | 0..1 | string |  |  |
| `NamingSystem.extension` | `NamingSystem.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `NamingSystem.id` | `NamingSystem.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `NamingSystem.implicitRules` | `NamingSystem.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `NamingSystem.kind` | `NamingSystem.kind` | `kind` |  | codesystem \| identifier \| root | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/namingsystem-type` |
| `NamingSystem.language` | `NamingSystem.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `NamingSystem.meta` | `NamingSystem.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `NamingSystem.modifierExtension` | `NamingSystem.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `NamingSystem.name` | `NamingSystem.name` | `name` |  | Human-readable label | 1..1 | string |  |  |
| `NamingSystem.publisher` | `NamingSystem.publisher` | `publisher` |  | Name of the publisher (Organization or individual) | 0..1 | string |  |  |
| `NamingSystem.replacedBy` | `NamingSystem.replacedBy` | `replacedBy` |  | Use this instead | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/NamingSystem) |  |  |
| `NamingSystem.responsible` | `NamingSystem.responsible` | `responsible` |  | Who maintains system namespace? | 0..1 | string |  |  |
| `NamingSystem.status` | `NamingSystem.status` | `status` |  | draft \| active \| retired | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/conformance-resource-status` |
| `NamingSystem.text` | `NamingSystem.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `NamingSystem.type` | `NamingSystem.type` | `type` |  | e.g. driver,  provider,  patient, bank etc. | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/identifier-type` |
| `NamingSystem.uniqueId` | `NamingSystem.uniqueId` | `uniqueId` |  | Unique identifiers used for system | 1..* | BackboneElement |  |  |
| `NamingSystem.uniqueId.extension` | `NamingSystem.uniqueId.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `NamingSystem.uniqueId.id` | `NamingSystem.uniqueId.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `NamingSystem.uniqueId.modifierExtension` | `NamingSystem.uniqueId.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `NamingSystem.uniqueId.period` | `NamingSystem.uniqueId.period` | `period` |  | When is identifier valid? | 0..1 | Period |  |  |
| `NamingSystem.uniqueId.preferred` | `NamingSystem.uniqueId.preferred` | `preferred` |  | Is this the id that should be used for this type | 0..1 | boolean |  |  |
| `NamingSystem.uniqueId.type` | `NamingSystem.uniqueId.type` | `type` |  | oid \| uuid \| uri \| other | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/namingsystem-identifier-type` |
| `NamingSystem.uniqueId.value` | `NamingSystem.uniqueId.value` | `value` |  | The unique identifier | 1..1 | string |  |  |
| `NamingSystem.usage` | `NamingSystem.usage` | `usage` |  | How/where is it used | 0..1 | string |  |  |
| `NamingSystem.useContext` | `NamingSystem.useContext` | `useContext` |  | Content intends to support these contexts | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/use-context` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [NamingSystem](/docs/R2/Resources/NamingSystem.md)<br/> `http://hl7.org/fhir/StructureDefinition/NamingSystem\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `130`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `296`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [NamingSystem](/docs/R3/Resources/NamingSystem.md)<br/> `http://hl7.org/fhir/StructureDefinition/NamingSystem\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `487`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `681`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [NamingSystem](/docs/R4/Resources/NamingSystem.md)<br/> `http://hl7.org/fhir/StructureDefinition/NamingSystem\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1553`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1554`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [NamingSystem](/docs/R4B/Resources/NamingSystem.md)<br/> `http://hl7.org/fhir/StructureDefinition/NamingSystem\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1012`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1241`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [NamingSystem](/docs/R5/Resources/NamingSystem.md)<br/> `http://hl7.org/fhir/StructureDefinition/NamingSystem\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition NamingSystem from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 NamingSystem| Relationship | [R3 NamingSystem](/docs/R3/Resources/NamingSystem.md)| Relationship | [R4 NamingSystem](/docs/R4/Resources/NamingSystem.md)| Relationship | [R4B NamingSystem](/docs/R4B/Resources/NamingSystem.md)| Relationship | [R5 NamingSystem](/docs/R5/Resources/NamingSystem.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`NamingSystem`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(6429)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(6430)| `NamingSystem`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(16270)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(16271)| `NamingSystem`| _Equivalent_<br/>(30582/30583)| `NamingSystem`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(45174)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(45175)| `NamingSystem`
| **`NamingSystem.id`**| _Equivalent_<br/>(6431/6432)| `NamingSystem.id`| _Equivalent_<br/>(16272/16273)| `NamingSystem.id`| _Equivalent_<br/>(30584/30585)| `NamingSystem.id`| _Equivalent_<br/>(45176/45177)| `NamingSystem.id`
| **`NamingSystem.meta`**| _Equivalent_<br/>(6433/6434)| `NamingSystem.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16274)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(16275)| `NamingSystem.meta`| _Equivalent_<br/>(30586/30587)| `NamingSystem.meta`| _Equivalent_<br/>(45178/45179)| `NamingSystem.meta`
| **`NamingSystem.implicitRules`**| _Equivalent_<br/>(6435/6436)| `NamingSystem.implicitRules`| _Equivalent_<br/>(16276/16277)| `NamingSystem.implicitRules`| _Equivalent_<br/>(30588/30589)| `NamingSystem.implicitRules`| _Equivalent_<br/>(45180/45181)| `NamingSystem.implicitRules`
| **`NamingSystem.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(6437)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(6438)| `NamingSystem.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16278)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(16279)| `NamingSystem.language`| _Equivalent_<br/>(30590/30591)| `NamingSystem.language`| _Equivalent_<br/>(45182/45183)| `NamingSystem.language`
| **`NamingSystem.text`**| _Equivalent_<br/>(6439/6440)| `NamingSystem.text`| _Equivalent_<br/>(16280/16281)| `NamingSystem.text`| _Equivalent_<br/>(30592/30593)| `NamingSystem.text`| _Equivalent_<br/>(45184/45185)| `NamingSystem.text`
| **`NamingSystem.contained`**| _Equivalent_<br/>(6441/6442)| `NamingSystem.contained`| _Equivalent_<br/>(16282/16283)| `NamingSystem.contained`| _Equivalent_<br/>(30594/30595)| `NamingSystem.contained`| _Equivalent_<br/>(45186/45187)| `NamingSystem.contained`
| **`NamingSystem.extension`**| _Equivalent_<br/>(6443/6444)| `NamingSystem.extension`| _Equivalent_<br/>(16284/16285)| `NamingSystem.extension`| _Equivalent_<br/>(30596/30597)| `NamingSystem.extension`| _Equivalent_<br/>(45188/45189)| `NamingSystem.extension`
| **`NamingSystem.modifierExtension`**| _Equivalent_<br/>(6445/6446)| `NamingSystem.modifierExtension`| _Equivalent_<br/>(16286/16287)| `NamingSystem.modifierExtension`| _Equivalent_<br/>(30598/30599)| `NamingSystem.modifierExtension`| _Equivalent_<br/>(45190/45191)| `NamingSystem.modifierExtension`
| **`NamingSystem.name`**| _Equivalent_<br/>(6447/6448)| `NamingSystem.name`| _Equivalent_<br/>(16288/16289)| `NamingSystem.name`| _Equivalent_<br/>(30600/30601)| `NamingSystem.name`| _Equivalent_<br/>(45192/45193)| `NamingSystem.name`
| **`NamingSystem.status`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(6449)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6450)| `NamingSystem.status`| _Equivalent_<br/>(16290/16291)| `NamingSystem.status`| _Equivalent_<br/>(30602/30603)| `NamingSystem.status`| _Equivalent_<br/>(45194/45195)| `NamingSystem.status`
| **`NamingSystem.kind`**| _Equivalent_<br/>(6451/6452)| `NamingSystem.kind`| _Equivalent_<br/>(16292/16293)| `NamingSystem.kind`| _Equivalent_<br/>(30604/30605)| `NamingSystem.kind`| _Equivalent_<br/>(45196/45197)| `NamingSystem.kind`
| **`NamingSystem.publisher`**| _Equivalent_<br/>(6453/6454)| `NamingSystem.publisher`| _Equivalent_<br/>(16296/16297)| `NamingSystem.publisher`| _Equivalent_<br/>(30608/30609)| `NamingSystem.publisher`| _Equivalent_<br/>(45200/45201)| `NamingSystem.publisher`
| **`NamingSystem.contact`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(6455)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6456)| `NamingSystem.contact`| _Equivalent_<br/>(16298/16299)| `NamingSystem.contact`| _Equivalent_<br/>(30610/30611)| `NamingSystem.contact`| _Equivalent_<br/>(45202/45203)| `NamingSystem.contact`
| **`NamingSystem.contact.id`**| | | | | | | | | 
| **`NamingSystem.contact.extension`**| | | | | | | | | 
| **`NamingSystem.contact.modifierExtension`**| | | | | | | | | 
| **`NamingSystem.contact.name`**| | | | | | | | | 
| **`NamingSystem.contact.telecom`**| | | | | | | | | 
| **`NamingSystem.responsible`**| _Equivalent_<br/>(6462/6463)| `NamingSystem.responsible`| _Equivalent_<br/>(16300/16301)| `NamingSystem.responsible`| _Equivalent_<br/>(30612/30613)| `NamingSystem.responsible`| _Equivalent_<br/>(45204/45205)| `NamingSystem.responsible`
| **`NamingSystem.date`**| _Equivalent_<br/>(6464/6465)| `NamingSystem.date`| _Equivalent_<br/>(16294/16295)| `NamingSystem.date`| _Equivalent_<br/>(30606/30607)| `NamingSystem.date`| _Equivalent_<br/>(45198/45199)| `NamingSystem.date`
| **`NamingSystem.type`**| _Equivalent_<br/>(6466/6467)| `NamingSystem.type`| _Equivalent_<br/>(16302/16303)| `NamingSystem.type`| _Equivalent_<br/>(30614/30615)| `NamingSystem.type`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(45206)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(45207)| `NamingSystem.type`
| **`NamingSystem.description`**| _Equivalent_<br/>(6468/6469)| `NamingSystem.description`| _Equivalent_<br/>(16304/16305)| `NamingSystem.description`| _Equivalent_<br/>(30616/30617)| `NamingSystem.description`| _Equivalent_<br/>(45208/45209)| `NamingSystem.description`
| **`NamingSystem.useContext`**| _Equivalent_<br/>(458/789)| `NamingSystem.useContext`| _Equivalent_<br/>(16306/16307)| `NamingSystem.useContext`| _Equivalent_<br/>(30618/30619)| `NamingSystem.useContext`| _Equivalent_<br/>(45210/45211)| `NamingSystem.useContext`
| **`NamingSystem.useContext`**| _Equivalent_<br/>(458/789)| `NamingSystem.jurisdiction`| _Equivalent_<br/>(16308/16309)| `NamingSystem.jurisdiction`| _Equivalent_<br/>(30620/30621)| `NamingSystem.jurisdiction`| _Equivalent_<br/>(45212/45213)| `NamingSystem.jurisdiction`
| **`NamingSystem.usage`**| _Equivalent_<br/>(6470/6471)| `NamingSystem.usage`| _Equivalent_<br/>(16310/16311)| `NamingSystem.usage`| _Equivalent_<br/>(30622/30623)| `NamingSystem.usage`| _Equivalent_<br/>(45214/45215)| `NamingSystem.usage`
| **`NamingSystem.uniqueId`**| _Equivalent_<br/>(6472/6473)| `NamingSystem.uniqueId`| _Equivalent_<br/>(16312/16313)| `NamingSystem.uniqueId`| _Equivalent_<br/>(30624/30625)| `NamingSystem.uniqueId`| _Equivalent_<br/>(45216/45217)| `NamingSystem.uniqueId`
| **`NamingSystem.uniqueId.id`**| _Equivalent_<br/>(6474/6475)| `NamingSystem.uniqueId.id`| _Equivalent_<br/>(16314/16315)| `NamingSystem.uniqueId.id`| _Equivalent_<br/>(30626/30627)| `NamingSystem.uniqueId.id`| _Equivalent_<br/>(45218/45219)| `NamingSystem.uniqueId.id`
| **`NamingSystem.uniqueId.extension`**| _Equivalent_<br/>(6476/6477)| `NamingSystem.uniqueId.extension`| _Equivalent_<br/>(16316/16317)| `NamingSystem.uniqueId.extension`| _Equivalent_<br/>(30628/30629)| `NamingSystem.uniqueId.extension`| _Equivalent_<br/>(45220/45221)| `NamingSystem.uniqueId.extension`
| **`NamingSystem.uniqueId.modifierExtension`**| _Equivalent_<br/>(6478/6479)| `NamingSystem.uniqueId.modifierExtension`| _Equivalent_<br/>(16318/16319)| `NamingSystem.uniqueId.modifierExtension`| _Equivalent_<br/>(30630/30631)| `NamingSystem.uniqueId.modifierExtension`| _Equivalent_<br/>(45222/45223)| `NamingSystem.uniqueId.modifierExtension`
| **`NamingSystem.uniqueId.type`**| _Equivalent_<br/>(6480/6481)| `NamingSystem.uniqueId.type`| _Equivalent_<br/>(16320/16321)| `NamingSystem.uniqueId.type`| _Equivalent_<br/>(30632/30633)| `NamingSystem.uniqueId.type`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(45224)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(45225)| `NamingSystem.uniqueId.type`
| **`NamingSystem.uniqueId.value`**| _Equivalent_<br/>(6482/6483)| `NamingSystem.uniqueId.value`| _Equivalent_<br/>(16322/16323)| `NamingSystem.uniqueId.value`| _Equivalent_<br/>(30634/30635)| `NamingSystem.uniqueId.value`| _Equivalent_<br/>(45226/45227)| `NamingSystem.uniqueId.value`
| **`NamingSystem.uniqueId.preferred`**| _Equivalent_<br/>(6484/6485)| `NamingSystem.uniqueId.preferred`| _Equivalent_<br/>(16324/16325)| `NamingSystem.uniqueId.preferred`| _Equivalent_<br/>(30636/30637)| `NamingSystem.uniqueId.preferred`| _Equivalent_<br/>(45228/45229)| `NamingSystem.uniqueId.preferred`
| **`NamingSystem.uniqueId.period`**| _Equivalent_<br/>(6486/6487)| `NamingSystem.uniqueId.period`| _Equivalent_<br/>(16328/16329)| `NamingSystem.uniqueId.period`| _Equivalent_<br/>(30640/30641)| `NamingSystem.uniqueId.period`| _Equivalent_<br/>(45232/45233)| `NamingSystem.uniqueId.period`
| **`NamingSystem.replacedBy`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(6488)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6489)| `NamingSystem.replacedBy`| | | | | | | 
| *34 of 34 elements used* | | *30 of 31 elements used* <br/>remaining elements:<br/>`NamingSystem.uniqueId.comment`| | *29 of 30 elements used* <br/>remaining elements:<br/>`NamingSystem.uniqueId.comment`| | *29 of 30 elements used* <br/>remaining elements:<br/>`NamingSystem.uniqueId.comment`| | *29 of 49 elements used* <br/>remaining elements:<br/>`NamingSystem.approvalDate`, `NamingSystem.author`, `NamingSystem.copyright`, `NamingSystem.copyrightLabel`, `NamingSystem.editor`, `NamingSystem.effectivePeriod`, `NamingSystem.endorser`, `NamingSystem.experimental`, `NamingSystem.identifier`, `NamingSystem.lastReviewDate`, `NamingSystem.purpose`, `NamingSystem.relatedArtifact`, `NamingSystem.reviewer`, `NamingSystem.title`, `NamingSystem.topic`, `NamingSystem.uniqueId.authoritative`, `NamingSystem.uniqueId.comment`, `NamingSystem.url`, `NamingSystem.version`, `NamingSystem.versionAlgorithm[x]`

