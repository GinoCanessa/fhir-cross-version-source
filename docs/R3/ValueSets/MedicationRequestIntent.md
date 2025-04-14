Comparison of 
Generated at Monday, April 14, 2025 6:17:21 PM

### MedicationRequestIntent

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | MedicationRequestIntent |
| Canonical URL | `http://hl7.org/fhir/ValueSet/medication-request-intent` |
| Version | 3.0.2 |
| Description | The kind of medication order |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1333` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/MedicationRequest` | `MedicationRequest.intent` | `http://hl7.org/fhir/ValueSet/medication-request-intent` | `Required` | proposal \| plan \| order \| instance-order |

### Referenced Systems

* `http://hl7.org/fhir/medication-request-intent`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [MedicationRequestIntent](/docs/R3/ValueSets/MedicationRequestIntent.md)<br/> `http://hl7.org/fhir/ValueSet/medication-request-intent\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `443`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `665`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [medicationRequest Intent](/docs/R4/ValueSets/MedicationRequestIntent.md)<br/> `http://hl7.org/fhir/ValueSet/medicationrequest-intent\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1603`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1604`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [medicationRequest Intent](/docs/R4B/ValueSets/MedicationRequestIntent.md)<br/> `http://hl7.org/fhir/ValueSet/medicationrequest-intent\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `924`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1185`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [MedicationRequestIntent](/docs/R5/ValueSets/MedicationRequestIntent.md)<br/> `http://hl7.org/fhir/ValueSet/medicationrequest-intent\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set MedicationRequestIntent from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | R3 MedicationRequestIntent| Relationship | [R4 medicationRequest Intent](/docs/R4/ValueSets/MedicationRequestIntent.md)| Relationship | [R4B medicationRequest Intent](/docs/R4B/ValueSets/MedicationRequestIntent.md)| Relationship | [R5 MedicationRequestIntent](/docs/R5/ValueSets/MedicationRequestIntent.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/medication-request-intent`
| | | **`proposal`**| _Equivalent_ <br/>(3971/6297)| `proposal`| _Equivalent_ <br/>(16546/16547)| `proposal`| _Equivalent_ <br/>(8970/11279)| `proposal`
| | | **`plan`**| _Equivalent_ <br/>(3973/6296)| `plan`| _Equivalent_ <br/>(16548/16549)| `plan`| _Equivalent_ <br/>(8975/11284)| `plan`
| | | **`order`**| _Equivalent_ <br/>(3974/6294)| `order`| _Equivalent_ <br/>(16550/16551)| `order`| _Equivalent_ <br/>(8976/11285)| `order`
| | | **`instance-order`**| _Equivalent_ <br/>(3972/6292)| `instance-order`| _Equivalent_ <br/>(16558/16559)| `instance-order`| _Equivalent_ <br/>(8971/11280)| `instance-order`
| | | *4 of 4 codes used* | | *4 of 8 codes used* <br/>remaining codes:<br/>`filler-order`, `option`, `original-order`, `reflex-order`| | *4 of 8 codes used* <br/>remaining codes:<br/>`filler-order`, `option`, `original-order`, `reflex-order`| | *4 of 8 codes used* <br/>remaining codes:<br/>`filler-order`, `option`, `original-order`, `reflex-order`

