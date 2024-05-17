Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Consent |  | A record of a healthcare consumer’s  choices  or choices made on their behalf by a third party, which permits or denies identified recipient(s) or recipient role(s) to perform one or more actions within a given policy context, for specific purposes and periods of time. | 65 | 42 |
| Target | Consent |  | A record of a healthcare consumer’s  choices, which permits or denies identified recipient(s) or recipient role(s) to perform one or more actions within a given policy context, for specific purposes and periods of time. | 57 | 34 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 23 |
Equivalent | 4 |
RelatedTo | 38 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Consent | Consent | Equivalent | R5 `Consent` maps as Equivalent to R4B `Consent` |
| Consent.category | Consent.category | RelatedTo | R5 `Consent.category` maps as RelatedTo to R4B `Consent.category` - category made the element mandatory; category increased the minimum cardinality from 0 to 1; category changed the binding strength from Example to Extensible |
| Consent.contained | Consent.contained | Equivalent | R5 `Consent.contained` maps as Equivalent to R4B `Consent.contained` |
| Consent.controller | - | DoesNotExistInTarget | R5 `Consent.controller` does not appear in the target and has no mapping for `Consent`. |
| Consent.date | - | DoesNotExistInTarget | R5 `Consent.date` does not appear in the target and has no mapping for `Consent`. |
| Consent.decision | - | DoesNotExistInTarget | R5 `Consent.decision` does not appear in the target and has no mapping for `Consent`. |
| Consent.extension | Consent.extension | SourceIsBroaderThanTarget | R5 `Consent.extension` maps as SourceIsBroaderThanTarget to R4B `Consent.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Consent.grantee | - | DoesNotExistInTarget | R5 `Consent.grantee` does not appear in the target and has no mapping for `Consent`. |
| Consent.grantor | - | DoesNotExistInTarget | R5 `Consent.grantor` does not appear in the target and has no mapping for `Consent`. |
| Consent.id | Consent.id | Equivalent | R5 `Consent.id` maps as Equivalent to R4B `Consent.id` |
| Consent.identifier | Consent.identifier | Equivalent | R5 `Consent.identifier` maps as Equivalent to R4B `Consent.identifier` |
| Consent.implicitRules | Consent.implicitRules | Equivalent | R5 `Consent.implicitRules` maps as Equivalent to R4B `Consent.implicitRules` |
| Consent.language | Consent.language | RelatedTo | R5 `Consent.language` maps as RelatedTo to R4B `Consent.language` - language changed the binding strength from Required to Preferred |
| Consent.manager | - | DoesNotExistInTarget | R5 `Consent.manager` does not appear in the target and has no mapping for `Consent`. |
| Consent.meta | Consent.meta | Equivalent | R5 `Consent.meta` maps as Equivalent to R4B `Consent.meta` |
| Consent.modifierExtension | Consent.modifierExtension | SourceIsBroaderThanTarget | R5 `Consent.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Consent.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Consent.period | - | DoesNotExistInTarget | R5 `Consent.period` does not appear in the target and has no mapping for `Consent`. |
| Consent.policyBasis | - | DoesNotExistInTarget | R5 `Consent.policyBasis` does not appear in the target and has no mapping for `Consent`. |
| Consent.policyBasis.extension | - | DoesNotExistInTarget | R5 `Consent.policyBasis.extension` does not appear in the target and has no mapping for `Consent`. |
| Consent.policyBasis.id | - | DoesNotExistInTarget | R5 `Consent.policyBasis.id` does not appear in the target and has no mapping for `Consent`. |
| Consent.policyBasis.modifierExtension | - | DoesNotExistInTarget | R5 `Consent.policyBasis.modifierExtension` does not appear in the target and has no mapping for `Consent`. |
| Consent.policyBasis.reference | - | DoesNotExistInTarget | R5 `Consent.policyBasis.reference` does not appear in the target and has no mapping for `Consent`. |
| Consent.policyBasis.url | - | DoesNotExistInTarget | R5 `Consent.policyBasis.url` does not appear in the target and has no mapping for `Consent`. |
| Consent.policyText | - | DoesNotExistInTarget | R5 `Consent.policyText` does not appear in the target and has no mapping for `Consent`. |
| Consent.provision | Consent.provision | RelatedTo | R5 `Consent.provision` maps as RelatedTo to R4B `Consent.provision` - provision changed from array to scalar (max cardinality from * to 1) |
| Consent.provision.action | Consent.provision.action | Equivalent | R5 `Consent.provision.action` maps as Equivalent to R4B `Consent.provision.action` |
| Consent.provision.actor | Consent.provision.actor | Equivalent | R5 `Consent.provision.actor` maps as Equivalent to R4B `Consent.provision.actor` |
| Consent.provision.actor.extension | Consent.provision.actor.extension | SourceIsBroaderThanTarget | R5 `Consent.provision.actor.extension` maps as SourceIsBroaderThanTarget to R4B `Consent.provision.actor.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Consent.provision.actor.id | Consent.provision.actor.id | Equivalent | R5 `Consent.provision.actor.id` maps as Equivalent to R4B `Consent.provision.actor.id` |
| Consent.provision.actor.modifierExtension | Consent.provision.actor.modifierExtension | SourceIsBroaderThanTarget | R5 `Consent.provision.actor.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Consent.provision.actor.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Consent.provision.actor.reference | Consent.provision.actor.reference | RelatedTo | R5 `Consent.provision.actor.reference` maps as RelatedTo to R4B `Consent.provision.actor.reference` - reference made the element mandatory; reference increased the minimum cardinality from 0 to 1 |
| Consent.provision.actor.role | Consent.provision.actor.role | RelatedTo | R5 `Consent.provision.actor.role` maps as RelatedTo to R4B `Consent.provision.actor.role` - role made the element mandatory; role increased the minimum cardinality from 0 to 1 |
| Consent.provision.code | Consent.provision.code | Equivalent | R5 `Consent.provision.code` maps as Equivalent to R4B `Consent.provision.code` |
| Consent.provision.data | Consent.provision.data | Equivalent | R5 `Consent.provision.data` maps as Equivalent to R4B `Consent.provision.data` |
| Consent.provision.data.extension | Consent.provision.data.extension | SourceIsBroaderThanTarget | R5 `Consent.provision.data.extension` maps as SourceIsBroaderThanTarget to R4B `Consent.provision.data.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Consent.provision.data.id | Consent.provision.data.id | Equivalent | R5 `Consent.provision.data.id` maps as Equivalent to R4B `Consent.provision.data.id` |
| Consent.provision.data.meaning | Consent.provision.data.meaning | Equivalent | R5 `Consent.provision.data.meaning` maps as Equivalent to R4B `Consent.provision.data.meaning` - meaning has compatible required binding for code type: http://hl7.org/fhir/ValueSet/consent-data-meaning|5.0.0 and http://hl7.org/fhir/ValueSet/consent-data-meaning|4.3.0 (Equivalent) |
| Consent.provision.data.modifierExtension | Consent.provision.data.modifierExtension | SourceIsBroaderThanTarget | R5 `Consent.provision.data.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Consent.provision.data.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Consent.provision.data.reference | Consent.provision.data.reference | Equivalent | R5 `Consent.provision.data.reference` maps as Equivalent to R4B `Consent.provision.data.reference` |
| Consent.provision.dataPeriod | Consent.provision.dataPeriod | Equivalent | R5 `Consent.provision.dataPeriod` maps as Equivalent to R4B `Consent.provision.dataPeriod` |
| Consent.provision.documentType | - | DoesNotExistInTarget | R5 `Consent.provision.documentType` does not appear in the target and has no mapping for `Consent`. |
| Consent.provision.expression | - | DoesNotExistInTarget | R5 `Consent.provision.expression` does not appear in the target and has no mapping for `Consent`. |
| Consent.provision.extension | Consent.provision.extension | SourceIsBroaderThanTarget | R5 `Consent.provision.extension` maps as SourceIsBroaderThanTarget to R4B `Consent.provision.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Consent.provision.id | Consent.provision.id | Equivalent | R5 `Consent.provision.id` maps as Equivalent to R4B `Consent.provision.id` |
| Consent.provision.modifierExtension | Consent.provision.modifierExtension | SourceIsBroaderThanTarget | R5 `Consent.provision.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Consent.provision.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Consent.provision.period | Consent.provision.period | Equivalent | R5 `Consent.provision.period` maps as Equivalent to R4B `Consent.provision.period` |
| Consent.provision.provision | Consent.provision.provision | Equivalent | R5 `Consent.provision.provision` maps as Equivalent to R4B `Consent.provision.provision` |
| Consent.provision.purpose | Consent.provision.purpose | Equivalent | R5 `Consent.provision.purpose` maps as Equivalent to R4B `Consent.provision.purpose` |
| Consent.provision.resourceType | - | DoesNotExistInTarget | R5 `Consent.provision.resourceType` does not appear in the target and has no mapping for `Consent`. |
| Consent.provision.securityLabel | Consent.provision.securityLabel | RelatedTo | R5 `Consent.provision.securityLabel` maps as RelatedTo to R4B `Consent.provision.securityLabel` - securityLabel changed the binding strength from Example to Extensible |
| Consent.regulatoryBasis | - | DoesNotExistInTarget | R5 `Consent.regulatoryBasis` does not appear in the target and has no mapping for `Consent`. |
| Consent.sourceAttachment | - | DoesNotExistInTarget | R5 `Consent.sourceAttachment` does not appear in the target and has no mapping for `Consent`. |
| Consent.sourceReference | - | DoesNotExistInTarget | R5 `Consent.sourceReference` does not appear in the target and has no mapping for `Consent`. |
| Consent.status | Consent.status | Equivalent | R5 `Consent.status` maps as Equivalent to R4B `Consent.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/consent-state-codes|5.0.0 and http://hl7.org/fhir/ValueSet/consent-state-codes|4.3.0 (Equivalent) |
| Consent.subject | - | DoesNotExistInTarget | R5 `Consent.subject` does not appear in the target and has no mapping for `Consent`. |
| Consent.text | Consent.text | Equivalent | R5 `Consent.text` maps as Equivalent to R4B `Consent.text` |
| Consent.verification | Consent.verification | Equivalent | R5 `Consent.verification` maps as Equivalent to R4B `Consent.verification` |
| Consent.verification.extension | Consent.verification.extension | SourceIsBroaderThanTarget | R5 `Consent.verification.extension` maps as SourceIsBroaderThanTarget to R4B `Consent.verification.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Consent.verification.id | Consent.verification.id | Equivalent | R5 `Consent.verification.id` maps as Equivalent to R4B `Consent.verification.id` |
| Consent.verification.modifierExtension | Consent.verification.modifierExtension | SourceIsBroaderThanTarget | R5 `Consent.verification.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Consent.verification.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Consent.verification.verificationDate | Consent.verification.verificationDate | RelatedTo | R5 `Consent.verification.verificationDate` maps as RelatedTo to R4B `Consent.verification.verificationDate` - verificationDate changed from array to scalar (max cardinality from * to 1) |
| Consent.verification.verificationType | - | DoesNotExistInTarget | R5 `Consent.verification.verificationType` does not appear in the target and has no mapping for `Consent`. |
| Consent.verification.verified | Consent.verification.verified | Equivalent | R5 `Consent.verification.verified` maps as Equivalent to R4B `Consent.verification.verified` |
| Consent.verification.verifiedBy | - | DoesNotExistInTarget | R5 `Consent.verification.verifiedBy` does not appear in the target and has no mapping for `Consent`. |
| Consent.verification.verifiedWith | Consent.verification.verifiedWith | Equivalent | R5 `Consent.verification.verifiedWith` maps as Equivalent to R4B `Consent.verification.verifiedWith` |

