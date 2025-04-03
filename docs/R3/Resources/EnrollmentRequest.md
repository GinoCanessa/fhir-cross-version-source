Comparison of 
Generated at Thursday, April 3, 2025 8:18:12 AM

### EnrollmentRequest

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | EnrollmentRequest |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/EnrollmentRequest` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for EnrollmentRequest Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `518` |
| Database Snapshot Count | `17` |
| Database Differential Count | `9` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `EnrollmentRequest` | `EnrollmentRequest` | `EnrollmentRequest` | EnrollmentRequest | Enrollment request | 0..* | EnrollmentRequest |  |  |
| `EnrollmentRequest.contained` | `EnrollmentRequest.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `EnrollmentRequest.coverage` | `EnrollmentRequest.coverage` | `coverage` |  | Insurance information | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Coverage) |  |  |
| `EnrollmentRequest.created` | `EnrollmentRequest.created` | `created` |  | Creation date | 0..1 | dateTime |  |  |
| `EnrollmentRequest.extension` | `EnrollmentRequest.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `EnrollmentRequest.id` | `EnrollmentRequest.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `EnrollmentRequest.identifier` | `EnrollmentRequest.identifier` | `identifier` |  | Business Identifier | 0..* | Identifier |  |  |
| `EnrollmentRequest.implicitRules` | `EnrollmentRequest.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `EnrollmentRequest.insurer` | `EnrollmentRequest.insurer` | `insurer` |  | Target | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `EnrollmentRequest.language` | `EnrollmentRequest.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `EnrollmentRequest.meta` | `EnrollmentRequest.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `EnrollmentRequest.modifierExtension` | `EnrollmentRequest.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `EnrollmentRequest.organization` | `EnrollmentRequest.organization` | `organization` |  | Responsible organization | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `EnrollmentRequest.provider` | `EnrollmentRequest.provider` | `provider` |  | Responsible practitioner | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
| `EnrollmentRequest.status` | `EnrollmentRequest.status` | `status` |  | active \| cancelled \| draft \| entered-in-error | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/fm-status` |
| `EnrollmentRequest.subject` | `EnrollmentRequest.subject` | `subject` |  | The subject of the Products and Services | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `EnrollmentRequest.text` | `EnrollmentRequest.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [EnrollmentRequest](/docs/R2/Resources/EnrollmentRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/EnrollmentRequest\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `107`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `273`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EnrollmentRequest](/docs/R3/Resources/EnrollmentRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/EnrollmentRequest\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `456`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`RelatedTo`<br/>- DBKey: `651`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EnrollmentRequest](/docs/R4/Resources/EnrollmentRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/EnrollmentRequest\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1477`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1478`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EnrollmentRequest](/docs/R4B/Resources/EnrollmentRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/EnrollmentRequest\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `971`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1200`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EnrollmentRequest](/docs/R5/Resources/EnrollmentRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/EnrollmentRequest\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition EnrollmentRequest from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 EnrollmentRequest](/docs/R2/Resources/EnrollmentRequest.md)| Relationship | R3 EnrollmentRequest| Relationship | [R4 EnrollmentRequest](/docs/R4/Resources/EnrollmentRequest.md)| Relationship | [R4B EnrollmentRequest](/docs/R4B/Resources/EnrollmentRequest.md)| Relationship | [R5 EnrollmentRequest](/docs/R5/Resources/EnrollmentRequest.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `EnrollmentRequest`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(5110)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(5111)| **`EnrollmentRequest`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(13609)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(13610)| `EnrollmentRequest`| _Equivalent_<br/>(26336/26337)| `EnrollmentRequest`| _Equivalent_<br/>(41072/41073)| `EnrollmentRequest`
| `EnrollmentRequest.id`| _Equivalent_<br/>(5112/5113)| **`EnrollmentRequest.id`**| _Equivalent_<br/>(13611/13612)| `EnrollmentRequest.id`| _Equivalent_<br/>(26338/26339)| `EnrollmentRequest.id`| _Equivalent_<br/>(41074/41075)| `EnrollmentRequest.id`
| `EnrollmentRequest.meta`| _Equivalent_<br/>(5114/5115)| **`EnrollmentRequest.meta`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13613)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13614)| `EnrollmentRequest.meta`| _Equivalent_<br/>(26340/26341)| `EnrollmentRequest.meta`| _Equivalent_<br/>(41076/41077)| `EnrollmentRequest.meta`
| `EnrollmentRequest.implicitRules`| _Equivalent_<br/>(5116/5117)| **`EnrollmentRequest.implicitRules`**| _Equivalent_<br/>(13615/13616)| `EnrollmentRequest.implicitRules`| _Equivalent_<br/>(26342/26343)| `EnrollmentRequest.implicitRules`| _Equivalent_<br/>(41078/41079)| `EnrollmentRequest.implicitRules`
| `EnrollmentRequest.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5118)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(5119)| **`EnrollmentRequest.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13617)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(13618)| `EnrollmentRequest.language`| _Equivalent_<br/>(26344/26345)| `EnrollmentRequest.language`| _Equivalent_<br/>(41080/41081)| `EnrollmentRequest.language`
| `EnrollmentRequest.text`| _Equivalent_<br/>(5120/5121)| **`EnrollmentRequest.text`**| _Equivalent_<br/>(13619/13620)| `EnrollmentRequest.text`| _Equivalent_<br/>(26346/26347)| `EnrollmentRequest.text`| _Equivalent_<br/>(41082/41083)| `EnrollmentRequest.text`
| `EnrollmentRequest.contained`| _Equivalent_<br/>(5122/5123)| **`EnrollmentRequest.contained`**| _Equivalent_<br/>(13621/13622)| `EnrollmentRequest.contained`| _Equivalent_<br/>(26348/26349)| `EnrollmentRequest.contained`| _Equivalent_<br/>(41084/41085)| `EnrollmentRequest.contained`
| `EnrollmentRequest.extension`| _Equivalent_<br/>(5124/5125)| **`EnrollmentRequest.extension`**| _Equivalent_<br/>(13623/13624)| `EnrollmentRequest.extension`| _Equivalent_<br/>(26350/26351)| `EnrollmentRequest.extension`| _Equivalent_<br/>(41086/41087)| `EnrollmentRequest.extension`
| `EnrollmentRequest.modifierExtension`| _Equivalent_<br/>(5126/5127)| **`EnrollmentRequest.modifierExtension`**| _Equivalent_<br/>(13625/13626)| `EnrollmentRequest.modifierExtension`| _Equivalent_<br/>(26352/26353)| `EnrollmentRequest.modifierExtension`| _Equivalent_<br/>(41088/41089)| `EnrollmentRequest.modifierExtension`
| `EnrollmentRequest.identifier`| _Equivalent_<br/>(5128/5129)| **`EnrollmentRequest.identifier`**| _Equivalent_<br/>(13627/13628)| `EnrollmentRequest.identifier`| _Equivalent_<br/>(26354/26355)| `EnrollmentRequest.identifier`| _Equivalent_<br/>(41090/41091)| `EnrollmentRequest.identifier`
| | | **`EnrollmentRequest.status`**| _Equivalent_<br/>(13629/13630)| `EnrollmentRequest.status`| _Equivalent_<br/>(26356/26357)| `EnrollmentRequest.status`| _Equivalent_<br/>(41092/41093)| `EnrollmentRequest.status`
| `EnrollmentRequest.created`| _Equivalent_<br/>(5130/5131)| **`EnrollmentRequest.created`**| _Equivalent_<br/>(13631/13632)| `EnrollmentRequest.created`| _Equivalent_<br/>(26358/26359)| `EnrollmentRequest.created`| _Equivalent_<br/>(41094/41095)| `EnrollmentRequest.created`
| `EnrollmentRequest.target`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(224)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(617)| **`EnrollmentRequest.insurer`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13633)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13634)| `EnrollmentRequest.insurer`| _Equivalent_<br/>(26360/26361)| `EnrollmentRequest.insurer`| _Equivalent_<br/>(41096/41097)| `EnrollmentRequest.insurer`
| `EnrollmentRequest.provider`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5132)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5133)| **`EnrollmentRequest.provider`**| →→→→ _RelatedTo_ →→→→ <br/>(13635)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13636)| `EnrollmentRequest.provider`| _Equivalent_<br/>(26362/26363)| `EnrollmentRequest.provider`| _Equivalent_<br/>(41098/41099)| `EnrollmentRequest.provider`
| `EnrollmentRequest.organization`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5134)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5135)| **`EnrollmentRequest.organization`**| →→→→ _RelatedTo_ →→→→ <br/>(1041)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1502)| `EnrollmentRequest.provider`| _Equivalent_<br/>(26362/26363)| `EnrollmentRequest.provider`| _Equivalent_<br/>(41098/41099)| `EnrollmentRequest.provider`
| `EnrollmentRequest.subject`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5136)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(5137)| **`EnrollmentRequest.subject`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1042)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1501)| `EnrollmentRequest.candidate`| _Equivalent_<br/>(26364/26365)| `EnrollmentRequest.candidate`| _Equivalent_<br/>(41100/41101)| `EnrollmentRequest.candidate`
| `EnrollmentRequest.coverage`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5138)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(5139)| **`EnrollmentRequest.coverage`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13637)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13638)| `EnrollmentRequest.coverage`| _Equivalent_<br/>(26366/26367)| `EnrollmentRequest.coverage`| _Equivalent_<br/>(41102/41103)| `EnrollmentRequest.coverage`
| *16 of 19 elements used* <br/>remaining elements:<br/>`EnrollmentRequest.originalRuleset`, `EnrollmentRequest.relationship`, `EnrollmentRequest.ruleset`| | *17 of 17 elements used* | | *16 of 16 elements used* | | *16 of 16 elements used* | | *16 of 16 elements used* 

