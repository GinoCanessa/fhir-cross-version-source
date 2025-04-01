Comparison of 
Generated at Tuesday, April 1, 2025 1:39:07 PM

### ParticipantStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | ParticipantStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/participantstatus` |
| Version | 1.0.2 |
| Description | The Participation status of an appointment. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `270` |
| Database Concept Count | `6` |
| Database Active Concept Count | `6` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/AppointmentResponse` | `AppointmentResponse.participantStatus` | `http://hl7.org/fhir/ValueSet/participantstatus` | `Required` | accepted \| declined \| tentative \| in-process \| completed \| needs-action |

### Referenced Systems

* `http://hl7.org/fhir/participantstatus`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ParticipantStatus](/docs/R2/ValueSets/ParticipantStatus.md)<br/> `http://hl7.org/fhir/ValueSet/participantstatus\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `14`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `173`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ParticipationStatus](/docs/R3/ValueSets/ParticipationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/participationstatus\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `336`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `558`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ParticipationStatus](/docs/R4/ValueSets/ParticipationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/participationstatus\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1649`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1650`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ParticipationStatus](/docs/R4B/ValueSets/ParticipationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/participationstatus\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `780`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1041`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AppointmentResponseStatus](/docs/R5/ValueSets/AppointmentResponseStatus.md)<br/> `http://hl7.org/fhir/ValueSet/appointmentresponse-status\|5.0.0` 
| [ParticipantStatus](/docs/R2/ValueSets/ParticipantStatus.md)<br/> `http://hl7.org/fhir/ValueSet/participantstatus\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `14`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `173`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ParticipationStatus](/docs/R3/ValueSets/ParticipationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/participationstatus\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `336`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `558`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ParticipationStatus](/docs/R4/ValueSets/ParticipationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/participationstatus\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1649`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1650`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ParticipationStatus](/docs/R4B/ValueSets/ParticipationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/participationstatus\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `780`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1041`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ParticipationStatus](/docs/R5/ValueSets/ParticipationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/participationstatus\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set ParticipantStatus from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 ParticipantStatus| Relationship | [R3 ParticipationStatus](/docs/R3/ValueSets/ParticipationStatus.md)| Relationship | [R4 ParticipationStatus](/docs/R4/ValueSets/ParticipationStatus.md)| Relationship | [R4B ParticipationStatus](/docs/R4B/ValueSets/ParticipationStatus.md)| Relationship | [R5 AppointmentResponseStatus](/docs/R5/ValueSets/AppointmentResponseStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/participantstatus`
| **`accepted`**| →→→→ _Equivalent_ →→→→ <br/>(63)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1436) | `accepted`| _Equivalent_ <br/>(2928/5129)| `accepted`| _Equivalent_ <br/>(16740/16741)| `accepted`| _Equivalent_ <br/>(7457/9722)| `accepted`
| **`declined`**| _Equivalent_ <br/>(65/1434)| `declined`| _Equivalent_ <br/>(2926/5127)| `declined`| _Equivalent_ <br/>(16742/16743)| `declined`| _Equivalent_ <br/>(7455/9720)| `declined`
| **`tentative`**| _Equivalent_ <br/>(68/1438)| `tentative`| _Equivalent_ <br/>(2929/5130)| `tentative`| _Equivalent_ <br/>(16744/16745)| `tentative`| _Equivalent_ <br/>(7458/9723)| `tentative`
| **`in-process`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(66)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1437) | `accepted`| _Equivalent_ <br/>(2928/5129)| `accepted`| _Equivalent_ <br/>(16740/16741)| `accepted`| _Equivalent_ <br/>(7457/9722)| `accepted`
| **`completed`**| | | | | | | | | 
| **`needs-action`**| _Equivalent_ <br/>(67/1435)| `needs-action`| _Equivalent_ <br/>(2927/5128)| `needs-action`| _Equivalent_ <br/>(16746/16747)| `needs-action`| _Equivalent_ <br/>(7456/9721)| `needs-action`
| *6 of 6 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 5 codes used* 


#### Map Group 1

This group is centered on the Value Set ParticipantStatus from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 ParticipantStatus| Relationship | [R3 ParticipationStatus](/docs/R3/ValueSets/ParticipationStatus.md)| Relationship | [R4 ParticipationStatus](/docs/R4/ValueSets/ParticipationStatus.md)| Relationship | [R4B ParticipationStatus](/docs/R4B/ValueSets/ParticipationStatus.md)| Relationship | [R5 ParticipationStatus](/docs/R5/ValueSets/ParticipationStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/participantstatus`
| **`accepted`**| →→→→ _Equivalent_ →→→→ <br/>(63)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1436) | `accepted`| _Equivalent_ <br/>(2928/5129)| `accepted`| _Equivalent_ <br/>(16740/16741)| `accepted`| _Equivalent_ <br/>(7457/9722)| `accepted`
| **`declined`**| _Equivalent_ <br/>(65/1434)| `declined`| _Equivalent_ <br/>(2926/5127)| `declined`| _Equivalent_ <br/>(16742/16743)| `declined`| _Equivalent_ <br/>(7455/9720)| `declined`
| **`tentative`**| _Equivalent_ <br/>(68/1438)| `tentative`| _Equivalent_ <br/>(2929/5130)| `tentative`| _Equivalent_ <br/>(16744/16745)| `tentative`| _Equivalent_ <br/>(7458/9723)| `tentative`
| **`in-process`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(66)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1437) | `accepted`| _Equivalent_ <br/>(2928/5129)| `accepted`| _Equivalent_ <br/>(16740/16741)| `accepted`| _Equivalent_ <br/>(7457/9722)| `accepted`
| **`completed`**| | | | | | | | | 
| **`needs-action`**| _Equivalent_ <br/>(67/1435)| `needs-action`| _Equivalent_ <br/>(2927/5128)| `needs-action`| _Equivalent_ <br/>(16746/16747)| `needs-action`| _Equivalent_ <br/>(7456/9721)| `needs-action`
| *6 of 6 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* 

