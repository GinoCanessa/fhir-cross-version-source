Comparison of 
Generated at Tuesday, April 1, 2025 1:39:26 PM

### TestScriptOperationCode

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | TestScriptOperationCode |
| Canonical URL | `http://hl7.org/fhir/ValueSet/testscript-operation-codes` |
| Version | 4.3.0 |
| Description | This value set defines a set of codes that are used to indicate the supported operations of a testing engine or tool. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4161` |
| Database Concept Count | `45` |
| Database Active Concept Count | `45` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/TestScript` | `TestScript.setup.action.operation.type` | `http://hl7.org/fhir/ValueSet/testscript-operation-codes` | `Extensible` | The operation code type that will be executed |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/testscript-operation-codes`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [TestScriptOperationCode](/docs/R4B/ValueSets/TestScriptOperationCode.md)<br/> `http://hl7.org/fhir/ValueSet/testscript-operation-codes\|4.3.0` | →→→→→→→<br/>``<br/>- DBKey: `1020`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `1281`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TestScriptOperationCode](/docs/R5/ValueSets/TestScriptOperationCode.md)<br/> `http://hl7.org/fhir/ValueSet/testscript-operation-codes\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set TestScriptOperationCode from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | R4B TestScriptOperationCode| Relationship | [R5 TestScriptOperationCode](/docs/R5/ValueSets/TestScriptOperationCode.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://terminology.hl7.org/CodeSystem/testscript-operation-codes`
| | | | | | | **`read`**| _Equivalent_ <br/>(9629/11958)| `read`
| | | | | | | **`vread`**| _Equivalent_ <br/>(9641/11965)| `vread`
| | | | | | | **`update`**| _Equivalent_ <br/>(9637/11964)| `update`
| | | | | | | **`updateCreate`**| | | 
| | | | | | | **`patch`**| _Equivalent_ <br/>(9623/11957)| `patch`
| | | | | | | **`delete`**| _Equivalent_ <br/>(9604/11951)| `delete`
| | | | | | | **`deleteCondSingle`**| | | 
| | | | | | | **`deleteCondMultiple`**| | | 
| | | | | | | **`history`**| _Equivalent_ <br/>(9615/11952)| `history`
| | | | | | | **`create`**| _Equivalent_ <br/>(9602/11950)| `create`
| | | | | | | **`search`**| _Equivalent_ <br/>(9630/11959)| `search`
| | | | | | | **`batch`**| _Equivalent_ <br/>(9598/11948)| `batch`
| | | | | | | **`transaction`**| _Equivalent_ <br/>(9634/11963)| `transaction`
| | | | | | | **`capabilities`**| _Equivalent_ <br/>(9599/11949)| `capabilities`
| | | | | | | **`apply`**| | | 
| | | | | | | **`closure`**| | | 
| | | | | | | **`find-matches`**| | | 
| | | | | | | **`conforms`**| | | 
| | | | | | | **`data-requirements`**| | | 
| | | | | | | **`document`**| | | 
| | | | | | | **`evaluate`**| | | 
| | | | | | | **`evaluate-measure`**| | | 
| | | | | | | **`everything`**| | | 
| | | | | | | **`expand`**| | | 
| | | | | | | **`find`**| | | 
| | | | | | | **`graphql`**| | | 
| | | | | | | **`implements`**| | | 
| | | | | | | **`lastn`**| | | 
| | | | | | | **`lookup`**| | | 
| | | | | | | **`match`**| | | 
| | | | | | | **`meta`**| | | 
| | | | | | | **`meta-add`**| | | 
| | | | | | | **`meta-delete`**| | | 
| | | | | | | **`populate`**| | | 
| | | | | | | **`populatehtml`**| | | 
| | | | | | | **`populatelink`**| | | 
| | | | | | | **`process-message`**| | | 
| | | | | | | **`questionnaire`**| | | 
| | | | | | | **`stats`**| | | 
| | | | | | | **`subset`**| | | 
| | | | | | | **`subsumes`**| | | 
| | | | | | | **`transform`**| | | 
| | | | | | | **`translate`**| | | 
| | | | | | | **`validate`**| | | 
| | | | | | | **`validate-code`**| | | 
| | | | | | | *45 of 45 codes used* | | *11 of 18 codes used* 

