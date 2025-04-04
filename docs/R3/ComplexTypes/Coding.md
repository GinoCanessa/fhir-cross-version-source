Comparison of 
Generated at Friday, April 4, 2025 2:58:38 PM

### Coding

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | Coding |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Coding` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for Coding Type |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `446` |
| Database Snapshot Count | `8` |
| Database Differential Count | `6` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Coding` | `Coding` | `Coding` | Coding | A reference to a code defined by a terminology system | 0..* | Coding |  |  |
| `Coding.code` | `Coding.code` | `code` |  | Symbol in syntax defined by the system | 0..1 | code |  |  |
| `Coding.display` | `Coding.display` | `display` |  | Representation defined by the system | 0..1 | string |  |  |
| `Coding.extension` | `Coding.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Coding.id` | `Coding.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Coding.system` | `Coding.system` | `system` |  | Identity of the terminology system | 0..1 | uri |  |  |
| `Coding.userSelected` | `Coding.userSelected` | `userSelected` |  | If this coding was chosen directly by the user | 0..1 | boolean |  |  |
| `Coding.version` | `Coding.version` | `version` |  | Version of the system - if relevant | 0..1 | string |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Coding](/docs/R2/ComplexTypes/Coding.md)<br/> `http://hl7.org/fhir/StructureDefinition/Coding\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `51`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `218`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Coding](/docs/R3/ComplexTypes/Coding.md)<br/> `http://hl7.org/fhir/StructureDefinition/Coding\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `387`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `583`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Coding](/docs/R4/ComplexTypes/Coding.md)<br/> `http://hl7.org/fhir/StructureDefinition/Coding\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1319`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1320`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Coding](/docs/R4B/ComplexTypes/Coding.md)<br/> `http://hl7.org/fhir/StructureDefinition/Coding\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `895`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1124`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Coding](/docs/R5/ComplexTypes/Coding.md)<br/> `http://hl7.org/fhir/StructureDefinition/Coding\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Coding from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Coding](/docs/R2/ComplexTypes/Coding.md)| Relationship | R3 Coding| Relationship | [R4 Coding](/docs/R4/ComplexTypes/Coding.md)| Relationship | [R4B Coding](/docs/R4B/ComplexTypes/Coding.md)| Relationship | [R5 Coding](/docs/R5/ComplexTypes/Coding.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `Coding`| _Equivalent_<br/>(2493/2494)| **`Coding`**| _Equivalent_<br/>(9222/9223)| `Coding`| _Equivalent_<br/>(20572/20573)| `Coding`| _Equivalent_<br/>(35699/35700)| `Coding`
| `Coding.id`| _Equivalent_<br/>(2495/2496)| **`Coding.id`**| _Equivalent_<br/>(9224/9225)| `Coding.id`| _Equivalent_<br/>(20574/20575)| `Coding.id`| _Equivalent_<br/>(35701/35702)| `Coding.id`
| `Coding.extension`| _Equivalent_<br/>(2497/2498)| **`Coding.extension`**| _Equivalent_<br/>(9226/9227)| `Coding.extension`| _Equivalent_<br/>(20576/20577)| `Coding.extension`| _Equivalent_<br/>(35703/35704)| `Coding.extension`
| `Coding.system`| _Equivalent_<br/>(2499/2500)| **`Coding.system`**| _Equivalent_<br/>(9228/9229)| `Coding.system`| _Equivalent_<br/>(20578/20579)| `Coding.system`| _Equivalent_<br/>(35705/35706)| `Coding.system`
| `Coding.version`| _Equivalent_<br/>(2501/2502)| **`Coding.version`**| _Equivalent_<br/>(9230/9231)| `Coding.version`| _Equivalent_<br/>(20580/20581)| `Coding.version`| _Equivalent_<br/>(35707/35708)| `Coding.version`
| `Coding.code`| _Equivalent_<br/>(2503/2504)| **`Coding.code`**| _Equivalent_<br/>(9232/9233)| `Coding.code`| _Equivalent_<br/>(20582/20583)| `Coding.code`| _Equivalent_<br/>(35709/35710)| `Coding.code`
| `Coding.display`| _Equivalent_<br/>(2505/2506)| **`Coding.display`**| _Equivalent_<br/>(9234/9235)| `Coding.display`| _Equivalent_<br/>(20584/20585)| `Coding.display`| _Equivalent_<br/>(35711/35712)| `Coding.display`
| `Coding.userSelected`| _Equivalent_<br/>(2507/2508)| **`Coding.userSelected`**| _Equivalent_<br/>(9236/9237)| `Coding.userSelected`| _Equivalent_<br/>(20586/20587)| `Coding.userSelected`| _Equivalent_<br/>(35713/35714)| `Coding.userSelected`
| *8 of 8 elements used* | | *8 of 8 elements used* | | *8 of 8 elements used* | | *8 of 8 elements used* | | *8 of 8 elements used* 

