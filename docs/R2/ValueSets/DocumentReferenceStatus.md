Comparison of 
Generated at Tuesday, April 1, 2025 1:39:07 PM

### DocumentReferenceStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | DocumentReferenceStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/document-reference-status` |
| Version | 1.0.2 |
| Description | The status of the document reference. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `140` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/DocumentManifest` | `DocumentManifest.status` | `http://hl7.org/fhir/ValueSet/document-reference-status` | `Required` | current \| superseded \| entered-in-error |
| `http://hl7.org/fhir/StructureDefinition/DocumentReference` | `DocumentReference.status` | `http://hl7.org/fhir/ValueSet/document-reference-status` | `Required` | current \| superseded \| entered-in-error |

### Referenced Systems

* `http://hl7.org/fhir/document-reference-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [DocumentReferenceStatus](/docs/R2/ValueSets/DocumentReferenceStatus.md)<br/> `http://hl7.org/fhir/ValueSet/document-reference-status\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `51`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `210`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DocumentReferenceStatus](/docs/R3/ValueSets/DocumentReferenceStatus.md)<br/> `http://hl7.org/fhir/ValueSet/document-reference-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `388`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `611`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DocumentReferenceStatus](/docs/R4/ValueSets/DocumentReferenceStatus.md)<br/> `http://hl7.org/fhir/ValueSet/document-reference-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1481`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1482`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DocumentReferenceStatus](/docs/R4B/ValueSets/DocumentReferenceStatus.md)<br/> `http://hl7.org/fhir/ValueSet/document-reference-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `851`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1112`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DocumentReferenceStatus](/docs/R5/ValueSets/DocumentReferenceStatus.md)<br/> `http://hl7.org/fhir/ValueSet/document-reference-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set DocumentReferenceStatus from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 DocumentReferenceStatus| Relationship | [R3 DocumentReferenceStatus](/docs/R3/ValueSets/DocumentReferenceStatus.md)| Relationship | [R4 DocumentReferenceStatus](/docs/R4/ValueSets/DocumentReferenceStatus.md)| Relationship | [R4B DocumentReferenceStatus](/docs/R4B/ValueSets/DocumentReferenceStatus.md)| Relationship | [R5 DocumentReferenceStatus](/docs/R5/ValueSets/DocumentReferenceStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/document-reference-status`
| **`current`**| _Equivalent_ <br/>(243/1616)| `current`| _Equivalent_ <br/>(3210/5422)| `current`| _Equivalent_ <br/>(15814/15815)| `current`| _Equivalent_ <br/>(7939/10246)| `current`
| **`superseded`**| _Equivalent_ <br/>(244/1617)| `superseded`| _Equivalent_ <br/>(3211/5423)| `superseded`| _Equivalent_ <br/>(15816/15817)| `superseded`| _Equivalent_ <br/>(7940/10247)| `superseded`
| **`entered-in-error`**| _Equivalent_ <br/>(245/1618)| `entered-in-error`| _Equivalent_ <br/>(3212/5424)| `entered-in-error`| _Equivalent_ <br/>(15818/15819)| `entered-in-error`| _Equivalent_ <br/>(7941/10248)| `entered-in-error`
| *3 of 3 codes used* | | *3 of 3 codes used* | | *3 of 3 codes used* | | *3 of 3 codes used* | | *3 of 3 codes used* 

