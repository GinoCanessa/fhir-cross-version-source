Comparison of 
Generated at Monday, April 14, 2025 6:17:27 PM

### ParticipationStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | ParticipationStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/participationstatus` |
| Version | 4.0.1 |
| Description | The Participation status of an appointment. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2635` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Appointment` | `Appointment.participant.status` | `http://hl7.org/fhir/ValueSet/participationstatus\|4.0.1` | `Required` | accepted \| declined \| tentative \| needs-action |
| `http://hl7.org/fhir/StructureDefinition/AppointmentResponse` | `AppointmentResponse.participantStatus` | `http://hl7.org/fhir/ValueSet/participationstatus\|4.0.1` | `Required` | accepted \| declined \| tentative \| needs-action |

### Referenced Systems

* `http://hl7.org/fhir/participationstatus`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ParticipantStatus](/docs/R2/ValueSets/ParticipantStatus.md)<br/> `http://hl7.org/fhir/ValueSet/participantstatus\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `14`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>*no map*<br/>←←←←←←←| [ParticipationStatus](/docs/R3/ValueSets/ParticipationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/participationstatus\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `336`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `558`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [ParticipationStatus](/docs/R4/ValueSets/ParticipationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/participationstatus\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1649`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1650`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ParticipationStatus](/docs/R4B/ValueSets/ParticipationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/participationstatus\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `783`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1044`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [AppointmentResponseStatus](/docs/R5/ValueSets/AppointmentResponseStatus.md)<br/> `http://hl7.org/fhir/ValueSet/appointmentresponse-status\|5.0.0` 
| [ParticipationStatus](/docs/R2/ValueSets/ParticipationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/participationstatus\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `11`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>*no map*<br/>←←←←←←←| [ParticipationStatus](/docs/R3/ValueSets/ParticipationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/participationstatus\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `336`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `558`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [ParticipationStatus](/docs/R4/ValueSets/ParticipationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/participationstatus\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1649`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1650`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ParticipationStatus](/docs/R4B/ValueSets/ParticipationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/participationstatus\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `783`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1044`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [AppointmentResponseStatus](/docs/R5/ValueSets/AppointmentResponseStatus.md)<br/> `http://hl7.org/fhir/ValueSet/appointmentresponse-status\|5.0.0` 
| [ParticipantStatus](/docs/R2/ValueSets/ParticipantStatus.md)<br/> `http://hl7.org/fhir/ValueSet/participantstatus\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `14`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>*no map*<br/>←←←←←←←| [ParticipationStatus](/docs/R3/ValueSets/ParticipationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/participationstatus\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `336`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `558`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [ParticipationStatus](/docs/R4/ValueSets/ParticipationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/participationstatus\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1649`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1650`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ParticipationStatus](/docs/R4B/ValueSets/ParticipationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/participationstatus\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `780`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1041`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [ParticipationStatus](/docs/R5/ValueSets/ParticipationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/participationstatus\|5.0.0` 
| [ParticipationStatus](/docs/R2/ValueSets/ParticipationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/participationstatus\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `11`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>*no map*<br/>←←←←←←←| [ParticipationStatus](/docs/R3/ValueSets/ParticipationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/participationstatus\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `336`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `558`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [ParticipationStatus](/docs/R4/ValueSets/ParticipationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/participationstatus\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1649`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1650`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ParticipationStatus](/docs/R4B/ValueSets/ParticipationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/participationstatus\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `780`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1041`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [ParticipationStatus](/docs/R5/ValueSets/ParticipationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/participationstatus\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set ParticipationStatus from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 ParticipantStatus](/docs/R2/ValueSets/ParticipantStatus.md)| Relationship | [R3 ParticipationStatus](/docs/R3/ValueSets/ParticipationStatus.md)| Relationship | R4 ParticipationStatus| Relationship | [R4B ParticipationStatus](/docs/R4B/ValueSets/ParticipationStatus.md)| Relationship | [R5 AppointmentResponseStatus](/docs/R5/ValueSets/AppointmentResponseStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://hl7.org/fhir/participationstatus`
| `accepted`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(63)<hr/>←←←← __ ←←←← <br/>() | `accepted`| _Equivalent_ <br/>(2928/5129)| **`accepted`**| _Equivalent_ <br/>(16740/16741)| `accepted`| _Equivalent_ <br/>(7481/9743)| `accepted`
| `in-process`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(66)<hr/>←←←← __ ←←←← <br/>() | `accepted`| _Equivalent_ <br/>(2928/5129)| **`accepted`**| _Equivalent_ <br/>(16740/16741)| `accepted`| _Equivalent_ <br/>(7481/9743)| `accepted`
| `declined`| _Equivalent_ <br/>(65/1434)| `declined`| _Equivalent_ <br/>(2926/5127)| **`declined`**| _Equivalent_ <br/>(16742/16743)| `declined`| _Equivalent_ <br/>(7482/9744)| `declined`
| `tentative`| _Equivalent_ <br/>(68/1438)| `tentative`| _Equivalent_ <br/>(2929/5130)| **`tentative`**| _Equivalent_ <br/>(16744/16745)| `tentative`| _Equivalent_ <br/>(7484/9746)| `tentative`
| `needs-action`| _Equivalent_ <br/>(67/1435)| `needs-action`| _Equivalent_ <br/>(2927/5128)| **`needs-action`**| _Equivalent_ <br/>(16746/16747)| `needs-action`| _Equivalent_ <br/>(7483/9745)| `needs-action`
| *5 of 6 codes used* <br/>remaining codes:<br/>`completed`| | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 5 codes used* <br/>remaining codes:<br/>`entered-in-error`


#### Map Group 1

This group is centered on the Value Set ParticipationStatus from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 ParticipationStatus](/docs/R2/ValueSets/ParticipationStatus.md)| Relationship | [R3 ParticipationStatus](/docs/R3/ValueSets/ParticipationStatus.md)| Relationship | R4 ParticipationStatus| Relationship | [R4B ParticipationStatus](/docs/R4B/ValueSets/ParticipationStatus.md)| Relationship | [R5 AppointmentResponseStatus](/docs/R5/ValueSets/AppointmentResponseStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://hl7.org/fhir/participationstatus`
| `accepted`| _Equivalent_ <br/>(42/1412)| `accepted`| _Equivalent_ <br/>(2928/5129)| **`accepted`**| _Equivalent_ <br/>(16740/16741)| `accepted`| _Equivalent_ <br/>(7481/9743)| `accepted`
| `declined`| _Equivalent_ <br/>(40/1410)| `declined`| _Equivalent_ <br/>(2926/5127)| **`declined`**| _Equivalent_ <br/>(16742/16743)| `declined`| _Equivalent_ <br/>(7482/9744)| `declined`
| `tentative`| _Equivalent_ <br/>(43/1413)| `tentative`| _Equivalent_ <br/>(2929/5130)| **`tentative`**| _Equivalent_ <br/>(16744/16745)| `tentative`| _Equivalent_ <br/>(7484/9746)| `tentative`
| `needs-action`| _Equivalent_ <br/>(41/1411)| `needs-action`| _Equivalent_ <br/>(2927/5128)| **`needs-action`**| _Equivalent_ <br/>(16746/16747)| `needs-action`| _Equivalent_ <br/>(7483/9745)| `needs-action`
| *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 5 codes used* <br/>remaining codes:<br/>`entered-in-error`


#### Map Group 2

This group is centered on the Value Set ParticipationStatus from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 ParticipantStatus](/docs/R2/ValueSets/ParticipantStatus.md)| Relationship | [R3 ParticipationStatus](/docs/R3/ValueSets/ParticipationStatus.md)| Relationship | R4 ParticipationStatus| Relationship | [R4B ParticipationStatus](/docs/R4B/ValueSets/ParticipationStatus.md)| Relationship | [R5 ParticipationStatus](/docs/R5/ValueSets/ParticipationStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://hl7.org/fhir/participationstatus`
| `accepted`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(63)<hr/>←←←← __ ←←←← <br/>() | `accepted`| _Equivalent_ <br/>(2928/5129)| **`accepted`**| _Equivalent_ <br/>(16740/16741)| `accepted`| _Equivalent_ <br/>(7457/9722)| `accepted`
| `in-process`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(66)<hr/>←←←← __ ←←←← <br/>() | `accepted`| _Equivalent_ <br/>(2928/5129)| **`accepted`**| _Equivalent_ <br/>(16740/16741)| `accepted`| _Equivalent_ <br/>(7457/9722)| `accepted`
| `declined`| _Equivalent_ <br/>(65/1434)| `declined`| _Equivalent_ <br/>(2926/5127)| **`declined`**| _Equivalent_ <br/>(16742/16743)| `declined`| _Equivalent_ <br/>(7455/9720)| `declined`
| `tentative`| _Equivalent_ <br/>(68/1438)| `tentative`| _Equivalent_ <br/>(2929/5130)| **`tentative`**| _Equivalent_ <br/>(16744/16745)| `tentative`| _Equivalent_ <br/>(7458/9723)| `tentative`
| `needs-action`| _Equivalent_ <br/>(67/1435)| `needs-action`| _Equivalent_ <br/>(2927/5128)| **`needs-action`**| _Equivalent_ <br/>(16746/16747)| `needs-action`| _Equivalent_ <br/>(7456/9721)| `needs-action`
| *5 of 6 codes used* <br/>remaining codes:<br/>`completed`| | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* 


#### Map Group 3

This group is centered on the Value Set ParticipationStatus from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 ParticipationStatus](/docs/R2/ValueSets/ParticipationStatus.md)| Relationship | [R3 ParticipationStatus](/docs/R3/ValueSets/ParticipationStatus.md)| Relationship | R4 ParticipationStatus| Relationship | [R4B ParticipationStatus](/docs/R4B/ValueSets/ParticipationStatus.md)| Relationship | [R5 ParticipationStatus](/docs/R5/ValueSets/ParticipationStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://hl7.org/fhir/participationstatus`
| `accepted`| _Equivalent_ <br/>(42/1412)| `accepted`| _Equivalent_ <br/>(2928/5129)| **`accepted`**| _Equivalent_ <br/>(16740/16741)| `accepted`| _Equivalent_ <br/>(7457/9722)| `accepted`
| `declined`| _Equivalent_ <br/>(40/1410)| `declined`| _Equivalent_ <br/>(2926/5127)| **`declined`**| _Equivalent_ <br/>(16742/16743)| `declined`| _Equivalent_ <br/>(7455/9720)| `declined`
| `tentative`| _Equivalent_ <br/>(43/1413)| `tentative`| _Equivalent_ <br/>(2929/5130)| **`tentative`**| _Equivalent_ <br/>(16744/16745)| `tentative`| _Equivalent_ <br/>(7458/9723)| `tentative`
| `needs-action`| _Equivalent_ <br/>(41/1411)| `needs-action`| _Equivalent_ <br/>(2927/5128)| **`needs-action`**| _Equivalent_ <br/>(16746/16747)| `needs-action`| _Equivalent_ <br/>(7456/9721)| `needs-action`
| *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* 

