Comparison of 
Generated at Thursday, April 3, 2025 8:18:17 AM

### EvidenceVariableType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | EvidenceVariableType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/variable-type` |
| Version | 4.0.1 |
| Description | The possible types of variables for exposures or outcomes (E.g. Dichotomous, Continuous, Descriptive). |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2825` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/EvidenceVariable` | `EvidenceVariable.type` | `http://hl7.org/fhir/ValueSet/variable-type\|4.0.1` | `Required` | dichotomous \| continuous \| descriptive |
| `http://hl7.org/fhir/StructureDefinition/ResearchElementDefinition` | `ResearchElementDefinition.variableType` | `http://hl7.org/fhir/ValueSet/variable-type\|4.0.1` | `Required` | dichotomous \| continuous \| descriptive |

### Referenced Systems

* `http://hl7.org/fhir/variable-type`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [EvidenceVariableType](/docs/R4/ValueSets/EvidenceVariableType.md)<br/> `http://hl7.org/fhir/ValueSet/variable-type\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1781`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1782`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [VariableType](/docs/R4B/ValueSets/VariableType.md)<br/> `http://hl7.org/fhir/ValueSet/variable-type\|4.3.0` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set EvidenceVariableType from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | R4 EvidenceVariableType| Relationship | [R4B VariableType](/docs/R4B/ValueSets/VariableType.md)| Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://hl7.org/fhir/variable-type`
| | | | | **`dichotomous`**| _Equivalent_ <br/>(18400/18401)| `dichotomous`| | | 
| | | | | **`continuous`**| _Equivalent_ <br/>(18402/18403)| `continuous`| | | 
| | | | | **`descriptive`**| _Equivalent_ <br/>(18404/18405)| `descriptive`| | | 
| | | | | *3 of 3 codes used* | | *3 of 3 codes used* | | 

