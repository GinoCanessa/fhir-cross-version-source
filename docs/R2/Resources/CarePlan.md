Comparison of 
Generated at Friday, April 4, 2025 2:58:33 PM

### CarePlan

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | CarePlan |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/CarePlan` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for CarePlan Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `50` |
| Database Snapshot Count | `60` |
| Database Differential Count | `40` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `CarePlan` | `CarePlan` | `CarePlan` | CarePlan | Healthcare plan for patient or group | 0..* | CarePlan |  |  |
| `CarePlan.activity` | `CarePlan.activity` | `activity` |  | Action to occur as part of plan | 0..* | BackboneElement |  |  |
| `CarePlan.activity.actionResulting` | `CarePlan.activity.actionResulting` | `actionResulting` |  | Appointments, orders, etc. | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `CarePlan.activity.detail` | `CarePlan.activity.detail` | `detail` |  | In-line definition of activity | 0..1 | BackboneElement |  |  |
| `CarePlan.activity.detail.category` | `CarePlan.activity.detail.category` | `category` |  | diet \| drug \| encounter \| observation \| procedure \| supply \| other | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/care-plan-activity-category` |
| `CarePlan.activity.detail.code` | `CarePlan.activity.detail.code` | `code` |  | Detail type of activity | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/care-plan-activity` |
| `CarePlan.activity.detail.dailyAmount` | `CarePlan.activity.detail.dailyAmount` | `dailyAmount` |  | How to consume/day? | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
| `CarePlan.activity.detail.description` | `CarePlan.activity.detail.description` | `description` |  | Extra info describing activity to perform | 0..1 | string |  |  |
| `CarePlan.activity.detail.extension` | `CarePlan.activity.detail.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `CarePlan.activity.detail.goal` | `CarePlan.activity.detail.goal` | `goal` |  | Goals this activity relates to | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Goal) |  |  |
| `CarePlan.activity.detail.id` | `CarePlan.activity.detail.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `CarePlan.activity.detail.location` | `CarePlan.activity.detail.location` | `location` |  | Where it should happen | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Location) |  |  |
| `CarePlan.activity.detail.modifierExtension` | `CarePlan.activity.detail.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `CarePlan.activity.detail.performer` | `CarePlan.activity.detail.performer` | `performer` |  | Who will be responsible? | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `CarePlan.activity.detail.product[x]` | `CarePlan.activity.detail.product[x]` | `product[x]` |  | What is to be administered/supplied | 0..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/Medication), Reference(http://hl7.org/fhir/StructureDefinition/Substance) | `Example` | `http://hl7.org/fhir/ValueSet/medication-codes` |
| `CarePlan.activity.detail.prohibited` | `CarePlan.activity.detail.prohibited` | `prohibited` |  | Do NOT do | 1..1 | boolean |  |  |
| `CarePlan.activity.detail.quantity` | `CarePlan.activity.detail.quantity` | `quantity` |  | How much to administer/supply/consume | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
| `CarePlan.activity.detail.reasonCode` | `CarePlan.activity.detail.reasonCode` | `reasonCode` |  | Why activity should be done | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/activity-reason` |
| `CarePlan.activity.detail.reasonReference` | `CarePlan.activity.detail.reasonReference` | `reasonReference` |  | Condition triggering need for activity | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Condition) |  |  |
| `CarePlan.activity.detail.scheduled[x]` | `CarePlan.activity.detail.scheduled[x]` | `scheduled[x]` |  | When activity is to occur | 0..1 | Period, string, Timing |  |  |
| `CarePlan.activity.detail.status` | `CarePlan.activity.detail.status` | `status` |  | not-started \| scheduled \| in-progress \| on-hold \| completed \| cancelled | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/care-plan-activity-status` |
| `CarePlan.activity.detail.statusReason` | `CarePlan.activity.detail.statusReason` | `statusReason` |  | Reason for current status | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/goal-status-reason` |
| `CarePlan.activity.extension` | `CarePlan.activity.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `CarePlan.activity.id` | `CarePlan.activity.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `CarePlan.activity.modifierExtension` | `CarePlan.activity.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `CarePlan.activity.progress` | `CarePlan.activity.progress` | `progress` |  | Comments about the activity status/progress | 0..* | Annotation |  |  |
| `CarePlan.activity.reference` | `CarePlan.activity.reference` | `reference` |  | Activity details defined in specific resource | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Appointment), Reference(http://hl7.org/fhir/StructureDefinition/CommunicationRequest), Reference(http://hl7.org/fhir/StructureDefinition/DeviceUseRequest), Reference(http://hl7.org/fhir/StructureDefinition/DiagnosticOrder), Reference(http://hl7.org/fhir/StructureDefinition/MedicationOrder), Reference(http://hl7.org/fhir/StructureDefinition/NutritionOrder), Reference(http://hl7.org/fhir/StructureDefinition/Order), Reference(http://hl7.org/fhir/StructureDefinition/ProcedureRequest), Reference(http://hl7.org/fhir/StructureDefinition/ProcessRequest), Reference(http://hl7.org/fhir/StructureDefinition/ReferralRequest), Reference(http://hl7.org/fhir/StructureDefinition/SupplyRequest), Reference(http://hl7.org/fhir/StructureDefinition/VisionPrescription) |  |  |
| `CarePlan.addresses` | `CarePlan.addresses` | `addresses` |  | Health issues this plan addresses | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Condition) |  |  |
| `CarePlan.author` | `CarePlan.author` | `author` |  | Who is responsible for contents of the plan | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `CarePlan.category` | `CarePlan.category` | `category` |  | Type of plan | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/care-plan-category` |
| `CarePlan.contained` | `CarePlan.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `CarePlan.context` | `CarePlan.context` | `context` |  | Created in context of | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Encounter), Reference(http://hl7.org/fhir/StructureDefinition/EpisodeOfCare) |  |  |
| `CarePlan.description` | `CarePlan.description` | `description` |  | Summary of nature of plan | 0..1 | string |  |  |
| `CarePlan.extension` | `CarePlan.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `CarePlan.goal` | `CarePlan.goal` | `goal` |  | Desired outcome of plan | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Goal) |  |  |
| `CarePlan.id` | `CarePlan.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `CarePlan.identifier` | `CarePlan.identifier` | `identifier` |  | External Ids for this plan | 0..* | Identifier |  |  |
| `CarePlan.implicitRules` | `CarePlan.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `CarePlan.language` | `CarePlan.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `CarePlan.meta` | `CarePlan.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `CarePlan.modified` | `CarePlan.modified` | `modified` |  | When last updated | 0..1 | dateTime |  |  |
| `CarePlan.modifierExtension` | `CarePlan.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `CarePlan.note` | `CarePlan.note` | `note` |  | Comments about the plan | 0..1 | Annotation |  |  |
| `CarePlan.participant` | `CarePlan.participant` | `participant` |  | Who's involved in plan? | 0..* | BackboneElement |  |  |
| `CarePlan.participant.extension` | `CarePlan.participant.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `CarePlan.participant.id` | `CarePlan.participant.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `CarePlan.participant.member` | `CarePlan.participant.member` | `member` |  | Who is involved | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `CarePlan.participant.modifierExtension` | `CarePlan.participant.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `CarePlan.participant.role` | `CarePlan.participant.role` | `role` |  | Type of involvement | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/participant-role` |
| `CarePlan.period` | `CarePlan.period` | `period` |  | Time period plan covers | 0..1 | Period |  |  |
| `CarePlan.relatedPlan` | `CarePlan.relatedPlan` | `relatedPlan` |  | Plans related to this one | 0..* | BackboneElement |  |  |
| `CarePlan.relatedPlan.code` | `CarePlan.relatedPlan.code` | `code` |  | includes \| replaces \| fulfills | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/care-plan-relationship` |
| `CarePlan.relatedPlan.extension` | `CarePlan.relatedPlan.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `CarePlan.relatedPlan.id` | `CarePlan.relatedPlan.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `CarePlan.relatedPlan.modifierExtension` | `CarePlan.relatedPlan.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `CarePlan.relatedPlan.plan` | `CarePlan.relatedPlan.plan` | `plan` |  | Plan relationship exists with | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/CarePlan) |  |  |
| `CarePlan.status` | `CarePlan.status` | `status` |  | proposed \| draft \| active \| completed \| cancelled | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/care-plan-status` |
| `CarePlan.subject` | `CarePlan.subject` | `subject` |  | Who care plan is for | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `CarePlan.support` | `CarePlan.support` | `support` |  | Information considered as part of plan | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `CarePlan.text` | `CarePlan.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [CarePlan](/docs/R2/Resources/CarePlan.md)<br/> `http://hl7.org/fhir/StructureDefinition/CarePlan\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `82`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `248`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CarePlan](/docs/R3/Resources/CarePlan.md)<br/> `http://hl7.org/fhir/StructureDefinition/CarePlan\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `427`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `623`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CarePlan](/docs/R4/Resources/CarePlan.md)<br/> `http://hl7.org/fhir/StructureDefinition/CarePlan\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1413`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1414`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CarePlan](/docs/R4B/Resources/CarePlan.md)<br/> `http://hl7.org/fhir/StructureDefinition/CarePlan\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `940`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1169`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CarePlan](/docs/R5/Resources/CarePlan.md)<br/> `http://hl7.org/fhir/StructureDefinition/CarePlan\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition CarePlan from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 CarePlan| Relationship | [R3 CarePlan](/docs/R3/Resources/CarePlan.md)| Relationship | [R4 CarePlan](/docs/R4/Resources/CarePlan.md)| Relationship | [R4B CarePlan](/docs/R4B/Resources/CarePlan.md)| Relationship | [R5 CarePlan](/docs/R5/Resources/CarePlan.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`CarePlan`**| →→→→ _Equivalent_ →→→→ <br/>(10959)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(508)| `CarePlan`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10962)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10963)| `CarePlan`| _Equivalent_<br/>(22530/22531)| `CarePlan`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(37549)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(37550)| `CarePlan`
| **`CarePlan`**| →→→→ _Equivalent_ →→→→ <br/>(10959)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(508)| `CarePlan.careTeam`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11004)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11005)| `CarePlan.careTeam`| _Equivalent_<br/>(22582/22583)| `CarePlan.careTeam`| _Equivalent_<br/>(37599/37600)| `CarePlan.careTeam`
| **`CarePlan.id`**| _Equivalent_<br/>(3280/3281)| `CarePlan.id`| _Equivalent_<br/>(10964/10965)| `CarePlan.id`| _Equivalent_<br/>(22532/22533)| `CarePlan.id`| _Equivalent_<br/>(37551/37552)| `CarePlan.id`
| **`CarePlan.meta`**| _Equivalent_<br/>(3282/3283)| `CarePlan.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10966)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10967)| `CarePlan.meta`| _Equivalent_<br/>(22534/22535)| `CarePlan.meta`| _Equivalent_<br/>(37553/37554)| `CarePlan.meta`
| **`CarePlan.implicitRules`**| _Equivalent_<br/>(3284/3285)| `CarePlan.implicitRules`| _Equivalent_<br/>(10968/10969)| `CarePlan.implicitRules`| _Equivalent_<br/>(22536/22537)| `CarePlan.implicitRules`| _Equivalent_<br/>(37555/37556)| `CarePlan.implicitRules`
| **`CarePlan.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3286)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(3287)| `CarePlan.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10970)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(10971)| `CarePlan.language`| _Equivalent_<br/>(22538/22539)| `CarePlan.language`| _Equivalent_<br/>(37557/37558)| `CarePlan.language`
| **`CarePlan.text`**| _Equivalent_<br/>(3288/3289)| `CarePlan.text`| _Equivalent_<br/>(10972/10973)| `CarePlan.text`| _Equivalent_<br/>(22540/22541)| `CarePlan.text`| _Equivalent_<br/>(37559/37560)| `CarePlan.text`
| **`CarePlan.contained`**| _Equivalent_<br/>(3290/3291)| `CarePlan.contained`| _Equivalent_<br/>(10974/10975)| `CarePlan.contained`| _Equivalent_<br/>(22542/22543)| `CarePlan.contained`| _Equivalent_<br/>(37561/37562)| `CarePlan.contained`
| **`CarePlan.extension`**| →→→→ _Equivalent_ →→→→ <br/>(3292)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3293)| `CarePlan.extension`| _Equivalent_<br/>(10976/10977)| `CarePlan.extension`| _Equivalent_<br/>(22544/22545)| `CarePlan.extension`| _Equivalent_<br/>(37563/37564)| `CarePlan.extension`
| **`CarePlan.modifierExtension`**| _Equivalent_<br/>(3294/3295)| `CarePlan.modifierExtension`| _Equivalent_<br/>(10978/10979)| `CarePlan.modifierExtension`| _Equivalent_<br/>(22546/22547)| `CarePlan.modifierExtension`| _Equivalent_<br/>(37565/37566)| `CarePlan.modifierExtension`
| **`CarePlan.identifier`**| _Equivalent_<br/>(3296/3297)| `CarePlan.identifier`| _Equivalent_<br/>(10980/10981)| `CarePlan.identifier`| _Equivalent_<br/>(22548/22549)| `CarePlan.identifier`| _Equivalent_<br/>(37567/37568)| `CarePlan.identifier`
| **`CarePlan.subject`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3298)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3299)| `CarePlan.subject`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10998)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10999)| `CarePlan.subject`| _Equivalent_<br/>(22570/22571)| `CarePlan.subject`| _Equivalent_<br/>(37589/37590)| `CarePlan.subject`
| **`CarePlan.status`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3300)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3301)| `CarePlan.status`| _Equivalent_<br/>(10988/10989)| `CarePlan.status`| _Equivalent_<br/>(22560/22561)| `CarePlan.status`| _Equivalent_<br/>(37579/37580)| `CarePlan.status`
| **`CarePlan.context`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3302)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3303)| `CarePlan.context`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(842)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1368)| `CarePlan.encounter`| _Equivalent_<br/>(22572/22573)| `CarePlan.encounter`| _Equivalent_<br/>(37591/37592)| `CarePlan.encounter`
| **`CarePlan.period`**| _Equivalent_<br/>(3304/3305)| `CarePlan.period`| _Equivalent_<br/>(11000/11001)| `CarePlan.period`| _Equivalent_<br/>(22574/22575)| `CarePlan.period`| _Equivalent_<br/>(37593/37594)| `CarePlan.period`
| **`CarePlan.author`**| →→→→ _RelatedTo_ →→→→ <br/>(3306)<hr/>←←←← _RelatedTo_ ←←←← <br/>(3307)| `CarePlan.author`| →→→→ _RelatedTo_ →→→→ <br/>(11002)<hr/>←←←← _RelatedTo_ ←←←← <br/>(11003)| `CarePlan.author`| _Equivalent_<br/>(22578/22579)| `CarePlan.author`| _Equivalent_<br/>(1729/1973)| `CarePlan.custodian`
| **`CarePlan.modified`**| →→→→ _Equivalent_ →→→→ <br/>(10952)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(507)| `base64Binary`| | | | | | | 
| **`CarePlan.modified`**| →→→→ _Equivalent_ →→→→ <br/>(10952)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(507)| `CarePlan.extension`| _Equivalent_<br/>(10976/10977)| `CarePlan.extension`| _Equivalent_<br/>(22544/22545)| `CarePlan.extension`| _Equivalent_<br/>(37563/37564)| `CarePlan.extension`
| **`CarePlan.category`**| _Equivalent_<br/>(3308/3309)| `CarePlan.category`| _Equivalent_<br/>(10992/10993)| `CarePlan.category`| _Equivalent_<br/>(22564/22565)| `CarePlan.category`| _Equivalent_<br/>(37583/37584)| `CarePlan.category`
| **`CarePlan.description`**| _Equivalent_<br/>(3310/3311)| `CarePlan.description`| _Equivalent_<br/>(10996/10997)| `CarePlan.description`| _Equivalent_<br/>(22568/22569)| `CarePlan.description`| _Equivalent_<br/>(37587/37588)| `CarePlan.description`
| **`CarePlan.addresses`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3312)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3313)| `CarePlan.addresses`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11006)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11007)| `CarePlan.addresses`| _Equivalent_<br/>(22584/22585)| `CarePlan.addresses`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(37601)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(37602)| `CarePlan.addresses`
| **`CarePlan.support`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(55)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(506)| `CarePlan.supportingInfo`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11008)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11009)| `CarePlan.supportingInfo`| _Equivalent_<br/>(22586/22587)| `CarePlan.supportingInfo`| _Equivalent_<br/>(37603/37604)| `CarePlan.supportingInfo`
| **`CarePlan.relatedPlan`**| | | | | | | | | 
| **`CarePlan.relatedPlan.id`**| | | | | | | | | 
| **`CarePlan.relatedPlan.extension`**| | | | | | | | | 
| **`CarePlan.relatedPlan.modifierExtension`**| | | | | | | | | 
| **`CarePlan.relatedPlan.code`**| | | | | | | | | 
| **`CarePlan.relatedPlan.plan`**| | | | | | | | | 
| **`CarePlan.participant`**| | | | | | | | | 
| **`CarePlan.participant.id`**| | | | | | | | | 
| **`CarePlan.participant.extension`**| | | | | | | | | 
| **`CarePlan.participant.modifierExtension`**| | | | | | | | | 
| **`CarePlan.participant.role`**| | | | | | | | | 
| **`CarePlan.participant.member`**| | | | | | | | | 
| **`CarePlan.goal`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3322)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3323)| `CarePlan.goal`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11010)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11011)| `CarePlan.goal`| _Equivalent_<br/>(22588/22589)| `CarePlan.goal`| _Equivalent_<br/>(37605/37606)| `CarePlan.goal`
| **`CarePlan.activity`**| _Equivalent_<br/>(3324/3325)| `CarePlan.activity`| _Equivalent_<br/>(11012/11013)| `CarePlan.activity`| _Equivalent_<br/>(22590/22591)| `CarePlan.activity`| _Equivalent_<br/>(37607/37608)| `CarePlan.activity`
| **`CarePlan.activity.id`**| _Equivalent_<br/>(3326/3327)| `CarePlan.activity.id`| _Equivalent_<br/>(11014/11015)| `CarePlan.activity.id`| _Equivalent_<br/>(22592/22593)| `CarePlan.activity.id`| _Equivalent_<br/>(37609/37610)| `CarePlan.activity.id`
| **`CarePlan.activity.extension`**| _Equivalent_<br/>(3328/3329)| `CarePlan.activity.extension`| _Equivalent_<br/>(11016/11017)| `CarePlan.activity.extension`| _Equivalent_<br/>(22594/22595)| `CarePlan.activity.extension`| _Equivalent_<br/>(37611/37612)| `CarePlan.activity.extension`
| **`CarePlan.activity.modifierExtension`**| _Equivalent_<br/>(3330/3331)| `CarePlan.activity.modifierExtension`| _Equivalent_<br/>(11018/11019)| `CarePlan.activity.modifierExtension`| _Equivalent_<br/>(22596/22597)| `CarePlan.activity.modifierExtension`| _Equivalent_<br/>(37613/37614)| `CarePlan.activity.modifierExtension`
| **`CarePlan.activity.actionResulting`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(49)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(505)| `CarePlan.activity.outcomeReference`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11022)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11023)| `CarePlan.activity.outcomeReference`| _Equivalent_<br/>(22600/22601)| `CarePlan.activity.outcomeReference`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1732)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1976)| `CarePlan.activity.performedActivity`
| **`CarePlan.activity.progress`**| _Equivalent_<br/>(3332/3333)| `CarePlan.activity.progress`| _Equivalent_<br/>(11024/11025)| `CarePlan.activity.progress`| _Equivalent_<br/>(22602/22603)| `CarePlan.activity.progress`| _Equivalent_<br/>(37615/37616)| `CarePlan.activity.progress`
| **`CarePlan.activity.reference`**| →→→→ _RelatedTo_ →→→→ <br/>(3334)<hr/>←←←← _RelatedTo_ ←←←← <br/>(3335)| `CarePlan.activity.reference`| →→→→ _RelatedTo_ →→→→ <br/>(11026)<hr/>←←←← _RelatedTo_ ←←←← <br/>(11027)| `CarePlan.activity.reference`| _Equivalent_<br/>(22604/22605)| `CarePlan.activity.reference`| →→→→ _RelatedTo_ →→→→ <br/>(1730)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1974)| `CarePlan.activity.plannedActivityReference`
| **`CarePlan.activity.detail`**| _Equivalent_<br/>(3336/3337)| `CarePlan.activity.detail`| _Equivalent_<br/>(11028/11029)| `CarePlan.activity.detail`| _Equivalent_<br/>(22606/22607)| `CarePlan.activity.detail`| | | 
| **`CarePlan.activity.detail.id`**| _Equivalent_<br/>(3338/3339)| `CarePlan.activity.detail.id`| _Equivalent_<br/>(11030/11031)| `CarePlan.activity.detail.id`| _Equivalent_<br/>(22608/22609)| `CarePlan.activity.detail.id`| | | 
| **`CarePlan.activity.detail.extension`**| _Equivalent_<br/>(3340/3341)| `CarePlan.activity.detail.extension`| →→→→ _Equivalent_ →→→→ <br/>(11032)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11033)| `CarePlan.activity.detail.extension`| _Equivalent_<br/>(22610/22611)| `CarePlan.activity.detail.extension`| | | 
| **`CarePlan.activity.detail.modifierExtension`**| _Equivalent_<br/>(3342/3343)| `CarePlan.activity.detail.modifierExtension`| _Equivalent_<br/>(11034/11035)| `CarePlan.activity.detail.modifierExtension`| _Equivalent_<br/>(22612/22613)| `CarePlan.activity.detail.modifierExtension`| | | 
| **`CarePlan.activity.detail.category`**| _Equivalent_<br/>(3344/3345)| `CarePlan.activity.detail.category`| →→→→ _RelatedTo_ →→→→ <br/>(838)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1367)| `CarePlan.activity.detail.extension`| _Equivalent_<br/>(22610/22611)| `CarePlan.activity.detail.extension`| | | 
| **`CarePlan.activity.detail.category`**| _Equivalent_<br/>(3344/3345)| `CarePlan.activity.detail.category`| →→→→ _RelatedTo_ →→→→ <br/>(838)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1367)| `CarePlan.activity.detail.kind`| _Equivalent_<br/>(22614/22615)| `CarePlan.activity.detail.kind`| | | 
| **`CarePlan.activity.detail.code`**| _Equivalent_<br/>(3346/3347)| `CarePlan.activity.detail.code`| _Equivalent_<br/>(11037/11038)| `CarePlan.activity.detail.code`| _Equivalent_<br/>(22620/22621)| `CarePlan.activity.detail.code`| | | 
| **`CarePlan.activity.detail.reasonCode`**| _Equivalent_<br/>(3348/3349)| `CarePlan.activity.detail.reasonCode`| _Equivalent_<br/>(11039/11040)| `CarePlan.activity.detail.reasonCode`| _Equivalent_<br/>(22622/22623)| `CarePlan.activity.detail.reasonCode`| | | 
| **`CarePlan.activity.detail.reasonReference`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3350)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3351)| `CarePlan.activity.detail.reasonReference`| →→→→ _RelatedTo_ →→→→ <br/>(11041)<hr/>←←←← _RelatedTo_ ←←←← <br/>(11042)| `CarePlan.activity.detail.reasonReference`| _Equivalent_<br/>(22624/22625)| `CarePlan.activity.detail.reasonReference`| | | 
| **`CarePlan.activity.detail.goal`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3352)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3353)| `CarePlan.activity.detail.goal`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11043)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11044)| `CarePlan.activity.detail.goal`| _Equivalent_<br/>(22626/22627)| `CarePlan.activity.detail.goal`| | | 
| **`CarePlan.activity.detail.status`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3354)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3355)| `CarePlan.activity.detail.status`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11045)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11046)| `CarePlan.activity.detail.status`| _Equivalent_<br/>(22628/22629)| `CarePlan.activity.detail.status`| | | 
| **`CarePlan.activity.detail.statusReason`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3356)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3357)| `CarePlan.activity.detail.statusReason`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(11047)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11048)| `CarePlan.activity.detail.statusReason`| _Equivalent_<br/>(22630/22631)| `CarePlan.activity.detail.statusReason`| | | 
| **`CarePlan.activity.detail.prohibited`**| →→→→ _Equivalent_ →→→→ <br/>(3358)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(3359)| `CarePlan.activity.detail.prohibited`| _Equivalent_<br/>(841/1366)| `CarePlan.activity.detail.doNotPerform`| _Equivalent_<br/>(22632/22633)| `CarePlan.activity.detail.doNotPerform`| | | 
| **`CarePlan.activity.detail.scheduled[x]`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3360)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3361)| `CarePlan.activity.detail.scheduled[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11049)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11050)| `CarePlan.activity.detail.scheduled[x]`| _Equivalent_<br/>(22634/22635)| `CarePlan.activity.detail.scheduled[x]`| | | 
| **`CarePlan.activity.detail.location`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3362)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3363)| `CarePlan.activity.detail.location`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11051)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11052)| `CarePlan.activity.detail.location`| _Equivalent_<br/>(22636/22637)| `CarePlan.activity.detail.location`| | | 
| **`CarePlan.activity.detail.performer`**| →→→→ _RelatedTo_ →→→→ <br/>(3364)<hr/>←←←← _RelatedTo_ ←←←← <br/>(3365)| `CarePlan.activity.detail.performer`| →→→→ _RelatedTo_ →→→→ <br/>(11053)<hr/>←←←← _RelatedTo_ ←←←← <br/>(11054)| `CarePlan.activity.detail.performer`| _Equivalent_<br/>(22638/22639)| `CarePlan.activity.detail.performer`| | | 
| **`CarePlan.activity.detail.product[x]`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3366)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3367)| `CarePlan.activity.detail.product[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11055)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11056)| `CarePlan.activity.detail.product[x]`| _Equivalent_<br/>(22640/22641)| `CarePlan.activity.detail.product[x]`| | | 
| **`CarePlan.activity.detail.dailyAmount`**| _Equivalent_<br/>(3368/3369)| `CarePlan.activity.detail.dailyAmount`| _Equivalent_<br/>(11057/11058)| `CarePlan.activity.detail.dailyAmount`| _Equivalent_<br/>(22642/22643)| `CarePlan.activity.detail.dailyAmount`| | | 
| **`CarePlan.activity.detail.quantity`**| _Equivalent_<br/>(3370/3371)| `CarePlan.activity.detail.quantity`| _Equivalent_<br/>(11059/11060)| `CarePlan.activity.detail.quantity`| _Equivalent_<br/>(22644/22645)| `CarePlan.activity.detail.quantity`| | | 
| **`CarePlan.activity.detail.description`**| _Equivalent_<br/>(3372/3373)| `CarePlan.activity.detail.description`| _Equivalent_<br/>(11061/11062)| `CarePlan.activity.detail.description`| _Equivalent_<br/>(22646/22647)| `CarePlan.activity.detail.description`| | | 
| **`CarePlan.note`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3374)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3375)| `CarePlan.note`| _Equivalent_<br/>(11063/11064)| `CarePlan.note`| _Equivalent_<br/>(22648/22649)| `CarePlan.note`| _Equivalent_<br/>(37638/37639)| `CarePlan.note`
| *60 of 60 elements used* | | *49 of 56 elements used* <br/>remaining elements:<br/>`CarePlan.activity.detail.definition`, `CarePlan.activity.outcomeCodeableConcept`, `CarePlan.basedOn`, `CarePlan.definition`, `CarePlan.intent`, `CarePlan.partOf`, `CarePlan.replaces`, `CarePlan.title`| | *48 of 60 elements used* <br/>remaining elements:<br/>`CarePlan.activity.detail.instantiatesCanonical`, `CarePlan.activity.detail.instantiatesUri`, `CarePlan.activity.outcomeCodeableConcept`, `CarePlan.basedOn`, `CarePlan.contributor`, `CarePlan.created`, `CarePlan.instantiatesCanonical`, `CarePlan.instantiatesUri`, `CarePlan.intent`, `CarePlan.partOf`, `CarePlan.replaces`, `CarePlan.title`| | *48 of 60 elements used* <br/>remaining elements:<br/>`CarePlan.activity.detail.instantiatesCanonical`, `CarePlan.activity.detail.instantiatesUri`, `CarePlan.activity.outcomeCodeableConcept`, `CarePlan.basedOn`, `CarePlan.contributor`, `CarePlan.created`, `CarePlan.instantiatesCanonical`, `CarePlan.instantiatesUri`, `CarePlan.intent`, `CarePlan.partOf`, `CarePlan.replaces`, `CarePlan.title`| | *29 of 38 elements used* <br/>remaining elements:<br/>`CarePlan.basedOn`, `CarePlan.contributor`, `CarePlan.created`, `CarePlan.instantiatesCanonical`, `CarePlan.instantiatesUri`, `CarePlan.intent`, `CarePlan.partOf`, `CarePlan.replaces`, `CarePlan.title`

