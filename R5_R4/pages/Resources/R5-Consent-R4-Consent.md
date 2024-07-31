Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Consent |  | A record of a healthcare consumer’s  choices  or choices made on their behalf by a third party, which permits or denies identified recipient(s) or recipient role(s) to perform one or more actions within a given policy context, for specific purposes and periods of time. | 65 | 42 |
| Target | Consent |  | A record of a healthcare consumer’s  choices, which permits or denies identified recipient(s) or recipient role(s) to perform one or more actions within a given policy context, for specific purposes and periods of time. | 57 | 34 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 13 |
Equivalent | 25 |
RelatedTo | 4 |
SourceIsBroaderThanTarget | 20 |
SourceIsNarrowerThanTarget | 3 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Consent | Consent | Equivalent | R5 `Consent` maps as Equivalent to R4 `Consent` |
| Consent.category | Consent.category | RelatedTo | R5 `Consent.category` maps as RelatedTo to R4 `Consent.category` - category made the element mandatory; category increased the minimum cardinality from 0 to 1; category changed the binding strength from Example to Extensible; category has change due to type change: R5 `category` `CodeableConcept` maps as SourceIsBroaderThanTarget for R4 `category` |
| Consent.contained | Consent.contained | Equivalent | R5 `Consent.contained` maps as Equivalent to R4 `Consent.contained` |
| Consent.controller | - | DoesNotExistInTarget | R5 `Consent.controller` does not appear in the target and has no mapping for `Consent`. |
| Consent.date | Consent.dateTime | SourceIsBroaderThanTarget | R5 `Consent.date` maps as SourceIsBroaderThanTarget to R4 `Consent.dateTime` - dateTime has change due to type change: R5 date date has no equivalent or mapped type in R4 dateTime |
| Consent.decision | - | DoesNotExistInTarget | R5 `Consent.decision` does not appear in the target and has no mapping for `Consent`. |
| Consent.extension | Consent.extension | SourceIsBroaderThanTarget | R5 `Consent.extension` maps as SourceIsBroaderThanTarget to R4 `Consent.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Consent.grantee | Consent.performer | SourceIsBroaderThanTarget | R5 `Consent.grantee` maps as SourceIsBroaderThanTarget to R4 `Consent.performer` - performer has change due to type change: R5 `grantee` `Reference` maps as SourceIsBroaderThanTarget for R4 `performer` |
| Consent.grantor | - | DoesNotExistInTarget | R5 `Consent.grantor` does not appear in the target and has no mapping for `Consent`. |
| Consent.id | Consent.id | Equivalent | R5 `Consent.id` maps as Equivalent to R4 `Consent.id` |
| Consent.identifier | Consent.identifier | Equivalent | R5 `Consent.identifier` maps as Equivalent to R4 `Consent.identifier` |
| Consent.implicitRules | Consent.implicitRules | Equivalent | R5 `Consent.implicitRules` maps as Equivalent to R4 `Consent.implicitRules` |
| Consent.language | Consent.language | SourceIsNarrowerThanTarget | R5 `Consent.language` maps as SourceIsNarrowerThanTarget to R4 `Consent.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| Consent.manager | - | DoesNotExistInTarget | R5 `Consent.manager` does not appear in the target and has no mapping for `Consent`. |
| Consent.meta | Consent.meta | Equivalent | R5 `Consent.meta` maps as Equivalent to R4 `Consent.meta` |
| Consent.modifierExtension | Consent.modifierExtension | SourceIsBroaderThanTarget | R5 `Consent.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Consent.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Consent.period | - | DoesNotExistInTarget | R5 `Consent.period` does not appear in the target and has no mapping for `Consent`. |
| Consent.policyBasis | Consent.policy | SourceIsNarrowerThanTarget | R5 `Consent.policyBasis` maps as SourceIsNarrowerThanTarget to R4 `Consent.policy` - policy changed from scalar to array (max cardinality from 1 to *) |
| Consent.policyBasis.extension | - | DoesNotExistInTarget | R5 `Consent.policyBasis.extension` does not appear in the target and has no mapping for `Consent`. |
| Consent.policyBasis.id | - | DoesNotExistInTarget | R5 `Consent.policyBasis.id` does not appear in the target and has no mapping for `Consent`. |
| Consent.policyBasis.modifierExtension | - | DoesNotExistInTarget | R5 `Consent.policyBasis.modifierExtension` does not appear in the target and has no mapping for `Consent`. |
| Consent.policyBasis.reference | - | DoesNotExistInTarget | R5 `Consent.policyBasis.reference` does not appear in the target and has no mapping for `Consent`. |
| Consent.policyBasis.url | Consent.policy.uri | SourceIsBroaderThanTarget | R5 `Consent.policyBasis.url` maps as SourceIsBroaderThanTarget to R4 `Consent.policy.uri` - uri has change due to type change: R5 url url has no equivalent or mapped type in R4 uri |
| Consent.policyText | - | DoesNotExistInTarget | R5 `Consent.policyText` does not appear in the target and has no mapping for `Consent`. |
| Consent.provision | Consent.provision | SourceIsBroaderThanTarget | R5 `Consent.provision` maps as SourceIsBroaderThanTarget to R4 `Consent.provision` - provision changed from array to scalar (max cardinality from * to 1) |
| Consent.provision.action | Consent.provision.action | Equivalent | R5 `Consent.provision.action` maps as Equivalent to R4 `Consent.provision.action` |
| Consent.provision.actor | Consent.provision.actor | Equivalent | R5 `Consent.provision.actor` maps as Equivalent to R4 `Consent.provision.actor` |
| Consent.provision.actor.extension | Consent.provision.actor.extension | SourceIsBroaderThanTarget | R5 `Consent.provision.actor.extension` maps as SourceIsBroaderThanTarget to R4 `Consent.provision.actor.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Consent.provision.actor.id | Consent.provision.actor.id | Equivalent | R5 `Consent.provision.actor.id` maps as Equivalent to R4 `Consent.provision.actor.id` |
| Consent.provision.actor.modifierExtension | Consent.provision.actor.modifierExtension | SourceIsBroaderThanTarget | R5 `Consent.provision.actor.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Consent.provision.actor.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Consent.provision.actor.reference | Consent.provision.actor.reference | RelatedTo | R5 `Consent.provision.actor.reference` maps as RelatedTo to R4 `Consent.provision.actor.reference` - reference made the element mandatory; reference increased the minimum cardinality from 0 to 1 |
| Consent.provision.actor.role | Consent.provision.actor.role | RelatedTo | R5 `Consent.provision.actor.role` maps as RelatedTo to R4 `Consent.provision.actor.role` - role made the element mandatory; role increased the minimum cardinality from 0 to 1 |
| Consent.provision.code | Consent.provision.code | Equivalent | R5 `Consent.provision.code` maps as Equivalent to R4 `Consent.provision.code` |
| Consent.provision.data | Consent.provision.data | Equivalent | R5 `Consent.provision.data` maps as Equivalent to R4 `Consent.provision.data` |
| Consent.provision.data.extension | Consent.provision.data.extension | SourceIsBroaderThanTarget | R5 `Consent.provision.data.extension` maps as SourceIsBroaderThanTarget to R4 `Consent.provision.data.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Consent.provision.data.id | Consent.provision.data.id | Equivalent | R5 `Consent.provision.data.id` maps as Equivalent to R4 `Consent.provision.data.id` |
| Consent.provision.data.meaning | Consent.provision.data.meaning | Equivalent | R5 `Consent.provision.data.meaning` maps as Equivalent to R4 `Consent.provision.data.meaning` - meaning has compatible required binding for code type: http://hl7.org/fhir/ValueSet/consent-data-meaning|5.0.0 and http://hl7.org/fhir/ValueSet/consent-data-meaning|4.0.1 (Equivalent) |
| Consent.provision.data.modifierExtension | Consent.provision.data.modifierExtension | SourceIsBroaderThanTarget | R5 `Consent.provision.data.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Consent.provision.data.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Consent.provision.data.reference | Consent.provision.data.reference | Equivalent | R5 `Consent.provision.data.reference` maps as Equivalent to R4 `Consent.provision.data.reference` |
| Consent.provision.dataPeriod | Consent.provision.dataPeriod | Equivalent | R5 `Consent.provision.dataPeriod` maps as Equivalent to R4 `Consent.provision.dataPeriod` |
| Consent.provision.documentType | Consent.provision.class | SourceIsBroaderThanTarget | R5 `Consent.provision.documentType` maps as SourceIsBroaderThanTarget to R4 `Consent.provision.class` - class changed the binding strength from Preferred to Extensible; class has change due to type change: R5 `documentType` `Coding` maps as SourceIsBroaderThanTarget for R4 `class` |
| Consent.provision.expression | - | DoesNotExistInTarget | R5 `Consent.provision.expression` does not appear in the target and has no mapping for `Consent`. |
| Consent.provision.extension | Consent.provision.extension | SourceIsBroaderThanTarget | R5 `Consent.provision.extension` maps as SourceIsBroaderThanTarget to R4 `Consent.provision.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Consent.provision.id | Consent.provision.id | Equivalent | R5 `Consent.provision.id` maps as Equivalent to R4 `Consent.provision.id` |
| Consent.provision.modifierExtension | Consent.provision.modifierExtension | SourceIsBroaderThanTarget | R5 `Consent.provision.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Consent.provision.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Consent.provision.period | Consent.provision.period | Equivalent | R5 `Consent.provision.period` maps as Equivalent to R4 `Consent.provision.period` |
| Consent.provision.provision | Consent.provision.provision | Equivalent | R5 `Consent.provision.provision` maps as Equivalent to R4 `Consent.provision.provision` |
| Consent.provision.purpose | Consent.provision.purpose | Equivalent | R5 `Consent.provision.purpose` maps as Equivalent to R4 `Consent.provision.purpose` |
| Consent.provision.resourceType | Consent.provision.class | SourceIsNarrowerThanTarget | R5 `Consent.provision.resourceType` is narrower than R4 `Consent.provision.class` and is compatible. `Consent.provision.class` is mapped from `Consent.provision.documentType` and `Consent.provision.resourceType`. |
| Consent.provision.securityLabel | Consent.provision.securityLabel | SourceIsBroaderThanTarget | R5 `Consent.provision.securityLabel` maps as SourceIsBroaderThanTarget to R4 `Consent.provision.securityLabel` - securityLabel changed the binding strength from Example to Extensible; securityLabel has change due to type change: R5 `securityLabel` `Coding` maps as SourceIsBroaderThanTarget for R4 `securityLabel` |
| Consent.regulatoryBasis | Consent.policyRule | SourceIsBroaderThanTarget | R5 `Consent.regulatoryBasis` maps as SourceIsBroaderThanTarget to R4 `Consent.policyRule` - policyRule changed from array to scalar (max cardinality from * to 1); policyRule changed the binding strength from Example to Extensible; policyRule has change due to type change: R5 `regulatoryBasis` `CodeableConcept` maps as SourceIsBroaderThanTarget for R4 `policyRule` |
| Consent.sourceAttachment | Consent.source[x] | RelatedTo | R5 `Consent.sourceAttachment` maps as RelatedTo to R4 `Consent.source[x]` - source[x] changed from array to scalar (max cardinality from * to 1); source[x] has change due to type change: R5 `sourceAttachment` `Attachment` maps as RelatedTo for R4 `source[x]` |
| Consent.sourceReference | Consent.source[x] | SourceIsBroaderThanTarget | R5 `Consent.sourceReference` maps as SourceIsBroaderThanTarget to R4 `Consent.source[x]` - source[x] changed from array to scalar (max cardinality from * to 1) |
| Consent.status | Consent.status | Equivalent | R5 `Consent.status` maps as Equivalent to R4 `Consent.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/consent-state-codes|5.0.0 and http://hl7.org/fhir/ValueSet/consent-state-codes|4.0.1 (Equivalent) |
| Consent.subject | Consent.patient | SourceIsBroaderThanTarget | R5 `Consent.subject` maps as SourceIsBroaderThanTarget to R4 `Consent.patient` - patient has change due to type change: R5 `subject` `Reference` maps as SourceIsBroaderThanTarget for R4 `patient` |
| Consent.text | Consent.text | Equivalent | R5 `Consent.text` maps as Equivalent to R4 `Consent.text` |
| Consent.verification | Consent.verification | Equivalent | R5 `Consent.verification` maps as Equivalent to R4 `Consent.verification` |
| Consent.verification.extension | Consent.verification.extension | SourceIsBroaderThanTarget | R5 `Consent.verification.extension` maps as SourceIsBroaderThanTarget to R4 `Consent.verification.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Consent.verification.id | Consent.verification.id | Equivalent | R5 `Consent.verification.id` maps as Equivalent to R4 `Consent.verification.id` |
| Consent.verification.modifierExtension | Consent.verification.modifierExtension | SourceIsBroaderThanTarget | R5 `Consent.verification.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Consent.verification.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Consent.verification.verificationDate | Consent.verification.verificationDate | SourceIsBroaderThanTarget | R5 `Consent.verification.verificationDate` maps as SourceIsBroaderThanTarget to R4 `Consent.verification.verificationDate` - verificationDate changed from array to scalar (max cardinality from * to 1) |
| Consent.verification.verificationType | - | DoesNotExistInTarget | R5 `Consent.verification.verificationType` does not appear in the target and has no mapping for `Consent`. |
| Consent.verification.verified | Consent.verification.verified | Equivalent | R5 `Consent.verification.verified` maps as Equivalent to R4 `Consent.verification.verified` |
| Consent.verification.verifiedBy | - | DoesNotExistInTarget | R5 `Consent.verification.verifiedBy` does not appear in the target and has no mapping for `Consent`. |
| Consent.verification.verifiedWith | Consent.verification.verifiedWith | Equivalent | R5 `Consent.verification.verifiedWith` maps as Equivalent to R4 `Consent.verification.verifiedWith` |

