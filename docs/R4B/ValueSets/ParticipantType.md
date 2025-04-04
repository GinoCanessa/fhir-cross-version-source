Comparison of 
Generated at Friday, April 4, 2025 2:58:51 PM

### ParticipantType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | ParticipantType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/encounter-participant-type` |
| Version | 4.3.0 |
| Description | This value set defines a set of codes that can be used to indicate how an individual participates in an encounter. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `3736` |
| Database Concept Count | `12` |
| Database Active Concept Count | `12` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Appointment` | `Appointment.participant.type` | `http://hl7.org/fhir/ValueSet/encounter-participant-type` | `Extensible` | Role of participant in the appointment |
| `http://hl7.org/fhir/StructureDefinition/AppointmentResponse` | `AppointmentResponse.participantType` | `http://hl7.org/fhir/ValueSet/encounter-participant-type` | `Extensible` | Role of participant in the appointment |
| `http://hl7.org/fhir/StructureDefinition/Encounter` | `Encounter.participant.type` | `http://hl7.org/fhir/ValueSet/encounter-participant-type` | `Extensible` | Role of participant in encounter |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/v3-ParticipationType`
* `http://terminology.hl7.org/CodeSystem/participant-type`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [ParticipantType](/docs/R4B/ValueSets/ParticipantType.md)<br/> `http://hl7.org/fhir/ValueSet/encounter-participant-type\|4.3.0` | →→→→→→→<br/>``<br/>- DBKey: `781`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `1042`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ParticipantType](/docs/R5/ValueSets/ParticipantType.md)<br/> `http://hl7.org/fhir/ValueSet/encounter-participant-type\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set ParticipantType from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | R4B ParticipantType| Relationship | [R5 ParticipantType](/docs/R5/ValueSets/ParticipantType.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://terminology.hl7.org/CodeSystem/v3-ParticipationType`
| | | | | | | **`ADM`**| _Equivalent_ <br/>(7461/9726)| `ADM`
| | | | | | | **`ATND`**| _Equivalent_ <br/>(7462/9727)| `ATND`
| | | | | | | **`CALLBCK`**| _Equivalent_ <br/>(7463/9728)| `CALLBCK`
| | | | | | | **`CON`**| _Equivalent_ <br/>(7464/9729)| `CON`
| | | | | | | **`DIS`**| _Equivalent_ <br/>(7465/9730)| `DIS`
| | | | | | | **`ESC`**| _Equivalent_ <br/>(7466/9731)| `ESC`
| | | | | | | **`REF`**| _Equivalent_ <br/>(7469/9732)| `REF`
| | | | | | | **`SPRF`**| | | 
| | | | | | | **`PPRF`**| | | 
| | | | | | | **`PART`**| | | 
| <td colspan="8">**R4B** System: `http://terminology.hl7.org/CodeSystem/participant-type`
| | | | | | | **`translator`**| _Equivalent_ <br/>(7460/9725)| `translator`
| | | | | | | **`emergency`**| _Equivalent_ <br/>(7459/9724)| `emergency`
| | | | | | | *12 of 12 codes used* | | *9 of 9 codes used* 

