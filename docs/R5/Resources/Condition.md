Comparison of 
Generated at Monday, April 14, 2025 6:17:49 PM

### Condition

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | Condition |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Condition` |
| Version | 5.0.0 |
| Description | A clinical condition, problem, diagnosis, or other event, situation, issue, or clinical concept that has risen to a level of concern. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2280` |
| Database Snapshot Count | `36` |
| Database Differential Count | `22` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Condition` | `Condition` | `Condition` | Condition | Detailed information about conditions, problems or diagnoses | 0..* | Condition |  |  |
| `Condition.abatement[x]` | `Condition.abatement[x]` | `abatement[x]` | Condition.abatement[x] | When in resolution/remission | 0..1 | Age, dateTime, Period, Range, string |  |  |
| `Condition.bodySite` | `Condition.bodySite` | `bodySite` | Condition.bodySite | Anatomical location, if relevant | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/body-site` |
| `Condition.category` | `Condition.category` | `category` | Condition.category | problem-list-item \| encounter-diagnosis | 0..* | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/condition-category` |
| `Condition.clinicalStatus` | `Condition.clinicalStatus` | `clinicalStatus` | Condition.clinicalStatus | active \| recurrence \| relapse \| inactive \| remission \| resolved \| unknown | 1..1 | CodeableConcept | `Required` | `http://hl7.org/fhir/ValueSet/condition-clinical|5.0.0` |
| `Condition.code` | `Condition.code` | `code` | Condition.code | Identification of the condition, problem or diagnosis | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/condition-code` |
| `Condition.contained` | `Condition.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Condition.encounter` | `Condition.encounter` | `encounter` | Condition.encounter | The Encounter during which this Condition was created | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Encounter) |  |  |
| `Condition.evidence` | `Condition.evidence` | `evidence` | Condition.evidence | Supporting evidence for the verification status | 0..* | CodeableReference(http://hl7.org/fhir/StructureDefinition/Resource) | `Example` | `http://hl7.org/fhir/ValueSet/clinical-findings` |
| `Condition.extension` | `Condition.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Condition.id` | `Condition.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Condition.identifier` | `Condition.identifier` | `identifier` | Condition.identifier | External Ids for this condition | 0..* | Identifier |  |  |
| `Condition.implicitRules` | `Condition.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Condition.language` | `Condition.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `Condition.meta` | `Condition.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Condition.modifierExtension` | `Condition.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Condition.note` | `Condition.note` | `note` | Condition.note | Additional information about the Condition | 0..* | Annotation |  |  |
| `Condition.onset[x]` | `Condition.onset[x]` | `onset[x]` | Condition.onset[x] | Estimated or actual date,  date-time, or age | 0..1 | Age, dateTime, Period, Range, string |  |  |
| `Condition.participant` | `Condition.participant` | `participant` | Condition.participant | Who or what participated in the activities related to the condition and how they were involved | 0..* | BackboneElement |  |  |
| `Condition.participant.actor` | `Condition.participant.actor` | `actor` | Condition.participant.actor | Who or what participated in the activities related to the condition | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/CareTeam), Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `Condition.participant.extension` | `Condition.participant.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Condition.participant.function` | `Condition.participant.function` | `function` | Condition.participant.function | Type of involvement | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/participation-role-type` |
| `Condition.participant.id` | `Condition.participant.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Condition.participant.modifierExtension` | `Condition.participant.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Condition.recordedDate` | `Condition.recordedDate` | `recordedDate` | Condition.recordedDate | Date condition was first recorded | 0..1 | dateTime |  |  |
| `Condition.severity` | `Condition.severity` | `severity` | Condition.severity | Subjective severity of condition | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/condition-severity` |
| `Condition.stage` | `Condition.stage` | `stage` | Condition.stage | Stage/grade, usually assessed formally | 0..* | BackboneElement |  |  |
| `Condition.stage.assessment` | `Condition.stage.assessment` | `assessment` | Condition.stage.assessment | Formal record of assessment | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/ClinicalImpression), Reference(http://hl7.org/fhir/StructureDefinition/DiagnosticReport), Reference(http://hl7.org/fhir/StructureDefinition/Observation) |  |  |
| `Condition.stage.extension` | `Condition.stage.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Condition.stage.id` | `Condition.stage.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Condition.stage.modifierExtension` | `Condition.stage.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Condition.stage.summary` | `Condition.stage.summary` | `summary` | Condition.stage.summary | Simple summary (disease specific) | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/condition-stage` |
| `Condition.stage.type` | `Condition.stage.type` | `type` | Condition.stage.type | Kind of staging | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/condition-stage-type` |
| `Condition.subject` | `Condition.subject` | `subject` | Condition.subject | Who has the condition? | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `Condition.text` | `Condition.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `Condition.verificationStatus` | `Condition.verificationStatus` | `verificationStatus` | Condition.verificationStatus | unconfirmed \| provisional \| differential \| confirmed \| refuted \| entered-in-error | 0..1 | CodeableConcept | `Required` | `http://hl7.org/fhir/ValueSet/condition-ver-status|5.0.0` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Condition](/docs/R2/Resources/Condition.md)<br/> `http://hl7.org/fhir/StructureDefinition/Condition\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `90`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `257`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Condition](/docs/R3/Resources/Condition.md)<br/> `http://hl7.org/fhir/StructureDefinition/Condition\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `439`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `635`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Condition](/docs/R4/Resources/Condition.md)<br/> `http://hl7.org/fhir/StructureDefinition/Condition\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1441`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1442`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Condition](/docs/R4B/Resources/Condition.md)<br/> `http://hl7.org/fhir/StructureDefinition/Condition\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `955`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1184`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Condition](/docs/R5/Resources/Condition.md)<br/> `http://hl7.org/fhir/StructureDefinition/Condition\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Condition from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Condition](/docs/R2/Resources/Condition.md)| Relationship | [R3 Condition](/docs/R3/Resources/Condition.md)| Relationship | [R4 Condition](/docs/R4/Resources/Condition.md)| Relationship | [R4B Condition](/docs/R4B/Resources/Condition.md)| Relationship | R5 Condition
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `Condition`| _Equivalent_<br/>(3982/3983)| `Condition`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12457)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12458)| `Condition`| _Equivalent_<br/>(24257/24258)| `Condition`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(39536)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(39537)| **`Condition`**
| `Condition.id`| _Equivalent_<br/>(3984/3985)| `Condition.id`| _Equivalent_<br/>(12459/12460)| `Condition.id`| _Equivalent_<br/>(24259/24260)| `Condition.id`| _Equivalent_<br/>(39538/39539)| **`Condition.id`**
| `Condition.meta`| _Equivalent_<br/>(3986/3987)| `Condition.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12461)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12462)| `Condition.meta`| _Equivalent_<br/>(24261/24262)| `Condition.meta`| _Equivalent_<br/>(39540/39541)| **`Condition.meta`**
| `Condition.implicitRules`| _Equivalent_<br/>(3988/3989)| `Condition.implicitRules`| _Equivalent_<br/>(12463/12464)| `Condition.implicitRules`| _Equivalent_<br/>(24263/24264)| `Condition.implicitRules`| _Equivalent_<br/>(39542/39543)| **`Condition.implicitRules`**
| `Condition.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3990)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(3991)| `Condition.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12465)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(12466)| `Condition.language`| _Equivalent_<br/>(24265/24266)| `Condition.language`| _Equivalent_<br/>(39544/39545)| **`Condition.language`**
| `Condition.text`| _Equivalent_<br/>(3992/3993)| `Condition.text`| _Equivalent_<br/>(12467/12468)| `Condition.text`| _Equivalent_<br/>(24267/24268)| `Condition.text`| _Equivalent_<br/>(39546/39547)| **`Condition.text`**
| `Condition.contained`| _Equivalent_<br/>(3994/3995)| `Condition.contained`| _Equivalent_<br/>(12469/12470)| `Condition.contained`| _Equivalent_<br/>(24269/24270)| `Condition.contained`| _Equivalent_<br/>(39548/39549)| **`Condition.contained`**
| `Condition.extension`| _Equivalent_<br/>(3996/3997)| `Condition.extension`| _Equivalent_<br/>(12471/12472)| `Condition.extension`| _Equivalent_<br/>(24271/24272)| `Condition.extension`| _Equivalent_<br/>(39550/39551)| **`Condition.extension`**
| `Condition.modifierExtension`| _Equivalent_<br/>(3998/3999)| `Condition.modifierExtension`| _Equivalent_<br/>(12473/12474)| `Condition.modifierExtension`| _Equivalent_<br/>(24273/24274)| `Condition.modifierExtension`| _Equivalent_<br/>(39552/39553)| **`Condition.modifierExtension`**
| `Condition.identifier`| _Equivalent_<br/>(4000/4001)| `Condition.identifier`| _Equivalent_<br/>(12475/12476)| `Condition.identifier`| _Equivalent_<br/>(24275/24276)| `Condition.identifier`| _Equivalent_<br/>(39554/39555)| **`Condition.identifier`**
| `Condition.clinicalStatus`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4008)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(4009)| `Condition.clinicalStatus`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12477)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12478)| `Condition.clinicalStatus`| _Equivalent_<br/>(24277/24278)| `Condition.clinicalStatus`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(39556)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(39557)| **`Condition.clinicalStatus`**
| `Condition.verificationStatus`| →→→→ _Equivalent_ →→→→ <br/>(4010)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(4011)| `Condition.verificationStatus`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(12479)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12480)| `Condition.verificationStatus`| _Equivalent_<br/>(24279/24280)| `Condition.verificationStatus`| _Equivalent_<br/>(39558/39559)| **`Condition.verificationStatus`**
| `Condition.category`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4006)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4007)| `Condition.category`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(12481)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(12482)| `Condition.category`| _Equivalent_<br/>(24281/24282)| `Condition.category`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(39560)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(39561)| **`Condition.category`**
| `Condition.severity`| _Equivalent_<br/>(4012/4013)| `Condition.severity`| _Equivalent_<br/>(12483/12484)| `Condition.severity`| _Equivalent_<br/>(24283/24284)| `Condition.severity`| _Equivalent_<br/>(39562/39563)| **`Condition.severity`**
| `Condition.code`| →→→→ _Equivalent_ →→→→ <br/>(4004)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(4005)| `Condition.code`| _Equivalent_<br/>(12485/12486)| `Condition.code`| _Equivalent_<br/>(24285/24286)| `Condition.code`| _Equivalent_<br/>(39564/39565)| **`Condition.code`**
| `Condition.bodySite`| _Equivalent_<br/>(4042/4043)| `Condition.bodySite`| _Equivalent_<br/>(12487/12488)| `Condition.bodySite`| _Equivalent_<br/>(24287/24288)| `Condition.bodySite`| _Equivalent_<br/>(39566/39567)| **`Condition.bodySite`**
| `Condition.patient`| →→→→ _RelatedTo_ →→→→ <br/>(160)<hr/>←←←← _RelatedTo_ ←←←← <br/>(579)| `Condition.subject`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12489)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12490)| `Condition.subject`| _Equivalent_<br/>(24289/24290)| `Condition.subject`| _Equivalent_<br/>(39568/39569)| **`Condition.subject`**
| `Condition.encounter`| →→→→ _RelatedTo_ →→→→ <br/>(158)<hr/>←←←← _RelatedTo_ ←←←← <br/>(577)| `Condition.context`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(907)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1418)| `Condition.encounter`| _Equivalent_<br/>(24291/24292)| `Condition.encounter`| _Equivalent_<br/>(39570/39571)| **`Condition.encounter`**
| `Condition.onset[x]`| →→→→ _RelatedTo_ →→→→ <br/>(4014)<hr/>←←←← _RelatedTo_ ←←←← <br/>(4015)| `Condition.onset[x]`| _Equivalent_<br/>(12491/12492)| `Condition.onset[x]`| _Equivalent_<br/>(24293/24294)| `Condition.onset[x]`| _Equivalent_<br/>(39572/39573)| **`Condition.onset[x]`**
| `Condition.abatement[x]`| →→→→ _RelatedTo_ →→→→ <br/>(4016)<hr/>←←←← _RelatedTo_ ←←←← <br/>(4017)| `Condition.abatement[x]`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(12493)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(12494)| `Condition.abatement[x]`| _Equivalent_<br/>(24295/24296)| `Condition.abatement[x]`| _Equivalent_<br/>(39574/39575)| **`Condition.abatement[x]`**
| `Condition.dateRecorded`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(157)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(576)| `Condition.assertedDate`| _Equivalent_<br/>(906/1419)| `Condition.recordedDate`| _Equivalent_<br/>(24297/24298)| `Condition.recordedDate`| _Equivalent_<br/>(39576/39577)| **`Condition.recordedDate`**
| | | | | | | | | **`Condition.participant`**
| | | | | | | | | **`Condition.participant.id`**
| | | | | | | | | **`Condition.participant.extension`**
| | | | | | | | | **`Condition.participant.modifierExtension`**
| | | | | | | | | **`Condition.participant.function`**
| | | | | | | | | **`Condition.participant.actor`**
| `Condition.stage`| _Equivalent_<br/>(4018/4019)| `Condition.stage`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12497)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12498)| `Condition.stage`| _Equivalent_<br/>(24303/24304)| `Condition.stage`| _Equivalent_<br/>(39580/39581)| **`Condition.stage`**
| `Condition.stage.id`| _Equivalent_<br/>(4020/4021)| `Condition.stage.id`| _Equivalent_<br/>(12499/12500)| `Condition.stage.id`| _Equivalent_<br/>(24305/24306)| `Condition.stage.id`| _Equivalent_<br/>(39582/39583)| **`Condition.stage.id`**
| `Condition.stage.extension`| _Equivalent_<br/>(4022/4023)| `Condition.stage.extension`| _Equivalent_<br/>(12501/12502)| `Condition.stage.extension`| _Equivalent_<br/>(24307/24308)| `Condition.stage.extension`| _Equivalent_<br/>(39584/39585)| **`Condition.stage.extension`**
| `Condition.stage.modifierExtension`| _Equivalent_<br/>(4024/4025)| `Condition.stage.modifierExtension`| _Equivalent_<br/>(12503/12504)| `Condition.stage.modifierExtension`| _Equivalent_<br/>(24309/24310)| `Condition.stage.modifierExtension`| _Equivalent_<br/>(39586/39587)| **`Condition.stage.modifierExtension`**
| `Condition.stage.summary`| _Equivalent_<br/>(4026/4027)| `Condition.stage.summary`| _Equivalent_<br/>(12505/12506)| `Condition.stage.summary`| _Equivalent_<br/>(24311/24312)| `Condition.stage.summary`| _Equivalent_<br/>(39588/39589)| **`Condition.stage.summary`**
| `Condition.stage.assessment`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4028)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4029)| `Condition.stage.assessment`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12507)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12508)| `Condition.stage.assessment`| _Equivalent_<br/>(24313/24314)| `Condition.stage.assessment`| _Equivalent_<br/>(39590/39591)| **`Condition.stage.assessment`**
| | | | | `Condition.stage.type`| _Equivalent_<br/>(24315/24316)| `Condition.stage.type`| _Equivalent_<br/>(39592/39593)| **`Condition.stage.type`**
| `Condition.evidence`| _Equivalent_<br/>(4030/4031)| `Condition.evidence`| _Equivalent_<br/>(12509/12510)| `Condition.evidence`| _Equivalent_<br/>(24317/24318)| `Condition.evidence`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(39594)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(39595)| **`Condition.evidence`**
| `Condition.notes`| →→→→ _RelatedTo_ →→→→ <br/>(159)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(578)| `Condition.note`| _Equivalent_<br/>(12521/12522)| `Condition.note`| _Equivalent_<br/>(24329/24330)| `Condition.note`| _Equivalent_<br/>(39601/39602)| **`Condition.note`**
| *29 of 35 elements used* <br/>remaining elements:<br/>`Condition.asserter`, `Condition.evidence.code`, `Condition.evidence.detail`, `Condition.evidence.extension`, `Condition.evidence.id`, `Condition.evidence.modifierExtension`| | *29 of 35 elements used* <br/>remaining elements:<br/>`Condition.asserter`, `Condition.evidence.code`, `Condition.evidence.detail`, `Condition.evidence.extension`, `Condition.evidence.id`, `Condition.evidence.modifierExtension`| | *30 of 37 elements used* <br/>remaining elements:<br/>`Condition.asserter`, `Condition.evidence.code`, `Condition.evidence.detail`, `Condition.evidence.extension`, `Condition.evidence.id`, `Condition.evidence.modifierExtension`, `Condition.recorder`| | *30 of 37 elements used* <br/>remaining elements:<br/>`Condition.asserter`, `Condition.evidence.code`, `Condition.evidence.detail`, `Condition.evidence.extension`, `Condition.evidence.id`, `Condition.evidence.modifierExtension`, `Condition.recorder`| | *36 of 36 elements used* 

