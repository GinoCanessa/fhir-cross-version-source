Comparison of 
Generated at Tuesday, April 1, 2025 1:39:10 PM

### CarePlanIntent

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | CarePlanIntent |
| Canonical URL | `http://hl7.org/fhir/ValueSet/care-plan-intent` |
| Version | 3.0.2 |
| Description | Codes indicating the degree of authority/intentionality associated with a care plan |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1096` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/CarePlan` | `CarePlan.intent` | `http://hl7.org/fhir/ValueSet/care-plan-intent` | `Required` | proposal \| plan \| order \| option |

### Referenced Systems

* `http://hl7.org/fhir/care-plan-intent`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [CarePlanIntent](/docs/R3/ValueSets/CarePlanIntent.md)<br/> `http://hl7.org/fhir/ValueSet/care-plan-intent\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `376`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `599`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CarePlanIntent](/docs/R4/ValueSets/CarePlanIntent.md)<br/> `http://hl7.org/fhir/ValueSet/care-plan-intent\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1407`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1408`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CarePlanIntent](/docs/R4B/ValueSets/CarePlanIntent.md)<br/> `http://hl7.org/fhir/ValueSet/care-plan-intent\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `822`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1083`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CarePlanIntent](/docs/R5/ValueSets/CarePlanIntent.md)<br/> `http://hl7.org/fhir/ValueSet/care-plan-intent\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set CarePlanIntent from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | R3 CarePlanIntent| Relationship | [R4 CarePlanIntent](/docs/R4/ValueSets/CarePlanIntent.md)| Relationship | [R4B CarePlanIntent](/docs/R4B/ValueSets/CarePlanIntent.md)| Relationship | [R5 CarePlanIntent](/docs/R5/ValueSets/CarePlanIntent.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/care-plan-intent`
| | | **`proposal`**| _Equivalent_ <br/>(3140/5353)| `proposal`| _Equivalent_ <br/>(14620/14621)| `proposal`| _Equivalent_ <br/>(7704/10005)| `proposal`
| | | **`plan`**| _Equivalent_ <br/>(3141/5352)| `plan`| _Equivalent_ <br/>(14622/14623)| `plan`| _Equivalent_ <br/>(7705/10006)| `plan`
| | | **`order`**| _Equivalent_ <br/>(3142/5351)| `order`| _Equivalent_ <br/>(14624/14625)| `order`| _Equivalent_ <br/>(7706/10008)| `order`
| | | **`option`**| _Equivalent_ <br/>(3143/5350)| `option`| _Equivalent_ <br/>(14626/14627)| `option`| _Equivalent_ <br/>(7707/10009)| `option`
| | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 5 codes used* 

