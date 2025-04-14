Comparison of 
Generated at Monday, April 14, 2025 6:17:19 PM

### StructureDefinitionKind

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | StructureDefinitionKind |
| Canonical URL | `http://hl7.org/fhir/ValueSet/structure-definition-kind` |
| Version | 3.0.2 |
| Description | Defines the type of structure that a definition is describing. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1491` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/StructureDefinition` | `StructureDefinition.kind` | `http://hl7.org/fhir/ValueSet/structure-definition-kind` | `Required` | primitive-type \| complex-type \| resource \| logical |

### Referenced Systems

* `http://hl7.org/fhir/structure-definition-kind`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [StructureDefinitionKind](/docs/R2/ValueSets/StructureDefinitionKind.md)<br/> `http://hl7.org/fhir/ValueSet/structure-definition-kind\|1.0.2` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `133`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `291`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [StructureDefinitionKind](/docs/R3/ValueSets/StructureDefinitionKind.md)<br/> `http://hl7.org/fhir/ValueSet/structure-definition-kind\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `493`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `716`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [StructureDefinitionKind](/docs/R4/ValueSets/StructureDefinitionKind.md)<br/> `http://hl7.org/fhir/ValueSet/structure-definition-kind\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1747`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1748`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [StructureDefinitionKind](/docs/R4B/ValueSets/StructureDefinitionKind.md)<br/> `http://hl7.org/fhir/ValueSet/structure-definition-kind\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `982`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1243`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [StructureDefinitionKind](/docs/R5/ValueSets/StructureDefinitionKind.md)<br/> `http://hl7.org/fhir/ValueSet/structure-definition-kind\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set StructureDefinitionKind from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 StructureDefinitionKind](/docs/R2/ValueSets/StructureDefinitionKind.md)| Relationship | R3 StructureDefinitionKind| Relationship | [R4 StructureDefinitionKind](/docs/R4/ValueSets/StructureDefinitionKind.md)| Relationship | [R4B StructureDefinitionKind](/docs/R4B/ValueSets/StructureDefinitionKind.md)| Relationship | [R5 StructureDefinitionKind](/docs/R5/ValueSets/StructureDefinitionKind.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/structure-definition-kind`
| `datatype`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1109)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2529) | **`primitive-type`**| _Equivalent_ <br/>(4596/6908)| `primitive-type`| _Equivalent_ <br/>(18228/18229)| `primitive-type`| _Equivalent_ <br/>(9342/11680)| `primitive-type`
| `datatype`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1108)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2527) | **`complex-type`**| _Equivalent_ <br/>(4598/6910)| `complex-type`| _Equivalent_ <br/>(18230/18231)| `complex-type`| _Equivalent_ <br/>(9344/11682)| `complex-type`
| `resource`| _Equivalent_ <br/>(1111/2530)| **`resource`**| _Equivalent_ <br/>(4597/6909)| `resource`| _Equivalent_ <br/>(18232/18233)| `resource`| _Equivalent_ <br/>(9343/11681)| `resource`
| `logical`| _Equivalent_ <br/>(1110/2528)| **`logical`**| _Equivalent_ <br/>(4599/6911)| `logical`| _Equivalent_ <br/>(18234/18235)| `logical`| _Equivalent_ <br/>(9345/11683)| `logical`
| *3 of 3 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* 

