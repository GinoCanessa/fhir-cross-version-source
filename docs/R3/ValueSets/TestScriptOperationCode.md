Comparison of 
Generated at Thursday, April 3, 2025 8:18:10 AM

### TestScriptOperationCode

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | TestScriptOperationCode |
| Canonical URL | `http://hl7.org/fhir/ValueSet/testscript-operation-codes` |
| Version | 3.0.2 |
| Description | This value set defines a set of codes that are used to indicate the supported operations of a testing engine or tool. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1512` |
| Database Concept Count | `53` |
| Database Active Concept Count | `53` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/TestScript` | `TestScript.setup.action.operation.type` | `http://hl7.org/fhir/ValueSet/testscript-operation-codes` | `Extensible` | The operation code type that will be executed |

### Referenced Systems

* `http://hl7.org/fhir/testscript-operation-codes`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [TestScriptOperationCodes](/docs/R2/ValueSets/TestScriptOperationCodes.md)<br/> `http://hl7.org/fhir/ValueSet/testscript-operation-codes\|1.0.2` | →→→→→→→<br/>``<br/>- DBKey: `157`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `315`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TestScriptOperationCode](/docs/R3/ValueSets/TestScriptOperationCode.md)<br/> `http://hl7.org/fhir/ValueSet/testscript-operation-codes\|3.0.2` | →→→→→→→<br/>``<br/>- DBKey: `537`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `759`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TestScriptOperationCode](/docs/R4/ValueSets/TestScriptOperationCode.md)<br/> `http://hl7.org/fhir/ValueSet/testscript-operation-codes\|4.0.1` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set TestScriptOperationCode from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 TestScriptOperationCodes](/docs/R2/ValueSets/TestScriptOperationCodes.md)| Relationship | R3 TestScriptOperationCode| Relationship | [R4 TestScriptOperationCode](/docs/R4/ValueSets/TestScriptOperationCode.md)| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/testscript-operation-codes`
| `read`| _Equivalent_ <br/>(1361/2836)| **`read`**| _Equivalent_ <br/>(5022/7367)| `read`| | | | | 
| `vread`| _Equivalent_ <br/>(1368/2856)| **`vread`**| _Equivalent_ <br/>(5042/7379)| `vread`| | | | | 
| `update`| _Equivalent_ <br/>(1365/2852)| **`update`**| _Equivalent_ <br/>(5038/7375)| `update`| | | | | 
| | | **`updateCreate`**| _Equivalent_ <br/>(5039/7376)| `updateCreate`| | | | | 
| `delete`| _Equivalent_ <br/>(1348/2813)| **`delete`**| _Equivalent_ <br/>(4999/7342)| `delete`| | | | | 
| | | **`deleteCondSingle`**| _Equivalent_ <br/>(5001/7344)| `deleteCondSingle`| | | | | 
| | | **`deleteCondMultiple`**| _Equivalent_ <br/>(5000/7343)| `deleteCondMultiple`| | | | | 
| `history`| _Equivalent_ <br/>(1353/2824)| **`history`**| _Equivalent_ <br/>(5010/7353)| `history`| | | | | 
| `create`| _Equivalent_ <br/>(1347/2811)| **`create`**| _Equivalent_ <br/>(4997/7340)| `create`| | | | | 
| `search`| _Equivalent_ <br/>(1362/2840)| **`search`**| _Equivalent_ <br/>(5026/7368)| `search`| | | | | 
| | | **`batch`**| _Equivalent_ <br/>(4991/7336)| `batch`| | | | | 
| `transaction`| _Equivalent_ <br/>(1363/2849)| **`transaction`**| _Equivalent_ <br/>(5035/7372)| `transaction`| | | | | 
| `conformance`| _Equivalent_ <br/>(1346/2807)| **`capabilities`**| _Equivalent_ <br/>(4993/7337)| `capabilities`| | | | | 
| | | **`apply`**| _Equivalent_ <br/>(4990/7335)| `apply`| | | | | 
| | | **`cancel`**| | | | | | | 
| `closure`| _Equivalent_ <br/>(1345/2808)| **`closure`**| _Equivalent_ <br/>(4994/7338)| `closure`| | | | | 
| | | **`compose`**| | | | | | | 
| | | **`conforms`**| _Equivalent_ <br/>(4996/7339)| `conforms`| | | | | 
| | | **`data-requirements`**| _Equivalent_ <br/>(4998/7341)| `data-requirements`| | | | | 
| `document`| _Equivalent_ <br/>(1349/2816)| **`document`**| _Equivalent_ <br/>(5002/7345)| `document`| | | | | 
| | | **`evaluate`**| _Equivalent_ <br/>(5003/7346)| `evaluate`| | | | | 
| | | **`evaluate-measure`**| _Equivalent_ <br/>(5004/7347)| `evaluate-measure`| | | | | 
| `everything`| _Equivalent_ <br/>(1350/2819)| **`everything`**| _Equivalent_ <br/>(5005/7348)| `everything`| | | | | 
| `expand`| _Equivalent_ <br/>(1351/2820)| **`expand`**| _Equivalent_ <br/>(5006/7349)| `expand`| | | | | 
| | | **`fail`**| | | | | | | 
| `find`| _Equivalent_ <br/>(1352/2822)| **`find`**| _Equivalent_ <br/>(5008/7350)| `find`| | | | | 
| | | **`finish`**| | | | | | | 
| | | **`implements`**| _Equivalent_ <br/>(5011/7354)| `implements`| | | | | 
| `lookup`| _Equivalent_ <br/>(1354/2826)| **`lookup`**| _Equivalent_ <br/>(5012/7356)| `lookup`| | | | | 
| | | **`match`**| _Equivalent_ <br/>(5013/7357)| `match`| | | | | 
| `meta`| _Equivalent_ <br/>(1355/2828)| **`meta`**| _Equivalent_ <br/>(5014/7358)| `meta`| | | | | 
| `meta-add`| _Equivalent_ <br/>(1356/2829)| **`meta-add`**| _Equivalent_ <br/>(5015/7359)| `meta-add`| | | | | 
| `meta-delete`| _Equivalent_ <br/>(1357/2830)| **`meta-delete`**| _Equivalent_ <br/>(5016/7360)| `meta-delete`| | | | | 
| `populate`| _Equivalent_ <br/>(1358/2831)| **`populate`**| _Equivalent_ <br/>(5017/7362)| `populate`| | | | | 
| | | **`populatehtml`**| _Equivalent_ <br/>(5018/7363)| `populatehtml`| | | | | 
| | | **`populatelink`**| _Equivalent_ <br/>(5019/7364)| `populatelink`| | | | | 
| `process-message`| _Equivalent_ <br/>(1359/2834)| **`process-message`**| _Equivalent_ <br/>(5020/7365)| `process-message`| | | | | 
| `questionnaire`| _Equivalent_ <br/>(1360/2835)| **`questionnaire`**| _Equivalent_ <br/>(5021/7366)| `questionnaire`| | | | | 
| | | **`release`**| | | | | | | 
| | | **`reserve`**| | | | | | | 
| | | **`resume`**| | | | | | | 
| | | **`set-input`**| | | | | | | 
| | | **`set-output`**| | | | | | | 
| | | **`start`**| | | | | | | 
| | | **`stats`**| _Equivalent_ <br/>(5030/7369)| `stats`| | | | | 
| | | **`stop`**| | | | | | | 
| | | **`subset`**| _Equivalent_ <br/>(5032/7370)| `subset`| | | | | 
| | | **`subsumes`**| _Equivalent_ <br/>(5033/7371)| `subsumes`| | | | | 
| | | **`suspend`**| | | | | | | 
| | | **`transform`**| _Equivalent_ <br/>(5036/7373)| `transform`| | | | | 
| `translate`| _Equivalent_ <br/>(1364/2851)| **`translate`**| _Equivalent_ <br/>(5037/7374)| `translate`| | | | | 
| `validate`| _Equivalent_ <br/>(1366/2854)| **`validate`**| _Equivalent_ <br/>(5040/7377)| `validate`| | | | | 
| `validate-code`| _Equivalent_ <br/>(1367/2855)| **`validate-code`**| _Equivalent_ <br/>(5041/7378)| `validate-code`| | | | | 
| *24 of 24 codes used* | | *53 of 53 codes used* | | *41 of 45 codes used* <br/>remaining codes:<br/>`find-matches`, `graphql`, `lastn`, `patch`| | | | 

