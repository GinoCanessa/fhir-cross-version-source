Comparison of 
Generated at Monday, April 14, 2025 6:17:43 PM

### PlanDefinitionType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | PlanDefinitionType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/plan-definition-type` |
| Version | 5.0.0 |
| Description | The type of PlanDefinition. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4795` |
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
| | | | | | | [PlanDefinitionType](/docs/R4B/ValueSets/PlanDefinitionType.md)<br/> `http://hl7.org/fhir/ValueSet/plan-definition-type\|4.3.0` | →→→→→→→<br/>``<br/>- DBKey: `959`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `1220`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [PlanDefinitionType](/docs/R5/ValueSets/PlanDefinitionType.md)<br/> `http://hl7.org/fhir/ValueSet/plan-definition-type\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set PlanDefinitionType from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | [R4B PlanDefinitionType](/docs/R4B/ValueSets/PlanDefinitionType.md)| Relationship | R5 PlanDefinitionType
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://terminology.hl7.org/CodeSystem/plan-definition-type`
| | | | | | | `order-set`| _Equivalent_ <br/>(9211/11525)| **`order-set`**
| | | | | | | `clinical-protocol`| _Equivalent_ <br/>(9209/11523)| **`clinical-protocol`**
| | | | | | | `eca-rule`| _Equivalent_ <br/>(9210/11524)| **`eca-rule`**
| | | | | | | `workflow-definition`| _Equivalent_ <br/>(9212/11526)| **`workflow-definition`**
| | | | | | | *4 of 4 codes used* | | *4 of 4 codes used* 

