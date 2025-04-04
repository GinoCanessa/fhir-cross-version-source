Comparison of 
Generated at Friday, April 4, 2025 2:58:40 PM

### Consent

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | Consent |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Consent` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for Consent Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `500` |
| Database Snapshot Count | `65` |
| Database Differential Count | `39` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Consent` | `Consent` | `Consent` | Consent | A healthcare consumer's policy choices to permits or denies recipients or roles to perform actions for specific purposes and periods of time | 0..* | Consent |  |  |
| `Consent.action` | `Consent.action` | `action` |  | Actions controlled by this consent | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/consent-action` |
| `Consent.actor` | `Consent.actor` | `actor` |  | Who\|what controlled by this consent (or group, by role) | 0..* | BackboneElement |  |  |
| `Consent.actor.extension` | `Consent.actor.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Consent.actor.id` | `Consent.actor.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Consent.actor.modifierExtension` | `Consent.actor.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Consent.actor.reference` | `Consent.actor.reference` | `reference` |  | Resource for the actor (or group, by role) | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/CareTeam), Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `Consent.actor.role` | `Consent.actor.role` | `role` |  | How the actor is involved | 1..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/security-role-type` |
| `Consent.category` | `Consent.category` | `category` |  | Classification of the consent statement - for indexing/retrieval | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/consent-category` |
| `Consent.consentingParty` | `Consent.consentingParty` | `consentingParty` |  | Who is agreeing to the policy and exceptions | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `Consent.contained` | `Consent.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Consent.data` | `Consent.data` | `data` |  | Data controlled by this consent | 0..* | BackboneElement |  |  |
| `Consent.data.extension` | `Consent.data.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Consent.data.id` | `Consent.data.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Consent.data.meaning` | `Consent.data.meaning` | `meaning` |  | instance \| related \| dependents \| authoredby | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/consent-data-meaning` |
| `Consent.data.modifierExtension` | `Consent.data.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Consent.data.reference` | `Consent.data.reference` | `reference` |  | The actual data reference | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `Consent.dataPeriod` | `Consent.dataPeriod` | `dataPeriod` |  | Timeframe for data controlled by this consent | 0..1 | Period |  |  |
| `Consent.dateTime` | `Consent.dateTime` | `dateTime` |  | When this Consent was created or indexed | 0..1 | dateTime |  |  |
| `Consent.except` | `Consent.except` | `except` |  | Additional rule -  addition or removal of permissions | 0..* | BackboneElement |  |  |
| `Consent.except.action` | `Consent.except.action` | `action` |  | Actions controlled by this exception | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/consent-action` |
| `Consent.except.actor` | `Consent.except.actor` | `actor` |  | Who\|what controlled by this exception (or group, by role) | 0..* | BackboneElement |  |  |
| `Consent.except.actor.extension` | `Consent.except.actor.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Consent.except.actor.id` | `Consent.except.actor.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Consent.except.actor.modifierExtension` | `Consent.except.actor.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Consent.except.actor.reference` | `Consent.except.actor.reference` | `reference` |  | Resource for the actor (or group, by role) | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/CareTeam), Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `Consent.except.actor.role` | `Consent.except.actor.role` | `role` |  | How the actor is involved | 1..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/security-role-type` |
| `Consent.except.class` | `Consent.except.class` | `class` |  | e.g. Resource Type, Profile, or CDA etc | 0..* | Coding | `Extensible` | `http://hl7.org/fhir/ValueSet/consent-content-class` |
| `Consent.except.code` | `Consent.except.code` | `code` |  | e.g. LOINC or SNOMED CT code, etc in the content | 0..* | Coding | `Example` | `http://hl7.org/fhir/ValueSet/consent-content-code` |
| `Consent.except.data` | `Consent.except.data` | `data` |  | Data controlled by this exception | 0..* | BackboneElement |  |  |
| `Consent.except.data.extension` | `Consent.except.data.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Consent.except.data.id` | `Consent.except.data.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Consent.except.data.meaning` | `Consent.except.data.meaning` | `meaning` |  | instance \| related \| dependents \| authoredby | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/consent-data-meaning` |
| `Consent.except.data.modifierExtension` | `Consent.except.data.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Consent.except.data.reference` | `Consent.except.data.reference` | `reference` |  | The actual data reference | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `Consent.except.dataPeriod` | `Consent.except.dataPeriod` | `dataPeriod` |  | Timeframe for data controlled by this exception | 0..1 | Period |  |  |
| `Consent.except.extension` | `Consent.except.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Consent.except.id` | `Consent.except.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Consent.except.modifierExtension` | `Consent.except.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Consent.except.period` | `Consent.except.period` | `period` |  | Timeframe for this exception | 0..1 | Period |  |  |
| `Consent.except.purpose` | `Consent.except.purpose` | `purpose` |  | Context of activities covered by this exception | 0..* | Coding | `Extensible` | `http://hl7.org/fhir/ValueSet/v3-PurposeOfUse` |
| `Consent.except.securityLabel` | `Consent.except.securityLabel` | `securityLabel` |  | Security Labels that define affected resources | 0..* | Coding | `Extensible` | `http://hl7.org/fhir/ValueSet/security-labels` |
| `Consent.except.type` | `Consent.except.type` | `type` |  | deny \| permit | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/consent-except-type` |
| `Consent.extension` | `Consent.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Consent.id` | `Consent.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Consent.identifier` | `Consent.identifier` | `identifier` |  | Identifier for this record (external references) | 0..1 | Identifier |  |  |
| `Consent.implicitRules` | `Consent.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Consent.language` | `Consent.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `Consent.meta` | `Consent.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Consent.modifierExtension` | `Consent.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Consent.organization` | `Consent.organization` | `organization` |  | Custodian of the consent | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `Consent.patient` | `Consent.patient` | `patient` |  | Who the consent applies to | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `Consent.period` | `Consent.period` | `period` |  | Period that this consent applies | 0..1 | Period |  |  |
| `Consent.policy` | `Consent.policy` | `policy` |  | Policies covered by this consent | 0..* | BackboneElement |  |  |
| `Consent.policy.authority` | `Consent.policy.authority` | `authority` |  | Enforcement source for policy | 0..1 | uri |  |  |
| `Consent.policy.extension` | `Consent.policy.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Consent.policy.id` | `Consent.policy.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Consent.policy.modifierExtension` | `Consent.policy.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Consent.policy.uri` | `Consent.policy.uri` | `uri` |  | Specific policy covered by this consent | 0..1 | uri |  |  |
| `Consent.policyRule` | `Consent.policyRule` | `policyRule` |  | Policy that this consents to | 0..1 | uri |  |  |
| `Consent.purpose` | `Consent.purpose` | `purpose` |  | Context of activities for which the agreement is made | 0..* | Coding | `Extensible` | `http://hl7.org/fhir/ValueSet/v3-PurposeOfUse` |
| `Consent.securityLabel` | `Consent.securityLabel` | `securityLabel` |  | Security Labels that define affected resources | 0..* | Coding | `Extensible` | `http://hl7.org/fhir/ValueSet/security-labels` |
| `Consent.source[x]` | `Consent.source[x]` | `source[x]` |  | Source from which this consent is taken | 0..1 | Attachment, Identifier, Reference(http://hl7.org/fhir/StructureDefinition/Consent), Reference(http://hl7.org/fhir/StructureDefinition/Contract), Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference), Reference(http://hl7.org/fhir/StructureDefinition/QuestionnaireResponse) |  |  |
| `Consent.status` | `Consent.status` | `status` |  | draft \| proposed \| active \| rejected \| inactive \| entered-in-error | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/consent-state-codes` |
| `Consent.text` | `Consent.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [Consent](/docs/R3/Resources/Consent.md)<br/> `http://hl7.org/fhir/StructureDefinition/Consent\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `440`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `636`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Consent](/docs/R4/Resources/Consent.md)<br/> `http://hl7.org/fhir/StructureDefinition/Consent\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1443`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1444`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Consent](/docs/R4B/Resources/Consent.md)<br/> `http://hl7.org/fhir/StructureDefinition/Consent\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `956`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1185`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Consent](/docs/R5/Resources/Consent.md)<br/> `http://hl7.org/fhir/StructureDefinition/Consent\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Consent from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | R3 Consent| Relationship | [R4 Consent](/docs/R4/Resources/Consent.md)| Relationship | [R4B Consent](/docs/R4B/Resources/Consent.md)| Relationship | [R5 Consent](/docs/R5/Resources/Consent.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | **`Consent`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(12523)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(12524)| `Consent`| _Equivalent_<br/>(24349/24350)| `Consent`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(39603)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(39604)| `Consent`
| | | **`Consent.id`**| _Equivalent_<br/>(12525/12526)| `Consent.id`| _Equivalent_<br/>(24351/24352)| `Consent.id`| _Equivalent_<br/>(39605/39606)| `Consent.id`
| | | **`Consent.meta`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12527)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12528)| `Consent.meta`| _Equivalent_<br/>(24353/24354)| `Consent.meta`| _Equivalent_<br/>(39607/39608)| `Consent.meta`
| | | **`Consent.implicitRules`**| _Equivalent_<br/>(12529/12530)| `Consent.implicitRules`| _Equivalent_<br/>(24355/24356)| `Consent.implicitRules`| _Equivalent_<br/>(39609/39610)| `Consent.implicitRules`
| | | **`Consent.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12531)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(12532)| `Consent.language`| _Equivalent_<br/>(24357/24358)| `Consent.language`| _Equivalent_<br/>(39611/39612)| `Consent.language`
| | | **`Consent.text`**| _Equivalent_<br/>(12533/12534)| `Consent.text`| _Equivalent_<br/>(24359/24360)| `Consent.text`| _Equivalent_<br/>(39613/39614)| `Consent.text`
| | | **`Consent.contained`**| _Equivalent_<br/>(12535/12536)| `Consent.contained`| _Equivalent_<br/>(24361/24362)| `Consent.contained`| _Equivalent_<br/>(39615/39616)| `Consent.contained`
| | | **`Consent.extension`**| _Equivalent_<br/>(12537/12538)| `Consent.extension`| _Equivalent_<br/>(24363/24364)| `Consent.extension`| _Equivalent_<br/>(39617/39618)| `Consent.extension`
| | | **`Consent.modifierExtension`**| _Equivalent_<br/>(12539/12540)| `Consent.modifierExtension`| _Equivalent_<br/>(24365/24366)| `Consent.modifierExtension`| _Equivalent_<br/>(39619/39620)| `Consent.modifierExtension`
| | | **`Consent.identifier`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12541)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12542)| `Consent.identifier`| _Equivalent_<br/>(24367/24368)| `Consent.identifier`| _Equivalent_<br/>(39621/39622)| `Consent.identifier`
| | | **`Consent.status`**| _Equivalent_<br/>(12543/12544)| `Consent.status`| _Equivalent_<br/>(24369/24370)| `Consent.status`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(39623)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(39624)| `Consent.status`
| | | **`Consent.category`**| →→→→ _RelatedTo_ →→→→ <br/>(12545)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(12546)| `Consent.category`| _Equivalent_<br/>(24373/24374)| `Consent.category`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(39626)<hr/>←←←← _RelatedTo_ ←←←← <br/>(39627)| `Consent.category`
| | | **`Consent.patient`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12547)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(12548)| `Consent.patient`| _Equivalent_<br/>(24375/24376)| `Consent.patient`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1748)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1991)| `Consent.subject`
| | | **`Consent.period`**| | | | | | | 
| | | **`Consent.dateTime`**| _Equivalent_<br/>(12549/12550)| `Consent.dateTime`| _Equivalent_<br/>(24377/24378)| `Consent.dateTime`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1749)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1992)| `Consent.date`
| | | **`Consent.consentingParty`**| →→→→ _RelatedTo_ →→→→ <br/>(912)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1420)| `Consent.performer`| _Equivalent_<br/>(24379/24380)| `Consent.performer`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1750)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1993)| `Consent.grantee`
| | | **`Consent.actor`**| →→→→ _Equivalent_ →→→→ <br/>(909)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1424)| `Consent.provision.actor`| _Equivalent_<br/>(24425/24426)| `Consent.provision.actor`| _Equivalent_<br/>(39659/39660)| `Consent.provision.actor`
| | | **`Consent.actor.id`**| | | | | | | 
| | | **`Consent.actor.extension`**| | | | | | | 
| | | **`Consent.actor.modifierExtension`**| | | | | | | 
| | | **`Consent.actor.role`**| →→→→ _Equivalent_ →→→→ <br/>(911)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1428)| `Consent.provision.actor.role`| _Equivalent_<br/>(24433/24434)| `Consent.provision.actor.role`| →→→→ _Equivalent_ →→→→ <br/>(39667)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(39668)| `Consent.provision.actor.role`
| | | **`Consent.actor.reference`**| →→→→ _RelatedTo_ →→→→ <br/>(910)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1426)| `Consent.provision.actor.reference`| _Equivalent_<br/>(24435/24436)| `Consent.provision.actor.reference`| →→→→ _Equivalent_ →→→→ <br/>(39669)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(39670)| `Consent.provision.actor.reference`
| | | **`Consent.action`**| →→→→ _Equivalent_ →→→→ <br/>(908)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1422)| `Consent.provision.action`| _Equivalent_<br/>(24437/24438)| `Consent.provision.action`| _Equivalent_<br/>(39671/39672)| `Consent.provision.action`
| | | **`Consent.organization`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12554)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12555)| `Consent.organization`| _Equivalent_<br/>(24381/24382)| `Consent.organization`| | | 
| | | **`Consent.source[x]`**| →→→→ _RelatedTo_ →→→→ <br/>(12556)<hr/>←←←← _RelatedTo_ ←←←← <br/>(12557)| `Consent.source[x]`| _Equivalent_<br/>(24383/24384)| `Consent.source[x]`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1755)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1997)| `Consent.sourceAttachment`
| | | **`Consent.source[x]`**| →→→→ _RelatedTo_ →→→→ <br/>(12556)<hr/>←←←← _RelatedTo_ ←←←← <br/>(12557)| `Consent.source[x]`| _Equivalent_<br/>(24383/24384)| `Consent.source[x]`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1755)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1997)| `Consent.sourceReference`
| | | **`Consent.policy`**| _Equivalent_<br/>(12558/12559)| `Consent.policy`| _Equivalent_<br/>(24385/24386)| `Consent.policy`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1751)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1994)| `Consent.policyBasis`
| | | **`Consent.policy.id`**| _Equivalent_<br/>(12560/12561)| `Consent.policy.id`| _Equivalent_<br/>(24387/24388)| `Consent.policy.id`| | | 
| | | **`Consent.policy.extension`**| _Equivalent_<br/>(12562/12563)| `Consent.policy.extension`| _Equivalent_<br/>(24389/24390)| `Consent.policy.extension`| | | 
| | | **`Consent.policy.modifierExtension`**| _Equivalent_<br/>(12564/12565)| `Consent.policy.modifierExtension`| _Equivalent_<br/>(24391/24392)| `Consent.policy.modifierExtension`| | | 
| | | **`Consent.policy.authority`**| _Equivalent_<br/>(12566/12567)| `Consent.policy.authority`| _Equivalent_<br/>(24393/24394)| `Consent.policy.authority`| | | 
| | | **`Consent.policy.uri`**| _Equivalent_<br/>(12568/12569)| `Consent.policy.uri`| _Equivalent_<br/>(24395/24396)| `Consent.policy.uri`| | | 
| | | **`Consent.policyRule`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(12570)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(12571)| `Consent.policyRule`| _Equivalent_<br/>(24397/24398)| `Consent.policyRule`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1756)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1998)| `Consent.regulatoryBasis`
| | | **`Consent.securityLabel`**| →→→→ _Equivalent_ →→→→ <br/>(934)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1444)| `Consent.provision.securityLabel`| _Equivalent_<br/>(24439/24440)| `Consent.provision.securityLabel`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(39673)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(39674)| `Consent.provision.securityLabel`
| | | **`Consent.purpose`**| →→→→ _Equivalent_ →→→→ <br/>(933)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1442)| `Consent.provision.purpose`| _Equivalent_<br/>(24441/24442)| `Consent.provision.purpose`| _Equivalent_<br/>(39675/39676)| `Consent.provision.purpose`
| | | **`Consent.dataPeriod`**| →→→→ _Equivalent_ →→→→ <br/>(916)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1438)| `Consent.provision.dataPeriod`| _Equivalent_<br/>(24447/24448)| `Consent.provision.dataPeriod`| _Equivalent_<br/>(39679/39680)| `Consent.provision.dataPeriod`
| | | **`Consent.data`**| →→→→ _Equivalent_ →→→→ <br/>(913)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1432)| `Consent.provision.data`| _Equivalent_<br/>(24449/24450)| `Consent.provision.data`| _Equivalent_<br/>(39681/39682)| `Consent.provision.data`
| | | **`Consent.data.id`**| | | | | | | 
| | | **`Consent.data.extension`**| | | | | | | 
| | | **`Consent.data.modifierExtension`**| | | | | | | 
| | | **`Consent.data.meaning`**| →→→→ _Equivalent_ →→→→ <br/>(914)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1434)| `Consent.provision.data.meaning`| _Equivalent_<br/>(24457/24458)| `Consent.provision.data.meaning`| _Equivalent_<br/>(39689/39690)| `Consent.provision.data.meaning`
| | | **`Consent.data.reference`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(915)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1436)| `Consent.provision.data.reference`| _Equivalent_<br/>(24459/24460)| `Consent.provision.data.reference`| _Equivalent_<br/>(39691/39692)| `Consent.provision.data.reference`
| | | **`Consent.except`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(917)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1421)| `Consent.provision`| _Equivalent_<br/>(24413/24414)| `Consent.provision`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(39648)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(39649)| `Consent.provision`
| | | **`Consent.except.id`**| | | | | | | 
| | | **`Consent.except.extension`**| | | | | | | 
| | | **`Consent.except.modifierExtension`**| | | | | | | 
| | | **`Consent.except.type`**| →→→→ _Equivalent_ →→→→ <br/>(931)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1445)| `Consent.provision.type`| _Equivalent_<br/>(24421/24422)| `Consent.provision.type`| | | 
| | | **`Consent.except.period`**| _Equivalent_<br/>(928/1440)| `Consent.provision.period`| _Equivalent_<br/>(24423/24424)| `Consent.provision.period`| _Equivalent_<br/>(39657/39658)| `Consent.provision.period`
| | | **`Consent.except.actor`**| →→→→ _Equivalent_ →→→→ <br/>(919)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1425)| `Consent.provision.actor`| _Equivalent_<br/>(24425/24426)| `Consent.provision.actor`| _Equivalent_<br/>(39659/39660)| `Consent.provision.actor`
| | | **`Consent.except.actor.id`**| | | | | | | 
| | | **`Consent.except.actor.extension`**| | | | | | | 
| | | **`Consent.except.actor.modifierExtension`**| | | | | | | 
| | | **`Consent.except.actor.role`**| →→→→ _Equivalent_ →→→→ <br/>(921)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1429)| `Consent.provision.actor.role`| _Equivalent_<br/>(24433/24434)| `Consent.provision.actor.role`| →→→→ _Equivalent_ →→→→ <br/>(39667)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(39668)| `Consent.provision.actor.role`
| | | **`Consent.except.actor.reference`**| →→→→ _RelatedTo_ →→→→ <br/>(920)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1427)| `Consent.provision.actor.reference`| _Equivalent_<br/>(24435/24436)| `Consent.provision.actor.reference`| →→→→ _Equivalent_ →→→→ <br/>(39669)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(39670)| `Consent.provision.actor.reference`
| | | **`Consent.except.action`**| →→→→ _Equivalent_ →→→→ <br/>(918)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1423)| `Consent.provision.action`| _Equivalent_<br/>(24437/24438)| `Consent.provision.action`| _Equivalent_<br/>(39671/39672)| `Consent.provision.action`
| | | **`Consent.except.securityLabel`**| →→→→ _Equivalent_ →→→→ <br/>(930)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1443)| `Consent.provision.securityLabel`| _Equivalent_<br/>(24439/24440)| `Consent.provision.securityLabel`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(39673)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(39674)| `Consent.provision.securityLabel`
| | | **`Consent.except.purpose`**| →→→→ _Equivalent_ →→→→ <br/>(929)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1441)| `Consent.provision.purpose`| _Equivalent_<br/>(24441/24442)| `Consent.provision.purpose`| _Equivalent_<br/>(39675/39676)| `Consent.provision.purpose`
| | | **`Consent.except.class`**| _Equivalent_<br/>(922/1430)| `Consent.provision.class`| _Equivalent_<br/>(24443/24444)| `Consent.provision.class`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1752)<hr/>←←←← _Equivalent_ ←←←← <br/>(1995)| `Consent.provision.documentType`
| | | **`Consent.except.class`**| _Equivalent_<br/>(922/1430)| `Consent.provision.class`| _Equivalent_<br/>(24443/24444)| `Consent.provision.class`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1752)<hr/>←←←← _Equivalent_ ←←←← <br/>(1995)| `Consent.provision.resourceType`
| | | **`Consent.except.code`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(923)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1431)| `Consent.provision.code`| _Equivalent_<br/>(24445/24446)| `Consent.provision.code`| _Equivalent_<br/>(39677/39678)| `Consent.provision.code`
| | | **`Consent.except.dataPeriod`**| →→→→ _Equivalent_ →→→→ <br/>(927)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1439)| `Consent.provision.dataPeriod`| _Equivalent_<br/>(24447/24448)| `Consent.provision.dataPeriod`| _Equivalent_<br/>(39679/39680)| `Consent.provision.dataPeriod`
| | | **`Consent.except.data`**| →→→→ _Equivalent_ →→→→ <br/>(924)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1433)| `Consent.provision.data`| _Equivalent_<br/>(24449/24450)| `Consent.provision.data`| _Equivalent_<br/>(39681/39682)| `Consent.provision.data`
| | | **`Consent.except.data.id`**| | | | | | | 
| | | **`Consent.except.data.extension`**| | | | | | | 
| | | **`Consent.except.data.modifierExtension`**| | | | | | | 
| | | **`Consent.except.data.meaning`**| →→→→ _Equivalent_ →→→→ <br/>(925)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1435)| `Consent.provision.data.meaning`| _Equivalent_<br/>(24457/24458)| `Consent.provision.data.meaning`| _Equivalent_<br/>(39689/39690)| `Consent.provision.data.meaning`
| | | **`Consent.except.data.reference`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(926)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1437)| `Consent.provision.data.reference`| _Equivalent_<br/>(24459/24460)| `Consent.provision.data.reference`| _Equivalent_<br/>(39691/39692)| `Consent.provision.data.reference`
| | | *65 of 65 elements used* | | *39 of 57 elements used* <br/>remaining elements:<br/>`Consent.provision.actor.extension`, `Consent.provision.actor.id`, `Consent.provision.actor.modifierExtension`, `Consent.provision.data.extension`, `Consent.provision.data.id`, `Consent.provision.data.modifierExtension`, `Consent.provision.extension`, `Consent.provision.id`, `Consent.provision.modifierExtension`, `Consent.provision.provision`, `Consent.scope`, `Consent.verification`, `Consent.verification.extension`, `Consent.verification.id`, `Consent.verification.modifierExtension`, `Consent.verification.verificationDate`, `Consent.verification.verified`, `Consent.verification.verifiedWith`| | *39 of 57 elements used* <br/>remaining elements:<br/>`Consent.provision.actor.extension`, `Consent.provision.actor.id`, `Consent.provision.actor.modifierExtension`, `Consent.provision.data.extension`, `Consent.provision.data.id`, `Consent.provision.data.modifierExtension`, `Consent.provision.extension`, `Consent.provision.id`, `Consent.provision.modifierExtension`, `Consent.provision.provision`, `Consent.scope`, `Consent.verification`, `Consent.verification.extension`, `Consent.verification.id`, `Consent.verification.modifierExtension`, `Consent.verification.verificationDate`, `Consent.verification.verified`, `Consent.verification.verifiedWith`| | *34 of 65 elements used* <br/>remaining elements:<br/>`Consent.controller`, `Consent.decision`, `Consent.grantor`, `Consent.manager`, `Consent.period`, `Consent.policyBasis.extension`, `Consent.policyBasis.id`, `Consent.policyBasis.modifierExtension`, `Consent.policyBasis.reference`, `Consent.policyBasis.url`, `Consent.policyText`, `Consent.provision.actor.extension`, `Consent.provision.actor.id`, `Consent.provision.actor.modifierExtension`, `Consent.provision.data.extension`, `Consent.provision.data.id`, `Consent.provision.data.modifierExtension`, `Consent.provision.expression`, `Consent.provision.extension`, `Consent.provision.id`, `Consent.provision.modifierExtension`, `Consent.provision.provision`, `Consent.verification`, `Consent.verification.extension`, `Consent.verification.id`, `Consent.verification.modifierExtension`, `Consent.verification.verificationDate`, `Consent.verification.verificationType`, `Consent.verification.verified`, `Consent.verification.verifiedBy`, `Consent.verification.verifiedWith`

