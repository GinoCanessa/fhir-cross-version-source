Comparison of 
Generated at Thursday, April 3, 2025 8:18:04 AM

### ConformanceResourceStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | ConformanceResourceStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/conformance-resource-status` |
| Version | 1.0.2 |
| Description | The lifecycle status of a Value Set or Concept Map. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `73` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ConceptMap` | `ConceptMap.status` | `http://hl7.org/fhir/ValueSet/conformance-resource-status` | `Required` | draft \| active \| retired |
| `http://hl7.org/fhir/StructureDefinition/Conformance` | `Conformance.status` | `http://hl7.org/fhir/ValueSet/conformance-resource-status` | `Required` | draft \| active \| retired |
| `http://hl7.org/fhir/StructureDefinition/DataElement` | `DataElement.status` | `http://hl7.org/fhir/ValueSet/conformance-resource-status` | `Required` | draft \| active \| retired |
| `http://hl7.org/fhir/StructureDefinition/ImplementationGuide` | `ImplementationGuide.status` | `http://hl7.org/fhir/ValueSet/conformance-resource-status` | `Required` | draft \| active \| retired |
| `http://hl7.org/fhir/StructureDefinition/NamingSystem` | `NamingSystem.status` | `http://hl7.org/fhir/ValueSet/conformance-resource-status` | `Required` | draft \| active \| retired |
| `http://hl7.org/fhir/StructureDefinition/OperationDefinition` | `OperationDefinition.status` | `http://hl7.org/fhir/ValueSet/conformance-resource-status` | `Required` | draft \| active \| retired |
| `http://hl7.org/fhir/StructureDefinition/SearchParameter` | `SearchParameter.status` | `http://hl7.org/fhir/ValueSet/conformance-resource-status` | `Required` | draft \| active \| retired |
| `http://hl7.org/fhir/StructureDefinition/StructureDefinition` | `StructureDefinition.status` | `http://hl7.org/fhir/ValueSet/conformance-resource-status` | `Required` | draft \| active \| retired |
| `http://hl7.org/fhir/StructureDefinition/TestScript` | `TestScript.status` | `http://hl7.org/fhir/ValueSet/conformance-resource-status` | `Required` | draft \| active \| retired |
| `http://hl7.org/fhir/StructureDefinition/ValueSet` | `ValueSet.status` | `http://hl7.org/fhir/ValueSet/conformance-resource-status` | `Required` | draft \| active \| retired |

### Referenced Systems

* `http://hl7.org/fhir/conformance-resource-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ConformanceResourceStatus](/docs/R2/ValueSets/ConformanceResourceStatus.md)<br/> `http://hl7.org/fhir/ValueSet/conformance-resource-status\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `24`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `184`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [PublicationStatus](/docs/R3/ValueSets/PublicationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/publication-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `325`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `547`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [PublicationStatus](/docs/R4/ValueSets/PublicationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/publication-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1663`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1664`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [PublicationStatus](/docs/R4B/ValueSets/PublicationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/publication-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `771`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1032`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [PublicationStatus](/docs/R5/ValueSets/PublicationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/publication-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set ConformanceResourceStatus from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 ConformanceResourceStatus| Relationship | [R3 PublicationStatus](/docs/R3/ValueSets/PublicationStatus.md)| Relationship | [R4 PublicationStatus](/docs/R4/ValueSets/PublicationStatus.md)| Relationship | [R4B PublicationStatus](/docs/R4B/ValueSets/PublicationStatus.md)| Relationship | [R5 PublicationStatus](/docs/R5/ValueSets/PublicationStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/conformance-resource-status`
| **`draft`**| _Equivalent_ <br/>(113/1485)| `draft`| _Equivalent_ <br/>(2889/5078)| `draft`| _Equivalent_ <br/>(16810/16811)| `draft`| _Equivalent_ <br/>(7429/9694)| `draft`
| **`active`**| _Equivalent_ <br/>(114/1484)| `active`| _Equivalent_ <br/>(2890/5079)| `active`| _Equivalent_ <br/>(16812/16813)| `active`| _Equivalent_ <br/>(7430/9695)| `active`
| **`retired`**| _Equivalent_ <br/>(115/1486)| `retired`| _Equivalent_ <br/>(2891/5080)| `retired`| _Equivalent_ <br/>(16814/16815)| `retired`| _Equivalent_ <br/>(7431/9696)| `retired`
| *3 of 3 codes used* | | *3 of 4 codes used* <br/>remaining codes:<br/>`unknown`| | *3 of 4 codes used* <br/>remaining codes:<br/>`unknown`| | *3 of 4 codes used* <br/>remaining codes:<br/>`unknown`| | *3 of 4 codes used* <br/>remaining codes:<br/>`unknown`

