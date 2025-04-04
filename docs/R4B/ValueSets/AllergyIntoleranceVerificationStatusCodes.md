Comparison of 
Generated at Friday, April 4, 2025 2:58:51 PM

### AllergyIntoleranceVerificationStatusCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | AllergyIntoleranceVerificationStatusCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/allergyintolerance-verification` |
| Version | 4.3.0 |
| Description | Preferred value set for AllergyIntolerance Verification Status. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `3531` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/AllergyIntolerance` | `AllergyIntolerance.verificationStatus` | `http://hl7.org/fhir/ValueSet/allergyintolerance-verification\|4.3.0` | `Required` | unconfirmed \| confirmed \| refuted \| entered-in-error |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/allergyintolerance-verification`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [AllergyIntoleranceStatus](/docs/R2/ValueSets/AllergyIntoleranceStatus.md)<br/> `http://hl7.org/fhir/ValueSet/allergy-intolerance-status\|1.0.2` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `7`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1289`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AllergyIntoleranceVerificationStatus](/docs/R3/ValueSets/AllergyIntoleranceVerificationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/allergy-verification-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `333`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `555`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AllergyIntoleranceVerificationStatusCodes](/docs/R4/ValueSets/AllergyIntoleranceVerificationStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/allergyintolerance-verification\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1383`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1384`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AllergyIntoleranceVerificationStatusCodes](/docs/R4B/ValueSets/AllergyIntoleranceVerificationStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/allergyintolerance-verification\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `778`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1039`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AllergyIntoleranceVerificationStatus](/docs/R5/ValueSets/AllergyIntoleranceVerificationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/allergyintolerance-verification\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set AllergyIntoleranceVerificationStatusCodes from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 AllergyIntoleranceStatus](/docs/R2/ValueSets/AllergyIntoleranceStatus.md)| Relationship | [R3 AllergyIntoleranceVerificationStatus](/docs/R3/ValueSets/AllergyIntoleranceVerificationStatus.md)| Relationship | [R4 AllergyIntoleranceVerificationStatusCodes](/docs/R4/ValueSets/AllergyIntoleranceVerificationStatusCodes.md)| Relationship | R4B AllergyIntoleranceVerificationStatusCodes| Relationship | [R5 AllergyIntoleranceVerificationStatus](/docs/R5/ValueSets/AllergyIntoleranceVerificationStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://terminology.hl7.org/CodeSystem/allergyintolerance-verification`
| `unconfirmed`| _Equivalent_ <br/>(25/11989)| `unconfirmed`| _Equivalent_ <br/>(2916/5117)| `unconfirmed`| _Equivalent_ <br/>(14458/14459)| **`unconfirmed`**| _Equivalent_ <br/>(7451/9716)| `unconfirmed`
| `confirmed`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(30)<hr/>←←←← _Equivalent_ ←←←← <br/>(11990) | `confirmed`| _Equivalent_ <br/>(2919/5120)| `confirmed`| _Equivalent_ <br/>(14460/14461)| **`confirmed`**| _Equivalent_ <br/>(7448/9713)| `confirmed`
| `refuted`| _Equivalent_ <br/>(27/11991)| `refuted`| _Equivalent_ <br/>(2917/5118)| `refuted`| _Equivalent_ <br/>(14462/14463)| **`refuted`**| _Equivalent_ <br/>(7450/9715)| `refuted`
| `entered-in-error`| _Equivalent_ <br/>(29/11992)| `entered-in-error`| _Equivalent_ <br/>(2918/5119)| `entered-in-error`| _Equivalent_ <br/>(14464/14465)| **`entered-in-error`**| _Equivalent_ <br/>(7449/9714)| `entered-in-error`
| *4 of 7 codes used* <br/>remaining codes:<br/>`active`, `inactive`, `resolved`| | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 5 codes used* <br/>remaining codes:<br/>`presumed`

