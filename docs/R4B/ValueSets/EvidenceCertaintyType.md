Comparison of 
Generated at Monday, April 14, 2025 6:17:34 PM

### EvidenceCertaintyType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | EvidenceCertaintyType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/certainty-type` |
| Version | 4.3.0 |
| Description | The aspect of quality, confidence, or certainty. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `3579` |
| Database Concept Count | `9` |
| Database Active Concept Count | `9` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Evidence` | `Evidence.certainty.type` | `http://hl7.org/fhir/ValueSet/certainty-type` | `Extensible` | Aspect of certainty being rated |
| `http://hl7.org/fhir/StructureDefinition/cqf-certainty` | `Extension.extension.value[x]` | `http://hl7.org/fhir/ValueSet/certainty-type` | `Example` | Value of extension |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/certainty-type`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [EvidenceCertaintyType](/docs/R4B/ValueSets/EvidenceCertaintyType.md)<br/> `http://hl7.org/fhir/ValueSet/certainty-type\|4.3.0` | →→→→→→→<br/>``<br/>- DBKey: `879`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `1140`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [EvidenceCertaintyType](/docs/R5/ValueSets/EvidenceCertaintyType.md)<br/> `http://hl7.org/fhir/ValueSet/certainty-type\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set EvidenceCertaintyType from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | R4B EvidenceCertaintyType| Relationship | [R5 EvidenceCertaintyType](/docs/R5/ValueSets/EvidenceCertaintyType.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://terminology.hl7.org/CodeSystem/certainty-type`
| | | | | | | **`Overall`**| _Equivalent_ <br/>(8081/10386)| `Overall`
| | | | | | | **`RiskOfBias`**| _Equivalent_ <br/>(8084/10389)| `RiskOfBias`
| | | | | | | **`Inconsistency`**| _Equivalent_ <br/>(8082/10387)| `Inconsistency`
| | | | | | | **`Indirectness`**| _Equivalent_ <br/>(8083/10388)| `Indirectness`
| | | | | | | **`Imprecision`**| _Equivalent_ <br/>(8088/10393)| `Imprecision`
| | | | | | | **`PublicationBias`**| _Equivalent_ <br/>(8087/10392)| `PublicationBias`
| | | | | | | **`DoseResponseGradient`**| _Equivalent_ <br/>(8085/10390)| `DoseResponseGradient`
| | | | | | | **`PlausibleConfounding`**| _Equivalent_ <br/>(8086/10391)| `PlausibleConfounding`
| | | | | | | **`LargeEffect`**| _Equivalent_ <br/>(8080/10385)| `LargeEffect`
| | | | | | | *9 of 9 codes used* | | *9 of 9 codes used* 

