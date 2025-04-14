Comparison of 
Generated at Monday, April 14, 2025 6:17:15 PM

### PatientContactRelationship

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | PatientContactRelationship |
| Canonical URL | `http://hl7.org/fhir/ValueSet/patient-contact-relationship` |
| Version | 1.0.2 |
| Description | This value set defines a set of codes that are used to indicate the nature of the relationship between a patient and a contactperson for that patient. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `272` |
| Database Concept Count | `11` |
| Database Active Concept Count | `11` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Patient` | `Patient.contact.relationship` | `http://hl7.org/fhir/ValueSet/patient-contact-relationship` | `Extensible` | The kind of relationship |

### Referenced Systems

* `http://hl7.org/fhir/patient-contact-relationship`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [PatientContactRelationship](/docs/R2/ValueSets/PatientContactRelationship.md)<br/> `http://hl7.org/fhir/ValueSet/patient-contact-relationship\|1.0.2` | →→→→→→→<br/>``<br/>- DBKey: `114`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `270`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [v2 Contact Role](/docs/R3/ValueSets/V2ContactRole.md)<br/> `http://hl7.org/fhir/ValueSet/v2-0131\|2.8.2` | →→→→→→→<br/>``<br/>- DBKey: `463`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `687`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [PatientContactRelationship](/docs/R4/ValueSets/PatientContactRelationship.md)<br/> `http://hl7.org/fhir/ValueSet/patient-contactrelationship\|4.0.1` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set PatientContactRelationship from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 PatientContactRelationship| Relationship | [R3 v2 Contact Role](/docs/R3/ValueSets/V2ContactRole.md)| Relationship | [R4 PatientContactRelationship](/docs/R4/ValueSets/PatientContactRelationship.md)| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/patient-contact-relationship`
| **`emergency`**| _Equivalent_ <br/>(953/2320)| `C`| _Equivalent_ <br/>(4124/6470)| `C`| | | | | 
| **`emergency`**| _Equivalent_ <br/>(954/2323)| `EP`| | | | | | | 
| **`family`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(955)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2326) | `N`| _Equivalent_ <br/>(4130/6476)| `N`| | | | | 
| **`guardian`**| | | | | | | | | 
| **`friend`**| | | | | | | | | 
| **`partner`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(961)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2328) | `N`| _Equivalent_ <br/>(4130/6476)| `N`| | | | | 
| **`work`**| _Equivalent_ <br/>(962/2322)| `E`| _Equivalent_ <br/>(4126/6472)| `E`| | | | | 
| **`caregiver`**| | | | | | | | | 
| **`agent`**| | | | | | | | | 
| **`guarantor`**| | | | | | | | | 
| **`owner`**| | | | | | | | | 
| **`parent`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(960)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2327) | `N`| _Equivalent_ <br/>(4130/6476)| `N`| | | | | 
| *11 of 11 codes used* | | *4 of 12 codes used* <br/>remaining codes:<br/>`BP`, `CP`, `F`, `I`, `O`, `PR`, `S`, `U`| | *3 of 7 codes used* <br/>remaining codes:<br/>`F`, `I`, `S`, `U`| | | | 

