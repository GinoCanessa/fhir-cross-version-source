Comparison of 
Generated at Tuesday, April 1, 2025 1:39:19 PM

### NoteType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | NoteType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/note-type` |
| Version | 4.0.1 |
| Description | The presentation types of notes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2611` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.processNote.type` | `http://hl7.org/fhir/ValueSet/note-type\|4.0.1` | `Required` | display \| print \| printoper |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.processNote.type` | `http://hl7.org/fhir/ValueSet/note-type\|4.0.1` | `Required` | display \| print \| printoper |
| `http://hl7.org/fhir/StructureDefinition/PaymentReconciliation` | `PaymentReconciliation.processNote.type` | `http://hl7.org/fhir/ValueSet/note-type\|4.0.1` | `Required` | display \| print \| printoper |

### Referenced Systems

* `http://hl7.org/fhir/note-type`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [NoteType](/docs/R2/ValueSets/NoteType.md)<br/> `http://hl7.org/fhir/ValueSet/note-type\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `22`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `181`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [NoteType](/docs/R3/ValueSets/NoteType.md)<br/> `http://hl7.org/fhir/ValueSet/note-type\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `348`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `571`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [NoteType](/docs/R4/ValueSets/NoteType.md)<br/> `http://hl7.org/fhir/ValueSet/note-type\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1635`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1636`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [NoteType](/docs/R4B/ValueSets/NoteType.md)<br/> `http://hl7.org/fhir/ValueSet/note-type\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `796`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1057`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [NoteType](/docs/R5/ValueSets/NoteType.md)<br/> `http://hl7.org/fhir/ValueSet/note-type\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set NoteType from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 NoteType](/docs/R2/ValueSets/NoteType.md)| Relationship | [R3 NoteType](/docs/R3/ValueSets/NoteType.md)| Relationship | R4 NoteType| Relationship | [R4B NoteType](/docs/R4B/ValueSets/NoteType.md)| Relationship | [R5 NoteType](/docs/R5/ValueSets/NoteType.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://hl7.org/fhir/note-type`
| `display`| _Equivalent_ <br/>(102/1472)| `display`| _Equivalent_ <br/>(3006/5214)| **`display`**| _Equivalent_ <br/>(16694/16695)| `display`| _Equivalent_ <br/>(7542/9811)| `display`
| `print`| _Equivalent_ <br/>(101/1471)| `print`| _Equivalent_ <br/>(3005/5213)| **`print`**| _Equivalent_ <br/>(16696/16697)| `print`| _Equivalent_ <br/>(7541/9810)| `print`
| `printoper`| _Equivalent_ <br/>(103/1473)| `printoper`| _Equivalent_ <br/>(3007/5215)| **`printoper`**| _Equivalent_ <br/>(16698/16699)| `printoper`| _Equivalent_ <br/>(7543/9812)| `printoper`
| *3 of 3 codes used* | | *3 of 3 codes used* | | *3 of 3 codes used* | | *3 of 3 codes used* | | *3 of 3 codes used* 

