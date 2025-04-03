Comparison of 
Generated at Thursday, April 3, 2025 8:18:31 AM

### SlotStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | SlotStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/slotstatus` |
| Version | 5.0.0 |
| Description | The free/busy status of the slot. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4904` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Slot` | `Slot.status` | `http://hl7.org/fhir/ValueSet/slotstatus\|5.0.0` | `Required` | busy \| free \| busy-unavailable \| busy-tentative \| entered-in-error |

### Referenced Systems

* `http://hl7.org/fhir/slotstatus`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [SlotStatus](/docs/R2/ValueSets/SlotStatus.md)<br/> `http://hl7.org/fhir/ValueSet/slotstatus\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `144`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `302`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SlotStatus](/docs/R3/ValueSets/SlotStatus.md)<br/> `http://hl7.org/fhir/ValueSet/slotstatus\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `505`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `726`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SlotStatus](/docs/R4/ValueSets/SlotStatus.md)<br/> `http://hl7.org/fhir/ValueSet/slotstatus\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1735`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1736`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SlotStatus](/docs/R4B/ValueSets/SlotStatus.md)<br/> `http://hl7.org/fhir/ValueSet/slotstatus\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `984`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1245`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SlotStatus](/docs/R5/ValueSets/SlotStatus.md)<br/> `http://hl7.org/fhir/ValueSet/slotstatus\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set SlotStatus from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 SlotStatus](/docs/R2/ValueSets/SlotStatus.md)| Relationship | [R3 SlotStatus](/docs/R3/ValueSets/SlotStatus.md)| Relationship | [R4 SlotStatus](/docs/R4/ValueSets/SlotStatus.md)| Relationship | [R4B SlotStatus](/docs/R4B/ValueSets/SlotStatus.md)| Relationship | R5 SlotStatus
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/slotstatus`
| `busy`| _Equivalent_ <br/>(1270/2714)| `busy`| _Equivalent_ <br/>(4778/7099)| `busy`| _Equivalent_ <br/>(17506/17507)| `busy`| _Equivalent_ <br/>(9352/11690)| **`busy`**
| `free`| _Equivalent_ <br/>(1272/2718)| `free`| _Equivalent_ <br/>(4780/7101)| `free`| _Equivalent_ <br/>(17508/17509)| `free`| _Equivalent_ <br/>(9354/11692)| **`free`**
| `busy-unavailable`| _Equivalent_ <br/>(1269/2716)| `busy-unavailable`| _Equivalent_ <br/>(4777/7098)| `busy-unavailable`| _Equivalent_ <br/>(17510/17511)| `busy-unavailable`| _Equivalent_ <br/>(9351/11689)| **`busy-unavailable`**
| `busy-tentative`| _Equivalent_ <br/>(1271/2715)| `busy-tentative`| _Equivalent_ <br/>(4779/7100)| `busy-tentative`| _Equivalent_ <br/>(17512/17513)| `busy-tentative`| _Equivalent_ <br/>(9353/11691)| **`busy-tentative`**
| | | `entered-in-error`| _Equivalent_ <br/>(4781/7102)| `entered-in-error`| _Equivalent_ <br/>(17514/17515)| `entered-in-error`| _Equivalent_ <br/>(9355/11693)| **`entered-in-error`**
| *4 of 4 codes used* | | *5 of 5 codes used* | | *5 of 5 codes used* | | *5 of 5 codes used* | | *5 of 5 codes used* 

