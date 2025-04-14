Comparison of 
Generated at Monday, April 14, 2025 6:17:35 PM

### ActionRequiredBehavior

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | ActionRequiredBehavior |
| Canonical URL | `http://hl7.org/fhir/ValueSet/action-required-behavior` |
| Version | 4.3.0 |
| Description | Defines expectations around whether an action or action group is required. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `3499` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/PlanDefinition` | `PlanDefinition.action.requiredBehavior` | `http://hl7.org/fhir/ValueSet/action-required-behavior\|4.3.0` | `Required` | must \| could \| must-unless-documented |
| `http://hl7.org/fhir/StructureDefinition/RequestGroup` | `RequestGroup.action.requiredBehavior` | `http://hl7.org/fhir/ValueSet/action-required-behavior\|4.3.0` | `Required` | must \| could \| must-unless-documented |

### Referenced Systems

* `http://hl7.org/fhir/action-required-behavior`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [ActionRequiredBehavior](/docs/R3/ValueSets/ActionRequiredBehavior.md)<br/> `http://hl7.org/fhir/ValueSet/action-required-behavior\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `471`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `695`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [ActionRequiredBehavior](/docs/R4/ValueSets/ActionRequiredBehavior.md)<br/> `http://hl7.org/fhir/ValueSet/action-required-behavior\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1349`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1350`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ActionRequiredBehavior](/docs/R4B/ValueSets/ActionRequiredBehavior.md)<br/> `http://hl7.org/fhir/ValueSet/action-required-behavior\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `956`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1217`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [ActionRequiredBehavior](/docs/R5/ValueSets/ActionRequiredBehavior.md)<br/> `http://hl7.org/fhir/ValueSet/action-required-behavior\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set ActionRequiredBehavior from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | [R3 ActionRequiredBehavior](/docs/R3/ValueSets/ActionRequiredBehavior.md)| Relationship | [R4 ActionRequiredBehavior](/docs/R4/ValueSets/ActionRequiredBehavior.md)| Relationship | R4B ActionRequiredBehavior| Relationship | [R5 ActionRequiredBehavior](/docs/R5/ValueSets/ActionRequiredBehavior.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://hl7.org/fhir/action-required-behavior`
| | | `must`| _Equivalent_ <br/>(4178/6523)| `must`| _Equivalent_ <br/>(13912/13913)| **`must`**| _Equivalent_ <br/>(9197/11511)| `must`
| | | `could`| _Equivalent_ <br/>(4177/6522)| `could`| _Equivalent_ <br/>(13914/13915)| **`could`**| _Equivalent_ <br/>(9196/11510)| `could`
| | | `must-unless-documented`| _Equivalent_ <br/>(4179/6524)| `must-unless-documented`| _Equivalent_ <br/>(13916/13917)| **`must-unless-documented`**| _Equivalent_ <br/>(9198/11512)| `must-unless-documented`
| | | *3 of 3 codes used* | | *3 of 3 codes used* | | *3 of 3 codes used* | | *3 of 3 codes used* 

