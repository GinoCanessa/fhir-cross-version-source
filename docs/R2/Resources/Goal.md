Comparison of 
Generated at Tuesday, April 1, 2025 1:39:08 PM

### Goal

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | Goal |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Goal` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for Goal Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `83` |
| Database Snapshot Count | `27` |
| Database Differential Count | `16` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Goal` | `Goal` | `Goal` | Goal | Describes the intended objective(s) for a patient, group or organization | 0..* | Goal |  |  |
| `Goal.addresses` | `Goal.addresses` | `addresses` |  | Issues addressed by this goal | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Condition), Reference(http://hl7.org/fhir/StructureDefinition/MedicationStatement), Reference(http://hl7.org/fhir/StructureDefinition/NutritionOrder), Reference(http://hl7.org/fhir/StructureDefinition/Observation), Reference(http://hl7.org/fhir/StructureDefinition/ProcedureRequest), Reference(http://hl7.org/fhir/StructureDefinition/RiskAssessment) |  |  |
| `Goal.author` | `Goal.author` | `author` |  | Who's responsible for creating Goal? | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `Goal.category` | `Goal.category` | `category` |  | E.g. Treatment, dietary, behavioral, etc. | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/goal-category` |
| `Goal.contained` | `Goal.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Goal.description` | `Goal.description` | `description` |  | What's the desired outcome? | 1..1 | string |  |  |
| `Goal.extension` | `Goal.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Goal.id` | `Goal.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Goal.identifier` | `Goal.identifier` | `identifier` |  | External Ids for this goal | 0..* | Identifier |  |  |
| `Goal.implicitRules` | `Goal.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Goal.language` | `Goal.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `Goal.meta` | `Goal.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Goal.modifierExtension` | `Goal.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Goal.note` | `Goal.note` | `note` |  | Comments about the goal | 0..* | Annotation |  |  |
| `Goal.outcome` | `Goal.outcome` | `outcome` |  | What was end result of goal? | 0..* | BackboneElement |  |  |
| `Goal.outcome.extension` | `Goal.outcome.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Goal.outcome.id` | `Goal.outcome.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Goal.outcome.modifierExtension` | `Goal.outcome.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Goal.outcome.result[x]` | `Goal.outcome.result[x]` | `result[x]` |  | Code or observation that resulted from goal | 0..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/Observation) | `Example` |  |
| `Goal.priority` | `Goal.priority` | `priority` |  | high \| medium \|low | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/goal-priority` |
| `Goal.start[x]` | `Goal.start[x]` | `start[x]` |  | When goal pursuit begins | 0..1 | CodeableConcept, date | `Example` | `http://hl7.org/fhir/ValueSet/goal-start-event` |
| `Goal.status` | `Goal.status` | `status` |  | proposed \| planned \| accepted \| rejected \| in-progress \| achieved \| sustaining \| on-hold \| cancelled | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/goal-status` |
| `Goal.statusDate` | `Goal.statusDate` | `statusDate` |  | When goal status took effect | 0..1 | date |  |  |
| `Goal.statusReason` | `Goal.statusReason` | `statusReason` |  | Reason for current status | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/goal-status-reason` |
| `Goal.subject` | `Goal.subject` | `subject` |  | Who this goal is intended for | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `Goal.target[x]` | `Goal.target[x]` | `target[x]` |  | Reach goal on or before | 0..1 | date, Quantity[http://hl7.org/fhir/StructureDefinition/Duration] |  |  |
| `Goal.text` | `Goal.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Goal](/docs/R2/Resources/Goal.md)<br/> `http://hl7.org/fhir/StructureDefinition/Goal\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `113`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`RelatedTo`<br/>- DBKey: `279`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Goal](/docs/R3/Resources/Goal.md)<br/> `http://hl7.org/fhir/StructureDefinition/Goal\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `463`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `657`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Goal](/docs/R4/Resources/Goal.md)<br/> `http://hl7.org/fhir/StructureDefinition/Goal\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1497`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1498`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Goal](/docs/R4B/Resources/Goal.md)<br/> `http://hl7.org/fhir/StructureDefinition/Goal\|4.3.0` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `982`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1211`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Goal](/docs/R5/Resources/Goal.md)<br/> `http://hl7.org/fhir/StructureDefinition/Goal\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Goal from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 Goal| Relationship | [R3 Goal](/docs/R3/Resources/Goal.md)| Relationship | [R4 Goal](/docs/R4/Resources/Goal.md)| Relationship | [R4B Goal](/docs/R4B/Resources/Goal.md)| Relationship | [R5 Goal](/docs/R5/Resources/Goal.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`Goal`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5341)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5342)| `Goal`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(14506)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(14507)| `Goal`| _Equivalent_<br/>(27528/27529)| `Goal`| _Equivalent_<br/>(42520/42521)| `Goal`
| **`Goal.id`**| _Equivalent_<br/>(5343/5344)| `Goal.id`| _Equivalent_<br/>(14508/14509)| `Goal.id`| _Equivalent_<br/>(27530/27531)| `Goal.id`| _Equivalent_<br/>(42522/42523)| `Goal.id`
| **`Goal.meta`**| _Equivalent_<br/>(5345/5346)| `Goal.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(14510)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(14511)| `Goal.meta`| _Equivalent_<br/>(27532/27533)| `Goal.meta`| _Equivalent_<br/>(42524/42525)| `Goal.meta`
| **`Goal.implicitRules`**| _Equivalent_<br/>(5347/5348)| `Goal.implicitRules`| _Equivalent_<br/>(14512/14513)| `Goal.implicitRules`| _Equivalent_<br/>(27534/27535)| `Goal.implicitRules`| _Equivalent_<br/>(42526/42527)| `Goal.implicitRules`
| **`Goal.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5349)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(5350)| `Goal.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(14514)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(14515)| `Goal.language`| _Equivalent_<br/>(27536/27537)| `Goal.language`| _Equivalent_<br/>(42528/42529)| `Goal.language`
| **`Goal.text`**| _Equivalent_<br/>(5351/5352)| `Goal.text`| _Equivalent_<br/>(14516/14517)| `Goal.text`| _Equivalent_<br/>(27538/27539)| `Goal.text`| _Equivalent_<br/>(42530/42531)| `Goal.text`
| **`Goal.contained`**| _Equivalent_<br/>(5353/5354)| `Goal.contained`| _Equivalent_<br/>(14518/14519)| `Goal.contained`| _Equivalent_<br/>(27540/27541)| `Goal.contained`| _Equivalent_<br/>(42532/42533)| `Goal.contained`
| **`Goal.extension`**| _Equivalent_<br/>(5355/5356)| `Goal.extension`| _Equivalent_<br/>(14520/14521)| `Goal.extension`| _Equivalent_<br/>(27542/27543)| `Goal.extension`| _Equivalent_<br/>(42534/42535)| `Goal.extension`
| **`Goal.modifierExtension`**| _Equivalent_<br/>(5357/5358)| `Goal.modifierExtension`| _Equivalent_<br/>(14522/14523)| `Goal.modifierExtension`| _Equivalent_<br/>(27544/27545)| `Goal.modifierExtension`| _Equivalent_<br/>(42536/42537)| `Goal.modifierExtension`
| **`Goal.identifier`**| _Equivalent_<br/>(5359/5360)| `Goal.identifier`| _Equivalent_<br/>(14524/14525)| `Goal.identifier`| _Equivalent_<br/>(27546/27547)| `Goal.identifier`| _Equivalent_<br/>(42538/42539)| `Goal.identifier`
| **`Goal.subject`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5361)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5362)| `Goal.subject`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(14532)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(14533)| `Goal.subject`| _Equivalent_<br/>(27558/27559)| `Goal.subject`| _Equivalent_<br/>(42550/42551)| `Goal.subject`
| **`Goal.start[x]`**| _Equivalent_<br/>(5363/5364)| `Goal.start[x]`| _Equivalent_<br/>(14534/14535)| `Goal.start[x]`| _Equivalent_<br/>(27560/27561)| `Goal.start[x]`| _Equivalent_<br/>(42552/42553)| `Goal.start[x]`
| **`Goal.target[x]`**| →→→→ _RelatedTo_ →→→→ <br/>(242)<hr/>←←←← _RelatedTo_ ←←←← <br/>(628)| `Goal.target`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(14536)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(14537)| `Goal.target`| _Equivalent_<br/>(27562/27563)| `Goal.target`| _Equivalent_<br/>(42554/42555)| `Goal.target`
| **`Goal.target[x]`**| →→→→ _RelatedTo_ →→→→ <br/>(242)<hr/>←←←← _RelatedTo_ ←←←← <br/>(628)| `Goal.target.detail[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(14546)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(14547)| `Goal.target.detail[x]`| _Equivalent_<br/>(27572/27573)| `Goal.target.detail[x]`| _Equivalent_<br/>(42564/42565)| `Goal.target.detail[x]`
| **`Goal.target[x]`**| →→→→ _RelatedTo_ →→→→ <br/>(242)<hr/>←←←← _RelatedTo_ ←←←← <br/>(628)| `Goal.target.due[x]`| _Equivalent_<br/>(14548/14549)| `Goal.target.due[x]`| _Equivalent_<br/>(27574/27575)| `Goal.target.due[x]`| _Equivalent_<br/>(42566/42567)| `Goal.target.due[x]`
| **`Goal.category`**| _Equivalent_<br/>(5365/5366)| `Goal.category`| _Equivalent_<br/>(14526/14527)| `Goal.category`| _Equivalent_<br/>(27552/27553)| `Goal.category`| _Equivalent_<br/>(42544/42545)| `Goal.category`
| **`Goal.description`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(5367)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(5368)| `Goal.description`| _Equivalent_<br/>(14530/14531)| `Goal.description`| _Equivalent_<br/>(27556/27557)| `Goal.description`| _Equivalent_<br/>(42548/42549)| `Goal.description`
| **`Goal.status`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5369)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5370)| `Goal.status`| →→→→ _RelatedTo_ →→→→ <br/>(1082)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1532)| `Goal.lifecycleStatus`| _Equivalent_<br/>(27548/27549)| `Goal.lifecycleStatus`| _Equivalent_<br/>(42540/42541)| `Goal.lifecycleStatus`
| **`Goal.status`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5369)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5370)| `Goal.status`| →→→→ _RelatedTo_ →→→→ <br/>(1082)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1532)| `Goal.achievementStatus`| _Equivalent_<br/>(27550/27551)| `Goal.achievementStatus`| _Equivalent_<br/>(42542/42543)| `Goal.achievementStatus`
| **`Goal.statusDate`**| _Equivalent_<br/>(5371/5372)| `Goal.statusDate`| _Equivalent_<br/>(14550/14551)| `Goal.statusDate`| _Equivalent_<br/>(27576/27577)| `Goal.statusDate`| _Equivalent_<br/>(42568/42569)| `Goal.statusDate`
| **`Goal.statusReason`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5373)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5374)| `Goal.statusReason`| _Equivalent_<br/>(14552/14553)| `Goal.statusReason`| _Equivalent_<br/>(27578/27579)| `Goal.statusReason`| _Equivalent_<br/>(42570/42571)| `Goal.statusReason`
| **`Goal.author`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(237)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(623)| `Goal.expressedBy`| →→→→ _RelatedTo_ →→→→ <br/>(14554)<hr/>←←←← _RelatedTo_ ←←←← <br/>(14555)| `Goal.expressedBy`| _Equivalent_<br/>(27580/27581)| `Goal.expressedBy`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1795)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2039)| `Goal.source`
| **`Goal.priority`**| _Equivalent_<br/>(5375/5376)| `Goal.priority`| _Equivalent_<br/>(14528/14529)| `Goal.priority`| _Equivalent_<br/>(27554/27555)| `Goal.priority`| _Equivalent_<br/>(42546/42547)| `Goal.priority`
| **`Goal.addresses`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5377)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5378)| `Goal.addresses`| →→→→ _RelatedTo_ →→→→ <br/>(14556)<hr/>←←←← _RelatedTo_ ←←←← <br/>(14557)| `Goal.addresses`| _Equivalent_<br/>(27582/27583)| `Goal.addresses`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(42572)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(42573)| `Goal.addresses`
| **`Goal.note`**| _Equivalent_<br/>(5379/5380)| `Goal.note`| _Equivalent_<br/>(14558/14559)| `Goal.note`| _Equivalent_<br/>(27584/27585)| `Goal.note`| _Equivalent_<br/>(42574/42575)| `Goal.note`
| **`Goal.outcome`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(238)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(622)| `Goal`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(14506)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(14507)| `Goal`| _Equivalent_<br/>(27528/27529)| `Goal`| _Equivalent_<br/>(42520/42521)| `Goal`
| **`Goal.outcome.id`**| | | | | | | | | 
| **`Goal.outcome.extension`**| | | | | | | | | 
| **`Goal.outcome.modifierExtension`**| | | | | | | | | 
| **`Goal.outcome.result[x]`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(240)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(625)| `Goal.outcomeCode`| _Equivalent_<br/>(14560/14561)| `Goal.outcomeCode`| _Equivalent_<br/>(27586/27587)| `Goal.outcomeCode`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1796)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2040)| `Goal.outcome`
| **`Goal.outcome.result[x]`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(240)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(625)| `Goal.outcomeReference`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(14562)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(14563)| `Goal.outcomeReference`| _Equivalent_<br/>(27588/27589)| `Goal.outcomeReference`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1797)<hr/>←←←← _RelatedTo_ ←←←← <br/>(2041)| `Goal.outcome`
| *27 of 27 elements used* | | *26 of 30 elements used* | | *27 of 31 elements used* | | *27 of 31 elements used* | | *26 of 31 elements used* 

