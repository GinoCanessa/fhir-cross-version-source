Comparison of 
Generated at Tuesday, April 1, 2025 1:39:34 PM

### EvidenceCertaintyType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | EvidenceCertaintyType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/certainty-type` |
| Version | 5.0.0 |
| Description | The aspect of quality, confidence, or certainty. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4344` |
| Database Concept Count | `9` |
| Database Active Concept Count | `9` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ArtifactAssessment` | `ArtifactAssessment.content.type` | `http://hl7.org/fhir/ValueSet/certainty-type` | `Example` | What type of content |
| `http://hl7.org/fhir/StructureDefinition/Evidence` | `Evidence.certainty.type` | `http://hl7.org/fhir/ValueSet/certainty-type` | `Extensible` | Aspect of certainty being rated |

### Referenced Systems

* `http://hl7.org/fhir/certainty-type`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [EvidenceCertaintyType](/docs/R4B/ValueSets/EvidenceCertaintyType.md)<br/> `http://hl7.org/fhir/ValueSet/certainty-type\|4.3.0` | →→→→→→→<br/>``<br/>- DBKey: `879`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `1140`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EvidenceCertaintyType](/docs/R5/ValueSets/EvidenceCertaintyType.md)<br/> `http://hl7.org/fhir/ValueSet/certainty-type\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set EvidenceCertaintyType from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | [R4B EvidenceCertaintyType](/docs/R4B/ValueSets/EvidenceCertaintyType.md)| Relationship | R5 EvidenceCertaintyType
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/certainty-type`
| | | | | | | `Overall`| _Equivalent_ <br/>(8081/10386)| **`Overall`**
| | | | | | | `RiskOfBias`| _Equivalent_ <br/>(8084/10389)| **`RiskOfBias`**
| | | | | | | `Inconsistency`| _Equivalent_ <br/>(8082/10387)| **`Inconsistency`**
| | | | | | | `Indirectness`| _Equivalent_ <br/>(8083/10388)| **`Indirectness`**
| | | | | | | `Imprecision`| _Equivalent_ <br/>(8088/10393)| **`Imprecision`**
| | | | | | | `PublicationBias`| _Equivalent_ <br/>(8087/10392)| **`PublicationBias`**
| | | | | | | `DoseResponseGradient`| _Equivalent_ <br/>(8085/10390)| **`DoseResponseGradient`**
| | | | | | | `PlausibleConfounding`| _Equivalent_ <br/>(8086/10391)| **`PlausibleConfounding`**
| | | | | | | `LargeEffect`| _Equivalent_ <br/>(8080/10385)| **`LargeEffect`**
| | | | | | | *9 of 9 codes used* | | *9 of 9 codes used* 

