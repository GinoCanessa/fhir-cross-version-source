Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | RegulatedAuthorization |  | Regulatory approval, clearance or licencing related to a regulated product, treatment, facility or activity that is cited in a guidance, regulation, rule or legislative act. An example is Market Authorization relating to a Medicinal Product. | 32 | 21 |
| Target | RegulatedAuthorization |  | Regulatory approval, clearance or licencing related to a regulated product, treatment, facility or activity that is cited in a guidance, regulation, rule or legislative act. An example is Market Authorization relating to a Medicinal Product. | 31 | 20 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 1 |
Equivalent | 4 |
RelatedTo | 27 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| RegulatedAuthorization | RegulatedAuthorization | Equivalent | R5 `RegulatedAuthorization` maps as Equivalent to R4B `RegulatedAuthorization` |
| RegulatedAuthorization.attachedDocument | - | DoesNotExistInTarget | R5 `RegulatedAuthorization.attachedDocument` does not appear in the target and has no mapping for `RegulatedAuthorization`. |
| RegulatedAuthorization.basis | RegulatedAuthorization.basis | Equivalent | R5 `RegulatedAuthorization.basis` maps as Equivalent to R4B `RegulatedAuthorization.basis` |
| RegulatedAuthorization.case | RegulatedAuthorization.case | Equivalent | R5 `RegulatedAuthorization.case` maps as Equivalent to R4B `RegulatedAuthorization.case` |
| RegulatedAuthorization.case.application | RegulatedAuthorization.case.application | Equivalent | R5 `RegulatedAuthorization.case.application` maps as Equivalent to R4B `RegulatedAuthorization.case.application` |
| RegulatedAuthorization.case.date[x] | RegulatedAuthorization.case.date[x] | Equivalent | R5 `RegulatedAuthorization.case.date[x]` maps as Equivalent to R4B `RegulatedAuthorization.case.date[x]` |
| RegulatedAuthorization.case.extension | RegulatedAuthorization.case.extension | SourceIsBroaderThanTarget | R5 `RegulatedAuthorization.case.extension` maps as SourceIsBroaderThanTarget to R4B `RegulatedAuthorization.case.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| RegulatedAuthorization.case.id | RegulatedAuthorization.case.id | Equivalent | R5 `RegulatedAuthorization.case.id` maps as Equivalent to R4B `RegulatedAuthorization.case.id` |
| RegulatedAuthorization.case.identifier | RegulatedAuthorization.case.identifier | Equivalent | R5 `RegulatedAuthorization.case.identifier` maps as Equivalent to R4B `RegulatedAuthorization.case.identifier` |
| RegulatedAuthorization.case.modifierExtension | RegulatedAuthorization.case.modifierExtension | SourceIsBroaderThanTarget | R5 `RegulatedAuthorization.case.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `RegulatedAuthorization.case.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| RegulatedAuthorization.case.status | RegulatedAuthorization.case.status | Equivalent | R5 `RegulatedAuthorization.case.status` maps as Equivalent to R4B `RegulatedAuthorization.case.status` |
| RegulatedAuthorization.case.type | RegulatedAuthorization.case.type | Equivalent | R5 `RegulatedAuthorization.case.type` maps as Equivalent to R4B `RegulatedAuthorization.case.type` |
| RegulatedAuthorization.contained | RegulatedAuthorization.contained | Equivalent | R5 `RegulatedAuthorization.contained` maps as Equivalent to R4B `RegulatedAuthorization.contained` |
| RegulatedAuthorization.description | RegulatedAuthorization.description | Equivalent | R5 `RegulatedAuthorization.description` maps as Equivalent to R4B `RegulatedAuthorization.description` |
| RegulatedAuthorization.extension | RegulatedAuthorization.extension | SourceIsBroaderThanTarget | R5 `RegulatedAuthorization.extension` maps as SourceIsBroaderThanTarget to R4B `RegulatedAuthorization.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| RegulatedAuthorization.holder | RegulatedAuthorization.holder | Equivalent | R5 `RegulatedAuthorization.holder` maps as Equivalent to R4B `RegulatedAuthorization.holder` |
| RegulatedAuthorization.id | RegulatedAuthorization.id | Equivalent | R5 `RegulatedAuthorization.id` maps as Equivalent to R4B `RegulatedAuthorization.id` |
| RegulatedAuthorization.identifier | RegulatedAuthorization.identifier | Equivalent | R5 `RegulatedAuthorization.identifier` maps as Equivalent to R4B `RegulatedAuthorization.identifier` |
| RegulatedAuthorization.implicitRules | RegulatedAuthorization.implicitRules | Equivalent | R5 `RegulatedAuthorization.implicitRules` maps as Equivalent to R4B `RegulatedAuthorization.implicitRules` |
| RegulatedAuthorization.indication | RegulatedAuthorization.indication | RelatedTo | R5 `RegulatedAuthorization.indication` maps as RelatedTo to R4B `RegulatedAuthorization.indication` - indication changed from array to scalar (max cardinality from * to 1) |
| RegulatedAuthorization.intendedUse | RegulatedAuthorization.intendedUse | Equivalent | R5 `RegulatedAuthorization.intendedUse` maps as Equivalent to R4B `RegulatedAuthorization.intendedUse` |
| RegulatedAuthorization.language | RegulatedAuthorization.language | RelatedTo | R5 `RegulatedAuthorization.language` maps as RelatedTo to R4B `RegulatedAuthorization.language` - language changed the binding strength from Required to Preferred |
| RegulatedAuthorization.meta | RegulatedAuthorization.meta | Equivalent | R5 `RegulatedAuthorization.meta` maps as Equivalent to R4B `RegulatedAuthorization.meta` |
| RegulatedAuthorization.modifierExtension | RegulatedAuthorization.modifierExtension | SourceIsBroaderThanTarget | R5 `RegulatedAuthorization.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `RegulatedAuthorization.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| RegulatedAuthorization.region | RegulatedAuthorization.region | Equivalent | R5 `RegulatedAuthorization.region` maps as Equivalent to R4B `RegulatedAuthorization.region` |
| RegulatedAuthorization.regulator | RegulatedAuthorization.regulator | Equivalent | R5 `RegulatedAuthorization.regulator` maps as Equivalent to R4B `RegulatedAuthorization.regulator` |
| RegulatedAuthorization.status | RegulatedAuthorization.status | Equivalent | R5 `RegulatedAuthorization.status` maps as Equivalent to R4B `RegulatedAuthorization.status` |
| RegulatedAuthorization.statusDate | RegulatedAuthorization.statusDate | Equivalent | R5 `RegulatedAuthorization.statusDate` maps as Equivalent to R4B `RegulatedAuthorization.statusDate` |
| RegulatedAuthorization.subject | RegulatedAuthorization.subject | SourceIsBroaderThanTarget | R5 `RegulatedAuthorization.subject` maps as SourceIsBroaderThanTarget to R4B `RegulatedAuthorization.subject` - subject has change due to type change: R5 `subject` `Reference` maps as SourceIsBroaderThanTarget for R4B `subject` |
| RegulatedAuthorization.text | RegulatedAuthorization.text | Equivalent | R5 `RegulatedAuthorization.text` maps as Equivalent to R4B `RegulatedAuthorization.text` |
| RegulatedAuthorization.type | RegulatedAuthorization.type | Equivalent | R5 `RegulatedAuthorization.type` maps as Equivalent to R4B `RegulatedAuthorization.type` |
| RegulatedAuthorization.validityPeriod | RegulatedAuthorization.validityPeriod | Equivalent | R5 `RegulatedAuthorization.validityPeriod` maps as Equivalent to R4B `RegulatedAuthorization.validityPeriod` |

