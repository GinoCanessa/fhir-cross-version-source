Comparison of 
Generated at Monday, April 14, 2025 6:17:43 PM

### TestScriptOperationCode

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | TestScriptOperationCode |
| Canonical URL | `http://hl7.org/fhir/ValueSet/testscript-operation-codes` |
| Version | 5.0.0 |
| Description | This value set defines a set of codes that are used to indicate the supported operations of a testing engine or tool. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4965` |
| Database Concept Count | `18` |
| Database Active Concept Count | `18` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ExampleScenario` | `ExampleScenario.process.step.operation.type` | `http://hl7.org/fhir/ValueSet/testscript-operation-codes` | `Extensible` | Kind of action |
| `http://hl7.org/fhir/StructureDefinition/TestScript` | `TestScript.setup.action.operation.type` | `http://hl7.org/fhir/ValueSet/testscript-operation-codes` | `Extensible` | The operation code type that will be executed |

### Referenced Systems

* `http://hl7.org/fhir/restful-interaction`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [TestScriptOperationCode](/docs/R4B/ValueSets/TestScriptOperationCode.md)<br/> `http://hl7.org/fhir/ValueSet/testscript-operation-codes\|4.3.0` | →→→→→→→<br/>``<br/>- DBKey: `1020`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `1281`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [TestScriptOperationCode](/docs/R5/ValueSets/TestScriptOperationCode.md)<br/> `http://hl7.org/fhir/ValueSet/testscript-operation-codes\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set TestScriptOperationCode from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | [R4B TestScriptOperationCode](/docs/R4B/ValueSets/TestScriptOperationCode.md)| Relationship | R5 TestScriptOperationCode
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/restful-interaction`
| | | | | | | `read`| _Equivalent_ <br/>(9629/11958)| **`read`**
| | | | | | | `vread`| _Equivalent_ <br/>(9641/11965)| **`vread`**
| | | | | | | `update`| _Equivalent_ <br/>(9637/11964)| **`update`**
| | | | | | | `patch`| _Equivalent_ <br/>(9623/11957)| **`patch`**
| | | | | | | `delete`| _Equivalent_ <br/>(9604/11951)| **`delete`**
| | | | | | | `history`| _Equivalent_ <br/>(9615/11952)| **`history`**
| | | | | | | | | **`history-instance`**
| | | | | | | | | **`history-type`**
| | | | | | | | | **`history-system`**
| | | | | | | `create`| _Equivalent_ <br/>(9602/11950)| **`create`**
| | | | | | | `search`| _Equivalent_ <br/>(9630/11959)| **`search`**
| | | | | | | | | **`search-type`**
| | | | | | | | | **`search-system`**
| | | | | | | | | **`search-compartment`**
| | | | | | | `capabilities`| _Equivalent_ <br/>(9599/11949)| **`capabilities`**
| | | | | | | `transaction`| _Equivalent_ <br/>(9634/11963)| **`transaction`**
| | | | | | | `batch`| _Equivalent_ <br/>(9598/11948)| **`batch`**
| | | | | | | | | **`operation`**
| | | | | | | *11 of 45 codes used* <br/>remaining codes:<br/>`apply`, `closure`, `conforms`, `data-requirements`, `deleteCondMultiple`, `deleteCondSingle`, `document`, `evaluate`, `evaluate-measure`, `everything`, `expand`, `find`, `find-matches`, `graphql`, `implements`, `lastn`, `lookup`, `match`, `meta`, `meta-add`, `meta-delete`, `populate`, `populatehtml`, `populatelink`, `process-message`, `questionnaire`, `stats`, `subset`, `subsumes`, `transform`, `translate`, `updateCreate`, `validate`, `validate-code`| | *18 of 18 codes used* 

