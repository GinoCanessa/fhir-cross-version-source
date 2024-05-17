Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | ChargeItemDefinition |  | The ChargeItemDefinition resource provides the properties that apply to the (billing) codes necessary to calculate costs and prices. The properties may differ largely depending on type and realm, therefore this resource gives only a rough structure and requires profiling for each type of billing code system. | 46 | 32 |
| Target | ChargeItemDefinition |  | The ChargeItemDefinition resource provides the properties that apply to the (billing) codes necessary to calculate costs and prices. The properties may differ largely depending on type and realm, therefore this resource gives only a rough structure and requires profiling for each type of billing code system. | 50 | 33 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 7 |
Equivalent | 4 |
RelatedTo | 35 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| ChargeItemDefinition | ChargeItemDefinition | Equivalent | R5 `ChargeItemDefinition` maps as Equivalent to R4B `ChargeItemDefinition` |
| ChargeItemDefinition.applicability | ChargeItemDefinition.applicability | Equivalent | R5 `ChargeItemDefinition.applicability` maps as Equivalent to R4B `ChargeItemDefinition.applicability` |
| ChargeItemDefinition.applicability.condition | - | DoesNotExistInTarget | R5 `ChargeItemDefinition.applicability.condition` does not appear in the target and has no mapping for `ChargeItemDefinition`. |
| ChargeItemDefinition.applicability.effectivePeriod | - | DoesNotExistInTarget | R5 `ChargeItemDefinition.applicability.effectivePeriod` does not appear in the target and has no mapping for `ChargeItemDefinition`. |
| ChargeItemDefinition.applicability.extension | ChargeItemDefinition.applicability.extension | SourceIsBroaderThanTarget | R5 `ChargeItemDefinition.applicability.extension` maps as SourceIsBroaderThanTarget to R4B `ChargeItemDefinition.applicability.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| ChargeItemDefinition.applicability.id | ChargeItemDefinition.applicability.id | Equivalent | R5 `ChargeItemDefinition.applicability.id` maps as Equivalent to R4B `ChargeItemDefinition.applicability.id` |
| ChargeItemDefinition.applicability.modifierExtension | ChargeItemDefinition.applicability.modifierExtension | SourceIsBroaderThanTarget | R5 `ChargeItemDefinition.applicability.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `ChargeItemDefinition.applicability.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| ChargeItemDefinition.applicability.relatedArtifact | - | DoesNotExistInTarget | R5 `ChargeItemDefinition.applicability.relatedArtifact` does not appear in the target and has no mapping for `ChargeItemDefinition`. |
| ChargeItemDefinition.approvalDate | ChargeItemDefinition.approvalDate | Equivalent | R5 `ChargeItemDefinition.approvalDate` maps as Equivalent to R4B `ChargeItemDefinition.approvalDate` |
| ChargeItemDefinition.code | ChargeItemDefinition.code | Equivalent | R5 `ChargeItemDefinition.code` maps as Equivalent to R4B `ChargeItemDefinition.code` |
| ChargeItemDefinition.contact | ChargeItemDefinition.contact | Equivalent | R5 `ChargeItemDefinition.contact` maps as Equivalent to R4B `ChargeItemDefinition.contact` |
| ChargeItemDefinition.contained | ChargeItemDefinition.contained | Equivalent | R5 `ChargeItemDefinition.contained` maps as Equivalent to R4B `ChargeItemDefinition.contained` |
| ChargeItemDefinition.copyright | ChargeItemDefinition.copyright | Equivalent | R5 `ChargeItemDefinition.copyright` maps as Equivalent to R4B `ChargeItemDefinition.copyright` |
| ChargeItemDefinition.copyrightLabel | - | DoesNotExistInTarget | R5 `ChargeItemDefinition.copyrightLabel` does not appear in the target and has no mapping for `ChargeItemDefinition`. |
| ChargeItemDefinition.date | ChargeItemDefinition.date | Equivalent | R5 `ChargeItemDefinition.date` maps as Equivalent to R4B `ChargeItemDefinition.date` |
| ChargeItemDefinition.derivedFromUri | ChargeItemDefinition.derivedFromUri | Equivalent | R5 `ChargeItemDefinition.derivedFromUri` maps as Equivalent to R4B `ChargeItemDefinition.derivedFromUri` |
| ChargeItemDefinition.description | ChargeItemDefinition.description | Equivalent | R5 `ChargeItemDefinition.description` maps as Equivalent to R4B `ChargeItemDefinition.description` |
| ChargeItemDefinition.experimental | ChargeItemDefinition.experimental | Equivalent | R5 `ChargeItemDefinition.experimental` maps as Equivalent to R4B `ChargeItemDefinition.experimental` |
| ChargeItemDefinition.extension | ChargeItemDefinition.extension | SourceIsBroaderThanTarget | R5 `ChargeItemDefinition.extension` maps as SourceIsBroaderThanTarget to R4B `ChargeItemDefinition.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| ChargeItemDefinition.id | ChargeItemDefinition.id | Equivalent | R5 `ChargeItemDefinition.id` maps as Equivalent to R4B `ChargeItemDefinition.id` |
| ChargeItemDefinition.identifier | ChargeItemDefinition.identifier | Equivalent | R5 `ChargeItemDefinition.identifier` maps as Equivalent to R4B `ChargeItemDefinition.identifier` |
| ChargeItemDefinition.implicitRules | ChargeItemDefinition.implicitRules | Equivalent | R5 `ChargeItemDefinition.implicitRules` maps as Equivalent to R4B `ChargeItemDefinition.implicitRules` |
| ChargeItemDefinition.instance | ChargeItemDefinition.instance | SourceIsBroaderThanTarget | R5 `ChargeItemDefinition.instance` maps as SourceIsBroaderThanTarget to R4B `ChargeItemDefinition.instance` - instance has change due to type change: R5 `instance` `Reference` maps as SourceIsBroaderThanTarget for R4B `instance` |
| ChargeItemDefinition.jurisdiction | ChargeItemDefinition.jurisdiction | Equivalent | R5 `ChargeItemDefinition.jurisdiction` maps as Equivalent to R4B `ChargeItemDefinition.jurisdiction` |
| ChargeItemDefinition.language | ChargeItemDefinition.language | RelatedTo | R5 `ChargeItemDefinition.language` maps as RelatedTo to R4B `ChargeItemDefinition.language` - language changed the binding strength from Required to Preferred |
| ChargeItemDefinition.lastReviewDate | ChargeItemDefinition.lastReviewDate | Equivalent | R5 `ChargeItemDefinition.lastReviewDate` maps as Equivalent to R4B `ChargeItemDefinition.lastReviewDate` |
| ChargeItemDefinition.meta | ChargeItemDefinition.meta | Equivalent | R5 `ChargeItemDefinition.meta` maps as Equivalent to R4B `ChargeItemDefinition.meta` |
| ChargeItemDefinition.modifierExtension | ChargeItemDefinition.modifierExtension | SourceIsBroaderThanTarget | R5 `ChargeItemDefinition.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `ChargeItemDefinition.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| ChargeItemDefinition.name | - | DoesNotExistInTarget | R5 `ChargeItemDefinition.name` does not appear in the target and has no mapping for `ChargeItemDefinition`. |
| ChargeItemDefinition.partOf | ChargeItemDefinition.partOf | Equivalent | R5 `ChargeItemDefinition.partOf` maps as Equivalent to R4B `ChargeItemDefinition.partOf` |
| ChargeItemDefinition.propertyGroup | ChargeItemDefinition.propertyGroup | Equivalent | R5 `ChargeItemDefinition.propertyGroup` maps as Equivalent to R4B `ChargeItemDefinition.propertyGroup` |
| ChargeItemDefinition.propertyGroup.applicability | ChargeItemDefinition.propertyGroup.applicability | Equivalent | R5 `ChargeItemDefinition.propertyGroup.applicability` maps as Equivalent to R4B `ChargeItemDefinition.propertyGroup.applicability` |
| ChargeItemDefinition.propertyGroup.extension | ChargeItemDefinition.propertyGroup.extension | SourceIsBroaderThanTarget | R5 `ChargeItemDefinition.propertyGroup.extension` maps as SourceIsBroaderThanTarget to R4B `ChargeItemDefinition.propertyGroup.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| ChargeItemDefinition.propertyGroup.id | ChargeItemDefinition.propertyGroup.id | Equivalent | R5 `ChargeItemDefinition.propertyGroup.id` maps as Equivalent to R4B `ChargeItemDefinition.propertyGroup.id` |
| ChargeItemDefinition.propertyGroup.modifierExtension | ChargeItemDefinition.propertyGroup.modifierExtension | SourceIsBroaderThanTarget | R5 `ChargeItemDefinition.propertyGroup.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `ChargeItemDefinition.propertyGroup.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| ChargeItemDefinition.propertyGroup.priceComponent | ChargeItemDefinition.propertyGroup.priceComponent | SourceIsBroaderThanTarget | R5 `ChargeItemDefinition.propertyGroup.priceComponent` maps as SourceIsBroaderThanTarget to R4B `ChargeItemDefinition.propertyGroup.priceComponent` - priceComponent has change due to type change: R5 type MonetaryComponent does not exist in R4B |
| ChargeItemDefinition.publisher | ChargeItemDefinition.publisher | Equivalent | R5 `ChargeItemDefinition.publisher` maps as Equivalent to R4B `ChargeItemDefinition.publisher` |
| ChargeItemDefinition.purpose | - | DoesNotExistInTarget | R5 `ChargeItemDefinition.purpose` does not appear in the target and has no mapping for `ChargeItemDefinition`. |
| ChargeItemDefinition.replaces | ChargeItemDefinition.replaces | Equivalent | R5 `ChargeItemDefinition.replaces` maps as Equivalent to R4B `ChargeItemDefinition.replaces` |
| ChargeItemDefinition.status | ChargeItemDefinition.status | Equivalent | R5 `ChargeItemDefinition.status` maps as Equivalent to R4B `ChargeItemDefinition.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|5.0.0 and http://hl7.org/fhir/ValueSet/publication-status|4.3.0 (Equivalent) |
| ChargeItemDefinition.text | ChargeItemDefinition.text | Equivalent | R5 `ChargeItemDefinition.text` maps as Equivalent to R4B `ChargeItemDefinition.text` |
| ChargeItemDefinition.title | ChargeItemDefinition.title | Equivalent | R5 `ChargeItemDefinition.title` maps as Equivalent to R4B `ChargeItemDefinition.title` |
| ChargeItemDefinition.url | ChargeItemDefinition.url | RelatedTo | R5 `ChargeItemDefinition.url` maps as RelatedTo to R4B `ChargeItemDefinition.url` - url made the element mandatory; url increased the minimum cardinality from 0 to 1 |
| ChargeItemDefinition.useContext | ChargeItemDefinition.useContext | Equivalent | R5 `ChargeItemDefinition.useContext` maps as Equivalent to R4B `ChargeItemDefinition.useContext` |
| ChargeItemDefinition.version | ChargeItemDefinition.version | Equivalent | R5 `ChargeItemDefinition.version` maps as Equivalent to R4B `ChargeItemDefinition.version` |
| ChargeItemDefinition.versionAlgorithm[x] | - | DoesNotExistInTarget | R5 `ChargeItemDefinition.versionAlgorithm[x]` does not appear in the target and has no mapping for `ChargeItemDefinition`. |

