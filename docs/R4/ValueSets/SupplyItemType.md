Comparison of 
Generated at Monday, April 14, 2025 6:17:26 PM

### SupplyItemType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | SupplyItemType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/supplydelivery-type` |
| Version | 4.0.1 |
| Description | This value sets refers to a specific supply item. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2789` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/SupplyDelivery` | `SupplyDelivery.type` | `http://hl7.org/fhir/ValueSet/supplydelivery-type\|4.0.1` | `Required` | Category of dispense event |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/supply-item-type`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Supply Item Type](/docs/R2/ValueSets/SupplyItemType.md)<br/> `http://hl7.org/fhir/ValueSet/supplydelivery-type\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `149`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `307`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [Supply Item Type](/docs/R3/ValueSets/SupplyItemType.md)<br/> `http://hl7.org/fhir/ValueSet/supplydelivery-type\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `520`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `741`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [SupplyItemType](/docs/R4/ValueSets/SupplyItemType.md)<br/> `http://hl7.org/fhir/ValueSet/supplydelivery-type\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1757`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1758`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [SupplyItemType](/docs/R4B/ValueSets/SupplyItemType.md)<br/> `http://hl7.org/fhir/ValueSet/supplydelivery-type\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1000`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1261`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [SupplyDeliverySupplyItemType](/docs/R5/ValueSets/SupplyDeliverySupplyItemType.md)<br/> `http://hl7.org/fhir/ValueSet/supplydelivery-supplyitemtype\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set SupplyItemType from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 Supply Item Type](/docs/R2/ValueSets/SupplyItemType.md)| Relationship | [R3 Supply Item Type](/docs/R3/ValueSets/SupplyItemType.md)| Relationship | R4 SupplyItemType| Relationship | [R4B SupplyItemType](/docs/R4B/ValueSets/SupplyItemType.md)| Relationship | [R5 SupplyDeliverySupplyItemType](/docs/R5/ValueSets/SupplyDeliverySupplyItemType.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://terminology.hl7.org/CodeSystem/supply-item-type`
| `medication`| _Equivalent_ <br/>(1292/2739)| `medication`| _Equivalent_ <br/>(4861/7184)| **`medication`**| _Equivalent_ <br/>(18268/18269)| `medication`| _Equivalent_ <br/>(9439/11777)| `medication`
| `device`| _Equivalent_ <br/>(1293/2740)| `device`| _Equivalent_ <br/>(4862/7185)| **`device`**| _Equivalent_ <br/>(18270/18271)| `device`| _Equivalent_ <br/>(9440/11776)| `device`
| *2 of 2 codes used* | | *2 of 2 codes used* | | *2 of 2 codes used* | | *2 of 2 codes used* | | *2 of 3 codes used* <br/>remaining codes:<br/>`biologicallyderivedproduct`

