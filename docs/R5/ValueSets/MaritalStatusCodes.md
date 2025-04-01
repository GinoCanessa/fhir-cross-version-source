Comparison of 
Generated at Tuesday, April 1, 2025 1:39:34 PM

### MaritalStatusCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | MaritalStatusCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/marital-status` |
| Version | 5.0.0 |
| Description | This value set defines the set of codes that can be used to indicate the marital status of a person. |
| Status | `Active` |
| Has Escape Valve Code | `True` |
| Database Key | `4682` |
| Database Concept Count | `12` |
| Database Active Concept Count | `12` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Patient` | `Patient.maritalStatus` | `http://hl7.org/fhir/ValueSet/marital-status` | `Extensible` | Marital (civil) status of a patient |
| `http://hl7.org/fhir/StructureDefinition/Person` | `Person.maritalStatus` | `http://hl7.org/fhir/ValueSet/marital-status` | `Extensible` | Marital (civil) status of a person |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/v3-MaritalStatus`
* `http://terminology.hl7.org/CodeSystem/v3-NullFlavor`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [Marital Status Codes](/docs/R4B/ValueSets/MaritalStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/marital-status\|4.3.0` | →→→→→→→<br/>``<br/>- DBKey: `950`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `1211`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MaritalStatusCodes](/docs/R5/ValueSets/MaritalStatusCodes.md)<br/> `http://hl7.org/fhir/ValueSet/marital-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set MaritalStatusCodes from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | [R4B Marital Status Codes](/docs/R4B/ValueSets/MaritalStatusCodes.md)| Relationship | R5 MaritalStatusCodes
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://terminology.hl7.org/CodeSystem/v3-MaritalStatus`
| | | | | | | `A`| _Equivalent_ <br/>(9166/11480)| **`A`**
| | | | | | | `D`| _Equivalent_ <br/>(9167/11481)| **`D`**
| | | | | | | `I`| _Equivalent_ <br/>(9168/11482)| **`I`**
| | | | | | | `L`| _Equivalent_ <br/>(9169/11483)| **`L`**
| | | | | | | `M`| _Equivalent_ <br/>(9170/11484)| **`M`**
| | | | | | | | | **`C`**
| | | | | | | `P`| _Equivalent_ <br/>(9171/11485)| **`P`**
| | | | | | | `T`| _Equivalent_ <br/>(9173/11487)| **`T`**
| | | | | | | `U`| _Equivalent_ <br/>(9174/11488)| **`U`**
| | | | | | | `S`| _Equivalent_ <br/>(9172/11486)| **`S`**
| | | | | | | `W`| _Equivalent_ <br/>(9175/11489)| **`W`**
| <td colspan="8">**R5** System: `http://terminology.hl7.org/CodeSystem/v3-NullFlavor`
| | | | | | | `UNK`| _Equivalent_ <br/>(9176/11490)| **`UNK`**
| | | | | | | *11 of 12 codes used* | | *12 of 12 codes used* 

