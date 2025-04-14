Comparison of 
Generated at Monday, April 14, 2025 6:17:42 PM

### EvidenceVariableHandling

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | EvidenceVariableHandling |
| Canonical URL | `http://hl7.org/fhir/ValueSet/variable-handling` |
| Version | 5.0.0 |
| Description | The handling of the variable in statistical analysis for exposures or outcomes (E.g. Dichotomous, Continuous, Descriptive). |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `5000` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Evidence` | `Evidence.statistic.modelCharacteristic.variable.handling` | `http://hl7.org/fhir/ValueSet/variable-handling\|5.0.0` | `Required` | continuous \| dichotomous \| ordinal \| polychotomous |
| `http://hl7.org/fhir/StructureDefinition/EvidenceVariable` | `EvidenceVariable.handling` | `http://hl7.org/fhir/ValueSet/variable-handling\|5.0.0` | `Required` | continuous \| dichotomous \| ordinal \| polychotomous |

### Referenced Systems

* `http://hl7.org/fhir/variable-handling`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [EvidenceVariableHandling](/docs/R4B/ValueSets/EvidenceVariableHandling.md)<br/> `http://hl7.org/fhir/ValueSet/variable-handling\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `882`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1143`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [EvidenceVariableHandling](/docs/R5/ValueSets/EvidenceVariableHandling.md)<br/> `http://hl7.org/fhir/ValueSet/variable-handling\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set EvidenceVariableHandling from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | [R4B EvidenceVariableHandling](/docs/R4B/ValueSets/EvidenceVariableHandling.md)| Relationship | R5 EvidenceVariableHandling
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/variable-handling`
| | | | | | | `continuous`| _Equivalent_ <br/>(8179/10484)| **`continuous`**
| | | | | | | `dichotomous`| _Equivalent_ <br/>(8181/10486)| **`dichotomous`**
| | | | | | | `ordinal`| _Equivalent_ <br/>(8182/10487)| **`ordinal`**
| | | | | | | `polychotomous`| _Equivalent_ <br/>(8180/10485)| **`polychotomous`**
| | | | | | | *4 of 4 codes used* | | *4 of 4 codes used* 

