Comparison of 
Generated at Friday, April 4, 2025 2:58:58 PM

### EvidenceCertaintyRating

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | EvidenceCertaintyRating |
| Canonical URL | `http://hl7.org/fhir/ValueSet/certainty-rating` |
| Version | 5.0.0 |
| Description | The assessment of quality, confidence, or certainty. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4343` |
| Database Concept Count | `16` |
| Database Active Concept Count | `16` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ArtifactAssessment` | `ArtifactAssessment.content.classifier` | `http://hl7.org/fhir/ValueSet/certainty-rating` | `Example` | Rating, classifier, or assessment |
| `http://hl7.org/fhir/StructureDefinition/Evidence` | `Evidence.certainty.rating` | `http://hl7.org/fhir/ValueSet/certainty-rating` | `Extensible` | Assessment or judgement of the aspect |

### Referenced Systems

* `http://hl7.org/fhir/certainty-rating`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [EvidenceCertaintyRating](/docs/R4B/ValueSets/EvidenceCertaintyRating.md)<br/> `http://hl7.org/fhir/ValueSet/certainty-rating\|4.3.0` | →→→→→→→<br/>``<br/>- DBKey: `878`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `1139`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EvidenceCertaintyRating](/docs/R5/ValueSets/EvidenceCertaintyRating.md)<br/> `http://hl7.org/fhir/ValueSet/certainty-rating\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set EvidenceCertaintyRating from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | [R4B EvidenceCertaintyRating](/docs/R4B/ValueSets/EvidenceCertaintyRating.md)| Relationship | R5 EvidenceCertaintyRating
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/certainty-rating`
| | | | | | | `high`| _Equivalent_ <br/>(8067/10372)| **`high`**
| | | | | | | `moderate`| _Equivalent_ <br/>(8079/10384)| **`moderate`**
| | | | | | | `low`| _Equivalent_ <br/>(8070/10375)| **`low`**
| | | | | | | `very-low`| _Equivalent_ <br/>(8074/10379)| **`very-low`**
| | | | | | | `no-concern`| _Equivalent_ <br/>(8066/10371)| **`no-concern`**
| | | | | | | `serious-concern`| _Equivalent_ <br/>(8068/10373)| **`serious-concern`**
| | | | | | | `very-serious-concern`| _Equivalent_ <br/>(8072/10377)| **`very-serious-concern`**
| | | | | | | `extremely-serious-concern`| _Equivalent_ <br/>(8064/10369)| **`extremely-serious-concern`**
| | | | | | | `present`| _Equivalent_ <br/>(8076/10381)| **`present`**
| | | | | | | `absent`| _Equivalent_ <br/>(8073/10378)| **`absent`**
| | | | | | | `no-change`| _Equivalent_ <br/>(8065/10370)| **`no-change`**
| | | | | | | `downcode1`| _Equivalent_ <br/>(8078/10383)| **`downcode1`**
| | | | | | | `downcode2`| _Equivalent_ <br/>(8077/10382)| **`downcode2`**
| | | | | | | `downcode3`| _Equivalent_ <br/>(8075/10380)| **`downcode3`**
| | | | | | | `upcode1`| _Equivalent_ <br/>(8071/10376)| **`upcode1`**
| | | | | | | `upcode2`| _Equivalent_ <br/>(8069/10374)| **`upcode2`**
| | | | | | | *16 of 16 codes used* | | *16 of 16 codes used* 

