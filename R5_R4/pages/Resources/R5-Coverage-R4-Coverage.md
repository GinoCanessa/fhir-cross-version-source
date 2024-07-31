Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Coverage |  | Financial instrument which may be used to reimburse or pay for health care products and services. Includes both insurance and self-payment. | 55 | 35 |
| Target | Coverage |  | Financial instrument which may be used to reimburse or pay for health care products and services. Includes both insurance and self-payment. | 43 | 26 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 12 |
Equivalent | 29 |
RelatedTo | 2 |
SourceIsBroaderThanTarget | 10 |
SourceIsNarrowerThanTarget | 2 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Coverage | Coverage | SourceIsNarrowerThanTarget | R5 `Coverage` is narrower than R4 `Coverage` and is compatible. `Coverage` is mapped from `Coverage` and `Coverage.subscriberId`. |
| Coverage.beneficiary | Coverage.beneficiary | Equivalent | R5 `Coverage.beneficiary` maps as Equivalent to R4 `Coverage.beneficiary` |
| Coverage.class | Coverage.class | Equivalent | R5 `Coverage.class` maps as Equivalent to R4 `Coverage.class` |
| Coverage.class.extension | Coverage.class.extension | SourceIsBroaderThanTarget | R5 `Coverage.class.extension` maps as SourceIsBroaderThanTarget to R4 `Coverage.class.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Coverage.class.id | Coverage.class.id | Equivalent | R5 `Coverage.class.id` maps as Equivalent to R4 `Coverage.class.id` |
| Coverage.class.modifierExtension | Coverage.class.modifierExtension | SourceIsBroaderThanTarget | R5 `Coverage.class.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Coverage.class.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Coverage.class.name | Coverage.class.name | Equivalent | R5 `Coverage.class.name` maps as Equivalent to R4 `Coverage.class.name` |
| Coverage.class.type | Coverage.class.type | Equivalent | R5 `Coverage.class.type` maps as Equivalent to R4 `Coverage.class.type` |
| Coverage.class.value | Coverage.class.value | SourceIsBroaderThanTarget | R5 `Coverage.class.value` maps as SourceIsBroaderThanTarget to R4 `Coverage.class.value` - value has change due to type change: R5 value Identifier has no equivalent or mapped type in R4 value |
| Coverage.contained | Coverage.contained | Equivalent | R5 `Coverage.contained` maps as Equivalent to R4 `Coverage.contained` |
| Coverage.contract | Coverage.contract | Equivalent | R5 `Coverage.contract` maps as Equivalent to R4 `Coverage.contract` |
| Coverage.costToBeneficiary | Coverage.costToBeneficiary | Equivalent | R5 `Coverage.costToBeneficiary` maps as Equivalent to R4 `Coverage.costToBeneficiary` |
| Coverage.costToBeneficiary.category | - | DoesNotExistInTarget | R5 `Coverage.costToBeneficiary.category` does not appear in the target and has no mapping for `Coverage`. |
| Coverage.costToBeneficiary.exception | Coverage.costToBeneficiary.exception | Equivalent | R5 `Coverage.costToBeneficiary.exception` maps as Equivalent to R4 `Coverage.costToBeneficiary.exception` |
| Coverage.costToBeneficiary.exception.extension | Coverage.costToBeneficiary.exception.extension | SourceIsBroaderThanTarget | R5 `Coverage.costToBeneficiary.exception.extension` maps as SourceIsBroaderThanTarget to R4 `Coverage.costToBeneficiary.exception.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Coverage.costToBeneficiary.exception.id | Coverage.costToBeneficiary.exception.id | Equivalent | R5 `Coverage.costToBeneficiary.exception.id` maps as Equivalent to R4 `Coverage.costToBeneficiary.exception.id` |
| Coverage.costToBeneficiary.exception.modifierExtension | Coverage.costToBeneficiary.exception.modifierExtension | SourceIsBroaderThanTarget | R5 `Coverage.costToBeneficiary.exception.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Coverage.costToBeneficiary.exception.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Coverage.costToBeneficiary.exception.period | Coverage.costToBeneficiary.exception.period | Equivalent | R5 `Coverage.costToBeneficiary.exception.period` maps as Equivalent to R4 `Coverage.costToBeneficiary.exception.period` |
| Coverage.costToBeneficiary.exception.type | Coverage.costToBeneficiary.exception.type | Equivalent | R5 `Coverage.costToBeneficiary.exception.type` maps as Equivalent to R4 `Coverage.costToBeneficiary.exception.type` |
| Coverage.costToBeneficiary.extension | Coverage.costToBeneficiary.extension | SourceIsBroaderThanTarget | R5 `Coverage.costToBeneficiary.extension` maps as SourceIsBroaderThanTarget to R4 `Coverage.costToBeneficiary.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Coverage.costToBeneficiary.id | Coverage.costToBeneficiary.id | Equivalent | R5 `Coverage.costToBeneficiary.id` maps as Equivalent to R4 `Coverage.costToBeneficiary.id` |
| Coverage.costToBeneficiary.modifierExtension | Coverage.costToBeneficiary.modifierExtension | SourceIsBroaderThanTarget | R5 `Coverage.costToBeneficiary.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Coverage.costToBeneficiary.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Coverage.costToBeneficiary.network | - | DoesNotExistInTarget | R5 `Coverage.costToBeneficiary.network` does not appear in the target and has no mapping for `Coverage`. |
| Coverage.costToBeneficiary.term | - | DoesNotExistInTarget | R5 `Coverage.costToBeneficiary.term` does not appear in the target and has no mapping for `Coverage`. |
| Coverage.costToBeneficiary.type | Coverage.costToBeneficiary.type | Equivalent | R5 `Coverage.costToBeneficiary.type` maps as Equivalent to R4 `Coverage.costToBeneficiary.type` |
| Coverage.costToBeneficiary.unit | - | DoesNotExistInTarget | R5 `Coverage.costToBeneficiary.unit` does not appear in the target and has no mapping for `Coverage`. |
| Coverage.costToBeneficiary.value[x] | Coverage.costToBeneficiary.value[x] | RelatedTo | R5 `Coverage.costToBeneficiary.value[x]` maps as RelatedTo to R4 `Coverage.costToBeneficiary.value[x]` - value[x] made the element mandatory; value[x] increased the minimum cardinality from 0 to 1 |
| Coverage.dependent | Coverage.dependent | Equivalent | R5 `Coverage.dependent` maps as Equivalent to R4 `Coverage.dependent` |
| Coverage.extension | Coverage.extension | SourceIsBroaderThanTarget | R5 `Coverage.extension` maps as SourceIsBroaderThanTarget to R4 `Coverage.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Coverage.id | Coverage.id | Equivalent | R5 `Coverage.id` maps as Equivalent to R4 `Coverage.id` |
| Coverage.identifier | Coverage.identifier | Equivalent | R5 `Coverage.identifier` maps as Equivalent to R4 `Coverage.identifier` |
| Coverage.implicitRules | Coverage.implicitRules | Equivalent | R5 `Coverage.implicitRules` maps as Equivalent to R4 `Coverage.implicitRules` |
| Coverage.insurancePlan | - | DoesNotExistInTarget | R5 `Coverage.insurancePlan` does not appear in the target and has no mapping for `Coverage`. |
| Coverage.insurer | Coverage.payor | RelatedTo | R5 `Coverage.insurer` maps as RelatedTo to R4 `Coverage.payor` - payor made the element mandatory; payor increased the minimum cardinality from 0 to 1; payor changed from scalar to array (max cardinality from 1 to *); payor has change due to type change: R5 `insurer` `Reference` maps as SourceIsNarrowerThanTarget for R4 `payor` |
| Coverage.kind | - | DoesNotExistInTarget | R5 `Coverage.kind` does not appear in the target and has no mapping for `Coverage`. |
| Coverage.language | Coverage.language | SourceIsNarrowerThanTarget | R5 `Coverage.language` maps as SourceIsNarrowerThanTarget to R4 `Coverage.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| Coverage.meta | Coverage.meta | Equivalent | R5 `Coverage.meta` maps as Equivalent to R4 `Coverage.meta` |
| Coverage.modifierExtension | Coverage.modifierExtension | SourceIsBroaderThanTarget | R5 `Coverage.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Coverage.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Coverage.network | Coverage.network | Equivalent | R5 `Coverage.network` maps as Equivalent to R4 `Coverage.network` |
| Coverage.order | Coverage.order | Equivalent | R5 `Coverage.order` maps as Equivalent to R4 `Coverage.order` |
| Coverage.paymentBy | - | DoesNotExistInTarget | R5 `Coverage.paymentBy` does not appear in the target and has no mapping for `Coverage`. |
| Coverage.paymentBy.extension | - | DoesNotExistInTarget | R5 `Coverage.paymentBy.extension` does not appear in the target and has no mapping for `Coverage`. |
| Coverage.paymentBy.id | - | DoesNotExistInTarget | R5 `Coverage.paymentBy.id` does not appear in the target and has no mapping for `Coverage`. |
| Coverage.paymentBy.modifierExtension | - | DoesNotExistInTarget | R5 `Coverage.paymentBy.modifierExtension` does not appear in the target and has no mapping for `Coverage`. |
| Coverage.paymentBy.party | - | DoesNotExistInTarget | R5 `Coverage.paymentBy.party` does not appear in the target and has no mapping for `Coverage`. |
| Coverage.paymentBy.responsibility | - | DoesNotExistInTarget | R5 `Coverage.paymentBy.responsibility` does not appear in the target and has no mapping for `Coverage`. |
| Coverage.period | Coverage.period | Equivalent | R5 `Coverage.period` maps as Equivalent to R4 `Coverage.period` |
| Coverage.policyHolder | Coverage.policyHolder | Equivalent | R5 `Coverage.policyHolder` maps as Equivalent to R4 `Coverage.policyHolder` |
| Coverage.relationship | Coverage.relationship | Equivalent | R5 `Coverage.relationship` maps as Equivalent to R4 `Coverage.relationship` |
| Coverage.status | Coverage.status | Equivalent | R5 `Coverage.status` maps as Equivalent to R4 `Coverage.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/fm-status|5.0.0 and http://hl7.org/fhir/ValueSet/fm-status|4.0.1 (Equivalent) |
| Coverage.subrogation | Coverage.subrogation | Equivalent | R5 `Coverage.subrogation` maps as Equivalent to R4 `Coverage.subrogation` |
| Coverage.subscriber | Coverage.subscriber | Equivalent | R5 `Coverage.subscriber` maps as Equivalent to R4 `Coverage.subscriber` |
| Coverage.subscriberId | Coverage | SourceIsBroaderThanTarget | R5 `Coverage.subscriberId` maps as SourceIsBroaderThanTarget to R4 `Coverage` - Coverage has change due to type change: R5 subscriberId Identifier has no equivalent or mapped type in R4 Coverage |
| Coverage.text | Coverage.text | Equivalent | R5 `Coverage.text` maps as Equivalent to R4 `Coverage.text` |
| Coverage.type | Coverage.type | Equivalent | R5 `Coverage.type` maps as Equivalent to R4 `Coverage.type` |

