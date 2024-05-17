Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | RegulatedAuthorization |  | Regulatory approval, clearance or licencing related to a regulated product, treatment, facility or activity that is cited in a guidance, regulation, rule or legislative act. An example is Market Authorization relating to a Medicinal Product. | 31 | 20 |
| Target | RegulatedAuthorization |  | Regulatory approval, clearance or licencing related to a regulated product, treatment, facility or activity that is cited in a guidance, regulation, rule or legislative act. An example is Market Authorization relating to a Medicinal Product. | 32 | 21 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 27 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| RegulatedAuthorization | RegulatedAuthorization | Equivalent | R4B `RegulatedAuthorization` maps as Equivalent to R5 `RegulatedAuthorization` |
| RegulatedAuthorization.basis | RegulatedAuthorization.basis | Equivalent | R4B `RegulatedAuthorization.basis` maps as Equivalent to R5 `RegulatedAuthorization.basis` |
| RegulatedAuthorization.case | RegulatedAuthorization.case | Equivalent | R4B `RegulatedAuthorization.case` maps as Equivalent to R5 `RegulatedAuthorization.case` |
| RegulatedAuthorization.case.application | RegulatedAuthorization.case.application | Equivalent | R4B `RegulatedAuthorization.case.application` maps as Equivalent to R5 `RegulatedAuthorization.case.application` |
| RegulatedAuthorization.case.date[x] | RegulatedAuthorization.case.date[x] | Equivalent | R4B `RegulatedAuthorization.case.date[x]` maps as Equivalent to R5 `RegulatedAuthorization.case.date[x]` |
| RegulatedAuthorization.case.extension | RegulatedAuthorization.case.extension | RelatedTo | R4B `RegulatedAuthorization.case.extension` maps as RelatedTo to R5 `RegulatedAuthorization.case.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| RegulatedAuthorization.case.id | RegulatedAuthorization.case.id | Equivalent | R4B `RegulatedAuthorization.case.id` maps as Equivalent to R5 `RegulatedAuthorization.case.id` |
| RegulatedAuthorization.case.identifier | RegulatedAuthorization.case.identifier | Equivalent | R4B `RegulatedAuthorization.case.identifier` maps as Equivalent to R5 `RegulatedAuthorization.case.identifier` |
| RegulatedAuthorization.case.modifierExtension | RegulatedAuthorization.case.modifierExtension | RelatedTo | R4B `RegulatedAuthorization.case.modifierExtension` maps as RelatedTo to R5 `RegulatedAuthorization.case.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| RegulatedAuthorization.case.status | RegulatedAuthorization.case.status | Equivalent | R4B `RegulatedAuthorization.case.status` maps as Equivalent to R5 `RegulatedAuthorization.case.status` |
| RegulatedAuthorization.case.type | RegulatedAuthorization.case.type | Equivalent | R4B `RegulatedAuthorization.case.type` maps as Equivalent to R5 `RegulatedAuthorization.case.type` |
| RegulatedAuthorization.contained | RegulatedAuthorization.contained | Equivalent | R4B `RegulatedAuthorization.contained` maps as Equivalent to R5 `RegulatedAuthorization.contained` |
| RegulatedAuthorization.description | RegulatedAuthorization.description | Equivalent | R4B `RegulatedAuthorization.description` maps as Equivalent to R5 `RegulatedAuthorization.description` |
| RegulatedAuthorization.extension | RegulatedAuthorization.extension | RelatedTo | R4B `RegulatedAuthorization.extension` maps as RelatedTo to R5 `RegulatedAuthorization.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| RegulatedAuthorization.holder | RegulatedAuthorization.holder | Equivalent | R4B `RegulatedAuthorization.holder` maps as Equivalent to R5 `RegulatedAuthorization.holder` |
| RegulatedAuthorization.id | RegulatedAuthorization.id | Equivalent | R4B `RegulatedAuthorization.id` maps as Equivalent to R5 `RegulatedAuthorization.id` |
| RegulatedAuthorization.identifier | RegulatedAuthorization.identifier | Equivalent | R4B `RegulatedAuthorization.identifier` maps as Equivalent to R5 `RegulatedAuthorization.identifier` |
| RegulatedAuthorization.implicitRules | RegulatedAuthorization.implicitRules | Equivalent | R4B `RegulatedAuthorization.implicitRules` maps as Equivalent to R5 `RegulatedAuthorization.implicitRules` |
| RegulatedAuthorization.indication | RegulatedAuthorization.indication | RelatedTo | R4B `RegulatedAuthorization.indication` maps as RelatedTo to R5 `RegulatedAuthorization.indication` - indication changed from scalar to array (max cardinality from 1 to *) |
| RegulatedAuthorization.intendedUse | RegulatedAuthorization.intendedUse | Equivalent | R4B `RegulatedAuthorization.intendedUse` maps as Equivalent to R5 `RegulatedAuthorization.intendedUse` |
| RegulatedAuthorization.language | RegulatedAuthorization.language | RelatedTo | R4B `RegulatedAuthorization.language` maps as RelatedTo to R5 `RegulatedAuthorization.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| RegulatedAuthorization.meta | RegulatedAuthorization.meta | Equivalent | R4B `RegulatedAuthorization.meta` maps as Equivalent to R5 `RegulatedAuthorization.meta` |
| RegulatedAuthorization.modifierExtension | RegulatedAuthorization.modifierExtension | RelatedTo | R4B `RegulatedAuthorization.modifierExtension` maps as RelatedTo to R5 `RegulatedAuthorization.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| RegulatedAuthorization.region | RegulatedAuthorization.region | Equivalent | R4B `RegulatedAuthorization.region` maps as Equivalent to R5 `RegulatedAuthorization.region` |
| RegulatedAuthorization.regulator | RegulatedAuthorization.regulator | Equivalent | R4B `RegulatedAuthorization.regulator` maps as Equivalent to R5 `RegulatedAuthorization.regulator` |
| RegulatedAuthorization.status | RegulatedAuthorization.status | Equivalent | R4B `RegulatedAuthorization.status` maps as Equivalent to R5 `RegulatedAuthorization.status` |
| RegulatedAuthorization.statusDate | RegulatedAuthorization.statusDate | Equivalent | R4B `RegulatedAuthorization.statusDate` maps as Equivalent to R5 `RegulatedAuthorization.statusDate` |
| RegulatedAuthorization.subject | RegulatedAuthorization.subject | SourceIsNarrowerThanTarget | R4B `RegulatedAuthorization.subject` maps as SourceIsNarrowerThanTarget to R5 `RegulatedAuthorization.subject` - subject has change due to type change: R4B `subject` `Reference` maps as SourceIsNarrowerThanTarget for R5 `subject` |
| RegulatedAuthorization.text | RegulatedAuthorization.text | Equivalent | R4B `RegulatedAuthorization.text` maps as Equivalent to R5 `RegulatedAuthorization.text` |
| RegulatedAuthorization.type | RegulatedAuthorization.type | Equivalent | R4B `RegulatedAuthorization.type` maps as Equivalent to R5 `RegulatedAuthorization.type` |
| RegulatedAuthorization.validityPeriod | RegulatedAuthorization.validityPeriod | Equivalent | R4B `RegulatedAuthorization.validityPeriod` maps as Equivalent to R5 `RegulatedAuthorization.validityPeriod` |

