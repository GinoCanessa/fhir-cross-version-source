Comparison of 
Generated at Friday, April 4, 2025 2:58:58 PM

### SupplyDeliverySupplyItemType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | SupplyDeliverySupplyItemType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/supplydelivery-supplyitemtype` |
| Version | 5.0.0 |
| Description | This value sets refers to a specific supply item. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4954` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/SupplyDelivery` | `SupplyDelivery.type` | `http://hl7.org/fhir/ValueSet/supplydelivery-supplyitemtype\|5.0.0` | `Required` | Category of supply event |
| `http://hl7.org/fhir/StructureDefinition/SupplyDelivery` | `SupplyDelivery.suppliedItem.item[x]` | `http://hl7.org/fhir/ValueSet/supplydelivery-supplyitemtype` | `Example` | Medication, Substance, Device or Biologically Derived Product supplied |

### Referenced Systems

* `http://hl7.org/fhir/supplydelivery-supplyitemtype`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Supply Item Type](/docs/R2/ValueSets/SupplyItemType.md)<br/> `http://hl7.org/fhir/ValueSet/supplydelivery-type\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `149`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `307`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Supply Item Type](/docs/R3/ValueSets/SupplyItemType.md)<br/> `http://hl7.org/fhir/ValueSet/supplydelivery-type\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `520`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `741`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SupplyItemType](/docs/R4/ValueSets/SupplyItemType.md)<br/> `http://hl7.org/fhir/ValueSet/supplydelivery-type\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1757`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1758`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SupplyItemType](/docs/R4B/ValueSets/SupplyItemType.md)<br/> `http://hl7.org/fhir/ValueSet/supplydelivery-type\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1000`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1261`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SupplyDeliverySupplyItemType](/docs/R5/ValueSets/SupplyDeliverySupplyItemType.md)<br/> `http://hl7.org/fhir/ValueSet/supplydelivery-supplyitemtype\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set SupplyDeliverySupplyItemType from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 Supply Item Type](/docs/R2/ValueSets/SupplyItemType.md)| Relationship | [R3 Supply Item Type](/docs/R3/ValueSets/SupplyItemType.md)| Relationship | [R4 SupplyItemType](/docs/R4/ValueSets/SupplyItemType.md)| Relationship | [R4B SupplyItemType](/docs/R4B/ValueSets/SupplyItemType.md)| Relationship | R5 SupplyDeliverySupplyItemType
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/supplydelivery-supplyitemtype`
| `medication`| _Equivalent_ <br/>(1292/2739)| `medication`| _Equivalent_ <br/>(4861/7184)| `medication`| _Equivalent_ <br/>(18268/18269)| `medication`| _Equivalent_ <br/>(9439/11777)| **`medication`**
| `device`| _Equivalent_ <br/>(1293/2740)| `device`| _Equivalent_ <br/>(4862/7185)| `device`| _Equivalent_ <br/>(18270/18271)| `device`| _Equivalent_ <br/>(9440/11776)| **`device`**
| | | | | | | | | **`biologicallyderivedproduct`**
| *2 of 2 codes used* | | *2 of 2 codes used* | | *2 of 2 codes used* | | *2 of 2 codes used* | | *3 of 3 codes used* 

