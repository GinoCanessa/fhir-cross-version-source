Comparison of 
Generated at Friday, April 4, 2025 2:58:59 PM

### QuestionnaireResponseStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | QuestionnaireResponseStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/questionnaire-answers-status` |
| Version | 5.0.0 |
| Description | Lifecycle status of the questionnaire response. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4823` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/QuestionnaireResponse` | `QuestionnaireResponse.status` | `http://hl7.org/fhir/ValueSet/questionnaire-answers-status\|5.0.0` | `Required` | in-progress \| completed \| amended \| entered-in-error \| stopped |

### Referenced Systems

* `http://hl7.org/fhir/questionnaire-answers-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [QuestionnaireResponseStatus](/docs/R2/ValueSets/QuestionnaireResponseStatus.md)<br/> `http://hl7.org/fhir/ValueSet/questionnaire-answers-status\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `125`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `283`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [QuestionnaireResponseStatus](/docs/R3/ValueSets/QuestionnaireResponseStatus.md)<br/> `http://hl7.org/fhir/ValueSet/questionnaire-answers-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `484`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `707`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [QuestionnaireResponseStatus](/docs/R4/ValueSets/QuestionnaireResponseStatus.md)<br/> `http://hl7.org/fhir/ValueSet/questionnaire-answers-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1669`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1670`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [QuestionnaireResponseStatus](/docs/R4B/ValueSets/QuestionnaireResponseStatus.md)<br/> `http://hl7.org/fhir/ValueSet/questionnaire-answers-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `966`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1227`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [QuestionnaireResponseStatus](/docs/R5/ValueSets/QuestionnaireResponseStatus.md)<br/> `http://hl7.org/fhir/ValueSet/questionnaire-answers-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set QuestionnaireResponseStatus from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 QuestionnaireResponseStatus](/docs/R2/ValueSets/QuestionnaireResponseStatus.md)| Relationship | [R3 QuestionnaireResponseStatus](/docs/R3/ValueSets/QuestionnaireResponseStatus.md)| Relationship | [R4 QuestionnaireResponseStatus](/docs/R4/ValueSets/QuestionnaireResponseStatus.md)| Relationship | [R4B QuestionnaireResponseStatus](/docs/R4B/ValueSets/QuestionnaireResponseStatus.md)| Relationship | R5 QuestionnaireResponseStatus
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/questionnaire-answers-status`
| `in-progress`| _Equivalent_ <br/>(1064/2478)| `in-progress`| _Equivalent_ <br/>(4529/6839)| `in-progress`| _Equivalent_ <br/>(16832/16833)| `in-progress`| _Equivalent_ <br/>(9240/11564)| **`in-progress`**
| `completed`| _Equivalent_ <br/>(1063/2476)| `completed`| _Equivalent_ <br/>(4527/6837)| `completed`| _Equivalent_ <br/>(16834/16835)| `completed`| _Equivalent_ <br/>(9238/11562)| **`completed`**
| `amended`| _Equivalent_ <br/>(1062/2475)| `amended`| _Equivalent_ <br/>(4525/6835)| `amended`| _Equivalent_ <br/>(16836/16837)| `amended`| _Equivalent_ <br/>(9236/11560)| **`amended`**
| | | `entered-in-error`| _Equivalent_ <br/>(4528/6838)| `entered-in-error`| _Equivalent_ <br/>(16838/16839)| `entered-in-error`| _Equivalent_ <br/>(9239/11563)| **`entered-in-error`**
| | | `stopped`| _Equivalent_ <br/>(4526/6836)| `stopped`| _Equivalent_ <br/>(16840/16841)| `stopped`| _Equivalent_ <br/>(9237/11561)| **`stopped`**
| *3 of 3 codes used* | | *5 of 5 codes used* | | *5 of 5 codes used* | | *5 of 5 codes used* | | *5 of 5 codes used* 

