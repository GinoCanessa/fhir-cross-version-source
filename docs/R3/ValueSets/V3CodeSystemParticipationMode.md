Comparison of 
Generated at Monday, April 14, 2025 6:17:20 PM

### v3 Code System ParticipationMode

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | v3 Code System ParticipationMode |
| Canonical URL | `http://hl7.org/fhir/ValueSet/v3-ParticipationMode` |
| Version | 2016-11-11 |
| Description | A set of codes specifying the modality by which the Entity playing the Role is participating in the Act.  Examples:<br/><br/>Physically present, over the telephone, written communication.  Rationale:<br/><br/>Particularly for author (originator) participants this is used to specify whether the information represented by the act was initially provided verbally, (hand-)written, or electronically.  Open Issue:<br/><br/>There needs to be a reexamination of the hierarchies as there seems to be some muddling between ELECTRONIC and other concepts that involve electronic communication that are in other hierarchies. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `2089` |
| Database Concept Count | `15` |
| Database Active Concept Count | `15` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Communication` | `Communication.medium` | `http://hl7.org/fhir/ValueSet/v3-ParticipationMode` | `Example` | A channel of communication |
| `http://hl7.org/fhir/StructureDefinition/CommunicationRequest` | `CommunicationRequest.medium` | `http://hl7.org/fhir/ValueSet/v3-ParticipationMode` | `Example` | A channel of communication |

### Referenced Systems

* `http://hl7.org/fhir/v3/ParticipationMode`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/v3/ParticipationMode` | `DICTATE` | dictated |
| `http://hl7.org/fhir/v3/ParticipationMode` | `ELECTRONIC` | electronic data |
| `http://hl7.org/fhir/v3/ParticipationMode` | `EMAILWRIT` | email |
| `http://hl7.org/fhir/v3/ParticipationMode` | `FACE` | face-to-face |
| `http://hl7.org/fhir/v3/ParticipationMode` | `FAXWRIT` | telefax |
| `http://hl7.org/fhir/v3/ParticipationMode` | `HANDWRIT` | handwritten |
| `http://hl7.org/fhir/v3/ParticipationMode` | `MAILWRIT` | mail |
| `http://hl7.org/fhir/v3/ParticipationMode` | `ONLINEWRIT` | online written |
| `http://hl7.org/fhir/v3/ParticipationMode` | `PHONE` | telephone |
| `http://hl7.org/fhir/v3/ParticipationMode` | `PHYSICAL` | physical presence |
| `http://hl7.org/fhir/v3/ParticipationMode` | `REMOTE` | remote presence |
| `http://hl7.org/fhir/v3/ParticipationMode` | `TYPEWRIT` | typewritten |
| `http://hl7.org/fhir/v3/ParticipationMode` | `VERBAL` | verbal |
| `http://hl7.org/fhir/v3/ParticipationMode` | `VIDEOCONF` | videoconferencing |
| `http://hl7.org/fhir/v3/ParticipationMode` | `WRITTEN` | written |
