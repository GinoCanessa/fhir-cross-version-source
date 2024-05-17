Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

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
| OperationOutcome | OperationOutcome | Equivalent | R4B `OperationOutcome` maps as Equivalent to R5 `OperationOutcome` |
| OperationOutcome.contained | OperationOutcome.contained | Equivalent | R4B `OperationOutcome.contained` maps as Equivalent to R5 `OperationOutcome.contained` |
| OperationOutcome.extension | OperationOutcome.extension | RelatedTo | R4B `OperationOutcome.extension` maps as RelatedTo to R5 `OperationOutcome.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| OperationOutcome.id | OperationOutcome.id | Equivalent | R4B `OperationOutcome.id` maps as Equivalent to R5 `OperationOutcome.id` |
| OperationOutcome.implicitRules | OperationOutcome.implicitRules | Equivalent | R4B `OperationOutcome.implicitRules` maps as Equivalent to R5 `OperationOutcome.implicitRules` |
| OperationOutcome.issue | OperationOutcome.issue | Equivalent | R4B `OperationOutcome.issue` maps as Equivalent to R5 `OperationOutcome.issue` |
| OperationOutcome.issue.code | OperationOutcome.issue.code | Equivalent | R4B `OperationOutcome.issue.code` maps as Equivalent to R5 `OperationOutcome.issue.code` - code has compatible required binding for code type: http://hl7.org/fhir/ValueSet/issue-type|4.3.0 and http://hl7.org/fhir/ValueSet/issue-type|5.0.0 (Equivalent) |
| OperationOutcome.issue.details | OperationOutcome.issue.details | Equivalent | R4B `OperationOutcome.issue.details` maps as Equivalent to R5 `OperationOutcome.issue.details` |
| OperationOutcome.issue.diagnostics | OperationOutcome.issue.diagnostics | Equivalent | R4B `OperationOutcome.issue.diagnostics` maps as Equivalent to R5 `OperationOutcome.issue.diagnostics` |
| OperationOutcome.issue.expression | OperationOutcome.issue.expression | Equivalent | R4B `OperationOutcome.issue.expression` maps as Equivalent to R5 `OperationOutcome.issue.expression` |
| OperationOutcome.issue.extension | OperationOutcome.issue.extension | RelatedTo | R4B `OperationOutcome.issue.extension` maps as RelatedTo to R5 `OperationOutcome.issue.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| OperationOutcome.issue.id | OperationOutcome.issue.id | Equivalent | R4B `OperationOutcome.issue.id` maps as Equivalent to R5 `OperationOutcome.issue.id` |
| OperationOutcome.issue.location | OperationOutcome.issue.location | Equivalent | R4B `OperationOutcome.issue.location` maps as Equivalent to R5 `OperationOutcome.issue.location` |
| OperationOutcome.issue.modifierExtension | OperationOutcome.issue.modifierExtension | RelatedTo | R4B `OperationOutcome.issue.modifierExtension` maps as RelatedTo to R5 `OperationOutcome.issue.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| OperationOutcome.issue.severity | OperationOutcome.issue.severity | Equivalent | R4B `OperationOutcome.issue.severity` maps as Equivalent to R5 `OperationOutcome.issue.severity` - severity has compatible required binding for code type: http://hl7.org/fhir/ValueSet/issue-severity|4.3.0 and http://hl7.org/fhir/ValueSet/issue-severity|5.0.0 (Equivalent) |
| OperationOutcome.language | OperationOutcome.language | RelatedTo | R4B `OperationOutcome.language` maps as RelatedTo to R5 `OperationOutcome.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| OperationOutcome.meta | OperationOutcome.meta | Equivalent | R4B `OperationOutcome.meta` maps as Equivalent to R5 `OperationOutcome.meta` |
| OperationOutcome.modifierExtension | OperationOutcome.modifierExtension | RelatedTo | R4B `OperationOutcome.modifierExtension` maps as RelatedTo to R5 `OperationOutcome.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| OperationOutcome.text | OperationOutcome.text | Equivalent | R4B `OperationOutcome.text` maps as Equivalent to R5 `OperationOutcome.text` |

