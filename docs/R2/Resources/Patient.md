Comparison of 
Generated at Thursday, April 3, 2025 8:18:07 AM

### Patient

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | Patient |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Patient` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for Patient Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `109` |
| Database Snapshot Count | `52` |
| Database Differential Count | `32` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Patient` | `Patient` | `Patient` | Patient | Information about an individual or animal receiving health care services | 0..* | Patient |  |  |
| `Patient.active` | `Patient.active` | `active` |  | Whether this patient's record is in active use | 0..1 | boolean |  |  |
| `Patient.address` | `Patient.address` | `address` |  | Addresses for the individual | 0..* | Address |  |  |
| `Patient.animal` | `Patient.animal` | `animal` |  | This patient is known to be an animal (non-human) | 0..1 | BackboneElement |  |  |
| `Patient.animal.breed` | `Patient.animal.breed` | `breed` |  | E.g. Poodle, Angus | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/animal-breeds` |
| `Patient.animal.extension` | `Patient.animal.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Patient.animal.genderStatus` | `Patient.animal.genderStatus` | `genderStatus` |  | E.g. Neutered, Intact | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/animal-genderstatus` |
| `Patient.animal.id` | `Patient.animal.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Patient.animal.modifierExtension` | `Patient.animal.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Patient.animal.species` | `Patient.animal.species` | `species` |  | E.g. Dog, Cow | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/animal-species` |
| `Patient.birthDate` | `Patient.birthDate` | `birthDate` |  | The date of birth for the individual | 0..1 | date |  |  |
| `Patient.careProvider` | `Patient.careProvider` | `careProvider` |  | Patient's nominated primary care provider | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
| `Patient.communication` | `Patient.communication` | `communication` |  | A list of Languages which may be used to communicate with the patient about his or her health | 0..* | BackboneElement |  |  |
| `Patient.communication.extension` | `Patient.communication.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Patient.communication.id` | `Patient.communication.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Patient.communication.language` | `Patient.communication.language` | `language` |  | The language which can be used to communicate with the patient about his or her health | 1..1 | CodeableConcept | `Required` | `http://tools.ietf.org/html/bcp47` |
| `Patient.communication.modifierExtension` | `Patient.communication.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Patient.communication.preferred` | `Patient.communication.preferred` | `preferred` |  | Language preference indicator | 0..1 | boolean |  |  |
| `Patient.contact` | `Patient.contact` | `contact` |  | A contact party (e.g. guardian, partner, friend) for the patient | 0..* | BackboneElement |  |  |
| `Patient.contact.address` | `Patient.contact.address` | `address` |  | Address for the contact person | 0..1 | Address |  |  |
| `Patient.contact.extension` | `Patient.contact.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Patient.contact.gender` | `Patient.contact.gender` | `gender` |  | male \| female \| other \| unknown | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/administrative-gender` |
| `Patient.contact.id` | `Patient.contact.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Patient.contact.modifierExtension` | `Patient.contact.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Patient.contact.name` | `Patient.contact.name` | `name` |  | A name associated with the contact person | 0..1 | HumanName |  |  |
| `Patient.contact.organization` | `Patient.contact.organization` | `organization` |  | Organization that is associated with the contact | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `Patient.contact.period` | `Patient.contact.period` | `period` |  | The period during which this contact person or organization is valid to be contacted relating to this patient | 0..1 | Period |  |  |
| `Patient.contact.relationship` | `Patient.contact.relationship` | `relationship` |  | The kind of relationship | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/patient-contact-relationship` |
| `Patient.contact.telecom` | `Patient.contact.telecom` | `telecom` |  | A contact detail for the person | 0..* | ContactPoint |  |  |
| `Patient.contained` | `Patient.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Patient.deceased[x]` | `Patient.deceased[x]` | `deceased[x]` |  | Indicates if the individual is deceased or not | 0..1 | boolean, dateTime |  |  |
| `Patient.extension` | `Patient.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Patient.gender` | `Patient.gender` | `gender` |  | male \| female \| other \| unknown | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/administrative-gender` |
| `Patient.id` | `Patient.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Patient.identifier` | `Patient.identifier` | `identifier` |  | An identifier for this patient | 0..* | Identifier |  |  |
| `Patient.implicitRules` | `Patient.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Patient.language` | `Patient.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `Patient.link` | `Patient.link` | `link` |  | Link to another patient resource that concerns the same actual person | 0..* | BackboneElement |  |  |
| `Patient.link.extension` | `Patient.link.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Patient.link.id` | `Patient.link.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Patient.link.modifierExtension` | `Patient.link.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Patient.link.other` | `Patient.link.other` | `other` |  | The other patient resource that the link refers to | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `Patient.link.type` | `Patient.link.type` | `type` |  | replace \| refer \| seealso - type of link | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/link-type` |
| `Patient.managingOrganization` | `Patient.managingOrganization` | `managingOrganization` |  | Organization that is the custodian of the patient record | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `Patient.maritalStatus` | `Patient.maritalStatus` | `maritalStatus` |  | Marital (civil) status of a patient | 0..1 | CodeableConcept | `Required` | `http://hl7.org/fhir/ValueSet/marital-status` |
| `Patient.meta` | `Patient.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Patient.modifierExtension` | `Patient.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Patient.multipleBirth[x]` | `Patient.multipleBirth[x]` | `multipleBirth[x]` |  | Whether patient is part of a multiple birth | 0..1 | boolean, integer |  |  |
| `Patient.name` | `Patient.name` | `name` |  | A name associated with the patient | 0..* | HumanName |  |  |
| `Patient.photo` | `Patient.photo` | `photo` |  | Image of the patient | 0..* | Attachment |  |  |
| `Patient.telecom` | `Patient.telecom` | `telecom` |  | A contact detail for the individual | 0..* | ContactPoint |  |  |
| `Patient.text` | `Patient.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Patient](/docs/R2/Resources/Patient.md)<br/> `http://hl7.org/fhir/StructureDefinition/Patient\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `139`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `305`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Patient](/docs/R3/Resources/Patient.md)<br/> `http://hl7.org/fhir/StructureDefinition/Patient\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `494`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `689`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Patient](/docs/R4/Resources/Patient.md)<br/> `http://hl7.org/fhir/StructureDefinition/Patient\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1571`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1572`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Patient](/docs/R4B/Resources/Patient.md)<br/> `http://hl7.org/fhir/StructureDefinition/Patient\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1021`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1250`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Patient](/docs/R5/Resources/Patient.md)<br/> `http://hl7.org/fhir/StructureDefinition/Patient\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Patient from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 Patient| Relationship | [R3 Patient](/docs/R3/Resources/Patient.md)| Relationship | [R4 Patient](/docs/R4/Resources/Patient.md)| Relationship | [R4B Patient](/docs/R4B/Resources/Patient.md)| Relationship | [R5 Patient](/docs/R5/Resources/Patient.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`Patient`**| _Equivalent_<br/>(6938/6939)| `Patient`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(16791)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(16792)| `Patient`| _Equivalent_<br/>(31279/31280)| `Patient`| _Equivalent_<br/>(45946/45947)| `Patient`
| **`Patient.id`**| _Equivalent_<br/>(6940/6941)| `Patient.id`| _Equivalent_<br/>(16793/16794)| `Patient.id`| _Equivalent_<br/>(31281/31282)| `Patient.id`| _Equivalent_<br/>(45948/45949)| `Patient.id`
| **`Patient.meta`**| _Equivalent_<br/>(6942/6943)| `Patient.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16795)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(16796)| `Patient.meta`| _Equivalent_<br/>(31283/31284)| `Patient.meta`| _Equivalent_<br/>(45950/45951)| `Patient.meta`
| **`Patient.implicitRules`**| _Equivalent_<br/>(6944/6945)| `Patient.implicitRules`| _Equivalent_<br/>(16797/16798)| `Patient.implicitRules`| _Equivalent_<br/>(31285/31286)| `Patient.implicitRules`| _Equivalent_<br/>(45952/45953)| `Patient.implicitRules`
| **`Patient.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(6946)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(6947)| `Patient.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16799)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(16800)| `Patient.language`| _Equivalent_<br/>(31287/31288)| `Patient.language`| _Equivalent_<br/>(45954/45955)| `Patient.language`
| **`Patient.text`**| _Equivalent_<br/>(6948/6949)| `Patient.text`| _Equivalent_<br/>(16801/16802)| `Patient.text`| _Equivalent_<br/>(31289/31290)| `Patient.text`| _Equivalent_<br/>(45956/45957)| `Patient.text`
| **`Patient.contained`**| _Equivalent_<br/>(6950/6951)| `Patient.contained`| _Equivalent_<br/>(16803/16804)| `Patient.contained`| _Equivalent_<br/>(31291/31292)| `Patient.contained`| _Equivalent_<br/>(45958/45959)| `Patient.contained`
| **`Patient.extension`**| _Equivalent_<br/>(6952/6953)| `Patient.extension`| _Equivalent_<br/>(16805/16806)| `Patient.extension`| _Equivalent_<br/>(31293/31294)| `Patient.extension`| _Equivalent_<br/>(45960/45961)| `Patient.extension`
| **`Patient.modifierExtension`**| _Equivalent_<br/>(6954/6955)| `Patient.modifierExtension`| _Equivalent_<br/>(16807/16808)| `Patient.modifierExtension`| _Equivalent_<br/>(31295/31296)| `Patient.modifierExtension`| _Equivalent_<br/>(45962/45963)| `Patient.modifierExtension`
| **`Patient.identifier`**| _Equivalent_<br/>(6956/6957)| `Patient.identifier`| _Equivalent_<br/>(16809/16810)| `Patient.identifier`| _Equivalent_<br/>(31297/31298)| `Patient.identifier`| _Equivalent_<br/>(45964/45965)| `Patient.identifier`
| **`Patient.active`**| _Equivalent_<br/>(6958/6959)| `Patient.active`| _Equivalent_<br/>(16811/16812)| `Patient.active`| _Equivalent_<br/>(31299/31300)| `Patient.active`| _Equivalent_<br/>(45966/45967)| `Patient.active`
| **`Patient.name`**| _Equivalent_<br/>(6960/6961)| `Patient.name`| _Equivalent_<br/>(16813/16814)| `Patient.name`| _Equivalent_<br/>(31301/31302)| `Patient.name`| _Equivalent_<br/>(45968/45969)| `Patient.name`
| **`Patient.telecom`**| _Equivalent_<br/>(6962/6963)| `Patient.telecom`| _Equivalent_<br/>(16815/16816)| `Patient.telecom`| _Equivalent_<br/>(31303/31304)| `Patient.telecom`| _Equivalent_<br/>(45970/45971)| `Patient.telecom`
| **`Patient.gender`**| _Equivalent_<br/>(6964/6965)| `Patient.gender`| _Equivalent_<br/>(16817/16818)| `Patient.gender`| _Equivalent_<br/>(31305/31306)| `Patient.gender`| _Equivalent_<br/>(45972/45973)| `Patient.gender`
| **`Patient.birthDate`**| _Equivalent_<br/>(6966/6967)| `Patient.birthDate`| _Equivalent_<br/>(16819/16820)| `Patient.birthDate`| _Equivalent_<br/>(31307/31308)| `Patient.birthDate`| _Equivalent_<br/>(45974/45975)| `Patient.birthDate`
| **`Patient.deceased[x]`**| _Equivalent_<br/>(6968/6969)| `Patient.deceased[x]`| _Equivalent_<br/>(16821/16822)| `Patient.deceased[x]`| _Equivalent_<br/>(31309/31310)| `Patient.deceased[x]`| _Equivalent_<br/>(45976/45977)| `Patient.deceased[x]`
| **`Patient.address`**| _Equivalent_<br/>(6970/6971)| `Patient.address`| _Equivalent_<br/>(16823/16824)| `Patient.address`| _Equivalent_<br/>(31311/31312)| `Patient.address`| _Equivalent_<br/>(45978/45979)| `Patient.address`
| **`Patient.maritalStatus`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(6972)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(6973)| `Patient.maritalStatus`| _Equivalent_<br/>(16825/16826)| `Patient.maritalStatus`| _Equivalent_<br/>(31313/31314)| `Patient.maritalStatus`| _Equivalent_<br/>(45980/45981)| `Patient.maritalStatus`
| **`Patient.multipleBirth[x]`**| _Equivalent_<br/>(6974/6975)| `Patient.multipleBirth[x]`| _Equivalent_<br/>(16827/16828)| `Patient.multipleBirth[x]`| _Equivalent_<br/>(31315/31316)| `Patient.multipleBirth[x]`| _Equivalent_<br/>(45982/45983)| `Patient.multipleBirth[x]`
| **`Patient.photo`**| _Equivalent_<br/>(6976/6977)| `Patient.photo`| _Equivalent_<br/>(16829/16830)| `Patient.photo`| _Equivalent_<br/>(31317/31318)| `Patient.photo`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(45984)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(45985)| `Patient.photo`
| **`Patient.contact`**| _Equivalent_<br/>(6978/6979)| `Patient.contact`| _Equivalent_<br/>(16831/16832)| `Patient.contact`| _Equivalent_<br/>(31319/31320)| `Patient.contact`| _Equivalent_<br/>(45986/45987)| `Patient.contact`
| **`Patient.contact.id`**| _Equivalent_<br/>(6980/6981)| `Patient.contact.id`| _Equivalent_<br/>(16833/16834)| `Patient.contact.id`| _Equivalent_<br/>(31321/31322)| `Patient.contact.id`| _Equivalent_<br/>(45988/45989)| `Patient.contact.id`
| **`Patient.contact.extension`**| _Equivalent_<br/>(6982/6983)| `Patient.contact.extension`| _Equivalent_<br/>(16835/16836)| `Patient.contact.extension`| _Equivalent_<br/>(31323/31324)| `Patient.contact.extension`| _Equivalent_<br/>(45990/45991)| `Patient.contact.extension`
| **`Patient.contact.modifierExtension`**| _Equivalent_<br/>(6984/6985)| `Patient.contact.modifierExtension`| _Equivalent_<br/>(16837/16838)| `Patient.contact.modifierExtension`| _Equivalent_<br/>(31325/31326)| `Patient.contact.modifierExtension`| _Equivalent_<br/>(45992/45993)| `Patient.contact.modifierExtension`
| **`Patient.contact.relationship`**| _Equivalent_<br/>(6986/6987)| `Patient.contact.relationship`| _Equivalent_<br/>(16839/16840)| `Patient.contact.relationship`| _Equivalent_<br/>(31327/31328)| `Patient.contact.relationship`| _Equivalent_<br/>(45994/45995)| `Patient.contact.relationship`
| **`Patient.contact.name`**| _Equivalent_<br/>(6988/6989)| `Patient.contact.name`| _Equivalent_<br/>(16841/16842)| `Patient.contact.name`| _Equivalent_<br/>(31329/31330)| `Patient.contact.name`| _Equivalent_<br/>(45996/45997)| `Patient.contact.name`
| **`Patient.contact.telecom`**| _Equivalent_<br/>(6990/6991)| `Patient.contact.telecom`| _Equivalent_<br/>(16843/16844)| `Patient.contact.telecom`| _Equivalent_<br/>(31331/31332)| `Patient.contact.telecom`| _Equivalent_<br/>(45998/45999)| `Patient.contact.telecom`
| **`Patient.contact.address`**| _Equivalent_<br/>(6992/6993)| `Patient.contact.address`| _Equivalent_<br/>(16845/16846)| `Patient.contact.address`| _Equivalent_<br/>(31333/31334)| `Patient.contact.address`| _Equivalent_<br/>(46000/46001)| `Patient.contact.address`
| **`Patient.contact.gender`**| _Equivalent_<br/>(6994/6995)| `Patient.contact.gender`| _Equivalent_<br/>(16847/16848)| `Patient.contact.gender`| _Equivalent_<br/>(31335/31336)| `Patient.contact.gender`| _Equivalent_<br/>(46002/46003)| `Patient.contact.gender`
| **`Patient.contact.organization`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(6996)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6997)| `Patient.contact.organization`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16849)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(16850)| `Patient.contact.organization`| _Equivalent_<br/>(31337/31338)| `Patient.contact.organization`| _Equivalent_<br/>(46004/46005)| `Patient.contact.organization`
| **`Patient.contact.period`**| _Equivalent_<br/>(6998/6999)| `Patient.contact.period`| _Equivalent_<br/>(16851/16852)| `Patient.contact.period`| _Equivalent_<br/>(31339/31340)| `Patient.contact.period`| _Equivalent_<br/>(46006/46007)| `Patient.contact.period`
| **`Patient.animal`**| _Equivalent_<br/>(7000/7001)| `Patient.animal`| | | | | | | 
| **`Patient.animal.id`**| _Equivalent_<br/>(7002/7003)| `Patient.animal.id`| | | | | | | 
| **`Patient.animal.extension`**| _Equivalent_<br/>(7004/7005)| `Patient.animal.extension`| | | | | | | 
| **`Patient.animal.modifierExtension`**| _Equivalent_<br/>(7006/7007)| `Patient.animal.modifierExtension`| | | | | | | 
| **`Patient.animal.species`**| _Equivalent_<br/>(7008/7009)| `Patient.animal.species`| | | | | | | 
| **`Patient.animal.breed`**| _Equivalent_<br/>(7010/7011)| `Patient.animal.breed`| | | | | | | 
| **`Patient.animal.genderStatus`**| _Equivalent_<br/>(7012/7013)| `Patient.animal.genderStatus`| | | | | | | 
| **`Patient.communication`**| _Equivalent_<br/>(7014/7015)| `Patient.communication`| _Equivalent_<br/>(16857/16858)| `Patient.communication`| _Equivalent_<br/>(31341/31342)| `Patient.communication`| _Equivalent_<br/>(46008/46009)| `Patient.communication`
| **`Patient.communication.id`**| _Equivalent_<br/>(7016/7017)| `Patient.communication.id`| _Equivalent_<br/>(16859/16860)| `Patient.communication.id`| _Equivalent_<br/>(31343/31344)| `Patient.communication.id`| _Equivalent_<br/>(46010/46011)| `Patient.communication.id`
| **`Patient.communication.extension`**| _Equivalent_<br/>(7018/7019)| `Patient.communication.extension`| _Equivalent_<br/>(16861/16862)| `Patient.communication.extension`| _Equivalent_<br/>(31345/31346)| `Patient.communication.extension`| _Equivalent_<br/>(46012/46013)| `Patient.communication.extension`
| **`Patient.communication.modifierExtension`**| _Equivalent_<br/>(7020/7021)| `Patient.communication.modifierExtension`| _Equivalent_<br/>(16863/16864)| `Patient.communication.modifierExtension`| _Equivalent_<br/>(31347/31348)| `Patient.communication.modifierExtension`| _Equivalent_<br/>(46014/46015)| `Patient.communication.modifierExtension`
| **`Patient.communication.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7022)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7023)| `Patient.communication.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16865)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(16866)| `Patient.communication.language`| _Equivalent_<br/>(31349/31350)| `Patient.communication.language`| _Equivalent_<br/>(46016/46017)| `Patient.communication.language`
| **`Patient.communication.preferred`**| _Equivalent_<br/>(7024/7025)| `Patient.communication.preferred`| _Equivalent_<br/>(16867/16868)| `Patient.communication.preferred`| _Equivalent_<br/>(31351/31352)| `Patient.communication.preferred`| _Equivalent_<br/>(46018/46019)| `Patient.communication.preferred`
| **`Patient.careProvider`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(317)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(681)| `Patient.generalPractitioner`| →→→→ _RelatedTo_ →→→→ <br/>(16869)<hr/>←←←← _RelatedTo_ ←←←← <br/>(16870)| `Patient.generalPractitioner`| _Equivalent_<br/>(31353/31354)| `Patient.generalPractitioner`| _Equivalent_<br/>(46020/46021)| `Patient.generalPractitioner`
| **`Patient.managingOrganization`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7026)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7027)| `Patient.managingOrganization`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16871)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(16872)| `Patient.managingOrganization`| _Equivalent_<br/>(31355/31356)| `Patient.managingOrganization`| _Equivalent_<br/>(46022/46023)| `Patient.managingOrganization`
| **`Patient.link`**| _Equivalent_<br/>(7028/7029)| `Patient.link`| _Equivalent_<br/>(16873/16874)| `Patient.link`| _Equivalent_<br/>(31357/31358)| `Patient.link`| _Equivalent_<br/>(46024/46025)| `Patient.link`
| **`Patient.link.id`**| _Equivalent_<br/>(7030/7031)| `Patient.link.id`| _Equivalent_<br/>(16875/16876)| `Patient.link.id`| _Equivalent_<br/>(31359/31360)| `Patient.link.id`| _Equivalent_<br/>(46026/46027)| `Patient.link.id`
| **`Patient.link.extension`**| _Equivalent_<br/>(7032/7033)| `Patient.link.extension`| _Equivalent_<br/>(16877/16878)| `Patient.link.extension`| _Equivalent_<br/>(31361/31362)| `Patient.link.extension`| _Equivalent_<br/>(46028/46029)| `Patient.link.extension`
| **`Patient.link.modifierExtension`**| _Equivalent_<br/>(7034/7035)| `Patient.link.modifierExtension`| _Equivalent_<br/>(16879/16880)| `Patient.link.modifierExtension`| _Equivalent_<br/>(31363/31364)| `Patient.link.modifierExtension`| _Equivalent_<br/>(46030/46031)| `Patient.link.modifierExtension`
| **`Patient.link.other`**| →→→→ _RelatedTo_ →→→→ <br/>(7036)<hr/>←←←← _RelatedTo_ ←←←← <br/>(7037)| `Patient.link.other`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16881)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(16882)| `Patient.link.other`| _Equivalent_<br/>(31365/31366)| `Patient.link.other`| _Equivalent_<br/>(46032/46033)| `Patient.link.other`
| **`Patient.link.type`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(7038)<hr/>←←←← _RelatedTo_ ←←←← <br/>(7039)| `Patient.link.type`| _Equivalent_<br/>(16883/16884)| `Patient.link.type`| _Equivalent_<br/>(31367/31368)| `Patient.link.type`| _Equivalent_<br/>(46034/46035)| `Patient.link.type`
| *52 of 52 elements used* | | *52 of 52 elements used* | | *45 of 45 elements used* | | *45 of 45 elements used* | | *45 of 45 elements used* 

