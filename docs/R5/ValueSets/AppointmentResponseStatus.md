Comparison of 
Generated at Thursday, April 3, 2025 8:18:32 AM

### AppointmentResponseStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | AppointmentResponseStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/appointmentresponse-status` |
| Version | 5.0.0 |
| Description | The Participation status for a participant in response to a request for an appointment. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4293` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/AppointmentResponse` | `AppointmentResponse.participantStatus` | `http://hl7.org/fhir/ValueSet/appointmentresponse-status\|5.0.0` | `Required` | accepted \| declined \| tentative \| needs-action \| entered-in-error |

### Referenced Systems

* `http://hl7.org/fhir/participationstatus`
* `http://hl7.org/fhir/appointmentstatus`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ParticipantStatus](/docs/R2/ValueSets/ParticipantStatus.md)<br/> `http://hl7.org/fhir/ValueSet/participantstatus\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `14`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `170`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ParticipationStatus](/docs/R3/ValueSets/ParticipationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/participationstatus\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `336`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `558`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ParticipationStatus](/docs/R4/ValueSets/ParticipationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/participationstatus\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1649`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1650`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ParticipationStatus](/docs/R4B/ValueSets/ParticipationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/participationstatus\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `783`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1044`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AppointmentResponseStatus](/docs/R5/ValueSets/AppointmentResponseStatus.md)<br/> `http://hl7.org/fhir/ValueSet/appointmentresponse-status\|5.0.0` 
| [ParticipationStatus](/docs/R2/ValueSets/ParticipationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/participationstatus\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `11`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `170`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ParticipationStatus](/docs/R3/ValueSets/ParticipationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/participationstatus\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `336`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `558`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ParticipationStatus](/docs/R4/ValueSets/ParticipationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/participationstatus\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1649`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1650`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ParticipationStatus](/docs/R4B/ValueSets/ParticipationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/participationstatus\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `783`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1044`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AppointmentResponseStatus](/docs/R5/ValueSets/AppointmentResponseStatus.md)<br/> `http://hl7.org/fhir/ValueSet/appointmentresponse-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set AppointmentResponseStatus from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 ParticipantStatus](/docs/R2/ValueSets/ParticipantStatus.md)| Relationship | [R3 ParticipationStatus](/docs/R3/ValueSets/ParticipationStatus.md)| Relationship | [R4 ParticipationStatus](/docs/R4/ValueSets/ParticipationStatus.md)| Relationship | [R4B ParticipationStatus](/docs/R4B/ValueSets/ParticipationStatus.md)| Relationship | R5 AppointmentResponseStatus
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/participationstatus`
| `accepted`| →→→→ _Equivalent_ →→→→ <br/>(42)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1412) | `accepted`| _Equivalent_ <br/>(2928/5129)| `accepted`| _Equivalent_ <br/>(16740/16741)| `accepted`| _Equivalent_ <br/>(7481/9743)| **`accepted`**
| `declined`| _Equivalent_ <br/>(40/1410)| `declined`| _Equivalent_ <br/>(2926/5127)| `declined`| _Equivalent_ <br/>(16742/16743)| `declined`| _Equivalent_ <br/>(7482/9744)| **`declined`**
| `tentative`| _Equivalent_ <br/>(43/1413)| `tentative`| _Equivalent_ <br/>(2929/5130)| `tentative`| _Equivalent_ <br/>(16744/16745)| `tentative`| _Equivalent_ <br/>(7484/9746)| **`tentative`**
| `needs-action`| _Equivalent_ <br/>(41/1411)| `needs-action`| _Equivalent_ <br/>(2927/5128)| `needs-action`| _Equivalent_ <br/>(16746/16747)| `needs-action`| _Equivalent_ <br/>(7483/9745)| **`needs-action`**
| <td colspan="8">**R5** System: `http://hl7.org/fhir/appointmentstatus`
| | | | | | | | | **`entered-in-error`**
| *4 of 6 codes used* <br/>remaining codes:<br/>`accepted`, `completed`, `declined`, `in-process`, `needs-action`, `tentative`| | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *5 of 5 codes used* 


#### Map Group 1

This group is centered on the Value Set AppointmentResponseStatus from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 ParticipationStatus](/docs/R2/ValueSets/ParticipationStatus.md)| Relationship | [R3 ParticipationStatus](/docs/R3/ValueSets/ParticipationStatus.md)| Relationship | [R4 ParticipationStatus](/docs/R4/ValueSets/ParticipationStatus.md)| Relationship | [R4B ParticipationStatus](/docs/R4B/ValueSets/ParticipationStatus.md)| Relationship | R5 AppointmentResponseStatus
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/participationstatus`
| `accepted`| →→→→ _Equivalent_ →→→→ <br/>(42)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1412) | `accepted`| _Equivalent_ <br/>(2928/5129)| `accepted`| _Equivalent_ <br/>(16740/16741)| `accepted`| _Equivalent_ <br/>(7481/9743)| **`accepted`**
| `declined`| _Equivalent_ <br/>(40/1410)| `declined`| _Equivalent_ <br/>(2926/5127)| `declined`| _Equivalent_ <br/>(16742/16743)| `declined`| _Equivalent_ <br/>(7482/9744)| **`declined`**
| `tentative`| _Equivalent_ <br/>(43/1413)| `tentative`| _Equivalent_ <br/>(2929/5130)| `tentative`| _Equivalent_ <br/>(16744/16745)| `tentative`| _Equivalent_ <br/>(7484/9746)| **`tentative`**
| `needs-action`| _Equivalent_ <br/>(41/1411)| `needs-action`| _Equivalent_ <br/>(2927/5128)| `needs-action`| _Equivalent_ <br/>(16746/16747)| `needs-action`| _Equivalent_ <br/>(7483/9745)| **`needs-action`**
| <td colspan="8">**R5** System: `http://hl7.org/fhir/appointmentstatus`
| | | | | | | | | **`entered-in-error`**
| *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *5 of 5 codes used* 

