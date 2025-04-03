Comparison of 
Generated at Thursday, April 3, 2025 8:18:32 AM

### AssertionOperatorType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | AssertionOperatorType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/assert-operator-codes` |
| Version | 5.0.0 |
| Description | The type of operator to use for assertion. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4304` |
| Database Concept Count | `12` |
| Database Active Concept Count | `12` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/TestScript` | `TestScript.setup.action.assert.operator` | `http://hl7.org/fhir/ValueSet/assert-operator-codes\|5.0.0` | `Required` | equals \| notEquals \| in \| notIn \| greaterThan \| lessThan \| empty \| notEmpty \| contains \| notContains \| eval \| manualEval |

### Referenced Systems

* `http://hl7.org/fhir/assert-operator-codes`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [AssertionOperatorType](/docs/R2/ValueSets/AssertionOperatorType.md)<br/> `http://hl7.org/fhir/ValueSet/assert-operator-codes\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `155`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `313`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AssertionOperatorType](/docs/R3/ValueSets/AssertionOperatorType.md)<br/> `http://hl7.org/fhir/ValueSet/assert-operator-codes\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `534`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `756`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AssertionOperatorType](/docs/R4/ValueSets/AssertionOperatorType.md)<br/> `http://hl7.org/fhir/ValueSet/assert-operator-codes\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1389`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1390`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AssertionOperatorType](/docs/R4B/ValueSets/AssertionOperatorType.md)<br/> `http://hl7.org/fhir/ValueSet/assert-operator-codes\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1017`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1278`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AssertionOperatorType](/docs/R5/ValueSets/AssertionOperatorType.md)<br/> `http://hl7.org/fhir/ValueSet/assert-operator-codes\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set AssertionOperatorType from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 AssertionOperatorType](/docs/R2/ValueSets/AssertionOperatorType.md)| Relationship | [R3 AssertionOperatorType](/docs/R3/ValueSets/AssertionOperatorType.md)| Relationship | [R4 AssertionOperatorType](/docs/R4/ValueSets/AssertionOperatorType.md)| Relationship | [R4B AssertionOperatorType](/docs/R4B/ValueSets/AssertionOperatorType.md)| Relationship | R5 AssertionOperatorType
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/assert-operator-codes`
| `equals`| _Equivalent_ <br/>(1326/2783)| `equals`| _Equivalent_ <br/>(4965/7309)| `equals`| _Equivalent_ <br/>(14490/14491)| `equals`| _Equivalent_ <br/>(9549/11886)| **`equals`**
| `notEquals`| _Equivalent_ <br/>(1328/2790)| `notEquals`| _Equivalent_ <br/>(4967/7311)| `notEquals`| _Equivalent_ <br/>(14492/14493)| `notEquals`| _Equivalent_ <br/>(9551/11894)| **`notEquals`**
| `in`| _Equivalent_ <br/>(1324/2786)| `in`| _Equivalent_ <br/>(4963/7307)| `in`| _Equivalent_ <br/>(14494/14495)| `in`| _Equivalent_ <br/>(9547/11889)| **`in`**
| `notIn`| _Equivalent_ <br/>(1329/2791)| `notIn`| _Equivalent_ <br/>(4968/7312)| `notIn`| _Equivalent_ <br/>(14496/14497)| `notIn`| _Equivalent_ <br/>(9552/11895)| **`notIn`**
| `greaterThan`| _Equivalent_ <br/>(1331/2785)| `greaterThan`| _Equivalent_ <br/>(4970/7314)| `greaterThan`| _Equivalent_ <br/>(14498/14499)| `greaterThan`| _Equivalent_ <br/>(9554/11888)| **`greaterThan`**
| `lessThan`| _Equivalent_ <br/>(1327/2787)| `lessThan`| _Equivalent_ <br/>(4966/7310)| `lessThan`| _Equivalent_ <br/>(14500/14501)| `lessThan`| _Equivalent_ <br/>(9550/11890)| **`lessThan`**
| `empty`| _Equivalent_ <br/>(1332/2782)| `empty`| _Equivalent_ <br/>(4971/7315)| `empty`| _Equivalent_ <br/>(14502/14503)| `empty`| _Equivalent_ <br/>(9555/11885)| **`empty`**
| `notEmpty`| _Equivalent_ <br/>(1330/2789)| `notEmpty`| _Equivalent_ <br/>(4969/7313)| `notEmpty`| _Equivalent_ <br/>(14504/14505)| `notEmpty`| _Equivalent_ <br/>(9553/11893)| **`notEmpty`**
| `contains`| _Equivalent_ <br/>(1323/2781)| `contains`| _Equivalent_ <br/>(4961/7305)| `contains`| _Equivalent_ <br/>(14506/14507)| `contains`| _Equivalent_ <br/>(9545/11884)| **`contains`**
| `notContains`| _Equivalent_ <br/>(1325/2788)| `notContains`| _Equivalent_ <br/>(4964/7308)| `notContains`| _Equivalent_ <br/>(14508/14509)| `notContains`| _Equivalent_ <br/>(9548/11892)| **`notContains`**
| | | `eval`| _Equivalent_ <br/>(4962/7306)| `eval`| _Equivalent_ <br/>(14510/14511)| `eval`| _Equivalent_ <br/>(9546/11887)| **`eval`**
| | | | | | | | | **`manualEval`**
| *10 of 10 codes used* | | *11 of 11 codes used* | | *11 of 11 codes used* | | *11 of 11 codes used* | | *12 of 12 codes used* 

