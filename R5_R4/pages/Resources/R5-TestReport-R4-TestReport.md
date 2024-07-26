Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1
Generated at Thursday, July 25, 2024 3:56:51 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | TestReport |  | A summary of information based on the results of executing a TestScript. | 72 | 34 |
| Target | TestReport |  | A summary of information based on the results of executing a TestScript. | 67 | 32 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 5 |
Equivalent | 4 |
RelatedTo | 63 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| TestReport | TestReport | Equivalent | R5 `TestReport` maps as Equivalent to R4 `TestReport` |
| TestReport.contained | TestReport.contained | Equivalent | R5 `TestReport.contained` maps as Equivalent to R4 `TestReport.contained` |
| TestReport.extension | TestReport.extension | SourceIsBroaderThanTarget | R5 `TestReport.extension` maps as SourceIsBroaderThanTarget to R4 `TestReport.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| TestReport.id | TestReport.id | Equivalent | R5 `TestReport.id` maps as Equivalent to R4 `TestReport.id` |
| TestReport.identifier | TestReport.identifier | Equivalent | R5 `TestReport.identifier` maps as Equivalent to R4 `TestReport.identifier` |
| TestReport.implicitRules | TestReport.implicitRules | Equivalent | R5 `TestReport.implicitRules` maps as Equivalent to R4 `TestReport.implicitRules` |
| TestReport.issued | TestReport.issued | Equivalent | R5 `TestReport.issued` maps as Equivalent to R4 `TestReport.issued` |
| TestReport.language | TestReport.language | RelatedTo | R5 `TestReport.language` maps as RelatedTo to R4 `TestReport.language` - language changed the binding strength from Required to Preferred |
| TestReport.meta | TestReport.meta | Equivalent | R5 `TestReport.meta` maps as Equivalent to R4 `TestReport.meta` |
| TestReport.modifierExtension | TestReport.modifierExtension | SourceIsBroaderThanTarget | R5 `TestReport.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `TestReport.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| TestReport.name | TestReport.name | Equivalent | R5 `TestReport.name` maps as Equivalent to R4 `TestReport.name` |
| TestReport.participant | TestReport.participant | Equivalent | R5 `TestReport.participant` maps as Equivalent to R4 `TestReport.participant` |
| TestReport.participant.display | TestReport.participant.display | Equivalent | R5 `TestReport.participant.display` maps as Equivalent to R4 `TestReport.participant.display` |
| TestReport.participant.extension | TestReport.participant.extension | SourceIsBroaderThanTarget | R5 `TestReport.participant.extension` maps as SourceIsBroaderThanTarget to R4 `TestReport.participant.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| TestReport.participant.id | TestReport.participant.id | Equivalent | R5 `TestReport.participant.id` maps as Equivalent to R4 `TestReport.participant.id` |
| TestReport.participant.modifierExtension | TestReport.participant.modifierExtension | SourceIsBroaderThanTarget | R5 `TestReport.participant.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `TestReport.participant.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| TestReport.participant.type | TestReport.participant.type | Equivalent | R5 `TestReport.participant.type` maps as Equivalent to R4 `TestReport.participant.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/report-participant-type|5.0.0 and http://hl7.org/fhir/ValueSet/report-participant-type|4.0.1 (Equivalent) |
| TestReport.participant.uri | TestReport.participant.uri | Equivalent | R5 `TestReport.participant.uri` maps as Equivalent to R4 `TestReport.participant.uri` |
| TestReport.result | TestReport.result | Equivalent | R5 `TestReport.result` maps as Equivalent to R4 `TestReport.result` - result has compatible required binding for code type: http://hl7.org/fhir/ValueSet/report-result-codes|5.0.0 and http://hl7.org/fhir/ValueSet/report-result-codes|4.0.1 (Equivalent) |
| TestReport.score | TestReport.score | Equivalent | R5 `TestReport.score` maps as Equivalent to R4 `TestReport.score` |
| TestReport.setup | TestReport.setup | Equivalent | R5 `TestReport.setup` maps as Equivalent to R4 `TestReport.setup` |
| TestReport.setup.action | TestReport.setup.action | Equivalent | R5 `TestReport.setup.action` maps as Equivalent to R4 `TestReport.setup.action` |
| TestReport.setup.action.assert | TestReport.setup.action.assert | Equivalent | R5 `TestReport.setup.action.assert` maps as Equivalent to R4 `TestReport.setup.action.assert` |
| TestReport.setup.action.assert.detail | TestReport.setup.action.assert.detail | Equivalent | R5 `TestReport.setup.action.assert.detail` maps as Equivalent to R4 `TestReport.setup.action.assert.detail` |
| TestReport.setup.action.assert.extension | TestReport.setup.action.assert.extension | SourceIsBroaderThanTarget | R5 `TestReport.setup.action.assert.extension` maps as SourceIsBroaderThanTarget to R4 `TestReport.setup.action.assert.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| TestReport.setup.action.assert.id | TestReport.setup.action.assert.id | Equivalent | R5 `TestReport.setup.action.assert.id` maps as Equivalent to R4 `TestReport.setup.action.assert.id` |
| TestReport.setup.action.assert.message | TestReport.setup.action.assert.message | Equivalent | R5 `TestReport.setup.action.assert.message` maps as Equivalent to R4 `TestReport.setup.action.assert.message` |
| TestReport.setup.action.assert.modifierExtension | TestReport.setup.action.assert.modifierExtension | SourceIsBroaderThanTarget | R5 `TestReport.setup.action.assert.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `TestReport.setup.action.assert.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| TestReport.setup.action.assert.requirement | - | DoesNotExistInTarget | R5 `TestReport.setup.action.assert.requirement` does not appear in the target and has no mapping for `TestReport`. |
| TestReport.setup.action.assert.requirement.extension | - | DoesNotExistInTarget | R5 `TestReport.setup.action.assert.requirement.extension` does not appear in the target and has no mapping for `TestReport`. |
| TestReport.setup.action.assert.requirement.id | - | DoesNotExistInTarget | R5 `TestReport.setup.action.assert.requirement.id` does not appear in the target and has no mapping for `TestReport`. |
| TestReport.setup.action.assert.requirement.link[x] | - | DoesNotExistInTarget | R5 `TestReport.setup.action.assert.requirement.link[x]` does not appear in the target and has no mapping for `TestReport`. |
| TestReport.setup.action.assert.requirement.modifierExtension | - | DoesNotExistInTarget | R5 `TestReport.setup.action.assert.requirement.modifierExtension` does not appear in the target and has no mapping for `TestReport`. |
| TestReport.setup.action.assert.result | TestReport.setup.action.assert.result | Equivalent | R5 `TestReport.setup.action.assert.result` maps as Equivalent to R4 `TestReport.setup.action.assert.result` - result has compatible required binding for code type: http://hl7.org/fhir/ValueSet/report-action-result-codes|5.0.0 and http://hl7.org/fhir/ValueSet/report-action-result-codes|4.0.1 (Equivalent) |
| TestReport.setup.action.extension | TestReport.setup.action.extension | SourceIsBroaderThanTarget | R5 `TestReport.setup.action.extension` maps as SourceIsBroaderThanTarget to R4 `TestReport.setup.action.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| TestReport.setup.action.id | TestReport.setup.action.id | Equivalent | R5 `TestReport.setup.action.id` maps as Equivalent to R4 `TestReport.setup.action.id` |
| TestReport.setup.action.modifierExtension | TestReport.setup.action.modifierExtension | SourceIsBroaderThanTarget | R5 `TestReport.setup.action.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `TestReport.setup.action.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| TestReport.setup.action.operation | TestReport.setup.action.operation | Equivalent | R5 `TestReport.setup.action.operation` maps as Equivalent to R4 `TestReport.setup.action.operation` |
| TestReport.setup.action.operation.detail | TestReport.setup.action.operation.detail | Equivalent | R5 `TestReport.setup.action.operation.detail` maps as Equivalent to R4 `TestReport.setup.action.operation.detail` |
| TestReport.setup.action.operation.extension | TestReport.setup.action.operation.extension | SourceIsBroaderThanTarget | R5 `TestReport.setup.action.operation.extension` maps as SourceIsBroaderThanTarget to R4 `TestReport.setup.action.operation.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| TestReport.setup.action.operation.id | TestReport.setup.action.operation.id | Equivalent | R5 `TestReport.setup.action.operation.id` maps as Equivalent to R4 `TestReport.setup.action.operation.id` |
| TestReport.setup.action.operation.message | TestReport.setup.action.operation.message | Equivalent | R5 `TestReport.setup.action.operation.message` maps as Equivalent to R4 `TestReport.setup.action.operation.message` |
| TestReport.setup.action.operation.modifierExtension | TestReport.setup.action.operation.modifierExtension | SourceIsBroaderThanTarget | R5 `TestReport.setup.action.operation.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `TestReport.setup.action.operation.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| TestReport.setup.action.operation.result | TestReport.setup.action.operation.result | Equivalent | R5 `TestReport.setup.action.operation.result` maps as Equivalent to R4 `TestReport.setup.action.operation.result` - result has compatible required binding for code type: http://hl7.org/fhir/ValueSet/report-action-result-codes|5.0.0 and http://hl7.org/fhir/ValueSet/report-action-result-codes|4.0.1 (Equivalent) |
| TestReport.setup.extension | TestReport.setup.extension | SourceIsBroaderThanTarget | R5 `TestReport.setup.extension` maps as SourceIsBroaderThanTarget to R4 `TestReport.setup.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| TestReport.setup.id | TestReport.setup.id | Equivalent | R5 `TestReport.setup.id` maps as Equivalent to R4 `TestReport.setup.id` |
| TestReport.setup.modifierExtension | TestReport.setup.modifierExtension | SourceIsBroaderThanTarget | R5 `TestReport.setup.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `TestReport.setup.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| TestReport.status | TestReport.status | Equivalent | R5 `TestReport.status` maps as Equivalent to R4 `TestReport.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/report-status-codes|5.0.0 and http://hl7.org/fhir/ValueSet/report-status-codes|4.0.1 (Equivalent) |
| TestReport.teardown | TestReport.teardown | Equivalent | R5 `TestReport.teardown` maps as Equivalent to R4 `TestReport.teardown` |
| TestReport.teardown.action | TestReport.teardown.action | Equivalent | R5 `TestReport.teardown.action` maps as Equivalent to R4 `TestReport.teardown.action` |
| TestReport.teardown.action.extension | TestReport.teardown.action.extension | SourceIsBroaderThanTarget | R5 `TestReport.teardown.action.extension` maps as SourceIsBroaderThanTarget to R4 `TestReport.teardown.action.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| TestReport.teardown.action.id | TestReport.teardown.action.id | Equivalent | R5 `TestReport.teardown.action.id` maps as Equivalent to R4 `TestReport.teardown.action.id` |
| TestReport.teardown.action.modifierExtension | TestReport.teardown.action.modifierExtension | SourceIsBroaderThanTarget | R5 `TestReport.teardown.action.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `TestReport.teardown.action.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| TestReport.teardown.action.operation | TestReport.teardown.action.operation | Equivalent | R5 `TestReport.teardown.action.operation` maps as Equivalent to R4 `TestReport.teardown.action.operation` |
| TestReport.teardown.extension | TestReport.teardown.extension | SourceIsBroaderThanTarget | R5 `TestReport.teardown.extension` maps as SourceIsBroaderThanTarget to R4 `TestReport.teardown.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| TestReport.teardown.id | TestReport.teardown.id | Equivalent | R5 `TestReport.teardown.id` maps as Equivalent to R4 `TestReport.teardown.id` |
| TestReport.teardown.modifierExtension | TestReport.teardown.modifierExtension | SourceIsBroaderThanTarget | R5 `TestReport.teardown.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `TestReport.teardown.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| TestReport.test | TestReport.test | Equivalent | R5 `TestReport.test` maps as Equivalent to R4 `TestReport.test` |
| TestReport.test.action | TestReport.test.action | Equivalent | R5 `TestReport.test.action` maps as Equivalent to R4 `TestReport.test.action` |
| TestReport.test.action.assert | TestReport.test.action.assert | Equivalent | R5 `TestReport.test.action.assert` maps as Equivalent to R4 `TestReport.test.action.assert` |
| TestReport.test.action.extension | TestReport.test.action.extension | SourceIsBroaderThanTarget | R5 `TestReport.test.action.extension` maps as SourceIsBroaderThanTarget to R4 `TestReport.test.action.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| TestReport.test.action.id | TestReport.test.action.id | Equivalent | R5 `TestReport.test.action.id` maps as Equivalent to R4 `TestReport.test.action.id` |
| TestReport.test.action.modifierExtension | TestReport.test.action.modifierExtension | SourceIsBroaderThanTarget | R5 `TestReport.test.action.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `TestReport.test.action.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| TestReport.test.action.operation | TestReport.test.action.operation | Equivalent | R5 `TestReport.test.action.operation` maps as Equivalent to R4 `TestReport.test.action.operation` |
| TestReport.test.description | TestReport.test.description | Equivalent | R5 `TestReport.test.description` maps as Equivalent to R4 `TestReport.test.description` |
| TestReport.test.extension | TestReport.test.extension | SourceIsBroaderThanTarget | R5 `TestReport.test.extension` maps as SourceIsBroaderThanTarget to R4 `TestReport.test.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| TestReport.test.id | TestReport.test.id | Equivalent | R5 `TestReport.test.id` maps as Equivalent to R4 `TestReport.test.id` |
| TestReport.test.modifierExtension | TestReport.test.modifierExtension | SourceIsBroaderThanTarget | R5 `TestReport.test.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `TestReport.test.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| TestReport.test.name | TestReport.test.name | Equivalent | R5 `TestReport.test.name` maps as Equivalent to R4 `TestReport.test.name` |
| TestReport.tester | TestReport.tester | Equivalent | R5 `TestReport.tester` maps as Equivalent to R4 `TestReport.tester` |
| TestReport.testScript | TestReport.testScript | SourceIsBroaderThanTarget | R5 `TestReport.testScript` maps as SourceIsBroaderThanTarget to R4 `TestReport.testScript` - testScript has change due to type change: R5 testScript canonical has no equivalent or mapped type in R4 testScript |
| TestReport.text | TestReport.text | Equivalent | R5 `TestReport.text` maps as Equivalent to R4 `TestReport.text` |

