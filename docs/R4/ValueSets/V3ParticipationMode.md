Comparison of 
Generated at Thursday, April 3, 2025 8:18:16 AM

### v3.ParticipationMode

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | v3.ParticipationMode |
| Canonical URL | `http://terminology.hl7.org/ValueSet/v3-ParticipationMode` |
| Version | 2018-08-12 |
| Description | A set of codes specifying the modality by which the Entity playing the Role is participating in the Act.  Examples:<br/><br/>Physically present, over the telephone, written communication.  Rationale:<br/><br/>Particularly for author (originator) participants this is used to specify whether the information represented by the act was initially provided verbally, (hand-)written, or electronically.  Open Issue:<br/><br/>There needs to be a reexamination of the hierarchies as there seems to be some muddling between ELECTRONIC and other concepts that involve electronic communication that are in other hierarchies. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `3411` |
| Database Concept Count | `15` |
| Database Active Concept Count | `15` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Communication` | `Communication.medium` | `http://terminology.hl7.org/ValueSet/v3-ParticipationMode` | `Example` | A channel of communication |
| `http://hl7.org/fhir/StructureDefinition/CommunicationRequest` | `CommunicationRequest.medium` | `http://terminology.hl7.org/ValueSet/v3-ParticipationMode` | `Example` | A channel of communication |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/v3-ParticipationMode`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationMode` | `DICTATE` | dictated |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationMode` | `ELECTRONIC` | electronic data |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationMode` | `EMAILWRIT` | email |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationMode` | `FACE` | face-to-face |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationMode` | `FAXWRIT` | telefax |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationMode` | `HANDWRIT` | handwritten |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationMode` | `MAILWRIT` | mail |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationMode` | `ONLINEWRIT` | online written |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationMode` | `PHONE` | telephone |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationMode` | `PHYSICAL` | physical presence |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationMode` | `REMOTE` | remote presence |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationMode` | `TYPEWRIT` | typewritten |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationMode` | `VERBAL` | verbal |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationMode` | `VIDEOCONF` | videoconferencing |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationMode` | `WRITTEN` | written |
