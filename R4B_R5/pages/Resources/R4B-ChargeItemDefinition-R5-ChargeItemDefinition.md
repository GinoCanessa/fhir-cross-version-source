Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | ChargeItemDefinition |  | The ChargeItemDefinition resource provides the properties that apply to the (billing) codes necessary to calculate costs and prices. The properties may differ largely depending on type and realm, therefore this resource gives only a rough structure and requires profiling for each type of billing code system. | 50 | 33 |
| Target | ChargeItemDefinition |  | The ChargeItemDefinition resource provides the properties that apply to the (billing) codes necessary to calculate costs and prices. The properties may differ largely depending on type and realm, therefore this resource gives only a rough structure and requires profiling for each type of billing code system. | 46 | 32 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 11 |
Equivalent | 4 |
RelatedTo | 35 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| ChargeItemDefinition | ChargeItemDefinition | Equivalent | R4B `ChargeItemDefinition` maps as Equivalent to R5 `ChargeItemDefinition` |
| ChargeItemDefinition.applicability | ChargeItemDefinition.applicability | Equivalent | R4B `ChargeItemDefinition.applicability` maps as Equivalent to R5 `ChargeItemDefinition.applicability` |
| ChargeItemDefinition.applicability.description | - | DoesNotExistInTarget | R4B `ChargeItemDefinition.applicability.description` does not appear in the target and has no mapping for `ChargeItemDefinition`. |
| ChargeItemDefinition.applicability.expression | - | DoesNotExistInTarget | R4B `ChargeItemDefinition.applicability.expression` does not appear in the target and has no mapping for `ChargeItemDefinition`. |
| ChargeItemDefinition.applicability.extension | ChargeItemDefinition.applicability.extension | RelatedTo | R4B `ChargeItemDefinition.applicability.extension` maps as RelatedTo to R5 `ChargeItemDefinition.applicability.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ChargeItemDefinition.applicability.id | ChargeItemDefinition.applicability.id | Equivalent | R4B `ChargeItemDefinition.applicability.id` maps as Equivalent to R5 `ChargeItemDefinition.applicability.id` |
| ChargeItemDefinition.applicability.language | - | DoesNotExistInTarget | R4B `ChargeItemDefinition.applicability.language` does not appear in the target and has no mapping for `ChargeItemDefinition`. |
| ChargeItemDefinition.applicability.modifierExtension | ChargeItemDefinition.applicability.modifierExtension | RelatedTo | R4B `ChargeItemDefinition.applicability.modifierExtension` maps as RelatedTo to R5 `ChargeItemDefinition.applicability.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ChargeItemDefinition.approvalDate | ChargeItemDefinition.approvalDate | Equivalent | R4B `ChargeItemDefinition.approvalDate` maps as Equivalent to R5 `ChargeItemDefinition.approvalDate` |
| ChargeItemDefinition.code | ChargeItemDefinition.code | Equivalent | R4B `ChargeItemDefinition.code` maps as Equivalent to R5 `ChargeItemDefinition.code` |
| ChargeItemDefinition.contact | ChargeItemDefinition.contact | Equivalent | R4B `ChargeItemDefinition.contact` maps as Equivalent to R5 `ChargeItemDefinition.contact` |
| ChargeItemDefinition.contained | ChargeItemDefinition.contained | Equivalent | R4B `ChargeItemDefinition.contained` maps as Equivalent to R5 `ChargeItemDefinition.contained` |
| ChargeItemDefinition.copyright | ChargeItemDefinition.copyright | Equivalent | R4B `ChargeItemDefinition.copyright` maps as Equivalent to R5 `ChargeItemDefinition.copyright` |
| ChargeItemDefinition.date | ChargeItemDefinition.date | Equivalent | R4B `ChargeItemDefinition.date` maps as Equivalent to R5 `ChargeItemDefinition.date` |
| ChargeItemDefinition.derivedFromUri | ChargeItemDefinition.derivedFromUri | Equivalent | R4B `ChargeItemDefinition.derivedFromUri` maps as Equivalent to R5 `ChargeItemDefinition.derivedFromUri` |
| ChargeItemDefinition.description | ChargeItemDefinition.description | Equivalent | R4B `ChargeItemDefinition.description` maps as Equivalent to R5 `ChargeItemDefinition.description` |
| ChargeItemDefinition.effectivePeriod | - | DoesNotExistInTarget | R4B `ChargeItemDefinition.effectivePeriod` does not appear in the target and has no mapping for `ChargeItemDefinition`. |
| ChargeItemDefinition.experimental | ChargeItemDefinition.experimental | Equivalent | R4B `ChargeItemDefinition.experimental` maps as Equivalent to R5 `ChargeItemDefinition.experimental` |
| ChargeItemDefinition.extension | ChargeItemDefinition.extension | RelatedTo | R4B `ChargeItemDefinition.extension` maps as RelatedTo to R5 `ChargeItemDefinition.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ChargeItemDefinition.id | ChargeItemDefinition.id | Equivalent | R4B `ChargeItemDefinition.id` maps as Equivalent to R5 `ChargeItemDefinition.id` |
| ChargeItemDefinition.identifier | ChargeItemDefinition.identifier | Equivalent | R4B `ChargeItemDefinition.identifier` maps as Equivalent to R5 `ChargeItemDefinition.identifier` |
| ChargeItemDefinition.implicitRules | ChargeItemDefinition.implicitRules | Equivalent | R4B `ChargeItemDefinition.implicitRules` maps as Equivalent to R5 `ChargeItemDefinition.implicitRules` |
| ChargeItemDefinition.instance | ChargeItemDefinition.instance | SourceIsNarrowerThanTarget | R4B `ChargeItemDefinition.instance` maps as SourceIsNarrowerThanTarget to R5 `ChargeItemDefinition.instance` - instance has change due to type change: R4B `instance` `Reference` maps as SourceIsNarrowerThanTarget for R5 `instance` |
| ChargeItemDefinition.jurisdiction | ChargeItemDefinition.jurisdiction | Equivalent | R4B `ChargeItemDefinition.jurisdiction` maps as Equivalent to R5 `ChargeItemDefinition.jurisdiction` |
| ChargeItemDefinition.language | ChargeItemDefinition.language | RelatedTo | R4B `ChargeItemDefinition.language` maps as RelatedTo to R5 `ChargeItemDefinition.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| ChargeItemDefinition.lastReviewDate | ChargeItemDefinition.lastReviewDate | Equivalent | R4B `ChargeItemDefinition.lastReviewDate` maps as Equivalent to R5 `ChargeItemDefinition.lastReviewDate` |
| ChargeItemDefinition.meta | ChargeItemDefinition.meta | Equivalent | R4B `ChargeItemDefinition.meta` maps as Equivalent to R5 `ChargeItemDefinition.meta` |
| ChargeItemDefinition.modifierExtension | ChargeItemDefinition.modifierExtension | RelatedTo | R4B `ChargeItemDefinition.modifierExtension` maps as RelatedTo to R5 `ChargeItemDefinition.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ChargeItemDefinition.partOf | ChargeItemDefinition.partOf | Equivalent | R4B `ChargeItemDefinition.partOf` maps as Equivalent to R5 `ChargeItemDefinition.partOf` |
| ChargeItemDefinition.propertyGroup | ChargeItemDefinition.propertyGroup | Equivalent | R4B `ChargeItemDefinition.propertyGroup` maps as Equivalent to R5 `ChargeItemDefinition.propertyGroup` |
| ChargeItemDefinition.propertyGroup.applicability | ChargeItemDefinition.propertyGroup.applicability | Equivalent | R4B `ChargeItemDefinition.propertyGroup.applicability` maps as Equivalent to R5 `ChargeItemDefinition.propertyGroup.applicability` |
| ChargeItemDefinition.propertyGroup.extension | ChargeItemDefinition.propertyGroup.extension | RelatedTo | R4B `ChargeItemDefinition.propertyGroup.extension` maps as RelatedTo to R5 `ChargeItemDefinition.propertyGroup.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ChargeItemDefinition.propertyGroup.id | ChargeItemDefinition.propertyGroup.id | Equivalent | R4B `ChargeItemDefinition.propertyGroup.id` maps as Equivalent to R5 `ChargeItemDefinition.propertyGroup.id` |
| ChargeItemDefinition.propertyGroup.modifierExtension | ChargeItemDefinition.propertyGroup.modifierExtension | RelatedTo | R4B `ChargeItemDefinition.propertyGroup.modifierExtension` maps as RelatedTo to R5 `ChargeItemDefinition.propertyGroup.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ChargeItemDefinition.propertyGroup.priceComponent | ChargeItemDefinition.propertyGroup.priceComponent | SourceIsBroaderThanTarget | R4B `ChargeItemDefinition.propertyGroup.priceComponent` maps as SourceIsBroaderThanTarget to R5 `ChargeItemDefinition.propertyGroup.priceComponent` - priceComponent has change due to type change: R4B priceComponent BackboneElement has no equivalent or mapped type in R5 priceComponent |
| ChargeItemDefinition.propertyGroup.priceComponent.amount | - | DoesNotExistInTarget | R4B `ChargeItemDefinition.propertyGroup.priceComponent.amount` does not appear in the target and has no mapping for `ChargeItemDefinition`. |
| ChargeItemDefinition.propertyGroup.priceComponent.code | - | DoesNotExistInTarget | R4B `ChargeItemDefinition.propertyGroup.priceComponent.code` does not appear in the target and has no mapping for `ChargeItemDefinition`. |
| ChargeItemDefinition.propertyGroup.priceComponent.extension | - | DoesNotExistInTarget | R4B `ChargeItemDefinition.propertyGroup.priceComponent.extension` does not appear in the target and has no mapping for `ChargeItemDefinition`. |
| ChargeItemDefinition.propertyGroup.priceComponent.factor | - | DoesNotExistInTarget | R4B `ChargeItemDefinition.propertyGroup.priceComponent.factor` does not appear in the target and has no mapping for `ChargeItemDefinition`. |
| ChargeItemDefinition.propertyGroup.priceComponent.id | - | DoesNotExistInTarget | R4B `ChargeItemDefinition.propertyGroup.priceComponent.id` does not appear in the target and has no mapping for `ChargeItemDefinition`. |
| ChargeItemDefinition.propertyGroup.priceComponent.modifierExtension | - | DoesNotExistInTarget | R4B `ChargeItemDefinition.propertyGroup.priceComponent.modifierExtension` does not appear in the target and has no mapping for `ChargeItemDefinition`. |
| ChargeItemDefinition.propertyGroup.priceComponent.type | - | DoesNotExistInTarget | R4B `ChargeItemDefinition.propertyGroup.priceComponent.type` does not appear in the target and has no mapping for `ChargeItemDefinition`. |
| ChargeItemDefinition.publisher | ChargeItemDefinition.publisher | Equivalent | R4B `ChargeItemDefinition.publisher` maps as Equivalent to R5 `ChargeItemDefinition.publisher` |
| ChargeItemDefinition.replaces | ChargeItemDefinition.replaces | Equivalent | R4B `ChargeItemDefinition.replaces` maps as Equivalent to R5 `ChargeItemDefinition.replaces` |
| ChargeItemDefinition.status | ChargeItemDefinition.status | Equivalent | R4B `ChargeItemDefinition.status` maps as Equivalent to R5 `ChargeItemDefinition.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|4.3.0 and http://hl7.org/fhir/ValueSet/publication-status|5.0.0 (Equivalent) |
| ChargeItemDefinition.text | ChargeItemDefinition.text | Equivalent | R4B `ChargeItemDefinition.text` maps as Equivalent to R5 `ChargeItemDefinition.text` |
| ChargeItemDefinition.title | ChargeItemDefinition.title | Equivalent | R4B `ChargeItemDefinition.title` maps as Equivalent to R5 `ChargeItemDefinition.title` |
| ChargeItemDefinition.url | ChargeItemDefinition.url | Equivalent | R4B `ChargeItemDefinition.url` maps as Equivalent to R5 `ChargeItemDefinition.url` |
| ChargeItemDefinition.useContext | ChargeItemDefinition.useContext | Equivalent | R4B `ChargeItemDefinition.useContext` maps as Equivalent to R5 `ChargeItemDefinition.useContext` |
| ChargeItemDefinition.version | ChargeItemDefinition.version | Equivalent | R4B `ChargeItemDefinition.version` maps as Equivalent to R5 `ChargeItemDefinition.version` |

