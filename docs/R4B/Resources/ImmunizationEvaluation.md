Comparison of 
Generated at Thursday, April 3, 2025 8:18:29 AM

### ImmunizationEvaluation

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| Stucture Name | ImmunizationEvaluation |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ImmunizationEvaluation` |
| Version | 4.3.0 |
| Description | Describes a comparison of an immunization event against published recommendations to determine if the administration is "valid" in relation to those  recommendations. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1704` |
| Database Snapshot Count | `22` |
| Database Differential Count | `14` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ImmunizationEvaluation` | `ImmunizationEvaluation` | `ImmunizationEvaluation` | ImmunizationEvaluation | Immunization evaluation information | 0..* | ImmunizationEvaluation |  |  |
| `ImmunizationEvaluation.authority` | `ImmunizationEvaluation.authority` | `authority` | ImmunizationEvaluation.authority | Who is responsible for publishing the recommendations | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `ImmunizationEvaluation.contained` | `ImmunizationEvaluation.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `ImmunizationEvaluation.date` | `ImmunizationEvaluation.date` | `date` | ImmunizationEvaluation.date | Date evaluation was performed | 0..1 | dateTime |  |  |
| `ImmunizationEvaluation.description` | `ImmunizationEvaluation.description` | `description` | ImmunizationEvaluation.description | Evaluation notes | 0..1 | string |  |  |
| `ImmunizationEvaluation.doseNumber[x]` | `ImmunizationEvaluation.doseNumber[x]` | `doseNumber[x]` | ImmunizationEvaluation.doseNumber[x] | Dose number within series | 0..1 | positiveInt, string |  |  |
| `ImmunizationEvaluation.doseStatus` | `ImmunizationEvaluation.doseStatus` | `doseStatus` | ImmunizationEvaluation.doseStatus | Status of the dose relative to published recommendations | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/immunization-evaluation-dose-status` |
| `ImmunizationEvaluation.doseStatusReason` | `ImmunizationEvaluation.doseStatusReason` | `doseStatusReason` | ImmunizationEvaluation.doseStatusReason | Reason for the dose status | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/immunization-evaluation-dose-status-reason` |
| `ImmunizationEvaluation.extension` | `ImmunizationEvaluation.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ImmunizationEvaluation.id` | `ImmunizationEvaluation.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `ImmunizationEvaluation.identifier` | `ImmunizationEvaluation.identifier` | `identifier` | ImmunizationEvaluation.identifier | Business identifier | 0..* | Identifier |  |  |
| `ImmunizationEvaluation.immunizationEvent` | `ImmunizationEvaluation.immunizationEvent` | `immunizationEvent` | ImmunizationEvaluation.immunizationEvent | Immunization being evaluated | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Immunization) |  |  |
| `ImmunizationEvaluation.implicitRules` | `ImmunizationEvaluation.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `ImmunizationEvaluation.language` | `ImmunizationEvaluation.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `ImmunizationEvaluation.meta` | `ImmunizationEvaluation.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `ImmunizationEvaluation.modifierExtension` | `ImmunizationEvaluation.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ImmunizationEvaluation.patient` | `ImmunizationEvaluation.patient` | `patient` | ImmunizationEvaluation.patient | Who this evaluation is for | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `ImmunizationEvaluation.series` | `ImmunizationEvaluation.series` | `series` | ImmunizationEvaluation.series | Name of vaccine series | 0..1 | string |  |  |
| `ImmunizationEvaluation.seriesDoses[x]` | `ImmunizationEvaluation.seriesDoses[x]` | `seriesDoses[x]` | ImmunizationEvaluation.seriesDoses[x] | Recommended number of doses for immunity | 0..1 | positiveInt, string |  |  |
| `ImmunizationEvaluation.status` | `ImmunizationEvaluation.status` | `status` | ImmunizationEvaluation.status | completed \| entered-in-error | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/immunization-evaluation-status|4.3.0` |
| `ImmunizationEvaluation.targetDisease` | `ImmunizationEvaluation.targetDisease` | `targetDisease` | ImmunizationEvaluation.targetDisease | Evaluation target disease | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/immunization-evaluation-target-disease` |
| `ImmunizationEvaluation.text` | `ImmunizationEvaluation.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [ImmunizationEvaluation](/docs/R4/Resources/ImmunizationEvaluation.md)<br/> `http://hl7.org/fhir/StructureDefinition/ImmunizationEvaluation\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1511`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1512`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ImmunizationEvaluation](/docs/R4B/Resources/ImmunizationEvaluation.md)<br/> `http://hl7.org/fhir/StructureDefinition/ImmunizationEvaluation\|4.3.0` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `989`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1218`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ImmunizationEvaluation](/docs/R5/Resources/ImmunizationEvaluation.md)<br/> `http://hl7.org/fhir/StructureDefinition/ImmunizationEvaluation\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition ImmunizationEvaluation from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | [R4 ImmunizationEvaluation](/docs/R4/Resources/ImmunizationEvaluation.md)| Relationship | R4B ImmunizationEvaluation| Relationship | [R5 ImmunizationEvaluation](/docs/R5/Resources/ImmunizationEvaluation.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | `ImmunizationEvaluation`| _Equivalent_<br/>(28177/28178)| **`ImmunizationEvaluation`**| _Equivalent_<br/>(43056/43057)| `ImmunizationEvaluation`
| | | | | `ImmunizationEvaluation.id`| _Equivalent_<br/>(28179/28180)| **`ImmunizationEvaluation.id`**| _Equivalent_<br/>(43058/43059)| `ImmunizationEvaluation.id`
| | | | | `ImmunizationEvaluation.meta`| _Equivalent_<br/>(28181/28182)| **`ImmunizationEvaluation.meta`**| _Equivalent_<br/>(43060/43061)| `ImmunizationEvaluation.meta`
| | | | | `ImmunizationEvaluation.implicitRules`| _Equivalent_<br/>(28183/28184)| **`ImmunizationEvaluation.implicitRules`**| _Equivalent_<br/>(43062/43063)| `ImmunizationEvaluation.implicitRules`
| | | | | `ImmunizationEvaluation.language`| _Equivalent_<br/>(28185/28186)| **`ImmunizationEvaluation.language`**| _Equivalent_<br/>(43064/43065)| `ImmunizationEvaluation.language`
| | | | | `ImmunizationEvaluation.text`| _Equivalent_<br/>(28187/28188)| **`ImmunizationEvaluation.text`**| _Equivalent_<br/>(43066/43067)| `ImmunizationEvaluation.text`
| | | | | `ImmunizationEvaluation.contained`| _Equivalent_<br/>(28189/28190)| **`ImmunizationEvaluation.contained`**| _Equivalent_<br/>(43068/43069)| `ImmunizationEvaluation.contained`
| | | | | `ImmunizationEvaluation.extension`| _Equivalent_<br/>(28191/28192)| **`ImmunizationEvaluation.extension`**| _Equivalent_<br/>(43070/43071)| `ImmunizationEvaluation.extension`
| | | | | `ImmunizationEvaluation.modifierExtension`| _Equivalent_<br/>(28193/28194)| **`ImmunizationEvaluation.modifierExtension`**| _Equivalent_<br/>(43072/43073)| `ImmunizationEvaluation.modifierExtension`
| | | | | `ImmunizationEvaluation.identifier`| _Equivalent_<br/>(28195/28196)| **`ImmunizationEvaluation.identifier`**| _Equivalent_<br/>(43074/43075)| `ImmunizationEvaluation.identifier`
| | | | | `ImmunizationEvaluation.status`| _Equivalent_<br/>(28197/28198)| **`ImmunizationEvaluation.status`**| _Equivalent_<br/>(43076/43077)| `ImmunizationEvaluation.status`
| | | | | `ImmunizationEvaluation.patient`| _Equivalent_<br/>(28199/28200)| **`ImmunizationEvaluation.patient`**| _Equivalent_<br/>(43078/43079)| `ImmunizationEvaluation.patient`
| | | | | `ImmunizationEvaluation.date`| _Equivalent_<br/>(28201/28202)| **`ImmunizationEvaluation.date`**| _Equivalent_<br/>(43080/43081)| `ImmunizationEvaluation.date`
| | | | | `ImmunizationEvaluation.authority`| _Equivalent_<br/>(28203/28204)| **`ImmunizationEvaluation.authority`**| _Equivalent_<br/>(43082/43083)| `ImmunizationEvaluation.authority`
| | | | | `ImmunizationEvaluation.targetDisease`| _Equivalent_<br/>(28205/28206)| **`ImmunizationEvaluation.targetDisease`**| _Equivalent_<br/>(43084/43085)| `ImmunizationEvaluation.targetDisease`
| | | | | `ImmunizationEvaluation.immunizationEvent`| _Equivalent_<br/>(28207/28208)| **`ImmunizationEvaluation.immunizationEvent`**| _Equivalent_<br/>(43086/43087)| `ImmunizationEvaluation.immunizationEvent`
| | | | | `ImmunizationEvaluation.doseStatus`| _Equivalent_<br/>(28209/28210)| **`ImmunizationEvaluation.doseStatus`**| _Equivalent_<br/>(43088/43089)| `ImmunizationEvaluation.doseStatus`
| | | | | `ImmunizationEvaluation.doseStatusReason`| _Equivalent_<br/>(28211/28212)| **`ImmunizationEvaluation.doseStatusReason`**| _Equivalent_<br/>(43090/43091)| `ImmunizationEvaluation.doseStatusReason`
| | | | | `ImmunizationEvaluation.description`| _Equivalent_<br/>(28213/28214)| **`ImmunizationEvaluation.description`**| _Equivalent_<br/>(43092/43093)| `ImmunizationEvaluation.description`
| | | | | `ImmunizationEvaluation.series`| _Equivalent_<br/>(28215/28216)| **`ImmunizationEvaluation.series`**| _Equivalent_<br/>(43094/43095)| `ImmunizationEvaluation.series`
| | | | | `ImmunizationEvaluation.doseNumber[x]`| _Equivalent_<br/>(28217/28218)| **`ImmunizationEvaluation.doseNumber[x]`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1803)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2047)| `ImmunizationEvaluation.doseNumber`
| | | | | `ImmunizationEvaluation.seriesDoses[x]`| _Equivalent_<br/>(28219/28220)| **`ImmunizationEvaluation.seriesDoses[x]`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1804)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2048)| `ImmunizationEvaluation.seriesDoses`
| | | | | *22 of 22 elements used* | | *22 of 22 elements used* | | *22 of 22 elements used* 

