Comparison of 
Generated at Tuesday, April 1, 2025 1:39:14 PM

### CareTeam

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | CareTeam |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/CareTeam` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for CareTeam Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `488` |
| Database Snapshot Count | `28` |
| Database Differential Count | `17` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `CareTeam` | `CareTeam` | `CareTeam` | CareTeam | Planned participants in the coordination and delivery of care for a patient or group | 0..* | CareTeam |  |  |
| `CareTeam.category` | `CareTeam.category` | `category` |  | Type of team | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/care-team-category` |
| `CareTeam.contained` | `CareTeam.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `CareTeam.context` | `CareTeam.context` | `context` |  | Encounter or episode associated with CareTeam | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Encounter), Reference(http://hl7.org/fhir/StructureDefinition/EpisodeOfCare) |  |  |
| `CareTeam.extension` | `CareTeam.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `CareTeam.id` | `CareTeam.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `CareTeam.identifier` | `CareTeam.identifier` | `identifier` |  | External Ids for this team | 0..* | Identifier |  |  |
| `CareTeam.implicitRules` | `CareTeam.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `CareTeam.language` | `CareTeam.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `CareTeam.managingOrganization` | `CareTeam.managingOrganization` | `managingOrganization` |  | Organization responsible for the care team | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `CareTeam.meta` | `CareTeam.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `CareTeam.modifierExtension` | `CareTeam.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `CareTeam.name` | `CareTeam.name` | `name` |  | Name of the team, such as crisis assessment team | 0..1 | string |  |  |
| `CareTeam.note` | `CareTeam.note` | `note` |  | Comments made about the CareTeam | 0..* | Annotation |  |  |
| `CareTeam.participant` | `CareTeam.participant` | `participant` |  | Members of the team | 0..* | BackboneElement |  |  |
| `CareTeam.participant.extension` | `CareTeam.participant.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `CareTeam.participant.id` | `CareTeam.participant.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `CareTeam.participant.member` | `CareTeam.participant.member` | `member` |  | Who is involved | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/CareTeam), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `CareTeam.participant.modifierExtension` | `CareTeam.participant.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `CareTeam.participant.onBehalfOf` | `CareTeam.participant.onBehalfOf` | `onBehalfOf` |  | Organization of the practitioner | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `CareTeam.participant.period` | `CareTeam.participant.period` | `period` |  | Time period of participant | 0..1 | Period |  |  |
| `CareTeam.participant.role` | `CareTeam.participant.role` | `role` |  | Type of involvement | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/participant-role` |
| `CareTeam.period` | `CareTeam.period` | `period` |  | Time period team covers | 0..1 | Period |  |  |
| `CareTeam.reasonCode` | `CareTeam.reasonCode` | `reasonCode` |  | Why the care team exists | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/clinical-findings` |
| `CareTeam.reasonReference` | `CareTeam.reasonReference` | `reasonReference` |  | Why the care team exists | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Condition) |  |  |
| `CareTeam.status` | `CareTeam.status` | `status` |  | proposed \| active \| suspended \| inactive \| entered-in-error | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/care-team-status` |
| `CareTeam.subject` | `CareTeam.subject` | `subject` |  | Who care team is for | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `CareTeam.text` | `CareTeam.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [CareTeam](/docs/R3/Resources/CareTeam.md)<br/> `http://hl7.org/fhir/StructureDefinition/CareTeam\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `428`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `624`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CareTeam](/docs/R4/Resources/CareTeam.md)<br/> `http://hl7.org/fhir/StructureDefinition/CareTeam\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1415`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1416`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CareTeam](/docs/R4B/Resources/CareTeam.md)<br/> `http://hl7.org/fhir/StructureDefinition/CareTeam\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `941`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1170`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CareTeam](/docs/R5/Resources/CareTeam.md)<br/> `http://hl7.org/fhir/StructureDefinition/CareTeam\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition CareTeam from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | R3 CareTeam| Relationship | [R4 CareTeam](/docs/R4/Resources/CareTeam.md)| Relationship | [R4B CareTeam](/docs/R4B/Resources/CareTeam.md)| Relationship | [R5 CareTeam](/docs/R5/Resources/CareTeam.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | **`CareTeam`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11065)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11066)| `CareTeam`| _Equivalent_<br/>(22651/22652)| `CareTeam`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(37640)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(37641)| `CareTeam`
| | | **`CareTeam.id`**| _Equivalent_<br/>(11067/11068)| `CareTeam.id`| _Equivalent_<br/>(22653/22654)| `CareTeam.id`| _Equivalent_<br/>(37642/37643)| `CareTeam.id`
| | | **`CareTeam.meta`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11069)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11070)| `CareTeam.meta`| _Equivalent_<br/>(22655/22656)| `CareTeam.meta`| _Equivalent_<br/>(37644/37645)| `CareTeam.meta`
| | | **`CareTeam.implicitRules`**| _Equivalent_<br/>(11071/11072)| `CareTeam.implicitRules`| _Equivalent_<br/>(22657/22658)| `CareTeam.implicitRules`| _Equivalent_<br/>(37646/37647)| `CareTeam.implicitRules`
| | | **`CareTeam.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11073)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11074)| `CareTeam.language`| _Equivalent_<br/>(22659/22660)| `CareTeam.language`| _Equivalent_<br/>(37648/37649)| `CareTeam.language`
| | | **`CareTeam.text`**| _Equivalent_<br/>(11075/11076)| `CareTeam.text`| _Equivalent_<br/>(22661/22662)| `CareTeam.text`| _Equivalent_<br/>(37650/37651)| `CareTeam.text`
| | | **`CareTeam.contained`**| _Equivalent_<br/>(11077/11078)| `CareTeam.contained`| _Equivalent_<br/>(22663/22664)| `CareTeam.contained`| _Equivalent_<br/>(37652/37653)| `CareTeam.contained`
| | | **`CareTeam.extension`**| _Equivalent_<br/>(11079/11080)| `CareTeam.extension`| _Equivalent_<br/>(22665/22666)| `CareTeam.extension`| _Equivalent_<br/>(37654/37655)| `CareTeam.extension`
| | | **`CareTeam.modifierExtension`**| _Equivalent_<br/>(11081/11082)| `CareTeam.modifierExtension`| _Equivalent_<br/>(22667/22668)| `CareTeam.modifierExtension`| _Equivalent_<br/>(37656/37657)| `CareTeam.modifierExtension`
| | | **`CareTeam.identifier`**| _Equivalent_<br/>(11083/11084)| `CareTeam.identifier`| _Equivalent_<br/>(22669/22670)| `CareTeam.identifier`| _Equivalent_<br/>(37658/37659)| `CareTeam.identifier`
| | | **`CareTeam.status`**| _Equivalent_<br/>(11085/11086)| `CareTeam.status`| _Equivalent_<br/>(22671/22672)| `CareTeam.status`| _Equivalent_<br/>(37660/37661)| `CareTeam.status`
| | | **`CareTeam.category`**| _Equivalent_<br/>(11087/11088)| `CareTeam.category`| _Equivalent_<br/>(22673/22674)| `CareTeam.category`| _Equivalent_<br/>(37662/37663)| `CareTeam.category`
| | | **`CareTeam.name`**| _Equivalent_<br/>(11089/11090)| `CareTeam.name`| _Equivalent_<br/>(22675/22676)| `CareTeam.name`| _Equivalent_<br/>(37664/37665)| `CareTeam.name`
| | | **`CareTeam.subject`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11091)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11092)| `CareTeam.subject`| _Equivalent_<br/>(22677/22678)| `CareTeam.subject`| _Equivalent_<br/>(37666/37667)| `CareTeam.subject`
| | | **`CareTeam.context`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(844)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1371)| `CareTeam.encounter`| _Equivalent_<br/>(22679/22680)| `CareTeam.encounter`| | | 
| | | **`CareTeam.period`**| _Equivalent_<br/>(11093/11094)| `CareTeam.period`| _Equivalent_<br/>(22681/22682)| `CareTeam.period`| _Equivalent_<br/>(37669/37670)| `CareTeam.period`
| | | **`CareTeam.participant`**| _Equivalent_<br/>(11095/11096)| `CareTeam.participant`| _Equivalent_<br/>(22683/22684)| `CareTeam.participant`| _Equivalent_<br/>(37671/37672)| `CareTeam.participant`
| | | **`CareTeam.participant.id`**| _Equivalent_<br/>(11097/11098)| `CareTeam.participant.id`| _Equivalent_<br/>(22685/22686)| `CareTeam.participant.id`| _Equivalent_<br/>(37673/37674)| `CareTeam.participant.id`
| | | **`CareTeam.participant.extension`**| _Equivalent_<br/>(11099/11100)| `CareTeam.participant.extension`| _Equivalent_<br/>(22687/22688)| `CareTeam.participant.extension`| _Equivalent_<br/>(37675/37676)| `CareTeam.participant.extension`
| | | **`CareTeam.participant.modifierExtension`**| _Equivalent_<br/>(11101/11102)| `CareTeam.participant.modifierExtension`| _Equivalent_<br/>(22689/22690)| `CareTeam.participant.modifierExtension`| _Equivalent_<br/>(37677/37678)| `CareTeam.participant.modifierExtension`
| | | **`CareTeam.participant.role`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11103)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11104)| `CareTeam.participant.role`| _Equivalent_<br/>(22691/22692)| `CareTeam.participant.role`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(37679)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(37680)| `CareTeam.participant.role`
| | | **`CareTeam.participant.member`**| →→→→ _RelatedTo_ →→→→ <br/>(11105)<hr/>←←←← _RelatedTo_ ←←←← <br/>(11106)| `CareTeam.participant.member`| _Equivalent_<br/>(22693/22694)| `CareTeam.participant.member`| _Equivalent_<br/>(37681/37682)| `CareTeam.participant.member`
| | | **`CareTeam.participant.onBehalfOf`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11107)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11108)| `CareTeam.participant.onBehalfOf`| _Equivalent_<br/>(22695/22696)| `CareTeam.participant.onBehalfOf`| _Equivalent_<br/>(37683/37684)| `CareTeam.participant.onBehalfOf`
| | | **`CareTeam.participant.period`**| _Equivalent_<br/>(11109/11110)| `CareTeam.participant.period`| _Equivalent_<br/>(22697/22698)| `CareTeam.participant.period`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1854)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2097)| `CareTeam.participant.coverage[x]`
| | | **`CareTeam.reasonCode`**| _Equivalent_<br/>(11111/11112)| `CareTeam.reasonCode`| _Equivalent_<br/>(22699/22700)| `CareTeam.reasonCode`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1855)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2098)| `CareTeam.reason`
| | | **`CareTeam.reasonReference`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11113)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11114)| `CareTeam.reasonReference`| _Equivalent_<br/>(22701/22702)| `CareTeam.reasonReference`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1856)<hr/>←←←← _RelatedTo_ ←←←← <br/>(2099)| `CareTeam.reason`
| | | **`CareTeam.managingOrganization`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11115)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11116)| `CareTeam.managingOrganization`| _Equivalent_<br/>(22703/22704)| `CareTeam.managingOrganization`| _Equivalent_<br/>(37685/37686)| `CareTeam.managingOrganization`
| | | **`CareTeam.note`**| _Equivalent_<br/>(11117/11118)| `CareTeam.note`| _Equivalent_<br/>(22707/22708)| `CareTeam.note`| _Equivalent_<br/>(37689/37690)| `CareTeam.note`
| | | *28 of 28 elements used* | | *28 of 29 elements used* | | *28 of 29 elements used* | | *26 of 27 elements used* 

