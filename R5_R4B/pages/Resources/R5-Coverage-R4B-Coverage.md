Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Coverage |  | Financial instrument which may be used to reimburse or pay for health care products and services. Includes both insurance and self-payment. | 55 | 35 |
| Target | Coverage |  | Financial instrument which may be used to reimburse or pay for health care products and services. Includes both insurance and self-payment. | 43 | 26 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 13 |
Equivalent | 4 |
RelatedTo | 38 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Coverage | Coverage | Equivalent | R5 `Coverage` maps as Equivalent to R4B `Coverage` |
| Coverage.beneficiary | Coverage.beneficiary | Equivalent | R5 `Coverage.beneficiary` maps as Equivalent to R4B `Coverage.beneficiary` |
| Coverage.class | Coverage.class | Equivalent | R5 `Coverage.class` maps as Equivalent to R4B `Coverage.class` |
| Coverage.class.extension | Coverage.class.extension | SourceIsBroaderThanTarget | R5 `Coverage.class.extension` maps as SourceIsBroaderThanTarget to R4B `Coverage.class.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Coverage.class.id | Coverage.class.id | Equivalent | R5 `Coverage.class.id` maps as Equivalent to R4B `Coverage.class.id` |
| Coverage.class.modifierExtension | Coverage.class.modifierExtension | SourceIsBroaderThanTarget | R5 `Coverage.class.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Coverage.class.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Coverage.class.name | Coverage.class.name | Equivalent | R5 `Coverage.class.name` maps as Equivalent to R4B `Coverage.class.name` |
| Coverage.class.type | Coverage.class.type | Equivalent | R5 `Coverage.class.type` maps as Equivalent to R4B `Coverage.class.type` |
| Coverage.class.value | Coverage.class.value | SourceIsBroaderThanTarget | R5 `Coverage.class.value` maps as SourceIsBroaderThanTarget to R4B `Coverage.class.value` - value has change due to type change: R5 value Identifier has no equivalent or mapped type in R4B value |
| Coverage.contained | Coverage.contained | Equivalent | R5 `Coverage.contained` maps as Equivalent to R4B `Coverage.contained` |
| Coverage.contract | Coverage.contract | Equivalent | R5 `Coverage.contract` maps as Equivalent to R4B `Coverage.contract` |
| Coverage.costToBeneficiary | Coverage.costToBeneficiary | Equivalent | R5 `Coverage.costToBeneficiary` maps as Equivalent to R4B `Coverage.costToBeneficiary` |
| Coverage.costToBeneficiary.category | - | DoesNotExistInTarget | R5 `Coverage.costToBeneficiary.category` does not appear in the target and has no mapping for `Coverage`. |
| Coverage.costToBeneficiary.exception | Coverage.costToBeneficiary.exception | Equivalent | R5 `Coverage.costToBeneficiary.exception` maps as Equivalent to R4B `Coverage.costToBeneficiary.exception` |
| Coverage.costToBeneficiary.exception.extension | Coverage.costToBeneficiary.exception.extension | SourceIsBroaderThanTarget | R5 `Coverage.costToBeneficiary.exception.extension` maps as SourceIsBroaderThanTarget to R4B `Coverage.costToBeneficiary.exception.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Coverage.costToBeneficiary.exception.id | Coverage.costToBeneficiary.exception.id | Equivalent | R5 `Coverage.costToBeneficiary.exception.id` maps as Equivalent to R4B `Coverage.costToBeneficiary.exception.id` |
| Coverage.costToBeneficiary.exception.modifierExtension | Coverage.costToBeneficiary.exception.modifierExtension | SourceIsBroaderThanTarget | R5 `Coverage.costToBeneficiary.exception.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Coverage.costToBeneficiary.exception.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Coverage.costToBeneficiary.exception.period | Coverage.costToBeneficiary.exception.period | Equivalent | R5 `Coverage.costToBeneficiary.exception.period` maps as Equivalent to R4B `Coverage.costToBeneficiary.exception.period` |
| Coverage.costToBeneficiary.exception.type | Coverage.costToBeneficiary.exception.type | Equivalent | R5 `Coverage.costToBeneficiary.exception.type` maps as Equivalent to R4B `Coverage.costToBeneficiary.exception.type` |
| Coverage.costToBeneficiary.extension | Coverage.costToBeneficiary.extension | SourceIsBroaderThanTarget | R5 `Coverage.costToBeneficiary.extension` maps as SourceIsBroaderThanTarget to R4B `Coverage.costToBeneficiary.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Coverage.costToBeneficiary.id | Coverage.costToBeneficiary.id | Equivalent | R5 `Coverage.costToBeneficiary.id` maps as Equivalent to R4B `Coverage.costToBeneficiary.id` |
| Coverage.costToBeneficiary.modifierExtension | Coverage.costToBeneficiary.modifierExtension | SourceIsBroaderThanTarget | R5 `Coverage.costToBeneficiary.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Coverage.costToBeneficiary.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Coverage.costToBeneficiary.network | - | DoesNotExistInTarget | R5 `Coverage.costToBeneficiary.network` does not appear in the target and has no mapping for `Coverage`. |
| Coverage.costToBeneficiary.term | - | DoesNotExistInTarget | R5 `Coverage.costToBeneficiary.term` does not appear in the target and has no mapping for `Coverage`. |
| Coverage.costToBeneficiary.type | Coverage.costToBeneficiary.type | Equivalent | R5 `Coverage.costToBeneficiary.type` maps as Equivalent to R4B `Coverage.costToBeneficiary.type` |
| Coverage.costToBeneficiary.unit | - | DoesNotExistInTarget | R5 `Coverage.costToBeneficiary.unit` does not appear in the target and has no mapping for `Coverage`. |
| Coverage.costToBeneficiary.value[x] | Coverage.costToBeneficiary.value[x] | RelatedTo | R5 `Coverage.costToBeneficiary.value[x]` maps as RelatedTo to R4B `Coverage.costToBeneficiary.value[x]` - value[x] made the element mandatory; value[x] increased the minimum cardinality from 0 to 1; value[x] has change due to type change: R5 `value[x]` `Money` maps as RelatedTo for R4B `value[x]` |
| Coverage.dependent | Coverage.dependent | Equivalent | R5 `Coverage.dependent` maps as Equivalent to R4B `Coverage.dependent` |
| Coverage.extension | Coverage.extension | SourceIsBroaderThanTarget | R5 `Coverage.extension` maps as SourceIsBroaderThanTarget to R4B `Coverage.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Coverage.id | Coverage.id | Equivalent | R5 `Coverage.id` maps as Equivalent to R4B `Coverage.id` |
| Coverage.identifier | Coverage.identifier | Equivalent | R5 `Coverage.identifier` maps as Equivalent to R4B `Coverage.identifier` |
| Coverage.implicitRules | Coverage.implicitRules | Equivalent | R5 `Coverage.implicitRules` maps as Equivalent to R4B `Coverage.implicitRules` |
| Coverage.insurancePlan | - | DoesNotExistInTarget | R5 `Coverage.insurancePlan` does not appear in the target and has no mapping for `Coverage`. |
| Coverage.insurer | - | DoesNotExistInTarget | R5 `Coverage.insurer` does not appear in the target and has no mapping for `Coverage`. |
| Coverage.kind | - | DoesNotExistInTarget | R5 `Coverage.kind` does not appear in the target and has no mapping for `Coverage`. |
| Coverage.language | Coverage.language | RelatedTo | R5 `Coverage.language` maps as RelatedTo to R4B `Coverage.language` - language changed the binding strength from Required to Preferred |
| Coverage.meta | Coverage.meta | Equivalent | R5 `Coverage.meta` maps as Equivalent to R4B `Coverage.meta` |
| Coverage.modifierExtension | Coverage.modifierExtension | SourceIsBroaderThanTarget | R5 `Coverage.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Coverage.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Coverage.network | Coverage.network | Equivalent | R5 `Coverage.network` maps as Equivalent to R4B `Coverage.network` |
| Coverage.order | Coverage.order | Equivalent | R5 `Coverage.order` maps as Equivalent to R4B `Coverage.order` |
| Coverage.paymentBy | - | DoesNotExistInTarget | R5 `Coverage.paymentBy` does not appear in the target and has no mapping for `Coverage`. |
| Coverage.paymentBy.extension | - | DoesNotExistInTarget | R5 `Coverage.paymentBy.extension` does not appear in the target and has no mapping for `Coverage`. |
| Coverage.paymentBy.id | - | DoesNotExistInTarget | R5 `Coverage.paymentBy.id` does not appear in the target and has no mapping for `Coverage`. |
| Coverage.paymentBy.modifierExtension | - | DoesNotExistInTarget | R5 `Coverage.paymentBy.modifierExtension` does not appear in the target and has no mapping for `Coverage`. |
| Coverage.paymentBy.party | - | DoesNotExistInTarget | R5 `Coverage.paymentBy.party` does not appear in the target and has no mapping for `Coverage`. |
| Coverage.paymentBy.responsibility | - | DoesNotExistInTarget | R5 `Coverage.paymentBy.responsibility` does not appear in the target and has no mapping for `Coverage`. |
| Coverage.period | Coverage.period | Equivalent | R5 `Coverage.period` maps as Equivalent to R4B `Coverage.period` |
| Coverage.policyHolder | Coverage.policyHolder | Equivalent | R5 `Coverage.policyHolder` maps as Equivalent to R4B `Coverage.policyHolder` |
| Coverage.relationship | Coverage.relationship | Equivalent | R5 `Coverage.relationship` maps as Equivalent to R4B `Coverage.relationship` |
| Coverage.status | Coverage.status | Equivalent | R5 `Coverage.status` maps as Equivalent to R4B `Coverage.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/fm-status|5.0.0 and http://hl7.org/fhir/ValueSet/fm-status|4.3.0 (Equivalent) |
| Coverage.subrogation | Coverage.subrogation | Equivalent | R5 `Coverage.subrogation` maps as Equivalent to R4B `Coverage.subrogation` |
| Coverage.subscriber | Coverage.subscriber | Equivalent | R5 `Coverage.subscriber` maps as Equivalent to R4B `Coverage.subscriber` |
| Coverage.subscriberId | Coverage.subscriberId | RelatedTo | R5 `Coverage.subscriberId` maps as RelatedTo to R4B `Coverage.subscriberId` - subscriberId changed from array to scalar (max cardinality from * to 1); subscriberId has change due to type change: R5 subscriberId Identifier has no equivalent or mapped type in R4B subscriberId |
| Coverage.text | Coverage.text | Equivalent | R5 `Coverage.text` maps as Equivalent to R4B `Coverage.text` |
| Coverage.type | Coverage.type | Equivalent | R5 `Coverage.type` maps as Equivalent to R4B `Coverage.type` |

