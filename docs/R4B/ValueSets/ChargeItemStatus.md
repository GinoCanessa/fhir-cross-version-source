Comparison of 
Generated at Friday, April 4, 2025 2:58:51 PM

### ChargeItemStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | ChargeItemStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/chargeitem-status` |
| Version | 4.3.0 |
| Description | Codes identifying the lifecycle stage of a ChargeItem. |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `3583` |
| Database Concept Count | `7` |
| Database Active Concept Count | `7` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ChargeItem` | `ChargeItem.status` | `http://hl7.org/fhir/ValueSet/chargeitem-status\|4.3.0` | `Required` | planned \| billable \| not-billable \| aborted \| billed \| entered-in-error \| unknown |

### Referenced Systems

* `http://hl7.org/fhir/chargeitem-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [ChargeItemStatus](/docs/R3/ValueSets/ChargeItemStatus.md)<br/> `http://hl7.org/fhir/ValueSet/chargeitem-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `342`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `566`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ChargeItemStatus](/docs/R4/ValueSets/ChargeItemStatus.md)<br/> `http://hl7.org/fhir/ValueSet/chargeitem-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1411`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1412`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ChargeItemStatus](/docs/R4B/ValueSets/ChargeItemStatus.md)<br/> `http://hl7.org/fhir/ValueSet/chargeitem-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `791`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1052`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ChargeItemStatus](/docs/R5/ValueSets/ChargeItemStatus.md)<br/> `http://hl7.org/fhir/ValueSet/chargeitem-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set ChargeItemStatus from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | [R3 ChargeItemStatus](/docs/R3/ValueSets/ChargeItemStatus.md)| Relationship | [R4 ChargeItemStatus](/docs/R4/ValueSets/ChargeItemStatus.md)| Relationship | R4B ChargeItemStatus| Relationship | [R5 ChargeItemStatus](/docs/R5/ValueSets/ChargeItemStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://hl7.org/fhir/chargeitem-status`
| | | `planned`| _Equivalent_ <br/>(2981/5194)| `planned`| _Equivalent_ <br/>(14638/14639)| **`planned`**| _Equivalent_ <br/>(7522/9786)| `planned`
| | | `billable`| _Equivalent_ <br/>(2983/5196)| `billable`| _Equivalent_ <br/>(14640/14641)| **`billable`**| _Equivalent_ <br/>(7524/9788)| `billable`
| | | `not-billable`| _Equivalent_ <br/>(2978/5191)| `not-billable`| _Equivalent_ <br/>(14642/14643)| **`not-billable`**| _Equivalent_ <br/>(7519/9783)| `not-billable`
| | | `aborted`| _Equivalent_ <br/>(2980/5193)| `aborted`| _Equivalent_ <br/>(14644/14645)| **`aborted`**| _Equivalent_ <br/>(7521/9785)| `aborted`
| | | `billed`| _Equivalent_ <br/>(2979/5192)| `billed`| _Equivalent_ <br/>(14646/14647)| **`billed`**| _Equivalent_ <br/>(7520/9784)| `billed`
| | | `entered-in-error`| _Equivalent_ <br/>(2982/5195)| `entered-in-error`| _Equivalent_ <br/>(14648/14649)| **`entered-in-error`**| _Equivalent_ <br/>(7523/9787)| `entered-in-error`
| | | `unknown`| _Equivalent_ <br/>(2984/5197)| `unknown`| _Equivalent_ <br/>(14650/14651)| **`unknown`**| _Equivalent_ <br/>(7525/9789)| `unknown`
| | | *7 of 7 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* 

