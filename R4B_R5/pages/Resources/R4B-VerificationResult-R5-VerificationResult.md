Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | VerificationResult |  | Describes validation requirements, source(s), status and dates for one or more elements. | 50 | 33 |
| Target | VerificationResult |  | Describes validation requirements, source(s), status and dates for one or more elements. | 50 | 33 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 46 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| VerificationResult | VerificationResult | Equivalent | R4B `VerificationResult` maps as Equivalent to R5 `VerificationResult` |
| VerificationResult.attestation | VerificationResult.attestation | Equivalent | R4B `VerificationResult.attestation` maps as Equivalent to R5 `VerificationResult.attestation` |
| VerificationResult.attestation.communicationMethod | VerificationResult.attestation.communicationMethod | Equivalent | R4B `VerificationResult.attestation.communicationMethod` maps as Equivalent to R5 `VerificationResult.attestation.communicationMethod` |
| VerificationResult.attestation.date | VerificationResult.attestation.date | Equivalent | R4B `VerificationResult.attestation.date` maps as Equivalent to R5 `VerificationResult.attestation.date` |
| VerificationResult.attestation.extension | VerificationResult.attestation.extension | RelatedTo | R4B `VerificationResult.attestation.extension` maps as RelatedTo to R5 `VerificationResult.attestation.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| VerificationResult.attestation.id | VerificationResult.attestation.id | Equivalent | R4B `VerificationResult.attestation.id` maps as Equivalent to R5 `VerificationResult.attestation.id` |
| VerificationResult.attestation.modifierExtension | VerificationResult.attestation.modifierExtension | RelatedTo | R4B `VerificationResult.attestation.modifierExtension` maps as RelatedTo to R5 `VerificationResult.attestation.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| VerificationResult.attestation.onBehalfOf | VerificationResult.attestation.onBehalfOf | Equivalent | R4B `VerificationResult.attestation.onBehalfOf` maps as Equivalent to R5 `VerificationResult.attestation.onBehalfOf` |
| VerificationResult.attestation.proxyIdentityCertificate | VerificationResult.attestation.proxyIdentityCertificate | Equivalent | R4B `VerificationResult.attestation.proxyIdentityCertificate` maps as Equivalent to R5 `VerificationResult.attestation.proxyIdentityCertificate` |
| VerificationResult.attestation.proxySignature | VerificationResult.attestation.proxySignature | Equivalent | R4B `VerificationResult.attestation.proxySignature` maps as Equivalent to R5 `VerificationResult.attestation.proxySignature` |
| VerificationResult.attestation.sourceIdentityCertificate | VerificationResult.attestation.sourceIdentityCertificate | Equivalent | R4B `VerificationResult.attestation.sourceIdentityCertificate` maps as Equivalent to R5 `VerificationResult.attestation.sourceIdentityCertificate` |
| VerificationResult.attestation.sourceSignature | VerificationResult.attestation.sourceSignature | Equivalent | R4B `VerificationResult.attestation.sourceSignature` maps as Equivalent to R5 `VerificationResult.attestation.sourceSignature` |
| VerificationResult.attestation.who | VerificationResult.attestation.who | Equivalent | R4B `VerificationResult.attestation.who` maps as Equivalent to R5 `VerificationResult.attestation.who` |
| VerificationResult.contained | VerificationResult.contained | Equivalent | R4B `VerificationResult.contained` maps as Equivalent to R5 `VerificationResult.contained` |
| VerificationResult.extension | VerificationResult.extension | RelatedTo | R4B `VerificationResult.extension` maps as RelatedTo to R5 `VerificationResult.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| VerificationResult.failureAction | VerificationResult.failureAction | Equivalent | R4B `VerificationResult.failureAction` maps as Equivalent to R5 `VerificationResult.failureAction` |
| VerificationResult.frequency | VerificationResult.frequency | Equivalent | R4B `VerificationResult.frequency` maps as Equivalent to R5 `VerificationResult.frequency` |
| VerificationResult.id | VerificationResult.id | Equivalent | R4B `VerificationResult.id` maps as Equivalent to R5 `VerificationResult.id` |
| VerificationResult.implicitRules | VerificationResult.implicitRules | Equivalent | R4B `VerificationResult.implicitRules` maps as Equivalent to R5 `VerificationResult.implicitRules` |
| VerificationResult.language | VerificationResult.language | RelatedTo | R4B `VerificationResult.language` maps as RelatedTo to R5 `VerificationResult.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| VerificationResult.lastPerformed | VerificationResult.lastPerformed | Equivalent | R4B `VerificationResult.lastPerformed` maps as Equivalent to R5 `VerificationResult.lastPerformed` |
| VerificationResult.meta | VerificationResult.meta | Equivalent | R4B `VerificationResult.meta` maps as Equivalent to R5 `VerificationResult.meta` |
| VerificationResult.modifierExtension | VerificationResult.modifierExtension | RelatedTo | R4B `VerificationResult.modifierExtension` maps as RelatedTo to R5 `VerificationResult.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| VerificationResult.need | VerificationResult.need | Equivalent | R4B `VerificationResult.need` maps as Equivalent to R5 `VerificationResult.need` |
| VerificationResult.nextScheduled | VerificationResult.nextScheduled | Equivalent | R4B `VerificationResult.nextScheduled` maps as Equivalent to R5 `VerificationResult.nextScheduled` |
| VerificationResult.primarySource | VerificationResult.primarySource | Equivalent | R4B `VerificationResult.primarySource` maps as Equivalent to R5 `VerificationResult.primarySource` |
| VerificationResult.primarySource.canPushUpdates | VerificationResult.primarySource.canPushUpdates | Equivalent | R4B `VerificationResult.primarySource.canPushUpdates` maps as Equivalent to R5 `VerificationResult.primarySource.canPushUpdates` |
| VerificationResult.primarySource.communicationMethod | VerificationResult.primarySource.communicationMethod | Equivalent | R4B `VerificationResult.primarySource.communicationMethod` maps as Equivalent to R5 `VerificationResult.primarySource.communicationMethod` |
| VerificationResult.primarySource.extension | VerificationResult.primarySource.extension | RelatedTo | R4B `VerificationResult.primarySource.extension` maps as RelatedTo to R5 `VerificationResult.primarySource.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| VerificationResult.primarySource.id | VerificationResult.primarySource.id | Equivalent | R4B `VerificationResult.primarySource.id` maps as Equivalent to R5 `VerificationResult.primarySource.id` |
| VerificationResult.primarySource.modifierExtension | VerificationResult.primarySource.modifierExtension | RelatedTo | R4B `VerificationResult.primarySource.modifierExtension` maps as RelatedTo to R5 `VerificationResult.primarySource.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| VerificationResult.primarySource.pushTypeAvailable | VerificationResult.primarySource.pushTypeAvailable | Equivalent | R4B `VerificationResult.primarySource.pushTypeAvailable` maps as Equivalent to R5 `VerificationResult.primarySource.pushTypeAvailable` |
| VerificationResult.primarySource.type | VerificationResult.primarySource.type | Equivalent | R4B `VerificationResult.primarySource.type` maps as Equivalent to R5 `VerificationResult.primarySource.type` |
| VerificationResult.primarySource.validationDate | VerificationResult.primarySource.validationDate | Equivalent | R4B `VerificationResult.primarySource.validationDate` maps as Equivalent to R5 `VerificationResult.primarySource.validationDate` |
| VerificationResult.primarySource.validationStatus | VerificationResult.primarySource.validationStatus | Equivalent | R4B `VerificationResult.primarySource.validationStatus` maps as Equivalent to R5 `VerificationResult.primarySource.validationStatus` |
| VerificationResult.primarySource.who | VerificationResult.primarySource.who | Equivalent | R4B `VerificationResult.primarySource.who` maps as Equivalent to R5 `VerificationResult.primarySource.who` |
| VerificationResult.status | VerificationResult.status | Equivalent | R4B `VerificationResult.status` maps as Equivalent to R5 `VerificationResult.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/verificationresult-status|4.3.0 and http://hl7.org/fhir/ValueSet/verificationresult-status|5.0.0 (Equivalent) |
| VerificationResult.statusDate | VerificationResult.statusDate | Equivalent | R4B `VerificationResult.statusDate` maps as Equivalent to R5 `VerificationResult.statusDate` |
| VerificationResult.target | VerificationResult.target | Equivalent | R4B `VerificationResult.target` maps as Equivalent to R5 `VerificationResult.target` |
| VerificationResult.targetLocation | VerificationResult.targetLocation | Equivalent | R4B `VerificationResult.targetLocation` maps as Equivalent to R5 `VerificationResult.targetLocation` |
| VerificationResult.text | VerificationResult.text | Equivalent | R4B `VerificationResult.text` maps as Equivalent to R5 `VerificationResult.text` |
| VerificationResult.validationProcess | VerificationResult.validationProcess | Equivalent | R4B `VerificationResult.validationProcess` maps as Equivalent to R5 `VerificationResult.validationProcess` |
| VerificationResult.validationType | VerificationResult.validationType | Equivalent | R4B `VerificationResult.validationType` maps as Equivalent to R5 `VerificationResult.validationType` |
| VerificationResult.validator | VerificationResult.validator | Equivalent | R4B `VerificationResult.validator` maps as Equivalent to R5 `VerificationResult.validator` |
| VerificationResult.validator.attestationSignature | VerificationResult.validator.attestationSignature | Equivalent | R4B `VerificationResult.validator.attestationSignature` maps as Equivalent to R5 `VerificationResult.validator.attestationSignature` |
| VerificationResult.validator.extension | VerificationResult.validator.extension | RelatedTo | R4B `VerificationResult.validator.extension` maps as RelatedTo to R5 `VerificationResult.validator.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| VerificationResult.validator.id | VerificationResult.validator.id | Equivalent | R4B `VerificationResult.validator.id` maps as Equivalent to R5 `VerificationResult.validator.id` |
| VerificationResult.validator.identityCertificate | VerificationResult.validator.identityCertificate | Equivalent | R4B `VerificationResult.validator.identityCertificate` maps as Equivalent to R5 `VerificationResult.validator.identityCertificate` |
| VerificationResult.validator.modifierExtension | VerificationResult.validator.modifierExtension | RelatedTo | R4B `VerificationResult.validator.modifierExtension` maps as RelatedTo to R5 `VerificationResult.validator.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| VerificationResult.validator.organization | VerificationResult.validator.organization | Equivalent | R4B `VerificationResult.validator.organization` maps as Equivalent to R5 `VerificationResult.validator.organization` |

