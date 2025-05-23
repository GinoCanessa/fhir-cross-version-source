Comparison of 
Generated at Monday, April 14, 2025 6:17:21 PM

### HTTPVerb

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | HTTPVerb |
| Canonical URL | `http://hl7.org/fhir/ValueSet/http-verb` |
| Version | 3.0.2 |
| Description | HTTP verbs (in the HTTP command line). |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1267` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Bundle` | `Bundle.entry.request.method` | `http://hl7.org/fhir/ValueSet/http-verb` | `Required` | GET \| POST \| PUT \| DELETE |

### Referenced Systems

* `http://hl7.org/fhir/http-verb`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [HTTPVerb](/docs/R2/ValueSets/HTTPVerb.md)<br/> `http://hl7.org/fhir/ValueSet/http-verb\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `15`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `174`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [HTTPVerb](/docs/R3/ValueSets/HTTPVerb.md)<br/> `http://hl7.org/fhir/ValueSet/http-verb\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `339`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `561`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [HTTPVerb](/docs/R4/ValueSets/HTTPVerb.md)<br/> `http://hl7.org/fhir/ValueSet/http-verb\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1537`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1538`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [HTTPVerb](/docs/R4B/ValueSets/HTTPVerb.md)<br/> `http://hl7.org/fhir/ValueSet/http-verb\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `784`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1045`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [HTTPVerb](/docs/R5/ValueSets/HTTPVerb.md)<br/> `http://hl7.org/fhir/ValueSet/http-verb\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set HTTPVerb from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 HTTPVerb](/docs/R2/ValueSets/HTTPVerb.md)| Relationship | R3 HTTPVerb| Relationship | [R4 HTTPVerb](/docs/R4/ValueSets/HTTPVerb.md)| Relationship | [R4B HTTPVerb](/docs/R4B/ValueSets/HTTPVerb.md)| Relationship | [R5 HTTPVerb](/docs/R5/ValueSets/HTTPVerb.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/http-verb`
| `GET`| _Equivalent_ <br/>(71/1441)| **`GET`**| _Equivalent_ <br/>(2964/5166)| `GET`| _Equivalent_ <br/>(16178/16179)| `GET`| _Equivalent_ <br/>(7488/9751)| `GET`
| `POST`| _Equivalent_ <br/>(70/1440)| **`POST`**| _Equivalent_ <br/>(2963/5169)| `POST`| _Equivalent_ <br/>(16182/16183)| `POST`| _Equivalent_ <br/>(7487/9750)| `POST`
| `PUT`| _Equivalent_ <br/>(72/1442)| **`PUT`**| _Equivalent_ <br/>(2965/5170)| `PUT`| _Equivalent_ <br/>(16184/16185)| `PUT`| _Equivalent_ <br/>(7489/9752)| `PUT`
| `DELETE`| _Equivalent_ <br/>(69/1439)| **`DELETE`**| _Equivalent_ <br/>(2962/5165)| `DELETE`| _Equivalent_ <br/>(16186/16187)| `DELETE`| _Equivalent_ <br/>(7486/9749)| `DELETE`
| *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 6 codes used* <br/>remaining codes:<br/>`HEAD`, `PATCH`| | *4 of 6 codes used* <br/>remaining codes:<br/>`HEAD`, `PATCH`| | *4 of 6 codes used* <br/>remaining codes:<br/>`HEAD`, `PATCH`

