Comparison of 
Generated at Friday, April 4, 2025 2:58:36 PM

### ParticipantType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | ParticipantType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/encounter-participant-type` |
| Version | 3.0.2 |
| Description | This value set defines a set of codes that can be used to indicate how an individual participates in an encounter. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1208` |
| Database Concept Count | `12` |
| Database Active Concept Count | `12` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Appointment` | `Appointment.participant.type` | `http://hl7.org/fhir/ValueSet/encounter-participant-type` | `Extensible` | Role of participant in the appointment |
| `http://hl7.org/fhir/StructureDefinition/AppointmentResponse` | `AppointmentResponse.participantType` | `http://hl7.org/fhir/ValueSet/encounter-participant-type` | `Extensible` | Role of participant in the appointment |
| `http://hl7.org/fhir/StructureDefinition/Encounter` | `Encounter.participant.type` | `http://hl7.org/fhir/ValueSet/encounter-participant-type` | `Extensible` | Role of participant in encounter |

### Referenced Systems

* `http://hl7.org/fhir/v3/ParticipationType`
* `http://hl7.org/fhir/participant-type`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ParticipantType](/docs/R2/ValueSets/ParticipantType.md)<br/> `http://hl7.org/fhir/ValueSet/encounter-participant-type\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `12`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `171`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ParticipantType](/docs/R3/ValueSets/ParticipantType.md)<br/> `http://hl7.org/fhir/ValueSet/encounter-participant-type\|3.0.2` | →→→→→→→<br/>``<br/>- DBKey: `337`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `559`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ParticipantType](/docs/R4/ValueSets/ParticipantType.md)<br/> `http://hl7.org/fhir/ValueSet/encounter-participant-type\|4.0.1` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set ParticipantType from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 ParticipantType](/docs/R2/ValueSets/ParticipantType.md)| Relationship | R3 ParticipantType| Relationship | [R4 ParticipantType](/docs/R4/ValueSets/ParticipantType.md)| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/v3/ParticipationType`
| `ADM`| _Equivalent_ <br/>(44/1414)| **`ADM`**| →→→→ _Equivalent_ →→→→ <br/>(2938)<hr/>←←←← __ ←←←← <br/>() | `ADM`| | | | | 
| `ADM`| _Equivalent_ <br/>(44/1414)| **`ADM`**| _Equivalent_ <br/>(2947/5151)| `ADM`| | | | | 
| `ATND`| _Equivalent_ <br/>(45/1415)| **`ATND`**| →→→→ _Equivalent_ →→→→ <br/>(2930)<hr/>←←←← __ ←←←← <br/>() | `ATND`| | | | | 
| `ATND`| _Equivalent_ <br/>(45/1415)| **`ATND`**| _Equivalent_ <br/>(2944/5143)| `ATND`| | | | | 
| `CALLBCK`| _Equivalent_ <br/>(46/1416)| **`CALLBCK`**| →→→→ _Equivalent_ →→→→ <br/>(2931)<hr/>←←←← __ ←←←← <br/>() | `CALLBCK`| | | | | 
| `CALLBCK`| _Equivalent_ <br/>(46/1416)| **`CALLBCK`**| _Equivalent_ <br/>(2946/5144)| `CALLBCK`| | | | | 
| `CON`| _Equivalent_ <br/>(47/1417)| **`CON`**| →→→→ _Equivalent_ →→→→ <br/>(2934)<hr/>←←←← __ ←←←← <br/>() | `CON`| | | | | 
| `CON`| _Equivalent_ <br/>(47/1417)| **`CON`**| _Equivalent_ <br/>(2945/5147)| `CON`| | | | | 
| `DIS`| _Equivalent_ <br/>(48/1418)| **`DIS`**| →→→→ _Equivalent_ →→→→ <br/>(2935)<hr/>←←←← __ ←←←← <br/>() | `DIS`| | | | | 
| `DIS`| _Equivalent_ <br/>(48/1418)| **`DIS`**| _Equivalent_ <br/>(2950/5148)| `DIS`| | | | | 
| `ESC`| _Equivalent_ <br/>(49/1419)| **`ESC`**| →→→→ _Equivalent_ →→→→ <br/>(2933)<hr/>←←←← __ ←←←← <br/>() | `ESC`| | | | | 
| `ESC`| _Equivalent_ <br/>(49/1419)| **`ESC`**| _Equivalent_ <br/>(2952/5146)| `ESC`| | | | | 
| `REF`| _Equivalent_ <br/>(52/1422)| **`REF`**| →→→→ _Equivalent_ →→→→ <br/>(2932)<hr/>←←←← __ ←←←← <br/>() | `REF`| | | | | 
| `REF`| _Equivalent_ <br/>(52/1422)| **`REF`**| _Equivalent_ <br/>(2948/5145)| `REF`| | | | | 
| `SPRF`| _Equivalent_ <br/>(53/1423)| **`SPRF`**| →→→→ _Equivalent_ →→→→ <br/>(2937)<hr/>←←←← __ ←←←← <br/>() | `SPRF`| | | | | 
| `SPRF`| _Equivalent_ <br/>(53/1423)| **`SPRF`**| _Equivalent_ <br/>(2951/5150)| `SPRF`| | | | | 
| `PPRF`| _Equivalent_ <br/>(51/1421)| **`PPRF`**| →→→→ _Equivalent_ →→→→ <br/>(2939)<hr/>←←←← __ ←←←← <br/>() | `PPRF`| | | | | 
| `PPRF`| _Equivalent_ <br/>(51/1421)| **`PPRF`**| _Equivalent_ <br/>(2949/5152)| `PPRF`| | | | | 
| `PART`| _Equivalent_ <br/>(50/1420)| **`PART`**| →→→→ _Equivalent_ →→→→ <br/>(2936)<hr/>←←←← __ ←←←← <br/>() | `PART`| | | | | 
| `PART`| _Equivalent_ <br/>(50/1420)| **`PART`**| _Equivalent_ <br/>(2953/5149)| `PART`| | | | | 
| <td colspan="8">**R3** System: `http://hl7.org/fhir/participant-type`
| `translator`| _Equivalent_ <br/>(55/1425)| **`translator`**| →→→→ _Equivalent_ →→→→ <br/>(2940)<hr/>←←←← __ ←←←← <br/>() | `translator`| | | | | 
| `translator`| _Equivalent_ <br/>(55/1425)| **`translator`**| _Equivalent_ <br/>(2942/5153)| `translator`| | | | | 
| `emergency`| _Equivalent_ <br/>(54/1424)| **`emergency`**| →→→→ _Equivalent_ →→→→ <br/>(2941)<hr/>←←←← __ ←←←← <br/>() | `emergency`| | | | | 
| `emergency`| _Equivalent_ <br/>(54/1424)| **`emergency`**| _Equivalent_ <br/>(2943/5154)| `emergency`| | | | | 
| *12 of 12 codes used* | | *12 of 12 codes used* | | *12 of 12 codes used* | | | | 

