Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | TestReport |  | A summary of information based on the results of executing a TestScript. | 67 | 32 |
| Target | TestReport |  | A summary of information based on the results of executing a TestScript. | 72 | 34 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 63 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| TestReport | TestReport | Equivalent | R4B `TestReport` maps as Equivalent to R5 `TestReport` |
| TestReport.contained | TestReport.contained | Equivalent | R4B `TestReport.contained` maps as Equivalent to R5 `TestReport.contained` |
| TestReport.extension | TestReport.extension | RelatedTo | R4B `TestReport.extension` maps as RelatedTo to R5 `TestReport.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| TestReport.id | TestReport.id | Equivalent | R4B `TestReport.id` maps as Equivalent to R5 `TestReport.id` |
| TestReport.identifier | TestReport.identifier | Equivalent | R4B `TestReport.identifier` maps as Equivalent to R5 `TestReport.identifier` |
| TestReport.implicitRules | TestReport.implicitRules | Equivalent | R4B `TestReport.implicitRules` maps as Equivalent to R5 `TestReport.implicitRules` |
| TestReport.issued | TestReport.issued | Equivalent | R4B `TestReport.issued` maps as Equivalent to R5 `TestReport.issued` |
| TestReport.language | TestReport.language | RelatedTo | R4B `TestReport.language` maps as RelatedTo to R5 `TestReport.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| TestReport.meta | TestReport.meta | Equivalent | R4B `TestReport.meta` maps as Equivalent to R5 `TestReport.meta` |
| TestReport.modifierExtension | TestReport.modifierExtension | RelatedTo | R4B `TestReport.modifierExtension` maps as RelatedTo to R5 `TestReport.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| TestReport.name | TestReport.name | Equivalent | R4B `TestReport.name` maps as Equivalent to R5 `TestReport.name` |
| TestReport.participant | TestReport.participant | Equivalent | R4B `TestReport.participant` maps as Equivalent to R5 `TestReport.participant` |
| TestReport.participant.display | TestReport.participant.display | Equivalent | R4B `TestReport.participant.display` maps as Equivalent to R5 `TestReport.participant.display` |
| TestReport.participant.extension | TestReport.participant.extension | RelatedTo | R4B `TestReport.participant.extension` maps as RelatedTo to R5 `TestReport.participant.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| TestReport.participant.id | TestReport.participant.id | Equivalent | R4B `TestReport.participant.id` maps as Equivalent to R5 `TestReport.participant.id` |
| TestReport.participant.modifierExtension | TestReport.participant.modifierExtension | RelatedTo | R4B `TestReport.participant.modifierExtension` maps as RelatedTo to R5 `TestReport.participant.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| TestReport.participant.type | TestReport.participant.type | Equivalent | R4B `TestReport.participant.type` maps as Equivalent to R5 `TestReport.participant.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/report-participant-type|4.3.0 and http://hl7.org/fhir/ValueSet/report-participant-type|5.0.0 (Equivalent) |
| TestReport.participant.uri | TestReport.participant.uri | Equivalent | R4B `TestReport.participant.uri` maps as Equivalent to R5 `TestReport.participant.uri` |
| TestReport.result | TestReport.result | Equivalent | R4B `TestReport.result` maps as Equivalent to R5 `TestReport.result` - result has compatible required binding for code type: http://hl7.org/fhir/ValueSet/report-result-codes|4.3.0 and http://hl7.org/fhir/ValueSet/report-result-codes|5.0.0 (Equivalent) |
| TestReport.score | TestReport.score | Equivalent | R4B `TestReport.score` maps as Equivalent to R5 `TestReport.score` |
| TestReport.setup | TestReport.setup | Equivalent | R4B `TestReport.setup` maps as Equivalent to R5 `TestReport.setup` |
| TestReport.setup.action | TestReport.setup.action | Equivalent | R4B `TestReport.setup.action` maps as Equivalent to R5 `TestReport.setup.action` |
| TestReport.setup.action.assert | TestReport.setup.action.assert | Equivalent | R4B `TestReport.setup.action.assert` maps as Equivalent to R5 `TestReport.setup.action.assert` |
| TestReport.setup.action.assert.detail | TestReport.setup.action.assert.detail | Equivalent | R4B `TestReport.setup.action.assert.detail` maps as Equivalent to R5 `TestReport.setup.action.assert.detail` |
| TestReport.setup.action.assert.extension | TestReport.setup.action.assert.extension | RelatedTo | R4B `TestReport.setup.action.assert.extension` maps as RelatedTo to R5 `TestReport.setup.action.assert.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| TestReport.setup.action.assert.id | TestReport.setup.action.assert.id | Equivalent | R4B `TestReport.setup.action.assert.id` maps as Equivalent to R5 `TestReport.setup.action.assert.id` |
| TestReport.setup.action.assert.message | TestReport.setup.action.assert.message | Equivalent | R4B `TestReport.setup.action.assert.message` maps as Equivalent to R5 `TestReport.setup.action.assert.message` |
| TestReport.setup.action.assert.modifierExtension | TestReport.setup.action.assert.modifierExtension | RelatedTo | R4B `TestReport.setup.action.assert.modifierExtension` maps as RelatedTo to R5 `TestReport.setup.action.assert.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| TestReport.setup.action.assert.result | TestReport.setup.action.assert.result | Equivalent | R4B `TestReport.setup.action.assert.result` maps as Equivalent to R5 `TestReport.setup.action.assert.result` - result has compatible required binding for code type: http://hl7.org/fhir/ValueSet/report-action-result-codes|4.3.0 and http://hl7.org/fhir/ValueSet/report-action-result-codes|5.0.0 (Equivalent) |
| TestReport.setup.action.extension | TestReport.setup.action.extension | RelatedTo | R4B `TestReport.setup.action.extension` maps as RelatedTo to R5 `TestReport.setup.action.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| TestReport.setup.action.id | TestReport.setup.action.id | Equivalent | R4B `TestReport.setup.action.id` maps as Equivalent to R5 `TestReport.setup.action.id` |
| TestReport.setup.action.modifierExtension | TestReport.setup.action.modifierExtension | RelatedTo | R4B `TestReport.setup.action.modifierExtension` maps as RelatedTo to R5 `TestReport.setup.action.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| TestReport.setup.action.operation | TestReport.setup.action.operation | Equivalent | R4B `TestReport.setup.action.operation` maps as Equivalent to R5 `TestReport.setup.action.operation` |
| TestReport.setup.action.operation.detail | TestReport.setup.action.operation.detail | Equivalent | R4B `TestReport.setup.action.operation.detail` maps as Equivalent to R5 `TestReport.setup.action.operation.detail` |
| TestReport.setup.action.operation.extension | TestReport.setup.action.operation.extension | RelatedTo | R4B `TestReport.setup.action.operation.extension` maps as RelatedTo to R5 `TestReport.setup.action.operation.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| TestReport.setup.action.operation.id | TestReport.setup.action.operation.id | Equivalent | R4B `TestReport.setup.action.operation.id` maps as Equivalent to R5 `TestReport.setup.action.operation.id` |
| TestReport.setup.action.operation.message | TestReport.setup.action.operation.message | Equivalent | R4B `TestReport.setup.action.operation.message` maps as Equivalent to R5 `TestReport.setup.action.operation.message` |
| TestReport.setup.action.operation.modifierExtension | TestReport.setup.action.operation.modifierExtension | RelatedTo | R4B `TestReport.setup.action.operation.modifierExtension` maps as RelatedTo to R5 `TestReport.setup.action.operation.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| TestReport.setup.action.operation.result | TestReport.setup.action.operation.result | Equivalent | R4B `TestReport.setup.action.operation.result` maps as Equivalent to R5 `TestReport.setup.action.operation.result` - result has compatible required binding for code type: http://hl7.org/fhir/ValueSet/report-action-result-codes|4.3.0 and http://hl7.org/fhir/ValueSet/report-action-result-codes|5.0.0 (Equivalent) |
| TestReport.setup.extension | TestReport.setup.extension | RelatedTo | R4B `TestReport.setup.extension` maps as RelatedTo to R5 `TestReport.setup.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| TestReport.setup.id | TestReport.setup.id | Equivalent | R4B `TestReport.setup.id` maps as Equivalent to R5 `TestReport.setup.id` |
| TestReport.setup.modifierExtension | TestReport.setup.modifierExtension | RelatedTo | R4B `TestReport.setup.modifierExtension` maps as RelatedTo to R5 `TestReport.setup.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| TestReport.status | TestReport.status | Equivalent | R4B `TestReport.status` maps as Equivalent to R5 `TestReport.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/report-status-codes|4.3.0 and http://hl7.org/fhir/ValueSet/report-status-codes|5.0.0 (Equivalent) |
| TestReport.teardown | TestReport.teardown | Equivalent | R4B `TestReport.teardown` maps as Equivalent to R5 `TestReport.teardown` |
| TestReport.teardown.action | TestReport.teardown.action | Equivalent | R4B `TestReport.teardown.action` maps as Equivalent to R5 `TestReport.teardown.action` |
| TestReport.teardown.action.extension | TestReport.teardown.action.extension | RelatedTo | R4B `TestReport.teardown.action.extension` maps as RelatedTo to R5 `TestReport.teardown.action.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| TestReport.teardown.action.id | TestReport.teardown.action.id | Equivalent | R4B `TestReport.teardown.action.id` maps as Equivalent to R5 `TestReport.teardown.action.id` |
| TestReport.teardown.action.modifierExtension | TestReport.teardown.action.modifierExtension | RelatedTo | R4B `TestReport.teardown.action.modifierExtension` maps as RelatedTo to R5 `TestReport.teardown.action.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| TestReport.teardown.action.operation | TestReport.teardown.action.operation | Equivalent | R4B `TestReport.teardown.action.operation` maps as Equivalent to R5 `TestReport.teardown.action.operation` |
| TestReport.teardown.extension | TestReport.teardown.extension | RelatedTo | R4B `TestReport.teardown.extension` maps as RelatedTo to R5 `TestReport.teardown.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| TestReport.teardown.id | TestReport.teardown.id | Equivalent | R4B `TestReport.teardown.id` maps as Equivalent to R5 `TestReport.teardown.id` |
| TestReport.teardown.modifierExtension | TestReport.teardown.modifierExtension | RelatedTo | R4B `TestReport.teardown.modifierExtension` maps as RelatedTo to R5 `TestReport.teardown.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| TestReport.test | TestReport.test | Equivalent | R4B `TestReport.test` maps as Equivalent to R5 `TestReport.test` |
| TestReport.test.action | TestReport.test.action | Equivalent | R4B `TestReport.test.action` maps as Equivalent to R5 `TestReport.test.action` |
| TestReport.test.action.assert | TestReport.test.action.assert | Equivalent | R4B `TestReport.test.action.assert` maps as Equivalent to R5 `TestReport.test.action.assert` |
| TestReport.test.action.extension | TestReport.test.action.extension | RelatedTo | R4B `TestReport.test.action.extension` maps as RelatedTo to R5 `TestReport.test.action.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| TestReport.test.action.id | TestReport.test.action.id | Equivalent | R4B `TestReport.test.action.id` maps as Equivalent to R5 `TestReport.test.action.id` |
| TestReport.test.action.modifierExtension | TestReport.test.action.modifierExtension | RelatedTo | R4B `TestReport.test.action.modifierExtension` maps as RelatedTo to R5 `TestReport.test.action.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| TestReport.test.action.operation | TestReport.test.action.operation | Equivalent | R4B `TestReport.test.action.operation` maps as Equivalent to R5 `TestReport.test.action.operation` |
| TestReport.test.description | TestReport.test.description | Equivalent | R4B `TestReport.test.description` maps as Equivalent to R5 `TestReport.test.description` |
| TestReport.test.extension | TestReport.test.extension | RelatedTo | R4B `TestReport.test.extension` maps as RelatedTo to R5 `TestReport.test.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| TestReport.test.id | TestReport.test.id | Equivalent | R4B `TestReport.test.id` maps as Equivalent to R5 `TestReport.test.id` |
| TestReport.test.modifierExtension | TestReport.test.modifierExtension | RelatedTo | R4B `TestReport.test.modifierExtension` maps as RelatedTo to R5 `TestReport.test.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| TestReport.test.name | TestReport.test.name | Equivalent | R4B `TestReport.test.name` maps as Equivalent to R5 `TestReport.test.name` |
| TestReport.tester | TestReport.tester | Equivalent | R4B `TestReport.tester` maps as Equivalent to R5 `TestReport.tester` |
| TestReport.testScript | TestReport.testScript | SourceIsBroaderThanTarget | R4B `TestReport.testScript` maps as SourceIsBroaderThanTarget to R5 `TestReport.testScript` - testScript has change due to type change: R4B testScript Reference has no equivalent or mapped type in R5 testScript |
| TestReport.text | TestReport.text | Equivalent | R4B `TestReport.text` maps as Equivalent to R5 `TestReport.text` |

