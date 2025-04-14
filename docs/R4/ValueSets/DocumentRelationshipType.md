Comparison of 
Generated at Monday, April 14, 2025 6:17:27 PM

### DocumentRelationshipType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | DocumentRelationshipType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/document-relationship-type` |
| Version | 4.0.1 |
| Description | The type of relationship between documents. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2397` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Composition` | `Composition.relatesTo.code` | `http://hl7.org/fhir/ValueSet/document-relationship-type\|4.0.1` | `Required` | replaces \| transforms \| signs \| appends |
| `http://hl7.org/fhir/StructureDefinition/DocumentReference` | `DocumentReference.relatesTo.code` | `http://hl7.org/fhir/ValueSet/document-relationship-type\|4.0.1` | `Required` | replaces \| transforms \| signs \| appends |

### Referenced Systems

* `http://hl7.org/fhir/document-relationship-type`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [DocumentRelationshipType](/docs/R2/ValueSets/DocumentRelationshipType.md)<br/> `http://hl7.org/fhir/ValueSet/document-relationship-type\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `52`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `211`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [DocumentRelationshipType](/docs/R3/ValueSets/DocumentRelationshipType.md)<br/> `http://hl7.org/fhir/ValueSet/document-relationship-type\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `353`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `576`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [DocumentRelationshipType](/docs/R4/ValueSets/DocumentRelationshipType.md)<br/> `http://hl7.org/fhir/ValueSet/document-relationship-type\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1483`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1484`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [DocumentRelationshipType](/docs/R4B/ValueSets/DocumentRelationshipType.md)<br/> `http://hl7.org/fhir/ValueSet/document-relationship-type\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `850`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1111`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [DocumentRelationshipType](/docs/R5/ValueSets/DocumentRelationshipType.md)<br/> `http://hl7.org/fhir/ValueSet/document-relationship-type\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set DocumentRelationshipType from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 DocumentRelationshipType](/docs/R2/ValueSets/DocumentRelationshipType.md)| Relationship | [R3 DocumentRelationshipType](/docs/R3/ValueSets/DocumentRelationshipType.md)| Relationship | R4 DocumentRelationshipType| Relationship | [R4B DocumentRelationshipType](/docs/R4B/ValueSets/DocumentRelationshipType.md)| Relationship | [R5 DocumentRelationshipType](/docs/R5/ValueSets/DocumentRelationshipType.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://hl7.org/fhir/document-relationship-type`
| `replaces`| _Equivalent_ <br/>(247/1620)| `replaces`| _Equivalent_ <br/>(3032/5240)| **`replaces`**| _Equivalent_ <br/>(15820/15821)| `replaces`| _Equivalent_ <br/>(7936/10242)| `replaces`
| `transforms`| _Equivalent_ <br/>(248/1621)| `transforms`| _Equivalent_ <br/>(3033/5241)| **`transforms`**| _Equivalent_ <br/>(15822/15823)| `transforms`| _Equivalent_ <br/>(7937/10245)| `transforms`
| `signs`| _Equivalent_ <br/>(246/1619)| `signs`| _Equivalent_ <br/>(3031/5239)| **`signs`**| _Equivalent_ <br/>(15824/15825)| `signs`| _Equivalent_ <br/>(7935/10243)| `signs`
| `appends`| _Equivalent_ <br/>(249/1622)| `appends`| _Equivalent_ <br/>(3034/5242)| **`appends`**| _Equivalent_ <br/>(15826/15827)| `appends`| _Equivalent_ <br/>(7938/10240)| `appends`
| *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 6 codes used* <br/>remaining codes:<br/>`incorporates`, `summarizes`

