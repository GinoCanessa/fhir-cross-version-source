Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | SupplyRequest |  | A record of a request for a medication, substance or device used in the healthcare setting. | 29 | 18 |
| Target | SupplyRequest |  | A record of a non-patient specific request for a medication, substance, device, certain types of biologically derived product, and nutrition product used in the healthcare setting. | 30 | 19 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 3 |
Equivalent | 4 |
RelatedTo | 22 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| SupplyRequest | SupplyRequest | Equivalent | R4B `SupplyRequest` maps as Equivalent to R5 `SupplyRequest` |
| SupplyRequest.authoredOn | SupplyRequest.authoredOn | Equivalent | R4B `SupplyRequest.authoredOn` maps as Equivalent to R5 `SupplyRequest.authoredOn` |
| SupplyRequest.category | SupplyRequest.category | Equivalent | R4B `SupplyRequest.category` maps as Equivalent to R5 `SupplyRequest.category` |
| SupplyRequest.contained | SupplyRequest.contained | Equivalent | R4B `SupplyRequest.contained` maps as Equivalent to R5 `SupplyRequest.contained` |
| SupplyRequest.deliverFrom | SupplyRequest.deliverFrom | Equivalent | R4B `SupplyRequest.deliverFrom` maps as Equivalent to R5 `SupplyRequest.deliverFrom` |
| SupplyRequest.deliverTo | SupplyRequest.deliverTo | SourceIsNarrowerThanTarget | R4B `SupplyRequest.deliverTo` maps as SourceIsNarrowerThanTarget to R5 `SupplyRequest.deliverTo` - deliverTo has change due to type change: R4B `deliverTo` `Reference` maps as SourceIsNarrowerThanTarget for R5 `deliverTo` |
| SupplyRequest.extension | SupplyRequest.extension | RelatedTo | R4B `SupplyRequest.extension` maps as RelatedTo to R5 `SupplyRequest.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| SupplyRequest.id | SupplyRequest.id | Equivalent | R4B `SupplyRequest.id` maps as Equivalent to R5 `SupplyRequest.id` |
| SupplyRequest.identifier | SupplyRequest.identifier | Equivalent | R4B `SupplyRequest.identifier` maps as Equivalent to R5 `SupplyRequest.identifier` |
| SupplyRequest.implicitRules | SupplyRequest.implicitRules | Equivalent | R4B `SupplyRequest.implicitRules` maps as Equivalent to R5 `SupplyRequest.implicitRules` |
| SupplyRequest.item[x] | - | DoesNotExistInTarget | R4B `SupplyRequest.item[x]` does not appear in the target and has no mapping for `SupplyRequest`. |
| SupplyRequest.language | SupplyRequest.language | RelatedTo | R4B `SupplyRequest.language` maps as RelatedTo to R5 `SupplyRequest.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| SupplyRequest.meta | SupplyRequest.meta | Equivalent | R4B `SupplyRequest.meta` maps as Equivalent to R5 `SupplyRequest.meta` |
| SupplyRequest.modifierExtension | SupplyRequest.modifierExtension | RelatedTo | R4B `SupplyRequest.modifierExtension` maps as RelatedTo to R5 `SupplyRequest.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| SupplyRequest.occurrence[x] | SupplyRequest.occurrence[x] | Equivalent | R4B `SupplyRequest.occurrence[x]` maps as Equivalent to R5 `SupplyRequest.occurrence[x]` |
| SupplyRequest.parameter | SupplyRequest.parameter | Equivalent | R4B `SupplyRequest.parameter` maps as Equivalent to R5 `SupplyRequest.parameter` |
| SupplyRequest.parameter.code | SupplyRequest.parameter.code | Equivalent | R4B `SupplyRequest.parameter.code` maps as Equivalent to R5 `SupplyRequest.parameter.code` |
| SupplyRequest.parameter.extension | SupplyRequest.parameter.extension | RelatedTo | R4B `SupplyRequest.parameter.extension` maps as RelatedTo to R5 `SupplyRequest.parameter.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| SupplyRequest.parameter.id | SupplyRequest.parameter.id | Equivalent | R4B `SupplyRequest.parameter.id` maps as Equivalent to R5 `SupplyRequest.parameter.id` |
| SupplyRequest.parameter.modifierExtension | SupplyRequest.parameter.modifierExtension | RelatedTo | R4B `SupplyRequest.parameter.modifierExtension` maps as RelatedTo to R5 `SupplyRequest.parameter.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| SupplyRequest.parameter.value[x] | SupplyRequest.parameter.value[x] | Equivalent | R4B `SupplyRequest.parameter.value[x]` maps as Equivalent to R5 `SupplyRequest.parameter.value[x]` |
| SupplyRequest.priority | SupplyRequest.priority | Equivalent | R4B `SupplyRequest.priority` maps as Equivalent to R5 `SupplyRequest.priority` - priority has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-priority|4.3.0 and http://hl7.org/fhir/ValueSet/request-priority|5.0.0 (Equivalent) |
| SupplyRequest.quantity | SupplyRequest.quantity | Equivalent | R4B `SupplyRequest.quantity` maps as Equivalent to R5 `SupplyRequest.quantity` |
| SupplyRequest.reasonCode | - | DoesNotExistInTarget | R4B `SupplyRequest.reasonCode` does not appear in the target and has no mapping for `SupplyRequest`. |
| SupplyRequest.reasonReference | - | DoesNotExistInTarget | R4B `SupplyRequest.reasonReference` does not appear in the target and has no mapping for `SupplyRequest`. |
| SupplyRequest.requester | SupplyRequest.requester | SourceIsNarrowerThanTarget | R4B `SupplyRequest.requester` maps as SourceIsNarrowerThanTarget to R5 `SupplyRequest.requester` - requester has change due to type change: R4B `requester` `Reference` maps as SourceIsNarrowerThanTarget for R5 `requester` |
| SupplyRequest.status | SupplyRequest.status | Equivalent | R4B `SupplyRequest.status` maps as Equivalent to R5 `SupplyRequest.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/supplyrequest-status|4.3.0 and http://hl7.org/fhir/ValueSet/supplyrequest-status|5.0.0 (Equivalent) |
| SupplyRequest.supplier | SupplyRequest.supplier | Equivalent | R4B `SupplyRequest.supplier` maps as Equivalent to R5 `SupplyRequest.supplier` |
| SupplyRequest.text | SupplyRequest.text | Equivalent | R4B `SupplyRequest.text` maps as Equivalent to R5 `SupplyRequest.text` |

