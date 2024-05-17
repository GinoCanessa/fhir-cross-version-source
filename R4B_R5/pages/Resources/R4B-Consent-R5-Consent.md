Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Consent |  | A record of a healthcare consumer’s  choices, which permits or denies identified recipient(s) or recipient role(s) to perform one or more actions within a given policy context, for specific purposes and periods of time. | 57 | 34 |
| Target | Consent |  | A record of a healthcare consumer’s  choices  or choices made on their behalf by a third party, which permits or denies identified recipient(s) or recipient role(s) to perform one or more actions within a given policy context, for specific purposes and periods of time. | 65 | 42 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 15 |
Equivalent | 4 |
RelatedTo | 38 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Consent | Consent | Equivalent | R4B `Consent` maps as Equivalent to R5 `Consent` |
| Consent.category | Consent.category | RelatedTo | R4B `Consent.category` maps as RelatedTo to R5 `Consent.category` - category changed the binding strength from Extensible to Example |
| Consent.contained | Consent.contained | Equivalent | R4B `Consent.contained` maps as Equivalent to R5 `Consent.contained` |
| Consent.dateTime | - | DoesNotExistInTarget | R4B `Consent.dateTime` does not appear in the target and has no mapping for `Consent`. |
| Consent.extension | Consent.extension | RelatedTo | R4B `Consent.extension` maps as RelatedTo to R5 `Consent.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Consent.id | Consent.id | Equivalent | R4B `Consent.id` maps as Equivalent to R5 `Consent.id` |
| Consent.identifier | Consent.identifier | Equivalent | R4B `Consent.identifier` maps as Equivalent to R5 `Consent.identifier` |
| Consent.implicitRules | Consent.implicitRules | Equivalent | R4B `Consent.implicitRules` maps as Equivalent to R5 `Consent.implicitRules` |
| Consent.language | Consent.language | RelatedTo | R4B `Consent.language` maps as RelatedTo to R5 `Consent.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Consent.meta | Consent.meta | Equivalent | R4B `Consent.meta` maps as Equivalent to R5 `Consent.meta` |
| Consent.modifierExtension | Consent.modifierExtension | RelatedTo | R4B `Consent.modifierExtension` maps as RelatedTo to R5 `Consent.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Consent.organization | - | DoesNotExistInTarget | R4B `Consent.organization` does not appear in the target and has no mapping for `Consent`. |
| Consent.patient | - | DoesNotExistInTarget | R4B `Consent.patient` does not appear in the target and has no mapping for `Consent`. |
| Consent.performer | - | DoesNotExistInTarget | R4B `Consent.performer` does not appear in the target and has no mapping for `Consent`. |
| Consent.policy | - | DoesNotExistInTarget | R4B `Consent.policy` does not appear in the target and has no mapping for `Consent`. |
| Consent.policy.authority | - | DoesNotExistInTarget | R4B `Consent.policy.authority` does not appear in the target and has no mapping for `Consent`. |
| Consent.policy.extension | - | DoesNotExistInTarget | R4B `Consent.policy.extension` does not appear in the target and has no mapping for `Consent`. |
| Consent.policy.id | - | DoesNotExistInTarget | R4B `Consent.policy.id` does not appear in the target and has no mapping for `Consent`. |
| Consent.policy.modifierExtension | - | DoesNotExistInTarget | R4B `Consent.policy.modifierExtension` does not appear in the target and has no mapping for `Consent`. |
| Consent.policy.uri | - | DoesNotExistInTarget | R4B `Consent.policy.uri` does not appear in the target and has no mapping for `Consent`. |
| Consent.policyRule | - | DoesNotExistInTarget | R4B `Consent.policyRule` does not appear in the target and has no mapping for `Consent`. |
| Consent.provision | Consent.provision | RelatedTo | R4B `Consent.provision` maps as RelatedTo to R5 `Consent.provision` - provision changed from scalar to array (max cardinality from 1 to *) |
| Consent.provision.action | Consent.provision.action | Equivalent | R4B `Consent.provision.action` maps as Equivalent to R5 `Consent.provision.action` |
| Consent.provision.actor | Consent.provision.actor | Equivalent | R4B `Consent.provision.actor` maps as Equivalent to R5 `Consent.provision.actor` |
| Consent.provision.actor.extension | Consent.provision.actor.extension | RelatedTo | R4B `Consent.provision.actor.extension` maps as RelatedTo to R5 `Consent.provision.actor.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Consent.provision.actor.id | Consent.provision.actor.id | Equivalent | R4B `Consent.provision.actor.id` maps as Equivalent to R5 `Consent.provision.actor.id` |
| Consent.provision.actor.modifierExtension | Consent.provision.actor.modifierExtension | RelatedTo | R4B `Consent.provision.actor.modifierExtension` maps as RelatedTo to R5 `Consent.provision.actor.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Consent.provision.actor.reference | Consent.provision.actor.reference | Equivalent | R4B `Consent.provision.actor.reference` maps as Equivalent to R5 `Consent.provision.actor.reference` |
| Consent.provision.actor.role | Consent.provision.actor.role | Equivalent | R4B `Consent.provision.actor.role` maps as Equivalent to R5 `Consent.provision.actor.role` |
| Consent.provision.class | - | DoesNotExistInTarget | R4B `Consent.provision.class` does not appear in the target and has no mapping for `Consent`. |
| Consent.provision.code | Consent.provision.code | Equivalent | R4B `Consent.provision.code` maps as Equivalent to R5 `Consent.provision.code` |
| Consent.provision.data | Consent.provision.data | Equivalent | R4B `Consent.provision.data` maps as Equivalent to R5 `Consent.provision.data` |
| Consent.provision.data.extension | Consent.provision.data.extension | RelatedTo | R4B `Consent.provision.data.extension` maps as RelatedTo to R5 `Consent.provision.data.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Consent.provision.data.id | Consent.provision.data.id | Equivalent | R4B `Consent.provision.data.id` maps as Equivalent to R5 `Consent.provision.data.id` |
| Consent.provision.data.meaning | Consent.provision.data.meaning | Equivalent | R4B `Consent.provision.data.meaning` maps as Equivalent to R5 `Consent.provision.data.meaning` - meaning has compatible required binding for code type: http://hl7.org/fhir/ValueSet/consent-data-meaning|4.3.0 and http://hl7.org/fhir/ValueSet/consent-data-meaning|5.0.0 (Equivalent) |
| Consent.provision.data.modifierExtension | Consent.provision.data.modifierExtension | RelatedTo | R4B `Consent.provision.data.modifierExtension` maps as RelatedTo to R5 `Consent.provision.data.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Consent.provision.data.reference | Consent.provision.data.reference | Equivalent | R4B `Consent.provision.data.reference` maps as Equivalent to R5 `Consent.provision.data.reference` |
| Consent.provision.dataPeriod | Consent.provision.dataPeriod | Equivalent | R4B `Consent.provision.dataPeriod` maps as Equivalent to R5 `Consent.provision.dataPeriod` |
| Consent.provision.extension | Consent.provision.extension | RelatedTo | R4B `Consent.provision.extension` maps as RelatedTo to R5 `Consent.provision.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Consent.provision.id | Consent.provision.id | Equivalent | R4B `Consent.provision.id` maps as Equivalent to R5 `Consent.provision.id` |
| Consent.provision.modifierExtension | Consent.provision.modifierExtension | RelatedTo | R4B `Consent.provision.modifierExtension` maps as RelatedTo to R5 `Consent.provision.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Consent.provision.period | Consent.provision.period | Equivalent | R4B `Consent.provision.period` maps as Equivalent to R5 `Consent.provision.period` |
| Consent.provision.provision | Consent.provision.provision | Equivalent | R4B `Consent.provision.provision` maps as Equivalent to R5 `Consent.provision.provision` |
| Consent.provision.purpose | Consent.provision.purpose | Equivalent | R4B `Consent.provision.purpose` maps as Equivalent to R5 `Consent.provision.purpose` |
| Consent.provision.securityLabel | Consent.provision.securityLabel | RelatedTo | R4B `Consent.provision.securityLabel` maps as RelatedTo to R5 `Consent.provision.securityLabel` - securityLabel changed the binding strength from Extensible to Example |
| Consent.provision.type | - | DoesNotExistInTarget | R4B `Consent.provision.type` does not appear in the target and has no mapping for `Consent`. |
| Consent.scope | - | DoesNotExistInTarget | R4B `Consent.scope` does not appear in the target and has no mapping for `Consent`. |
| Consent.source[x] | - | DoesNotExistInTarget | R4B `Consent.source[x]` does not appear in the target and has no mapping for `Consent`. |
| Consent.status | Consent.status | Equivalent | R4B `Consent.status` maps as Equivalent to R5 `Consent.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/consent-state-codes|4.3.0 and http://hl7.org/fhir/ValueSet/consent-state-codes|5.0.0 (Equivalent) |
| Consent.text | Consent.text | Equivalent | R4B `Consent.text` maps as Equivalent to R5 `Consent.text` |
| Consent.verification | Consent.verification | Equivalent | R4B `Consent.verification` maps as Equivalent to R5 `Consent.verification` |
| Consent.verification.extension | Consent.verification.extension | RelatedTo | R4B `Consent.verification.extension` maps as RelatedTo to R5 `Consent.verification.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Consent.verification.id | Consent.verification.id | Equivalent | R4B `Consent.verification.id` maps as Equivalent to R5 `Consent.verification.id` |
| Consent.verification.modifierExtension | Consent.verification.modifierExtension | RelatedTo | R4B `Consent.verification.modifierExtension` maps as RelatedTo to R5 `Consent.verification.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Consent.verification.verificationDate | Consent.verification.verificationDate | RelatedTo | R4B `Consent.verification.verificationDate` maps as RelatedTo to R5 `Consent.verification.verificationDate` - verificationDate changed from scalar to array (max cardinality from 1 to *) |
| Consent.verification.verified | Consent.verification.verified | Equivalent | R4B `Consent.verification.verified` maps as Equivalent to R5 `Consent.verification.verified` |
| Consent.verification.verifiedWith | Consent.verification.verifiedWith | Equivalent | R4B `Consent.verification.verifiedWith` maps as Equivalent to R5 `Consent.verification.verifiedWith` |

