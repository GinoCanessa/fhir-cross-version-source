Comparison of 
Generated at Monday, April 14, 2025 6:17:35 PM

### ActionRelationshipType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | ActionRelationshipType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/action-relationship-type` |
| Version | 4.3.0 |
| Description | Defines the types of relationships between actions. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `3498` |
| Database Concept Count | `9` |
| Database Active Concept Count | `9` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/PlanDefinition` | `PlanDefinition.action.relatedAction.relationship` | `http://hl7.org/fhir/ValueSet/action-relationship-type\|4.3.0` | `Required` | before-start \| before \| before-end \| concurrent-with-start \| concurrent \| concurrent-with-end \| after-start \| after \| after-end |
| `http://hl7.org/fhir/StructureDefinition/RequestGroup` | `RequestGroup.action.relatedAction.relationship` | `http://hl7.org/fhir/ValueSet/action-relationship-type\|4.3.0` | `Required` | before-start \| before \| before-end \| concurrent-with-start \| concurrent \| concurrent-with-end \| after-start \| after \| after-end |
| `http://hl7.org/fhir/StructureDefinition/cqf-relativeDateTime` | `Extension.extension.value[x]` | `http://hl7.org/fhir/ValueSet/action-relationship-type\|4.3.0` | `Required` | Value of extension |
| `http://hl7.org/fhir/StructureDefinition/relative-date` | `Extension.extension.value[x]` | `http://hl7.org/fhir/ValueSet/action-relationship-type\|4.3.0` | `Required` | Value of extension |

### Referenced Systems

* `http://hl7.org/fhir/action-relationship-type`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [ActionRelationshipType](/docs/R3/ValueSets/ActionRelationshipType.md)<br/> `http://hl7.org/fhir/ValueSet/action-relationship-type\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `470`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `694`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [ActionRelationshipType](/docs/R4/ValueSets/ActionRelationshipType.md)<br/> `http://hl7.org/fhir/ValueSet/action-relationship-type\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1347`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1348`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ActionRelationshipType](/docs/R4B/ValueSets/ActionRelationshipType.md)<br/> `http://hl7.org/fhir/ValueSet/action-relationship-type\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `955`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1216`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [ActionRelationshipType](/docs/R5/ValueSets/ActionRelationshipType.md)<br/> `http://hl7.org/fhir/ValueSet/action-relationship-type\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set ActionRelationshipType from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | [R3 ActionRelationshipType](/docs/R3/ValueSets/ActionRelationshipType.md)| Relationship | [R4 ActionRelationshipType](/docs/R4/ValueSets/ActionRelationshipType.md)| Relationship | R4B ActionRelationshipType| Relationship | [R5 ActionRelationshipType](/docs/R5/ValueSets/ActionRelationshipType.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://hl7.org/fhir/action-relationship-type`
| | | `before-start`| _Equivalent_ <br/>(4176/6521)| `before-start`| _Equivalent_ <br/>(13894/13895)| **`before-start`**| _Equivalent_ <br/>(9195/11509)| `before-start`
| | | `before`| _Equivalent_ <br/>(4169/6514)| `before`| _Equivalent_ <br/>(13896/13897)| **`before`**| _Equivalent_ <br/>(9188/11502)| `before`
| | | `before-end`| _Equivalent_ <br/>(4172/6517)| `before-end`| _Equivalent_ <br/>(13898/13899)| **`before-end`**| _Equivalent_ <br/>(9191/11505)| `before-end`
| | | `concurrent-with-start`| _Equivalent_ <br/>(4170/6515)| `concurrent-with-start`| _Equivalent_ <br/>(13900/13901)| **`concurrent-with-start`**| _Equivalent_ <br/>(9189/11504)| `concurrent-with-start`
| | | `concurrent`| _Equivalent_ <br/>(4171/6516)| `concurrent`| _Equivalent_ <br/>(13902/13903)| **`concurrent`**| _Equivalent_ <br/>(9190/11503)| `concurrent`
| | | `concurrent-with-end`| _Equivalent_ <br/>(4174/6519)| `concurrent-with-end`| _Equivalent_ <br/>(13904/13905)| **`concurrent-with-end`**| _Equivalent_ <br/>(9193/11507)| `concurrent-with-end`
| | | `after-start`| _Equivalent_ <br/>(4175/6520)| `after-start`| _Equivalent_ <br/>(13906/13907)| **`after-start`**| _Equivalent_ <br/>(9194/11508)| `after-start`
| | | `after`| _Equivalent_ <br/>(4173/6518)| `after`| _Equivalent_ <br/>(13908/13909)| **`after`**| _Equivalent_ <br/>(9192/11506)| `after`
| | | `after-end`| _Equivalent_ <br/>(4168/6513)| `after-end`| _Equivalent_ <br/>(13910/13911)| **`after-end`**| _Equivalent_ <br/>(9187/11501)| `after-end`
| | | *9 of 9 codes used* | | *9 of 9 codes used* | | *9 of 9 codes used* | | *9 of 9 codes used* 

