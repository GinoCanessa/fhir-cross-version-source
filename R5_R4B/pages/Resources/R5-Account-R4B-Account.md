Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Account |  | A financial tool for tracking value accrued for a particular purpose.  In the healthcare field, used to track charges for a patient, cost centers, etc. | 67 | 41 |
| Target | Account |  | A financial tool for tracking value accrued for a particular purpose.  In the healthcare field, used to track charges for a patient, cost centers, etc. | 31 | 17 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 37 |
Equivalent | 4 |
RelatedTo | 26 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Account | Account | Equivalent | R5 `Account` maps as Equivalent to R4B `Account` |
| Account.balance | - | DoesNotExistInTarget | R5 `Account.balance` does not appear in the target and has no mapping for `Account`. |
| Account.balance.aggregate | - | DoesNotExistInTarget | R5 `Account.balance.aggregate` does not appear in the target and has no mapping for `Account`. |
| Account.balance.amount | - | DoesNotExistInTarget | R5 `Account.balance.amount` does not appear in the target and has no mapping for `Account`. |
| Account.balance.estimate | - | DoesNotExistInTarget | R5 `Account.balance.estimate` does not appear in the target and has no mapping for `Account`. |
| Account.balance.extension | - | DoesNotExistInTarget | R5 `Account.balance.extension` does not appear in the target and has no mapping for `Account`. |
| Account.balance.id | - | DoesNotExistInTarget | R5 `Account.balance.id` does not appear in the target and has no mapping for `Account`. |
| Account.balance.modifierExtension | - | DoesNotExistInTarget | R5 `Account.balance.modifierExtension` does not appear in the target and has no mapping for `Account`. |
| Account.balance.term | - | DoesNotExistInTarget | R5 `Account.balance.term` does not appear in the target and has no mapping for `Account`. |
| Account.billingStatus | - | DoesNotExistInTarget | R5 `Account.billingStatus` does not appear in the target and has no mapping for `Account`. |
| Account.calculatedAt | - | DoesNotExistInTarget | R5 `Account.calculatedAt` does not appear in the target and has no mapping for `Account`. |
| Account.contained | Account.contained | Equivalent | R5 `Account.contained` maps as Equivalent to R4B `Account.contained` |
| Account.coverage | Account.coverage | Equivalent | R5 `Account.coverage` maps as Equivalent to R4B `Account.coverage` |
| Account.coverage.coverage | Account.coverage.coverage | Equivalent | R5 `Account.coverage.coverage` maps as Equivalent to R4B `Account.coverage.coverage` |
| Account.coverage.extension | Account.coverage.extension | SourceIsBroaderThanTarget | R5 `Account.coverage.extension` maps as SourceIsBroaderThanTarget to R4B `Account.coverage.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Account.coverage.id | Account.coverage.id | Equivalent | R5 `Account.coverage.id` maps as Equivalent to R4B `Account.coverage.id` |
| Account.coverage.modifierExtension | Account.coverage.modifierExtension | SourceIsBroaderThanTarget | R5 `Account.coverage.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Account.coverage.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Account.coverage.priority | Account.coverage.priority | Equivalent | R5 `Account.coverage.priority` maps as Equivalent to R4B `Account.coverage.priority` |
| Account.currency | - | DoesNotExistInTarget | R5 `Account.currency` does not appear in the target and has no mapping for `Account`. |
| Account.description | Account.description | SourceIsBroaderThanTarget | R5 `Account.description` maps as SourceIsBroaderThanTarget to R4B `Account.description` - description has change due to type change: R5 description markdown has no equivalent or mapped type in R4B description |
| Account.diagnosis | - | DoesNotExistInTarget | R5 `Account.diagnosis` does not appear in the target and has no mapping for `Account`. |
| Account.diagnosis.condition | - | DoesNotExistInTarget | R5 `Account.diagnosis.condition` does not appear in the target and has no mapping for `Account`. |
| Account.diagnosis.dateOfDiagnosis | - | DoesNotExistInTarget | R5 `Account.diagnosis.dateOfDiagnosis` does not appear in the target and has no mapping for `Account`. |
| Account.diagnosis.extension | - | DoesNotExistInTarget | R5 `Account.diagnosis.extension` does not appear in the target and has no mapping for `Account`. |
| Account.diagnosis.id | - | DoesNotExistInTarget | R5 `Account.diagnosis.id` does not appear in the target and has no mapping for `Account`. |
| Account.diagnosis.modifierExtension | - | DoesNotExistInTarget | R5 `Account.diagnosis.modifierExtension` does not appear in the target and has no mapping for `Account`. |
| Account.diagnosis.onAdmission | - | DoesNotExistInTarget | R5 `Account.diagnosis.onAdmission` does not appear in the target and has no mapping for `Account`. |
| Account.diagnosis.packageCode | - | DoesNotExistInTarget | R5 `Account.diagnosis.packageCode` does not appear in the target and has no mapping for `Account`. |
| Account.diagnosis.sequence | - | DoesNotExistInTarget | R5 `Account.diagnosis.sequence` does not appear in the target and has no mapping for `Account`. |
| Account.diagnosis.type | - | DoesNotExistInTarget | R5 `Account.diagnosis.type` does not appear in the target and has no mapping for `Account`. |
| Account.extension | Account.extension | SourceIsBroaderThanTarget | R5 `Account.extension` maps as SourceIsBroaderThanTarget to R4B `Account.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Account.guarantor | Account.guarantor | Equivalent | R5 `Account.guarantor` maps as Equivalent to R4B `Account.guarantor` |
| Account.guarantor.extension | Account.guarantor.extension | SourceIsBroaderThanTarget | R5 `Account.guarantor.extension` maps as SourceIsBroaderThanTarget to R4B `Account.guarantor.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Account.guarantor.id | Account.guarantor.id | Equivalent | R5 `Account.guarantor.id` maps as Equivalent to R4B `Account.guarantor.id` |
| Account.guarantor.modifierExtension | Account.guarantor.modifierExtension | SourceIsBroaderThanTarget | R5 `Account.guarantor.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Account.guarantor.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Account.guarantor.onHold | Account.guarantor.onHold | Equivalent | R5 `Account.guarantor.onHold` maps as Equivalent to R4B `Account.guarantor.onHold` |
| Account.guarantor.party | Account.guarantor.party | Equivalent | R5 `Account.guarantor.party` maps as Equivalent to R4B `Account.guarantor.party` |
| Account.guarantor.period | Account.guarantor.period | Equivalent | R5 `Account.guarantor.period` maps as Equivalent to R4B `Account.guarantor.period` |
| Account.id | Account.id | Equivalent | R5 `Account.id` maps as Equivalent to R4B `Account.id` |
| Account.identifier | Account.identifier | Equivalent | R5 `Account.identifier` maps as Equivalent to R4B `Account.identifier` |
| Account.implicitRules | Account.implicitRules | Equivalent | R5 `Account.implicitRules` maps as Equivalent to R4B `Account.implicitRules` |
| Account.language | Account.language | RelatedTo | R5 `Account.language` maps as RelatedTo to R4B `Account.language` - language changed the binding strength from Required to Preferred |
| Account.meta | Account.meta | Equivalent | R5 `Account.meta` maps as Equivalent to R4B `Account.meta` |
| Account.modifierExtension | Account.modifierExtension | SourceIsBroaderThanTarget | R5 `Account.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Account.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Account.name | Account.name | Equivalent | R5 `Account.name` maps as Equivalent to R4B `Account.name` |
| Account.owner | Account.owner | Equivalent | R5 `Account.owner` maps as Equivalent to R4B `Account.owner` |
| Account.procedure | - | DoesNotExistInTarget | R5 `Account.procedure` does not appear in the target and has no mapping for `Account`. |
| Account.procedure.code | - | DoesNotExistInTarget | R5 `Account.procedure.code` does not appear in the target and has no mapping for `Account`. |
| Account.procedure.dateOfService | - | DoesNotExistInTarget | R5 `Account.procedure.dateOfService` does not appear in the target and has no mapping for `Account`. |
| Account.procedure.device | - | DoesNotExistInTarget | R5 `Account.procedure.device` does not appear in the target and has no mapping for `Account`. |
| Account.procedure.extension | - | DoesNotExistInTarget | R5 `Account.procedure.extension` does not appear in the target and has no mapping for `Account`. |
| Account.procedure.id | - | DoesNotExistInTarget | R5 `Account.procedure.id` does not appear in the target and has no mapping for `Account`. |
| Account.procedure.modifierExtension | - | DoesNotExistInTarget | R5 `Account.procedure.modifierExtension` does not appear in the target and has no mapping for `Account`. |
| Account.procedure.packageCode | - | DoesNotExistInTarget | R5 `Account.procedure.packageCode` does not appear in the target and has no mapping for `Account`. |
| Account.procedure.sequence | - | DoesNotExistInTarget | R5 `Account.procedure.sequence` does not appear in the target and has no mapping for `Account`. |
| Account.procedure.type | - | DoesNotExistInTarget | R5 `Account.procedure.type` does not appear in the target and has no mapping for `Account`. |
| Account.relatedAccount | - | DoesNotExistInTarget | R5 `Account.relatedAccount` does not appear in the target and has no mapping for `Account`. |
| Account.relatedAccount.account | - | DoesNotExistInTarget | R5 `Account.relatedAccount.account` does not appear in the target and has no mapping for `Account`. |
| Account.relatedAccount.extension | - | DoesNotExistInTarget | R5 `Account.relatedAccount.extension` does not appear in the target and has no mapping for `Account`. |
| Account.relatedAccount.id | - | DoesNotExistInTarget | R5 `Account.relatedAccount.id` does not appear in the target and has no mapping for `Account`. |
| Account.relatedAccount.modifierExtension | - | DoesNotExistInTarget | R5 `Account.relatedAccount.modifierExtension` does not appear in the target and has no mapping for `Account`. |
| Account.relatedAccount.relationship | - | DoesNotExistInTarget | R5 `Account.relatedAccount.relationship` does not appear in the target and has no mapping for `Account`. |
| Account.servicePeriod | Account.servicePeriod | Equivalent | R5 `Account.servicePeriod` maps as Equivalent to R4B `Account.servicePeriod` |
| Account.status | Account.status | Equivalent | R5 `Account.status` maps as Equivalent to R4B `Account.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/account-status|5.0.0 and http://hl7.org/fhir/ValueSet/account-status|4.3.0 (Equivalent) |
| Account.subject | Account.subject | Equivalent | R5 `Account.subject` maps as Equivalent to R4B `Account.subject` |
| Account.text | Account.text | Equivalent | R5 `Account.text` maps as Equivalent to R4B `Account.text` |
| Account.type | Account.type | Equivalent | R5 `Account.type` maps as Equivalent to R4B `Account.type` |

