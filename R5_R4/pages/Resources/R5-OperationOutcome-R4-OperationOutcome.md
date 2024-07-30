Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | OperationOutcome |  | A collection of error, warning, or information messages that result from a system action. | 19 | 8 |
| Target | OperationOutcome |  | A collection of error, warning, or information messages that result from a system action. | 19 | 8 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 15 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| OperationOutcome | OperationOutcome | Equivalent | R5 `OperationOutcome` maps as Equivalent to R4 `OperationOutcome` |
| OperationOutcome.contained | OperationOutcome.contained | Equivalent | R5 `OperationOutcome.contained` maps as Equivalent to R4 `OperationOutcome.contained` |
| OperationOutcome.extension | OperationOutcome.extension | SourceIsBroaderThanTarget | R5 `OperationOutcome.extension` maps as SourceIsBroaderThanTarget to R4 `OperationOutcome.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| OperationOutcome.id | OperationOutcome.id | Equivalent | R5 `OperationOutcome.id` maps as Equivalent to R4 `OperationOutcome.id` |
| OperationOutcome.implicitRules | OperationOutcome.implicitRules | Equivalent | R5 `OperationOutcome.implicitRules` maps as Equivalent to R4 `OperationOutcome.implicitRules` |
| OperationOutcome.issue | OperationOutcome.issue | Equivalent | R5 `OperationOutcome.issue` maps as Equivalent to R4 `OperationOutcome.issue` |
| OperationOutcome.issue.code | OperationOutcome.issue.code | Equivalent | R5 `OperationOutcome.issue.code` maps as Equivalent to R4 `OperationOutcome.issue.code` - code has compatible required binding for code type: http://hl7.org/fhir/ValueSet/issue-type|5.0.0 and http://hl7.org/fhir/ValueSet/issue-type|4.0.1 (Equivalent) |
| OperationOutcome.issue.details | OperationOutcome.issue.details | Equivalent | R5 `OperationOutcome.issue.details` maps as Equivalent to R4 `OperationOutcome.issue.details` |
| OperationOutcome.issue.diagnostics | OperationOutcome.issue.diagnostics | Equivalent | R5 `OperationOutcome.issue.diagnostics` maps as Equivalent to R4 `OperationOutcome.issue.diagnostics` |
| OperationOutcome.issue.expression | OperationOutcome.issue.expression | Equivalent | R5 `OperationOutcome.issue.expression` maps as Equivalent to R4 `OperationOutcome.issue.expression` |
| OperationOutcome.issue.extension | OperationOutcome.issue.extension | SourceIsBroaderThanTarget | R5 `OperationOutcome.issue.extension` maps as SourceIsBroaderThanTarget to R4 `OperationOutcome.issue.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| OperationOutcome.issue.id | OperationOutcome.issue.id | Equivalent | R5 `OperationOutcome.issue.id` maps as Equivalent to R4 `OperationOutcome.issue.id` |
| OperationOutcome.issue.location | OperationOutcome.issue.location | Equivalent | R5 `OperationOutcome.issue.location` maps as Equivalent to R4 `OperationOutcome.issue.location` |
| OperationOutcome.issue.modifierExtension | OperationOutcome.issue.modifierExtension | SourceIsBroaderThanTarget | R5 `OperationOutcome.issue.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `OperationOutcome.issue.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| OperationOutcome.issue.severity | OperationOutcome.issue.severity | Equivalent | R5 `OperationOutcome.issue.severity` maps as Equivalent to R4 `OperationOutcome.issue.severity` - severity has compatible required binding for code type: http://hl7.org/fhir/ValueSet/issue-severity|5.0.0 and http://hl7.org/fhir/ValueSet/issue-severity|4.0.1 (Equivalent) |
| OperationOutcome.language | OperationOutcome.language | RelatedTo | R5 `OperationOutcome.language` maps as RelatedTo to R4 `OperationOutcome.language` - language changed the binding strength from Required to Preferred |
| OperationOutcome.meta | OperationOutcome.meta | Equivalent | R5 `OperationOutcome.meta` maps as Equivalent to R4 `OperationOutcome.meta` |
| OperationOutcome.modifierExtension | OperationOutcome.modifierExtension | SourceIsBroaderThanTarget | R5 `OperationOutcome.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `OperationOutcome.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| OperationOutcome.text | OperationOutcome.text | Equivalent | R5 `OperationOutcome.text` maps as Equivalent to R4 `OperationOutcome.text` |

