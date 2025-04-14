Comparison of 
Generated at Monday, April 14, 2025 6:17:27 PM

### PlanDefinitionType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | PlanDefinitionType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/plan-definition-type` |
| Version | 4.0.1 |
| Description | The type of PlanDefinition. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2644` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/PlanDefinition` | `PlanDefinition.type` | `http://hl7.org/fhir/ValueSet/plan-definition-type` | `Extensible` | order-set \| clinical-protocol \| eca-rule \| workflow-definition |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/plan-definition-type`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [PlanDefinitionType](/docs/R3/ValueSets/PlanDefinitionType.md)<br/> `http://hl7.org/fhir/ValueSet/plan-definition-type\|3.0.2` | →→→→→→→<br/>``<br/>- DBKey: `474`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `698`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [PlanDefinitionType](/docs/R4/ValueSets/PlanDefinitionType.md)<br/> `http://hl7.org/fhir/ValueSet/plan-definition-type\|4.0.1` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set PlanDefinitionType from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | [R3 PlanDefinitionType](/docs/R3/ValueSets/PlanDefinitionType.md)| Relationship | R4 PlanDefinitionType| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://terminology.hl7.org/CodeSystem/plan-definition-type`
| | | `order-set`| _Equivalent_ <br/>(4192/6537)| **`order-set`**| | | | | 
| | | `protocol`| _Equivalent_ <br/>(4190/6535)| **`clinical-protocol`**| | | | | 
| | | `eca-rule`| _Equivalent_ <br/>(4191/6536)| **`eca-rule`**| | | | | 
| | | | | **`workflow-definition`**| | | | | 
| | | *3 of 3 codes used* | | *4 of 4 codes used* | | | | 

