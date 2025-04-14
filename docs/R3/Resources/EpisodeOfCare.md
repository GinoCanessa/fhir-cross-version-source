Comparison of 
Generated at Monday, April 14, 2025 6:17:22 PM

### EpisodeOfCare

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | EpisodeOfCare |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/EpisodeOfCare` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for EpisodeOfCare Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `520` |
| Database Snapshot Count | `32` |
| Database Differential Count | `18` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `EpisodeOfCare` | `EpisodeOfCare` | `EpisodeOfCare` | EpisodeOfCare | An association of a Patient with an Organization and  Healthcare Provider(s) for a period of time that the Organization assumes some level of responsibility | 0..* | EpisodeOfCare |  |  |
| `EpisodeOfCare.account` | `EpisodeOfCare.account` | `account` |  | The set of accounts that may be used for billing for this EpisodeOfCare | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Account) |  |  |
| `EpisodeOfCare.careManager` | `EpisodeOfCare.careManager` | `careManager` |  | Care manager/care co-ordinator for the patient | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
| `EpisodeOfCare.contained` | `EpisodeOfCare.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `EpisodeOfCare.diagnosis` | `EpisodeOfCare.diagnosis` | `diagnosis` |  | The list of diagnosis relevant to this episode of care | 0..* | BackboneElement |  |  |
| `EpisodeOfCare.diagnosis.condition` | `EpisodeOfCare.diagnosis.condition` | `condition` |  | Conditions/problems/diagnoses this episode of care is for | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Condition) |  |  |
| `EpisodeOfCare.diagnosis.extension` | `EpisodeOfCare.diagnosis.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `EpisodeOfCare.diagnosis.id` | `EpisodeOfCare.diagnosis.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `EpisodeOfCare.diagnosis.modifierExtension` | `EpisodeOfCare.diagnosis.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `EpisodeOfCare.diagnosis.rank` | `EpisodeOfCare.diagnosis.rank` | `rank` |  | Ranking of the diagnosis (for each role type) | 0..1 | positiveInt |  |  |
| `EpisodeOfCare.diagnosis.role` | `EpisodeOfCare.diagnosis.role` | `role` |  | Role that this diagnosis has within the episode of care (e.g. admission, billing, discharge …) | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/diagnosis-role` |
| `EpisodeOfCare.extension` | `EpisodeOfCare.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `EpisodeOfCare.id` | `EpisodeOfCare.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `EpisodeOfCare.identifier` | `EpisodeOfCare.identifier` | `identifier` |  | Business Identifier(s) relevant for this EpisodeOfCare | 0..* | Identifier |  |  |
| `EpisodeOfCare.implicitRules` | `EpisodeOfCare.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `EpisodeOfCare.language` | `EpisodeOfCare.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `EpisodeOfCare.managingOrganization` | `EpisodeOfCare.managingOrganization` | `managingOrganization` |  | Organization that assumes care | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `EpisodeOfCare.meta` | `EpisodeOfCare.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `EpisodeOfCare.modifierExtension` | `EpisodeOfCare.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `EpisodeOfCare.patient` | `EpisodeOfCare.patient` | `patient` |  | The patient who is the focus of this episode of care | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `EpisodeOfCare.period` | `EpisodeOfCare.period` | `period` |  | Interval during responsibility is assumed | 0..1 | Period |  |  |
| `EpisodeOfCare.referralRequest` | `EpisodeOfCare.referralRequest` | `referralRequest` |  | Originating Referral Request(s) | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/ReferralRequest) |  |  |
| `EpisodeOfCare.status` | `EpisodeOfCare.status` | `status` |  | planned \| waitlist \| active \| onhold \| finished \| cancelled \| entered-in-error | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/episode-of-care-status` |
| `EpisodeOfCare.statusHistory` | `EpisodeOfCare.statusHistory` | `statusHistory` |  | Past list of status codes (the current status may be included to cover the start date of the status) | 0..* | BackboneElement |  |  |
| `EpisodeOfCare.statusHistory.extension` | `EpisodeOfCare.statusHistory.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `EpisodeOfCare.statusHistory.id` | `EpisodeOfCare.statusHistory.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `EpisodeOfCare.statusHistory.modifierExtension` | `EpisodeOfCare.statusHistory.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `EpisodeOfCare.statusHistory.period` | `EpisodeOfCare.statusHistory.period` | `period` |  | Duration the EpisodeOfCare was in the specified status | 1..1 | Period |  |  |
| `EpisodeOfCare.statusHistory.status` | `EpisodeOfCare.statusHistory.status` | `status` |  | planned \| waitlist \| active \| onhold \| finished \| cancelled \| entered-in-error | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/episode-of-care-status` |
| `EpisodeOfCare.team` | `EpisodeOfCare.team` | `team` |  | Other practitioners facilitating this episode of care | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/CareTeam) |  |  |
| `EpisodeOfCare.text` | `EpisodeOfCare.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `EpisodeOfCare.type` | `EpisodeOfCare.type` | `type` |  | Type/class  - e.g. specialist referral, disease management | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/episodeofcare-type` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [EpisodeOfCare](/docs/R2/Resources/EpisodeOfCare.md)<br/> `http://hl7.org/fhir/StructureDefinition/EpisodeOfCare\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `109`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `275`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [EpisodeOfCare](/docs/R3/Resources/EpisodeOfCare.md)<br/> `http://hl7.org/fhir/StructureDefinition/EpisodeOfCare\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `458`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `653`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [EpisodeOfCare](/docs/R4/Resources/EpisodeOfCare.md)<br/> `http://hl7.org/fhir/StructureDefinition/EpisodeOfCare\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1481`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1482`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [EpisodeOfCare](/docs/R4B/Resources/EpisodeOfCare.md)<br/> `http://hl7.org/fhir/StructureDefinition/EpisodeOfCare\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `973`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1202`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [EpisodeOfCare](/docs/R5/Resources/EpisodeOfCare.md)<br/> `http://hl7.org/fhir/StructureDefinition/EpisodeOfCare\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition EpisodeOfCare from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 EpisodeOfCare](/docs/R2/Resources/EpisodeOfCare.md)| Relationship | R3 EpisodeOfCare| Relationship | [R4 EpisodeOfCare](/docs/R4/Resources/EpisodeOfCare.md)| Relationship | [R4B EpisodeOfCare](/docs/R4B/Resources/EpisodeOfCare.md)| Relationship | [R5 EpisodeOfCare](/docs/R5/Resources/EpisodeOfCare.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `EpisodeOfCare`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5174)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5175)| **`EpisodeOfCare`**| _Equivalent_<br/>(13682/13683)| `EpisodeOfCare`| _Equivalent_<br/>(26402/26403)| `EpisodeOfCare`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(41138)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(41139)| `EpisodeOfCare`
| `EpisodeOfCare.id`| _Equivalent_<br/>(5176/5177)| **`EpisodeOfCare.id`**| _Equivalent_<br/>(13684/13685)| `EpisodeOfCare.id`| _Equivalent_<br/>(26404/26405)| `EpisodeOfCare.id`| _Equivalent_<br/>(41140/41141)| `EpisodeOfCare.id`
| `EpisodeOfCare.meta`| _Equivalent_<br/>(5178/5179)| **`EpisodeOfCare.meta`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13686)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13687)| `EpisodeOfCare.meta`| _Equivalent_<br/>(26406/26407)| `EpisodeOfCare.meta`| _Equivalent_<br/>(41142/41143)| `EpisodeOfCare.meta`
| `EpisodeOfCare.implicitRules`| _Equivalent_<br/>(5180/5181)| **`EpisodeOfCare.implicitRules`**| _Equivalent_<br/>(13688/13689)| `EpisodeOfCare.implicitRules`| _Equivalent_<br/>(26408/26409)| `EpisodeOfCare.implicitRules`| _Equivalent_<br/>(41144/41145)| `EpisodeOfCare.implicitRules`
| `EpisodeOfCare.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5182)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(5183)| **`EpisodeOfCare.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13690)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(13691)| `EpisodeOfCare.language`| _Equivalent_<br/>(26410/26411)| `EpisodeOfCare.language`| _Equivalent_<br/>(41146/41147)| `EpisodeOfCare.language`
| `EpisodeOfCare.text`| _Equivalent_<br/>(5184/5185)| **`EpisodeOfCare.text`**| _Equivalent_<br/>(13692/13693)| `EpisodeOfCare.text`| _Equivalent_<br/>(26412/26413)| `EpisodeOfCare.text`| _Equivalent_<br/>(41148/41149)| `EpisodeOfCare.text`
| `EpisodeOfCare.contained`| _Equivalent_<br/>(5186/5187)| **`EpisodeOfCare.contained`**| _Equivalent_<br/>(13694/13695)| `EpisodeOfCare.contained`| _Equivalent_<br/>(26414/26415)| `EpisodeOfCare.contained`| _Equivalent_<br/>(41150/41151)| `EpisodeOfCare.contained`
| `EpisodeOfCare.extension`| _Equivalent_<br/>(5188/5189)| **`EpisodeOfCare.extension`**| _Equivalent_<br/>(13696/13697)| `EpisodeOfCare.extension`| _Equivalent_<br/>(26416/26417)| `EpisodeOfCare.extension`| _Equivalent_<br/>(41152/41153)| `EpisodeOfCare.extension`
| `EpisodeOfCare.modifierExtension`| _Equivalent_<br/>(5190/5191)| **`EpisodeOfCare.modifierExtension`**| _Equivalent_<br/>(13698/13699)| `EpisodeOfCare.modifierExtension`| _Equivalent_<br/>(26418/26419)| `EpisodeOfCare.modifierExtension`| _Equivalent_<br/>(41154/41155)| `EpisodeOfCare.modifierExtension`
| `EpisodeOfCare.identifier`| _Equivalent_<br/>(5192/5193)| **`EpisodeOfCare.identifier`**| _Equivalent_<br/>(13700/13701)| `EpisodeOfCare.identifier`| _Equivalent_<br/>(26420/26421)| `EpisodeOfCare.identifier`| _Equivalent_<br/>(41156/41157)| `EpisodeOfCare.identifier`
| `EpisodeOfCare.status`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5194)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5195)| **`EpisodeOfCare.status`**| _Equivalent_<br/>(13702/13703)| `EpisodeOfCare.status`| _Equivalent_<br/>(26422/26423)| `EpisodeOfCare.status`| _Equivalent_<br/>(41158/41159)| `EpisodeOfCare.status`
| `EpisodeOfCare.statusHistory`| _Equivalent_<br/>(5196/5197)| **`EpisodeOfCare.statusHistory`**| _Equivalent_<br/>(13704/13705)| `EpisodeOfCare.statusHistory`| _Equivalent_<br/>(26424/26425)| `EpisodeOfCare.statusHistory`| _Equivalent_<br/>(41160/41161)| `EpisodeOfCare.statusHistory`
| `EpisodeOfCare.statusHistory.id`| _Equivalent_<br/>(5198/5199)| **`EpisodeOfCare.statusHistory.id`**| _Equivalent_<br/>(13706/13707)| `EpisodeOfCare.statusHistory.id`| _Equivalent_<br/>(26426/26427)| `EpisodeOfCare.statusHistory.id`| _Equivalent_<br/>(41162/41163)| `EpisodeOfCare.statusHistory.id`
| `EpisodeOfCare.statusHistory.extension`| _Equivalent_<br/>(5200/5201)| **`EpisodeOfCare.statusHistory.extension`**| _Equivalent_<br/>(13708/13709)| `EpisodeOfCare.statusHistory.extension`| _Equivalent_<br/>(26428/26429)| `EpisodeOfCare.statusHistory.extension`| _Equivalent_<br/>(41164/41165)| `EpisodeOfCare.statusHistory.extension`
| `EpisodeOfCare.statusHistory.modifierExtension`| _Equivalent_<br/>(5202/5203)| **`EpisodeOfCare.statusHistory.modifierExtension`**| _Equivalent_<br/>(13710/13711)| `EpisodeOfCare.statusHistory.modifierExtension`| _Equivalent_<br/>(26430/26431)| `EpisodeOfCare.statusHistory.modifierExtension`| _Equivalent_<br/>(41166/41167)| `EpisodeOfCare.statusHistory.modifierExtension`
| `EpisodeOfCare.statusHistory.status`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5204)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5205)| **`EpisodeOfCare.statusHistory.status`**| _Equivalent_<br/>(13712/13713)| `EpisodeOfCare.statusHistory.status`| _Equivalent_<br/>(26432/26433)| `EpisodeOfCare.statusHistory.status`| _Equivalent_<br/>(41168/41169)| `EpisodeOfCare.statusHistory.status`
| `EpisodeOfCare.statusHistory.period`| _Equivalent_<br/>(5206/5207)| **`EpisodeOfCare.statusHistory.period`**| _Equivalent_<br/>(13714/13715)| `EpisodeOfCare.statusHistory.period`| _Equivalent_<br/>(26434/26435)| `EpisodeOfCare.statusHistory.period`| _Equivalent_<br/>(41170/41171)| `EpisodeOfCare.statusHistory.period`
| `EpisodeOfCare.type`| _Equivalent_<br/>(5208/5209)| **`EpisodeOfCare.type`**| _Equivalent_<br/>(13716/13717)| `EpisodeOfCare.type`| _Equivalent_<br/>(26436/26437)| `EpisodeOfCare.type`| _Equivalent_<br/>(41172/41173)| `EpisodeOfCare.type`
| | | **`EpisodeOfCare.diagnosis`**| _Equivalent_<br/>(13718/13719)| `EpisodeOfCare.diagnosis`| _Equivalent_<br/>(26438/26439)| `EpisodeOfCare.diagnosis`| _Equivalent_<br/>(41174/41175)| `EpisodeOfCare.diagnosis`
| | | **`EpisodeOfCare.diagnosis.id`**| _Equivalent_<br/>(13720/13721)| `EpisodeOfCare.diagnosis.id`| _Equivalent_<br/>(26440/26441)| `EpisodeOfCare.diagnosis.id`| _Equivalent_<br/>(41176/41177)| `EpisodeOfCare.diagnosis.id`
| | | **`EpisodeOfCare.diagnosis.extension`**| _Equivalent_<br/>(13722/13723)| `EpisodeOfCare.diagnosis.extension`| _Equivalent_<br/>(26442/26443)| `EpisodeOfCare.diagnosis.extension`| _Equivalent_<br/>(41178/41179)| `EpisodeOfCare.diagnosis.extension`
| | | **`EpisodeOfCare.diagnosis.modifierExtension`**| _Equivalent_<br/>(13724/13725)| `EpisodeOfCare.diagnosis.modifierExtension`| _Equivalent_<br/>(26444/26445)| `EpisodeOfCare.diagnosis.modifierExtension`| _Equivalent_<br/>(41180/41181)| `EpisodeOfCare.diagnosis.modifierExtension`
| `EpisodeOfCare.condition`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(231)<hr/>←←←← _RelatedTo_ ←←←← <br/>(618)| **`EpisodeOfCare.diagnosis.condition`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13726)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13727)| `EpisodeOfCare.diagnosis.condition`| _Equivalent_<br/>(26446/26447)| `EpisodeOfCare.diagnosis.condition`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(41182)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(41183)| `EpisodeOfCare.diagnosis.condition`
| | | **`EpisodeOfCare.diagnosis.role`**| _Equivalent_<br/>(13728/13729)| `EpisodeOfCare.diagnosis.role`| _Equivalent_<br/>(26448/26449)| `EpisodeOfCare.diagnosis.role`| _Equivalent_<br/>(1783/2027)| `EpisodeOfCare.diagnosis.use`
| | | **`EpisodeOfCare.diagnosis.rank`**| _Equivalent_<br/>(13730/13731)| `EpisodeOfCare.diagnosis.rank`| _Equivalent_<br/>(26450/26451)| `EpisodeOfCare.diagnosis.rank`| | | 
| `EpisodeOfCare.patient`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5210)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5211)| **`EpisodeOfCare.patient`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13732)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13733)| `EpisodeOfCare.patient`| _Equivalent_<br/>(26452/26453)| `EpisodeOfCare.patient`| _Equivalent_<br/>(41185/41186)| `EpisodeOfCare.patient`
| `EpisodeOfCare.managingOrganization`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5212)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5213)| **`EpisodeOfCare.managingOrganization`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13734)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13735)| `EpisodeOfCare.managingOrganization`| _Equivalent_<br/>(26454/26455)| `EpisodeOfCare.managingOrganization`| _Equivalent_<br/>(41187/41188)| `EpisodeOfCare.managingOrganization`
| `EpisodeOfCare.period`| _Equivalent_<br/>(5214/5215)| **`EpisodeOfCare.period`**| _Equivalent_<br/>(13736/13737)| `EpisodeOfCare.period`| _Equivalent_<br/>(26456/26457)| `EpisodeOfCare.period`| _Equivalent_<br/>(41189/41190)| `EpisodeOfCare.period`
| `EpisodeOfCare.referralRequest`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5216)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5217)| **`EpisodeOfCare.referralRequest`**| →→→→ _RelatedTo_ →→→→ <br/>(13738)<hr/>←←←← _RelatedTo_ ←←←← <br/>(13739)| `EpisodeOfCare.referralRequest`| _Equivalent_<br/>(26458/26459)| `EpisodeOfCare.referralRequest`| _Equivalent_<br/>(41191/41192)| `EpisodeOfCare.referralRequest`
| `EpisodeOfCare.careManager`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5218)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5219)| **`EpisodeOfCare.careManager`**| →→→→ _RelatedTo_ →→→→ <br/>(13740)<hr/>←←←← _RelatedTo_ ←←←← <br/>(13741)| `EpisodeOfCare.careManager`| _Equivalent_<br/>(26460/26461)| `EpisodeOfCare.careManager`| _Equivalent_<br/>(41193/41194)| `EpisodeOfCare.careManager`
| `EpisodeOfCare`| →→→→ _Equivalent_ →→→→ <br/>(13680)<hr/>←←←← __ ←←←← <br/>()| **`EpisodeOfCare.team`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13742)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13743)| `EpisodeOfCare.team`| _Equivalent_<br/>(26462/26463)| `EpisodeOfCare.team`| _Equivalent_<br/>(1784/2028)| `EpisodeOfCare.careTeam`
| `EpisodeOfCare.careTeam`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(227)<hr/>←←←← __ ←←←← <br/>()| **`EpisodeOfCare.team`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13742)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13743)| `EpisodeOfCare.team`| _Equivalent_<br/>(26462/26463)| `EpisodeOfCare.team`| _Equivalent_<br/>(1784/2028)| `EpisodeOfCare.careTeam`
| | | **`EpisodeOfCare.account`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13744)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13745)| `EpisodeOfCare.account`| _Equivalent_<br/>(26464/26465)| `EpisodeOfCare.account`| _Equivalent_<br/>(41195/41196)| `EpisodeOfCare.account`
| *25 of 31 elements used* <br/>remaining elements:<br/>`EpisodeOfCare.careTeam.extension`, `EpisodeOfCare.careTeam.id`, `EpisodeOfCare.careTeam.member`, `EpisodeOfCare.careTeam.modifierExtension`, `EpisodeOfCare.careTeam.period`, `EpisodeOfCare.careTeam.role`| | *32 of 32 elements used* | | *32 of 32 elements used* | | *32 of 32 elements used* | | *31 of 37 elements used* <br/>remaining elements:<br/>`EpisodeOfCare.reason`, `EpisodeOfCare.reason.extension`, `EpisodeOfCare.reason.id`, `EpisodeOfCare.reason.modifierExtension`, `EpisodeOfCare.reason.use`, `EpisodeOfCare.reason.value`

