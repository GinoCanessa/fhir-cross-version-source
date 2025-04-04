Comparison of 
Generated at Friday, April 4, 2025 2:58:57 PM

### Consent

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| Stucture Name | Consent |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Consent` |
| Version | 4.3.0 |
| Description | A record of a healthcare consumer’s  choices, which permits or denies identified recipient(s) or recipient role(s) to perform one or more actions within a given policy context, for specific purposes and periods of time. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1669` |
| Database Snapshot Count | `57` |
| Database Differential Count | `34` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Consent` | `Consent` | `Consent` | Consent | A healthcare consumer's  choices to permit or deny recipients or roles to perform actions for specific purposes and periods of time | 0..* | Consent |  |  |
| `Consent.category` | `Consent.category` | `category` | Consent.category | Classification of the consent statement - for indexing/retrieval | 1..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/consent-category` |
| `Consent.contained` | `Consent.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Consent.dateTime` | `Consent.dateTime` | `dateTime` | Consent.dateTime | When this Consent was created or indexed | 0..1 | dateTime |  |  |
| `Consent.extension` | `Consent.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Consent.id` | `Consent.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Consent.identifier` | `Consent.identifier` | `identifier` | Consent.identifier | Identifier for this record (external references) | 0..* | Identifier |  |  |
| `Consent.implicitRules` | `Consent.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Consent.language` | `Consent.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `Consent.meta` | `Consent.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Consent.modifierExtension` | `Consent.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Consent.organization` | `Consent.organization` | `organization` | Consent.organization | Custodian of the consent | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `Consent.patient` | `Consent.patient` | `patient` | Consent.patient | Who the consent applies to | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `Consent.performer` | `Consent.performer` | `performer` | Consent.performer | Who is agreeing to the policy and rules | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `Consent.policy` | `Consent.policy` | `policy` | Consent.policy | Policies covered by this consent | 0..* | BackboneElement |  |  |
| `Consent.policy.authority` | `Consent.policy.authority` | `authority` | Consent.policy.authority | Enforcement source for policy | 0..1 | uri |  |  |
| `Consent.policy.extension` | `Consent.policy.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Consent.policy.id` | `Consent.policy.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Consent.policy.modifierExtension` | `Consent.policy.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Consent.policy.uri` | `Consent.policy.uri` | `uri` | Consent.policy.uri | Specific policy covered by this consent | 0..1 | uri |  |  |
| `Consent.policyRule` | `Consent.policyRule` | `policyRule` | Consent.policyRule | Regulation that this consents to | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/consent-policy` |
| `Consent.provision` | `Consent.provision` | `provision` | Consent.provision | Constraints to the base Consent.policyRule | 0..1 | BackboneElement |  |  |
| `Consent.provision.action` | `Consent.provision.action` | `action` | Consent.provision.action | Actions controlled by this rule | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/consent-action` |
| `Consent.provision.actor` | `Consent.provision.actor` | `actor` | Consent.provision.actor | Who\|what controlled by this rule (or group, by role) | 0..* | BackboneElement |  |  |
| `Consent.provision.actor.extension` | `Consent.provision.actor.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Consent.provision.actor.id` | `Consent.provision.actor.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Consent.provision.actor.modifierExtension` | `Consent.provision.actor.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Consent.provision.actor.reference` | `Consent.provision.actor.reference` | `reference` | Consent.provision.actor.reference | Resource for the actor (or group, by role) | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/CareTeam), Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `Consent.provision.actor.role` | `Consent.provision.actor.role` | `role` | Consent.provision.actor.role | How the actor is involved | 1..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/security-role-type` |
| `Consent.provision.class` | `Consent.provision.class` | `class` | Consent.provision.class | e.g. Resource Type, Profile, CDA, etc. | 0..* | Coding | `Extensible` | `http://hl7.org/fhir/ValueSet/consent-content-class` |
| `Consent.provision.code` | `Consent.provision.code` | `code` | Consent.provision.code | e.g. LOINC or SNOMED CT code, etc. in the content | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/consent-content-code` |
| `Consent.provision.data` | `Consent.provision.data` | `data` | Consent.provision.data | Data controlled by this rule | 0..* | BackboneElement |  |  |
| `Consent.provision.data.extension` | `Consent.provision.data.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Consent.provision.data.id` | `Consent.provision.data.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Consent.provision.data.meaning` | `Consent.provision.data.meaning` | `meaning` | Consent.provision.data.meaning | instance \| related \| dependents \| authoredby | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/consent-data-meaning|4.3.0` |
| `Consent.provision.data.modifierExtension` | `Consent.provision.data.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Consent.provision.data.reference` | `Consent.provision.data.reference` | `reference` | Consent.provision.data.reference | The actual data reference | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `Consent.provision.dataPeriod` | `Consent.provision.dataPeriod` | `dataPeriod` | Consent.provision.dataPeriod | Timeframe for data controlled by this rule | 0..1 | Period |  |  |
| `Consent.provision.extension` | `Consent.provision.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Consent.provision.id` | `Consent.provision.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Consent.provision.modifierExtension` | `Consent.provision.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Consent.provision.period` | `Consent.provision.period` | `period` | Consent.provision.period | Timeframe for this rule | 0..1 | Period |  |  |
| `Consent.provision.provision` | `Consent.provision.provision` | `provision` | Consent.provision.provision | Nested Exception Rules | 0..* | Consent.provision |  |  |
| `Consent.provision.purpose` | `Consent.provision.purpose` | `purpose` | Consent.provision.purpose | Context of activities covered by this rule | 0..* | Coding | `Extensible` | `http://terminology.hl7.org/ValueSet/v3-PurposeOfUse` |
| `Consent.provision.securityLabel` | `Consent.provision.securityLabel` | `securityLabel` | Consent.provision.securityLabel | Security Labels that define affected resources | 0..* | Coding | `Extensible` | `http://hl7.org/fhir/ValueSet/security-labels` |
| `Consent.provision.type` | `Consent.provision.type` | `type` | Consent.provision.type | deny \| permit | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/consent-provision-type|4.3.0` |
| `Consent.scope` | `Consent.scope` | `scope` | Consent.scope | Which of the four areas this resource covers (extensible) | 1..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/consent-scope` |
| `Consent.source[x]` | `Consent.source[x]` | `source[x]` | Consent.source[x] | Source from which this consent is taken | 0..1 | Attachment, Reference(http://hl7.org/fhir/StructureDefinition/Consent), Reference(http://hl7.org/fhir/StructureDefinition/Contract), Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference), Reference(http://hl7.org/fhir/StructureDefinition/QuestionnaireResponse) |  |  |
| `Consent.status` | `Consent.status` | `status` | Consent.status | draft \| proposed \| active \| rejected \| inactive \| entered-in-error | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/consent-state-codes|4.3.0` |
| `Consent.text` | `Consent.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `Consent.verification` | `Consent.verification` | `verification` | Consent.verification | Consent Verified by patient or family | 0..* | BackboneElement |  |  |
| `Consent.verification.extension` | `Consent.verification.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Consent.verification.id` | `Consent.verification.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Consent.verification.modifierExtension` | `Consent.verification.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Consent.verification.verificationDate` | `Consent.verification.verificationDate` | `verificationDate` | Consent.verification.verificationDate | When consent verified | 0..1 | dateTime |  |  |
| `Consent.verification.verified` | `Consent.verification.verified` | `verified` | Consent.verification.verified | Has been verified | 1..1 | boolean |  |  |
| `Consent.verification.verifiedWith` | `Consent.verification.verifiedWith` | `verifiedWith` | Consent.verification.verifiedWith | Person who verified | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [Consent](/docs/R3/Resources/Consent.md)<br/> `http://hl7.org/fhir/StructureDefinition/Consent\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `440`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `636`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Consent](/docs/R4/Resources/Consent.md)<br/> `http://hl7.org/fhir/StructureDefinition/Consent\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1443`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1444`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Consent](/docs/R4B/Resources/Consent.md)<br/> `http://hl7.org/fhir/StructureDefinition/Consent\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `956`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1185`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Consent](/docs/R5/Resources/Consent.md)<br/> `http://hl7.org/fhir/StructureDefinition/Consent\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Consent from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | [R3 Consent](/docs/R3/Resources/Consent.md)| Relationship | [R4 Consent](/docs/R4/Resources/Consent.md)| Relationship | R4B Consent| Relationship | [R5 Consent](/docs/R5/Resources/Consent.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | `Consent`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(12523)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(12524)| `Consent`| _Equivalent_<br/>(24349/24350)| **`Consent`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(39603)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(39604)| `Consent`
| | | `Consent.id`| _Equivalent_<br/>(12525/12526)| `Consent.id`| _Equivalent_<br/>(24351/24352)| **`Consent.id`**| _Equivalent_<br/>(39605/39606)| `Consent.id`
| | | `Consent.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12527)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12528)| `Consent.meta`| _Equivalent_<br/>(24353/24354)| **`Consent.meta`**| _Equivalent_<br/>(39607/39608)| `Consent.meta`
| | | `Consent.implicitRules`| _Equivalent_<br/>(12529/12530)| `Consent.implicitRules`| _Equivalent_<br/>(24355/24356)| **`Consent.implicitRules`**| _Equivalent_<br/>(39609/39610)| `Consent.implicitRules`
| | | `Consent.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12531)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(12532)| `Consent.language`| _Equivalent_<br/>(24357/24358)| **`Consent.language`**| _Equivalent_<br/>(39611/39612)| `Consent.language`
| | | `Consent.text`| _Equivalent_<br/>(12533/12534)| `Consent.text`| _Equivalent_<br/>(24359/24360)| **`Consent.text`**| _Equivalent_<br/>(39613/39614)| `Consent.text`
| | | `Consent.contained`| _Equivalent_<br/>(12535/12536)| `Consent.contained`| _Equivalent_<br/>(24361/24362)| **`Consent.contained`**| _Equivalent_<br/>(39615/39616)| `Consent.contained`
| | | `Consent.extension`| _Equivalent_<br/>(12537/12538)| `Consent.extension`| _Equivalent_<br/>(24363/24364)| **`Consent.extension`**| _Equivalent_<br/>(39617/39618)| `Consent.extension`
| | | `Consent.modifierExtension`| _Equivalent_<br/>(12539/12540)| `Consent.modifierExtension`| _Equivalent_<br/>(24365/24366)| **`Consent.modifierExtension`**| _Equivalent_<br/>(39619/39620)| `Consent.modifierExtension`
| | | `Consent.identifier`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12541)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12542)| `Consent.identifier`| _Equivalent_<br/>(24367/24368)| **`Consent.identifier`**| _Equivalent_<br/>(39621/39622)| `Consent.identifier`
| | | `Consent.status`| _Equivalent_<br/>(12543/12544)| `Consent.status`| _Equivalent_<br/>(24369/24370)| **`Consent.status`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(39623)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(39624)| `Consent.status`
| | | | | `Consent.scope`| _Equivalent_<br/>(24371/24372)| **`Consent.scope`**| | | 
| | | `Consent.category`| →→→→ _RelatedTo_ →→→→ <br/>(12545)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(12546)| `Consent.category`| _Equivalent_<br/>(24373/24374)| **`Consent.category`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(39626)<hr/>←←←← _RelatedTo_ ←←←← <br/>(39627)| `Consent.category`
| | | `Consent.patient`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12547)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(12548)| `Consent.patient`| _Equivalent_<br/>(24375/24376)| **`Consent.patient`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1748)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1991)| `Consent.subject`
| | | `Consent.dateTime`| _Equivalent_<br/>(12549/12550)| `Consent.dateTime`| _Equivalent_<br/>(24377/24378)| **`Consent.dateTime`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1749)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1992)| `Consent.date`
| | | `Consent.consentingParty`| →→→→ _RelatedTo_ →→→→ <br/>(912)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1420)| `Consent.performer`| _Equivalent_<br/>(24379/24380)| **`Consent.performer`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1750)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1993)| `Consent.grantee`
| | | `Consent.organization`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12554)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12555)| `Consent.organization`| _Equivalent_<br/>(24381/24382)| **`Consent.organization`**| | | 
| | | `Consent.source[x]`| →→→→ _RelatedTo_ →→→→ <br/>(12556)<hr/>←←←← _RelatedTo_ ←←←← <br/>(12557)| `Consent.source[x]`| _Equivalent_<br/>(24383/24384)| **`Consent.source[x]`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1755)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1997)| `Consent.sourceAttachment`
| | | `Consent.source[x]`| →→→→ _RelatedTo_ →→→→ <br/>(12556)<hr/>←←←← _RelatedTo_ ←←←← <br/>(12557)| `Consent.source[x]`| _Equivalent_<br/>(24383/24384)| **`Consent.source[x]`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1755)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1997)| `Consent.sourceReference`
| | | `Consent.policy`| _Equivalent_<br/>(12558/12559)| `Consent.policy`| _Equivalent_<br/>(24385/24386)| **`Consent.policy`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1751)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1994)| `Consent.policyBasis`
| | | `Consent.policy.id`| _Equivalent_<br/>(12560/12561)| `Consent.policy.id`| _Equivalent_<br/>(24387/24388)| **`Consent.policy.id`**| | | 
| | | `Consent.policy.extension`| _Equivalent_<br/>(12562/12563)| `Consent.policy.extension`| _Equivalent_<br/>(24389/24390)| **`Consent.policy.extension`**| | | 
| | | `Consent.policy.modifierExtension`| _Equivalent_<br/>(12564/12565)| `Consent.policy.modifierExtension`| _Equivalent_<br/>(24391/24392)| **`Consent.policy.modifierExtension`**| | | 
| | | `Consent.policy.authority`| _Equivalent_<br/>(12566/12567)| `Consent.policy.authority`| _Equivalent_<br/>(24393/24394)| **`Consent.policy.authority`**| | | 
| | | `Consent.policy.uri`| _Equivalent_<br/>(12568/12569)| `Consent.policy.uri`| _Equivalent_<br/>(24395/24396)| **`Consent.policy.uri`**| | | 
| | | `Consent.policyRule`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(12570)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(12571)| `Consent.policyRule`| _Equivalent_<br/>(24397/24398)| **`Consent.policyRule`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1756)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1998)| `Consent.regulatoryBasis`
| | | | | `Consent.verification`| _Equivalent_<br/>(24399/24400)| **`Consent.verification`**| _Equivalent_<br/>(39634/39635)| `Consent.verification`
| | | | | `Consent.verification.id`| _Equivalent_<br/>(24401/24402)| **`Consent.verification.id`**| _Equivalent_<br/>(39636/39637)| `Consent.verification.id`
| | | | | `Consent.verification.extension`| _Equivalent_<br/>(24403/24404)| **`Consent.verification.extension`**| _Equivalent_<br/>(39638/39639)| `Consent.verification.extension`
| | | | | `Consent.verification.modifierExtension`| _Equivalent_<br/>(24405/24406)| **`Consent.verification.modifierExtension`**| _Equivalent_<br/>(39640/39641)| `Consent.verification.modifierExtension`
| | | | | `Consent.verification.verified`| _Equivalent_<br/>(24407/24408)| **`Consent.verification.verified`**| _Equivalent_<br/>(39642/39643)| `Consent.verification.verified`
| | | | | `Consent.verification.verifiedWith`| _Equivalent_<br/>(24409/24410)| **`Consent.verification.verifiedWith`**| _Equivalent_<br/>(39644/39645)| `Consent.verification.verifiedWith`
| | | | | `Consent.verification.verificationDate`| _Equivalent_<br/>(24411/24412)| **`Consent.verification.verificationDate`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(39646)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(39647)| `Consent.verification.verificationDate`
| | | `Consent.except`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(917)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1421)| `Consent.provision`| _Equivalent_<br/>(24413/24414)| **`Consent.provision`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(39648)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(39649)| `Consent.provision`
| | | | | `Consent.provision.id`| _Equivalent_<br/>(24415/24416)| **`Consent.provision.id`**| _Equivalent_<br/>(39650/39651)| `Consent.provision.id`
| | | | | `Consent.provision.extension`| _Equivalent_<br/>(24417/24418)| **`Consent.provision.extension`**| _Equivalent_<br/>(39652/39653)| `Consent.provision.extension`
| | | | | `Consent.provision.modifierExtension`| _Equivalent_<br/>(24419/24420)| **`Consent.provision.modifierExtension`**| _Equivalent_<br/>(39654/39655)| `Consent.provision.modifierExtension`
| | | `Consent.except.type`| →→→→ _Equivalent_ →→→→ <br/>(931)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1445)| `Consent.provision.type`| _Equivalent_<br/>(24421/24422)| **`Consent.provision.type`**| | | 
| | | `Consent.except.period`| _Equivalent_<br/>(928/1440)| `Consent.provision.period`| _Equivalent_<br/>(24423/24424)| **`Consent.provision.period`**| _Equivalent_<br/>(39657/39658)| `Consent.provision.period`
| | | `Consent.actor`| →→→→ _Equivalent_ →→→→ <br/>(909)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1425)| `Consent.provision.actor`| _Equivalent_<br/>(24425/24426)| **`Consent.provision.actor`**| _Equivalent_<br/>(39659/39660)| `Consent.provision.actor`
| | | `Consent.except.actor`| →→→→ _Equivalent_ →→→→ <br/>(919)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1425)| `Consent.provision.actor`| _Equivalent_<br/>(24425/24426)| **`Consent.provision.actor`**| _Equivalent_<br/>(39659/39660)| `Consent.provision.actor`
| | | | | `Consent.provision.actor.id`| _Equivalent_<br/>(24427/24428)| **`Consent.provision.actor.id`**| _Equivalent_<br/>(39661/39662)| `Consent.provision.actor.id`
| | | | | `Consent.provision.actor.extension`| _Equivalent_<br/>(24429/24430)| **`Consent.provision.actor.extension`**| _Equivalent_<br/>(39663/39664)| `Consent.provision.actor.extension`
| | | | | `Consent.provision.actor.modifierExtension`| _Equivalent_<br/>(24431/24432)| **`Consent.provision.actor.modifierExtension`**| _Equivalent_<br/>(39665/39666)| `Consent.provision.actor.modifierExtension`
| | | `Consent.actor.role`| →→→→ _Equivalent_ →→→→ <br/>(911)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1429)| `Consent.provision.actor.role`| _Equivalent_<br/>(24433/24434)| **`Consent.provision.actor.role`**| →→→→ _Equivalent_ →→→→ <br/>(39667)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(39668)| `Consent.provision.actor.role`
| | | `Consent.except.actor.role`| →→→→ _Equivalent_ →→→→ <br/>(921)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1429)| `Consent.provision.actor.role`| _Equivalent_<br/>(24433/24434)| **`Consent.provision.actor.role`**| →→→→ _Equivalent_ →→→→ <br/>(39667)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(39668)| `Consent.provision.actor.role`
| | | `Consent.actor.reference`| →→→→ _RelatedTo_ →→→→ <br/>(910)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1427)| `Consent.provision.actor.reference`| _Equivalent_<br/>(24435/24436)| **`Consent.provision.actor.reference`**| →→→→ _Equivalent_ →→→→ <br/>(39669)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(39670)| `Consent.provision.actor.reference`
| | | `Consent.except.actor.reference`| →→→→ _RelatedTo_ →→→→ <br/>(920)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1427)| `Consent.provision.actor.reference`| _Equivalent_<br/>(24435/24436)| **`Consent.provision.actor.reference`**| →→→→ _Equivalent_ →→→→ <br/>(39669)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(39670)| `Consent.provision.actor.reference`
| | | `Consent.action`| →→→→ _Equivalent_ →→→→ <br/>(908)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1423)| `Consent.provision.action`| _Equivalent_<br/>(24437/24438)| **`Consent.provision.action`**| _Equivalent_<br/>(39671/39672)| `Consent.provision.action`
| | | `Consent.except.action`| →→→→ _Equivalent_ →→→→ <br/>(918)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1423)| `Consent.provision.action`| _Equivalent_<br/>(24437/24438)| **`Consent.provision.action`**| _Equivalent_<br/>(39671/39672)| `Consent.provision.action`
| | | `Consent.securityLabel`| →→→→ _Equivalent_ →→→→ <br/>(934)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1443)| `Consent.provision.securityLabel`| _Equivalent_<br/>(24439/24440)| **`Consent.provision.securityLabel`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(39673)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(39674)| `Consent.provision.securityLabel`
| | | `Consent.except.securityLabel`| →→→→ _Equivalent_ →→→→ <br/>(930)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1443)| `Consent.provision.securityLabel`| _Equivalent_<br/>(24439/24440)| **`Consent.provision.securityLabel`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(39673)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(39674)| `Consent.provision.securityLabel`
| | | `Consent.purpose`| →→→→ _Equivalent_ →→→→ <br/>(933)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1441)| `Consent.provision.purpose`| _Equivalent_<br/>(24441/24442)| **`Consent.provision.purpose`**| _Equivalent_<br/>(39675/39676)| `Consent.provision.purpose`
| | | `Consent.except.purpose`| →→→→ _Equivalent_ →→→→ <br/>(929)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1441)| `Consent.provision.purpose`| _Equivalent_<br/>(24441/24442)| **`Consent.provision.purpose`**| _Equivalent_<br/>(39675/39676)| `Consent.provision.purpose`
| | | `Consent.except.class`| _Equivalent_<br/>(922/1430)| `Consent.provision.class`| _Equivalent_<br/>(24443/24444)| **`Consent.provision.class`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1752)<hr/>←←←← _Equivalent_ ←←←← <br/>(1995)| `Consent.provision.documentType`
| | | `Consent.except.class`| _Equivalent_<br/>(922/1430)| `Consent.provision.class`| _Equivalent_<br/>(24443/24444)| **`Consent.provision.class`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1752)<hr/>←←←← _Equivalent_ ←←←← <br/>(1995)| `Consent.provision.resourceType`
| | | `Consent.except.code`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(923)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1431)| `Consent.provision.code`| _Equivalent_<br/>(24445/24446)| **`Consent.provision.code`**| _Equivalent_<br/>(39677/39678)| `Consent.provision.code`
| | | `Consent.dataPeriod`| →→→→ _Equivalent_ →→→→ <br/>(916)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1439)| `Consent.provision.dataPeriod`| _Equivalent_<br/>(24447/24448)| **`Consent.provision.dataPeriod`**| _Equivalent_<br/>(39679/39680)| `Consent.provision.dataPeriod`
| | | `Consent.except.dataPeriod`| →→→→ _Equivalent_ →→→→ <br/>(927)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1439)| `Consent.provision.dataPeriod`| _Equivalent_<br/>(24447/24448)| **`Consent.provision.dataPeriod`**| _Equivalent_<br/>(39679/39680)| `Consent.provision.dataPeriod`
| | | `Consent.data`| →→→→ _Equivalent_ →→→→ <br/>(913)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1433)| `Consent.provision.data`| _Equivalent_<br/>(24449/24450)| **`Consent.provision.data`**| _Equivalent_<br/>(39681/39682)| `Consent.provision.data`
| | | `Consent.except.data`| →→→→ _Equivalent_ →→→→ <br/>(924)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1433)| `Consent.provision.data`| _Equivalent_<br/>(24449/24450)| **`Consent.provision.data`**| _Equivalent_<br/>(39681/39682)| `Consent.provision.data`
| | | | | `Consent.provision.data.id`| _Equivalent_<br/>(24451/24452)| **`Consent.provision.data.id`**| _Equivalent_<br/>(39683/39684)| `Consent.provision.data.id`
| | | | | `Consent.provision.data.extension`| _Equivalent_<br/>(24453/24454)| **`Consent.provision.data.extension`**| _Equivalent_<br/>(39685/39686)| `Consent.provision.data.extension`
| | | | | `Consent.provision.data.modifierExtension`| _Equivalent_<br/>(24455/24456)| **`Consent.provision.data.modifierExtension`**| _Equivalent_<br/>(39687/39688)| `Consent.provision.data.modifierExtension`
| | | `Consent.data.meaning`| →→→→ _Equivalent_ →→→→ <br/>(914)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1435)| `Consent.provision.data.meaning`| _Equivalent_<br/>(24457/24458)| **`Consent.provision.data.meaning`**| _Equivalent_<br/>(39689/39690)| `Consent.provision.data.meaning`
| | | `Consent.except.data.meaning`| →→→→ _Equivalent_ →→→→ <br/>(925)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1435)| `Consent.provision.data.meaning`| _Equivalent_<br/>(24457/24458)| **`Consent.provision.data.meaning`**| _Equivalent_<br/>(39689/39690)| `Consent.provision.data.meaning`
| | | `Consent.data.reference`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(915)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1437)| `Consent.provision.data.reference`| _Equivalent_<br/>(24459/24460)| **`Consent.provision.data.reference`**| _Equivalent_<br/>(39691/39692)| `Consent.provision.data.reference`
| | | `Consent.except.data.reference`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(926)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1437)| `Consent.provision.data.reference`| _Equivalent_<br/>(24459/24460)| **`Consent.provision.data.reference`**| _Equivalent_<br/>(39691/39692)| `Consent.provision.data.reference`
| | | | | `Consent.provision.provision`| _Equivalent_<br/>(24461/24462)| **`Consent.provision.provision`**| _Equivalent_<br/>(39693/39694)| `Consent.provision.provision`
| | | *49 of 65 elements used* <br/>remaining elements:<br/>`Consent.actor.extension`, `Consent.actor.id`, `Consent.actor.modifierExtension`, `Consent.data.extension`, `Consent.data.id`, `Consent.data.modifierExtension`, `Consent.except.actor.extension`, `Consent.except.actor.id`, `Consent.except.actor.modifierExtension`, `Consent.except.data.extension`, `Consent.except.data.id`, `Consent.except.data.modifierExtension`, `Consent.except.extension`, `Consent.except.id`, `Consent.except.modifierExtension`, `Consent.period`| | *57 of 57 elements used* | | *57 of 57 elements used* | | *51 of 65 elements used* <br/>remaining elements:<br/>`Consent.controller`, `Consent.decision`, `Consent.grantor`, `Consent.manager`, `Consent.period`, `Consent.policyBasis.extension`, `Consent.policyBasis.id`, `Consent.policyBasis.modifierExtension`, `Consent.policyBasis.reference`, `Consent.policyBasis.url`, `Consent.policyText`, `Consent.provision.expression`, `Consent.verification.verificationType`, `Consent.verification.verifiedBy`

