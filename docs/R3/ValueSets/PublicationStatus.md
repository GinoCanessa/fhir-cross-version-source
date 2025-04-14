Comparison of 
Generated at Monday, April 14, 2025 6:17:19 PM

### PublicationStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | PublicationStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/publication-status` |
| Version | 3.0.2 |
| Description | The lifecycle status of a Value Set or Concept Map. |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `1413` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ActivityDefinition` | `ActivityDefinition.status` | `http://hl7.org/fhir/ValueSet/publication-status` | `Required` | draft \| active \| retired \| unknown |
| `http://hl7.org/fhir/StructureDefinition/CapabilityStatement` | `CapabilityStatement.status` | `http://hl7.org/fhir/ValueSet/publication-status` | `Required` | draft \| active \| retired \| unknown |
| `http://hl7.org/fhir/StructureDefinition/CodeSystem` | `CodeSystem.status` | `http://hl7.org/fhir/ValueSet/publication-status` | `Required` | draft \| active \| retired \| unknown |
| `http://hl7.org/fhir/StructureDefinition/CompartmentDefinition` | `CompartmentDefinition.status` | `http://hl7.org/fhir/ValueSet/publication-status` | `Required` | draft \| active \| retired \| unknown |
| `http://hl7.org/fhir/StructureDefinition/ConceptMap` | `ConceptMap.status` | `http://hl7.org/fhir/ValueSet/publication-status` | `Required` | draft \| active \| retired \| unknown |
| `http://hl7.org/fhir/StructureDefinition/DataElement` | `DataElement.status` | `http://hl7.org/fhir/ValueSet/publication-status` | `Required` | draft \| active \| retired \| unknown |
| `http://hl7.org/fhir/StructureDefinition/ExpansionProfile` | `ExpansionProfile.status` | `http://hl7.org/fhir/ValueSet/publication-status` | `Required` | draft \| active \| retired \| unknown |
| `http://hl7.org/fhir/StructureDefinition/GraphDefinition` | `GraphDefinition.status` | `http://hl7.org/fhir/ValueSet/publication-status` | `Required` | draft \| active \| retired \| unknown |
| `http://hl7.org/fhir/StructureDefinition/ImplementationGuide` | `ImplementationGuide.status` | `http://hl7.org/fhir/ValueSet/publication-status` | `Required` | draft \| active \| retired \| unknown |
| `http://hl7.org/fhir/StructureDefinition/Library` | `Library.status` | `http://hl7.org/fhir/ValueSet/publication-status` | `Required` | draft \| active \| retired \| unknown |
| `http://hl7.org/fhir/StructureDefinition/Measure` | `Measure.status` | `http://hl7.org/fhir/ValueSet/publication-status` | `Required` | draft \| active \| retired \| unknown |
| `http://hl7.org/fhir/StructureDefinition/MessageDefinition` | `MessageDefinition.status` | `http://hl7.org/fhir/ValueSet/publication-status` | `Required` | draft \| active \| retired \| unknown |
| `http://hl7.org/fhir/StructureDefinition/NamingSystem` | `NamingSystem.status` | `http://hl7.org/fhir/ValueSet/publication-status` | `Required` | draft \| active \| retired \| unknown |
| `http://hl7.org/fhir/StructureDefinition/OperationDefinition` | `OperationDefinition.status` | `http://hl7.org/fhir/ValueSet/publication-status` | `Required` | draft \| active \| retired \| unknown |
| `http://hl7.org/fhir/StructureDefinition/PlanDefinition` | `PlanDefinition.status` | `http://hl7.org/fhir/ValueSet/publication-status` | `Required` | draft \| active \| retired \| unknown |
| `http://hl7.org/fhir/StructureDefinition/Questionnaire` | `Questionnaire.status` | `http://hl7.org/fhir/ValueSet/publication-status` | `Required` | draft \| active \| retired \| unknown |
| `http://hl7.org/fhir/StructureDefinition/SearchParameter` | `SearchParameter.status` | `http://hl7.org/fhir/ValueSet/publication-status` | `Required` | draft \| active \| retired \| unknown |
| `http://hl7.org/fhir/StructureDefinition/ServiceDefinition` | `ServiceDefinition.status` | `http://hl7.org/fhir/ValueSet/publication-status` | `Required` | draft \| active \| retired \| unknown |
| `http://hl7.org/fhir/StructureDefinition/StructureDefinition` | `StructureDefinition.status` | `http://hl7.org/fhir/ValueSet/publication-status` | `Required` | draft \| active \| retired \| unknown |
| `http://hl7.org/fhir/StructureDefinition/StructureMap` | `StructureMap.status` | `http://hl7.org/fhir/ValueSet/publication-status` | `Required` | draft \| active \| retired \| unknown |
| `http://hl7.org/fhir/StructureDefinition/TestScript` | `TestScript.status` | `http://hl7.org/fhir/ValueSet/publication-status` | `Required` | draft \| active \| retired \| unknown |
| `http://hl7.org/fhir/StructureDefinition/ValueSet` | `ValueSet.status` | `http://hl7.org/fhir/ValueSet/publication-status` | `Required` | draft \| active \| retired \| unknown |

### Referenced Systems

* `http://hl7.org/fhir/publication-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ConformanceResourceStatus](/docs/R2/ValueSets/ConformanceResourceStatus.md)<br/> `http://hl7.org/fhir/ValueSet/conformance-resource-status\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `24`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>*no map*<br/>←←←←←←←| [PublicationStatus](/docs/R3/ValueSets/PublicationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/publication-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `325`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `547`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [PublicationStatus](/docs/R4/ValueSets/PublicationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/publication-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1663`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1664`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [PublicationStatus](/docs/R4B/ValueSets/PublicationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/publication-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `771`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1032`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [PublicationStatus](/docs/R5/ValueSets/PublicationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/publication-status\|5.0.0` 
| [QuestionnaireStatus](/docs/R2/ValueSets/QuestionnaireStatus.md)<br/> `http://hl7.org/fhir/ValueSet/questionnaire-status\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `128`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>*no map*<br/>←←←←←←←| [PublicationStatus](/docs/R3/ValueSets/PublicationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/publication-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `325`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `547`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [PublicationStatus](/docs/R4/ValueSets/PublicationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/publication-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1663`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1664`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [PublicationStatus](/docs/R4B/ValueSets/PublicationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/publication-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `771`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1032`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [PublicationStatus](/docs/R5/ValueSets/PublicationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/publication-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set PublicationStatus from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 ConformanceResourceStatus](/docs/R2/ValueSets/ConformanceResourceStatus.md)| Relationship | R3 PublicationStatus| Relationship | [R4 PublicationStatus](/docs/R4/ValueSets/PublicationStatus.md)| Relationship | [R4B PublicationStatus](/docs/R4B/ValueSets/PublicationStatus.md)| Relationship | [R5 PublicationStatus](/docs/R5/ValueSets/PublicationStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/publication-status`
| `draft`| _Equivalent_ <br/>(113/1485)| **`draft`**| _Equivalent_ <br/>(2889/5078)| `draft`| _Equivalent_ <br/>(16810/16811)| `draft`| _Equivalent_ <br/>(7429/9694)| `draft`
| `active`| _Equivalent_ <br/>(114/1484)| **`active`**| _Equivalent_ <br/>(2890/5079)| `active`| _Equivalent_ <br/>(16812/16813)| `active`| _Equivalent_ <br/>(7430/9695)| `active`
| `retired`| _Equivalent_ <br/>(115/1486)| **`retired`**| _Equivalent_ <br/>(2891/5080)| `retired`| _Equivalent_ <br/>(16814/16815)| `retired`| _Equivalent_ <br/>(7431/9696)| `retired`
| | | **`unknown`**| _Equivalent_ <br/>(2892/5081)| `unknown`| _Equivalent_ <br/>(16816/16817)| `unknown`| _Equivalent_ <br/>(7432/9697)| `unknown`
| *3 of 3 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* 


#### Map Group 1

This group is centered on the Value Set PublicationStatus from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 QuestionnaireStatus](/docs/R2/ValueSets/QuestionnaireStatus.md)| Relationship | R3 PublicationStatus| Relationship | [R4 PublicationStatus](/docs/R4/ValueSets/PublicationStatus.md)| Relationship | [R4B PublicationStatus](/docs/R4B/ValueSets/PublicationStatus.md)| Relationship | [R5 PublicationStatus](/docs/R5/ValueSets/PublicationStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/publication-status`
| `draft`| _Equivalent_ <br/>(1085/2502)| **`draft`**| _Equivalent_ <br/>(2889/5078)| `draft`| _Equivalent_ <br/>(16810/16811)| `draft`| _Equivalent_ <br/>(7429/9694)| `draft`
| `published`| _Equivalent_ <br/>(1086/2501)| **`active`**| _Equivalent_ <br/>(2890/5079)| `active`| _Equivalent_ <br/>(16812/16813)| `active`| _Equivalent_ <br/>(7430/9695)| `active`
| `retired`| _Equivalent_ <br/>(1087/2503)| **`retired`**| _Equivalent_ <br/>(2891/5080)| `retired`| _Equivalent_ <br/>(16814/16815)| `retired`| _Equivalent_ <br/>(7431/9696)| `retired`
| | | **`unknown`**| _Equivalent_ <br/>(2892/5081)| `unknown`| _Equivalent_ <br/>(16816/16817)| `unknown`| _Equivalent_ <br/>(7432/9697)| `unknown`
| *3 of 3 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* 

