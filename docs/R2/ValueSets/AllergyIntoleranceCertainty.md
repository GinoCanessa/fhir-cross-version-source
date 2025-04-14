Comparison of 
Generated at Monday, April 14, 2025 6:17:14 PM

### AllergyIntoleranceCertainty

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | AllergyIntoleranceCertainty |
| Canonical URL | `http://hl7.org/fhir/ValueSet/reaction-event-certainty` |
| Version | 1.0.2 |
| Description | Statement about the degree of clinical certainty that a Specific Substance was the cause of the Manifestation in an reaction event. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `331` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/AllergyIntolerance` | `AllergyIntolerance.reaction.certainty` | `http://hl7.org/fhir/ValueSet/reaction-event-certainty` | `Required` | unlikely \| likely \| confirmed - clinical certainty about the specific substance |

### Referenced Systems

* `http://hl7.org/fhir/reaction-event-certainty`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [AllergyIntoleranceCertainty](/docs/R2/ValueSets/AllergyIntoleranceCertainty.md)<br/> `http://hl7.org/fhir/ValueSet/reaction-event-certainty\|1.0.2` | →→→→→→→<br/>``<br/>- DBKey: `1301`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `1302`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [AllergyIntoleranceCertainty](/docs/R3/ValueSets/AllergyIntoleranceCertainty.md)<br/> `http://hl7.org/fhir/ValueSet/reaction-event-certainty\|3.0.2` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set AllergyIntoleranceCertainty from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 AllergyIntoleranceCertainty| Relationship | [R3 AllergyIntoleranceCertainty](/docs/R3/ValueSets/AllergyIntoleranceCertainty.md)| Relationship | *No Map* | Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/reaction-event-certainty`
| **`unlikely`**| _Equivalent_ <br/>(12329/12330)| `unlikely`| | | | | | | 
| **`likely`**| _Equivalent_ <br/>(12331/12332)| `likely`| | | | | | | 
| **`confirmed`**| _Equivalent_ <br/>(12333/12334)| `confirmed`| | | | | | | 
| *3 of 3 codes used* | | *3 of 4 codes used* <br/>remaining codes:<br/>`unknown`| | | | | | 

