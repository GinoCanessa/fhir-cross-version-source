Comparison of 
Generated at Tuesday, April 1, 2025 1:39:10 PM

### AllergyIntoleranceClinicalStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | AllergyIntoleranceClinicalStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/allergy-clinical-status` |
| Version | 3.0.2 |
| Description | The clinical status of the allergy or intolerance. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1054` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/AllergyIntolerance` | `AllergyIntolerance.clinicalStatus` | `http://hl7.org/fhir/ValueSet/allergy-clinical-status` | `Required` | active \| inactive \| resolved |

### Referenced Systems

* `http://hl7.org/fhir/allergy-clinical-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [AllergyIntoleranceStatus](/docs/R2/ValueSets/AllergyIntoleranceStatus.md)<br/> `http://hl7.org/fhir/ValueSet/allergy-intolerance-status\|1.0.2` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `6`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1288`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AllergyIntoleranceClinicalStatus](/docs/R3/ValueSets/AllergyIntoleranceClinicalStatus.md)<br/> `http://hl7.org/fhir/ValueSet/allergy-clinical-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `329`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `551`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AllergyIntoleranceClinicalStatusCodes](/docs/R4/ValueSets/AllergyIntoleranceClinicalStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/allergyintolerance-clinical\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1381`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1382`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AllergyIntoleranceClinicalStatusCodes](/docs/R4B/ValueSets/AllergyIntoleranceClinicalStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/allergyintolerance-clinical\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `775`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1036`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AllergyIntoleranceClinicalStatusCodes](/docs/R5/ValueSets/AllergyIntoleranceClinicalStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/allergyintolerance-clinical\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set AllergyIntoleranceClinicalStatus from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 AllergyIntoleranceStatus](/docs/R2/ValueSets/AllergyIntoleranceStatus.md)| Relationship | R3 AllergyIntoleranceClinicalStatus| Relationship | [R4 AllergyIntoleranceClinicalStatusCodes](/docs/R4/ValueSets/AllergyIntoleranceClinicalStatusCodes.md)| Relationship | [R4B AllergyIntoleranceClinicalStatusCodes](/docs/R4B/ValueSets/AllergyIntoleranceClinicalStatusCodes.md)| Relationship | [R5 AllergyIntoleranceClinicalStatusCodes](/docs/R5/ValueSets/AllergyIntoleranceClinicalStatusCodes.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/allergy-clinical-status`
| `confirmed`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(23)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11986) | **`active`**| _Equivalent_ <br/>(2906/5107)| `active`| _Equivalent_ <br/>(14452/14453)| `active`| _Equivalent_ <br/>(7439/9704)| `active`
| `active`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(21)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11986) | **`active`**| _Equivalent_ <br/>(2906/5107)| `active`| _Equivalent_ <br/>(14452/14453)| `active`| _Equivalent_ <br/>(7439/9704)| `active`
| `inactive`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(19)<hr/>←←←← _Equivalent_ ←←←← <br/>(11988) | **`inactive`**| _Equivalent_ <br/>(2905/5106)| `inactive`| _Equivalent_ <br/>(14454/14455)| `inactive`| _Equivalent_ <br/>(7440/9705)| `inactive`
| `resolved`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(24)<hr/>←←←← _Equivalent_ ←←←← <br/>(11987) | **`resolved`**| _Equivalent_ <br/>(2907/5108)| `resolved`| _Equivalent_ <br/>(14456/14457)| `resolved`| _Equivalent_ <br/>(7441/9706)| `resolved`
| *4 of 7 codes used* | | *3 of 3 codes used* | | *3 of 3 codes used* | | *3 of 3 codes used* | | *3 of 3 codes used* 

