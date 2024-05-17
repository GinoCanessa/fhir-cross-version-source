Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | SupplyRequest |  | A record of a non-patient specific request for a medication, substance, device, certain types of biologically derived product, and nutrition product used in the healthcare setting. | 30 | 19 |
| Target | SupplyRequest |  | A record of a request for a medication, substance or device used in the healthcare setting. | 29 | 18 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 4 |
Equivalent | 4 |
RelatedTo | 22 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| SupplyRequest | SupplyRequest | Equivalent | R5 `SupplyRequest` maps as Equivalent to R4B `SupplyRequest` |
| SupplyRequest.authoredOn | SupplyRequest.authoredOn | Equivalent | R5 `SupplyRequest.authoredOn` maps as Equivalent to R4B `SupplyRequest.authoredOn` |
| SupplyRequest.basedOn | - | DoesNotExistInTarget | R5 `SupplyRequest.basedOn` does not appear in the target and has no mapping for `SupplyRequest`. |
| SupplyRequest.category | SupplyRequest.category | Equivalent | R5 `SupplyRequest.category` maps as Equivalent to R4B `SupplyRequest.category` |
| SupplyRequest.contained | SupplyRequest.contained | Equivalent | R5 `SupplyRequest.contained` maps as Equivalent to R4B `SupplyRequest.contained` |
| SupplyRequest.deliverFor | - | DoesNotExistInTarget | R5 `SupplyRequest.deliverFor` does not appear in the target and has no mapping for `SupplyRequest`. |
| SupplyRequest.deliverFrom | SupplyRequest.deliverFrom | Equivalent | R5 `SupplyRequest.deliverFrom` maps as Equivalent to R4B `SupplyRequest.deliverFrom` |
| SupplyRequest.deliverTo | SupplyRequest.deliverTo | SourceIsBroaderThanTarget | R5 `SupplyRequest.deliverTo` maps as SourceIsBroaderThanTarget to R4B `SupplyRequest.deliverTo` - deliverTo has change due to type change: R5 `deliverTo` `Reference` maps as SourceIsBroaderThanTarget for R4B `deliverTo` |
| SupplyRequest.extension | SupplyRequest.extension | SourceIsBroaderThanTarget | R5 `SupplyRequest.extension` maps as SourceIsBroaderThanTarget to R4B `SupplyRequest.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| SupplyRequest.id | SupplyRequest.id | Equivalent | R5 `SupplyRequest.id` maps as Equivalent to R4B `SupplyRequest.id` |
| SupplyRequest.identifier | SupplyRequest.identifier | Equivalent | R5 `SupplyRequest.identifier` maps as Equivalent to R4B `SupplyRequest.identifier` |
| SupplyRequest.implicitRules | SupplyRequest.implicitRules | Equivalent | R5 `SupplyRequest.implicitRules` maps as Equivalent to R4B `SupplyRequest.implicitRules` |
| SupplyRequest.item | - | DoesNotExistInTarget | R5 `SupplyRequest.item` does not appear in the target and has no mapping for `SupplyRequest`. |
| SupplyRequest.language | SupplyRequest.language | RelatedTo | R5 `SupplyRequest.language` maps as RelatedTo to R4B `SupplyRequest.language` - language changed the binding strength from Required to Preferred |
| SupplyRequest.meta | SupplyRequest.meta | Equivalent | R5 `SupplyRequest.meta` maps as Equivalent to R4B `SupplyRequest.meta` |
| SupplyRequest.modifierExtension | SupplyRequest.modifierExtension | SourceIsBroaderThanTarget | R5 `SupplyRequest.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `SupplyRequest.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| SupplyRequest.occurrence[x] | SupplyRequest.occurrence[x] | Equivalent | R5 `SupplyRequest.occurrence[x]` maps as Equivalent to R4B `SupplyRequest.occurrence[x]` |
| SupplyRequest.parameter | SupplyRequest.parameter | Equivalent | R5 `SupplyRequest.parameter` maps as Equivalent to R4B `SupplyRequest.parameter` |
| SupplyRequest.parameter.code | SupplyRequest.parameter.code | Equivalent | R5 `SupplyRequest.parameter.code` maps as Equivalent to R4B `SupplyRequest.parameter.code` |
| SupplyRequest.parameter.extension | SupplyRequest.parameter.extension | SourceIsBroaderThanTarget | R5 `SupplyRequest.parameter.extension` maps as SourceIsBroaderThanTarget to R4B `SupplyRequest.parameter.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| SupplyRequest.parameter.id | SupplyRequest.parameter.id | Equivalent | R5 `SupplyRequest.parameter.id` maps as Equivalent to R4B `SupplyRequest.parameter.id` |
| SupplyRequest.parameter.modifierExtension | SupplyRequest.parameter.modifierExtension | SourceIsBroaderThanTarget | R5 `SupplyRequest.parameter.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `SupplyRequest.parameter.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| SupplyRequest.parameter.value[x] | SupplyRequest.parameter.value[x] | Equivalent | R5 `SupplyRequest.parameter.value[x]` maps as Equivalent to R4B `SupplyRequest.parameter.value[x]` |
| SupplyRequest.priority | SupplyRequest.priority | Equivalent | R5 `SupplyRequest.priority` maps as Equivalent to R4B `SupplyRequest.priority` - priority has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-priority|5.0.0 and http://hl7.org/fhir/ValueSet/request-priority|4.3.0 (Equivalent) |
| SupplyRequest.quantity | SupplyRequest.quantity | Equivalent | R5 `SupplyRequest.quantity` maps as Equivalent to R4B `SupplyRequest.quantity` |
| SupplyRequest.reason | - | DoesNotExistInTarget | R5 `SupplyRequest.reason` does not appear in the target and has no mapping for `SupplyRequest`. |
| SupplyRequest.requester | SupplyRequest.requester | SourceIsBroaderThanTarget | R5 `SupplyRequest.requester` maps as SourceIsBroaderThanTarget to R4B `SupplyRequest.requester` - requester has change due to type change: R5 `requester` `Reference` maps as SourceIsBroaderThanTarget for R4B `requester` |
| SupplyRequest.status | SupplyRequest.status | Equivalent | R5 `SupplyRequest.status` maps as Equivalent to R4B `SupplyRequest.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/supplyrequest-status|5.0.0 and http://hl7.org/fhir/ValueSet/supplyrequest-status|4.3.0 (Equivalent) |
| SupplyRequest.supplier | SupplyRequest.supplier | Equivalent | R5 `SupplyRequest.supplier` maps as Equivalent to R4B `SupplyRequest.supplier` |
| SupplyRequest.text | SupplyRequest.text | Equivalent | R5 `SupplyRequest.text` maps as Equivalent to R4B `SupplyRequest.text` |

