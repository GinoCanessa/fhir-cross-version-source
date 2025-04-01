Comparison of 
Generated at Tuesday, April 1, 2025 1:39:07 PM

### ActInvoiceGroupCode

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | ActInvoiceGroupCode |
| Canonical URL | `http://hl7.org/fhir/ValueSet/v3-ActInvoiceGroupCode` |
| Version | 2014-03-26 |
| Description | Type of invoice element that is used to assist in describing an Invoice that is either submitted for adjudication or for which is returned on adjudication results. Invoice elements of this type signify a grouping of one or more children (detail) invoice elements.  They do not have intrinsic costing associated with them, but merely reflect the sum of all costing for it's immediate children invoice elements. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `863` |
| Database Concept Count | `19` |
| Database Active Concept Count | `17` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.item.type` | `http://hl7.org/fhir/ValueSet/v3-ActInvoiceGroupCode` | `Required` | Group or type of product or service |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.item.detail.type` | `http://hl7.org/fhir/ValueSet/v3-ActInvoiceGroupCode` | `Required` | Group or type of product or service |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.item.detail.subDetail.type` | `http://hl7.org/fhir/ValueSet/v3-ActInvoiceGroupCode` | `Required` | Type of product or service |

### Referenced Systems

* `http://hl7.org/fhir/v3/ActCode`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ActInvoiceGroupCode](/docs/R2/ValueSets/ActInvoiceGroupCode.md)<br/> `http://hl7.org/fhir/ValueSet/v3-ActInvoiceGroupCode\|2014-03-26` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1313`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1314`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ActInvoiceGroupCode](/docs/R3/ValueSets/ActInvoiceGroupCode.md)<br/> `http://hl7.org/fhir/ValueSet/v3-ActInvoiceGroupCode\|2014-03-26` | →→→→→→→<br/>``<br/>- DBKey: `1333`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `1334`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [v3.ActInvoiceGroupCode](/docs/R4/ValueSets/V3ActInvoiceGroupCode.md)<br/> `http://terminology.hl7.org/ValueSet/v3-ActInvoiceGroupCode\|2014-03-26` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set ActInvoiceGroupCode from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 ActInvoiceGroupCode| Relationship | [R3 ActInvoiceGroupCode](/docs/R3/ValueSets/ActInvoiceGroupCode.md)| Relationship | [R4 v3.ActInvoiceGroupCode](/docs/R4/ValueSets/V3ActInvoiceGroupCode.md)| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/v3/ActCode`
| **`CPNDDRGING`**| _Equivalent_ <br/>(12781/12782)| `CPNDDRGING`| _Equivalent_ <br/>(13822/13823)| `CPNDDRGING`| | | | | 
| **`CPNDINDING`**| _Equivalent_ <br/>(12783/12784)| `CPNDINDING`| _Equivalent_ <br/>(13824/13825)| `CPNDINDING`| | | | | 
| **`CPNDSUPING`**| _Equivalent_ <br/>(12785/12786)| `CPNDSUPING`| _Equivalent_ <br/>(13826/13827)| `CPNDSUPING`| | | | | 
| **`DRUGING`**| _Equivalent_ <br/>(12787/12788)| `DRUGING`| _Equivalent_ <br/>(13828/13829)| `DRUGING`| | | | | 
| **`FRAMEING`**| _Equivalent_ <br/>(12789/12790)| `FRAMEING`| _Equivalent_ <br/>(13830/13831)| `FRAMEING`| | | | | 
| **`LENSING`**| _Equivalent_ <br/>(12791/12792)| `LENSING`| _Equivalent_ <br/>(13832/13833)| `LENSING`| | | | | 
| **`PRDING`**| _Equivalent_ <br/>(12793/12794)| `PRDING`| _Equivalent_ <br/>(13834/13835)| `PRDING`| | | | | 
| **`CPINV`**| _Equivalent_ <br/>(12795/12796)| `CPINV`| _Equivalent_ <br/>(13836/13837)| `CPINV`| | | | | 
| **`CSINV`**| _Equivalent_ <br/>(12797/12798)| `CSINV`| _Equivalent_ <br/>(13838/13839)| `CSINV`| | | | | 
| **`CSPINV`**| _Equivalent_ <br/>(12799/12800)| `CSPINV`| _Equivalent_ <br/>(13840/13841)| `CSPINV`| | | | | 
| **`FININV`**| _Equivalent_ <br/>(12801/12802)| `FININV`| _Equivalent_ <br/>(13842/13843)| `FININV`| | | | | 
| **`OHSINV`**| _Equivalent_ <br/>(12803/12804)| `OHSINV`| _Equivalent_ <br/>(13844/13845)| `OHSINV`| | | | | 
| **`PAINV`**| _Equivalent_ <br/>(12805/12806)| `PAINV`| _Equivalent_ <br/>(13846/13847)| `PAINV`| | | | | 
| **`RXCINV`**| _Equivalent_ <br/>(12807/12808)| `RXCINV`| _Equivalent_ <br/>(13848/13849)| `RXCINV`| | | | | 
| **`RXDINV`**| _Equivalent_ <br/>(12809/12810)| `RXDINV`| _Equivalent_ <br/>(13850/13851)| `RXDINV`| | | | | 
| **`SBFINV`**| _Equivalent_ <br/>(12811/12812)| `SBFINV`| _Equivalent_ <br/>(13852/13853)| `SBFINV`| | | | | 
| **`VRXINV`**| _Equivalent_ <br/>(12813/12814)| `VRXINV`| _Equivalent_ <br/>(13854/13855)| `VRXINV`| | | | | 
| **`_ActInvoiceInterGroupCode`**| | | | | | | | | 
| **`_ActInvoiceRootGroupCode`**| | | | | | | | | 
| *19 of 19 codes used* | | *17 of 17 codes used* | | *17 of 19 codes used* | | | | 

