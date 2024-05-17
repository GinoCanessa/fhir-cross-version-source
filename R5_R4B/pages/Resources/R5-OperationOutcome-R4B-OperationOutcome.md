Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

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
| OperationOutcome | OperationOutcome | Equivalent | R5 `OperationOutcome` maps as Equivalent to R4B `OperationOutcome` |
| OperationOutcome.contained | OperationOutcome.contained | Equivalent | R5 `OperationOutcome.contained` maps as Equivalent to R4B `OperationOutcome.contained` |
| OperationOutcome.extension | OperationOutcome.extension | SourceIsBroaderThanTarget | R5 `OperationOutcome.extension` maps as SourceIsBroaderThanTarget to R4B `OperationOutcome.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| OperationOutcome.id | OperationOutcome.id | Equivalent | R5 `OperationOutcome.id` maps as Equivalent to R4B `OperationOutcome.id` |
| OperationOutcome.implicitRules | OperationOutcome.implicitRules | Equivalent | R5 `OperationOutcome.implicitRules` maps as Equivalent to R4B `OperationOutcome.implicitRules` |
| OperationOutcome.issue | OperationOutcome.issue | Equivalent | R5 `OperationOutcome.issue` maps as Equivalent to R4B `OperationOutcome.issue` |
| OperationOutcome.issue.code | OperationOutcome.issue.code | Equivalent | R5 `OperationOutcome.issue.code` maps as Equivalent to R4B `OperationOutcome.issue.code` - code has compatible required binding for code type: http://hl7.org/fhir/ValueSet/issue-type|5.0.0 and http://hl7.org/fhir/ValueSet/issue-type|4.3.0 (Equivalent) |
| OperationOutcome.issue.details | OperationOutcome.issue.details | Equivalent | R5 `OperationOutcome.issue.details` maps as Equivalent to R4B `OperationOutcome.issue.details` |
| OperationOutcome.issue.diagnostics | OperationOutcome.issue.diagnostics | Equivalent | R5 `OperationOutcome.issue.diagnostics` maps as Equivalent to R4B `OperationOutcome.issue.diagnostics` |
| OperationOutcome.issue.expression | OperationOutcome.issue.expression | Equivalent | R5 `OperationOutcome.issue.expression` maps as Equivalent to R4B `OperationOutcome.issue.expression` |
| OperationOutcome.issue.extension | OperationOutcome.issue.extension | SourceIsBroaderThanTarget | R5 `OperationOutcome.issue.extension` maps as SourceIsBroaderThanTarget to R4B `OperationOutcome.issue.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| OperationOutcome.issue.id | OperationOutcome.issue.id | Equivalent | R5 `OperationOutcome.issue.id` maps as Equivalent to R4B `OperationOutcome.issue.id` |
| OperationOutcome.issue.location | OperationOutcome.issue.location | Equivalent | R5 `OperationOutcome.issue.location` maps as Equivalent to R4B `OperationOutcome.issue.location` |
| OperationOutcome.issue.modifierExtension | OperationOutcome.issue.modifierExtension | SourceIsBroaderThanTarget | R5 `OperationOutcome.issue.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `OperationOutcome.issue.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| OperationOutcome.issue.severity | OperationOutcome.issue.severity | Equivalent | R5 `OperationOutcome.issue.severity` maps as Equivalent to R4B `OperationOutcome.issue.severity` - severity has compatible required binding for code type: http://hl7.org/fhir/ValueSet/issue-severity|5.0.0 and http://hl7.org/fhir/ValueSet/issue-severity|4.3.0 (Equivalent) |
| OperationOutcome.language | OperationOutcome.language | RelatedTo | R5 `OperationOutcome.language` maps as RelatedTo to R4B `OperationOutcome.language` - language changed the binding strength from Required to Preferred |
| OperationOutcome.meta | OperationOutcome.meta | Equivalent | R5 `OperationOutcome.meta` maps as Equivalent to R4B `OperationOutcome.meta` |
| OperationOutcome.modifierExtension | OperationOutcome.modifierExtension | SourceIsBroaderThanTarget | R5 `OperationOutcome.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `OperationOutcome.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| OperationOutcome.text | OperationOutcome.text | Equivalent | R5 `OperationOutcome.text` maps as Equivalent to R4B `OperationOutcome.text` |

