Comparison of 
Generated at Tuesday, April 1, 2025 1:39:26 PM

### HTTPVerb

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | HTTPVerb |
| Canonical URL | `http://hl7.org/fhir/ValueSet/http-verb` |
| Version | 4.3.0 |
| Description | HTTP verbs (in the HTTP command line). See [HTTP rfc](https://tools.ietf.org/html/rfc7231) for details. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `3810` |
| Database Concept Count | `6` |
| Database Active Concept Count | `6` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Bundle` | `Bundle.entry.request.method` | `http://hl7.org/fhir/ValueSet/http-verb\|4.3.0` | `Required` | GET \| HEAD \| POST \| PUT \| DELETE \| PATCH |

### Referenced Systems

* `http://hl7.org/fhir/http-verb`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [HTTPVerb](/docs/R2/ValueSets/HTTPVerb.md)<br/> `http://hl7.org/fhir/ValueSet/http-verb\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `15`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `174`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [HTTPVerb](/docs/R3/ValueSets/HTTPVerb.md)<br/> `http://hl7.org/fhir/ValueSet/http-verb\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `339`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `561`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [HTTPVerb](/docs/R4/ValueSets/HTTPVerb.md)<br/> `http://hl7.org/fhir/ValueSet/http-verb\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1537`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1538`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [HTTPVerb](/docs/R4B/ValueSets/HTTPVerb.md)<br/> `http://hl7.org/fhir/ValueSet/http-verb\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `784`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1045`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [HTTPVerb](/docs/R5/ValueSets/HTTPVerb.md)<br/> `http://hl7.org/fhir/ValueSet/http-verb\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set HTTPVerb from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 HTTPVerb](/docs/R2/ValueSets/HTTPVerb.md)| Relationship | [R3 HTTPVerb](/docs/R3/ValueSets/HTTPVerb.md)| Relationship | [R4 HTTPVerb](/docs/R4/ValueSets/HTTPVerb.md)| Relationship | R4B HTTPVerb| Relationship | [R5 HTTPVerb](/docs/R5/ValueSets/HTTPVerb.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://hl7.org/fhir/http-verb`
| `GET`| _Equivalent_ <br/>(71/1441)| `GET`| _Equivalent_ <br/>(2964/5166)| `GET`| _Equivalent_ <br/>(16178/16179)| **`GET`**| _Equivalent_ <br/>(7488/9751)| `GET`
| | | | | `HEAD`| _Equivalent_ <br/>(16180/16181)| **`HEAD`**| _Equivalent_ <br/>(7485/9748)| `HEAD`
| `POST`| _Equivalent_ <br/>(70/1440)| `POST`| _Equivalent_ <br/>(2963/5169)| `POST`| _Equivalent_ <br/>(16182/16183)| **`POST`**| _Equivalent_ <br/>(7487/9750)| `POST`
| `PUT`| _Equivalent_ <br/>(72/1442)| `PUT`| _Equivalent_ <br/>(2965/5170)| `PUT`| _Equivalent_ <br/>(16184/16185)| **`PUT`**| _Equivalent_ <br/>(7489/9752)| `PUT`
| `DELETE`| _Equivalent_ <br/>(69/1439)| `DELETE`| _Equivalent_ <br/>(2962/5165)| `DELETE`| _Equivalent_ <br/>(16186/16187)| **`DELETE`**| _Equivalent_ <br/>(7486/9749)| `DELETE`
| | | | | `PATCH`| _Equivalent_ <br/>(16188/16189)| **`PATCH`**| _Equivalent_ <br/>(7490/9753)| `PATCH`
| *4 of 4 codes used* | | *4 of 4 codes used* | | *6 of 6 codes used* | | *6 of 6 codes used* | | *6 of 6 codes used* 

