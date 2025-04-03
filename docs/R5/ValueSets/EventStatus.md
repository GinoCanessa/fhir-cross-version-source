Comparison of 
Generated at Thursday, April 3, 2025 8:18:32 AM

### EventStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | EventStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/event-status` |
| Version | 5.0.0 |
| Description | Codes identifying the lifecycle stage of an event. |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `4543` |
| Database Concept Count | `8` |
| Database Active Concept Count | `8` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ClinicalImpression` | `ClinicalImpression.status` | `http://hl7.org/fhir/ValueSet/event-status\|5.0.0` | `Required` | preparation \| in-progress \| not-done \| on-hold \| stopped \| completed \| entered-in-error \| unknown |
| `http://hl7.org/fhir/StructureDefinition/Communication` | `Communication.status` | `http://hl7.org/fhir/ValueSet/event-status\|5.0.0` | `Required` | preparation \| in-progress \| not-done \| on-hold \| stopped \| completed \| entered-in-error \| unknown |
| `http://hl7.org/fhir/StructureDefinition/NutritionIntake` | `NutritionIntake.status` | `http://hl7.org/fhir/ValueSet/event-status\|5.0.0` | `Required` | preparation \| in-progress \| not-done \| on-hold \| stopped \| completed \| entered-in-error \| unknown |
| `http://hl7.org/fhir/StructureDefinition/Procedure` | `Procedure.status` | `http://hl7.org/fhir/ValueSet/event-status\|5.0.0` | `Required` | preparation \| in-progress \| not-done \| on-hold \| stopped \| completed \| entered-in-error \| unknown |

### Referenced Systems

* `http://hl7.org/fhir/event-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ClinicalImpressionStatus](/docs/R2/ValueSets/ClinicalImpressionStatus.md)<br/> `http://hl7.org/fhir/ValueSet/clinical-impression-status\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `18`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `177`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ClinicalImpressionStatus](/docs/R3/ValueSets/ClinicalImpressionStatus.md)<br/> `http://hl7.org/fhir/ValueSet/clinical-impression-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `343`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `567`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ClinicalImpressionStatus](/docs/R4/ValueSets/ClinicalImpressionStatus.md)<br/> `http://hl7.org/fhir/ValueSet/clinicalimpression-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1415`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1416`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ClinicalImpressionStatus](/docs/R4B/ValueSets/ClinicalImpressionStatus.md)<br/> `http://hl7.org/fhir/ValueSet/clinicalimpression-status\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `792`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1062`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EventStatus](/docs/R5/ValueSets/EventStatus.md)<br/> `http://hl7.org/fhir/ValueSet/event-status\|5.0.0` 
| [CommunicationStatus](/docs/R2/ValueSets/CommunicationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/communication-status\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `31`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `277`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EventStatus](/docs/R3/ValueSets/EventStatus.md)<br/> `http://hl7.org/fhir/ValueSet/event-status\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `358`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `581`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EventStatus](/docs/R4/ValueSets/EventStatus.md)<br/> `http://hl7.org/fhir/ValueSet/event-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1499`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1500`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EventStatus](/docs/R4B/ValueSets/EventStatus.md)<br/> `http://hl7.org/fhir/ValueSet/event-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `801`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1062`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EventStatus](/docs/R5/ValueSets/EventStatus.md)<br/> `http://hl7.org/fhir/ValueSet/event-status\|5.0.0` 
| [ProcedureStatus](/docs/R2/ValueSets/ProcedureStatus.md)<br/> `http://hl7.org/fhir/ValueSet/procedure-status\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `119`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `277`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EventStatus](/docs/R3/ValueSets/EventStatus.md)<br/> `http://hl7.org/fhir/ValueSet/event-status\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `358`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `581`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EventStatus](/docs/R4/ValueSets/EventStatus.md)<br/> `http://hl7.org/fhir/ValueSet/event-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1499`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1500`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EventStatus](/docs/R4B/ValueSets/EventStatus.md)<br/> `http://hl7.org/fhir/ValueSet/event-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `801`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1062`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EventStatus](/docs/R5/ValueSets/EventStatus.md)<br/> `http://hl7.org/fhir/ValueSet/event-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set EventStatus from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 ClinicalImpressionStatus](/docs/R2/ValueSets/ClinicalImpressionStatus.md)| Relationship | [R3 ClinicalImpressionStatus](/docs/R3/ValueSets/ClinicalImpressionStatus.md)| Relationship | [R4 ClinicalImpressionStatus](/docs/R4/ValueSets/ClinicalImpressionStatus.md)| Relationship | [R4B ClinicalImpressionStatus](/docs/R4B/ValueSets/ClinicalImpressionStatus.md)| Relationship | R5 EventStatus
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/event-status`
| | | | | | | `preparation`| _Equivalent_ <br/>(7575/9845)| **`preparation`**
| | | | | | | `in-progress`| _Equivalent_ <br/>(7573/9843)| **`in-progress`**
| | | | | | | `not-done`| _Equivalent_ <br/>(7571/9841)| **`not-done`**
| | | | | | | `on-hold`| _Equivalent_ <br/>(7574/9844)| **`on-hold`**
| | | | | | | `stopped`| _Equivalent_ <br/>(7569/9839)| **`stopped`**
| | | | | | | `completed`| _Equivalent_ <br/>(7570/9840)| **`completed`**
| | | | | | | `entered-in-error`| _Equivalent_ <br/>(7572/9842)| **`entered-in-error`**
| | | | | | | `unknown`| _Equivalent_ <br/>(7576/9846)| **`unknown`**
| *0 of 3 codes used* <br/>remaining codes:<br/>`completed`, `entered-in-error`, `in-progress`| | *0 of 3 codes used* <br/>remaining codes:<br/>`completed`, `draft`, `entered-in-error`| | *0 of 3 codes used* <br/>remaining codes:<br/>`completed`, `entered-in-error`, `in-progress`| | *8 of 3 codes used* | | *8 of 8 codes used* 


#### Map Group 1

This group is centered on the Value Set EventStatus from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 CommunicationStatus](/docs/R2/ValueSets/CommunicationStatus.md)| Relationship | [R3 EventStatus](/docs/R3/ValueSets/EventStatus.md)| Relationship | [R4 EventStatus](/docs/R4/ValueSets/EventStatus.md)| Relationship | [R4B EventStatus](/docs/R4B/ValueSets/EventStatus.md)| Relationship | R5 EventStatus
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/event-status`
| | | `preparation`| _Equivalent_ <br/>(3061/5266)| `preparation`| _Equivalent_ <br/>(15900/15901)| `preparation`| _Equivalent_ <br/>(7575/9845)| **`preparation`**
| `in-progress`| _Equivalent_ <br/>(995/2396)| `in-progress`| _Equivalent_ <br/>(3058/5263)| `in-progress`| _Equivalent_ <br/>(15902/15903)| `in-progress`| _Equivalent_ <br/>(7573/9843)| **`in-progress`**
| `aborted`| _Equivalent_ <br/>(992/2393)| `aborted`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(3054)<hr/>←←←← _Equivalent_ ←←←← <br/>(5264) | `not-done`| _Equivalent_ <br/>(15904/15905)| `not-done`| _Equivalent_ <br/>(7571/9841)| **`not-done`**
| | | `suspended`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(3060)<hr/>←←←← _Equivalent_ ←←←← <br/>(5265) | `on-hold`| _Equivalent_ <br/>(15906/15907)| `on-hold`| _Equivalent_ <br/>(7574/9844)| **`on-hold`**
| `aborted`| _Equivalent_ <br/>(992/2393)| `aborted`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(3055)<hr/>←←←← _Equivalent_ ←←←← <br/>(5267) | `stopped`| _Equivalent_ <br/>(15908/15909)| `stopped`| _Equivalent_ <br/>(7569/9839)| **`stopped`**
| `completed`| _Equivalent_ <br/>(993/2394)| `completed`| _Equivalent_ <br/>(3056/5261)| `completed`| _Equivalent_ <br/>(15910/15911)| `completed`| _Equivalent_ <br/>(7570/9840)| **`completed`**
| `entered-in-error`| _Equivalent_ <br/>(994/2395)| `entered-in-error`| _Equivalent_ <br/>(3057/5262)| `entered-in-error`| _Equivalent_ <br/>(15912/15913)| `entered-in-error`| _Equivalent_ <br/>(7572/9842)| **`entered-in-error`**
| | | `unknown`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3062)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5268) | `unknown`| _Equivalent_ <br/>(15914/15915)| `unknown`| _Equivalent_ <br/>(7576/9846)| **`unknown`**
| *4 of 5 codes used* <br/>remaining codes:<br/>`completed`, `failed`, `in-progress`, `rejected`, `suspended`| | *7 of 7 codes used* | | *8 of 8 codes used* | | *8 of 8 codes used* | | *8 of 8 codes used* 


#### Map Group 2

This group is centered on the Value Set EventStatus from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 ProcedureStatus](/docs/R2/ValueSets/ProcedureStatus.md)| Relationship | [R3 EventStatus](/docs/R3/ValueSets/EventStatus.md)| Relationship | [R4 EventStatus](/docs/R4/ValueSets/EventStatus.md)| Relationship | [R4B EventStatus](/docs/R4B/ValueSets/EventStatus.md)| Relationship | R5 EventStatus
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/event-status`
| | | `preparation`| _Equivalent_ <br/>(3061/5266)| `preparation`| _Equivalent_ <br/>(15900/15901)| `preparation`| _Equivalent_ <br/>(7575/9845)| **`preparation`**
| `in-progress`| _Equivalent_ <br/>(995/2396)| `in-progress`| _Equivalent_ <br/>(3058/5263)| `in-progress`| _Equivalent_ <br/>(15902/15903)| `in-progress`| _Equivalent_ <br/>(7573/9843)| **`in-progress`**
| `aborted`| _Equivalent_ <br/>(992/2393)| `aborted`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(3054)<hr/>←←←← _Equivalent_ ←←←← <br/>(5264) | `not-done`| _Equivalent_ <br/>(15904/15905)| `not-done`| _Equivalent_ <br/>(7571/9841)| **`not-done`**
| | | `suspended`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(3060)<hr/>←←←← _Equivalent_ ←←←← <br/>(5265) | `on-hold`| _Equivalent_ <br/>(15906/15907)| `on-hold`| _Equivalent_ <br/>(7574/9844)| **`on-hold`**
| `aborted`| _Equivalent_ <br/>(992/2393)| `aborted`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(3055)<hr/>←←←← _Equivalent_ ←←←← <br/>(5267) | `stopped`| _Equivalent_ <br/>(15908/15909)| `stopped`| _Equivalent_ <br/>(7569/9839)| **`stopped`**
| `completed`| _Equivalent_ <br/>(993/2394)| `completed`| _Equivalent_ <br/>(3056/5261)| `completed`| _Equivalent_ <br/>(15910/15911)| `completed`| _Equivalent_ <br/>(7570/9840)| **`completed`**
| `entered-in-error`| _Equivalent_ <br/>(994/2395)| `entered-in-error`| _Equivalent_ <br/>(3057/5262)| `entered-in-error`| _Equivalent_ <br/>(15912/15913)| `entered-in-error`| _Equivalent_ <br/>(7572/9842)| **`entered-in-error`**
| | | `unknown`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3062)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5268) | `unknown`| _Equivalent_ <br/>(15914/15915)| `unknown`| _Equivalent_ <br/>(7576/9846)| **`unknown`**
| *4 of 4 codes used* | | *7 of 7 codes used* | | *8 of 8 codes used* | | *8 of 8 codes used* | | *8 of 8 codes used* 

