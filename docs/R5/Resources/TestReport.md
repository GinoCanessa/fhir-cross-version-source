Comparison of 
Generated at Thursday, April 3, 2025 8:18:36 AM

### TestReport

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | TestReport |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/TestReport` |
| Version | 5.0.0 |
| Description | A summary of information based on the results of executing a TestScript. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2402` |
| Database Snapshot Count | `72` |
| Database Differential Count | `34` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `TestReport` | `TestReport` | `TestReport` | TestReport | Describes the results of a TestScript execution | 0..* | TestReport |  |  |
| `TestReport.contained` | `TestReport.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `TestReport.extension` | `TestReport.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `TestReport.id` | `TestReport.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `TestReport.identifier` | `TestReport.identifier` | `identifier` | TestReport.identifier | External identifier | 0..1 | Identifier |  |  |
| `TestReport.implicitRules` | `TestReport.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `TestReport.issued` | `TestReport.issued` | `issued` | TestReport.issued | When the TestScript was executed and this TestReport was generated | 0..1 | dateTime |  |  |
| `TestReport.language` | `TestReport.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `TestReport.meta` | `TestReport.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `TestReport.modifierExtension` | `TestReport.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `TestReport.name` | `TestReport.name` | `name` | TestReport.name | Informal name of the executed TestReport | 0..1 | string |  |  |
| `TestReport.participant` | `TestReport.participant` | `participant` | TestReport.participant | A participant in the test execution, either the execution engine, a client, or a server | 0..* | BackboneElement |  |  |
| `TestReport.participant.display` | `TestReport.participant.display` | `display` | TestReport.participant.display | The display name of the participant | 0..1 | string |  |  |
| `TestReport.participant.extension` | `TestReport.participant.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `TestReport.participant.id` | `TestReport.participant.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `TestReport.participant.modifierExtension` | `TestReport.participant.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `TestReport.participant.type` | `TestReport.participant.type` | `type` | TestReport.participant.type | test-engine \| client \| server | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/report-participant-type|5.0.0` |
| `TestReport.participant.uri` | `TestReport.participant.uri` | `uri` | TestReport.participant.uri | The uri of the participant. An absolute URL is preferred | 1..1 | uri |  |  |
| `TestReport.result` | `TestReport.result` | `result` | TestReport.result | pass \| fail \| pending | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/report-result-codes|5.0.0` |
| `TestReport.score` | `TestReport.score` | `score` | TestReport.score | The final score (percentage of tests passed) resulting from the execution of the TestScript | 0..1 | decimal |  |  |
| `TestReport.setup` | `TestReport.setup` | `setup` | TestReport.setup | The results of the series of required setup operations before the tests were executed | 0..1 | BackboneElement |  |  |
| `TestReport.setup.action` | `TestReport.setup.action` | `action` | TestReport.setup.action | A setup operation or assert that was executed | 1..* | BackboneElement |  |  |
| `TestReport.setup.action.assert` | `TestReport.setup.action.assert` | `assert` | TestReport.setup.action.assert | The assertion to perform | 0..1 | BackboneElement |  |  |
| `TestReport.setup.action.assert.detail` | `TestReport.setup.action.assert.detail` | `detail` | TestReport.setup.action.assert.detail | A link to further details on the result | 0..1 | string |  |  |
| `TestReport.setup.action.assert.extension` | `TestReport.setup.action.assert.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `TestReport.setup.action.assert.id` | `TestReport.setup.action.assert.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `TestReport.setup.action.assert.message` | `TestReport.setup.action.assert.message` | `message` | TestReport.setup.action.assert.message | A message associated with the result | 0..1 | markdown |  |  |
| `TestReport.setup.action.assert.modifierExtension` | `TestReport.setup.action.assert.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `TestReport.setup.action.assert.requirement` | `TestReport.setup.action.assert.requirement` | `requirement` | TestReport.setup.action.assert.requirement | Links or references to the testing requirements | 0..* | BackboneElement |  |  |
| `TestReport.setup.action.assert.requirement.extension` | `TestReport.setup.action.assert.requirement.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `TestReport.setup.action.assert.requirement.id` | `TestReport.setup.action.assert.requirement.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `TestReport.setup.action.assert.requirement.link[x]` | `TestReport.setup.action.assert.requirement.link[x]` | `link[x]` | TestReport.setup.action.assert.requirement.link[x] | Link or reference to the testing requirement | 0..1 | canonical(http://hl7.org/fhir/StructureDefinition/Requirements), uri |  |  |
| `TestReport.setup.action.assert.requirement.modifierExtension` | `TestReport.setup.action.assert.requirement.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `TestReport.setup.action.assert.result` | `TestReport.setup.action.assert.result` | `result` | TestReport.setup.action.assert.result | pass \| skip \| fail \| warning \| error | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/report-action-result-codes|5.0.0` |
| `TestReport.setup.action.extension` | `TestReport.setup.action.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `TestReport.setup.action.id` | `TestReport.setup.action.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `TestReport.setup.action.modifierExtension` | `TestReport.setup.action.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `TestReport.setup.action.operation` | `TestReport.setup.action.operation` | `operation` | TestReport.setup.action.operation | The operation to perform | 0..1 | BackboneElement |  |  |
| `TestReport.setup.action.operation.detail` | `TestReport.setup.action.operation.detail` | `detail` | TestReport.setup.action.operation.detail | A link to further details on the result | 0..1 | uri |  |  |
| `TestReport.setup.action.operation.extension` | `TestReport.setup.action.operation.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `TestReport.setup.action.operation.id` | `TestReport.setup.action.operation.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `TestReport.setup.action.operation.message` | `TestReport.setup.action.operation.message` | `message` | TestReport.setup.action.operation.message | A message associated with the result | 0..1 | markdown |  |  |
| `TestReport.setup.action.operation.modifierExtension` | `TestReport.setup.action.operation.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `TestReport.setup.action.operation.result` | `TestReport.setup.action.operation.result` | `result` | TestReport.setup.action.operation.result | pass \| skip \| fail \| warning \| error | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/report-action-result-codes|5.0.0` |
| `TestReport.setup.extension` | `TestReport.setup.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `TestReport.setup.id` | `TestReport.setup.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `TestReport.setup.modifierExtension` | `TestReport.setup.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `TestReport.status` | `TestReport.status` | `status` | TestReport.status | completed \| in-progress \| waiting \| stopped \| entered-in-error | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/report-status-codes|5.0.0` |
| `TestReport.teardown` | `TestReport.teardown` | `teardown` | TestReport.teardown | The results of running the series of required clean up steps | 0..1 | BackboneElement |  |  |
| `TestReport.teardown.action` | `TestReport.teardown.action` | `action` | TestReport.teardown.action | One or more teardown operations performed | 1..* | BackboneElement |  |  |
| `TestReport.teardown.action.extension` | `TestReport.teardown.action.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `TestReport.teardown.action.id` | `TestReport.teardown.action.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `TestReport.teardown.action.modifierExtension` | `TestReport.teardown.action.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `TestReport.teardown.action.operation` | `TestReport.teardown.action.operation` | `operation` | TestReport.teardown.action.operation | The teardown operation performed | 1..1 | TestReport.setup.action.operation |  |  |
| `TestReport.teardown.extension` | `TestReport.teardown.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `TestReport.teardown.id` | `TestReport.teardown.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `TestReport.teardown.modifierExtension` | `TestReport.teardown.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `TestReport.test` | `TestReport.test` | `test` | TestReport.test | A test executed from the test script | 0..* | BackboneElement |  |  |
| `TestReport.test.action` | `TestReport.test.action` | `action` | TestReport.test.action | A test operation or assert that was performed | 1..* | BackboneElement |  |  |
| `TestReport.test.action.assert` | `TestReport.test.action.assert` | `assert` | TestReport.test.action.assert | The assertion performed | 0..1 | TestReport.setup.action.assert |  |  |
| `TestReport.test.action.extension` | `TestReport.test.action.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `TestReport.test.action.id` | `TestReport.test.action.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `TestReport.test.action.modifierExtension` | `TestReport.test.action.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `TestReport.test.action.operation` | `TestReport.test.action.operation` | `operation` | TestReport.test.action.operation | The operation performed | 0..1 | TestReport.setup.action.operation |  |  |
| `TestReport.test.description` | `TestReport.test.description` | `description` | TestReport.test.description | Tracking/reporting short description of the test | 0..1 | string |  |  |
| `TestReport.test.extension` | `TestReport.test.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `TestReport.test.id` | `TestReport.test.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `TestReport.test.modifierExtension` | `TestReport.test.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `TestReport.test.name` | `TestReport.test.name` | `name` | TestReport.test.name | Tracking/logging name of this test | 0..1 | string |  |  |
| `TestReport.testScript` | `TestReport.testScript` | `testScript` | TestReport.testScript | Canonical URL to the  version-specific TestScript that was executed to produce this TestReport | 1..1 | canonical(http://hl7.org/fhir/StructureDefinition/TestScript) |  |  |
| `TestReport.tester` | `TestReport.tester` | `tester` | TestReport.tester | Name of the tester producing this report (Organization or individual) | 0..1 | string |  |  |
| `TestReport.text` | `TestReport.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [TestReport](/docs/R3/Resources/TestReport.md)<br/> `http://hl7.org/fhir/StructureDefinition/TestReport\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `525`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `721`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TestReport](/docs/R4/Resources/TestReport.md)<br/> `http://hl7.org/fhir/StructureDefinition/TestReport\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1637`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1638`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TestReport](/docs/R4B/Resources/TestReport.md)<br/> `http://hl7.org/fhir/StructureDefinition/TestReport\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1055`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1284`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TestReport](/docs/R5/Resources/TestReport.md)<br/> `http://hl7.org/fhir/StructureDefinition/TestReport\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition TestReport from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | [R3 TestReport](/docs/R3/Resources/TestReport.md)| Relationship | [R4 TestReport](/docs/R4/Resources/TestReport.md)| Relationship | [R4B TestReport](/docs/R4B/Resources/TestReport.md)| Relationship | R5 TestReport
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | `TestReport`| _Equivalent_<br/>(19273/19274)| `TestReport`| _Equivalent_<br/>(34348/34349)| `TestReport`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(48767)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(48768)| **`TestReport`**
| | | `TestReport.id`| _Equivalent_<br/>(19275/19276)| `TestReport.id`| _Equivalent_<br/>(34350/34351)| `TestReport.id`| _Equivalent_<br/>(48769/48770)| **`TestReport.id`**
| | | `TestReport.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(19277)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(19278)| `TestReport.meta`| _Equivalent_<br/>(34352/34353)| `TestReport.meta`| _Equivalent_<br/>(48771/48772)| **`TestReport.meta`**
| | | `TestReport.implicitRules`| _Equivalent_<br/>(19279/19280)| `TestReport.implicitRules`| _Equivalent_<br/>(34354/34355)| `TestReport.implicitRules`| _Equivalent_<br/>(48773/48774)| **`TestReport.implicitRules`**
| | | `TestReport.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(19281)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(19282)| `TestReport.language`| _Equivalent_<br/>(34356/34357)| `TestReport.language`| _Equivalent_<br/>(48775/48776)| **`TestReport.language`**
| | | `TestReport.text`| _Equivalent_<br/>(19283/19284)| `TestReport.text`| _Equivalent_<br/>(34358/34359)| `TestReport.text`| _Equivalent_<br/>(48777/48778)| **`TestReport.text`**
| | | `TestReport.contained`| _Equivalent_<br/>(19285/19286)| `TestReport.contained`| _Equivalent_<br/>(34360/34361)| `TestReport.contained`| _Equivalent_<br/>(48779/48780)| **`TestReport.contained`**
| | | `TestReport.extension`| _Equivalent_<br/>(19287/19288)| `TestReport.extension`| _Equivalent_<br/>(34362/34363)| `TestReport.extension`| _Equivalent_<br/>(48781/48782)| **`TestReport.extension`**
| | | `TestReport.modifierExtension`| _Equivalent_<br/>(19289/19290)| `TestReport.modifierExtension`| _Equivalent_<br/>(34364/34365)| `TestReport.modifierExtension`| _Equivalent_<br/>(48783/48784)| **`TestReport.modifierExtension`**
| | | `TestReport.identifier`| _Equivalent_<br/>(19291/19292)| `TestReport.identifier`| _Equivalent_<br/>(34366/34367)| `TestReport.identifier`| _Equivalent_<br/>(48785/48786)| **`TestReport.identifier`**
| | | `TestReport.name`| _Equivalent_<br/>(19293/19294)| `TestReport.name`| _Equivalent_<br/>(34368/34369)| `TestReport.name`| _Equivalent_<br/>(48787/48788)| **`TestReport.name`**
| | | `TestReport.status`| _Equivalent_<br/>(19295/19296)| `TestReport.status`| _Equivalent_<br/>(34370/34371)| `TestReport.status`| _Equivalent_<br/>(48789/48790)| **`TestReport.status`**
| | | `TestReport.testScript`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(19297)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(19298)| `TestReport.testScript`| _Equivalent_<br/>(34372/34373)| `TestReport.testScript`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(48791)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(48792)| **`TestReport.testScript`**
| | | `TestReport.result`| _Equivalent_<br/>(19299/19300)| `TestReport.result`| _Equivalent_<br/>(34374/34375)| `TestReport.result`| _Equivalent_<br/>(48793/48794)| **`TestReport.result`**
| | | `TestReport.score`| _Equivalent_<br/>(19301/19302)| `TestReport.score`| _Equivalent_<br/>(34376/34377)| `TestReport.score`| _Equivalent_<br/>(48795/48796)| **`TestReport.score`**
| | | `TestReport.tester`| _Equivalent_<br/>(19303/19304)| `TestReport.tester`| _Equivalent_<br/>(34378/34379)| `TestReport.tester`| _Equivalent_<br/>(48797/48798)| **`TestReport.tester`**
| | | `TestReport.issued`| _Equivalent_<br/>(19305/19306)| `TestReport.issued`| _Equivalent_<br/>(34380/34381)| `TestReport.issued`| _Equivalent_<br/>(48799/48800)| **`TestReport.issued`**
| | | `TestReport.participant`| _Equivalent_<br/>(19307/19308)| `TestReport.participant`| _Equivalent_<br/>(34382/34383)| `TestReport.participant`| _Equivalent_<br/>(48801/48802)| **`TestReport.participant`**
| | | `TestReport.participant.id`| _Equivalent_<br/>(19309/19310)| `TestReport.participant.id`| _Equivalent_<br/>(34384/34385)| `TestReport.participant.id`| _Equivalent_<br/>(48803/48804)| **`TestReport.participant.id`**
| | | `TestReport.participant.extension`| _Equivalent_<br/>(19311/19312)| `TestReport.participant.extension`| _Equivalent_<br/>(34386/34387)| `TestReport.participant.extension`| _Equivalent_<br/>(48805/48806)| **`TestReport.participant.extension`**
| | | `TestReport.participant.modifierExtension`| _Equivalent_<br/>(19313/19314)| `TestReport.participant.modifierExtension`| _Equivalent_<br/>(34388/34389)| `TestReport.participant.modifierExtension`| _Equivalent_<br/>(48807/48808)| **`TestReport.participant.modifierExtension`**
| | | `TestReport.participant.type`| _Equivalent_<br/>(19315/19316)| `TestReport.participant.type`| _Equivalent_<br/>(34390/34391)| `TestReport.participant.type`| _Equivalent_<br/>(48809/48810)| **`TestReport.participant.type`**
| | | `TestReport.participant.uri`| _Equivalent_<br/>(19317/19318)| `TestReport.participant.uri`| _Equivalent_<br/>(34392/34393)| `TestReport.participant.uri`| _Equivalent_<br/>(48811/48812)| **`TestReport.participant.uri`**
| | | `TestReport.participant.display`| _Equivalent_<br/>(19319/19320)| `TestReport.participant.display`| _Equivalent_<br/>(34394/34395)| `TestReport.participant.display`| _Equivalent_<br/>(48813/48814)| **`TestReport.participant.display`**
| | | `TestReport.setup`| _Equivalent_<br/>(19321/19322)| `TestReport.setup`| _Equivalent_<br/>(34396/34397)| `TestReport.setup`| _Equivalent_<br/>(48815/48816)| **`TestReport.setup`**
| | | `TestReport.setup.id`| _Equivalent_<br/>(19323/19324)| `TestReport.setup.id`| _Equivalent_<br/>(34398/34399)| `TestReport.setup.id`| _Equivalent_<br/>(48817/48818)| **`TestReport.setup.id`**
| | | `TestReport.setup.extension`| _Equivalent_<br/>(19325/19326)| `TestReport.setup.extension`| _Equivalent_<br/>(34400/34401)| `TestReport.setup.extension`| _Equivalent_<br/>(48819/48820)| **`TestReport.setup.extension`**
| | | `TestReport.setup.modifierExtension`| _Equivalent_<br/>(19327/19328)| `TestReport.setup.modifierExtension`| _Equivalent_<br/>(34402/34403)| `TestReport.setup.modifierExtension`| _Equivalent_<br/>(48821/48822)| **`TestReport.setup.modifierExtension`**
| | | `TestReport.setup.action`| _Equivalent_<br/>(19329/19330)| `TestReport.setup.action`| _Equivalent_<br/>(34404/34405)| `TestReport.setup.action`| _Equivalent_<br/>(48823/48824)| **`TestReport.setup.action`**
| | | `TestReport.setup.action.id`| _Equivalent_<br/>(19331/19332)| `TestReport.setup.action.id`| _Equivalent_<br/>(34406/34407)| `TestReport.setup.action.id`| _Equivalent_<br/>(48825/48826)| **`TestReport.setup.action.id`**
| | | `TestReport.setup.action.extension`| _Equivalent_<br/>(19333/19334)| `TestReport.setup.action.extension`| _Equivalent_<br/>(34408/34409)| `TestReport.setup.action.extension`| _Equivalent_<br/>(48827/48828)| **`TestReport.setup.action.extension`**
| | | `TestReport.setup.action.modifierExtension`| _Equivalent_<br/>(19335/19336)| `TestReport.setup.action.modifierExtension`| _Equivalent_<br/>(34410/34411)| `TestReport.setup.action.modifierExtension`| _Equivalent_<br/>(48829/48830)| **`TestReport.setup.action.modifierExtension`**
| | | `TestReport.setup.action.operation`| _Equivalent_<br/>(19337/19338)| `TestReport.setup.action.operation`| _Equivalent_<br/>(34412/34413)| `TestReport.setup.action.operation`| _Equivalent_<br/>(48831/48832)| **`TestReport.setup.action.operation`**
| | | `TestReport.setup.action.operation.id`| _Equivalent_<br/>(19339/19340)| `TestReport.setup.action.operation.id`| _Equivalent_<br/>(34414/34415)| `TestReport.setup.action.operation.id`| _Equivalent_<br/>(48833/48834)| **`TestReport.setup.action.operation.id`**
| | | `TestReport.setup.action.operation.extension`| _Equivalent_<br/>(19341/19342)| `TestReport.setup.action.operation.extension`| _Equivalent_<br/>(34416/34417)| `TestReport.setup.action.operation.extension`| _Equivalent_<br/>(48835/48836)| **`TestReport.setup.action.operation.extension`**
| | | `TestReport.setup.action.operation.modifierExtension`| _Equivalent_<br/>(19343/19344)| `TestReport.setup.action.operation.modifierExtension`| _Equivalent_<br/>(34418/34419)| `TestReport.setup.action.operation.modifierExtension`| _Equivalent_<br/>(48837/48838)| **`TestReport.setup.action.operation.modifierExtension`**
| | | `TestReport.setup.action.operation.result`| _Equivalent_<br/>(19345/19346)| `TestReport.setup.action.operation.result`| _Equivalent_<br/>(34420/34421)| `TestReport.setup.action.operation.result`| _Equivalent_<br/>(48839/48840)| **`TestReport.setup.action.operation.result`**
| | | `TestReport.setup.action.operation.message`| _Equivalent_<br/>(19347/19348)| `TestReport.setup.action.operation.message`| _Equivalent_<br/>(34422/34423)| `TestReport.setup.action.operation.message`| _Equivalent_<br/>(48841/48842)| **`TestReport.setup.action.operation.message`**
| | | `TestReport.setup.action.operation.detail`| _Equivalent_<br/>(19349/19350)| `TestReport.setup.action.operation.detail`| _Equivalent_<br/>(34424/34425)| `TestReport.setup.action.operation.detail`| _Equivalent_<br/>(48843/48844)| **`TestReport.setup.action.operation.detail`**
| | | `TestReport.setup.action.assert`| _Equivalent_<br/>(19351/19352)| `TestReport.setup.action.assert`| _Equivalent_<br/>(34426/34427)| `TestReport.setup.action.assert`| _Equivalent_<br/>(48845/48846)| **`TestReport.setup.action.assert`**
| | | `TestReport.setup.action.assert.id`| _Equivalent_<br/>(19353/19354)| `TestReport.setup.action.assert.id`| _Equivalent_<br/>(34428/34429)| `TestReport.setup.action.assert.id`| _Equivalent_<br/>(48847/48848)| **`TestReport.setup.action.assert.id`**
| | | `TestReport.setup.action.assert.extension`| _Equivalent_<br/>(19355/19356)| `TestReport.setup.action.assert.extension`| _Equivalent_<br/>(34430/34431)| `TestReport.setup.action.assert.extension`| _Equivalent_<br/>(48849/48850)| **`TestReport.setup.action.assert.extension`**
| | | `TestReport.setup.action.assert.modifierExtension`| _Equivalent_<br/>(19357/19358)| `TestReport.setup.action.assert.modifierExtension`| _Equivalent_<br/>(34432/34433)| `TestReport.setup.action.assert.modifierExtension`| _Equivalent_<br/>(48851/48852)| **`TestReport.setup.action.assert.modifierExtension`**
| | | `TestReport.setup.action.assert.result`| _Equivalent_<br/>(19359/19360)| `TestReport.setup.action.assert.result`| _Equivalent_<br/>(34434/34435)| `TestReport.setup.action.assert.result`| _Equivalent_<br/>(48853/48854)| **`TestReport.setup.action.assert.result`**
| | | `TestReport.setup.action.assert.message`| _Equivalent_<br/>(19361/19362)| `TestReport.setup.action.assert.message`| _Equivalent_<br/>(34436/34437)| `TestReport.setup.action.assert.message`| _Equivalent_<br/>(48855/48856)| **`TestReport.setup.action.assert.message`**
| | | `TestReport.setup.action.assert.detail`| _Equivalent_<br/>(19363/19364)| `TestReport.setup.action.assert.detail`| _Equivalent_<br/>(34438/34439)| `TestReport.setup.action.assert.detail`| _Equivalent_<br/>(48857/48858)| **`TestReport.setup.action.assert.detail`**
| | | | | | | | | **`TestReport.setup.action.assert.requirement`**
| | | | | | | | | **`TestReport.setup.action.assert.requirement.id`**
| | | | | | | | | **`TestReport.setup.action.assert.requirement.extension`**
| | | | | | | | | **`TestReport.setup.action.assert.requirement.modifierExtension`**
| | | | | | | | | **`TestReport.setup.action.assert.requirement.link[x]`**
| | | `TestReport.test`| _Equivalent_<br/>(19365/19366)| `TestReport.test`| _Equivalent_<br/>(34440/34441)| `TestReport.test`| _Equivalent_<br/>(48859/48860)| **`TestReport.test`**
| | | `TestReport.test.id`| _Equivalent_<br/>(19367/19368)| `TestReport.test.id`| _Equivalent_<br/>(34442/34443)| `TestReport.test.id`| _Equivalent_<br/>(48861/48862)| **`TestReport.test.id`**
| | | `TestReport.test.extension`| _Equivalent_<br/>(19369/19370)| `TestReport.test.extension`| _Equivalent_<br/>(34444/34445)| `TestReport.test.extension`| _Equivalent_<br/>(48863/48864)| **`TestReport.test.extension`**
| | | `TestReport.test.modifierExtension`| _Equivalent_<br/>(19371/19372)| `TestReport.test.modifierExtension`| _Equivalent_<br/>(34446/34447)| `TestReport.test.modifierExtension`| _Equivalent_<br/>(48865/48866)| **`TestReport.test.modifierExtension`**
| | | `TestReport.test.name`| _Equivalent_<br/>(19373/19374)| `TestReport.test.name`| _Equivalent_<br/>(34448/34449)| `TestReport.test.name`| _Equivalent_<br/>(48867/48868)| **`TestReport.test.name`**
| | | `TestReport.test.description`| _Equivalent_<br/>(19375/19376)| `TestReport.test.description`| _Equivalent_<br/>(34450/34451)| `TestReport.test.description`| _Equivalent_<br/>(48869/48870)| **`TestReport.test.description`**
| | | `TestReport.test.action`| _Equivalent_<br/>(19377/19378)| `TestReport.test.action`| _Equivalent_<br/>(34452/34453)| `TestReport.test.action`| _Equivalent_<br/>(48871/48872)| **`TestReport.test.action`**
| | | `TestReport.test.action.id`| _Equivalent_<br/>(19379/19380)| `TestReport.test.action.id`| _Equivalent_<br/>(34454/34455)| `TestReport.test.action.id`| _Equivalent_<br/>(48873/48874)| **`TestReport.test.action.id`**
| | | `TestReport.test.action.extension`| _Equivalent_<br/>(19381/19382)| `TestReport.test.action.extension`| _Equivalent_<br/>(34456/34457)| `TestReport.test.action.extension`| _Equivalent_<br/>(48875/48876)| **`TestReport.test.action.extension`**
| | | `TestReport.test.action.modifierExtension`| _Equivalent_<br/>(19383/19384)| `TestReport.test.action.modifierExtension`| _Equivalent_<br/>(34458/34459)| `TestReport.test.action.modifierExtension`| _Equivalent_<br/>(48877/48878)| **`TestReport.test.action.modifierExtension`**
| | | `TestReport.test.action.operation`| _Equivalent_<br/>(19385/19386)| `TestReport.test.action.operation`| _Equivalent_<br/>(34460/34461)| `TestReport.test.action.operation`| _Equivalent_<br/>(48879/48880)| **`TestReport.test.action.operation`**
| | | `TestReport.test.action.assert`| _Equivalent_<br/>(19387/19388)| `TestReport.test.action.assert`| _Equivalent_<br/>(34462/34463)| `TestReport.test.action.assert`| _Equivalent_<br/>(48881/48882)| **`TestReport.test.action.assert`**
| | | `TestReport.teardown`| _Equivalent_<br/>(19389/19390)| `TestReport.teardown`| _Equivalent_<br/>(34464/34465)| `TestReport.teardown`| _Equivalent_<br/>(48883/48884)| **`TestReport.teardown`**
| | | `TestReport.teardown.id`| _Equivalent_<br/>(19391/19392)| `TestReport.teardown.id`| _Equivalent_<br/>(34466/34467)| `TestReport.teardown.id`| _Equivalent_<br/>(48885/48886)| **`TestReport.teardown.id`**
| | | `TestReport.teardown.extension`| _Equivalent_<br/>(19393/19394)| `TestReport.teardown.extension`| _Equivalent_<br/>(34468/34469)| `TestReport.teardown.extension`| _Equivalent_<br/>(48887/48888)| **`TestReport.teardown.extension`**
| | | `TestReport.teardown.modifierExtension`| _Equivalent_<br/>(19395/19396)| `TestReport.teardown.modifierExtension`| _Equivalent_<br/>(34470/34471)| `TestReport.teardown.modifierExtension`| _Equivalent_<br/>(48889/48890)| **`TestReport.teardown.modifierExtension`**
| | | `TestReport.teardown.action`| _Equivalent_<br/>(19397/19398)| `TestReport.teardown.action`| _Equivalent_<br/>(34472/34473)| `TestReport.teardown.action`| _Equivalent_<br/>(48891/48892)| **`TestReport.teardown.action`**
| | | `TestReport.teardown.action.id`| _Equivalent_<br/>(19399/19400)| `TestReport.teardown.action.id`| _Equivalent_<br/>(34474/34475)| `TestReport.teardown.action.id`| _Equivalent_<br/>(48893/48894)| **`TestReport.teardown.action.id`**
| | | `TestReport.teardown.action.extension`| _Equivalent_<br/>(19401/19402)| `TestReport.teardown.action.extension`| _Equivalent_<br/>(34476/34477)| `TestReport.teardown.action.extension`| _Equivalent_<br/>(48895/48896)| **`TestReport.teardown.action.extension`**
| | | `TestReport.teardown.action.modifierExtension`| _Equivalent_<br/>(19403/19404)| `TestReport.teardown.action.modifierExtension`| _Equivalent_<br/>(34478/34479)| `TestReport.teardown.action.modifierExtension`| _Equivalent_<br/>(48897/48898)| **`TestReport.teardown.action.modifierExtension`**
| | | `TestReport.teardown.action.operation`| _Equivalent_<br/>(19405/19406)| `TestReport.teardown.action.operation`| _Equivalent_<br/>(34480/34481)| `TestReport.teardown.action.operation`| _Equivalent_<br/>(48899/48900)| **`TestReport.teardown.action.operation`**
| | | *67 of 67 elements used* | | *67 of 67 elements used* | | *67 of 67 elements used* | | *72 of 72 elements used* 

