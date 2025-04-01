Comparison of 
Generated at Tuesday, April 1, 2025 1:39:28 PM

### EnrollmentResponse

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| Stucture Name | EnrollmentResponse |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/EnrollmentResponse` |
| Version | 4.3.0 |
| Description | This resource provides enrollment and plan details from the processing of an EnrollmentRequest resource. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1687` |
| Database Snapshot Count | `17` |
| Database Differential Count | `9` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `EnrollmentResponse` | `EnrollmentResponse` | `EnrollmentResponse` | EnrollmentResponse | EnrollmentResponse resource | 0..* | EnrollmentResponse |  |  |
| `EnrollmentResponse.contained` | `EnrollmentResponse.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `EnrollmentResponse.created` | `EnrollmentResponse.created` | `created` | EnrollmentResponse.created | Creation date | 0..1 | dateTime |  |  |
| `EnrollmentResponse.disposition` | `EnrollmentResponse.disposition` | `disposition` | EnrollmentResponse.disposition | Disposition Message | 0..1 | string |  |  |
| `EnrollmentResponse.extension` | `EnrollmentResponse.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `EnrollmentResponse.id` | `EnrollmentResponse.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `EnrollmentResponse.identifier` | `EnrollmentResponse.identifier` | `identifier` | EnrollmentResponse.identifier | Business Identifier | 0..* | Identifier |  |  |
| `EnrollmentResponse.implicitRules` | `EnrollmentResponse.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `EnrollmentResponse.language` | `EnrollmentResponse.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `EnrollmentResponse.meta` | `EnrollmentResponse.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `EnrollmentResponse.modifierExtension` | `EnrollmentResponse.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `EnrollmentResponse.organization` | `EnrollmentResponse.organization` | `organization` | EnrollmentResponse.organization | Insurer | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `EnrollmentResponse.outcome` | `EnrollmentResponse.outcome` | `outcome` | EnrollmentResponse.outcome | queued \| complete \| error \| partial | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/remittance-outcome|4.3.0` |
| `EnrollmentResponse.request` | `EnrollmentResponse.request` | `request` | EnrollmentResponse.request | Claim reference | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/EnrollmentRequest) |  |  |
| `EnrollmentResponse.requestProvider` | `EnrollmentResponse.requestProvider` | `requestProvider` | EnrollmentResponse.requestProvider | Responsible practitioner | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole) |  |  |
| `EnrollmentResponse.status` | `EnrollmentResponse.status` | `status` | EnrollmentResponse.status | active \| cancelled \| draft \| entered-in-error | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/fm-status|4.3.0` |
| `EnrollmentResponse.text` | `EnrollmentResponse.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [EnrollmentResponse](/docs/R2/Resources/EnrollmentResponse.md)<br/> `http://hl7.org/fhir/StructureDefinition/EnrollmentResponse\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `108`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `274`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EnrollmentResponse](/docs/R3/Resources/EnrollmentResponse.md)<br/> `http://hl7.org/fhir/StructureDefinition/EnrollmentResponse\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `457`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`RelatedTo`<br/>- DBKey: `652`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EnrollmentResponse](/docs/R4/Resources/EnrollmentResponse.md)<br/> `http://hl7.org/fhir/StructureDefinition/EnrollmentResponse\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1479`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1480`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EnrollmentResponse](/docs/R4B/Resources/EnrollmentResponse.md)<br/> `http://hl7.org/fhir/StructureDefinition/EnrollmentResponse\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `972`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1201`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EnrollmentResponse](/docs/R5/Resources/EnrollmentResponse.md)<br/> `http://hl7.org/fhir/StructureDefinition/EnrollmentResponse\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition EnrollmentResponse from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 EnrollmentResponse](/docs/R2/Resources/EnrollmentResponse.md)| Relationship | [R3 EnrollmentResponse](/docs/R3/Resources/EnrollmentResponse.md)| Relationship | [R4 EnrollmentResponse](/docs/R4/Resources/EnrollmentResponse.md)| Relationship | R4B EnrollmentResponse| Relationship | [R5 EnrollmentResponse](/docs/R5/Resources/EnrollmentResponse.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `EnrollmentResponse`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(5140)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(5141)| `EnrollmentResponse`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(13640)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(13641)| `EnrollmentResponse`| _Equivalent_<br/>(26368/26369)| **`EnrollmentResponse`**| _Equivalent_<br/>(41104/41105)| `EnrollmentResponse`
| `EnrollmentResponse.id`| _Equivalent_<br/>(5142/5143)| `EnrollmentResponse.id`| _Equivalent_<br/>(13642/13643)| `EnrollmentResponse.id`| _Equivalent_<br/>(26370/26371)| **`EnrollmentResponse.id`**| _Equivalent_<br/>(41106/41107)| `EnrollmentResponse.id`
| `EnrollmentResponse.meta`| _Equivalent_<br/>(5144/5145)| `EnrollmentResponse.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13644)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13645)| `EnrollmentResponse.meta`| _Equivalent_<br/>(26372/26373)| **`EnrollmentResponse.meta`**| _Equivalent_<br/>(41108/41109)| `EnrollmentResponse.meta`
| `EnrollmentResponse.implicitRules`| _Equivalent_<br/>(5146/5147)| `EnrollmentResponse.implicitRules`| _Equivalent_<br/>(13646/13647)| `EnrollmentResponse.implicitRules`| _Equivalent_<br/>(26374/26375)| **`EnrollmentResponse.implicitRules`**| _Equivalent_<br/>(41110/41111)| `EnrollmentResponse.implicitRules`
| `EnrollmentResponse.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5148)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(5149)| `EnrollmentResponse.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13648)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(13649)| `EnrollmentResponse.language`| _Equivalent_<br/>(26376/26377)| **`EnrollmentResponse.language`**| _Equivalent_<br/>(41112/41113)| `EnrollmentResponse.language`
| `EnrollmentResponse.text`| _Equivalent_<br/>(5150/5151)| `EnrollmentResponse.text`| _Equivalent_<br/>(13650/13651)| `EnrollmentResponse.text`| _Equivalent_<br/>(26378/26379)| **`EnrollmentResponse.text`**| _Equivalent_<br/>(41114/41115)| `EnrollmentResponse.text`
| `EnrollmentResponse.contained`| _Equivalent_<br/>(5152/5153)| `EnrollmentResponse.contained`| _Equivalent_<br/>(13652/13653)| `EnrollmentResponse.contained`| _Equivalent_<br/>(26380/26381)| **`EnrollmentResponse.contained`**| _Equivalent_<br/>(41116/41117)| `EnrollmentResponse.contained`
| `EnrollmentResponse.extension`| _Equivalent_<br/>(5154/5155)| `EnrollmentResponse.extension`| _Equivalent_<br/>(13654/13655)| `EnrollmentResponse.extension`| _Equivalent_<br/>(26382/26383)| **`EnrollmentResponse.extension`**| _Equivalent_<br/>(41118/41119)| `EnrollmentResponse.extension`
| `EnrollmentResponse.modifierExtension`| _Equivalent_<br/>(5156/5157)| `EnrollmentResponse.modifierExtension`| _Equivalent_<br/>(13656/13657)| `EnrollmentResponse.modifierExtension`| _Equivalent_<br/>(26384/26385)| **`EnrollmentResponse.modifierExtension`**| _Equivalent_<br/>(41120/41121)| `EnrollmentResponse.modifierExtension`
| `EnrollmentResponse.identifier`| _Equivalent_<br/>(5158/5159)| `EnrollmentResponse.identifier`| _Equivalent_<br/>(13658/13659)| `EnrollmentResponse.identifier`| _Equivalent_<br/>(26386/26387)| **`EnrollmentResponse.identifier`**| _Equivalent_<br/>(41122/41123)| `EnrollmentResponse.identifier`
| | | `EnrollmentResponse.status`| _Equivalent_<br/>(13660/13661)| `EnrollmentResponse.status`| _Equivalent_<br/>(26388/26389)| **`EnrollmentResponse.status`**| _Equivalent_<br/>(41124/41125)| `EnrollmentResponse.status`
| `EnrollmentResponse.request`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5160)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5161)| `EnrollmentResponse.request`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13662)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13663)| `EnrollmentResponse.request`| _Equivalent_<br/>(26390/26391)| **`EnrollmentResponse.request`**| _Equivalent_<br/>(41126/41127)| `EnrollmentResponse.request`
| `EnrollmentResponse.outcome`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5162)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5163)| `EnrollmentResponse.outcome`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13664)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13665)| `EnrollmentResponse.outcome`| _Equivalent_<br/>(26392/26393)| **`EnrollmentResponse.outcome`**| _Equivalent_<br/>(41128/41129)| `EnrollmentResponse.outcome`
| `EnrollmentResponse.disposition`| _Equivalent_<br/>(5164/5165)| `EnrollmentResponse.disposition`| _Equivalent_<br/>(13666/13667)| `EnrollmentResponse.disposition`| _Equivalent_<br/>(26394/26395)| **`EnrollmentResponse.disposition`**| _Equivalent_<br/>(41130/41131)| `EnrollmentResponse.disposition`
| `EnrollmentResponse.created`| _Equivalent_<br/>(5166/5167)| `EnrollmentResponse.created`| _Equivalent_<br/>(13668/13669)| `EnrollmentResponse.created`| _Equivalent_<br/>(26396/26397)| **`EnrollmentResponse.created`**| _Equivalent_<br/>(41132/41133)| `EnrollmentResponse.created`
| `EnrollmentResponse.organization`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5168)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5169)| `EnrollmentResponse.organization`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13670)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13671)| `EnrollmentResponse.organization`| _Equivalent_<br/>(26398/26399)| **`EnrollmentResponse.organization`**| _Equivalent_<br/>(41134/41135)| `EnrollmentResponse.organization`
| `EnrollmentResponse.requestProvider`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5170)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5171)| `EnrollmentResponse.requestProvider`| →→→→ _RelatedTo_ →→→→ <br/>(13672)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1503)| `EnrollmentResponse.requestProvider`| _Equivalent_<br/>(26400/26401)| **`EnrollmentResponse.requestProvider`**| _Equivalent_<br/>(41136/41137)| `EnrollmentResponse.requestProvider`
| `EnrollmentResponse.requestOrganization`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5172)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5173)| `EnrollmentResponse.requestOrganization`| →→→→ _RelatedTo_ →→→→ <br/>(1043)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1503)| `EnrollmentResponse.requestProvider`| _Equivalent_<br/>(26400/26401)| **`EnrollmentResponse.requestProvider`**| _Equivalent_<br/>(41136/41137)| `EnrollmentResponse.requestProvider`
| *17 of 19 elements used* | | *18 of 18 elements used* | | *17 of 17 elements used* | | *17 of 17 elements used* | | *17 of 17 elements used* 

