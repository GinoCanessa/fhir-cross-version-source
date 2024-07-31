Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | CoverageEligibilityRequest |  | The CoverageEligibilityRequest provides patient and insurance coverage information to an insurer for them to respond, in the form of an CoverageEligibilityResponse, with information regarding whether the stated coverage is valid and in-force and optionally to provide the insurance details of the policy. | 58 | 35 |
| Target | CoverageEligibilityRequest |  | The CoverageEligibilityRequest provides patient and insurance coverage information to an insurer for them to respond, in the form of an CoverageEligibilityResponse, with information regarding whether the stated coverage is valid and in-force and optionally to provide the insurance details of the policy. | 52 | 32 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 6 |
Equivalent | 41 |
SourceIsBroaderThanTarget | 10 |
SourceIsNarrowerThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| CoverageEligibilityRequest | CoverageEligibilityRequest | Equivalent | R5 `CoverageEligibilityRequest` maps as Equivalent to R4 `CoverageEligibilityRequest` |
| CoverageEligibilityRequest.contained | CoverageEligibilityRequest.contained | Equivalent | R5 `CoverageEligibilityRequest.contained` maps as Equivalent to R4 `CoverageEligibilityRequest.contained` |
| CoverageEligibilityRequest.created | CoverageEligibilityRequest.created | Equivalent | R5 `CoverageEligibilityRequest.created` maps as Equivalent to R4 `CoverageEligibilityRequest.created` |
| CoverageEligibilityRequest.enterer | CoverageEligibilityRequest.enterer | Equivalent | R5 `CoverageEligibilityRequest.enterer` maps as Equivalent to R4 `CoverageEligibilityRequest.enterer` |
| CoverageEligibilityRequest.event | - | DoesNotExistInTarget | R5 `CoverageEligibilityRequest.event` does not appear in the target and has no mapping for `CoverageEligibilityRequest`. |
| CoverageEligibilityRequest.event.extension | - | DoesNotExistInTarget | R5 `CoverageEligibilityRequest.event.extension` does not appear in the target and has no mapping for `CoverageEligibilityRequest`. |
| CoverageEligibilityRequest.event.id | - | DoesNotExistInTarget | R5 `CoverageEligibilityRequest.event.id` does not appear in the target and has no mapping for `CoverageEligibilityRequest`. |
| CoverageEligibilityRequest.event.modifierExtension | - | DoesNotExistInTarget | R5 `CoverageEligibilityRequest.event.modifierExtension` does not appear in the target and has no mapping for `CoverageEligibilityRequest`. |
| CoverageEligibilityRequest.event.type | - | DoesNotExistInTarget | R5 `CoverageEligibilityRequest.event.type` does not appear in the target and has no mapping for `CoverageEligibilityRequest`. |
| CoverageEligibilityRequest.event.when[x] | - | DoesNotExistInTarget | R5 `CoverageEligibilityRequest.event.when[x]` does not appear in the target and has no mapping for `CoverageEligibilityRequest`. |
| CoverageEligibilityRequest.extension | CoverageEligibilityRequest.extension | SourceIsBroaderThanTarget | R5 `CoverageEligibilityRequest.extension` maps as SourceIsBroaderThanTarget to R4 `CoverageEligibilityRequest.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| CoverageEligibilityRequest.facility | CoverageEligibilityRequest.facility | Equivalent | R5 `CoverageEligibilityRequest.facility` maps as Equivalent to R4 `CoverageEligibilityRequest.facility` |
| CoverageEligibilityRequest.id | CoverageEligibilityRequest.id | Equivalent | R5 `CoverageEligibilityRequest.id` maps as Equivalent to R4 `CoverageEligibilityRequest.id` |
| CoverageEligibilityRequest.identifier | CoverageEligibilityRequest.identifier | Equivalent | R5 `CoverageEligibilityRequest.identifier` maps as Equivalent to R4 `CoverageEligibilityRequest.identifier` |
| CoverageEligibilityRequest.implicitRules | CoverageEligibilityRequest.implicitRules | Equivalent | R5 `CoverageEligibilityRequest.implicitRules` maps as Equivalent to R4 `CoverageEligibilityRequest.implicitRules` |
| CoverageEligibilityRequest.insurance | CoverageEligibilityRequest.insurance | Equivalent | R5 `CoverageEligibilityRequest.insurance` maps as Equivalent to R4 `CoverageEligibilityRequest.insurance` |
| CoverageEligibilityRequest.insurance.businessArrangement | CoverageEligibilityRequest.insurance.businessArrangement | Equivalent | R5 `CoverageEligibilityRequest.insurance.businessArrangement` maps as Equivalent to R4 `CoverageEligibilityRequest.insurance.businessArrangement` |
| CoverageEligibilityRequest.insurance.coverage | CoverageEligibilityRequest.insurance.coverage | Equivalent | R5 `CoverageEligibilityRequest.insurance.coverage` maps as Equivalent to R4 `CoverageEligibilityRequest.insurance.coverage` |
| CoverageEligibilityRequest.insurance.extension | CoverageEligibilityRequest.insurance.extension | SourceIsBroaderThanTarget | R5 `CoverageEligibilityRequest.insurance.extension` maps as SourceIsBroaderThanTarget to R4 `CoverageEligibilityRequest.insurance.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| CoverageEligibilityRequest.insurance.focal | CoverageEligibilityRequest.insurance.focal | Equivalent | R5 `CoverageEligibilityRequest.insurance.focal` maps as Equivalent to R4 `CoverageEligibilityRequest.insurance.focal` |
| CoverageEligibilityRequest.insurance.id | CoverageEligibilityRequest.insurance.id | Equivalent | R5 `CoverageEligibilityRequest.insurance.id` maps as Equivalent to R4 `CoverageEligibilityRequest.insurance.id` |
| CoverageEligibilityRequest.insurance.modifierExtension | CoverageEligibilityRequest.insurance.modifierExtension | SourceIsBroaderThanTarget | R5 `CoverageEligibilityRequest.insurance.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `CoverageEligibilityRequest.insurance.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| CoverageEligibilityRequest.insurer | CoverageEligibilityRequest.insurer | Equivalent | R5 `CoverageEligibilityRequest.insurer` maps as Equivalent to R4 `CoverageEligibilityRequest.insurer` |
| CoverageEligibilityRequest.item | CoverageEligibilityRequest.item | Equivalent | R5 `CoverageEligibilityRequest.item` maps as Equivalent to R4 `CoverageEligibilityRequest.item` |
| CoverageEligibilityRequest.item.category | CoverageEligibilityRequest.item.category | Equivalent | R5 `CoverageEligibilityRequest.item.category` maps as Equivalent to R4 `CoverageEligibilityRequest.item.category` |
| CoverageEligibilityRequest.item.detail | CoverageEligibilityRequest.item.detail | Equivalent | R5 `CoverageEligibilityRequest.item.detail` maps as Equivalent to R4 `CoverageEligibilityRequest.item.detail` |
| CoverageEligibilityRequest.item.diagnosis | CoverageEligibilityRequest.item.diagnosis | Equivalent | R5 `CoverageEligibilityRequest.item.diagnosis` maps as Equivalent to R4 `CoverageEligibilityRequest.item.diagnosis` |
| CoverageEligibilityRequest.item.diagnosis.diagnosis[x] | CoverageEligibilityRequest.item.diagnosis.diagnosis[x] | Equivalent | R5 `CoverageEligibilityRequest.item.diagnosis.diagnosis[x]` maps as Equivalent to R4 `CoverageEligibilityRequest.item.diagnosis.diagnosis[x]` |
| CoverageEligibilityRequest.item.diagnosis.extension | CoverageEligibilityRequest.item.diagnosis.extension | SourceIsBroaderThanTarget | R5 `CoverageEligibilityRequest.item.diagnosis.extension` maps as SourceIsBroaderThanTarget to R4 `CoverageEligibilityRequest.item.diagnosis.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| CoverageEligibilityRequest.item.diagnosis.id | CoverageEligibilityRequest.item.diagnosis.id | Equivalent | R5 `CoverageEligibilityRequest.item.diagnosis.id` maps as Equivalent to R4 `CoverageEligibilityRequest.item.diagnosis.id` |
| CoverageEligibilityRequest.item.diagnosis.modifierExtension | CoverageEligibilityRequest.item.diagnosis.modifierExtension | SourceIsBroaderThanTarget | R5 `CoverageEligibilityRequest.item.diagnosis.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `CoverageEligibilityRequest.item.diagnosis.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| CoverageEligibilityRequest.item.extension | CoverageEligibilityRequest.item.extension | SourceIsBroaderThanTarget | R5 `CoverageEligibilityRequest.item.extension` maps as SourceIsBroaderThanTarget to R4 `CoverageEligibilityRequest.item.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| CoverageEligibilityRequest.item.facility | CoverageEligibilityRequest.item.facility | Equivalent | R5 `CoverageEligibilityRequest.item.facility` maps as Equivalent to R4 `CoverageEligibilityRequest.item.facility` |
| CoverageEligibilityRequest.item.id | CoverageEligibilityRequest.item.id | Equivalent | R5 `CoverageEligibilityRequest.item.id` maps as Equivalent to R4 `CoverageEligibilityRequest.item.id` |
| CoverageEligibilityRequest.item.modifier | CoverageEligibilityRequest.item.modifier | Equivalent | R5 `CoverageEligibilityRequest.item.modifier` maps as Equivalent to R4 `CoverageEligibilityRequest.item.modifier` |
| CoverageEligibilityRequest.item.modifierExtension | CoverageEligibilityRequest.item.modifierExtension | SourceIsBroaderThanTarget | R5 `CoverageEligibilityRequest.item.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `CoverageEligibilityRequest.item.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| CoverageEligibilityRequest.item.productOrService | CoverageEligibilityRequest.item.productOrService | Equivalent | R5 `CoverageEligibilityRequest.item.productOrService` maps as Equivalent to R4 `CoverageEligibilityRequest.item.productOrService` |
| CoverageEligibilityRequest.item.provider | CoverageEligibilityRequest.item.provider | Equivalent | R5 `CoverageEligibilityRequest.item.provider` maps as Equivalent to R4 `CoverageEligibilityRequest.item.provider` |
| CoverageEligibilityRequest.item.quantity | CoverageEligibilityRequest.item.quantity | Equivalent | R5 `CoverageEligibilityRequest.item.quantity` maps as Equivalent to R4 `CoverageEligibilityRequest.item.quantity` |
| CoverageEligibilityRequest.item.supportingInfoSequence | CoverageEligibilityRequest.item.supportingInfoSequence | Equivalent | R5 `CoverageEligibilityRequest.item.supportingInfoSequence` maps as Equivalent to R4 `CoverageEligibilityRequest.item.supportingInfoSequence` |
| CoverageEligibilityRequest.item.unitPrice | CoverageEligibilityRequest.item.unitPrice | Equivalent | R5 `CoverageEligibilityRequest.item.unitPrice` maps as Equivalent to R4 `CoverageEligibilityRequest.item.unitPrice` |
| CoverageEligibilityRequest.language | CoverageEligibilityRequest.language | SourceIsNarrowerThanTarget | R5 `CoverageEligibilityRequest.language` maps as SourceIsNarrowerThanTarget to R4 `CoverageEligibilityRequest.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| CoverageEligibilityRequest.meta | CoverageEligibilityRequest.meta | Equivalent | R5 `CoverageEligibilityRequest.meta` maps as Equivalent to R4 `CoverageEligibilityRequest.meta` |
| CoverageEligibilityRequest.modifierExtension | CoverageEligibilityRequest.modifierExtension | SourceIsBroaderThanTarget | R5 `CoverageEligibilityRequest.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `CoverageEligibilityRequest.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| CoverageEligibilityRequest.patient | CoverageEligibilityRequest.patient | Equivalent | R5 `CoverageEligibilityRequest.patient` maps as Equivalent to R4 `CoverageEligibilityRequest.patient` |
| CoverageEligibilityRequest.priority | CoverageEligibilityRequest.priority | Equivalent | R5 `CoverageEligibilityRequest.priority` maps as Equivalent to R4 `CoverageEligibilityRequest.priority` |
| CoverageEligibilityRequest.provider | CoverageEligibilityRequest.provider | Equivalent | R5 `CoverageEligibilityRequest.provider` maps as Equivalent to R4 `CoverageEligibilityRequest.provider` |
| CoverageEligibilityRequest.purpose | CoverageEligibilityRequest.purpose | Equivalent | R5 `CoverageEligibilityRequest.purpose` maps as Equivalent to R4 `CoverageEligibilityRequest.purpose` - purpose has compatible required binding for code type: http://hl7.org/fhir/ValueSet/eligibilityrequest-purpose|5.0.0 and http://hl7.org/fhir/ValueSet/eligibilityrequest-purpose|4.0.1 (Equivalent) |
| CoverageEligibilityRequest.serviced[x] | CoverageEligibilityRequest.serviced[x] | Equivalent | R5 `CoverageEligibilityRequest.serviced[x]` maps as Equivalent to R4 `CoverageEligibilityRequest.serviced[x]` |
| CoverageEligibilityRequest.status | CoverageEligibilityRequest.status | Equivalent | R5 `CoverageEligibilityRequest.status` maps as Equivalent to R4 `CoverageEligibilityRequest.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/fm-status|5.0.0 and http://hl7.org/fhir/ValueSet/fm-status|4.0.1 (Equivalent) |
| CoverageEligibilityRequest.supportingInfo | CoverageEligibilityRequest.supportingInfo | Equivalent | R5 `CoverageEligibilityRequest.supportingInfo` maps as Equivalent to R4 `CoverageEligibilityRequest.supportingInfo` |
| CoverageEligibilityRequest.supportingInfo.appliesToAll | CoverageEligibilityRequest.supportingInfo.appliesToAll | Equivalent | R5 `CoverageEligibilityRequest.supportingInfo.appliesToAll` maps as Equivalent to R4 `CoverageEligibilityRequest.supportingInfo.appliesToAll` |
| CoverageEligibilityRequest.supportingInfo.extension | CoverageEligibilityRequest.supportingInfo.extension | SourceIsBroaderThanTarget | R5 `CoverageEligibilityRequest.supportingInfo.extension` maps as SourceIsBroaderThanTarget to R4 `CoverageEligibilityRequest.supportingInfo.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| CoverageEligibilityRequest.supportingInfo.id | CoverageEligibilityRequest.supportingInfo.id | Equivalent | R5 `CoverageEligibilityRequest.supportingInfo.id` maps as Equivalent to R4 `CoverageEligibilityRequest.supportingInfo.id` |
| CoverageEligibilityRequest.supportingInfo.information | CoverageEligibilityRequest.supportingInfo.information | Equivalent | R5 `CoverageEligibilityRequest.supportingInfo.information` maps as Equivalent to R4 `CoverageEligibilityRequest.supportingInfo.information` |
| CoverageEligibilityRequest.supportingInfo.modifierExtension | CoverageEligibilityRequest.supportingInfo.modifierExtension | SourceIsBroaderThanTarget | R5 `CoverageEligibilityRequest.supportingInfo.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `CoverageEligibilityRequest.supportingInfo.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| CoverageEligibilityRequest.supportingInfo.sequence | CoverageEligibilityRequest.supportingInfo.sequence | Equivalent | R5 `CoverageEligibilityRequest.supportingInfo.sequence` maps as Equivalent to R4 `CoverageEligibilityRequest.supportingInfo.sequence` |
| CoverageEligibilityRequest.text | CoverageEligibilityRequest.text | Equivalent | R5 `CoverageEligibilityRequest.text` maps as Equivalent to R4 `CoverageEligibilityRequest.text` |

