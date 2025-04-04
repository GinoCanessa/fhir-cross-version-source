Comparison of 
Generated at Friday, April 4, 2025 2:58:33 PM

### ClinicalImpression

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | ClinicalImpression |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ClinicalImpression` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for ClinicalImpression Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `53` |
| Database Snapshot Count | `41` |
| Database Differential Count | `24` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ClinicalImpression` | `ClinicalImpression` | `ClinicalImpression` | ClinicalImpression | A clinical assessment performed when planning treatments and management strategies for a patient | 0..* | ClinicalImpression |  |  |
| `ClinicalImpression.action` | `ClinicalImpression.action` | `action` |  | Actions taken during assessment | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Appointment), Reference(http://hl7.org/fhir/StructureDefinition/DiagnosticOrder), Reference(http://hl7.org/fhir/StructureDefinition/MedicationOrder), Reference(http://hl7.org/fhir/StructureDefinition/NutritionOrder), Reference(http://hl7.org/fhir/StructureDefinition/Procedure), Reference(http://hl7.org/fhir/StructureDefinition/ProcedureRequest), Reference(http://hl7.org/fhir/StructureDefinition/ReferralRequest), Reference(http://hl7.org/fhir/StructureDefinition/SupplyRequest) |  |  |
| `ClinicalImpression.assessor` | `ClinicalImpression.assessor` | `assessor` |  | The clinician performing the assessment | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
| `ClinicalImpression.contained` | `ClinicalImpression.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `ClinicalImpression.date` | `ClinicalImpression.date` | `date` |  | When the assessment occurred | 0..1 | dateTime |  |  |
| `ClinicalImpression.description` | `ClinicalImpression.description` | `description` |  | Why/how the assessment was performed | 0..1 | string |  |  |
| `ClinicalImpression.extension` | `ClinicalImpression.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ClinicalImpression.finding` | `ClinicalImpression.finding` | `finding` |  | Possible or likely findings and diagnoses | 0..* | BackboneElement |  |  |
| `ClinicalImpression.finding.cause` | `ClinicalImpression.finding.cause` | `cause` |  | Which investigations support finding | 0..1 | string |  |  |
| `ClinicalImpression.finding.extension` | `ClinicalImpression.finding.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ClinicalImpression.finding.id` | `ClinicalImpression.finding.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `ClinicalImpression.finding.item` | `ClinicalImpression.finding.item` | `item` |  | Specific text or code for finding | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/condition-code` |
| `ClinicalImpression.finding.modifierExtension` | `ClinicalImpression.finding.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ClinicalImpression.id` | `ClinicalImpression.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `ClinicalImpression.implicitRules` | `ClinicalImpression.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `ClinicalImpression.investigations` | `ClinicalImpression.investigations` | `investigations` |  | One or more sets of investigations (signs, symptions, etc.) | 0..* | BackboneElement |  |  |
| `ClinicalImpression.investigations.code` | `ClinicalImpression.investigations.code` | `code` |  | A name/code for the set | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/investigation-sets` |
| `ClinicalImpression.investigations.extension` | `ClinicalImpression.investigations.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ClinicalImpression.investigations.id` | `ClinicalImpression.investigations.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `ClinicalImpression.investigations.item` | `ClinicalImpression.investigations.item` | `item` |  | Record of a specific investigation | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/DiagnosticReport), Reference(http://hl7.org/fhir/StructureDefinition/FamilyMemberHistory), Reference(http://hl7.org/fhir/StructureDefinition/Observation), Reference(http://hl7.org/fhir/StructureDefinition/QuestionnaireResponse) |  |  |
| `ClinicalImpression.investigations.modifierExtension` | `ClinicalImpression.investigations.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ClinicalImpression.language` | `ClinicalImpression.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `ClinicalImpression.meta` | `ClinicalImpression.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `ClinicalImpression.modifierExtension` | `ClinicalImpression.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ClinicalImpression.patient` | `ClinicalImpression.patient` | `patient` |  | The patient being assessed | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `ClinicalImpression.plan` | `ClinicalImpression.plan` | `plan` |  | Plan of action after assessment | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Appointment), Reference(http://hl7.org/fhir/StructureDefinition/CarePlan), Reference(http://hl7.org/fhir/StructureDefinition/CommunicationRequest), Reference(http://hl7.org/fhir/StructureDefinition/DeviceUseRequest), Reference(http://hl7.org/fhir/StructureDefinition/DiagnosticOrder), Reference(http://hl7.org/fhir/StructureDefinition/MedicationOrder), Reference(http://hl7.org/fhir/StructureDefinition/NutritionOrder), Reference(http://hl7.org/fhir/StructureDefinition/Order), Reference(http://hl7.org/fhir/StructureDefinition/ProcedureRequest), Reference(http://hl7.org/fhir/StructureDefinition/ProcessRequest), Reference(http://hl7.org/fhir/StructureDefinition/ReferralRequest), Reference(http://hl7.org/fhir/StructureDefinition/SupplyRequest), Reference(http://hl7.org/fhir/StructureDefinition/VisionPrescription) |  |  |
| `ClinicalImpression.previous` | `ClinicalImpression.previous` | `previous` |  | Reference to last assessment | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/ClinicalImpression) |  |  |
| `ClinicalImpression.problem` | `ClinicalImpression.problem` | `problem` |  | General assessment of patient state | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/AllergyIntolerance), Reference(http://hl7.org/fhir/StructureDefinition/Condition) |  |  |
| `ClinicalImpression.prognosis` | `ClinicalImpression.prognosis` | `prognosis` |  | Estimate of likely outcome | 0..1 | string |  |  |
| `ClinicalImpression.protocol` | `ClinicalImpression.protocol` | `protocol` |  | Clinical Protocol followed | 0..1 | uri |  |  |
| `ClinicalImpression.resolved` | `ClinicalImpression.resolved` | `resolved` |  | Diagnoses/conditions resolved since previous assessment | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/condition-code` |
| `ClinicalImpression.ruledOut` | `ClinicalImpression.ruledOut` | `ruledOut` |  | Diagnosis considered not possible | 0..* | BackboneElement |  |  |
| `ClinicalImpression.ruledOut.extension` | `ClinicalImpression.ruledOut.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ClinicalImpression.ruledOut.id` | `ClinicalImpression.ruledOut.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `ClinicalImpression.ruledOut.item` | `ClinicalImpression.ruledOut.item` | `item` |  | Specific text of code for diagnosis | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/condition-code` |
| `ClinicalImpression.ruledOut.modifierExtension` | `ClinicalImpression.ruledOut.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ClinicalImpression.ruledOut.reason` | `ClinicalImpression.ruledOut.reason` | `reason` |  | Grounds for elimination | 0..1 | string |  |  |
| `ClinicalImpression.status` | `ClinicalImpression.status` | `status` |  | in-progress \| completed \| entered-in-error | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/clinical-impression-status` |
| `ClinicalImpression.summary` | `ClinicalImpression.summary` | `summary` |  | Summary of the assessment | 0..1 | string |  |  |
| `ClinicalImpression.text` | `ClinicalImpression.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `ClinicalImpression.trigger[x]` | `ClinicalImpression.trigger[x]` | `trigger[x]` |  | Request or event that necessitated this assessment | 0..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/Resource) | `Example` | `http://hl7.org/fhir/ValueSet/clinical-findings` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ClinicalImpression](/docs/R2/Resources/ClinicalImpression.md)<br/> `http://hl7.org/fhir/StructureDefinition/ClinicalImpression\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `85`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `251`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ClinicalImpression](/docs/R3/Resources/ClinicalImpression.md)<br/> `http://hl7.org/fhir/StructureDefinition/ClinicalImpression\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `432`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`RelatedTo`<br/>- DBKey: `628`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ClinicalImpression](/docs/R4/Resources/ClinicalImpression.md)<br/> `http://hl7.org/fhir/StructureDefinition/ClinicalImpression\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1427`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1428`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ClinicalImpression](/docs/R4B/Resources/ClinicalImpression.md)<br/> `http://hl7.org/fhir/StructureDefinition/ClinicalImpression\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `947`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1176`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ClinicalImpression](/docs/R5/Resources/ClinicalImpression.md)<br/> `http://hl7.org/fhir/StructureDefinition/ClinicalImpression\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition ClinicalImpression from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 ClinicalImpression| Relationship | [R3 ClinicalImpression](/docs/R3/Resources/ClinicalImpression.md)| Relationship | [R4 ClinicalImpression](/docs/R4/Resources/ClinicalImpression.md)| Relationship | [R4B ClinicalImpression](/docs/R4B/Resources/ClinicalImpression.md)| Relationship | [R5 ClinicalImpression](/docs/R5/Resources/ClinicalImpression.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`ClinicalImpression`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(3689)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(3690)| `ClinicalImpression`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11721)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11722)| `ClinicalImpression`| _Equivalent_<br/>(23583/23584)| `ClinicalImpression`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(38796)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(38797)| `ClinicalImpression`
| **`ClinicalImpression.id`**| _Equivalent_<br/>(3691/3692)| `ClinicalImpression.id`| _Equivalent_<br/>(11723/11724)| `ClinicalImpression.id`| _Equivalent_<br/>(23585/23586)| `ClinicalImpression.id`| _Equivalent_<br/>(38798/38799)| `ClinicalImpression.id`
| **`ClinicalImpression.meta`**| _Equivalent_<br/>(3693/3694)| `ClinicalImpression.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11725)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11726)| `ClinicalImpression.meta`| _Equivalent_<br/>(23587/23588)| `ClinicalImpression.meta`| _Equivalent_<br/>(38800/38801)| `ClinicalImpression.meta`
| **`ClinicalImpression.implicitRules`**| _Equivalent_<br/>(3695/3696)| `ClinicalImpression.implicitRules`| _Equivalent_<br/>(11727/11728)| `ClinicalImpression.implicitRules`| _Equivalent_<br/>(23589/23590)| `ClinicalImpression.implicitRules`| _Equivalent_<br/>(38802/38803)| `ClinicalImpression.implicitRules`
| **`ClinicalImpression.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3697)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(3698)| `ClinicalImpression.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11729)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11730)| `ClinicalImpression.language`| _Equivalent_<br/>(23591/23592)| `ClinicalImpression.language`| _Equivalent_<br/>(38804/38805)| `ClinicalImpression.language`
| **`ClinicalImpression.text`**| _Equivalent_<br/>(3699/3700)| `ClinicalImpression.text`| _Equivalent_<br/>(11731/11732)| `ClinicalImpression.text`| _Equivalent_<br/>(23593/23594)| `ClinicalImpression.text`| _Equivalent_<br/>(38806/38807)| `ClinicalImpression.text`
| **`ClinicalImpression.contained`**| _Equivalent_<br/>(3701/3702)| `ClinicalImpression.contained`| _Equivalent_<br/>(11733/11734)| `ClinicalImpression.contained`| _Equivalent_<br/>(23595/23596)| `ClinicalImpression.contained`| _Equivalent_<br/>(38808/38809)| `ClinicalImpression.contained`
| **`ClinicalImpression.extension`**| _Equivalent_<br/>(3703/3704)| `ClinicalImpression.extension`| _Equivalent_<br/>(11735/11736)| `ClinicalImpression.extension`| _Equivalent_<br/>(23597/23598)| `ClinicalImpression.extension`| _Equivalent_<br/>(38810/38811)| `ClinicalImpression.extension`
| **`ClinicalImpression.modifierExtension`**| _Equivalent_<br/>(3705/3706)| `ClinicalImpression.modifierExtension`| _Equivalent_<br/>(11737/11738)| `ClinicalImpression.modifierExtension`| _Equivalent_<br/>(23599/23600)| `ClinicalImpression.modifierExtension`| _Equivalent_<br/>(38812/38813)| `ClinicalImpression.modifierExtension`
| **`ClinicalImpression.patient`**| →→→→ _RelatedTo_ →→→→ <br/>(128)<hr/>←←←← _RelatedTo_ ←←←← <br/>(552)| `ClinicalImpression.subject`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11747)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11748)| `ClinicalImpression.subject`| _Equivalent_<br/>(23611/23612)| `ClinicalImpression.subject`| _Equivalent_<br/>(38823/38824)| `ClinicalImpression.subject`
| **`ClinicalImpression.assessor`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3707)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3708)| `ClinicalImpression.assessor`| →→→→ _RelatedTo_ →→→→ <br/>(11753)<hr/>←←←← _RelatedTo_ ←←←← <br/>(11754)| `ClinicalImpression.assessor`| _Equivalent_<br/>(23619/23620)| `ClinicalImpression.assessor`| _Equivalent_<br/>(1736/1980)| `ClinicalImpression.performer`
| **`ClinicalImpression.status`**| _Equivalent_<br/>(3709/3710)| `ClinicalImpression.status`| _Equivalent_<br/>(11741/11742)| `ClinicalImpression.status`| _Equivalent_<br/>(23603/23604)| `ClinicalImpression.status`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(38816)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(38817)| `ClinicalImpression.status`
| **`ClinicalImpression.date`**| _Equivalent_<br/>(3711/3712)| `ClinicalImpression.date`| _Equivalent_<br/>(11751/11752)| `ClinicalImpression.date`| _Equivalent_<br/>(23617/23618)| `ClinicalImpression.date`| _Equivalent_<br/>(38829/38830)| `ClinicalImpression.date`
| **`ClinicalImpression.description`**| _Equivalent_<br/>(3713/3714)| `ClinicalImpression.description`| _Equivalent_<br/>(11745/11746)| `ClinicalImpression.description`| _Equivalent_<br/>(23609/23610)| `ClinicalImpression.description`| _Equivalent_<br/>(38821/38822)| `ClinicalImpression.description`
| **`ClinicalImpression.previous`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3715)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3716)| `ClinicalImpression.previous`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11755)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11756)| `ClinicalImpression.previous`| _Equivalent_<br/>(23621/23622)| `ClinicalImpression.previous`| _Equivalent_<br/>(38831/38832)| `ClinicalImpression.previous`
| **`ClinicalImpression.problem`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3717)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3718)| `ClinicalImpression.problem`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11757)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11758)| `ClinicalImpression.problem`| _Equivalent_<br/>(23623/23624)| `ClinicalImpression.problem`| _Equivalent_<br/>(38833/38834)| `ClinicalImpression.problem`
| **`ClinicalImpression.trigger[x]`**| | | | | | | | | 
| **`ClinicalImpression.investigations`**| _Equivalent_<br/>(125/549)| `ClinicalImpression.investigation`| _Equivalent_<br/>(11759/11760)| `ClinicalImpression.investigation`| _Equivalent_<br/>(23625/23626)| `ClinicalImpression.investigation`| | | 
| **`ClinicalImpression.investigations.id`**| | | | | | | | | 
| **`ClinicalImpression.investigations.extension`**| | | | | | | | | 
| **`ClinicalImpression.investigations.modifierExtension`**| | | | | | | | | 
| **`ClinicalImpression.investigations.code`**| _Equivalent_<br/>(126/550)| `ClinicalImpression.investigation.code`| _Equivalent_<br/>(11767/11768)| `ClinicalImpression.investigation.code`| _Equivalent_<br/>(23633/23634)| `ClinicalImpression.investigation.code`| | | 
| **`ClinicalImpression.investigations.item`**| →→→→ _RelatedTo_ →→→→ <br/>(127)<hr/>←←←← _RelatedTo_ ←←←← <br/>(551)| `ClinicalImpression.investigation.item`| →→→→ _RelatedTo_ →→→→ <br/>(11769)<hr/>←←←← _RelatedTo_ ←←←← <br/>(11770)| `ClinicalImpression.investigation.item`| _Equivalent_<br/>(23635/23636)| `ClinicalImpression.investigation.item`| | | 
| **`ClinicalImpression.protocol`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3722)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3723)| `ClinicalImpression.protocol`| _Equivalent_<br/>(11771/11772)| `ClinicalImpression.protocol`| _Equivalent_<br/>(23637/23638)| `ClinicalImpression.protocol`| _Equivalent_<br/>(38841/38842)| `ClinicalImpression.protocol`
| **`ClinicalImpression.summary`**| _Equivalent_<br/>(3724/3725)| `ClinicalImpression.summary`| _Equivalent_<br/>(11773/11774)| `ClinicalImpression.summary`| _Equivalent_<br/>(23639/23640)| `ClinicalImpression.summary`| _Equivalent_<br/>(38843/38844)| `ClinicalImpression.summary`
| **`ClinicalImpression.finding`**| _Equivalent_<br/>(3726/3727)| `ClinicalImpression.finding`| _Equivalent_<br/>(11775/11776)| `ClinicalImpression.finding`| _Equivalent_<br/>(23641/23642)| `ClinicalImpression.finding`| _Equivalent_<br/>(38845/38846)| `ClinicalImpression.finding`
| **`ClinicalImpression.finding.id`**| _Equivalent_<br/>(3728/3729)| `ClinicalImpression.finding.id`| _Equivalent_<br/>(11777/11778)| `ClinicalImpression.finding.id`| _Equivalent_<br/>(23643/23644)| `ClinicalImpression.finding.id`| _Equivalent_<br/>(38847/38848)| `ClinicalImpression.finding.id`
| **`ClinicalImpression.finding.extension`**| _Equivalent_<br/>(3730/3731)| `ClinicalImpression.finding.extension`| _Equivalent_<br/>(11779/11780)| `ClinicalImpression.finding.extension`| _Equivalent_<br/>(23645/23646)| `ClinicalImpression.finding.extension`| _Equivalent_<br/>(38849/38850)| `ClinicalImpression.finding.extension`
| **`ClinicalImpression.finding.modifierExtension`**| _Equivalent_<br/>(3732/3733)| `ClinicalImpression.finding.modifierExtension`| _Equivalent_<br/>(11781/11782)| `ClinicalImpression.finding.modifierExtension`| _Equivalent_<br/>(23647/23648)| `ClinicalImpression.finding.modifierExtension`| _Equivalent_<br/>(38851/38852)| `ClinicalImpression.finding.modifierExtension`
| **`ClinicalImpression.finding.item`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(124)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(548)| `ClinicalImpression.finding.item[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(892)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1408)| `ClinicalImpression.finding.itemCodeableConcept`| _Equivalent_<br/>(23649/23650)| `ClinicalImpression.finding.itemCodeableConcept`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1737)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1981)| `ClinicalImpression.finding.item`
| **`ClinicalImpression.finding.item`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(124)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(548)| `ClinicalImpression.finding.item[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(892)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1408)| `ClinicalImpression.finding.itemReference`| _Equivalent_<br/>(23651/23652)| `ClinicalImpression.finding.itemReference`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1738)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1982)| `ClinicalImpression.finding.item`
| **`ClinicalImpression.finding.cause`**| _Equivalent_<br/>(11717/553)| `base64Binary`| | | | | | | 
| **`ClinicalImpression.finding.cause`**| _Equivalent_<br/>(11717/553)| `ClinicalImpression.finding.basis`| _Equivalent_<br/>(11783/11784)| `ClinicalImpression.finding.basis`| _Equivalent_<br/>(23653/23654)| `ClinicalImpression.finding.basis`| _Equivalent_<br/>(38853/38854)| `ClinicalImpression.finding.basis`
| **`ClinicalImpression.resolved`**| | | | | | | | | 
| **`ClinicalImpression.ruledOut`**| | | | | | | | | 
| **`ClinicalImpression.ruledOut.id`**| | | | | | | | | 
| **`ClinicalImpression.ruledOut.extension`**| | | | | | | | | 
| **`ClinicalImpression.ruledOut.modifierExtension`**| | | | | | | | | 
| **`ClinicalImpression.ruledOut.item`**| | | | | | | | | 
| **`ClinicalImpression.ruledOut.reason`**| | | | | | | | | 
| **`ClinicalImpression.prognosis`**| | | | | | | | | 
| **`ClinicalImpression.plan`**| | | | | | | | | 
| **`ClinicalImpression.action`**| →→→→ _RelatedTo_ →→→→ <br/>(3738)<hr/>←←←← _RelatedTo_ ←←←← <br/>(3739)| `ClinicalImpression.action`| | | | | | | 
| *41 of 41 elements used* | | *29 of 38 elements used* <br/>remaining elements:<br/>`ClinicalImpression.code`, `ClinicalImpression.context`, `ClinicalImpression.effective[x]`, `ClinicalImpression.identifier`, `ClinicalImpression.investigation.extension`, `ClinicalImpression.investigation.id`, `ClinicalImpression.investigation.modifierExtension`, `ClinicalImpression.note`, `ClinicalImpression.prognosisCodeableConcept`, `ClinicalImpression.prognosisReference`| | *28 of 40 elements used* <br/>remaining elements:<br/>`ClinicalImpression.code`, `ClinicalImpression.effective[x]`, `ClinicalImpression.encounter`, `ClinicalImpression.identifier`, `ClinicalImpression.investigation.extension`, `ClinicalImpression.investigation.id`, `ClinicalImpression.investigation.modifierExtension`, `ClinicalImpression.note`, `ClinicalImpression.prognosisCodeableConcept`, `ClinicalImpression.prognosisReference`, `ClinicalImpression.statusReason`, `ClinicalImpression.supportingInfo`| | *28 of 40 elements used* <br/>remaining elements:<br/>`ClinicalImpression.code`, `ClinicalImpression.effective[x]`, `ClinicalImpression.encounter`, `ClinicalImpression.identifier`, `ClinicalImpression.investigation.extension`, `ClinicalImpression.investigation.id`, `ClinicalImpression.investigation.modifierExtension`, `ClinicalImpression.note`, `ClinicalImpression.prognosisCodeableConcept`, `ClinicalImpression.prognosisReference`, `ClinicalImpression.statusReason`, `ClinicalImpression.supportingInfo`| | *24 of 33 elements used* <br/>remaining elements:<br/>`ClinicalImpression.changePattern`, `ClinicalImpression.effective[x]`, `ClinicalImpression.encounter`, `ClinicalImpression.identifier`, `ClinicalImpression.note`, `ClinicalImpression.prognosisCodeableConcept`, `ClinicalImpression.prognosisReference`, `ClinicalImpression.statusReason`, `ClinicalImpression.supportingInfo`

