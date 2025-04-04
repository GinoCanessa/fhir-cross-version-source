Comparison of 
Generated at Friday, April 4, 2025 2:58:43 PM

### ImmunizationFunctionCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | ImmunizationFunctionCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/immunization-function` |
| Version | 4.0.1 |
| Description | The value set to instantiate this attribute should be drawn from a terminologically robust code system that consists of or contains concepts to support describing the function a practitioner or organization may play in the immunization event. This value set is provided as a suggestive example. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2501` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Immunization` | `Immunization.performer.function` | `http://hl7.org/fhir/ValueSet/immunization-function` | `Extensible` | What type of performance was done |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/v2-0443`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [Immunization Role Codes](/docs/R3/ValueSets/ImmunizationRoleCodes.md)<br/> `http://hl7.org/fhir/ValueSet/immunization-role\|3.0.2` | →→→→→→→<br/>``<br/>- DBKey: `426`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `648`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ImmunizationFunctionCodes](/docs/R4/ValueSets/ImmunizationFunctionCodes.md)<br/> `http://hl7.org/fhir/ValueSet/immunization-function\|4.0.1` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set ImmunizationFunctionCodes from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | [R3 Immunization Role Codes](/docs/R3/ValueSets/ImmunizationRoleCodes.md)| Relationship | R4 ImmunizationFunctionCodes| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://terminology.hl7.org/CodeSystem/v2-0443`
| | | `OP`| _Equivalent_ <br/>(3784/6102)| **`OP`**| | | | | 
| | | `AP`| _Equivalent_ <br/>(3785/6103)| **`AP`**| | | | | 
| | | *2 of 2 codes used* | | *2 of 2 codes used* | | | | 

