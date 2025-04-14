Comparison of 
Generated at Monday, April 14, 2025 6:17:15 PM

### IssueType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | IssueType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/issue-type` |
| Version | 1.0.2 |
| Description | A code that describes the type of issue. |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `202` |
| Database Concept Count | `29` |
| Database Active Concept Count | `29` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/OperationOutcome` | `OperationOutcome.issue.code` | `http://hl7.org/fhir/ValueSet/issue-type` | `Required` | Error or warning code |

### Referenced Systems

* `http://hl7.org/fhir/issue-type`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [IssueType](/docs/R2/ValueSets/IssueType.md)<br/> `http://hl7.org/fhir/ValueSet/issue-type\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `111`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `267`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [IssueType](/docs/R3/ValueSets/IssueType.md)<br/> `http://hl7.org/fhir/ValueSet/issue-type\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `460`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `684`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [IssueType](/docs/R4/ValueSets/IssueType.md)<br/> `http://hl7.org/fhir/ValueSet/issue-type\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1557`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1558`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [IssueType](/docs/R4B/ValueSets/IssueType.md)<br/> `http://hl7.org/fhir/ValueSet/issue-type\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `946`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1207`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [IssueType](/docs/R5/ValueSets/IssueType.md)<br/> `http://hl7.org/fhir/ValueSet/issue-type\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set IssueType from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 IssueType| Relationship | [R3 IssueType](/docs/R3/ValueSets/IssueType.md)| Relationship | [R4 IssueType](/docs/R4/ValueSets/IssueType.md)| Relationship | [R4B IssueType](/docs/R4B/ValueSets/IssueType.md)| Relationship | [R5 IssueType](/docs/R5/ValueSets/IssueType.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/issue-type`
| **`structure`**| _Equivalent_ <br/>(932/2300)| `structure`| _Equivalent_ <br/>(4105/6451)| `structure`| _Equivalent_ <br/>(16266/16267)| `structure`| _Equivalent_ <br/>(9137/11450)| `structure`
| **`required`**| _Equivalent_ <br/>(915/2283)| `required`| _Equivalent_ <br/>(4088/6449)| `required`| _Equivalent_ <br/>(16268/16269)| `required`| _Equivalent_ <br/>(9119/11448)| `required`
| **`value`**| _Equivalent_ <br/>(924/2292)| `value`| _Equivalent_ <br/>(4097/6459)| `value`| _Equivalent_ <br/>(16270/16271)| `value`| _Equivalent_ <br/>(9129/11459)| `value`
| **`invariant`**| _Equivalent_ <br/>(933/2301)| `invariant`| _Equivalent_ <br/>(4106/6441)| `invariant`| _Equivalent_ <br/>(16272/16273)| `invariant`| _Equivalent_ <br/>(9138/11439)| `invariant`
| **`invalid`**| _Equivalent_ <br/>(936/2304)| `invalid`| _Equivalent_ <br/>(4109/6440)| `invalid`| _Equivalent_ <br/>(16264/16265)| `invalid`| _Equivalent_ <br/>(9142/11438)| `invalid`
| **`login`**| _Equivalent_ <br/>(914/2282)| `login`| _Equivalent_ <br/>(4087/6443)| `login`| _Equivalent_ <br/>(16276/16277)| `login`| _Equivalent_ <br/>(9118/11442)| `login`
| **`unknown`**| _Equivalent_ <br/>(917/2285)| `unknown`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4090)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6458) | `unknown`| _Equivalent_ <br/>(16278/16279)| `unknown`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9121)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11458) | `unknown`
| **`expired`**| _Equivalent_ <br/>(920/2288)| `expired`| _Equivalent_ <br/>(4093/6435)| `expired`| _Equivalent_ <br/>(16280/16281)| `expired`| _Equivalent_ <br/>(9124/11433)| `expired`
| **`forbidden`**| _Equivalent_ <br/>(929/2297)| `forbidden`| _Equivalent_ <br/>(4102/6437)| `forbidden`| _Equivalent_ <br/>(16282/16283)| `forbidden`| _Equivalent_ <br/>(9134/11435)| `forbidden`
| **`suppressed`**| _Equivalent_ <br/>(922/2290)| `suppressed`| _Equivalent_ <br/>(4095/6452)| `suppressed`| _Equivalent_ <br/>(16284/16285)| `suppressed`| _Equivalent_ <br/>(9126/11452)| `suppressed`
| **`security`**| _Equivalent_ <br/>(918/2286)| `security`| _Equivalent_ <br/>(4091/6450)| `security`| _Equivalent_ <br/>(16274/16275)| `security`| _Equivalent_ <br/>(9122/11449)| `security`
| **`not-supported`**| _Equivalent_ <br/>(923/2291)| `not-supported`| _Equivalent_ <br/>(4096/6447)| `not-supported`| _Equivalent_ <br/>(16288/16289)| `not-supported`| _Equivalent_ <br/>(9127/11446)| `not-supported`
| **`duplicate`**| _Equivalent_ <br/>(931/2299)| `duplicate`| _Equivalent_ <br/>(4104/6433)| `duplicate`| _Equivalent_ <br/>(16290/16291)| `duplicate`| _Equivalent_ <br/>(9136/11431)| `duplicate`
| **`not-found`**| _Equivalent_ <br/>(934/2302)| `not-found`| _Equivalent_ <br/>(4107/6446)| `not-found`| _Equivalent_ <br/>(16294/16295)| `not-found`| _Equivalent_ <br/>(9139/11445)| `not-found`
| **`too-long`**| _Equivalent_ <br/>(930/2298)| `too-long`| _Equivalent_ <br/>(4103/6456)| `too-long`| _Equivalent_ <br/>(16298/16299)| `too-long`| _Equivalent_ <br/>(9135/11456)| `too-long`
| **`code-invalid`**| _Equivalent_ <br/>(928/2296)| `code-invalid`| _Equivalent_ <br/>(4101/6430)| `code-invalid`| _Equivalent_ <br/>(16300/16301)| `code-invalid`| _Equivalent_ <br/>(9133/11428)| `code-invalid`
| **`extension`**| _Equivalent_ <br/>(913/2281)| `extension`| _Equivalent_ <br/>(4086/6436)| `extension`| _Equivalent_ <br/>(16302/16303)| `extension`| _Equivalent_ <br/>(9117/11434)| `extension`
| **`too-costly`**| _Equivalent_ <br/>(925/2293)| `too-costly`| _Equivalent_ <br/>(4098/6455)| `too-costly`| _Equivalent_ <br/>(16304/16305)| `too-costly`| _Equivalent_ <br/>(9130/11455)| `too-costly`
| **`business-rule`**| _Equivalent_ <br/>(927/2295)| `business-rule`| _Equivalent_ <br/>(4100/6429)| `business-rule`| _Equivalent_ <br/>(16306/16307)| `business-rule`| _Equivalent_ <br/>(9132/11427)| `business-rule`
| **`conflict`**| _Equivalent_ <br/>(938/2306)| `conflict`| _Equivalent_ <br/>(4111/6431)| `conflict`| _Equivalent_ <br/>(16308/16309)| `conflict`| _Equivalent_ <br/>(9144/11429)| `conflict`
| **`incomplete`**| _Equivalent_ <br/>(919/2287)| `incomplete`| _Equivalent_ <br/>(4092/6438)| `incomplete`| _Equivalent_ <br/>(16320/16321)| `incomplete`| _Equivalent_ <br/>(9123/11436)| `incomplete`
| **`processing`**| _Equivalent_ <br/>(937/2305)| `processing`| _Equivalent_ <br/>(4110/6448)| `processing`| _Equivalent_ <br/>(16286/16287)| `processing`| _Equivalent_ <br/>(9143/11447)| `processing`
| **`lock-error`**| _Equivalent_ <br/>(926/2294)| `lock-error`| _Equivalent_ <br/>(4099/6442)| `lock-error`| _Equivalent_ <br/>(16312/16313)| `lock-error`| _Equivalent_ <br/>(9131/11441)| `lock-error`
| **`no-store`**| _Equivalent_ <br/>(939/2307)| `no-store`| _Equivalent_ <br/>(4112/6445)| `no-store`| _Equivalent_ <br/>(16314/16315)| `no-store`| _Equivalent_ <br/>(9145/11444)| `no-store`
| **`exception`**| _Equivalent_ <br/>(912/2280)| `exception`| _Equivalent_ <br/>(4085/6434)| `exception`| _Equivalent_ <br/>(16316/16317)| `exception`| _Equivalent_ <br/>(9116/11432)| `exception`
| **`timeout`**| _Equivalent_ <br/>(916/2284)| `timeout`| _Equivalent_ <br/>(4089/6454)| `timeout`| _Equivalent_ <br/>(16318/16319)| `timeout`| _Equivalent_ <br/>(9120/11454)| `timeout`
| **`throttled`**| _Equivalent_ <br/>(940/2308)| `throttled`| _Equivalent_ <br/>(4113/6453)| `throttled`| _Equivalent_ <br/>(16322/16323)| `throttled`| _Equivalent_ <br/>(9146/11453)| `throttled`
| **`transient`**| _Equivalent_ <br/>(935/2303)| `transient`| _Equivalent_ <br/>(4108/6457)| `transient`| _Equivalent_ <br/>(16310/16311)| `transient`| _Equivalent_ <br/>(9141/11457)| `transient`
| **`informational`**| _Equivalent_ <br/>(921/2289)| `informational`| _Equivalent_ <br/>(4094/6439)| `informational`| _Equivalent_ <br/>(16324/16325)| `informational`| _Equivalent_ <br/>(9125/11437)| `informational`
| *29 of 29 codes used* | | *29 of 29 codes used* | | *29 of 31 codes used* <br/>remaining codes:<br/>`deleted`, `multiple-matches`| | *29 of 31 codes used* <br/>remaining codes:<br/>`deleted`, `multiple-matches`| | *29 of 33 codes used* <br/>remaining codes:<br/>`deleted`, `limited-filter`, `multiple-matches`, `success`

