Comparison of 
Generated at Monday, April 14, 2025 6:17:35 PM

### CompartmentType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | CompartmentType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/compartment-type` |
| Version | 4.3.0 |
| Description | Which type a compartment definition describes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `3615` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/CompartmentDefinition` | `CompartmentDefinition.code` | `http://hl7.org/fhir/ValueSet/compartment-type\|4.3.0` | `Required` | Patient \| Encounter \| RelatedPerson \| Practitioner \| Device |
| `http://hl7.org/fhir/StructureDefinition/GraphDefinition` | `GraphDefinition.link.target.compartment.code` | `http://hl7.org/fhir/ValueSet/compartment-type\|4.3.0` | `Required` | Patient \| Encounter \| RelatedPerson \| Practitioner \| Device |

### Referenced Systems

* `http://hl7.org/fhir/compartment-type`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [CompartmentType](/docs/R3/ValueSets/CompartmentType.md)<br/> `http://hl7.org/fhir/ValueSet/compartment-type\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `374`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `597`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [CompartmentType](/docs/R4/ValueSets/CompartmentType.md)<br/> `http://hl7.org/fhir/ValueSet/compartment-type\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1423`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1424`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [CompartmentType](/docs/R4B/ValueSets/CompartmentType.md)<br/> `http://hl7.org/fhir/ValueSet/compartment-type\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `821`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1082`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [CompartmentType](/docs/R5/ValueSets/CompartmentType.md)<br/> `http://hl7.org/fhir/ValueSet/compartment-type\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set CompartmentType from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | [R3 CompartmentType](/docs/R3/ValueSets/CompartmentType.md)| Relationship | [R4 CompartmentType](/docs/R4/ValueSets/CompartmentType.md)| Relationship | R4B CompartmentType| Relationship | [R5 CompartmentType](/docs/R5/ValueSets/CompartmentType.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://hl7.org/fhir/compartment-type`
| | | `Patient`| _Equivalent_ <br/>(3130/5338)| `Patient`| _Equivalent_ <br/>(14686/14687)| **`Patient`**| _Equivalent_ <br/>(7701/10002)| `Patient`
| | | `Encounter`| _Equivalent_ <br/>(3131/5339)| `Encounter`| _Equivalent_ <br/>(14688/14689)| **`Encounter`**| _Equivalent_ <br/>(7702/10000)| `Encounter`
| | | `RelatedPerson`| _Equivalent_ <br/>(3132/5340)| `RelatedPerson`| _Equivalent_ <br/>(14690/14691)| **`RelatedPerson`**| _Equivalent_ <br/>(7703/10004)| `RelatedPerson`
| | | `Practitioner`| _Equivalent_ <br/>(3128/5336)| `Practitioner`| _Equivalent_ <br/>(14692/14693)| **`Practitioner`**| _Equivalent_ <br/>(7699/10003)| `Practitioner`
| | | `Device`| _Equivalent_ <br/>(3129/5337)| `Device`| _Equivalent_ <br/>(14694/14695)| **`Device`**| _Equivalent_ <br/>(7700/9999)| `Device`
| | | *5 of 5 codes used* | | *5 of 5 codes used* | | *5 of 5 codes used* | | *5 of 6 codes used* <br/>remaining codes:<br/>`EpisodeOfCare`

