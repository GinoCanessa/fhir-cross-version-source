Comparison of 
Generated at Monday, April 14, 2025 6:17:19 PM

### ActionParticipantType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | ActionParticipantType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/action-participant-type` |
| Version | 3.0.2 |
| Description | The type of participant for the action |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1024` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ActivityDefinition` | `ActivityDefinition.participant.type` | `http://hl7.org/fhir/ValueSet/action-participant-type` | `Required` | patient \| practitioner \| related-person |
| `http://hl7.org/fhir/StructureDefinition/PlanDefinition` | `PlanDefinition.action.participant.type` | `http://hl7.org/fhir/ValueSet/action-participant-type` | `Required` | patient \| practitioner \| related-person |

### Referenced Systems

* `http://hl7.org/fhir/action-participant-type`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [ActionParticipantType](/docs/R3/ValueSets/ActionParticipantType.md)<br/> `http://hl7.org/fhir/ValueSet/action-participant-type\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `324`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `546`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ActionParticipantType](/docs/R4/ValueSets/ActionParticipantType.md)<br/> `http://hl7.org/fhir/ValueSet/action-participant-type\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1343`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1344`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ActionParticipantType](/docs/R4B/ValueSets/ActionParticipantType.md)<br/> `http://hl7.org/fhir/ValueSet/action-participant-type\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `769`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1030`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ActionParticipantType](/docs/R5/ValueSets/ActionParticipantType.md)<br/> `http://hl7.org/fhir/ValueSet/action-participant-type\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set ActionParticipantType from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | R3 ActionParticipantType| Relationship | [R4 ActionParticipantType](/docs/R4/ValueSets/ActionParticipantType.md)| Relationship | [R4B ActionParticipantType](/docs/R4B/ValueSets/ActionParticipantType.md)| Relationship | [R5 ActionParticipantType](/docs/R5/ValueSets/ActionParticipantType.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/action-participant-type`
| | | **`patient`**| _Equivalent_ <br/>(2888/5075)| `patient`| _Equivalent_ <br/>(13882/13883)| `patient`| _Equivalent_ <br/>(7422/9683)| `patient`
| | | **`practitioner`**| _Equivalent_ <br/>(2887/5076)| `practitioner`| _Equivalent_ <br/>(13884/13885)| `practitioner`| _Equivalent_ <br/>(7423/9681)| `practitioner`
| | | **`related-person`**| _Equivalent_ <br/>(2886/5077)| `related-person`| _Equivalent_ <br/>(13886/13887)| `related-person`| _Equivalent_ <br/>(7424/9686)| `relatedperson`
| | | *3 of 3 codes used* | | *3 of 4 codes used* <br/>remaining codes:<br/>`device`| | *3 of 4 codes used* <br/>remaining codes:<br/>`device`| | *3 of 10 codes used* <br/>remaining codes:<br/>`careteam`, `device`, `group`, `healthcareservice`, `location`, `organization`, `practitionerrole`

