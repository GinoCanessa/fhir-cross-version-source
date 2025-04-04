Comparison of 
Generated at Friday, April 4, 2025 2:58:44 PM

### PatientContactRelationship

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | PatientContactRelationship |
| Canonical URL | `http://hl7.org/fhir/ValueSet/patient-contactrelationship` |
| Version | 4.0.1 |
| Description | The nature of the relationship between the patient and the contact person. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `2636` |
| Database Concept Count | `7` |
| Database Active Concept Count | `7` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Patient` | `Patient.contact.relationship` | `http://hl7.org/fhir/ValueSet/patient-contactrelationship` | `Extensible` | The kind of relationship |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/v2-0131`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [PatientContactRelationship](/docs/R2/ValueSets/PatientContactRelationship.md)<br/> `http://hl7.org/fhir/ValueSet/patient-contact-relationship\|1.0.2` | →→→→→→→<br/>``<br/>- DBKey: `114`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `270`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [v2 Contact Role](/docs/R3/ValueSets/V2ContactRole.md)<br/> `http://hl7.org/fhir/ValueSet/v2-0131\|2.8.2` | →→→→→→→<br/>``<br/>- DBKey: `463`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `687`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [PatientContactRelationship](/docs/R4/ValueSets/PatientContactRelationship.md)<br/> `http://hl7.org/fhir/ValueSet/patient-contactrelationship\|4.0.1` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set PatientContactRelationship from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 PatientContactRelationship](/docs/R2/ValueSets/PatientContactRelationship.md)| Relationship | [R3 v2 Contact Role](/docs/R3/ValueSets/V2ContactRole.md)| Relationship | R4 PatientContactRelationship| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://terminology.hl7.org/CodeSystem/v2-0131`
| `emergency`| _Equivalent_ <br/>(953/2320)| `C`| _Equivalent_ <br/>(4124/6470)| **`C`**| | | | | 
| `work`| _Equivalent_ <br/>(962/2322)| `E`| _Equivalent_ <br/>(4126/6472)| **`E`**| | | | | 
| | | `F`| _Equivalent_ <br/>(4128/6474)| **`F`**| | | | | 
| | | `I`| _Equivalent_ <br/>(4129/6475)| **`I`**| | | | | 
| `family`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(955)<hr/>←←←← __ ←←←← <br/>() | `N`| _Equivalent_ <br/>(4130/6476)| **`N`**| | | | | 
| `partner`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(961)<hr/>←←←← __ ←←←← <br/>() | `N`| _Equivalent_ <br/>(4130/6476)| **`N`**| | | | | 
| `parent`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(960)<hr/>←←←← __ ←←←← <br/>() | `N`| _Equivalent_ <br/>(4130/6476)| **`N`**| | | | | 
| | | `S`| _Equivalent_ <br/>(4125/6471)| **`S`**| | | | | 
| | | `U`| _Equivalent_ <br/>(4127/6473)| **`U`**| | | | | 
| *5 of 11 codes used* <br/>remaining codes:<br/>`agent`, `caregiver`, `friend`, `guarantor`, `guardian`, `owner`| | *7 of 12 codes used* <br/>remaining codes:<br/>`BP`, `CP`, `EP`, `O`, `PR`| | *7 of 7 codes used* | | | | 

