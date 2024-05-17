Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Account |  | A financial tool for tracking value accrued for a particular purpose.  In the healthcare field, used to track charges for a patient, cost centers, etc. | 31 | 17 |
| Target | Account |  | A financial tool for tracking value accrued for a particular purpose.  In the healthcare field, used to track charges for a patient, cost centers, etc. | 67 | 41 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 1 |
Equivalent | 4 |
RelatedTo | 26 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Account | Account | Equivalent | R4B `Account` maps as Equivalent to R5 `Account` |
| Account.contained | Account.contained | Equivalent | R4B `Account.contained` maps as Equivalent to R5 `Account.contained` |
| Account.coverage | Account.coverage | Equivalent | R4B `Account.coverage` maps as Equivalent to R5 `Account.coverage` |
| Account.coverage.coverage | Account.coverage.coverage | Equivalent | R4B `Account.coverage.coverage` maps as Equivalent to R5 `Account.coverage.coverage` |
| Account.coverage.extension | Account.coverage.extension | RelatedTo | R4B `Account.coverage.extension` maps as RelatedTo to R5 `Account.coverage.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Account.coverage.id | Account.coverage.id | Equivalent | R4B `Account.coverage.id` maps as Equivalent to R5 `Account.coverage.id` |
| Account.coverage.modifierExtension | Account.coverage.modifierExtension | RelatedTo | R4B `Account.coverage.modifierExtension` maps as RelatedTo to R5 `Account.coverage.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Account.coverage.priority | Account.coverage.priority | Equivalent | R4B `Account.coverage.priority` maps as Equivalent to R5 `Account.coverage.priority` |
| Account.description | Account.description | SourceIsBroaderThanTarget | R4B `Account.description` maps as SourceIsBroaderThanTarget to R5 `Account.description` - description has change due to type change: R4B description string has no equivalent or mapped type in R5 description |
| Account.extension | Account.extension | RelatedTo | R4B `Account.extension` maps as RelatedTo to R5 `Account.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Account.guarantor | Account.guarantor | Equivalent | R4B `Account.guarantor` maps as Equivalent to R5 `Account.guarantor` |
| Account.guarantor.extension | Account.guarantor.extension | RelatedTo | R4B `Account.guarantor.extension` maps as RelatedTo to R5 `Account.guarantor.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Account.guarantor.id | Account.guarantor.id | Equivalent | R4B `Account.guarantor.id` maps as Equivalent to R5 `Account.guarantor.id` |
| Account.guarantor.modifierExtension | Account.guarantor.modifierExtension | RelatedTo | R4B `Account.guarantor.modifierExtension` maps as RelatedTo to R5 `Account.guarantor.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Account.guarantor.onHold | Account.guarantor.onHold | Equivalent | R4B `Account.guarantor.onHold` maps as Equivalent to R5 `Account.guarantor.onHold` |
| Account.guarantor.party | Account.guarantor.party | Equivalent | R4B `Account.guarantor.party` maps as Equivalent to R5 `Account.guarantor.party` |
| Account.guarantor.period | Account.guarantor.period | Equivalent | R4B `Account.guarantor.period` maps as Equivalent to R5 `Account.guarantor.period` |
| Account.id | Account.id | Equivalent | R4B `Account.id` maps as Equivalent to R5 `Account.id` |
| Account.identifier | Account.identifier | Equivalent | R4B `Account.identifier` maps as Equivalent to R5 `Account.identifier` |
| Account.implicitRules | Account.implicitRules | Equivalent | R4B `Account.implicitRules` maps as Equivalent to R5 `Account.implicitRules` |
| Account.language | Account.language | RelatedTo | R4B `Account.language` maps as RelatedTo to R5 `Account.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Account.meta | Account.meta | Equivalent | R4B `Account.meta` maps as Equivalent to R5 `Account.meta` |
| Account.modifierExtension | Account.modifierExtension | RelatedTo | R4B `Account.modifierExtension` maps as RelatedTo to R5 `Account.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Account.name | Account.name | Equivalent | R4B `Account.name` maps as Equivalent to R5 `Account.name` |
| Account.owner | Account.owner | Equivalent | R4B `Account.owner` maps as Equivalent to R5 `Account.owner` |
| Account.partOf | - | DoesNotExistInTarget | R4B `Account.partOf` does not appear in the target and has no mapping for `Account`. |
| Account.servicePeriod | Account.servicePeriod | Equivalent | R4B `Account.servicePeriod` maps as Equivalent to R5 `Account.servicePeriod` |
| Account.status | Account.status | Equivalent | R4B `Account.status` maps as Equivalent to R5 `Account.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/account-status|4.3.0 and http://hl7.org/fhir/ValueSet/account-status|5.0.0 (Equivalent) |
| Account.subject | Account.subject | Equivalent | R4B `Account.subject` maps as Equivalent to R5 `Account.subject` |
| Account.text | Account.text | Equivalent | R4B `Account.text` maps as Equivalent to R5 `Account.text` |
| Account.type | Account.type | Equivalent | R4B `Account.type` maps as Equivalent to R5 `Account.type` |

