Comparison of 
Generated at Friday, April 4, 2025 2:58:42 PM

### Practitioner

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | Practitioner |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Practitioner` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for Practitioner Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `561` |
| Database Snapshot Count | `26` |
| Database Differential Count | `15` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Practitioner` | `Practitioner` | `Practitioner` | Practitioner | A person with a  formal responsibility in the provisioning of healthcare or related services | 0..* | Practitioner |  |  |
| `Practitioner.active` | `Practitioner.active` | `active` |  | Whether this practitioner's record is in active use | 0..1 | boolean |  |  |
| `Practitioner.address` | `Practitioner.address` | `address` |  | Address(es) of the practitioner that are not role specific (typically home address) | 0..* | Address |  |  |
| `Practitioner.birthDate` | `Practitioner.birthDate` | `birthDate` |  | The date  on which the practitioner was born | 0..1 | date |  |  |
| `Practitioner.communication` | `Practitioner.communication` | `communication` |  | A language the practitioner is able to use in patient communication | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `Practitioner.contained` | `Practitioner.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Practitioner.extension` | `Practitioner.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Practitioner.gender` | `Practitioner.gender` | `gender` |  | male \| female \| other \| unknown | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/administrative-gender` |
| `Practitioner.id` | `Practitioner.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Practitioner.identifier` | `Practitioner.identifier` | `identifier` |  | A identifier for the person as this agent | 0..* | Identifier |  |  |
| `Practitioner.implicitRules` | `Practitioner.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Practitioner.language` | `Practitioner.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `Practitioner.meta` | `Practitioner.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Practitioner.modifierExtension` | `Practitioner.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Practitioner.name` | `Practitioner.name` | `name` |  | The name(s) associated with the practitioner | 0..* | HumanName |  |  |
| `Practitioner.photo` | `Practitioner.photo` | `photo` |  | Image of the person | 0..* | Attachment |  |  |
| `Practitioner.qualification` | `Practitioner.qualification` | `qualification` |  | Qualifications obtained by training and certification | 0..* | BackboneElement |  |  |
| `Practitioner.qualification.code` | `Practitioner.qualification.code` | `code` |  | Coded representation of the qualification | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/v2-2.7-0360` |
| `Practitioner.qualification.extension` | `Practitioner.qualification.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Practitioner.qualification.id` | `Practitioner.qualification.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Practitioner.qualification.identifier` | `Practitioner.qualification.identifier` | `identifier` |  | An identifier for this qualification for the practitioner | 0..* | Identifier |  |  |
| `Practitioner.qualification.issuer` | `Practitioner.qualification.issuer` | `issuer` |  | Organization that regulates and issues the qualification | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `Practitioner.qualification.modifierExtension` | `Practitioner.qualification.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Practitioner.qualification.period` | `Practitioner.qualification.period` | `period` |  | Period during which the qualification is valid | 0..1 | Period |  |  |
| `Practitioner.telecom` | `Practitioner.telecom` | `telecom` |  | A contact detail for the practitioner (that apply to all roles) | 0..* | ContactPoint |  |  |
| `Practitioner.text` | `Practitioner.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Practitioner](/docs/R2/Resources/Practitioner.md)<br/> `http://hl7.org/fhir/StructureDefinition/Practitioner\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `143`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `309`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Practitioner](/docs/R3/Resources/Practitioner.md)<br/> `http://hl7.org/fhir/StructureDefinition/Practitioner\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `499`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `694`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Practitioner](/docs/R4/Resources/Practitioner.md)<br/> `http://hl7.org/fhir/StructureDefinition/Practitioner\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1581`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1582`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Practitioner](/docs/R4B/Resources/Practitioner.md)<br/> `http://hl7.org/fhir/StructureDefinition/Practitioner\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1026`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1255`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Practitioner](/docs/R5/Resources/Practitioner.md)<br/> `http://hl7.org/fhir/StructureDefinition/Practitioner\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Practitioner from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Practitioner](/docs/R2/Resources/Practitioner.md)| Relationship | R3 Practitioner| Relationship | [R4 Practitioner](/docs/R4/Resources/Practitioner.md)| Relationship | [R4B Practitioner](/docs/R4B/Resources/Practitioner.md)| Relationship | [R5 Practitioner](/docs/R5/Resources/Practitioner.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `Practitioner`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(7185)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7186)| **`Practitioner`**| _Equivalent_<br/>(17233/17234)| `Practitioner`| _Equivalent_<br/>(31773/31774)| `Practitioner`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(46389)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(46390)| `Practitioner`
| `Practitioner.id`| _Equivalent_<br/>(7187/7188)| **`Practitioner.id`**| _Equivalent_<br/>(17235/17236)| `Practitioner.id`| _Equivalent_<br/>(31775/31776)| `Practitioner.id`| _Equivalent_<br/>(46391/46392)| `Practitioner.id`
| `Practitioner.meta`| _Equivalent_<br/>(7189/7190)| **`Practitioner.meta`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17237)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17238)| `Practitioner.meta`| _Equivalent_<br/>(31777/31778)| `Practitioner.meta`| _Equivalent_<br/>(46393/46394)| `Practitioner.meta`
| `Practitioner.implicitRules`| _Equivalent_<br/>(7191/7192)| **`Practitioner.implicitRules`**| _Equivalent_<br/>(17239/17240)| `Practitioner.implicitRules`| _Equivalent_<br/>(31779/31780)| `Practitioner.implicitRules`| _Equivalent_<br/>(46395/46396)| `Practitioner.implicitRules`
| `Practitioner.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7193)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7194)| **`Practitioner.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17241)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(17242)| `Practitioner.language`| _Equivalent_<br/>(31781/31782)| `Practitioner.language`| _Equivalent_<br/>(46397/46398)| `Practitioner.language`
| `Practitioner.text`| _Equivalent_<br/>(7195/7196)| **`Practitioner.text`**| _Equivalent_<br/>(17243/17244)| `Practitioner.text`| _Equivalent_<br/>(31783/31784)| `Practitioner.text`| _Equivalent_<br/>(46399/46400)| `Practitioner.text`
| `Practitioner.contained`| _Equivalent_<br/>(7197/7198)| **`Practitioner.contained`**| _Equivalent_<br/>(17245/17246)| `Practitioner.contained`| _Equivalent_<br/>(31785/31786)| `Practitioner.contained`| _Equivalent_<br/>(46401/46402)| `Practitioner.contained`
| `Practitioner.extension`| _Equivalent_<br/>(7199/7200)| **`Practitioner.extension`**| _Equivalent_<br/>(17247/17248)| `Practitioner.extension`| _Equivalent_<br/>(31787/31788)| `Practitioner.extension`| _Equivalent_<br/>(46403/46404)| `Practitioner.extension`
| `Practitioner.modifierExtension`| _Equivalent_<br/>(7201/7202)| **`Practitioner.modifierExtension`**| _Equivalent_<br/>(17249/17250)| `Practitioner.modifierExtension`| _Equivalent_<br/>(31789/31790)| `Practitioner.modifierExtension`| _Equivalent_<br/>(46405/46406)| `Practitioner.modifierExtension`
| `Practitioner.identifier`| _Equivalent_<br/>(7203/7204)| **`Practitioner.identifier`**| _Equivalent_<br/>(17251/17252)| `Practitioner.identifier`| _Equivalent_<br/>(31791/31792)| `Practitioner.identifier`| _Equivalent_<br/>(46407/46408)| `Practitioner.identifier`
| `Practitioner.active`| _Equivalent_<br/>(7205/7206)| **`Practitioner.active`**| _Equivalent_<br/>(17253/17254)| `Practitioner.active`| _Equivalent_<br/>(31793/31794)| `Practitioner.active`| _Equivalent_<br/>(46409/46410)| `Practitioner.active`
| `Practitioner.name`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7207)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7208)| **`Practitioner.name`**| _Equivalent_<br/>(17255/17256)| `Practitioner.name`| _Equivalent_<br/>(31795/31796)| `Practitioner.name`| _Equivalent_<br/>(46411/46412)| `Practitioner.name`
| `Practitioner.telecom`| _Equivalent_<br/>(7209/7210)| **`Practitioner.telecom`**| _Equivalent_<br/>(17257/17258)| `Practitioner.telecom`| _Equivalent_<br/>(31797/31798)| `Practitioner.telecom`| _Equivalent_<br/>(46413/46414)| `Practitioner.telecom`
| `Practitioner.address`| _Equivalent_<br/>(7211/7212)| **`Practitioner.address`**| _Equivalent_<br/>(17259/17260)| `Practitioner.address`| _Equivalent_<br/>(31799/31800)| `Practitioner.address`| _Equivalent_<br/>(46415/46416)| `Practitioner.address`
| `Practitioner.gender`| _Equivalent_<br/>(7213/7214)| **`Practitioner.gender`**| _Equivalent_<br/>(17261/17262)| `Practitioner.gender`| _Equivalent_<br/>(31801/31802)| `Practitioner.gender`| _Equivalent_<br/>(46417/46418)| `Practitioner.gender`
| `Practitioner.birthDate`| _Equivalent_<br/>(7215/7216)| **`Practitioner.birthDate`**| _Equivalent_<br/>(17263/17264)| `Practitioner.birthDate`| _Equivalent_<br/>(31803/31804)| `Practitioner.birthDate`| _Equivalent_<br/>(46419/46420)| `Practitioner.birthDate`
| `Practitioner.photo`| _Equivalent_<br/>(7217/7218)| **`Practitioner.photo`**| _Equivalent_<br/>(17265/17266)| `Practitioner.photo`| _Equivalent_<br/>(31805/31806)| `Practitioner.photo`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(46421)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(46422)| `Practitioner.photo`
| `Practitioner.qualification`| _Equivalent_<br/>(7223/7224)| **`Practitioner.qualification`**| _Equivalent_<br/>(17267/17268)| `Practitioner.qualification`| _Equivalent_<br/>(31807/31808)| `Practitioner.qualification`| _Equivalent_<br/>(46423/46424)| `Practitioner.qualification`
| `Practitioner.qualification.id`| _Equivalent_<br/>(7225/7226)| **`Practitioner.qualification.id`**| _Equivalent_<br/>(17269/17270)| `Practitioner.qualification.id`| _Equivalent_<br/>(31809/31810)| `Practitioner.qualification.id`| _Equivalent_<br/>(46425/46426)| `Practitioner.qualification.id`
| `Practitioner.qualification.extension`| _Equivalent_<br/>(7227/7228)| **`Practitioner.qualification.extension`**| _Equivalent_<br/>(17271/17272)| `Practitioner.qualification.extension`| _Equivalent_<br/>(31811/31812)| `Practitioner.qualification.extension`| _Equivalent_<br/>(46427/46428)| `Practitioner.qualification.extension`
| `Practitioner.qualification.modifierExtension`| _Equivalent_<br/>(7229/7230)| **`Practitioner.qualification.modifierExtension`**| _Equivalent_<br/>(17273/17274)| `Practitioner.qualification.modifierExtension`| _Equivalent_<br/>(31813/31814)| `Practitioner.qualification.modifierExtension`| _Equivalent_<br/>(46429/46430)| `Practitioner.qualification.modifierExtension`
| `Practitioner.qualification.identifier`| _Equivalent_<br/>(7231/7232)| **`Practitioner.qualification.identifier`**| _Equivalent_<br/>(17275/17276)| `Practitioner.qualification.identifier`| _Equivalent_<br/>(31815/31816)| `Practitioner.qualification.identifier`| _Equivalent_<br/>(46431/46432)| `Practitioner.qualification.identifier`
| `Practitioner.qualification.code`| _Equivalent_<br/>(7233/7234)| **`Practitioner.qualification.code`**| _Equivalent_<br/>(17277/17278)| `Practitioner.qualification.code`| _Equivalent_<br/>(31817/31818)| `Practitioner.qualification.code`| _Equivalent_<br/>(46433/46434)| `Practitioner.qualification.code`
| `Practitioner.qualification.period`| _Equivalent_<br/>(7235/7236)| **`Practitioner.qualification.period`**| _Equivalent_<br/>(17279/17280)| `Practitioner.qualification.period`| _Equivalent_<br/>(31819/31820)| `Practitioner.qualification.period`| _Equivalent_<br/>(46435/46436)| `Practitioner.qualification.period`
| `Practitioner.qualification.issuer`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7237)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7238)| **`Practitioner.qualification.issuer`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17281)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17282)| `Practitioner.qualification.issuer`| _Equivalent_<br/>(31821/31822)| `Practitioner.qualification.issuer`| _Equivalent_<br/>(46437/46438)| `Practitioner.qualification.issuer`
| `Practitioner.communication`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7239)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7240)| **`Practitioner.communication`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17283)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(17284)| `Practitioner.communication`| _Equivalent_<br/>(31823/31824)| `Practitioner.communication`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(46439)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(46440)| `Practitioner.communication`
| *26 of 36 elements used* <br/>remaining elements:<br/>`Practitioner.practitionerRole`, `Practitioner.practitionerRole.extension`, `Practitioner.practitionerRole.healthcareService`, `Practitioner.practitionerRole.id`, `Practitioner.practitionerRole.location`, `Practitioner.practitionerRole.managingOrganization`, `Practitioner.practitionerRole.modifierExtension`, `Practitioner.practitionerRole.period`, `Practitioner.practitionerRole.role`, `Practitioner.practitionerRole.specialty`| | *26 of 26 elements used* | | *26 of 26 elements used* | | *26 of 26 elements used* | | *26 of 32 elements used* <br/>remaining elements:<br/>`Practitioner.communication.extension`, `Practitioner.communication.id`, `Practitioner.communication.language`, `Practitioner.communication.modifierExtension`, `Practitioner.communication.preferred`, `Practitioner.deceased[x]`

