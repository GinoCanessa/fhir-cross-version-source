Comparison of 
Generated at Monday, April 14, 2025 6:17:43 PM

### CitedArtifactStatusType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | CitedArtifactStatusType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/cited-artifact-status-type` |
| Version | 5.0.0 |
| Description | Cited Artifact Status Type |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `4356` |
| Database Concept Count | `16` |
| Database Active Concept Count | `16` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Citation` | `Citation.citedArtifact.currentState` | `http://hl7.org/fhir/ValueSet/cited-artifact-status-type` | `Extensible` | The status of the cited artifact |
| `http://hl7.org/fhir/StructureDefinition/Citation` | `Citation.citedArtifact.statusDate.activity` | `http://hl7.org/fhir/ValueSet/cited-artifact-status-type` | `Extensible` | Classification of the status |

### Referenced Systems

* `http://hl7.org/fhir/cited-artifact-status-type`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [CitedArtifactStatusType](/docs/R4B/ValueSets/CitedArtifactStatusType.md)<br/> `http://hl7.org/fhir/ValueSet/cited-artifact-status-type\|4.3.0` | →→→→→→→<br/>``<br/>- DBKey: `840`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `1101`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [CitedArtifactStatusType](/docs/R5/ValueSets/CitedArtifactStatusType.md)<br/> `http://hl7.org/fhir/ValueSet/cited-artifact-status-type\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set CitedArtifactStatusType from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | [R4B CitedArtifactStatusType](/docs/R4B/ValueSets/CitedArtifactStatusType.md)| Relationship | R5 CitedArtifactStatusType
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/cited-artifact-status-type`
| | | | | | | `created`| _Equivalent_ <br/>(7829/10133)| **`created`**
| | | | | | | `submitted`| _Equivalent_ <br/>(7837/10142)| **`submitted`**
| | | | | | | `withdrawn`| _Equivalent_ <br/>(7831/10135)| **`withdrawn`**
| | | | | | | `pre-review`| _Equivalent_ <br/>(7840/10145)| **`pre-review`**
| | | | | | | `under-review`| _Equivalent_ <br/>(7841/10146)| **`under-review`**
| | | | | | | `post-review-pre-published`| _Equivalent_ <br/>(7839/10144)| **`post-review-pre-published`**
| | | | | | | `rejected`| _Equivalent_ <br/>(7828/10132)| **`rejected`**
| | | | | | | `published-early-form`| _Equivalent_ <br/>(7830/10134)| **`published-early-form`**
| | | | | | | `published-final-form`| _Equivalent_ <br/>(7827/10131)| **`published-final-form`**
| | | | | | | `accepted`| _Equivalent_ <br/>(7832/10136)| **`accepted`**
| | | | | | | `archived`| _Equivalent_ <br/>(7834/10139)| **`archived`**
| | | | | | | `retracted`| _Equivalent_ <br/>(7835/10140)| **`retracted`**
| | | | | | | `draft`| _Equivalent_ <br/>(7838/10143)| **`draft`**
| | | | | | | `active`| _Equivalent_ <br/>(7833/10137)| **`active`**
| | | | | | | `approved`| _Equivalent_ <br/>(7836/10141)| **`approved`**
| | | | | | | | | **`unknown`**
| | | | | | | *15 of 15 codes used* | | *16 of 16 codes used* 

