Comparison of 
Generated at Monday, April 14, 2025 6:17:21 PM

### ActIncidentCode

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | ActIncidentCode |
| Canonical URL | `http://hl7.org/fhir/ValueSet/v3-ActIncidentCode` |
| Version | 2014-03-26 |
| Description | Set of codes indicating the type of incident or accident. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `1981` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.accident.type` | `http://hl7.org/fhir/ValueSet/v3-ActIncidentCode` | `Required` | The nature of the accident |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.accident.type` | `http://hl7.org/fhir/ValueSet/v3-ActIncidentCode` | `Required` | The nature of the accident |

### Referenced Systems

* `http://hl7.org/fhir/v3/ActCode`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ActIncidentCode](/docs/R2/ValueSets/ActIncidentCode.md)<br/> `http://hl7.org/fhir/ValueSet/v3-ActIncidentCode\|2014-03-26` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `19`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `178`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [ActIncidentCode](/docs/R3/ValueSets/ActIncidentCode.md)<br/> `http://hl7.org/fhir/ValueSet/v3-ActIncidentCode\|2014-03-26` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `344`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `568`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [v3.ActIncidentCode](/docs/R4/ValueSets/V3ActIncidentCode.md)<br/> `http://terminology.hl7.org/ValueSet/v3-ActIncidentCode\|2014-03-26` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set ActIncidentCode from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 ActIncidentCode](/docs/R2/ValueSets/ActIncidentCode.md)| Relationship | R3 ActIncidentCode| Relationship | [R4 v3.ActIncidentCode](/docs/R4/ValueSets/V3ActIncidentCode.md)| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/v3/ActCode`
| `MVA`| _Equivalent_ <br/>(90/1458)| **`MVA`**| _Equivalent_ <br/>(2988/5201)| `MVA`| | | | | 
| `SCHOOL`| _Equivalent_ <br/>(91/1459)| **`SCHOOL`**| _Equivalent_ <br/>(2989/5202)| `SCHOOL`| | | | | 
| `SPT`| _Equivalent_ <br/>(89/1460)| **`SPT`**| _Equivalent_ <br/>(2990/5203)| `SPT`| | | | | 
| `WPA`| _Equivalent_ <br/>(88/1461)| **`WPA`**| _Equivalent_ <br/>(2991/5204)| `WPA`| | | | | 
| *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | | | 

