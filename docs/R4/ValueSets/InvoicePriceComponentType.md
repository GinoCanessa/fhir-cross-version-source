Comparison of 
Generated at Friday, April 4, 2025 2:58:43 PM

### InvoicePriceComponentType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | InvoicePriceComponentType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/invoice-priceComponentType` |
| Version | 4.0.1 |
| Description | Codes indicating the kind of the price component. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2523` |
| Database Concept Count | `6` |
| Database Active Concept Count | `6` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ChargeItemDefinition` | `ChargeItemDefinition.propertyGroup.priceComponent.type` | `http://hl7.org/fhir/ValueSet/invoice-priceComponentType\|4.0.1` | `Required` | base \| surcharge \| deduction \| discount \| tax \| informational |
| `http://hl7.org/fhir/StructureDefinition/Invoice` | `Invoice.lineItem.priceComponent.type` | `http://hl7.org/fhir/ValueSet/invoice-priceComponentType\|4.0.1` | `Required` | base \| surcharge \| deduction \| discount \| tax \| informational |

### Referenced Systems

* `http://hl7.org/fhir/invoice-priceComponentType`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [InvoicePriceComponentType](/docs/R4/ValueSets/InvoicePriceComponentType.md)<br/> `http://hl7.org/fhir/ValueSet/invoice-priceComponentType\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1551`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1552`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [InvoicePriceComponentType](/docs/R4B/ValueSets/InvoicePriceComponentType.md)<br/> `http://hl7.org/fhir/ValueSet/invoice-priceComponentType\|4.3.0` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set InvoicePriceComponentType from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | R4 InvoicePriceComponentType| Relationship | [R4B InvoicePriceComponentType](/docs/R4B/ValueSets/InvoicePriceComponentType.md)| Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://hl7.org/fhir/invoice-priceComponentType`
| | | | | **`base`**| _Equivalent_ <br/>(16234/16235)| `base`| | | 
| | | | | **`surcharge`**| _Equivalent_ <br/>(16236/16237)| `surcharge`| | | 
| | | | | **`deduction`**| _Equivalent_ <br/>(16238/16239)| `deduction`| | | 
| | | | | **`discount`**| _Equivalent_ <br/>(16240/16241)| `discount`| | | 
| | | | | **`tax`**| _Equivalent_ <br/>(16242/16243)| `tax`| | | 
| | | | | **`informational`**| _Equivalent_ <br/>(16244/16245)| `informational`| | | 
| | | | | *6 of 6 codes used* | | *6 of 6 codes used* | | 

