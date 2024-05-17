Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | CoverageEligibilityRequest |  | The CoverageEligibilityRequest provides patient and insurance coverage information to an insurer for them to respond, in the form of an CoverageEligibilityResponse, with information regarding whether the stated coverage is valid and in-force and optionally to provide the insurance details of the policy. | 52 | 32 |
| Target | CoverageEligibilityRequest |  | The CoverageEligibilityRequest provides patient and insurance coverage information to an insurer for them to respond, in the form of an CoverageEligibilityResponse, with information regarding whether the stated coverage is valid and in-force and optionally to provide the insurance details of the policy. | 58 | 35 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 48 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| CoverageEligibilityRequest | CoverageEligibilityRequest | Equivalent | R4B `CoverageEligibilityRequest` maps as Equivalent to R5 `CoverageEligibilityRequest` |
| CoverageEligibilityRequest.contained | CoverageEligibilityRequest.contained | Equivalent | R4B `CoverageEligibilityRequest.contained` maps as Equivalent to R5 `CoverageEligibilityRequest.contained` |
| CoverageEligibilityRequest.created | CoverageEligibilityRequest.created | Equivalent | R4B `CoverageEligibilityRequest.created` maps as Equivalent to R5 `CoverageEligibilityRequest.created` |
| CoverageEligibilityRequest.enterer | CoverageEligibilityRequest.enterer | Equivalent | R4B `CoverageEligibilityRequest.enterer` maps as Equivalent to R5 `CoverageEligibilityRequest.enterer` |
| CoverageEligibilityRequest.extension | CoverageEligibilityRequest.extension | RelatedTo | R4B `CoverageEligibilityRequest.extension` maps as RelatedTo to R5 `CoverageEligibilityRequest.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| CoverageEligibilityRequest.facility | CoverageEligibilityRequest.facility | Equivalent | R4B `CoverageEligibilityRequest.facility` maps as Equivalent to R5 `CoverageEligibilityRequest.facility` |
| CoverageEligibilityRequest.id | CoverageEligibilityRequest.id | Equivalent | R4B `CoverageEligibilityRequest.id` maps as Equivalent to R5 `CoverageEligibilityRequest.id` |
| CoverageEligibilityRequest.identifier | CoverageEligibilityRequest.identifier | Equivalent | R4B `CoverageEligibilityRequest.identifier` maps as Equivalent to R5 `CoverageEligibilityRequest.identifier` |
| CoverageEligibilityRequest.implicitRules | CoverageEligibilityRequest.implicitRules | Equivalent | R4B `CoverageEligibilityRequest.implicitRules` maps as Equivalent to R5 `CoverageEligibilityRequest.implicitRules` |
| CoverageEligibilityRequest.insurance | CoverageEligibilityRequest.insurance | Equivalent | R4B `CoverageEligibilityRequest.insurance` maps as Equivalent to R5 `CoverageEligibilityRequest.insurance` |
| CoverageEligibilityRequest.insurance.businessArrangement | CoverageEligibilityRequest.insurance.businessArrangement | Equivalent | R4B `CoverageEligibilityRequest.insurance.businessArrangement` maps as Equivalent to R5 `CoverageEligibilityRequest.insurance.businessArrangement` |
| CoverageEligibilityRequest.insurance.coverage | CoverageEligibilityRequest.insurance.coverage | Equivalent | R4B `CoverageEligibilityRequest.insurance.coverage` maps as Equivalent to R5 `CoverageEligibilityRequest.insurance.coverage` |
| CoverageEligibilityRequest.insurance.extension | CoverageEligibilityRequest.insurance.extension | RelatedTo | R4B `CoverageEligibilityRequest.insurance.extension` maps as RelatedTo to R5 `CoverageEligibilityRequest.insurance.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| CoverageEligibilityRequest.insurance.focal | CoverageEligibilityRequest.insurance.focal | Equivalent | R4B `CoverageEligibilityRequest.insurance.focal` maps as Equivalent to R5 `CoverageEligibilityRequest.insurance.focal` |
| CoverageEligibilityRequest.insurance.id | CoverageEligibilityRequest.insurance.id | Equivalent | R4B `CoverageEligibilityRequest.insurance.id` maps as Equivalent to R5 `CoverageEligibilityRequest.insurance.id` |
| CoverageEligibilityRequest.insurance.modifierExtension | CoverageEligibilityRequest.insurance.modifierExtension | RelatedTo | R4B `CoverageEligibilityRequest.insurance.modifierExtension` maps as RelatedTo to R5 `CoverageEligibilityRequest.insurance.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| CoverageEligibilityRequest.insurer | CoverageEligibilityRequest.insurer | Equivalent | R4B `CoverageEligibilityRequest.insurer` maps as Equivalent to R5 `CoverageEligibilityRequest.insurer` |
| CoverageEligibilityRequest.item | CoverageEligibilityRequest.item | Equivalent | R4B `CoverageEligibilityRequest.item` maps as Equivalent to R5 `CoverageEligibilityRequest.item` |
| CoverageEligibilityRequest.item.category | CoverageEligibilityRequest.item.category | Equivalent | R4B `CoverageEligibilityRequest.item.category` maps as Equivalent to R5 `CoverageEligibilityRequest.item.category` |
| CoverageEligibilityRequest.item.detail | CoverageEligibilityRequest.item.detail | Equivalent | R4B `CoverageEligibilityRequest.item.detail` maps as Equivalent to R5 `CoverageEligibilityRequest.item.detail` |
| CoverageEligibilityRequest.item.diagnosis | CoverageEligibilityRequest.item.diagnosis | Equivalent | R4B `CoverageEligibilityRequest.item.diagnosis` maps as Equivalent to R5 `CoverageEligibilityRequest.item.diagnosis` |
| CoverageEligibilityRequest.item.diagnosis.diagnosis[x] | CoverageEligibilityRequest.item.diagnosis.diagnosis[x] | Equivalent | R4B `CoverageEligibilityRequest.item.diagnosis.diagnosis[x]` maps as Equivalent to R5 `CoverageEligibilityRequest.item.diagnosis.diagnosis[x]` |
| CoverageEligibilityRequest.item.diagnosis.extension | CoverageEligibilityRequest.item.diagnosis.extension | RelatedTo | R4B `CoverageEligibilityRequest.item.diagnosis.extension` maps as RelatedTo to R5 `CoverageEligibilityRequest.item.diagnosis.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| CoverageEligibilityRequest.item.diagnosis.id | CoverageEligibilityRequest.item.diagnosis.id | Equivalent | R4B `CoverageEligibilityRequest.item.diagnosis.id` maps as Equivalent to R5 `CoverageEligibilityRequest.item.diagnosis.id` |
| CoverageEligibilityRequest.item.diagnosis.modifierExtension | CoverageEligibilityRequest.item.diagnosis.modifierExtension | RelatedTo | R4B `CoverageEligibilityRequest.item.diagnosis.modifierExtension` maps as RelatedTo to R5 `CoverageEligibilityRequest.item.diagnosis.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| CoverageEligibilityRequest.item.extension | CoverageEligibilityRequest.item.extension | RelatedTo | R4B `CoverageEligibilityRequest.item.extension` maps as RelatedTo to R5 `CoverageEligibilityRequest.item.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| CoverageEligibilityRequest.item.facility | CoverageEligibilityRequest.item.facility | Equivalent | R4B `CoverageEligibilityRequest.item.facility` maps as Equivalent to R5 `CoverageEligibilityRequest.item.facility` |
| CoverageEligibilityRequest.item.id | CoverageEligibilityRequest.item.id | Equivalent | R4B `CoverageEligibilityRequest.item.id` maps as Equivalent to R5 `CoverageEligibilityRequest.item.id` |
| CoverageEligibilityRequest.item.modifier | CoverageEligibilityRequest.item.modifier | Equivalent | R4B `CoverageEligibilityRequest.item.modifier` maps as Equivalent to R5 `CoverageEligibilityRequest.item.modifier` |
| CoverageEligibilityRequest.item.modifierExtension | CoverageEligibilityRequest.item.modifierExtension | RelatedTo | R4B `CoverageEligibilityRequest.item.modifierExtension` maps as RelatedTo to R5 `CoverageEligibilityRequest.item.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| CoverageEligibilityRequest.item.productOrService | CoverageEligibilityRequest.item.productOrService | Equivalent | R4B `CoverageEligibilityRequest.item.productOrService` maps as Equivalent to R5 `CoverageEligibilityRequest.item.productOrService` |
| CoverageEligibilityRequest.item.provider | CoverageEligibilityRequest.item.provider | Equivalent | R4B `CoverageEligibilityRequest.item.provider` maps as Equivalent to R5 `CoverageEligibilityRequest.item.provider` |
| CoverageEligibilityRequest.item.quantity | CoverageEligibilityRequest.item.quantity | Equivalent | R4B `CoverageEligibilityRequest.item.quantity` maps as Equivalent to R5 `CoverageEligibilityRequest.item.quantity` |
| CoverageEligibilityRequest.item.supportingInfoSequence | CoverageEligibilityRequest.item.supportingInfoSequence | Equivalent | R4B `CoverageEligibilityRequest.item.supportingInfoSequence` maps as Equivalent to R5 `CoverageEligibilityRequest.item.supportingInfoSequence` |
| CoverageEligibilityRequest.item.unitPrice | CoverageEligibilityRequest.item.unitPrice | RelatedTo | R4B `CoverageEligibilityRequest.item.unitPrice` maps as RelatedTo to R5 `CoverageEligibilityRequest.item.unitPrice` - unitPrice has change due to type change: R4B `unitPrice` `Money` maps as RelatedTo for R5 `unitPrice` |
| CoverageEligibilityRequest.language | CoverageEligibilityRequest.language | RelatedTo | R4B `CoverageEligibilityRequest.language` maps as RelatedTo to R5 `CoverageEligibilityRequest.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| CoverageEligibilityRequest.meta | CoverageEligibilityRequest.meta | Equivalent | R4B `CoverageEligibilityRequest.meta` maps as Equivalent to R5 `CoverageEligibilityRequest.meta` |
| CoverageEligibilityRequest.modifierExtension | CoverageEligibilityRequest.modifierExtension | RelatedTo | R4B `CoverageEligibilityRequest.modifierExtension` maps as RelatedTo to R5 `CoverageEligibilityRequest.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| CoverageEligibilityRequest.patient | CoverageEligibilityRequest.patient | Equivalent | R4B `CoverageEligibilityRequest.patient` maps as Equivalent to R5 `CoverageEligibilityRequest.patient` |
| CoverageEligibilityRequest.priority | CoverageEligibilityRequest.priority | Equivalent | R4B `CoverageEligibilityRequest.priority` maps as Equivalent to R5 `CoverageEligibilityRequest.priority` |
| CoverageEligibilityRequest.provider | CoverageEligibilityRequest.provider | Equivalent | R4B `CoverageEligibilityRequest.provider` maps as Equivalent to R5 `CoverageEligibilityRequest.provider` |
| CoverageEligibilityRequest.purpose | CoverageEligibilityRequest.purpose | Equivalent | R4B `CoverageEligibilityRequest.purpose` maps as Equivalent to R5 `CoverageEligibilityRequest.purpose` - purpose has compatible required binding for code type: http://hl7.org/fhir/ValueSet/eligibilityrequest-purpose|4.3.0 and http://hl7.org/fhir/ValueSet/eligibilityrequest-purpose|5.0.0 (Equivalent) |
| CoverageEligibilityRequest.serviced[x] | CoverageEligibilityRequest.serviced[x] | Equivalent | R4B `CoverageEligibilityRequest.serviced[x]` maps as Equivalent to R5 `CoverageEligibilityRequest.serviced[x]` |
| CoverageEligibilityRequest.status | CoverageEligibilityRequest.status | Equivalent | R4B `CoverageEligibilityRequest.status` maps as Equivalent to R5 `CoverageEligibilityRequest.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/fm-status|4.3.0 and http://hl7.org/fhir/ValueSet/fm-status|5.0.0 (Equivalent) |
| CoverageEligibilityRequest.supportingInfo | CoverageEligibilityRequest.supportingInfo | Equivalent | R4B `CoverageEligibilityRequest.supportingInfo` maps as Equivalent to R5 `CoverageEligibilityRequest.supportingInfo` |
| CoverageEligibilityRequest.supportingInfo.appliesToAll | CoverageEligibilityRequest.supportingInfo.appliesToAll | Equivalent | R4B `CoverageEligibilityRequest.supportingInfo.appliesToAll` maps as Equivalent to R5 `CoverageEligibilityRequest.supportingInfo.appliesToAll` |
| CoverageEligibilityRequest.supportingInfo.extension | CoverageEligibilityRequest.supportingInfo.extension | RelatedTo | R4B `CoverageEligibilityRequest.supportingInfo.extension` maps as RelatedTo to R5 `CoverageEligibilityRequest.supportingInfo.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| CoverageEligibilityRequest.supportingInfo.id | CoverageEligibilityRequest.supportingInfo.id | Equivalent | R4B `CoverageEligibilityRequest.supportingInfo.id` maps as Equivalent to R5 `CoverageEligibilityRequest.supportingInfo.id` |
| CoverageEligibilityRequest.supportingInfo.information | CoverageEligibilityRequest.supportingInfo.information | Equivalent | R4B `CoverageEligibilityRequest.supportingInfo.information` maps as Equivalent to R5 `CoverageEligibilityRequest.supportingInfo.information` |
| CoverageEligibilityRequest.supportingInfo.modifierExtension | CoverageEligibilityRequest.supportingInfo.modifierExtension | RelatedTo | R4B `CoverageEligibilityRequest.supportingInfo.modifierExtension` maps as RelatedTo to R5 `CoverageEligibilityRequest.supportingInfo.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| CoverageEligibilityRequest.supportingInfo.sequence | CoverageEligibilityRequest.supportingInfo.sequence | Equivalent | R4B `CoverageEligibilityRequest.supportingInfo.sequence` maps as Equivalent to R5 `CoverageEligibilityRequest.supportingInfo.sequence` |
| CoverageEligibilityRequest.text | CoverageEligibilityRequest.text | Equivalent | R4B `CoverageEligibilityRequest.text` maps as Equivalent to R5 `CoverageEligibilityRequest.text` |

