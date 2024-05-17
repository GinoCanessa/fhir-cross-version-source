Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Coverage |  | Financial instrument which may be used to reimburse or pay for health care products and services. Includes both insurance and self-payment. | 43 | 26 |
| Target | Coverage |  | Financial instrument which may be used to reimburse or pay for health care products and services. Includes both insurance and self-payment. | 55 | 35 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 1 |
Equivalent | 4 |
RelatedTo | 38 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Coverage | Coverage | Equivalent | R4B `Coverage` maps as Equivalent to R5 `Coverage` |
| Coverage.beneficiary | Coverage.beneficiary | Equivalent | R4B `Coverage.beneficiary` maps as Equivalent to R5 `Coverage.beneficiary` |
| Coverage.class | Coverage.class | Equivalent | R4B `Coverage.class` maps as Equivalent to R5 `Coverage.class` |
| Coverage.class.extension | Coverage.class.extension | RelatedTo | R4B `Coverage.class.extension` maps as RelatedTo to R5 `Coverage.class.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Coverage.class.id | Coverage.class.id | Equivalent | R4B `Coverage.class.id` maps as Equivalent to R5 `Coverage.class.id` |
| Coverage.class.modifierExtension | Coverage.class.modifierExtension | RelatedTo | R4B `Coverage.class.modifierExtension` maps as RelatedTo to R5 `Coverage.class.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Coverage.class.name | Coverage.class.name | Equivalent | R4B `Coverage.class.name` maps as Equivalent to R5 `Coverage.class.name` |
| Coverage.class.type | Coverage.class.type | Equivalent | R4B `Coverage.class.type` maps as Equivalent to R5 `Coverage.class.type` |
| Coverage.class.value | Coverage.class.value | SourceIsBroaderThanTarget | R4B `Coverage.class.value` maps as SourceIsBroaderThanTarget to R5 `Coverage.class.value` - value has change due to type change: R4B value string has no equivalent or mapped type in R5 value |
| Coverage.contained | Coverage.contained | Equivalent | R4B `Coverage.contained` maps as Equivalent to R5 `Coverage.contained` |
| Coverage.contract | Coverage.contract | Equivalent | R4B `Coverage.contract` maps as Equivalent to R5 `Coverage.contract` |
| Coverage.costToBeneficiary | Coverage.costToBeneficiary | Equivalent | R4B `Coverage.costToBeneficiary` maps as Equivalent to R5 `Coverage.costToBeneficiary` |
| Coverage.costToBeneficiary.exception | Coverage.costToBeneficiary.exception | Equivalent | R4B `Coverage.costToBeneficiary.exception` maps as Equivalent to R5 `Coverage.costToBeneficiary.exception` |
| Coverage.costToBeneficiary.exception.extension | Coverage.costToBeneficiary.exception.extension | RelatedTo | R4B `Coverage.costToBeneficiary.exception.extension` maps as RelatedTo to R5 `Coverage.costToBeneficiary.exception.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Coverage.costToBeneficiary.exception.id | Coverage.costToBeneficiary.exception.id | Equivalent | R4B `Coverage.costToBeneficiary.exception.id` maps as Equivalent to R5 `Coverage.costToBeneficiary.exception.id` |
| Coverage.costToBeneficiary.exception.modifierExtension | Coverage.costToBeneficiary.exception.modifierExtension | RelatedTo | R4B `Coverage.costToBeneficiary.exception.modifierExtension` maps as RelatedTo to R5 `Coverage.costToBeneficiary.exception.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Coverage.costToBeneficiary.exception.period | Coverage.costToBeneficiary.exception.period | Equivalent | R4B `Coverage.costToBeneficiary.exception.period` maps as Equivalent to R5 `Coverage.costToBeneficiary.exception.period` |
| Coverage.costToBeneficiary.exception.type | Coverage.costToBeneficiary.exception.type | Equivalent | R4B `Coverage.costToBeneficiary.exception.type` maps as Equivalent to R5 `Coverage.costToBeneficiary.exception.type` |
| Coverage.costToBeneficiary.extension | Coverage.costToBeneficiary.extension | RelatedTo | R4B `Coverage.costToBeneficiary.extension` maps as RelatedTo to R5 `Coverage.costToBeneficiary.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Coverage.costToBeneficiary.id | Coverage.costToBeneficiary.id | Equivalent | R4B `Coverage.costToBeneficiary.id` maps as Equivalent to R5 `Coverage.costToBeneficiary.id` |
| Coverage.costToBeneficiary.modifierExtension | Coverage.costToBeneficiary.modifierExtension | RelatedTo | R4B `Coverage.costToBeneficiary.modifierExtension` maps as RelatedTo to R5 `Coverage.costToBeneficiary.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Coverage.costToBeneficiary.type | Coverage.costToBeneficiary.type | Equivalent | R4B `Coverage.costToBeneficiary.type` maps as Equivalent to R5 `Coverage.costToBeneficiary.type` |
| Coverage.costToBeneficiary.value[x] | Coverage.costToBeneficiary.value[x] | RelatedTo | R4B `Coverage.costToBeneficiary.value[x]` maps as RelatedTo to R5 `Coverage.costToBeneficiary.value[x]` - value[x] has change due to type change: R4B `value[x]` `Money` maps as RelatedTo for R5 `value[x]` |
| Coverage.dependent | Coverage.dependent | Equivalent | R4B `Coverage.dependent` maps as Equivalent to R5 `Coverage.dependent` |
| Coverage.extension | Coverage.extension | RelatedTo | R4B `Coverage.extension` maps as RelatedTo to R5 `Coverage.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Coverage.id | Coverage.id | Equivalent | R4B `Coverage.id` maps as Equivalent to R5 `Coverage.id` |
| Coverage.identifier | Coverage.identifier | Equivalent | R4B `Coverage.identifier` maps as Equivalent to R5 `Coverage.identifier` |
| Coverage.implicitRules | Coverage.implicitRules | Equivalent | R4B `Coverage.implicitRules` maps as Equivalent to R5 `Coverage.implicitRules` |
| Coverage.language | Coverage.language | RelatedTo | R4B `Coverage.language` maps as RelatedTo to R5 `Coverage.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Coverage.meta | Coverage.meta | Equivalent | R4B `Coverage.meta` maps as Equivalent to R5 `Coverage.meta` |
| Coverage.modifierExtension | Coverage.modifierExtension | RelatedTo | R4B `Coverage.modifierExtension` maps as RelatedTo to R5 `Coverage.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Coverage.network | Coverage.network | Equivalent | R4B `Coverage.network` maps as Equivalent to R5 `Coverage.network` |
| Coverage.order | Coverage.order | Equivalent | R4B `Coverage.order` maps as Equivalent to R5 `Coverage.order` |
| Coverage.payor | - | DoesNotExistInTarget | R4B `Coverage.payor` does not appear in the target and has no mapping for `Coverage`. |
| Coverage.period | Coverage.period | Equivalent | R4B `Coverage.period` maps as Equivalent to R5 `Coverage.period` |
| Coverage.policyHolder | Coverage.policyHolder | Equivalent | R4B `Coverage.policyHolder` maps as Equivalent to R5 `Coverage.policyHolder` |
| Coverage.relationship | Coverage.relationship | Equivalent | R4B `Coverage.relationship` maps as Equivalent to R5 `Coverage.relationship` |
| Coverage.status | Coverage.status | Equivalent | R4B `Coverage.status` maps as Equivalent to R5 `Coverage.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/fm-status|4.3.0 and http://hl7.org/fhir/ValueSet/fm-status|5.0.0 (Equivalent) |
| Coverage.subrogation | Coverage.subrogation | Equivalent | R4B `Coverage.subrogation` maps as Equivalent to R5 `Coverage.subrogation` |
| Coverage.subscriber | Coverage.subscriber | Equivalent | R4B `Coverage.subscriber` maps as Equivalent to R5 `Coverage.subscriber` |
| Coverage.subscriberId | Coverage.subscriberId | RelatedTo | R4B `Coverage.subscriberId` maps as RelatedTo to R5 `Coverage.subscriberId` - subscriberId changed from scalar to array (max cardinality from 1 to *); subscriberId has change due to type change: R4B subscriberId string has no equivalent or mapped type in R5 subscriberId |
| Coverage.text | Coverage.text | Equivalent | R4B `Coverage.text` maps as Equivalent to R5 `Coverage.text` |
| Coverage.type | Coverage.type | Equivalent | R4B `Coverage.type` maps as Equivalent to R5 `Coverage.type` |

