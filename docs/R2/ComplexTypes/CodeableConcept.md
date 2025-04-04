Comparison of 
Generated at Friday, April 4, 2025 2:58:33 PM

### CodeableConcept

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | CodeableConcept |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/CodeableConcept` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for CodeableConcept Type |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `23` |
| Database Snapshot Count | `5` |
| Database Differential Count | `3` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `CodeableConcept` | `CodeableConcept` | `CodeableConcept` | CodeableConcept | Concept - reference to a terminology or just  text | 0..* | CodeableConcept |  |  |
| `CodeableConcept.coding` | `CodeableConcept.coding` | `coding` |  | Code defined by a terminology system | 0..* | Coding |  |  |
| `CodeableConcept.extension` | `CodeableConcept.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `CodeableConcept.id` | `CodeableConcept.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `CodeableConcept.text` | `CodeableConcept.text` | `text` |  | Plain text representation of the concept | 0..1 | string |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [CodeableConcept](/docs/R2/ComplexTypes/CodeableConcept.md)<br/> `http://hl7.org/fhir/StructureDefinition/CodeableConcept\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `50`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `217`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CodeableConcept](/docs/R3/ComplexTypes/CodeableConcept.md)<br/> `http://hl7.org/fhir/StructureDefinition/CodeableConcept\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `386`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `582`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CodeableConcept](/docs/R4/ComplexTypes/CodeableConcept.md)<br/> `http://hl7.org/fhir/StructureDefinition/CodeableConcept\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1317`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1318`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CodeableConcept](/docs/R4B/ComplexTypes/CodeableConcept.md)<br/> `http://hl7.org/fhir/StructureDefinition/CodeableConcept\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `893`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1122`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CodeableConcept](/docs/R5/ComplexTypes/CodeableConcept.md)<br/> `http://hl7.org/fhir/StructureDefinition/CodeableConcept\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition CodeableConcept from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 CodeableConcept| Relationship | [R3 CodeableConcept](/docs/R3/ComplexTypes/CodeableConcept.md)| Relationship | [R4 CodeableConcept](/docs/R4/ComplexTypes/CodeableConcept.md)| Relationship | [R4B CodeableConcept](/docs/R4B/ComplexTypes/CodeableConcept.md)| Relationship | [R5 CodeableConcept](/docs/R5/ComplexTypes/CodeableConcept.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`CodeableConcept`**| _Equivalent_<br/>(2483/2484)| `CodeableConcept`| _Equivalent_<br/>(9212/9213)| `CodeableConcept`| _Equivalent_<br/>(20562/20563)| `CodeableConcept`| _Equivalent_<br/>(35679/35680)| `CodeableConcept`
| **`CodeableConcept.id`**| _Equivalent_<br/>(2485/2486)| `CodeableConcept.id`| _Equivalent_<br/>(9214/9215)| `CodeableConcept.id`| _Equivalent_<br/>(20564/20565)| `CodeableConcept.id`| _Equivalent_<br/>(35681/35682)| `CodeableConcept.id`
| **`CodeableConcept.extension`**| _Equivalent_<br/>(2487/2488)| `CodeableConcept.extension`| _Equivalent_<br/>(9216/9217)| `CodeableConcept.extension`| _Equivalent_<br/>(20566/20567)| `CodeableConcept.extension`| _Equivalent_<br/>(35683/35684)| `CodeableConcept.extension`
| **`CodeableConcept.coding`**| _Equivalent_<br/>(2489/2490)| `CodeableConcept.coding`| _Equivalent_<br/>(9218/9219)| `CodeableConcept.coding`| _Equivalent_<br/>(20568/20569)| `CodeableConcept.coding`| _Equivalent_<br/>(35685/35686)| `CodeableConcept.coding`
| **`CodeableConcept.text`**| _Equivalent_<br/>(2491/2492)| `CodeableConcept.text`| _Equivalent_<br/>(9220/9221)| `CodeableConcept.text`| _Equivalent_<br/>(20570/20571)| `CodeableConcept.text`| _Equivalent_<br/>(35687/35688)| `CodeableConcept.text`
| *5 of 5 elements used* | | *5 of 5 elements used* | | *5 of 5 elements used* | | *5 of 5 elements used* | | *5 of 5 elements used* 

