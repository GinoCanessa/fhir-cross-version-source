Comparison of 
Generated at Tuesday, April 1, 2025 1:39:06 PM

### TestScriptOperationCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | TestScriptOperationCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/testscript-operation-codes` |
| Version | 1.0.2 |
| Description | This value set defines a set of codes that are used to indicate the supported operations of a testing engine or tool. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `394` |
| Database Concept Count | `24` |
| Database Active Concept Count | `24` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/TestScript` | `TestScript.setup.action.operation.type` | `http://hl7.org/fhir/ValueSet/testscript-operation-codes` | `Extensible` | The setup operation type that will be executed |

### Referenced Systems

* `http://hl7.org/fhir/testscript-operation-codes`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [TestScriptOperationCodes](/docs/R2/ValueSets/TestScriptOperationCodes.md)<br/> `http://hl7.org/fhir/ValueSet/testscript-operation-codes\|1.0.2` | →→→→→→→<br/>``<br/>- DBKey: `157`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `315`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TestScriptOperationCode](/docs/R3/ValueSets/TestScriptOperationCode.md)<br/> `http://hl7.org/fhir/ValueSet/testscript-operation-codes\|3.0.2` | →→→→→→→<br/>``<br/>- DBKey: `537`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `759`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TestScriptOperationCode](/docs/R4/ValueSets/TestScriptOperationCode.md)<br/> `http://hl7.org/fhir/ValueSet/testscript-operation-codes\|4.0.1` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set TestScriptOperationCodes from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 TestScriptOperationCodes| Relationship | [R3 TestScriptOperationCode](/docs/R3/ValueSets/TestScriptOperationCode.md)| Relationship | [R4 TestScriptOperationCode](/docs/R4/ValueSets/TestScriptOperationCode.md)| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/testscript-operation-codes`
| **`read`**| _Equivalent_ <br/>(1361/2836)| `read`| _Equivalent_ <br/>(5022/7367)| `read`| | | | | 
| **`vread`**| _Equivalent_ <br/>(1368/2856)| `vread`| _Equivalent_ <br/>(5042/7379)| `vread`| | | | | 
| **`update`**| _Equivalent_ <br/>(1365/2852)| `update`| _Equivalent_ <br/>(5038/7375)| `update`| | | | | 
| **`delete`**| _Equivalent_ <br/>(1348/2813)| `delete`| _Equivalent_ <br/>(4999/7342)| `delete`| | | | | 
| **`history`**| _Equivalent_ <br/>(1353/2824)| `history`| _Equivalent_ <br/>(5010/7353)| `history`| | | | | 
| **`create`**| _Equivalent_ <br/>(1347/2811)| `create`| _Equivalent_ <br/>(4997/7340)| `create`| | | | | 
| **`search`**| _Equivalent_ <br/>(1362/2840)| `search`| _Equivalent_ <br/>(5026/7368)| `search`| | | | | 
| **`transaction`**| _Equivalent_ <br/>(1363/2849)| `transaction`| _Equivalent_ <br/>(5035/7372)| `transaction`| | | | | 
| **`conformance`**| _Equivalent_ <br/>(1346/2807)| `capabilities`| _Equivalent_ <br/>(4993/7337)| `capabilities`| | | | | 
| **`closure`**| _Equivalent_ <br/>(1345/2808)| `closure`| _Equivalent_ <br/>(4994/7338)| `closure`| | | | | 
| **`document`**| _Equivalent_ <br/>(1349/2816)| `document`| _Equivalent_ <br/>(5002/7345)| `document`| | | | | 
| **`everything`**| _Equivalent_ <br/>(1350/2819)| `everything`| _Equivalent_ <br/>(5005/7348)| `everything`| | | | | 
| **`expand`**| _Equivalent_ <br/>(1351/2820)| `expand`| _Equivalent_ <br/>(5006/7349)| `expand`| | | | | 
| **`find`**| _Equivalent_ <br/>(1352/2822)| `find`| _Equivalent_ <br/>(5008/7350)| `find`| | | | | 
| **`lookup`**| _Equivalent_ <br/>(1354/2826)| `lookup`| _Equivalent_ <br/>(5012/7356)| `lookup`| | | | | 
| **`meta`**| _Equivalent_ <br/>(1355/2828)| `meta`| _Equivalent_ <br/>(5014/7358)| `meta`| | | | | 
| **`meta-add`**| _Equivalent_ <br/>(1356/2829)| `meta-add`| _Equivalent_ <br/>(5015/7359)| `meta-add`| | | | | 
| **`meta-delete`**| _Equivalent_ <br/>(1357/2830)| `meta-delete`| _Equivalent_ <br/>(5016/7360)| `meta-delete`| | | | | 
| **`populate`**| _Equivalent_ <br/>(1358/2831)| `populate`| _Equivalent_ <br/>(5017/7362)| `populate`| | | | | 
| **`process-message`**| _Equivalent_ <br/>(1359/2834)| `process-message`| _Equivalent_ <br/>(5020/7365)| `process-message`| | | | | 
| **`questionnaire`**| _Equivalent_ <br/>(1360/2835)| `questionnaire`| _Equivalent_ <br/>(5021/7366)| `questionnaire`| | | | | 
| **`translate`**| _Equivalent_ <br/>(1364/2851)| `translate`| _Equivalent_ <br/>(5037/7374)| `translate`| | | | | 
| **`validate`**| _Equivalent_ <br/>(1366/2854)| `validate`| _Equivalent_ <br/>(5040/7377)| `validate`| | | | | 
| **`validate-code`**| _Equivalent_ <br/>(1367/2855)| `validate-code`| _Equivalent_ <br/>(5041/7378)| `validate-code`| | | | | 
| *24 of 24 codes used* | | *24 of 53 codes used* | | *24 of 45 codes used* | | | | 

