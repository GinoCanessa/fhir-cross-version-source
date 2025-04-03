Comparison of 
Generated at Thursday, April 3, 2025 8:18:31 AM

### TestScriptRequestMethodCode

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | TestScriptRequestMethodCode |
| Canonical URL | `http://hl7.org/fhir/ValueSet/http-operations` |
| Version | 5.0.0 |
| Description | The allowable request method or HTTP operation codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4603` |
| Database Concept Count | `7` |
| Database Active Concept Count | `7` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/TestScript` | `TestScript.setup.action.operation.method` | `http://hl7.org/fhir/ValueSet/http-operations\|5.0.0` | `Required` | delete \| get \| options \| patch \| post \| put \| head |
| `http://hl7.org/fhir/StructureDefinition/TestScript` | `TestScript.setup.action.assert.requestMethod` | `http://hl7.org/fhir/ValueSet/http-operations\|5.0.0` | `Required` | delete \| get \| options \| patch \| post \| put \| head |

### Referenced Systems

* `http://hl7.org/fhir/http-operations`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [TestScriptRequestMethodCode](/docs/R3/ValueSets/TestScriptRequestMethodCode.md)<br/> `http://hl7.org/fhir/ValueSet/http-operations\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `535`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `757`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TestScriptRequestMethodCode](/docs/R4/ValueSets/TestScriptRequestMethodCode.md)<br/> `http://hl7.org/fhir/ValueSet/http-operations\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1535`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1536`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TestScriptRequestMethodCode](/docs/R4B/ValueSets/TestScriptRequestMethodCode.md)<br/> `http://hl7.org/fhir/ValueSet/http-operations\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1018`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1279`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TestScriptRequestMethodCode](/docs/R5/ValueSets/TestScriptRequestMethodCode.md)<br/> `http://hl7.org/fhir/ValueSet/http-operations\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set TestScriptRequestMethodCode from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | [R3 TestScriptRequestMethodCode](/docs/R3/ValueSets/TestScriptRequestMethodCode.md)| Relationship | [R4 TestScriptRequestMethodCode](/docs/R4/ValueSets/TestScriptRequestMethodCode.md)| Relationship | [R4B TestScriptRequestMethodCode](/docs/R4B/ValueSets/TestScriptRequestMethodCode.md)| Relationship | R5 TestScriptRequestMethodCode
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/http-operations`
| | | `delete`| _Equivalent_ <br/>(4976/7316)| `delete`| _Equivalent_ <br/>(16164/16165)| `delete`| _Equivalent_ <br/>(9561/11901)| **`delete`**
| | | `get`| _Equivalent_ <br/>(4974/7317)| `get`| _Equivalent_ <br/>(16166/16167)| `get`| _Equivalent_ <br/>(9559/11899)| **`get`**
| | | `options`| _Equivalent_ <br/>(4975/7319)| `options`| _Equivalent_ <br/>(16168/16169)| `options`| _Equivalent_ <br/>(9560/11900)| **`options`**
| | | `patch`| _Equivalent_ <br/>(4972/7320)| `patch`| _Equivalent_ <br/>(16170/16171)| `patch`| _Equivalent_ <br/>(9556/11896)| **`patch`**
| | | `post`| _Equivalent_ <br/>(4973/7321)| `post`| _Equivalent_ <br/>(16172/16173)| `post`| _Equivalent_ <br/>(9558/11898)| **`post`**
| | | `put`| _Equivalent_ <br/>(4977/7322)| `put`| _Equivalent_ <br/>(16174/16175)| `put`| _Equivalent_ <br/>(9562/11902)| **`put`**
| | | | | `head`| _Equivalent_ <br/>(16176/16177)| `head`| _Equivalent_ <br/>(9557/11897)| **`head`**
| | | *6 of 6 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* | | *7 of 7 codes used* 

