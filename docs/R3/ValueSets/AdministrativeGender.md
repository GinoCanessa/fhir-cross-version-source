Comparison of 
Generated at Thursday, April 3, 2025 8:18:09 AM

### AdministrativeGender

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | AdministrativeGender |
| Canonical URL | `http://hl7.org/fhir/ValueSet/administrative-gender` |
| Version | 3.0.2 |
| Description | The gender of a person used for administrative purposes. |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `1041` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/FamilyMemberHistory` | `FamilyMemberHistory.gender` | `http://hl7.org/fhir/ValueSet/administrative-gender` | `Required` | male \| female \| other \| unknown |
| `http://hl7.org/fhir/StructureDefinition/Patient` | `Patient.gender` | `http://hl7.org/fhir/ValueSet/administrative-gender` | `Required` | male \| female \| other \| unknown |
| `http://hl7.org/fhir/StructureDefinition/Patient` | `Patient.contact.gender` | `http://hl7.org/fhir/ValueSet/administrative-gender` | `Required` | male \| female \| other \| unknown |
| `http://hl7.org/fhir/StructureDefinition/Person` | `Person.gender` | `http://hl7.org/fhir/ValueSet/administrative-gender` | `Required` | male \| female \| other \| unknown |
| `http://hl7.org/fhir/StructureDefinition/Practitioner` | `Practitioner.gender` | `http://hl7.org/fhir/ValueSet/administrative-gender` | `Required` | male \| female \| other \| unknown |
| `http://hl7.org/fhir/StructureDefinition/RelatedPerson` | `RelatedPerson.gender` | `http://hl7.org/fhir/ValueSet/administrative-gender` | `Required` | male \| female \| other \| unknown |

### Referenced Systems

* `http://hl7.org/fhir/administrative-gender`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [AdministrativeGender](/docs/R2/ValueSets/AdministrativeGender.md)<br/> `http://hl7.org/fhir/ValueSet/administrative-gender\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `78`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `234`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AdministrativeGender](/docs/R3/ValueSets/AdministrativeGender.md)<br/> `http://hl7.org/fhir/ValueSet/administrative-gender\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `417`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `639`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AdministrativeGender](/docs/R4/ValueSets/AdministrativeGender.md)<br/> `http://hl7.org/fhir/ValueSet/administrative-gender\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1357`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1358`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AdministrativeGender](/docs/R4B/ValueSets/AdministrativeGender.md)<br/> `http://hl7.org/fhir/ValueSet/administrative-gender\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `891`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1152`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AdministrativeGender](/docs/R5/ValueSets/AdministrativeGender.md)<br/> `http://hl7.org/fhir/ValueSet/administrative-gender\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set AdministrativeGender from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 AdministrativeGender](/docs/R2/ValueSets/AdministrativeGender.md)| Relationship | R3 AdministrativeGender| Relationship | [R4 AdministrativeGender](/docs/R4/ValueSets/AdministrativeGender.md)| Relationship | [R4B AdministrativeGender](/docs/R4B/ValueSets/AdministrativeGender.md)| Relationship | [R5 AdministrativeGender](/docs/R5/ValueSets/AdministrativeGender.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/administrative-gender`
| `male`| _Equivalent_ <br/>(556/1913)| **`male`**| _Equivalent_ <br/>(3704/5989)| `male`| _Equivalent_ <br/>(13946/13947)| `male`| _Equivalent_ <br/>(8293/10598)| `male`
| `female`| _Equivalent_ <br/>(555/1912)| **`female`**| _Equivalent_ <br/>(3703/5988)| `female`| _Equivalent_ <br/>(13948/13949)| `female`| _Equivalent_ <br/>(8292/10597)| `female`
| `other`| _Equivalent_ <br/>(554/1911)| **`other`**| _Equivalent_ <br/>(3702/5987)| `other`| _Equivalent_ <br/>(13950/13951)| `other`| _Equivalent_ <br/>(8291/10596)| `other`
| `unknown`| _Equivalent_ <br/>(557/1914)| **`unknown`**| _Equivalent_ <br/>(3705/5990)| `unknown`| _Equivalent_ <br/>(13952/13953)| `unknown`| _Equivalent_ <br/>(8294/10599)| `unknown`
| *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* 

