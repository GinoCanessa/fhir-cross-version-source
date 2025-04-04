Comparison of 
Generated at Friday, April 4, 2025 2:58:43 PM

### InvoiceStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | InvoiceStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/invoice-status` |
| Version | 4.0.1 |
| Description | Codes identifying the lifecycle stage of an Invoice. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2524` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Invoice` | `Invoice.status` | `http://hl7.org/fhir/ValueSet/invoice-status\|4.0.1` | `Required` | draft \| issued \| balanced \| cancelled \| entered-in-error |

### Referenced Systems

* `http://hl7.org/fhir/invoice-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [InvoiceStatus](/docs/R4/ValueSets/InvoiceStatus.md)<br/> `http://hl7.org/fhir/ValueSet/invoice-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1553`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1554`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [InvoiceStatus](/docs/R4B/ValueSets/InvoiceStatus.md)<br/> `http://hl7.org/fhir/ValueSet/invoice-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `906`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1167`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [InvoiceStatus](/docs/R5/ValueSets/InvoiceStatus.md)<br/> `http://hl7.org/fhir/ValueSet/invoice-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set InvoiceStatus from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | R4 InvoiceStatus| Relationship | [R4B InvoiceStatus](/docs/R4B/ValueSets/InvoiceStatus.md)| Relationship | [R5 InvoiceStatus](/docs/R5/ValueSets/InvoiceStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://hl7.org/fhir/invoice-status`
| | | | | **`draft`**| _Equivalent_ <br/>(16246/16247)| `draft`| _Equivalent_ <br/>(8721/11030)| `draft`
| | | | | **`issued`**| _Equivalent_ <br/>(16248/16249)| `issued`| _Equivalent_ <br/>(8723/11032)| `issued`
| | | | | **`balanced`**| _Equivalent_ <br/>(16250/16251)| `balanced`| _Equivalent_ <br/>(8725/11034)| `balanced`
| | | | | **`cancelled`**| _Equivalent_ <br/>(16252/16253)| `cancelled`| _Equivalent_ <br/>(8722/11031)| `cancelled`
| | | | | **`entered-in-error`**| _Equivalent_ <br/>(16254/16255)| `entered-in-error`| _Equivalent_ <br/>(8724/11033)| `entered-in-error`
| | | | | *5 of 5 codes used* | | *5 of 5 codes used* | | *5 of 5 codes used* 

