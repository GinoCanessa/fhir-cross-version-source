Comparison of 
Generated at Friday, April 4, 2025 2:58:32 PM

### AllergyIntoleranceStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | AllergyIntoleranceStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/allergy-intolerance-status` |
| Version | 1.0.2 |
| Description | Assertion about certainty associated with a propensity, or potential risk, of a reaction to the identified Substance. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `14` |
| Database Concept Count | `7` |
| Database Active Concept Count | `7` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/AllergyIntolerance` | `AllergyIntolerance.status` | `http://hl7.org/fhir/ValueSet/allergy-intolerance-status` | `Required` | active \| unconfirmed \| confirmed \| inactive \| resolved \| refuted \| entered-in-error |

### Referenced Systems

* `http://hl7.org/fhir/allergy-intolerance-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [AllergyIntoleranceStatus](/docs/R2/ValueSets/AllergyIntoleranceStatus.md)<br/> `http://hl7.org/fhir/ValueSet/allergy-intolerance-status\|1.0.2` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `6`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1288`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AllergyIntoleranceClinicalStatus](/docs/R3/ValueSets/AllergyIntoleranceClinicalStatus.md)<br/> `http://hl7.org/fhir/ValueSet/allergy-clinical-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `329`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `551`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AllergyIntoleranceClinicalStatusCodes](/docs/R4/ValueSets/AllergyIntoleranceClinicalStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/allergyintolerance-clinical\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1381`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1382`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AllergyIntoleranceClinicalStatusCodes](/docs/R4B/ValueSets/AllergyIntoleranceClinicalStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/allergyintolerance-clinical\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `775`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1036`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AllergyIntoleranceClinicalStatusCodes](/docs/R5/ValueSets/AllergyIntoleranceClinicalStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/allergyintolerance-clinical\|5.0.0` 
| [AllergyIntoleranceStatus](/docs/R2/ValueSets/AllergyIntoleranceStatus.md)<br/> `http://hl7.org/fhir/ValueSet/allergy-intolerance-status\|1.0.2` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `7`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1289`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AllergyIntoleranceVerificationStatus](/docs/R3/ValueSets/AllergyIntoleranceVerificationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/allergy-verification-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `333`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `555`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AllergyIntoleranceVerificationStatusCodes](/docs/R4/ValueSets/AllergyIntoleranceVerificationStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/allergyintolerance-verification\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1383`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1384`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AllergyIntoleranceVerificationStatusCodes](/docs/R4B/ValueSets/AllergyIntoleranceVerificationStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/allergyintolerance-verification\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `778`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1039`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AllergyIntoleranceVerificationStatus](/docs/R5/ValueSets/AllergyIntoleranceVerificationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/allergyintolerance-verification\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set AllergyIntoleranceStatus from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 AllergyIntoleranceStatus| Relationship | [R3 AllergyIntoleranceClinicalStatus](/docs/R3/ValueSets/AllergyIntoleranceClinicalStatus.md)| Relationship | [R4 AllergyIntoleranceClinicalStatusCodes](/docs/R4/ValueSets/AllergyIntoleranceClinicalStatusCodes.md)| Relationship | [R4B AllergyIntoleranceClinicalStatusCodes](/docs/R4B/ValueSets/AllergyIntoleranceClinicalStatusCodes.md)| Relationship | [R5 AllergyIntoleranceClinicalStatusCodes](/docs/R5/ValueSets/AllergyIntoleranceClinicalStatusCodes.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/allergy-intolerance-status`
| **`unconfirmed`**| | | | | | | | | 
| **`confirmed`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(23)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11985) | `active`| _Equivalent_ <br/>(2906/5107)| `active`| _Equivalent_ <br/>(14452/14453)| `active`| _Equivalent_ <br/>(7439/9704)| `active`
| **`active`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(21)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11986) | `active`| _Equivalent_ <br/>(2906/5107)| `active`| _Equivalent_ <br/>(14452/14453)| `active`| _Equivalent_ <br/>(7439/9704)| `active`
| **`resolved`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(24)<hr/>←←←← _Equivalent_ ←←←← <br/>(11987) | `resolved`| _Equivalent_ <br/>(2907/5108)| `resolved`| _Equivalent_ <br/>(14456/14457)| `resolved`| _Equivalent_ <br/>(7441/9706)| `resolved`
| **`refuted`**| | | | | | | | | 
| **`entered-in-error`**| | | | | | | | | 
| **`inactive`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(19)<hr/>←←←← _Equivalent_ ←←←← <br/>(11988) | `inactive`| _Equivalent_ <br/>(2905/5106)| `inactive`| _Equivalent_ <br/>(14454/14455)| `inactive`| _Equivalent_ <br/>(7440/9705)| `inactive`
| *7 of 7 codes used* | | *3 of 3 codes used* | | *3 of 3 codes used* | | *3 of 3 codes used* | | *3 of 3 codes used* 


#### Map Group 1

This group is centered on the Value Set AllergyIntoleranceStatus from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 AllergyIntoleranceStatus| Relationship | [R3 AllergyIntoleranceVerificationStatus](/docs/R3/ValueSets/AllergyIntoleranceVerificationStatus.md)| Relationship | [R4 AllergyIntoleranceVerificationStatusCodes](/docs/R4/ValueSets/AllergyIntoleranceVerificationStatusCodes.md)| Relationship | [R4B AllergyIntoleranceVerificationStatusCodes](/docs/R4B/ValueSets/AllergyIntoleranceVerificationStatusCodes.md)| Relationship | [R5 AllergyIntoleranceVerificationStatus](/docs/R5/ValueSets/AllergyIntoleranceVerificationStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/allergy-intolerance-status`
| **`unconfirmed`**| _Equivalent_ <br/>(25/11989)| `unconfirmed`| _Equivalent_ <br/>(2916/5117)| `unconfirmed`| _Equivalent_ <br/>(14458/14459)| `unconfirmed`| _Equivalent_ <br/>(7451/9716)| `unconfirmed`
| **`confirmed`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(30)<hr/>←←←← _Equivalent_ ←←←← <br/>(11990) | `confirmed`| _Equivalent_ <br/>(2919/5120)| `confirmed`| _Equivalent_ <br/>(14460/14461)| `confirmed`| _Equivalent_ <br/>(7448/9713)| `confirmed`
| **`active`**| | | | | | | | | 
| **`resolved`**| | | | | | | | | 
| **`refuted`**| _Equivalent_ <br/>(27/11991)| `refuted`| _Equivalent_ <br/>(2917/5118)| `refuted`| _Equivalent_ <br/>(14462/14463)| `refuted`| _Equivalent_ <br/>(7450/9715)| `refuted`
| **`entered-in-error`**| _Equivalent_ <br/>(29/11992)| `entered-in-error`| _Equivalent_ <br/>(2918/5119)| `entered-in-error`| _Equivalent_ <br/>(14464/14465)| `entered-in-error`| _Equivalent_ <br/>(7449/9714)| `entered-in-error`
| **`inactive`**| | | | | | | | | 
| *7 of 7 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 5 codes used* <br/>remaining codes:<br/>`presumed`

