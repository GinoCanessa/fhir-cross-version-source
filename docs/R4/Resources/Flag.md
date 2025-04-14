Comparison of 
Generated at Monday, April 14, 2025 6:17:32 PM

### Flag

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | Flag |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Flag` |
| Version | 4.0.1 |
| Description | Prospective warnings of potential issues when providing care to the patient. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1086` |
| Database Snapshot Count | `17` |
| Database Differential Count | `9` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Flag` | `Flag` | `Flag` | Flag | Key information to flag to healthcare providers | 0..* | Flag |  |  |
| `Flag.author` | `Flag.author` | `author` | Flag.author | Flag creator | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole) |  |  |
| `Flag.category` | `Flag.category` | `category` | Flag.category | Clinical, administrative, etc. | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/flag-category` |
| `Flag.code` | `Flag.code` | `code` | Flag.code | Coded or textual message to display to user | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/flag-code` |
| `Flag.contained` | `Flag.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Flag.encounter` | `Flag.encounter` | `encounter` | Flag.encounter | Alert relevant during encounter | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Encounter) |  |  |
| `Flag.extension` | `Flag.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Flag.id` | `Flag.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Flag.identifier` | `Flag.identifier` | `identifier` | Flag.identifier | Business identifier | 0..* | Identifier |  |  |
| `Flag.implicitRules` | `Flag.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Flag.language` | `Flag.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `Flag.meta` | `Flag.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Flag.modifierExtension` | `Flag.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Flag.period` | `Flag.period` | `period` | Flag.period | Time period when flag is active | 0..1 | Period |  |  |
| `Flag.status` | `Flag.status` | `status` | Flag.status | active \| inactive \| entered-in-error | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/flag-status|4.0.1` |
| `Flag.subject` | `Flag.subject` | `subject` | Flag.subject | Who/What is flag about? | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Location), Reference(http://hl7.org/fhir/StructureDefinition/Medication), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/PlanDefinition), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/Procedure) |  |  |
| `Flag.text` | `Flag.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Flag](/docs/R2/Resources/Flag.md)<br/> `http://hl7.org/fhir/StructureDefinition/Flag\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `112`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `278`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Flag](/docs/R3/Resources/Flag.md)<br/> `http://hl7.org/fhir/StructureDefinition/Flag\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `462`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `656`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Flag](/docs/R4/Resources/Flag.md)<br/> `http://hl7.org/fhir/StructureDefinition/Flag\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1495`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1496`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Flag](/docs/R4B/Resources/Flag.md)<br/> `http://hl7.org/fhir/StructureDefinition/Flag\|4.3.0` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `981`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1210`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Flag](/docs/R5/Resources/Flag.md)<br/> `http://hl7.org/fhir/StructureDefinition/Flag\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Flag from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Flag](/docs/R2/Resources/Flag.md)| Relationship | [R3 Flag](/docs/R3/Resources/Flag.md)| Relationship | R4 Flag| Relationship | [R4B Flag](/docs/R4B/Resources/Flag.md)| Relationship | [R5 Flag](/docs/R5/Resources/Flag.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `Flag`| _Equivalent_<br/>(5307/5308)| `Flag`| _Equivalent_<br/>(14468/14469)| **`Flag`**| _Equivalent_<br/>(27494/27495)| `Flag`| _Equivalent_<br/>(42486/42487)| `Flag`
| `Flag.id`| _Equivalent_<br/>(5309/5310)| `Flag.id`| _Equivalent_<br/>(14470/14471)| **`Flag.id`**| _Equivalent_<br/>(27496/27497)| `Flag.id`| _Equivalent_<br/>(42488/42489)| `Flag.id`
| `Flag.meta`| _Equivalent_<br/>(5311/5312)| `Flag.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(14472)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(14473)| **`Flag.meta`**| _Equivalent_<br/>(27498/27499)| `Flag.meta`| _Equivalent_<br/>(42490/42491)| `Flag.meta`
| `Flag.implicitRules`| _Equivalent_<br/>(5313/5314)| `Flag.implicitRules`| _Equivalent_<br/>(14474/14475)| **`Flag.implicitRules`**| _Equivalent_<br/>(27500/27501)| `Flag.implicitRules`| _Equivalent_<br/>(42492/42493)| `Flag.implicitRules`
| `Flag.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5315)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(5316)| `Flag.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(14476)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(14477)| **`Flag.language`**| _Equivalent_<br/>(27502/27503)| `Flag.language`| _Equivalent_<br/>(42494/42495)| `Flag.language`
| `Flag.text`| _Equivalent_<br/>(5317/5318)| `Flag.text`| _Equivalent_<br/>(14478/14479)| **`Flag.text`**| _Equivalent_<br/>(27504/27505)| `Flag.text`| _Equivalent_<br/>(42496/42497)| `Flag.text`
| `Flag.contained`| _Equivalent_<br/>(5319/5320)| `Flag.contained`| _Equivalent_<br/>(14480/14481)| **`Flag.contained`**| _Equivalent_<br/>(27506/27507)| `Flag.contained`| _Equivalent_<br/>(42498/42499)| `Flag.contained`
| `Flag.extension`| _Equivalent_<br/>(5321/5322)| `Flag.extension`| _Equivalent_<br/>(14482/14483)| **`Flag.extension`**| _Equivalent_<br/>(27508/27509)| `Flag.extension`| _Equivalent_<br/>(42500/42501)| `Flag.extension`
| `Flag.modifierExtension`| _Equivalent_<br/>(5323/5324)| `Flag.modifierExtension`| _Equivalent_<br/>(14484/14485)| **`Flag.modifierExtension`**| _Equivalent_<br/>(27510/27511)| `Flag.modifierExtension`| _Equivalent_<br/>(42502/42503)| `Flag.modifierExtension`
| `Flag.identifier`| _Equivalent_<br/>(5325/5326)| `Flag.identifier`| _Equivalent_<br/>(14486/14487)| **`Flag.identifier`**| _Equivalent_<br/>(27512/27513)| `Flag.identifier`| _Equivalent_<br/>(42504/42505)| `Flag.identifier`
| `Flag.status`| _Equivalent_<br/>(5329/5330)| `Flag.status`| _Equivalent_<br/>(14488/14489)| **`Flag.status`**| _Equivalent_<br/>(27514/27515)| `Flag.status`| _Equivalent_<br/>(42506/42507)| `Flag.status`
| `Flag.category`| _Equivalent_<br/>(5327/5328)| `Flag.category`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(14490)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(14491)| **`Flag.category`**| _Equivalent_<br/>(27516/27517)| `Flag.category`| _Equivalent_<br/>(42508/42509)| `Flag.category`
| `Flag.code`| _Equivalent_<br/>(5339/5340)| `Flag.code`| _Equivalent_<br/>(14492/14493)| **`Flag.code`**| _Equivalent_<br/>(27518/27519)| `Flag.code`| _Equivalent_<br/>(42510/42511)| `Flag.code`
| `Flag.subject`| →→→→ _RelatedTo_ →→→→ <br/>(5333)<hr/>←←←← _RelatedTo_ ←←←← <br/>(5334)| `Flag.subject`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(14494)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(14495)| **`Flag.subject`**| _Equivalent_<br/>(27520/27521)| `Flag.subject`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(42512)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(42513)| `Flag.subject`
| `Flag.period`| _Equivalent_<br/>(5331/5332)| `Flag.period`| _Equivalent_<br/>(14496/14497)| **`Flag.period`**| _Equivalent_<br/>(27522/27523)| `Flag.period`| _Equivalent_<br/>(42514/42515)| `Flag.period`
| `Flag.encounter`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5335)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5336)| `Flag.encounter`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(14498)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(14499)| **`Flag.encounter`**| _Equivalent_<br/>(27524/27525)| `Flag.encounter`| _Equivalent_<br/>(42516/42517)| `Flag.encounter`
| `Flag.author`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5337)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5338)| `Flag.author`| →→→→ _RelatedTo_ →→→→ <br/>(14500)<hr/>←←←← _RelatedTo_ ←←←← <br/>(14501)| **`Flag.author`**| _Equivalent_<br/>(27526/27527)| `Flag.author`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(42518)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(42519)| `Flag.author`
| *17 of 17 elements used* | | *17 of 17 elements used* | | *17 of 17 elements used* | | *17 of 17 elements used* | | *17 of 17 elements used* 

