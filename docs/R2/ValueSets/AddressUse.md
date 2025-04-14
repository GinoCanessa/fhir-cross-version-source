Comparison of 
Generated at Monday, April 14, 2025 6:17:14 PM

### AddressUse

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | AddressUse |
| Canonical URL | `http://hl7.org/fhir/ValueSet/address-use` |
| Version | 1.0.2 |
| Description | The use of an address  The use of an address (home / work / etc.). |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `6` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Address` | `Address.use` | `http://hl7.org/fhir/ValueSet/address-use` | `Required` | home \| work \| temp \| old - purpose of this address |

### Referenced Systems

* `http://hl7.org/fhir/address-use`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [AddressUse](/docs/R2/ValueSets/AddressUse.md)<br/> `http://hl7.org/fhir/ValueSet/address-use\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `2`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `163`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [AddressUse](/docs/R3/ValueSets/AddressUse.md)<br/> `http://hl7.org/fhir/ValueSet/address-use\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `322`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `544`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [AddressUse](/docs/R4/ValueSets/AddressUse.md)<br/> `http://hl7.org/fhir/ValueSet/address-use\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1355`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1356`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [AddressUse](/docs/R4B/ValueSets/AddressUse.md)<br/> `http://hl7.org/fhir/ValueSet/address-use\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `766`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1027`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [AddressUse](/docs/R5/ValueSets/AddressUse.md)<br/> `http://hl7.org/fhir/ValueSet/address-use\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set AddressUse from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 AddressUse| Relationship | [R3 AddressUse](/docs/R3/ValueSets/AddressUse.md)| Relationship | [R4 AddressUse](/docs/R4/ValueSets/AddressUse.md)| Relationship | [R4B AddressUse](/docs/R4B/ValueSets/AddressUse.md)| Relationship | [R5 AddressUse](/docs/R5/ValueSets/AddressUse.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/address-use`
| **`home`**| _Equivalent_ <br/>(7/1391)| `home`| _Equivalent_ <br/>(2885/5070)| `home`| _Equivalent_ <br/>(13936/13937)| `home`| _Equivalent_ <br/>(7410/9669)| `home`
| **`work`**| _Equivalent_ <br/>(5/1389)| `work`| _Equivalent_ <br/>(2883/5073)| `work`| _Equivalent_ <br/>(13938/13939)| `work`| _Equivalent_ <br/>(7408/9667)| `work`
| **`temp`**| _Equivalent_ <br/>(4/1388)| `temp`| _Equivalent_ <br/>(2882/5072)| `temp`| _Equivalent_ <br/>(13940/13941)| `temp`| _Equivalent_ <br/>(7407/9666)| `temp`
| **`old`**| _Equivalent_ <br/>(6/1390)| `old`| _Equivalent_ <br/>(2884/5071)| `old`| _Equivalent_ <br/>(13942/13943)| `old`| _Equivalent_ <br/>(7409/9668)| `old`
| *4 of 4 codes used* | | *4 of 4 codes used* | | *4 of 5 codes used* <br/>remaining codes:<br/>`billing`| | *4 of 5 codes used* <br/>remaining codes:<br/>`billing`| | *4 of 5 codes used* <br/>remaining codes:<br/>`billing`

