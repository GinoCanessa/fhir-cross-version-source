Comparison of 
Generated at Friday, April 4, 2025 2:58:38 PM

### Person

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | Person |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Person` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for Person Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `559` |
| Database Snapshot Count | `24` |
| Database Differential Count | `13` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Person` | `Person` | `Person` | Person | A generic person record | 0..* | Person |  |  |
| `Person.active` | `Person.active` | `active` |  | This person's record is in active use | 0..1 | boolean |  |  |
| `Person.address` | `Person.address` | `address` |  | One or more addresses for the person | 0..* | Address |  |  |
| `Person.birthDate` | `Person.birthDate` | `birthDate` |  | The date on which the person was born | 0..1 | date |  |  |
| `Person.contained` | `Person.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Person.extension` | `Person.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Person.gender` | `Person.gender` | `gender` |  | male \| female \| other \| unknown | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/administrative-gender` |
| `Person.id` | `Person.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Person.identifier` | `Person.identifier` | `identifier` |  | A human identifier for this person | 0..* | Identifier |  |  |
| `Person.implicitRules` | `Person.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Person.language` | `Person.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `Person.link` | `Person.link` | `link` |  | Link to a resource that concerns the same actual person | 0..* | BackboneElement |  |  |
| `Person.link.assurance` | `Person.link.assurance` | `assurance` |  | level1 \| level2 \| level3 \| level4 | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/identity-assuranceLevel` |
| `Person.link.extension` | `Person.link.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Person.link.id` | `Person.link.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Person.link.modifierExtension` | `Person.link.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Person.link.target` | `Person.link.target` | `target` |  | The resource to which this actual person is associated | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Person), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `Person.managingOrganization` | `Person.managingOrganization` | `managingOrganization` |  | The organization that is the custodian of the person record | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `Person.meta` | `Person.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Person.modifierExtension` | `Person.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Person.name` | `Person.name` | `name` |  | A name associated with the person | 0..* | HumanName |  |  |
| `Person.photo` | `Person.photo` | `photo` |  | Image of the person | 0..1 | Attachment |  |  |
| `Person.telecom` | `Person.telecom` | `telecom` |  | A contact detail for the person | 0..* | ContactPoint |  |  |
| `Person.text` | `Person.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Person](/docs/R2/Resources/Person.md)<br/> `http://hl7.org/fhir/StructureDefinition/Person\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `142`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `308`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Person](/docs/R3/Resources/Person.md)<br/> `http://hl7.org/fhir/StructureDefinition/Person\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `497`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `692`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Person](/docs/R4/Resources/Person.md)<br/> `http://hl7.org/fhir/StructureDefinition/Person\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1577`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1578`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Person](/docs/R4B/Resources/Person.md)<br/> `http://hl7.org/fhir/StructureDefinition/Person\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1024`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1253`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Person](/docs/R5/Resources/Person.md)<br/> `http://hl7.org/fhir/StructureDefinition/Person\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Person from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Person](/docs/R2/Resources/Person.md)| Relationship | R3 Person| Relationship | [R4 Person](/docs/R4/Resources/Person.md)| Relationship | [R4B Person](/docs/R4B/Resources/Person.md)| Relationship | [R5 Person](/docs/R5/Resources/Person.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `Person`| _Equivalent_<br/>(7137/7138)| **`Person`**| _Equivalent_<br/>(16989/16990)| `Person`| _Equivalent_<br/>(31503/31504)| `Person`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(46133)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(46134)| `Person`
| `Person.id`| _Equivalent_<br/>(7139/7140)| **`Person.id`**| _Equivalent_<br/>(16991/16992)| `Person.id`| _Equivalent_<br/>(31505/31506)| `Person.id`| _Equivalent_<br/>(46135/46136)| `Person.id`
| `Person.meta`| _Equivalent_<br/>(7141/7142)| **`Person.meta`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16993)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(16994)| `Person.meta`| _Equivalent_<br/>(31507/31508)| `Person.meta`| _Equivalent_<br/>(46137/46138)| `Person.meta`
| `Person.implicitRules`| _Equivalent_<br/>(7143/7144)| **`Person.implicitRules`**| _Equivalent_<br/>(16995/16996)| `Person.implicitRules`| _Equivalent_<br/>(31509/31510)| `Person.implicitRules`| _Equivalent_<br/>(46139/46140)| `Person.implicitRules`
| `Person.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7145)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7146)| **`Person.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16997)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(16998)| `Person.language`| _Equivalent_<br/>(31511/31512)| `Person.language`| _Equivalent_<br/>(46141/46142)| `Person.language`
| `Person.text`| _Equivalent_<br/>(7147/7148)| **`Person.text`**| _Equivalent_<br/>(16999/17000)| `Person.text`| _Equivalent_<br/>(31513/31514)| `Person.text`| _Equivalent_<br/>(46143/46144)| `Person.text`
| `Person.contained`| _Equivalent_<br/>(7149/7150)| **`Person.contained`**| _Equivalent_<br/>(17001/17002)| `Person.contained`| _Equivalent_<br/>(31515/31516)| `Person.contained`| _Equivalent_<br/>(46145/46146)| `Person.contained`
| `Person.extension`| _Equivalent_<br/>(7151/7152)| **`Person.extension`**| _Equivalent_<br/>(17003/17004)| `Person.extension`| _Equivalent_<br/>(31517/31518)| `Person.extension`| _Equivalent_<br/>(46147/46148)| `Person.extension`
| `Person.modifierExtension`| _Equivalent_<br/>(7153/7154)| **`Person.modifierExtension`**| _Equivalent_<br/>(17005/17006)| `Person.modifierExtension`| _Equivalent_<br/>(31519/31520)| `Person.modifierExtension`| _Equivalent_<br/>(46149/46150)| `Person.modifierExtension`
| `Person.identifier`| _Equivalent_<br/>(7155/7156)| **`Person.identifier`**| _Equivalent_<br/>(17007/17008)| `Person.identifier`| _Equivalent_<br/>(31521/31522)| `Person.identifier`| _Equivalent_<br/>(46151/46152)| `Person.identifier`
| `Person.name`| _Equivalent_<br/>(7157/7158)| **`Person.name`**| _Equivalent_<br/>(17009/17010)| `Person.name`| _Equivalent_<br/>(31523/31524)| `Person.name`| _Equivalent_<br/>(46153/46154)| `Person.name`
| `Person.telecom`| _Equivalent_<br/>(7159/7160)| **`Person.telecom`**| _Equivalent_<br/>(17011/17012)| `Person.telecom`| _Equivalent_<br/>(31525/31526)| `Person.telecom`| _Equivalent_<br/>(46155/46156)| `Person.telecom`
| `Person.gender`| _Equivalent_<br/>(7161/7162)| **`Person.gender`**| _Equivalent_<br/>(17013/17014)| `Person.gender`| _Equivalent_<br/>(31527/31528)| `Person.gender`| _Equivalent_<br/>(46157/46158)| `Person.gender`
| `Person.birthDate`| _Equivalent_<br/>(7163/7164)| **`Person.birthDate`**| _Equivalent_<br/>(17015/17016)| `Person.birthDate`| _Equivalent_<br/>(31529/31530)| `Person.birthDate`| _Equivalent_<br/>(46159/46160)| `Person.birthDate`
| `Person.address`| _Equivalent_<br/>(7165/7166)| **`Person.address`**| _Equivalent_<br/>(17017/17018)| `Person.address`| _Equivalent_<br/>(31531/31532)| `Person.address`| _Equivalent_<br/>(46161/46162)| `Person.address`
| `Person.photo`| _Equivalent_<br/>(7167/7168)| **`Person.photo`**| _Equivalent_<br/>(17019/17020)| `Person.photo`| _Equivalent_<br/>(31533/31534)| `Person.photo`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(46163)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(46164)| `Person.photo`
| `Person.managingOrganization`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7169)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7170)| **`Person.managingOrganization`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17021)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17022)| `Person.managingOrganization`| _Equivalent_<br/>(31535/31536)| `Person.managingOrganization`| _Equivalent_<br/>(46165/46166)| `Person.managingOrganization`
| `Person.active`| _Equivalent_<br/>(7171/7172)| **`Person.active`**| _Equivalent_<br/>(17023/17024)| `Person.active`| _Equivalent_<br/>(31537/31538)| `Person.active`| _Equivalent_<br/>(46167/46168)| `Person.active`
| `Person.link`| _Equivalent_<br/>(7173/7174)| **`Person.link`**| _Equivalent_<br/>(17025/17026)| `Person.link`| _Equivalent_<br/>(31539/31540)| `Person.link`| _Equivalent_<br/>(46169/46170)| `Person.link`
| `Person.link.id`| _Equivalent_<br/>(7175/7176)| **`Person.link.id`**| _Equivalent_<br/>(17027/17028)| `Person.link.id`| _Equivalent_<br/>(31541/31542)| `Person.link.id`| _Equivalent_<br/>(46171/46172)| `Person.link.id`
| `Person.link.extension`| _Equivalent_<br/>(7177/7178)| **`Person.link.extension`**| _Equivalent_<br/>(17029/17030)| `Person.link.extension`| _Equivalent_<br/>(31543/31544)| `Person.link.extension`| _Equivalent_<br/>(46173/46174)| `Person.link.extension`
| `Person.link.modifierExtension`| _Equivalent_<br/>(7179/7180)| **`Person.link.modifierExtension`**| _Equivalent_<br/>(17031/17032)| `Person.link.modifierExtension`| _Equivalent_<br/>(31545/31546)| `Person.link.modifierExtension`| _Equivalent_<br/>(46175/46176)| `Person.link.modifierExtension`
| `Person.link.target`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7181)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7182)| **`Person.link.target`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17033)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17034)| `Person.link.target`| _Equivalent_<br/>(31547/31548)| `Person.link.target`| _Equivalent_<br/>(46177/46178)| `Person.link.target`
| `Person.link.assurance`| _Equivalent_<br/>(7183/7184)| **`Person.link.assurance`**| _Equivalent_<br/>(17035/17036)| `Person.link.assurance`| _Equivalent_<br/>(31549/31550)| `Person.link.assurance`| _Equivalent_<br/>(46179/46180)| `Person.link.assurance`
| *24 of 24 elements used* | | *24 of 24 elements used* | | *24 of 24 elements used* | | *24 of 24 elements used* | | *24 of 32 elements used* <br/>remaining elements:<br/>`Person.communication`, `Person.communication.extension`, `Person.communication.id`, `Person.communication.language`, `Person.communication.modifierExtension`, `Person.communication.preferred`, `Person.deceased[x]`, `Person.maritalStatus`

