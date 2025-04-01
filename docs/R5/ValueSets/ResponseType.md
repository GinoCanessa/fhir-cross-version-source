Comparison of 
Generated at Tuesday, April 1, 2025 1:39:33 PM

### ResponseType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | ResponseType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/response-code` |
| Version | 5.0.0 |
| Description | The kind of response to a message. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4876` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/MessageHeader` | `MessageHeader.response.code` | `http://hl7.org/fhir/ValueSet/response-code\|5.0.0` | `Required` | ok \| transient-error \| fatal-error |

### Referenced Systems

* `http://hl7.org/fhir/response-code`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ResponseType](/docs/R2/ValueSets/ResponseType.md)<br/> `http://hl7.org/fhir/ValueSet/response-code\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `98`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `254`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ResponseType](/docs/R3/ValueSets/ResponseType.md)<br/> `http://hl7.org/fhir/ValueSet/response-code\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `449`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `671`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ResponseType](/docs/R4/ValueSets/ResponseType.md)<br/> `http://hl7.org/fhir/ValueSet/response-code\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1717`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1718`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ResponseType](/docs/R4B/ValueSets/ResponseType.md)<br/> `http://hl7.org/fhir/ValueSet/response-code\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `930`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1191`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ResponseType](/docs/R5/ValueSets/ResponseType.md)<br/> `http://hl7.org/fhir/ValueSet/response-code\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set ResponseType from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 ResponseType](/docs/R2/ValueSets/ResponseType.md)| Relationship | [R3 ResponseType](/docs/R3/ValueSets/ResponseType.md)| Relationship | [R4 ResponseType](/docs/R4/ValueSets/ResponseType.md)| Relationship | [R4B ResponseType](/docs/R4B/ValueSets/ResponseType.md)| Relationship | R5 ResponseType
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/response-code`
| `ok`| _Equivalent_ <br/>(810/2174)| `ok`| _Equivalent_ <br/>(3997/6322)| `ok`| _Equivalent_ <br/>(17408/17409)| `ok`| _Equivalent_ <br/>(9002/11311)| **`ok`**
| `transient-error`| _Equivalent_ <br/>(811/2175)| `transient-error`| _Equivalent_ <br/>(3998/6323)| `transient-error`| _Equivalent_ <br/>(17410/17411)| `transient-error`| _Equivalent_ <br/>(9003/11312)| **`transient-error`**
| `fatal-error`| _Equivalent_ <br/>(809/2173)| `fatal-error`| _Equivalent_ <br/>(3996/6321)| `fatal-error`| _Equivalent_ <br/>(17412/17413)| `fatal-error`| _Equivalent_ <br/>(9001/11310)| **`fatal-error`**
| *3 of 3 codes used* | | *3 of 3 codes used* | | *3 of 3 codes used* | | *3 of 3 codes used* | | *3 of 3 codes used* 

